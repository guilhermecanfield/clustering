# Medidas de Dissimilaridade
- Identifica a Distância entre as observações.

![alt text](png/image-5.png)
![alt text](png/image-6.png)

**Tabela de exemplo:**

![alt text](png/image-1.png)

**Cálculos:**

``Distância Euclidiana Quadrática e Euclidiana:``

![alt text](png/image.png)

``Distância de Manhattan (City Block):``

![alt text](png/image-2.png)
*``Distância de Chebychev`` é a maior distância entre as distâncias determinadas pelo cálculo de Manhattan (valor grifado em vermelho no exemplo 7,6).*

*``Distância de Camberra:`` o valor desta distância sempre será maior que zero e menor que a quantidade de variáveis do dataset (3 nesse exemplo).*

![alt text](png/image-3.png)

*``Correlação de Pearson`` tem uma particularidade perante as outras, esta medida se trata de uma medida de similaridade, ao contrário das outras*

![alt text](png/image-4.png)

# Métodos de Encadeamento
- É o método de referência para as medidas de distância, que irá nortear a formação dos clusters, ou seja, na prática ele irá determinar a distância entre os clusters.

![alt text](png/image-7.png)
- ``Nearst Neighbor (Single Linkage)`` privilegia menores distâncias, recomendável em casos de observações distintas.
- ``Furthest Neighbor (Complete Linkage)`` privilegia maiores distâncias, recomendável em casos de observações parecidas.
- ``Between Groups (Average Linkage)`` junção de grupos pela distância média entre todos os pares de observações dos grupos em análise.


# Esquemas de Aglomeração
- ``Hierárquico Aglomerativo``: Começa com todas as observações separadas e vai agrupando todas em clusters de acordo com a distância entre elas até que exista somente um cluster (juntando todas em um único cluster).

*Exemplo de como funciona aglomeração com single linkage:*
![alt text](png/image-8.png)

*Exemplo de como funciona aglomeração com complete linkage:*
![alt text](png/image-9.png)

*Exemplo de como funciona aglomeração com o avarage linkage:*
![alt text](png/image-10.png)
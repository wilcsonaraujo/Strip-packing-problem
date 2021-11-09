# Strip-packing-problem

## Problema e Objetivo

A aplicação do GRASP, neste problema, busca a minimização geométrica bidimensional. Dado um conjunto de retângulos alinhados ao eixo e uma faixa de largura limitada e altura infinita, determine um empacotamento livre de sobreposição dos retângulos na faixa, minimizando sua altura

```
Esse algoritmo tem como base o artigo **A priority heuristic for the guillotine rectangular packing problem**
```
Objetivo desse problema a eficiência em encontrar o melhor resultado ideal.
 
## Configuração

O algoritimo está em Python.
Para rodá-lo é necessário a instalação do python na versão mais recente e do pip.

Instalar a biblioteca de gráfico 
~~~ 
matplotlib
~~~ 
utilizando o comando 
~~~
python -m pip install -U matplotlib 
~~~
ou instalar a partir do [Anaconda](https://www.anaconda.com) (Eu prefiro)
~~~
conda install matplotlib
~~~

## Rodando a aplicação

No arquivo exemplo.py é possivel encontrar os valores de entrada dos retangulos, eles estão guardados em um array de nome **boxes** e a largura do espaço a ser destribuidos os retângulos já está predefinida com valor de 30 na varável **width**.

Ao rodar o aplicativo, ele irá gerar no final uma imagem com os retangulos preenchidos e numerados

![Resultado](https://ibb.co/WPYGsWg)


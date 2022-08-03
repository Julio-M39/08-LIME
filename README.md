# 08-LIME
## Interpretação dos resultados de um modelo usando LIME

### Local Surrogate (LIME)

Modelos Local Surrogate são modelos interpretadores que são usados para explicar previsões individuais de modelos de aprendizado de máquina de caixa preta. Explicações agnósticas podem ser encontradas em <a href="https://christophm.github.io/interpretable-ml-book/lime.html#fn50">Local Surrogate (LIME)</a>, nesse artigo os autores propõem uma implementação concreta de modelos Local Surrogate. Já em <a href="https://christophm.github.io/interpretable-ml-book/lime.html">LIME</a> pode se encontrar o passo a passo de como interpretar os resultados de um modelo usando LIME.

Na imagem abaixo podemos observar a imagem original e a classificação realizada por uma rede neural convolucional, os labels verdes e vermelhos são as explicações e interpretações feitas pelo LIME.

<div>
<img src="https://user-images.githubusercontent.com/54995990/182652724-b5773b68-9398-48a6-8e67-9f21c081ea30.png" width="600px" />
</div>

Os resultados obtidos pelo modelo não são os melhores, devido a vários fatores porém é possível notar o comportamento do modelo e suas previsões utilizando o LIME.
 

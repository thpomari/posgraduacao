## Rgressão linear simples

### Definições
Abordagem para modelar o relacionamento entre variáveis independentes explicativas e dependentes numéricas ajustando um modelo linear

Y = b0 + b1 * x

**y** é uma variável dependente.
**b0** é o intercepto em y, o valor do Y quando o x é 0, ou seja, a reta é paralela ao eixo x e seu angulo de inclinação é 0.
**b1** é a inclinação da reta, ou seja, é o valor adicionado a y ao andar um ponto em x.
**x** é a variavel independente.

**Ex:** Em um gráfico onde o eixo X é a experiência em anos e o eixo y é o salário anual, o **y** seria o salário, o **b0** seria o salário quando uma
pessoa tem 0 anos de experiência, o **b1** seria o valor que é adicionado ao salário a cada ano de experiência e o **x** seria a experiência em questão.

![image](https://user-images.githubusercontent.com/22582744/122484294-b1d75000-cfaa-11eb-87b0-84dedea4077e.png)

### Como escolher a melhor Reta?
Dado um conjunto de dados, existem N combinações de retas (valores de b0 e b1) que o modelo pode adotar, porém como é possível saber a reta ideal?
Essa conclusão pode ser feita através do cálculo dos erros das amostras em relação a sua predição. Esse valor pode ser medido através de uma função que busca os
valores para b0 e b1 que minimizam ao máximo a função de custo para o conjunto de treinamento.
![image](https://user-images.githubusercontent.com/22582744/122484395-e5b27580-cfaa-11eb-8d90-e1da5b423dd3.png)

### Função de Custo (ou função de erro):

**Mean Square Error (MSE)** 

![image](https://user-images.githubusercontent.com/22582744/122484445-024ead80-cfab-11eb-9ee4-6eeafacfd6ce.png)

Essa abordagem faz uma somatória da diferença do valor real da amostra de teste com o valor predito pela reta ao quadrado, para depois tirar média. 
Porque elevar ao elevar ao quadrado? Pois isso ajuda a aumentar o peso de erros mais graves na hora de computar a média de todos os erros, dando um maior foco para 
os valores mais distantes da reta

Quando estamos escolhendo os valores de b0 adotando o b1 como 0, ou seja, ajustando a reta partindo do ponto 0 em x, podemos utilizar um gráfico bidmensional para 
visualizar a parábola formada pelos valores descobertos pelo **MSE**. E o ideal é chegar o mais proximo do eixo X.
![image](https://user-images.githubusercontent.com/22582744/122484507-1c888b80-cfab-11eb-8c97-0ecaab899e68.png)


Caso estejamos variando os valores de b0 e b1, teremos um gráfico tri dimensional (parecido com uma rede) e o objetivo é chegar no ponto mínimo do gráfico, em que podemos utilizar
o algoritimo de gradiente descendente. O vetor gradiente é responsável por apontar para a direção de maior crescimento da função, para um dado ponto da função, com uma dada taxa de crescimento.

![image](https://user-images.githubusercontent.com/22582744/122484542-30cc8880-cfab-11eb-9d06-c0780f6fba23.png)


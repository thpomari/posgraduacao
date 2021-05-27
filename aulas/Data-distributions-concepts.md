### Types of Sampling

» **Random sampling** => simplesmente busca N amostras de forma totalmente aleatória, podendo trazer viés para a amostra (sample não respeita a propoção da base de dados)

» **Stratified Sampling** => Divide a base em subgrupos de acordo com determinada característica relevante e ai sim aplica o random sampling nesses subgroups respeitando a proporção da base (scikit-learn usando o train_test_split)

» **Bias** => Viés ou tendência, pode ser um parâmetro subestimado ou superestimado.

» **Selection Bias** => Observações em um estudo que diferem muito da realidade no geral. Ex: escolher um bairro rico de uma cidade para fazer conclusões sobre a população, ignorando todos os outros bairros de menor renda.

» **Self-selection Bias** => Indivíduos não são selecionados randomicamente para fazer a pesquisa, Ex: Pessoas querem responder uma pesquisa por alguma motivação.


### Data Distribution

» **random experiment** => processo que observamos um fenomeno incerto, processo pode ser repetido várias vezes Ex: Jogar uma moeda, rolar um dado.

» **Outcome** => resultado de um random experiment, esse resultado não pode ser afetado pelo resultado anterior 

» **Sample space** => Todas as possibilidade de um experimento randomico 

» **Event** => subconjunto de um espaço amostrar, outcome ou conjunto de outcomes de um experimento.

» **Random Variable** => variaveis cuja o valor depende do outcome de um experimento aleatório, pode ser discreta ou continua. Ex: cara = 0 e coroa = 1, variavel aleatória X pode ser 0 ou 1 pra representar o resultado do lançamento de uma moeda; Resultados de uma partida como numero de gols, carrinhos, escanteios etc

» **Data distribution** => Distribuição de cada observação da base de dados, pode ser uma lista ou uma função que representa todos os valores ou intervalos possíveis do dados. Diz também qual a frequencia dos valores.

» **Probability Distribution** => função matemática que representa a probabilidade de ocorrencia de diferentes resultados para um experimento ex: Jogar uma moeda duas vezes, temos um Sample Space = {HH, HT, TH, TT}, qual a função que expressa o Event = Ter pelo menos 1 H na jogada.

» **Probability Mass Function (PMF)** => é a probabilidade de distribuição de uma variável aleatória discreta. Probabilidade de uma variável X em um ponto especifico x. A soma das probabilidades sempre devem ser 1. A probabilidade de um resultado deve sempre estar entre 0 e 1, e todas as probabilidades são positivas. Baseado em checar um ponto (resultado) e ver sua probabilidade.

» **Probability Density Function (PDF)** =>  a probabilidade de distribuição de uma variável aleatória cointinua. Baseada na área da curva de um intervalo de variáveis. Medida por intervalos.

» **Cumulative Distribution Function (CDF)** => funciona pra discreta e continua, define a probabilidade de uma amostra ser menor ou igual a X. Para valores discretos basta somar as probabilidades de todos os possíveis resultados até o ponto em questão, para valores continuos deve-se media a área da curva do início das possibilidades até o ponto em questão.

» **Expected Value** => Abordagem prática resulta em um distribuição de frequências e um valor médio, em uma abordagem mais teórica resulta em uma distribuição de probabilidades e um valor esperado.


### Distribuição de Probabilidade

» **Bernoulli Distribution** => Distribuição mais simples, apenas 2 outcomes (resultado), uma ensaio (tentativa).

» **Binomial Distribution** => (discreta) frequencia de distribuição de uma quantidade de sucessos (x) em uma quantidade de tentativas com a probabilidade definida de sucesso em cada tentativa EX: obter 2 caras ao jogar 3 moedas. n de mulheres em uma familia.

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

» **Poisson Distribution** => usada pra descrever um numero de ocorrências em um período ou espaço específico. A probabilidade de sucesso é a mesma para todas as partes do intervalo, um sucesso não deve influenciar no outro, a probabilidade de sucesso é a mesma em intervalos com mesmo tamanho, a probabilidade de sucesso em um intervalo se aproxima a zero ao diminuir o intervalo. Ex: Numero de ligações de emergência feitas para um hospital em um dia; Numero de suicídios reportados em determinada cidade; numero de erros de impressão em cada página de um livro.

» **Uniform Distribution** => Discreta ou continua, a probabilidade de um evento é uniformemente distribuída, de modo que todas as chances são iguais. Ex: dado.

» **Normal Distribution** => 


### Estimation

» **Estimativas** => o processo de usar uma amostra para fazer inferências sobre a população é chamada de inferência estatistica. Existem 2 tipos: estimativas pontuais e estimativas intervalar.

» **Estimativa pontual** =>  é uma estimativa de um único valor para um parâmetro populacional, não é possível afirmar qualidade ou precisão. Ex: pegar uma amostra das pessoas de uma determinada cidade e calcular a média de altura delas e dizer baseado nisso que a altura média da cidade é de 1.75m.

» **Estimativa intervalar** => ou intervalo de confiança, passa um certo grau de confiança que o intervalo contém do parametro da população estimado. Ex: dizer que a estimativa média de altura da população de uma cidade tem 95% de chance de estar entre 1.6 e 1.8m.

» **Distribuição Amostral Estatística** => computando uma média, por exemplo, por um número K de vezes para um determinado grupo amostral de N amostras.

» **Teorema do limite central** => quanto maior o número de amostras a média das distribuições amostrais se aproxima de uma distribuição normal, independente de qual era a distribuição da população. A média da distribuição amostral tende a distribuição normal quando o N for >= 30.

» **Intervalo de Confiança** => 

» **Nivel de Significância** => 

» **Resampling** => 

» **Bootstrap** => 

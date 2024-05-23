## Introdução a estatística
Podemos definir estatística como a ciência de usar informação obtida através de coleta, organização e estudo de dados. É um braço da matemática que nos permite tirar insights sobre quaisquer tipos de dados que tivermos a nossa disposição.

> Sem dados, você é só mais uma pessoa com opinião

### Estatísticas dedutiva e indutiva
Estatística dedutiva, também conhecia domo estatística descritiva, tem o objetivo de obter informações e insights sobre o que já foi observado. Por exemplo, quando queremos avaliar o padrão de consumo das pessoas que utilizam um determinado serviço de streaming de vídeo. Podemos analisar a variedade de títulos, a média de tempo assistido e até mesmo informações demográficas.

Estatística indutiva, também conhecida como estatística inferencial, tem o objetivo de obter estimativas para o que não foi observado. Usando o exemplo anterior, poderíamos tentar prever quais conteúdos farão sucesso utilizando os dados de consumo já observados, ou mesmo tentar classificar potenciais pessoas que podem cancelar o serviço a qualquer momento e tentar alguma ação para que permaneçam com suas assinaturas.

Na prática, vamos usar o método estatístico e suas 7 fases para descomplicar a análise de dados.

### Definir o problema
A primeira fase do método estatístico é a definição do problema. É a fase mais importante de qualquer estudo analítico, pois vai direcionar completamente a análise que será feita.

### Planejamento
A segunda fase é o planejamento, onde traçamos um plano para resolver o problema que temos. Aqui, definimos quais dados vamos precisar, de onde vamos extraí-los, quais análises vamos fazer em cima desses dados e por quanto tempo vamos analisá-los.

### Coleta de dados
A terceira fase é a coleta de dados. Aqui, vamos atrás dos dados que definimos que precisamos na fase anterior. Em qual base de dados eles estão, em qual formato, qual acesso precisamos e qual a natureza desses dados. São algumas das perguntas que precisamos responder nessa etapa.

### Validação dos dados
A quarta fase é a da crítica dos dados. É muito importante investigarmos a qualidade dos dados que temos à nossa disposição. Dados ruins levam a interpretações erradas. Também precisamos revisar se o dado está se comportamento de maneira esperada, por exemplo, se temos um dado de tempo gasto em uma página, ele nunca pode ser negativo.

### Apuração dos dados
A quinta fase é da apuração dos dados. Nessa fase, vamos revisar os dados que temos com boa qualidade e começarmos a fazer as análises que já planejamos fazer. Também é nessa fase que olhamos novamente para as perguntas que queremos responder para entendermos se falta algum dado ou alguma informação ou análise para cumprir esse objetivo.

### Apresentação dos dados
A sexta fase é a da apresentação dos dados. Precisamos levar em consideração o público alvo da apresentação. Não sendo um público técnico, vamos dar preferência para gráficos e informações mais mastigadas. Por outro lado, para um público mais técnico, podemos explicar até pontos de como a análise foi feita. Também vale a pena medir a periodicidade de apresentação desses dados. Uma base diária pode pedir um dashboard, enquanto algo mais pontual pode ser resolvido com uma apresentação.

### Análise e interpretação dos dados
A sétima fase, por fim, é a da interpretação dos dados. Nessa fase conectamos o resultado das análises (gráficos, médias, estimativas, etc) com o problema do negócio que queríamos resolver em primeiro lugar. Um número ou um gráfico em por sí só não responde nenhuma pergunta, eles precisam estar ligados a um contexto de negócio.

## Amostragem
Primeiro, precisamos definir os conceitos de população e amostra

### População
É o conjunto de dados que contém todas as observações possíveis. Por exemplo, quando pensamos nas pessoas que trabalham em uma empresa, a população seria todas as pessoas que trabalham nessa empresa, em todos os setores, de todas as filiais. Como considera todas as observações existentes, qualquer análise feita utilizando a população reflete a realidade e não possui qualquer erro intrínseco. Chamamos as medidas que calculamos utilizando a população de parâmetros.

### Amostra
É o subconjunto da população, é a parte do todo que é usada para representar a população. Pegando o exemplo das pessoas de uma empresa, uma amostra poderia ser as pessoas que trabalham no time de marketing, ou as pessoas que trabalham numa cidade específica, ou qualquer subgrupo de pessoas que trabalham na empresa. Como considera apenas uma parte das observações existentes, qualquer análise feita utilizando uma amostra possui uma margem de erro intrínseca. Chamamos as medidas que calculamos utilizando a amostra de estimativa.

Se utilizamos uma amostra que não reflete bem a população, vamos chegar a resultados enviesados que não vão estimar bem a realidade. Por isso, é importante entender e escolher bem a forma como amostramos os dados vindos da população. Temos várias técnicas para amostragem de dados, mas 4 se destacam como as mais úteis.

### Amostragem aleatória simples
Selecionamos de forma aleatória as observações que irão compor a amostra. É a mais popular e utilizada. Por ser aleatório, ela evita qualquer viés de seleção. Além de ser simples de comunicar para pessoas não técnicas.

Como desvantagem, ela pode ter uma execução cara quando queremos amostras de uma população muito grande e xiste um risco de subgrupos populacionais pequenos estarem mal representados na amostra.

### Amostragem sistemática
Selecionamos uma regra de seleção de observações para compor a amostra. Por exemplo, poderíamos dar um número para cada observação da população de origem e, começando pela observação de número 13, somamos 9 e selecionamos a observação, resultando na observação 22, ao adicionar mais 9 selecionamos a observação 31 e assim por diante, até termos uma amostra de tamanho 1000. 

A vantagem é que ela é rápida de ser executada, mas dependendo da regra de seleção escolhida, podemos imputar um viés inesperado na amostra, obtendo um subconjunto de dados não representativos.

### Amostragem aleatória estratificada
Selecionamos subgrupos heterogêneos entre si da população, a quem chamamos de estratos, e fazemos uma amostragem aleatória simples para cada estrato, juntando os resultados para compor a amostra final. Por exemplo, podemos considerar cada departamento de uma empresa como um estrato e selecionar aleatoriamente pessoas de cada departamento para compor a amostra aleatória estratificada.

A vantagem dessa técnica é que todos os estratos estarão representados na amostra, gerando um conjunto de dados que representa bem a população.

A desvantagem é que é necessário escolher bem os estratos (aquilo que agrupa as observações) e é custoso amostrar aleatoriamente cada um dos estratos.

### Amostragem aleatória por conglomerados
Separamos a população em subgrupos homogêneos entre si, a quem chamamos de conglomerados, e escolhemos aleatoriamente um subconjunto de conglomerados que irá compor a amostra. Exemplo, dividir uma vila de casas em conglomerados por rua.

A vantagem é quando a população já está naturalmente dividida, mas a desvantagem é que pode ser um processo custoso e o conglomerado pode não ser homogênio, inputando um víes de seleção na amostra.
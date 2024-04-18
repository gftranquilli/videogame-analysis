
# Projeto Integrado 1

Parabéns! Você concluiu oficialmente a primeira parte do programa na plataforma interativa. Agora é hora de reunir tudo o que você aprendeu até agora em seu primeiro projeto integrado, um estudo de caso analítico da vida real.

Este projeto vai abranger todas as habilidades que você desenvolveu até este momento.

Quando você terminar o projeto, envie seu trabalho para ser avaliado na revisão. Você vai receber feedback dentro de 48 horas. Use o feedback para fazer alterações e, em seguida, envie a nova versão de volta ao revisor do projeto.

Você pode obter mais feedback sobre a nova versão. Isso é completamente normal. Não é incomum passar por vários ciclos de feedback e revisão.

Seu projeto será considerado concluído assim que o revisor do projeto o aprovar.

## Descrição do Projeto

Você trabalha para a loja online Ice, que vende videogames no mundo todo. As avaliações de usuários e especialistas, gêneros, plataformas (por exemplo, Xbox ou PlayStation) e dados históricos sobre vendas de jogos estão disponíveis em fontes abertas. Você precisa identificar padrões que determinam se um jogo tem sucesso ou não. Isso vai permitir que você identifique possíveis sucessos e planeje campanhas publicitárias.

Os dados disponibilizados remontam a 2016. Vamos imaginar que estamos em dezembro de 2016 e você está planejando uma campanha para 2017.

(O importante é ter experiência trabalhando com dados. Realmente não importa se você está prevendo as vendas de 2017 com base nos dados de 2016 ou as vendas de 2027 com base nos dados de 2026.)

O conjunto de dados contém uma coluna de "rating" (classificação) que armazena a classificação ESRB de cada jogo. O Entertainment Software Rating Board avalia o conteúdo de um jogo e atribui uma classificação etária, como Teen (Adolescente) ou Mature (Adulto).

### Instruções para Concluir o Projeto

#### Etapa 1: Abrir e Estudar o Arquivo de Dados

- Caminho do arquivo: `/datasets/games.csv`

#### Etapa 2: Preparar os Dados

- Substituir os nomes das colunas (transformar tudo em minúsculas).
- Converter os dados para os tipos necessários.
- Descrever as colunas onde os tipos de dados foram alterados e por quê.
- Decidir como lidar com valores ausentes.
  - Explicar por que você preencheu os valores ausentes da forma que você fez ou por que você decidiu deixá-los em branco.
  - Dar possíveis razões para a ausência de valores.
  - Prestar atenção à abreviação TBD (a ser determinada) e especificar como pretende lidar com esses casos.
- Calcular o total de vendas (a soma das vendas em todas as regiões) para cada jogo e colocar esses valores em uma coluna separada.

#### Etapa 3: Analisar os Dados

- Ver quantos jogos foram lançados em anos diferentes. Os dados de cada período são significativos?
- Ver como as vendas variaram de plataforma para plataforma. Escolher as plataformas com as maiores vendas totais e construir uma distribuição com base em dados para cada ano. Encontrar as plataformas que costumavam ser populares, mas agora não têm vendas. Quanto tempo leva para as novas plataformas aparecerem e as antigas desaparecerem?
- Determinar para qual período você deve pegar dados. Para fazê-lo, olhar para suas respostas para as perguntas anteriores. Os dados devem permitir construir um modelo para 2017.
- Trabalhar apenas com os dados que você decidiu que são relevantes. Desconsiderar os dados de anos anteriores.
- Identificar as plataformas líderes em vendas e as que estão crescendo ou diminuindo. Selecionar várias plataformas potencialmente lucrativas.
- Construir um diagrama de caixa para as vendas globais de todos os jogos, divididos por plataforma. As diferenças nas vendas são significativas? E quanto às vendas médias em várias plataformas? Descrever suas descobertas.
- Ver como as avaliações de usuários e profissionais afetam as vendas de uma plataforma popular (você escolhe). Construir um gráfico de dispersão e calcular a correlação entre revisões e vendas. Tirar conclusões.
- Comparar as vendas dos mesmos jogos em outras plataformas.
- Observar a distribuição geral de jogos por gênero. O que podemos dizer sobre os gêneros mais lucrativos? Pode-se generalizar sobre gêneros com vendas altas e baixas?

#### Etapa 4: Criar um Perfil de Usuário para Cada Região

- Para cada região (AN, UE, JP), determinar:
  - As cinco plataformas principais. Descrever as variações de suas quotas de mercado de região para região.
  - Os cinco principais gêneros. Explicar a diferença.
  - As classificações do ESRB afetam as vendas em regiões individuais?

#### Etapa 5: Testar as Seguintes Hipóteses

- As classificações médias dos usuários das plataformas Xbox One e PC são as mesmas.
- As classificações médias de usuários para os gêneros Action (ação) e Sports (esportes) são diferentes.
  
  - Definir o valor do limiar alfa.
  - Explicar como você formula as hipóteses alternativas e nulas.
  - Apresentar os critérios utilizados para testar as hipóteses.

#### Etapa 6: Escrever uma Conclusão Geral

- Formato: Complete a tarefa no Jupyter Notebook. Inserir o código nas células code e textos de explicação nas células markdown. Aplicar a formatação e adicionar títulos.

### Descrição de Dados

- **Name:** nome
- **Platform:** plataforma
- **Year_of_Release:** Ano de lançamento
- **Genre:** gênero
- **NA_sales:** vendas norte-americanas em milhões de USD
- **EU_sales:** vendas na Europa em milhões de USD
- **JP_sales:** vendas no Japão em milhões de USD
- **Other_sales:** vendas em outros países em milhões de USD
- **Critic_Score:** Pontuação crítica (máximo de 100)
- **User_Score:** Pontuação do usuário (máximo de 10)
- **Classificação (ESRB):** Classificação ESRB

Os dados de 2016 podem estar incompletos.

### Como o Meu Projeto Será Avaliado?

Leia atentamente esses critérios de avaliação do projeto antes de começar a trabalhar.

- Como você descreve os problemas que identifica nos dados?
- Como você prepara um conjunto de dados para análise?
- Como você constrói gráficos de distribuição e como você os explica?
- Como você calcula o desvio padrão e a variância?
- Você formula hipóteses alternativas e nulas?
- Que métodos você aplica ao testá-los?
- Você explica os resultados dos testes de hipóteses?
- Você segue a estrutura do projeto e mantém seu código limpo e compreensível?
- Quais conclusões você pode tirar?
- Você deixou comentários claros e relevantes a cada etapa?

Tudo o que você precisa para concluir este projeto está nas folhas de conclusões e resumos de capítulos anteriores.

Boa sorte!

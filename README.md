# PI_G36
Projeto Integrador - Grupo 36

Tema do projeto: Análise de Dieta, previsão de peso.  
Analisando os efeitos da dieta, do exercício e do estilo de vida na mudança de peso.

Integrantes do Projeto:  
• Jefferson Rodrigues Feitosa  
• Maicon de Oliveira Pedro  
• Daniela Santana Ferreira Santos  
• Amanda Moreira Braz  
• Gabriel Cruz Souza  
• Bruno do Nascimento Efigenio  
• Francisco Ideam Gonçalves Marinho  

Objetivo:  
O crescente uso da análise de dados na área da saúde tem possibilitado compreender de forma mais precisa como diferentes fatores do estilo de vida influenciam o bem-estar e as mudanças no peso corporal. Nesse contexto, este projeto utiliza um conjunto de dados disponível na plataforma Kaggle composto por informações de 100 participantes, incluindo variáveis demográficas, hábitos alimentares, níveis de atividade física e aspectos relacionados ao estilo de vida.  
Entre os principais atributos analisados estão idade, gênero, peso atual, ingestão calórica diária, distribuição de macronutrientes, qualidade do sono e níveis de estresse. O objetivo desta análise é investigar como essas variáveis se relacionam e de que forma podem influenciar variações no peso ao longo do tempo. A partir da exploração dos dados, queremos identificar padrões e gerar insights que contribuam para uma melhor compreensão dos fatores associados à saúde e ao controle de peso.

Divisão de Tarefas do Grupo:

Para garantir uma melhor organização e andamento do projeto, foi definida uma divisão de tarefas entre os integrantes, considerando as principais etapas necessárias para o desenvolvimento da análise e construção do dashboard.

*Coleta e organização dos dados:

Responsável por realizar o download da base de dados, verificar se os arquivos estão corretos e disponíveis para todos os integrantes. Também deverá organizar os dados em pastas ou ambientes compartilhados, garantindo fácil acesso ao grupo.

*Criação das métricas:

Responsável por desenvolver os cálculos necessários para a análise dos dados, como médias, percentuais, variações e comparações entre grupos. Essa etapa é fundamental para transformar os dados brutos em informações relevantes.

*Elaboração dos gráficos:

Responsável pela construção dos gráficos e visualizações no dashboard, escolhendo os tipos mais adequados para representar cada análise (como gráficos de barras, linhas, pizza ou indicadores). Também deverá organizar o layout visual para facilitar a interpretação.

*Organização da documentação:

Responsável por registrar todas as etapas do projeto, incluindo objetivos, metodologia, análises realizadas e decisões tomadas pelo grupo. Essa documentação será importante tanto para acompanhamento interno quanto para a entrega final do trabalho.

*Organização da apresentação:

Responsável por estruturar a apresentação do projeto, definindo a sequência dos conteúdos, elaborando os slides e preparando a explicação dos resultados obtidos no dashboard.

*Validação e testes:

Responsável por revisar os dados, verificar se as métricas e gráficos estão corretos, testar filtros e interações do dashboard e identificar possíveis erros ou inconsistências antes da entrega final.

Sugestões de Análises para o Desenvolvimento do Projeto:

Com base na base de dados definida pelo grupo, seguem algumas sugestões de análises que podem ser utilizadas na construção do dashboard e na extração de informações relevantes:

1. Variação entre o peso inicial e o peso final.
Realizar a análise da mudança de peso dos indivíduos ao longo do período observado, identificando:

- A quantidade de pessoas que ganharam peso;
- A quantidade de pessoas que perderam peso;
- A quantidade de pessoas que mantiveram o peso.

Além disso, pode-se calcular a média de variação de peso para cada um desses grupos, permitindo uma melhor compreensão do comportamento geral da amostra.

2. Influência da atividade física.
Comparar o peso médio ou a variação média de peso entre indivíduos que praticam atividades físicas e aqueles que não praticam.
Essa análise pode ajudar a identificar o impacto do nível de atividade física na mudança de peso.

3. Influência da alimentação.
Avaliar fatores relacionados aos hábitos alimentares, como:

- Tipo de dieta adotada;
- Frequência alimentar diária;
- Consumo calórico médio.

O objetivo é verificar como esses fatores podem estar associados ao ganho ou perda de peso.

4. Influência da idade.
Realizar a análise da mudança de peso considerando diferentes faixas etárias, possibilitando:

- Comparação entre jovens, adultos e idosos;
- Identificação de padrões de ganho ou perda de peso conforme a idade.

5. Importância do descanso e do sono.
Investigar a relação entre aspectos do estilo de vida e a variação de peso, como:

- Quantidade média de horas de sono;
- Níveis de estresse e ansiedade.

 6. Comparativo de resultados da dieta entre homens e mulheres.
- Variação média de peso entre homens e mulheres;
- Diferença de padrões alimentares;
- Comparação das diferentes necessidades nutricionais.

Essa análise pode contribuir para compreender se fatores relacionados ao descanso e ao bem-estar emocional influenciam no ganho ou perda de peso.

## Processo de limpeza
Os dados forma tratados utilizando Google colab incluindo
-remoção de valores nulos
-exclusão de duplicados
-padronização de colunas

## PROCESSO DE ELABORAÇÃO DOS GRÁFICOS

# Análise Exploratória de Dados — Projeto Integrador Grupo 36

Este projeto apresenta uma análise exploratória detalhada de um conjunto de dados sobre hábitos de saúde e comportamento físico, realizada em **Python** utilizando **Google Colab** e **pandas**.

---

## Objetivo

Explorar o dataset `dataset_tratado.csv` para identificar padrões relacionados a:
- Idade, gênero e composição corporal  
- Taxa metabólica basal (BMR)  
- Consumo e saldo calórico diário  
- Nível de atividade física  
- Qualidade do sono e nível de estresse  
- Mudança de peso ao longo do acompanhamento  

---

## Principais Insights

- Participantes mais pesados apresentam maior **BMR** e **consumo calórico**.  
- A maioria mantém um **saldo calórico neutro**, indicando equilíbrio energético.  
- O grupo **Lightly Active** é o mais frequente, enquanto o **Sedentary** é o menor.  
- A **qualidade do sono** tende a ser moderada, sem extremos predominantes.  
- O **nível de estresse** é majoritariamente intermediário.  
- Há correlação forte entre **peso atual**, **peso final** e **BMR**.

---

## Visualizações

O notebook inclui gráficos para:
- Distribuição de idade, gênero, peso e BMR  
- Saldo calórico diário e mudança de peso  
- Nível de atividade física e estresse  
- Qualidade do sono  
- Correlação entre variáveis numéricas  
- Relação entre calorias consumidas e peso  
- Peso final por nível de atividade física  

---

## Ferramentas Utilizadas

- **Python 3.10+**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Google Colab**

---

## Estrutura do Repositório

PI_G36/

│

├── dataset_tratado.csv          # Dataset tratado e pronto para análise

├── analise_exploratoria.ipynb   # Notebook com toda a análise exploratória

└── README.md                    # Descrição do projeto

---

## Como Executar

Abra o notebook diretamente no Colab:
https://colab.research.google.com/github/amdbraz/PI_G36/blob/main/analise_exploratoria.ipynb

O dataset é carregado automaticamente via GitHub:

import pandas as pd
url = 'https://raw.githubusercontent.com/amdbraz/PI_G36/refs/heads/main/dataset_tratado.csv'
df = pd.read_csv(url)

Execute as células para gerar os gráficos e análises.

---

## Métricas Definidas

Peso inicial, final e variação percentual
BMR individual e saldo calórico médio
Classificação de atividade física
Qualidade média do sono
Correlação entre peso, BMR e calorias


## Etapas do Projeto

Coleta e organização dos dados:
Nesta etapa foi realizada a coleta da base de dados escolhida no Kaggle, reunindo informações relacionadas à saúde, hábitos alimentares, atividades físicas e estilo de vida dos participantes. Após a coleta, os dados foram organizados e estruturados para facilitar as análises posteriores, garantindo maior consistência e qualidade das informações utilizadas no projeto.

Criação das métricas:
Nesta fase foram definidas as principais métricas utilizadas para análise dos dados. Foram criados indicadores que possibilitam entender padrões relacionados à saúde e ao comportamento dos participantes, como média de calorias consumidas, qualidade do sono, níveis de atividade física e variações de peso. Essas métricas servem como base para a interpretação dos resultados obtidos.

Elaboração dos gráficos:
Após a definição das métricas, foram desenvolvidos gráficos e visualizações para facilitar a compreensão dos dados. Os gráficos ajudam a identificar tendências, padrões e possíveis relações entre variáveis, tornando a análise mais intuitiva e objetiva.

Organização da documentação:
Nesta etapa será feita a organização de toda a documentação do projeto, reunindo informações sobre o objetivo da análise, descrição da base de dados, metodologia aplicada, ferramentas utilizadas e resultados obtidos. O intuito é garantir que o projeto fique bem estruturado e fácil de entender para qualquer pessoa que acessar o repositório.

Organização da apresentação:
Aqui será preparada a apresentação final do projeto, resumindo os principais pontos da análise de forma visual e objetiva. Serão destacados os objetivos, metodologia, gráficos gerados, insights encontrados e conclusões obtidas ao longo do desenvolvimento do trabalho.

Validação e testes:
Nesta fase serão realizados testes para verificar se todas as análises, métricas e visualizações estão funcionando corretamente. Também será feita a validação dos dados e dos resultados obtidos, garantindo maior confiabilidade para o projeto e reduzindo possíveis erros ou inconsistências.

Publicação no Streamlit:
Por fim, o projeto será publicado utilizando o Streamlit, permitindo transformar a análise em uma aplicação interativa. Dessa forma, os usuários poderão visualizar os gráficos, explorar os dados e interagir com as informações de maneira prática e dinâmica através de uma interface web.


## Autores
Projeto desenvolvido por Grupo 36 — Projeto Integrador.
Colaboração: Maicon e equipe.

## Licença
Este projeto é de uso acadêmico e educacional.
Distribuição livre mediante citação da fonte.


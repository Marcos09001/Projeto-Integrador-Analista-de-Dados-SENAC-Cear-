# Projeto-Integrador-Analista-de-Dados-SENAC-Ceará

Visão Geral

Este repositório contém o Projeto Integrador de Conclusão do curso de Analista de Dados – SENAC Ceará. O projeto contempla praticamente todas as fases do ciclo de vida da Análise de Dados, desde o entendimento do problema até a geração de insights por meio de visualizações interativas (com exceção da etapa de feedback).
O estudo foi desenvolvido utilizando Python no Google Colab para as etapas de entendimento do problema, coleta, preparação e análise exploratória dos dados, e Power BI para a visualização final e extração de insights.

Autor:
Antonio Marcos Feitosa da Silva

Objetivo do Projeto:

Analisar os fatores que influenciam o desempenho acadêmico dos estudantes, com foco específico em compreender como o nível de escolaridade dos pais (parent_education) impacta o desempenho geral dos alunos, representado pela métrica overall_score.
O projeto busca apoiar decisões educacionais baseadas em dados, contribuindo para ações pedagógicas mais eficazes e equitativas.

Ciclo de Vida da Análise de Dados Aplicado
1. Entendimento do Problema (Ask)

Compreensão do contexto educacional
Definição das perguntas de negócio
Identificação das variáveis relevantes para análise

2. Coleta dos Dados (Collect):

Utilização de um dataset sintético: Student_Performance
Dados demográficos, familiares, hábitos de estudo e desempenho escolar

3. Preparação e Limpeza dos Dados (Prepare):

Verificação e tratamento de valores ausentes
Conversão de tipos de dados

4. Análise Exploratória dos Dados (Analyze):

Estatísticas descritivas
Análise comparativa por escolaridade dos pais
Identificação de padrões e tendências

5. Visualização e Insights (Visualize):

Construção de Dashboard interativo no Power BI
Indicadores de desempenho médio
Gráficos comparativos por nível de escolaridade dos pais
Filtros para cruzamento com outros fatores (tipo de escola, método de estudo, etc.)

Principais Insights:

Existe uma relação positiva entre a escolaridade dos pais e o desempenho acadêmico dos estudantes.
Estudantes cujos pais possuem ensino superior ou pós-graduação apresentam, em média, melhores resultados.
Mesmo ao cruzar com outros fatores, a escolaridade familiar permanece um fator estrutural relevante.
Embora não seja determinante isolado, a escolaridade dos pais influencia significativamente o desempenho escolar.

Tecnologias e Ferramentas Utilizadas:

Python 3
Google Colab
Pandas – Manipulação e análise de dados
NumPy – Operações numéricas
Power BI – Visualização final e geração de insights

Estrutura do Repositório:

├── Projeto_Integrador_AD_Senac.ipynb   # Notebook com ETL e análise exploratória
├── Student_Performance.csv             # Dataset original
├── Student_Performance_Clean.csv       # Dataset tratado
├── Dashboard PI.pbix                   # Dashboard Power BI
├── Roteiro de Apresentação.pdf         # Roteiro utilizado na apresentação
└── README.md                           # Documentação do projeto


Observações:
O dataset utilizado é sintético, com fins educacionais
Este projeto faz parte da formação em Análise de Dados, com foco em boas práticas de ETL, EDA e visualização

Licença:
Projeto de uso educacional e acadêmico. Caso utilize como referência, cite o autor e a finalidade educacional.

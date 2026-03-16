# data_analysis_treinos
Análise exploratória de dados pessoais de treinos de musculação exportados do aplicativo Hevy, utilizando Python e Google Colab.

<h2>📌 Sobre o projeto</h2><br>
Este repositório reúne um notebook de análise exploratória de dados (EDA) construído a partir dos registros pessoais de treinos de musculação exportados pelo app Hevy. O objetivo é transformar dados brutos de séries, repetições e cargas em insights visuais e quantitativos sobre evolução de performance, frequência de treinos e padrões de volume ao longo do tempo.

<h2>📂 Fonte dos dados</h2><br>
Os dados são exportados diretamente pelo aplicativo Hevy no formato .csv. O arquivo contém informações como:
ColunaDescriçãodateData e hora do treinoworkout_nameNome do treino (ex: Push, Pull, Legs)exercise_titleNome do exercícioset_indexNúmero da sérieweight_kgCarga utilizada (kg)repsRepetições realizadasrpePercepção de esforço (quando registrado)notesAnotações livres


<h2>🎯 Objetivos da análise</h2><br>
As principais perguntas que este projeto busca responder:<br><br>

* Qual é a minha frequência semanal de treinos ao longo do tempo?<br>
* Quais exercícios aparecem com mais frequência nos meus treinos?<br>
* Como a carga progressiva evoluiu nos exercícios principais (agachamento, supino, terra, etc.)?<br>
* Quais grupos musculares são mais trabalhados? Existe algum desequilíbrio?<br>
* Qual é o volume médio (séries × repetições × carga) por sessão e por semana?<br>
* Existe algum padrão nos dias da semana em que treino mais ou melhor?<br>
* Como o tempo médio de treino varia ao longo dos meses?<br>


<h2>🛠️ Tecnologias utilizadas</h2><br>

* Python 3.x<br>
* Pandas — limpeza e manipulação dos dados<br>
* Matplotlib / Seaborn — visualizações estáticas<br>
* Plotly — gráficos interativos<br>
* Google Colab — ambiente de execução do notebook<br>


<h2>🚀 Como usar</h2><br>
1. Exporte seus dados do Hevy<br>
No app Hevy: Perfil → Configurações → Exportar dados → salve o arquivo .csv.<br><br>
2. Abra o notebook no Google Colab<br>
Clique no badge abaixo ou faça upload manual do .ipynb:<br>
Show Image<br><br>
3. Faça upload do arquivo CSV<br>
No Colab, utilize o bloco de upload de arquivo indicado no início do notebook e selecione o .csv exportado do Hevy.<br><br>
4. Execute as células<br>
Execute todas as células em ordem (Runtime → Run all) e explore os resultados!<br>

<h2>🗂️ Estrutura do repositório</h2><br>
data_analysis_treinos/<br>
│<br>
├── notebook/<br>
│   └── analise_treinos_hevy.ipynb   # Notebook principal com toda a análise<br>
│<br>
├── README.md                        # Este arquivo<br>
└── requirements.txt                 # Dependências Python (opcional, para uso local)<br>

<h2>📊 Exemplos de visualizações</h2><br>

* Heatmap de frequência de treinos por semana/mês<br>
* Gráfico de linha da evolução de carga por exercício<br>
* Gráfico de barras de volume mensal por grupo muscular<br>
* Distribuição de repetições e cargas por exercício<br>
* Ranking dos exercícios mais realizados<br><br>


 <p align="center">Feito com 💪 e muita análise de dados</p>

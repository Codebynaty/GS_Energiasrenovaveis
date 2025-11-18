# GS_Energiasrenovaveis
🌿 Global Solution – Análise Energética (Opção A)
Ciência da Computação

Este repositório apresenta uma análise completa de consumo energético aplicada ao contexto de ambientes produtivos, com foco em identificar desperdícios, estimar ganhos econômicos e ambientais e propor intervenções sustentáveis com base em dados reais ou simulados.

📌 Objetivo do Projeto
Analisar dados de consumo energético.
Identificar padrões, picos, anomalias e desperdícios.
Propor ações de otimização com impacto econômico e ambiental.
Demonstrar como práticas sustentáveis contribuem para o futuro do trabalho.

📂 Estrutura do Repositório

📁 Global-Solution-Energia/

📄 README.md               # Documentação principal do projeto

📄 Relatorio_Analise_Energetica_OpA.docx  # Relatório completo 

📓 notebooks/
analise_energetica.ipynb  # Código completo da análise
visualizacoes.ipynb       # Gráficos complementares

📁 slides/
apresentacao.pptx         # Slides prontos da Global Solution

📁 resultados/
graficos/                 # PNGs gerados na análise
tabelas/                  # Tabela ficticia que utilizamos

⚙️ Tecnologias Utilizadas

Python 3.10+

Pandas — manipulação e transformação de dados

NumPy — cálculos e operações avançadas

Matplotlib / Plotly — visualizações

Scikit-learn — detecção de anomalias (Isolation Forest)

Jupyter Notebook — documentação e execução do pipeline

📊 Principais Análises Realizadas

- Perfil de carga diária e horária
- Identificação de picos e horários críticos
- Análise por área: Escritório, Sala de Reunião e DataCenter
- Estimativa de desperdícios
- Detecção de anomalias (ML)
- Simulações de economia energética
- Cálculo de impacto ambiental (CO₂)
- Estimativa de economia anual e payback
  
🌱 Principais Resultados

- Consumo total analisado: ~6.729 kWh (90 dias)
- Maior consumidor: DataCenter (carga contínua 24h)
- Pico médio diário: 14h
- +50 anomalias detectadas, apontando uso indevido ou falhas operacionais
- Economia anual estimada com intervenções:
- Redução significativa de kWh
- Economia financeira anual
- Mais de 620 kg de CO₂ evitados por ano
- Intervenções priorizadas:

Retrofit LED
  - Otimização HVAC (DataCenter)
  - Redução de standby
    
📈 Como Executar a Análise

- Clone este repositório: git clone (https://github.com/Codebynaty/GS_Energiasrenovaveis) 
- Entre no diretório: GS_Energiasrenovaveis_analise
- Crie o ambiente virtual (opcional):
  python -m venv venv
  source venv/bin/activate   # Linux/Mac
  venv\Scripts\activate      # Windows
  
- Instale as dependências:
pip install -r requirements.txt

- Execute o notebook:
jupyter notebook notebooks/analise_energetica.ipynb

🧠 Metodologias Aplicadas

🔹 Análises Estatísticas
- Agregações
- Médias móveis
- Correlações
  
🔹 Economia e Sustentabilidade

- Cálculo de economia (kWh + R$)
- Cálculo de emissão evitada (kg CO₂)
- Priorização baseada em payback
  
🖼️ Visualizações Incluídas

- Gráficos de linha e barras (consumo horário e diário)
- Heatmaps por dia/hora
- Gráficos comparativos antes/depois
- Destaques visuais das anomalias
  
📑 Relatório Completo
O documento em (https://fiapcom-my.sharepoint.com/:w:/g/personal/rm568570_fiap_com_br/IQAr508g4ieyT4QW708ZhOCIARzw6P-O7PZhvw86YnoZXqc?e=Eq0nSr) inclui:

- Explicação detalhada de cada etapa
- Resultados completos
- Tabelas e interpretações
- Conclusão e recomendações práticas
- Arquivo: Relatorio_Analise_Energetica_OpA.docx

🎥 Slides da Apresentação

Disponíveis em /slides/apresentacao.pptx, incluindo:

- Introdução
- Metodologia
- Resultados
- Gráficos
- 
Recomendações finais

🤝 Contribuições
Contribuições são bem-vindas! Envie sua issue ou pull request para melhorias e novas análises.

📬 Contato
Caso tenha dúvidas, sugestões ou queira aprimorar o projeto, fique à vontade para abrir uma issue ou entrar em contato.

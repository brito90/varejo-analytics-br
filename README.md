# varejo-analytics-br
📊 Varejo Analytics AI: Simulação de Cenários e Inteligência de Dados
🎯 Visão Geral do Projeto
Este repositório contém uma solução completa de Análise de Dados Preditiva e Descritiva focada no setor de varejo. Diferente de análises estáticas, este projeto implementa um motor de geração de dados sintéticos que replica comportamentos reais de mercado, permitindo a simulação de cenários complexos sem depender de dados sensíveis ou restritos.

O objetivo é demonstrar a capacidade de transformar dados brutos em insights acionáveis para tomada de decisão estratégica, utilizando Python como linguagem central e bibliotecas de alto desempenho para processamento e visualização.

🏗️ Arquitetura da Solução
O pipeline de dados foi estruturado em três camadas distintas para garantir escalabilidade e clareza lógica:

1. Camada de Ingestão e Geração (Data Fabric)
Motor Sintético: Algoritmo personalizado que gera 10.000+ transações simulando variáveis reais: sazonalidade regional, mix de produtos, métodos de pagamento e comportamento do consumidor.
Injeção de Ruído Controlado: Implementação de variações aleatórias para simular imprevistos do mercado (quebra de estoque, picos de demanda não planejados), testando a robustez da análise.
Estruturação de Dados: Criação de DataFrames tipados e otimizados utilizando Pandas, garantindo eficiência de memória mesmo em grandes volumes.
2. Camada de Processamento e Lógica de Negócios
Limpeza Automatizada: Rotinas de ETL (Extract, Transform, Load) para tratamento de nulls, padronização de datas e categorização de regiões.
Cálculo de KPIs: Implementação de métricas críticas de varejo:
Ticket Médio por Região e Categoria.
Taxa de Conversão por Método de Pagamento.
Crescimento MoM (Month-over-Month) e YoY (Year-over-Year).
Detecção de Padrões: Identificação automática de correlações entre sazonalidade (ex: Páscoa, Black Friday) e volume de vendas.
3. Camada de Visualização e Storytelling
Dashboards Interativos: Utilização da biblioteca Plotly para criar gráficos dinâmicos que permitem drill-down (exploração detalhada) dos dados diretamente no navegador.
Foco em UX de Dados: Design limpo e informativo, priorizando a legibilidade das tendências sobre a estética decorativa.
Exportabilidade: Estrutura pronta para conversão em relatórios PDF ou嵌入 em aplicações web via Streamlit/Dash.
🚀 Principais Insights Gerados
A execução deste projeto revela padrões críticos para o negócio:

Sazonalidade Regionalizada: Confirmação de que campanhas nacionais têm impactos desproporcionais dependendo da região (ex: Norte tem pico no Q1, Sudeste no Q4).

Migração de Pagamento: Tendência clara de substituição de dinheiro por Pix em transações de baixo valor, afetando a gestão de fluxo de caixa.

Elasticidade de Categoria: Produtos de "Saúde e Bem-estar" mostram menor sensibilidade a crises econômicas comparados a "Eletrônicos".

🛠️ Stack Tecnológico
Linguagem: Python 3.10+
Manipulação de Dados: Pandas, NumPy
Visualização: Plotly Express, Matplotlib
Ambiente de Execução: Google Colab (GPU/TPU ready)
Controle de Versão: Git & GitHub

🏃 Como Executar
Não é necessária instalação local. O projeto foi desenhado para rodar nativamente na nuvem:

Clique no botão "Open in Colab" (se disponível) ou baixe o arquivo .ipynb.

Acesse Google Colab.

Faça o upload do notebook.

Execute a célula única (Run All). O script gerará os dados, processará as informações e renderizará os gráficos interativos em menos de 30 segundos.

👤 Sobre o Autor
Kauan Santiago Desenvolvedor Full-Stack | Especialista em IA e Otimização de Sistemas Focado em transformar dados brutos em vantagem competitiva através de arquitetura de software limpa e análise preditiva.

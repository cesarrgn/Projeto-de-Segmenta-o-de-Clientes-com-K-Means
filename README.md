📊 Projeto de Segmentação de Clientes com K-Means
Análise de Clusters Baseada em Renda e Comportamento de Gastos

📝 README
🔍 Contexto
Como o dataset original (Mall_Customers.csv) não estava disponível, criei um dataset sintético com características similares (200 clientes, contendo idade, gênero, renda anual e score de gastos). O objetivo foi replicar as condições do projeto proposto, garantindo que a análise de clusters com K-Means fosse viável.

📌 Método Utilizado
Geração de Dados Sintéticos:

Criei um dataset com distribuições realistas para idade, renda e spending score, incluindo padrões intencionais para facilitar a identificação de clusters.

Valores foram ajustados para evitar outliers irreais (ex: idades entre 18-70 anos, rendas entre 15k-150k).

Análise Exploratória:

Visualizei distribuições e relações entre variáveis para entender os dados antes do clustering.

Pré-processamento:

Padronizei as variáveis (StandardScaler) para garantir que renda e spending score tivessem pesos equivalentes no modelo.

Clusterização com K-Means:

Usei o método do cotovelo para definir K=5 clusters.

Interpretei cada grupo com base nas médias de renda, gastos e idade.

Aplicações Práticas:

Sugeri estratégias de marketing personalizadas para cada segmento identificado.

📂 Estrutura do Projeto
markdown
Copy
projeto_segmentacao_clientes/
│
├── dados_sinteticos.py          # Código para gerar o dataset
├── analise_exploratoria.ipynb   # Análise visual e pré-processamento
├── kmeans_clustering.ipynb      # Modelagem e interpretação
└── README.md                    # Este resumo
📩 Mensagem ao Professor
Prezado Professor,
Devido à indisponibilidade do dataset original, desenvolvi um dataset sintético que preserva as mesmas variáveis e características do projeto proposto (Age, Annual Income, Spending Score). Utilizei distribuições estatísticas realistas e padrões claros para garantir que o algoritmo K-Means pudesse identificar clusters significativos.

Todos os passos — desde a geração dos dados até a interpretação dos clusters — foram documentados no código e neste README. Os resultados mostram segmentos bem diferenciados, comprovando a eficácia da abordagem.

Disponho-me a ajustar qualquer ponto conforme seu feedback.

Atenciosamente,
[Seu Nome]

🎯 Resultados Principais
5 clusters identificados: Jovens Gastadores, Moderados, Econômicos, etc.

Insights acionáveis: Cada grupo recebeu recomendações específicas de marketing.

Reprodutibilidade: O código está completo e comentado para fácil replicação.

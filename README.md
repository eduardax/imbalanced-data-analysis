📊 Imbalanced Data Analysis
Este repositório contém um notebook extraído de um projeto maior desenvolvido como parte do Trabalho de Conclusão de Curso (TCC), com foco na análise e tratamento de dados desbalanceados em problemas de classificação.

O notebook concentra-se na aplicação de técnicas de oversampling com a biblioteca imbalanced-learn, análise exploratória com pandas-profiling e visualização de dados com matplotlib e seaborn.

🧠 Objetivo
Investigar e aplicar abordagens para lidar com o desbalanceamento de classes em datasets de classificação, explorando o impacto dessas técnicas no desempenho de modelos de aprendizado de máquina supervisionado.

🧰 Ferramentas e Bibliotecas
Python: linguagem principal

Pandas, NumPy: manipulação e análise de dados

Imbalanced-learn: técnicas de oversampling (SMOTE, ADASYN, etc.)

Scikit-learn: modelagem, avaliação e pipelines

Matplotlib, Seaborn: visualização de dados

Pandas Profiling: análise exploratória automática

Torch: usado para compatibilidade com etapas posteriores do projeto original (não é utilizado diretamente neste notebook)

📂 Estrutura
imbalanced_data_notebook.ipynb: notebook com código comentado e estruturado, demonstrando a preparação, balanceamento e avaliação de modelos.

⚠️ Observações
Este notebook representa um recorte do projeto completo de TCC, com foco específico no tratamento de dados desbalanceados.

As saídas foram removidas do notebook para facilitar a visualização e versionamento no GitHub.

O conteúdo pode ser expandido ou adaptado para outros conjuntos de dados com problemas semelhantes.

📌 Requisitos
Instale as dependências necessárias com:

bash
Copiar
Editar
pip install pandas-profiling imbalanced-learn tqdm seaborn matplotlib scikit-learn
📈 Resultados Esperados
Após aplicar as técnicas de oversampling, o notebook permite visualizar a melhora na distribuição das classes e avaliar o desempenho dos modelos com métricas como acurácia, matriz de confusão e relatório de classificação.

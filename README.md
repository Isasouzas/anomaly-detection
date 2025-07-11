## Detecção de Anomalias em Vibrações de Máquinas Industriais

Este projeto tem como objetivo desenvolver um sistema inteligente para **detecção automática de anomalias** em máquinas industriais com base em leituras de vibração. Utilizando dados reais extraídos de sensores, foram aplicadas técnicas de **aprendizado de máquina não supervisionado** para identificar padrões fora do esperado que podem indicar falhas mecânicas ou necessidade de manutenção.

### Objetivos do Projeto

- Coletar e tratar arquivos JSON com informações de vibração (FFT e RMS).
- Testar diferentes algoritmos de **detecção de anomalias**.
-  Avaliar o desempenho dos modelos com base em **Anomaly Scores** e visualizações.

### Tecnologias Utilizadas

- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **Modelos de Machine Learning**:
  - Isolation Forest
  - One-Class SVM
  - Local Outlier Factor (LOF)
  
- **Ambiente**: Google Colab + Google Drive

### Contexto do Problema

A vibração é uma das variáveis mais sensíveis para identificar o estado de funcionamento de máquinas industriais. Mudanças nos padrões de frequência podem indicar falhas como:

- Desbalanceamento de peças rotativas
- Desgaste de rolamentos
- Desalinhamentos e folgas

Neste cenário, um modelo de detecção de anomalias permite:

-  Sinalizar variações críticas de forma automática
- Auxiliar equipes de manutenção com alertas baseados em dados
- Reduzir o risco de falhas inesperadas

### Premissas

- Os dados representam **leituras simuladas**, processadas a partir de arquivos `.json`.
- O treinamento foi feito com dados considerados "normais", sem rótulos supervisionados.
- A validação foi realizada com leituras artificialmente modificadas e reais com comportamento atípico.
- Os resultados dependem do contexto operacional e podem exigir calibração periódica.


### Exemplos de Visualizações

- Comparação entre curva média de leituras normais e uma leitura anômala
- Destaque nos picos de frequência mais relevantes
- Score de anomalia atribuído a cada leitura analisada

### Próximos Passos

- Implementação de uma API com **FastAPI** ou interface com **Streamlit** para inferência em tempo real
- Adoção de métodos de validação com especialistas da área técnica
- Criação de pipeline automático para ingestão e classificação de novos dados

---

>  **Nota**: Por motivos de confidencialidade, os dados utilizados neste projeto não são públicos.


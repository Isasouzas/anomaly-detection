## 🔍🚨 Detecção de Anomalias em Dados Industriais

Este projeto tem como objetivo desenvolver um sistema para detecção automática de anomalias em dados industriais simulados, utilizando técnicas de aprendizado de máquina não supervisionado. Os dados utilizados são sintéticos, gerados artificialmente para representar medições de sensores em ambientes industriais.

Foram aplicados modelos estatísticos e de machine learning para identificar padrões fora do comportamento esperado, que podem indicar falhas, desvios operacionais ou eventos fora do padrão.

### Objetivos do Projeto

- Coletar e tratar arquivos JSON contendo leituras simuladas de sensores.
- Testar diferentes algoritmos de detecção de anomalias.
- Avaliar o desempenho dos modelos com base em scores de anomalia e visualizações.
- Gerar gráficos que ajudem na interpretação e validação dos resultados.

### Tecnologias Utilizadas

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Modelos de Machine Learning:
  - Isolation Forest
  - One-Class SVM
- Ambiente: Google Colab com dados armazenados no Google Drive

### Contexto do Problema

A análise de sinais e medições industriais é uma estratégia fundamental para identificar falhas precoces e evitar paradas inesperadas. Mudanças sutis em dados operacionais podem representar:

- Desbalanceamento em componentes rotativos
- Desgaste mecânico
- Desvios de processo ou condições fora do padrão

A utilização de modelos não supervisionados permite classificar automaticamente leituras como normais ou anômalas, mesmo sem rótulos definidos previamente.

### Premissas

- Os dados utilizados são completamente simulados e não representam nenhum sistema real ou corporativo.
- O modelo foi treinado com dados considerados normais, e testado com variações geradas artificialmente.
- Os resultados são baseados em comportamento estatístico e podem variar conforme o contexto de aplicação.
- Este projeto tem fins exclusivamente educacionais e demonstrativos.

### Exemplos de Visualizações

- Comparação entre curvas médias de leituras normais e leituras anômalas simuladas
- Destaque de pontos com variações abruptas
- Score de anomalia atribuído a cada leitura

### Próximos Passos

- Implementar uma interface com Streamlit ou uma API com FastAPI para testes em tempo real
- Criar um pipeline automático para leitura, análise e classificação de novos dados simulados
- Explorar modelos baseados em séries temporais e autoencoders para ambientes com comportamento sequencial

---

**Aviso**: Todos os dados utilizados neste repositório são sintéticos e foram gerados para fins de demonstração. Nenhuma informação sensível, real ou empresarial foi utilizada.

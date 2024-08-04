### Projeto: PySpark-ML-Classification

Este projeto utiliza PySpark para trabalhar com modelos de classificação, visando prever o cancelamento de contratos a partir de um conjunto de dados em formato CSV. O processo consiste nas seguintes etapas:

1. **Método Dummy**: Aplicação do método dummy para variáveis categóricas.
2. **Vetorização dos Dados**: Transformação dos dados em vetores para serem utilizados nos modelos de classificação.
3. **Modelos de Classificação**:
   - Regressão Logística
   - Árvore de Decisão
   - Random Forest
4. **Avaliação de Métricas**: Avaliação dos modelos utilizando métricas como acurácia, precisão, recall e F1.
5. **Validação Cruzada**: Aplicação de cross-validation para otimizar os modelos.
6. **Comparação de Modelos**: Comparação dos resultados para determinar o melhor modelo.
7. **Previsão de Cancelamento**: Criação de um DataFrame com características do cliente usando PySpark e classificação se o cliente cancelará ou não o contrato.

O objetivo final é identificar o modelo de classificação mais preciso para prever quais clientes cancelarão o contrato com a empresa.

**Lembrete**: O conjunto de dados se chama `dados_clientes.csv` e está localizado na pasta `data`. É necessário atualizar o caminho de leitura do arquivo no código para garantir que o arquivo seja lido corretamente.

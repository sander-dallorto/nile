# Análise de Fluxo do Rio Nilo

Este projeto analisa o fluxo de água do Rio Nilo utilizando o dataset histórico de 1871 a 1970, disponível na biblioteca **statsmodels**. O objetivo principal é estudar os impactos da construção da represa de Assuã (construída em 1898) no fluxo do rio, dividindo os dados em dois períodos: antes e depois da construção da represa. 

## Objetivos

- **Analisar a série temporal** do fluxo do Rio Nilo para entender os padrões de comportamento do rio ao longo do tempo.
- **Comparar os períodos** antes e depois da construção da represa de Assuã para detectar possíveis mudanças no volume de água.
- **Aplicar testes estatísticos** como o **Teste de Wilcoxon** para verificar se as diferenças entre os dois períodos são estatisticamente significativas.
- **Construir modelos de séries temporais** ARIMA para prever os fluxos futuros com base nos dados históricos.

## Abordagem

1. **Pré-processamento dos Dados:**
   - Importação e limpeza dos dados de fluxo do Rio Nilo.
   - Divisão do dataset em dois períodos: antes e depois da construção da represa de Assuã (1898).

2. **Análise Exploratória:**
   - Visualização do fluxo anual do Rio Nilo ao longo do tempo.
   - Identificação de padrões sazonais e comparações antes e depois da represa.

3. **Testes Estatísticos:**
   - Aplicação do **Teste de Wilcoxon** para avaliar se há diferenças significativas no fluxo do rio nos dois períodos.

4. **Modelagem de Séries Temporais:**
   - Aplicação de **ARIMA** para modelar o fluxo do rio e realizar previsões futuras.

5. **Visualização das Previsões:**
   - Gráficos de séries temporais, mostrando tanto os dados históricos quanto as previsões geradas pelos modelos.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **pandas**: Para manipulação e análise de dados.
- **statsmodels**: Para análise de séries temporais (incluindo ARIMA e Holt-Winters).
- **matplotlib**: Para criação de gráficos.
- **scipy**: Para testes estatísticos, como o Teste de Wilcoxon.

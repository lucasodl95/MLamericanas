
# Previsão de Preços de Ações com LSTM

Este projeto consiste em uma aplicação de Redes Neurais Recorrentes (RNNs) do tipo Long Short-Term Memory (LSTM) para prever os preços de ações da Americanas. O objetivo é utilizar dados históricos de preços de ações para treinar um modelo de previsão capaz de fazer previsões futuras. (Será que não era possível prever o crash?)

## Pré-requisitos

Antes de executar este projeto, certifique-se de ter instalado as seguintes bibliotecas Python:

*numpy*

*matplotlib*

*pandas*

*keras*

*scikit-learn*

Você pode instalar essas bibliotecas via pip. Por exemplo:

```bash
pip install numpy matplotlib pandas keras scikit-learn
```

## Conjunto de Dados

O conjunto de dados usado neste projeto consiste em dados históricos de preços de ações da empresa AMER3. O conjunto de dados de treinamento e teste deve ser fornecido em formato CSV com pelo menos uma coluna contendo os preços de abertura das ações. E está disponível o link para download no código.

## Resultados

Os resultados da previsão dos preços de ações são apresentados em um gráfico, onde é possível comparar os preços reais e os preços previstos pelo modelo LSTM, onde podemos observar que talvez(?) já sabiam dessa tendência de desvalorização das ações.

## Contribuição

Contribuições são bem-vindas! Se você encontrar algum problema, bug ou tiver sugestões de melhorias, por favor, abra uma issue neste repositório.

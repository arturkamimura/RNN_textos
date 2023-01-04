# Descrição deste projeto
O projeto consiste em um gerador de texto utilizando uma rede neural recorrente (RNN) treinada com o framework Tensorflow 2.0. O dataset utilizado é um texto em francês, que é pré-processado para remover caracteres indesejados e criar o vocabulário utilizado pelo modelo. O modelo é treinado para prever a próxima letra de uma sequência de entrada, e pode ser utilizado para gerar novas sequências de texto. As sequências de entrada e saída são geradas em batches para treinar o modelo de maneira mais eficiente. Além disso, um método é fornecido para gerar batches de maneira sequencial, de modo a preservar a ordem das sequências no texto original.

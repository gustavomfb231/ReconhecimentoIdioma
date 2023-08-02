Explorando a biblioteca do nltk para reconhecimento de idiomas, sendo aplicado à priori uma limpeza dos dados, de maneira a reduzir a presença
de pontuações e tags html, e em seguinte padronizando a estrutura dos textos, e por fim criando, treinando e validando o modelo por meio da 
medidade de perplexidade. Foi constatado a necessidade de utilizar um modelo de Laplace para uma medição correta dos valores de teste, uma vez
que no MLE a probabilidade dada a uma palavra que não está no treino é de 0, o que leva a perplexidade a infinito impossibilitando uma boa 
performance do modelo. 

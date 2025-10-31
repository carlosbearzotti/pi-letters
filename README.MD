# Melhor Modelo – Comparação

Após avaliar os modelos usando cross-validation (3 folds) sobre o dataset de vogais manuscritas para detectar a letra “i”, os resultados foram:

Primeira avaliação
Modelo  Acurácia    Precision   Recall	F1	    Observações
KNN	    0.9874	    0.9467	    0.9930	0.9693	Mais rápido, melhor F1, ideal para uso prático
MLP	    0.9788	    0.9673	    0.9255	0.9459	Boa precisão, mas treino mais lento
SVM	    0.9705	    0.9220	    0.9315	0.9267	demora (25+ minutos), e menor Score

Segunda avaliação
Modelo  Acurácia    Precision   Recall	F1	    Observações
KNN    0.9696   0.894557  0.961500  0.926787    Mais rápido, melhor F1, ideal para uso prático pelo menor tempo de treino
MLP    0.9538   0.890172  0.878474  0.883484    Boa precisão, treino semelhante em tempo porém menor F1
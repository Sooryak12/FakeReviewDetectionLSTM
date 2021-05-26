# FakeReviewDetection
 Final File :**FinalModel_svm** |
Testing Accuracy :**80.69%**    |
 Final Model : **svmmodelup.sav**

## Trained Models with their Accuracies
1. Initial Model with No Embeddings [Train: 84% and Test: 59%.]
2. Model With No Pretrained Embeddings.
3. GloveWithLSTM
4. Glove Model [25 epochs]
5. BERTModels
6. SVMmodelp
7. FinalModel_SVM


## Insights

I am delighted to share my first project on Amazon fake review detection. I have used an SVM model with inputs as the review text and verified purchase column and have achieved a Testing Accuracy of 81%. This was my first hands-on project where I learned a lot. I was amused by the amount of knowledge I could gain in a limited amount of time by doing projects.

I had used all kinds of NN's starting from RNNs to State of the art Bert Model. I came across a lot of interesting articles and amazing videos on NLP. After working on a variety of models  I came to the conclusion that almost all of the NN models overfitted(80-90% accuracy) and could give only 60-65% testing accuracy with only the review text. 

The Models couldn't predict properly with only the review text[I think this is due to there is no proper difference between a real and fake review in their text] of my dataset. When I gave additional input of whether the product is verified or not my Testing Accuracy jumped to 80%.

I was actually amused by the jump in testing accuracy with just adding 1 column to the already present 5000 dimensions of TFIDF Vectorized Words. Useful data can help the model to improve remarkably. Proper Data Analysis can significantly help in creating a good model.

Andrew Ng's Method of  Idea->Code->Experiment->Repeat has helped me a lot in experimenting with a variety of ideas.
I would highly recommend Data Science Enthusiasts to see Jay Alammers's Blog(link: https://jalammar.github.io/). He visualizes the concepts and it is so easy to understand with the help of his articles.





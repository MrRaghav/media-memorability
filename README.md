This project is an attempt towards *Media Memorability* section of **mediaeval2019** in which we predict the memorability of a video to the viewers.  
Link (2019) : http://www.multimediaeval.org/mediaeval2019/memorability/

Since last decade, MediaEval offers yearly challenges in the forms of shared tasks.

Website (2010-2019) : http://www.multimediaeval.org/  
Website (2020-) : https://multimediaeval.github.io/


Video memorability has various applications. In this project, features extracted by a different team have been utlized to predict the short- and long-term memorability of the videos.  

Features used:  
--------------  
HMP  
C3D  
C3D with HMP  
captions using count vectorizer  
captions using tf-idf  
captions with HMP  
captions with C3D  

Regression techniques used:  
---------------------------  
Linear Regression  
KNN  
Decision tree  
Random forest  
VotingRegressor  
AdaBoostRegressor  
GradientBoostingRegressor  
Neural Network  

After analyzing the **spearman's score** for all of them, the best regressor was used for the test set.
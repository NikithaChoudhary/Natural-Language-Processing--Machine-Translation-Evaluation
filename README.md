# Natural-Language-Processing--Machine-Translation-Evaluation
Built a program to enhance METEOR evaluation. The default accuracy was 0.483.  
For better evaluation accuracies created feature vectors out of extended METEOR values on n-grams and fits the feature set using SVM model.



1. Run the command, 
python evaluate > eval.out

It runs the algorithm and predicts labels to eval.out

2. Now the accuracy on the first half od the dataset is performed by the below command. 
python compare-with-human-evaluation  < eval.out

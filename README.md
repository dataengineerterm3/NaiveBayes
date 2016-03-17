# NaiveBayes
Implementation of text classification by Naive Bayes

compile methods: 

mvn clean

mvn package

mvn exec:java -Dexec.mainClass="Source.NBMain" -Dexec.args="input/cv_pos_750.txt input/cv_neg_750.txt input/cv_pos_250.txt input/cv_neg_250.txt output1 output2"

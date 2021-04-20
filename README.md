## Irony Detection in English Tweets 
This experiment is to design a binary detect ironic tweets on Twitter. 

The data is provided by SemEval-2018 Task 3: Irony Detection in English Tweets (https://www.aclweb.org/anthology/S18-1005/)  see https://github.com/Cyvhee/SemEval2018-Task3/tree/master/datasets. The training and test sets are train/SemEval2018-T3-train-taskA_emoji.txt and goldtest_TaskA/SemEval2018-T3_gold_test_taskA_emoji.txt, respectively.

### Methods
I have used three methods to explore this task. Due to my PC capcility, I did not carefully tune the hyperparamters and the performance may not be best.

The first method is text-CNN, referred to the paper "Convolutional neural networks for sentence classification". 

The second method is attention models, referred to the paper "Hierarchical attention networks for document classification"

The third second is the well-known Bert model, referred to the link "https://www.tensorflow.org/tutorials/text/classify_text_with_bert."




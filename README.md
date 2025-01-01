# CNN for classifying street house numbers from images, reaching 97% accuracy


## confusion matrix:
![confusion_matrix](https://github.com/user-attachments/assets/6aecfa33-092d-4051-b947-b8473c2624de)


Loss and Accuracy Graphs:
![loss_accuracy_graph](https://github.com/user-attachments/assets/f2997ac3-4f72-4efa-86f7-ddcc0f5e82b3)

Epoch [1/20], Loss: 1.9247, Accuracy: 30.88%
Epoch [2/20], Loss: 1.0838, Accuracy: 63.89%
Epoch [3/20], Loss: 0.8004, Accuracy: 74.47%
Epoch [4/20], Loss: 0.6701, Accuracy: 78.96%
Epoch [5/20], Loss: 0.5710, Accuracy: 82.48%
Epoch [6/20], Loss: 0.4947, Accuracy: 84.78%
Epoch [7/20], Loss: 0.4296, Accuracy: 87.06%
Epoch [8/20], Loss: 0.3784, Accuracy: 88.63%
Epoch [9/20], Loss: 0.3320, Accuracy: 89.97%
Epoch [10/20], Loss: 0.2942, Accuracy: 91.04%
Epoch [11/20], Loss: 0.2595, Accuracy: 92.27%
Epoch [12/20], Loss: 0.2302, Accuracy: 93.11%
Epoch [13/20], Loss: 0.2050, Accuracy: 93.90%
Epoch [14/20], Loss: 0.1781, Accuracy: 94.60%
Epoch [15/20], Loss: 0.1615, Accuracy: 95.05%
Epoch [16/20], Loss: 0.1438, Accuracy: 95.63%
Epoch [17/20], Loss: 0.1274, Accuracy: 96.14%
Epoch [18/20], Loss: 0.1188, Accuracy: 96.36%
Epoch [19/20], Loss: 0.1066, Accuracy: 96.71%
Epoch [20/20], Loss: 0.1007, Accuracy: 96.89%

RESULTS:
Test Loss: 0.0687
Test Accuracy: 97.78%

Classification Report:
              precision    recall  f1-score   support

           0       0.98      0.99      0.98      4948
           1       0.98      0.99      0.98     13861
           2       0.99      0.98      0.99     10585
           3       0.95      0.98      0.97      8497
           4       0.99      0.98      0.99      7458
           5       0.99      0.94      0.96      6882
           6       0.99      0.97      0.98      5727
           7       0.97      0.99      0.98      5595
           8       0.97      0.96      0.97      5045
           9       0.98      0.98      0.98      4659
    accuracy                           0.98     73257
   macro avg       0.98      0.98      0.98     73257
weighted avg       0.98      0.98      0.98     73257

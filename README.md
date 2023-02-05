# Deep-Learning-Models-for-Fall-Classification
낙상 분류를 위한 딥러닝 모델

## Data
- [clinical-notes-dataset](https://github.com/ni-inha/clinical-notes-dataset)

## BERT-based models

### English Data
- BERT-base
- BERT-multilingual
- Bio-Clinical-BERT
- Blue-BERT

### Korean Data
- BERT-multilingual
- KLUE-BERT

## LSTM-based models

### English Data
- LSTM
- Bi-LSTM

### Korean Data
- LSTM
- Bi-LSTM
## Perfomance Of Models in Kor
| **Language** | **Data Type**             | **Dataset**    | **Model Type**               | **Precision** | **Recall** | **Accuracy** | **F1 score** | **F2 score** | **Epochs** |
|:------------:|---------------------------|----------------|------------------------------|---------------|------------|--------------|--------------|--------------|------------|
|    Korean    | De-identified Korean data | Multisite data | BERT-base-multilingual-cased | 0.9636        | 0.9955     | 0.9877       | 0.9793       | 0.9890       | 6          |
|    Korean    | De-identified Korean data | Multisite data | fastText                     | 0.9614        | 0.9614     | 0.9774       | 0.9614       | 0.9614       | 6          |
|    Korean    | De-identified Korean data | Multisite data | KLUE BERT-base               | 0.9814        | 0.9906     | 0.9917       | 0.9860       | 0.9887       | 6          |
|    Korean    | De-identified Korean data | Multisite data | LSTM-base                    | 0.9798        | 0.9822     | 0.9888       | 0.9810       | 0.9802       | 8          |
|    Korean    | De-identified Korean data | Multisite data | BiLSTM-base                  | 0.9764        | 0.9837     | 0.9833       | 0.9800       | 0.9778       | 9          |

## Perfomance Of Models in Eng
| **Language** | **Data Type**              | **Dataset**    | **Model Type**               | **Precision** | **Recall** | **Accuracy** | **F1 score** | **F2 score** | **Epochs** |
|--------------|----------------------------|----------------|------------------------------|---------------|------------|--------------|--------------|--------------|------------|
|    English   | De-identified English data | Multisite data | fastText                     | 0.9610        | 0.9624     | 0.9775       | 0.9617       | 0.9621       | 6          |
|    English   | De-identified English data | Multisite data | BERT-base-multilingual-cased | 0.9713        | 0.9866     | 0.9842       | 0.9789       | 0.9835       | 2          |
|    English   | De-identified English data | Multisite data | BERT-base-cased              | 0.9702        | 0.9837     | 0.9864       | 0.9769       | 0.9810       | 2          |
|    English   | De-identified English data | Multisite data | Bio+Clinical BERT            | 0.9736        | 0.9842     | 0.9875       | 0.9788       | 0.9820       | 2          |
|    English   | De-identified English data | Multisite data | BlueBERT                     | 0.9726        | 0.9847     | 0.9874       | 0.9786       | 0.9823       | 2          |
|    English   | De-identified English data | Multisite data | LSTM-base                    | 0.9707        | 0.9832     | 0.9834       | 0.9769       | 0.9731       | 12         |
|    English   | De-identified English data | Multisite data | BiLSTM-base                  | 0.9832        | 0.9817     | 0.9897       | 0.9824       | 0.9829       | 9          |

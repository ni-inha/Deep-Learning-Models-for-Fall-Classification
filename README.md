# Deep-Learning-Models-for-Fall-Classification
EMR 임상 노트 내 **낙상 기록 식별**을 위한 딥러닝 기반 모델

## Data
- [clinical-notes-dataset](https://github.com/ni-inha/clinical-notes-dataset)

# Models

## BERT-based models

- BERT<sub>Base</sub> cased
- BERT<sub>Base</sub> multilingual cased
- Bio+Clinical BERT
- BLUE BERT
- KLUE BERT<sub>Base</sub>  

## LSTM-based models

- LSTM
- Bi-LSTM

## Perfomances
- Data Type
  - De-identified English data
  - De-identified Korean data
- The model marked with `*` is the model with the highest **F1 Score**.
- And the model marked with `**` is the model with the highest **F2 Score**.

### De-identified English data
| **Model**                                      | **Precision** | **Recall** | **Accuracy** | **F1 Score**        | **F2 Score**      |
|:-----------------------------------------------|---------------|------------|--------------|---------------------|-------------------|
| fastText                                       | 0.9610        | 0.9624     | 0.9775       | 0.9617              | 0.9621            | 
| LSTM                                           | 0.9707        | 0.9832     | 0.9834       | 0.9769              | 0.9731            | 
| \***Bi-LSTM**                                  | **0.9832**    | 0.9817     | **0.9897**   | \*_**0.9824**_      | 0.9829            | 
| BERT<sub>Base</sub> cased                      | 0.9702        | 0.9837     | 0.9864       | 0.9769              | 0.9810            |
| \*\***BERT<sub>Base</sub> multilingual cased** | 0.9713        | **0.9866** | 0.9842       | 0.9789              | \*\*_**0.9835**_  |
| Bio+Clinical BERT                              | 0.9736        | 0.9842     | 0.9875       | 0.9788              | 0.9820            | 
| BLUE BERT                                      | 0.9726        | 0.9847     | 0.9874       | 0.9786              | 0.9823            | 


### De-identified Korean data
| **Model**                                      | **Precision** | **Recall** | **Accuracy** | **F1 Score**   | **F2 Score**      |
|:-----------------------------------------------|---------------|------------|--------------|----------------|-------------------|
| fastText                                       | 0.9614        | 0.9614     | 0.9774       | 0.9614         | 0.9614            |
| LSTM                                           | 0.9798        | 0.9822     | 0.9888       | 0.9810         | 0.9802            |
| Bi-LSTM                                        | 0.9764        | 0.9837     | 0.9833       | 0.9800         | 0.9778            |
| \*\***BERT<sub>Base</sub> multilingual cased** | 0.9636        | **0.9955** | 0.9877       | 0.9793         | \*\*_**0.9890**_  |
| \***KLUE BERT<sub>Base</sub>**                 | **0.9814**    | 0.9906     | **0.9917**   | \*_**0.9860**_ | 0.9887            |


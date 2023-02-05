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
## Perfomance Of Models
| **Language** 	| **Data Type**             	| **Dataset**    	| **Model Type**               	| **Precision** 	| **Recall** 	| **Accuracy** 	| **F1 score** 	| **F2 score** 	| **Epochs** 	|
|--------------	|---------------------------	|----------------	|------------------------------	|---------------	|------------	|--------------	|--------------	|--------------	|------------	|
|              	| De-identified Korean data 	| Multisite data 	| BERT-base-multilingual-cased 	| 0.9636        	| 0.9955     	| 0.9877       	| 0.9793       	| 0.9890       	| 6          	|
|    Korean    	| De-identified Korean data 	| Multisite data 	| fastText                     	| 0.9614        	| 0.9614     	| 0.9774       	| 0.9614       	| 0.9614       	| 6          	|
|              	| De-identified Korean data 	| Multisite data 	| KLUE BERT-base               	| 0.9814        	| 0.9906     	| 0.9917       	| 0.9860       	| 0.9887       	| 6          	|
|              	| De-identified Korean data 	| Multisite data 	| LSTM-base                    	| 0.9798        	| 0.9822     	| 0.9888       	| 0.9810       	| 0.9802       	| 8          	|
|              	| De-identified Korean data 	| Multisite data 	| BiLSTM-base                  	| 0.9764        	| 0.9837     	| 0.9833       	| 0.9800       	| 0.9778       	| 9          	|

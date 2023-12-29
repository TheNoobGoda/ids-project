# KNN

## Missing data
### imputation

* accuracy: 0.9008438818565401
* recall: 0.3435114503816794
* precision: 0.8490566037735849
* f1: 0.48913043478260876

* confusion matrix:

    |     |     |
    |-----|-----|
    | 809 | 8   |
    | 86  | 45  |

### drop na

* accuracy: 0.9008782936010038
* recall: 0.32710280373831774
* precision: 0.8333333333333334
* f1: 0.46979865771812074

* confusion matrix:

    |     |     |
    |-----|-----|
    | 683 | 7   |
    | 72  | 35  |


## Removing correlated columns
### removing

* accuracy: 0.8850210970464135
* recall: 0.3055555555555556
* precision: 0.8301886792452831
* f1: 0.44670050761421326

* confusion matrix:

    |     |     |
    |-----|-----|
    | 795 | 9  |
    | 100  | 44  |

### not removing

* accuracy: 0.8945147679324894
* recall: 0.4
* precision: 0.631578947368421
* f1: 0.4897959183673469

* confusion matrix:

    |     |     |
    |-----|-----|
    | 800 | 28  |
    | 72  | 48  |


## handling imbalence
### nothing

* accuracy: 0.8850210970464135
* recall: 0.29850746268656714
* precision: 0.7272727272727273
* f1: 0.42328042328042326

* confusion matrix:

    |     |     |
    |-----|-----|
    | 799 | 15  |
    | 94  | 40  |

### oversampling

* accuracy: 0.8892405063291139
* recall: 0.3359375
* precision: 0.6825396825396826
* f1: 0.4502617801047121

* confusion matrix:

    |     |     |
    |-----|-----|
    | 800 | 20  |
    | 85  | 43  |

### undersampling

* accuracy: 0.8924050632911392
* recall: 0.2222222222222222
* precision: 0.875
* f1: 0.3544303797468354

* confusion matrix:

    |     |     |
    |-----|-----|
    | 818 | 4  |
    | 98  | 28  |





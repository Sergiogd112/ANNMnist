# Models Report
## Lime test
### Correct-Correct

true output: 7

#### ANN

!['ANN true'](ANNtslime0.png)
filename: ANNtslime0.png

#### RF

!['RF true'](RFtslime0.png)
filename: RFtslime0.png

### ANN Correct-RF Incorrect

true output: 7

#### ANN

!['ANN true'](ANNtslime1.png)
filename: ANNtslime1.png

#### RF

predicted: 0

!['RF true'](RFtslime1.png)
!['RF predicted'](RFtslime4.png)
filename: 
* RFtslime1.png
* RFtslime4.png

### ANN Incorrect-RF Correct

true output: 7

#### ANN

predicted: 0

!['ANN true'](ANNtslime2.png)
!['ANN predicted'](RFtslime5.png)

filename:
* ANNtslime2.png
* RFtslime5.png

#### RF

!['RF true'](RFtslime2.png)

filename: RFtslime2.png

### ANN Incorrect-RF Correct

true output: 7

#### ANN

predicted: 0

!['ANN true'](ANNtslime3.png)
!['ANN predicted'](ANNtslime3.png)

filename: 
* ANNtslime3.png
* ANNtslime3.png

#### RF

predicted: 0


!['RF true'](RFtslime6.png)
!['RF predicted'](RFtslime7.png)

filename: 
* RFtslime6.png
* RFtslime7.png

## Confusion matrices

### ANN training

!['ANN training confution matrix'](ANNtrainconf.png)

filename: ANNtrainconf.png

### ANN testing

!['ANN test confution matrix'](ANNtestconf.png)
filename: ANNtestconf.png

### RF training

!['RF training confution matrix'](RFtrainconf.png)

filename: RFtrainconf.png

### RF testing

!['RF test confution matrix'](RFtestconf.png)

filename: RFtestconf.png

## Stats

### Acuracy

ANN acccuracy: 
* training: 0.7135166666666667
* test: 0.7168

RF accuracy:
* training: 0.78795
* test: 0.7743

!['Accuracy'](acc.png)

filename: acc.png

### Loss

ANN loss: 
* training: 0.019620925
* test: 0.019194128
RF loss:
* training: 0.010987174
* test: 0.011564514

!['Loss'](loss.png)

filename: loss.png

# Models Report
## Lime test
### Correct-Correct

true output: occ_

#### model1

!['_lgcc1_'](_filenamelgcc1_)
filename: _filenamelgcc1_

#### model2

!['_lgcc2_'](_filenamelgcc2_)
filename: _filenamelgcc2_

### model1 Correct-model2 Incorrect

true output: oci_

#### model1

!['_lgci1_'](_filenamelgci1_)
filename: _filenamelgci1_

#### model2

predicted: oci2

!['_lgci2c_'](_filenamelgci2c_)
!['_lgci2p_'](_filenamelgci2p_)
filename: 
* _filenamelgci2c_
* _filenamelgci2p_

### model1 Incorrect-model2 Correct

true output: oic_

#### model1

predicted: oic1

!['_lgic1c_'](_filenamelgic1c_)
!['_lgic1p_'](_filenamelgic1p_)

filename:
* _filenamelgic1c_
* _filenamelgic1p_

#### model2

!['_lgic2_'](_filenamelgic2_)

filename: _filenamelgic2_

### model1 Incorrect-model2 Correct

true output: oii_

#### model1

predicted: oii1

!['_lgii1c_'](_filenamelgii1c_)
!['_lgii1p_'](_filenamelgii1p_)

filename: 
* _filenamelgii1c_
* _filenamelgii1p_

#### model2

predicted: oii2


!['_lgii2c_'](_filenamelgii2c_)
!['_lgii2p_'](_filenamelgii2p_)

filename: 
* _filenamelgii2c_
* _filenamelgii2p_

## Confusion matrices

### model1 training

!['_cg1tr_'](_filenamecg1tr_)

filename: _filenamecg1tr_

### model1 testing

!['_cg1ts_'](_filenamecg1ts_)
filename: _filenamecg1ts_

### model2 training

!['_cg2tr_'](_filenamecg2tr_)

filename: _filenamecg2tr_

### model2 testing

!['_cg2ts_'](_filenamecg2ts_)

filename: _filenamecg2ts_

## Stats

### Acuracy

model1 acccuracy: 
* training: tracc1val
* test: tsacc1val

model2 accuracy:
* training: tracc2val
* test: tsacc2val

!['Accuracy'](_filenameacc_)

filename: _filenameacc_

### Loss

model1 loss: 
* training: trloss1val
* test: tsloss1val
model2 loss:
* training: trloss2val
* test: tsloss2val

!['Loss'](_filenameloss_)

filename: _filenameloss_

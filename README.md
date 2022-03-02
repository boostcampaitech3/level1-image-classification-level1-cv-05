# Getting Started    
### Dependencies
- torch==1.6.0
- torchvision==0.7.0                                                              

### Install Requirements
- `pip install -r requirements.txt`

### Training
- `SM_CHANNEL_TRAIN=[train image dir] SM_MODEL_DIR=[model saving dir] python train.py`

### Inference
- `SM_CHANNEL_EVAL=[eval image dir] SM_CHANNEL_MODEL=[model saved dir] SM_OUTPUT_DATA_DIR=[inference output dir] python inference.py`

### Evaluation
- `SM_GROUND_TRUTH_DIR=[GT dir] SM_OUTPUT_DATA_DIR=[inference output dir] python evaluation.py`



SM_CHANNEL_MODEL='/opt/ml/level1-image-classification-level1-cv-05/model/__' python inference.py --model __

# Convention
## Issue Template
**Title** : [ Head ] contents

**Body**  
- Experiment  : 
- Content : 

- Progress
- [] A
- [] B
- [] C


## Issue Comment

**Performance** : { train, test loss and metric }

**Explanation** :

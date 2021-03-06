# oral_AI_challenge_2021
## About The Project
Submitted code for **2021 Oral AI challenge (2021 구강계질환 의료영상 인공지능 경진대회)**<br />
hosted by Samsung Seoul Hospital, Ajou University Hospital, and MINDs'n company<br />
**Link:** http://aifactory.space/task/detail.do?taskId=T001727<br /><br />

## Usage
- **dataloader_cancer.py**　-----　to read data from filenames and save image and label data<br />
- **classifier.py**　　　　　-----　to train classifier and test it with validation dataset<br />
- **train.py**　　　　　　　-----　to train classifier<br />
- **train.sh**　　　　　　　-----　shell script to run 'train.py' with various settings<br />
- **metrics.py**　　　　　　-----　to calculate evaluation metrics<br />
- **utils.py**　　　　　　　-----　functions utilized in main script<br />
- **inference.py**　　　　　-----　predict label with given dataset and trained model<br />
- **submit.py**　　　　　　-----　to submit inference results<br /><br />

## Directory Structure
```bash
├── README.md
├── dataloader_cancer.py
├── classifier.py
├── train.py
├── train.sh
├── metrics.py
├── utils.py
├── inference.py
└── submit.py
```
<br />

## License
**copyrightⓒ 2021 All rights reserved by Hyebin Lee, Jieun Choi, Eunjin Kim, and Ajou University Hospital<br /><br />**

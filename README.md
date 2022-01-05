# ConferencingSpeech 2022 challenge
This repository contains the datasets list and scripts required for the ConferencingSpeech 2022 challenge. For more details about the challenge, please see our [website](https://tea-lab.qq.com/).
# Details
* `baseline`, this folder contains baseline system include inference model exported by inference scripts;
* `eval`, this folder contains evaluation scripts to calculate PLCC, RMSE and SRCC;
* `data-sets`, this folder contains training and development test data-sets provied to the participant; 
  * `Tencent Corpus`, this dataset  includes about 14,000 speech chinese speech clips. 
  * `NISQA Corpus`, the NISQA Corpus includes more than 14,000 speech samples with simulated (e.g. codecs, packet-loss, background noise) and live (e.g. mobile phone, Zoom, Skype, WhatsApp) conditions. 
  * `IU Bloomington Corpus`, there are 10,000 speech signals extracted from COSINE  and VOiCESdatasets, each truncated between 3 to 6 seconds long.
  * `Microsoft Corpus`

# Requirements
python3.6 or above

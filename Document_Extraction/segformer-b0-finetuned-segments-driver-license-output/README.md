---
license: other
base_model: nvidia/mit-b0
tags:
- vision
- image-segmentation
- generated_from_trainer
model-index:
- name: segformer-b0-finetuned-segments-driver-license
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# segformer-b0-finetuned-segments-driver-license

This model is a fine-tuned version of [nvidia/mit-b0](https://huggingface.co/nvidia/mit-b0) on the narutophuc113/driver_license dataset.
It achieves the following results on the evaluation set:
- Loss: 0.0010
- Mean Iou: 0.0
- Mean Accuracy: nan
- Overall Accuracy: nan
- Accuracy Background: nan
- Accuracy Unknown: nan
- Accuracy Document: nan
- Iou Background: 0.0
- Iou Unknown: 0.0
- Iou Document: 0.0

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 6e-05
- train_batch_size: 2
- eval_batch_size: 2
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 50

### Training results

| Training Loss | Epoch   | Step | Validation Loss | Mean Iou | Mean Accuracy | Overall Accuracy | Accuracy Background | Accuracy Unknown | Accuracy Document | Iou Background | Iou Unknown | Iou Document |
|:-------------:|:-------:|:----:|:---------------:|:--------:|:-------------:|:----------------:|:-------------------:|:----------------:|:-----------------:|:--------------:|:-----------:|:------------:|
| 0.4763        | 0.3448  | 20   | 0.6550          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.3745        | 0.6897  | 40   | 0.3990          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.2955        | 1.0345  | 60   | 0.2332          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.237         | 1.3793  | 80   | 0.1806          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.1622        | 1.7241  | 100  | 0.1400          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.1565        | 2.0690  | 120  | 0.1455          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.1153        | 2.4138  | 140  | 0.1042          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.1237        | 2.7586  | 160  | 0.0938          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.092         | 3.1034  | 180  | 0.0566          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0916        | 3.4483  | 200  | 0.0586          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.094         | 3.7931  | 220  | 0.0515          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0478        | 4.1379  | 240  | 0.0410          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0385        | 4.4828  | 260  | 0.0355          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0394        | 4.8276  | 280  | 0.0335          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0473        | 5.1724  | 300  | 0.0279          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0339        | 5.5172  | 320  | 0.0227          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0245        | 5.8621  | 340  | 0.0231          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.026         | 6.2069  | 360  | 0.0186          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0233        | 6.5517  | 380  | 0.0176          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0225        | 6.8966  | 400  | 0.0180          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0161        | 7.2414  | 420  | 0.0163          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0177        | 7.5862  | 440  | 0.0172          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0161        | 7.9310  | 460  | 0.0139          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0163        | 8.2759  | 480  | 0.0142          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0113        | 8.6207  | 500  | 0.0118          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0097        | 8.9655  | 520  | 0.0096          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.012         | 9.3103  | 540  | 0.0107          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0151        | 9.6552  | 560  | 0.0107          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0097        | 10.0    | 580  | 0.0084          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0091        | 10.3448 | 600  | 0.0080          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0077        | 10.6897 | 620  | 0.0079          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0089        | 11.0345 | 640  | 0.0075          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0055        | 11.3793 | 660  | 0.0066          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0069        | 11.7241 | 680  | 0.0063          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0073        | 12.0690 | 700  | 0.0068          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0042        | 12.4138 | 720  | 0.0054          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0064        | 12.7586 | 740  | 0.0056          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0065        | 13.1034 | 760  | 0.0063          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0067        | 13.4483 | 780  | 0.0053          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0077        | 13.7931 | 800  | 0.0051          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.005         | 14.1379 | 820  | 0.0046          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.004         | 14.4828 | 840  | 0.0046          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0072        | 14.8276 | 860  | 0.0049          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0051        | 15.1724 | 880  | 0.0042          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0033        | 15.5172 | 900  | 0.0043          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0059        | 15.8621 | 920  | 0.0044          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0023        | 16.2069 | 940  | 0.0039          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0047        | 16.5517 | 960  | 0.0040          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0039        | 16.8966 | 980  | 0.0035          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0034        | 17.2414 | 1000 | 0.0038          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0054        | 17.5862 | 1020 | 0.0037          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.004         | 17.9310 | 1040 | 0.0033          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0032        | 18.2759 | 1060 | 0.0031          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0042        | 18.6207 | 1080 | 0.0033          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0037        | 18.9655 | 1100 | 0.0031          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0035        | 19.3103 | 1120 | 0.0032          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0046        | 19.6552 | 1140 | 0.0032          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0028        | 20.0    | 1160 | 0.0029          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0023        | 20.3448 | 1180 | 0.0026          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.003         | 20.6897 | 1200 | 0.0027          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0029        | 21.0345 | 1220 | 0.0028          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0025        | 21.3793 | 1240 | 0.0024          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0037        | 21.7241 | 1260 | 0.0025          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0026        | 22.0690 | 1280 | 0.0024          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0035        | 22.4138 | 1300 | 0.0023          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0027        | 22.7586 | 1320 | 0.0027          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0015        | 23.1034 | 1340 | 0.0025          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0012        | 23.4483 | 1360 | 0.0023          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0021        | 23.7931 | 1380 | 0.0023          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0019        | 24.1379 | 1400 | 0.0023          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0017        | 24.4828 | 1420 | 0.0019          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0017        | 24.8276 | 1440 | 0.0020          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0019        | 25.1724 | 1460 | 0.0019          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0024        | 25.5172 | 1480 | 0.0018          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0025        | 25.8621 | 1500 | 0.0021          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0017        | 26.2069 | 1520 | 0.0018          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0022        | 26.5517 | 1540 | 0.0018          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0029        | 26.8966 | 1560 | 0.0022          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0016        | 27.2414 | 1580 | 0.0017          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0024        | 27.5862 | 1600 | 0.0021          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0015        | 27.9310 | 1620 | 0.0018          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0025        | 28.2759 | 1640 | 0.0018          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0018        | 28.6207 | 1660 | 0.0016          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0017        | 28.9655 | 1680 | 0.0018          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0016        | 29.3103 | 1700 | 0.0016          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0021        | 29.6552 | 1720 | 0.0018          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0009        | 30.0    | 1740 | 0.0015          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0025        | 30.3448 | 1760 | 0.0015          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0027        | 30.6897 | 1780 | 0.0017          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0022        | 31.0345 | 1800 | 0.0015          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0013        | 31.3793 | 1820 | 0.0016          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0018        | 31.7241 | 1840 | 0.0014          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0006        | 32.0690 | 1860 | 0.0013          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.002         | 32.4138 | 1880 | 0.0016          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0008        | 32.7586 | 1900 | 0.0015          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0015        | 33.1034 | 1920 | 0.0014          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0024        | 33.4483 | 1940 | 0.0013          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0018        | 33.7931 | 1960 | 0.0014          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0018        | 34.1379 | 1980 | 0.0013          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0009        | 34.4828 | 2000 | 0.0013          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.002         | 34.8276 | 2020 | 0.0014          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0009        | 35.1724 | 2040 | 0.0013          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0011        | 35.5172 | 2060 | 0.0013          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0014        | 35.8621 | 2080 | 0.0013          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0023        | 36.2069 | 2100 | 0.0013          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.002         | 36.5517 | 2120 | 0.0013          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0008        | 36.8966 | 2140 | 0.0012          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0011        | 37.2414 | 2160 | 0.0013          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0011        | 37.5862 | 2180 | 0.0012          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0013        | 37.9310 | 2200 | 0.0012          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0009        | 38.2759 | 2220 | 0.0012          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0019        | 38.6207 | 2240 | 0.0012          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0019        | 38.9655 | 2260 | 0.0013          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0009        | 39.3103 | 2280 | 0.0011          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.001         | 39.6552 | 2300 | 0.0009          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0007        | 40.0    | 2320 | 0.0012          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0011        | 40.3448 | 2340 | 0.0011          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0009        | 40.6897 | 2360 | 0.0010          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0017        | 41.0345 | 2380 | 0.0011          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0014        | 41.3793 | 2400 | 0.0012          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.001         | 41.7241 | 2420 | 0.0010          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0015        | 42.0690 | 2440 | 0.0011          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0007        | 42.4138 | 2460 | 0.0010          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0014        | 42.7586 | 2480 | 0.0011          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0009        | 43.1034 | 2500 | 0.0011          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.001         | 43.4483 | 2520 | 0.0011          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0016        | 43.7931 | 2540 | 0.0011          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0013        | 44.1379 | 2560 | 0.0011          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0015        | 44.4828 | 2580 | 0.0010          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0013        | 44.8276 | 2600 | 0.0011          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0013        | 45.1724 | 2620 | 0.0011          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0008        | 45.5172 | 2640 | 0.0010          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0016        | 45.8621 | 2660 | 0.0011          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0009        | 46.2069 | 2680 | 0.0011          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.001         | 46.5517 | 2700 | 0.0010          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0009        | 46.8966 | 2720 | 0.0012          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0009        | 47.2414 | 2740 | 0.0010          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0012        | 47.5862 | 2760 | 0.0011          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0011        | 47.9310 | 2780 | 0.0010          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0011        | 48.2759 | 2800 | 0.0011          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0012        | 48.6207 | 2820 | 0.0011          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0013        | 48.9655 | 2840 | 0.0010          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0014        | 49.3103 | 2860 | 0.0010          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0006        | 49.6552 | 2880 | 0.0009          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |
| 0.0008        | 50.0    | 2900 | 0.0010          | 0.0      | nan           | nan              | nan                 | nan              | nan               | 0.0            | 0.0         | 0.0          |


### Framework versions

- Transformers 4.40.2
- Pytorch 2.2.0+cpu
- Datasets 2.19.1
- Tokenizers 0.19.1

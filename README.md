# Awesome Long-Tailed Learning 

A curated list of awesome deep long-tailed learning resources.

Recently, we released *[Deep Long-Tailed Learning: A Survey]()* to the community. In this survey, we reviewed recent advances of long-tailed learning based on deep neural networks. To be specific, existing deep long-tailed learning studies can be grouped into three main categories (i.e., class re-balancing, information augmentation and module improvement), which can be further classified into nine sub-categories (as shown in below figure). We also empirically analyzeed several state-of-the-art methods by evaluating to what extent they address the issue of class imbalance. We concluded the survey by highlighting important applications of deep long-tailed learning and identifying several promising directions for future research. After completing this survey, we decided to release the collected long-tailed learning resources, hoping to push the development of the community. We will keep updating our survey and this repository. If you have any questions or suggestions, please feel free to contact us.

<p align="center">
<img src="Taxonomy.png" width=800>
</p>

## Type of Long-tailed Learning

| Symbol    | `Sampling`          | `CSL`           | `LA`                   | `TL`                 | `Aug`                  | 
|:----------- |:-------------:|:--------------:|:----------------------: |:---------------------:|:----------------------:| 
| Type | Re-Sampling | Cost-sensitive Learning | Logit Adjustment | Transfer Learning | Data Augmentation | 

| Symbol    | `RL`          | `CD`           | `DT`                   | `Ensemble`                 | `other`                  | 
|:----------- |:-------------:|:--------------:|:----------------------: |:---------------------:|:----------------------:| 
| Type | Representation Learning | Classifier Design | Decoupled Training | Ensemble Learning | Other Types | 

## Papers

### 2021

| Title    | Venue    | Year | Type     | Code     | 
|:-------- |:--------:|:--------:|:--------:|:--------:|
[Video-LT]() | ICCV  | 2021 | `Sampling`     |       | 
[LOCE]() | ICCV  | 2021 | `Sampling`, `CSL`     |       |  
[GIST]() | ICCV  | 2021 | `Sampling`, `TL`, `DC`      |       |  
[FASA]() | ICCV  | 2021 | `Sampling`, `CSL`     |       |  
[ACE]() | ICCV  | 2021 | `Sampling`, `Ensemble`     |       |  
[DARS]() | ICCV  | 2021 | `TL`     |       |  
[SSD]() | ICCV  | 2021 | `TL`     |       |  
[DiVE]() | ICCV  | 2021 | `TL`     |       |  
[MosaicOS]() | ICCV  | 2021 | `TL`     |       |  
[PaCo]() | ICCV  | 2021 | `RL`     |       |  
[DRO-LT]() | ICCV  | 2021 | `RL`     |       | 
[DT2]() | ICCV  | 2021 | `DT`     |       |  
[Delving into Deep Imbalanced Regression]() | ICML  | 2021 | `Other`     |    [Official](https://github.com/YyzHarry/imbalanced-regression.)   |  
[LTML]() | CVPR  | 2021 | `Sampling`, `Ensemble` |       | 
[Long-Tail Learning via Logit Adjustment](https://arxiv.org/pdf/2007.07314.pdf) | ICLR  | 2021 | `CLW`     | Official    | 


## Citing this work 

If this repository is helpful to you, please cite our survey.

```
@article{zhang2021deep,
    title={Deep Long-Tailed Learning: A Survey},
    author={Zhang, Yifan and Kang, Bingyi and Hooi, Bryan and Yan, Shuicheng and Feng, Jiashi},
    journal={arXiv preprint},
    year={2021}
}
```

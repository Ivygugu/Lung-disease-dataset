# 肺部疾病影像数据集集锦
# 目录
=================

* [肺](#肺)
   * [MSD肺癌分割](#msd肺癌分割)
   * [LoLa11肺叶分割](#lola11肺叶分割)
   * [StructSeg2019](#structseg2019)
   * [肺部多病智能诊断](#肺部多病智能诊断)
   * [CheXpert](#chexpert)
   * [NIHChest Xray](#nihchest-xray)
   * [QIN Lung CT](#qin-lung-ct)
   * [4D-Lung](#4d-lung)
   * [NSCLC-Radiomics](#nsclc-radiomics)
   * [vessel12 肺部血管分割](#vessel12-肺部血管分割)
   * [肺结核](#肺结核)
      * [Shenzhen Hospital X-ray Set](#shenzhen-hospital-x-ray-set)
      * [Montgomery County X-ray Set](#montgomery-county-x-ray-set)
   * [肺炎](#肺炎)
      * [Ieee8023](#ieee8023)
      * [covid19-ct-scans](#covid19-ct-scans)
      * [COVID-CT](#covid-ct)
      * [Figure1-COVID-chestxray-dataset](#figure1-covid-chestxray-dataset)
      * [RSNA肺炎检测](#rsna肺炎检测)
      * [CovidX](#covidx)
      * [Flyai Covid](#flyai-covid)
      * [covid19-radiography-database](#covid19-radiography-database)
      * [COVID-19-AR](#covid-19-ar)
      * [CT Images in COVID-19](#ct-images-in-covid-19)
   * [肺结节](#肺结节)
      * [LIDC-IDRI](#lidc-idri)
      * [LUNA16](#luna16)
      * [天池肺部结节](#天池肺部结节)
      * [LNDB](#lndb)
      * [Lung Nodule Malignancy](#lung-nodule-malignancy)
      * [Data Science Bowl 17](#data-science-bowl-17)
      * [Lung-PET-CT-Dx](#lung-pet-ct-dx)
   * [气胸](#气胸)
      * [SIIM-ACR Pneumothorax Segmentation](#siim-acr-pneumothorax-segmentation)
      
=================

# 肺
## MSD肺癌分割

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式  | License |
| - | - | - | - | - | - | - | - |
| [MSD肺癌分割](http://medicaldecathlon.com/) | 肺脏 | 分割 | CT | 96 | 0/1 | nii | [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |

![Lung-Tumours](https://raw.githubusercontent.com/linhandev/dataset/main/static/Lung-Tumours.png)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/10334)

## LoLa11肺叶分割

[//]: # (FIN)

| 名称 | 标注内容    | 类型 | 模态 | 数量 | 标签格式 | 文件格式  | License |
| - | - | - | - | - | - | - | - |
| [LoLa11](https://lola11.grand-challenge.org/) | None | 分割 | CT   | 55 | None  | Metaimage | [Other](https://zenodo.org/record/4708800) |

![lola11](https://grand-challenge-public.s3.amazonaws.com/f/challenge/39/c4ab1b11-3338-4b99-a732-174ddc9e3b70/lola11_web.png)

LoLa11 包含55套CT数据，未发现任何公开标注信息

[zenodo下载](https://zenodo.org/record/4708800)

[//]: # (30417)

## StructSeg2019

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [StructSeg2019](https://structseg2019.grand-challenge.org/) ||      |||||

![structseg2019](https://grand-challenge-public.s3.amazonaws.com/b/398/banner2_XdYKwmN.jpg)


## 肺部多病智能诊断

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [肺部多病智能诊断](https://tianchi.aliyun.com/competition/entrance/231724/) |          |      | CT   |      |          |          |

[//]: # (34323)

## CheXpert

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [CheXpert](https://stanfordmlgroup.github.io/competitions/chexpert/) |  |      |      |      |          |          | [Other](https://stanfordmlgroup.github.io/competitions/chexpert/) |

![chestxpert](https://raw.githubusercontent.com/linhandev/dataset/main/static/chest-x-pert.png)

介绍论文： [CheXpert: A Large Chest Radiograph Dataset with Uncertainty Labels and Expert Comparison](https://arxiv.org/abs/1901.07031)

[相关项目](https://github.com/gaetandi/cheXpert)

## NIHChest Xray

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [NIHChest Xray](https://www.kaggle.com/nih-chest-xrays/data) | 14种肺部疾病/部分病灶位置 | 分类/检测 | CXR | 112,120 | csv | png | [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/) |

![img](https://raw.githubusercontent.com/linhandev/dataset/main/static/nih-chest-xray.png)
介绍论文： [ChestX-ray8: Hospital-scale Chest X-ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases](http://openaccess.thecvf.com/content_cvpr_2017/papers/Wang_ChestX-ray8_Hospital-Scale_Chest_CVPR_2017_paper.pdf)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/35660)

## QIN Lung CT

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [QIN Lung CT](https://wiki.cancerimagingarchive.net/display/Public/QIN+LUNG+CT) | 非小細胞癌 |  | CT  | 47 |  | dcm | [Other](https://wiki.cancerimagingarchive.net/display/Public/Data+Usage+Policies+and+Restrictions) |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/35205)

## 4D-Lung

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [4D-Lung](https://wiki.cancerimagingarchive.net/display/Public/4D-Lung) | 非小細胞癌 |      | CT |  | 20 | dcm |[Other](https://wiki.cancerimagingarchive.net/display/Public/Data+Usage+Policies+and+Restrictions)|

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/37482)

## NSCLC-Radiomics

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [NSCLC-Radiomics](https://wiki.cancerimagingarchive.net/display/Public/NSCLC-Radiomics) | 非小细胞癌　| 分割　|　CT | 422 |          | dcm |

![NSCLC-Radiomics](https://raw.githubusercontent.com/linhandev/dataset/main/static/NSCLC-Radiomics.png)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/63958)



## vessel12 肺部血管分割

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [vessel12 肺部血管分割](https://vessel12.grand-challenge.org/) | 肺部血管 | 分割　|　CT | 20 |  | raw | |

![vessel12](https://grand-challenge-public-prod.s3.amazonaws.com/b/1/header.x15.jpeg)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/94923)

## 肺结核

### Shenzhen Hospital X-ray Set

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [Shenzhen Hospital X-ray Set](https://lhncbc.nlm.nih.gov/publication/pub9931) | 肺结核/正常 | 分类 | CXR  | 662  | 类别     | 图片     |

深圳第三医院收集的肺结核胸透数据集，包含326张正常扫描和336张不正常的扫描。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/25237)

### Montgomery County X-ray Set

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [Montgomery County X-ray Set](https://lhncbc.nlm.nih.gov/publication/pub9931) | 肺结核/正常 | 分类 | CXR  | 138  | 类别     | 图片     |

蒙哥马利市收集的肺结核胸透数据集，包含80张正常的扫描和58张不正常的扫描。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/34229)

## 肺炎
### Ieee8023

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [Ieee8023](https://github.com/ieee8023/covid-chestxray-dataset) | 肺脏     | 分类 | CT   | 20   |      | nii      |

持续搜集公开的新冠CT扫描，目前有20个病例。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/34221)

### covid19-ct-scans

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [covid19-ct-scans](https://www.kaggle.com/andrewmvd/covid19-ct-scans) | 左右肺/新冠感染 | 分割 | CT   | 20   |          | nii      |

数据来自Ieee8023，对20组扫描进行了左右肺和感染区的标注。基于这个数据集和另外几个数据集，大佬们做了一个新冠分割的 [benchmark](https://gitee.com/junma11/COVID-19-CT-Seg-Benchmark)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/34221)

### COVID-CT

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [COVID-CT](https://github.com/UCSD-AI4H/COVID-CT) |          | 分类 | CT   | 349  |          | 图片     |

包含216名新冠患者的349张胸部CT图片，从相关paper中收集。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/27732)

### Figure1-COVID-chestxray-dataset

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [Figure1-COVID-chestxray-dataset](https://github.com/agchung/Figure1-COVID-chestxray-dataset) |          | 分类 | CXR  | 48   |          | 图片     |

DarwinAI收集的一些新冠CT的图片，是CovidX数据集的一部分。持续更新，使用前可以先pull。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/34208)

### RSNA肺炎检测

|                                     名称                                     |      标注内容       |   类型    | 模态 |    数量    | 标签格式 | 文件格式 |                                   License                                   |
| ---------------------------------------------------------------------------- | ------------------- | --------- | ---- | ---------- | -------- | -------- | --------------------------------------------------------------------------- |
| [RSNA肺炎检测](https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/) | 是否肺炎 肺炎区域BB | 分类 检测 | CXR  | 26684+3000 |          |   图片   | [Custom](https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/rules) |

北美放射学会在Kaggle上组织的一个比赛数据集，数据来自[NIH](https://nihcc.app.box.com/v/ChestXray-NIHCC)。包含26684张训练数据，有图片的分类和肺炎区域的边界框。

[//]: # (https://aistudio.baidu.com/aistudio/datasetdetail/34214)

### CovidX

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [CovidX](https://github.com/lindawangg/COVID-Net/blob/master/docs/COVIDx.md) | 新冠/其他肺炎/正常 | 分类 | CT   | 13569+231 |          | 图片     |

CovidX数据集是DarwinAI训练[CovidNet](https://github.com/lindawangg/COVID-Net)做的一个数据集，本身没有新的数据，是Ieee8023，Figure1和RSNA组合成的一个数据集。


### Flyai Covid

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [Flyai Covid](https://www.flyai.com/d/ChestXray02) |          |      |      |      |          |          |

Flyai举办的一个新冠分类比赛。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/34230)

### covid19-radiography-database

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [covid19-radiography-database](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database) | 新冠/其他肺炎/正常 | 分类 | CT   | 219+1314+1345 |          | 图片     |

跟CovidX一样是一个组合数据集，数据来自论文图片和RSNA。

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/34241)

### COVID-19-AR

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [COVID-19-AR](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=70226443) | |  |    |  | | dcm|

Chest Imaging with Clinical and Genomic Correlates Representing a Rural COVID-19 Positive Population (COVID-19-AR)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/63553)

### CT Images in COVID-19

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| --- | --- | --- | --- | --- | --- | --- |
| [CT Images in COVID-19](https://wiki.cancerimagingarchive.net/display/Public/CT+Images+in+COVID-19) | 无标签 | 分类/分割 | CT 平扫 | 771 | 无 | nii |

<img src="https://raw.githubusercontent.com/linhandev/dataset/main/static/ct-images-in-covid19.png" width="50%"/>

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/63794)
相关论文：
- [Artificial intelligence for the detection of COVID-19 pneumonia on chest CT using multinational datasets](https://www.nature.com/articles/s41467-020-17971-2)
- [Generalized chest CT and lab curves throughout the course of COVID-19](https://www.nature.com/articles/s41598-021-85694-5)

## 肺结节

### LIDC-IDRI

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [LIDC-IDRI](https://wiki.cancerimagingarchive.net/display/Public/LIDC-IDRI) | 肺部肿瘤 | 目标检测 | CT | 1012 | xls | dcm |

介绍论文： [The Lung Image Database Consortium (LIDC) and Image Database Resource Initiative (IDRI): A Completed Reference Database of Lung Nodules on CT Scans](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3041807/)

[The public cancer radiology imaging collections of The Cancer Imaging Archive](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3041807/)

Aistudio下载 [Part1](https://aistudio.baidu.com/aistudio/datasetdetail/63957) [Part2](https://aistudio.baidu.com/aistudio/datasetdetail/64008)

### LUNA16

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [LUNA16](https://luna16.grand-challenge.org) |          |      |      |      |          |          |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/1860)

### 天池肺部结节

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - | - | - | - | - |
| [天池肺部结节](https://tianchi.aliyun.com/competition/entrance/231601/introduction) | 肺部结节| 检测 | 低剂量肺部CT | 1000(初赛) + 2000(复赛) | 位置+直径 | mhd | [Custom](https://tianchi.aliyun.com/competition/entrance/231601/introduction) |

[//]: # (训练：https://aistudio.baidu.com/aistudio/datasetDetail/20000 测试 : https://aistudio.baidu.com/aistudio/datasetdetail/10063)

### LNDB

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [LNDB](https://lndb.grand-challenge.org) | 直径大于3mm的肿瘤分割标注/小于3mm肿瘤和非肿瘤标记中心 | 分割/分类 | CT   | 294  | XML      | MetaImage |

介绍论文： [LNDb: A Lung Nodule Database on Computed Tomography](https://arxiv.org/abs/1911.08434)

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/23909)

### Lung Nodule Malignancy

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [Lung Nodule Malignancy](https://www.kaggle.com/kmader/lungnodemalignancy) | 肺结界良恶性 | 分类 | CT   | 4165+2526 |          | tif      |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/28474)

### Data Science Bowl 17

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [Data Science Bowl 17](https://www.kaggle.com/c/data-science-bowl-2017) |          |      |      |      |          |          |

[Aistudio下载](https://aistudio.baidu.com/aistudio/datasetdetail/25423)

### Lung-PET-CT-Dx

| 名称 | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [Lung-PET-CT-Dx](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=70224216) | 肺癌　| 目标检测 | CT | 363 | xml | dcm |

![Lung-PET-CT-Dx](https://raw.githubusercontent.com/linhandev/dataset/main/static/Lung-PET-CT-Dx.png)

## 气胸

### SIIM-ACR Pneumothorax Segmentation

| 名称      | 标注内容 | 类型 | 模态 | 数量 | 标签格式 | 文件格式 |
| - | - | - | - | - | - | - |
| [SIIM-ACR Pneumothorax Segmentation](https://www.kaggle.com/c/siim-acr-pneumothorax-segmentation) |   |   |    |   |   |  |


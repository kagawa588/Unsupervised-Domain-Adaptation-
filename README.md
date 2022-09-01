# Unsupervised-Domain-Adaptation


## LeaderBoard

 ### Domain Adaptation for Semantic Segmentation (GTAV->Cityscapes and Synthia->Cityscapes Dataset)

 | Name | gta2cs | syn2cs | Methods | Reference |
| -------- | ----- | ---- | ---- | ---- |
|CLUDA | 74.4 | 67.2 | Pixel Contrastive Loss | "[CLUDA : Contrastive Learning in Unsupervised Domain Adaptation for Semantic Segmentation]" (https://arxiv.org/pdf/2208.14227.pdf)", Midhun Vayyat, Jaswin Kasi, Anuraag Bhattacharya, Shuaib Ahmed, Rahul Tallamraju, 27/8/2022|
|HRDA | 73.8 | 65.8 | Higher Resolution | "[HRDA: Context-Aware High-Resolution Domain-Adaptive Semantic Segmentation]" (https://arxiv.org/pdf/2204.13132v2.pdf)", Lukas Hoyer, Dengxin Dai, Luc Van Gools, ECCV 2022|
|DAFormer + SePiCo | 70.3 | 64.3 | Pixel Contrastive Loss | "[SePiCo: Semantic-Guided Pixel Contrast for Domain Adaptive Semantic Segmentation]" (https://arxiv.org/pdf/2204.08808v1.pdf)", Binhui Xie, Shuang Li, Mingjia Li, Chi Harold Liu, Gao Huang, and Guoren Wang, T-PAMI|
|HRDA + ProCST | 73.9 | 66.4 | Image Translation | "[ProCST: Boosting Semantic Segmentation Using Progressive Cyclic Style-Transfer]"(https://arxiv.org/pdf/2204.11891v2.pdf)", Shahaf Ettedgui, Shady Abu-Hussein, Raja Giryes, 25/4/2022|
|DAFormer + ProCST | 69.4 | 61.6 | Image Translation | "[ProCST: Boosting Semantic Segmentation Using Progressive Cyclic Style-Transfer]"(https://arxiv.org/pdf/2204.11891v2.pdf)", Shahaf Ettedgui, Shady Abu-Hussein, Raja Giryes, 25/4/2022|
|DAFormer + CRnet | 68.2 | 61.6 | Pixel Contrastive Loss | "[Consistency Regularization for Domain Adaptation]" , 不太靠谱 , 23/8/2022|
|DAFormer | 68.3 | 60.9 | Transformer | "[DAFormer: Improving Network Architectures and Training Strategies for Domain-Adaptive Semantic Segmentation](https://arxiv.org/pdf/2111.14887v2.pdf)", Lukas Hoyer, Dengxin Dai, Luc Van Gool, CVPR 2022|
|DACS | 52.14 | 48.34 | Mix Sampling | "[DACS: Domain Adaptation via Cross-domain Mixed Sampling](https://openaccess.thecvf.com/content/WACV2021/papers/Tranheden_DACS_Domain_Adaptation_via_Cross-Domain_Mixed_Sampling_WACV_2021_paper.pdf)", Wilhelm Tranheden, Viktor Olsson, Juliano Pinto, Lennart Svensson, WACV 2021|
|DecoupleNet | 59.1 | 57.0 | Decouple Feature Distribution Alignment | "[DecoupleNet: Decoupled Network for Domain Adaptive Semantic Segmentation](https://arxiv.org/pdf/2207.09988.pdf)", Xin Lai, Zhuotao Tian, Xiaogang Xu, Yingcong Chen, Shu Liu, Hengshuang Zhao, Liwei Wang, Jiaya Jia, ECCV 2022|
|HTCM | 58.8 | 57.8 |  Target Domain Pixel Cross-Domain Mixing | "[Exploring High-quality Target Domain Information for Unsupervised Domain Adaptive Semantic Segmentation](https://arxiv.org/pdf/2208.06100.pdf)", Junjie Li, Zilei Wang, Yuan Gao, Xiaoming Hu, 12/8/2022|
|ProDA + CRA | 58.6 | 56.9 | Adversarial Training in Target Domain | "[Cross-Region Domain Adaptation for Class-level Alignment](https://arxiv.org/pdf/2109.06422.pdf)", Zhijie Wang, Xing Liu, Masanori Suganuma, Takayuki Okatani, 14/9/2021|
|ProDA | 57.5 | 55.5 | Prototypical pseudo label denoising, (a popular baseline) | "[Prototypical Pseudo Label Denoising and Target Structure Learning for Domain Adaptive Semantic Segmentation](https://arxiv.org/pdf/2101.10979v2.pdf)", Pan Zhang, Bo Zhang, Ting Zhang, Dong Chen, Yong Wang, Fang Wen, CVPR 2021|

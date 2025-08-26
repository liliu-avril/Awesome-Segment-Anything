[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![arXiv](https://img.shields.io/badge/Paper-arXiv-2b9348.svg?logo=arXiv)](https://arxiv.org/abs/2305.08196)

# A Comprehensive Survey on Segment Anything Model for Vision and Beyond

> **The First Comprehensive SAM Survey: A Comprehensive Survey on Segment Anything Model for Vision and Beyond.** Chunhui Zhang, Li Liu, Yawen Cui, Guanjie Huang, Weilin Lin, Yiqian Yang, Yuehong Hu. [[paper](https://arxiv.org/abs/2305.08196)] [[homepage](https://github.com/liliu-avril/Awesome-Segment-Anything)][[中文解读](https://mp.weixin.qq.com/s/uYpRzvRp22-40x8e0pLVIg)] 

> **<p align="justify"> Abstract:** *Artificial intelligence (AI) is evolving towards artificial general intelligence, which refers to the ability of an AI system to perform a wide range of tasks and exhibit a level of intelligence similar to that of a human being. This is in contrast to narrow or specialized AI, which is designed to perform specific tasks with a high degree of efficiency. Therefore, it is urgent to design a general class of models, which we term foundation models, trained on broad data that can be adapted to various downstream tasks. The recently proposed segment anything model (SAM) has made significant progress in breaking the boundaries of segmentation, greatly promoting the development of foundation models for computer vision. To fully comprehend SAM, we conduct a survey study. As the first to comprehensively review the progress of segmenting anything task for vision and beyond based on the foundation model of SAM, this work focuses on its applications to various tasks and data types by discussing its historical development, recent progress, and profound impact on broad applications. We first introduce the background and terminology for foundation models including SAM, as well as state-of-the-art methods contemporaneous with SAM that are significant for segmenting anything task. Then, we analyze and summarize the advantages and limitations of SAM across various image processing applications, including software scenes, real-world scenes, and complex scenes. Importantly, many insights are drawn to guide future research to develop more versatile foundation models and improve the architecture of SAM. We also summarize massive other amazing applications of SAM in vision and beyond. Finally, we maintain a continuously updated paper list and an open-source project summary for foundation model SAM at [here](https://github.com/liliu-avril/Awesome-Segment-Anything).* </p>

> **Awesome Segment Anything Models:** A curated list of awesome segment anything models in computer vision and beyond. This repository supplements our survey paper. We intend to continuously update it.
#### If you like our project, please give us a star ⭐ on GitHub for latest update.

#### We strongly encourage authors of relevant works to make a pull request and add their paper's information [[here](https://docs.google.com/spreadsheets/d/1AdOc_mZrkKP7XoKL9g7YO4EEpjlxdxEDK2yOdRZ_edg/edit?usp=sharing)].

:boom:**[SAM 2](https://github.com/facebookresearch/segment-anything-2): Segment Anything in Images and Videos was released.**

:boom:**[The first survey on SAM & SAM2 for videos](https://github.com/983632847/SAM-for-Videos): Segment Anything for Videos: A Systematic Survey was online.**
____

## :fire: Highlights
![Last Updated](https://badgen.net/github/last-commit/liliu-avril/Awesome-Segment-Anything?icon=github&label=last%20updated&color=green)
```
- 2025.04.22: SAM2 won the ICLR 2025 Best Paper Honorable Mention.
- 2024.07.31: The first survey on SAM & SAM2 for Videos was online.
- 2024.07.29: The SAM 2 was released.
- 2023.07.14: "Segment Anything" was accepted by ICCV 2023 (Best Paper Honorable Mention).
- 2023.05.16: An initial version of this Awesome-Segment-Anything project.
- 2023.05.14: The first comprehensive SAM survey was online.
- 2023.04.05: The paper of "Segment Anything" was online.
```

## Contents
- [Survey](#survey)
- [Paper List](#paper-list) 
  - [Seminal Papers](#seminal-papers)
  - [Follow-up Papers ](#follow-up-papers)
    - [2025](#2025)
    - [2024](#2024)
    - [2023](#2023)
- [Open Source Projects](#open-source-projects)
- [Awesome Repositories for SAM](#awesome-repositories-for-sam)

## Citation

If you find our work useful in your research, please consider citing:
```
@article{zhang2023comprehensive,
  title={A Comprehensive Survey on Segment Anything Model for Vision and Beyond},
  author={Zhang, Chunhui and Liu, Li and Cui, Yawen and Huang, Guanjie and Lin, Weilin and Yang, Yiqian and Hu, Yuehong},
  journal={arXiv preprint arXiv:2305.08196},
  year={2023}
}

@article{zhang2024segment,
  title={Segment Anything for Videos: A Systematic Survey},
  author={Zhang, Chunhui and Cui, Yawen and Lin, Weilin and Huang, Guanjie and Rong, Yan and Liu, Li and Shan, Shiguang},
  journal={arXiv preprint arXiv:2408.08315},
  year={2024}
}
```

## Survey
- **The first comprehensive SAM survey:** Chunhui Zhang, Li Liu, Yawen Cui, Guanjie Huang, Weilin Lin, Yiqian Yang, Yuehong Hu.<br />
  "A Comprehensive Survey on Segment Anything Model for Vision and Beyond." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2305.08196)]
  [[homepage]](https://github.com/liliu-avril/Awesome-Segment-Anything)
  [[中文解读]](https://mp.weixin.qq.com/s/uYpRzvRp22-40x8e0pLVIg)
  [2023.05]

- **The first survey on SAM & SAM2 for Videos:** Chunhui Zhang, Yawen Cui, Weilin Lin, Guanjie Huang, Yan Rong, Li Liu, Shiguang Shan.<br />
  "Segment Anything for Videos: A Systematic Survey." ArXiv (2024).
[[ArXiv]](https://arxiv.org/abs/2408.08315) 
[[ChinaXiv]](https://chinaxiv.org/abs/202408.00019)
[[ResearchGate]](https://www.researchgate.net/publication/382737497_Segment_Anything_for_Videos_A_Systematic_Survey)
[[Project]](https://github.com/983632847/SAM-for-Videos)
[[中文解读]](https://zhuanlan.zhihu.com/p/712807912)
[2024.07]

- **SAM4MIS:** Yichi Zhang, Rushi Jiao.<br />
  "Towards Segment Anything Model (SAM) for Medical Image Segmentation: A Survey." CBM (2024).
  [[paper](https://arxiv.org/abs/2305.03678)] 
  [[project](https://github.com/YichiZhang98/SAM4MIS)]
  [2023.05]

- Yichi Zhang, Zhenrong Shen.<br />
  "Unleashing the Potential of SAM2 for Biomedical Images and Videos: A Survey." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.12889)] 
  [[code](https://github.com/YichiZhang98/SAM4MIS)]
  [2024.08]

- Tianfei Zhou, Fei Zhang, Boyu Chang, Wenguan Wang, Ye Yuan, Ender Konukoglu, Daniel Cremers.<br />
  "Image Segmentation in Foundation Model Era: A Survey." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.12957)] 
  [2024.08]

- Chaoning Zhang, Fachrina Dewi Puspitasari, Sheng Zheng, Chenghao Li, Yu Qiao, Taegoo Kang, Xinru Shan, Chenshuang Zhang, Caiyan Qin, Francois Rameau, Lik-Hang Lee, Sung-Ho Bae, Choong Seon Hong.<br />
  "A Survey on Segment Anything Model (SAM): Vision Foundation Model Meets Prompt Engineering." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2306.06211)] 
  [2023.05]

- Mudassar Ali and Tong Wu and Haoji Hu and Qiong Luo and Dong Xu and Weizeng Zheng and Neng Jin and Chen Yang and Jincao Yao.<br />
"A review of the Segment Anything Model (SAM) for medical image analysis: Accomplishments and perspectives." Computerized Medical Imaging and Graphics (2024).
[[paper](https://www.sciencedirect.com/science/article/pii/S0895611124001502)]
[2024.12]

- Zhang Jiaxing, Tang Hao.<br />
"SAM2 for Image and Video Segmentation: A Comprehensive Survey." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.12781)]
[2025.03]

- Kang Wang.<br />
"A survey on SAM-based methods for medical image segmentation." IS-AII (2025).
[[paper](https://doi.org/10.1117/12.3073583)]
[2025.07]

- Guoping Xu, Jayaram K. Udupa, Yajun Yu, Hua-Chieh Shao, Songlin Zhao, Wei Liu, You Zhang.<br />
"Segment Anything for Video: A Comprehensive Review of Video Object Segmentation and Tracking from Past to Future." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.22792)]
[2025.07]



## Paper List
### Seminal Papers
- **SAM:** Alexander Kirillov, Eric Mintun, Nikhila Ravi, Hanzi Mao, Chloe Rolland, Laura Gustafson, Tete Xiao, Spencer Whitehead, Alexander C. Berg, Wan-Yen Lo, Piotr Dollár, Ross Girshick.<br />
  "Segment Anything." **ICCV (2023) Best Paper Honorable Mention**.
  [[paper](https://arxiv.org/abs/2304.02643)] 
  [[homepage](https://segment-anything.com/)] 
  [[code](https://github.com/facebookresearch/segment-anything)]
  [[Zhihu](https://www.zhihu.com/question/593914819)]
  [[Reddit](https://www.reddit.com/r/singularity/comments/12cq56n/meta_ai_has_released_both_the_model_and_the/)]
  [2023.04]

- **SAM 2:** Nikhila Ravi∗,†, Valentin Gabeur∗, Yuan-Ting Hu∗, Ronghang Hu∗, Chaitanya Ryali∗, Tengyu Ma∗, Haitham Khedr∗, Roman Rädle∗  Chloe Rolland, Laura Gustafson, Eric Mintun, Junting Pan, Kalyan Vasudev Alwala, Nicolas Carion, Chao-Yuan Wu, Ross Girshick, Piotr Dollár†, Christoph Feichtenhofer∗,†.<br />
  "SAM 2: Segment Anything in Images and Videos." **ICLR (2025) Best Paper Honorable Mention**.
  [[paper](https://arxiv.org/abs/2408.00714)] 
  [[demo]](https://sam2.metademolab.com/)] 
  [[code](https://github.com/facebookresearch/segment-anything-2)]
  [[project]](https://ai.meta.com/sam2)]
  [[dataset](https://ai.meta.com/datasets/segment-anything-video)]
  [[blog](https://ai.meta.com/blog/segment-anything-2)] 
  [2024.07]


- **GPT-4V:** OpenAI.<br />
  "GPT-4V(ision) System Card." ArXiv (2023).
  [[paper](https://cdn.openai.com/papers/GPTV_System_Card.pdf)] 
  [[homepage](https://openai.com/research/gpt-4v-system-card)]
  [2023.09]

- **Gemini:** Gemini Team, Googl.<br />
  "Gemini: A Family of Highly Capable Multimodal Models." ArXiv (2023).
  [[paper](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf)] 
  [[homepage](https://blog.google/technology/ai/google-gemini-ai/#sundar-note)]
  [[blog](https://deepmind.google/technologies/gemini/#introduction)]
  [2023.12]

- **SEEM:** Xueyan Zou, Jianwei Yang, Hao Zhang, Feng Li, Linjie Li, Jianfeng Gao, Yong Jae Lee.<br />
  "Segment Everything Everywhere All at Once." NeurIPS (2023).
  [[paper](https://arxiv.org/abs/2304.06718)] 
  [[code](https://github.com/UX-Decoder/Segment-Everything-Everywhere-All-At-Once)]
  [2023.04]
  
- **SegGPT:** Xinlong Wang, Xiaosong Zhang, Yue Cao, Wen Wang, Chunhua Shen, Tiejun Huang.<br />
  "SegGPT: Segmenting Everything In Context." ICCV (2023).
  [[paper](https://arxiv.org/abs/2304.03284)] 
  [[code](https://github.com/baaivision/Painter)]
  [2023.04]

- **Grounding DINO:** Shilong Liu, Zhaoyang Zeng, Tianhe Ren, Feng Li, Hao Zhang, Jie Yang, Chunyuan Li, Jianwei Yang, Hang Su, Jun Zhu, Lei Zhang.<br />
  "Grounding DINO: Marrying DINO with Grounded Pre-Training for Open-Set Object Detection." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2303.05499)] 
  [[code]( https://github.com/IDEA-Research/GroundingDINO)]
  [2023.04]
  
- **ImageBind:** Rohit Girdhar, Alaaeldin El-Nouby, Zhuang Liu, Mannat Singh, Kalyan Vasudev Alwala, Armand Joulin, Ishan Misra.<br />
  "ImageBind: One Embedding Space To Bind Them All." CVPR (2023).
  [[paper](https://arxiv.org/abs/2305.05665)] 
  [[homepage](https://imagebind.metademolab.com/)] 
  [[code](https://github.com/facebookresearch/ImageBind)]
  [2023.05]

- **LanguageBind:** Bin Zhu, Bin Lin, Munan Ning, Yang Yan, Jiaxi Cui, HongFa Wang, Yatian Pang, Wenhao Jiang, Junwu Zhang, Zongwei Li, Wancai Zhang, Zhifeng Li, Wei Liu, Li Yuan.<br />
  "LanguageBind: Extending Video-Language Pretraining to N-modality by Language-based Semantic Alignment." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.01852)] 
  [[code](https://github.com/PKU-YuanGroup/LanguageBind)]

- **Meta-Transformer:** Yiyuan Zhang, Kaixiong Gong, Kaipeng Zhang, Hongsheng Li, Yu Qiao, Wanli Ouyang, Xiangyu Yue.<br />
  "Meta-Transformer: A Unified Framework for Multimodal Learning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.10802)] 
  [[homepage](https://github.com/invictus717/MetaTransformer)]
  [[code](https://github.com/invictus717/MetaTransformer)]
  [[中文解读](https://mp.weixin.qq.com/s/r38bzqdJxDZUvtDI0c9CEw?poc_token=HJBW1GSjrlLI_fXbnZeCfAefBIyL3OT0__QH-hfc)]
  [2023.07]

- **OpenSeeD:** Hao Zhang, Feng Li, Xueyan Zou, Shilong Liu, Chunyuan Li, Jianfeng Gao, Jianwei Yang, Lei Zhang.<br />
  "A Simple Framework for Open-Vocabulary Segmentation and Detection." ICCV (2023).
  [[paper](https://arxiv.org/abs/2303.08131)] 
  [[code](https://github.com/IDEA-Research/OpenSeeD)]
  [2023.03]
 
- **RAM:** Youcai Zhang, Xinyu Huang, Jinyu Ma, Zhaoyang Li, Zhaochuan Luo, Yanchun Xie, Yuzhuo Qin, Tong Luo, Yaqian Li, Shilong Liu, Yandong Guo, Lei Zhang.<br />
  "Recognize Anything: A Strong Image Tagging Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.03514)] 
  [[homepage](https://recognize-anything.github.io/)] 
  [[code](https://github.com/xinyu1205/Recognize_Anything-Tag2Text)]
  [2023.06]

- **PACGen:** Yuheng Li, Haotian Liu, Yangming Wen, Yong Jae Lee.<br />
  "Generate Anything Anywhere in Any Scene." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.17154)] 
  [[homepage](https://github.com/Yuheng-Li/PACGen)] 
  [[code](https://yuheng-li.github.io/PACGen/)]
  [2023.06]

- **ASM:** Weiyun Wang, Min Shi, Qingyun Li, Wenhai Wang, Zhenhang Huang, Linjie Xing, Zhe Chen, Hao Li, Xizhou Zhu, Zhiguo Cao, Yushi Chen, Tong Lu, Jifeng Dai, Yu Qiao.<br />
  "The All-Seeing Project: Towards Panoptic Visual Recognition and Understanding of the Open World." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.01907)] 
  [[homepage](https://github.com/OpenGVLab/All-Seeing)] 
  [[demo](https://huggingface.co/spaces/OpenGVLab/all-seeing)]
  [2023.08]

- **OneFormer:** Jitesh Jain, Jiachen Li, MangTik Chiu, Ali Hassani, Nikita Orlov, Humphrey Shi.<br />
  "OneFormer: One Transformer to Rule Universal Image Segmentation." CVPR (2023).
  [[paper]( https://arxiv.org/abs/2211.06220)] 
  [[homepage](https://praeclarumjj3.github.io/oneformer)] 
  [[code](https://github.com/SHI-Labs/OneFormer)]
  [2022.11]
  
- **OVSeg:** Feng Liang, Bichen Wu, Xiaoliang Dai, Kunpeng Li, Yinan Zhao, Hang Zhang, Peizhao Zhang, Peter Vajda, Diana Marculescu.<br />
  "Open-Vocabulary Semantic Segmentation with Mask-adapted CLIP." CVPR (2023).
  [[paper](https://arxiv.org/abs/2210.04150)] 
  [[homepage]( https://jeff-liangf.github.io/projects/ovseg/)] 
  [[code](https://github.com/facebookresearch/ov-seg)]
  [2022.10]

- **WAM:** Tom Sander, Pierre Fernandez, Alain Durmus, Teddy Furon, Matthijs Douze.<br />
"Watermark Anything with Localized Messages." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.07231)]
[[code](https://github.com/facebookresearch/watermark-anything)]
[2024.11]

- **Sa2VA:** Haobo Yuan, Xiangtai Li, Tao Zhang, Zilong Huang, Shilin Xu, Shunping Ji, Yunhai Tong, Lu Qi, Jiashi Feng, Ming-Hsuan Yang.<br />
"Sa2VA: Marrying SAM2 with LLaVA for Dense Grounded Understanding of Images and Videos." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.04001)]
[[code](https://github.com/magic-research/Sa2VA)]
[[project](https://lxtgh.github.io/project/sa2va)]
[[hugging face](https://huggingface.co/ByteDance/Sa2VA-8B)]
[2025.01]

- **DAM:** Long Lian, Yifan Ding, Yunhao Ge, Sifei Liu, Hanzi Mao, Boyi Li, Marco Pavone, Ming-Yu Liu, Trevor Darrell, Adam Yala, Yin Cui.<br />
"Describe Anything: Detailed Localized Image and Video Captioning." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.16072)]
[[code](https://github.com/NVlabs/describe-anything)]
[[project](https://describe-anything.github.io/)]
[[huggingface](https://huggingface.co/collections/nvidia/describe-anything-680825bb8f5e41ff0785834c)]
[2025.04]

- **DINOv3:** Oriane Siméoni, Huy V. Vo, Maximilian Seitzer, Federico Baldassarre, Maxime Oquab, Cijo Jose, Vasil Khalidov, Marc Szafraniec, Seungeun Yi, Michaël Ramamonjisoa, Francisco Massa, Daniel Haziza, Luca Wehrstedt, Jianyuan Wang, Timothée Darcet, Théo Moutakanni, Leonel Sentana, Claire Roberts, Andrea Vedaldi, Jamie Tolan, John Brandt, Camille Couprie, Julien Mairal, Hervé Jégou, Patrick Labatut, Piotr Bojanowski.<br />
"DINOv3." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.10104)]
[[code](https://github.com/facebookresearch/dinov3)]
[2025.08]


### Follow-up Papers
#### The latest papers within a week are marked with a :boom:
#### 2025
:boom:**DeH4R:** Dengxian Gong, Shunping Ji.<br />
"DeH4R: A Decoupled and Hybrid Method for Road Network Graph Extraction." ArXiv (2025).
[[paper](https://www.arxiv.org/abs/2508.13669)]
[[code](https://github.com/7777777FAN/DeH4R)]
[2025.08]

:boom:**SAMDWICH:** Seunghun Lee, Jiwan Seo, Jeonghoon Kim, Siwon Kim, Haeun Yun, Hyogyeong Jeon, Wonhyeok Choi, Jaehoon Jeong, Zane Durante, Sang Hyun Park, Sunghoon Im.<br />
"SAMDWICH: Moment-aware Video-text Alignment for Referring Video Object Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.11955)]
[[project](https://seung-hun-lee.github.io/projects/SAMDWICH/)]
[[code](https://github.com/Seung-Hun-Lee/SAMDWICH)]
[2025.08]

:boom:**Q-MiniSAM2:** Xuanxuan Ren , Xiangyu Li , Kun Wei , Xu Yang , Yanhua Yang.<br />
"Q-MiniSAM2: A Quantization-based Benchmark for Resource-Efficient Video Segmentation." IJCAI (2025).
[[paper](https://ijcai-preprints.s3.us-west-1.amazonaws.com/2025/2112.pdf)]
[2025.08]

:boom:**ODS-SAM:** Chao Huang et al.<br />
"Omni-Dimensional State Space Model-driven SAM for Pixel-level Anomaly Detection." IJCAI (2025).
[[paper](https://ijcai-preprints.s3.us-west-1.amazonaws.com/2025/6311.pdf)]
[2025.08]

:boom:**DenseSAM:** Linyun Zhou et al.<br />
"DenseSAM: Semantic Enhance SAM For Efficient Dense Object Segmentation." IJCAI (2025).
[[paper](https://ijcai-preprints.s3.us-west-1.amazonaws.com/2025/3133.pdf)]
[[code](https://github.com/imAzhou/DenseSAM)]
[2025.08]

:boom:**PG-SAM:** Hadee Madadum,  Fazal E Nasir, Kanjana Haruehansapong.<br />
"Optimizing Watermelon Leaf Disease Detection Using SAM-based Augmentation with YOLO for Practical Agricultural Solutions." Smart Agricultural Technology (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S277237552500557X)]
[2025.08]

:boom:**ShadowCraft-Nerf:** Xun Chen et al.<br />
"ShadowCraft-Nerf: Occlusion and Shadow Mitigation via SAM-Guided Nerf." CASA (2025).
[[paper](https://books.google.com.hk/books?hl=zh-CN&lr=&id=9qh-EQAAQBAJ&oi=fnd&pg=PA93&ots=c6sYGYyArX&sig=tHNgp8kDDnuQlFYQtyGtFoU7aTw&redir_esc=y#v=onepage&q&f=false)]
[2025.08]

:boom:**SAM2Med3D:** Ying Chen and Wenjing Cui and Xiaoyan Dong and Shuai Zhou and Zhongqiu Wang.<br />
"SAM2Med3D: Leveraging video foundation models for 3D breast MRI segmentation." Computers & Graphics (2025).
[[paper](https://doi.org/10.1016/j.cag.2025.104341)]
[2025.08]

:boom:Huang, X., Long, A., Han, W., Chen, Y., Min, G., & Yan, D.<br />
"A segment anything model-based geological remote sensing interpretation method with a distributed data-parallel deep learning framework."  International Journal of Digital Earth (2025).
[[paper](https://www.tandfonline.com/doi/full/10.1080/17538947.2025.2542913)]
[2025.08]

:boom:**MFB-SAC:** Xutao Sun et al.<br />
"MFB-SAC: A Multi-Scale Frequency and Boundary-Enhanced SAM for Cell Segmentation." ICIP (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/11084537)]
[[code](https://github.com/Mrliujunwen/SAC)]
[2025.08]

:boom:**Self-TrainingSAM:** Mauricio Fernandez M. et al.<br />
"SAM 2-Driven Self-Training for Mammogram Segmentation: Zero-Shot Mask Generation Via Pseudo-Video." ICIP (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/11084376)]
[[code](https://github.com/MauricioFernandezM/Self-TrainingSAM)]
[2025.08]

:boom:**PAL-SAM:** Christopher Bunn et al.<br />
"Re-Purposing Segment Anything For Skeleton Action Localization." ICIP (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/11084482)]
[2025.08]

:boom:**subCellSAM:** Jacob Hanimann, Daniel Siegismund, Mario Wieser, Stephan Steigele.<br />
"subCellSAM: Zero-Shot (Sub-)Cellular Segmentation for Hit Validation in Drug Discovery." GCPR (2025).
[[paper](https://arxiv.org/abs/2508.13701)]
[2025.08]

- **Lang2Lift:** Huy Hoang Nguyen, Johannes Huemer, Markus Murschitz, Tobias Glueck, Minh Nhat Vu, Andreas Kugi.<br />
"Lang2Lift: A Framework for Language-Guided Pallet Detection and Pose Estimation Integrated in Autonomous Outdoor Forklift Operation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.15427)]
[[code](https://eric-nguyen1402.github.io/lang2lift.github.io/)]
[2025.08]

- **All-in-SAM:** Xueyuan Li, Can Cui, Ruining Deng, Yucheng Tang, Quan Liu, Tianyuan Yao, Shunxing Bao, Naweed Chowdhury, Haichun Yang, Yuankai Huo.<br />
"Fine-grained Multi-class Nuclei Segmentation with Molecular-empowered All-in-SAM Model." Journal of Medical Imaging(2025).
[[paper](https://arxiv.org/abs/2508.15751)]
[2025.08]

- **RAG-SEG:** Wutao Liu, YiDan Wang, Pan Gao.<br />
"First RAG, Second SEG: A Training-Free Paradigm for Camouflaged Object Detection." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.15313)]
[2025.08]

- **TOM:**  Jiacheng Xie, Ziyang Zhang, Biplab Poudel, Congyu Guo, Yang Yu, Guanghui An, Xiaoting Tang, Lening Zhao, Chunhui Xu, Dong Xu.<br />
"TOM: An Open-Source Tongue Segmentation Method with Multi-Teacher Distillation and Task-Specific Data Augmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.14932)]
[[code](https://itongue.cn/)]
[2025.08]

- **EASSA:** Wang, Jinghan and Cao, Zhen and Fu, Shiyang and Kang, Zhizhong and Wang, Jingyi.<br />
"A Novel Flexible Architecture Based on SAM for Automatic Exraction of Rampart Craters From Martian High Resolution Images." IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/11122573)]
[2025.08]

- **UGCA:** Haowen Pang, Xiaoming Hong, Peng Zhang & Chuyang Ye.<br />
"Cascaded Diffusion Model and Segment Anything Model for Medical Image Synthesis via Uncertainty-Guided Prompt Generation." IPMI (2025).
[[paper](https://doi.org/10.1007/978-3-031-96628-6_14)]
[2025.08]

- **MSAM:** Xing, Jiezhen, and Jicong Zhang.<br />
"Segmentation of Brain Tumors Using a Multi-Modal Segment Anything Model (MSAM) with Missing Modality Adaptation." Bioengineering (2025).
[[paper](https://doi.org/10.3390/bioengineering12080871)]
[2025.08]

- **Co2SAM:** Liu, Chunmeng and Shen, Yao and Zhou, Haoran and Xiao, Qingguo and Chen, Qiaochuan and Li, Guangyao.<br />
"Co2SAM: Exploring Co-occurrence Challenges With SAM in Weakly Supervised Semantic Segmentation." IEEE Internet of Things Journal (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/11124587)]
[[code](https://github.com/chunmengliu666/Co2SAM)]
[2025.08]

- **CD-SAM:** Guowei Zheng and Pengbo Bo and Songhua Xu and Linqin Wang and Zhaoyang Cong and Liangliang Liu and Ziyang Zhao and Caiming Zhang.<br />
"Enhancing Segment Anything Model with spatial context and textural detail for cardiac MRI segmentation." Biomedical Signal Processing and Control(2025).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S1746809425009486)]
[[code](https://github.com/LZUzgw/CD-SAM)]
[2025.08]

- **LENS:** Lianghui Zhu, Bin Ouyang, Yuxuan Zhang, Tianheng Cheng, Rui Hu, Haocheng Shen, Longjin Ran, Xiaoxin Chen, Li Yu, Wenyu Liu, Xinggang Wang.<br />
"LENS: Learning to Segment Anything with Unified Reinforced Reasoning." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.14153)]
[[code](https://github.com/hustvl/LENS)]
[2025.08]

- **GeoSAM2:** Ken Deng, Yunhan Yang, Jingxiang Sun, Xihui Liu, Yebin Liu, Ding Liang, Yan-Pei Cao.<br />
"GeoSAM2: Unleashing the Power of SAM2 for 3D Part Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.14036)]
[[code](https://detailgen3d.github.io/GeoSAM2/)]
[2025.08]

- **InstDrive:** Hongyuan Liu, Haochen Yu, Jianfei Jiang, Qiankun Liu, Jiansheng Chen, Huimin Ma.<br />
"InstDrive: Instance-Aware 3D Gaussian Splatting for Driving Scenes." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.12015)]
[2025.08]

- **CoFi:** Hongjin Fang, Daniel Reisenbüchler, Kenji Ikemura, Mert R. Sabuncu, Yihe Yang, Ruining Deng.<br />
"CoFi: A Fast Coarse-to-Fine Few-Shot Pipeline for Glomerular Basement Membrane Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.11469)]
[[code](https://github.com/ddrrnn123/CoFi)]
[2025.08]

- Cesar Alan Contreras, Manolis Chiou, Alireza Rastegarpanah, Michal Szulik, Rustam Stolkin.<br />
"Utilizing Vision-Language Models as Action Models for Intent Recognition and Assistance." IEEE RO-MAN (2025).
[[paper](https://arxiv.org/abs/2508.11093)]
[2025.08]

- **MedSAMix:** Yanwu Yang, Guinan Su, Jiesi Hu, Francesco Sammarco, Jonas Geiping, Thomas Wolfers.<br />
"MedSAMix: A Training-Free Model Merging Approach for Medical Image Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.11032)]
[2025.08]

- **Bolt-SAM:** Yangjie Xiao, Ke Zhang, Jiacun Wang, Xin Sheng, Yurong Guo, Meijuan Chen, Zehua Ren, Zhaoye Zheng, Zhenbing Zhao.<br />
"A Segmentation-driven Editing Method for Bolt Defect Augmentation and Detection." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.10509)]
[[code](https://github.com/Jay-xyj/SBDE)]
[2025.08]

- **SAM-CEM-CD:** Humza Naveed, Xina Zeng, Mitch Bryson, Nagita Mehrseresht.<br />
"Adapting SAM via Cross-Entropy Masking for Class Imbalance in Remote Sensing Change Detection." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.10568)]
[[code](https://github.com/humza909/SAM-CEM-CD)]
[2025.08]

- **PG-SAM:** Zhongyuan Wu, Chuan-Xian Ren, Yu Wang, Xiaohua Ban, Jianning Xiao, Xiaohui Duan.<br />
"Multi-Sequence Parotid Gland Lesion Segmentation via Expert Text-Guided Segment Anything Model." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.09645)]
[2025.08]

- **SegDAC:** Alexandre Brown, Glen Berseth.<br />
"SegDAC: Segmentation-Driven Actor-Critic for Visual Reinforcement Learning." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.09325)]
[[code](https://segdac.github.io/)]
[2025.08]

- **AutoSAME:** Tuo Liu, Qinghan Yang, Yu Zhang, Rongjun Ge, Yang Chen, Guangquan Zhou.<br />
"Think as Cardiac Sonographers: Marrying SAM with Left Ventricular Indicators Measurements According to Clinical Guidelines." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.08566)]
[[code](https://github.com/QC-LIU-1997/AutoSAME)]
[2025.08]

- **RSFIQA:** Chenyue Song, Chen Hui, Haiqi Zhu, Feng Jiang, Yachun Mi, Wei Zhang, Shaohui Liu.<br />
"Segmenting and Understanding: Region-aware Semantic Attention for Fine-grained Image Quality Assessment with Large Language Models." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.07818)]
[2025.08]

- **CAV-SAM:** Haoran Wang, Zekun Li, Jian Zhang, Lei Qi, Yinghuan Shi.<br />
"Correspondence as Video: Test-Time Adaption on SAM2 for Reference Segmentation in the Wild." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.07759)]
[[code](https://github.com/wanghr64/cav-sam)]
[2025.08]

- **CLUE:** Youqi Wang, Shunquan Tan, Rongxuan Peng, Bin Li, Jiwu Huang.<br />
"CLUE: Leveraging Low-Rank Adaptation to Capture Latent Uncovered Evidence for Image Forgery Localization." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.07413)]
[[code](https://github.com/SZAISEC/CLUE)]
[2025.08]

- **ForensicsSAM:** Rongxuan Peng, Shunquan Tan, Chenqi Kong, Anwei Luo, Alex C. Kot, Jiwu Huang.<br />
"ForensicsSAM: Toward Robust and Unified Image Forgery Detection and Localization Resisting to Adversarial Attack." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.07402)]
[[code](https://github.com/siriusPRX/ForensicsSAM)]
[2025.08]

- **S2-UniSeg:** Huihui Xu, Jin Ye, Hongqiu Wang, Changkai Ji, Jiashi Lin, Ming Hu, Ziyan Huang, Ying Chen, Chenglong Ma, Tianbin Li, Lihao Liu, Junjun He, Lei Zhu.<br />
"S2-UniSeg: Fast Universal Agglomerative Pooling for Scalable Segment Anything without Supervision." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.06995)]
[[code](https://github.com/bio-mlhui/S2-UniSeg)]
[2025.08]

- **IAPF:** Chao Yin, Jide Li, Xiaoqiang Li.<br />
"A Simple yet Powerful Instance-Aware Prompting Framework for Training-free Camouflaged Object Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.06904)]
[[code](https://github.com/ycyinchao/RDVP-MSD)]
[2025.08]

- **SAGOnline:** Wentao Sun, Quanyun Wu, Hanqing Xu, Kyle Gao, Zhengsen Xu, Yiping Chen, Dedong Zhang, Lingfei Ma, John S. Zelek, Jonathan Li.<br />
"SAGOnline: Segment Any Gaussians Online." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.08219)]
[2025.08]

- **SAM-Med3D:** Wang, Haoyu and Guo, Sizheng and Ye, Jin and Deng, Zhongying and Cheng, Junlong and Li, Tianbin and Chen, Jianpin and Su, Yanzhou and Huang, Ziyan and Shen, Yiqing and Fu, Bin and Zhang, Shaoting and He, Junjun.<br />
"SAM-Med3D: A Vision Foundation Model for General-Purpose Segmentation on Volumetric Medical Images." TNNLS (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/11105528/)]
[[code](https://github.com/uni-medical/SAM-Med3D)]
[2025.08]

- **AP-SAM:** Peigang Liu and Peijie Wang and Chaozhi Yang and Honghao Dong and Jing Ma and Zongmin Li.<br />
"Automatic pore structure analysis of mudstone and shale in hydrocarbon-rich areas using SEM images and AP-SAM." Fuel (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S0016236125020915)]
[2025.08]

- **AP-SAM:** Feng, Yunjian and Li, Jun.<br />
"Auto-Prompting SAM for Container Detection and Localization in Container Yards." TITS (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/11098671)]
[2025.08]

- Y. Xia et al.<br />
"Box-Prompt Zero-Shot Smart Segmentation in Radiation Oncology Using a SAM-Based Model: SmartSAM." AAPM (2025).
[[paper](file:///C:/Users/p1/Desktop/Yuqing%20Xia%20Poster_AAPM.pdf)]
[2025.08]

- Chenxiao Zhang and Peng Yue.<br />
"Toward unsupervised building extraction from very high-resolutionremote sensing images using SAM and CLIP." GIScience & Remote Sensing (2025).
[[paper](https://doi.org/10.1080/15481603.2025.2543102)]
[2025.08]

- **ScribbleSAM:** Tae Hun Lee , Jae Yeol Lee.<br />
"ScribbleSAM: Weakly supervised salient object detection and localization in remote sensing images using Transformer and Segment Anything Model." Journal of Computational Design and Engineering (2025).
[[paper](https://academic.oup.com/jcde/advance-article/doi/10.1093/jcde/qwaf081/8222498?login=false)]
[2025.08]

- **2AM:** Ren, Chenyu, Liwen Zou, and Luying Gui.<br />
"2AM: Weakly Supervised Tumor Segmentation in Pathology via CAM and SAM Synergy." Electronics (2025).
[[paper](https://doi.org/10.3390/electronics14153109)]
[2025.08]

- Ying Qu.<br />
"Attitude Estimation for Cardan-Connected End-Effector of an Underwater Robot by Integrating SAM-based Segmentation and Neural Network." ICECET (2025).
[[paper](https://portal.findresearcher.sdu.dk/en/publications/attitude-estimation-for-cardan-connected-end-effector-of-an-under)]
[2025.08]

- Rajesh Bhayana, Bo Wang.<br />
"Segment Anything in the Ovary: Toward Scalable AI-assisted Lesion Classification." Radiology (2025).
[[paper](https://pubs.rsna.org/doi/abs/10.1148/radiol.252185?journalCode=radiology)]
[2025.08]

- **Vessel-SAM2:** Zihuang Wu and Xinyu Xiong.<br />
"Vessel-SAM2: Adapting Segment Anything 2 for Patch-Free Retinal Vessel Segmentation in Ultra-High Resolution Fundus Images." IEEE Sensors Letters (2025).
[[paper](https://ieeexplore.ieee.org/document/11107345)]
[2025.08]

- **TFSeg:** He, Jiaqi and Li, Haofeng and Yang, Liang and Chen, Bohui.<br />
"Training-Free Breast Ultrasound Image Segmentation with Retrieval-based SAM2." IEEE Transactions on Biomedical Engineering (2025).
[[paper](https://ieeexplore.ieee.org/document/11113315)]
[2025.08]

- **BCTDNet:** Zhang, Wei, Jinsong Li, Shuaipeng Wang, and Jianhua Wan.<br />
"BCTDNet: Building Change-Type Detection Networks with the Segment Anything Model in Remote Sensing Images." Remote Sensing (2025).
[[paper](https://doi.org/10.3390/rs17152742)]
[2025.08]
- **Prompt-DINO:** Yuchen Guan, Chong Sun, Canmiao Fu, Zhipeng Huang, Chun Yuan, Chen Li.<br />
"Text-guided Visual Prompt DINO for Generic Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.06146)]
[[code](https://github.com/WeChatCV/WeVisionOne)]
[2025.08]

- **VeSCA:** Yi Qin, Rui Wang, Tao Huang, Tong Xiao, Liping Jing.<br />
"SAM Encoder Breach by Adversarial Simplicial Complex Triggers Downstream Model Failures." ICCV(2025).
[[paper](https://arxiv.org/abs/2508.06127)]
[[code](https://github.com/Seveone/SAM_VeSCA.)]
[2025.08]

- Sri Ramana Saketh Vasanthawada, Pengkun Liu, Pingbo Tang.<br />
"Enhancing Construction Site Analysis and Understanding with 3D Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.05922)]
[2025.08]

- Ahmad Farooq, Kamran Iqbal.<br />
"Integrating Vision Foundation Models with Reinforcement Learning for Enhanced Object Interaction." RCVE(2025).
[[paper](https://arxiv.org/abs/2508.05838)]
[2025.08]

- **TSMS-SAM2:** Guoping Xu, Hua-Chieh Shao, You Zhang.<br />
"TSMS-SAM2: Multi-scale Temporal Sampling Augmentation and Memory-Splitting Pruning for Promptable Video Object Segmentation and Tracking in Surgical Scenarios." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.05829)]
[[code](https://github.com/apple1986/TSMS-SAM2)]
[2025.08]

- Ojonugwa Oluwafemi Ejiga Peter, Akingbola Oluwapemiisin, Amalahu Chetachi, Adeniran Opeyemi, Fahmi Khalifa, Md Mahmudur Rahman.<br />
"Synthetic Data-Driven Multi-Architecture Framework for Automated Polyp Segmentation Through Integrated Detection and Mask Generation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.06170)]
[2025.08]

- **SGDFuse:** Xiaoyang Zhang, Zhen Hua, Yakun Ju, Wei Zhou, Jun Liu, Alex C. Kot.<br />
"SGDFuse: SAM-Guided Diffusion for High-Fidelity Infrared and Visible Image Fusion." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.05264)]
[[code](https://github.com/boshizhang123/SGDFuse)]
[2025.08]

- **SMOL-MapSeg:** Yunshuang Yuan, Frank Thiemann, Thorsten Dahms, Monika Sester.<br />
"SMOL-MapSeg: Show Me One Label." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.05501)]
[2025.08]

- Semanur Küçük, Cosimo Della Santina, Angeliki Laskari.<br />
"Segmenting the Complex and Irregular in Two-Phase Flows: A Real-World Empirical Study with SAM2." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.05227)]
[2025.08]

- **DecoupleCSS:** Yifu Guo, Yuquan Lu, Wentao Zhang, Zishan Xu, Dexia Chen, Siyu Zhang, Yizhe Zhang, Ruixuan Wang.<br />
"Decoupling Continual Semantic Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.05065)]
[[code](https://github.com/euyis1019/Decoupling-Continual-Semantic-Segmentation)]
[2025.08]

- **TGS-Agent:** Jinxing Zhou, Yanghao Zhou, Mingfei Han, Tong Wang, Xiaojun Chang, Hisham Cholakkal, Rao Muhammad Anwer.<br />
"Think Before You Segment: An Object-aware Reasoning Agent for Referring Audio-Visual Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.04418)]
[[code](https://github.com/jasongief/TGS-Agent)]
[2025.08]

- **X-SAM:** Hao Wang, Limeng Qiao, Zequn Jie, Zhijian Huang, Chengjian Feng, Qingfang Zheng, Lin Ma, Xiangyuan Lan, Xiaodan Liang.<br />
"X-SAM: From Segment Anything to Any Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.04655)]
[[code](https://github.com/wanghao9610/X-SAM)]
[2025.08]

- **Edge2Prompt:** Nathan Hollet, Oumeymah Cherkaoui, Philippe C. Cattin, Sidaty El hadramy.<br />
"Edge2Prompt: Modality-Agnostic Model for Out-of-Distribution Liver Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.04305)]
[2025.08]

- **SAV:** Xiao Wang, Ziwen Wang, Wentao Wu, Anjie Wang, Jiashu Wu, Yantao Pan, Chenglong Li.<br />
"Segment Any Vehicle: Semantic and Visual Context Driven SAM and A Benchmark." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.04260)]
[[code](https://github.com/Event-AHU/SAV)]
[2025.08]

- **MLLMSeg:** Jingchao Wang, Zhijian Wu, Dingjiang Huang, Yefeng Zheng, Hong Wang.<br />
"Unlocking the Potential of MLLMs in Referring Expression Segmentation via a Light-weight Mask Decode." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.04107)]
[[code](https://github.com/jcwang0602/MLLMSeg)]
[2025.08]

- **RAP-SAM:** Shilin Xu, Haobo Yuan, Qingyu Shi, Lu Qi, Jingbo Wang, Yibo Yang, Yining Li, Kai Chen, Yunhai Tong, Bernard Ghanem, Xiangtai Li, Ming-Hsuan Yang.<br />
"RMP-SAM: Towards Real-Time Multi-Purpose Segment Anything." ICLR (2025).
[[paper](https://arxiv.org/abs/2401.10228)]
[[code](https://github.com/xushilin1/RAP-SAM)]
[2025.08]

- **ParticleSAM:** Yu Zhou, Pelle Thielmann, Ayush Chamoli, Bruno Mirbach, Didier Stricker, Jason Rambach.<br />
"ParticleSAM: Small Particle Segmentation for Material Quality Monitoring in Recycling Processes." EUSIPCO(2025).
[[paper](https://arxiv.org/abs/2508.03490)]
[2025.08]

- **SAM2-UNeXT:** Xinyu Xiong, Zihuang Wu, Lei Zhang, Lei Lu, Ming Li, Guanbin Li.<br />
"SAM2-UNeXT: An Improved High-Resolution Baseline for Adapting Foundation Models to Downstream Segmentation Tasks." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.03566)]
[[code](https://github.com/WZH0120/SAM2-UNeXT)]
[2025.08]

- **MAUP:** Yazhou Zhu, Haofeng Zhang.<br />
"MAUP: Training-free Multi-center Adaptive Uncertainty-aware Prompting for Cross-domain Few-shot Medical Image Segmentation." MICCAI (2025).
[[paper](https://arxiv.org/abs/2508.03511)]
[[code](https://github.com/YazhouZhu19/MAUP)]
[2025.08]

- Freida Barnatan, Emunah Goldstein, Einav Kalimian, Orchen Madar, Avi Huri, David Zitoun, Ya'akov Mandelbaum, Moshe Amitay.<br />
"Zero-shot Shape Classification of Nanoparticles in SEM Images using Vision Foundation Models." ArXiv (2025).

- **MFNet:** Ma, Xianping and Zhang, Xiaokang and Pun, Man-On and Huang, Bo.<br />
"A Unified Framework with Multimodal Fine-tuning for Remote Sensing Semantic Segmentation." TGRS (2025).
[[paper](https://ieeexplore.ieee.org/document/11063320)]
[[code](https://github.com/sstary/SSRS)]
[2025.08]

- **SAMPO:** Yonghuang Wu, Wenwen Zeng, Xuan Xie, Chengqian Zhao, Guoqing Wu, Jinhua Yu.<br />
"SAMPO: Visual Preference Optimization for Intent-Aware Segmentation with Vision Foundation Models." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.02464)]
[2025.08]

- Kumail Abbas, Zeeshan Afzal, Aqeel Raza, Taha Mansouri, Andrew W. Dowsey, Chaidate Inchaisri, Ali Alameer.<br />
"Vision transformer-based multi-camera multi-object tracking framework for dairy cow monitoring." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.01752)]
[2025.08]

- **PromptReg:** Shiqi Huang, Tingfa Xu, Wen Yan, Dean Barratt, Yipeng Hu.<br />
"Register Anything: Estimating "Corresponding Prompts" for Segment Anything Model." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.01697)]
[2025.08]

- **Rein++:** Zhixiang Wei, Xiaoxiao Ma, Ruishen Yan, Tao Tu, Huaian Chen, Jinjin Zheng, Yi Jin, Enhong Chen.<br />
"Rein++: Efficient Generalization and Adaptation for Semantic Segmentation with Vision Foundation Models." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.01667)]
[[code](https://github.com/wloves/Rein)]
[2025.08]

- **VELA:** Zhixuan Li, Yujia Liu, Chen Hui, Weisi Lin.<br />
"Single Point, Full Mask: Velocity-Guided Level Set Evolution for End-to-End Amodal Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.01661)]
[2025.08]

- Yang Liu, Muzhi Zhu, Hao Chen, Xinlong Wang, Bo Feng, Hao Wang, Shiyu Li, Raviteja Vemulapalli & Chunhua Shen .<br />
"Segment Anything in Context with Vision Foundation Models." IJCV (2025).
[[paper](https://link.springer.com/article/10.1007/s11263-025-02517-0)]
[2025.08]

- **SAMSA 2.0:** Alfie Roddan, Tobias Czempiel, Chi Xu, Daniel S. Elson, Stamatia Giannarou.<br />
"SAMSA 2.0: Prompting Segment Anything with Spectral Angles for Hyperspectral Interactive Medical Image Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.00493)]
[2025.08]

- **Omni-Scan:** Tianshuang Qiu, Zehan Ma, Karim El-Refai, Hiya Shah, Chung Min Kim, Justin Kerr, Ken Goldberg.<br />
"Omni-Scan: Creating Visually-Accurate Digital Twin Object Models Using a Bimanual Robot with Handover and Gaussian Splat Merging ." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.00354)]
[[code](https://berkeleyautomation.github.io/omni-scan/)]
[2025.08]

- Aymane Abdali, Bartosz Boguslawski, Lucas Drumetz, Vincent Gripon.<br />
"Object-Centric Cropping for Visual Few-Shot Classification." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.00218)]
[2025.08]

- **SAM-PTx:** Shayan Jalilian, Abdul Bais.<br />
"SAM-PTx: Text-Guided Fine-Tuning of SAM with Parameter-Efficient, Parallel-Text Adapters." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.00213)]
[2025.08]

- **SAMSA:** Alfie Roddan, Tobias Czempiel, Chi Xu, Daniel S. Elson, Stamatia Giannarou.<br />
"SAMSA: Segment Anything Model Enhanced with Spectral Angles for Hyperspectral Interactive Medical Image Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.23673)]
[2025.07]

- **ST-SAM:** Xihang Hu, Fuming Sun, Jiazhe Liu, Feilong Xu, Xiaoli Zhang.<br />
"ST-SAM: SAM-Driven Self-Training Framework for Semi-Supervised Camouflaged Object Detection." ACM MM (2025).
[[paper](https://arxiv.org/abs/2507.23307)]
[[code](https://github.com/hu-xh/ST-SAM)]
[2025.07]

- Solha Kang, Eugene Kim, Joris Vankerschaver, Utku Ozbulak.<br />
"Towards Affordable Tumor Segmentation and Visualization for 3D Breast MRI Using SAM2." MICCAI Workshop (2025).
[[paper](https://arxiv.org/abs/2507.23272)]
[2025.07]

- Lalithkumar Seenivasan, Jiru Xu, Roger D. Soberanis Mukul, Hao Ding, Grayson Byrd, Yu-Chun Ku, Jose L. Porras, Masaru Ishii, Mathias Unberath.<br />
"Beyond Rigid AI: Towards Natural Human-Machine Symbiosis for Interoperative Surgical Assistance." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.23088)]
[2025.07]

- **MergeSAM:** Meiqi Hu, Lingzhi Lu, Chengxi Han, Xiaoping Liu.<br />
"MergeSAM: Unsupervised change detection of remote sensing images based on the Segment Anything Model." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.22675)]
[2025.07]

- **SAMITE:** Qianxiong Xu, Lanyun Zhu, Chenxi Liu, Guosheng Lin, Cheng Long, Ziyue Li, Rui Zhao.<br />
"SAMITE: Position Prompted SAM2 with Calibrated Memory for Visual Object Tracking." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.21732)]
[[code](https://github.com/Sam1224/SAMITE)]
[2025.07]

- Maoquan Zhang, Bisser Raytchev, Xiujuan Sun.<br />
"Semantic Segmentation of iPS Cells: Case Study on Model Complexity in Biomedical Imaging." MVA(2025).
[[paper](https://arxiv.org/abs/2507.21608)]
[2025.07]

- Marcel Moran, Arunav Gupta, Jiali Qian, Debra Laefer.<br />
"Scaling Pedestrian Crossing Analysis to 100 U.S. Cities via AI-based Segmentation of Satellite Imagery." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.20497)]
[2025.07]

- **SAMwave:** Saurabh Yadav, Avi Gupta, Koteswar Rao Jerripothula.<br />
"SAMwave: Wavelet-Driven Feature Enrichment for Effective Adaptation of Segment Anything Model." BMVC(2025).
[[paper](https://arxiv.org/abs/2507.20186)]
[2025.07]

- **HQ-SMem:** Elham Soltani Kazemi, Imad Eddine Toubal, Gani Rahmon, Jaired Collins, K. Palaniappan.<br />
"HQ-SMem: Video Segmentation and Tracking Using Memory Efficient Object Embedding With Selective Update and Self-Supervised Distillation Feedback." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.18921)]
[2025.07]

- **SAM2-Aug:** Guoping Xu, Yan Dai, Hengrui Zhao, Ying Zhang, Jie Deng, Weiguo Lu, You Zhang.<br />
"SAM2-Aug: Prior knowledge-based Augmentation for Target Volume Auto-Segmentation in Adaptive Radiation Therapy Using Segment Anything Model 2." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.19282)]
[[code](https://github.com/apple1986/SAM2-Aug)]
[2025.07]

- **Lacune_Detection:** Pon Deepika et al.<br />
"Automated Detection of Lacunes in Brain MR Images Using SAM with Robust Prompts via Self-Distillation and Anatomy-Informed Priors." ArXiv (2025).
[[paper](https://www.medrxiv.org/content/10.1101/2025.07.09.25331177v1)]
[[code](https://github.com/PonDeepika/Lacune_Detection)]
[2025.07]

- **SinkSAM-Net:** Osher Rafaeli and Tal Svoray and Ariel Nahlieli.<br />
"SinkSAM-Net: Knowledge-driven self-supervised sinkhole segmentation using topographic priors and Segment Anything Model." ISPRS Journal of Photogrammetry and Remote Sensing (2025).
[[paper](https://doi.org/10.1016/j.isprsjprs.2025.06.035)]
[[code](https://osherr1996.github.io/SinkSAMNet)]
[2025.07]

- Sergi, G., Bocchino, F., Ravanelli, R., & Crespi, M.<br />
"Monitoring water reservoirs extent with Segment Anything Model applied to Sentinel imagery." European Journal of Remote Sensing(2025).
[[paper](https://www.tandfonline.com/doi/full/10.1080/22797254.2025.2527248)]
[2025.07]

- **DefectSAM:** Yan, Feng and Jiang, Xiaoheng and Lu, Yang and Cao, Jiale and Xu, Mingliang.<br />
"DefectSAM: Hierarchically Adapting SAM for Pixel-Wise Surface Defect Detection." TNNLS (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/11078420)]
[2025.07]

- **GAM:** Ge, Rongjun and Li, Ruiyi and Wang, Chong and Liu, Yuxin and Zhu, Heng and Coatrieux, Jean-Louis and Zhang, Daoqiang and Lu, Jian and Chen, Yang and Li, Shuo and He, Yuting.<br />
"Adaptation follow human attention: Gaze-assisted medical segment anything model." TCSVT (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/11079704)]
[[code](https://github.com/Ruiz1026/GAM)]
[2025.07]

- **IPPIS:** Hui Chen, Nannan Li, Ming An, Chengxi Xia & Kekun Zhu.<br />
"Enhancing image dehazing with polarization awareness and SAM-guided fusion." ArXiv (2025).
[[paper](https://link.springer.com/article/10.1007/s00371-025-04083-5)]
[[code](https://github.com/chenhuiphd/IPPIS)]
[2025.07]

- **TS-SAM:** Zhang, E. et al.<br />
"Unleashing the Potential of SAM for Change Detection: A Two-Stage Approach for Enhanced Remote Sensing Analysis." ICIC (2025).
[[paper](https://doi.org/10.1007/978-981-96-9952-0_4)]
[2025.07]

- **EdgeSAM-CASD:** Zhang, J. et al.<br />
"EdgeSAM-CASD: Lightweight Mural Damage Segmentation via Convolutional Adapter." ICIC (2025).
[[paper](https://doi.org/10.1007/978-981-96-9794-6_5)]
[2025.07]

- **SMBA-MIL:** Zhou, B., Wang, C., Wu, X., Liao, C., Wang, P., Wang, H.<br />
"SMBA-MIL: SAM-Enhanced Multi-branch Attention Multi-instance Learning for Whole Slide Image Classification." ICIC (2025).
[[paper](https://doi.org/10.1007/978-981-96-9794-6_43)]
[2025.07]

- **Yolo-HLSAM:** Banteng Liu and Hongguang Chen and Tianyi Zhu and Zanting Ye and Haidong Cui and Ke Wang.<br />
"Yolo-HLSAM: Adapting foundation segment anything model for semi-automatic detection and segmentation of breast cancer microcalcification clusters." Biomedical Signal Processing and Control (2025).
[[paper](https://doi.org/10.1016/j.bspc.2025.108300)]
[[code](https://github.com/ccchg/yolo-hlsam)]
[2025.07]

- **Rad_SAM2:** Ezekiel Chukwujindu and Khunsa Faiz and Alexandra {De Sequeira} and Stephanie Chidom and Hafsa Faiz.<br />
"Improving medical image segmentation with SAM2: analyzing the impact of object characteristics and finetuning on multi-planar datasets." European Journal of Radiology Artificial Intelligence (2025).
[[paper](https://doi.org/10.1016/j.ejrai.2025.100034)]
[[code](https://github.com/RadSam2/rad_sam2)]
[2025.07]

- Jia, Runda and Wang, Jinglong and Zheng, Jun and Li, Jiahao and He, Dakuo.<br />
"Feature Extraction for Mining Industry Image Based on SAM: A Case Study From Froth Flotation." TII (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/11082383)]
[2025.07]

- **SAID-Net:** Wu, Y., Zhao, T., Hu, S. et al.<br />
"SAID-Net: enhancing segment anything model with implicit decoding for echocardiography sequences segmentation." Med Biol Eng Comput (2025).
[[paper](https://doi.org/10.1007/s11517-025-03419-6)]
[2025.07]

- **TP-SAM:** Xiao, T., Ling, Y.<br />
"TP-SAM: Fine-Tuning SAM with Task-Specific Prompt in the Loop." ICIC (2025).
[[paper](https://doi.org/10.1007/978-981-96-9964-3_44)]
[2025.07]

- **3DGS-SAM 2:** Duan, D., Wang, Z., Xin, Y. et al.<br />
"Defect segmentation and 3D reconstruction in concrete structures using SAM 2 and 3D Gaussian splatting." J Civil Struct Health Monit(2025).
[[paper](https://doi.org/10.1007/s13349-025-00993-z)]
[2025.07]

- **DCVA-SAM:** Sudipan Saha; Kanishk Awadhiya.<br />
"Integrating Deep Change Vector Analysis and SAM for Class-Specific Change Detection." IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/11086368)]
[[code](https://github.com/sudipansaha/classSpecificCDWithDCVAAndSAM)]
[2025.07]

- **KD-MedSAM:** Zhou, W., Zhu, J., Chen, W., Li, C., He, Y., He, M.<br />
"KD-MedSAM: Lightweight Knowledge Distillation of Segment Anything Model for Multi-modality Medical Image Segmentation." ICIC (2025).
[[paper](https://doi.org/10.1007/978-981-95-0036-9_31)]
[2025.07]

- **FreqSAM2-UNet:** Wang, C., Cao, J., Gao, Y., Wang, J.<br />
"FreqSAM2-UNet: Adapter Fine-Tuning Frequency-Aware Network of SAM2 for Universal Medical Segmentation." ICIC (2025).
[[paper](https://doi.org/10.1007/978-981-95-0036-9_26)]
[2025.07]

- **SCCAM:** Liu, Y., Fei, Y., Dai, X., Zhou, Y., Wang, X., Huang, X.<br />
"Annotation-Free Salient Object Detection via Spatial-Enhanced Contrastive Learning and SAM." ICIC (2025).
[[paper](https://doi.org/10.1007/978-981-96-9866-0_36)]
[2025.07]

- **YOSAM:** Li, Z., Chen, L., Lu, L., Ding, Y., Hao, X.<br />
"YOSAM: A YOLO and MedSAM-Based Framework for Automatic Measurement of Fetal Head Circumference in Ultrasound Images." ICIC (2025).
[[paper](https://doi.org/10.1007/978-981-95-0033-8_37)]
[2025.07]

- Li, J., Yan, F., Zhang, X., Yang, L.<br />
"Two-Stage Multi-stained Cell Analysis with the Segment Anything Model for Pathological Image Segmentation." ICIC (2025).
[[paper](https://doi.org/10.1007/978-981-95-0033-8_21)]
[2025.07]

- **FB-SAM:** Wen, Z., Ma, J.<br />
"FB-SAM: An Effective Learning Framework for First Break Picking Based on the SAM Model with Limited Data." ICIC (2025).
[[paper](https://doi.org/10.1007/978-981-95-0006-2_33)]
[2025.07]

- **SAM2-DFBCNet:** Yuan, Cao, Libang Liu, Yaqin Li, and Jianxiang Li.<br />
"SAM2-DFBCNet: A Camouflaged Object Detection Network Based on the Heira Architecture of SAM2." Sensors (2025).
[[paper](https://www.mdpi.com/1424-8220/25/14/4509)]
[2025.07]

- Bolutife Atoki, Jenny Benois-Pineau, Renaud Péteri, Fabien Baldacci, Aymar de Rugy.<br />
"Object segmentation in the wild with foundation models: application to vision assisted neuro-prostheses for upper limbs." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.18517)]
[[code](https://universe.roboflow.com/iwrist/grasping-in-the-wild)]
[2025.07]

- **TextSAM-EUS::** Pascal Spiegler, Taha Koleilat, Arash Harirpoush, Corey S. Miller, Hassan Rivaz, Marta Kersten-Oertel, Yiming Xiao.<br />
"TextSAM-EUS: Text Prompt Learning for SAM to Accurately Segment Pancreatic Tumor in Endoscopic Ultrasound." ICCVW (2025).
[[paper](https://arxiv.org/abs/2507.18082)]
[2025.07]

- **FA-SAM:** Huanli Zhuo, Leilei Ma, Haifeng Zhao, Shiwei Zhou, Dengdi Sun, Yanping Fu.<br />
"Fully Automated SAM for Single-source Domain Generalization in Medical Image Segmentation." IEEE SMC (2025).
[[paper](https://arxiv.org/abs/2507.17281)]
[2025.07]

- **ScSAM:** Bo Fang, Jianan Fan, Dongnan Liu, Hang Chang, Gerald J. Shami, Filip Braet, Weidong Cai.<br />
"ScSAM: Debiasing Morphology and Distributional Variability in Subcellular Semantic Segmentation." ECAI (2025).
[[paper](https://arxiv.org/abs/2507.17149)]
[2025.07]

- **MARSCalib:** Seokhwan Jeong, Hogyun Kim, Younggun Cho.<br />
"MARSCalib: Multi-robot, Automatic, Robust, Spherical Target-based Extrinsic Calibration in Field and Extraterrestrial Environments." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.17130)]
[[code](https://github.com/sparolab/MARSCalib)]
[2025.07]

- **SpelkeNet:** Rahul Venkatesh, Klemen Kotar, Lilian Naing Chen, Seungwoo Kim, Luca Thomas Wheeler, Jared Watrous, Ashley Xu, Gia Ancone, Wanhee Lee, Honglin Chen, Daniel Bear, Stefan Stojanov, Daniel Yamins.<br />
"Discovering and using Spelke segments." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.16038)]
[[code](https://neuroailab.github.io/spelke_net)]
[2025.07]

- **CMP:** Shuai Chen, Fanman Meng, Chunjin Yang, Haoran Wei, Chenhao Wu, Qingbo Wu, Hongliang Li.<br />
"CMP: A Composable Meta Prompt for SAM-Based Cross-Domain Few-Shot Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.16753)]
[2025.07]

- **DFR::** Shuai Chen, Fanman Meng, Xiwei Zhang, Haoran Wei, Chenhao Wu, Qingbo Wu, Hongliang Li.<br />
"DFR: A Decompose-Fuse-Reconstruct Framework for Multi-Modal Few-Shot Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.16736)]
[2025.07]

- **PlantSAM:** Youcef Sklab, Florian Castanet, Hanane Ariouat, Souhila Arib, Jean-Daniel Zucker, Eric Chenin, Edi Prifti.<br />
"PlantSAM: An Object Detection-Driven Segmentation Pipeline for Herbarium Specimens." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.16506)]
[2025.07]

- **OP-SAM:** Xinyu Mao, Xiaohan Xing, Fei Meng, Jianbang Liu, Fan Bai, Qiang Nie, Max Meng.<br />
"One Polyp Identifies All: One-Shot Polyp Segmentation with SAM via Cascaded Priors and Iterative Prompt Evolution." ICCV (2025).
[[paper](https://arxiv.org/abs/2507.16337)]
[[code](https://github.com/Hectormxy/OP-SAM)]
[2025.07]

- **HFS-SAM2:** Wu, Zihuang and Xiong, Xinyu and Gao, Guangwei and Li, Hongwei and Chen, Hua.<br />
"HFS-SAM2: Segment Anything Model 2 with High-Frequency Feature Supplementation for Camouflaged Object Detection." IEEE SPL (2025).
[[paper](https://ieeexplore.ieee.org/document/11081899)]
[[code](https://github.com/WZH0120/HFS-SAM2)]
[2025.07]

- **SeC:** Zhixiong Zhang, Shuangrui Ding, Xiaoyi Dong, Songxin He, Jianfan Lin, Junsong Tang, Yuhang Zang, Yuhang Cao, Dahua Lin, Jiaqi Wang.<br />
"SeC: Advancing Complex Video Object Segmentation via Progressive Concept Construction." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.15852)]
[[project](https://rookiexiong7.github.io/projects/SeC/)]
[[code](https://github.com/OpenIXCLab/SeC)]
[[dataset](https://huggingface.co/datasets/OpenIXCLab/SeCVOS)]
[2025.07]

- **PseudonuScenes:** Atharv Goel, Mehar Khurana.<br />
"Just Add Geometry: Gradient-Free Open-Vocabulary 3D Detection Without Human-in-the-Loop." ArXiv (2025).
[[paper](Just Add Geometry: Gradient-Free Open-Vocabulary 3D Detection Without Human-in-the-Loop)]
[[code](https://github.com/atharv0goel/open-world-3D-det)]
[2025.07]

- **ConformalSAM:** Danhui Chen, Ziquan Liu, Chuxi Yang, Dan Wang, Yan Yan, Yi Xu, Xiangyang Ji.<br />
"ConformalSAM: Unlocking the Potential of Foundational Segmentation Models in Semi-Supervised Semantic Segmentation with Conformal Prediction." ICCV (2025).
[[paper](https://arxiv.org/abs/2507.15803)]
[2025.07]

- **FastSmoothSAM:** Jiasheng Xu, Yewang Chen.<br />
"FastSmoothSAM: A Fast Smooth Method For Segment Anything Model." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.15008)]
[[code](https://github.com/XFastDataLab/FastSmoothSAM)]
[2025.07]

- **DD-SAM2:** Guoping Xu, Christopher Kabat, You Zhang.<br />
"Depthwise-Dilated Convolutional Adapters for Medical Object Tracking and Segmentation Using the Segment Anything Model 2." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.14613)]
[[code](https://github.com/apple1986/DD-SAM2)]
[2025.07]

- **SAM2Plus:** Yin, Jun, Fei Wu, Hao Su, Peng Huang, and Yuetong Qixuan.<br />
"Improvement of SAM2 Algorithm Based on Kalman Filtering for Long-Term Video Object Segmentation." Sensors (2025).
[[paper](https://www.mdpi.com/1424-8220/25/13/4199)]
[2025.07]

- **BreastSegNet:** Qihang Li, Jichen Yang, Yaqian Chen, Yuwen Chen, Hanxue Gu, Lars J. Grimm, Maciej A. Mazurowski.<br />
"BreastSegNet: Multi-label Segmentation of Breast MRI." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.13604)]
[2025.07]

- **CSW-SAM:** Tianyi Zhang and Yi Ren and Weibin Li and Chenhao Qin and Licheng Jiao and Hua Su.<br />
"CSW-SAM: a cross-scale algorithm for very-high-resolution water body segmentation based on segment anything model 2." ISPRS Journal of Photogrammetry and Remote Sensing(2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S0924271625002709)]
[2025.07]

- Hanxue Gu, Yaqian Chen, Nicholas Konz, Qihang Li, Maciej A. Mazurowski.<br />
"Are Vision Foundation Models Ready for Out-of-the-Box Medical Image Registration?." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.11569)]
[[code](https://github.com/mazurowski-lab/Foundation-based-reg)]
[2025.07]

- **RegCL:**  Yuan-Chen Shu, Zhiwei Lin, Yongtao Wang.<br />
"RegCL: Continual Adaptation of Segment Anything Model via Model Merging." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.12297)]
[2025.07]

- Antonio Finocchiaro, Giovanni Maria Farinella, Antonino Furnari.<br />
"Efficient Calisthenics Skills Classification through Foreground Instance Selection and Depth Estimation." International Conference on Image Analysis and Processing(2025).
[[paper](https://arxiv.org/abs/2507.12292)]
[[code](https://iplab.dmi.unict.it/fpv/)]
[2025.07]

- **SAMST:** Jun Yin, Fei Wu, Yupeng Ren, Jisheng Huang, Qiankun Li, Heng jin, Jianhai Fu, Chanjie Cui.<br />
"SAMST: A Transformer framework based on SAM pseudo label filtering for remote sensing semi-supervised semantic segmentation."  IGARSS(2025).
[[paper](https://arxiv.org/abs/2507.11994)]
[2025.07]

- Ekaterina Stansfield, Jennifer A. Mitterer, Abdulrahman Altahhan.<br />
"Landmark Detection for Medical Images using a General-purpose Segmentation Model." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.11551)]
[2025.07]

- **CSCPNet:** Jinglin Zhang et al.<br />
"Controlled-SAM and Context Promoting Network for Fine-Grained Semantic Segmentation." JSTARS (2025).
[[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11045311&tag=1)]
[2025.07]

- Wang Zhicheng, Satoshi Yagi, Satoshi Yamamori, Jun Morimoto.<br />
"Object-Centric Mobile Manipulation through SAM2-Guided Perception and Imitation Learning." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.10899)]
[2025.07]

- **StaRFM:** Behraj Khan, Tahir Syed.<br />
"Calibrated and Robust Foundation Models for Vision-Language and Medical Image Tasks Under Distribution Shift." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.09222)]
[[code](https://anonymous.4open.science/r/StaRFM-C0CD/)]
[2025.07]

- **DEARLi:** Ivan Martinović, Josip Šarić, Marin Oršić, Matej Kristan, Siniša Šegvić.<br />
"DEARLi: Decoupled Enhancement of Recognition and Localization for Semi-supervised Panoptic Segmentation." ICCV Workshop (2025).
[[paper](https://arxiv.org/abs/2507.10118)]
[[code](https://github.com/helen1c/DEARLi)]
[2025.07]

- **FOCAL:** Utkarsh Singhal, Ryan Feng, Stella X. Yu, Atul Prakash.<br />
"Test-Time Canonicalization by Foundation Models for Robust Perception." ICML (2025).
[[paper](https://arxiv.org/abs/2507.10375)]
[[code](https://github.com/sutkarsh/focal)]
[2025.07]

- **Inter2Former.:** You Huang, Lichao Chen, Jiayi Ji, Liujuan Cao, Shengchuan Zhang, Rongrong Ji.<br />
"Inter2Former: Dynamic Hybrid Attention for Efficient High-Precision Interactive." ICCV (2025).
[[paper](https://arxiv.org/abs/2507.09612)]
[2025.07]

- **MA-SAM2:** Ming Yin, Fu Wang, Xujiong Ye, Yanda Meng, Zeyu Fu.<br />
"Memory-Augmented SAM2 for Training-Free Surgical Video Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.09577)]
[[code](https://github.com/Fawke108/MA-SAM2)]
[2025.07]

- Yidong Jiang.<br />
"Prompt Engineering in Segment Anything Model: Methodologies, Applications, and Emerging Challenges." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.09562)]
[2025.07]

- **Birkhoff:** Juntong Fan, Zhiwei Hao, Jianqiang Shen, Shang-Ling Jui, Yi Zhang, Jing-Xiao Liao, Feng-Lei Fan.<br />
"Compress Any Segment Anything Model (SAM)." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.08765)]
[[code](https://github.com/Juntongkuki/Birkhoff-Model-Compression.git)]
[2025.07]

- Wu, Xiaoqin, Dacheng Wang, Caihong Ma, Yi Zeng, Yongze Lv, Xianmiao Huang, and Jiandong Wang.<br />
"Parcel Segmentation Method Combined YOLOV5s and Segment Anything Model Using Remote Sensing Image." ArXiv (2025).
[[paper](https://www.mdpi.com/2073-445X/14/7/1429)]
[2025.07]

- **PlantSAM:** Daniel J Petti, Changying Li, Alina Zare.<br />
"PlantSAM: Towards Real-Time Plant Segmentation with Efficient Vision-Language Foundation Models." ArXiv (2025).
[[paper](https://elibrary.asabe.org/abstract.asp?aid=55403)]
[2025.07]

- **HiM2SAM:** Ruixiang Chen, Guolei Sun, Yawei Li, Jie Qin, Luca Benini.<br />
"HiM2SAM: Enhancing SAM2 with Hierarchical Motion Estimation and Memory Optimization towards Long-term Tracking." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.07603)]
[[code](https://github.com/LouisFinner/HiM2SAM)]
[2025.07]

- **Objectomaly:** Jeonghoon Song, Sunghun Kim, Jaegyun Im, Byeongjoon Noh.<br />
"Objectomaly: Objectness-Aware Refinement for OoD Segmentation with Structural Consistency and Boundary Precision." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.07460)]
[2025.07]

- **Seg-Wild:** Yongtang Bao, Chengjie Tang, Yuze Wang, Haojie Li.<br />
"Seg-Wild: Interactive Segmentation based on 3D Gaussian Splatting for Unconstrained Image Collections." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.07395)]
[[code](https://github.com/Sugar0725/Seg-Wild)]
[2025.07]

- **LangSplatV2:** Wanhua Li, Yujie Zhao, Minghan Qin, Yang Liu, Yuanhao Cai, Chuang Gan, Hanspeter Pfister.<br />
"LangSplatV2: High-dimensional 3D Language Gaussian Splatting with 450+ FPS." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.07136)]
[[code](https://langsplat-v2.github.io)]
[2025.07]

- **Raps-3D:** Théo Danielou, Daniel Tordjman, Pierre Manceron, Corentin Dancette.<br />
"RAPS-3D: Efficient interactive segmentation for 3D radiological imaging." MIUA (2025).
[[paper](https://arxiv.org/abs/2507.07730)]
[2025.07]

- **SMML:** Guoyan Liang, Qin Zhou, Jingyuan Chen, Bingcang Huang, Kai Chen, Lin Gu, Zhe Wang, Sai Wu, Chang Yao.<br />
"Semantic-guided Masked Mutual Learning for Multi-modal Brain Tumor Segmentation with Arbitrary Missing Modalities." AAAI (2025).
[[paper](https://arxiv.org/abs/2507.07592)]
[2025.07]

- **SpatialReasoner:** Zhenyang Liu, Sixiao Zheng, Siyu Chen, Cairong Zhao, Longfei Liang, Xiangyang Xue, Yanwei Fu.<br />
"A Neural Representation Framework with LLM-Driven Spatial Reasoning for Open-Vocabulary 3D Visual Grounding." ACM MM (2025).
[[paper](https://arxiv.org/abs/2507.06719)]
[[code](https://zhenyangliu.github.io/SpatialReasoner/)]
[2025.07]

- **RSRefSeg 2:** Keyan Chen, Chenyang Liu, Bowen Chen, Jiafan Zhang, Zhengxia Zou, Zhenwei Shi.<br />
"RSRefSeg 2: Decoupling Referring Remote Sensing Image Segmentation with Foundation Models." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.06231)]
[[code](https://github.com/KyanChen/RSRefSeg2)]
[2025.07]

- **Accordion:** Jingye Chen, Zhaowen Wang, Nanxuan Zhao, Li Zhang, Difan Liu, Jimei Yang, Qifeng Chen.<br />
"Rethinking Layered Graphic Design Generation with a Top-Down Approach." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.05601)]
[2025.07]

- **OpenWorldSAM:** Shiting Xiao, Rishabh Kabra, Yuhang Li, Donghyun Lee, Joao Carreira, Priyadarshini Panda.<br />
"OpenWorldSAM: Extending SAM2 for Universal Image Segmentation with Language Prompts." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.05427)]
[2025.07]

- **SAMed-2:** Zhiling Yan, Sifan Song, Dingjie Song, Yiwei Li, Rong Zhou, Weixiang Sun, Zhennong Chen, Sekeun Kim, Hui Ren, Tianming Liu, Quanzheng Li, Xiang Li, Lifang He, Lichao Sun.<br />
"SAMed-2: Selective Memory Enhanced Medical Segment Anything Model." MICCAI (2025).
[[paper](https://arxiv.org/abs/2507.03698)]
[[code](https://github.com/ZhilingYan/Medical-SAM-Bench)]
[2025.07]

- **Causal-SAM-LLM:** Tao Tang, Shijie Xu, Yiting Wu, Zhixiang Lu.<br />
"Causal-SAM-LLM: Large Language Models as Causal Reasoners for Robust Medical Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.03585)]
[2025.07]

- **SAM2RL:** Alen Adamyan, Tomáš Čížek, Matej Straka, Klara Janouskova, Martin Schmid.<br />
"SAM2RL: Towards Reinforcement Learning Memory Control in Segment Anything Model 2." RLC Workshop on RL4RS (2025).
[[paper](https://openreview.net/forum?id=nikfkVtih1)]
[2025.07]

- **PAP-SAM:** Jizhe Yu, Xiya Bu, Yu Liu, and Kaiping Xu.<br />
"PAP-SAM: Global-Local Prior Adaptive Perception SAM for Co-Salient Object Detection." ICMR (2025).
[[paper](https://dl.acm.org/doi/abs/10.1145/3731715.3733413)]
[2025.07]

- **Light SAM:** Jiahong Chen, Hui Li, Shengnan Shen, Yingjie Wang, Rongzhe Ma, Haoyuan Chen, Hong Yin, Liwei Xia.<br />
"Universal Light SAM algorithm for in-situ melting pool monitoring of L-DED/L-PBF/PAM processes." Journal of Computational Design and Engineering(2025).
[[paper](https://doi.org/10.1093/jcde/qwaf057)]
[2025.07]

- Zhanghao Qin.<br />
"Diffusion-Based Adversarial Generation with SAM-Guided Spatial Semantics for Text-to-Image Models." ICMR (2025).
[[paper](https://dl.acm.org/doi/abs/10.1145/3731715.3733306)]
[2025.07]

- **EFI-SAM:** Huang, Junqing and Bao, Junqi and Xia, Min and Yuan, Xiaochen.<br />
"SAM-Based Efficient Feature Integration Network for Remote Sensing Change Detection: A Case Study on Macao Sea Reclamation." JSTARS (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/11058393)]
[[code](https://github.com/juncyan/efi-sam.git)]
[2025.07]

- **FlexiSAM:** Zhan Zhang et al.<br />
"FlexiSAM: A flexible SAM-based semantic segmentation model for land cover classification using high-resolution multimodal remote sensing imagery." ISPRS Journal of Photogrammetry and Remote Sensing (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S0924271625002151)]
[2025.07]

- Yuan Meng et al.<br />
"Unsupervised SAM segmentation of zebrafish body: Application to melanin analysis." Environmental Pollution (2025).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S0269749125011248)]
[2025.07]

- Gandul, Luis Villanueva, Antonio Madueño-Luna, José Miguel Madueño-Luna, Miguel Calixto López-Gordillo, and Manuel Jesús González-Ortega.<br />
"Diagnosis by SAM Linked to Machine Vision Systems in Olive Pitting Machines." Applied Sciences (2025).
[[paper](https://www.mdpi.com/2076-3417/15/13/7395)]
[2025.07]

- Sui, Y., Hu, Q. & Zhang, Y.<br />
"Cross-domain subcortical brain structure segmentation algorithm based on low-rank adaptation fine-tuning SAM." BMC Med Imaging (2025). 
[[paper](https://link.springer.com/article/10.1186/s12880-025-01779-x)]
[2025.07]

- **SAMUSA:** Baptiste Podvin et al.<br />
"SAMUSA: Segment Anything Model 2 for UltraSound Annotation." ArXiv (2025).
[[paper](https://www.researchgate.net/profile/Daniel-George-3/publication/393160079_SAMUSA_Segment_Anything_Model_2_for_UltraSound_Annotation/links/6862713d92697d42903be602/SAMUSA-Segment-Anything-Model-2-for-UltraSound-Annotation.pdf)]
[2025.07]

- **Sway:** Gupta, J., Sharma, S. Sway.<br />
"Sway: efficient pedestrian detection using SAM-based walkable area segmentation and YOLO." Int. j. inf. tecnol.(2025).
[[paper](https://link.springer.com/article/10.1007/s41870-025-02596-9)]
[2025.07]

- Luis Villanueva Gandul et al.<br />
"Diagnosis by SAM Linked to Machine Vision Systems in Olive Pitting Machines." Appl. Sci. (2025).
[[paper](https://idus.us.es/server/api/core/bitstreams/4ba7ee3a-7568-4eb6-ba6f-e3afc08b83aa/content)]
[2025.07]

- **FESS-SAM:** Hangbin Wu and Shaojun Zhou and Zhengwen Xu and Haili Sun and Lianbi Yao.<br />
"FESS-SAM: Full-element semantic segmentation of tunnel linear array images based on the segment anything model." Advanced Engineering Informatics (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S1474034625005026)]
[2025.07]

- **SAMOccNet:** Qifan Tan and Wenzhuo Liu and Han Bi and Lening Wang and Lei Yang and Yicheng Qiao and Zhuo Zhao and Yanhuan Jiang and Qiannan Guo and Huaping Liu and Zhiwei Li and Cheng Qiu.<br />
"SAMOccNet: Refined SAM-based Surrounding Semantic Occupancy Perception for Autonomous Driving." Neurocomputing (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S0925231225015905)]
[2025.07]

- **Training-free:** Miguel Espinosa, Chenhongyi Yang, Linus Ericsson, Steven McDonagh, Elliot J. Crowley.<br />
"No time to train! Training-Free Reference-Based Instance Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.02798)]
[[code](https://miquel-espinosa.github.io/no-time-to-train)]
[2025.07]

- **WeCoL:** Weiwei Duan, Luping Ji, Shengjia Chen, Sicheng Zhu, Jianghong Huang, Mao Ye.<br />
"Weakly-supervised Contrastive Learning with Quantity Prompts for Moving Infrared Small Target Detection." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.02454)]
[[code](https://github.com/UESTC-nnLab/WeCoL)]
[2025.07]

- **ViRefSAM:** Hanbo Bi, Yulong Xu, Ya Li, Yongqiang Mao, Boyuan Tong, Chongyang Li, Chunbo Lang, Wenhui Diao, Hongqi Wang, Yingchao Feng, Xian Sun.<br />
"ViRefSAM: Visual Reference-Guided Segment Anything Model for Remote Sensing Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.02294)]
[2025.07]

- **NOCTIS:** Max Gandyra, Alessandro Santonicola, Michael Beetz.<br />
"NOCTIS: Novel Object Cyclic Threshold based Instance Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.01463)]
[[code](https://github.com/code-iai/noctis)]
[2025.07]

- **ADA-SAM:** Tyler Ward, Meredith K. Owen, O'Kira Coleman, Brian Noehren, Abdullah-Al-Zubaer Imran.<br />
"Autoadaptive Medical Segment Anything Model." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.01828)]
[[code](https://github.com/tbwa233/ADA-SAM)]
[2025.07]

- **SGP:** Zihong Guo, Chen Wan, Yayin Zheng, Hailing Kuang, Xiaohai Lu.<br />
"Boosting Adversarial Transferability Against Defenses via Multi-Scale Transformation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2507.01791)]
[2025.07]

- **SAM-MaGuP:** Tapas K. Dutta, Snehashis Majhi, Deepak Ranjan Nayak, Debesh Jha.<br />
"Mamba Guided Boundary Prior Matters: A New Perspective for Generalized Polyp Segmentation." MICCAI (2025).
[[paper](https://arxiv.org/abs/2507.01509)]
[[code](https://github.com/deepak1113/SAM-MaGuP)]
[2025.07]

- **Seg-R1:** Zuyao You, Zuxuan Wu.<br />
"Seg-R1: Segmentation Can Be Surprisingly Simple with Reinforcement Learning." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.22624)]
[[code](https://geshang777.github.io/seg-r1.github.io/)]
[2025.06]

- **CRISP-SAM2:** Xinlei Yu, Chanmiao Wang, Hui Jin, Ahmed Elazab, Gangyong Jia, Xiang Wan, Changqing Zou, Ruiquan Ge.<br />
"CRISP-SAM2: SAM2 with Cross-Modal Interaction and Semantic Prompting for Multi-Organ Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.23121)]
[[code](https://github.com/YU-deep/CRISP_SAM2.git)]
[2025.06]

- **MaTIR:** Li-Cheng Shen, Jih-Kang Hsieh, Wei-Hua Li, Chu-Song Chen.<br />
"Mask-aware Text-to-Image Retrieval: Referring Expression Segmentation Meets Cross-modal Retrieval." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.22864)]
[[code](ttps://github.com/AI-Application-andIntegration-Lab/MaTIR)]
[2025.06]

- **DeSa2VA:** Dang Jisheng, Wu Xudong, Wang Bimei, Lv Ning, Chen Jiayu, Jingwen Zhao, Yichu liu, Jizhao Liu, Juncheng Li, Teng Wang.<br />
"Decoupled Seg Tokens Make Stronger Reasoning Video Segmenter and Grounder." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.22880)]
[[code](https://github.com/longmalongma/DeSa2VA)]
[2025.06]

- **GroundingDINO-US-SAM:** Hamza Rasaee, Taha Koleilat, Hassan Rivaz.<br />
"GroundingDINO-US-SAM: Text-Prompted Multi-Organ Segmentation in Ultrasound with LoRA-Tuned Vision-Language Models." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.23903)]
[2025.06]

- **VoteSplat:** Minchao Jiang, Shunyu Jia, Jiaming Gu, Xiaoyuan Lu, Guangming Zhu, Anqi Dong, Liang Zhang.<br />
"VoteSplat: Hough Voting Gaussian Splatting for 3D Scene Understanding." ICCV (2025).
[[paper](https://arxiv.org/abs/2506.22799)]
[[code](https://sy-ja.github.io/votesplat/)]
[2025.06]

- Shubhabrata Mukherjee, Jack Lang, Obeen Kwon, Iryna Zenyuk, Valerie Brogden, Adam Weber, Daniela Ushizima.<br />
"Foundation Models for Zero-Shot Segmentation of Scientific Images without AI-Ready Data." ICPPW (2025).
[[paper](https://arxiv.org/abs/2506.24039)]
[2025.06]

- **MedSAM-CA:** Peiting Tian, Xi Chen, Haixia Bi, Fan Li.<br />
"MedSAM-CA: A CNN-Augmented ViT with Attention-Enhanced Multi-Scale Fusion for Medical Image Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.23700)]
[2025.06]

- Fangyijie Wang, Kevin Whelan, Félix Balado, Guénolé Silvestre, Kathleen M. Curran.<br />
"Diffusion Model-based Data Augmentation Method for Fetal Head Ultrasound Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.23664)]
[2025.06]

- **SurgTPGS:** Yiming Huang, Long Bai, Beilei Cui, Kun Yuan, Guankun Wang, Mobarakol Islam, Nicolas Padoy, Nassir Navab, Hongliang Ren.<br />
"SurgTPGS: Semantic 3D Surgical Scene Understanding with Text Promptable Gaussian Splatting." MICCAI (2025).
[[paper](https://arxiv.org/abs/2506.23309)]
[[code](https://github.com/lastbasket/SurgTPGS)]
[2025.06]

- **DC-TTA:** Jihun Kim, Hoyong Kwon, Hyeokjun Kweon, Wooseong Jeong, Kuk-Jin Yoon.<br />
"DC-TTA: Divide-and-Conquer Framework for Test-Time Adaptation of Interactive Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.23104)]
[2025.06]

- **TASeg:** Meng Yu, Te Cui, Qitong Chu, Wenjie Song, Yi Yang, Yufeng Yue.<br />
"TASeg: Text-aware RGB-T Semantic Segmentation based on Fine-tuning Vision Foundation Models." lROS(2025).
[[paper](https://arxiv.org/abs/2506.21975)]
[2025.06]

- **ProSAM:** Xiaoqi Wang, Clint Sebastian, Wenbin He, Liu Ren.<br />
"ProSAM: Enhancing the Robustness of SAM-based Visual Reference Segmentation with Probabilistic Prompts." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.21835)]
[2025.06]

- Xianjun Han and Can Bai and Jie Wang and Zijian Wu.<br />
"Improving a segment anything model for segmenting low-quality medical images via an adapter." CVIU(2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S1077314225001481)]
[2025.06]

- **LiSegAgr:** Yunkai Wang, Yanfeng Lu.<br />
"LiSegAgr: Labeled Instance Segmentation for Agricultural Remote Sensing Images Through Iterative SAM." Neural Information Processing (2025).
[[paper](https://link.springer.com/chapter/10.1007/978-981-96-6972-1_25)]
[[code](https://github.com/WangYunKa/ISAgrSC2)]
[2025.06]

- **DoRL:** Yongcheng Li and Lingcong Cai and Ying Lu and Cheng Lin and Yupeng Zhang and Jingyan Jiang and Genan Dai and Bowen Zhang and Jingzhou Cao and Xiangzhong Zhang and Xiaomao Fan.<br />
"Domain-invariant representation learning via SAM for blood cell classification." Pattern Recognition (2025).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320325006600)]
[[code](https://github.com/AnoK3111/DoRL)]
[2025.06]

- Michal Stastny, Sean Harrell.<br />
"Application of SAM2 for Defect Detection in Manufacturing." ArXiv (2025).
[[paper](https://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1975033&dswid=1486)]
[2025.06]

- **SAM4D:** Jianyun Xu, Song Wang, Ziqian Ni, Chunyong Hu, Sheng Yang, Jianke Zhu, Qiang Li.<br />
"SAM4D: Segment Anything in Camera and LiDAR Streams." ICCV (2025).
[[paper](https://arxiv.org/abs/2506.21547)]
[[code](https://SAM4D-Project.github.io)]
[2025.06]

- **FFCL-SAM:** Tyler Ward, Xiaoqin Wang, Braxton McFarland, Md Atik Ahamed, Sahar Nozad, Talal Arshad, Hafsa Nebbache, Jin Chen, Abdullah Imran.<br />
"Detection of Breast Cancer Lumpectomy Margin with SAM-incorporated Forward-Forward Contrastive Learning." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.21006)]
[[code](https://github.com/tbwa233/FFCL-SAM/)]
[2025.06]

- **PathSegmentor:** Zhixuan Chen, Junlin Hou, Liqi Lin, Yihui Wang, Yequan Bie, Xi Wang, Yanning Zhou, Ronald Cheong Kin Chan, Hao Chen.<br />
"Segment Anything in Pathology Images with Natural Language." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.20988)]
[[code](https://github.com/zhi-xuan-chen/PathSegmentor)]
[2025.06]

- Connor Ludwig, Khashayar Namdar, Farzad Khalvati.<br />
"AI-Driven MRI-based Brain Tumour Segmentation Benchmarking." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.20786)]
[2025.06]

- **CON-SAM:** Zihang Huang, Yaning Feng, Lilin Guo, Qiutao Shi, Wei Jin.<br />
"Fully Automated Mandibular Condyle Segmentation: More Detailed Extraction With Hybrid Customized SAM." International Journal of Imaging Systems and Technology (2025).
[[paper](https://onlinelibrary.wiley.com/doi/epdf/10.1002/ima.70138)]
[2025.06]

- **MLFA-SAM:** Hui Yang and Zhipeng Jiang and Yaobo Zhang and Yanlan Wu and Heng Luo and Peng Zhang and Biao Wang.<br />
"A high-resolution remote sensing land use/land cover classification method based on multi-level features adaptation of segment anything model." International Journal of Applied Earth Observation and Geoinformation(2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S1569843225003061)]
[2025.06]

- Siwei Xie.<br />
"Accelerating Segment Anything Models via Token Merging: A Comparative Study and a Spectrum Preservation-Based Approach." ArXiv (2025).
[[paper](https://elib.uni-stuttgart.de/server/api/core/bitstreams/baca7815-a21a-4085-be5d-f1250ba7011e/content)]
[2025.06]

- **PanSAM3D:** Zheng, Yifeng and Liu, Yuanyuan and Zhang, Yangfan and Qian, Huiying and Cao, Yi and Hou, Jue and Mei, Ying and Wang, Shuxin and Liu, Xiaoqing and Qian, Haifeng and Zhong, Jing and Yan, Qiang.<br />
"PanSAM3D: A SAM Foundation Model-Based Framework for Automatic 3D Pancreatic Segmentation Across Multi-Sequence MRI." ArXiv (2025).
[[paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5286619)]
[2025.06]

- Wang, Shengyi; Huang, Yuxiang; and El-Gohary, Nora.<br />
"SAM-based Segmentation of Multi-Class Bridge Components from Diverse Real-Scene Inspection Images." CIB Conferences (2025).
[[paper](https://docs.lib.purdue.edu/cib-conferences/vol1/iss1/240/)]
[2025.06]

- Bamwenda, Julius, Mehmet Siraç Özerdem, Orhan Ayyıldız, and Veysı Akpolat.<br />
"A Hybrid Deep Learning Framework for Accurate Cell Segmentation in Whole Slide Images Using YOLOv11, StarDist, and SAM2." Bioengineering (2025).
[[paper](https://www.mdpi.com/2306-5354/12/6/674)]
[2025.06]

- **SAM-MyoNet:** Yuhan Ying and Xingyu Fang and Yiwen Zhao and XinGang Zhao and Yufeng Zhou and Gang Du and Ying Zhan and Tian Gao and Andi Li and Dandan Sun and Guoli Song.<br />
"SAM-MyoNet: A fine-grained perception myocardial ultrasound segmentation network based on segment anything model with prior knowledge driven." Biomedical Signal Processing and Control (2025).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S1746809425006287)]
[[code](https://github.com/yingyuhan/SAM-MyoNet)]
[2025.06]

- **adaptive-SAM:** Chenqi Fang, Kai Duan, Zhipeng Lv, Juncai Huang, Qirui Zhong, Jing Chen, Di Lon.<br />
"Improving image-based water-level monitoring by coupling water-line detection techniques and the Segment Anything Model." Environmental Modelling and Software (2025).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S1364815225002506)]
[2025.06]

- **AL-SAM:** Yuze Sun, Hongwei Zhao, Jianhang Zhou.<br />
"Segment Anything Model for detecting salient objects with accurate prompting and Ladder Directional Perception." PRL (2025).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S0167865525002302)]
[2025.06]

- **SAM2-SGP:** Yang Xing, Jiong Wu, Yuheng Bu, Kuang Gong.<br />
"SAM2-SGP: Enhancing SAM2 for Medical Image Segmentation via Support-Set Guided Prompting." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.19658)]
[[code](https://github.com/astlian9/SAM_Support)]
[2025.06]

- **COCUS:** Kai Zhao, Wubang Yuan, Zheng Wang, Guanyi Li, Xiaoqiang Zhu, Deng-ping Fan, Dan Zeng.<br />
"Open-Vocabulary Camouflaged Object Segmentation with Cascaded Vision Language Models." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.19300)]
[[code](https://github.com/intcomp/camouflaged-vlm)]
[2025.06]

- **GeNIE:** Jiaming Wang, Diwen Liu, Jizhuo Chen, Jiaxuan Da, Nuowen Qian, Tram Minh Man, Harold Soh.<br />
"GeNIE: A Generalizable Navigation System for In-the-Wild Environments." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.17960)]
[2025.06]

- **Scene-R1:** Zhihao Yuan, Shuyi Jiang, Chun-Mei Feng, Yaolun Zhang, Shuguang Cui, Zhen Li, Na Zhao.<br />
"Scene-R1: Video-Grounded Large Language Models for 3D Scene Reasoning without 3D Annotations." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.17545)]
[2025.06]

- Yufan Liu, Yi Wu, Gweneth Ge, Haoliang Cheng, Rui Liu.<br />
"Reflective VLM Planning for Dual-Arm Desktop Cleaning: Bridging Open-Vocabulary Perception and Precise Manipulation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.17328)]
[2025.06]

- **SafeClick:** Yifan Gao, Jiaxi Sheng, Wenbin Wu, Haoyue Li, Yaoxian Dong, Chaoyang Ge, Feng Yuan, Xin Gao.<br />
"SafeClick: Error-Tolerant Interactive Segmentation of Any Medical Volumes via Hierarchical Expert Consensus." MICCAI (2025).
[[paper](https://arxiv.org/abs/2506.18404)]
[[code](https://github.com/yifangao112/SafeClick)]
[2025.06]

- **PicoSAM2:** Pietro Bonazzi, Nicola Farronato, Stefan Zihlmann, Haotong Qi, Michele Magno.<br />
"PicoSAM2: Low-Latency Segmentation In-Sensor for Edge Vision Applications." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.18807)]
[2025.06]

- **MedSeg-R:** Hao Shao, Qibin Hou.<br />
"MedSeg-R: Medical Image Segmentation with Clinical Reasoning." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.18669)]
[[code](https://github.com/haoshao-nku/MedSeg-R.git)]
[2025.06]

- **ERAS:** Carmelo Scribano, Elena Govi, Paolo bertellini, Simone Parisi, Giorgia Franchini, Marko Bertogna.<br />
"Segment Anything for Satellite Imagery: A Strong Baseline and a Regional Dataset for Automatic Field Delineation." ICIAP (2025).
[[paper](https://arxiv.org/abs/2506.16318)]
[[code](https://github.com/cscribano/ERAS-dataset)]
[2025.06]

- **STAR:** Qiwei Liang and Rulin Zhou and Yijing Zhou and Guankun Wang and Peng Peng and Xiaopin Zhong.<br />
"STAR: Empowering Semi-Supervised Medical Image Segmentation with SAM-based Teacher-Student Architecture and Contrastive Consistency Regularization." Expert Systems with Applications(2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S0957417425022699)]
[2025.06]

- **FreqWeaver Adapter:** Junhao Wu, Aboagye-Ntow Stephen, Chuyuan Wang, Gang Chen, Xin Huang.<br />
"Baltimore Atlas: FreqWeaver Adapter for Semi-supervised Ultra-high Spatial Resolution Land Cover Classification." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.15565)]
[2025.06]

- **Leader360V:** Weiming Zhang, Dingwen Xiao, Aobotao Dai, Yexin Liu, Tianbo Pan, Shiqi Wen, Lei Chen, Lin Wang.<br />
"Leader360V: The Large-scale, Real-world 360 Video Dataset for Multi-task Learning in Diverse Environment." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.14271)]
[2025.06]

- **SASAM:** Xingyi Zhang, Changqi Yu, Shihao Chen and Bin Pang.<br />
"SASAM: A Semantic-Aware SAM Framework for Weld Seam Vision Measurement." Measurement Science and Technology(2025).
[[paper](https://iopscience.iop.org/article/10.1088/1361-6501/ade32a/meta)]
[2025.06]

- **SAMSelect:** van Dalen, Joost and Asano, Yuki M. and Rußwurm, Marc.<br />
"SAMSelect: A Spectral Index Search for Marine Debris Visualization Using Segment Anything." IEEE Geoscience and Remote Sensing Letters (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/11028606)]
[2025.06]

- **SAAF:** Peilin Li, Jun Yin, Jing Zhong, Ran Luo, Pengyu Zeng, Miao Zhang.<br />
"Segment Any Architectural Facades (SAAF):An automatic segmentation model for building facades, walls and windows based on multimodal semantics guidance." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.09071)]
[2025.06]

- **Text3DSAM:** Yu Xin, Gorkem Can Ates, Wei Shao.<br />
"Text3DSAM: Text-Guided 3D Medical Image Segmentation Using SAM-Inspired Architecture." CVPRW (2025).
[[paper](https://openreview.net/forum?id=egbzGkOWVf)]
[[code](https://github.com/mirthAI/Text3DSAM)]
[2025.06]

- **SIT-SAM:** Wentao Shi, Junjun He, Yiqing Shen.<br />
"SIT-SAM: A semantic-integration transformer that adapts the Segment Anything Model to zero-shot medical image semantic segmentation." Biomedical Signal Processing and Control (2025).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S174680942500597X)]
[[code](https://github.com/wentao0429/SIT-SAM)]
[2025.06]

- Chang, Christian, Hudson Law, Connor Poon, Sydney Yen, Kaustubh Lall, Armin Jamshidi, Vadim Malis, Dosik Hwang, and Won C. Bae.<br />
"Segment Anything Model (SAM) and Medical SAM (MedSAM) for Lumbar Spine MRI." Sensors (2025).
[[paper](https://www.mdpi.com/1424-8220/25/12/3596)]
[2025.06]

- **conSAMme:** Josh Myers-Dean, Kangning Liu, Brian Price, Yifei Fan, Jason Kuen, Danna Gurari.<br />
"conSAMme: Achieving Consistent Segmentations with SAM." CVPRW (2025).
[[paper](https://openaccess.thecvf.com/content/CVPR2025W/NTIRE/html/Myers-Dean_conSAMme_Achieving_Consistent_Segmentations_with_SAM_CVPRW_2025_paper.html)]
[2025.06]

- **T-SAM:** Rangel Daroya, Deepak Chandran, Subhransu Maji, Andrea Fanelli.<br />
"T-SAM: Transductive Learning for Segment Anything Model." CVPRW (2025).
[[paper](https://openaccess.thecvf.com/content/CVPR2025W/DG-EBF/html/Daroya_T-SAM_Transductive_Learning_for_Segment_Anything_Model_CVPRW_2025_paper.html)]
[2025.06]

- **U-SAM:** Rohit Kundu, Sudipta Paul, Arindam Dutta, Amit Roy-Chowdhury.<br />
"Repurposing SAM for User-Defined Semantics Aware Segmentation." CVPRW (2025).
[[paper](https://openaccess.thecvf.com/content/CVPR2025W/MMFM/html/Kundu_Repurposing_SAM_for_User-Defined_Semantics_Aware_Segmentation_CVPRW_2025_paper.html)]
[[code](https://rohit-kundu.github.io/U-SAM)]
[2025.06]

- Almazroey, Alaa Atallah, Salma kammoun Jarraya, and Reem Alnanih.<br />
"SAM for Road Object Segmentation: Promising but Challenging." Journal of Imaging (2025).
[[paper](https://www.mdpi.com/2313-433X/11/6/189)]
[2025.06]

- **RouGE:** Guo, Yizhen and Guo, Hang and Dai, Tao and Wang, Zhi and Chen, Bin and Xia, Shutao.<br />
"Learning Gated Experts for Segment Anything in the Wild." ArXiv (2025).
[[paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5288257)]
[2025.06]

- Niu, Xuewei and Zhang, Jianyuan and Bai, Yu and Gao, Mengman and Yang, Xin.<br />
"SAM-Guided Accurate Pulmonary Nodule Image Segmentation." IEEE Access (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/11030594)]
[2025.06]

- **MorphSAM:** Dingwei Fan, Junyong Zhao, Chunlin Li, Xinlong Wang, Ronghan Zhang, Mingliang Wang, Qi Zhu, Haipeng Si, Daoqiang Zhang, Liang Sun.<br />
"MorphSAM: Learning the Morphological Prompts from Atlases for Spine Image Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.13094)]
[2025.06]

- **TAViS:** Ziyang Luo, Nian Liu, Xuguang Yang, Salman Khan, Rao Muhammad Anwer, Hisham Cholakkal, Fahad Shahbaz Khan, Junwei Han.<br />
"TAViS: Text-bridged Audio-Visual Segmentation with Foundation Models." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.11436)]
[2025.06]

- **Occ:** Yunhan Ren, Ruihuang Li, Lingbo Liu, Changwen Chen.<br />
"Prohibited Items Segmentation via Occlusion-aware Bilayer Modeling." ICME(2025).
[[paper](https://arxiv.org/abs/2506.11661)]
[[code](https://github.com/Ryh1218/Occ)]
[2025.06]

- **PSLGSAM:** Shuyang Li, Shuang Wang, Zhuangzhuang Sun, Jing Xiao.<br />
"Semantic Localization Guiding Segment Anything Model For Reference Remote Sensing Image Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.10503)]
[2025.06]

- Andrea Moglia, Matteo Leccardi, Matteo Cavicchioli, Alice Maccarini, Marco Marcon, Luca Mainardi, Pietro Cerveri.<br />
"Generalist Models in Medical Image Segmentation: A Survey and Performance Comparison with Task-Specific Approaches." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.10825)]
[2025.06]

- **Q-SAM2:** Nicola Farronato, Florian Scheidegger, Mattia Rigotti, Cristiano Malossi, Michele Magno, Haotong Qin.<br />
"Q-SAM2: Accurate Quantization for Segment Anything Model 2." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.09782)]
[2025.06]

- **SRPL-SFDA:** Xinya Liu, Jianghao Wu, Tao Lu, Shaoting Zhang, Guotai Wang.<br />
"SRPL-SFDA: SAM-Guided Reliable Pseudo-Labels for Source-Free Domain Adaptation in Medical Image Segmentation." Neurocomputing (2025).
[[paper](https://arxiv.org/abs/2506.09403)]
[[code](https://github.com/HiLab-git/SRPL-SFDA)]
[2025.06]

- **SemanticSplat:** Qijing Li, Jingxiang Sun, Liang An, Zhaoqi Su, Hongwen Zhang, Yebin Liu.<br />
"SemanticSplat: Feed-Forward 3D Scene Understanding with Language-Aware Gaussian Fields." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.09565)]
[[code](https://semanticsplat.github.io)]
[2025.06]

- **SSS:** Hongjie Zhu, Xiwei Liu, Rundong Xue, Zeyu Zhang, Yong Xu, Daji Ergu, Ying Cai, Yang Zhao.<br />
"SSS: Semi-Supervised SAM-2 with Efficient Prompting for Medical Imaging Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.08949)]
[[code](https://github.com/AIGeeksGroup/SSS)]
[2025.06]

- **SEE:** Chunming He, Kai Li, Yachao Zhang, Ziyun Yang, Youwei Pang, Longxiang Tang, Chengyu Fang, Yulun Zhang, Linghe Kong, Xiu Li, Sina Farsiu.<br />
"Segment Concealed Objects with Incomplete Supervision." IEEE TPAMI (2025).
[[paper](https://arxiv.org/abs/2506.08955)]
[2025.06]

- **SAMSelect:** Joost van Dalen, Yuki M. Asano, Marc Russwurm.<br />
"SAMSelect: A Spectral Index Search for Marine Debris Visualization using Segment Anything." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.08613)]
[2025.06]

- **SAM-SVN:** Jintao Tong, Ran Ma, Yixiong Zou, Guangyao Chen, Yuhua Li, Ruixuan Li.<br />
"Adapter Naturally Serves as Decoupler for Cross-Domain Few-Shot Semantic Segmentation." ICML (2025).
[[paper](https://arxiv.org/abs/2506.07376)]
[2025.06]

- Mingqi Gao, Haoran Duan, Tianlu Zhang, Jungong Han.<br />
"THU-Warwick Submission for EPIC-KITCHEN Challenge 2025: Semi-Supervised Video Object Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.06748)]
[2025.06]

- **RDVP-MSD:** Chao Yin, Hao Li, Kequan Yang, Jide Li, Pinpin Zhu, Xiaoqiang Li.<br />
"Stepwise Decomposition and Dual-stream Focus: A Novel Approach for Training-free Camouflaged Object Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.06818)]
[[code](https://github.com/ycyinchao/RDVP-MSD)]
[2025.06]

- Beining Xu, Junxian Li.<br />
"Design and Evaluation of Deep Learning-Based Dual-Spectrum Image Fusion Methods." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.07779)]
[2025.06]

- **OpenSplat3D:** Jens Piekenbrinck, Christian Schmidt, Alexander Hermans, Narunas Vaskevicius, Timm Linder, Bastian Leibe.<br />
"OpenSplat3D: Open-Vocabulary 3D Instance Segmentation using Gaussian Splatting." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.07697)]
[2025.06]

- **SAM2Auto:** Arash Rocky, Q.M. Jonathan Wu.<br />
"SAM2Auto: Auto Annotation Using FLASH." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.07850)]
[2025.06]

- Yannis Spyridis, Vasileios Argyriou.<br />
"Textile Analysis for Recycling Automation using Transfer Learning and Zero-Shot Foundation Models." IEEE DCOSS IoTi5(2025).
[[paper](https://arxiv.org/abs/2506.06569)]
[2025.06]

- **Talk2SAM:** Luka Vetoshkin, Dmitry Yudin.<br />
"Talk2SAM: Text-Guided Semantic Enhancement for Complex-Shaped Object Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.05396)]
[[code](https://github.com/richlukich/Talk2SAM)]
[2025.06]

- **TSAM:** Abduljalil Radman, Jorma Laaksonen.<br />
"TSAM: Temporal SAM Augmented with Multimodal Prompts for Referring Audio-Visual Segmentation." CVPR (2025).
[[paper](https://openaccess.thecvf.com/content/CVPR2025/html/Radman_TSAM_Temporal_SAM_Augmented_with_Multimodal_Prompts_for_Referring_Audio-Visual_CVPR_2025_paper.html)]
[[code](https://abdurad.github.io/TSAM/)]
[2025.06]

- **STT:** Tanner Schmidt, Richard Newcombe.<br />
"Segment This Thing: Foveated Tokenization for Efficient Point-Prompted Segmentation." CVPR (2025).
[[paper](https://openaccess.thecvf.com/content/CVPR2025/html/Schmidt_Segment_This_Thing_Foveated_Tokenization_for_Efficient_Point-Prompted_Segmentation_CVPR_2025_paper.html)]
[2025.06]

- **ESC-Net:** Minhyeok Lee, Suhwan Cho, Jungho Lee, Sunghun Yang, Heeseung Choi, Ig-Jae Kim, Sangyoun Lee.<br />
"Effective SAM Combination for Open-Vocabulary Semantic Segmentation." CVPR (2025).
[[paper](https://openaccess.thecvf.com/content/CVPR2025/html/Lee_Effective_SAM_Combination_for_Open-Vocabulary_Semantic_Segmentation_CVPR_2025_paper.html)]
[2025.06]


- **UNICL-SAM:** Dianmo Sheng, Dongdong Chen, Zhentao Tan, Qiankun Liu, Qi Chu, Tao Gong, Bin Liu, Jing Han, Wenbin Tu, Shengwei Xu, Nenghai Yu.<br />
"UNICL-SAM: Uncertainty-Driven In-Context Segmentation with Part Prototype Discovery." CVPR (2025).
[[paper](https://openaccess.thecvf.com/content/CVPR2025/html/Sheng_UNICL-SAM_Uncertainty-Driven_In-Context_Segmentation_with_Part_Prototype_Discovery_CVPR_2025_paper.html)]
[2025.06]

- **PPO:** Xueyu Liu, Rui Wang, Yexin Lai, Guangze Shi, Feixue Shao, Fang Hao, Jianan Zhang, Jia Shen, Yongfei Wu, Wen Zheng.<br />
"Plug-and-Play PPO: An Adaptive Point Prompt Optimizer Making SAM Greater." CVPR (2025).
[[paper](https://openaccess.thecvf.com/content/CVPR2025/html/Liu_Plug-and-Play_PPO_An_Adaptive_Point_Prompt_Optimizer_Making_SAM_Greater_CVPR_2025_paper.html)]
[[code](https://github.com/XueyuLiu/PPO)]
[2025.06]

- **SAM2Object:** Jihuai Zhao, Junbao Zhuo, Jiansheng Chen, Huimin Ma.<br />
"SAM2Object: Consolidating View Consistency via SAM2 for Zero-Shot 3D Instance Segmentation." CVPR (2025).
[[paper](https://openaccess.thecvf.com/content/CVPR2025/html/Zhao_SAM2Object_Consolidating_View_Consistency_via_SAM2_for_Zero-Shot_3D_Instance_CVPR_2025_paper.html)]
[[code](https://jihuaizhaohd.github.io/SAM2Object)]
[2025.06]

- **TAO:** Yuzhi Huang, Chenxin Li, Haitao Zhang, Zixu Lin, Yunlong Lin, Hengyu Liu, Wuyang Li, Xinyu Liu, Jiechao Gao, Yue Huang, Xinghao Ding, Yixuan Yuan.<br />
"Track Any Anomalous Object: A Granular Video Anomaly Detection Pipeline." CVPR (2025).
[[paper](https://openaccess.thecvf.com/content/CVPR2025/html/Huang_Track_Any_Anomalous_ObjectA_Granular_Video_Anomaly_Detection_Pipeline_CVPR_2025_paper.html)]
[[code](https://tao-25.github.io/)]
[2025.06]

- **EntitySAM:** Mingqiao Ye, Seoung Wug Oh, Lei Ke, Joon-Young Lee.<br />
"EntitySAM: Segment Everything in Video." CVPR (2025).
[[paper](https://openaccess.thecvf.com/content/CVPR2025/html/Ye_EntitySAM_Segment_Everything_in_Video_CVPR_2025_paper.html)]
[[code](https://github.com/ymq2017/entitysam)]
[2025.06]

- **SAM-REF:** Chongkai Yu, Ting Liu, Anqi Li, Xiaochao Qu, Chengjing Wu, Luoqi Liu, Xiaolin Hu.<br />
"SAM-REF: Introducing Image-Prompt Synergy during Interaction for Detail Enhancement in the Segment Anything Model." CVPR (2025).
[[paper](https://openaccess.thecvf.com/content/CVPR2025/html/Yu_SAM-REF_Introducing_Image-Prompt_Synergy_during_Interaction_for_Detail_Enhancement_in_CVPR_2025_paper.html)]
[2025.06]

- **VideoMolmo:** Ghazi Shazan Ahmad, Ahmed Heakl, Hanan Gani, Abdelrahman Shaker, Zhiqiang Shen, Ranjay Krishna, Fahad Shahbaz Khan, Salman Khan.<br />
"VideoMolmo: Spatio-Temporal Grounding Meets Pointing." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.05336)]
[[code](https://github.com/mbzuai-oryx/VideoMolmo)]
[2025.06]

- **ORES:** Shengcao Cao, Zijun Wei, Jason Kuen, Kangning Liu, Lingzhi Zhang, Jiuxiang Gu, HyunJoon Jung, Liang-Yan Gui, Yu-Xiong Wang.<br />
"Refer to Anything with Vision-Language Prompts." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.05342)]
[[code](https://Ref2Any.github.io)]
[2025.06]

- **PAM:** Weifeng Lin, Xinyu Wei, Ruichuan An, Tianhe Ren, Tingwei Chen, Renrui Zhang, Ziyu Guo, Wentao Zhang, Lei Zhang, Hongsheng Li.<br />
"Perceive Anything: Recognize, Explain, Caption, and Segment Anything in Images and Videos." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.05302)]
[[code](https://Perceive-Anything.github.io)]
[2025.06]

- **SAM-TTA:** Jianghao Wu, Yicheng Wu, Yutong Xie, Wenjia Bai, You Zhang, Feilong Tang, Yulong Li, Yasmeen George, Imran Razzak.<br />
"SAM-aware Test-time Adaptation for Universal Medical Image Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.05221)]
[[code](https://github.com/JianghaoWu/SAM-TTA)]
[2025.06]

- **BalSAM:** Mélisande Teng, Arthur Ouaknine, Etienne Laliberté, Yoshua Bengio, David Rolnick, Hugo Larochelle.<br />
"Bringing SAM to new heights: Leveraging elevation data for tree crown segmentation from drone imagery." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.04970)]
[2025.06]

- Michelle Chen, David Russell, Amritha Pallavoor, Derek Young, Jane Wu.<br />
"Zero-Shot Tree Detection and Segmentation from Aerial Forest Imagery." ICLR Workshop (2025).
[[paper](https://arxiv.org/abs/2506.03114)]
[[code](https://github.com/open-forest-observatory/tree-detection-framework)]
[2025.06]

- **GaRA-SAM:** Sohyun Lee, Yeho Kwon, Lukas Hoyer, Suha Kwak.<br />
"GaRA-SAM: Robustifying Segment Anything Model with Gated-Rank Adaptation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.02882)]
[2025.06]

- **HSP-SAM:** Mengmeng Zhang, Xingyuan Dai, Yicheng Sun, Jing Wang, Yueyang Yao, Xiaoyan Gong, Fuze Cong, Feiyue Wang, Yisheng Lv.<br />
"Hierarchical Self-Prompting SAM: A Prompt-Free Medical Image Segmentation Framework." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.02854)]
[2025.06]

- **SAMJ:** Carlos Garcia-Lopez-de-Haro, Caterina Fuster-Barcelo, Curtis T. Rueden, Jonathan Heras, Vladimir Ulman, Daniel Franco-Barranco, Adrian Ines, Kevin W. Eliceiri, Jean-Christophe Olivo-Marin, Jean-Yves Tinevez, Daniel Sage, Arrate Munoz-Barrutia.<br />
"SAMJ: Fast Image Annotation on ImageJ/Fiji via Segment Anything Model." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.02783)]
[2025.06]

- **SAM2-LOVE:** Yuji Wang, Haoran Xu, Yong Liu, Jiaze Li, Yansong Tang.<br />
"SAM2-LOVE: Segment Anything Model 2 in Language-aided Audio-Visual Scenes." CVPR (2025).
[[paper](https://arxiv.org/abs/2506.01558)]
[[code](https://github.com/VoyageWang/SAM2LOVE)]
[2025.06]

- **SAM-I2V:** Haiyang Mei, Pengyu Zhang, Mike Zheng Shou.<br />
"SAM-I2V: Upgrading SAM to Support Promptable Video Segmentation with Less than 0.2% Training Cost." CVPR (2025).
[[paper](https://arxiv.org/abs/2506.01304)]
[[code](https://github.com/showlab/SAM-I2V)]
[2025.06]

- **AuralSAM2:** Yuyuan Liu, Yuanhong Chen, Chong Wang, Junlin Han, Junde Wu, Can Peng, Jingkun Chen, Yu Tian, Gustavo Carneiro.<br />
"AuralSAM2: Enabling SAM2 Hear Through Pyramid Audio-Visual Feature Prompting." ArXiv (2025).
[[paper](https://arxiv.org/abs/2506.01015)]
[[code](https://github.com/yyliu01/AuralSAM2)]
[2025.06]

- Gang Xu and Yingshui Zhang and Qingrui Yue and Xiaogang Liu.<br />
"Automated detection and quantification of structural component dimensions using segment anything model (SAM)-based segmentation." Automation in Construction (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S0926580525003449)]
[2025.06]

- **EASAM:** Jianguo Zhang, Meng Lin, Hu Hou, Benhao Sun, Fengling Hu, Youcheng Yu & Menghan Li .<br />
"EASAM: an edge-aware SAM-based paradigm for tooth segmentation." Signal, Image and Video Processing (2025).
[[paper](https://link.springer.com/article/10.1007/s11760-025-04208-2)]
[[code](XXXXXXXXXXXXXXXXXXXXXX)]
[2025.06]

- Daixin Fu, Bowen Kuang, Lin Mi, Yongjie Liu, Qingyuan Wang, Junnan Lv, Lang Li.<br />
"A threshold-based prompt generation method for segment anything model to identify fission gas bubbles." ArXiv (2025).
[[paper](https://www.emerald.com/insight/content/doi/10.1108/ijsi-03-2025-0059/full/html)]
[2025.06]

- Liangyang Ouyang, Yuki Sakai, Ryosuke Furuta, Hisataka Nozawa, Hikoro Matsui, Yoichi Sato.<br />
"Leadership Assessment in Pediatric Intensive Care Unit Team Training." CVPRW (2025).
[[paper](https://arxiv.org/abs/2505.24389)]
[2025.05]

- **KairosAD:** Uzair Khan, Franco Fummi, Luigi Capogrosso.<br />
"KairosAD: A SAM-Based Model for Industrial Anomaly Detection on Embedded Devices." ICIAP (2025).
[[paper](https://arxiv.org/abs/2505.24334)]
[[code](https://github.com/intelligolabs/KairosAD)]
[2025.05]

- Gang Xu and Yingshui Zhang and Qingrui Yue and Xiaogang Liu.<br />
"Automated detection and quantification of structural component dimensions using segment anything model (SAM)-based segmentation." Automation in Construction(2025).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S0926580525003449)]
[2025.05]

- **SAMamba:** Wenhao Xu, Shuchen Zheng, Changwei Wang, Zherui Zhang, Chuan Ren, Rongtao Xu, Shibiao Xu.<br />
"SAMamba: Adaptive State Space Modeling with Hierarchical Vision for Infrared Small Target Detection." Information Fusion(2025).
[[paper](https://arxiv.org/abs/2505.23214)]
[[code](https://github.com/zhengshuchen/SAMamba)]
[2025.05]

- **TextRegion:** Yao Xiao, Qiqian Fu, Heyi Tao, Yuqun Wu, Zhen Zhu, Derek Hoiem.<br />
"TextRegion: Text-Aligned Region Tokens from Frozen Image-Text Models." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.23769)]
[[code](https://github.com/avaxiao/TextRegion)]
[2025.05]

- **MIAS-SAM:** Marco Colussi, Dragan Ahmetovic, Sergio Mascetti.<br />
"MIAS-SAM: Medical Image Anomaly Segmentation without thresholding." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.22762)]
[[code](https://github.com/warpcut/MIAS-SAM)]
[2025.05]

- **SAM-R1:** Jiaqi Huang, Zunnan Xu, Jun Zhou, Ting Liu, Yicheng Xiao, Mingwen Ou, Bowen Ji, Xiu Li, Kehong Yuan.<br />
"SAM-R1: Leveraging SAM for Reward Feedback in Multimodal Segmentation via Reinforcement Learning." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.22596)]
[2025.05]

- ** ELE-SAM :** Hang Chen, Maoyuan Ye, Peng Yang, Haibin He, Juhua Liu, Bo Du.<br />
"Adapting Segment Anything Model for Power Transmission Corridor Hazard Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.22105)]
[[code](https://github.com/Hhaizee/ELE-SAM)]
[2025.05]

- **InfoSAM:** Yuanhong Zhang, Muyao Yuan, Weizhan Zhang, Tieliang Gong, Wen Wen, Jiangyong Ying, Weijie Shi.<br />
"InfoSAM: Fine-Tuning the Segment Anything Model from An Information-Theoretic Perspective." ICML(2025).
[[paper](https://arxiv.org/abs/2505.21920)]
[2025.05]

- **SANSA::** Claudia Cuttano, Gabriele Trivigno, Giuseppe Averta, Carlo Masone.<br />
"SANSA: Unleashing the Hidden Semantics in SAM2 for Few-Shot Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.21795)]
[[code](https://github.com/ClaudiaCuttano/SANSA)]
[2025.05]

- ** TSP-SAM:** Bilin Wang, Changda Lei, Yunbo Guo, Kaicheng Hong, Xiuji Kan,
Yifan Ouyang, Junbo Li, Rui Li.<br />
"Task-Specific Prompting SAM for Multi-task Gastric Cancer Diagnosis in Endoscopic Images." Expert Systems with Applications(2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S0957417425019487)]
[2025.05]

- Kenneth Ball, Erin Taylor, Nirav Patel, Andrew Bartels, Gary Koplik, James Polly, Jay Hineman.<br />
"Geometric Feature Prompting of Image Segmentation Models." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.21644)]
[[code](https://pypi.org/project/geomprompt/)]
[2025.05]

- **ReaMOT:** Sijia Chen, Yanqiu Yu, En Yu, Wenbing Tao.<br />
"ReaMOT: A Benchmark and Framework for Reasoning-based Multi-Object Tracking." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.20381)]
[[code](https://github.com/chen-si-jia/ReaMOT)]
[2025.05]

- **RoBiS:** Xurui Li, Zhonesheng Jiang, Tingxuan Ai, Yu Zhou.<br />
"RoBiS: Robust Binary Segmentation for High-Resolution Industrial Images." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.21152)]
[[code](https://github.com/xrli-U/RoBiS)]
[2025.05]

- **CCL-LGS:** Lei Tian, Xiaomin Li, Liqian Ma, Hefei Huang, Zirui Zheng, Hao Yin, Taiqing Li, Huchuan Lu, Xu Jia.<br />
"CCL-LGS: Contrastive Codebook Learning for 3D Language Gaussian Splatting." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.20469)]
[[code](https://epsilontl.github.io/CCL-LGS/)]
[2025.05]

- **A3Tune:** Aofei Chang, Le Huang, Alex James Boyd, Parminder Bhatia, Taha Kass-Hout, Cao Xiao, Fenglong Ma.<br />
"Focus on What Matters: Enhancing Medical Vision-Language Models with Automatic Attention Alignment Tuning." ACL (2025).
[[paper](https://arxiv.org/abs/2505.18503)]
[[code](https://github.com/Aofei-Chang/A3Tune)]
[2025.05]

- **VL-SAM-V2:** Zhiwei Lin, Yongtao Wang.<br />
"VL-SAM-V2: Open-World Object Detection with General and Specific Query Fusion." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.18986)]
[2025.05]

- **SAMA:** Ye Sun, Hao Zhang, Henghui Ding, Tiehua Zhang, Xingjun Ma, Yu-Gang Jiang.<br />
"SAMA: Towards Multi-Turn Referential Grounded Video Chat with Large Language Models." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.18812)]
[[code](https://github.com/sunye23/SAMA)]
[2025.05]

- **FHGS:** Q. G. Duan, Benyun Zhao, Mingqiao Han Yijun Huang, Ben M. Chen.<br />
"FHGS: Feature-Homogenized Gaussian Splatting." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.19154)]
[[code](https://fhgs.cuastro.org/)]
[2025.05]

- Nagito Saito, Shintaro Ito, Koichi Ito, Takafumi Aoki.<br />
"Zero-Shot Pseudo Labels Generation Using SAM and CLIP for Semi-Supervised Semantic Segmentation." ICIP(2025).
[[paper](https://arxiv.org/abs/2505.19846)]
[2025.05]

- **PolyCL:** Tyler Ward, Aaron Moseley, Abdullah-Al-Zubaer Imran.<br />
"Domain and Task-Focused Example Selection for Data-Efficient Contrastive Medical Image Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.19208)]
[[code](https://github.com/tbwa233/PolyCL)]
[2025.05]

- Mobina Mansoori, Sajjad Shahabodini, Farnoush Bayatmakou, Jamshid Abouei, Konstantinos N. Plataniotis, Arash Mohammadi.<br />
"Advancements in Medical Image Classification through Fine-Tuning Natural Domain Foundation Models." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.19779)]
[[code](https://github.com/sajjad-sh33/Medical-Transfer-Learning)]
[2025.05]

- **ThinkVideo:** Shiu-hong Kao, Yu-Wing Tai, Chi-Keung Tang.<br />
"ThinkVideo: High-Quality Reasoning Video Segmentation with Chain of Thoughts." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.18561)]
[[code](https://cse.hkust.edu.hk/~skao/thinkvideo.html)]
[2025.05]

- **REN:** Savya Khosla, Sethuraman TV, Barnett Lee, Alexander Schwing, Derek Hoiem.<br />
"REN: Fast and Efficient Region Encodings from Patch-Based Image Encoders." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.18153)]
[[code](https://github.com/savya08/REN)]
[2025.05]

- **TAGS:** Sirui Li, Linkai Peng, Zheyuan Zhang, Gorkem Durak, Ulas Bagci.<br />
"TAGS: 3D Tumor-Adaptive Guidance for SAM." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.17096)]
[2025.05]

- Mahmoud Chick Zaouali, Todd Charter, Homayoun Najjaran.<br />
"From Flight to Insight: Semantic 3D Reconstruction for Aerial Inspection via Gaussian Splatting and Language-Guided Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.17402)]
[2025.05]

- **UWIPL_ETRI :** Cheng-Yen Yang, Hsiang-Wei Huang, Pyong-Kun Kim, Chien-Kai Kuo, Jui-Wei Chang, Kwang-Ju Kim, Chung-I Huang, Jenq-Neng Hwang.<br />
"Adapting SAM 2 for Visual Object Tracking: 1st Place Solution for MMVPR Challenge Multi-Modal Tracking." ICPRW (2025).
[[paper](https://arxiv.org/abs/2505.18111)]
[2025.05]

- **RemoteSAM:** Liang Yao, Fan Liu, Delong Chen, Chuanyi Zhang, Yijun Wang, Ziyun Chen, Wei Xu, Shimin Di, Yuhui Zheng.<br />
"RemoteSAM: Towards Segment Anything for Earth Observation." ACM MM (2025).
[[paper](https://arxiv.org/abs/2505.18022)]
[[code](https://github.com/1e12Leon/RemoteSAM)]
[2025.05]

- **Track Anything Annotate:** Nikita Ivanov, Mark Klimov, Dmitry Glukhikh, Tatiana Chernysheva, Igor Glukhikh.<br />
"Track Anything Annotate: Video annotation and dataset generation of computer vision models." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.17884)]
[[code](https://github.com/lnikioffic/track-anything-annotate)]
[2025.05]

- **H2-COMPACT:** Geeta Chandra Raju Bethala, Hao Huang, Niraj Pudasaini, Abdullah Mohamed Ali, Shuaihang Yuan, Congcong Wen, Anthony Tzes, Yi Fang.<br />
"H2-COMPACT: Human-Humanoid Co-Manipulation via Adaptive Contact Trajectory Policies." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.17627)]
[[code](https://h2compact.github.io/h2compact/)]
[2025.05]

- Martin Villagrana, Francisco Lopez-Tiro, Clement Larose, Gilberto Ochoa-Ruiz, Christian Daul.<br />
"Assessing the generalization performance of SAM for ureteroscopy scene understanding." MIUA (2025).
[[paper](https://arxiv.org/abs/2505.17210)]
[2025.05]

- **BuildingSAM:** Feng, Wenqing and Guan, Fangli and Tu, Jihui and Xu, Wei.<br />
"BuildingSAM: A Dual-Branch Feature-Augmented Segment Anything Model for Remote Sensing Building Extraction." IEEE Geoscience and Remote Sensing Letters (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/10994826)]
[2025.05]

- **SAM-TS:** Jianhong Gan, et al.<br />
"A segmentation method for oral CBCT image based on Segment Anything Model and semi-supervised teacher-student model." ArXiv (2025).
[[paper](https://aapm.onlinelibrary.wiley.com/doi/abs/10.1002/mp.17854)]
[2025.05]

- **MGNet,:** Xia Li, Xinran Liu, Lin Qi, Junyu Dong.<br />
"Weakly supervised camouflaged object detection based on the SAM model and mask guidance." Image and Vision Computing (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S0262885625001593)]
[2025.05]

- **ESAM:** Yuehong Chen, et al.<br />
"Edge-enhanced SAM for extracting photovoltaic power plants from remote sensing imagery." International Journal of Applied Earth
Observation and Geoinformation (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S1569843225002274)]
[2025.05]

- **UPLS:** Luda Tian, et al.<br />
"Attention-based unsupervised prompt learning for SAM in leaf disease segmentation." Knowledge-Based Systems (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S0950705125006987)]
[[code](https://github.com/Tianluda/UPLS)]
[2025.05]

- **DLK:** Nan Mo.<br />
"Brain image registration optimization method via SAM-Med3D multi-scale feature migration." ICBB(2025).
[[paper](https://www.bio-conferences.org/articles/bioconf/abs/2025/25/bioconf_icbb2025_03021/bioconf_icbb2025_03021.html)]
[2025.05]

- **EchoSAM:** Xue Li and Qian Hu and Xiangbo Lin and Yushi Li and Yu Dong and Tong Lin.<br />
"EchoSAM: SAM adaption for unified 2D echocardiography segmentation and ejection fraction calculation." Biomedical Signal Processing and Control (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S1746809425005117)]
[2025.05]

- Zheshuo Lin, et al.<br />
"Deploying Vision Foundation AI Models on the Edge. The SAM2 Experience." ArXiv (2025).
[[paper](https://people.ac.upc.edu/rtous/publications/conf_2025iwann.pdf)]
[2025.05]

- Zhang, J., Chen, X., Yu, M. et al.<br />
"Two-stage landslide satellite image recognition in the southeastern tibet region based on Cascade R-CNN and SAM2." Earth Sci Inform (2025).
[[paper](https://link.springer.com/article/10.1007/s12145-025-01910-0)]
[2025.05]

- **SemiT-SAM:** Jing Hao, Moyun Liu, Lei He, Lei Yao, James Kit Hon Tsoi & Kuo Feng Hung.<br />
"SemiT-SAM: Building A Visual Foundation Model for Tooth Instance Segmentation on Panoramic Radiographs." MICCAI (2024).
[[paper](https://link.springer.com/chapter/10.1007/978-3-031-88977-6_11)]
[[code](https://github.com/isbrycee/SemiTNet)]
[[dataset](https://huggingface.co/datasets/Bryceee/TISI15k-Dataset)]
[2025.05]

- **HF-SAM:** Shangwang Liu, Ruonan Xu.<br />
"Multi-scale feature fusion based SAM for high-quality few-shot medical image segmentation." CVIU (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S1077314225001122)]
[[code](https://github.com/1683194873xrn/HF-SAM)]
[2025.05]

- **MapSAM:** Juncheng Wang and Lei Shang and Wang Lu and Xiangyang Ji and Shujun Wang.<br />
"Model-agnostic personalized adaptation for segment anything model." Neurocomputing (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S0925231225010963)]
[[code](https://github.com/wjc2830/MapSAM.git)]
[2025.05]

- **Eff-SAM:** Nisar Ahmad and Yao-Tien Chen.<br />
"Eff-SAM: SAM-based Efficient Method for Brain Tumor Segmentation in Multimodal 3D MRI Scans." IEEE Access (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/11006993)]
[2025.05]

- **PASS-SAM:** Yin Tang; Rui Chen; Gensheng Pei; Qiong Wang.<br />
"PASS-SAM: Integration of segment anything model for large-scale unsupervised semantic segmentation." Computational Visual Media (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/11007221)]
[[code](https://github.com/PGSmall/jittor-PGSmall-LUSS)]
[2025.05]

- **MASG-SAM:** Zhou, Wei and Guan, Guilin and Gao, Yuan and Si, Pengju and Xu, Mengjia and Yan, Qifeng.<br />
"MASG-SAM: Enhancing Few-Shot Medical Image Segmentation with Multi-Scale Attention and Semantic Guidance." JBHI (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/11006907)]
[[code](https://github.com/ggllllll/MASG-SAM.git)]
[2025.05]

- **COD-SAM:** Dongyang Gao and Yichao Zhou and Hui Yan and Chen Chen and Xiyuan Hu.<br />
"COD-SAM: Camouflage object detection using SAM." Pattern Recognition(2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S0031320325004868)]
[2025.05]

- **SAMba-UNet:** Guohao Huo, Ruiting Dai, Hao Tang.<br />
"SAMba-UNet: Synergizing SAM2 and Mamba in UNet with Heterogeneous Aggregation for Cardiac MRI Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.16304)]
[2025.05]

- **TextureSAM:** Inbal Cohen, Boaz Meivar, Peihan Tu, Shai Avidan, Gal Oren.<br />
"TextureSAM: Towards a Texture Aware Foundation Model for Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.16540)]
[2025.05]

- **InstructSAM:** Yijie Zheng, Weijie Wu, Qingyun Li, Xuehui Wang, Xu Zhou, Aiai Ren, Jun Shen, Long Zhao, Guoqing Li, Xue Yang.<br />
"InstructSAM: A Training-Free Framework for Instruction-Oriented Remote Sensing Object Recognition." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.15818)]
[[code](https://github.com/VoyagerXvoyagerx/InstructSAM)]
[2025.05]

- **GEN2SEG:** Om Khangaonkar, Hamed Pirsiavash.<br />
"GEN2SEG: Generative Models Enable Generalizable Instance Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.15263)]
[[code](https://reachomk.github.io/gen2seg)]
[2025.05]

- **VP Lab:** Niccolo Avogaro, Thomas Frick, Yagmur G. Cinar, Daniel Caraballo, Cezary Skura, Filip M. Janicki, Piotr Kluska, Brown Ebouky, Nicola Farronato, Florian Scheidegger, Cristiano Malossi, Konrad Schindler, Andrea Bartezzaghi, Roy Assaf, Mattia Rigotti.<br />
"VP Lab: a PEFT-Enabled Visual Prompting Laboratory for Semantic Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.15592)]
[2025.05]

- **UWSAM:** Hua Li, Shijie Lian, Zhiyuan Li, Runmin Cong, Sam Kwong.<br />
"UWSAM: Segment Anything Model Guided Underwater Instance Segmentation and A Large-scale Benchmark Dataset." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.15581)]
[[code](https://github.com/LiamLian0727/UIIS10K)]
[2025.05]

- Tatyana Shmykova, Leila Khaertdinova, Ilya Pershin.<br />
"Zero-Shot Gaze-based Volumetric Medical Image Segmentation." CVPRW (2025).
[[paper](https://arxiv.org/abs/2505.15256)]
[2025.05]

- **FSSAM:** Qianxiong Xu, Lanyun Zhu, Xuanyi Liu, Guosheng Lin, Cheng Long, Ziyue Li, Rui Zhao.<br />
"Unlocking the Power of SAM 2 for Few-Shot Segmentation." ICML (2025).
[[paper](https://arxiv.org/abs/2505.14100)]
[2025.05]

- **IPENS:** Wentao Song, He Huang, Youqiang Sun, Fang Qu, Jiaqi Zhang, Longhui Fang, Yuwei Hao, Chenyang Peng.<br />
"IPENS: Interactive Unsupervised Framework for Rapid Plant Phenotyping Extraction via NeRF-SAM2 Fusion." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.13633)]
[2025.05]

- **Long-RVOS:** Tianming Liang, Haichao Jiang, Yuting Yang, Chaolei Tan, Shuai Li, Wei-Shi Zheng, Jian-Fang Hu.<br />
"Long-RVOS: A Comprehensive Benchmark for Long-term Referring Video Object Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.12702)]
[[code](https://isee-laboratory.github.io/Long-RVOS)]
[2025.05]

- **iSegMan:** Yian Zhao, Wanshi Xu, Ruochong Zheng, Pengchong Qiao, Chang Liu, Jie Chen.<br />
"iSegMan: Interactive Segment-and-Manipulate 3D Gaussians." CVPR (2025).
[[paper](https://arxiv.org/abs/2505.11934)]
[[code](https://zhao-yian.github.io/iSegMan)]
[2025.05]

- **InsCore:** Shinichi Mae, Ryosuke Yamada, Hirokatsu Kataoka.<br />
"Industry-focused Synthetic Segmentation Pre-training." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.13099)]
[2025.05]

- Yijie Zheng, Jinxuan Yang, Yu Chen, Yaxuan Wang, Yihang Lu, Guoqing Li.<br />
"Beluga Whale Detection from Satellite Imagery with Point Labels." IGARSS (2025).
[[paper](https://arxiv.org/abs/2505.12066)]
[[code](http://github.com/voyagerxvoyagerx/beluga-seeker)]
[2025.05]

- **AoP-SAM:** Yi Chen, Mu-Young Son, Chuanbo Hua, Joo-Young Kim.<br />
"AoP-SAM: Automation of Prompts for Efficient Segmentation." AAAI (2025).
[[paper](https://arxiv.org/abs/2505.11980)]
[2025.05]

- **SurgPose:** Utsav Rai, Haozheng Xu, Stamatia Giannarou.<br />
"SurgPose: Generalisable Surgical Instrument Pose Estimation using Zero-Shot Learning and Stereo Vision." ICRA (2025).
[[paper](https://arxiv.org/abs/2505.11439)]
[2025.05]

- **uLLSAM:** Manyu Li, Ruian He, Zixian Zhang, Weimin Tan, Bo Yan.<br />
"Unifying Segment Anything in Microscopy with Multimodal Large Language Model." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.10769)]
[[code](https://github.com/ieellee/uLLSAM)]
[2025.05]

- **ISGR:** Dayong Liang, Changmeng Zheng, Zhiyuan Wen, Yi Cai, Xiao-Yong Wei, Qing Li.<br />
"Seeing Beyond the Scene: Enhancing Vision-Language Models with Interactional Reasoning." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.09118)]
[[code](https://github.com/open_upon_acceptance)]
[2025.05]

- **PPT-net:** Guoying Liang ,Su Yang.<br />
"Promoting SAM for Camouflaged Object Detection via Selective Key Point-based Guidance." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.09123)]
[2025.05]

- Mohammad Wasil, Ahmad Drak, Brennan Penfold, Ludovico Scarton, Maximilian Johenneken, Alexander Asteroth, Sebastian Houben.<br />
"Parameter-Efficient Fine-Tuning of Vision Foundation Model for Forest Floor Segmentation from UAV Imagery."  IEEE ICRA Workshop (2025).
[[paper](https://arxiv.org/abs/2505.08932)]
[2025.05]

- **ReSurgSAM2:** Haofeng Liu, Mingqi Gao, Xuxiao Luo, Ziyue Wang, Guanyi Qin, Junde Wu, Yueming Jin.<br />
"ReSurgSAM2: Referring Segment Anything in Surgical Video via Credible Long-term Tracking." MICCAI (2025).
[[paper](https://arxiv.org/abs/2505.08581)]
[[code](https://github.com/jinlab-imvr/ReSurgSAM2)]
[2025.05]

- **DFG:** Zheang Huai, Hui Tang, Yi Li, Zhuangzhuang Chen, Xiaomeng Li.<br />
"Leveraging Segment Anything Model for Source-Free Domain Adaptation via Dual Feature Guided Auto-Prompting." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.08527)]
[[code](https://github.com/zheangh/DFG)]
[2025.05]

- **SLAG:** Laszlo Szilagyi, Francis Engelmann, Jeannette Bohg.<br />
"SLAG: Scalable Language-Augmented Gaussian Splatting." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.08124)]
[[code](https://slag-project.github.io/)]
[2025.05]

- **CPC-SAM:** Jingyao Wang, Jianqi Zhang, Wenwen Qiang, Changwen Zheng.<br />
"Causal Prompt Calibration Guided Segment Anything Model for Open-Vocabulary Multi-Entity Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.06524)]
[[code](https://github.com/WangJingyao07/CPC-SAM)]
[2025.05]

- **MarkMatch:** Fei Zhao, Runlin Zhang, Chengcui Zhang, Nitesh Saxena.<br />
"MarkMatch: Same-Hand Stuffing Detection." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.07032)]
[2025.05]

- **MAIS:** Mauricio Orbes-Arteaga, Oeslle Lucena, Sabastien Ourselin, M. Jorge Cardoso.<br />
"MAIS: Memory-Attention for Interactive Segmentation." MIDL (2025).
[[paper](https://arxiv.org/abs/2505.07511)]
[2025.05]

- **ABS-Mamba:** Feng Yuan, Yifan Gao, Wenbin Wu, Keqing Wu, Xiaotong Guo, Jie Jiang, Xin Gao.<br />
"ABS-Mamba: SAM2-Driven Bidirectional Spiral Mamba Network for Medical Image Translation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.07687)]
[[code](https://github.com/gatina-yone/ABS-Mamba)]
[2025.05]

- **SAMSR:** Zihang Liu, Zhenyu Zhang, Hao Tang.<br />
"Semantic-Guided Diffusion Model for Single-Step Image Super-Resolution." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.07071)]
[[code](https://github.com/Liu-Zihang/SAMSR)]
[2025.05]

- **BrainSegDMlF:** Hongming Wang, Yifeng Wu, Huimin Huang, Hongtao Wu, Jia-Xuan Jiang, Xiaodong Zhang, Hao Zheng, Xian Wu, Yefeng Zheng, Jinping Xu, Jing Cheng.<br />
"BrainSegDMlF: A Dynamic Fusion-enhanced SAM for Brain Lesion Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.06133)]
[2025.05]

- **SLCA:** Pengfei Gu, Haoteng Tang, Islam A. Ebeid, Jose A. Nunez, Fabian Vazquez, Diego Adame, Marcus Zhan, Huimin Li, Bin Fu, Danny Z. Chen.<br />
"Adapting a Segmentation Foundation Model for Medical Image Classification." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.06217)]
[2025.05]

- **SAMSelect :** Joost van Dalen, Yuki M. Asano, Marc Rußwurm.<br />
"SAMSELECT: A SPECTRAL INDEX SEARCH FOR MARINE DEBRIS VISUALIZATION USING SAM." ICLR Workshop (2025).
[[paper](https://ml-for-rs.github.io/iclr2025/camera_ready/papers/50.pdf)]
[2025.05]

- **TP-SA3M:** Li, T., Jiang, Z., Jin, Y. et al.<br />
"TP-SA3M: text prompts-assisted SAM for myopic maculopathy segmentation." Vis Comput (2025).
[[paper](https://link.springer.com/article/10.1007/s00371-025-03892-y)]
[2025.05]

- Wu, Z., Yang, JY., Yan, CB. et al.<br />
"Integrating SAM priors with U-Net for enhanced multiclass cell detection in digital pathology." Sci Rep (2025).
[[paper](https://www.nature.com/articles/s41598-025-99278-0)]
[2025.05]

- **SAMSAR:** Mahdi Rahimi, Saeed Sharifian.<br />
"SAMSAR: A modified SAM architecture for oceanic ship segmentation of satellite SAR images using CNN-based Cross-Fused Attention." ESWA (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S0957417425014745)]
[2025.05]

- **SAMSnake:** Yejun Wu and Jiao Zhan and Chi Guo and Huyin Zhang.<br />
"SAMSnake: A generic contour-based instance segmentation network assistedby Efficient Segment Anything Model." Neural Networks (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S0893608025003703)]
[[code](https://github.com/Giansar-Wu/SAMSnake)]
[2025.05]

- Tao, Kunjian, He Li, Chong Huang, Qingsheng Liu, Junyan Zhang, and Ruoqi Du.<br />
"Extraction of Cropland Based on Multi-Source Remote Sensing and an Improved Version of the Deep Learning-Based Segment Anything Model (SAM)." Agronomy (2025).
[[paper](https://www.mdpi.com/2073-4395/15/5/1139)]
[2025.05]

- **UncertainSAM:** Timo Kaiser, Thomas Norrenbrock, Bodo Rosenhahn.<br />
"UncertainSAM: Fast and Efficient Uncertainty Quantification of the Segment Anything Model." ICML (2025).
[[paper](https://arxiv.org/abs/2505.05049)]
[2025.05]

- **Mix-QSAM:** Navin Ranjan, Andreas Savakis.<br />
"Mix-QSAM: Mixed-Precision Quantization of the Segment Anything Model." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.04861)]
[2025.05]

- **CAPNet:** Baoshun Shi, Zheng Liu, Xin Meng, Yan Yang.<br />
"Cross-organ all-in-one parallel compressed sensing magnetic resonance imaging." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.04658)]
[[code](https://github.com/shibaoshun/CAPNet)]
[2025.05]

- **MAISY:** Andrew Zhang, Hao Wang, Shuchang Ye, Michael Fulham, Jinman Kim.<br />
"MAISY: Motion-Aware Image SYnthesis for Medical Image Motion Correction." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.04105)]
[2025.05]

- **CaRaFFusion:** Huawei Sun, Bora Kunter Sahin, Georg Stettinger, Maximilian Bernhard, Matthias Schubert, Robert Wille.<br />
"CaRaFFusion: Improving 2D Semantic Segmentation with Camera-Radar Point Cloud Fusion and Zero-Shot Image Inpainting." RA-L(2025).
[[paper](https://arxiv.org/abs/2505.03679)]
[2025.05]

- Siming He, Zachary Osman, Fernando Cladera, Dexter Ong, Nitant Rai, Patrick Corey Green, Vijay Kumar, Pratik Chaudhari.<br />
"Estimating the Diameter at Breast Height of Trees in a Forest With a Single 360 Camera." ICRA Workshop (2025).
[[paper](https://arxiv.org/abs/2505.03093)]
[2025.05]

- **SARTM:** Dong Xing, Xianxun Zhu, Wei Zhou, Qika Lin, Hang Yang, Yuqing Wang.<br />
"Segment Any RGB-Thermal Model with Language-aided Distillation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.01950)]
[2025.05]

- **SLM-SAM 2:** Yuwen Chen, Zafer Yildiz, Qihang Li, Yaqian Chen, Haoyu Dong, Hanxue Gu, Nicholas Konz, Maciej A. Mazurowski.<br />
"Accelerating Volumetric Medical Image Annotation via Short-Long Memory SAM 2." TMI (2025).
[[paper](https://arxiv.org/abs/2505.01854)]
[2025.05]

- **SAM-TIFF:** Michael Marinaccio, Fatemeh Afghah.<br />
"Seeing Heat with Color - RGB-Only Wildfire Temperature Inference from SAM-Guided Multimodal Distillation using Radiometric Ground Truth." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.01638)]
[2025.05]

- **ZS-VCOS:** Wenqi Guo, Shan Du.<br />
"ZS-VCOS: Zero-Shot Outperforms Supervised Video Camouflaged Object Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.01431)]
[[code](https://github.com/weathon/vcos)]
[2025.05]

- Malte Mosbach, Sven Behnke.<br />
"Prompt-responsive Object Retrieval with Memory-augmented Student-Teacher Learning." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.02232)]
[[code](https://memory-student-teacher.github.io)]
[2025.05]

- **MoSAM:** Qiushi Yang, Yuan Yao, Miaomiao Cui, Liefeng Bo.<br />
"MoSAM: Motion-Guided Segment Anything Model with Spatial-Temporal Memory Selection." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.00739)]
[2025.05]

- Yamagishi Y, Hanaoka S, Kikuchi T, Nakao T, Nakamura Y, Nomura Y, Miki S, Yoshikawa T, Abe O.<br />
"Using Segment Anything Model 2 for Zero-Shot 3D Segmentation of Abdominal Organs in Computed Tomography Scans to Adapt Video Tracking Capabilities for 3D Medical Imaging: Algorithm Development and Validation." JMIR AI (2025).
[[paper](https://ai.jmir.org/2025/1/e72109)]
[2025.05]

- Chen, Jinlong, Fuqiang Jin, Yingjie Jiao, Yongsong Zhan, and Xingguo Qin.<br />
"Improving Dynamic Gesture Recognition with Attention-Enhanced LSTM and Grounding SAM." Electronics (2025).
[[paper](https://www.mdpi.com/2079-9292/14/9/1793)]
[2025.05]

- Angelo Moroncelli and Sylvain Populus and Armand Rossi and Emanuele Carpanzano and Loris Roveda.<br />
"Vision-based robotic disassembly of aircraft engines with YOLO-SAM: a novel method for task orientation estimation." CIRP Annals (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S0007850625001106)]
[2025.05]

- **ICA-SAMv7:** Xiaotian Yan and Yuting Guo and Ziyi Pei and Xinyu Zhang and Jinghao Li and Zitao Zhou and Lifang Liang and Shuai Li and Peng Lun and Aimin Hao.<br />
"ICA-SAMv7: Internal carotid artery segmentation with coarse to fine network." Computerized Medical Imaging and Graphics (2025).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S0895611125000643)]
[[code](https://github.com/BessiePei/ICA-SAMv7)]
[2025.05]

- Muturi, T. W., & Adu-Gyamfi, Y.<br />
"Enhanced Crack Segmentation Using Meta’s Segment Anything Model with Low-Cost Ground Truths and Multimodal Prompts." ArXiv (2025).
[[paper](https://journals.sagepub.com/doi/abs/10.1177/03611981251322484)]
[2025.05]

- **UN-SAM:** Zhen Chen and Qing Xu and Xinyu Liu and Yixuan Yuan.<br />
"UN-SAM: Domain-adaptive self-prompt segmentation for universal nuclei images." Medical Image Analysis (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S1361841525001549)]
[[code](https://github.com/CUHK-AIM-Group/UN-SAM)]
[2025.05]

- Milman, Oded, Dovi Yellin, and Yehudit Aperstein.<br />
"Adapting SAM for Visible-Light Pupil Segmentation Baseline." Electronics (2025).
[[paper](https://www.mdpi.com/2079-9292/14/9/1850)]
[2025.05]

- **SV-Unet:** Wei Wang and Chong Yu and Tengyu Zhang and Feiyu Chen and Yufan Liu and Zongze Wu.<br />
"Oversized ore segmentation using SAM-enhanced U-Net with self-supervised pre-training and semi-supervised self-training." Expert Systems with Applications (2025).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S095741742501601X)]
[2025.05]

- **SAM-Brain3D:** Zhongying Deng, Haoyu Wang, Ziyan Huang, Lipei Zhang, Angelica I. Aviles-Rivero, Chaoyu Liu, Junjun He, Zoe Kourtzi, Carola-Bibiane Schönlieb.<br />
"Brain Foundation Models with Hypergraph Dynamic Adapter for Brain Disease Analysis." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.00627)]
[2025.05]

- Shuang Zhang, Carleton Coffin, Karyn L. Rogers, Catherine Ann Royer, Ge Wang.<br />
"AI-Driven High-Resolution Cell Segmentation and Quantitative Analysis." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.00578)]
[2025.05]

- **IDRA-H:** Marc Glocker, Peter Hönig, Matthias Hirschmanner, Markus Vincze.<br />
"LLM-Empowered Embodied Agent for Memory-Augmented Task Planning in Household Robotics." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.21716)]
[[code](https://github.com/marc1198/chat-hsr)]
[2025.04]

- **SAM4EM:** Uzair Shah, Marco Agus, Daniya Boges, Vanessa Chiappini, Mahmood Alzubaidi, Jens Schneider, Markus Hadwiger, Pierre J. Magistretti, Mowafa Househ, Corrado Calı.<br />
"SAM4EM:Efficient memory-based two stage prompt-free segment anything model adapter for complex 3D neuroscience electron microscopy stacks." CVPRW (2025).
[[paper](https://arxiv.org/abs/2504.21544)]
[[code](https://github.com/Uzshah/SAM4EM)]
[2025.04]

- **UniBiomed:** Linshan Wu, Yuxiang Nie, Sunan He, Jiaxin Zhuang, Hao Chen.<br />
"UniBiomed: A Universal Foundation Model for Grounded Biomedical Image Interpretation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.21336)]
[2025.04]

- **RadSAM:** Julien Khlaut, Elodie Ferreres, Daniel Tordjman, Hélène Philippe, Tom Boeken, Pierre Manceron, Corentin Dancette.<br />
"RadSAM: Segmenting 3D radiological images with a 2D promptable model." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.20837)]
[2025.04]

- **RRL-MedSAM:** Jia Wang, Yunan Mei, Jiarui Liu, and Xin Fan.<br />
"SAM-Guided Robust Representation Learning for One-Shot 3D Medical Image Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.20501)]
[2025.04]

- **Follow Everything:** Qianyi Zhang, Shijian Ma, Boyi Liu, Jingtai Liu, Jianhao Jiao, Dimitrios Kanoulas.<br />
"Follow Everything: A Leader-Following and Obstacle Avoidance Framework with Goal-Aware Adaptation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.19399)]
[[code](https://follow-everything.github.io/)]
[2025.04]

- **Res-SAM:** Xiren Zhou, Shikang Liu, Xinyu Yan, Yizhan Fan, Xiangyu Wang, Yu Kang, Jian Cheng, Huanhuan Chen.<br />
"Reservoir-enhanced Segment Anything Model for Subsurface Diagnosis." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.18802)]
[2025.04]

- **RSFR:** Jiahao Huang, Fanwen Wang, Pedro F. Ferreira, Haosen Zhang, Yinzhe Wu, Zhifan Gao, Lei Zhu, Angelica I. Aviles-Rivero, Carola-Bibiane Schonlieb, Andrew D. Scott, Zohya Khalique, Maria Dwornik, Ramyah Rajakulasingam, Ranil De Silva, Dudley J. Pennell, Guang Yang, Sonia Nielles-Vallespin.<br />
"RSFR: A Coarse-to-Fine Reconstruction Framework for Diffusion Tensor Cardiac MRI with Semantic-Aware Refinement." Medical Image Analysis (2025).
[[paper](https://arxiv.org/abs/2504.18520)]
[2025.04]

- **Tooth-ASAM:** Peijuan Wang, Hanjie Gu & Yuliang Sun.<br />
"Tooth segmentation on multimodal images using adapted segment anything model." Scientific Reports (2025).
[[paper](https://www.nature.com/articles/s41598-025-96301-2)]
[2025.04]

- Zhang, N., Ling, H., Zhang, W. et al.<br />
"A prediction method for radiation proctitis based on SAM-Med2D model." Scientific Reports (2025).
[[paper](https://www.nature.com/articles/s41598-025-87409-6)]
[2025.04]

- **ToothSC-SAM:** Li, C., Cheng Wang and Zhanchuan Cai.<br />
"ToothSC-SAM: A Novel Network Model Based on Skip-Connections and SAM for Tooth Segmentation in CBCT Images." ArXiv (2025).
[[paper](https://www.preprints.org/manuscript/202504.1562)]
[2025.04]

- **FLSSAM:** Li, Jiayuan and Wang, Zhen and Xu, Nan and You, Zhuhong.<br />
"Fine-Tuning SAM for Forward-Looking Sonar with Collaborative Prompts and Embedding." LGRS (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/10969803)]
[[code](https://github.com/darkseid-arch/FLSSAM)]
[2025.04]

- **IIIM-SAM:** Zhang, Zhe and Zhou, Yuhang and Yue, Jiahe and Zhang, Runchu and Ma, Jie.<br />
"IIIM-SAM: Zero-shot Texture Anomaly Detection Without External Prompts." IEEE TASE (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/10967541)]
[2025.04]

- **MIT-SAM:** Zhou, Xichuan and Yan, Lingfeng and Ding, Rui and Atabansi, Chukwuemeka Clinton and Nie, Jing and Chen, Lihui and Feng, Yujie and Liu, Haijun.<br />
"MIT-SAM: Medical Image-Text SAM with Mutually Enhanced Heterogeneous Features Fusion for Medical Image Segmentation." IEEE JBHI (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/10966035)]
[[code](https://github.com/jojodan514/MIT-SAM)]
[2025.04]

- **PTSAM:** Tristan Piater, Björn Barz, Alexander Freytag.<br />
"Prompt-Tuning SAM: From Generalist to Specialist with only 2,048 Parameters and 16 Training Images." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.16739)]
[2025.04]

- Boyue Xu, Ruichao Hou, Tongwei Ren, Gangshan Wu.<br />
"RGB-DVideo Object Segmentation via Enhanced Multi-store Feature Memory." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.16471)]
[2025.04]

- **AffordanceSAM:** Dengyang Jiang, Mengmeng Wang, Teli Ma, Hengzhuang Li, Yong liu, Guang Dai, Lei Zhang.<br />
"AffordanceSAM: Segment Anything Once More in Affordance Grounding." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.15650)]
[2025.04]

- **FS-DINO:** Wei Zhuo, Zhiyue Tang, Wufeng Xue, Hao Ding, Linlin Shen.<br />
"DINOv2-powered Few-Shot Semantic Segmentation: A Unified Framework via Cross-Model Distillation and 4D Correlation Mining." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.15669)]
[2025.04]

- **LSR-ST:** Guoyi Zhang, Siyang Chen, Guangsheng Xu, Han Wang, Xiaohu Zhang.<br />
"Vision-Centric Representation-Efficient Fine-Tuning for Robust Universal Foreground Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.14481)]
[2025.04]

- **EmoSEM:** Jing Zhang, Dan Guo, Zhangbin Li, Meng Wang.<br />
"EmoSEM: Segment and Explain Emotion Stimuli in Visual Art." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.14658)]
[2025.04]

- **SAC:** Ghodsiyeh Rostami, Po-Han Chen, Mahdi S. Hosseini.<br />
"Segment Any Crack: Deep Semantic Segmentation Adaptation for Crack Detection." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.14138)]
[2025.04]

- **HSACNet:** Qi'ao Xu, Pengfei Wang, Yanjun Li, Tianwen Qian, Xiaoling Wang.<br />
"HSACNet: Hierarchical Scale-Aware Consistency Regularized Semi-Supervised Change Detection." ICME (2025).
[[paper](https://arxiv.org/abs/2504.13428)]
[2025.04]

- Oliver Mills, Philip Conaghan, Nishant Ravikumar, Samuel Relton.<br />
"Putting the Segment Anything Model to the Test with 3D Knee MRI -- A Comparison with State-of-the-Art Performance." BMVC (2024).
[[paper](https://arxiv.org/abs/2504.13340)]
[[code](https://github.com/oliverjm1/BMVC_menisc_seg)]
[2025.04]

- **ProtoSAM-2D:** Yiqing Shen, David Dreizin, Blanca Inigo, Mathias Unberath.<br />
"ProtoSAM-2D: 2D semantic Segment Anything Model with mask-level prototype-learning and distillation." ArXiv (2025).
[[paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13406/1340605/ProtoSAM-2D--2D-semantic-Segment-Anything-Model-with-mask/10.1117/12.3047044.short)]
[2025.04]

- **GlomSAM:** Pan, S., Tang, X., Chen, B., Lai, X., & Jin, W.<br />
"GlomSAM: Hybrid customized SAM for multi-glomerular detection and segmentation in immunofluorescence images." PLOS ONE (2025).
[[paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0321096)]
[2025.04]

- **STSAMNet:** Yang, M., Yang, R., Wang, M., Xu, H., & Xu, G.<br />
"Integrating unsupervised domain adaptation and SAM technologies for image semantic segmentation: a case study on building extraction from high-resolution remote sensing images." International Journal of Digital Earth (2025).
[[paper](https://www.tandfonline.com/doi/full/10.1080/17538947.2025.2491108)]
[2025.04]

- **SAMBV:** Yuhan Wang and Shoujun Zhou and Ke Lu and Yuanquan Wang and Lei Zhang and Weipeng Liu and Zhida Wang.<br />
"SAMBV: A Fine-tuned SAM with Interpolation Consistency Regularization for Semi-supervised Bi-ventricle Segmentation from Cardiac MRI." Medical Engineering & Physics (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S1350453325000608)]
[2025.04]

- Gutiérrez, Juan D., Emilio Delgado, Carlos Breuer, José M. Conejero, and Roberto Rodriguez-Echeverria.<br />
"Prompt Once, Segment Everything: Leveraging SAM 2 Potential for Infinite Medical Image Segmentation with a Single Prompt." Algorithms(2025).
[[paper](https://www.mdpi.com/1999-4893/18/4/227)]
[2025.04]

- **DepthForge:** Siyu Chen, Ting Han, Changshe Zhang, Xin Luo, Meiliu Wu, Guorong Cai, Jinhe Su.<br />
"Stronger, Steadier & Superior: Geometric Consistency in Depth VFM Forges Domain Generalized Semantic Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.12753)]
[[code](https://github.com/anonymouse-xzrptkvyqc/DepthForge)]
[2025.04]

-**SAM-ESP:** Xinyu Zhao, Jun Liu, Faqiang Wang, Li Cui, Yuping Duan.<br />
"Contour Field based Elliptical Shape Prior for the Segment Anything Model." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.12556)]
[2025.04]

- **FAEWNet:** Yun-Cheng Li, Sen Lei, Yi-Tao Zhao, Heng-Chao Li, Jun Li, Antonio Plaza.<br />
"SAM-Based Building Change Detection with Distribution-Aware Fourier Adaptation and Edge-Constrained Warping." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.12619)]
[[code](https://github.com/SUPERMAN123000/FAEWNet)]
[2025.04]

- **DC-SAM:** Mengshi Qi, Pengfei Zhu, Xiangtai Li, Xiaoyang Bi, Lu Qi, Huadong Ma, Ming-Hsuan Yang.<br />
"DC-SAM: In-Context Segment Anything in Images and Videos via Dual Consistency." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.12080)]
[[code](https://github.com/zaplm/DC-SAM)]
[2025.04]

- **CAGS:** Wei Sun, Yanzhao Zhou, Jianbin Jiao, Yuan Li.<br />
"CAGS: Open-Vocabulary 3D Scene Understanding with Context-Aware Gaussian Splatting." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.11893)]
[2025.04]

- **PathSeqSAM:** Mingyang Zhu, Yinting Liu, Mingyu Li, Jiacheng Wang.<br />
"PathSeqSAM: Sequential Modeling for Pathology Image Segmentation with SAM2." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.10526)]
[[code](https://github.com/JackyyyWang/PathSeqSAM)]
[2025.04]

- **Robust SAM:** Long, J., Xu, Z., Jiang, T., Yao, W., Jia, S., Ma, C., & Chen, X.<br />
"Robust SAM: On the Adversarial Robustness of Vision Foundation Models." AAAI (2025).
[[paper](https://ojs.aaai.org/index.php/AAAI/article/view/32616)]
[2025.04]

- Jiahuan Long, Tingsong Jiang, Wen Yao, Yizhe Xiong, Zhengqin Xu, Shuai Jia, Chao Ma.<br />
"Parameter-Free Fine-tuning via Redundancy Elimination for Vision Foundation Models." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.08915)]
[2025.04]

- **AerOSeg:** Saikat Dutta, Akhil Vasim, Siddhant Gole, Hamid Rezatofighi, Biplab Banerjee.<br />
"AerOSeg: Harnessing SAM for Open-Vocabulary Segmentation in Remote Sensing Images." CVPRW (2025).
[[paper](https://arxiv.org/abs/2504.09203)]
[2025.04]

- **MoSE:** Jia Wei, Xiaoqi Zhao, Jonghye Woo, Jinsong Ouyang, Georges El Fakhri, Qingyu Chen, Xiaofeng Liu.<br />
"Mixture-of-Shape-Experts (MoSE): End-to-End Shape Dictionary Framework to Prompt SAM for Generalizable Medical Segmentation." CVPRW (2025).
[[paper](https://arxiv.org/abs/2504.09601)]
[2025.04]

- **ToolTipNet:** Zijian Wu, Shuojue Yang, Yueming Jin, Septimiu E Salcudean.<br />
"ToolTipNet: A Segmentation-Driven Deep Learning Baseline for Surgical Instrument Tip Detection." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.09700)]
[2025.04]

- **ATOMIC:** Jingyun Yang, Ruoyan Avery Yin, Chi Jiang, Yuepeng Hu, Xiaokai Zhu, Xingjian Hu, Sutharsika Kumar, Xiao Wang, Xiaohua Zhai, Keran Rong, Yunyue Zhu, Tianyi Zhang, Zongyou Yin, Jing Kong, Neil Zhenqiang Gong, Zhichu Ren, Haozhe Wang.<br />
"Zero-shot Autonomous Microscopy for Scalable and Intelligent Characterization of 2D Materials." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.10281)]
[2025.04]

- Yiwen Wang, Ying Liang, Yuxuan Zhang, Xinning Chai, Zhengxue Cheng, Yingsheng Qin, Yucai Yang, Rong Xie, Li Song.<br />
"Enhanced Semantic Extraction and Guidance for UGC Image Super Resolution." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.09887)]
[[code](https://github.com/Moonsofang/NTIRE-2025-SRlab)]
[2025.04]

- **STSeg:** Kehuan Song, Xinglin Xie, Kexin Zhang, Licheng Jiao, Lingling Li, Shuyuan Yang.<br />
"STSeg- Complex Video Object Segmentation: The 1st Solution for 4th PVUW MOSE Challenge." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.08306)]
[2025.04]

- **MASSeg:** Xuqiang Cao, Linnan Zhao, Jiaxuan Zhao, Fang Liu, Puhua Chen, Wenping Ma.<br />
"MASSeg: 2nd Technical Report for 4th PVUW MOSE Track." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.10254)]
[[code](https://github.com/cxqNet/MASSeg)]
[2025.04]

- **FVOS:** Mengjiao Wang, Junpei Zhang, Xu Liu, Yuting Yang, Mengru Ma.<br />
"FVOS for MOSE Track of 4th PVUW Challenge: 3rd Place Solution." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.09507)]
[2025.04]

- **SynthFM:** Sourya Sengupta, Satrajit Chakrabarty, Keerthi Sravan Ravi, Gopal Avinash, Ravi Soni.<br />
"SynthFM: Training Modality-agnostic Foundation Models for Medical Image Segmentation without Real Medical Data." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.08177)]
[2025.04]

- **FMLGS:** Xin Tan, Yuzhou Ji, He Zhu, and Yuan Xie.<br />
"FMLGS: Fast Multilevel Language Embedded Gaussians for Part-level Interactive Agents." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.08581)]
[2025.04]

- **ChildlikeSHAPES:** Astitva Srivastava, Harrison Jesse Smith, Thu Nguyen-Phuoc, Yuting Ye.<br />
"ChildlikeSHAPES: Semantic Hierarchical Region Parsing for Animating Figure Drawings." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.08022)]
[2025.04]

- **FindAnything:** Sebastián Barbas Laina, Simon Boche, Sotiris Papatheodorou, Simon Schaefer, Jaehyung Jung, Stefan Leutenegger.<br />
"FindAnything: Open-Vocabulary and Object-Centric Mapping for Robot Exploration in Any Environment." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.08603)]
[2025.04]

- **WS-SAM:** Zhang, Z., Ma, F., Liu, H. et al.<br />
"WS-SAM: self-prompting SAM with wavelet and spatial domain for OCTA retinal vessel segmentation." The Journal of Supercomputing (2025).
[[paper](https://link.springer.com/article/10.1007/s11227-025-07136-7)]
[2025.04]

- Anbalagan, N., Balraj, N., Jayasingh, N., & Thangavel, P.<br />
"Brain tumor detection using segment anything model." AIP Conference Proceedings(2025).
[[paper](https://pubs.aip.org/aip/acp/article-abstract/3279/1/020034/3341679/Brain-tumor-detection-using-segment-anything-model)]
[2025.04]

- Amirkhosro Kazemi, Aryan Ghazipour, Tyler Settle, Marcus F. Stoddard, and Amir A.<br />
"Semi-automated segmentation of magnitude images in 4D flow MR scans using segment anything model 2 (SAM 2)." Medical Imaging 2025: Clinical and Biomedical Imaging(2025).
[[paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13410/1341026/Semi-automated-segmentation-of-magnitude-images-in-4D-flow-MR/10.1117/12.3051724.short)]
[2025.04]

- **MIRSAM:** Zhang, M., Xu, Q., Wang, Y. et al.<br />
"MIRSAM: multimodal vision-language segment anything model for infrared small target detection." Visual Intelligence.(2025).
[[paper](https://link.springer.com/article/10.1007/s44267-025-00075-0)]
[2025.04]

- **DPSAM:** Peng Liu, Jinhong Deng, Lixin Duan, Wen Li, and Fengmao Lv.<br />
"Segmenting Anything in the Dark via Depth Perception." TMM (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/10948332)]
[[code](https://github.com/liupeng3425/DPSAM)]
[2025.04]

- Jinlong Huang, Xiao Sun, and Lisheng Wang.<br />
"Enhancing Foundation Model Robustness for Multi-center Real-World Medical Image Analysis." ArXiv (2025).
[[paper](https://books.google.com.hk/books?hl=zh-CN&lr=&id=ZlJTEQAAQBAJ&oi=fnd&pg=PA13&ots=rpVvxFnfBj&sig=7GtZgjpOlB3-QPAYJHSidJV_Ie0&redir_esc=y#v=onepage&q&f=false)]
[2025.04]

- **UV-AdaptFormer:** Feng, W., Guan, F., Tu, J., & Xu, W.<br />
"UV-AdaptFormer: adapting the segment anything model for urban village identification from high-resolution satellite imagery." Remote Sensing Letters (2025).
[[paper](https://www.tandfonline.com/doi/abs/10.1080/2150704X.2025.2488533)]
[2025.04]

- **LORA-MedSAM:** Hu, Jiamin, Xu, Xuwei, and Zou, Zhenmin.<br />
"LORA-MedSAM: Efficient Medical Image Segmentation." Lecture Notes in Electrical Engineering(2025).
[[paper](https://books.google.com.hk/books?hl=zh-CN&lr=&id=xIxTEQAAQBAJ&oi=fnd&pg=PA154&ots=BwyxPqC4QD&sig=CAdAI8IjLDTiX_PUOS6f1mpf6bI&redir_esc=y#v=onepage&q&f=false)]
[2025.04]

- **BuildWin-SAM:** Li, Zhengnan and Yan, Yizhen and Huang, Bo.<br />
"BuildWin-SAM: An Improved SAM-Based Method for Extracting Building Windows From Street View Images." IEEE Access (2025).
[[paper](https://ieeexplore.ieee.org/document/10955328)]
[[code](https://github.com/zhengnanle/svbw)]
[2025.04]

- Li, Hao, Jianxi Yang, Shixin Jiang, and Xiaoxia Yang.<br />
"SAM-Guided Concrete Bridge Damage Segmentation with Mamba–ResNet Hierarchical Fusion Network." Electronics (2025).
[[paper](https://www.mdpi.com/2079-9292/14/8/1497)]
[2025.04]

- Takashi Nagaoka.<br />
"Accurate Segmentation of Pigmented Skin Lesions Using Grounded-segment-anything." J Med Imaging Case Rep (2025).
[[paper](https://medimagingcasereports.com/micr/articles/v9n1/micr-116-takashi-nagaoka.pdf)]
[2025.04]

- **SAMJAM:** Joshua Li, Fernando Jose Pena Cantu, Emily Yu, Alexander Wong, Yuchen Cui, Yuhao Chen.<br />
"SAMJAM:Zero-Shot Video Scene Graph Generation for Egocentric Kitchen Videos." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.07867)]
[2025.04]

- **RP-SAM2:** Nuren Zhaksylyk, Ibrahim Almakky, Jay Paranjape, S. Swaroop Vedula, Shameema Sikder, Vishal M. Patel, Mohammad Yaqub.<br />
"RP-SAM2: Refining Point Prompts for Stable Surgical Instrument Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.07117)]
[[code](https://github.com/BioMedIA-MBZUAI/RP-SAM2)]
[2025.04]

- **MovSAM:** Chang Nie, Yiqing Xu, Guangming Wang, Zhe Liu, Yanzi Miao, Hesheng Wang.<br />
"MovSAM: A Single-image Moving Object Segmentation Framework Based on Deep Thinking." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.06863)]
[[code](https://github.com/IRMVLab/MovSAM)]
[2025.04]

- Marco Acerbis, Nataša Sladoje, Joakim Lindblad.<br />
"A Comparison of Deep Learning Methods for Cell Detection in Digital Cytology." SCIA (2025).
[[paper](https://arxiv.org/abs/2504.06957)]
[2025.04]

- **Wheat3DGS:** Daiwei Zhang, Joaquin Gajardo, Tomislav Medic, Isinsu Katircioglu, Mike Boss, Norbert Kirchgessner, Achim Walter, Lukas Roth.<br />
"Wheat3DGS: In-field 3D Reconstruction, Instance Segmentation and Phenotyping of Wheat Heads with Gaussian Splatting." CVPRW (2025).
[[paper](https://arxiv.org/abs/2504.06978)]
[[code](https://zdwww.github.io/wheat3dgs/)]
[2025.04]

- **econSG:** Can Zhang, Gim Hee Lee.<br />
"econSG: Efficient and Multi-view Consistent Open-Vocabulary 3D Semantic Gaussians." ICLR (2025).
[[paper](https://arxiv.org/abs/2504.06003)]
[[code](https://lulusindazc.github.io/econSGproject/)]
[2025.04]

- **CAT-V:** Yunlong Tang, Jing Bi, Chao Huang, Susan Liang, Daiki Shimada, Hang Hua, Yunzhong Xiao, Yizhi Song, Pinxin Liu, Mingqian Feng, Junjia Guo, Zhuo Liu, Luchuan Song, Ali Vosoughi, Jinxi He, Liu He, Zeliang Zhang, Jiebo Luo, Chenliang Xu.<br />
"Caption Anything in Video: Fine-grained Object-centric Captioning via Spatiotemporal Multimodal Prompting." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.05541)]
[[code](https://github.com/yunlong10/CAT-V)]
[2025.04]

- **KAN-SAM:** Xingyuan Li, Ruichao Hou, Tongwei Ren, Gangshan Wu.<br />
"KAN-SAM: Kolmogorov-Arnold Network Guided Segment Anything Model for RGB-T Salient Object Detection." ICME (2025).
[[paper](https://arxiv.org/abs/2504.05878)]
[2025.04]

- **HRMedSeg:** Qing Xu, Zhenye Lou, Chenxin Li, Xiangjian He, Rong Qu, Tesema Fiseha Berhanu, Yi Wang, Wenting Duan, Zhen Chen.<br />
"HRMedSeg: Unlocking High-resolution Medical Image segmentation via Memory-efficient Attention Modeling." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.06205)]
[[code](https://github.com/xq141839/HRMedSeg)]
[2025.04]

- **SAM2MOT:** Junjie Jiang, Zelin Wang, Manqi Zhao, Yin Li, DongSheng Jiang.<br />
"SAM2MOT:ANovelParadigm of Multi-Object Tracking by Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.04519)]
[2025.04]

- **S4M:** Heeji Yoon, Heeseong Shin, Eunbeen Hong, Hyunwook Choi, Hansang Cho, Daun Jeong, Seungryong Kim.<br />
"S^4M: Boosting Semi-Supervised Instance Segmentation with SAM." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.05301)]
[[code](https://cvlab-kaist.github.io/S4M)]
[2025.04]

- Hamza Riaz, Alan F. Smeaton.<br />
"Resilience of Vision Transformers for Domain Generalisation in the Presence of Out-of-Distribution Noisy Images." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.04225)]
[2025.04]

- **UCS:** Dianshuo Li, Li Chen, Yunxiang Cao, Kai Zhu, Jun Cheng.<br />
"UCS: A Universal Model for Curvilinear Structure Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.04034)]
[2025.04]

- Mengyuan Liu, Yixiao Chen, Anning Tian, Xinmeng Wu, Mozhi Shen, Tianchou Gong, Jeongkyu Lee.<br />
"Performance Analysis of Deep Learning Models for Femur Segmentation in MRI Scan." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.04066)]
[2025.04]

- **CMaP-SAM:** Shuai Chen, Fanman Meng, Haoran Wei, Chenhao Wu, Qingbo Wu, Linfeng Xu, Hongliang Li.<br />
"CMaP-SAM: Contraction Mapping Prior for SAM-driven Few-shot Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.05049)]
[2025.04]

- **MedSAM2:** Jun Ma, Zongxin Yang, Sumin Kim, Bihui Chen, Mohammed Baharoon, Adibvafa Fallahpour, Reza Asakereh, Hongwei Lyu, Bo Wang.<br />
"MedSAM2: Segment Anything in 3D Medical Images and Videos." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.03600)]
[[code](https://medsam2.github.io/)]
[2025.04]

- **GraphSeg:** Haozhan Tang, Tianyi Zhang, Oliver Kroemer, Matthew Johnson-Roberson, Weiming Zhi.<br />
"GraphSeg: Segmented 3D Representations via Graph Edge Addition and Contraction." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.03129)]
[[code](https://github.com/tomtang502/graphseg.git)]
[2025.04]

- **Delineate-Anything:** Mykola Lavreniuk, Nataliia Kussul, Andrii Shelestov, Bohdan Yailymov, Yevhenii Salii, Volodymyr Kuzin, Zoltan Szantoi.<br />
"Delineate Anything: Resolution-Agnostic Field Boundary Delineation on Satellite Imagery." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.02534)]
[[code](https://lavreniuk.github.io/Delineate-Anything)]
[2025.04]

- **APSeg:** Liying Xu, Hongliang He, Wei Han, Hanbin Huang, Siwei Feng, Guohong Fu.<br />
"APSeg: Auto-Prompt Model with Acquired and Injected Knowledge for Nuclear Instance Segmentation and Classification." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.02222)]
[2025.04]

- **F-ViTA:** Jay N. Paranjape, Celso de Melo, Vishal M. Patel.<br />
"F-ViTA: Foundation Model Guided Visible to Thermal Translation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.02801)]
[[code](https://github.com/JayParanjape/F-ViTA/tree/master)]
[2025.04]

- **MVP-Lab:** Hao Fang, Runmin Cong, Xiankai Lu, Zhiyang Chen, Wei Zhang.<br />
"The 1st Solution for 4th PVUW MeViS Challenge: Unleashing the Potential of Large Multimodal Models for Referring Video Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.05178)]
[2025.04]

- **ReferDINO-Plus:** Tianming Liang, Haichao Jiang, Wei-Shi Zheng, Jian-Fang Hu.<br />
"ReferDINO-Plus: 2nd Solution for 4th PVUW MeViS Challenge at CVPR 2025." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.23509)]
[[code](https://github.com/iSEE-Laboratory/ReferDINO-Plus)]
[2025.03]

- **Sa2VA:** Haobo Yuan, Tao Zhang, Xiangtai Li, Lu Qi, Zilong Huang, Shilin Xu, Jiashi Feng, Ming-Hsuan Yang.<br />
"4th PVUW MeViS 3rd Place Report: Sa2VA." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.00476)]
[[code](https://github.com/magic-research/Sa2VA)]
[2025.04]

- **BiSeg-SAM:** Encheng Su, Hu Cao, Alois Knoll.<br />
"BiSeg-SAM: Weakly-Supervised Post-Processing Framework for Boosting Binary Segmentation in Segment Anything Models." BIBM (2024).
[[paper](https://arxiv.org/abs/2504.01452)]
[[code](https://github.com/suencgo/BiSeg-SAM.)]
[2025.04]

- **DBF-UNet:** Haoxuan Li, Wei Song, Aofan Liu, Peiwu Qin.<br />
"DBF-UNet: A Two-Stage Framework for Carotid Artery Segmentation with Pseudo-Label Generation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.00908)]
[[code](https://github.com/Haoxuanli-Thu/DBF-UNet)]
[2025.04]

- **SAL-4D:** Yushan Zhang, Aljoša Ošep, Laura Leal-Taixé, Tim Meinhardt.<br />
"Zero-Shot 4D Lidar Panoptic Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.00848)]
[2025.04]

- **CamoSAM2:** Xin Zhang, Keren Fu, Qijun Zhao.<br />
"CamoSAM2: Motion-Appearance Induced Auto-Refining Prompts for Video Camouflaged Object Detection." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.00375)]
[2025.04]

- **HybridGL:** Ting Liu, Siyuan Li.<br />
"Hybrid Global-Local Representation with Augmented Spatial Guidance for Zero-Shot Referring Image Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.00356)]
[[code](https://github.com/fhgyuanshen/HybridGL)]
[2025.04]

- **SmartScan:** Savinay Nagendra, Kashif Rashid.<br />
"SmartScan: An AI-based Interactive Framework for Automated Region Extraction from Satellite Images." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.00200)]
[2025.04]

- **SALT:** Yanbo Wang, Yongtao Chen, Chuan Cao, Tianchen Deng, Wentao Zhao, Jingchuan Wang, Weidong Chen.<br />
"SALT: A Flexible Semi-Automatic Labeling Tool for General LiDAR Point Clouds with Cross-Scene Adaptability and 4D Consistency." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.23980)]
[[code](https://github.com/Cavendish518/SALT)]
[2025.03]

- **MedCL:** Ke Zhang, Vishal M. Patel.<br />
"MedCL: Learning Consistent Anatomy Distribution for Scribble-supervised Medical Image Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.22890)]
[[code](https://github.com/BWGZK/MedCL)]
[2025.03]

- **ReasonGrounder:** Zhenyang Liu, Yikai Wang, Sixiao Zheng, Tongying Pan, Longfei Liang, Yanwei Fu, Xiangyang Xue.<br />
"ReasonGrounder: LVLM-Guided Hierarchical Feature Splatting for Open-Vocabulary 3D Visual Grounding and Reasoning." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.23297)]
[[code](https://zhenyangliu.github.io/ReasonGrounder/)]
[2025.03]

- Uxue Delaquintana-Aramendi, Leire Benito-del-Valle, Aitor Alvarez-Gila, Javier Pascau, Luisa F Sánchez-Peralta, Artzai Picón, J Blas Pagador, Cristina L Saratxaga.<br />
"AI-Assisted Colonoscopy: Polyp Detection and Segmentation using Foundation Models." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.24138)]
[2025.03]

- **IMPACT:** Valentin Boussot, Cédric Hémon, Jean-Claude Nunes, Jason Downling, Simon Rouzé, Caroline Lafond, Anaïs Barateau, Jean-Louis Dillenseger.<br />
"IMPACT: A Generic Semantic Loss for Multimodal Medical Image Registration." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.24121)]
[2025.03]

- **MGD-SAM2:** Haoran Shen, Peixian Zhuang, Jiahao Kou, Yuxin Zeng, Haoying Xu, Jiangyun Li.<br />
"MGD-SAM2: Multi-view Guided Detail-enhanced Segment Anything Model 2 for High-Resolution Class-agnostic Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.23786)]
[[code](https://github.com/sevenshr/MGD-SAM2)]
[2025.03]

- **Motion-Seg:** Nan Huang, Wenzhao Zheng, Chenfeng Xu, Kurt Keutzer, Shanghang Zhang, Angjoo Kanazawa, Qianqian Wang.<br />
"Segment Any Motion in Videos." CVPR (2025).
[[paper](https://arxiv.org/abs/2503.22268)]
[[code](https://motion-seg.github.io/)]
[2025.03]

- **SCHNet:** Kunliang Liu, Jianming Wang, Rize Jin, Wonjun Hwang, Tae-Sun Chung.<br />
"SCHNet: SAM Marries CLIP for Human Parsing." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.22237)]
[2025.03]

- **BlooDet:** Jialun Pei, Zhangjun Zhou, Diandian Guo, Zhixi Li, Jing Qin, Bo Du, Pheng-Ann Heng.<br />
"Synergistic Bleeding Region and Point Detection in Surgical Videos." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.22174)]
[2025.03]

- **Erosion-SAM:** Hadi Shokati and Andreas Engelhardt and Kay Seufferheld and Ruhollah Taghizadeh-Mehrjardi and Peter Fiener and Hendrik P.A. Lensch and Thomas Scholten.<br />
"Erosion-SAM: Semantic segmentation of soil erosion by water." Catena(2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S0341816225002565)]
[2025.03]

- **SD-YOLOv8:** Zhang, Xintong, Dasheng Wu, and Fengya Xu.<br />
"SD-YOLOv8: SAM-Assisted Dual-Branch YOLOv8 Model for Tea Bud Detection on Optical Images." Agriculture(2025).
[[paper](https://www.mdpi.com/2077-0472/15/7/712)]
[2025.03]

- **WS-SAM:** Zhang, Z., Ma, F., Liu, H. et al.<br />
"WS-SAM: self-prompting SAM with wavelet and spatial domain for OCTA retinal vessel segmentation." The Journal of Supercomputing (2025).
[[paper](https://link.springer.com/article/10.1007/s11227-025-07136-7)]
[2025.03]

- **DGSUnet:** Yimin Xu.<br />
"DGSUnet: An Improved Unet Model with DINO-Guided SAM2 for Multi-Scale Feature Collaboration." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.21187)]
[[code](https://github.com/CheneyXuYiMin/SAM2DINO-Seg)]
[2025.03]

- **seconGS:** Hairong Yin, Huangying Zhan, Yi Xu, Raymond A. Yeh.<br />
"Semantic Consistent Language Gaussian Splatting for Point-Level Open-vocabulary Querying." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.21767)]
[[code](https://evelinyin.github.io/seconGS/)]
[2025.03]

- **AMA-SAM:** Jiahe Qian, Yaoyu Fang, Jinkui Hao, Bo Zhou.<br />
"AMA-SAM: Adversarial Multi-Domain Alignment of Segment Anything Model for High-Fidelity Histology Nuclei Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.21695)]
[2025.03]

- **Feature4X:** Shijie Zhou, Hui Ren, Yijia Weng, Shuwang Zhang, Zhen Wang, Dejia Xu, Zhiwen Fan, Suya You, Zhangyang Wang, Leonidas Guibas, Achuta Kadambi.<br />
"Feature4X: Bridging Any Monocular Video to 4D Agentic AI with Versatile Gaussian Feature Fields." CVPR (2025).
[[paper](https://arxiv.org/abs/2503.20776)]
[[code](https://feature4x.github.io/)]
[2025.03]

- **CABL:** Xinghao Wang, Changtao Miao, Dianmo Sheng, Tao Gong, Qi Chu, Bin Liu, Nenghai Yu.<br />
"Context-Aware Weakly Supervised Image Manipulation Localization with SAM Refinement." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.20294)]
[2025.03]

- **DSMPrompter:** Mélisande Teng, Arthur Ouaknine, Etienne Laliberté, Yoshua Bengio, David Rolnick, Hugo Larochelle.<br />
"Assessing SAM for Tree Crown Instance Segmentation from Drone Imagery." ICLR ML4RS workshop (2025).
[[paper](https://arxiv.org/abs/2503.20199)]
[2025.03]

- **Optimized MedSAM:** Boyi Li, Ye Yuan, Wenjun Tan.<br />
"Optimization of MedSAM model based on bounding box adaptive perturbation algorithm." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.19700)]
[2025.03]

- **BiPrompt-SAM:** Suzhe Xu, Jialin Peng, Chengyuan Zhang.<br />
"BiPrompt-SAM: Enhancing Image Segmentation via Explicit Selection between Point and Text Prompts." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.19769)]
[2025.03]

- **CamSAM2:** Yuli Zhou, Guolei Sun, Yawei Li, Yuqian Fu, Luca Benini, Ender Konukoglu.<br />
"CamSAM2: Segment Anything Accurately in Camouflaged Videos." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.19730)]
[[code](https://github.com/zhoustan/CamSAM2)]
[2025.03]

- **Siamese-SAM:** Wei, Gang and Miao, Yuqi and Wang, Zhicheng.<br />
"Siamese-SAM: Remote Sensing Image Change Detection with Siamese Structure Segment Anything Model." Applied Sciences (2025).
[[paper](https://www.mdpi.com/2076-3417/15/7/3475)]
[2025.03]

- **PanoGS:** Hongjia Zhai, Hai Li, Zhenzhe Li, Xiaokun Pan, Yijia He, Guofeng Zhang.<br />
"PanoGS: Gaussian-based Panoptic Segmentation for 3D Open Vocabulary Scene Understanding." CVPR (2025).
[[paper](https://arxiv.org/abs/2503.18107)]
[[code](https://zju3dv.github.io/panogs)]
[2025.03]

- **OCRT:** Luyao Tang, Yuxuan Yuan, Chaoqi Chen, Zeyu Zhang, Yue Huang, Kun Zhang.<br />
"OCRT: Boosting Foundation Models in the Open World with Object-Concept-Relation Triad." CVPR (2025).
[[paper](https://arxiv.org/abs/2503.18695)]
[[code](https://github.com/lytang63/OCRT)]
[2025.03]

- **HU-MCD:** Arne Grobrügge, Niklas Kühl, Gerhard Satzger, Philipp Spitzer.<br />
"Towards Human-Understandable Multi-Dimensional Concept Discovery." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.18629)]
[[code](https://github.com/grobruegge/hu-mcd)]
[2025.03]

- **PG-SAM:** Yiheng Zhong, Zihong Luo, Chengzhi Liu, Feilong Tang, Zelin Peng, Ming Hu, Yingzhen Hu, Jionglong Su, Zongyuan Geand, Imran Razzak.<br />
"PG-SAM: Prior-Guided SAM with Medical for Multi-organ Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.18227)]
[[code](https://github.com/logan-0623/PG-SAM)]
[2025.03]

- **MambaSAM:** Liang, Pengchen and Shi, Leijun and Pu, Bin and Wu, Renkai and Chen, Jianguo and Zhou, Lixin and Xu, Lite and Chen, Zhuangzhuang and Chang, Qing and Li, Yiwei.<br />
"MambaSAM: A Visual Mamba-Adapted SAM Framework for Medical Image Segmentation." JBHI (2025).
[[paper](https://ieeexplore.ieee.org/document/10899855)]
[2025.03]

- **SFA-Net:** Tian Gao and Chaozhen Lan and Wenjun Huang and Sheng Wang.<br />
"SFA-Net: A SAM-guided focused attention network for multimodal remote sensing image matching." ISPRS Journal of Photogrammetry and Remote Sensing (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S0924271625000905)]
[[code](https://github.com/GaotTian/SFA-Net)]
[2025.03]

- **DSATNet:** Li Y, Huang J, Zhang Y, Deng J, Zhang J, Dong L, Wang D, Mei L, Lei C.<br />
"Dual branch segment anything model-transformer fusion network for accurate breast ultrasound image segmentation." Med Phys (2025).
[[paper](https://pubmed.ncbi.nlm.nih.gov/40103542/)]
[[code](https://github.com/Skylanding/DSATNet)]
[2025.03]

- **M2N2V2:** Markus Karmann, Peng-Tao Jiang, Bo Li, Onay Urfalioglu.<br />
"M2N2V2: Multi-Modal Unsupervised and Training-free Interactive Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.16254)]
[2025.03]

- **USAM-Net:** Joseph Emmanuel DL Dayo, Prospero C. Naval Jr.<br />
"USAM-Net: A U-Net-based Network for Improved Stereo Correspondence and Scene Depth Estimation using Features from a Pre-trained Image Segmentation network." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.14950)]
[2025.03]

- **TransCaGNet:** Annalena Blänsdorf, Tristan Wirth, Arne Rak, Thomas Pöllabauer, Volker Knauthe, Arjan Kuijper.<br />
"Semantic Segmentation of Transparent and Opaque Drinking Glasses with the Help of Zero-shot Learning." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.15004)]
[2025.03]

- **SED-MVS:** Zhenlong Yuan, Zhidong Yang, Yujun Cai, Kuangxin Wu, Mufan Liu, Dapeng Zhang, Hao Jiang, Zhaoxin Li, Zhaoqi Wang.<br />
"SED-MVS: Segmentation-Driven and Edge-Aligned Deformation Multi-View Stereo with Depth Restoration and Occlusion Constraint." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.13721)]
[2025.03]
 
- Yizhou Li, Yusuke Monno, Masatoshi Okutomi, Yuuichi Tanaka, Seiichi Kataoka, Teruaki Kosiba.<br />
"Segmentation-Guided Neural Radiance Fields for Novel Street View Synthesis." VISAPP (2025).
[[paper]([2503.14219] Segmentation-Guided Neural Radiance Fields for Novel Street View Synthesis)]
[[code](http://www.ok.sc.e.titech.ac.jp/res/NVS/index.html)]
[2025.03]

- **OMT-SAM:** Wenjie Zhang, Ziyang Zhang, Mengnan He, Jiancheng Ye.<br />
"Organ-aware Multi-scale Medical Image Segmentation Using Text Prompt Engineering." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.13806)]
[2025.03]

- **ROS-SAM:** Zhe Shan, Yang Liu, Lei Zhou, Cheng Yan, Heng Wang, Xia Xie.<br />
"ROS-SAM: High-Quality Interactive Segmentation for Remote Sensing Moving Object." CVPR (2025).
[[paper](https://arxiv.org/abs/2503.12006)]
[[code](https://github.com/ShanZard/ROS-SAM)]
[2025.03]

- **SPC-GS:** Guibiao Liao, Qing Li, Zhenyu Bao, Guoping Qiu, Kanglin Liu.<br />
"SPC-GS: Gaussian Splatting with Semantic-Prompt Consistency for Indoor Open-World Free-view Synthesis from Sparse Inputs." CVPR (2025).
[[paper](https://arxiv.org/abs/2503.12535)]
[[code](https://gbliao.github.io/SPC-GS.github.io/)]
[2025.03]

- **GleSAM:** Guangqian Guo, Yoong Guo, Xuehui Yu, Wenbo Li, Yaoxing Wang, Shan Gao.<br />
"Segment Any-Quality Images with Generative Latent Space Enhancement." CVPR (2025).
[[paper](https://arxiv.org/abs/2503.12507)]
[2025.03]

- **MSMV-Swin:** Farnoush Bayatmakou, Reza Taleei, Milad Amir Toutounchian, Arash Mohammadi.<br />
"Integrating AI for Human-Centric Breast Cancer Diagnostics: A Multi-Scale and Multi-View Swin Transformer Framework." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.13309)]
[2025.03]

- **3DAxisPrompt:** Dingning Liu, Cheng Wang, Peng Gao, Renrui Zhang, Xinzhu Ma, Yuan Meng, Zhihui Wang.<br />
"3DAxisPrompt: Promoting the 3D Grounding and Reasoning in GPT-4o." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.13185)]
[2025.03]

- **CL-Net:** Dazhou Guo, Zhanghexuan Ji, Yanzhou Su, Dandan Zheng, Heng Guo, Puyang Wang, Ke Yan, Yirui Wang, Qinji Yu, Zi Li, Minfeng Xu, Jianfeng Zhang, Haoshen Li, Jia Ge, Tsung-Ying Ho, Bing-Shen Huang, Tashan Ai, Kuaile Zhao, Na Shen, Qifeng Wang, Yun Bian, Tingyu Wu, Peng Du, Hua Zhang, Feng-Ming Kong, Alan L. Yuille, Cher Heng Tan, Chunyan Miao, Perry J. Pickhardt, Senxiang Yan, Ronald M. Summers, Le Lu, Dakai Jin, Xianghua Ye.<br />
"AContinual Learning-driven Model for Accurate and Gen eralizable Segmentation of Clinically Comprehensive and Fine-grained Whole-body Anatomies in CT." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.12698)]
[2025.03]

- **SAM2-ELNet:** Jianhao Yang, Wenshuo Yu, Yuanchao Lv, Jiance Sun, Bokang Sun, Mingyang Liu.<br />
"SAM2-ELNet: Label Enhancement and Automatic Annotation for Remote Sensing Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.12404)]
[2025.03]

- **E-SAM:** Weiming Zhang, Dingwen Xiao, Lei Chen, Lin Wang.<br />
"E-SAM: Training-Free Segment Every Entity Model." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.12094)]
[2025.03]

- **EgoSplat:** Di Li, Jie Feng, Jiahao Chen, Weisheng Dong, Guanbin Li, Guangming Shi, Licheng Jiao.<br />
"EgoSplat: Open-Vocabulary Egocentric Scene Understanding with Language Embedded 3D Gaussian Splatting." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.11345)]
[2025.03]

- **PPO:** Xueyu Liu · Rui Wang · Yexin Lai · Guangze Shi · Feixue Shao · Fang Hao · Jianan Zhang · Jia Shen · Yongfei Wu · Wen Zheng.<br />
"Plug-and-Play PPO: An Adaptive Point Prompt Optimizer Making SAM Greater." CVPR (2025).
[[paper](https://cvpr.thecvf.com/Conferences/2025/AcceptedPapers)]
[[code](https://github.com/XueyuLiu/PPO)]
[2025.03]

- **EPAF:** Li, Dongsheng and Zang, Chunyan and Zhang, Huijie and Lin, Yiming and Xia, Qiushi.<br />
"An Efficient Pore Annotation Framework for Tight Sandstone Images with Segment Anything Model." ICASSP (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/10889236)]
[[code](https://github.com/wudi-ldd/EPAF)]
[2025.03]

- **SAM2-SP:** Wei, Sheng and Qiu, Song and Zhou, Mei and Zhang, He and Wang, Yan and Li, Qingli.<br />
"Self-Prompting Driven SAM2 for 3D Medical Image Segmentation." ICASSP (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/10889344)]
[2025.03]

- **EP-SAM:** Wang, Zhitao and Wen, Jiangtao and Han, Yuxing.<br />
"EP-SAM: An Edge-Detection Prompt SAM Based Efficient Framework for Ultra-Low Light Video Segmentation." ICASSP (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/10889601)]
[[code](https://github.com/wzt22thu/EP-SAM/releases/tag/DEMO)]
[2025.03]

- **U-SAM:** Jin, Xiaofeng and Hu, Jie and Lin, Jianghang and Zhang, Shengchuan and Cao, Liujuan.<br />
"U-SAM: Upgrade Segment Anything Model With Semantic-Aware and Memory-Efficient." ICASSP (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/10889270)]
[2025.03]

- **VLIMNet:** Chen, Zhongyuan and Zhang, Zhan and Zuo, Decheng and Wang, Ning and Fan, Liufeng and Liu, Zhiwei.<br />
"VLIMNet: A Visible Light And Infrared Image Matching Network Based On Segment Anything Model And SuperPoint." ICASSP (2025).
[[paper](https://ieeexplore.ieee.org/document/10889254)]
[2025.03]

- Ling, Yinzhou and Luo, Jingjing and Han, Yuan and Li, Wenxian and Wang, Hongbo.<br />
"Instance Segmentation of Airway Anatomies Using Mask R-CNN Prompt Adaptation-SAM." ICASSP (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/10889207)]
[2025.03]

- **SeqSAM:** Benjamin Towle, Xin Chen, Ke Zhou.<br />
"SeqSAM: Autoregressive Multiple Hypothesis Prediction for Medical Image Segmentation using SAM." ISBI (2025).
[[paper](https://arxiv.org/abs/2503.09797)]
[[code](https://github.com/BenjaminTowle/SeqSAM)]
[2025.03]

- **NVP-HRI:** Yuzhi Lai, Shenghai Yuan, Youssef Nassar, Mingyu Fan, Thomas Weber, Matthias Rätsch.<br />
"NVP-HRI: Zero Shot Natural Voice and Posture-based Human-Robot Interaction via Large Language Model." ESWA(2025).
[[paper](https://arxiv.org/abs/2503.09335)]
[[code](https://github.com/laiyuzhi/NVP-HRI.git)]
[2025.03]

- **nnInteractive:** Fabian Isensee, Maximilian Rokuss, Lars Krämer, Stefan Dinkelacker, Ashis Ravindran, Florian Stritzke, Benjamin Hamm, Tassilo Wald, Moritz Langenberg, Constantin Ulrich, Jonathan Deissler, Ralf Floca, Klaus Maier-Hein.<br />
"nnInteractive: Redefining 3D Promptable Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.08373)]
[[code](https://www.mitk.org/MITK-nnInteractive)]
[2025.03]

- Qipeng Mei, Dimitri Bulatov, Dorota Iwaszczuk.<br />
"Polygonizing roof segments from high-resolution aerial images using YOLOv8-based edge detection." VISAPP(2025).
[[paper](https://arxiv.org/abs/2503.09187)]
[2025.03]

- Julian Rene Cuellar Buritica, Vu Dinh, Manjula Burri, Julie Roelandts, James Wendling, Jon D. Klingensmith.<br />
"Evaluation of state-of-the-art deep learning models in the segmentation of the heart ventricles in parasternal short-axis echocardiograms." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.08970)]
[2025.03]

- **VTPSeg:** Xing Zi, Kairui Jin, Xian Tao, Jun Li, Ali Braytee, Rajiv Ratn Shah, Mukesh Prasad.<br />
"Visual and Text Prompt Segmentation: A Novel Multi-Model Framework for Remote Sensing." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.07911)]
[2025.03]

- **SAM-RD:** Zhu, Liangshan and Wu, Xing and Wang, Chengliang and Wang, Haidong.<br />
"SAM Adaptation with Refocused Attention and Diverse Prompts for Medical Image Segmentation." ICASSP (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/10889427)]
[2025.03]

- **YOLOE:** Ao Wang, Lihao Liu, Hui Chen, Zijia Lin, Jungong Han, Guiguang Ding.<br />
"YOLOE:Real-Time Seeing Anything." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.07465)]
[[code](https://github.com/THU-MIG/yoloe)]
[2025.03]

- **RS2-SAM 2:** Fu Rong, Meng Lan, Qian Zhang, Lefei Zhang.<br />
"Customized SAM 2 for Referring Remote Sensing Image Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.07266)]
[2025.03]

- **OmniSAM:** Ding Zhong, Xu Zheng, Chenfei Liao, Yuanhuiyi Lyu, Jialei Chen, Shengyang Wu, Linfeng Zhang, Xuming Hu.<br />
"OmniSAM:Omnidirectional Segment Anything Model for UDA in Panoramic Semantic Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.07098)]
[2025.03]

- **MemorySAM:** Chenfei Liao, Xu Zheng, Yuanhuiyi Lyu, Haiwei Xue, Yihong Cao, Jiawen Wang, Kailun Yang, Xuming Hu.<br />
"MemorySAM:MemorizeModalities and Semantics with Segment Anything Model 2 for Multi-modal Semantic Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.06700)]
[2025.03]

- **SAQ-SAM:** Jing Zhang, Zhikai Li, Qingyi Gu.<br />
"SAQ-SAM: Semantically-Aligned Quantization for Segment Anything Model." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.06515)]
[2025.03]

- **SAMEO:** Wei-En Tai, Yu-Lin Shih, Cheng Sun, Yu-Chiang Frank Wang, Hwann-Tzong Chen.<br />
"Segment Anything, Even Occluded." CVPR (2025).
[[paper](https://arxiv.org/abs/2503.06261)]
[2025.03]

- **EvoSAM:** Zhaori Liu, Mengyang Li, Hu Han, Enli Zhang, Shiguang Shan, Zhiming Zhao.<br />
"Dynamically evolving segment anything model with continuous learning for medical image segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.06236)]
[2025.03]

- **PDFNet:** Xianjie Liu, Keren Fu, Qijun Zhao.<br />
"Patch-Depth Fusion: Dichotomous Image Segmentation via Fine-Grained Patch Strategy and Depth Integrity-Prior." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.06100)]
[[code](https://github.com/Tennine2077/PDFNet)]
[2025.03]

- **SAM-COD:** Jiaming Liu, Linghe Kong, Guihai Chen.<br />
"Improving SAM for Camouflaged Object Detection via Dual Stream Adapters." ICCV (2025).
[[paper](https://arxiv.org/abs/2503.06042)]
[2025.03]

- **OpenVocabCT:** Yuheng Li, Yuxiang Lai, Maria Thor, Deborah Marshall, Zachary Buchwald, David S. Yu and Xiaofeng Yang.<br />
"Towards Universal Text-driven CT Image Segmentation." TMI (2025).
[[paper](https://arxiv.org/abs/2503.06030)]
[[code](https://github.com/ricklisz/OpenVocabCT.)]
[2025.03]

- **SAS:** Danielle L. Ferreira, Ahana Gangopadhyay, Hsi-Ming Chang, Ravi Soni, Gopal Avinash.<br />
"SAS: Segment Anything Small for Ultrasound- A Non-Generative Data Augmentation Technique for Robust Deep Learning in Ultrasound Imaging." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.05916)]
[2025.03]

- Melvin Reka, Tessa Pulli, Markus Vincze.<br />
"Multi-Modal 3D Mesh Reconstruction from Images and Text." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.07190)]
[2025.03]

- Yuchen Mao, Hongwei Li, Yinyi Lai, Giorgos Papanastasiou, Peng Qi, Yunjie Yang, Chengjia Wang.<br />
"Semi-Supervised Medical Image Segmentation via Knowledge Mining from Large Models." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.06816)]
[[code](https://anonymous.4open.science/r/Knowledge-Mining-from-Large-Models-C7FE)]
[2025.03]

- **LPANet:** Wentao Wu, Chenglong Li, Xiao Wang, Bin Luo, Qi Liu.<br />
"Large Language Model Guided Progressive Feature Alignment for Multimodal UAVObject Detection." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.06948)]
[2025.03]

- **S4M:** Adrien Meyer, Lorenzo Arboit, Giuseppe Massimiani, Francesco Brucchi, Luca Emanuele Amodio, Didier Mutter, Nicolas Padoy.<br />
"S4M: Segment Anything with 4 Extreme Points." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.05534)]
[2025.03]

- Haiyue Zu, Jun Ge, Heting Xiao, Jile Xie, Zhangzhe Zhou, Yifan Meng, Jiayi Ni, Junjie Niu, Linlin Zhang, Li Ni, Huilin Yang.<br />
"Rethinking Few-Shot Medical Image Segmentation by SAM2: A Training-Free Framework with Augmentative Prompting and Dynamic Matching." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.04826)]
[2025.03]

- **APG-SAM:** Danping Yin and Qingqing Zheng and Long Chen and Ying Hu and Qiong Wang.<br />
"APG-SAM: Automatic prompt generation for SAM-based breast lesion segmentation with boundary-aware optimization." Expert Systems with Applications (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S0957417425006700)]
[2025.03]

- **Meta-CD:** Gao, Junyu and Zhang, Da and Wang, Feiyu and Ning, Lichen and Zhao, Zhiyuan and Li, Xuelong.<br />
"Combining SAM with Limited Data for Change Detection in Remote Sensing." TGRS (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/10902491)]
[[code](https://github.com/zhangda1018/Meta-CD)]
[2025.03]

- **SAM-MedUS:** Feng Tian, Jintao Zhai, Jinru Gong, Weirui Lei, Shuai Chang, Fangfang Ju, Shengyou Qian, Xiao Zou.<br />
"SAM-MedUS: a foundational model for universal ultrasound image segmentation." Journal of Medical Imaging (2025).
[[paper](https://www.spiedigitallibrary.org/journals/journal-of-medical-imaging/volume-12/issue-2/027001/SAM-MedUS--a-foundational-model-for-universal-ultrasound-image/10.1117/1.JMI.12.2.027001.short)]
[2025.03]

- **Yolo-MLSAM:** Hongguang Chen, Banteng Liu, Ke Wang.<br />
"Yolo-MLSAM: SAM Based Breast Cancer Microcalcification Cluster-Segmentation Method." JCEIM (2025).
[[paper](https://jceim.org/index.php/ojs/article/view/8)]
[2025.03]

- Ananth Kochuparambil Biju; Vishnu Prasad Vasu; Sreekumar Krishnan.<br />
"Consolidated extraterrestrial planetary crater detection using SAM (segment anything model)." AIP Conf. Proc.(2025).
[[paper](https://pubs.aip.org/aip/acp/article-abstract/3237/1/030008/3337667/Consolidated-extraterrestrial-planetary-crater)]
[2025.03]

- Chen Jiang, Tianling Lyu, Gege Ma, Zhan Wu, Xinyun Zhong, Yan Xi, Yang Chen, Wentao Zhu.<br />
"CBCT projection domain metal segmentation for metal artifact reduction using hessian-inspired dual-encoding network with guidance from segment anything model." Medical Physics (2025).
[[paper](https://aapm.onlinelibrary.wiley.com/doi/epdf/10.1002/mp.17716?saml_referrer)]
[2025.03]

- **SegLGAD:** Xiao Du and Bing Li and Tongkun Liu and Yi Ding and Liuyi Jin and Zhuo Zhao.<br />
"SegLGAD: Local-to-global industrial anomaly detection with visual segmentation model." Optics & Laser Technology(2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S003039922500221X)]
[[code](https://drive.google.com/file/d/1rJF9LMe8abOl0a4Yst5Om5E7041MXI4C/view?usp=drive_link)]
[2025.03]

- **Det-SAM-Ore:** Li, Fei and Liu, Xiaoyan and Li, Zongping.<br />
"A Two-Stage Framework with Ore-Detect and Segment Anything Model for Ore Particle Segmentation and Size Measurement." IEEE Sensors Journal (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/10908534)]
[2025.03]

- **MAET-SAM:** Shuaiyu Bu, Yuanyuan Li, Guoqiang Liu , Yifan Li.<br />
"MAET-SAM: Magneto-Acousto-Electrical Tomography segmentation network based on the segment anything model." Mathematical Biosciences and Engineering (2025).
[[paper](https://www.aimspress.com/article/doi/10.3934/mbe.2025022)]
[2025.03]

- **PCCFU:** Sulan Zhai and Chengzhuang Liu and Zhengzheng Tu and Chenglong Li and Liuxuanqi Gao.<br />
"Weakly Supervised RGBT Salient Object Detection via SAM-Guided Label Optimization and Progressive Cross-modal Cross-scale Fusion." Information Fusion (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S1566253525001216)]
[[code](https://github.com/tzz-ahu)]
[2025.03]

- Aishik Konwer, Zhijian Yang, Erhan Bas, Cao Xiao, Prateek Prasanna, Parminder Bhatia, Taha Kass-Hout.<br />
"Enhancing SAM with Efficient Prompting and Preference Optimization for Semi-supervised Medical Image Segmentation." CVPR (2025).
[[paper](https://arxiv.org/abs/2503.04639)]
[2025.03]

- Steve Andreas Immanuel, Woojin Cho, Junhyuk Heo, Darongsae Kwon.<br />
"Tackling Few-Shot Segmentation in Remote Sensing via Inpainting Diffusion Model." ICLRW (2025).
[[paper](https://arxiv.org/abs/2503.03785)]
[[code](https://github.com/SteveImmanuel/rs-paint)]
[2025.03]

- **SurgiSAM2:** Devanish N. Kamtam, Joseph B. Shrager, Satya Deepya Malla, Xiaohan Wang, Nicole Lin, Juan J. Cardona, Serena Yeung-Levy, Clarence Hu.<br />
"SurgiSAM2: Fine-tuning a foundational model for surgical video anatomy segmentation and detection." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.03942)]
[2025.03]

- **GBT-SAM:** Cecilia Diana-Albelda, Roberto Alcover-Couso, Álvaro García-Martín, Jesus Bescos, Marcos Escudero-Viñolo.<br />
"GBT-SAM: A Parameter-Efficient Depth-Aware Model for Generalizable Brain tumour Segmentation on mp-MRI." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.04325)]
[[code](https://github.com/vpulab/med-sam-brain)]
[2025.03]

- **WeakMedSAM:** Haoran Wang, Lian Huai, Wenbin Li, Lei Qi, Xingqun Jiang, Yinghuan Shi.<br />
"WeakMedSAM: Weakly-Supervised Medical Image Segmentation via SAM with Sub-Class Exploration and Prompt Affinity Mining ." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.04106)]
[[code](https://github.com/wanghr64/WeakMedSAM)]
[2025.03]

- **AHCPTQ:** Wenlun Zhang, Shimpei Ando, Kentaro Yoshioka.<br />
"AHCPTQ: Accurate and Hardware-Compatible Post-Training Quantization for Segment Anything Model." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.03088)]
[2025.03]

- **SPD-VFM:** Pengchen Liang, Leijun Shi, Huiping Yao, Bin Pu, Jianguo Chen, Lei Zhao, Haishan Huang, Zhuangzhuang Chen, Zhaozhao Xu, Lite Xu, Qing Chang, Yiwei Li.<br />
"Semantic Prior Distillation with Vision Foundation Model for Enhanced Rapid Bone Scintigraphy Image Restoration." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.02321)]
[2025.03]

- **SHIFNet :** Jiayi Zhao, Fei Teng, Kai Luo, Guoqiang Zhao, Zhiyong Li, Xu Zheng, Kailun Yang.<br />
"Unveiling the Potential of Segment Anything Model 2 for RGB-Thermal Semantic Segmentation with Language Guidance." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.02581)]
[[code](https://github.com/iAsakiT3T/SHIFNet)]
[2025.03]

- **ReID-SAM:** Kunjun Li, Cheng-Yen Yang, Hsiang-Wei Huang, Jenq-Neng Hwang.<br />
"Technical Report for ReID-SAM on SkiTB Visual Tracking Challenge 2025." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.01907)]
[2025.03]

- Clayton Bromley, Alexander Moore, Amar Saini, Doug Poland, Carmen Carrano.<br />
"An Analysis of Segment Anything 2." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.00042)]
[2025.03]

- **SAGE:** Guanyao Wu, Haoyu Liu, Hongming Fu, Yichuan Peng, Jinyuan Liu, Xin Fan, Risheng Liu.<br />
"Every SAM Drop Counts: Embracing Semantic Priors for Multi-Modality Image Fusion and Beyond." CVPR (2025).
[[paper](https://arxiv.org/abs/2503.01210)]
[[code](https://github.com/RollingPlain/SAGE_IVIF)]
[2025.03]

- **SparseMamba-PCL:** Luyi Qiu, Tristan Till, Xiaobao Guo, Adams Wai-Kin Kong.<br />
"SparseMamba-PCL: Scribble-Supervised Medical Image Segmentation via SAM-Guided Progressive Collaborative Learning." ArXiv (2025).
[[paper](https://arxiv.org/abs/2503.01633)]
[[code](http://sparsemamba-pcl.git/)]
[2025.03]

- **SemiSAM+:** Yichi Zhang, Bohao Lv, Le Xue, Wenbo Zhang, Yuchen Liu, Yu Fu, Yuan Cheng, Yuan Qi.<br />
"SemiSAM+: Rethinking Semi-Supervised Medical Image Segmentation in the Era of Foundation Models." MIA (2025).
[[paper](https://arxiv.org/abs/2502.20749)]
[2025.02]

- Silius M. Vandeskog, Magne Aldrin, Daniel Howell, Edvin Fuglebakk.<br />
"Adding smoothing splines to the SAM model improves stock assessment." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.20788)]
[2025.02]

- Utku Ozbulak, Seyed Amir Mousavi, Francesca Tozzi, Nikdokht Rashidian, Wouter Willaert, Wesley De Neve, Joris Vankerschaver.<br />
"Less is More? Revisiting the Importance of Frame Rate in Real-Time Zero-Shot Surgical Video Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.20934)]
[2025.02]

- **BudSAM:** Zhou, Chenxi and Wan, Tianjiao and Xu, Kele and Qiao, Peng and Dou, Yong.<br />
"Segment Anything for Visual Bird Sound Denoising." IEEE SPL (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/10902138)]
[[code](https://github.com/colaudiolab/BudSAM)]
[2025.02]

- **LORENZA:** Yehonathan Refael, Iftach Arbel, Ofir Lindenbaum, Tom Tirer.<br />
"LORENZA: Enhancing Generalization in Low-Rank Gradient LLM Training and Fine-Tuning via Efficient Zeroth-Order Adaptive SAM Optimization." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.19571)]
[2025.02]

- **HumanCLIP:** Keito Suzuki, Bang Du, Girish Krishnan, Kunyao Chen, Runfa Blark Li, Truong Nguyen.<br />
"Open-Vocabulary Semantic Part Segmentation of 3D Human." 3DV (2025).
[[paper](https://arxiv.org/abs/2502.19782)]
[2025.02]

- **CLIP+Grad-CAM+SAM:** Muhammad A. Muttaqien, Tomohiro Motoda, Ryo Hanai, Domae Yukiyasu.<br />
"Attention-Guided Integration of CLIP and SAM for Precise Object Masking in Robotic Manipulation." 2025 IEEE/SICE International Symposium on System Integration (2025).
[[paper](https://arxiv.org/abs/2502.18842)]
[2025.02]

- **VesselSAM:** Adnan Iltaf, Rayan Merghani Ahmed, Bin Li, Shoujun Zhou.<br />
"VesselSAM: Leveraging SAM for Aortic Vessel Segmentation with LoRA and Atrous Attention." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.18185)]
[[code](https://github.com/Adnan-CAS/AtrousLora)]
[2025.02]

- **DICEPTION:** Canyu Zhao, Mingyu Liu, Huanyi Zheng, Muzhi Zhu, Zhiyue Zhao, Hao Chen, Tong He, Chunhua Shen.<br />
"DICEPTION: A Generalist Diffusion Model for Visual Perceptual Tasks." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.17157)]
[[code](https://huggingface.co/spaces/Canyu/Diception-Demo)]
[[project](https://aim-uofa.github.io/Diception/)]
[2025.02]

- **AV2T-SAM:** Kyungbok Lee, You Zhang, Zhiyao Duan.<br />
"AUDIO VISUAL SEGMENTATION THROUGH TEXT EMBEDDINGS." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.16359)]
[2025.02]

- **LVM-MSC:** Feibo Jiang, Siwei Tu, Li Dong, Kezhi Wang, Kun Yang, Ruiqi Liu, Cunhua Pan, Jiangzhou Wang.<br />
"Lightweight Vision Model-based Multi-user Semantic Communication Systems." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.16424)]
[2025.02]

- **USegMix:** Jiamu Wang, Jin Tae Kwak.<br />
"USegMix: Unsupervised Segment Mix for Efficient Data Augmentation in Pathology Images." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.16160)]
[2025.02]

- **SESSRS:** Qiao, Yang and Zhong, Bo and Du, Bailin and Cai, He and Jiang, Jinxiong and Liu, Qinhuo and Yang, Aixia and Wu, Junjun and Wang, Xiaoya.<br />
"SAM Enhanced Semantic Segmentation for Remote Sensing Imagery Without Additional Training." TGRS (2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/10857947)]
[[code](https://github.com/qycools/SESSRS)]
[2025.02]

- **UrbanSAM:** Chenyu Li, Danfeng Hong, Bing Zhang, Yuxuan Li, Gustau Camps-Valls, Xiao Xiang Zhu, Jocelyn Chanussot.<br />
"UrbanSAM: Learning Invariance-Inspired Adapters for Segment Anything Models in Urban Construction." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.15199)]
[[code](https://github.com/danfenghong)]
[2025.02]

- Ufaq Khan, Umair Nawaz, Adnan Qayyum, Shazad Ashraf, Muhammad Bilal, Junaid Qadir.<br />
"Surgical Scene Understanding in the Era of Foundation AI Models: A Comprehensive Review." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.14886)]
[2025.02]

- **YOLO-SAM:** Tianyou Jiang, Mingshun Shao, Tianyi Zhang, Xiaoyu Liu, Qun Yu.<br />
"Soybean pod and seed counting in both outdoor fields and indoor laboratories using unions of deep neural networks." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.15286)]
[2025.02]

- **SIYO:** Mayankeyshwar, Mridul and Kumar, Lookinder and Wagh, Mamata P. and Behuria, Swatishree and Yadav, Dev.<br />
"Brain Tumor Detection and Segmentation using SAM integrated YOLOv9 Scheme." ASPCC (2024).
[[paper](https://ieeexplore.ieee.org/abstract/document/10881978)]
[2025.02]

- **FieldSeg:** Lucas B. Ferreira and Vitor S. Martins and Uilson R.V. Aires and Nuwan Wijewardane and Xin Zhang and Sathish Samiappan.<br />
"FieldSeg: A scalable agricultural field extraction framework based on the Segment Anything Model and 10-m Sentinel-2 imagery." Computers and Electronics in Agriculture (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S0168169925001929)]
[2025.02]

- **GDPGO-SAM:** Hua, Shuzhen, Biao Yang, Xinchang Zhang, Ji Qi, Fengxi Su, Jing Sun, and Yongjian Ruan.<br />
"GDPGO-SAM: An Unsupervised Fine Segmentation of Desert Vegetation Driven by Grounding DINO Prompt Generation and Optimization Segment Anything Model." Remote Sensing (2025).
[[paper](https://www.mdpi.com/2072-4292/17/4/691)]
[2025.02]

- Raphael Stock, et al.<br />
"Segment Anything in Medical Images with nnUNet." ArXiv (2025).
[[paper](https://books.google.com.hk/books?hl=zh-CN&lr=&id=j75HEQAAQBAJ&oi=fnd&pg=PA167&ots=OTPhRogBsG&sig=sxq3kAFSJ-PTJT2QSL8rUrEn3E8&redir_esc=y#v=onepage&q&f=false)]
[2025.02]

- **MedfcientSAM:** Bao-Hiep Le, et al.<br />
"MedfcientSAM: A Robust Medical Segmentation Model with Optimized Inference Pipeline for Limited Clinical Settings." ArXiv (2025).
[[paper](https://books.google.com.hk/books?hl=zh-CN&lr=&id=j75HEQAAQBAJ&oi=fnd&pg=PA1&ots=OTPhRogBsG&sig=tAtQslzglGF3YRcBZY0kXGNUjIU&redir_esc=y#v=onepage&q&f=false)]
[[code](https://github.com/hieplpvip/medficientsam)]
[2025.02]

- **SegAnyPET:** Yichi Zhang, Le Xue, Wenbo Zhang, Lanlan Li, Yuchen Liu, Chen Jiang, Yuan Cheng, Yuan Qi.<br />
"SegAnyPET: Universal Promptable Segmentation from Positron Emission Tomography Images." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.14351)]
[[code](https://github.com/YichiZhang98/SegAnyPET)]
[2025.02]

- Pengchen Liang, Bin Pu, Haishan Huang, Yiwei Li, Hualiang Wang, Weibo Ma, Qing Chang.<br />
"Vision Foundation Models in Medical Image Analysis: Advances and Challenges." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.14584)]
[2025.02]

- **SASVi:** Ssharvien Kumar Sivakumar, Yannik Frisch, Amin Ranem, Anirban Mukhopadhyay.<br />
"SASVi - Segment Any Surgical Video." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.09653)]
[2025.02]

- **SpeHeatal:** Yi Shi, Yunkai Wang, Xupeng Tian, Tieyi Zhang, Bing Yao, Hui Wang, Yong Shao, Cencen Wang, Rong Zeng.<br />
"SpeHeatal: A Cluster-Enhanced Segmentation Method for Sperm Morphology Analysis." AAAI (2025).
[[paper](https://arxiv.org/abs/2502.13192)]
[2025.02]

- **MaizeEar-SAM:** Hossein Zaremehrjerdi, Lisa Coffey, Talukder Jubery, Huyu Liu, Jon Turkus, Kyle Linders, James C. Schnable, Patrick S. Schnable, Baskar Ganapathysubramanian.<br />
"MaizeEar-SAM: Zero-Shot Maize Ear Phenotyping." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.13399)]
[2025.02]

- **PRISM:** Kangning Cui, Rongkun Zhu, Manqi Wang, Wei Tang, Gregory D. Larsen, Victor P. Pauca, Sarra Alqahtani, Fan Yang, David Segurado, David Lutz, Jean-Michel Morel, Miles R. Silman.<br />
"Detection and Geographic Localization of Natural Objects in the Wild: A Case Study on Palms." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.13023)]
[2025.02]

- **SAM-Assisted-Registration:** Hao Xu, Tengfei Xue, Jianan Fan, Dongnan Liu, Yuqian Chen, Fan Zhang, Carl-Fredrik Westin, Ron Kikinis, Lauren J. O'Donnell, Weidong Cai.<br />
"Medical Image Registration Meets Vision Foundation Model: Prototype Learning and Contour Awareness." IPMI (2025).
[[paper](https://arxiv.org/abs/2502.11440)]
[[code](https://github.com/HaoXu0507/IPMI25-SAM-Assisted-Registration)]
[2025.02]

- **WRT-SAM:** Yunyi Zhou, Kun Shi, Gang Hao.<br />
"WRT-SAM: Foundation Model-Driven Segmentation for Generalized Weld Radiographic Testing ." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.11338)]
[2025.02]

- **MITO:** Laura Dodds, Tara Boroushaki, Fadel Adib.<br />
"MITO: Enabling Non-Line-of-Sight Perception using Millimeter-waves through Real-World Datasets and Simulation Tools." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.10259)]
[2025.02]

- **SAM2Refiner:** Yuan Yao, Qiushi Yang, Miaomiao Cui, Liefeng Bo.<br />
"Towards Fine-grained Interactive Segmentation in Images and Videos." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.09660)]
[2025.02]

- **SAM-QA:** Emil Mededovic, Valdy Laurentius, Yuli Wu, Marcin Kopaczka, Zhu Chen, Mareike Schulz, René Tolba, Johannes Stegmaier.<br />
"No Free Lunch in Annotation either: An objective evaluation of foundation models for streamlining annotation in animal tracking." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.03907)]
[[code](https://github.com/medem23/SAM-QA)]
[2025.02]

- **CBCT-US:** Feng Li, Yuan Bi, Dianye Huang, Zhongliang Jiang, Nassir Navab.<br />
"Robotic CBCT Meets Robotic Ultrasound." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.12019)]
[2025.02]

- **IDCC-SAM:** Fanijo, Samuel, Ali Jannesari, and Julie Dickerson.<br />
"IDCC-SAM: A Zero-Shot Approach for Cell Counting in Immunocytochemistry Dataset Using the Segment Anything Model." Bioengineering (2025).
[[paper](https://www.mdpi.com/2306-5354/12/2/184)]
[2025.02]

- **LV-SAM:** Yagang Wu, Tianli Zhao, Shijun Hu, Qin Wu, Yingxu Chen, Xin Huang & Zhoushun Zheng.<br />
"Integrating multi-scale information and diverse prompts in large model SAM-Med2D for accurate left ventricular ejection fraction estimation." Med Biol Eng Comput(2025).
[[paper](https://link.springer.com/article/10.1007/s11517-025-03310-4)]
[2025.02]

- **LangRS:** Mohanad Diab and Polychronis Kolokoussis and Maria Antonia Brovelli.<br />
"Optimizing zero-shot text-based segmentation of remote sensing imagery using SAM and Grounding DINO." Artificial Intelligence in Geosciences (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S2666544125000012)]
[[code](https://github.com/MohanadDiab/langrs)]
[2025.02]

- Xia, Sijie, Rufu Qin, Yang Lu, Lianjiang Ma, and Zhenghu Liu.<br />
"A Monocular Vision-Based Safety Monitoring Framework for Offshore Infrastructures Utilizing Grounded SAM." Journal of Marine Science and Engineering(2025).
[[paper](https://www.mdpi.com/2077-1312/13/2/340)]
[2025.02]

- Yufang He and Bo Chen and Mahdi Motagh and Yuyan Zhu and Songdong Shao and Jiaye Li and Bing Zhang and Hermann Kaufmann.<br />
"International Journal of Applied Earth Observation and Geoinformation." International Journal of Applied Earth Observation and Geoinformation (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S1569843225000548)]
[2025.02]

- **Save:** Park, Chae Jung and Nguyen, Khanh-Binh.<br />
"Save: Segment Audio-Visual Easy Way Using The Segment Anything Model." SSRN (2025).
[[paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5132584)]
[2025.02]

- **CAB-USRI:** Jinxin Shao, Haosu Zhang & Jianming Miao.<br />
"Depthanything and SAM for UIE: exploring large model information contributes to underwater image restoration." Machine Vision and Applications (2025).
[[paper](https://link.springer.com/article/10.1007/s00138-025-01662-3)]
[2025.02]

- **REMOTE SENSING LETTERS:** Hui Zhang.<br />
"A SAM-based dual-branch network for remote sensing semantic segmentation." REMOTE SENSING LETTERS (2025).
[[paper](https://www.tandfonline.com/doi/abs/10.1080/2150704X.2025.2461331)]
[2025.02]

- **SAMCell:** Alexandra D. VandeLoo, Nathan J. Malta, Emilio Aponte, Caitlin van Zyl, Danfei Xu, Craig R. Forest.<br />
"SAMCell: Generalized Label-Free Biological Cell Segmentation with Segment Anything." ArXiv (2025).
[[paper](https://www.biorxiv.org/content/biorxiv/early/2025/02/08/2025.02.06.636835.full.pdf)]
[2025.02]

- **AutoMedSAM:** Peng Huang, Shu Hu, Bo Peng, Jiashu Zhang, Hongtu Zhu, Xi Wu, Xin Wang.<br />
"Diffusion-empowered AutoPrompt MedSAM." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.06817)]
[[code](https://github.com/HP-ML/AutoPromptMedSAM.git)]
[2025.02]

- **SAMRefiner:** Yuqi Lin, Hengjia Li, Wenqi Shao, Zheng Yang, Jun Zhao, Xiaofei He, Ping Luo, Kaipeng Zhang.<br />
"SAMRefiner: Taming Segment Anything Model for Universal Mask Refinement." ICLR (2025).
[[paper](https://arxiv.org/abs/2502.06756)]
[[code](https://github.com/linyq2117/SAMRefiner)]
[2025.02]

- **MTRMB:** You Zhou, Jiangshan Zhao, Deyu Zeng, Zuo Zuo, Weixiang Liu, Zongze Wu.<br />
"Multimodal Task Representation Memory Bank vs. Catastrophic Forgetting in Anomaly Detection." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.06194)]
[2025.02]

- **FunduSAM:** Jinchen Yu, Yongwei Nie, Fei Qi, Wenxiong Liao, Hongmin Cai.<br />
"FunduSAM: A Specialized Deep Learning Model for Enhanced Optic Disc and Cup Segmentation in Fundus Images." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.06220)]
[2025.02]

- **GlandSAM:** Zhang, Qixiang and Li, Yi and Xue, Cheng and Wang, Haonan and Li, Xiaomeng.<br />
"GlandSAM: Injecting Morphology Knowledge Into Segment Anything Model for Label-Free Gland Segmentation." TMI.(2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/10707661)]
[2025.02]

- **LAM:** Wei-Bin Kou, Guangxu Zhu, Rongguang Ye, Shuai Wang, Ming Tang, Yik-Chung Wu.<br />
"Label Anything: An Interpretable, High-Fidelity and Prompt-Free Annotator." ICRA (2025).
[[paper](https://arxiv.org/abs/2502.02972)]
[2025.02]

- **PP:** Wang Xinyi, Kang Hongyu, Wei Peishan, Shuai Li, Yu Sun, Sai Kit Lam, Yongping Zheng.<br />
"Proxy Prompt: Endowing SAM and SAM 2 with Auto-Interactive-Prompt for Medical Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.03501)]
[2025.02]

- **FE-UNet:** Guohao Huo, Ruiting Dai, Ling Shao, Hao Tang.<br />
"FE-UNet: Frequency Domain Enhanced U-Net with Segment Anything Capability for Versatile Image Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.03829)]
[2025.02]

- **ZISVFM:** Ying Zhang, Maoliang Yin, Wenfu Bi, Haibao Yan, Shaohan Bian, Cui-Hua Zhang, Changchun Hua.<br />
"ZISVFM: Zero-Shot Object Instance Segmentation in Indoor Robotic Environments with Vision Foundation Models." IEEE Transactions on Robotics (2025).
[[paper](https://arxiv.org/abs/2502.03266)]
[[code](https://github.com/Yinmlmaoliang/zisvfm)]
[2025.02]

- **RFMedSAM 2:** Bin Xie, Hao Tang, Yan Yan, Gady Agam.<br />
"RFMedSAM 2: Automatic Prompt Refinement for Enhanced Volumetric Medical Image Segmentation with SAM 2." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.02741)]
[2025.02]

- **FLIP:** Manuel Traub, Martin V. Butz.<br />
"Rethinking Vision Transformer for Object Centric Foundation Models." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.02763)]
[2025.02]

- **Tell2Reg:** Wen Yan, Qianye Yang, Shiqi Huang, Yipei Wang, Shonit Punwani, Mark Emberton, Vasilis Stavrinides, Yipeng Hu, Dean Barratt.<br />
"Tell2Reg: Establishing spatial correspondence between images by the same language prompts." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.03118)]
[[code](https://github.com/yanwenCi/Tell2Reg.git)]
[2025.02]

- **Functional-SAM:** Sidak Pal Singh, Hossein Mobahi, Atish Agarwala, Yann Dauphin.<br />
"Avoiding spurious sharpness minimization broadens applicability of SAM." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.02407)]
[2025.02]

- **IMDPrompter:** Quan Zhang, Yuxin Qi, Xi Tang, Jinwei Fang, Xi Lin, Ke Zhang, Chun Yuan.<br />
"IMDPrompter: Adapting SAM to Image Manipulation Detection by Cross-View Automated Prompt Learning." ICLR (2025).
[[paper](https://arxiv.org/abs/2502.02454)]
[2025.02]

- **LBG:** Rohan Chacko, Nicolai Haeni, Eldar Khaliullin, Lin Sun, Douglas Lee.<br />
"Lifting by Gaussians: A Simple, Fast and Flexible Method for 3D Instance Segmentation." WACV(2025).
[[paper](https://arxiv.org/abs/2502.00173)]
[2025.02]

- **GFDS:** Tongkun Liu, Bing Li, Xiao Jin, Yupeng Shi, Qiuying Li, Xiang Wei.<br />
"Exploring Few-Shot Defect Segmentation in General Industrial Scenarios with Metric Learning and Vision Foundation Models." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.01216)]
[[code](https://github.com/liutongkun/GFDS)]
[2025.02]

- **SAM-PLE:** Mingyu Yang, Jitong Lu, and Hun-Seok Kim.<br />
"SAM-guided Pseudo Label Enhancement for Multi-modal 3D Semantic Segmentation." ICRA (2025).
[[paper](https://arxiv.org/abs/2502.00960)]
[2025.02]

- **VLP-SAM:** Kosuke Sakurai, Ryotaro Shimizu, Masayuki Goto.<br />
"Vision and Language Reference Prompt into SAM for Few-shot Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.00719)]
[[code](https://github.com/kosukesakurai1/VLP-SAM)]
[2025.02]

- **Self-Prompt-SAM:** Bin Xie, Hao Tang, Dawen Cai, Yan Yan, Gady Agam.<br />
"Self-Prompt SAM: Medical Image Segmentation via Automatic Prompt SAM Adaptation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.00630)]
[2025.02]

- **PEFT-SAM:** Carolin Teuber, Anwai Archit, Constantin Pape.<br />
"Parameter Efficient Fine-Tuning of Segment Anything Model." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.00418)]
[[code](https://github.com/computational-cell-analytics/peft-sam)]
[2025.02]

- **PathoSAM:** Titus Griebel, Anwai Archit, Constantin Pape.<br />
"Segment Anything for Histopathology." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.00408)]
[[code](https://github.com/computational-cell-analytics/patho-sam)]
[2025.02]

- **AVSBench-Robust:** Jia Li, Wenjie Zhao, Ziru Huang, Yunhui Guo, Yapeng Tian.<br />
"Do Audio-Visual Segmentation Models Truly Segment Sounding Objects?." ArXiv (2025).
[[paper](https://arxiv.org/abs/2502.00358)]
[2025.02]

- Diogo Ebert Gatti; Eduardo Lobo Lustosa Cabral.<br />
"SISTEMAS PARA PERCEPÇÃO DO ESPAÇO LIVRE À FRENTE DE UM VEÍCULO E CÁLCULO DA DISTÂNCIA DE SEUS LIMITES." ArXiv (2025).
[[paper](https://maua.br/files/gatti-cabral-1734101582.pdf)]
[2025.01]

- **OHIF-SAM2:** Jaeyoung Cho, Aditya Rastogi, Jingyu Liu, et al.<br />
"OHIF-SAM2: Accelerating Radiology Workflows with Segment Anything Model 2." ArXiv (2025).
[[paper](https://www.techrxiv.org/doi/full/10.36227/techrxiv.173387978.85520380)]
[[code](https://github.com/CCI-Bonn/OHIF-SAM2)]
[2025.01]

- Joseph Lundy.<br />
"Foosball Robot Object Detection and Angle Estimation." ArXiv (2025).
[[paper](https://www.cs.toronto.edu/~lindell/teaching/2529/past_projects/2024/report/joseph-lundy.pdf)]
[2025.01]

- Niu, Ziang; Huang, Ting; Xu, Chengjia; Sun, Xinyue; Taha, Mohamed Farag; He, Yong; Qiu, Zhengjun.<br />
"A Novel Approach to Optimize Key Limitations of Azure Kinect DK for Efficient and Precise Leaf Area Measurement." ArXiv (2025).
[[paper](https://openurl.ebsco.com/EPDB%3Agcd%3A11%3A22953339/detailv2?sid=ebsco%3Aplink%3Ascholar&id=ebsco%3Agcd%3A182476115&crl=c&link_origin=scholar.google.cz)]
[2025.01]

- J Valero Casas-Aljama.<br />
"AI-powered 2D animation editor." ArXiv (2025).
[[paper](https://upcommons.upc.edu/handle/2117/423234)]
[2025.01]

- Tavakoli, Neda et al.<br />
"Automated quantification of left ventricular scar volume in cardiac MRI using large vision models." Journal of Cardiovascular Magnetic Resonance (2025).
[[paper](https://www.journalofcmr.com/article/S1097-6647(24)01304-8/fulltext)]
[2025.01]

- Mehrnia, Mehri et al.<br />
"Evaluating foundational 'segment anything' (Med-SAM1, Med-SAM2) deep learning models for left atrial segmentation in 3d LGE CMR." Journal of Cardiovascular Magnetic Resonance (2025).
[[paper](https://www.journalofcmr.com/article/S1097-6647(24)01544-8/fulltext)]
[2025.01]

- **SAM2Act:** Haoquan Fang, Markus Grotz, Wilbert Pumacay, Yi Ru Wang, Dieter Fox, Ranjay Krishna, Jiafei Duan.<br />
"SAM2Act: Integrating Visual Foundation Model with A MemoryArchitecture for Robotic Manipulation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.18564)]
[[code](https://sam2act.github.io/)]
[2025.01]

- **FlexiCrackNet:** Xinlong Wan, Xiaoyan Jiang, Guangsheng Luo, Ferdous Sohel, Jenqneng Hwang.<br />
"FlexiCrackNet: A Flexible Pipeline for Enhanced Crack Segmentation with General Features Transfered from SAM." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.18855)]
[2025.01]

- **DeepSketchCamo:** Ying Zang, Runlong Cao, Jianqi Zhang, Yidong Han, Ziyue Cao, Wenjun Hu, Didi Zhu, Lanyun Zhu, Zejian Li, Deyi Ji, Tianrun Chen.<br />
"Let Human Sketches Help: Empowering Challenging Image Segmentation Task with Freehand Sketches." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.19329)]
[2025.01]

- Tongxu Zhang, Bei Wang.<br />
"Point Cloud Upsampling as Statistical Shape Model for Pelvic." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.16716)]
[2025.01]

- **Marker Track:** Aimee Guo, Weihua Mao.<br />
"Marker Track: Accurate Fiducial Marker Tracking for Evaluation of Residual Motions During Breath-Hold Radiotherapy." Biomedical Physics & Engineering Express (2024).
[[paper](https://arxiv.org/abs/2501.15660)]
[[code](https://sites.google.com/view/markertrack?usp=sharing)]
[2025.01]

- **CLISC:** Xiaochuan Ma, Jia Fu, Wenjun Liao, Shichuan Zhang, Guotai Wang.<br />
"CLISC: Bridging clip and sam by enhanced cam for unsupervised brain tumor segmentation." ISBI (2025).
[[paper](https://arxiv.org/abs/2501.16246)]
[2025.01]

- **KD-SAM:** Kunal Dasharath Patil, Gowthamaan Palani, Ganapathy Krishnamurthi.<br />
"Efficient Knowledge Distillation of SAM for Medical Image Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.16740)]
[2025.01]

- **EG-SAM:** Longyi Chen and Xiandong Wang and Fengqin Yao and Mingchen Song and Jiaheng Zhang and Shengke Wang.<br />
"An Edge-Guided SAM for effective complex object segmentation." Expert Systems With Applications (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S0957417425001824)]
[2025.01]

- Yijie Zhu, Shan E Ahmed Raza.<br />
"Gland Segmentation Using SAM With Cancer Grade as a Prompt." ISBI (2025).
[[paper](https://arxiv.org/abs/2501.14718)]
[2025.01]

- **MPG-SAM 2:** Fu Rong, Meng Lan, Qian Zhang, Lefei Zhang.<br />
"MPG-SAM 2: Adapting SAM 2 with Mask Priors and Global Context for Referring Video Object Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.13667)]
[2025.01]

- Gabrielle Hoyer, Michelle W Tong, Rupsa Bhattacharjee, Valentina Pedoia, Sharmila Majumdar.<br />
"Scalable Evaluation Framework for Foundation Models in Musculoskeletal MRI Bridging Computational Innovation with Clinical Utility." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.13376)]
[2025.01]

- **APSAM:** Jian Wang, Xiaokang Zhang, Xianping Ma, Weikang Yu, Pedram Ghamisi.<br />
"Auto-Prompting SAM for Weakly Supervised Landslide Extraction." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.13426)]
[[code](https://github.com/zxk688)]
[2025.01]

- **MONA:** Boxun Hu, Mingze Xia, Ding Zhao, Guanlin Wu.<br />
"MONA: Moving Object Detection from Videos Shot by Dynamic Camera." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.13183)]
[2025.01]

- **DynamicEarth:** Kaiyu Li, Xiangyong Cao, Yupeng Deng, Chao Pang, Zepeng Xin, Deyu Meng, Zhi Wang.<br />
"DynamicEarth: How Far are We from Open-Vocabulary Change Detection?." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.12931)]
[[code](https://likyoo.github.io/DynamicEarth)]
[2025.01]

- **fabSAM:** Yufeng Xie, Hanzhi Wu, Hongxiang Tong, Lei Xiao, Wenwen Zhou, Ling Li, Thomas Cherico Wanger.<br />
"fabSAM: A Farmland Boundary Delineation Method Based on the Segment Anything Model." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.12487)]
[2025.01]

- **MedicoSAM:** Anwai Archit, Luca Freckmann, Constantin Pape.<br />
"MedicoSAM: Towards foundation models for medical image segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.11734)]
[[code](https://github.com/computational-cell-analytics/medico-sam)]
[2025.01]

- **UW-COT220 & VL-SAM2:** Chunhui Zhang, Li Liu, Guanjie Huang, Hao Wen, Xi Zhou, Yanfeng Wang.<br />
  "Towards Underwater Camouflaged Object Tracking: Benchmark and Baselines." CVPR Workshop (2025).
  [[paper](https://arxiv.org/abs/2409.16902)]
  [[ResearchGate](https://www.researchgate.net/publication/388189638_Towards_Underwater_Camouflaged_Object_Tracking_Benchmark_and_Baselines)]
  [[project](https://github.com/983632847/Awesome-Multimodal-Object-Tracking/tree/main/UW-COT220)]
  [2025.01]
  
- **HOPOMOP:** Michael Schwingshackl, Fabio Francisco Oberweger, Markus Murschitz.<br />
"Few-shot Structure-Informed Machinery Part Segmentation with Foundation Models and Graph Neural Networks." WACV (2025).
[[paper](https://arxiv.org/abs/2501.10080)]
[[code](https://github.com/AIT-Assistive-Autonomous-Systems/Hopomop)]
[2025.01]

- **CableSAM:** Aihua Ling, Junwen Wang, Jiaming Lu & Ruyu Liu.<br />
"CableSAM: an efficient automatic segmentation method for aircraft cabin cables." Optoelectronics Letters (2025).
[[paper](https://link.springer.com/article/10.1007/s11801-025-4026-8)]
[2025.01]

- Wang, Yunlong, and Zhiyong Zhang.<br />
"Segment Any Leaf 3D: A Zero-Shot 3D Leaf Instance Segmentation Method Based on Multi-View Images." Sensors (2025).
[[paper](https://www.mdpi.com/1424-8220/25/2/526)]
[2025.01]

- **SegmentAnyTooth:** Khoa Dang Nguyen and Hung Trong Hoang and Thi-Phuong Hong Doan and Khai Quang Dao and Ding-Han Wang and Ming-Lun Hsu.<br />
"SegmentAnyTooth: An open-source deep learning framework for tooth enumeration and segmentation in intraoral photos." Journal of Dental Sciences (2025).
[[paper](SegmentAnyTooth: An open-source deep learning framework for tooth enumeration and segmentation in intraoral photos - ScienceDirect)]
[2025.01]

- **SAM-Glomeruli:** Sun, Rui, and Tianzhu Zhang.<br />
"SAM-Glomeruli: Enhanced Segment Anything Model for Precise Glomeruli." MICCAI Workshop (2024).
[[paper](https://www.google.com/books?hl=zh-CN&lr=&id=GkE_EQAAQBAJ&oi=fnd&pg=PA182&dq=SAM-Glomeruli:+Enhanced+Segment+Anything+Model+for+Precise+Glomeruli&ots=3psKjnNt8g&sig=B_G_F-RemAgJFiGDS3w0M_p6sfg)]
[2025.01]

- **FATE-SAM:** Xingxin He, Yifan Hu, Zhaoye Zhou, Mohamed Jarraya, Fang Liu.<br />
"Few-Shot Adaptation of Training-Free Foundation Model for 3D Medical Image Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.09138)]
[2025.01]

- Pengru Deng, Jiapeng Yao, Chun Li, Su Wang, Xinrun Li, Varun Ojha, Xuhui He, Takashi Matsumoto.<br />
"Unified Few-shot Crack Segmentation and its Precise 3D Automatic Measurement in Concrete Structures." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.09203)]
[2025.01]

- **VRS-HQ:** Sitong Gong, Yunzhi Zhuge, Lu Zhang, Zongxin Yang, Pingping Zhang, Huchuan Lu.<br />
"The Devil is in Temporal Token: High Quality Video Reasoning Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.08549)]
[[code](https://github.com/SitongGong/VRS-HQ)]
[2025.01]

- **SuperSAM:** Waqwoya Abebe, Sadegh Jafari, Sixing Yu, Akash Dutta, Jan Strube, Nathan R. Tallent, Luanzheng Guo, Pablo Munoz, Ali Jannesari.<br />
"SuperSAM: Crafting a SAM Supernetwork via Structured Pruning and Unstructured Parameter Prioritization." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.08504)]
[2025.01]

- **SkipClick:** Robin Schön, Julian Lorenz, Daniel Kienzle, Rainer Lienhart.<br />
"SkipClick: Combining Quick Responses and Low-Level Features for Interactive Segmentation in Winter Sports Contexts." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.07960)]
[[code](https://github.com/Schorob/skipclick)]
[2025.01]

- **SAM-DA:** Javier Gamazo Tejero, Moritz Schmid, Pablo Márquez Neila, Martin S. Zinkernagel, Sebastian Wolf, Raphael Sznitman.<br />
"SAM-DA: Decoder Adapter for Efficient Medical Domain Adaptation." WACV (2025).
[[paper](https://arxiv.org/abs/2501.06836)]
[2025.01]

- **PGP-SAM:** Zhonghao Yan, Zijin Yin, Tianyu Lin, Xiangzhu Zeng, Kongming Liang, Zhanyu Ma.<br />
"PGP-SAM: Prototype-Guided Prompt Learning for Efficient Few-Shot Medical Image Segmentation." ISBI (2025).
[[paper](https://arxiv.org/abs/2501.06692)]
[2025.01]

- **SST:** Zhenyang Feng, Zihe Wang, Saul Ibaven Bueno, Tomasz Frelek, Advikaa Ramesh, Jingyan Bai, Lemeng Wang, Zanming Huang, Jianyang Gu, Jinsu Yoo, Tai-Yu Pan, Arpita Chowdhury, Michelle Ramirez, Elizabeth G. Campolongo, Matthew J. Thompson, Christopher G. Lawrence, Sydne Record, Neil Rosser, Anuj Karpatne, Daniel Rubenstein, Hilmar Lapp, Charles V. Stewart, Tanya Berger-Wolf, Yu Su, Wei-Lun Chao.<br />
"Static Segmentation by Tracking: A Frustratingly Label-Efficient Approach to Fine-Grained Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.06749)]
[2025.01]

- **OCORD:** Shuo Zhang, Runpu Wei, Kongming Liang.<br />
"OCORD: Open-Campus Object Removal Dataset." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.07397)]
[[code](https://huggingface.co/datasets/theSure/OCORD)]
[2025.01]

- **Guided SAM:** S.B. van Rooij, G.J. Burghouts.<br />
"Guided SAM: Label-Efficient Part Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.07434)]
[2025.01]

- **EdgeTAM:** Chong Zhou, Chenchen Zhu, Yunyang Xiong, Saksham Suri, Fanyi Xiao, Lemeng Wu, Raghuraman Krishnamoorthi, Bo Dai, Chen Change Loy, Vikas Chandra, Bilge Soran.<br />
"EdgeTAM: On-Device Track Anything Model." CVPR (2025).
[[paper](https://arxiv.org/abs/2501.07256)]
[[code](https://github.com/facebookresearch/EdgeTAM)]
[2025.01]

- **RSRefSeg:** Keyan Chen, Jiafan Zhang, Chenyang Liu, Zhengxia Zou, Zhenwei Shi.<br />
"RSRefSeg: Referring Remote Sensing Image Segmentation with Foundation Models." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.06809)]
[[code](https://github.com/KyanChen/RSRefSeg)]
[2025.01]

- **CCT:** Olivier Morelle, Justus Bisten, Maximilian W. M. Wintergerst, Robert P. Finger, Thomas Schultz.<br />
"Weakly Supervised Segmentation of Hyper-Reflective Foci with Compact Convolutional Transformers and SAM2." German Conference on Medical Image Computing(2025).
[[paper](https://arxiv.org/abs/2501.05933)]
[2025.01]

- **FLAIR:** Chinmay K Lalgudi, Mark E Leone, Jaden V Clark, Sergio Madrigal-Mora, Mario Espinoza.<br />
"Zero-shot Shark Tracking and Biometrics from Aerial Imagery." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.05717)]
[2025.01]

- **SPA:** Hu, Jihong and Li, Yinhao and Jain, Rahul Kumar and Lin, Lanfen and Chen, Yen-wei.<br />
"SPA: Leveraging the SAM with Spatial Priors Adapter for Enhanced Medical Image Segmentation." JBHI(2025).
[[paper](https://ieeexplore.ieee.org/abstract/document/10829779)]
[2025.01]

- **SAM-Upflow Splitter:** Wenhui Liu, Yulong Qiao, Zhengyi Xing, Yue Zhao.<br />
"Zero-shot moving ship segmentation based on segment anything network and optical flow network." ELECTRONICS LETTERS (2025).
[[paper](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/ell2.70136)]
[2025.01]

- Naddaf-Sh, Amir-M., Vinay S. Baburao, and Hassan Zargarzadeh.<br />
"Leveraging Segment Anything Model (SAM) for Weld Defect Detection in Industrial Ultrasonic B-Scan Images." Sensors (2025).
[[paper](https://www.mdpi.com/1424-8220/25/1/277)]
[2025.01]

- **Sa2VA:** Haobo Yuan, Xiangtai Li, Tao Zhang, Zilong Huang, Shilin Xu, Shunping Ji, Yunhai Tong, Lu Qi, Jiashi Feng, Ming-Hsuan Yang.<br />
"Sa2VA: Marrying SAM2 with LLaVA for Dense Grounded Understanding of Images and Videos." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.04001)]
[[code](https://github.com/magic-research/Sa2VA)]
[[project](https://lxtgh.github.io/project/sa2va)]
[[hugging face](https://huggingface.co/ByteDance/Sa2VA-8B)]
[2025.01]

- **AutoFish:** Stefan Hein Bengtson, Daniel Lehotský, Vasiliki Ismiroglou, Niels Madsen, Thomas B. Moeslund, Malte Pedersen.<br />
"AutoFish: Dataset and Benchmark for Fine-grained Analysis of Fish." WACV Workshop (2025).
[[paper](https://arxiv.org/abs/2501.03767)]
[[code](https://vap.aau.dk/autofish/)]
[2025.01]

- **MedFocusCLIP :** Aadya Arora, Vinay Namboodiri.<br />
"MedFocusCLIP : Improving few shot classification in medical datasets using pixel wise attention." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.03839)]
[[code](https://aadya-arora.github.io/MedFocusClip/)]
[2025.01]

- Risha Goel, Zain Shabeeb, Isabel Panicker, Vida Jamali.<br />
"Segment Anything Model for Zero-shot Single Particle Tracking in Liquid Phase Transmission Electron Microscopy." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.03153)]
[2025.01]

- **SAM4EM:** Javier Montalvo, Álvaro García-Martín, Pablo Carballeira, Juan C. SanMiguel.<br />
"Unsupervised Class Generation to Expand Semantic Segmentation Datasets." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.02264)]
[2025.01]

- **EdgeSAM:** Yang, Wenya and Chen, Xiao-Diao and Wu, Wen and Qin, Hongshuai and Yan, Kangming and Mao, Xiaoyang and Song, Haichuan.<br />
"Boosting Deep Unsupervised Edge Detection via Segment Anything Model." IEEE TII (2024).
[[paper](https://ieeexplore.ieee.org/document/10490131)]
[2025.01]

- **PowerSAM:** Nannan Yan, Yuhao Li, Yingke Mao, et al.<br />
"PowerSAM: Edge-Efficient Segment Anything for Power Systems Through Visual Model Distilla- tion PowerSAM: Edge-Efficient Segment Anything for Power Systems Through Visual Model Distillation." ArXiv (2025).
[[paper](https://www.researchgate.net/publication/387673524_PowerSAM_Edge-Efficient_Segment_Anything_for_Power_Systems_Through_Visual_Model_Distilla-_tion_PowerSAM_Edge-Efficient_Segment_Anything_for_Power_Systems_Through_Visual_Model_Distillation)]
[2025.01]

- **PG-SAG:** Tengfei Wang, Xin Wang, Yongmao Hou, Yiwei Xu, Wendi Zhang, Zongqian Zhan.<br />
"PG-SAG: Parallel Gaussian Splatting for Fine-Grained Large-Scale Urban Buildings Reconstruction via Semantic-Aware Grouping." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.01677)]
[[code](https://github.com/TFWang-9527/PG-SAG)]
[2025.01]

- **MA-SAM:** D. Fan et al.<br />
"MA-SAM: A Multi-atlas Guided SAM Using Pseudo Mask Prompts without Manual Annotation for Spine Image Segmentation." TMI (2025).
[[paper](https://ieeexplore.ieee.org/document/10819446)]
[2025.01]

- **ReferSAM:** S. -A. Liu, H. Xie, J. Ge and Y. Zhang.<br />
"ReferSAM: Unleashing Segment Anything Model for Referring Image Segmentation." TCSVT (2025).
[[paper](https://ieeexplore.ieee.org/document/10819432)]
[[code](https://github.com/lsa1997/ReferSAM)]
[2025.01]

- **YS3AM:** Mu S, Liu J, Zhang P, et al.<br />
"YS3AM: Adaptive 3D Reconstruction and Harvesting Target Detection for Clustered Green Asparagus." ArXiv (2025).
[[paper](https://www.preprints.org/frontend/manuscript/487777b31e6377d16c8fef09489e9418/download_pub)]
[2025.01]

- **FCP:** Suho Park, SuBeen Lee, Hyun Seok Seong, Jaejoon Yoo, Jae-Pil Heo.<br />
"Foreground-Covering Prototype Generation and Matching for SAM-Aided Few-Shot Segmentation." AAAI (2025).
[[paper](https://arxiv.org/abs/2501.00752)]
[[code](https://github.com/SuhoPark0706/FCP)]
[2025.01]

- **ScarNet:** Neda Tavakoli, Amir Ali Rahsepar, Brandon C. Benefield, Daming Shen, Santiago López-Tapia, Florian Schiffers, Jeffrey J. Goldberger, Christine M. Albert, Edwin Wu, Aggelos K. Katsaggelos, Daniel C. Lee, Daniel Kim.<br />
"ScarNet: A Novel Foundation Model for Automated Myocardial Scar Quantification from LGE in Cardiac MRI." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.01372)]
[2025.01]

- **EUGIS:** Jiang Shang, Yuanmeng Wu, Xiaoxiang Han, Xi Chen and Qi Zhang.<br />
"Evidential Calibrated Uncertainty-Guided Interactive Segmentation paradigm for Ultrasound Images." ArXiv (2025).
[[paper](https://arxiv.org/abs/2501.01072)]
[[code](https://github.com/JiangVentinal/EUGIS)]
[2025.01]

#### 2024
[Paper list 2024](https://github.com/liliu-avril/Awesome-Segment-Anything/blob/main/Paper_List/paper_list_2024.md)

#### 2023
[Paper list 2023](https://github.com/liliu-avril/Awesome-Segment-Anything/blob/main/Paper_List/paper_list_2023.md)

## Open Source Projects
| No. | Project | Title | Project page | Code base | Affiliation | Description |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 000 | SAM | Segment Anything | [Project page](https://segment-anything.com/)  | [Code](https://github.com/facebookresearch/segment-anything) | Meta | A foundation model for general image segmentation. |
| 001 | SAM2 | Segment Anything Model 2 | [Project page](https://ai.meta.com/sam2)  | [Code](https://github.com/facebookresearch/segment-anything-2) | Meta | A video foundation model. |
| 002 | SAM-Track | Segment and Track Anything | [Colab](https://colab.research.google.com/drive/1R10N70AJaslzADFqb-a5OihYkllWEVxB?usp=sharing)  |  [Code](https://github.com/z-x-yang/Segment-and-Track-Anything)   |   Zhejiang University    |    A  project dedicated to tracking and segmenting any objects in videos, either automatically or interactively. |
| 003  |  Grounded-SAM  |  Grounded-Segment-Anything  |  [Colab](https://github.com/camenduru/grounded-segment-anything-colab)   |  [Code](https://github.com/IDEA-Research/Grounded-Segment-Anything)    |  IDEA-Research   |    A project by combining Grounding DINO and SAM which aims to detect and segment Anything with text inputs. |
| 004  |  MMDet-SAM  |  -  |  -   |  [Code](https://github.com/open-mmlab/playground/tree/main/mmdet_sam)    |   OpenMMLab    |    A new way of instance segmentation by combining SAM with Closed-Set Object Detection, Open-Vocabulary Object Detection, Grounding Object Detection. |
| 005  |  MMRotate-SAM  |  Zero-shot Oriented Object Detection with SAM  |  -   |  [Code](https://github.com/open-mmlab/playground/tree/main/mmrotate_sam)    |   OpenMMLab    |    A project join SAM and weakly supervised horizontal box detection to achieve rotated box detection. |
| 006  |  MMOCR-SAM  |  -  |  -   |  [Code](https://github.com/open-mmlab/playground/tree/main/mmocr_sam)    |   OpenMMLab    |    A solution of Text Detection/Recognition and SAM that segments every text character, with striking text removal and text inpainting demos driven by diffusion models and Gradio. |
| 007  |  MMEditing-SAM  |  -  |  -   |  [Code](https://github.com/open-mmlab/playground/tree/main/mmagic_sam)    |   OpenMMLab    |    A project join SAM and image generation to create awesome images and edit any part of them. |
|  008  |  Label-Studio-SAM  |  OpenMMLab PlayGround: Semi-Automated Annotation with Label-Studio and SAM  |  -   |  [Code](https://github.com/open-mmlab/playground/tree/main/label_anything)    |   OpenMMLab     |    A project combining Label-Studio and SAM to achieve semi-automated annotation. |
|  009  |  PaddleSeg  |  Segment Anything with PaddleSeg  |  -   |  [Code](https://github.com/PaddlePaddle/PaddleSeg/tree/release/2.8/contrib/SegmentAnything)   |   PaddlePaddle   |    A pretrained model parameters of PaddlePaddle format.|
| 010  |  SegGPT  |  Segmenting Everything In Context  |  [Hugging Face](https://huggingface.co/spaces/BAAI/SegGPT)   |  [Code](https://github.com/baaivision/Painter)    |   BAAI-Vision    |    SAM In Context based on Painter. |
| 011  |  SEEM  |  Segment Everything Everywhere All at Once  |  [Hugging Face](https://huggingface.co/spaces/xdecoder/SEEM)   |  [Code](https://github.com/UX-Decoder/Segment-Everything-Everywhere-All-At-Once)    |   Microsoft    |    A project can Segment Everything Everywhere with Multi-modal prompts all at once. |
| 012  |  CLIP Surgery  |  CLIP Surgery for Better Explainability with Enhancement in Open Vocabulary Tasks   |  [Project page](https://github.com/xmed-lab/CLIP_Surgery/blob/master/demo.ipynb)   |  [Code](https://github.com/xmed-lab/CLIP_Surgery)    |   HKUST    |    A work about SAM based on CLIP's explainability to achieve text to mask without manual points. |
| 013  |  SAMCOD  | Can SAM Segment Anything? When SAM Meets Camouflaged Object Detection |-|[Code](https://github.com/luckybird1994/SAMCOD)|-|SAM +Camouflaged object detection (COD) task.|
| 014  |  Inpaint Anything  |  Segment Anything Meets Image Inpainting  |  [Hugging Face](https://huggingface.co/spaces/InpaintAI/Inpaint-Anything)  |  [Code](https://github.com/geekyutao/Inpaint-Anything)    |   USTC and EIT    |    SAM combines Inpainting, which is able to remove the object smoothly. |
|  015  |  PerSAM  |  Personalize Segment Anything Model with One Shot  |  [Hugging Face](https://huggingface.co/papers/2305.03048)   |  [Code](https://github.com/ZrrSkywalker/Personalize-SAM)    |    -   |  SAM with specific concepts.  |
| 016  |  MedSAM  |  Segment Anything in Medical Images|  -   |  [Code](https://github.com/bowang-lab/MedSAM)    |   -    |    A step-by-step tutorial with a small dataset to help you quickly utilize SAM. |
| 017  |  Segment-Any-Anomaly  |  GroundedSAM Anomaly Detection  |  [Colab](https://colab.research.google.com/drive/1Rwio_KfziuLp79Qh_ugum64Hjnq4ZwsE?usp=sharing)  |  [Code](https://github.com/caoyunkang/Segment-Any-Anomaly)    |   HUST   |    Grounding DINO + SAM to segment any anomaly. |
| 018  |   SSA  |  Semantic Segment Anything  |  -   |  [Code](https://github.com/fudan-zvg/Semantic-Segment-Anything)    |   Fudan University    |    A dense category annotation engine. |
| 019  |  Magic Copy  |  -  |  -   |  [Code](https://github.com/kevmo314/magic-copy)    |   -   |    Magic Copy is a Chrome extension that uses SAM to extract a foreground object from an image and copy it to the clipboard. |
| 020  |  Segment Anything with Clip  |  Segment Anything with Clip  |  [Hugging Face](https://huggingface.co/spaces/curt-park/segment-anything-with-clip)   |  [Code](https://github.com/Curt-Park/segment-anything-with-clip)    |   -    |    SAM combined with CLIP. |
| 021  |  MetaSeg  |  Segment Anything Video|  [Hugging Face](https://huggingface.co/spaces/ArtGAN/Segment-Anything-Video)   |  [Code](https://github.com/kadirnar/segment-anything-video)   |   -    |   Packaged version of the SAM. |
| 022 |  SAM in Napari  |  Segment Anything Model (SAM) in Napari  |  [Project page](https://www.napari-hub.org/plugins/napari-sam)   |  [Code](https://github.com/MIC-DKFZ/napari-sam)    |   Applied Computer Vision Lab and German Cancer Research Center   |    Extended SAM's click-based foreground separation to full click-based semantic segmentation and instance segmentation. |
| 023  |  SAM Medical Imaging  |  SAM Medical Imaging  |  -   | [Code](https://github.com/amine0110/SAM-Medical-Imaging)    |   - | SAM for Medical Imaging.|
|  024  |  3D-Box  |  3D-Box via Segment Anything  |  -   |  [Code](https://github.com/dvlab-research/3D-Box-Segment-Anything)    |   -    |    SAM is extended to 3D perception by combining it with VoxelNeXt. |
| 025  |  Anything-3D  |  -  |  -   |  [Code](https://github.com/Anything-of-anything/Anything-3D)    |   -    |    Anything 3DNovel View, Anything-NeRF, Any 3DFace. |
| 026  |  L2SET  |  Learning to Segment EveryThing  |   -   |  [Code](https://github.com/ronghanghu/seg_every_thing)   |  UC Berkeley, FAIR    |   A new partially supervised training paradigm for instance segmentation. |
| 027  |  Edit Anything  |  Edit Anything by Segment-Anything  |  -   |  [Code](https://github.com/sail-sg/EditAnything)    |   -    |    Edit anything in images powered by SAM, ControlNet, StableDiffusion, \etc. |
| 028  |  Image Edit Anything  |  IEA: Image Editing Anything  |  -   |  [Code](https://github.com/feizc/IEA)    |   -    |  Using stable diffusion and SAM for image editing.   |
| 029  |  SAM for Stable Diffusion Webui  |  Segment Anything for Stable Diffusion WebUI  |  -   |  [Code](https://github.com/continue-revolution/sd-webui-segment-anything)   |   -    |    This extension aim for connecting AUTOMATIC1111 Stable Diffusion WebUI and Mikubill ControlNet Extension with SAM and GroundingDINO to enhance Stable Diffusion/ControlNet inpainting. |
| 030  |  Earth Observation Tools  |  Segment Anything EO tools  |  [Colab](https://colab.research.google.com/drive/1RC1V68tD1O-YissBq9nOvS2PHEjAsFkA?usp=share_link)   |  [Code](https://github.com/aliaksandr960/segment-anything-eo)    |   -    |    An earth observation tools for SAM. |
| 031  |  Moving Object Detection  |  Towards Segmenting Anything That Moves  |  -   |  [Code](https://github.com/achalddave/segment-any-moving) | - | A project about SAM + Moving Object Detection.|
|  032  |  OCR-SAM  |  Optical Character Recognition with Segment Anything  | [Project page](https://www.zhihu.com/question/593914819/answer/2976012032) | [Code](https://github.com/yeungchenwa/OCR-SAM)   |   -    |  Combining MMOCR with SAM and Stable Diffusion. |
| 033  |  SALT  |  Segment Anything Labelling Tool  |  -   |  [Code](https://github.com/anuragxel/salt#segment-anything-labelling-tool-salt)    |   -    |   A project uses the SAM Model and adds a barebones interface to label images and saves the masks in the COCO format. |
|  034  |  Prompt Segment Anything  |  Prompt Segment Anything  |  -   |  [Code](https://github.com/RockeyCoss/Prompt-Segment-Anything)    |   -    |    An implementation of zero-shot instance segmentation using SAM. |
| 035  |  SAM-RBox  |  -  |  -   |  [Code](https://github.com/Li-Qingyun/sam-mmrotate)    |   -    |   A project uses SAM for generating rotated bounding boxes with MMRotate, which is a comparison method of H2RBox-v2. |
| 036  |  VISAM  |  MOTRv2: Bootstrapping End-to-End Multi-Object Tracking by Pretrained Object Detectors  |-|[Code](https://github.com/BingfengYan/VISAM) |-|   Combining SAM with MOT, it create the era of "MOTS". |
| 037  |  SegEO  |  Segment Anything EO tools  |  -   |  [Code](https://github.com/aliaksandr960/segment-anything-eo)    |   -    |    The tools are developed to ease the processing of spatial data (GeoTIFF and TMS) with SAM using sliding window algorithm for big files. |
| 038  |  Napari Segment Anything |  Napari Segment Anything  |  [Project page](https://app.codecov.io/gh/jookuma/napari-segment-anything)   |  [Code](https://github.com/JoOkuma/napari-segment-anything)    |   -    |    SAM native Qt UI. |
| 039  |  Segment-Anything-U-Specify  |  Segment-Anything-U-Specify  |  -   |  [Code](https://github.com/MaybeShewill-CV/segment-anything-u-specify)    |   -    |  Using CLIP and SAM to segment any instance you specify with text prompt of any instance names. |
|  040  |  SegDrawer  |  Simple static web-based mask drawer  |  [Colab](https://colab.research.google.com/drive/1PdWCpBgYwiQtvkdTBnW-y2T-s_Fc-2iI?usp=sharing)  |  [Code](https://github.com/lujiazho/SegDrawer)    |   -    |    Simple static web-based mask drawer, supporting semantic segmentation with SAM. |
| 041  |  Track Anything  |  Segment Anything Meets Videos  |  [Hugging Face](https://huggingface.co/spaces/VIPLab/Track-Anything)   |  [Code](https://github.com/gaomingqi/Track-Anything)    |   SUSTech    | Track-Anything is a flexible and interactive tool for video object tracking and segmentation. |
| 042  |  Count Anything  |  -  |  -   |  [Code](https://github.com/ylqi/Count-Anything)   |   -    |    A method uses SAM and CLIP to ground and count any object that matches a custom text prompt, without requiring any point or box annotation. |
|  043  |  RAM  |  Relate Anything Model   |  [Hugging Face](https://huggingface.co/spaces/mmlab-ntu/relate-anything-model)   |  [Code](https://github.com/Luodian/RelateAnything)    |   MMLab, NTU and VisCom Lab, KCL/TongJi    |    Relate Anything Model is capable of taking an image as input and utilizing SAM to identify the corresponding mask within the image. |
| 044  |  Segment Any RGBD  |  Segment Any RGBD  |  [Project page](https://github.com/Jun-CEN/SegmentAnyRGBD)   |   [Code](https://huggingface.co/spaces/jcenaa/Segment-Any-RGBD)   |   -    |   Segment AnyRGBD is a toolbox to segment rendered depth images based on SAM. |
|  045  |  Show Anything  |  Show Anything  |  [Hugging Face](https://huggingface.co/spaces/weijiawu/ImageEditAnything)  |  [Code](https://github.com/showlab/ShowAnything)    |   Showlab, NUS    |    Some Applications that are compatible with both SAM and Generation. |
| 046  |  Transfer Any Style|  Any-to-Any Style Transfer: Making Picasso and Da Vinci Collaborate  |  -   |  [Code](https://github.com/Huage001/Transfer-Any-Style)    |   LV-lab, NUS    |   An interactive demo based on Segment-Anything for style transfer which enables different content regions apply different styles. |
| 047  |  Caption Anything  |  -  |  [Colab](https://colab.research.google.com/github/ttengwang/Caption-Anything/blob/main/notebooks/tutorial.ipynb)  |   [Code](https://github.com/ttengwang/Caption-Anything)   |  VIP lab, SUSTech   |    Caption-Anything is a versatile image processing tool that combines the capabilities of SAM, Visual Captioning, and ChatGPT.  |
|  048  |  Image2Paragraph  |  Transform Image Into Unique Paragraph  |  [Project page](https://zhaohengyuan1.github.io/image2paragraph.github.io/)  |  [Code](https://github.com/showlab/Image2Paragraph)  |  -  |  Transform Image into Unique Paragraph with ChatGPT, BLIP2, OFA, GRIT, Segment Anything, ControlNet. |
| 049    |  LIME SAM  |  Local Interpretable Model-agnostic Explanations Segment Anything  |  [Colab](https://colab.research.google.com/drive/1bj6B-O47NHpqsWovOrVZcpWNhIfO56sj?usp=sharing)  |  [Code](https://github.com/jaydeep-work/LIME-SAM)  |  -  | LIME-SAM aims to create an Explainable Artificial Intelligence (XAI) framework for image classification using LIME (Local Interpretable Model-agnostic Explanations) as the base algorithm, with the super-pixel method replaced by SAM. |
|  050  |  Paint Anything  |  -  |  -  |  [Code](https://github.com/Huage001/Paint-Anything)  |  -  |  An interactive demo based on SAM for stroke-based painting which enables human-like painting. |
| 051  |  SAMed  |  Customized Segment Anything Model for Medical Image Segmentation  |  [Colab](https://colab.research.google.com/drive/1KCS5ulpZasYl9DgJJn59WsGEB8vwSI_m?usp=sharing)  |  [Code](https://github.com/hitachinsk/SAMed)  |  USTC  |  SAMed is built upon the large-scale image segmentation model, SAM, to explore the new research paradigm of customizing large-scale models for medical image segmentation. |
| 052  |  Personalize SAM  |  Personalize Segment Anything with 1 Shot in 10 Seconds  |  [Hugging Face](https://huggingface.co/spaces/justin-zk/Personalize-SAM)  |  [Code](https://github.com/ZrrSkywalker/Personalize-SAM)  |  MMLab, CUHK  |  A training-free Personalization approach for SAM, termed as PerSAM. Given only a single image with a reference mask, PerSAM can segment specific visual concepts. |
| 053  |  Open-vocabulary-Segment-Anything  | Open-vocabulary-Segment-Anything  |  -  |  [Code](https://github.com/ngthanhtin/owlvit_segment_anything)  |  -  |  Combining OwlViT with Segment Anything - Open-vocabulary Detection and Segmentation (Text-conditioned, and Image-conditioned). |
| 054  |  Labal-Anything-Pipeline  |  Label-Anything-Pipeline |  -  |  [Code](https://github.com/Yuqifan1117/Labal-Anything-Pipeline)  |  ZJU  |  Annotation anything in visual tasks just all in one-pipeline with GPT-4 and SAM. |
| 055  |  Grounded-Segment-Any-Parts  |  Grounded Segment Anything: From Objects to Parts  |  [Project page](https://cheems-seminar.github.io/)  |  [Code](https://github.com/Cheems-Seminar/grounded-segment-any-parts)  |  HKU  |  Expand Segment Anything Model (SAM) to support text prompt input. The text prompt could be object-level(eg, dog) and part-level(eg, dog head).  |
| 056  |  AnyLabeling  |  AnyLabeling  |  [Youtube page](https://www.youtube.com/watch?v=5qVJiYNX5Kk)  |  [Code](https://github.com/vietanhdev/anylabeling)  |  -  |  Effortless AI-assisted data labeling with AI support from Segment Anything and YOLO. |
| 057  |  SSA |  Semantic-Segment-Anything  |  [Project page](https://replicate.com/cjwbw/semantic-segment-anything)  |  [Code](https://github.com/fudan-zvg/Semantic-Segment-Anything)  |  -  |  Automated dense category annotation engine that serves as the initial semantic labeling for the Segment Anything dataset (SA-1B). |
| 058  |  RefSAM |  Label Data with Segment Anything in Roboflow  |  [Project page](https://blog.roboflow.com/label-data-segment-anything-model-sam/)   |  [Code](https://github.com/helblazer811/RefSAM)  |  -  |  Referring Image Segmentation Benchmarking with Segment Anything Model (SAM). |
| 059  |  Roboflow Annotate |  Launch: Label Data with Segment Anything in Roboflow  |  [Project page](https://blog.roboflow.com/label-data-segment-anything-model-sam/)  |  [APP](https://app.roboflow.com/)  |  Roboflow  |  SAM-assisted labeling for training computer vision models. |
| 060  |  ImageBind SAM |  -  |  -  |  [Code](https://github.com/IDEA-Research/Grounded-Segment-Anything/tree/main/playground/ImageBind_SAM)  |  IDEA-Research  |  This is an experimental demo aims to combine ImageBind and SAM to generate mask with different modalities. |
| 061  | X-AnyLabeling	|   X-AnyLabeling	|  [WeChat](https://mp.weixin.qq.com/s/Fi7i4kw0n_QsA7AgmtP-JQ) | 	[Code](https://github.com/CVHub520/X-AnyLabeling)	| CVHub	| A new interactive automatic labeling tool based on AnyLabeling.|
| 062  |Segment Anything + NNCF |	-	| [WeChat](https://mp.weixin.qq.com/s/LrUx1HEYPCU41k5VZDa7fg) |	[Code](https://github.com/openvinotoolkit/openvino_notebooks/blob/main/notebooks/237-segment-anything/237-segment-anything.ipynb)	 |  -	 | OpenVINO™ NNCF for segment anything encoder quantization acceleration.|
| 063  |YOLOv8 + SAM	|  - | 	[WeChat](https://mp.weixin.qq.com/s/-rbsvGfc-Q8LZANzUWwn-A) |	-	| - |	Use SAM in YOLOv8. |
| 064  |SearchAnything|  SearchAnything | [Zhihu blog](https://zhuanlan.zhihu.com/p/641128049), [Twitter](https://twitter.com/jd92wang/status/1676114619168067585)	 |[Code](https://github.com/Immortalise/SearchAnything)	| CAS and MSRA |	A semantic local search engine powered by various AI models. |
| 065  |SAM Meets Stable Diffusion 	|  - | 	[WeChat](https://mp.weixin.qq.com/s/HBl-PBdi4Hi6z4Z2FjiYIA) |	[Code](https://aistudio.baidu.com/aistudio/projectdetail/6300584)	| PaddlePaddle |	Segment and generate Anything. |
| 066  |Language Segment-Anything| - | - | [Code](https://github.com/luca-medeiros/lang-segment-anything) | - | SAM with text prompts generates masks for specific objects in images. |
| 067  |Expedit-SAM| - | - | [Code](https://github.com/Expedit-LargeScale-Vision-Transformer/Expedit-SAM) | - | Expediting SAM without Fine-tuning. |
| 068  |Segment-Anything-Fast |  Accelerating Generative AI with PyTorch: Segment Anything, Fast  |  [Project page](https://pytorch.org/blog/accelerating-generative-ai/)  |  [Code](https://github.com/pytorch-labs/segment-anything-fast)  | Team PyTorch | A batched offline inference oriented version of segment-anything. |
| 069  |YOLOv9+SAM |YOLOv9+SAM   |  [Project page](https://zhuanlan.zhihu.com/p/689061673)  |  [Code](https://zhuanlan.zhihu.com/p/689061673)  | - | Dynamic Detection and Segmentation with YOLOv9+SAM. |
| 070  | LiteMedSAM  | LiteMedSAM   |  [Project page](https://github.com/bowang-lab/MedSAM/tree/LiteMedSAM)  |  [Code](https://github.com/bowang-lab/MedSAM/tree/LiteMedSAM)  | - | A lightweight version of MedSAM for fast training and inference. |
| 071  | ISAT_with_segment_anything  | ISAT_with_segment_anything   |  [Project page](https://github.com/yatengLG/ISAT_with_segment_anything)  |  [Code](https://github.com/yatengLG/ISAT_with_segment_anything)  | - | An Interactive Semi-automatic Annotation Tool based on segment anything model, supporting SAM, SAM2, SAM-HQ, MobileSAM, EdgeSAM, etc. |
| 072  |  Track Anything Annotate    | Track Anything Annotate      | [Project page](https://github.com/lnikioffic/track-anything-annotate)  |  [Code](https://github.com/lnikioffic/track-anything-annotate)  | - | A video annotation tool combining SAM2 and Xmem++. |

## Awesome Repositories for SAM
- [VainF/Awesome-Anything](https://github.com/VainF/Awesome-Anything)
- [Hedlen/Awesome Segment Anything](https://github.com/Hedlen/awesome-segment-anything)
- [Vision-Intelligence-and-Robots-Group/Awesome-Segment-Anything](https://github.com/Vision-Intelligence-and-Robots-Group/Awesome-Segment-Anything)
- [JerryX1110/Awesome-segment-anything-extensions](https://github.com/JerryX1110/awesome-segment-anything-extensions)
- [dk-liang/Awesome-Segment-Anything](https://github.com/dk-liang/Awesome-Segment-Anything)


## License
This project is released under the MIT license. Please see the [LICENSE](LICENSE) file for more information.

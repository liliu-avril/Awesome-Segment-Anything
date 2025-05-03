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


### Follow-up Papers
#### The latest papers within a week are marked with a :boom:
#### 2025
:boom:Yamagishi Y, Hanaoka S, Kikuchi T, Nakao T, Nakamura Y, Nomura Y, Miki S, Yoshikawa T, Abe O.<br />
"Using Segment Anything Model 2 for Zero-Shot 3D Segmentation of Abdominal Organs in Computed Tomography Scans to Adapt Video Tracking Capabilities for 3D Medical Imaging: Algorithm Development and Validation." JMIR AI (2025).
[[paper](https://ai.jmir.org/2025/1/e72109)]
[2025.05]

:boom: Chen, Jinlong, Fuqiang Jin, Yingjie Jiao, Yongsong Zhan, and Xingguo Qin.<br />
"Improving Dynamic Gesture Recognition with Attention-Enhanced LSTM and Grounding SAM." Electronics (2025).
[[paper](https://www.mdpi.com/2079-9292/14/9/1793)]
[2025.05]

:boom:Angelo Moroncelli and Sylvain Populus and Armand Rossi and Emanuele Carpanzano and Loris Roveda.<br />
"Vision-based robotic disassembly of aircraft engines with YOLO-SAM: a novel method for task orientation estimation." CIRP Annals (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S0007850625001106)]
[2025.05]

:boom:**ICA-SAMv7:** Xiaotian Yan and Yuting Guo and Ziyi Pei and Xinyu Zhang and Jinghao Li and Zitao Zhou and Lifang Liang and Shuai Li and Peng Lun and Aimin Hao.<br />
"ICA-SAMv7: Internal carotid artery segmentation with coarse to fine network." Computerized Medical Imaging and Graphics (2025).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S0895611125000643)]
[[code](https://github.com/BessiePei/ICA-SAMv7)]
[2025.05]

:boom:Muturi, T. W., & Adu-Gyamfi, Y.<br />
"Enhanced Crack Segmentation Using Meta’s Segment Anything Model with Low-Cost Ground Truths and Multimodal Prompts." ArXiv (2025).
[[paper](https://journals.sagepub.com/doi/abs/10.1177/03611981251322484)]
[2025.05]

:boom:**UN-SAM:** Zhen Chen and Qing Xu and Xinyu Liu and Yixuan Yuan.<br />
"UN-SAM: Domain-adaptive self-prompt segmentation for universal nuclei images." Medical Image Analysis (2025).
[[paper](https://www.sciencedirect.com/science/article/pii/S1361841525001549)]
[[code](https://github.com/CUHK-AIM-Group/UN-SAM)]
[2025.05]

:boom:Milman, Oded, Dovi Yellin, and Yehudit Aperstein.<br />
"Adapting SAM for Visible-Light Pupil Segmentation Baseline." Electronics (2025).
[[paper](https://www.mdpi.com/2079-9292/14/9/1850)]
[2025.05]

:boom:**SV-Unet:** Wei Wang and Chong Yu and Tengyu Zhang and Feiyu Chen and Yufan Liu and Zongze Wu.<br />
"Oversized ore segmentation using SAM-enhanced U-Net with self-supervised pre-training and semi-supervised self-training." Expert Systems with Applications (2025).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S095741742501601X)]
[2025.05]

:boom:**SAM-Brain3D:** Zhongying Deng, Haoyu Wang, Ziyan Huang, Lipei Zhang, Angelica I. Aviles-Rivero, Chaoyu Liu, Junjun He, Zoe Kourtzi, Carola-Bibiane Schönlieb.<br />
"Brain Foundation Models with Hypergraph Dynamic Adapter for Brain Disease Analysis." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.00627)]
[2025.05]

:boom:Shuang Zhang, Carleton Coffin, Karyn L. Rogers, Catherine Ann Royer, Ge Wang.<br />
"AI-Driven High-Resolution Cell Segmentation and Quantitative Analysis." ArXiv (2025).
[[paper](https://arxiv.org/abs/2505.00578)]
[2025.05]

:boom:**IDRA-H:** Marc Glocker, Peter Hönig, Matthias Hirschmanner, Markus Vincze.<br />
"LLM-Empowered Embodied Agent for Memory-Augmented Task Planning in Household Robotics." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.21716)]
[[code](https://github.com/marc1198/chat-hsr)]
[2025.04]

:boom:**SAM4EM:** Uzair Shah, Marco Agus, Daniya Boges, Vanessa Chiappini, Mahmood Alzubaidi, Jens Schneider, Markus Hadwiger, Pierre J. Magistretti, Mowafa Househ, Corrado Calı.<br />
"SAM4EM:Efficient memory-based two stage prompt-free segment anything model adapter for complex 3D neuroscience electron microscopy stacks." CVPRW (2025).
[[paper](https://arxiv.org/abs/2504.21544)]
[[code](https://github.com/Uzshah/SAM4EM)]
[2025.04]

:boom:**UniBiomed:** Linshan Wu, Yuxiang Nie, Sunan He, Jiaxin Zhuang, Hao Chen.<br />
"UniBiomed: A Universal Foundation Model for Grounded Biomedical Image Interpretation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.21336)]
[2025.04]

:boom:**RadSAM:** Julien Khlaut, Elodie Ferreres, Daniel Tordjman, Hélène Philippe, Tom Boeken, Pierre Manceron, Corentin Dancette.<br />
"RadSAM: Segmenting 3D radiological images with a 2D promptable model." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.20837)]
[2025.04]

:boom:**RRL-MedSAM:** Jia Wang, Yunan Mei, Jiarui Liu, and Xin Fan.<br />
"SAM-Guided Robust Representation Learning for One-Shot 3D Medical Image Segmentation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.20501)]
[2025.04]

:boom:**Follow Everything:** Qianyi Zhang, Shijian Ma, Boyi Liu, Jingtai Liu, Jianhao Jiao, Dimitrios Kanoulas.<br />
"Follow Everything: A Leader-Following and Obstacle Avoidance Framework with Goal-Aware Adaptation." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.19399)]
[[code](https://follow-everything.github.io/)]
[2025.04]

:boom:**Res-SAM:** Xiren Zhou, Shikang Liu, Xinyu Yan, Yizhan Fan, Xiangyu Wang, Yu Kang, Jian Cheng, Huanhuan Chen.<br />
"Reservoir-enhanced Segment Anything Model for Subsurface Diagnosis." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.18802)]
[2025.04]

:boom:**RSFR:** Jiahao Huang, Fanwen Wang, Pedro F. Ferreira, Haosen Zhang, Yinzhe Wu, Zhifan Gao, Lei Zhu, Angelica I. Aviles-Rivero, Carola-Bibiane Schonlieb, Andrew D. Scott, Zohya Khalique, Maria Dwornik, Ramyah Rajakulasingam, Ranil De Silva, Dudley J. Pennell, Guang Yang, Sonia Nielles-Vallespin.<br />
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
"Improving SAM for Camouflaged Object Detection via Dual Stream Adapters." ArXiv (2025).
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


## Awesome Repositories for SAM
- [VainF/Awesome-Anything](https://github.com/VainF/Awesome-Anything)
- [Hedlen/Awesome Segment Anything](https://github.com/Hedlen/awesome-segment-anything)
- [Vision-Intelligence-and-Robots-Group/Awesome-Segment-Anything](https://github.com/Vision-Intelligence-and-Robots-Group/Awesome-Segment-Anything)
- [JerryX1110/Awesome-segment-anything-extensions](https://github.com/JerryX1110/awesome-segment-anything-extensions)
- [dk-liang/Awesome-Segment-Anything](https://github.com/dk-liang/Awesome-Segment-Anything)


## License
This project is released under the MIT license. Please see the [LICENSE](LICENSE) file for more information.

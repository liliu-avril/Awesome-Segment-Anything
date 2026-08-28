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

:boom:**[SAM 3.1](https://github.com/facebookresearch/sam3/blob/main/RELEASE_SAM3p1.md): ''SAM 3.1 Object Multiplex'' was released.**

:boom:**[SAM Audio](https://github.com/facebookresearch/sam-audio): ''SAM Audio: Segment Anything in Audio'' was released.**

:boom:**[SAM 3D](https://github.com/facebookresearch/sam-3d-objects?tab=readme-ov-file#citing-sam-3d-objects): ''SAM 3D: 3Dfy Anything in Images'' was released.**

:boom:**[SAM 3](https://github.com/facebookresearch/sam3): ''SAM 3: Segment Anything with Concepts'' was released.**

:boom:**[SAM 2](https://github.com/facebookresearch/segment-anything-2): ''Segment Anything in Images and Videos'' was released.**

:boom:**[SAM](https://github.com/facebookresearch/segment-anything): ''Segment Anything'' was released.**

:boom:**[SAM & SAM2 for videos](https://github.com/983632847/SAM-for-Videos): The first survey on Segment Anything for Videos: A Systematic Survey was online.**
____


## :fire: Highlights
![Last Updated](https://badgen.net/github/last-commit/liliu-avril/Awesome-Segment-Anything?icon=github&label=last%20updated&color=green)
```
- 2026.06.05: SAM 3D won the CVPR 2026 Best Paper Honorable Mention.
- 2026.03.27: SAM 3.1 Object Multiplex was released.
- 2025.12.15: SAM Audio was released.
- 2025.11.19: SAM 3 and SAM 3D were released.
- 2025.10.11: SAM 3 arrives! Officially announced and set to launch.
- 2025.04.22: SAM 2 won the ICLR 2025 Best Paper Honorable Mention.
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
    - [2026](#2026)
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
- **The First Comprehensive SAM Survey:** Chunhui Zhang, Li Liu, Yawen Cui, Guanjie Huang, Weilin Lin, Yiqian Yang, Yuehong Hu.<br />
  "A Comprehensive Survey on Segment Anything Model for Vision and Beyond." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2305.08196)]
  [[homepage]](https://github.com/liliu-avril/Awesome-Segment-Anything)
  [[中文解读]](https://mp.weixin.qq.com/s/uYpRzvRp22-40x8e0pLVIg)
  [2023.05]

- **The First Survey on SAM & SAM2 for Videos:** Chunhui Zhang, Yawen Cui, Weilin Lin, Guanjie Huang, Yan Rong, Li Liu, Shiguang Shan.<br />
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

- Xiaorui Sun, Jun Liu, Heng Tao Shen, Xiaofeng Zhu, Ping Hu.<br />
  "On Efficient Variants of Segment Anything Model: A Survey." IJCV (2025).
  [[paper](https://arxiv.org/abs/2410.04960)] 
  [2024.10]
  
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

- **WanSAM4RS-Tracker:** Zhipeng Wan and Sheng Wang and Wei Han and Yuewei Wang and Xiaohui Huang and Xiaohan Zhang and Xiaodao Chen and Yunliang Chen.<br />
"A systematic survey and meta-analysis of the segment anything model in remote sensing image processing: Challenges, advances, applications, and opportunities." ISPRS Journal of Photogrammetry and Remote Sensing (2025).
[[paper](https://doi.org/10.1016/j.isprsjprs.2025.08.023)]
[[project](https://github.com/WanZhan-lucky/WanSAM4RS-Tracker)]
[2025.09]

- Yang, Yizai and Cheng, Lechao and Wang, Yaxiong and Hui, Tianrui and Li, Wenjing and Zhong, Zhun.<br />
"A Survey for Point Prompt of Segment Anything Model." MMAsia Workshops (2025).
[[paper](https://dl.acm.org/doi/full/10.1145/3769748.3773346)]
[2025.12]


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

- **SAM 3:** Nicolas Carion*, Laura Gustafson*, Yuan-Ting Hu*, Shoubhik Debnath*, Ronghang Hu*, Didac Suris*, Chaitanya Ryali*, Kalyan Vasudev Alwala*, Haitham Khedr*, Andrew Huang, Jie Lei, Tengyu Ma, Baishan Guo, Arpit Kalla, Markus Marks, Joseph Greer, Meng Wang, Peize Sun, Roman Rädle, Triantafyllos Afouras, Effrosyni Mavroudi, Katherine Xu°, Tsung-Han Wu°, Yu Zhou°, Liliane Momeni°, Rishi Hazra°, Shuangrui Ding°, Sagar Vaze°, Francois Porcher°, Feng Li°, Siyuan Li°, Aishwarya Kamath°, Ho Kei Cheng°, Piotr Dollar†, Nikhila Ravi†, Kate Saenko†, Pengchuan Zhang†, Christoph Feichtenhofer†.<br />
  "SAM 3: Segment Anything with Concepts." ICLR (2026). 
  [[paper](https://scontent-hkg1-2.xx.fbcdn.net/v/t39.2365-6/586037495_2236299700208804_3520531923593328648_n.pdf?_nc_cat=107&ccb=1-7&_nc_sid=3c67a6&_nc_ohc=nmZfwAXlWFIQ7kNvwG4Ziha&_nc_oc=AdkN4o3mxVR9EsmETWKcD22Es9j13TyVnzBM4i12yV--s4BBVU7JRjK7o5i8gmi3GXY&_nc_zt=14&_nc_ht=scontent-hkg1-2.xx&_nc_gid=cv151uZyJ6W0M4xGA5YJeg&oh=00_AfhGOif-baPFkfDU5Os8PdgwzC4mo825cMW2vNKx2E9vog&oe=6924E449)]
  [[arXiv](https://arxiv.org/abs/2511.16719)]
  [[code](https://github.com/facebookresearch/sam3)]
  [[homepage](https://ai.meta.com/sam3/)] 
  [[中文解读](https://zhuanlan.zhihu.com/p/1961100103482873205)]
  [2025.10]

- **SAM 3D:** SAM 3D Team, Xingyu Chen, Fu-Jen Chu, Pierre Gleize, Kevin J Liang, Alexander Sax, Hao Tang Weiyao Wang, Michelle Guo, Thibaut Hardin, Xiang Li, Aohan Lin, Jiawei Liu, Ziqi Ma, Anushka Sagar, Bowen Song, Xiaodong Wang, Jianing Yang, Bowen Zhang, Piotr Dollár, Georgia Gkioxari, MattFeiszli, Jitendra Malik.<br />
"SAM 3D: 3Dfy Anything in Images." CVPR (2026). **CVPR (2026) Best Paper Honorable Mention**.
[[paper](https://ai.meta.com/research/publications/sam-3d-3dfy-anything-in-images/)]
[[code](https://github.com/facebookresearch/sam-3d-objects)]
[[project](https://ai.meta.com/sam3d/)]
[[demo](https://www.aidemos.meta.com/segment-anything/editor/convert-image-to-3d)]
[[blog](https://ai.meta.com/blog/sam-3d/)]
[[中文解读](https://zhuanlan.zhihu.com/p/1974819250574209615)]
[2025.11]

- **SAM 3D Body:** Xitong Yang⋆, Devansh Kukreja⋆, Don Pinkus⋆, Anushka Sagar, Taosha Fan, Jinhyung Park◦, Soyong Shin◦, Jinkun Cao, Jiawei Liu, Nicolas Ugrinovic, Matt Feiszli†, Jitendra Malik†, Piotr Dollar†, Kris Kitani†.<br />
"SAM 3D Body: Robust Full-Body Human Mesh Recovery." ArXiv (2025).
[[paper](https://ai.meta.com/research/publications/sam-3d-body-robust-full-body-human-mesh-recovery/)]
[[code](https://github.com/facebookresearch/sam-3d-body)]
[[project](https://ai.meta.com/sam3d)]
[2025.11]

- **SAM Audio:** Bowen Shi∗, Andros Tjandra∗, John Hoffman∗, Helin Wang∗, Yi-Chiao Wu∗, Luya Gao∗, Julius Richter†,Matt Le†, Apoorv Vyas†, Sanyuan Chen†, Christoph Feichtenhofer‡, Piotr Dollár‡, Wei-Ning Hsu‡, Ann Lee‡.<br />
"SAM Audio: Segment Anything in Audio." ArXiv (2025).
[[paper](https://ai.meta.com/research/publications/sam-audio-segment-anything-in-audio/)]
[[code](https://github.com/facebookresearch/sam-audio)]
[[project](https://ai.meta.com/samaudio/)]
[[demo](https://aidemos.meta.com/segment-anything/editor/segment-audio)]
[2025.12]

- **GPT-4V:** OpenAI.<br />
  "GPT-4V(ision) System Card." ArXiv (2023).
  [[paper](https://cdn.openai.com/papers/GPTV_System_Card.pdf)] 
  [[homepage](https://openai.com/research/gpt-4v-system-card)]
  [2023.09]

- **Gemini:** Gemini Team, Google.<br />
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

- **SAMTok:** Yikang Zhou, Tao Zhang, Dengxian Gong, Yuanzheng Wu, Ye Tian, Haochen Wang, Haobo Yuan, Jiacong Wang, Lu Qi, Hao Fei, Anran Wang, Zhuochen Wang, Yujing Wang, Cheng Chen, Shunping Ji, Xiangtai Li.<br />
"SAMTok: Representing Any Mask with Two Words." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.16093)]
[[code](https://github.com/bytedance/Sa2VA/tree/main/projects/samtok)]
[[project](https://zhouyiks.github.io/projects/SAMTok/)]
[[hugging face](https://huggingface.co/collections/zhouyik/samtok)]
[[demo](https://huggingface.co/spaces/insomnia7/SAMTok)]
[2026.01]

- **DAM:** Long Lian, Yifan Ding, Yunhao Ge, Sifei Liu, Hanzi Mao, Boyi Li, Marco Pavone, Ming-Yu Liu, Trevor Darrell, Adam Yala, Yin Cui.<br />
"Describe Anything: Detailed Localized Image and Video Captioning." ArXiv (2025).
[[paper](https://arxiv.org/abs/2504.16072)]
[[code](https://github.com/NVlabs/describe-anything)]
[[project](https://describe-anything.github.io/)]
[[huggingface](https://huggingface.co/collections/nvidia/describe-anything-680825bb8f5e41ff0785834c)]
[2025.04]

- **DINOv2:** Maxime Oquab, Timothée Darcet, Théo Moutakanni, Huy Vo, Marc Szafraniec, Vasil Khalidov, Pierre Fernandez, Daniel Haziza, Francisco Massa, Alaaeldin El-Nouby, Mahmoud Assran, Nicolas Ballas, Wojciech Galuba, Russell Howes, Po-Yao Huang, Shang-Wen Li, Ishan Misra, Michael Rabbat, Vasu Sharma, Gabriel Synnaeve, Hu Xu, Hervé Jegou, Julien Mairal, Patrick Labatut, Armand Joulin, Piotr Bojanowski.<br />
"DINOv2: Learning Robust Visual Features without Supervision." TMLR (2024).
[[paper](https://arxiv.org/abs/2304.07193)]
[[code](https://github.com/facebookresearch/dinov2)]
[[project](https://dinov2.metademolab.com/)]
[2023.04]

- **DINOv3:** Oriane Siméoni, Huy V. Vo, Maximilian Seitzer, Federico Baldassarre, Maxime Oquab, Cijo Jose, Vasil Khalidov, Marc Szafraniec, Seungeun Yi, Michaël Ramamonjisoa, Francisco Massa, Daniel Haziza, Luca Wehrstedt, Jianyuan Wang, Timothée Darcet, Théo Moutakanni, Leonel Sentana, Claire Roberts, Andrea Vedaldi, Jamie Tolan, John Brandt, Camille Couprie, Julien Mairal, Hervé Jégou, Patrick Labatut, Piotr Bojanowski.<br />
"DINOv3." ArXiv (2025).
[[paper](https://arxiv.org/abs/2508.10104)]
[[code](https://github.com/facebookresearch/dinov3)]
[2025.08]

- **Rex-Omni:** Qing Jiang, Junan Huo, Xingyu Chen, Yuda Xiong, Zhaoyang Zeng, Yihao Chen, Tianhe Ren, Junzhi Yu, Lei Zhang.<br />
"Detect Anything via Next Point Prediction." ArXiv (2025).
[[paper](https://arxiv.org/abs/2510.12798)]
[[project](http://rex-omni.github.io/)]
[[code](https://github.com/IDEA-Research/Rex-Omni)]
[2025.10]

- **Mamba-3:** Anonymous authors.<br />
"Mamba-3: Improved Sequence Modeling using State Space Principles." ICLR (2026).
[[paper](https://openreview.net/forum?id=HwCvaJOiCj)]
[2025.11]

- **Depth Anything 3:** Haotong Lin, Sili Chen, Junhao Liew, Donny Y. Chen, Zhenyu Li, Guang Shi, Jiashi Feng, Bingyi Kang.<br />
"Depth Anything 3: Recovering the Visual Space from Any Views." ICLR (2026).
[[paper](https://arxiv.org/abs/2511.10647)]
[[code](https://depth-anything-3.github.io/)]
[2025.11]

- **Vision Banana:** Valentin Gabeur, Shangbang Long, Songyou Peng, Paul Voigtlaender, Shuyang Sun, Yanan Bao, Karen Truong, Zhicheng Wang, Wenlei Zhou, Jonathan T. Barron, Kyle Genova, Nithish Kannen, Sherry Ben, Yandong Li, Mandy Guo, Suhas Yogin, Yiming Gu, Huizhong Chen, Oliver Wang, Saining Xie, Howard Zhou, Kaiming He, Thomas Funkhouser, Jean-Baptiste Alayrac, Radu Soricut.<br />
"Image Generators are Generalist Vision Learners." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.20329)]
[[code](http://vision-banana.github.io)]
[2026.04]

### Follow-up Papers
#### The latest papers within a week are marked with a :boom:
#### 2026
:boom:**T2S:** Kumju Jo, Heesun Jung, Sungyong Baik.<br />
"Text-to-seed generation: Training-free open-vocabulary seeded semantic segmentation via re-purposing diffusion as text-guided seed generator." KBS (2026).
[[paper](https://arxiv.org/abs/2608.26624)]
[2026.08]

:boom:**FAN-LoRA:** Ziquan Liu, Zhewei Zhu, Xuyang Shi.<br />
"FAN-LoRA: A Fourier-Adaptive Nonlinear Low-Rank Adaptor for Medical Foundation Model Domain Adaptation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.26531)]
[2026.08]

:boom:**LiDAR-SAM2:** Jihun Kim, Hyun-Kurl Jang, Hyemin Yang, Jinnyeong Yang, Hyeokjun Kweon, Kuk-Jin Yoon.<br />
"Bootstrapping a 4D LiDAR Annotation Tool from Video Foundation Models." ECCV Workshop(2026).
[[paper](https://arxiv.org/abs/2608.25418)]
[2026.08]

:boom:**HPMA:** Xinning Yao, Jingjing Wang, Jinghua Yue, Xiaoyan Luo, Fugen Zhou, Bo Liu.<br />
"Hierarchical Prototype-Memory Adaptation of SAM for Surgical Instrument Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.24541)]
[2026.08]

:boom:**ReGround-Surg:** Jiaxin Wen, Ming Yin, Lu Liu, Zeyu Fu.<br />
"ReGround-Surg: Reliability-Guided Anchor Grounding for Referring Surgical Video Segmentation." PRCV (2026).
[[paper](https://arxiv.org/abs/2608.24671)]
[[code](https://github.com/JiaxinWen1/ReGround-Surg)]
[2026.08]

:boom:**OptiSight:** Alperen Avan, Jordi Sanchez-Riera.<br />
"OptiSight: Bridging Semantic Reasoning and Geometric Control for Embodied Navigation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.23354)]
[[code](https://github.com/avanalperen/OptiSight-Python-Multimodal-CoT-for-Visual-Reasoning)]
[2026.08]
 
:boom:Liangtao Shi, Jinxia Xie, Xiantao Hu, Ting Liu.<br />
"MLLM-Assisted Audio VOS: A 3rd Place Report for the MeViS-Audio Track, 8th LSVOS Challenge." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.23234)]
[2026.08]

:boom:**SAM3Dual:** JeongRae Kim, Chaehyun Kim, Changwon Lim.<br />
"SAM3Dual: A 3rd Place Solution to the MOSEv2 Track, 8th LSVOS Challenge." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.22193)]
[2026.08]

:boom:Mingqi Gao, Sijie Li, Jungong Han.<br />
"Competitive Memory Readout for Robust Video Object Segmentation: 2nd Place Technical Report for the MOSEv2 Track of the 8th LSVOS Challenge." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.22064)]
[2026.08]
 
:boom:**RAVP:** Salvatore Calcagno, Marco Finocchiaro, Giovanni Bellitto, Daniela Giordano, Concetto Spampinato, Federica Proietto Salanitri.<br />
"Retrieval-Augmented Visual Prompting: Guiding Foundation Models in Two-Photon Imaging." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.21970)]
[2026.08]

:boom:**SPARK-SAM:** Aji Mao, Zhenming Peng, Bailin Mu, Tian Pu.<br />
"SPARK-SAM: Self-Prompt Adaptation with Response Knowledge for SAM in Infrared Small Target Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.20754)]
[[code](https://github.com/Sakauma/SPARK-SAM)]
[2026.08]
 
:boom:**GAP-SAM:** Haozhen Yan, Siyuan Shan, Zijian Yu, Youqi Wang, Yan Hong, Jun Lan, Jianfu Zhang.<br />
"GAP-SAM: A Global Artifact Prior for Generalizable AI-Generated Image Manipulation Localization." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.20929)]
[2026.08]

:boom:Manani, Hiren.<br />
"From Detection to Segmentation: A Foundation Model Approach to Organoid Brightfield Image Analysis Using SAM 3." ArXiv (2026).
[[paper](https://www.proquest.com/openview/bc6be627378a7492620e94471f278918/1?pq-origsite=gscholar&cbl=18750&diss=y)]
[2026.08]

:boom:**DPD-SAM:** Ma, Yize and Liang, Zhenyang and Yin, Feiyu and Song, Pengfei and Song, Junyi and Yang, Shengxiang and Wu, Guoqing and Ren, Yan and Yu, Jinhua.<br />
"Latent Domain-Specific Prompt-Driven SAM via Conditional Diffusion Refinement for Postoperative Glioma Segmentation." TII (2026).
[[paper](https://doi.org/10.1109/TII.2026.3716639)]
[2026.08]
 
:boom:Hilla Fred and Mogens Agerbo Krogh and Britt {Bang Jensen} and Laura Ruotsalainen and Jouni Vielma and Matti Pastell.<br />
"Automatic visual detection of fish in Recirculated Aquaculture Systems using the Segment Anything Model." Aquaculture (2026).
[[paper](https://doi.org/10.1016/j.aquaculture.2026.744459)]
[2026.08]

:boom:**SNFusion:** Yang Fang and Jingjing Chen and Dahang Wan and Xianli Lang and Shuangbao Shu and Rongsheng Lu and Qianqian Wu.<br />
"SNFusion: A SAMv2-guided boundary-aware fusion framework for visible-infrared maritime vessel detection." Ocean Engineering (2026).
[[paper](https://doi.org/10.1016/j.oceaneng.2026.127219)]
[[code](https://github.com/Young7Sun/SNFusion)]
[2026.08]

:boom:**ACRIS-SAM2:** Jiaxiang Luo, Weiwen Chen.<br />
"ACRIS-SAM2: Attribute-driven cross-modal interaction and dual semantic prompting for few-shot segmentation." Neurocomputing (2026).
[[paper](https://doi.org/10.1016/j.neucom.2026.134805)]
[2026.08]

:boom:**SAM2 R-CNN:** Mehdi Gharbage, Céline Teulière, Pierre Bouges & Thierry Chateau .<br />
"SAM2 R-CNN: Transferring SAM 2 Knowledge for Data Efficient Instance Segmentation." ICPR (2026).
[[paper](https://link.springer.com/chapter/10.1007/978-3-032-31920-3_27)]
[[code](https://github.com/comsee-research/sam2-rcnn)]
[2026.08]
 
:boom:Yang, Chenzheng, Shenhua Yang, Pu Wang, Weijun Wang, and Zeyang Huang.<br />
"Constrained Boundary Enhancement for SAM 2-Based Ship Segmentation in UAV Berthing and Unberthing Videos." Applied Sciences (2026).
[[paper](https://www.mdpi.com/2076-3417/16/15/7730)]
[2026.08]

:boom:Swapnil Biswas.<br />
"Enhancing Skin Lesion Classification in Teledermatology via SAM-Based Segmentation and Wavelet-Based Convolutional Autoencoder." ArXiv (2026).
[[paper](https://www.proquest.com/openview/a030812e3a877d8f96b50bebd9fc43bb/1?pq-origsite=gscholar&cbl=18750&diss=y)]
[2026.08]

:boom:**FlexiCrackNet:** Xiaoyan Jiang, et al.<br />
"FlexiCrackNet: A Flexible Pipeline for Lightweight Crack Segmentation with Distilled Features from SAM." ArXiv (2026).
[[paper](https://dx.doi.org/10.2139/ssrn.7291688)]
[[code](https://github.com/sky-visionX/FlexiCrackNet)]
[2026.08]
 
:boom:**EchoFlow-SAM:** Wanting Li, et al.<br />
"EchoFlow-SAM: Motion-guided semi-supervised segmentation for echocardiographic videos." Biomedical Signal Processing and Control (2026).
[[paper](https://doi.org/10.1016/j.bspc.2026.111256)]
[2026.08]

:boom:Geng, Chao, Yajie Wang, Quanming Li, Zhentao Li, Xianfeng Shi, Botao Fu, Wei Li, Cheng Chen, Hong Zhang, Yukai Wang, and et al.<br />
"Automated Detection and Segmentation of Cracks in Urban Underground Structures Based on YOLOv8-SAM2." Buildings (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S2643651526001019)]
[2026.08]

:boom:**SAM-CLIP-Thermal:** Yiyuan Lin and Chenjiao Tan and Changying Li and Yu Jiang.<br />
"SAM-CLIP-Thermal: Leveraging large multimodal models for reliable and scalable annotation in thermal image segmentation for field plant phenotyping." Plant Phenomics (2026).
[[paper](https://doi.org/10.1016/j.plaphe.2026.100264)]
[[code](https://cornell.box.com/s/dh69xf84464yrc1vlws92l1tflx7qa89)]
[2026.08]

:boom:**HBF-BCER:** Ping, Shengyang, Zhijie Lin, Liliang Lin, Lei Zhao, Lisha Ye, Bangguo Wang, and Tao Wang.<br />
"A Prompt-Preserving SAM ViT-B Adaptation Framework with Historical Branch Fusion and Soft Convolutional Expert Weighting for Medical Image Segmentation." Bioengineering (2026).
[[paper](https://www.mdpi.com/2306-5354/13/8/914)]
[2026.08]

:boom:Puspitasari, Fachrina Dewi and Zhang, Chaoning and Mandal, Avilasha and Zheng, Sheng and Qin, Caiyan and Kim, Tae-Ho and Lee, Jewon and Wang, Guoqing and Yang, Yang and Shen, Heng Tao.<br />
"Accelerating SAM2 with Efficient Memory Attention Module via Spatiotemporal Token Pruning." TPAMI (2026).
[[paper](https://doi.org/10.1109/TPAMI.2026.3723878)]
[2026.08]
 
:boom:**Token-Adaptive LoRA:** Xin Chen, Jun Yan, Zhiyu Yan, Jianwen Deng, Jiaqi Wu, Yonghong Gong, Xiaohua Jiang.<br />
"Token-Adaptive LoRA: Enhancing Segment Anything for Remote Sensing Imagery through Parameter-Efficient Fine- Tuning." ArXiv (2026).
[[paper](https://www.researchsquare.com/article/rs-10597532/v1)]
[2026.08]

:boom:**Zero-Click-SAM2:** Pasierb, Daniel and Wijata, Agata M. and Nalepa, Jakub.<br />
"Zero-Click Brain Tumor Segmentation Using Segment Anything Model 2." ICIP (2026).
[[paper](https://doi.org/10.1109/ICIP61757.2026.11630246)]
[[code](https://github.com/smile-research/Zero-Click-SAM2)]
[2026.08]

:boom:Bui-Tran, Quang-Khai and Nguyen, Thanh-Huy and Le, Bac and Xu, Min.<br />
"Adapting SAM Without Labels: Uncertainty-Aware Source-Free Medical Image Segmentation." ICIP (2026).
[[paper](https://doi.org/10.1109/ICIP61757.2026.11630514)]
[2026.08]
 
:boom:**SAM2TC:** Cocco, Marco and Dunnhofer, Matteo and Micheloni, Christian.<br />
"Representation Compensation of SAM2 for Segmenting Objects under Transformation in Videos." ICIP (2026).
[[paper](https://doi.org/10.1109/ICIP61757.2026.11630455)]
[2026.08]

:boom:**FE-SAM:** Gao, Feng and Pan, Zizhe and Wang, Haoting and Hua, Ruzhuang and Cao, Jingchao and Dong, Junyu and Du, Qian.<br />
"Frequency and Edge-Guided Segment Anything Model for Remote Sensing Image Semantic Segmentation." TGRS (2026).
[[paper](https://doi.org/10.1109/TGRS.2026.3724839)]
[[code](https://github.com/oucailab/FE-SAM)]
[2026.08]

:boom:Sachin Dudda Nagaraju, Bendik Skarre Abrahamsen, Ashkan Moradi, Mattijs Elschot.<br />
"A Few Cases Are All You Need: An Empirical Study of Annotation-Efficient LoRA Fine-Tuning of MedSAM3." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.18731)]
[2026.08]

- **SAM2Dual:** JeongRae Kim and Changwon Lim.<br />
"SAM2Dual: Training-Free, Dual Memory for Long-Term Video Object Segmentation." TIP (2026).
[[paper](https://arxiv.org/abs/2608.18640)]
[2026.08]
 
- **SAM2-DPT:** Steven Landgraf, Joceline Hinz, Markus Ulrich.<br />
"A Critical Synthesis of Uncertainty Quantification and Foundation Models for Semantic Segmentation." ISPRS (2026).
[[paper](https://arxiv.org/abs/2608.18709)]
[2026.08]

- **EpigraphNet:** Utsav Poudel, Rasik Bhattarai, Siddhartha Pathak, Raghavendra Ramacharna, Gaurav Jaswal.<br />
"Zero-Shot SAM2 Segmentation and Vision Transformer-Based Recognition of Elamite Cuneiform Symbols from Degraded Tablet Images." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.18544)]
[[code](https://github.com/r11up/sam-guided-vit)]
[2026.08]

- Ce Bian, Xusheng He, Jinrong Zhang, Canyang Wu, Xianjing Han, Jianlong Wu.<br />
"Key-Frame Reasoning with SAM3: Third Place Solution for the MeViS-Text Track of the 8th LSVOS Challenge." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.17279)]
[2026.08]

- Cesar Borja, Breck A. McCollum, Jarret E. Byrnes, Kenneth Sebens, Ana C. Murillo.<br />
"Leveraging existing sparse point annotations for benthic imagery dense segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.17561)]
[2026.08]
 
- **SSSAM:** Ruichao Hou, Boyue Xu, Tongwei Ren, Dongming Zhou, Gangshan Wu, Jinde Cao.<br />
"S3AM: A Single-Stream SAM with Reliability-Calibrated Frequency Adapter for Multi-modal Salient Object Detection." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.17475)]
[[code](https://github.com/xuboyue1999/SSSAM)]
[2026.08]

- **SAM-RNO:** Wang, F., Liu, Q. & Wu, G.<br />
"Road negative obstacle segmentation via a dual-branch segment anything model with RGB-depth cross-prompting." J Supercomput (2026).
[[paper](https://link.springer.com/article/10.1007/s11227-026-08745-6)]
[2026.08]

- **SAM-Med2D-GeoCrop:** Wang, Tianqi and Li, Jianuo and Yang, Chenhao and Xu, Jinyi and Zhou, Mian and Dang, Kang and Zhang, Linxue.<br />
"ROI-Focused Geometry-Aware Adaptation for Accurate Small-Structure Segmentation in Medical SAM." ICIP (2026).
[[paper](https://ieeexplore.ieee.org/abstract/document/11629916)]
[2026.08]

- **RISE:** Yanbo Jiang, Haotian Zheng, Jiahao Wang, Hanxiao Ren, Yitao Xu, Yining Xing, Zehong Ke, Hao Cheng, Yiqian Tu, Jinhao Li, Zhiyuan Xuan, Fang Zhang, Jianqiang Wang.<br />
"RISE: Roadside Infrastructure Sequence Understanding across 3D Tracking and Structured Vision-Language Reasoning." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.16480)]
[2026.08]
 
- **DreamX-Phi 1.0:** DreamX Team, Rui Chen, Xiangxiang Chu, Geng Li, Jifan Li, Qingfeng Shi, Datao Tang, Jing Tang, Jun Wang, Pengfei Zhang.<br />
"DreamX-Phi 1.0: Action-Conditioned Video World Model for Robotic Manipulation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.13489)]
[[code](https://github.com/AMAP-ML/DreamX-Phi)]
[2026.08]

- **VOS-Agent:** Canyang Wu, Jinrong Zhang, Xusheng He, Ce Bian, Xianjing Han, Jianlong Wu.<br />
"VOS-Agent: The 1st Place Solution for the 8th LSVOS Challenge (MOSEv2 Track)." ECCV Workshop(2026).
[[paper](https://arxiv.org/abs/2608.12721)]
[2026.08]

- **TCSR-Monito:** Hieu D. Pham, Dang P. M. Cao, Thanh Trung Huynh.<br />
"Beyond Uncertainty: Generalizable Failure Monitoring for Surgical Segmentation under Acquisition Degradation." MICCAI Workshop(2026).
[[paper](https://arxiv.org/abs/2608.16748)]
[[code](https://github.com/dinhieufam/tcsr-monitor)]
[2026.08]

- **SUGFW+:** Xiaochuan Ma, Ning Zhu, Jia Fu, Lanfeng Zhong, Hanyu Jiang, Bin Song, Kang Li, Guotai Wang.<br />
"SUGFW+: An Uncertainty-guided Feature Weighting Framework for Cold Start Active Adaptation of SAM in Medical Image Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.16110)]
[[code](https://github.com/HiLab-git/SUGFW-plus)]
[2026.08]

- **FE-SAM:** Feng Gao, Zizhe Pan, Haoting Wang, Ruzhuang Hua, Jingchao Cao, Junyu Dong, Qian Du.<br />
"Frequency and Edge-Guided Segment Anything Model for Remote Sensing Image Semantic Segmentation." IEEE TGRS (2026).
[[paper](https://arxiv.org/abs/2608.15054)]
[[code](https://github.com/oucailab/FE-SAM)]
[2026.08]

- Mohammadreza Narimani, Shreyan Mitra, Parastoo Farajpoor.<br />
"From crown candidates to neighborhood screening: integrating optical GeoAI and spatial modeling for urban-canopy assessment in Davis, California." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.13856)]
[[code](https://github.com/MohammadrezaNarimaniUCDavis/Davis_Urban_Canopy_GeoAI)]
[[dataset](https://doi.org/10.5281/zenodo.21925527)]
[2026.08]

- Yiwen Ren, Jianing Liu, Yingxin Wang, Kexin Zhang, Licheng Jiao, Lingling Li, Xu Liu.<br />
"Agreement-Based Audio-Visual Segmentation:Champion Report for the MeViS-Audio Track in the 8th LSVOS Challenge." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.09475)]
[2026.08]

- **RoboSeg:** Zhaochen Lan, Mengxiang Lin.<br />
"RoboSeg: Online Part-Level Semantic Reconstruction for Robotic Manipulation via a Single Eye-in-Hand Camera." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.09778)]
[2026.08]

- Roni Blushtein-Livnon, Tal Svoray, Osher Rafaeli, Michael Dorman, Itay Fischhendler, Havazelet Yahel, Emir Galilee.<br />
"Evaluating Semantic and Spatial Guidance for Foundation Model Segmentation of Small-Scale PV in Remote Sensing Imagery." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.10801)]
[2026.08]
 
- **Seed2GS:** Zongjian Ding, Yudong Gao, Jiale Liu, Xinglin Yu, Junxing Ren, Dong Wei, Yajing Chen, Shan Huang, Mingjun Cheng, Min Li.<br />
"Seed2GS: Camera-Free, Training-Free Object Extraction from 3D Gaussian Scenes via a Single Reference-View Grounding." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.11928)]
[2026.08]

- Mike Szklarzewski, CJ George, Gavin Smithson, Christopher Stokes, Dakota Fulp, William M. Jones, Benjamin Wynn, Alexander Ur, Agit Yesiloz, Clint Kallenbach, Mark Swartz, Nathan DeBardeleben, Sharmistha Chakrabarti.<br />
"From Benchmark Performance to Tool Deployment: Human-in-the-Loop Anomaly Detection." ICMLA (2026).
[[paper](https://arxiv.org/abs/2608.07770)]
[2026.08]

- **BAP-MOS:** Satvik Praveen, Shengji Jin, Ahmed Lamidi, Xin Qian, Yi Sheng.<br />
"BAP-MOS: Bandit-Based Adaptive Prompting for Boundary-Sensitive Multi-Organ Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.08191)]
[[code](https://github.com/SatvikPraveen/BAP-MOS)]
[2026.08]
 
- Shah Imran Ahsan Chowdhury, Kazi Jihadur Rashid, Rajsree Das Tuli, Rahul Saha, Bulbul Ahammad.<br />
"GeoAI-based post-segmentation quality validation of building footprints via spatial feature engineering." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.09048)]
[2026.08]

- **LEGO:** Yuning Peng, Haiping Wang, Yuan Liu, Yipeng Lu, Zhen Dong, Bisheng Yang.<br />
"LEGO: Leveled Language Gaussian Splatting." ECCV (2026).
[[paper](https://arxiv.org/abs/2608.11458)]
[[code](https://pz0826.github.io/LEGO-Webpage/)]
[2026.08]

- **SSUPER:** Jungyoon Lee, Gyuil Lim, Doeon Kim, Seong-heum Kim.<br />
"Multi-Agent Target-Existence Verification and Learned Mask Geometry Refinement: Winning Report of the MeViS-Text Track at the 8th LSVOS Challenge 2026." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.11458)]
[2026.08]
 
- Duy Tran Thanh, Yeejin Lee, Byeongkeun Kang.<br />
"Learning from Multimodal Pseudo-Labels for Robust Open-Vocabulary Instance and Panoptic Segmentation." Neurocomputing (2026).
[[paper](https://arxiv.org/abs/2608.11681)]
[2026.08]

- AmirHossein Eshghi, Hamid Saadatfar, Seyyed Ali Hoseini, AmirMohsen Eshghi, Siavash Arjomand Bigdel.<br />
"Class Activation Mapping in Explainable Computer Vision: A Method-Centered Review of CNN, Transformer, and Foundation-Model-Era Visual Explanations." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.12299)]
[2026.08]

- **VOLA:** Yuchen Zhang, Yuan Gao, Sebastian Schmidt, Johannes Betz.<br />
"VOLA: Improving Open-World Driving by VLM-Based Semantic Attribute Prediction." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.11777)]
[[code](https://anonymous.4open.science/r/VOLA)]
[2026.08]
 
- **SAM3tool:** Nakul Poudel, Richard Simon, Cristian A. Linte.<br />
"Toward Mask Annotation-Free Surgical Instrument Segmentation from Endoscopic Images Using Text-Prompted Segment Anything Model 3 (SAM3)." MIUA (2026).
[[paper](https://arxiv.org/abs/2608.08844)]
[2026.08]

- **KD-SAM:** Yang Fang and Bingbing Jiang and Haopeng Huo and Uswah Khairuddin and Yeon Lee and Yong Qin.<br />
"KD-SAM: Keep-Awake and Detail-Enhanced Segment Anything Model for Multi-Modality Multi-Organ Medical Image Segmentation." Expert Systems with Applications (2026).
[[paper](https://doi.org/10.1016/j.eswa.2026.133883)]
[[code](https://github.com/ShowUNow/KD-SAM)]
[2026.08]

- **S3-Diff:** Jiaming Liang, QiHui Han, Guangye Ou, Jiawen Liu, Haolin Chen, Xi Zhong, Jiazhou Chen, Xiaoqi Sheng, Hongmin Cai.<br />
"S3-Diff: Structural Semantic Synergy Diffusion Model for High Fidelity Super Resolution of Pathological Images." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.03540)]
[2026.08]

- **GeoDistill-Refine:** Yonglong Zhang, Zongwu Xie, Yang Liu.<br />
"GeoDistill-Refine: Silhouette-First Geometry Distillation for Annotation-Free Spacecraft Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.07405)]
[2026.08]

- Hao Wang, Yuxuan Zhang, Wei Yang.<br />
"Universal Concept Disruption for SAM3 Image Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.05983)]
[2026.08]

- **EgoAfford:** Xinyuan Guan, Feifan Chen, Xinyu Zhan, Fu-Cheng Zhang, Cewu Lu, Lixin Yang.<br />
"EgoAfford: Task-Oriented Affordance Grounding via Egocentric Referring Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.04533)]
[[code](https://egoafford.github.io)]
[2026.08]

- Jonathan Klingspon, Scott McAvoy, Maurizio Seracini, Falko Kuester.<br />
"Material-Segmented Per-Pixel Emissivity Correction for Thermographic Anomaly Detection in Cultural Heritage Digital Twins." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.02964)]
[2026.08]
 
- **CROSS:** Tingzhang Luo, Ruizhong Liu, Yichao Liu, Cheng Fan, Yu Liu, Jianyuan Guo.<br />
"CROSS: Cascaded Distillation and Dual-Constraint Grounding for Remote Sensing Referring Segmentation." ECCV (2026).
[[paper](https://arxiv.org/abs/2608.03147)]
[[code](https://clarence-cv.github.io/CROSS/)]
[2026.08]

- **FS-CPL:** Rahul Venkataramani, Rachana Sathish.<br />
"Few-Shot Concept Prompt Learning for Segmentation Foundation Models via Visual Grounding." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.01663)]
[2026.08]

- **ACTrack:** Wenrui Cai, Yuzhe Li, Qingjie Liu, Yunhong Wang.<br />
"Models as Tools: An Agentic Coordination Framework for Unified Multimodal Visual Tracking." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.00847)]
[2026.08]

- **GaussianSelector:** Baihan Yang, Tiexin Li, Yuheng Liu, Xin Lin, Xinke Li, Xiaohui Xie, Truong Nguyen.<br />
"GaussianSelector: Lightweight Human-Guided Object Selection in 3D Gaussian Splatting with Graph Optimization." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.01492)]
[2026.08]

- **EOVSAM:** Haomin Peng, Yongkang Li, Zhaoxiang Liu, Xiaojie Jin, Shiguo Lian, Yunchao Wei, Xinggang Wang.<br />
"EOVSAM: Efficient Open-Vocabulary Segmentation with SAM 3 in One Pass." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.02284)]
[[code](https://github.com/hustvl/EOVSAM)]
[2026.08]

- **PhenoStitch:** Xuechen Li.<br />
"PhenoStitch: Training-Free Panoptic Crop Mapping from Satellite Image Time Series." ArXiv (2026).
[[paper](https://arxiv.org/abs/2608.00870)]
[2026.08]

- **ELFSS-AR:** Xueting Bai, Huan Ni.<br />
"Training-Free Entity-Level Few-Shot Segmentation of Remote Sensing Images with Advection Refinement." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.29278)]
[[code](https://github.com/yu-ni1989/ELFSS-AR)]
[2026.08]

- **UltraSAM3:** Bo Xu, Quanhao Zhu, Rui Lin, Boling Zhu, Chenyuan Wang, Hongfei Lin, Feng Xia, Chenhua Ji.<br />
"UltraSAM3: A Concept-Driven Foundation Model for Universal Ultrasound Image Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.29200)]
[[code](https://github.com/zhuqh19/UltraSAM3)]
[2026.08]

- **SAM+D:** Yu Song, Hao Sun, Shiyu Teng, Ikuko Nishikawa, Yen-wei Chen.<br />
"SAM+D: Parameter-Efficient Dimensional Lifting of SAM-Family Models via Depth-Routed LoRA and Depth Shifting." ECCV (2026).
[[paper](https://arxiv.org/abs/2607.29033)]
[[code](https://github.com/JerrySongCST/SAM-Plus-D)]
[2026.08]

- **TMMSAM2:** Fu, Xiyou and Zhang, Ting and Zhang, Xiaoyu and Lin, Mingying and Lv, Zijun and He, Wangquan and Ren, Qi and Xu, Meng and Jia, Sen.<br />
"TMMSAM2: Tracker-Aided Multitemporal Memory SAM2 for Hyperspectral Object Tracking." TNNLS (2026).
[[paper](https://ieeexplore.ieee.org/abstract/document/11597947)]
[2026.08]

- **SAM3D-VLA:** Zonghe Liu, et al.<br />
"SAM3D-Guided Object-Centric Representation Alignment for Vision-Language-Action Models." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.25912)]
[2026.07]

- Jinghong Liu, Yuchuan Deng, Fanping Liu, Meng Huang, Xirong Li.<br />
"Benchmarking Foundation and Large Language Models for Few-Shot Medical Image Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.27856)]
[2026.07]

- **ZMIS-SAM:** Dekun Yuan, Zhongwei Li, Zheng Qiao, Jie Zhang.<br />
"ZMIS-SAM: Segment Anything Model Enhanced with Wavelet Transform for Zooplankton Microscopy Image Instance Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.27585)]
[[code](https://github.com/sdydk/ZMIS-SAM)]
[2026.07]

- Nevio Dubbini, Lisa Yeomans, Marco Pavia, Ramazan Parmaksiz, Ayse Atas Hooglugt, Gabriele Gattiglia, Beatrice Demarchi.<br />
"Multimodal fusion of visual and morphometric features for avian bone classification." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.26743)]
[2026.07]

- **RDVSv2:** Tianyu Li, Jiahao He, Keren Fu, Qijun Zhao.<br />
"RDVSv2: A Large-scale Benchmark for RGB-D Video Salient Object Detection." ACMMM (2026).
[[paper](https://arxiv.org/abs/2607.25392)]
[[code](https://github.com/ltynick/RDVSv2)]
[2026.07]

- Sanjay Subramanian, Junwei Yu, Zirui Wang, Rohil Malpani, Maggie Chung, Adam Yala, Dan Klein, Trevor Darrell.<br />
"Open-Ended CT Volume Segmentation with Weak Supervision from Language." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.25860)]
[2026.07]

- **SADe:** Hang Xing, Guangjun Liu, Yan Xia, Xueming Ding.<br />
"SADe: Sparse-Atom Support Decontamination for Few-Shot Segmentation with Weak Support Annotations." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.24706)]
[2026.07]

- **ConFusion:** Guo Yurong, He Yufei, Li Yonghao, Chang Dongliang, Zhang Ke, Ma Zhanyu.<br />
"ConFusion: Continuous Fusion Space Learning for Fine-Grained Controllable Infrared and Visible Image Fusion." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.23600)]
[[code](https://github.com/HeyufeiAnto/Confusion)]
[2026.07]
 
- **EditCLEVR:** Anuraag Gadehothur Karnam, Tarunesh Sathish.<br />
"EditCLEVR: A Paired-Scene Intervention Benchmark for Compositional Faithfulness of Object-Centric Representations." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.22705)]
[[code](https://github.com/torux-bughunter/EditCLEVR)]
[2026.07]

- **SurgSAM3:** Changjing Liu, Yiming Huang, Beilei Cui, Liangjing Shao, Long Bai, Yanheng Li, Haoxuan Che, Hongliang Ren.<br />
"Parameter-Efficient Adaptation of SAM3 for Prompt-Driven Surgical Concept Segmentation." MICCAI Workshop (2026).
[[paper](https://arxiv.org/abs/2607.23694)]
[[code](https://github.com/ChangjingLiu/SurgSAM3)]
[2026.07]

- Hiu Ching Cheung, Wenchao Yue, Zhengran Han, Mingcong Chen, Guanglin Cao, Hongbin Liu, Hongliang Ren.<br />
"Learning-based Hierarchical Tracheal Anatomy Understanding from Sparse Surgical Demonstration Annotations for Ultrasound Robots." ICCBS (2026).
[[paper](https://arxiv.org/abs/2607.22789)]
[2026.07]

- **LSP-SAM2:** Zhaoyuan Wu, Naiyang Guan, Yinghui Gao, Longfei Su, Min Liu.<br />
"A Light-Weight Self-Prompting Foundation Model for Automatous Video Object Segmentation." ICIC (2026).
[[paper](https://dl.acm.org/doi/abs/10.1007/978-981-92-3510-0_29)]
[[code](https://github.com/jone-Wu/LSP-SAM2)]
[2026.07]
 
- **FESAM:** Chaoyue Wang, Jiang Wang, Lingfang Li, Weijian Hu & Lizhen Cui .<br />
"FESAM: Frequency-Enhanced SAM with Boundary-Aware Decoding for Ultrasound Image Segmentation." ICIC (2026).
[[paper](https://link.springer.com/chapter/10.1007/978-981-92-3538-4_4)]
[2026.07]

- **Agent-SAM-I2V:** Guo Yang, Jiaqi Zhang, Yao Zhu & Longze Fan.<br />
"Agent-SAM-I2V: Self-correcting Promptable Video Segmentation via Agentic Drift Detection and Multi-Prompt Fusion." ICIC (2026).
[[paper](https://link.springer.com/chapter/10.1007/978-981-92-3513-1_49)]
[2026.07]

- **GB-SAM:** Chenlin Xu, Lei Zhang, Lituan Wang, Xinyu Pu, Pengfei Ma, Guangwu Qian.<br />
"GB-SAM: Gaussian-Prior and Boundary-Guided Test-Time Adaptation for Medical Image Segmentation." ICIC (2026).
[[paper](https://dl.acm.org/doi/abs/10.1007/978-981-92-3501-8_23)]
[[code](https://github.com/Emilychenlin/GB-SAM/tree/main)]
[2026.07]
 
- **CME-SAM:** Qiyuan Wang, Jinfu Wang, Chuyu Chen, Pengtao Ren, Shijie Ling, Kejiang Xiao.<br />
"CME-SAM: Contrastive Mask-Enhanced Segment Anything Model for Generalizable Medical Image Segmentation." ICIC (2026).
[[paper](https://dl.acm.org/doi/abs/10.1007/978-981-92-3513-1_8)]
[2026.07]

- **IBS-EMA:** Yizhuo Wang, Shiquan Min, Jiangping Zhu & Pei Zhou.<br />
"IBS-EMA: Mitigating Test-Time Prompt Distribution Shift for Medical Segment Anything Models." ICIC (2026).
[[paper](https://link.springer.com/chapter/10.1007/978-981-92-3378-6_14)]
[2026.07]

- **HCFNet:** Yu, Jiwei, Kecheng Zhou, Ting Wang, Hongxiao Gan, Yu Wang, and Shuzhi Gao.<br />
"HCFNet: A SAM2-Based Hierarchical Cross-Branch Frequency-Aware Network for Industrial Surface Defect Segmentation." Sensors (2026).
[[paper](https://www.mdpi.com/1424-8220/26/14/4597)]
[2026.07]
 
- **ZA-SAM:** Jinliang Su, Yun Jiang, Zequn Zhang & Yuhang Li .<br />
"Adaptive Prompted, Zero-Annotation SAM: Weakly Supervised Binary Medical Image Segmentation." ICIC (2026).
[[paper](https://link.springer.com/chapter/10.1007/978-981-92-3378-6_12)]
[2026.07]

- **SURE-SAM2:** Yucan Duan, Chun Wang, Kaiyu Miao & Xiaoyan He.<br />
"SURE-SAM2: Semantic and Uncertainty-aware Refinement SAM2 for Change Detection." ICIC (2026).
[[paper](https://link.springer.com/chapter/10.1007/978-981-92-3378-6_21)]
[2026.07]

- **PolypSAM-Lite:** Hasan, Umar, and Muhammad Ali Nayeem.<br />
"Low-Rank Attention Reparameterization for Parameter-Efficient Adaptation of the Segment Anything Model to Colorectal Polyp Segmentation." Mathematics (2026).
[[paper](https://www.mdpi.com/2227-7390/14/14/2646)]
[2026.07]
 
- Koki AMANO, Otoha YAMANAKA, Wakana KAWAI, Tatsuya HAYASHI, Nobuo KOCHI, Ippeita DAN.<br />
"Segment-Anything-based AOI Analysis for Eye-tracking: A Gaze Judgment Method Considering the Visual Angle." J-STAGE(2026).
[[paper](https://www.jstage.jst.go.jp/article/ijae/advpub/0/advpub_IJAE-D-25-00049/_article/-char/ja/)]
[2026.07]

- **Naka-SAM:** Chen, Juan; Wu, Jiajie; Guo, Lei; Ge, Wenping; Ma, Jie.<br />
"Naka-SAM: A Cognition-Inspired Framework with Nakagami Prior for Ultrasound Segmentation." Proceedings of the Annual Meeting of the Cognitive Science Society (2026).
[[paper](https://escholarship.org/uc/item/7hd8g739)]
[2026.07]

- **CG-SAM2:** Bin He, Zhiwei Chen, Shengmin Zhao, Qinqin Zhou, Aiwen Jiang, Miaohui Zhang.<br />
"CG-SAM2: Confidence-Guided Pseudo-label Refinement for Weakly Supervised Camouflaged Object Detection." ICIC (2026).
[[paper](https://dl.acm.org/doi/abs/10.1007/978-981-92-3507-0_2)]
[2026.07]

- Mohammadreza Narimani, Vikram Anand, Parastoo Farajpoor.<br />
"Farmland Extent and Visible Boundary Mapping from 1 m NAIP Imagery Using Residual U-Net and Text-Prompted SAM 3 Refinement." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.21881)]
[[code](https://github.com/MohammadrezaNarimaniUCDavis/NAIP_Farmland_ResSAM)]
[[dataset](https://doi.org/10.5281/zenodo.21519912)]
[2026.07]

- **FluxGraph:** Yihong Sun, Bharath Hariharan.<br />
"Efficient Tracking and Understanding Object Transformations." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.19743)]
[[code](https://github.com/YihongSun/FluxGraph)]
[2026.07]

- **SENSATION-DS:** Hakan Calim, Anamaria Dumitrescu, Adarsh Bhandary Panambur, Huzaifa Asif, Andreas Maier.<br />
"Safety-oriented sidewalk and road segmentation for smartphone-based assistive navigation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.21137)]
[2026.07]
 
- **Lean-SAM2:** Xudong Ouyang, Wenlun Zhang, Yimin Xu, Huazhong Liu, Yunshan Zhong.<br />
"Lean-SAM2: Target-Anchored Memory and Encoder Acceleration for SAM2." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.19811)]
[[code](https://github.com/DeawhaleQwQ/Lean-SAM2)]
[2026.07]

- Samy Mounir, Mikolaj Cieslak, Najmeddine Dhieb, Hakim Ghazzai, Jonathan Klein, Katja Froehlich, Soeren Pirk, Wojciech Palubicki, Gianluca Setti, Ahmed M. Eltawil, Dominik L. Michels.<br />
"Text-conditioned Segmentation for Tomato Phenotyping via Procedural Synthetic Data." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.18576)]
[2026.07]

- **Scene-SAM3D:** Yuqi Zhang, et al.<br />
"Scene-SAM3D: Multi-View Scene Asset Generation Without Fine-Tuning." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.16805)]
[[code](https://github.com/xibi777/Scene-SAM3D)]
[2026.07]

- **OP-HRG:** Kazi Sajeed Mehrab, Hani Alomari, Najibul Haque Sarker, Chia-Wei Tang, Zaber Ibn Abdul Hakim, Anuj Karpatne, Chris Thomas.<br />
"Reasoning-Guided Part-Level Visual Grounding via Reinforcement Learning." ECCV  (2026).
[[paper](https://arxiv.org/abs/2607.15374)]
[[code](https://github.com/sajeedmehrab/op-hrg)]
[2026.07]

- Silas kwabla Gah, Ebenezer Owusu.<br />
"Training-Free Open-Vocabulary 3D Point-Cloud Segmentation on the Generalized Few-Shot Benchmark." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.15331)]
[2026.07]

- Jinchang Zhang, Arnold Zumbrun, Jing Lin, and Guoyu Lu.<br />
"Foundation-Assisted Active Learning for Object Detection Annotation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.16671)]
[2026.07]

- **Lite-Pi:** Shivanshu Agnihotri, Snehashis Majhi, Deepak Ranjan Nayak, Dwarikanath Mahapatra, Debesh Jha.<br />
"Induce to Empower: Improving Lightweight Baselines via Foundation Model Induction for Generalized Polyp Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.17208)]
[[code](https://github.com/lostinrepo/Lite-Pi)]
[2026.07]

- Joey Páolo Kardolus, Daan Hendriks, Jaap Jansen.<br />
"Direct Clinical Joint Angle Extraction from Parametric Body Model Rotation Matrices." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.17639)]
[[code](https://github.com/Babon-Innovations-b-v/movalytics)]
[2026.07]

- Zhe Xin, Hanzhi Chang, Penghui Huang, Yinian Mao, Guoquan Huang.<br />
"Robust Multimodal Dynamic Object Segmentation." ICRA (2026).
[[paper](https://arxiv.org/abs/2607.18153)]
[2026.07]
 
- Minghui Xu, Chaoyi Zhou, Aaron P. Cecil, Xi Liu, Siyu Huang, Yuhao Xu.<br />
"Digital measurement of droplet flame diameter in microgravity combustion images using Segment Anything Model 2 with automatic prompt selection." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.16587)]
[2026.07]

- **SAMRI-3D:** Zhao Wang, Wei Dai, Hongfu Sun, Craig Engstrom, Shekhar S. Chandra.<br />
"SAMRI-3D: Adapting SAM2 for 3D MRI Segmentation with Global Volume Tokens." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.18014)]
[[code](https://github.com/wangzhaomxy/SAMRI-3D)]
[2026.07]

- **IMTrack:** Zhiqiang Hou, Chuangye Xu, Sugang Ma, Xiaobao Yang, Lei Pu.<br />
"Robust visual tracking via implicit memory-guided re-detection." EAAI (2026).
[[paper](https://doi.org/10.1016/j.engappai.2026.115596)]
[2026.07]

- **ReportMedSAM:** Anghong Du, Theodoros N. Arvanitis, Colin Watts, Alejandro F. Frangi, Le Zhang.<br />
"ReportMedSAM: Guiding Segmentation Through Radiology Reports." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.14116)]
[2026.07]

- **ViPSAM:** San Lee, Nalee Kim, Jeong Il Yu, Hee Chul Park, Boah Kim.<br />
"ViPSAM: Visual Prompting Medical Image Segmentation Using Segment Anything Model." MICCAI (2026).
[[paper](https://arxiv.org/abs/2607.14328)]
[2026.07]

- **XCT-SAM:** Md Mahedi Hasan, Md Mushfiqur Rahaman, Alan Pachkovskiy, Imtiaz Ahmed, Jeremy Dawson, Srinjoy Das.<br />
"XCT-SAM: Sequential Parameter-Efficient Domain Adaptation of SAM for Industrial XCT Defect Segmentation." ICPR workshop (2026).
[[paper](https://arxiv.org/abs/2607.14287)]
[[code](https://github.com/Mahedi-61/XCT-SAM.git)]
[2026.07]

- Yuanzhi He.<br />
"Detector Confidence Signals Presence Rather Than Occlusion in Cluttered Manipulation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.13361)]
[2026.07]

- **SARFA:** Tyler Ward, Abdullah Imran.<br />
"SARFA: Segment Anything with Radiomic Feature Alignment." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.13323)]
[[code](https://github.com/tbwa233/SARFA)]
[2026.07]
 
- **SAM-PAG:** Wenqi Si, Gongyang Li, Shixiang Shi, Weisi Lin.<br />
"Weakly-Supervised RGB-D Salient Object Detection via SAM-driven Pseudo Annotation and State Space Interaction-based Diffusion." IEEE TMM (2026).
[[paper](https://arxiv.org/abs/2607.15041)]
[[code](https://github.com/Switch457/WeakS2Diff_SOD)]
[2026.07]

- **SERD:** Shipeng Liu, Zhanping Song, Liang Zhao, Dengfeng Chen.<br />
"Semantic-Edge Response Decoding of SAM3 for Zero-Shot Crack Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.12292)]
[[code](https://github.com/xauat-liushipeng/SERD)]
[2026.07]

- **GFR-SAM:** Yilong Yang, Jianxin Tian, Shengchuan Zhang, Liujuan Cao.<br />
"GFR-SAM: Training-Free Referring Camouflaged Object Segmentation via Cross-Image Prompting." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.11732)]
[2026.07]
 
- **MobileSAM2:** Kai Jiang, Jiaxing Huang, Jingyi Zhang, Weiying Xie, Yunsong Li, Yufei Wang, Aoran Xiao, Dacheng Tao.<br />
"MobileSAM2: Lightweight Segment Anything for Spatial Intelligence." ECCV (2026).
[[paper](https://arxiv.org/abs/2607.12297)]
[2026.07]

- **REBASE:** Mantha Sai Gopal, Jaison Saji Chacko, Harsh Nandwana, Sandesh Hegde, Debarshi Banerjee, Uma Mahesh.<br />
"REBASE: Reference-Background Subspace Elimination for Training-Free In-Context Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.09082)]
[[code](https://github.com/ai-and-lab/rebase)]
[2026.07]

- **CtrlVTON:** Seungyong Lee, Hyun Jun Jang, Sangoh Kim, Sungjoon Park.<br />
"CtrlVTON: Controllable Virtual Try-On via Visual-Instance-Prompt Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.09362)]
[[code](https://github.com/nxnai/CtrlVTON)]
[2026.07]

- **SAMPLe:** Hossein Rajoli, Fatemeh Lotfi, Niloufar Alipour Talemi, Hossein Kashiani, Xiaolong Ma, Fatemeh Afghah.<br />
"SAMPLe: SAM-based Optimizer for Prompt Learning in VLMs." ECCV  (2026).
[[paper](https://arxiv.org/abs/2607.05727)]
[2026.07]

- Mohammad Dabaja, Turgay Celik.<br />
"Promptable Concept Segmentation from Above: Evaluating SAM 3's Zero-Shot and One-Shot Capabilities in Remote Sensing." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.09583)]
[2026.07]

- **SAM-MT:** Ruiqi Shen, Chang Liu, Henghui Ding.<br />
"SAM-MT: Real-Time Interactive Multi-Target Video Segmentation." ECCV (2026).
[[paper](https://arxiv.org/abs/2607.08688)]
[[code](https://henghuiding.com/SAM-MT/)]
[2026.07]

- **EP-SAM:** Wenhao Li, Fangyi Liu, Bo Du.<br />
"An Edge-aware Prompt-enhanced SAM for Ultrasound Image Segmentation." ICME (2026).
[[paper](https://arxiv.org/abs/2607.07240)]
[2026.07]
 
- **HPR-SAM:** Yingzhen Hu, Yiheng Zhong, Keying Zhu, Zimu Zhang, Zihan Ye, Sifan Song, Jionglong Su, Xiaofeng Liu.<br />
"HPR-SAM: Hierarchical Probabilistic Representation Learning for Prompt-free SAM-based Medical Image Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.06972)]
[[code](https://anonymous.4open.science/r/HPR-SAM-E4AF)]
[2026.07]

- **DA-SAM3:** Ying Chen, Jinyue Li, Kun Wang, Qiankun Li, Yang Liu.<br />
"Dual-Adaptive SAM3: Hierarchical Routing over Low-Rank Expert Layers for Parameter-Efficient Medical Image Segmentation." MICCAI (2026).
[[paper](https://arxiv.org/abs/2607.02571)]
[[code](https://github.com/Reconsider80/DA-SAM3)]
[2026.07]

- **RVAF:** Jin Yang, Ping Wei, Nanning Zheng.<br />
"Differential Amplifier-Inspired AmpAttention for Multi-View Robotic Manipulation." IROS (2026).
[[paper](https://arxiv.org/abs/2607.02845)]
[[code](https://anonymous.4open.science/w/RVAF-Anonymization)]
[2026.07]

- **GeoSAM-Lite:** Yongcong Wang, Jie Zhang, Rui Jiang, Xubing Yang, Ting Yun, Li Zhang.<br />
"GeoSAM-Lite: A Lightweight Foundation Model for Onboard Remote Sensing Segmentation." GRSL (2026).
[[paper](https://arxiv.org/abs/2607.03760)]
[2026.07]
 
- **GLLS:** Runzhi Deng, Yundi Hu, Yiming Zhong, Zhao Wang, Xixi Liu, Hongsong Wang, Caifeng Shan, Fang Zhao.<br />
"Global Logic and Local Search: Dual-Stream Multimodal In-Context Learning for Verifiable Industrial Anomaly Detection." ECCV (2026).
[[paper](https://arxiv.org/abs/2607.03817)]
[2026.07]

- **SharpSplat:** Porus Vaid, Shivam Chopra, Vaibhav Kumar.<br />
"SharpSplat: Edge-Regularized 3D Gaussian Splatting for High Fidelity Urban Building Reconstruction from UAV images." IGARSS(2026).
[[paper](https://arxiv.org/abs/2607.03872)]
[2026.07]

- **ChatImage:** Wencan Jiang, Jiangning Zhang, Yong Liu.<br />
"ChatImage: Navigating Long-Form LLM Answers through Interactive Images." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.05290)]
[[code](https://wencanjiang.github.io/ChatImage)]
[[project](https://wencanjiang.github.io/ChatImage/)]
[2026.07]
 
- **IPS-Seg:** Le-Anh Tran.<br />
"Exploring SAM Supervision for Fine-Grained UAV Target Segmentation under Data Scarcity." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.03754)]
[2026.07]

- Muhammad Aamir, Matthew Wijers, Sangyun Shin, Andrew Loveridge, Andrew Markham.<br />
"A non-invasive video-based method for individual identification of wildlife using gait dynamics." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.04518)]
[2026.07]

- **Improved Iris-SAM:** Maduabuchi Kingsley Okorie, et al.<br />
"Improved Iris-SAM -Based Iris Segmentation for Recognition in Biometric Security." EJASET (2026).
[[paper](https://ejaset.com/index.php/journal/article/view/523)]
[2026.07]

- **GPS:** Park, J., Jeong, J.<br />
"GPS: GlobalCLIP-PatchCore-SAM Based Zero-Shot Anomaly Detection and Localization in Smart Manufacturing." ICCSA (2026).
[[paper](https://link.springer.com/chapter/10.1007/978-3-032-30488-9_28)]
[2026.07]
 
- **SE-MTDNet:** Qing Geng and Kaiqi Ye and Fan Xu and Yu Meng and Miao Huang and Chunyan Yuan and Li Li and Bingbo Gao and Hu Zhou and Jianyu Yang and Ying Li and Jianxi Huang and Xiaochuang Yao.<br />
"A data- and knowledge-driven cropland parcel recognition method based on segment anything model (SAM)." International Journal of Applied Earth Observation and Geoinformation (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S1569843226003584)]
[2026.07]

- **SAM2-ICHNet:** Wanying Xie, Ronghui Ju, He Li, Wei Guo, Zhaoxuan Gong & Guodong Zhang.<br />
"SAM2-ICHNet: A detection-guided intracranial hemorrhage segmentation framework for tiny lesions and complex backgrounds." SIViP (2026).
[[paper](https://link.springer.com/article/10.1007/s11760-026-05517-w)]
[2026.07]

- **G2TAM:** Chenming Zhu, Peizhou Cao, Jingli Lin, Wenbo Hu, Yunlong Ran, Jiangmiao Pang, Tai Wang, Xihui Liu.<br />
"G2TAM: Geometry Grounded Track Anything Model." ICML (2026).
[[paper](https://openreview.net/forum?id=mkguKl16Ou)]
[2026.07]
 
- **HBF-BCER:** Shengyang Ping,Zhijie Lin  *,Liliang Lin,Lei Zhao,Lisha Ye,Bangguo Wang,Tao Wang.<br />
"A Prompt-Preserving MedSAM Enhancement Framework with Historical Feature Fusion and Soft Convolutional Expert Weighting for Medical Image Segmentation." ArXiv (2026).
[[paper](https://www.preprints.org/manuscript/202607.0078)]
[2026.07]

- **SAMURAI:** Carlos Perez, Neeru Gupta, Ipek Oruc.<br />
"SAMURAI: A Two-Stage Foundation Model Pipeline for Robust Optic Nerve Head Segmentation in Fundus Images." The 39th Canadian Conference on Artificial Intelligence (2026).
[[paper](https://raw.githubusercontent.com/mlresearch/v318/main/assets/perez26a/perez26a.pdf)]
[2026.07]

- **LongEgoRefer:** Shunya Kato, Taiki Miyanishi, Shuhei Kurita, Mahiro Ukai, Nakamasa Inoue, Chenhui Chu.<br />
"LongEgoRefer: A Benchmark for Long-Form Egocentric Video Referring Expression Comprehension." ECCV (2026).
[[paper](https://arxiv.org/abs/2607.02096)]
[[code](https://github.com/shunya-kato/LongEgoRefer)]
[2026.06]
 
- **MMIR-TCM:** Lihui Luo, Joongwon Chae, Ziyan Chen, Yang Liu, Siyi Cheng, Weihan Gao, Zelin Zeng, Xiaoming Yin, Samaneh Beheshti Kashi, Dongmei Yu, Lian Zhang, Jing Sui, Zeming Liang, Jiansong Ji, Peter E. Lobie, Peiwu Qin.<br />
"MMIR-TCM: Memory-Integrated Multimodal Inference and Retrieval for TCM Clinical Decision Support." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.01814)]
[[code](https://github.com/jw-chae/MMIR-TCM)]
[2026.06]

- **AdaCount:** Muhammad Ibraheem Siddiqui, Muhammad Haris Khan.<br />
"AdaCount: Training-Free Similarity-Guided Spatial and Feature Adaptation for Zero-Shot Object Counting." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.02139)]
[[code](https://muhammad-ibraheem-siddiqui.github.io/AdaCount/)]
[2026.06]

- **Object LeJEPA:** Jakob Geusen, Ender Konukoglu.<br />
"Object-centric LeJEPA." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.02404)]
[2026.06]

- Jian Song, Tian Zi, Shen Guanting.<br />
"From Technical Metrics to User Perception: A User Study of a Multimodal Human–Robot Interaction System for Object Detection and Grasping." ArXiv (2026).
[[paper](https://arxiv.org/abs/2607.00530)]
[2026.06]

- Chenyan Jing, Hao Ding, Lalithkumar Seenivasan, Jacob M. Delgado López, Mathias Unberath.<br />
"Dense Structural Priors for Sparse Functional Landmark Localization in Surgical Videos." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.31007)]
[2026.06]

- **BEE:** Zhiqiang Hou, et al.<br />
"Bridging the encoder gap: Stability-aware efficient adaptation of SAM2 for video object segmentation." ArXiv (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S0031320326012987)]
[2026.06]

- **EpiSAM:** Arnav Sharma, Pratyush Jena, Amal Joseph, Ravi Kiran Sarvadevabhatla.<br />
"EpiSAM: Character Segmentation in Challenging Stone Inscriptions." ICDAR (2026).
[[paper](https://arxiv.org/abs/2606.28859)]
[[code](https://ihdia.iiit.ac.in/episam/)]
[2026.06]

- **PGE-SAM:** Tuan-Duc Nguyen, Anh-Tuan Mai, Duc-Trong Le.<br />
"PGE-SAM: Prompt-Guided Feature Enhancement for Interactive Segmentation under Degradation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.30477)]
[2026.06]

- **ExACT:** Zixiao Zhang, Lingling Li, Pei He, Xu Liu, Licheng Jiao.<br />
"ExACT: Exemplar-Driven Calibrated Refinement for Training-Free Visual Grounding in Remote Sensing Images." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.28920)]
[2026.06]
 
- **SemDynReg:** Ruitao Chen, Mozhang Guo, Jinge Li.<br />
"SemDynReg: Semantics-Guided Deformation Regularization for Dynamic 3D Gaussian Splatting." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.28656)]
[[code](https://dyn-reg-3dgs.github.io/)]
[2026.06]

- Xin Dong, Wenfeng Deng, Yansong Tang.<br />
"Occlusion-Robust Multi-Object Decoupling for Physics-Based Interaction." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.29303)]
[2026.06]

- **SPARK:** Bryce Grant, Aryeh Rothenberg, Logan Senning, Zonghe Chua, Zach Patterson, Peng Wang.<br />
"Sequential Planning via Anchored Robotic Keypoints." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.30613)]
[[code](https://cwru-aism.github.io/spark-page/)]
[2026.06]

- **CG-ICS:** Zhigang Chen, Xiawu Zheng, Rongrong Ji.<br />
"Toward Robust In-Context Segmentation via Concept Guidance." ECCV (2026).
[[paper](https://arxiv.org/abs/2606.28149)]
[2026.06]

- Nicola Fanelli, Pasquale De Marinis, Raffaele Scaringi, Eva Cetinic, Gennaro Vessio, Giovanna Castellano.<br />
"Understanding How MLLMs Describe Artworks Using Token Activation Maps." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.27947)]
[[code](https://nicolafan.github.io/tamart/)]
[2026.06]

- **TEP-SAM:** Yinghui Xing, Donghao Chu, Shizhou Zhang, Di Xu.<br />
"Temporal-Emerged Prompting for Segment Anything in Multiframe Infrared Small Target Detection." ICML (2026).
[[paper](https://arxiv.org/abs/2606.27655)]
[[code](https://github.com/cdh8285/TEP-SAM)]
[2026.06]

- **Simple-ViLMedSAM:** Chengcan Qian, Dong Nie, Geng Chen, Daoqiang Zhang, Xuyun Wen.<br />
"Simple-ViLMedSAM: Simple Text Prompts Meet Vision-Language Models for Medical Image Segmentation." CVPR (2026).
[[paper](https://openaccess.thecvf.com/content/CVPR2026/html/Qian_Simple-ViLMedSAM_Simple_Text_Prompts_Meet_Vision-Language_Models_for_Medical_Image_CVPR_2026_paper.html)]
[[code](https://github.com/qcc001/Simple-ViLMedSAM)]
[2026.06]

- **ScribSAM:** Long Chen, et al.<br />
"ScribSAM: A robust scribble-supervised framework for spatiotemporal segmentation of breast lesions in ultrasound videos." Computerized Medical Imaging and Graphics (2026).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S0895611126000935)]
[[code](https://github.com/003-GH/ScribSAM)]
[2026.06]
 
- **Stat-SAM:** Juan Chen, et al.<br />
"Stat-SAM: Learning Global Echo-Intensity Priors as Prompts for SAM in Ultrasound Image Segmentation." ICMR (2026).
[[paper](https://doi.org/10.1145/3805622.3810649)]
[2026.06]

- Lv, X. et al.<br />
"Lightweight Shape-Aware Segment Anything for Cardiac Ultrasound Segmentation." SMC-IOT (2026).
[[paper](https://link.springer.com/chapter/10.1007/978-981-95-8232-7_57)]
[2026.06]

- **Lighted-SAM:** Yuhan Jia, Lixin Duan, Wen Li, and Fengmao Lv.<br />
"Lighted-SAM: Lightening Open-World SAM for Low-Light Segmentation." TIP (2026).
[[paper](https://ieeexplore.ieee.org/abstract/document/11568962)]
[[code](https://github.com/Jaaaahan/LightedSAM)]
[2026.06]
 
- **NeuroSeg-MF:** Zhehao Xu, Weiyi Liu, Shanshan Liang, Hongbo Jia, Xiaowei Chen, Han Qin, and Xiang Liao.<br />
"NeuroSeg-MF: robust neuron segmentation in two-photon Ca2+ imaging using multi-feature fusion and detection-guided SAM." Biomed. Opt. Express (2026).
[[paper](https://opg.optica.org/boe/fulltext.cfm?uri=boe-17-7-3727)]
[2026.06]

- **CPPS-SAM:** Zerong Zhang, Lianghua He.<br />
"SAM foundation model and expert model cross prompting framework for semi-supervised medical image segmentation." Journal of Visual Communication and Image Representation (2026).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S1047320326001719)]
[[code](https://github.com/zzzz-r/CPPS-SAM)]
[2026.06]

- Elakiya Sivakumar.<br />
"Fine-Tuning SAM2 for Coronary Artery Segmentation in X-Ray Fluoroscopy." ArXiv (2026).
[[paper](https://www.medrxiv.org/content/10.64898/2026.06.16.26355803v1)]
[2026.06]
 
- Tian, J., Cai, W., Sun, Z. et al.<br />
"Unsupervised Change Detection in Remote Sensing Images Using an Integrated SAM and MAD Method." J Indian Soc Remote Sens (2026).
[[paper](https://link.springer.com/article/10.1007/s12524-026-02473-3)]
[2026.06]

- Hizukuri, A.<br />
"Computerized Classification Method for Glioma Molecular Subtypes on Brain MR Images Using SAM-Med3D with Low-Rank Adaptation." J Digit Imaging. Inform. med.(2026).
[[paper](https://link.springer.com/article/10.1007/s10278-026-02074-z)]
[2026.06]

- **M2C:** Quan Zhou, Shaoqing Zhai, Qiang Hu Jia Chen, Qiang Li, Zhiwei Wang.<br />
"Mask to Concept: Auto-Promptable SAM3 via Efficient Test-Time Concept Embedding Search for Few-Shot Annotation." MICCAI (2026).
[[paper](https://arxiv.org/abs/2606.26711)]
[[code](https://github.com/Huster-Hq/M2C)]
[2026.06]
 
- **SAM2Matting:** Ruiqi Shen, Guangquan Jie, Chang Liu, Henghui Ding.<br />
"SAM2Matting: Generalized Image and Video Matting." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.27339)]
[[code](https://github.com/FudanCVL/SAM2Matting)]
[[website](https://henghuiding.com/SAM2Matting)]
[2026.06]

- **SENTRY:** Mohamad Alansari, Yonathan Michael, Hasan AlMarzouqi, Muzammal Naseer, Naoufel Werghi, Sajid Javed.<br />
"SENTRY: SAM2-Enhanced Neighbor-Aware and Temporally Reasoned Memory for Visual Tracking." ECCV (2026).
[[paper](https://arxiv.org/abs/2606.24449)]
[[code](https://hamadya.github.io/SENTRY/page/)]
[2026.06]

- **MorVess:** Fuyou Mao, Yifei Chen, Beining Wu, Lixin Lin, Jinnan Dai, Zhiling Li, Yilei Chen, Yaqi Wang, Hao Zhang, Yan Tang, Huiyu Zhou, Feiwei Qin.<br />
"MorVess: Morphology-Aware Pulmonary Vessel Segmentation Network." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.24214)]
[[code](https://github.com/MaoFuyou/MorVess)]
[2026.06]
 
- Marvin Rüdt, Hao Pang, Constantin Enke, Zäzilia Seibold, Kai Furmans.<br />
"Vision-Language Model Reasoning for Contextual Semantic Mapping in Intralogistics." IEEE ETFA (2026).
[[paper](https://arxiv.org/abs/2606.24814)]
[2026.06]

- **FEENet:** Yang, Zhiyuan and Xu, Jindong and Ni, Mengying and Su, Menghui and Peng, Jiantao.<br />
"A Fuzzy-Embedded Edge Enhancement Network via Segment Anything Model for VHR Remote Sensing Images Change Detection." TGRS (2026).
[[paper](https://ieeexplore.ieee.org/document/11318031)]
[2026.06]

- **DR-MV3D:** Jiho Choi, Seonho Lee, Seojeong Park, Hyunjung Shim.<br />
"Dense Reward for Multi-View 3D Reasoning with Global Maps and Local Views." ECCV (2026).
[[paper](https://arxiv.org/abs/2606.23557)]
[[code](https://github.com/kaist-cvml/dr-mv3d)]
[2026.06]
 
- **ARTEMIS:** Tong Wang, Siwen Wang, Yaolei Qi, Jinxing Zhou, Yuting He, Guanyu Yang, Yutong Xie.<br />
"ARTEMIS: Agent-guided Reliability-aware Temporal Mask Evolution for Imperfectly Supervised Video Polyp Segmentation." IEEE TIP (2026).
[[paper](https://arxiv.org/abs/2606.20161)]
[[code](https://github.com/wangtong627/ARTEMIS)]
[2026.06]

- **VTOS:** Jinchao Ge, Lingqiao Liu, Shuwen Zhao, Lei Wang.<br />
"VTOS: Learning to Orchestrate Vision Tools by Co-Searching Solutions and Observers." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.20728)]
[2026.06]

- **SSL.Prop.:** Tatsuya Suzuki, Kazuya Ijuin, Hideki Tomimori, Megumi Chikano, Katsushi Sakai.<br />
"Sparse Point-Guided Fusion of Supervised and Self-Supervised Learning Model for Seaweed Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.21026)]
[2026.06]
 
- **ProC-SAM3:** Yanghui Song, Nanqing Liu, Haonan Yin, Yingjie Gao, Chengfu Yang, Qi Ming.<br />
"Prompt-Calibrated SAM 3 for Open-Vocabulary Remote Sensing Semantic Segmentation." GRSL (2026).
[[paper](https://arxiv.org/abs/2606.21863)]
[[code](https://github.com/YanghuiSong/ProC-SAM3)]
[2026.06]

- **&mu;Match:** Marei Freitag, Olesia Korchevaia, Luca Freckmann, Anwai Archit, Constantin Pape.<br />
"Match: Foundation Models for Semi-supervised Learning and Domain Adaptation in EM." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.21605)]
[2026.06]

- **CM-TTA:** Yubo Zhou, Jianghao Wu, Ping Ye, Shaoting Zhang, Guotai Wang.<br />
"Concept Alignment Contrast and Long-Short Prompt Memory for Test-Time Adaptation of SAM3 in Medical Image Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.22963)]
[2026.06]
 
- **Hi-Seg:** Hongqiao Dong, Wenhao Chi, Ruobing Liang, Xiaokui Yang, Wenhua Liang, Peng Hou, Wenjun Pu, Yipeng Zhao, Ping Chen, Haiping Liu, Jianxing He, Bo Liu.<br />
"Human and AI collaboration for pulmonary nodule segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.22486)]
[2026.06]

- **DeformX:** Yi Yang, Xiang Fei, Lehong Wang, Chenhao Li, Zilin Dai, Henry Kou, Lu Li, Howie Choset.<br />
"DeformX: A Versatile Co-Simulation Framework for Deformable Linear Objects." IROS (2026).
[[paper](https://arxiv.org/abs/2606.22116)]
[[code](https://deformx.github.io/)]
[2026.06]

- **SARIF:** Dong-Hyun Moon, Ju-Hyeon Nam, Sang-Chul Lee.<br />
"SARIF: Segment Anything for Robust Image Forensics." ECCV (2026).
[[paper](https://arxiv.org/abs/2606.21108)]
[[code](https://github.com/Inha-CVAI/SARIF_ECCV2026)]
[2026.06]

- **Auto-SAM:** Yijun Wang and Dongyu Zheng and Mingcai Hou and Hongjun Li and Wei Zeng and Caihua Chen and Sixuan Wu and Yujie Gao and Yifan Bai.<br />
"An auto-prompting Segment Anything Model for dual-modal grain segmentation in rock images." Applied Computing and Geosciences (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S2590197426000595)]
[2026.06]

- **SA-VIS:** Edoardo Mello Rella, Ajad Chhatkuli, Shipra Jain, Ender Konukoglu, Luc Van Gool.<br />
"SA-VIS: Sparse frame Annotations for training Video Instance Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.20140)]
[2026.06]

- SAM3 Self-Distillation for Fine-Grained GOOSE 2D Semantic Segmentation.<br />
"SAM3 Self-Distillation for Fine-Grained GOOSE 2D Semantic Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.20130)]
[2026.06]

- **Intrinsic-GS:** Hasan Yazar, Mohamed Rayan Barhdadi, Erchin Serpedin, Mehmet Tuncel, Hasan Kurban.<br />
"Intrinsic 4D Gaussian Segmentation from Scene Cues." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.18623)]
[[code](https://kurbanintelligencelab.github.io/intrinsic-gs/)]
[2026.06]

- Sonata Simonaitis-Boyd, Soonhong Lee, Lauren N. O'Brien, Brandon T. Turner, Ralph Massarczyk, Steven R. Elliott, Aobo Li, Alexander F. Leder.<br />
"Vision AI Agent for Continuous Material Monitoring of LEGEND-1000 LoFi Reentrant Tube." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.18294)]
[2026.06]

- **PEFT-MedSAM:** Asad Channa, Abdullah Khan, Asghar Ali Chandio, Aamir Akbar, Shahzad Memon, Aqib Hussain, Ameer Hamza.<br />
"PEFT-MedSAM: Efficient Fine-Tuning of Medical Foundation Models for Explainable Skin Lesion Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.18707)]
[2026.06]

- Paul Julius Kühn, Saptarshi Neil Sinha, Jakob Hansen, Robin Horst.<br />
"Human-in-the-Loop Atlas-Based 3D Asset Segmentation for Interactive Content Workflows." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.17824)]
[2026.06]

- Nicholas A. Welsh, Lennon J. Shikhman, Monty Nehru Attazs, Seemanthini K. Putane, Van Minh Nguyen, Ryan T. White.<br />
"Post-Launch Capability Expansion of Vision-Language Models via Prompting for On-Orbit Spacecraft Inspection." CVPR Workshop (2026).
[[paper](https://arxiv.org/abs/2606.15427)]
[2026.06]

- **TVG:** Junkai Zhang, Yihe Deng, Kai-Wei Chang, Wei Wang.<br />
"Thinking with Visual Grounding." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.16122)]
[[code](https://github.com/Jun-Kai-Zhang/visually_grounded_thinking)]
[[dataset](https://huggingface.co/datasets/JunkaiZ/TVG)]
[2026.06]
 
- **Multi-HMR 2:** Guénolé Fiche, Philippe Weinzaepfel, Romain Brégier, Fabien Baradel.<br />
"Multi-HMR 2: Multi-Person Camera-Centric Human Detection, Mesh Recovery and Tracking." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.14841)]
[2026.06]

- **DETECTURE:** Aviad Cohen Zada, Nadav Orenstein, Shai Avidan, Gal Oren.<br />
"Sub-Semantic Image Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.14754)]
[[code](https://github.com/Scientific-Computing-Lab/TextureDetecture)]
[2026.06]

- **MuDuo:** Fuyou Mao, Beining Wu, Yanfeng Jiang, Bohan Xu, Lixin Lin, Naye Ji, Hao Zhang, Yan Tang.<br />
"Mutual Distillation of Dual-Foundation Models for Semi-Supervised PET/CT Segmentation." MICCAI (2026).
[[paper](https://arxiv.org/abs/2606.15611)]
[[code](https://github.com/Wu-beining/MuDuo)]
[2026.06]
 
- **Gen-VCoT::** Zhiqiang Zhou, Xu Ling, Junliang Dai.<br />
"Gen-VCoT: Generative Visual Chain-of-Thought Reasoning via Diffusion-Based RGB Intermediate Representations." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.16783)]
[2026.06]

- Nadav Orenstein, Aviad Cohen Zada, Shai Avidan, Gal Oren.<br />
"Where Does Texture Evidence Live in SAM? Features, Proposal Masks, and Texture Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.14755)]
[2026.06]

- Changwoo Song.<br />
"Parameter-Efficient Adaptation of SAM 3 for Automated ITV Generation from 4DCT Images." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.15604)]
[2026.06]
 
- Aniq Ahmad, Heather Bedle, Ahmad Mustafa.<br />
"Domain-Guided Prompting of the Segment Anything Model for Seismic Interpretation: The Role of Attributes, Visualization, and Hybrid Prompts." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.15786)]
[2026.06]

- Yiping Li, Ronald de Jong, Romy van Jaarsveld, Franco Badaloni, Gino Kuiper, Jelle Ruurda, Josien Pluim, Marcel Breeuwer.<br />
"Object Tokens as a Bridge Between Segmentation and Visual Question Answering in Robotic Surgery." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.15861)]
[2026.06]

- **MaxCode:** Qiyue Liang, Steven Ingram, George Vanica, Andi Gavrilescu, Newfel Harrat, Hassan Sipra, Sethuraman Sankaran.<br />
"Agentic Framework for Deep Learning workload migration via In-Context Learning." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.15994)]
[[code](https://github.com/AI-Hypercomputer/accelerator-agents/tree/main/MaxCode)]
[2026.06]
 
- **ActiveSAM:** Tran Dinh Tien, Zhiqiang Shen.<br />
"ActiveSAM: Image-Conditional Class Pruning for Fast and Accurate Open-Vocabulary Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.16996)]
[[code](https://github.com/VILA-Lab/ActiveSAM)]
[2026.06]

- **MooMIns:** Robert Langendörfer, Markus Hillemann, Markus Ulrich.<br />
"MooMIns -- Monocular 3D Reconstruction and Object Pose Estimation from Multiple Instances." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.14389)]
[[code](https://pimpilimpo.github.io/projects/MooMIns/)]
[2026.06]
 
- Keyi Zhu, Kyle Lammers, Chaaran Arunachalam, Kaixiang Zhang, Renfu Lu, Zhaojian Li.<br />
"A Modular Dual-Arm Apple Harvesting Robot with Enhanced Field Performance." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.14089)]
[2026.06]

- **SAM-Deep-EIoU:** Alexander Holmberg.<br />
"SAM-Deep-EIoU: Selective Mask Propagation for Multi-Object Tracking." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.13033)]
[2026.06]

- Li, Chenying, Xiao Tan, Xinyu Huang, Ling Sa, Nailong Zhang, and Gang Qiu.<br />
"Galloping Target Tracking and Parameter Measurement Method for Overhead Transmission Lines Based on SAM2 Video Segmentation." Electronics (2026).
[[paper](https://doi.org/10.3390/electronics15112305)]
[2026.06]
 
- **MSBA-SAM:** Tao Guo, Kui Xu, Kailei Chen, Chun Xie, Shi Qiu & Rui Ye.<br />
"MSBA-SAM: a multi-scale and boundary-aware framework for power grid segmentation in aerial image." Energy Informatics(2026).
[[paper](https://link.springer.com/content/pdf/10.1186/s42162-026-00669-y_reference.pdf)]
[2026.06]

- Suyog Jadhav, Dilip K. Prasad, Krishna Agarwal.<br />
"SAM for Robust Mitochondria Instance Segmentation in Fluorescence Microscopy." CVPRW (2026).
[[paper](https://openaccess.thecvf.com/content/CVPR2026W/PHAROS-AIF-MIH/papers/Jadhav_SAM_for_Robust_Mitochondria_Instance_Segmentation_in_Fluorescence_Microscopy_CVPRW_2026_paper.pdf)]
[2026.06]

- **Mix-QSAM3:** Navin Ranjan, Andreas Savakis.<br />
"Mix-QSAM3: Mixed-Precision Quantization for the Segment Anything with Concepts Model." CVPRW (2026).
[[paper](https://openaccess.thecvf.com/content/CVPR2026W/AIGENS/papers/Ranjan_Mix-QSAM3_Mixed-Precision_Quantization_for_the_Segment_Anything_with_Concepts_Model_CVPRW_2026_paper.pdf)]
[2026.06]
 
- **LSG-SAM:** Muhammad Imran, Yugyung Lee.<br />
"Latent-Stability Gated SAM: Detecting Hallucinated Segmentations under Domain Shift." CVPRW (2026).
[[paper](https://openaccess.thecvf.com/content/CVPR2026W/COGVL/papers/Imran_Latent-Stability_Gated_SAM_Detecting_Hallucinated_Segmentations_under_Domain_Shift_CVPRW_2026_paper.pdf)]
[2026.06]

- **VegSAM:** Chenxiang Wu, Chenyu Li, Danfeng Hong.<br />
"VegSAM: Vegetation-aware Adapter for Segment Anything Model in Urban Tree Segmentation." CVPRW (2026).
[[paper](https://openaccess.thecvf.com/content/CVPR2026W/MORSE/papers/Wu_VegSAM_Vegetation-aware_Adapter_for_Segment_Anything_Model_in_Urban_Tree_CVPRW_2026_paper.pdf)]
[2026.06]

- **SAM3Count:** Joana Konadu Owusu, Shivanand Venkanna Sheshappanavar.<br />
"SAM3Count for Zero-Shot Open Vocabulary Counting in Images and Videos." CVPRW (2026).
[[paper](https://openaccess.thecvf.com/content/CVPR2026W/WiCV/papers/Owusu_SAM3Count_for_Zero-Shot_Open_Vocabulary_Counting_in_Images_and_Videos_CVPRW_2026_paper.pdf)]
[[code](https://github.com/Joan947/SAM3Count)]
[2026.06]
 
- **SAM-OOD:** Seher Kanwal, Seung-Ik Lee.<br />
"SAM-OOD: Foundation-Model-Guided Unknown Mining for Object-Level Anomaly Detection." CVPRW (2026).
[[paper](https://openaccess.thecvf.com/content/CVPR2026W/ADFM/papers/Kanwal_SAM-OOD_Foundation-Model-Guided_Unknown_Mining_for_Object-Level_Anomaly_Detection_CVPRW_2026_paper.pdf)]
[2026.06]

- **C-RWHD:** Khalil Khazmi, Zied Lachiri.<br />
"Coupled annotation and architecture tailoring for lightweight and robust wheat head detection: SAM-oriented bounding boxes with simplified YOLO variants validated on a Tunisian wheat head dataset." SAT (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S2772375526004752)]
[2026.06]

- Chun Cao, et al.<br />
"A Segment Anything Model adaptation framework for battery visual inspection under complex radiographic imaging conditions." PR (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S0031320326010526)]
[2026.06]
 
- **IFP:** Shuqi Xia, Guangze Shi, Jiarui Cao, Aoyuan Shi, Meilin Liu, Xiaoyi Zhang, Yujie Wang, Xueyu Liu, Cai Zhao, Ziyuan He, Yongfei Wu, Mingqiang Wei.<br />
"Instruction-Focus-Prompt:Semantics-Driven Structural Prompts for Universal SAM Segmentation." CVPR Findings (2026).
[[paper](https://openaccess.thecvf.com/content/CVPR2026F/papers/Xia_Instruction-Focus-PromptSemantics-Driven_Structural_Prompts_for_Universal_SAM_Segmentation_CVPRF_2026_paper.pdf)]
[[code](https://github.com/L-AILab/IFP)]
[2026.06]

- **UCOD-MKD:** Huafeng Chen, Chenguang Zhu, Yueming Lyu, Caifeng Shan.<br />
"Beyond Weak Supervision: MLLMs-Guided Graded Knowledge Distillation for Unsupervised Camouflaged Object Detection." CVPR (2026).
[[paper](https://openaccess.thecvf.com/content/CVPR2026/papers/Chen_Beyond_Weak_Supervision_MLLMs-Guided_Graded_Knowledge_Distillation_for_Unsupervised_Camouflaged_CVPR_2026_paper.pdf)]
[[code](https://github.com/2231122/UCOD-MKD)]
[2026.06]

- **mSAMUNet:** Md. Shariful Alam, et al.<br />
"Cell segmentation in microscopy images using a SAM-based U-Net architecture and a novel dataset." CMPB (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S0169260726002245)]
[2026.06]
 
- **RFD:** Ji Xia, et al.<br />
"RFD: A Reducing Feature Discrepancy method for unsupervised cross-modality SAM adaptation." CMIG (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S0895611126000844)]
[2026.06]

- **SAMosaic3D:** Peng Wang, Yongcai Wang, Wang Chen, Hualong Cao, Kang Yang, Chunxu Li, Jie Wen, Deying Li.<br />
"SAMosaic3D: Modular Scene Assembly for Real-Time 3D Segment Anything." CVPR (2026).
[[paper](https://openaccess.thecvf.com/content/CVPR2026/papers/Wang_SAMosaic3D_Modular_Scene_Assembly_for_Real-Time_3D_Segment_Anything_CVPR_2026_paper.pdf)]
[[code](https://penk1ng.github.io/SAMosaic3D/)]
[2026.06]

 
- **RoSAMDepth:** Xuanang Gao, Zhiwei Ning, Gengming Zhang, Jiaxi Cao, Runze Yang, Zhonglong Zheng, Jie Yang, Rong Xiao, Wei Liu.<br />
"RoSAMDepth: Robust Self-supervised Depth Estimation Leveraging Segment Anything Model." CVPR (2026).
[[paper](https://openaccess.thecvf.com/content/CVPR2026/papers/Gao_RoSAMDepth_Robust_Self-supervised_Depth_Estimation_Leveraging_Segment_Anything_Model_CVPR_2026_paper.pdf)]
[[code](https://github.com/xagao/RoSAMDepth)]
[2026.06]

- **PASD:** Zhang, Yuliang and He, Fang and Peng, Lulu and Yan, Tianyu and Zhang, Pingping and Song, Ting and Du, Lili and Chen, Dunjin.<br />
"3D Segment Anything Model With Visual Mamba for Diagnosing Placenta Accreta Spectrum." TIP (2026).
[[paper](https://ieeexplore.ieee.org/document/11551831)]
[[code](https://github.com/Drchip61/PASD)]
[2026.06]

- **CSAM-TUNet:** Chao Xu, et al.<br />
"CSAM-TUNet: A SAM-guided contrastive learning framework with topological attention for pericardial adipose tissue segmentation." BSPC (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S1746809426012474)]
[2026.06]
 
- **TransNet–SAM2:** Bamwenda, Julius, Mehmet Siraç Özerdem, Orhan Ayyildiz, Veysi Akpolat, and İrem Akpolat.<br />
"TransNet–SAM2: A Transformer–Foundation Model Framework for Prompt-Free Segmentation of White Blood Cells in Microscopic Blood Smear Images." Diagnostics (2026).
[[paper](https://doi.org/10.3390/diagnostics16111737)]
[2026.06]

- **SAM-3D-MSF:** Yifu Zhang, Chun Shen & Jianbing Li.<br />
"SAM-3D-MSF: Parameter-Efficient Adaptation of Segment Anything Model for 3D Tooth CBCT Segmentation." PAKDD (2026).
[[paper](https://link.springer.com/chapter/10.1007/978-981-92-1462-4_42)]
[2026.06]

- Fatih Fehmi Şimşek, Melih Altay, Kaan Kalkan, Mehmet Cengiz Arslanoğlu.<br />
"Assessing the Impact of Spatial Resolution and Hyperparameters on Automatic Agricultural Parcel Delineation Using the Segment Anything Model With Multi-Resolution and Super-Resolved Satellite Imagery." Transactions in GIS (2026).
[[paper](https://doi.org/10.1111/tgis.70306)]
[2026.06]

- **LSAC:** Yuxuan Chen, Haoyuan Xu, Peize He.<br />
"Inside the Latent Flow: Causal Deciphering of Attention Dynamics in Audio Separation Foundation Models." INTERSPEECH  (2026).
[[paper](https://arxiv.org/abs/2606.10046)]
[2026.06]

- **ZODS-RS:** Zuan Gu, Tianhan Gao, Langxu Zhao.<br />
"ZODS-RS -- Zero-training Oriented Detection & Segmentation for Remote Sensing." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.10769)]
[2026.06]

- Avi Gupta, Nilotpal Sinha, Vishnu Raj, Sambuddha Saha, Pratik Joshi, Koteswar Rao Jerripothula, Tammam Tillo.<br />
"Listen, Look, and Learn: Learning Without Forgetting through SAM-Audio."  ICML Workshop (2026).
[[paper](https://arxiv.org/abs/2606.10887)]
[2026.06]
 
- **IPSM-Bench:** Jinglin Xu, Shangyan Zhao, Jiabo Wang, Xinghong Mu, Yulong Lei, Jiacheng Zhang, Hongbo Sun, Yageng Li.<br />
"IPSM-Bench: A New Intermediate Phase Segmentation Benchmark in Microstructure Images of Zinc-Based Absorbable Biomaterials." IJCAI  (2026).
[[paper](https://arxiv.org/abs/2606.11001)]
[2026.06]

- Nermeen Abou Baker, Uwe Handmann.<br />
"Don't waste SAM." ESANN (2023).
[[paper](https://arxiv.org/abs/2606.10696)]
[2026.06]

- **RTVP:** Zekai Zhang, Qinghui Chen, Maomao Xiong, Shijiao Ding, Zhanzhi Su, Xinjie Yao, Yiming Sun, Cong Bai, Jinglin Zhang.<br />
"Zero-Shot Learning in Industrial Scenarios: New Large-Scale Benchmark, Challenges and Baseline." AAAI (2025).
[[paper](https://arxiv.org/abs/2606.07965)]
[[code](https://github.com/hellozzk/MMIO)]
[2026.06]
 
- **Open-V:** Silas Kwabla Gah, Ebenezer Owusu.<br />
"Training-Free Generalized Few-Shot Segmentation through Open-Vocabulary Semantic Arbitration." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.09474)]
[2026.06]

- **SAM-Flow:** Haowang Cui, Rui Chen, Tao Luo, Tao Guo, Zheng Qin, Jiaze Wang.<br />
"SAM-Flow: Source-Anchored Masked Flow for Training-Free Image Editing." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.06228)]
[[code](https://github.com/chwbob/Sam-Flow)]
[2026.06]

- **Pigformer:** Mk Bashar, Kuljit Bhatti, Gary Rohrer, Madonna Benjamin, Tami Brown-Brandl, Daniel Morris.<br />
"What's Under the Skin? Estimating Swine Body Condition." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.05611)]
[[code](https://github.com/iambashar/Pigformer)]
[2026.06]
 
- **TopoPult-SSL:** Nicolò Savioli, Luca Del Tongo.<br />
"TopoPult-SSL: Gland-Mask-Free Cross-Device Meibomian Gland Segmentation via Self-Distilled Weak Clinical Priors." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.05347)]
[2026.06]

- **MedSAM-BoxPredictor:** Amirhossein Movahedisefat, Amirreza Fateh, Mohammad Reza Mohammadi.<br />
"Enhancing MedSAM with a Lightweight Box Predictor for Medical Image Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.04705)]
[[code](https://github.com/Amirhosseinmovahedi/MedSAM-BoxPredictor)]
[2026.06]

- **CR-SEG:** Yifan Cao, Xiaocui Yang, Faxian Wan, Shi Feng, Daling Wang, Yifei Zhang.<br />
"CR-SEG: Attention-Guided and CoT-Enhanced Coarse-to-Refined Reasoning Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.03564)]
[2026.06]
 
- **SAMatcher:** Xu Pan, Qiyuan Ma, Mingyue Dong, He Chen, Wei Ji, Xianwei Zheng.<br />
"SAMatcher: Co-Visibility Modeling with Segment Anything for Robust Feature Matching." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.03406)]
[[code](https://xupan.top/Projects/samatcher)]
[2026.06]

- Sema Helali, Lina Abu Nadab, Sausan Alqawas, Alaa Abd-Alrazaq, Faleh Tamimi, Rafat Damseh.<br />
"Large AI Models in Dental Healthcare: From General-Purpose Systems to Domain-Specific Foundation Models." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.02914)]
[2026.06]

- **FLAME:** Yiming Wang, Baiqi Wu, Qingming Li, Jiahao Chen, Tong Zhang, Shouling Ji.<br />
"Order within Chaos: Capturing Intrinsic Energy Anomalies for AI-Manipulated Image Forgery Localization." ICML  (2026).
[[paper](https://arxiv.org/abs/2606.02178)]
[[code](https://github.com/phoenixnir/FLAME)]
[2026.06]
 
- **PerBite:** Ahmad AlMughrabi, Farid Al-Areqi, David Fernández Gómez, Umair Haroon, Marc Bolaños, Ricardo Marques, Petia Radeva.<br />
"PerBite: A Curated Diagnostic Workflow for Bite-Aware Food Volume Estimation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.02021)]
[[code](https://github.com/GCVCG/PerBite-CVPR-MetaFood-2026)]
[2026.06]

- **LG-SAM:** Panav Shah, Geet Sethi, Ashutosh Gandhe.<br />
"Improving Visual Grounding in Remote Sensing via Cluster-Guided Refinement and Model Ensemble Voting." CVPR Workshops (2026).
[[paper](https://arxiv.org/abs/2606.00556)]
[[code](https://github.com/PanavShah1/LG-SAM)]
[2026.06]

- Sakib Mohammad, Jarin Ritu, Md Sakhawat Hossain.<br />
"Single-Channel Tissue Segmentation via Cross-Modal Distillation from Foundation Models." ArXiv (2026).
[[paper](https://arxiv.org/abs/2606.00928)]
[2026.06]

- **GeoSAM-3D:** Arun Sharma.<br />
"GeoSAM-3D: Geodesic Prompt Propagation for Open-Vocabulary 3D Scene Segmentation from Monocular Video." (NeurIPS(2026).
[[paper](https://arxiv.org/abs/2606.00447)]
[2026.06]
 
- **MLAM:** Yuliang Zhang, Fang He, Lulu Peng, Tianyu Yan, Pingping Zhang, Ting Song, Lili Du, Dunjin Chen.<br />
"3D Segment Anything Model with Visual Mamba for Diagnosing Placenta Accreta Spectrum." TIP (2026).
[[paper](https://arxiv.org/abs/2606.00489)]
[[code](https://github.com/Drchip61/PASD)]
[2026.06]

- **CLOC:** Mengqi Lei, Shuokun Cheng, Wei Bao, Shaoyi Du, Jun-Hai Yong, Siqi Li, Yue Gao.<br />
"Count Anything." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.30846)]
[[code](https://github.com/Mengqi-Lei/count-anything)]
[2026.05]

- Suyog Jadhav, Dilip K. Prasad, Krishna Agarwal.<br />
"SAM for Robust Mitochondria Instance Segmentation in Fluorescence Microscopy." CVPR Workshops (2026).
[[paper](https://arxiv.org/abs/2605.31284)]
[2026.05]

- **CM-SAM:** Jiexin Liang, et al.<br />
"CM-SAM: Chaos-enhanced hybrid encoder for medical image segmentation with segment anything model." Biomedical Signal Processing and Control (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S1746809426012310)]
[2026.05]

- **SAM3D-Phys:** Xin Dong, Weijian Deng, Lihan Zhang, Tianru Dai, Wenfeng Deng, Yansong Tang.<br />
"SAM3D-Phys: Towards Multi-Object Interactive Simulation in Real World." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.30239)]
[[code](https://chnxindong.github.io/sam3d-phys/)]
[2026.05]

- **ESAM++:** Qin Liu, Lavisha Aggarwal, Saptarashmi Bandyopadhyay, Vikas Bahirwani, Marc Niethammer, Ehsan Adeli, Andrea Colaco.<br />
"ESAM++: Efficient Online 3D Perception on the Edge." CVPR (2026).
[[paper](https://arxiv.org/abs/2605.29505)]
[[code](https://github.com/qinliuliuqin/esamplusplus)]
[2026.05]

- **DOST:** Bolian Peng, Ying Tang, Xu Liu, Long Sun, Xiaoqiang Lu.<br />
"Turbulence-Robust Dynamic Object Segmentation with Multi-Signal Priors and SAM2 Refinement." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.29292)]
[2026.05]

- **ViTA:** Ji-Hoon Hwang, Jisung Bae, Dong-Wook Kim, Yeonkyu Lee, Seung-Woo Seo.<br />
"From General Vision to Reliable Traversability Estimation: Adapting Vision Foundation Models for Unstructured Outdoor Environments." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.29565)]
[2026.05]

- **CoP:** Sanghyun Jo, Seo Jin Lee, Seohyung Hong, Yoorim Gang, Hyeongsub Kim, Hyungseok Seo, Kyungsu Kim.<br />
"One Click per Cell Type Suffices: Training-free Group Interaction for Cell Instance Segmentation." MICCAI (2026).
[[paper](https://arxiv.org/abs/2605.29429)]
[[code](https://shjo-april.github.io/Chain-of-Prompts/)]
[2026.05]

- Toomas Tahves, Mauro Bellone, Junyi Gu, Raivo Sell.<br />
"SAM-Enhanced Segmentation on Road Datasets: Balancing Critical Classes in Autonomous Driving." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.28136)]
[[project](https://app.visin.eu/projects/sam-zod)]
[[dataset](https://app.visin.eu/datasets)]
[2026.05]

- **Water-AutoSAM:** Sun, Yingrui, Yang Hong, Xiaowei Zhou, and Junyu Dong.<br />
"Water-AutoSAM: Dual-Domain Enhanced Auto-Prompting SAM for Underwater Segmentation." Journal of Marine Science and Engineering (2026).
[[paper](https://doi.org/10.3390/jmse14100953)]
[2026.05]

- Dmytro Klepachevskyi, Alexander Wong, Sirisha Rambhatla, Yuhao Chen.<br />
"Zero-Shot Object Re-Identification in Egocentric Kitchen Videos via Multi-Stage SAM3 Feature Fusion." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.26383)]
[2026.05]

- **PlayClass:** Prince Ravi Leow, Neil Scheidwasser, Rebecca Oscarsson, Per Jensen, Samir Bhatt, David Alejandro Duchêne.<br />
"PlayClass: Automated Play Behaviour Classification in Poultry." CVPR Workshop (2026).
[[paper](https://arxiv.org/abs/2605.27304)]
[[code](https://github.com/sbhattlab/PlayClassCV4Animals)]
[2026.05]
 
- **PinPoint:** Pouya Sadeghi, Shawn He, Pedro Pablo Guerrero Vela, C. Thomas, Alex Wong, Sirisha Rambhatla.<br />
"PinPoint: Prompting with Informative Interior Points." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.26689)]
[2026.05]

- Mannat Khurana, Sanyam Jain, Rishav Agarwal.<br />
"Generative Animations: A Multi-Model Pipeline for Prompt-Driven Motion Synthesis." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.27203)]
[2026.05]

- **InstructSAM:** Yuqian Yuan, Wentong Li, Zhaocheng Li, Yutong Lin, Juncheng Li, Siliang Tang, Jun Xiao, Yueting Zhuang, Wenqiao Zhang.<br />
"InstructSAM: Segment Any Instance with Any Instructions." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.26102)]
[[code](https://github.com/DCDmllm/InstructSAM)]
[2026.05]

- **BED-SAM2:** Tyler Rust, Dara McNally, Kyle O'Donnell, Colin Kelly, Chandra Kambhamettu.<br />
"BED-SAM2: Boundary-Enhanced-Depth SAM2 via Monocular Geometric Priors." CVPR Workshop (2026).
[[paper](https://arxiv.org/abs/2605.24893)]
[[code](https://github.com/TylerRust-1/BED-SAM2)]
[2026.05]

- **ANAUS:** Chunzheng Zhu, Yijun Wang, Jianxin Lin, Feng Wang, Hongwei Wang, Lei Zhao, Shengli Li, Kenli Li.<br />
"Anatomy-Anchored Self-Supervision: Distilling Vision Foundation Models for Invariant Ultrasound Representation." MICCAI (2026).
[[paper](https://arxiv.org/abs/2605.25402)]
[[code](https://github.com/zhcz328/ANAUS)]
[2026.05]

- **RepSAM:** Wenhui Chu.<br />
"RepSAM: Bridging Foundation Models to Robotic Vision via Representation-Guided Adaptation." IJCAI-ECAI 2026 workshop (2026).
[[paper](https://arxiv.org/abs/2605.25495)]
[2026.05]

- **SAM 3-to-YOLOv8:** Marcos Vinicius Mendes Faria, Thiago Borges Pereira, Isabella C. F. S. Condotta, Thiago Meireles Paixão, Francisco de Assis Boldt.<br />
"SAM3-Assisted Training of Lightweight YOLO Models for Precision Pig Farming." IEEE SAS  (2026).
[[paper](https://arxiv.org/abs/2605.25860)]
[2026.05]
 
- **DeCoDrift:** H. M. Shadman Tabib, Md. Shamsuzzoha Bayzid, M Sohel Rahman.<br />
"DeCoDrift: Stabilizing Decoder Coupling in Closed-Loop Foundation Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.25730)]
[2026.05]

- **MGNet,:** Xia Li, Xinran Liu, Lin Qi, Junyu Dong.<br />
"Weakly Supervised Camouflaged Object Detection Based on the SAM Model and Mask Guidance." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.25385)]
[2026.05]

- **CLIP-Guided SAM:** Shayan Jalilian, Abdul Bais.<br />
"CLIP-Guided SAM: Parameter-Efficient Semantic Conditioning for Promptable Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.24807)]
[2026.05]

- **ViViD-5K:** Xiangzhi Tong, Chengrui Zhang, Mac Flaherty, Andre Matteo Garcia, Dominic Gorman, Jonathan Jaramillo, Justine E. Vanden Heuvel, Yu Jiang.<br />
"ViViD-5K: Vineyard vision dataset for field-based berry detection and segmentation and grape cluster closure estimation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.24353)]
[2026.05]

- **ConceptSeg-R1:** Yuan Zhao, Youwei Pang, Jiaming Zuo, Wei Ji, Kailai Zhou, Bin Fan, Yunkang Cao, Lihe Zhang, Xiaofeng Liu, Huchuan Lu, Weisi Lin, Dacheng Tao, Xiaoqi Zhao.<br />
"ConceptSeg-R1: Segment Any Concept via Meta-Reinforcement Learning." ArXiv (2026).
[[paper](https://arxiv.org/pdf/2605.20385)]
[[project](https://ntu-ai4x.github.io/ConceptSeg-R1/)]
[[code](https://github.com/NTU-AI4X/ConceptSeg-R1)]
[2026.05]

- **MGGA:** Fan Gao, et al.<br />
"MedSAM-guided geometry-aware 2D-3D feature fusion for medical image registration." Neural Networks (2026).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S0893608026005265)]
[[code](https://github.com/goghfan/MGGA)]
[2026.05]

- **PromptLessSAM:** Mohammed Al-Mustafa Hendo, et al.<br />
"PromptLessSAM: From Foundational Model to Domain Expert via Lightweight Decoder Adaptation for Crack Segmentation." Electrical, Computer and Communications Engineering (2026).
[[paper](https://journals.iium.edu.my/ejournal/index.php/iiumej/article/view/4124)]
[2026.05]
 
- **MT-SAM:** Zhao, Litao and Zhang, Yuhan and Ji, Libiao and Bao, Jie and Li, Caizi and NG, Chi-Fai and Heng, Pheng-Ann.<br />
"MT-SAM: A Mamba-Transformer Enhanced SAM with Prior-guided Prompting for Multi-modal Prostate Cancer Delineation." TMI (2026).
[[paper](https://ieeexplore.ieee.org/abstract/document/11516322)]
[[code](https://github.com/LuckLT/MT-SAM)]
[2026.05]

- **STATUARIO-40K:** Palmieri, Giorgio and Ranieri, Andrea and Vasarelli, Andrea and Di Angelo, Luca.<br />
"STATUARIO-40K: Fine-Tuning SAM 3 for Instance Segmentation at Scale of Monuments, Statues, and Cracks." ArXiv (2026).
[[paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6751498)]
[[dataset](http://deeplearning.ge.imati.cnr.it/statuario-40k)]
[2026.05]

- **Per-SAM-MCPA:** Hu, Chuting, Size Dai, Shifan Wu, Qiaolin Ye, and He Yan.<br />
"Per-SAM-MCPA: A Lightweight Framework for Individual Tree Crown Segmentation from UAV Imagery." Remote Sens (2026).
[[paper](https://www.mdpi.com/2072-4292/18/10/1559)]
[2026.05]

- **ColorSAM:** Bangcheng Zhan, et al.<br />
"ColorSAM: teaching SAM to segment color medical images via quaternion decoding and prompt generation." ESWA (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S0957417426017707)]
[[code](https://github.com/Chasingbetter/ColorSAM)]
[2026.05]

- **PromptSAMNet:** A.R. Revathi, et al.<br />
"PromptSAMNet: A memory-enhanced adaptive prompting and clustering-augmented SAM 2.0 framework for multi-leaf plant disease diagnosis." Applied Soft Computing (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S1568494626008951)]
[2026.05]

- **SDDNet:** Zhao, Yu and Sun, Jing and Zhang, Guohui and Sun, Fuming and Li, Haojie.<br />
"Enhancing SAM2 for Industrial Defect Detection via Dual-Adapter Fine-Tuning." TIM (2026).
[[paper](https://ieeexplore.ieee.org/abstract/document/11520404)]
[[code](https://github.com/wellMachine/SDDNet/)]
[2026.05]

- **FS-Grasp:** Zhai, Di-Hua and Yu, Sheng and Xia, Yuanqing.<br />
"Fast and Efficient 6-DoF Grasp Estimation With Segment Anything Model in Cluttered Scenes." IEEE/ASME Transactions on Mechatronics (2026).
[[paper](https://ieeexplore.ieee.org/abstract/document/11520551)]
[2026.05]
 
- **AISCT-SAM:** Kuang, Hulin and Tan, Xianzhen and Li, Shunuo and Kan, Shichao and Liu, Jin and Sun, Jiarui and Zhang, Jingyang and Yang, Chunfeng and Qiu, Wu and Zhang, Jiulou and Chen, Yang and Wang, Jianxin.<br />
"AISCT-SAM: Customized SAM-Med2D with 3D Context Awareness and Self-Prompt Generation for Fully Automatic Acute Ischemic Stroke Lesion Segmentation on Non-Contrast CT Scans." JBHI (2026).
[[paper](https://ieeexplore.ieee.org/abstract/document/11520231)]
[2026.05]

- **MUP-SAM:** Lyuyang Tong, Jingwen Jiang, Bo Du.<br />
"MUP-SAM: Multi-Scale Vision Mamba UNet Prompt Generation for SAM in Multi-Organ Medical Image Segmentation." Neural Networks (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S0893608026005666)]
[2026.05]

- **CraterSAM+:** Li, Miyu and Li, Junjie and Wang, Yumei and Liu, Yu.<br />
"Self-Improving SAM with Specialist Knowledge via Adaptive Direct Preference Optimization for Crater Segmentation." IEEE Geoscience and Remote Sensing Letters (2026).
[[paper](https://ieeexplore.ieee.org/abstract/document/11520836)]
[2026.05]

- **MedSAM-COALF:** Zhao, Pengyu and Hou, Yonghong and Wu, Jiasai and Yan, Ke and Huo, Shuwei.<br />
"MedSAM-COALF: A Cold-Start One-Shot Active Learning Framework for Medical Image Segmentation via Foundation Model-Guided Proxy Tasks and Uncertainty-Aware Sampling."IEEE Sensors Journal (2026).
[[paper](https://ieeexplore.ieee.org/abstract/document/11521038)]
[2026.05]

- **SAM-SS:** Wang, Yalin and Han, Wei and Peng, Hong and Zheng, Weihao and Li, Xiaoxu and Kang, Zhongfeng and Chan, Sixian.<br />
"SAM-SS: Straightforward and Efficient Designs Based on Segment Anything Model for Semantic Segmentation." TCSS (2026).
[[paper](https://ieeexplore.ieee.org/abstract/document/11520893)]
[2026.05]

- **S2C-Net:** Ning, Hailong and Li, Haojie and Zhang, Wuxia and Lei, Tao and Chen, Yanping and Cao, Xiaopeng and Nandi, Asoke K..<br />
"S2C-Net: SAM2-Based Dual-Domain Feature Reconstruction and Semantic Decoupling for Tiny Remote Sensing Object Counting." TGRS (2026).
[[paper](https://ieeexplore.ieee.org/abstract/document/11520899)]
[[code](https://github.com/xuptLHj/S2C-Net)]
[2026.05]

- **LiteWaveRep-MedSAM:** Lieqiang Liu, Chengping Zhao, Tengxiao Xu, Wutao Xiong and Yuxiao Zhang.<br />
"LiteWaveRep-MedSAM: A lightweight medical image segmentation model based on wavelet transform and reparameterization." Biomedical Physics & Engineering Express (2026).
[[paper](https://iopscience.iop.org/article/10.1088/2057-1976/ae6e48/meta)]
[[code](https://github.com/LIU1116268/litewaverep)]
[2026.05]
 
- **TorqueSAM:** Rahat, Shahzalal Khan, et al.<br />
"TorqueSAM: unsupervised kidney CT analysis with localization and SAM-integrated torque clustering segmentation." ArXiv (2026).
[[paper](https://dspace.bracu.ac.bd/xmlui/handle/10361/28062)]
[2026.05]

- Elgström, Albert, Diaz, Jose, Bosch, Carles.<br />
"Hierarchical Annotation of Mural Paintings Using SAM." ArXiv (2026).
[[paper](https://diglib.eg.org/items/ccb00843-2db2-4859-93e2-16ccd7f35e57)]
[2026.05]

- **ERSF-AS:** Cheng Ju, et al.<br />
"ERSF-AS: Explainable recursive zero-shot anomaly segmentation with spatial-frequency priors via CLIP-SAM collaboration." Neurocomputing (2026).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231226014256)]
[2026.05]

- Tan, L., Xia, Y., Teng, D. et al.<br />
"Comparative evaluation of conventional radiomics and VGG-SAM fusion strategies for MRI-based preoperative prediction of perineural invasion in cervical cancer." Abdom Radiol (2026).
[[paper](https://doi.org/10.1007/s00261-026-05559-1)]
[2026.05]

- **FAST-ME :** Kakia Panagidi, Stathes Hadjieftymiadis.<br />
"FAST-ME: Foundation-aware Adaptive Stopping for Motion Estimation for Efficient IoT Video Analysis." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.23428)]
[2026.05]

- Sebastian Cavada, Francesco Pelosin, Lapo Faggi.<br />
"Training-Free Fine-Grained Semantic Segmentations in Low Data Regimes: A FungiTastic Baseline." CVPRW (2026).
[[paper](https://arxiv.org/abs/2605.22492)]
[2026.05]

- **COCOTree:** Junhyub Lee, Seunghun Chae, Hyosu Kim.<br />
"COCOTree: A Dataset and Benchmark for Open Tree-Structured Visual Decomposition." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.22068)]
[[code](https://github.com/melonkick3090/COCOTree)]
[2026.05]

- **SAMOSA:** Deyi Zhu, Yuji Wang, Yong Liu, Yansong Tang, Bingyao Yu, Jiwen Lu, Jie Zhou.<br />
"Segment Anything with Motion, Geometry, and Semantic Adaptation for Complex Nonlinear Visual Object Tracking." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.22538)]
[[code](https://github.com/DurYi/SAMOSA)]
[2026.05]

- **DECA:** Lifeng Yang, Linshu Chen, Anxing Hu, et al.<br />
"Underwater image segmentation method based on dual-encoder." ICCIIA (2026).
[[paper](https://doi.org/10.1117/12.3113443)]
[2026.05]

- **SGA:** Jinjin Zhang, Xiefan Guo, Di Huang.<br />
"Spatial Gram Alignment for Ultra-High-Resolution Image Synthesis." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.20808)]
[[code](https://github.com/zhang0jhon/SGA)]
[2026.05]

- **HyDAR-Pano3D:** Yaoyao Yue, Jérôme Schmid, Xiaoshuang Li, Eduardo Delamare, Jinman Kim.<br />
"HyDAR-Pano3D: A Hybrid Disentangled Anatomical Recovery Framework for Panoramic-to-3D Reconstruction." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.20827)]
[2026.05]
 
- **SAM-Sode:** Wanying Tan, Shuo Yan, Dazhi Huang, Yazheng Liu, Zili Shao, Rufeng Chen, Hechang Chen, Mude Shi, Tianxing Ji, Sihong Xie.<br />
"SAM-Sode: Towards Faithful Explanations for Tiny Bacteria Detection." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.21186)]
[2026.05]

- **Stream3D:** Kaichen Zhou, Zeyang Bai, Xinhai Chang, Mengyu Wang, Paul Liang, Fangneng Zhan.<br />
"Stream3D: Sequential Multi-View 3D Generation via Evidential Memory." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.21472)]
[[code](https://anonymous-submission-20.github.io/streaming3D.github.io/)]
[2026.05]

- **LCA:** Qisai Liu, Alloy Das, Zhanhong Jiang, Joshua R. Waite, Aditya Balu, Adarsh Krishnamurthy, Soumik Sarkar.<br />
"Lighting-aware Unified Model for Instance Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.20436)]
[2026.05]

- **VASA:** Zilin Wang, Stella X. Yu.<br />
"Vision Harnessing Agent for Open Ad-hoc Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.19410)]
[2026.05]

- **DarkLLM:** Ye Sun, Xin Wang, Jiaming Zhang, Yifeng Gao, Yixu Wang, Yifan Ding, Qixian Zhang, Henghui Ding, Xingjun Ma, Yu-Gang Jiang.<br />
"DarkLLM: Learning Language-Driven Adversarial Attacks with Large Language Models." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.18868)]
[[code](https://github.com/sunye23/DarkLLM)]
[2026.05]

- Tonghao Zhuang, Shanglong Hu, Yongsheng Luo, Zhiqi Zhang, Yu Li.<br />
"Synergistic Foundation Models for Semi-Supervised Fetal Cardiac Ultrasound Analysis: SAM-Med2D Boundary Refinement and DINOv3 Semantic Enhancement." MICCAI Workshop (2026).
[[paper](https://arxiv.org/abs/2605.19799)]
[[code](https://github.com/2826056177/zcst_fetus2026)]
[2026.05]
 
- Ananth Sriram, Neel Mokaria, Rajveer Singh.<br />
"Passive Construction Site Safety Monitoring via Persona-Scaffolded Adversarial Chain-of-Thought VLM Verification." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.19869)]
[[code](https://github.com/ananthsriram1/ironsite-hackathon-project-safety_assistant)]
[2026.05]

- **MedFM-Robust:** Xiangxiang Cui, Tianjin Huang, Yifang Wang, Lijie Hu, Lu Yin.<br />
"MedFM-Robust: Benchmarking Robustness of Medical Foundation Models." MICCAI (2026).
[[paper](https://arxiv.org/abs/2605.19027)]
[[code](https://github.com/AbnerAI/MedFM-Robust)]
[2026.05]

- **OmniVL-Guard Pro:** Jinjie Shen, Zheng Huang, Yuchen Zhang, Yujiao Wu, Yaxiong Wang, Lechao Cheng, Shengeng Tang, Tianrui Hui, Nan Pu, Zhun Zhong.<br />
"OmniVL-Guard Pro: A Tool-Augmented Agent for Omnibus Vision-Language Forensics." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.16962)]
[[code](https://github.com/shen8424/OmniVL-Guard-Pro)]
[2026.05]
 
- **SegRAG:** Abderrahmene Boudiaf, Irfan Hussain, Sajid Javed.<br />
"SegRAG: Training-Free Retrieval-Augmented Semantic Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.17630)]
[[code](https://github.com/boudiafA/SegRAG)]
[2026.05]

- **D3S2:** Yachan Guo, JoseLuis Gomez Zurita, Danna Xue, Yi Xiao, AntonioManuel Lopez Pena.<br />
"Metric-Guided Feature Fusion of Visual Foundation Models for Segmentation Tasks." CVPR Findings (2026).
[[paper](https://arxiv.org/abs/2605.16864)]
[[code](https://github.com/gyc-code/metric-guided-fusion)]
[2026.05]

- **HyperVision:** Guanyiman Fu, Jingtao Li, Zihang Cheng, Zhuanfeng Li, Diqi Chen, Yan Xu, Fengchao Xiong, Jianfeng Lu, Jun Zhou.<br />
"HyperVision: A Channel-Adaptive Ground-Based Hyperspectral Vision Pre-trained Backbone." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.17286)]
[[code](https://github.com/lronkitty/HyperVision)]
[2026.05]
 
- **Rad-VLSM:** Fengyi Zhang, Xujie Zeng, Mohan Liu, Zengyi Wang, Yalong Jiang.<br />
"Rad-VLSM: A Cross-Modal Framework with Semantics-Assisted Prompting for Medical Segmentation and Diagnosis." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.18130)]
[2026.05]

- Divya Joshi, J. D. Peiffer, Colleen Peyton, R. James Cotton.<br />
"Markerless Motion Capture for Biomechanical Whole-Body Kinematic Estimation in Infants." EMBC (2026).
[[paper](https://arxiv.org/abs/2605.17120)]
[2026.05]

- **WOW-Seg:** Danyang Li, Tianhao Wu, Bin Li, Zhenyuan Chen, Yang Zhang, Yuxuan Li, Ming-Ming Cheng, Xiang Li.<br />
"WOW-Seg: A Word-free Open World Segmentation Model." ICLR (2026).
[[paper](https://arxiv.org/abs/2605.16903)]
[[code](https://github.com/AAwCAA/WOW-Seg-Meta)]
[2026.05]

- **TinySAM 2:** Zhaoyuan Ding, Yijing Yang, Han Shu, Xinghao Chen.<br />
"TinySAM 2: Extreme Memory Compression for Efficient Track Anything Model." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.18013)]
[2026.05]

- **SparseSAM:** Hoai-Chau Tran, Chi H. Nguyen, Duy M. H. Nguyen, Mathias Niepert, Fan Lai, Khoa D. Doan.<br />
"SparseSAM: Structured Sparsification of Activations in Segment Anything Models." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.17633)]
[2026.05]

- **CAR-SAM:** Houji Wen, Jiangyong Yu, Jun Li, Dawei Yang.<br />
"CAR-SAM: Cross-Attention Reconstruction for Post-Training Quantization of the Segment Anything Model." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.16901)]
[2026.05]

- Eugenia Moris, Alicia Costábile, Sebastián Rey, Irene Ferreiro, Joaquín Hurtado, Lizandra Lissette Luciano, Matías Villagrán, Aisha Espino Vázquez, Jomari Ramos, Isadora Monteiro, María Victoria de Santiago, Pilar Moreno, Gonzalo Moratorio, José Ignacio Orlando.<br />
"End-to-end plaque counting and virus titration from laboratory plate images with deep learning." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.16008)]
[2026.05]

- Raushan Joshi, Jean-Yves Guillemaut.<br />
"Robust Prior-Guided Segmentation for Editable 3D Gaussian Splatting." ICIP (2026).
[[paper](https://arxiv.org/abs/2605.16065)]
[2026.05]
 
- **MT-SAM:** Litao Zhao, Yuhan Zhang, Libiao Ji, Jie Bao, Caizi Li, Chi-Fai NG and Pheng-Ann Heng.<br />
"MT-SAM: A Mamba-Transformer Enhanced SAM with Prior-guided Prompting for Multi-modal Prostate Cancer Delineation." TMI (2026).
[[paper](https://ieeexplore.ieee.org/document/11516322/)]
[[code](https://github.com/LuckLT/MT-SAM)]
[2026.05]

- **DT-ZSAM:** Fan, Zhanpeng, Xinglei Gu, Qiyu Liu, Yangheng Hu, and Liang Yu.<br />
"Fusing Dual-Threshold Prompts with SAM for Shot Peening Coverage Assessment on Aircraft Propeller Blades." Applied Sciences (2026).
[[paper](https://doi.org/10.3390/app16094309)]
[2026.05]

- **DeFakerOne:** GuangJian Team, Ant Group.<br />
"Venus-DeFakerOne: Unified Fake Image Detection & Localization." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.14091)]
[[code](https://github.com/venus-guangjian/Venus-DeFakerOne)]
[2026.05]
 
- **PDI-Bench:** Jiaxin Wu, Yihao Pi, Yinling Zhang, Yuheng Li, Xueyan Zou.<br />
"Quantitative Video World Model Evaluation for Geometric-Consistency." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.15185)]
[[code](https://pdi-bench.github.io/)]
[2026.05]

- **MedCore:** Cenwei Zhang, Suncheng Xiang, Lei You.<br />
"MedCore: Boundary-Preserving Medical Core Pruning for MedSAM." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.13688)]
[[code](https://github.com/cenweizhang/MedCore)]
[2026.05]

- **Seg-Agent:** Chao Hao, Jun Xu, Ji Du, Shuo Ye, Ziyue Qiao, Xiaodong Cun, Guangcong Wang, Xubin Zheng, Zitong Yu.<br />
"Seg-Agent: Test-Time Multimodal Reasoning for Training-Free Language-Guided Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.12953)]
[[code](https://github.com/Fanye12/Seg-Agent)]
[2026.05]

- **PointGS:** Yixiao Song, Qingyong Li, Wen Wang, Zhicheng Yan.<br />
"PointGS: Semantic-Consistent Unsupervised 3D Point Cloud Segmentation with 3D Gaussian Splatting." CVPR (2026).
[[paper](https://arxiv.org/abs/2605.11520)]
[[code](https://github.com/SebastianYIXIAO/pointGS)]
[2026.05]

- **FocusDepth:** Yuxin Du, Tao Lin, Zile Zhong, Runting Li, Xiyao Chen, Jiting Liu, Chenglin Liu, Ying-Cong Chen, Yuqian Fu, Bo Zhao.<br />
"Focusable Monocular Depth Estimation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.11756)]
[2026.05]

- **M4-SAM:** Jiyuan Liu, Jia Lin, Xiaofei Zhou, Runmin Cong, Deyang Liu, Zhi Liu.<br />
"M4-SAM: Multi-Modal Mixture-of-Experts with Memory-Augmented SAM for RGB-D Video Salient Object Detection." CVPR (2026).
[[paper](https://arxiv.org/abs/2605.11760)]
[[code](https://github.com/HankLiu2020/M4-SAM)]
[2026.05]
 
- Stefano Colamonaco, Andrei-Bogdan Florea, Jaron Maene.<br />
"Weakly Supervised Segmentation as Semantic-Based Regularization." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.13674)]
[2026.05]

- **RUAC:** Hongyou Zhou, Marc Toussaint, Ling Shao, Zihan Ye.<br />
"Segment Anything with Robust Uncertainty-Accuracy Correlation." ICML (2026).
[[paper](https://arxiv.org/abs/2605.10603)]
[[code](https://github.com/HongyouZhou/ruac.git)]
[2026.05]

- **FSAM:** Phuoc-Nguyen Bui, Van-Nguyen Pham, Duc-Tai Le, Junghyun Bum, Hyunseung Choo.<br />
"Frequency Adapter with SAM for Generalized Medical Image Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.09925)]
[2026.05]

- **CAFE:** Shuang Liang, Zeqing Wang, Yuxian Li, Xihui Liu, Han Wang.<br />
"From Pixels to Concepts: Do Segmentation Models Understand What They Segment?." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.09591)]
[[code](https://github.com/T-S-Liang/CAFE)]
[[project](https://t-s-liang.github.io/CAFE)]
[[dataset](https://huggingface.co/datasets/teemosliang/CAFE)]
[2026.05]
 
- **SAMOFT:** Yanchao Wang, Dawei Zhang, Chengzhuan Yang, Wei Liu, Minglu Li, Hua Wang, Zhonglong Zheng, Ming-Hsuan Yang.<br />
"SAMOFT: Robust Multi-Object Tracking via Region and Flow." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.09417)]
[2026.05]

- R. James Cotton, Pouyan Firouzabadi, Wendy Murray.<br />
"Monocular Biomechanical Tracking of Fingers with Inverse Kinematics to Foundation Models." EMBC (2026).
[[paper](https://arxiv.org/abs/2605.09258)]
[2026.05]

- **RCoT-Seg:** Junwei Wen, Deshui Miao, Guangming Lu, Xin Li, Wenjie Pei.<br />
"RCoT-Seg: Reinforced Chain-of-Thought for Video Reasoning and Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.07334)]
[[code](https://github.com/Victor-wjw/RCoT-Seg)]
[2026.05]

- **SARA:** Jiesong Lian, Zixiang Zhou, Ruizhe Zhong, Yuan Zhou, Qinglin Lu, Rui Wang, Long Hu, Yixue Hao, Baoru Huang.<br />
"SARA: Semantically Adaptive Relational Alignment for Video Diffusion Models." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.07800)]
[2026.05]

- **SAM 3D Animal:** Xuyi Hu, Jin Lyu, Jiuming Liu, Yebin Liu, Silvia Zuffi, Liang An, Stefan Goetz.<br />
"SAM 3D Animal: Promptable Animal 3D Reconstruction from Images in the Wild." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.07604)]
[2026.05]

- **UniD-Shift:** Shuai Zhang, Zhecheng Shi, Zhuxiao Li, Jing Ou, Tengxi Wang, Yuan Liu, Wufan Zhao.<br />
"UniD-Shift: Towards Unified Semantic Segmentation via Interpretable Share-Private Multimodal Decomposition." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.07356)]
[[code](https://github.com/shuaizhang69/UniD-Shift)]
[2026.05]
 
- **Qwen3-VL-Seg:** Yuan Yao, Qiushi Yang, Humen Zhong, Jiangning Wei, Yifang Men, Shuai Bai, Miaomiao Cui, Zhibo Yang.<br />
"Qwen3-VL-Seg: Unlocking Open-World Referring Segmentation with Vision-Language Grounding." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.07141)]
[2026.05]

- **AS-SAM2:** Lv, Tao and Ding, Shenrun and Wang, Yuji and Li, Yue and Lu, Xiaohuan and Tian, Youliang.<br />
  "AS-SAM2: Adaptive Self-correction for Visual Tracking with SAM2." TCSVT (2026).
  [[paper](https://ieeexplore.ieee.org/abstract/document/11506610)] 
  [[code](https://github.com/oatlvv/AS-SAM2)]
  [2026.05]
  
- **GA3T:** Siwei Cai, Knut Peterson, Quan Tran, Christian Ricks, Dhanush Parthasarathy, Amir Kaidarov, Neil Deshpande, Sukaina Najm, David Han, Lifeng Zhou.<br />
"GA3T: A Ground-Aerial Terrain Traversability Dataset for Heterogeneous Robot Teams in Unstructured Environments." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.06478)]
[[code](https://drexel0-my.sharepoint.com/:f:/g/personal/sc3568_drexel_edu/IgAOBo94oaiBRJH3B1bgi4Y_AetpqXDjHcSPw28Rpb-h-lo?e=esDuho)]
[2026.05]

- **HP-Adapter:** Hinako Mitsuoka, Kazuhiro Hotta.<br />
"Prompt-Free and Efficient SAM2 Adaptation for Biomedical Semantic Segmentation via Dual Adapters." ICIP (2026).
[[paper](https://arxiv.org/abs/2605.05979)]
[2026.05]

- **Ilov3Splat:** Binh Long Nguyen, Kien Nguyen, Sridha Sridharan, Clinton Fookes, Peyman Moghadam.<br />
"Ilov3Splat: Instance-Level Open-Vocabulary 3D Scene Understanding in Gaussian Splatting." ICPR (2026).
[[paper](https://arxiv.org/abs/2605.04506)]
[[code](https://csiro-robotics.github.io/Ilov3Splat)]
[2026.05]

- ZhiXin Sun.<br />
"Example-Based Object Detection." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.04501)]
[[code](https://github.com/sunzx97/examples_based_object_detection)]
[2026.05]

- **X2SAM:** Hao Wang, Limeng Qiao, Chi Zhang, Lin Ma, Guanglu Wan, Xiangyuan Lan, Xiaodan Liang.<br />
"X2SAM: Any Segmentation in Images and Videos." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.00891)]
[[code](https://github.com/wanghao9610/X2SAM)]
[[project](https://wanghao9610.github.io/X2SAM)]
[2026.05]

- **GLASSNet:** Morteza Moradi, Mohammad Moradi, Simone Palazzo, Ali Borji, Concetto Spampinato.<br />
"Global-Local Feature Decoding with Adapter-Guided SAMv2 for Salient Object Detection." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.02616)]
[2026.05]

- **VL-SAM-v3:** Chih-Chung Liu, Zhiwei Lin, Yongtao Wang.<br />
"VL-SAM-v3: Memory-Guided Visual Priors for Open-World Object Detection." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.03456)]
[2026.05]

- **ViewSAM:** Jiawei Ge, Xintian Zhang, Jiuxin Cao, Bo Liu, Fabian Deuser, Chang Liu, Gong Wenkang, Siyou Li, Juexi Shao, Wenqing Wu, Chen Feng, Ioannis Patras.<br />
"ViewSAM: Learning View-aware Cross-modal Semantics for Weakly Supervised Cross-view Referring Multi-Object Tracking." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.02638)]
[2026.05]

- **DFUDA:** Yerin Cheon, Aruna Balasubramanian, Francois Rameau.<br />
"Dual-Foundation Models for Unsupervised Domain Adaptation." ICPR (2026).
[[paper](https://arxiv.org/abs/2605.03365)]
[[code](https://github.com/ycheon1101/DFUDA)]
[2026.05]
 
- Chase Cartwright, Gongbo Guo, Sai Teja Pusuluri, Christopher N. Mayhew, Mark Hester, Horacio E. Castillo.<br />
"Approaching human parity in the quality of automated organoid image segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.03053)]
[2026.05]

- **SAMamba3D:** Rui Zhang, Xianzhi Song, Linqi Zhu, Branko Bijeljic, Gensheng Li, Martin J. Blunt.<br />
"SAMamba3D: adapting Segment Anything for generalizable 3D segmentation of multiphase pore-scale images." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.00916)]
[[code](https://github.com/ImperialCollegeLondon/SAMamba-3D)]
[2026.05]

- **Remote SAMsing:** Osmar Luiz Ferreira de Carvalho, Osmar Abílio de Carvalho Júnior, Anesmar Olino de Albuquerque, Daniel Guerreiro e Silva.<br />
"Remote SAMsing: From Segment Anything to Segment Everything." ArXiv (2026).
[[paper](https://arxiv.org/abs/2605.00256)]
[2026.05]

- **MmSAM:** Qingpeng Wang, Zhou Huang, Ying Chen, Yi Bao.<br />
"MmSAM: multimodal meets SAM2 for efficient remote sensing semantic segmentation." International Journal of Applied Earth Observation and Geoinformation (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S1569843226002177)]
[[code](https://github.com/W-qp/MmSAM)]
[2026.04]
 
- **Three-shot SAM2:** Zhongyi Zhang, Julie Hides, Enrico De Martino, Gervase Tuxworth.<br />
"Multicenter evaluation of three-shot SAM2 segmentation for group-level quantification of lumbar paraspinal muscles at the L4/L5 level on multi-sequence MRI." European Journal of Radiology (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S0720048X26002342)]
[2026.04]

- Lee, H., Jo, Y., Hong, I. et al.<br />
"Segment anything model guided dual-mask framework for anatomically faithful medical image translation." Sci Rep (2026).
[[paper](https://doi.org/10.1038/s41598-026-50209-7)]
[2026.04]

- **SAM-BM:** Huanhuan Lv, Songru Jiang, Yuhao Bai, Tuohang Wan, Chang Gou, Lijun Chen.<br />
"SAM-BM: An adversarial benchmark for loss functions and multi-scale objects in segment anything models." CVIU (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S1077314226001566)]
[[code](https://github.com/Kahsolt/adv-SAM)]
[2026.04]

- **SAM2-PolypNet:** Zhaoting Mu, et al.<br />
"SAM2-PolypNet: SAM2 with adaptive context enhancement model for polyp segmentation." BSPC (2026).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S1746809426009353)]
[[code](https://github.com/XUPTMZT/SAM2-PolypNet)]
[2026.04]

- Zhihao Ni, Youwen He, Ziyue Zhou, Hankun Zhang, and Jun Tian.<br />
"Rapid 3D reconstruction of key power plant equipment using SAM foreground segmentation and 3D Gaussian splatting." AMNA(2026).
[[paper](https://doi.org/10.1117/12.3114168)]
[2026.04]

- Haiyu Yang, Miel Hostens.<br />
"Lightweight Distillation of SAM 3 and DINOv3 for Edge-Deployable Individual-Level Livestock Monitoring and Longitudinal Visual Analytics." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.27128)]
[2026.04]

- **SAM-FuseNet:** Zhu, Chenyang and Wang, Jierui and Zhang, Lanlan and Liang, Jia and Su, Qianxiao and Li, Baihua.<br />
"SAM-FuseNet: Segment Anything Guided Multimodal Fusion for RGB–Thermal Aerial Robotic Perception." TGRS (2026).
[[paper](https://ieeexplore.ieee.org/document/11314587)]
[2026.04]

- **MemOVCD:** Zuzheng Kuang, Honghao Chang, Boqiang Liang, Haoqian Wang, Lijun He, Fan Li, Haixia Bi.<br />
"MemOVCD: Training-Free Open-Vocabulary Change Detection via Cross-Temporal Memory Reasoning and Global-Local Adaptive Rectification." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.26774)]
[[code](https://github.com/kzigzag/MemOVCD)]
[2026.04]

- **Bridge:** Mingbo Hong, Feng Liu, Caroline Gevaert, George Vosselman, Hao Cheng.<br />
"Bridge: Basis-Driven Causal Inference Marries VFMs for Domain Generalization." CVPR (2026).
[[paper](https://arxiv.org/abs/2604.26820)]
[[code](https://mingbohong.github.io/Bridge/)]
[2026.04]

- **CRC-SAM:** Daniel Lao.<br />
"CRC-SAM: SAM-Based Multi-Modal Segmentation and Quantification of Colorectal Cancer in CT, Colonoscopy, and Histology Images." ISBI (2026).
[[paper](https://arxiv.org/abs/2604.24793)]
[2026.04]
 
- **MAFFNet:** Zhiwei Feng and Benyi Yang and Baosong Deng.<br />
"SAM-Assisted Multimodal Collaborative Enhancement for Remote Sensing Image Segmentation." Information Fusion (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S156625352600312X)]
[2026.04]

- Sanghati Basu.<br />
"Robustness Evaluation of a Foundation Segmentation Model Under Simulated Domain Shifts in Abdominal CT: Implications for Health Digital Twin Deployment." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.25685)]
[[code](https://github.com/SANGHATI23/sam-brats-robustness-audit)]
[2026.04]

- **FastSAM-CD:** Zhang, Shuxin and Lei, Tao and Wang, Xingwu and Liu, Tongfei and Lv, Zhiyong and Liu, Daqi and Gong, Maoguo and Nandi, Asoke K.<br />
"FastSAM-CD: Remote Sensing Image Change Detection Using Vision Foundation Models With Stronger Encoder and Decoder." TGRS (2026).
[[paper](https://ieeexplore.ieee.org/document/11371346)]
[2026.04]

- **GeoSAM:** Wujie Zhou, Jin Xie, Caie Xu, Yuanyuan Liu, Yunchao Wang.<br />
"Adapt, Generate, and Supervise: Geometry-Aware Diffusion-Guided SAM Framework for Remote Sensing Semantic Segmentation." TGRS (2026).
[[paper](https://ieeexplore.ieee.org/abstract/document/11348940)]
[[code](https://github.com/110-011/GeoSAM)]
[2026.04]

- **ATSG:** Zhang, Yifan and Jiang, Zhiguo and Zhang, Haopeng.<br />
"ATSG: Adaptive Token Linking With Segment Anything Model Guidance for Weakly Supervised Remote Sensing Image Semantic Segmentation." TGRS (2026).
[[paper](https://ieeexplore.ieee.org/document/11348965)]
[[code](https://github.com/zhangyifan25/ATSG)]
[2026.04]

- **SemiSAM-O1:** Yichi Zhang, Le Xue, Bichun Xu, Judong Luo, Zhigang Wu, Yu Fu, Zixin Hu, Yuan Cheng, Yuan Qi.<br />
"SemiSAM-O1: How far can we push the boundary of annotation-efficient medical image segmentation?." Medical Image Analysis (2026).
[[paper](https://arxiv.org/abs/2604.24109)]
[[code](https://github.com/YichiZhang98/SemiSAM-O1)]
[2026.04]

- **INSIGHT:** Alexander Nikitas Dimopoulos, Joseph Grasso, John Beltz.<br />
"INSIGHT: Indoor Scene Intelligence from Geometric-Semantic Hierarchy Transfer for Public Safety." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.23095)]
[2026.04]

- **AgentRVOS:** Deshui Miao, Chao Yang, Chao Tian, Guoqing Zhu, Kai Yang, Zhifan Mo, Xin Li.<br />
"AgentRVOS for MeViS-Text Track of 5th PVUW Challenge: 3rd Method." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.22836)]
[2026.04]
 
- **OAMVOS:** Deshui Miao, Xingsen Huang, Yameng Gu, Xiaogang yu, Xin Li, Ming-Hsuan Yang.<br />
"OAMVOS: 2nd Report for 5th PVUW MOSE Track." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.22837)]
[2026.04]

- **ASR-SaSaSa2VA:** Zhiyu Wang, Xudong Kang, Shutao Li.<br />
"2nd of the 5th PVUW MeViS-Audio Track: ASR-SaSaSa2VA." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.23935)]
[2026.04]

- **DiffuSAM:** Tal Grossman, Noa Cahan, Lev Ayzenberg, Hayit Greenspan.<br />
"DiffuSAM: Diffusion-Based Prompt-Free SAM2 for Few-Shot and Source-Free Medical Image Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.24719)]
[2026.04]

- **SPD:** Jingxuan Kang, Ziqi Zhang, Shaoming Zheng, Shuang Li, Uday Bharat Patel, Alexander Harry Fitzhugh, Phillip Lung, Yusuf Kiberu, Nikesh Jathanna, Shahnaz Jamil-Copley, Bernhard Kainz, Chen Qin.<br />
"Learning from Noisy Prompts: Saliency-Guided Prompt Distillation for Robust Segmentation with SAM." CVPR (2026).
[[paper](https://arxiv.org/abs/2604.23314)]
[2026.04]

- **SGP-SAM:** Zixuan Tang, Shen Zhao.<br />
"SGP-SAM: Self-Gated Prompting for Transferring 3D Segment Anything Models to Lesion Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.22825)]
[2026.04]

- **HFS-TriNet:** Xu Lu, Qianhong Peng, Qihao Zhou, Shaopeng Liu, Xiuqin Ye, Chuan Yang, Yuan Yuan.<br />
"HFS-TriNet: A Three-Branch Collaborative Feature Learning Network for Prostate Cancer Classification from TRUS Videos." CVPR (2026).
[[paper](https://arxiv.org/abs/2604.22388)]
[[code](https://github.com/ayushimehrotra/H-Sets)]
[2026.04]

- **HAM-SAM2:** Pan, Kanghua and Chen, Guo and Zhu, Wei and Zhao, Danhuai and Lu, Tong.<br />
"HAM-SAM2: Enhancing SAM2 for Visual Object Tracking with Adaptive Motion Modeling and Hierarchical Memory Bank." ICASSP (2026).
[[paper](https://ieeexplore.ieee.org/abstract/document/11462733)]
[2026.04]

- Xiao, Haodong and Yu, Wenbo and Fang, Hao and Sun, Shuoyang and Chen, Bin and Wang, Xuan and Xia, Shu-Tao.<br />
"Diffusion-Based Natural Adversarial Perturbations Towards Segment Anything Model." ICASSP (2026).
[[paper](https://ieeexplore.ieee.org/abstract/document/11460977)]
[2026.04]

- **AnchorDiffusion:** Honggang Zhao, et al.<br />
"AnchorDiffusion: High-fidelity local image editing via anchor-SAM masks and dynamic noise fusion." Information Sciences (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S0020025526004184)]
[[code](https://github.com/haizhu12/Local-Guidance-Edit/tree/main)]
[2026.04]

- Isaac (Zack) Duitz, et al.<br />
"Accelerating Medical Image Segmentation with EfficientViT-SAM." ArXiv (2026).
[[paper](https://sophie-guo.com/efficientvit-medical-report.pdf)]
[2026.04]

- **SAMDistill:** Zhaozhong Wang, Dian Shao, Lei Zhang, Zuowei Zhang & Binglu Wang.<br />
"SAMDistill: SAM-based Spatial-temporal Distillation for Robust 3D Object Detection." MIR (2026).
[[paper](https://link.springer.com/article/10.1007/s11633-025-1586-9)]
[2026.04]
 
- **DBSAM:** Zheng, Ziyi and Li, Weixing and Pan, Feng and Wang, Ronghao and Gao, Qi.<br />
"DBSAM: A Dual-Branch Segment Anything Model for Infrared Small Target Detection." TGRS (2026).
[[paper](https://ieeexplore.ieee.org/document/11482224)]
[2026.04]

- **Anchor-SAM:** Li, Wenhai and Huang, Xiaohui and Yang, Xiaofei and Zhou, Yicong and Peng, Jiangtao and Ban, Yifang and Jiang, Nan.<br />
"Anchor-SAM: Active Mining of Latent Anchors From SAM Encoder for Road Extraction." TGRS (2026).
[[paper](https://ieeexplore.ieee.org/document/11483139)]
[[code](https://github.com/Hmbb0606/Anchor-SAM)]
[2026.04]

- **PromptReg:** Huang, Shiqi and Xu, Tingfa and Li, Jianan and Saeed, Shaheer U. and Shen, Ziyi and Barratt, Dean C. and Hu, Yipeng.<br />
"PromptReg: Interactive Registration by “Corresponding Prompts” for Segment Anything Model (SAM)." TIP (2026).
[[paper](https://ieeexplore.ieee.org/document/11483297)]
[2026.04]
 
- **Echo-SAM:** Chang Liu, et al.<br />
"Echo-SAM: fully exploits the performance of SAM for echocardiography segmentation." Biomedical Signal Processing and Control (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S1746809426009031)]
[2026.04]

- **Med-JSCC:** Yang, Fan and Sun, Shuo and Jin, Chanyuan and Gao, Zhen and Niyato, Dusit.<br />
"MedSAM-2 Large Model-Driven Medical Image Semantic Communication for Telemedicine." IEEE Internet of Things Journal (2026).
[[paper](https://ieeexplore.ieee.org/document/11488641)]
[2026.04]
 
- **FMTW-SAM:** Wenjie Cai, et al.<br />
"FMTW-SAM: Foreground mixing and temporally weighted SAM feature fusion for cross-domain semi-supervised segmentation of type-B aortic dissection in computed tomography angiography." Neurocomputing (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S0925231226011550)]
[2026.04]

- **LAES-UNet:** Tingru Liu, Yantong​ Zhan, Yan Wang and Delong Shao.<br />
"An EfficientSAM-based Integrated Network for Ore Image Segmentation." Engineering Research Express (2026).
[[paper](https://iopscience.iop.org/article/10.1088/2631-8695/ae62d0/pdf)]
[2026.04]

- **DualSplat:** Xu Wang, Zhiru Wang, Shiyun Xie, Chengwei Pan, Yisong Chen.<br />
"DualSplat: Robust 3D Gaussian Splatting via Pseudo-Mask Bootstrapping from Reconstruction Failures." CVPR (2026).
[[paper](https://arxiv.org/abs/2604.21631)]
[[code](https://lans1ot.github.io/DualSplat/)]
[2026.04]

- **Amodal SAM:** Bo Zhang, Zhuotao Tian, Xin Tao, Songlin Tang, Jun Yu, Wenjie Pei.<br />
"Amodal SAM: A Unified Amodal Segmentation Framework with Generalization." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.20748)]
[2026.04]

- **DualGaze-VLM:** Zehong Ke, Yanbo Jiang, Jinhao Li, Zhiyuan Liu, Yiqian Tu, Qingwen Meng, Heye Huang, Jianqiang Wang.<br />
"From Scene to Object: Text-Guided Dual-Gaze Prediction." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.20191)]
[2026.04]
 
- **Semantic-Fast-SAM:** Byunghyun Kim.<br />
"Semantic-Fast-SAM: Efficient Semantic Segmenter." APSIPA ASC (2026).
[[paper](https://arxiv.org/abs/2604.20169)]
[[code](https://github.com/KBH00/Semantic-Fast-SAM)]
[2026.04]

- **SHP-SAM:** Xiao, Fen and Huang, Ruozhuo and Wu, Zhenwei and Gao, Xieping.<br />
"Scribble-guided Hierarchical Prompt for SAM-Based Weakly Supervised Salient Object Detection." TCSVT (2026).
[[paper](https://ieeexplore.ieee.org/document/11479339)]
[[code](https://github.com/XTU-ICIPL/SHP-SAM)]
[2026.04]

- **YOLOv10–SAM:** Verma, Pooja and Paul, Ayan and Machavaram, Rajendra and Bhattacharya, Mahua.<br />
"Toward Grounded YOLO-SAM: Unified Detection–Segmentation Framework for Agricultural Intelligence." ACDSA (2026).
[[paper](https://ieeexplore.ieee.org/abstract/document/11467945)]
[2026.04]

- **CoCo-SAM3:** Yanhui Chen, Baoyao Yang, Siqi Liu, Jingchao Wang.<br />
"CoCo-SAM3: Harnessing Concept Conflict in Open-Vocabulary Semantic Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.19648)]
[2026.04]

- **LiteBounD:** Shivanshu Agnihotri, Snehashis Majhi, Deepak Ranjan Nayak.<br />
"Sharpening Lightweight Models for Generalized Polyp Segmentation: A Boundary Guided Distillation from Foundation Models." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.17865)]
[[code](https://github.com/lostinrepo/LiteBounD)]
[2026.04]
 
- **ASTM Grain Size Estimator:** Abdul Mueez, Shruti Vyas.<br />
"Bridging Foundation Models and ASTM Metallurgical Standards for Automated Grain Size Estimation from Microscopy Images." CVPR Workshops (2026).
[[paper](https://arxiv.org/abs/2604.18957)]
[[code](https://github.com/mueez-overflow/ASTM-Grain-Size-Estimator)]
[2026.04]

- **RefAtt-SAM:** Wei, Xingji and Liu, Nanqing and Lei, Sen and Li, Heng-Chao.<br />
"Reference and Attention Guided Few-Shot Adaptation of Segment Anything Model for Remote Sensing Images." TGRS (2026).
[[paper](https://ieeexplore.ieee.org/document/11396980)]
[[code](https://github.com/WILSON10111/RefAtt-SAM)]
[2026.04]

- **SEM-SAM:** Linlin Wei, Yongfeng Xiao, Yifei Wang, Shan Ye, Tao Xu, Congyun Liu, Shuai Shao, Linge Ma, Jihong Cheng, Haowei Pei, Shuping Yin, Zhihua Han, Fuguo Jiang.<br />
"From Optical Inversion to AI Vision: an AI-driven SEM Workflow for Empowering Precise Granulometric Analysis." Clean Energy (2026).
[[paper](https://doi.org/10.1093/ce/zkag015)]
[2026.04]
 
- **SGCT-Net:** Jiang, Yubo and Yuan, Zheming and Zhou, Tairan and Chen, Jing and Xie, Fengying and Jiang, Zhiguo and Zhang, Haopeng.<br />
"SGCT-Net: SAM-Guided Cross-Teaching Network for Weakly Supervised Semantic Segmentation for Generating High-Quality CAMs in High-Resolution Remote Sensing Imagery." JSTARS (2026).
[[paper](https://ieeexplore.ieee.org/document/11477155)]
[2026.04]

- **PLS:** Zhang, Aoran and Ling, Zhigang and Tan, Haoran and Wang, Yaonan.<br />
"A Part-aware Learning Network for Weakly Supervised Semantic Segmentation." TMM (2026).
[[paper](https://ieeexplore.ieee.org/document/11472621)]
[2026.04]

- **DiffuSAM:** Geet Sethi, Panav Shah, Ashutosh Gandhe, Soumitra Darshan Nayak.<br />
"DiffuSAM: Diffusion Guided Zero-Shot Object Grounding for Remote Sensing Imagery." ICLR Workshop (2026).
[[paper](https://arxiv.org/abs/2604.18201)]
[2026.04]
 
- **ViperSAM:** Dawar Jyoti Deka.<br />
"Inference-Time Temporal Probability Smoothing for Stable Video Segmentation with SAM2 under Weak Prompts." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.17115)]
[2026.04]

- Qiuyu Kong, Shakiba Sharifi, Zanxi Ruan, Yiming Wang, Marco Cristani.<br />
"Is SAM3 ready for pathology segmentation?." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.18225)]
[2026.04]

- Yifei Yan, Yankai Liao, Linqi Ye.<br />
"A Rapid Deployment Pipeline for Autonomous Humanoid Grasping Based on Foundation Models." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.17258)]
[2026.04]

- **Dual-Anchoring:** Kangyi Wu, Pengna Li, Kailin Lyu, Lin Zhao, Qingrong He, Jinjun Wang, Jianyi Liu.<br />
"Dual-Anchoring: Addressing State Drift in Vision-Language Navigation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.17473)]
[2026.04]
 
- Islam Mansour, Francescopaolo Sica, Michael Schmitt.<br />
"Prompting Foundation Models for Zero-Shot Ship Instance Segmentation in SAR Imagery." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.17920)]
[2026.04]

- **Petro-SAM:** Yili Ren, Shiqi Wen, Li Hou, Dingwen Xiao, Weiming Zhang, Caleb Chen Cao, Lin Wang, Zilu Zheng, Qianxiao Su, Mingjun Zhao, Lei Chen.<br />
"From Boundaries to Semantics: Prompt-Guided Multi-Task Learning for Petrographic Thin-section Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.14805)]
[2026.04]
 
- **WILD-SAM:** Yucheng Pan, Heping Li, Zhangle Liu, Sajid Hussain, Bin Pan.<br />
"WILD-SAM: Phase-Aware Expert Adaptation of SAM for Landslide Detection in Wrapped InSAR Interferograms." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.14540)]
[2026.04]

- **TF-SMOT:** Laurence Bonat, Francesco Tonini, Elisa Ricci, Lorenzo Vaquero.<br />
"Training-Free Semantic Multi-Object Tracking with Vision-Language Models." FG (2026).
[[paper](https://arxiv.org/abs/2604.14074)]
[2026.04]
 
- Hayato Inoue, Shota Harada, Shumpei Takezaki, Ryoma Bise.<br />
"Cell Instance Segmentation via Multi-Task Image-to-Image Schrödinger Bridge." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.12318)]
[2026.04]

- **Pi-HOC:** Sravan Chittupalli, Ayush Jain, Dong Huang.<br />
"Pi-HOC: Pairwise 3D Human-Object Contact Estimation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.12923)]
[[code](https://pi-hoc.github.io/)]
[2026.04]

- Caiwen Jiang, Lei Zeng, Wei Liu.<br />
"A 3D SAM-Based Progressive Prompting Framework for Multi-Task Segmentation of Radiotherapy-induced Normal Tissue Injuries in Limited-Data Settings." Medical Image Analysis (2026).
[[paper](https://arxiv.org/abs/2604.13367)]
[2026.04]

- Hao Wang, Jiqing Zhang, Xin Yang, Baocai Yin, Lu Jiang, Zetian Mi, Huibing Wang.<br />
"Modality-Agnostic Prompt Learning for Multi-Modal Camouflaged Object Detection." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.12380)]
[2026.04]

- **PR-MaGIC:** Minjae Lee, Sungwoo Hur, Soojin Hwang, Won Hwa Kim.<br />
"PR-MaGIC: Prompt Refinement Via Mask Decoder Gradient Flow For In-Context Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.12113)]
[[code](https://postech-minjaelee.github.io/PR-MaGIC/)]
[2026.04]

- **OccSAM-Bench:** Nhan Ho, Luu Le, Thanh-Huy Nguyen, Thien Nguyen, Xiaofeng Liu, Ulas Bagci.<br />
"Seeing Through the Tool: A Controlled Benchmark for Occlusion Robustness in Foundation Segmentation Models." CVPR workshop (2026).
[[paper](https://arxiv.org/abs/2604.11711)]
[2026.04]

- **VLMaterial:** Jiangyou Zhu, He Chen.<br />
"VLMaterial: Vision-Language Model-Based Camera-Radar Fusion for Physics-Grounded Material Identification." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.11671)]
[2026.04]

- **H-SPAM:** Julien Walther, Rémi Giraud, Michaël Clément.<br />
"H-SPAM: Hierarchical Superpixel Anything Model." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.11218)]
[2026.04]
 
- **SeSAM :** Anurag Das, Anna Kukleva, Xinting Hu, Yuki M. Asano, Bernt Schiele.<br />
"Do Instance Priors Help Weakly Supervised Semantic Segmentation?." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.11170)]
[2026.04]

- **Boxes2Pixels:** Camile Lendering, Erkut Akdag, Egor Bondarev.<br />
"Boxes2Pixels: Learning Defect Segmentation from Noisy SAM Masks." CVPR workshop (2026).
[[paper](https://arxiv.org/abs/2604.11162)]
[[code](https://github.com/CLendering/Boxes2Pixels)]
[2026.04]
 
- Kaden Stillwagon, Alexandra Dunnum VandeLoo, Benjamin Magondu, Craig R. Forest.<br />
"Self-supervised Pretraining of Cell Segmentation Models." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.10609)]
[2026.04]

- **RobustMedSAM:** Jieru Li, Matthew Chen, Micky C. Nnamdi, J. Ben Tamo, Benoit L. Marteau, May D. Wang.<br />
"RobustMedSAM: Degradation-Resilient Medical Image Segmentation via Robust Foundation Model Adaptation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.09814)]
[2026.04]

- **PASTA:** Melanie Neubauer, Elmar Rueckert, Christian Rauch.<br />
"PASTA: Vision Transformer Patch Aggregation for Weakly Supervised Target and Anomaly Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.09701)]
[2026.04]

- **MV3DIS:** Yibo Zhao, Yigong Zhang, Jin Xie.<br />
"MV3DIS: Multi-View Mask Matching via 3D Guides for Zero-Shot 3D Instance Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.08916)]
[[code](https://github.com/zybjn/MV3DIS)]
[2026.04]

- Adrian Manchado, Tanner Cellio, Jonathan Keane, Yiyang Wang.<br />
"AI Driven Soccer Analysis Using Computer Vision." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.08722)]
[2026.04]

- Lars Lundqvist, Earl Ranario, Hamid Kamangir, Heesup Yun, Christine Diepenbrock, Brian N. Bailey, J. Mason Earles.<br />
"Does Your VFM Speak Plant? The Botanical Grammar of Vision Foundation Models for Object Detection." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.09920)]
[2026.04]

- **DiTTA:** Jihun Kim, Hoyong Kwon, Hyeokjun Kweon, Kuk-Jin Yoon.<br />
"Bootstrapping Video Semantic Segmentation Model via Distillation-assisted Test-Time Adaptation." CVPR (2026).
[[paper](https://arxiv.org/abs/2604.10950)]
[[code](https://github.com/jihun1998/DiTTA)]
[2026.04]

- **OVS-DINO:** Haoxi Zeng, Qiankun Liu, Yi Bin, Haiyue Zhang, Yujuan Ding, Guoqing Wang, Deqiang Ouyang, Heng Tao Shen.<br />
"OVS-DINO: Open-Vocabulary Segmentation via Structure-Aligned SAM-DINO with Language Guidance." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.08461)]
[2026.04]

- **Tarot-SAM3:** Weiming Zhang, Dingwen Xiao, Songyue Guo, Guangyu Xiang, Shiqi Wen, Minwei Zhao, Lei Chen, Lin Wang.<br />
"Tarot-SAM3: Training-free SAM3 for Any Referring Expression Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.07916)]
[2026.04]

- **PanoSAM2:** Dingwen Xiao, Weiming Zhang, Shiqi Wen, Lin Wang.<br />
"PanoSAM2: Lightweight Distortion- and Memory-aware Adaptions of SAM2 for 360 Video Object Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.07901)]
[2026.04]

- **UniSurgSAM:** Haofeng Liu, Ziyue Wang, Alex Y. W. Kong, Guanyi Qin, Yunqiu Xu, Chang Han Low, Mingqi Gao, Lap Yan Lennon Chan, Yueming Jin.<br />
"UniSurgSAM: A Unified Promptable Model for Reliable Surgical Video Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.03645)]
[[code](https://jinlab-imvr.github.io/UniSurgSAM)]
[2026.04]

- **Boxer:** Daniel DeTone, Tianwei Shen, Fan Zhang, Lingni Ma, Julian Straub, Richard Newcombe, Jakob Engel.<br />
"Boxer: Robust Lifting of Open-World 2D Bounding Boxes to 3D." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.05212)]
[[code](http://facebookresearch.github.io/boxer)]
[2026.04]
 
- Ye Bi, Bimala Acharya, David Rosero, Juan Steibel.<br />
"Automated Segmentation and Tracking of Group Housed Pigs Using Foundation Models." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.03426)]
[2026.04]

- Abdelmoamen Nasser, Yousef Baba'a, Murad Mebrahtu, Nadya Abdel Madjid, Jorge Dias, Majid Khonji.<br />
"Visual Prompt Based Reasoning for Offroad Mapping using Multimodal LLMs." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.04564)]
[2026.04]

- **SGPer:** Shijie Wang, Zijian Wang, Yadan Luo, Scott Chapman, Xin Yu, Zi Huang.<br />
"Learning to Synergize Semantic and Geometric Priors for Limited-Data Wheat Disease Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.05415)]
[2026.04]
 
- **Pickalo:** Alessandro Tarsi, Matteo Mastrogiuseppe, Saverio Taliani, Simone Cortinovis, Ugo Pattacini.<br />
"Pickalo: Leveraging 6D Pose Estimation for Low-Cost Industrial Bin Picking." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.04690)]
[[code](https://mesh-iit.github.io/project-jl2-camozzi/)]
[2026.04]

- **CardioSAM:** Ujjwal Jain.<br />
"CardioSAM: Topology-Aware Decoder Design for High-Precision Cardiac MRI Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.03313)]
[2026.04]

- **FSS-SAM3:** Yi-Jen Tsai, Yen-Yu Lin, Chien-Yao Wang.<br />
"Few-Shot Semantic Segmentation Meets SAM3." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.05433)]
[[code](https://github.com/WongKinYiu/FSS-SAM3)]
[2026.04]

- **XSeg:** Hongxia Gao, Litao Li, Yixin Chen, Jiali Wen, Kaijie Zhang, Qianyun Liu.<br />
"XSeg: A Large-scale X-ray Contraband Segmentation Benchmark For Real-World Security Screening." CVPR (2026).
[[paper](https://arxiv.org/abs/2604.03706)]
[[code](https://huggingface.co/datasets/xi801/XSeg)]
[2026.04]

- **IndoorCrowd:** Sebastian-Ion Nae, Radu Moldoveanu, Alexandra Stefania Ghita, Adina Magda Florea.<br />
"IndoorCrowd: A Multi-Scene Dataset for Human Detection, Segmentation, and Tracking with an Automated Annotation Pipeline." CVPR Workshop (2026).
[[paper](https://arxiv.org/abs/2604.02032)]
[[code](https://sheepseb.github.io/IndoorCrowd/)]
[2026.04]
 
- **GRAZE:** Syed Ahsan Masud Zaidi, Lior Shamir, William Hsu, Scott Dietrich, Talha Zaidi.<br />
"GRAZE: Grounded Refinement and Motion-Aware Zero-Shot Event Localization ." CVPR Workshop  (2026).
[[paper](https://arxiv.org/abs/2604.01383)]
[[code](https://github.com/AhsanZaidi12/GRAZE)]
[2026.04]

- **DPMO:** Hongru Chen, Jiyang Huang, Jia Wan, Antoni B. Chan.<br />
"Dense Point-to-Mask Optimization with Reinforced Point Selection for Crowd Instance Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.01742)]
[2026.04]
 
- Derek Austin.<br />
"Better Rigs, Not Bigger Networks: A Body Model Ablation for Gaussian Avatars." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.01447)]
[2026.04]

- Xusheng He, Canyang Wu, Jinrong Zhang, Weili Guan, Jianlong Wu, Liqiang Nie.<br />
"The 1st Winner for 5th PVUW MeViS-Text Challenge: Strong MLLMs Meet SAM3 for Referring Video Object Segmentation." CVPR Workshop (2026).
[[paper](https://arxiv.org/abs/2604.00404)]
[[code](https://github.com/Moujuruo/MeViSv2_Track_Solution_2026)]
[2026.04]

- **TEP:** Jinrong Zhang, Canyang Wu, Xusheng He, Weili Guan, Jianlong Wu, Liqiang Nie.<br />
"Advancing Complex Video Object Segmentation via Tracking-Enhanced Prompt: The 1st Winner for 5th PVUW MOSE Challenge." CVPR Workshop (2026).
[[paper](https://arxiv.org/abs/2604.00395)]
[2026.04]

- **APRVOS:** Deshui Miao, Yameng Gu, Chao Yang, Xin Li, Haijun Zhang, Ming-Hsuan Yang.<br />
"APRVOS: 1st Place Winner of 5th PVUW MeViS-Audio Track." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.18665)]
[2026.04]

- **AdaLoRA-QAT:** Prantik Deb, Srimanth Dhondy, N. Ramakrishna, Anu Kapoor, Raju S. Bapi, Tapabrata Chakraborti.<br />
"AdaLoRA-QAT: Adaptive Low-Rank and Quantization-Aware Segmentation." ISBI (2026).
[[paper](https://arxiv.org/abs/2604.01167)]
[[code](https://prantik-pdeb.github.io/adaloraqat.github.io/)]
[2026.04]

- **TF-SSD:** Zhijin He, Shuo Jin, Siyue Yu, Shuwei Wu, Bingfeng Zhang, Li Yu, Jimin Xiao.<br />
"TF-SSD: A Strong Pipeline via Synergic Mask Filter for Training-free Co-salient Object Detection." CVPR (2026).
[[paper](https://arxiv.org/abs/2604.00549)]
[[code](https://github.com/hzz-yy/TF-SSD)]
[2026.04]

- **PC-SAM:** Chengcheng Lv, Rushi Li, Mincheng Wu, Xiufang Shi, Zhenyu Wen, Shibo He.<br />
"PC-SAM: Patch-Constrained Fine-Grained Interactive Road Segmentation in High-Resolution Remote Sensing Images." ArXiv (2026).
[[paper](https://arxiv.org/abs/2604.00495)]
[[code](https://github.com/Cyber-CCOrange/PC-SAM)]
[2026.04]

- **LunarRockSAM:** Wang, Yinan and Ye, Hongxia and Fa, Wenzhe.<br />
"LunarRockSAM: A Domain-Adapted SAM with Bright-Spots Prompting and Conditional Screening for Lunar Rock Extraction." IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing (2026).
[[paper](https://ieeexplore.ieee.org/abstract/document/11442940)]
[2026.03]
 
- **DBM-SAM:** Wei Gao, Teng Li, Cunang Jiang, Sicheng Wang, Yu Dai.<br />
"DBM-SAM: Dual-branch multiscale adaptation of SAM for medical ultrasound segmentation." Displays (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S0141938226001095)]
[2026.03]

- **SAM2-RoadNet:** Feng, Ruyue, Ziyou Guo, Xiao Du, and Tieru Wu.<br />
"SAM2-RoadNet: Topology-Aware Multi-Scale Road Extraction from High-Resolution Remote Sensing Images." Remote Sensing (2026).
[[paper](https://www.mdpi.com/2072-4292/18/6/913)]
[2026.03]
 
- **IDRG-mSAM:** Wang, Leiquan and Meng, Yu and Luo, Chunbo and Xu, Mingming and Wu, Chunlei and Li, Zhongwei.<br />
"SAM-Based Multi-Scale Fine-Tuning with Inter-layer Difference Guidance for Remote Sensing Change Detection." IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing (2026).
[[paper](https://ieeexplore.ieee.org/abstract/document/11449005/)]
[2026.03]

- **SAM-ColonPolypGen:** Shasha Zhang and Yuang Cai and Yijun Chen and Xiang Cai and Peng Li.<br />
"SAM-ColonPolypGen: Enhancing automated colon polyp report generation via reinforcement learning and prompt chaining." Biomedical Signal Processing and Control (2026).
[[paper](https://doi.org/10.1016/j.bspc.2026.110084)]
[2026.03]

- **SemiBUVS:** Long Chen and Qingqing Zheng and Yingying Chen and Faqin Lv and Qiong Wang.<br />
"SAM-Guided Semi-Supervised Breast Lesion Segmentation in Ultrasound Videos with A New Dataset." Expert Systems with Applications (2026).
[[paper](https://doi.org/10.1016/j.eswa.2026.132141)]
[[code](https://github.com/003GH/SemiBUVS)]
[2026.03]
 
- **Mask-CDKD:** Daoyu Shu and Zhan Zhang and Xiao Huang and Ru Wang and Nan Jia and Xinzhe Fu and Bingnan Yang and Fang Wan and Jianzhong Lu and Jianya Gong.<br />
"Mask-CDKD: A source-free and label-free cross-domain knowledge distillation framework from SAM for satellite onboard VHR land-cover mapping." ISPRS Journal of Photogrammetry and Remote Sensing (2026).
[[paper](https://doi.org/10.1016/j.isprsjprs.2026.03.035)]
[2026.03]

- **SAM2-WaveUNet:** Shuzhou Lv and Shubin Zhang and Xiaoshuang Huang and Dong An and Jincun Liu and Yan Meng and Yaoguang Wei.<br />
"SAM2-WaveUNet: A Frequency-Enhanced Segmentation Network for Fine-Grained Marine Organism Delineation." Expert Systems with Applications (2026).
[[paper](https://doi.org/10.1016/j.eswa.2026.132175)]
[2026.03]
 
- **VLP-SAM:** Sakurai, Kosuke, Ryotaro Shimizu, and Masayuki Goto.<br />
"Vision and Language Reference for a Segment Anything Model for Few-Shot Segmentation." Journal of Imaging(2026).
[[paper](https://www.mdpi.com/2313-433X/12/4/143)]
[2026.03]

- **AutoPrompt-SAM3D:** Cheng, W., Tang, J., Wang, T. et al.<br />
"AutoPrompt-SAM3D: integrated generation and selection for SAM2-based 3D medical segmentation." BMC Bioinformatics (2026).
[[paper](https://doi.org/10.1186/s12859-026-06390-7)]
[2026.03]

- Shata, Dina, Simon Denman, Sara Omrani, Robin Drogemuller, Hend Ali, and Ayman Wagdy.<br />
"Parameter-Efficient Adaptation of Generative-Foundation (Flux, Qwen) vs. Zero-Shot (Gemini, SAM3) Models for Aerial Image Segmentation." Buildings (2026).
[[paper](https://www.mdpi.com/2075-5309/16/7/1369)]
[2026.03]
 
- **HATSAM:** Tang, T., Rao, Z., Wang, Y. et al.<br />
"HATSAM: hierarchical adaptation strategy for segment anything model in medical imaging." SIViP (2026).
[[paper](https://doi.org/10.1007/s11760-026-05288-4)]
[2026.03]

- **SaSaSaSa2VA:** Dengxian Gong, Quanzhu Niu, Shihao Chen, Yuanzheng Wu, Yikang Zhou, Tao Zhang, Haobo Yuan, Lu Qi, Shunping Ji.<br />
"SaSaSaSa2VA: 2nd Place of the 5th PVUW MeViS-Text Track." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.27241)]
[2026.03]

- Aviraj Bevli, Sofian Chaybouti, Yasser Dahou, Hakim Hacid, Ngoc Dung Huynh, Phuc H. Le Khac, Sanath Narayan, Wamiq Reyaz Para, Ankit Singh.<br />
"Falcon Perception." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.27365)]
[[code](https://github.com/tiiuae/Falcon-Perception)]
[2026.03]

- **FT-FSOD:** Xuanlong Yu, Youyang Sha, Longfei Liu, Xi Shen, Di Yang.<br />
"A Closer Look at Cross-Domain Few-Shot Object Detection: Fine-Tuning Matters and Parallel Decoder Helps." CVPR (2026).
[[paper](https://arxiv.org/abs/2603.28182)]
[[code](https://github.com/Intellindust-AI-Lab/FT-FSOD)]
[2026.03]
 
- **LIT:** Xinyu Yang, Haozheng Yu, Yihong Sun, Bharath Hariharan, Jennifer J. Sun.<br />
"Live Interactive Training for Video Segmentation." CVPR (2026).
[[paper](https://arxiv.org/abs/2603.26929)]
[[code](https://youngxinyu1802.github.io/projects/LIT/)]
[2026.03]

- Xinyao Zhang, Chang Liu, Xiao Liang, Minghui Zheng, Sara Behdad.<br />
"Evaluating Large and Lightweight Vision Models for Irregular Component Segmentation in E-Waste Disassembly." MSEC (2026).
[[paper](https://arxiv.org/abs/2603.27441)]
[2026.03]

- **Syn4Seg:** Guohuan Xie, Xin He, Dingying Fan, Le Zhang, Ming-Ming Cheng, Yun Liu.<br />
"Make It Up: Fake Images, Real Gains in Generalized Few-shot Semantic Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.27206)]
[2026.03]
 
- **IP-SAM:** Huiyao Zhang, Jin Bai, Rui Guo, JianWen Tan, HongFei Wang, Ye Li.<br />
"IP-SAM: Prompt-Space Conditioning for Prompt-Absent Camouflaged Object Detection." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.27250)]
[2026.03]

- **OpenDPR:** Qi Guo, Jue Wang, Yinhe Liu, Yanfei Zhong.<br />
"OpenDPR: Open-Vocabulary Change Detection via Vision-Centric Diffusion-Guided Prototype Retrieval for Remote Sensing Imagery." CVPR (2026).
[[paper](https://arxiv.org/abs/2603.27645)]
[[code](https://github.com/guoqi2002/OpenDPR)]
[2026.03]

- **Industrial3D:** Chao Yin, Hongzhe Yue, Qing Han, Difeng Hu, Zhenyu Liang, Fangzhou Lin, Bing Sun, Boyu Wang, Mingkai Li, Wei Yao, Jack C. P. Cheng.<br />
"Industrial3D: A Terrestrial LiDAR Point Cloud Dataset and CrossParadigm Benchmark for Industrial Infrastructure." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.28660)]
[[code](https://github.com/pointcloudyc/Industrial3D)]
[2026.03]

- **CFR-SAM:**  Jingze Su, Tianle Zhu, Jiaxin Cai, Zhiyi Wang, Qi Li, Xiao Zhang, Tong Tong, Shu Wang, Wenxi Liu.<br />
"Adapting SAM to Nuclei Instance Segmentation and Classification via Cooperative Fine-Grained Refinement." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.28027)]
[2026.03]
 
- **RAP:** Zhihao Mao, Bangpu Chen.<br />
"RAP: Retrieve, Adapt, and Prompt-Fit for Training-Free Few-Shot Medical Image Segmentation." IJCNN (2026).
[[paper](https://arxiv.org/abs/2603.27705)]
[2026.03]

- Samik Some, Vinay P. Namboodiri.<br />
"Can Unsupervised Segmentation Reduce Annotation Costs for Video Semantic Segmentation?." ICVGIP (2026).
[[paper](https://arxiv.org/abs/2603.27697)]
[2026.03]

- M. Fazri Nizar.<br />
"Domain-Guided YOLO26 with Composite BCE-Dice-Lovász Loss for Multi-Class Fetal Head Ultrasound Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.26755)]
[2026.03]

- **Mask-CDKD:** Daoyu Shu and Zhan Zhang and Xiao Huang and Ru Wang and Nan Jia and Xinzhe Fu and Bingnan Yang and Fang Wan and Jianzhong Lu and Jianya Gong.<br />
"Mask-CDKD: A source-free and label-free cross-domain knowledge distillation framework from SAM for satellite onboard VHR land-cover mapping." ISPRS Journal of Photogrammetry and Remote Sensing (2026).
[[paper](https://doi.org/10.1016/j.isprsjprs.2026.03.035)]
[[code](https://github.com/whujader/mask_cdkd)]
[2026.03]

- **Colon-Bench:** Abdullah Hamdi, Changchun Yang, Xin Gao.<br />
"Colon-Bench: An Agentic Workflow for Scalable Dense Lesion Annotation in Full-Procedure Colonoscopy Videos." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.25645)]
[[code](https://abdullahamdi.com/colon-bench)]
[2026.03]

- Nitin Kulkarni, Akhil Devarashetti, Charlie Cluss, Livio Forte, Philip Schneider, Chunming Qiao, Alina Vereshchaka.<br />
"Drive-Through 3D Vehicle Exterior Reconstruction via Dynamic-Scene SfM and Distortion-Aware Gaussian Splatting." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.26638)]
[2026.03]

- Guoping Xu, Jayaram K. Udupa, Yubing Tong, Xin Long, Ying Zhang, Jie Deng, Weiguo Lu, You Zhang.<br />
"Adapting Segment Anything Model 3 for Concept-Driven Lesion Segmentation inMedical Images: An Experimental Study." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.25945)]
[[code](https://github.com/apple1986/lesion-sam3)]
[2026.03]

- Sieradzki, Alexander, Kamil Koszela, Szymon Koszykowski, Jakub Bednarek, and Jarosław Kurek.<br />
"Zero-Shot Vertebral Instance Segmentation on DICOM Spine Radiographs Using Promptable Segment Anything Models." Journal of Clinical Medicine (2026).
[[paper](https://www.mdpi.com/2077-0383/15/5/2042)]
[2026.03]

- **SemiBUVS:** Long Chen and Qingqing Zheng and Yingying Chen and Faqin Lv and Qiong Wang.<br />
"SAM-Guided Semi-Supervised Breast Lesion Segmentation in Ultrasound Videos with A New Dataset." ESWA (2026).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S0957417426010547)]
[[code](https://github.com/003GH/SemiBUVS)]
[2026.03]

- **GridVAD:** Mohamed Eltahir, Ahmed O. Ibrahim, Obada Siralkhatim, Tabarak Abdallah, Sondos Mohamed.<br />
"GridVAD: Open-Set Video Anomaly Detection via Spatial Reasoning over Stratified Frame Grids." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.25467)]
[[code](https://gridvad.github.io/)]
[2026.03]

- **XAI-SAM:** Abu Noman Md Sakib, Merjulah Roby, Zijie Zhang, Satish Muluk, Mark K. Eskandari, Ender A. Finol.<br />
"Dissecting Model Failures in Abdominal Aortic Aneurysm Segmentation through Explainability-Driven Analysis." CVPR (2026).
[[paper](https://arxiv.org/abs/2603.24801)]
[2026.03]

- **ET-SAM:** Xike Zhang, Maoyuan Ye, Juhua Liu, Bo Du.<br />
"ET-SAM: Efficient Point Prompt Prediction in SAM for Unified Scene Text Detection and Layout Analysis." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.25168)]
[2026.03]

- **UW-VOS:** Hongshen Zhao, Jingkang Tai, Yuhang Wu, Wenkang Zhang, Xi Lan, Shangyan Wang, Tianyu Zhang, Wankou Yang.<br />
"UW-VOS: A Large-Scale Dataset for Underwater Video Object Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.24006)]
[2026.03]

- Mingqi Gao, Sijie Li, Jungong Han.<br />
"Re-Prompting SAM 3 via Object Retrieval: 3rd of the 5th PVUW MOSE Track." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.23788)]
[2026.03]

- **AgentRVOS:** Woojeong Jin, Jaeho Lee, Heeseong Shin, Seungho Jang, Junhwan Heo, Seungryong Kim.<br />
"AgentRVOS: Reasoning over Object Tracks for Zero-Shot Referring Video Object Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.23489)]
[[code](https://cvlab-kaist.github.io/AgentRVOS/)]
[2026.03]

- **FCL-COD:** Jingchen Ni, Quan Zhang, Dan Jiang, Keyu Lv, Ke Zhang, Chun Yuan.<br />
"FCL-COD: Weakly Supervised Camouflaged Object Detection with Frequency-aware and Contrastive Learning." CVPR (2026).
[[paper](https://arxiv.org/abs/2603.22969)]
[2026.03]

- Miquel Lopez Escoriza, Pau Amargant Alvarez.<br />
"Automatic Segmentation of 3D CT scans with SAM2 using a zero-shot approach." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.23116)]
[2026.03]

- **VIRST-Audio:** Jihwan Hong, Jaeyoung Do.<br />
"3rd Place of MeViS-Audio Track of the 5th PVUW: VIRST-Audio." CVPR workshop (2026).
[[paper](https://arxiv.org/abs/2603.23126)]
[[code](https://github.com/AIDASLab/VIRST/tree/virst-audio)]
[2026.03]

- **FoB:** Yuntian Bo, Yazhou Zhu, Piotr Koniusz, Haofeng Zhang.<br />
"Focus on Background: Exploring SAM's Potential in Few-shot Medical Image Segmentation with Background-centric Prompting." CVPR (2026).
[[paper](https://arxiv.org/abs/2603.21287)]
[[code](https://github.com/primebo1/FoB_SAM)]
[2026.03]

- **CataractSAM-2:** Mohammad Eslami, Dhanvinkumar Ganeshkumar, Saber Kazeminasab, Michael G. Morley, Michael V. Boland, Michael M. Lin, John B. Miller, David S. Friedman, Nazlee Zebardast, Lucia Sobrin, Tobias Elze.<br />
"CataractSAM-2: A Domain-Adapted Model for Anterior Segment Surgery Segmentation and Scalable Ground-Truth Annotation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.21566)]
[2026.03]

- Lei Huang, Kai-Li Wang, Zhang Chen, Zhen-Huang, Saidjafar Murodzoda, Xin Chen, Jing Chen, Chun-Hao Chen, Yu Xia, Yu-Tong Yang, Jia-Cheng Li, Dilshod Nematov, Ilhan Yavuz, Zhao-Kui Wang.<br />
"SAM Molecular Stacking with Heterogeneous Orientationfor High-Performance Perovskite Photovoltaics." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.21657)]
[2026.03]
 
- Thomas Mendelson, Joshua Francois, Galit Lahav, Tammy Riklin-Raviv.<br />
"Boundary-Aware Instance Segmentation in Microscopy Imaging." ISBI (2026).
[[paper](https://arxiv.org/abs/2603.21206)]
[2026.03]

- Muhammad Hassan Maqsood, Yanming Zhu, Alfred Lam, Getamesay Dagnaw, Xuefei Yin, Alan Wee-Chung Liew.<br />
"Prompt-Free Lightweight SAM Adaptation for Histopathology Nuclei Segmentation with Strong Cross-Dataset Generalization." ISBI (2026).
[[paper](https://arxiv.org/abs/2603.20326)]
[2026.03]

- Carolin Teuber, Anwai Archit, Tobias Boothe, Peter Ditte, Jochen Rink, Constantin Pape.<br />
"Evaluating Vision Foundation Models for Pixel and Object Classification in Microscopy." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.19802)]
[2026.03]

- **Distillation-SAM:** Tang, Jiyang and Han, Hu and Shan, Shiguang and Chen, Xilin.<br />
"Distillation-SAM: Knowledge Distillation Based Auto-prompt Embedding Learning for Surgical Image Segmentation." TMI (2026).
[[paper](https://ieeexplore.ieee.org/document/11436118)]
[[code](ttps://github.com/tjy828/DistillSAM)]
[2026.03]
 
- **EventVCOD:** Zhang, H., Lyu, Y., Liu, H., Song, J., Yuan, D., & Yang, Y.<br />
"Towards Explainable Video Camouflaged Object Detection: SAM2 with Eventstream-Inspired Data." AAAI (2026).
[[paper](https://ojs.aaai.org/index.php/AAAI/article/view/38245)]
[[code](https://github.com/lyu-yx/EventVCOD)]
[2026.03]

- **GoalVLM:** MoniJesu James, Amir Atef Habel, Aleksey Fedoseev, Dzmitry Tsetserokou.<br />
"GoalVLM: VLM-driven Object Goal Navigation for Multi-Agent System." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.18210)]
[2026.03]
 
- **Perceptio:** Yuchen Li, Amanmeet Garg, Shalini Chaudhuri, Rui Zhao, Garin Kessler.<br />
"Perceptio: Perception Enhanced Vision Language Models via Spatial Token Generation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.18795)]
[2026.03]

- **SCISSR:** Haonan Ping, Jian Jiang, Cheng Yuan, Qizhen Sun, Lv Wu, Yutong Ban.<br />
"SCISSR: Scribble-Conditioned Interactive Surgical Segmentation and Refinement." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.18544)]
[2026.03]

- **LoGSAM:** Mohammad Robaitul Islam Bhuiyan, Sheethal Bhat, Melika Qahqaie, Tri-Thien Nguyen, Paula Andrea Pérez Toro, Tomas Arias Vergara, Andreas Maier.<br />
"LoGSAM: Parameter-Efficient Cross-Modal Grounding for MRI Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.17576)]
[[code](https://github.com/robayet002/LoGSAM)]
[2026.03]

- Anwai Archit, Constantin Pape.<br />
"Revisiting foundation models for cell instance segmentation." MIDL (2026).
[[paper](https://arxiv.org/abs/2603.17845)]
[2026.03]

- Diederick C. Niehorster, Marcus Nyström.<br />
"Eye image segmentation using visual and concept prompts with Segment Anything Model 3 (SAM3)." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.17715)]
[2026.03]

- Paulo Vitor Santana Silva, Arthur Ricardo Sousa Vitória, Diogo Fernandes Costa Silva, Arlindo Rodrigues Galvão Filho.<br />
"Attention Guidance through Video Script: A Case Study of Object Focusing on 360° VR Video Tours." SVR (2026).
[[paper](https://arxiv.org/abs/2603.16875)]
[2026.03]

- **EDP-SAM:** Jiyang Huang, Hongru Cheng, Wei Lin, Jia Wan, Antoni B. Chan.<br />
"Exclusivity-Guided Mask Learning for Semi-Supervised Crowd Instance Segmentation and Counting." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.16241)]
[2026.03]

- **MessyKitchens:** Junaid Ahmed Ansari, Ran Ding, Fabio Pizzati, Ivan Laptev.<br />
"MessyKitchens: Contact-rich object-level 3D scene reconstruction." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.16868)]
[[code](https://messykitchens.github.io/)]
[2026.03]

- **SAMSEM:** Christian Gehrmann, Jonas Ricker, Simon Damm, Deruo Cheng, Julian Speith, Yiqiong Shi, Asja Fischer, Christof Paar.<br />
"SAMSEM -- A Generic and Scalable Approach for IC Metal Line Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.16548)]
[2026.03]
 
- **BADSEG:** Guangsheng Zhang, Huan Tian, Leo Zhang, Tianqing Zhu, Ming Ding, Wanlei Zhou, Bo Liu.<br />
"Poisoning the Pixels: Revisiting Backdoor Attacks on Semantic Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.16405)]
[2026.03]

- Shuai Guo, Ao Guo, Junchao Zhao, Qi Chen, Yuxiang Qi, Zechuan Li, Dong Chen, Tianjia Shao, Mingliang Xu.<br />
"Direct Object-Level Reconstruction via Probabilistic Gaussian Splatting." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.14316)]
[2026.03]
 
- **Fast-SAM-3D-Body:** Timing Yang, Sicheng He, Hongyi Jing, Jiawei Yang, Zhijian Liu, Chuhang Zou, Yue Wang.<br />
"Fast SAM 3D Body: Accelerating SAM 3D Body for Real-Time Full-Body Human Mesh Recovery." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.15603)]
[[code](https://github.com/yangtiming/Fast-SAM-3D-Body)]
[2026.03]

- **EviATTA:** Jiayi Chen, Yasmeen George, Winston Chong, Jianfei Cai.<br />
"EviATTA: Evidential Active Test-Time Adaptation for Medical Segment Anything Models." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.14666)]
[2026.03]

- **StAR:** Seokju Yun, Dongheon Lee, Noori Bae, Jaesung Jun, Chanseul Cho, Youngmin Ro.<br />
"StAR: Segment Anything Reasoner." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.14382)]
[[code](https://github.com/ysj9909/StAR)]
[2026.03]
 
- **SAIF:** Ke Wu, Shiqi Chen, Yiheng Zhong, Hengxian Liu, Yingxue Su, Yifang Wang, Junhao Jin, Guangyu Ren.<br />
"SAIF: A Stability-Aware Inference Framework for Medical Image Segmentation with Segment Anything Model." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.13533)]
[[code](https://anonymous.4open.science/r/SAIF)]
[2026.03]

- **Colony Grounded SAM2:** Daan Korporaal, Patrick de Kruijf, Ralph H. G. M. Litjens, Bas H. M. van der Velden.<br />
"Colony Grounded SAM2: Zero-shot detection and segmentation of bacterial colonies using foundation models." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.13393)]
[2026.03]

- Elodie Germani, Krystel Nyangoh-Timoh, Pierre Jannin, John S H Baxter.<br />
"Disentangling Prompt Dependence to Evaluate Segmentation Reliability in Gynecological MRI." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.13369)]
[2026.03]

- Tomislav Medic, Liangliang Nan.<br />
"In-Field 3D Wheat Head Instance Segmentation From TLS Point Clouds Using Deep Learning
Without Manual Labels." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.14309)]
[2026.03]

- **SPARROW:** Mohamad Alansari, Naufal Suryanto, Divya Velayudhan, Sajid Javed, Naoufel Werghi, Muzammal Naseer.<br />
"SPARROW: Learning Spatial Precision and Temporal Referential Consistency in Pixel-Grounded Video MLLMs." CVPR  (2026).
[[paper](https://arxiv.org/abs/2603.12382)]
[[project](https://risys-lab.github.io/SPARROW)]
[[code](https://github.com/RISys-Lab/SPARROW)]
[2026.03]

- **SAP:** Lutao Jiang, Zidong Cao, Weikai Chen, Xu Zheng, Yuanhuiyi Lyu, Zhenyang Li, Zeyu HU, Yingda Yin, Keyang Luo, Runze Zhang, Kai Yan, Shengju Qian, Haidi Fan, Yifan Peng, Xin Wang, Hui Xiong, Ying-Cong Chen.<br />
"SAP: Segment Any 4K Panorama." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.12759)]
[[code]( https://lutao2021.github.io/SAP_Page/)]
[2026.03]
 
- **HFP-SAM:** Pingping Zhang, Tianyu Yan, Yuhao Wang, Yang Liu, Tongdan Tang, Yili Ma, Long Lv, Feng Tian, Weibing Sun, and Huchuan Lu.<br />
"HFP-SAM: Hierarchical Frequency Prompted SAM for Efficient Marine Animal Segmentation." TIP (2026).
[[paper](https://arxiv.org/abs/2603.12708)]
[[code](https://github.com/Drchip61/TIP-HFP-SAM)]
[2026.03]

- **SAM FTI-FDet:** Guodong Sun, Qihang Liang, Xingyu Pan, Moyun Liu, Yang Zhang.<br />
"Prompt-Driven Lightweight Foundation Model for Instance Segmentation-Based Fault Detection in Freight Trains." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.12624)]
[[code](https://github.com/MVME-HBUT/SAM_FTI-FDet.git)]
[2026.03]

- **GoalSwarm:** MoniJesu Wonders James, Amir Atef Habel, Aleksey Fedoseev, Dzmitry Tsetserokou.<br />
"GoalSwarm: Multi-UAV Semantic Coordination for Open-Vocabulary Object Navigation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.12908)]
[2026.03]

- **AutoSAM:** Li, Jiayuan and Wang, Zhen and Sun, Xiao and Xu, Nan and You, Zhuhong and Huang, Deshuang.<br />
"AutoSAM: Auto-Prompting Mamba-Based Vision Foundation Model for Multimodal Remote Sensing Semantic Segmentation." TGRS (2026).
[[paper](https://ieeexplore.ieee.org/document/11408892)]
[[code](https://github.com/NWPUFranklee/AutoSAM.git)]
[2026.03]
 
- **SAMCM-SR:** Junchao Wang et al.<br />
"SAMCM-SR: Applying SAM3 Under Data-Scarce Conditions for Cross-Modal Segmentation of Power Equipment Infrared Images with Super-Resolution Enhancement." Appl. Sci. (2026).
[[paper](https://www.mdpi.com/2076-3417/16/5/2351)]
[2026.03]

- **BloodCellSAM2:** Zhening Qiu.<br />
"Research and Analysis of Fine-tuning Techniques for Cell Image Segmentation Model Based on SAM2." ArXiv (2026).
[[paper](https://www.deanfrancis.press/ojs/index.php/te/article/view/1650)]
[2026.03]

- **PolySAM-Lite:** Umar Hasan, Muhammad Ali Nayeem.<br />
"PolySAM-Lite: Parameter-efficient adaptation of the Segment Anything Model for colorectal polyp segmentation." ArXiv (2026).
[[paper](https://www.researchsquare.com/article/rs-8662498/v1)]
[2026.03]
 
- **RT-SAM:** Khor, Hee Guan and Yang, Xin and Sun, Yihua and Huang, Sijuan and Wang, Yingni and Wang, Jie and Wang, Shaobin and Bai, Lu and Ma, Longfei and Liao, Hongen.<br />
"RT-SAM: Visual-Prompt Fusion and Uncertainty Enhancement for Nasopharyngeal Carcinoma Radiotherapy Target Delineation." JBHI (2026).
[[paper](https://ieeexplore.ieee.org/document/11419735)]
[2026.03]

- **CPOVIS,:** Zheng, Rongkun and Qi, Lu and Chen, Xi and Wang, Yi and Wang, Kun and Qiao, Yu and Zhao, Hengshuang.<br />
"Causal Prompts for Open-vocabulary Video Instance Segmentation." TPAMI (2026).
[[paper](https://ieeexplore.ieee.org/document/11419811)]
[2026.03]

- **USCount-Net:** Yu Wang et al.<br />
"Low-Annotation Apple Flower Counting: A Color-SAM Enhanced and Uncertainty-Guided Semi-Supervised Framework." Plant Phenomics (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S2643651526000270)]
[2026.03]

- Snehalraj Chugh, Dharmendra Singh Chaudhary, Subash Sigdel, Shubham Thapa, Lalit BC, Nishan Ghimire, Bipendra Basnyat, Nirmalya Roy.<br />
"Segment Anything but Farms: Comparing Segmentation Paradigms for Rural UAV Captured Ultra-High-Resolution Imagery." WACVW (2026).
[[paper](https://openaccess.thecvf.com/content/WACV2026W/GeoCV/papers/Chugh_Segment_Anything_but_Farms_Comparing_Segmentation_Paradigms_for_Rural_UAV_WACVW_2026_paper.pdf)]
[2026.03]

- Linzhu Li et al.<br />
"Classification of Densely Packed Sand Particles Using a Digital Camera and the Segment Anything Model (SAM)." Geo-Congress (2026).
[[paper](https://ascelibrary.org/doi/abs/10.1061/9780784486719.003)]
[2026.03]

- Zhipeng Chen et al.<br />
"Occlusion-Aware Visual Object Tracking with SAM2-Based Segmentation via Temporal Convolutional Networks and a Dual-Memory Bank." ArXiv (2026).
[[paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6350476)]
[2026.03]

- Minghui Xu et al.<br />
"Automated flame boundary segmentation from droplet combustion images using SAM2 with auto-prompt selection and RANSAC fitting." ArXiv (2026).
[[paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6353899)]
[2026.03]

- **OAMOT:** Guo, Wen and Wang, Tuo and Gao, Junyu and Zhang, Tianzhu and Xu, Changsheng.<br />
"Occlusion-Aware Multi-Object Tracking via Joint Diffusion Motion Prediction and Appearance Purification." TCSVT (2026).
[[paper](https://ieeexplore.ieee.org/document/11422937)]
[[code](https://github.com/wangtuo111/OAMOT)]
[2026.03]

- **SegTS:** Jinsong Li et al.<br />
"SegTS: Subseries-driven temporo-spatial learning with Segment Anything Model for crop segmentation in satellite image time series." Computers and Electronics in Agriculture (2026).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S0168169926002218)]
[2026.03]

- Yunhao Hu, Penglin Zou, rongguo yan, Xiyun Zeng and Qi Wang.<br />
"Exploration and Performance Analysis of Deep Learning Applications in Spermatic Vein Ultrasound Segmentation." ArXiv (2026).
[[paper](https://iopscience.iop.org/article/10.1088/2057-1976/ae4eed/meta)]
[2026.03]

- Txai Sibley et al.<br />
"Evaluating and enhancing Segment Anything Model transferability for microstructural image analysis in nuclear materials." Computational Materials Science (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S0927025626001394)]
[2026.03]

- **DIT-SAM:** Yuhan Ying et al.<br />
"DIT-SAM: Enhancing segment anything model for automatic medical image segmentation via dual-interactive tuning." Biomedical Signal Processing and Control (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S1746809426005963)]
[[code](https://github.com/yingyuhan/DIT-SAM)]
[2026.03]

- **SA-SAM:** Zhuowen Deng, Fangce Li, Shenglin Shan, Jianchang Feng.<br />
"SA-SAM: a scale-adaptative method for wildfire scene segmentation." MLAIA (2026).
[[paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/14134/1413420/SA-SAM--a-scale-adaptative-method-for-wildfire-scene/10.1117/12.3110816.short)]
[2026.03]

- Amirreza Fateh, et al.<br />
"Adapting SAM with a triple-prompt strategy for one-shot semantic segmentation." Neurocomputing (2026).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231226006983)]
[2026.03]

- **PicoSAM3:** Pietro Bonazzi, Nicola Farronato, Stefan Zihlmann, Haotong Qin, Michele Magno.<br />
"PicoSAM3: Real-Time In-Sensor Region-of-Interest Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.11917)]
[2026.03]

- **DART:** Mehmet Kerem Turkcan.<br />
"Detect Anything in Real Time: From Single-Prompt Segmentation to Multi-Class Detection." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.11441)]
[[code](https://github.com/mkturkcan/DART)]
[2026.03]

- **BALD-SAM:** Prithwijit Chowdhury, Mohit Prabhushankar, Ghassan AlRegib.<br />
"BALD-SAM: Disagreement-based Active Prompting in Interactive Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.10828)]
[2026.03]
 
- **OilSAM2:** Shuaiyu Chen, Ming Yin, Peng Ren, Chunbo Luo, Zeyu Fu.<br />
"OilSAM2: Memory-Augmented SAM2 for Scalable SAR Oil Spill Detection." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.10231)]
[[code](https://github.com/Chenshuaiyu1120/OILSAM2)]
[2026.03]

- **SAMONAI:** Muhammad Alberb, Jianan Chen, Hossam El-rewaidy, Paul Karanicolas, Arun Seth, Yutaka Amemiya, Anne Martel, Helen Cheung.<br />
"An Automated Radiomics Framework for Postoperative Survival Prediction in Colorectal Liver Metastases using Preoperative MRI." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.10216)]
[2026.03]

- **Cybo-Waiter:** Peng Ren, Haoyang Ge, Chuan Qi, Cong Huang, Hong Li, Jiang Zhao, Pei Chi, Kai Chen.<br />
"Cybo-Waiter: A Physical Agentic Framework for Humanoid Whole-Body Locomotion-Manipulation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.10675)]
[2026.03]

- Caroline Magg, Maaike A. ter Wee, Johannes G. G. Dobbe, Geert J. Streekstra, Leendert Blankevoort, Clara I. Sánchez, Hoel Kervadec.<br />
"Prompting with the human-touch: evaluating model-sensitivity of foundation models for musculoskeletal CT segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.10541)]
[[code](https://github.com/CarolineMagg/segmentation-FM-benchmark/)]
[2026.03]

- **VQ-SAM:** Bing Fan, Minghao Li, Hanzhi Zhang, Shaohua Dong, Naga Prudhvi Mareedu, Weishi Shi, Yunhe Feng, Yan Huang, Heng Fan.<br />
"Towards Visual Query Segmentation in the Wild." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.08898)]
[2026.03]

- **RPG-SAM:** Weikun Lin, Yunhao Bai, Yan Wang.<br />
"RPG-SAM: Reliability-Weighted Prototypes and Geometric Adaptive Threshold Selection for Training-Free One-Shot Polyp Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.07436)]
[2026.03]

- Haoran Ding, Liang Ma, Yaxun Yang, Wen Yang, Tianyu Liu, Anqing Duan, Xiaodan Liang, Dezhen Song, Ivan Laptev, Yoshihiko Nakamura.<br />
"Choose What to Observe: Task-Aware Semantic-Geometric Representations for Visuomotor Policy." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.07875)]
[2026.03]

- **StructSAM:** Duy M. H. Nguyen, Tuan A. Tran, Duong Nguyen, Siwei Xie, Trung Q. Nguyen, Mai T. N. Truong, Daniel Palenicek, An T. Le, Michael Barz, TrungTin Nguyen, Tuan Dam, Ngan Le, Minh Vu, Khoa Doan, Vien Ngo, Pengtao Xie, James Zou, Daniel Sonntag, Jan Peters, Mathias Niepert.<br />
"StructSAM: Structure- and Spectrum-Preserving Token Merging for Segment Anything Models." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.07307)]
[2026.03]
 
- **OPTED:** Kibrom Gebremedhin, Hadush Hailu, Bruk Gebregziabher.<br />
"OPTED: Open Preprocessed Trachoma Eye Dataset Using Zero-Shot SAM 3 Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.06885)]
[2026.03]

- **VINE:** Hongli Liu, Yu Wang, Shengjie Zhao.<br />
"Unify the Views: View-Consistent Prototype Learning for Few-Shot Segmentation." CVPR (2026).
[[paper](https://arxiv.org/abs/2603.05952)]
[[code](https://github.com/HongliLiu1/VINE-main)]
[2026.03]

- **HCF-RES:** Keshen Zhou, Runnan Chen, Mingming Gong, Tongliang Liu.<br />
"Hierarchical Collaborative Fusion for 3D Instance-aware Referring Expression Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.06250)]
[2026.03]
 
- Yonghuang Wu, Zhenyang Liang, Wenwen Zeng, Xuan Xie, Jinhua Yu.<br />
"Prompt Group-Aware Training for Robust Text-Guided Nuclei Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.06384)]
[2026.03]

- Byeongseong Lee, Jihong Min.<br />
"Training-Free Target Emphasis with SAM2 Pseudo-Masks for Robust Single Object Tracking." WACV workshop (2026).
[[paper](https://openaccess.thecvf.com/content/WACV2026W/RWS/papers/Lee_Training-Free_Target_Emphasis_with_SAM2_Pseudo-Masks_for_Robust_Single_Object_WACVW_2026_paper.pdf)]
[2026.03]

- Akash Sharma, Pranjal Naman, Roopkatha Banerjee, Priyanshu Pansari, Sankalp Gawali, Mayank Arya, Sharath Chandra, Arun Josephraj, Rakshit Ramesh, Punit Rathore, Anirban Chakraborty, Raghu Krishnapuram, Vijay Kovvali, Yogesh Simmhan.<br />
"Scaling Real-Time Traffic Analytics on Edge-Cloud Fabrics for City-Scale Camera Networks." CCGRID Workshops (2026).
[[paper](https://arxiv.org/abs/2603.05217)]
[2026.03]

- Akif Islam, Raufun Nahar, Md. Ekramul Hamid.<br />
"When Denoising Hinders: Revisiting Zero-Shot ASR with SAM-Audio and Whisper." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.04710)]
[2026.03]

- **GarmentPile++:** Mingleyang Li, Yuran Wang, Yue Chen, Tianxing Chen, Jiaqi Liang, Zishun Shen, Haoran Lu, Ruihai Wu, Hao Dong.<br />
"GarmentPile++: Affordance-Driven Cluttered Garments Retrieval with Vision-Language Reasoning." ICRA (2026).
[[paper](https://arxiv.org/abs/2603.04158)]
[[code](https://garmentpile2.github.io/)]
[2026.03]

- **VANGUARD:** Yifei Chen, Xupeng Chen, Feng Wang, Niangang Jiao, Jiayin Liu.<br />
"VANGUARD: Vehicle-Anchored Ground Sample Distance Estimation for UAVs in GPS-Denied Environments." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.04277)]
[2026.03]

- **L2G-Det:** Qifan Zhang, Sai Haneesh Allu, Jikai Wang, Yangxiao Lu, Yu Xiang.<br />
"From Local Matches to Global Masks: Novel Instance Detection in Open-World Scenes." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.03577)]
[[code](https://irvlutd.github.io/L2G/)]
[2026.03]

- **SMART:** Yu Luo, Guangyu Wei, Yangfan Li, Jieyu He, Yueming Lyu.<br />
"Uncertainty-Aware Concept and Motion Segmentation for Semi-Supervised Angiography Videos." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.00881)]
[[code](https://github.com/qimingfan10/SMART)]
[2026.03]

- Carlos Monroy, Benjamin Navarro.<br />
"Leveraging GenAI for Segmenting and Labeling Centuries-old Technical Documents." IEEE-CH (2026).
[[paper](https://arxiv.org/abs/2603.00147)]
[2026.03]

- **STMI:** Xingguo Xu, Zhanyu Liu, Weixiang Zhou, Yuansheng Gao, Junjie Cao, Yuhao Wang, Jixiang Luo, Dell Zhang.<br />
"STMI: Segmentation-Guided Token Modulation with Cross-Modal Hypergraph Interaction for Multi-Modal Object Re-Identification." AAAI  (2026).
[[paper](https://arxiv.org/abs/2603.00695)]
[2026.03]

- Abhinav Munagala.<br />
"Zero-Shot and Supervised Bird Image Segmentation Using Foundation Models: A Dual-Pipeline Approach with Grounding DINO 1.5, YOLOv11, and SAM 2.1." ArXiv (2026).
[[paper](https://arxiv.org/abs/2603.00184)]
[[code](https://github.com/mvsakrishna/bird-segmentation-2025)]
[2026.03]

- **MFT:** Li, Guoqiang and Yuan, Hao and Chen, Suyang and Hu, Qi and Wang, Jun and Jiang, Kunming.<br />
"MFT: Memory-Aware Fine-Tuning of SAM2 for Efficient Long-Sequence Video Object Segmentation." IEEE SPL (2026).
[[paper](https://ieeexplore.ieee.org/document/11386858)]
[2026.03]

- **ReSeg-CLIP:** Mohammadreza Heidarianbaei, Mareike Dorozynski, Hubert Kanyamahanga, Max Mehltretter, Franz Rottensteiner.<br />
"Open-Vocabulary Semantic Segmentation in Remote Sensing via Hierarchical Attention Masking and Model Composition." BMVC Workshops (2026).
[[paper](https://arxiv.org/abs/2602.23869)]
[[code](https://github.com/aemrhb/ReSeg-CLIP)]
[2026.03]

- **SAM2-FNet:** Shaoli Li, Zihua Zhang, Dejian Li, Bin Liu, Luyao He, Siying Guo.<br />
"SAM2-FNet: Medical Image Lesion Segmentation Model Based on Frequency Domain Expert Fusion Network." IMA (2026).
[[paper](https://doi.org/10.1002/ima.70319)]
[[code](https://github.com/niubihonghong12345/SAM2-FNET)]
[2026.02]

- **SAM-Zero3D:** Zhang, Dejun and Xu, Shifeng and Bai, Yanzi and Wu, Yiqi and Liu, Jun.<br />
"SAM-Zero3D: Extending Segment Anything to Zero Shot 3D Scene Segmentation via Iterative Global–Local Interaction." TCSVT (2026).
[[paper](https://ieeexplore.ieee.org/document/11406142)]
[2026.02]

- **SAM2-ARAFNet:** Shi, W., Ding, J., Lei, J. et al.<br />
"SAM2-ARAFNet: adapting SAM2 with an attention-enhanced residual ASPP fusion network for high-resolution remote sensing semantic segmentation." Sci Rep(2026).
[[paper](https://www.nature.com/articles/s41598-026-38047-z)]
[2026.02]

- **TextureSAM:** Inbal Cohen, Boaz Meivar, Peihan Tu, Shai Avidan, Gal Oren.<br />
"Decoupling Shape and Texture in SAM-2 via Controlled Texture Replacement." WACV (2026).
[[paper](https://openaccess.thecvf.com/content/WACV2026/html/Cohen_Decoupling_Shape_and_Texture_in_SAM-2_via_Controlled_Texture_Replacement_WACV_2026_paper.html)]
[[code](https://github.com/Scientific-Computing-Lab/TextureSAM)]
[2026.02]

- **Interactive Medical-SAM2 GUI:** Woojae Hong, Jong Ha Hwang, Jiyong Chung, Joongyeon Choi, Hyunngun Kim, Yong Hwy Kim.<br />
"Interactive Medical-SAM2 GUI: A Napari-based semi-automatic annotation tool for medical images." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.22649)]
[[code](https://github.com/SKKU-IBE/Medical-SAM2GUI/)]
[2026.02]

- Katja Kossira, Yunxuan Zhu, Jürgen Seiler, André Kaup.<br />
"Towards Object Segmentation Mask Selection Using Specular Reflections." VCIP (2026).
[[paper](https://arxiv.org/abs/2602.21777)]
[2026.02]

- **L2RP:** Lokesha Rasanjalee, Jin Lin Tan, Dileepa Pitawela, Rajvinder Singh, Hsiang-Ting Chen.<br />
"Understanding Annotation Error Propagation and Learning an Adaptive Policy for Expert Intervention in Barrett's Video Segmentation." ISBI  (2026).
[[paper](https://arxiv.org/abs/2602.21855)]
[2026.02]

- Yida Lin, Bing Xue, Mengjie Zhang, Sam Schofield, Richard Green.<br />
"Progressive Per-Branch Depth Optimization for DEFOM-Stereo and SAM3 Joint Analysis in UAV Forestry Applications." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.20539)]
[2026.02]

- **CAD-Prompted SAM3:** Zhenran Tang, Rohan Nagabhirava, Changliu Liu.<br />
"CAD-Prompted SAM3: Geometry-Conditioned Instance Segmentation for Industrial Objects." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.20551)]
[2026.02]

- **YOLO–SAM2:** Shiyu Liu, Dylan Lester, Husnu Narman, Ammar Alzarrad, Pingping Zhu.<br />
"Depth-Enhanced YOLO-SAM2 Detection for Reliable Ballast Insufficiency Identification ." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.18961)]
[2026.02]
 
- **SMBlurDetect:** Ganesh Samarth, Sibendu Paul, Solale Tabarestani, Caren Chen .<br />
"Subtle Motion Blur Detection and Segmentation from Static Image Artworks." WACV (2026).
[[paper](https://arxiv.org/abs/2602.18720)]
[2026.02]

- **TactEx:** Felix Verstraete, Lan Wei, Wen Fan, Dandan Zhang.<br />
"TactEx: An Explainable Multimodal Robotic Interaction Framework for Human-Like Touch and Hardness Estimation." ICRA (2026).
[[paper](https://arxiv.org/abs/2602.18967)]
[2026.02]
 
- **SegMoTE:** Yujie Lu, Jingwen Li, Sibo Ju, Yanzhou Su, he yao, Yisong Liu, Min Zhu, Junlong Cheng.<br />
"SegMoTE: Token-Level Mixture of Experts for Medical Image Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.19213)]
[2026.02]

- **WOFTSAM:** Jonas Serych, Jiri Matas.<br />
"Accurate Planar Tracking With Robust Re-Detection." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.19624)]
[[code](https://github.com/serycjon/WOFTSAM)]
[2026.02]
 
- **DSS:** Yilong Yang, Jianxin Tian, Shengchuan Zhang, Liujuan Cao.<br />
"Discover, Segment, and Select: A Progressive Mechanism for Zero-shot Camouflaged Object Segmentation." CVPR (2026).
[[paper](https://arxiv.org/abs/2602.19944)]
[2026.02]

- **SegSEM:** Da Chen, Guangyu Hu, Kaihong Xu, Kaichao Liang, Songjiang Li, Wei Yang, XiangYu Wen, Mingxuan Yuan.<br />
"SegSEM: Enabling and Enhancing SAM2 for SEM Contour Extraction." ISCAS  (2026).
[[paper](https://arxiv.org/abs/2602.20471)]
[2026.02]
 
- **CL-MC:** Huayu Wang, Bahaa Alattar, Cheng-Yen Yang, Hsiang-Wei Huang, Jung Heon Kim, Linda Shapiro, Nathan White, Jenq-Neng Hwang.<br />
"Detector-in-the-Loop Tracking: Active Memory Rectification for Stable Glottic Opening Localization." MIDL (2026).
[[paper](https://arxiv.org/abs/2602.19380)]
[[code](https://github.com/huayuww/CL-MR)]
[2026.02]

- Hadi Shokati, et al.<br />
"Rapid flood mapping from aerial imagery using fine-tuned SAM and ResNet-backboned U-Net." Hydrology and Earth System Sciences (2026).
[[paper](https://hess.copernicus.org/articles/30/743/2026/)]
[2026.02]
 
- Lin, C., Yang, H., Wu, H. et al.<br />
"Horizontal nystagmus identification with joint SAM segmentation and time series classification." Eur Arch Otorhinolaryngol (2026).
[[paper](https://link.springer.com/article/10.1007/s00405-025-09950-4)]
[2026.02]

- **LDFSAM:** Xuanbo Zhao, et al.<br />
"LDFSAM: Localization Distillation-Enhanced Feature Prompting SAM for Medical Image Segmentation." Journal of Imaging (2026).
[[paper](https://www.mdpi.com/2313-433X/12/2/74)]
[2026.02]
 
- **DCS:** Yan Wan, Yingqi Lang, and Li Yao.<br />
"DCS: A Zero-Shot Anomaly Detection Framework with DINO-CLIP-SAM Integration." Applied Sciences (2026).
[[paper](https://www.mdpi.com/2076-3417/16/4/1836)]
[2026.02]

- **DAS-SAM:** Chen, Z., Zhou, N., Fan, Y. et al.<br />
"DAS-SAM: fine-tuning SAM towards drivable area segmentation via efficient multi-scale traffic scene-aware adaptation." Vis. Intell.(2026).
[[paper](https://link.springer.com/article/10.1007/s44267-026-00109-1)]
[2026.02]

- **SAM-IAD:** Yichi Chen, et al.<br />
"SAM-IAD: Injecting specific knowledge into SAM for industrial anomaly detection." KBS (2026).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705126002571)]
[2026.02]
 
- **SynSAM:** Krishnan, C., Onuoha, E., Hung, A. et al.<br />
"SynSAM: a hybrid synchronous learning framework with knowledge retention for prostate zonal segmentation leveraging the segment anything model." Med Biol Eng Comput (2026).
[[paper](https://link.springer.com/article/10.1007/s11517-026-03522-2)]
[2026.02]

- **HCCP-SAM2:** Rui Zhai, et al.<br />
"SAM2-driven dual-teacher framework using hierarchical cross-slice context for semi-supervised 3D medical image segmentation." Neurocomputing (2026).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231226005047)]
[2026.02]

- Yili Yang, et al.<br />
"Keeping pace with a changing planet: An interactive segmentation framework for refining delineations of dynamic Earth features with the Segment Anything Model." International Journal of Applied Earth Observation and Geoinformation (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S1569843226001032)]
[2026.02]
 
- **LG-SAM:** Chen Yi, et al.<br />
"Clinically oriented LG-SAM for lung CT tumor segmentation with 2D training achieving 3D-level performance." Biomedical Signal Processing and Control(2026).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S1746809426004751)]
[2026.02]

- **MUOT-3M:** Ahsan Baidar Bakht, Mohamad Alansari, Muhayy Ud Din, Muzammal Naseer, Sajid Javed, Irfan Hussain, Jiri Matas, Arif Mahmood.<br />
"MUOT-3M: A 3 Million Frame Multimodal Underwater Benchmark and the MUTrack Tracking Method ." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.18006)]
[[code](https://github.com/AhsanBaidar/MUOT-3M_Dataset)]
[2026.02]
 
- Jose Sosa, Danila Rukhovich, Anis Kacem, Djamila Aouada.<br />
"Enabling Training-Free Text-Based Remote Sensing Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.17799)]
[[code](https://github.com/josesosajs/trainfree-rs-segmentation)]
[2026.02]

- Phoenix Yu, Tilo Burghardt, Andrew W Dowsey, Neill W Campbell.<br />
"Automated Re-Identification of Holstein-Friesian Cattle in Dense Crowds." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.15962)]
[[code](https://phoenix4582.github.io/dazzlecows.github.io/)]
[2026.02]

- **TikArt:** Hao Ding, Zhichuan Yang, Weijie Ge, Ziqin Gao, Chaoyi Lu, Lei Zhao.<br />
"TikArt: Aperture-Guided Observation for Fine-Grained Visual Reasoning via Reinforcement Learning." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.14482)]
[2026.02]
 
- **SAM4Dcap:** Li Wang, HaoYu Wang, Xi Chen, ZeKun Jiang, Kang Li, Jian Li.<br />
"SAM4Dcap: Training-free Biomechanical Twin System from Monocular Video." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.13760)]
[[code](https://github.com/wanglihx/SAM4Dcap-core)]
[2026.02]

- **SAILS:** Shishir Muralidhara, Didier Stricker, René Schuster.<br />
"SAILS: Segment Anything with Incrementally Learned Semantics for Task-Invariant and Training-Free Continual Learning." IEEE CAI (2026).
[[paper](https://arxiv.org/abs/2602.14767)]
[2026.02]

- Julius Pesonen, Stefan Rua, Josef Taher, Niko Koivumäki, Xiaowei Yu, Eija Honkavaara.<br />
"Learning Image-based Tree Crown Segmentation from Enhanced Lidar-based Pseudo-labels." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.13022)]
[2026.02]

- **SAM3-LiteText:** Chengxi Zeng, Yuxuan Jiang, Ge Gao, Shuai Wang, Duolikun Danier, Bin Zhu, Stevan Rudinac, David Bull, Fan Zhang.<br />
"SAM3-LiteText: An Anatomical Study of the SAM3 Text Encoder for Efficient Vision-Language Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.12173)]
[[code](https://github.com/SimonZeng7108/efficientsam3/tree/sam3_litetext)]
[2026.02]

- **DBTANet:** Yun-Cheng Li, Sen Lei, Heng-Chao Li, Ke Li.<br />
"A Dual-Branch Framework for Semantic Change Detection with Boundary and Temporal Awareness." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.11466)]
[2026.02]

- **Hi-SAM:** Pingjun Pan, Tingting Zhou, Peiyao Lu, Tingting Fei, Hongxiang Chen, Chuanjiang Luo.<br />
"Hi-SAM: A Hierarchical Structure-Aware Multi-modal Framework for Large-Scale Recommendation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.11799)]
[2026.02]
 
- Yiming Zhou, Xuenjie Xie, Panfeng Li, Albrecht Kunz, Ahmad Osman, Xavier Maldague.<br />
"Efficient Segment Anything with Depth-Aware Fusion and Limited Training Data." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.11804)]
[2026.02]

- **Efficient-SAM2:** Jing Zhang, Zhikai Li, Xuewen Liu, Qingyi Gu.<br />
"Efficient-SAM2: Accelerating SAM2 with Object-Aware Visual Encoding and Memory Retrieval." ICLR (2026).
[[paper](https://arxiv.org/abs/2602.08224)]
[[code](https://github.com/jingjing0419/Efficient-SAM2)]
[2026.02]
 
- **RECITYGEN:** Di Mo, Mingyang Sun, Chengxiu Yin, Runjia Tian, Yanhong Wu, Liyan Xu.<br />
"RECITYGEN -- Interactive and Generative Participatory Urban Design Tool with Latent Diffusion and Segment Anything." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.07057)]
[[code](https://github.com/Myangsun/Streetview-app)]
[2026.02]

- Thomas H. Schmitt, Maximilian Bundscherer, Tobias Bocklet.<br />
"Learning to Detect Baked Goods with Limited Supervision." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.09979)]
[2026.02]

- **IR-SIS:** Ange Lou, Yamin Li, Qi Chang, Nan Xi, Luyuan Xie, Zichao Li, Tianyu Luan.<br />
"VLM-Guided Iterative Refinement for Surgical Image Segmentation with Foundation Models." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.09252)]
[2026.02]
 
- Yan Luo, Advaith Ravishankar, Serena Liu, Yutong Yang, Mengyu Wang.<br />
"Single-Slice-to-3D Reconstruction in Medical Imaging and Natural Objects: A Comparative Benchmark with SAM 3D." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.09407)]
[2026.02]

- **GenSeg-R1:** Sandesh Hegde, Jaison Saji Chacko, Debarshi Banerjee, Uma Mahesh.<br />
"GenSeg-R1: RL-Driven Vision-Language Grounding for Fine-Grained Referring Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.09701)]
[2026.02]

- **ConceptBank:** Gensheng Pei, Xiruo Jiang, Yazhou Yao, Xiangbo Shu, Fumin Shen, Byeungwoo Jeon.<br />
"Taming SAM3 in the Wild: A Concept Bank for Open-Vocabulary Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.06333)]
[[code](https://github.com/pgsmall/ConceptBank)]
[2026.02]

- **AdaptOVCD:** Mingyu Dou, Shi Qiu, Ming Hu, Yifan Chen, Huping Ye, Xiaohan Liao, Zhe Sun.<br />
"AdaptOVCD: Training-Free Open-Vocabulary Remote Sensing Change Detection via Adaptive Information Fusion." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.06529)]
[[code](https://github.com/Dmygithub/AdaptOVCD)]
[2026.02]
 
- **SPDA-SAM:** Yihan Shang, Wei Wang, Chao Huang, Xinghui Dong.<br />
"SPDA-SAM: A Self-prompted Depth-Aware Segment Anything Model for Instance Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.06335)]
[2026.02]

- **CPAC-SAM:** Juzheng Miao and Cheng Chen and Yuchen Yuan and Quanzheng Li and Pheng-Ann Heng.<br />
"SAM-Driven Cross Prompting with Adaptive Sampling Consistency for Semi-supervised Medical Image Segmentation." Medical Image Analysis(2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S1361841526000423)]
[[code](https://github.com/JuzhengMiao/CPAC-SAM)]
[2026.02]

- **SAMM:** Jiahao Tu, et al.<br />
"SAMM: A General-Purpose Segmentation Model for Material Micrographs Based on the Segment Anything Model 2." Advanced Powder Materials (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S2772834X26000126)]
[2026.02]

- **SAM2-PFF:** Henghao Sun, et al.<br />
"SAM2-PFF: Bridging SAM2 and Progressive Feature Fusion for Robust Indoor Salient Object Detection." ArXiv (2026).
[[paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6153643)]
[[code](https://github.com/fearless0721/SAM-PFF)]
[2026.02]

- **Semi-MedSAM:** Junhao Li, et al.<br />
"Semi-MedSAM: Adapting SAM-assisted semi-supervised multi-modality learning for medical endoscopic image segmentation." Pattern Recognition (2026).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320326001718)]
[2026.02]
 
- **SamFusion:** Yucheng Zhang, You Ma, Lin Chai.<br />
"SamFusion: A model for multimodal image fusion guided by SAM’s rich semantics." Infrared Physics & Technology (2026).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S1350449526000733)]
[2026.02]

- Takahashi, H., Kato, T., Yamashita, M. et al.<br />
"Floating object removal in underwater ROV video images using segment anything model and generative image in-painting." Artif Life Robotics (2026).
[[paper](https://link.springer.com/article/10.1007/s10015-025-01100-7)]
[2026.02]

- Binzagr, Faisal, and Majed Hariri.<br />
"Foundation-Model-Driven Skin Lesion Segmentation and Classification Using SAM-Adapters and Vision Transformers." Diagnostics (2026).
[[paper](https://www.mdpi.com/2075-4418/16/3/468)]
[2026.02]

- **StructSAM:** Liu, M., Yao, Y., Jia, J. et al.<br />
"StructSAM: structure-aware prompt adaptation for robust lung cancer lesion segmentation in CT." npj Digit. Med.(2026).
[[paper](https://www.nature.com/articles/s41746-025-02306-6)]
[2026.02]

- Raza, Tayyab and Ul Haq, Muhammad Arslan and Qanitah Naqvi, Syeda and Ramzan, Hafiz Arslan and Rehman, Abdul and Ramzan, Sadia.<br />
"Brain Tumor Segmentation and Classification Using Multi-Scale SAM and VGG16." ICoDT2 (2026).[[paper](https://ieeexplore.ieee.org/abstract/document/11360712)]
[2026.02]

- **Fast-SAM3D:** Weilun Feng, Mingqiang Wu, Zhiliang Chen, Chuanguang Yang, Haotong Qin, Yuqi Li, Xiaokun Liu, Guoxin Fan, Zhulin An, Libo Huang, Yulun Zhang, Michele Magno, Yongjun Xu.<br />
"Fast-SAM3D: 3Dfy Anything in Images but Faster." ICML (2026).
[[paper](https://arxiv.org/abs/2602.05293)]
[[code](https://github.com/wlfeng0509/Fast-SAM3D)]
[2026.02]

- **CPS:** Jiahao Nie, Yun Xing, Wenbin An, Qingsong Zhao, Jiawei Shao, Yap-Peng Tan, Alex C. Kot, Shijian Lu, Xuelong Li.<br />
"Boosting SAM for Cross-Domain Few-Shot Segmentation via Conditional Point Sparsification." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.05218)]
[2026.02]

- **AtlasPatch:** Ahmed Alagha, Christopher Leclerc, Yousef Kotp, Omar Metwally, Calvin Moras, Peter Rentopoulos, Ghodsiyeh Rostami, Bich Ngoc Nguyen, Jumanah Baig, Abdelhakim Khellaf, Vincent Quoc-Huy Trinh, Rabeb Mizouni, Hadi Otrok, Jamal Bentahar, Mahdi S. Hosseini.<br />
"AtlasPatch: An Efficient and Scalable Tool for Whole Slide Image Preprocessing in Computational Pathology." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.03998)]
[[code](https://github.com/AtlasAnalyticsLab/AtlasPatch)]
[2026.02]

- **FSOD-VFM:** Chen-Bin Feng, Youyang Sha, Longfei Liu, Yongjun Yu, Chi Man Vong, Xuanlong Yu, Xi Shen.<br />
"FSOD-VFM: Few-Shot Object Detection with Vision Foundation Models and Graph Diffusion." ICLR (2026).
[[paper](https://arxiv.org/abs/2602.03137)]
[[code](https://intellindust-ai-lab.github.io/projects/FSOD-VFM)]
[2026.02]

- **MedSAM-Agent:** Shengyuan Liu, Liuxin Bao, Qi Yang, Wanting Geng, Boyun Zheng, Chenxin Li, Wenting Chen, Houwen Peng, Yixuan Yuan.<br />
"MedSAM-Agent: Empowering Interactive Medical Image Segmentation with Multi-turn Agentic Reinforcement Learning." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.03320)]
[[code](https://github.com/CUHK-AIM-Group/MedSAM-Agent)]
[2026.02]

- **WATS-DA:** Ganggang Huang, Fasheng Wang, Binbin Wang, Hanwei Li, Mingshu Zhang, Mengyin Wang, Fuming Sun & Haojie Li.<br />
  "Wild Animal Tracking with High-Quality Segment Anything Model and Domain Adaptation." IJCV (2026).
  [[paper](https://link.springer.com/article/10.1007/s11263-025-02710-1)] 
  [[code](https://github.com/Hgg12/WATS-DA)]
  
- **S^3SPOT:** Lingsong Wang, Mancheng Meng, Ziyan Wu, Terrence Chen, Fan Yang, Dinggang Shen.<br />
"S^3POT: Contrast-Driven Face Occlusion Segmentation via Self-Supervised Prompt Learning." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.00635)]
[[code](https://github.com/Bh-Johnny/S3SPOT)]
[2026.02]

- **Mamba-SAM:** Mohammadreza Gholipour Shahraki, Mehdi Rezaeian, Mohammad Ghasemzadeh.<br />
"A Hybrid Mamba-SAM Architecture for Efficient 3D Medical Image Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.00650)]
[2026.02]
 
- **ZS-TreeSeg:** Pengyu Chen, Fangzheng Lyu, Sicheng Wang, Cuizhen Wang.<br />
"ZS-TreeSeg: A Zero-Shot Framework for Tree Crown Instance Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.00470)]
[2026.02]

- Penghao Deng, Jidong J. Yang, Jiachen Bian.<br />
"Cross-Paradigm Evaluation of Gaze-Based Semantic Object Identification for Intelligent Vehicles." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.01452)]
[2026.02]
 
- Samuel Church, Joshua D. Warner, Danyal Maqbool, Xin Tie, Junjie Hu, Meghan G. Lubner, Tyler J. Bradshaw.<br />
"Opportunistic Promptable Segmentation: Leveraging Routine Radiological Annotations to Guide 3D CT Lesion Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2602.00309)]
[2026.02]

- **SEAL:** Seungjun Lee, Gim Hee Lee.<br />
"Segment Any Events with Language." ICLR (2026).
[[paper](https://arxiv.org/abs/2601.23159)]
[[code](https://0nandon.github.io/SEAL)]
[2026.01]

- **OpenVTON-Bench:** Jin Li, Tao Chen, Shuai Jiang, Weijie Wang, Jingwen Luo, Chenhui Wu.<br />
"OpenVTON-Bench: A Large-Scale High-Resolution Benchmark for Controllable Virtual Try-On Evaluation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.22725)]
[2026.01]

- **Hive:** Kai Li, Jintao Cheng, Chang Zeng, Zijun Yan, Helin Wang, Zixiong Su, Bo Zheng, Xiaolin Hu.<br />
"A Semantically Consistent Dataset for Data-Efficient Query-Based Universal Sound Separation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.22599)]
[[code](https://shandaai.github.io/Hive)]
[2026.01]

- **RectiFine-SAM:** Lihong Qiao et al.<br />
"RectiFine-SAM: Feature Rectification and Boundary Refinement for Prompt-Free Medical Lesion Segmentation." ArXiv (2026).
[[paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6095770)]
[2026.01]

- Yung-Chen Cheng et al.<br />
"Automatic pore characterization in SEM images of foams using a fine-tuned segment anything model." Materials & Design (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S0264127526000997)]
[2026.01]

- **AerOSeg++:** Saikat Dutta et al.<br />
"AerOSeg++: Scale-Aware and Texture-Guided Open-Vocabulary Segmentation with SAM Features for Remote Sensing Images." ArXiv (2026).
[[paper](https://dl.acm.org/doi/abs/10.1145/3787522)]
[2026.01]
 
- **AutoPromptSeg:** Junan Zhu et al.<br />
"AutoPromptSeg: Automated Decoupling of Uncertainty Prompts with SAM for semi-supervised medical image segmentation." Computerized Medical Imaging and Graphics (2026).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S089561112600011X)]
[2026.01]
 
- **Scrap-SAM-CLIP:** Guangda Bao et al.<br />
"Scrap-SAM-CLIP: Assembling Foundation Models for Typical Shape Recognition in Scrap Classification and Rating." Sensors (2026).
[[paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC12846095/)]
[2026.01]

- **HL-SAM-Seg:** Xiong, Siting and Wu, Linfeng and Zhang, Bochen and Zhang, Dejin and Tao, Yu and Tang, Yuzhi.<br />
"HL-SAM-Seg: Complementary High- and Low-Resolution Features Based on SAM for Remote Sensing Image Semantic Segmentation." TGRS (2026).
[[paper](https://doi.org/10.1109/TGRS.2026.3655448)]
[2026.01]

- Guo, Pengyu and Jiang, Cuicui and Long, Chenrong and Hu, Qinglei and Li, Dongyu.<br />
"Noncooperative Spacecraft Pose Measurement Without Prior Knowledge Based on SAM2." TIM (2026).
[[paper](https://ieeexplore.ieee.org/document/11361374)]
[[code](https://github.com/pengyuguo1999/Spacecraft-Pose-Measurement-Without-Prior-Knowledge)]
[2026.01]
 
- **KTVFR:** Guoqing Zhang et al.<br />
"Advancing open-set object detection with SAM knowledge transfer and variational feature reconstruction." Neurocomputing (2026).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S092523122600175X)]
[2026.01]

- **PriorSAM-DBNet:** Zhang, Qiwei, Yisong Wang, Ning Li, Quanwen Jiang, and Yong He.<br />
"PriorSAM-DBNet: A SAM-Prior-Enhanced Dual-Branch Network for Efficient Semantic Segmentation of High-Resolution Remote Sensing Images." Sensors (2026).
[[paper](https://www.mdpi.com/1424-8220/26/2/749)]
[2026.01]

- Weiping M.A.<br />
"Study on salient object segmentation based on depth information guidance and SAM low-rank adaptation fine-tuning." ArXiv (2026).
[[paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0340765)]
[2026.01]

- **BLO-Inst:** Li Zhang, Pengtao Xie.<br />
"BLO-Inst: Bi-Level Optimization Based Alignment of YOLO and SAM for Robust Instance Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.22061)]
[[code](https://github.com/importZL/BLO-Inst)]
[2026.01]

- **DeepSeek-OCR 2:** Haoran Wei, Yaofeng Sun, Yukun Li.<br />
"DeepSeek-OCR 2: Visual Causal Flow." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.20552)]
[[code](http://github.com/deepseek-ai/DeepSeek-OCR-2)]
[2026.01]

- **SAJ:** Helin Wang, Bowen Shi, Andros Tjandra, John Hoffman, Yi-Chiao Wu, Apoorv Vyas, Najim Dehak, Ann Lee, Wei-Ning Hsu.<br />
"SAM Audio Judge: A Unified Multimodal Framework for Perceptual Evaluation of Audio Separation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.19702)]
[[code](https://github.com/facebookresearch/sam-audio)]
[2026.01]
 
- **DSTCS:** Yalin Luo, Shun Long, Huijin Wang, Jieyun Bai.<br />
"DSTCS: Dual-Student Teacher Framework with Segment Anything Model for Semi-Supervised Pubic Symphysis Fetal Head Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.19446)]
[2026.01]

- Puzhen Wu, Han Weng, Quan Zheng, Yi Zhan, Hewei Wang, Yiming Li, Jiahui Han, Rui Xu.<br />
"CLIP-Guided Unsupervised Semantic-Aware Exposure Correction." ICASSP (2026).
[[paper](https://arxiv.org/abs/2601.19129)]
[2026.01]

- Zeineb Dridi, Jihen Bennaceur, Amine Ben Hassouna.<br />
"Dynamic Mask-Based Backdoor Attack Against Vision AI Models: A Case Study on Mushroom Detection." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.18845)]
[2026.01]

- **C-RADIOv4:** Mike Ranzinger, Greg Heinrich, Collin McCarthy, Jan Kautz, Andrew Tao, Bryan Catanzaro, Pavlo Molchanov.<br />
"C-RADIOv4 (Tech Report)." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.17237)]
[[code](https://github.com/NVlabs/RADIO)]
[2026.01]

- **StealthMark:** Qinkai Yu, Chong Zhang, Gaojie Jin, Tianjin Huang, Wei Zhou, Wenhui Li, Xiaobo Jin, Bo Huang, Yitian Zhao, Guang Yang, Gregory Y. H. Lip, Yalin Zheng, Aline Villavicencio, Yanda Meng.<br />
"StealthMark: Harmless and Stealthy Ownership Verification for Medical Segmentation via Uncertainty-Guided Backdoors." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.17107)]
[[code](https://github.com/Qinkaiyu/StealthMark)]
[2026.01]

- Rabin Dulal, Wenfeng Jia, Lihong Zheng, Jane Quinn.<br />
"Agreement-Driven Multi-View 3D Reconstruction for Live Cattle Weight Estimation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.17791)]
[2026.01]
 
- **SC-SAM:** Vi Vu, Thanh-Huy Nguyen, Tien-Thinh Nguyen, Ba-Thinh Lam, Hoang-Thien Nguyen, Tianyang Wang, Xingjian Li, Min Xu.<br />
"From Specialist to Generalist: Unlocking SAM's Learning Potential on Unlabeled Medical Images." ISBI (2026).
[[paper](https://arxiv.org/abs/2601.17934)]
[[code](https://github.com/vnlvi2k3/SC-SAM)]
[2026.01]

- **MV-SAM:** Yoonwoo Jeong, Cheng Sun, Yu-Chiang Frank Wang, Minsu Cho, Jaesung Choe.<br />
"MV-SAM: Multi-view Promptable Segmentation using Pointmap Guidance." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.17866)]
[[code](https://jaesung-choe.github.io/mv_sam/index.html)]
[2026.01]
 
- Takato Yasuno.<br />
"Multi-stage Bridge Inspection System: Integrating Foundation Models with Location Anonymization." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.17254)]
[2026.01]

- **MPS-CLIP:** Yifan Li, Shiying Wang, Jianqiang Huang.<br />
"Multi-Perspective Subimage CLIP with Keyword Guidance for Remote Sensing Image-Text Retrieval." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.18190)]
[[code](https://github.com/Lcrucial1f/MPS-CLIP)]
[2026.01]

- **AutoPromptSeg:** Junan Zhu, Zhizhe Tang, Ping Ma, Zheng Liang, Chuanjian Wang.<br />
"AutoPromptSeg: Automated Decoupling of Uncertainty Prompts with SAM for semi-supervised medical image segmentation." Computerized Medical Imaging and Graphics (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S089561112600011X)]
[2026.01]

- **AM-SAM:** Li, Y., Zhang, L., Liang, Y. et al.<br />
"Am-sam: a spatially-aware prompt learning and mask calibration framework for few-shot semantic segmentation." International Journal of Machine Learning and Cybernetics (2026).
[[paper](https://link.springer.com/article/10.1007/s13042-025-02911-7)]
[[code](https://github.com/aierwaixi/AM-SAM)]
[2026.01]
 
- Huanyu Li, Li Li, Hao Wang, Weibo Zhang & Peng Ren.<br />
"Large Foundation Model Empowered Region-aware Underwater Image Captioning." IJCV (2026).
[[paper](https://link.springer.com/article/10.1007/s11263-025-02650-w)]
[2026.01]

- **SAMTok:** Yikang Zhou, Tao Zhang, Dengxian Gong, Yuanzheng Wu, Ye Tian, Haochen Wang, Haobo Yuan, Jiacong Wang, Lu Qi, Hao Fei, Anran Wang, Zhuochen Wang, Yujing Wang, Cheng Chen, Shunping Ji, Xiangtai Li.<br />
"SAMTok: Representing Any Mask with Two Words." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.16093)]
[[code](https://zhouyiks.github.io/projects/SAMTok/)]
[2026.01]
 
- **FeTal-SAM:** Qi Zeng, Weide Liu, Bo Li, Ryne Didier, P. Ellen Grant, Davood Karimi.<br />
"Atlas-Assisted Segment Anything Model for Fetal Brain MRI (FeTal-SAM)." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.15759)]
[2026.01]

- **BREPS:** Andrey Moskalenko, Danil Kuznetsov, Irina Dudko, Anastasiia Iasakova, Nikita Boldyrev, Denis Shepelev, Andrei Spiridonov, Andrey Kuznetsov, Vlad Shakhuro.<br />
"BREPS: Bounding-Box Robustness Evaluation of Promptable Segmentation." AAAI (2026).
[[paper](https://arxiv.org/abs/2601.15123)]
[[code](https://github.com/emb-ai/BREPS)]
[2026.01]
 
- **BBoxMaskPose v2:** Miroslav Purkrabek, Constantin Kolomiiets, Jiri Matas.<br />
"BBoxMaskPose v2: Expanding Mutual Conditioning to 3D." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.15200)]
[[code](https://mirapurkrabek.github.io/BBox-Mask-Pose/)]
[2026.01]

- **OmniOVCD:** Xu Zhang, Danyang Li, Yingjie Xia, Xiaohang Dong, Hualong Yu, Jianye Wang, Qicheng Li.<br />
"OmniOVCD: Streamlining Open-Vocabulary Change Detection with SAM 3." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.13895)]
[2026.01]

- **OCCAM:** Michail Spanakis, Iason Oikonomidis, Antonis Argyros.<br />
"OCCAM: Class-Agnostic, Training-Free, Prior-Free and Multi-Class Object Counting." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.13871)]
[[code](https://mikespanak.github.io/OCCAM_counter)]
[2026.01]
 
- **DepthCropSeg++:** Jiafei Zhang, Songliang Cao, Binghui Xu, Yanan Li, Weiwei Jia, Tingting Wu, Hao Lu, Weijuan Hu, Zhiguo Han.<br />
"DepthCropSeg++: Scaling a Crop Segmentation Foundation Model With Depth-Labeled Data." IEEE Journal of Selected Topics in Signal Processing (2026).
[[paper](https://arxiv.org/abs/2601.12366)]
[2026.01]
 
- **SynthFM-3D:** Satrajit Chakrabarty, Sourya Sengupta, Gopal Avinash, Ravi Soni.<br />
"Synthetic Volumetric Data Generation Enables Zero-Shot Generalization of Foundation Models in 3D Medical Image Segmentation." ISBI (2026).
[[paper](https://arxiv.org/abs/2601.12297)]
[2026.01]
 
- **SAMA:** Zezhong Fan, Xiaohan Li, Topojoy Biswas, Kaushiki Nag, Kannan Achan.<br />
"Segment and Matte Anything in a Unified Model." AAAI (2026).
[[paper](https://arxiv.org/abs/2601.12147)]
[2026.01]

- **VideoMaMa:** Sangbeom Lim, Seoung Wug Oh, Jiahui Huang, Heeji Yoon, Seungryong Kim, Joon-Young Lee.<br />
"VideoMaMa: Mask-Guided Video Matting via Generative Prior." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.14255)]
[[code](https://cvlab-kaist.github.io/VideoMaMa)]
[2026.01]
 
- **MQC-SAM:** H. Jiang, Y. Sun, Z. Dong, T. Liu, Y. Gu.<br />
"CroBIM-V: Memory-Quality Controlled Remote Sensing Referring Video Object Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.12076)]
[2026.01]

- **3D LPA:** Yanrui Lu, Danyang Chen, Haowen Xiao, Jiarui Zhu, Fukang Ge, Binqian Zou, Jiali Guan, Jiayin Liang, Yuting Wang, Ziqian Guan, Xiangcheng Bao, Jinhao Bi, Lin Gu, Jun He, Yingying Zhu.<br />
"Large-scale EM Benchmark for Multi-Organelle Instance Segmentation in the Wild." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.12464)]
[2026.01]
 
- Raffaele Mazza, Ciro Natale, Pietro Falco.<br />
"Active Cross-Modal Visuo-Tactile Perception of Deformable Linear Objects." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.13979)]
[2026.01]

- **Medical SAM3:** Chongcong Jiang, Tianxingjian Ding, Chuhan Song, Jiachen Tu, Ziyang Yan, Yihua Shao, Zhenyi Wang, Yuzhang Shang, Tianyu Han, Yu Tian.<br />
"Medical SAM3: A Foundation Model for Universal Prompt-Driven Medical Image Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.10880)]
[[code](https://github.com/AIM-Research-Lab/Medical-SAM3)]
[2026.01]

- **PRISM-CAFO:** Oishee Bintey Hoque, Nibir Chandra Mandal, Kyle Luong, Amanda Wilson, Samarth Swarup, Madhav Marathe, Abhijin Adiga.<br />
"PRISM-CAFO: Prior-conditioned Remote-sensing Infrastructure Segmentation and Mapping for CAFOs." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.11451)]
[[code](https://github.com/Nibir088/PRISM-CAFO)]
[2026.01]
 
- **WetSAM:** Shuai Yuan, Tianwu Lin, Shuang Chen, Yu Xia, Peng Qin, Xiangyu Liu, Xiaoqing Xu, Nan Xu, Hongsheng Zhang, Jie Wang, Peng Gong.<br />
"Wetland mapping from sparse annotations with satellite image time series and temporal-aware segment anything model." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.11400)]
[2026.01]
 
- **SAMannot:** Gergely Dinya, András Gelencsér, Krisztina Kupán, Clemens Küpper, Kristóf Karacs, Anna Gelencsér-Horváth.<br />
"SAMannot: A Memory-Efficient, Local, Open-source Framework for Interactive Video Instance Segmentation based on SAM2." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.11301)]
[2026.01]

- **VMPicker:** Bo Zhu et al.<br />
"VMPicker: A novel cryo-EM particle picker leveraging vision mamba and the segment anything model." Micron (2026).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S0968432826000090)]
[2026.01]

- Jiuyi Zhang, Jiaqi Ji, Sijia Feng, Huiying Ru.<br />
"3D Gaussian-Driven SAM2 Repair Method]{3D Gaussian-Driven SAM2 Multi-View Fusion Detection and Triple-Constrained Symmetry Plane Generation Repair Method." ArXiv (2026).
[[paper](https://www.researchsquare.com/article/rs-8451382/v1)]
[2026.01]

- **FILFArch:** Huang, Junqing and Ji, Shucheng and Wang, Yapeng and Xia, Min and Yuan, Xiaochen.<br />
"An SAM Fine-Tuning Framework With Frequency-Domain Interactive LoRA for Remote Sensing Change Detection." TGRS (2026).
[[paper](https://ieeexplore.ieee.org/document/11329007)]
[[code](https://github.com/juncyan/filora)]
[2026.01]
 
- Miao Liu et al.<br />
"Settlements Extraction and Spatiotemporal Analysis with SAM and Random Forest from High-Resolution Remote Sensing." Agriculture Communications (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S2949798126000013)]
[2026.01]
 
- **PMG-SAM:** Gao, Jixue, Xiaoyan Jiang, Anjie Wang, Yongbin Gao, Zhijun Fang, and Michael S. Lew.<br />
"PMG-SAM: Boosting Auto-Segmentation of SAM with Pre-Mask Guidance." Sensors (2026).
[[paper](https://www.mdpi.com/1424-8220/26/2/365)]
[2026.01]
 
- **TextSAM:** Xiang, Y., Xian, Y., Cairang, X. et al.<br />
"Handwritten text line segmentation with TextSAM: An enhanced segment anything model via multi-module fusion." IJDAR (2026).
[[paper](https://link.springer.com/article/10.1007/s10032-025-00567-1)]
[2026.01]

- Deboch Eyob Abera et al.<br />
"Automated prompt-guided multi-modality cell segmentation with shape-aware classification and boundary-aware SAM adaptation." Displays (2026).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S0141938225003749)]
[[code](https://github.com/MIXAILAB/Multi_Modality_CellSeg)]
[2026.01]
 
- **DescriptorMedSAM:** Zhang, W., Luo, L., He, M. et al.<br />
"DescriptorMedSAM: language-image fusion with multi-aspect text guidance for medical image segmentation." Sci Rep (2026).
[[paper](https://www.nature.com/articles/s41598-025-33843-5)]
[[code](https://github.com/Wenj1eee/Prompt-Dimensions-of-MedSAM)]
[2026.01]
 
- **TA-MedSAM:** Siyuan Tang et al.<br />
"TA-MedSAM: Text-augmented improved MedSAM for pulmonary lesion segmentation." Computerized Medical Imaging and Graphics (2026).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S0895611126000017)]
[2026.01]

- **SAMURAI:** Yang, Cheng-Yeng and Huang, Hsiang-Wei and Jiang, Zhongyu and Chai, Wenhao and Hwang, Jenq-Neng.<br />
"SAMURAI: Motion-Aware Memory for Training-Free Visual Object Tracking with SAM 2." TIP (2026).
[[paper](https://ieeexplore.ieee.org/document/11351313)]
[[code](https://github.com/yangchris11/samurai)]
[2026.01]

- **MedVL-SAM2:** Yang Xing, Jiong Wu, Savas Ozdemir, Ying Zhang, Yang Yang, Wei Shao, Kuang Gong.<br />
"MedVL-SAM2: A unified 3D medical vision-language model for multimodal reasoning and prompt-driven segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.09879)]
[2026.01]

- **SAM-guided-RGB-D-COD:** Dongdong Zhang and Chunping Wang and Qiang Fu and Yao Song.<br />
"SAM-guided Depth-aware Weakly Supervised Camouflaged Object Detection with Spatial-Frequency Exploration." KBS (2026).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705126000687)]
[[code](https://github.com/zcc0616/SAM-guided-RGB-D-COD.git)]
[2026.01]

- **SAM3-DMS:** Ruiqi Shen, Chang Liu, Henghui Ding.<br />
"SAM3-DMS: Decoupled Memory Selection for Multi-target Video Segmentation of SAM3." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.09699)]
[[code](https://github.com/FudanCVL/SAM3-DMS)]
[2026.01]
 
- **BrainSegNet:** Yucheng Li, Xiaofan Wang, Junyi Wang, Yijie Li, Xi Zhu, Mubai Du, Dian Sheng, Wei Zhang, Fan Zhang.<br />
"BrainSegNet: A Novel Framework for Whole-Brain MRI Parcellation Enhanced by Large Models." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.09263)]
[2026.01]
 
- **SAM-Aug:** Kai Hu, Yaozu Feng, Vladimir Lysenko, Ya Guo Member, Huayi Wu.<br />
"SAM-Aug: Leveraging SAM Priors for Few-Shot Parcel Segmentation in Satellite Time Series." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.09110)]
[2026.01]

- **SAM-pose2seg:** Constantin Kolomiiets, Miroslav Purkrabek, Jiri Matas.<br />
"SAM-pose2seg: Pose-Guided Human Instance Segmentation in Crowds." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.08982)]
[[code](https://github.com/MiraPurkrabek/BBoxMaskPose/)]
[2026.01]

- **3AM:** Yang-Che Sun, Cheng Sun, Chin-Yang Lin, Fu-En Yang, Min-Hung Chen, Yen-Yu Lin, Yu-Lun Liu.<br />
"3AM: Segment Anything with Geometric Consistency in Videos." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.08831)]
[[code](https://jayisaking.github.io/3AM-Page/)]
[2026.01]
 
- Sunusi Ibrahim Muhammad, Ismail Ismail Tijjani, Saadatu Yusuf Jumare, Fatima Isah Jibrin.<br />
"Sesame Plant Segmentation Dataset: A YOLO Formatted Annotated Dataset." ICCAIT (2026).
[[paper](https://arxiv.org/abs/2601.07970)]
[[code](https://www.kaggle.com/datasets/ismailismailtijjani/sesame-plant-detection-dataset)]
[2026.01]

- **SAM-RefiSeR:** Dillan Imans, Phuoc-Nguyen Bui, Duc-Tai Le, Hyunseung Choo.<br />
"Unsupervised Domain Adaptation with SAM-RefiSeR for Enhanced Brain Tumor Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.06882)]
[2026.01]
 
- **PanoSAMic:** Mahdi Chamseddine, Didier Stricker, Jason Rambach.<br />
"PanoSAMic: Panoramic Image Segmentation from SAM Feature Encoding and Dual View Fusion." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.07447)]
[[code](https://github.com/dfki-av/PanoSAMic)]
[2026.01]

- Aizierjiang Aiersilan, Ruting Cheng, James Hahn.<br />
"Investigating Anthropometric Fidelity in SAM 3D Body." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.06035)]
[2026.01]

- Sanjay Pradeep, Chen Wang, Matthew M. Dahm, Jeff D. Eldredge, Candace S. J. Tsai.<br />
"Quantification and Classification of Carbon Nanotubes in Electron Micrographs using Vision Foundation Models." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.06673)]
[2026.01]

- **WaveRNet:** Chanchan Wang, Yuanfang Wang, Qing Xu, Guanxin Chen.<br />
"WaveRNet: Wavelet-Guided Frequency Learning for Multi-Source Domain-Generalized Retinal Vessel Segmentation." ESWA (2026).
[[paper](https://arxiv.org/abs/2601.05942)]
[[code](https://github.com/Chanchan-Wang/WaveRNet)]
[2026.01]

- **Prompt-Free SAM:** Samuel E. Johnny, Bernes L. Atabonfack, Israel Alagbe, Assane Gueye.<br />
"Prompt-Free SAM-Based Multi-Task Framework for Breast Ultrasound Lesion Segmentation and Classification." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.05498)]
[2026.01]

- **SSP-SAM:** Tang, Wei and Liu, Xuejing and Sun, Yanpeng and Li, Zechao.<br />
"SSP-SAM: SAM with Semantic-Spatial Prompt for Referring Expression Segmentation." TCSVT (2026).
[[paper](https://ieeexplore.ieee.org/abstract/document/11299097)]
[[code](https://github.com/WayneTomas/SSP-SAM)]
[2026.01]

- **DivAS:** Ayush Pande.<br />
"DivAS: Interactive 3D Segmentation of NeRFs via Depth-Weighted Voxel Aggregation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.04860)]
[2026.01]

- **Detector-Augmented SAMURAI:** Tamara R. Lenhard, Andreas Weinmann, Hichem Snoussi, Tobias Koch.<br />
"Detector-Augmented SAMURAI for Long-Duration Drone Tracking." WACV Workshop (2026).
[[paper](https://arxiv.org/abs/2601.04798)]
[2026.01]

- **HyperCOD & HSC-SAM:** Shuyan Bai, Tingfa Xu, Peifu Liu, Yuhao Qiu, Huiyan Bai, Huan Chen, Yanyan Peng, Jianan Li.<br />
"HyperCOD: The First Challenging Benchmark and Baseline for Hyperspectral Camouflaged Object Detection." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.03736)]
[[code](https://github.com/Baishuyanyan/HyperCOD)]
[2026.01]

- **SemiBCP-SAM2:** Guangqi Yang et al.<br />
"SemiBCP-SAM2: Semi-supervised model via enhanced bidirectional copy-paste based on SAM2 for medical image segmentation." Information Processing & Management (2026).
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S0306457325005175)]
[[code](https://github.com/ydlam/SemiBCP-SAM2)]
[2026.01]
 
- **SAMOIS:** Bing He et al.<br />
"SAMOIS: efficient fine-tuned SAM with multi-scale enhancement for optical remote sensing image segmentation." European Journal of Remote Sensing (2026).
[[paper](https://doi.org/10.1080/22797254.2025.2609404)]
[2026.01]
 
- **LoGoSAM:** Khang Ta Gia, Quan Nguyen Dinh, Giang Kang Dong & Tho Quan Thanh.<br />
"LoGoSAM: Enhancing Prototypical Networks for Medical Image One-Shot Segmentation Using Local-Global Encoder Integration and Visual Prompting." ICTIS (2026).
[[paper](https://link.springer.com/chapter/10.1007/978-981-96-9191-3_40)]
[2026.01]
 
- **XSegTx-SAM2:** Devis Salierno et al.<br />
"Ego-Exo Object Correspondence bySAM2 and Cross-View Prompting." ICIAP (2026).
[[paper](https://link.springer.com/chapter/10.1007/978-3-032-10192-1_27)]
[2026.01]

- **E2SAM:** Ziyi Li, Yinghui Xing, Feng Sang, Shizhou Zhang, Lingyan Ran & Yanning Zhang.<br />
"E2SAM: Edge-Enhanced SAM with FFC Adapter for Few-Shot Infrared Small Target Detection." JCRAI (2026).
[[paper](https://link.springer.com/chapter/10.1007/978-3-032-12757-0_9)]
[2026.01]
 
- Jiaxuan Wang et al.<br />
"Weakly Supervised Blue-Carbon Mapping of Reef Algae with SAM-Bootstrapped NnU-Net." ACIVS (2026).
[[paper](https://link.springer.com/chapter/10.1007/978-3-032-07343-3_38)]
[2026.01]
 
- Jieming Yu et al.<br />
"SAM 2 in Robotic Surgery: An Empirical Evaluation for Robustness and Generalization in Surgical Video Segmentation." EMA4MICCAI (2026).
[[paper](https://link.springer.com/chapter/10.1007/978-3-032-13961-0_18)]
[2026.01]
 
- **EvSAM:** Yi Ding, Bowen Yao, Yuhan Liu, Hao Chen, Ding Ding, Zhen Yang, Youfu Li, Yongjian Deng.<br />
"EvSAM: Segment Anything Model with Event-based Assistance." ACM Trans. Multimedia Comput. Commun. Appl. (2026).
[[paper](https://doi.org/10.1145/3786794)]
[2026.01]

- Fatih Fehmi Şimşek, Melih Altay.<br />
"Phenology aware agricultural boundary extraction using segment anything model and planet scope imagery (zero shot learning approach)." Advances in Space Research (2026).
[[paper](https://www.sciencedirect.com/science/article/pii/S0273117725015297)]
[2026.01]
 
- Yangxin Liu, De Li, and Xun Jin.<br />
"Research on game object segmentation method based on SAM." ICEEIE (2026).
[[paper](https://doi.org/10.1117/12.3093078)]
[2026.01]

- **DGA-Net:** Yuetong Li, Qing Zhang, Yilin Zhao, Gongyang Li, Zeming Liu.<br />
"DGA-Net: Enhancing SAM with Depth Prompting and Graph-Anchor Guidance for Camouflaged Object Detection." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.02831)]
[2026.01]

- Longzhen Li, Guang Li, Ren Togo, Keisuke Maeda, Takahiro Ogawa, Miki Haseyama.<br />
"Foreground-Aware Dataset Distillation via Dynamic Patch Selection." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.02727)]
[2026.01]
 
- **PatchAlign3D:** Souhail Hadgi, Bingchen Gong, Ramana Sundararaman, Emery Pierson, Lei Li, Peter Wonka, Maks Ovsjanikov.<br />
"PatchAlign3D: Local Feature Alignment for Dense 3D Shape Understanding." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.02457)]
[[code](https://souhail-hadgi.github.io/patchalign3dsite)]
[2026.01]

- **TopoLoRA-SAM:** Salim Khazem.<br />
"TopoLoRA-SAM: Topology-Aware Parameter-Efficient Adaptation of Foundation Segmenters for Thin-Structure and Cross-Domain Binary Semantic Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.02273)]
[[code](https://github.com/salimkhazem/Seglab.git)]
[2026.01]
 
- **GleSAM++:** Guangqian Guo, Aixi Ren, Yong Guo, Xuehui Yu, Jiacheng Tian, Wenli Li, Yaoxing Wang, Shan Gao.<br />
"Towards Any-Quality Image Segmentation via Generative and Adaptive Latent Space Enhancement." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.02018)]
[[code](https://guangqian-guo.github.io/glesam++)]
[2026.01]
 
- Riccardo Gelato, Carlo Sgaravatti, Jakob Grahn, Giacomo Boracchi, Filippo Maria Bianchi.<br />
"Promptable Foundation Models for SAR Remote Sensing: Adapting the Segment Anything Model for Snow Avalanche Segmentation." ArXiv (2026).
[[paper](https://arxiv.org/abs/2601.01213)]
[2026.01]

- Devis Salierno, Matteo Dunnhofer & Christian Micheloni.<br />
"Ego-Exo Object Correspondence by SAM2 and Cross-View Prompting." ICIAP (2026).
[[paper](https://link.springer.com/chapter/10.1007/978-3-032-10192-1_27)]
[2026.01]

- **VNS-SAM:** Guangqian Guo, Pengfei Chen, Yong Guo, Huafeng Chen, Boqiang Zhang, Shan Gao.<br />
"Boosting Segment Anything Model to Generalize Visually Non-Salient Scenarios." TIP (2026).
[[paper](https://arxiv.org/abs/2601.00537)]
[[code](https://guangqian-guo.github.io/VNS-SAM/)]
[2026.01]

- Miguel Abreu Cardenas, et al.<br />
"Few-Shot Cataract Detection via Feature Density Learning: Evaluating SAM Models and Backbone Embeddings." ArXiv (2026).
[[paper](https://www.researchgate.net/profile/Miguel-Abreu-Cardenas/publication/397632368_Few-Shot_Cataract_Detection_via_Feature_Density_Learning_Evaluating_SAM_Models_and_Backbone_Embeddings/links/6943fb7b0c98040d481eb13e/Few-Shot-Cataract-Detection-via-Feature-Density-Learning-Evaluating-SAM-Models-and-Backbone-Embeddings.pdf)]
[2026.01]


#### 2025
[Paper list 2025](https://github.com/liliu-avril/Awesome-Segment-Anything/blob/main/Paper_List/paper_list_2025.md)

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

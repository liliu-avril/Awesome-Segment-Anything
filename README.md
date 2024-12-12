[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

# A Comprehensive Survey on Segment Anything Model for Vision and Beyond

> **The First Comprehensive SAM Survey: A Comprehensive Survey on Segment Anything Model for Vision and Beyond.** Chunhui Zhang, Li Liu, Yawen Cui, Guanjie Huang, Weilin Lin, Yiqian Yang, Yuehong Hu. [[paper](https://arxiv.org/abs/2305.08196)] [[homepage](https://github.com/liliu-avril/Awesome-Segment-Anything)][[中文解读](https://mp.weixin.qq.com/s/uYpRzvRp22-40x8e0pLVIg)] 

> **<p align="justify"> Abstract:** *Artificial intelligence (AI) is evolving towards artificial general intelligence, which refers to the ability of an AI system to perform a wide range of tasks and exhibit a level of intelligence similar to that of a human being. This is in contrast to narrow or specialized AI, which is designed to perform specific tasks with a high degree of efficiency. Therefore, it is urgent to design a general class of models, which we term foundation models, trained on broad data that can be adapted to various downstream tasks. The recently proposed segment anything model (SAM) has made significant progress in breaking the boundaries of segmentation, greatly promoting the development of foundation models for computer vision. To fully comprehend SAM, we conduct a survey study. As the first to comprehensively review the progress of segmenting anything task for vision and beyond based on the foundation model of SAM, this work focuses on its applications to various tasks and data types by discussing its historical development, recent progress, and profound impact on broad applications. We first introduce the background and terminology for foundation models including SAM, as well as state-of-the-art methods contemporaneous with SAM that are significant for segmenting anything task. Then, we analyze and summarize the advantages and limitations of SAM across various image processing applications, including software scenes, real-world scenes, and complex scenes. Importantly, many insights are drawn to guide future research to develop more versatile foundation models and improve the architecture of SAM. We also summarize massive other amazing applications of SAM in vision and beyond. Finally, we maintain a continuously updated paper list and an open-source project summary for foundation model SAM at [here](https://github.com/liliu-avril/Awesome-Segment-Anything).* </p>

> **Awesome Segment Anything Models:** A curated list of awesome segment anything models in computer vision and beyond. This repository supplements our survey paper. We intend to continuously update it.
#### If you like our project, please give us a star ⭐ on GitHub for latest update.

#### We strongly encourage authors of relevant works to make a pull request and add their paper's information [[here](https://docs.google.com/spreadsheets/d/1AdOc_mZrkKP7XoKL9g7YO4EEpjlxdxEDK2yOdRZ_edg/edit?usp=sharing)].

:boom:**[SAM 2](https://github.com/facebookresearch/segment-anything-2): Segment Anything in Images and Videos was released.**

:boom:**[The first survey on SAM for videos](https://github.com/983632847/SAM-for-Videos): Segment Anything for Videos: A Systematic Survey was online.**
____

## :fire: Highlights
![Last Updated](https://badgen.net/github/last-commit/liliu-avril/Awesome-Segment-Anything?icon=github&label=last%20updated&color=green)
```
- 2024.07.31: The first survey on SAM for videos was online.
- 2024.07.30: The SAM 2 was released.
- 2023.07.14: "Segment Anything" was accepted by ICCV 2023.
- 2023.05.16: An initial version of recent papers and projects.
- 2023.04.05: The paper of "Segment Anything" was online.
```

## Contents
- [Survey](#survey)
- [Paper List](#paper-list) 
  - [Seminal Papers](#seminal-papers)
  - [Follow-up Papers ](#follow-up-papers)
- [Open Source Projects](#open-source-projects)
- [Awesome Repositories for SAM](#awesome-repositories-for-sam)

## Citation

If you find our work useful in your research, please consider citing:
```
@article{chunhui2023samsurvey,
  title={A Comprehensive Survey on Segment Anything Model for Vision and Beyond},
  author={Zhang, Chunhui and Liu, Li and Cui, Yawen and Huang, Guanjie and Lin, Weilin and Yang, Yiqian and Hu, Yuehong},
  journal={arXiv:2305.08196},
  year={2023}
}

@article{chunhui2024samforvideos,
  title={Segment Anything for Videos: A Systematic Survey},
  author={Chunhui Zhang, Yawen Cui, Weilin Lin, Guanjie Huang, Yan Rong, Li Liu, Shiguang Shan},
  journal={arXiv},
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

- **SAM for Videos:** Chunhui Zhang, Yawen Cui, Weilin Lin, Guanjie Huang, Yan Rong, Li Liu, Shiguang Shan.<br />
  "Segment Anything for Videos: A Systematic Survey." ArXiv (2024).
[[ArXiv]](https://arxiv.org/abs/2408.08315) 
[[ChinaXiv]](https://chinaxiv.org/abs/202408.00019)
[[ResearchGate]](https://www.researchgate.net/publication/382737497_Segment_Anything_for_Videos_A_Systematic_Survey)
[[Project]](https://github.com/983632847/SAM-for-Videos)
[[中文解读]](https://zhuanlan.zhihu.com/p/712807912)
[2024.07]

- Xiaorui Sun, Jun Liu, Heng Tao Shen, Xiaofeng Zhu, Ping Hu.<br />
  "On Efficient Variants of Segment Anything Model: A Survey." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.04960)] 
  [2024.10]
  
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
  "SAM 2: Segment Anything in Images and Videos." ArXiv (2024).
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


### Follow-up Papers
:boom:**SAM-Mix:** Tyler Ward, Abdullah-Al-Zubaer Imran.<br />
"Annotation-Efficient Task Guidance for Medical Segment Anything." ArXiv (2024).
[[paper](https://arxiv.org/abs/2412.08575)]
[[code](https://github.com/tbwa233/SAM-Mix)]
[2024.12]

:boom:**SAM-Mamba:** Tapas Kumar Dutta, Snehashis Majhi, Deepak Ranjan Nayak, Debesh Jha.<br />
"SAM-Mamba: Mamba Guided SAM Architecture for Generalized Zero-Shot Polyp Segmentation." ArXiv (2024).
[[paper](https://arxiv.org/abs/2412.08482)]
[[code](https://github.com/TapasKumarDutta1/SAM_Mamba_2025)]
[2024.12]

:boom:**LIM-Net:** Bingzhi Shen, Lufan Chang, Siqi Chen, Shuxiang Guo, Hao Liu.<br />
"Lightweight Method for Interactive 3D Medical Image Segmentation with Multi-Round Result Fusion." ArXiv (2024).
[[paper](https://arxiv.org/abs/2412.08315)]
[[code](https://github.com/goodtime-123/LIM-Net)]
[2024.12]

:boom:**Crack-EdgeSAM:** Yingchu Wang, Ji He, Shijie Yu.<br />
"Crack-EdgeSAM Self-Prompting Crack Segmentation System for Edge Devices." ArXiv (2024).
[[paper](https://arxiv.org/abs/2412.07205)]
[2024.12]

:boom:**OVHR3D:** Jiuyi Xu, Meida Chen, Andrew Feng, Yangming Shi, Zifan Yu.<br />
"Open-Vocabulary High-Resolution 3D (OVHR3D) Data Segmentation and Annotation Framework." I/ITSEC(2024).
[[paper](https://arxiv.org/abs/2412.06268)]
[2024.12]

:boom:**CoSAM:** Jinglong Yang, Yichen Wu, Jun Cen, Wenjian Huang, Hong Wang, Jianguo Zhang.<br />
"Continual Learning for Segment Anything Model Adaptation." ArXiv (2024).
[[paper](https://arxiv.org/abs/2412.06418)]
[[code](https://github.com/yangjl1215/CoSAM)]
[2024.12]

:boom:**RefSAM3D:** Xiang Gao, Kai Lu.<br />
"RefSAM3D: Adapting SAM with Cross-modal Reference for 3D Medical Image Segmentation." ArXiv (2024).
[[paper](https://arxiv.org/abs/2412.05605)]
[2024.12]

:boom:**MCP-MedSAM:** Donghang Lyu, Ruochen Gao, Marius Staring.<br />
"MCP-MedSAM: A Powerful Lightweight Medical Segment Anything Model Trained with a Single GPU in Just One Day." ArXiv (2024).
[[paper](https://arxiv.org/abs/2412.05888)]
[[code](https://github.com/dong845/MCP-MedSAM)]
[2024.12]

:boom:**SAMCL:** Zeqing Wang, Kangye Ji, Di Wang, Fei Cheng.<br />
"SAMCL: Empowering SAM to Continually Learn from Dynamic Domains." ArXiv (2024).
[[paper](https://arxiv.org/abs/2412.05012)]
[2024.12]

:boom:K Wheeler, E J Lang, C R Field, N Madden, R Schoell, R Peña, D J Senor, A Casella, K Hattar.<br />
"He Bubble Evolution in LiAlO2: A Comparison of Human and Artificial Intelligence Based Analysis." Microscopy and Microanalysis (2024).
[[paper](https://academic.oup.com/mam/article/30/Supplement_1/ozae044.816/7720148?login=false)]
[2024.12]

:boom:Vanhaeverbeke, J.; Decorte, R.; Slembrouck, M.; Hoecke, S.V.; Verstockt, S.<br />
"Point of Interest Recognition and Tracking in Aerial Video during Live Cycling Broadcasts." Applied Sciences(2024).
[[paper](https://www.mdpi.com/2076-3417/14/20/9246)]
[2024.12]

:boom:**Guided SAM:** Sabina B. van Rooij & Gertjan J. Burghouts.<br />
"Guided SAM: Label-Efficient Part Segmentation." ICPR(2024).
[[paper](https://link.springer.com/chapter/10.1007/978-3-031-78110-0_19)]
[2024.12]

:boom:**SAM-R:** Rosa Pia Devanna and Giulio Reina and Fernando Auat Cheein and Annalisa Milella.<br />
"Boosting grape bunch detection in RGB-D images using zero-shot annotation with Segment Anything and GroundingDINO." Computers and Electronics in Agriculture(2024).
[[paper](https://www.sciencedirect.com/science/article/pii/S0168169924010020)]
[2024.12]

:boom:**RS-SAM:** Enkai Zhang, Jingjing Liu, Anda Cao, Zhen Sun, Haofei Zhang, Huiqiong Wang, Li Sun, Mingli Song.<br />
"RS-SAM: Integrating Multi-Scale Information for Enhanced Remote Sensing Image Segmentation." ACCV(2024).
[[paper](https://openaccess.thecvf.com/content/ACCV2024/html/Zhang_RS-SAM_Integrating_Multi-Scale_Information_for_Enhanced_Remote_Sensing_Image_Segmentation_ACCV_2024_paper.html)]
[2024.12]

:boom:**SAMIF:** Lan Zhang, Xinshan Zhu, Di He, Xin Liao, Biao Sun.<br />
"SAMIF: Adapting Segment Anything Model for Image Inpainting Forensics." ACCV(2024).
[[paper](https://openaccess.thecvf.com/content/ACCV2024/html/Zhang_SAMIF_Adapting_Segment_Anything_Model_for_Image_Inpainting_Forensics_ACCV_2024_paper.html)]
[2024.12]

:boom:**LoRASAM:** Jay N. Paranjape, Shameema Sikder, S. Swaroop Vedula & Vishal M. Patel.<br />
"Low-Rank Adaptation of Segment Anything Model for Surgical Scene Segmentation." ICPR(2024).
[[paper](https://link.springer.com/chapter/10.1007/978-3-031-78198-8_13)]
[[code](https://github.com/JayParanjape/LoRASAM)]
[2024.12]

:boom:**TV-SAM:** Jiang, Zekun and Cheng, Dongjie and Qin, Ziyuan and Gao, Jun and Lao, Qicheng and Ismoilovich, Abdullaev Bakhrom and Gayrat, Urazboev and Elyorbek, Yuldashov and Habibullo, Bekchanov and Tang, Defu and Wei, Linjing and Li, Kang and Zhang, Le.<br />
"TV-SAM: Increasing Zero-Shot Segmentation Performance on Multimodal Medical Images Using GPT-4 Generated Descriptive Prompts Without Human Annotation." Big Data Mining and Analytics (2024).
[[paper](https://ieeexplore.ieee.org/abstract/document/10778143)]
[2024.12]

:boom:**3DMedSAM:** Haoneng Lin and Jing Zou and Sen Deng and Ka Po Wong and Angelica I. Aviles-Rivero and Yiting Fan and Alex Pui-Wai Lee and Xiaowei Hu and Jing Qin.<br />
"Volumetric medical image segmentation via fully 3D adaptation of Segment Anything Model." Biocybernetics and Biomedical Engineering(2024).
[[paper](https://www.sciencedirect.com/science/article/pii/S0208521624000846)]
[2024.12]

:boom:**SEMPNet:** Ao, W., Zheng, S., & Meng, Y.<br />
"SEMPNet: enhancing few-shot remote sensing image semantic segmentation through the integration of the segment anything model." GIScience & Remote Sensing(2024).
[[paper](https://www.tandfonline.com/doi/full/10.1080/15481603.2024.2426589#abstract)]
[2024.12]

- Yixin Zhang, Nicholas Konz, Kevin Kramer, Maciej A. Mazurowski.<br />
"Quantifying the Limits of Segment Anything Model: Analyzing Challenges in Segmenting Tree-Like and Low-Contrast Structures." ArXiv (2024).
[[paper](https://github.com/mazurowski-lab/SAM-TexturalConfusion-Metrics)]
[[code](https://github.com/mazurowski-lab/SAM-TexturalConfusion-Metrics)]
[2024.12]

- **MoE-LoRA:** Chenyang Zhu, Bin Xiao, Lin Shi, Shoukun Xu, Xu Zheng.<br />
"Customize Segment Anything Model for Multi-Modal Semantic Segmentation with Mixture of LoRA Experts." ArXiv (2024).
[[paper](https://arxiv.org/abs/2412.04220)]
[2024.12]

- J. Vega-Ferrero, F. Buitrago, J. Fernández-Iglesias, S. Raji, B. Sahelices, H. Domínguez Sánchez.<br />
"Automated galaxy sizes in Euclid images using the Segment Anything Model." Astronomy & Astrophysics(2024).
[[paper](https://arxiv.org/abs/2412.03642)]
[2024.12]

- **Measure Anything:** Yongkyu Lee, Shivam Kumar Panda, Wei Wang, Mohammad Khalid Jawed.<br />
"Measure Anything: Real-time, Multi-stage Vision-based Dimensional Measurement using Segment Anything." ArXiv (2024).
[[paper](https://arxiv.org/abs/2412.03472)]
[[code](https://github.com/StructuresComp/measure-anything)]
[2024.12]

- **ADIW:** Zhenyu Li, Mykola Lavreniuk, Jian Shi, Shariq Farooq Bhat, Peter Wonka.<br />
"Amodal Depth Anything: Amodal Depth Estimation in the Wild." ArXiv (2024).
[[paper](https://arxiv.org/abs/2412.02336)]
[[code](https://zhyever.github.io/amodaldepthanything/)]
[2024.12]

- **LMSeg:** Huadong Tang, Youpeng Zhao, Yan Huang, Min Xu, Jun Wang, Qiang Wu.<br />
"LMSeg: Unleashing the Power of Large-Scale Models for Open-Vocabulary Semantic Segmentation." ArXiv (2024).
[[paper](https://arxiv.org/abs/2412.00364)]
[2024.12]

- **MUG-VOS:** Sangbeom Lim, Seongchan Kim, Seungjun An, Seokju Cho, Paul Hongsuck Seo, Seungryong Kim.<br />
"Multi-Granularity Video Object Segmentation." ArXiv (2024).
[[paper](https://arxiv.org/abs/2412.01471)]
[[code](https://cvlab-kaist.github.io/MUG-VOS)]
[2024.12]

- **BMP:** Miroslav Purkrabek, Jiri Matas.<br />
"Detection, Pose Estimation and Segmentation for Multiple Bodies: Closing the Virtuous Circle." ArXiv (2024).
[[paper](https://arxiv.org/abs/2412.01562)]
[[code](https://mirapurkrabek.github.io/BBox-Mask-Pose)]
[2024.12]

- **CellSeg1:** Peilin Zhou, Bo Du, Yongchao Xu.<br />
"CellSeg1: Robust Cell Segmentation with One Training Image." ArXiv (2024).
[[paper](https://arxiv.org/abs/2412.01410)]
[2024.12]

- **SAMs-CDConcepts-Eval:** Xiaoqi Zhao, Youwei Pang, Shijie Chang, Yuan Zhao, Lihe Zhang, Huchuan Lu, Jinsong Ouyang, Georges El Fakhri, Xiaofeng Liu.<br />
"Inspiring the Next Generation of Segment Anything Models: Comprehensively Evaluate SAM and SAM 2 with Diverse Prompts Towards Context-Dependent Concepts under Different Scenes." ArXiv (2024).
[[paper](https://arxiv.org/abs/2412.01240)]
[[code](https://github.com/lartpang/SAMs-CDConcepts-Eval)]
[2024.12]

- **SOLA:** Seongchan Kim, Woojeong Jin, Sangbeom Lim, Heeji Yoon, Hyunwook Choi, Seungryong Kim.<br />
"Referring Video Object Segmentation via Language-aligned Track Selection." ArXiv (2024).
[[paper](https://arxiv.org/abs/2412.01136)]
[[code](https://cvlab-kaist.github.io/SOLA)]
[2024.12]

- **SADG:** Yun-Jin Li, Mariia Gladkova, Yan Xia, Daniel Cremers.<br />
"SADG: Segment Any Dynamic Gaussian Without Object Trackers." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.19290)]
[[code](https://yunjinli.github.io/project-sadg)]
[2024.11]

- **TABE:** Finlay G. C. Hudson, William A. P. Smith.<br />
"Track Anything Behind Everything: Zero-Shot Amodal Video Object Segmentation." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.19210)]
[2024.11]

- **Det-SAM2:** Zhiting Wang, Qiangong Zhou, Zongyang Liu.<br />
"Det-SAM2:Technical Report on the Self-Prompting Segmentation Framework Based on Segment Anything Model 2." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.18977)]
[[code](https://github.com/motern88/Det-SAM2)]
[2024.11]

- **EfficientTAMs:** Yunyang Xiong, Chong Zhou, Xiaoyu Xiang, Lemeng Wu, Chenchen Zhu, Zechun Liu, Saksham Suri, Balakrishnan Varadarajan, Ramya Akula, Forrest Iandola, Raghuraman Krishnamoorthi, Bilge Soran, Vikas Chandra.<br />
"Efficient Track Anything." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.18933)]
[[code](https://yformer.github.io/efficient-track-anything/)]
[2024.11]

- **COMPrompter:** Xiaoqin Zhang, Zhenni Yu, Li Zhao, Deng-Ping Fan, Guobao Xiao.<br />
"COMPrompter: reconceptualized segment anything model with multiprompt network for camouflaged object detection." SCIENCE CHINA Information Sciences (2024).
[[paper](https://arxiv.org/abs/2411.18858)]
[[code](https://github.com/guobaoxiao/COMPrompter)]
[2024.11]

- **SimCMF:** Chenyang Lei, Liyi Chen, Jun Cen, Xiao Chen, Zhen Lei, Felix Heide, Qifeng Chen, Zhaoxiang Zhang.<br />
"SimCMF: A Simple Cross-modal Fine-tuning Strategy from Vision Foundation Models to Any Imaging Modality." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.18669)]
[[code](https://github.com/mt-cly/SimCMF)]
[2024.11]

- Huanlong Zhang and Xiangbo Yang and Xin Wang and Weiqiang Fu and Bineng Zhong and Jianwei Zhang.<br />
"SAM-Assisted Temporal-Location Enhanced Transformer Segmentation for Object Tracking with Online Motion Inference." Neurocomputing (2024).
[[paper](https://www.sciencedirect.com/science/article/pii/S0925231224016850)]
[2024.11]

- **IngredSAM:** Chen, L., Wang, B., & Zhang, J.<br />
"IngredSAM: Open-World Food Ingredient Segmentation via a Single Image Prompt." Journal of Imaging(2024).
[[paper](https://www.mdpi.com/2313-433X/10/12/305)]
[2024.11]

- **SAMWISE:** Claudia Cuttano, Gabriele Trivigno, Gabriele Rosi, Carlo Masone, Giuseppe Averta.<br />
"SAMWISE: Infusing wisdom in SAM2 for Text-Driven Video Segmentation." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.17646)]
[[code](https://github.com/ClaudiaCuttano/SAMWISE)]
[2024.11]

- **SAM-MPA:** Jie Xu, Xiaokang Li, Chengyu Yue, Yuanyuan Wang, Yi Guo.<br />
"SAM-MPA: Applying SAM to Few-shot Medical Image Segmentation using Mask Propagation and Auto-prompting." NeurIPS 2024 AIM-FM Workshop(2024).
[[paper](https://arxiv.org/abs/2411.17363)]
[2024.11]

- **SPT:** Hui-Yue Yang, Hui Chen, Ao Wang, Kai Chen, Zijia Lin, Yongliang Tang, Pengcheng Gao, Yuming Quan, Jungong Han, Guiguang Ding.<br />
"Promptable Anomaly Segmentation with SAM Through Self-Perception Tuning." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.17217)]
[2024.11]

- **SAM-Road++:** Pan Yin, Kaiyu Li, Xiangyong Cao, Jing Yao, Lei Liu, Xueru Bai, Feng Zhou, Deyu Meng.<br />
"Towards Satellite Image Road Graph Extraction: A Global-Scale Dataset and A Novel Method." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.16733)]
[[code](https://github.com/earth-insights/samroadplus)]
[2024.11]

- **SAMatch:** Guoping Xu, Xiaoxue Qian, Hua Chieh Shao, Jax Luo, Weiguo Lu, You Zhang.<br />
"A SAM-guided and Match-based Semi-Supervised Segmentation Framework for Medical Imaging." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.16949)]
[[code](https://github.com/apple1986/SAMatch)]
[2024.11]

- **DAM4SAM:** Jovana Videnovic, Alan Lukezic, Matej Kristan.<br />
"A Distractor-Aware Memory for Visual Object Tracking with SAM2." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.17576)]
[[code](https://github.com/jovanavidenovic/DAM4SAM)]
[2024.11]

- **Any3DIS:** Phuc Nguyen, Minh Luu, Anh Tran, Cuong Pham, Khoi Nguyen.<br />
"Any3DIS: Class-Agnostic 3D Instance Segmentation by 2D Mask Tracking." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.16183)]
[[code](https://any3dis.github.io/)]
[2024.11]

- **SDM-D:** Yanan Wang, Zhenghao Fei, Ruichen Li, Yibin Ying.<br />
"Learn from Foundation Model: Fruit Detection Model without Manual Annotation." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.16196)]
[[code](https://github.com/AgRoboticsResearch/SDM-D.git)]
[2024.11]

- **UltraSam:** Adrien Meyer, Aditya Murali, Didier Mutter, Nicolas Padoy.<br />
"UltraSam: A Foundation Model for Ultrasound using Large Open-Access Segmentation Datasets." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.16222)]
[[code](https://github.com/CAMMA-public/UltraSam)]
[2024.11]

- Manuel Knott, Divinefavour Odion, Sameer Sontakke, Anup Karwa, Thijs Defraeye.<br />
"Weakly supervised image segmentation for defect-based grading of fresh produce." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.16219)]
[2024.11]

- **Med-PerSAM:** Hangyul Yoon, Doohyuk Jang, Jungeun Kim, Eunho Yang.<br />
"Med-PerSAM: One-Shot Visual Prompt Tuning for Personalized Segment Anything Model in Medical Domain." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.16123)]
[2024.11]

- Miguel Espinosa, Chenhongyi Yang, Linus Ericsson, Steven McDonagh, Elliot J. Crowley.<br />
"There is no SAMantics! Exploring SAM as a Backbone for Visual Understanding Tasks." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.15288)]
[[code](https://github.com/miquel-espinosa/samantics)]
[2024.11]

- **ESC-Net:** Minhyeok Lee, Suhwan Cho, Jungho Lee, Sunghun Yang, Heeseung Choi, Ig-Jae Kim, Sangyoun Lee.<br />
"Effective SAM Combination for Open-Vocabulary Semantic Segmentation." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.14723)]
[2024.11]

- Burke, Molly.<br />
"Segmentation and Quantification of Intersegmental Vessels in Zebrafish Embryos: Utilizing U-Net and MedSAM for automated vessel metric analysis." ArXiv (2024).
[[paper](https://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1914808&dswid=301)]
[2024.11]

- **SegAnyPath:** Wang, Chong and Wan, Yajie and Li, Shuxin and Qu, Kaili and Zhou, Xuezhi and He, Junjun and Ke, Jing and Yu, Yi and Wang, Tianyun and Shen, Yiqing.<br />
"SegAnyPath: A Foundation Model for Multi-resolution Stain-variant and Multi-task Pathology Image Segmentation." TMI(2024).
[[paper](https://ieeexplore.ieee.org/abstract/document/10756743)]
[[code](https://github.com/wagnchogn/SegAnyPath)]
[2024.11]

- Reddy, J., Niu, H., Scott, J. L. L., Bhandari, M., Landivar, J. A., Bednarz, C. W., & Duffield, N.<br />
"Cotton Yield Prediction via UAV-Based Cotton Boll Image Segmentation Using YOLO Model and Segment Anything Model (SAM)." Remote Sensing(2024).
[[paper](https://www.mdpi.com/2072-4292/16/23/4346)]
[2024.11]

- **WasteSAM:** Seokjae Heo and Seunguk Na.<br />
"Developing WasteSAM: A novel approach for accurate construction waste image segmentation to facilitate efficient recycling." ArXiv (2024).
[[paper](https://journals.sagepub.com/doi/abs/10.1177/0734242X241290743)]
[2024.11]

- **IMed-361M:** Junlong Cheng, Bin Fu, Jin Ye, Guoan Wang, Tianbin Li, Haoyu Wang, Ruoyu Li, He Yao, Junren Chen, JingWen Li, Yanzhou Su, Min Zhu, Junjun He.<br />
"." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.12814)]
[[code](https://github.com/uni-medical/IMIS-Bench)]
[2024.11]

- VENEZIANI, MICHELE.<br />
"Segmentazione semantica: prompt engineering per il modello Segment Anything." ArXiv (2024).
[[paper](https://thesis.unipd.it/handle/20.500.12608/76498)]
[2024.11]

- **DIS-Mine:** Mizanur Rahman Jewel, Mohamed Elmahallawy, Sanjay Madria, Samuel Frimpong.<br />
"DIS-Mine: Instance Segmentation for Disaster-Awareness in Poor-Light Condition in Underground Mines." IEEE BigData(2024).
[[paper](https://arxiv.org/abs/2411.13544)]
[2024.11]

- **GCR:** Kuiran Wang, Xuehui Yu, Wenwen Yu, Guorong Li, Xiangyuan Lan, Qixiang Ye, Jianbin Jiao, Zhenjun Han.<br />
"Click; Single Object Tracking; Video Object Segmentation; Real-time Interaction." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.13183)]
[2024.11]

- **SAM-I2I:** Jiayu Huo, Sebastien Ourselin, Rachel Sparks.<br />
"SAM-I2I: Unleash the Power of Segment Anything Model for Medical Image Translation." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.12755)]
[2024.11]

- **Sim Anything:** Haoyu Zhao, Hao Wang, Xingyue Zhao, Hongqiu Wang, Zhiyu Wu, Chengjiang Long, Hua Zou.<br />
"Automated 3D Physical Simulation of Open-world Scene with Gaussian Splatting." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.12789)]
[[code](https://sim-gs.github.io/)]
[2024.11]

- **SAC:** Hussni Mohd Zakir, Eric Tatt Wei Ho.<br />
"Segment Any Class (SAC): Multi-Class Few-Shot Semantic Segmentation via Class Region Proposals." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.13774)]
[2024.11]

- **LFSAM:** Nikolai Goncharov, Donald G. Dansereau.<br />
"Segment Anything in Light Fields for Real-Time Applications via Constrained Prompting." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.13840)]
[[code](https://roboticimaging.org/Projects/LFSAM/)]
[2024.11]

- **DINO-X:** Tianhe Ren, Yihao Chen, Qing Jiang, Zhaoyang Zeng, Yuda Xiong, Wenlong Liu, Zhengyu Ma, Junyi Shen, Yuan Gao, Xiaoke Jiang, Xingyu Chen, Zhuheng Song, Yuhong Zhang, Hongjie Huang, Han Gao, Shilong Liu, Hao Zhang, Feng Li, Kent Yu, Lei Zhang.<br />
"DINO-X: A Unified Vision Model for Open-World Object Detection and Understanding." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.14347)]
[[code](https://deepdataspace.com/home)]
[2024.11]

- **SAMURAI:** Cheng-Yen Yang, Hsiang-Wei Huang, Wenhao Chai, Zhongyu Jiang, Jenq-Neng Hwang.<br />
"SAMURAI: Adapting Segment Anything Model for Zero-Shot Visual Tracking with Motion-Aware Memory." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.11922)]
[[code](https://github.com/yangchris11/samurai)]
[2024.11]

- Ron Keuth, Lasse Hansen, Maren Balks, Ronja Jäger, Anne-Nele Schröder, Ludger Tüshaus, Mattias Heinrich.<br />
"SAM Carries the Burden: A Semi-Supervised Approach Refining Pseudo Labels for Medical Segmentation." MICCAI Workshop (2024).
[[paper](https://arxiv.org/abs/2411.12602)]
[[code](https://github.com/multimodallearning/SamCarriesTheBurden)]
[2024.11]

- Danny Barash, Emilie Manning, Aidan Van Vleck, Omri Hirsch, Kyi Lei Aye, Jingxi Li, Philip O. Scumpia, Aydogan Ozcan, Sumaira Aasi, Kerri E. Rieger, Kavita Y. Sarin, Oren Freifeld, Yonatan Winetraub.<br />
"Leveraging Computational Pathology AI for Noninvasive Optical Imaging Analysis Without Retraining." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.11613)]
[2024.11]

- **YOLO11n-seg:** Ranjan Sapkota, Achyut Paudel, Manoj Karkee.<br />
"Zero-Shot Automatic Annotation and Instance Segmentation using LLM-Generated Datasets: Eliminating Field Imaging and Manual Annotation for Deep Learning Model Development." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.11285)]
[2024.11]

- **SEAGULL:** Zewen Chen, Juan Wang, Wen Wang, Sunhan Xu, Hang Xiong, Yun Zeng, Jian Guo, Shuxun Wang, Chunfeng Yuan, Bing Li, Weiming Hu.<br />
"SEAGULL: No-reference Image Quality Assessment for Regions of Interest via Vision-Language Instruction Tuning." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.10161)]
[[code](https://github.com/chencn2020/Seagull)]
[2024.11]

- **CoSAM:** Yihang Fu, Ziyang Chen, Yiwen Ye, Xingliang Lei, Zhisong Wang, Yong Xia.<br />
"CoSAM: Self-Correcting SAM for Domain Generalization in 2D Medical Image Segmentation." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.10136)]
[2024.11]

- **CorrCLIP:** Dengke Zhang, Fagui Liu, Quan Tang.<br />
"CorrCLIP: Reconstructing Correlations in CLIP with Off-the-Shelf Foundation Models for Open-Vocabulary Semantic Segmentation." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.10086)]
[2024.11]

- **MORA:** Andong Deng, Tongjia Chen, Shoubin Yu, Taojiannan Yang, Lincoln Spencer, Yapeng Tian, Ajmal Saeed Mian, Mohit Bansal, Chen Chen.<br />
"Motion-Grounded Video Reasoning: Understanding and Perceiving Motion at Pixel Level." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.09921)]
[[code](https://groundmore.github.io/)]
[2024.11]

- **AoP-SAM:** Zihao Zhou and Yaosheng Lu and Jieyun Bai and Víctor M. Campello and Fan Feng and Karim Lekadir.<br />
"Segment Anything Model for fetal head-pubic symphysis segmentation in intrapartum ultrasound image analysis." Expert Systems with Applications(2024).
[[paper](https://www.sciencedirect.com/science/article/pii/S0957417424025661)]
[[code](https://github.com/maskoffs/AoP-SAM)]
[2024.11]

- **2MSPK-Net:** Gongtao Yue, Xiaoguang Ma, Wenrui Li, Ziheng An, Chen Yang.<br />
"2MSPK-Net: A nuclei segmentation network based on multi-scale, multi-dimensional attention, and SAM prior knowledge." Biomedical Signal Processing and Control(2024).
[[paper](https://www.sciencedirect.com/science/article/pii/S1746809424011984)]
[[code](https://github.com/ThirteenYue/2MSPK-Net)]
[2024.11]

- Garvita Allabadi, Ana Lucic, Yu-Xiong Wang & Vikram Adve.<br />
"Learning to Detect Novel Species with SAM in the Wild." IJCV (2024).
[[paper](https://link.springer.com/article/10.1007/s11263-024-02234-0)]
[2024.11]

- Steven Wallace, Aiden Durrant, William David Harcourt, Richard Hann, Georgios Leontidis.<br />
"Exploring Segment Anything Foundation Models for Out of Domain Crevasse Drone Image Segmentation." NLDL(2024).
[[paper](https://openreview.net/pdf?id=CGkyjTXomz)]
[2024.11]

- **DT-SAM:** Weili Shi, Penglong Zhang, Yuqin Li & Zhengang Jiang.<br />
"Segment anything model for few-shot medical image segmentation with domain tuning." Complex & Intelligent Systems (2024).
[[paper](https://link.springer.com/article/10.1007/s40747-024-01625-7)]
[2024.11]

- **Trident:** Yuheng Shi, Minjing Dong, Chang Xu.<br />
"Harnessing Vision Foundation Models for High-Performance, Training-Free Open Vocabulary Segmentation." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.09219)]
[[code](https://github.com/YuHengsss/Trident)]
[2024.11]

- **SUM:** Kangning Liu, Brian Price, Jason Kuen, Yifei Fan, Zijun Wei, Luis Figueroa, Krzysztof J. Geras, Carlos Fernandez-Granda.<br />
"Uncertainty-aware Fine-tuning of Segmentation Foundation Models." NeurIPS (2024).
[[paper](https://openreview.net/pdf?id=qNXRXUC90b)]
[[code](https://github.com/Kangningthu/SUM)]
[2024.11]

- Seungil Baek and Sooyoon Koh and Wonkook Kim and Taewan Kim.<br />
"Evaluation of coarse aggregate properties in hardened concrete based on segment anything model (SAM)." Construction and Building Materials (2024).
[[paper](https://www.sciencedirect.com/science/article/pii/S0950061824041552)]
[2024.11]

- **Uni-EPM:** Gao, Yilin and Mu, Shiyi and Xu, Shugong.<br />
"Uni-EPM: A Unified Extensible Perception Model Without Labeling Everything." TITS (2024).
[[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10747752)]
[2024.11]

- **SAMPart3D:** Yunhan Yang, Yukun Huang, Yuan-Chen Guo, Liangjun Lu, Xiaoyang Wu, Edmund Y. Lam, Yan-Pei Cao, Xihui Liu.<br />
"SAMPart3D: Segment Any Part in 3D Objects." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.07184)]
[[code](https://github.com/yhyang-myron/SAMPart3D-website)]
[2024.11]

- Caroline Magg, Hoel Kervadec, Clara I. Sánchez.<br />
"Zero-shot capability of SAM-family models for bone segmentation in CT scans." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.08629)]
[2024.11]

- **SAM-MorSP:** Jun Xie, Wenxiao Li, Faqiang Wang, Liqiang Zhang, Zhengyang Hou, Jun Liu.<br />
"Slender Object Scene Segmentation in Remote Sensing Image Based on Learnable Morphological Skeleton with Segment Anything Model." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.08592)]
[2024.11]

- Yutao Shen, Hongyu Zhou, Xin Yang, Xuqi Lu, Ziyue Guo, Lixi Jiang, Yong He, Haiyan Cen.<br />
"Biomass phenotyping of oilseed rape through UAV multi-view oblique imaging with 3DGS and SAM model." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.08453)]
[2024.11]

- **IntRaBench:** Constantin Ulrich, Tassilo Wald, Emily Tempus, Maximilian Rokuss, Paul F. Jaeger, Klaus Maier-Hein.<br />
"INTRABENCH: Interactive Radiological Benchmark." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.07885)]
[2024.11]

- **MSEG-VCUQ:** Chika Maduabuchi, Ericmoore Jossou, Matteo Bucci.<br />
"MSEG-VCUQ: Multimodal SEGmentation with Enhanced Vision Foundation Models, Convolutional Neural Networks, and Uncertainty Quantification for High-Speed Video Phase Detection Data." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.07463)]
[[code](https://github.com/chikap421/mseg_vcuq)]
[2024.11]

- **WAM:** Tom Sander, Pierre Fernandez, Alain Durmus, Teddy Furon, Matthijs Douze.<br />
"Watermark Anything with Localized Messages." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.07231)]
[[code](https://github.com/facebookresearch/watermark-anything)]
[2024.11]

- **LFSamba:** Zhengyi Liu, Longzhen Wang, Xianyong Fang, Zhengzheng Tu, Linbo Wang.<br />
"LFSamba: Marry SAM with Mamba for Light Field Salient Object Detection." SPL(2024).
[[paper](https://arxiv.org/abs/2411.06652)]
[[code](https://github.com/liuzywen/LFScribble)]
[2024.11]

- **MapSAM:** Xue Xia, Daiwei Zhang, Wenxuan Song, Wei Huang, Lorenz Hurni.<br />
"MapSAM: Adapting Segment Anything Model for Automated Feature Detection in Historical Maps." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.06971)]
[2024.11]

- **TAP:** Jia Syuen Lim, Yadan Luo, Zhi Chen, Tianqi Wei, Scott Chapman, Zi Huang.<br />
"Track Any Peppers: Weakly Supervised Sweet Pepper Tracking Using VLMs." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.06702)]
[2024.11]

- Rémi Giraud, Michaël Clément.<br />
"Superpixel Segmentation: A Long-Lasting Ill-Posed Problem." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.06478)]
[2024.11]

- Mehri Mehrnia, Mohamed Elbayumi, Mohammed S. M. Elbaz.<br />
"Assessing Foundational Medical 'Segment Anything' (Med-SAM1, Med-SAM2) Deep Learning Models for Left Atrial Segmentation in 3D LGE MRI." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.05963)]
[2024.11]

- **SAM-JOANet:** Shuchang Lyu, Qi Zhaoa, Guangliang Cheng, Yiwei He, Zheng Zhou, Guangbiao Wang, Zhenwei Shi.<br />
"Joint-Optimized Unsupervised Adversarial Domain Adaptation in Remote Sensing Segmentation with Prompted Foundation Model." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.05878)]
[[code](https://github.com/CV-ShuchangLyu/SAM-JOANet)]
[2024.11]

- **WavShadow:** Shreyans Jain, Aadya Arora, Viraj Vekaria, Karan Gandhi.<br />
"WavShadow: Wavelet Based Shadow Segmentation and Removal." ICVGIP(2024).
[[paper](https://arxiv.org/abs/2411.05747)]
[2024.11]

- **EAP4EMSIG:** Nils Friederich, Angelo Jovin Yamachui Sitcheu, Annika Nassal, Matthias Pesch, Erenus Yildiz, Maximilian Beichter, Lukas Scholtes, Bahar Akbaba, Thomas Lautenschlager, Oliver Neumann, Dietrich Kohlheyer, Hanno Scharr, Johannes Seiffarth, Katharina Nöh, Ralf Mikut.<br />
"EAP4EMSIG--Experiment Automation Pipeline for Event-Driven Microscopy to Smart Microfluidic Single-Cells Analysis." Workshop Computational Intelligence(2024).
[[paper](https://arxiv.org/abs/2411.05030)]
[2024.11]

- **VideoGLaMM:** Shehan Munasinghe, Hanan Gani, Wenqi Zhu, Jiale Cao, Eric Xing, Fahad Shahbaz Khan, Salman Khan.<br />
"VideoGLaMM: A Large Multimodal Model for Pixel-Level Visual Grounding in Videos." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.04923)]
[[code](https://mbzuai-oryx.github.io/VideoGLaMM)]
[2024.11]

- **ICH-SCNet:** Xinlei Yu, Ahmed Elazab, Ruiquan Ge, Hui Jin, Xinchen Jiang, Gangyong Jia, Qing Wu, Qinglei Shi, Changmiao Wang.<br />
"ICH-SCNet: Intracerebral Hemorrhage Segmentation and Prognosis Classification Network Using CLIP-guided SAM mechanism." BIBM (2024).
[[paper](https://arxiv.org/abs/2411.04656)]
[2024.11]

- **UEVAVD:** Xinhua Jiang, Tianpeng Liu, Li Liu, Zhen Liu, Yongxiang Liu.<br />
"UEVAVD: A Dataset for Developing UAV's Eye View Active Object Detection." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.04348)]
[[code](https://github.com/Leo000ooo/UEVAVD)]
[2024.11]

- **SA3DIP:** Xi Yang, Xu Gu, Xingyilang Yin, Xinbo Gao.<br />
"SA3DIP: Segment Any 3D Instance with Potential 3D Priors." NeurIPS(2024).
[[paper](https://arxiv.org/abs/2411.03819)]
[2024.11]

- Gabriel Bellon de Carvalho, Jurandy Almeida.<br />
"Exploiting the Segment Anything Model (SAM) for Lung Segmentation in Chest X-ray Images." CIARP(2024).
[[paper](https://arxiv.org/abs/2411.03064)]
[2024.11]

- **RGA:** Xiaoliang Liu, Furao Shen, Jian Zhao.<br />
"Region-Guided Attack on the Segment Anything Model (SAM)." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.02974)]
[2024.11]

- Xavier Timoneda, Markus Herb, Fabian Duerr, Daniel Goehring, Fisher Yu.<br />
"Multi-modal NeRF Self-Supervision for LiDAR Semantic Segmentation." IROS(2024).
[[paper](https://arxiv.org/abs/2411.02969)]
[2024.11]

- Rina Bao, Erfan Darzi, Sheng He, Chuan-Heng Hsiao, Mohammad Arafat Hussain, Jingpeng Li, Atle Bjornerud, Ellen Grant, Yangming Ou.<br />
"Foundation AI Model for Medical Image Segmentation." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.02745)]
[2024.11]

- **DendriteSAM:** Zewen Zhuo, Ilya Belevich, Ville Leinonen, Eija Jokitalo, Tarja Malm, Alejandra Sierra, Jussi Tohka.<br />
"Segment Anything for Dendrites from Electron Microscopy." IPAS(2024).
[[paper](https://arxiv.org/abs/2411.02562)]
[2024.11]

- **UnSegMedGAT:** A. Mudit Adityaja, Saurabh J. Shigwan, Nitin Kumar.<br />
"UnSegMedGAT: Unsupervised Medical Image Segmentation using Graph Attention Networks Clustering." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.01966)]
[[code](https://github.com/mudit-adityaja/UnSegMedGAT)]
[2024.11]

- **SpineFM:** Samuel J. Simons, Bartłomiej W. Papież.<br />
"SpineFM: Leveraging Foundation Models for Automatic Spine X-ray Segmentation." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.00326)]
[2024.11]

- **MV-Adapter:** Lianjun Liu et al.<br />
"MV-Adapter: Enhancing Underwater Instance Segmentation via Adaptive Channel Attention." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.00472)]
[2024.11]

- **ZIM:** Beomyoung Kim, Chanyong Shin, Joonhyun Jeong, Hyungsik Jung, Se-Yun Lee, Sewhan Chun, Dong-Hyun Hwang, Joonsang Yu.<br />
"ZIM: Zero-Shot Image Matting for Anything." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.00626)]
[[code](https://github.com/naver-ai/ZIM)]
[2024.11]

- Sourav Modak, Anthony Stein.<br />
"Generative AI-based Pipeline Architecture for Increasing Training Efficiency in Intelligent Weed Control Systems." ArXiv (2024).
[[paper](https://arxiv.org/abs/2411.00548)]
[2024.11]

- Yue, Jiahe and Zhang, Runchu and Zhang, Zhe and Zhao, Ruixiang and Lv, Wu and Ma, Jie.<br />
"How SAM helps Unsupervised Video Object Segmentation?." IJCNN (2024).
[[paper](https://ieeexplore.ieee.org/abstract/document/10651290)]
[2024.10]

- **SFCD-Net:** Zhang, Da and Wang, Feiyu and Ning, Lichen and Zhao, Zhiyuan and Gao, Junyu and Li, Xuelong.<br />
"Integrating SAM with Feature Interaction for Remote Sensing Change Detection." TGRS(2024).
[[paper](https://ieeexplore.ieee.org/abstract/document/10737290?casa_token=DLWPcqAVeVgAAAAA:L0PWxrMg4DCpxbmCFzr37o1n8QLVdyxNwHb9IW4B-DrIJqRaCE0FW8O8tA5uczccMEOWekfB11Bm)]
[2024.10]

- **Swin-Unet-SAM:** Lin, Yanfen, Tinghao Fan, and Congfu Fang.<br />
"A Classification and Segmentation Model for Diamond Abrasive Grains Based on Improved Swin-Unet-SAM." Electronics (2024).
[[paper](https://www.mdpi.com/2079-9292/13/21/4213)]
[2024.10]

- **RSPS-SAM:** Liu, Zhuoran, Zizhen Li, Ying Liang, Claudio Persello, Bo Sun, Guangjun He, and Lei Ma.<br />
"RSPS-SAM: A Remote Sensing Image Panoptic Segmentation Method Based on SAM." Remote Sensing(2024).
[[paper](https://www.mdpi.com/2072-4292/16/21/4002)]
[2024.10]

- **SF-SAM-Adapter:** Ting Lei, Jing Chen, Jixiang Chen.<br />
"SF-SAM-Adapter: SAM-based segmentation model integrates prior knowledge for gaze image reflection noise removal." Alexandria Engineering Journal(2024).
[[paper](https://www.sciencedirect.com/science/article/pii/S1110016824012572)]
[[code](https://github.com/leiting5297/SF-SAM-Adapter.git)]
[2024.10]

- **MWVOS:** Zhenghao Zhang and Shengfan Zhang and Zuozhuo Dai and Zilong Dong and Siyu Zhu.<br />
"MWVOS: Mask-Free Weakly Supervised Video Object Segmentation via promptable foundation model." Pattern Recognition(2024).
[[paper](https://www.sciencedirect.com/science/article/pii/S0031320324008513)]
[2024.10]

- Chuan Yang, Yueqin Zhu, Jiantong Zhang, Xiaoqiang Wei, Haomeng Zhu, and Zhehui Zhu.<br />
"A feature fusion method on landslide identification in remote sensing with Segment Anything Model." Landslides (2024).
[[paper](https://link.springer.com/article/10.1007/s10346-024-02390-x)]
[2024.10]

- Yanbin Yang, Feiyu Zhao, Ruxi Liang, Quan Guo, Junhua Gu, Yan Huang, Yun Yu.<br />
"Performance of the Segment Anything Model in Various RFI/Events Detection in Radio Astronomy." ArXiv (2024).
[[paper](https://arxiv.org/abs/2410.22497)]
[2024.10]

- **PointPrompt:** Jorge Quesada, Zoe Fowler, Mohammad Alotaibi, Mohit Prabhushankar, Ghassan AlRegib.<br />
"Benchmarking Human and Automated Prompting in the Segment Anything Model." ArXiv (2024).
[[paper](https://arxiv.org/abs/2410.22048)]
[[code](https://github.com/olivesgatech/PointPrompt)]
[2024.10]

- **SAM-Swin:** Jia Wei, Yun Li, Xiaomao Fan, Wenjun Ma, Meiyu Qiu, Hongyu Chen, Wenbin Lei.<br />
"SAM-Swin: SAM-Driven Dual-Swin Transformers with Adaptive Lesion Enhancement for Laryngo-Pharyngeal Tumor Detection." MIA (2024).
[[paper](https://arxiv.org/abs/2410.21813)]
[[code](https://github.com/VVJia/SAM-Swin)]
[2024.10]

- **VideoSAM:** Chika Maduabuchi, Ericmoore Jossou, Matteo Bucci.<br />
"VideoSAM: A Large Vision Foundation Model for High-Speed Video Segmentation." ArXiv (2024).
[[paper](https://arxiv.org/abs/2410.21304)]
[[code](https://github.com/chikap421/videosam)]
[2024.10]

- **RSAM-PT:** Mengke Li, Ye Liu, Yang Lu, Yiqun Zhang, Yiu-ming Cheung, Hui Huang.<br />
"Improving Visual Prompt Tuning by Gaussian Neighborhood Minimization for Long-Tailed Visual Recognition." NeurIPS (2024).
[[paper](https://arxiv.org/abs/2410.21042)]
[[code](https://github.com/Keke921/GNM-PT)]
[2024.10]

- **UMI-GRAT:** Song Xia, Wenhan Yang, Yi Yu, Xun Lin, Henghui Ding, Lingyu Duan, Xudong Jiang.<br />
"Transferable Adversarial Attacks on SAM and Its Downstream Models." NeurIPS (2024).
[[paper](https://arxiv.org/abs/2410.20197)]
[[code](https://github.com/xiasong0501/GRAT)]
[2024.10]

- **A-MFST:** Yuxin Chen, Zijian Wu, Adam Schmidt, Septimiu E. Salcudean.<br />
"A-MFST: Adaptive Multi-Flow Sparse Tracker for Real-Time Tissue Tracking Under Occlusion." ArXiv (2024).
[[paper](https://arxiv.org/abs/2410.19996)]
[2024.10]

- **MealSAM:** Lubnaa Abdur Rahman, Ioannis Papathanail, Lorenzo Brigato, Stavroula Mougiakakou.<br />
"A SAM based Tool for Semi-Automatic Food Annotation." ECAI (2024).
[[paper](https://arxiv.org/abs/2410.19756)]
[[code](https://github.com/lubnaa25/MealSAM_food_annotator)]
[2024.10]

- *OSAM-Fundus:** Rui Wang and Zhouwang Yang and Yanzhi Song.<br />
  "OSAM-Fundus: A training-free, one-shot segmentation framework for optic disc and cup in fundus images." Biomedical Signal Processing and Control (2024).
  [[paper](https://www.sciencedirect.com/science/article/pii/S1746809424011273)] 
  [2024.10]

- **CellSAM:** Xiao Ma, Jin Huang, Mengping Long, Xiaoxiao Li, Zhaoyi Ye, Wanting Hu, Yaxiaer Yalikun, Du Wang, Taobo Hu, Liye Mei, Cheng Lei.<br />
"CellSAM: Advancing Pathologic Image Cell Segmentation  via Asymmetric Large-Scale Vision Model Feature  Distillation Aggregation Network ." Microscopy Research and Technique(2024).
[[paper](https://analyticalsciencejournals.onlinelibrary.wiley.com/doi/abs/10.1002/jemt.24716)]
[2024.10]

- Chenyu Zhang, Sam Huang, Ruwen Qin.<br />
"When Segment Anything Model Meets Inventorying of Roadway Assets." International Journal of Transportation Science and Technology(2024).
[[paper](https://www.sciencedirect.com/science/article/pii/S2046043024001254)]
[2024.10]

- Hazzaa, Firas and Udoidiong, Innocent and Qashou, Akram and Yousef, Sufian.<br />
"Segment Anything: A Review." ArXiv (2024).
[[paper](https://journals.mesopotamian.press/index.php/cs/article/view/565)]
[2024.10]

- **SBC-Net:** Shize Wang, Gang Wu, Jin Wang, Qing Zhu, Yunhui Shi & Baocai Yin.<br />
"SBC-Net: semantic-guided brightness curve estimation network for low-light image enhancement." The Visual Computer(2024).
[[paper](https://link.springer.com/article/10.1007/s00371-024-03636-4)]
[[code](https://github.com/LambChuckEye/Semantic-Guided-Brightness-Curve-Estimation-for-Low-Light-Image-Enhancement)]
[2024.10]

- Chensheng Zhang, Xintong Shi, Xinyue Yin, Jiayi Sun, Jianhui Zhao, Yi Zhang.<br />
"Cleavage-Stage Embryo Segmentation Using SAM-Based Dual Branch Pipeline: Development and Evaluation with the CleavageEmbryo Dataset." Bioimage informatics (2024).
[[paper](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btae617/7826612?login=false)]
[[code](https://github.com/12austincc/Cleavage-StageEmbryoSegmentation)]
[2024.10]

- **CrackSeg:** Zhou, Wei and Huang, Hongpu and Zhang, Hancheng and Wang, Chen.<br />
"Teaching Segment-Anything-Model Domain-Specific Knowledge for Road Crack Segmentation From On-Board Cameras." TITS (2024).
[[paper](https://ieeexplore.ieee.org/document/10720639)]
[[code](https://github.com/TRMetaGroup/CrackSeg)]
[2024.10]

- Oussama Aiadi, Temmar, Salsabil.<br />
"SAM-UNet: a new model for medical image segmentation." ArXiv (2024).
[[paper](https://dspace.univ-ouargla.dz/jspui/handle/123456789/37280)]
[2024.10]

- Hongxin Peng, Yongjian Liao, Weijun Li, Chuanyu Fu, Guoxin Zhang, Ziquan Ding, Zijie Huang, Qiku Cao, Shuting Cai.<br />
  "Segmentation-aware Prior Assisted Joint Global Information Aggregated 3D Building Reconstruction." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.18433)] 
  [2024.10]

- Leila Khaertdinova, Ilya Pershin, Tatiana Shmykova, Bulat Ibragimov.<br />
  "Gaze-Assisted Medical Image Segmentation." ArXiv (2024).
  [[paper](Gaze-Assisted Medical Image Segmentation)] 
  [[code](https://github.com/leiluk1/gaze-based-segmentation)]
  [2024.10]

- **ROCKET-1:** Shaofei Cai, Zihao Wang, Kewei Lian, Zhancun Mu, Xiaojian Ma, Anji Liu, Yitao Liang.<br />
  "ROCKET-1: Master Open-World Interaction with Visual-Temporal Context Prompting." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.17856)] 
  [[code](https://craftjarvis.github.io/ROCKET-1)]
  [2024.10]

- **LIMIS:** Lena Heinemann, Alexander Jaus, Zdravko Marinov, Moon Kim, Maria Francesca Spadea, Jens Kleesiek, Rainer Stiefelhagen.<br />
  "LIMIS: Towards Language-based Interactive Medical Image Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.16939)] 
  [2024.10]

- **PlaneSAM:** Zhongchen Deng, Zhechen Yang, Chi Chen, Cheng Zeng, Yan Meng, Bisheng Yang.<br />
  "PlaneSAM: Multimodal Plane Instance Segmentation Using the Segment Anything Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.16545)] 
  [2024.10]

- **Multi-KernelGAN:** Haim Goldfisher, Asaf Yekutiel.<br />
  "Multi Kernel Estimation based Object Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.17064)] 
  [[code](https://github.com/kuty007/Multi-Kernel-GAN)]
  [2024.10]

- **SAM2Long:** Shuangrui Ding, Rui Qian, Xiaoyi Dong, Pan Zhang, Yuhang Zang, Yuhang Cao, Yuwei Guo, Dahua Lin, Jiaqi Wang.<br />
  "SAM2Long: Enhancing SAM 2 for Long Video Segmentation with a Training-Free Memory Tree." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.16268)] 
  [[code](https://github.com/Mark12Ding/SAM2Long)]
  [2024.10]

- **BYOCL:** Jiayue Dai, Yunya Wang, Yihan Fang, Yuetong Chen, Butian Xiong.<br />
  "BYOCL: Build Your Own Consistent Latent with Hierarchical Representative Latent Clustering." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.15060)] 
  [[code](https://github.com/cyt1202/BYOCL.git)]
  [2024.10]

- **LUDVIG:** Juliette Marrie, Romain Ménégaux, Michael Arbel, Diane Larlus, Julien Mairal.<br />
  "LUDVIG: Learning-free Uplifting of 2D Visual features to Gaussian Splatting scenes." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.14462)] 
  [2024.10]

- **SAMReg:** Shiqi Huang, Tingfa Xu, Ziyi Shen, Shaheer Ullah Saeed, Wen Yan, Dean Barratt, Yipeng Hu.<br />
  "SAMReg: SAM-enabled Image Registration with ROI-based Correspondence." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.14083)] 
  [[code](https://github.com/sqhuang0103/SAMReg.git)]
  [2024.10]
  
- **EP-SAM:** Joonhyeon Song, Seohwan Yun, Seongho Yoon, Joohyeok Kim, Sangmin Lee.<br />
  "EP-SAM: Weakly Supervised Histopathology Segmentation via Enhanced Prompt with Segment Anything." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.13621)] 
  [[code](https://github.com/QI-NemoSong/EP-SAM)]
  [2024.10]

- **GRS:** Alex Zook, Fan-Yun Sun, Josef Spjut, Valts Blukis, Stan Birchfield, Jonathan Tremblay.<br />
  "GRS: Generating Robotic Simulation Tasks from Real-World Images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.15536)] 
  [2024.10]

- **EPLC-SAM:** Joonhyeon Song, Seohwan Yun, Seongho Yoon, Joohyeok Kim, Sangmin Lee.<br />
  "Enhanced Prompt-leveraged Weakly Supervised Cancer Segmentation based on Segment Anything." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.13621)] 
  [[code](https://github.com/QI-NemoSong/EPLC-SAM)]
  [2024.10]

- **SAM-GT:** Zhimin Chen, Liang Yang, Yingwei Li, Longlong Jing, Bing Li.<br />
  "SAM-Guided Masked Token Prediction for 3D Scene Understanding." NeurIPS (2024).
  [[paper](https://arxiv.org/abs/2410.12158)] 
  [2024.10]

- Jiří Vyskočil, Lukas Picek.<br />
  "Towards Zero-Shot Camera Trap Image Categorization." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.12769)] 
  [2024.10]

- **APL-SAM:** Yao Shen, Ziwei Wei, Chunmeng Liu, Shuming Wei, Qi Zhao, Kaiyang Zeng, Guangyao Li.<br />
  "Adaptive Prompt Learning with SAM for Few-shot Scanning Probe Microscope Image Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.12562)] 
  [2024.10]

- **FEMed:** Chen Xu, Qiming Huang, Yuqi Hou, Jiangxing Wu, Fan Zhang, Hyung Jin Chang, Jianbo Jiao.<br />
  "Few Exemplar-Based General Medical Image Segmentation via Domain-Aware Selective Adaptation." ACCV (2024).
  [[paper](https://arxiv.org/pdf/2410.09254)] 
  [[code](https://xuchenjune.github.io/FEMed/)]
  [2024.10]

- **Words To Wheels:** Chanhoe Ryu, Hyunki Seong, Daegyu Lee, Seongwoo Moon, Sungjae Min, D. Hyunchul Shim.<br />
  "Words to Wheels: Vision-Based Autonomous Driving Understanding Human Language Instructions Using Foundation Models." ArXiv (2024).
  [[paper](https://arxiv.org/pdf/2410.10577)] 
  [2024.10]

- **RClicks:** Anton Antonov, Andrey Moskalenko, Denis Shepelev, Alexander Krapukhin, Konstantin Soshin, Anton Konushin, Vlad Shakhuro.<br />
  "RClicks: Realistic Click Simulation for Benchmarking Interactive Segmentation." NeurIPS (2024).
  [[paper](https://arxiv.org/abs/2410.11722)] 
  [[code](https://github.com/emb-ai/rclicks)]
  [2024.10]

- **MANet:** Xianping Ma, Xiaokang Zhang, Man-On Pun, Bo Huang.<br />
  "MANet: Fine-Tuning Segment Anything Model for Multimodal Remote Sensing Semantic Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.11160)] 
  [[code](https://github.com/sstary/SSRS)]
  [2024.10]

- **big.LITTLE:** He Guo, Yulong Wang, Zixuan Ye, Jifeng Dai, Yuwen Xiong.<br />
  "big.LITTLE Vision Transformer for Efficient Visual Recognition." ArXiv (2024).
  [[paper](https://arxiv.org/pdf/2410.10267)] 
  [2024.10]

- **CrackSegmentation:** Xiaoyan Jiang, Xinlong Wan, Kaiying Zhu, Xihe Qiu, Zhijun Fang.<br />
  "Distribution-aware Noisy-label Crack Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/pdf/2410.09409)] 
  [[code](https://github.com/sky-visionX/CrackSegmentation)]
  [2024.10]

- **UnSeg:** Ye Sun, Hao Zhang, Tiehua Zhang, Xingjun Ma, Yu-Gang Jiang.<br />
  "UnSeg: One Universal Unlearnable Example Generator is Enough against All Image Segmentation." NeurIPS (2024).
  [[paper](https://arxiv.org/pdf/2410.09909)] 
  [[code](https://github.com/sunye23/UnSeg)]
  [2024.10]

- **AM-SAM:** Yuchen Li, Li Zhang, Youwei Liang, Pengtao Xie.<br />
  "AM-SAM: Automated Prompting and Mask Calibration for Segment Anything Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.09714)] 
  [2024.10]

- **VideoSAM:** Pinxue Guo, Zixu Zhao, Jianxiong Gao, Chongruo Wu, Tong He, Zheng Zhang, Tianjun Xiao, Wenqiang Zhang.<br />
  "VideoSAM: Open-World Video Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.08781)] 
  [2024.10]

- Virmarie Maquiling, Sean Anthony Byrne, Diederick C. Niehorster, Marco Carminati, Enkelejda Kasneci.<br />
  "Zero-Shot Pupil Segmentation with SAM 2: A Case Study of Over 14 Million Images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.08926)] 
  [2024.10]

- **BioSAM:** Cai, Miaomiao and Liu, Xiaoyu and Xiong, Zhiwei and Chen, Xuejin.<br />
  "BioSAM: Generating SAM Prompts From Superpixel Graph for Biological Instance Segmentation." IEEE JBHI (2024).
[[paper](https://ieeexplore.ieee.org/abstract/document/10705688?casa_token=mzhkiYqdOiEAAAAA:x0rDxKHWVB8QUc--7GYLtJJvPEk5qwN-401-scjI7FDtE28_xEFLrRsXbBr8j1EF3ZXgLgM4cdTI)] 
  [2024.10]

- Delle Castelle, C., Spampinato, F., Proietto Salanitri, F., Bellitto, G., Spampinato, C.<br />
  "Leveraging SAM and Learnable Prompts for Pancreatic MRI Segmentation." PILM AIPAD (2024).
  [[paper](https://link.springer.com/chapter/10.1007/978-3-031-73483-0_3)] 
  [2024.10]

- **PTSAM-DA:** Junjun Wu, Yunbo Rao, Shaoning Zeng, Bob Zhang.<br />
  "Pre-trained SAM as data augmentation for image segmentation." CAAI Transactions on Intelligence Technology (2024).
  [[paper](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/cit2.12381)] 
  [2024.10]

- **DFSS:** Zhiyu Jiang; Ye Yuan; Yuan Yuan.<br />
  "Prototypical Metric Segment Anything Model for Data-Free Few-Shot Semantic Segmentation." IEEE Signal Processing Letters (2024).
[[paper](https://ieeexplore.ieee.org/abstract/document/10707179?casa_token=UwNPgeWbbTYAAAAA:ivo0_MZTBOSK2Aq6S456OoEl-mH7kCQYN6SA7Ecg6_qRTuK2YwOw53C1Rkl-b9PJICGL3i7d9RJW)] 
  [2024.10]

- **AIES:** Yifei Huang, Chuyun Shen, Wenhao Li, Xiangfeng Wang, Bo Jin & Haibin Cai.<br />
  "Optimizing Efficiency and Effectiveness in Sequential Prompt Strategy for SAM Using Reinforcement Learning." MICCAI (2024).
  [[paper](https://link.springer.com/chapter/10.1007/978-3-031-72111-3_45)] 
  [2024.10]

- **SAMPolyBuild:** Chenhao Wang and Jingbo Chen and Yu Meng and Yupeng Deng and Kai Li and Yunlong Kong.<br />
  "SAMPolyBuild: Adapting the Segment Anything Model for polygonal building extraction." ISPRS Journal of Photogrammetry and Remote Sensing (2024).
  [[paper](https://www.sciencedirect.com/science/article/abs/pii/S0924271624003563)] 
  [[code](https://github.com/wchh-2000/SAMPolyBuild)]
  [2024.10]

- **UW-SDF:** Zeyu Chen, Jingyi Tang, Gu Wang, Shengquan Li, Xinghui Li, Xiangyang Ji, Xiu Li.<br />
  "UW-SDF: Exploiting Hybrid Geometric Priors for Neural SDF Reconstruction from Underwater Multi-view Monocular Images." IROS (2024).
  [[paper](https://arxiv.org/abs/2410.08092)] 
  [2024.10]

- **PointOBB-v2:** Botao Ren, Xue Yang, Yi Yu, Junwei Luo, Zhidong Deng.<br />
  "PointOBB-v2: Towards Simpler, Faster, and Stronger Single Point Supervised Oriented Object Detection." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.08210)] 
  [[code](https://github.com/taugeren/PointOBB-v2)]
  [2024.10]

- Yuxuan Wen, Evgenia Roussinova, Olivier Brina, Paolo Machi, Mohamed Bouri.<br />
  "Generalizing Segmentation Foundation Model Under Sim-to-real Domain-shift for Guidewire Segmentation in X-ray Fluoroscopy." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.07460)] 
  [2024.10]

- **PixLens:** Stefan Stefanache, Lluís Pastor Pérez, Julen Costa Watanabe, Ernesto Sanchez Tejedor, Thomas Hofmann, Enis Simsar.<br />
  "PixLens: A Novel Framework for Disentangled Evaluation in Diffusion-Based Image Editing with Object Detection + SAM." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.05710)] 
  [2024.10]

- **VL-SAM:** Zhiwei Lin, Yongtao Wang, Zhi Tang.<br />
  "Training-Free Open-Ended Object Detection and Segmentation via Attention as Prompts." NeurIPS (2024).
  [[paper](https://arxiv.org/abs/2410.05963)] 
  [2024.10]
  
- **DirectSAM:** Shiyu Miao, Delong Chen, Fan Liu, Chuanyi Zhang, Yanhui Gu, Shengjie Guo, Jun Zhou.<br />
  "Prompting DirectSAM for Semantic Contour Extraction in Remote Sensing Images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.06194)] 
  [2024.10]

- Jiangfan Deng, Zhuang Jia, Zhaoxue Wang, Xiang Long, Daniel K. Du.<br />
  "Towards Unsupervised Eye-Region Segmentation for Eye Tracking." ECCVW (2024).
  [[paper](https://arxiv.org/abs/2410.06131)] 
  [2024.10]

- **SEMat:** Ruihao Xia, Yu Liang, Peng-Tao Jiang, Hao Zhang, Qianru Sun, Yang Tang, Bo Li, Pan Zhou.<br />
  "Towards Natural Image Matting in the Wild via Real-Scenario Prior." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.06593)] 
  [[code](https://github.com/XiaRho/SEMat)]
  [2024.10]

- Mohamed Deriche, Mohammad Marufur.<br />
  "K-SAM: A Prompting Method Using Pretrained U-Net to Improve Zero Shot Performance of SAM on Lung Segmentation in CXR Images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.06825)] 
  [2024.10]

- **GF-SAM:** Anqi Zhang, Guangyu Gao, Jianbo Jiao, Chi Harold Liu, Yunchao Wei.<br />
  "Bridge the Points: Graph-based Few-shot Segment Anything Semantically." NeurIPS (2024).
  [[paper](https://arxiv.org/abs/2410.06964)] 
  [[code](https://andyzaq.github.io/GF-SAM/)]
  [2024.10]

- **AvatarGO:** Yukang Cao, Liang Pan, Kai Han, Kwan-Yee K. Wong, Ziwei Liu.<br />
  "AvatarGO: Zero-shot 4D Human-Object Interaction Generation and Animation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.07164)] 
  [[code](https://yukangcao.github.io/AvatarGO/)]
  [2024.10]

- **Next Best Sense:** Matthew Strong, Boshu Lei, Aiden Swann, Wen Jiang, Kostas Daniilidis, Monroe Kennedy III.<br />
  "Next Best Sense: Guiding Vision and Touch with FisherRF for 3D Gaussian Splatting." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.04680)] 
  [[code](https://armlabstanford.github.io/next-best-sense)]
  [2024.10]

- **DB-SAM:** Chao Qin, Jiale Cao, Huazhu Fu, Fahad Shahbaz Khan, Rao Muhammad Anwer.<br />
  "DB-SAM: Delving into High Quality Universal Medical Image Segmentation." MICCAI (2024).
  [[paper](https://arxiv.org/abs/2410.04172)] 
  [[code](https://github.com/AlfredQin/DB-SAM)]
  [2024.10]

- Chen, Haoyuan, Sihang Zhou, Kuan Li, Jianping Yin, and Jian Huang.<br />
  "A Hybrid Framework for Referring Image Segmentation: Dual-Decoder Model with SAM Complementation." Mathematics (2024).
  [[paper](https://www.mdpi.com/2227-7390/12/19/3061)] 
  [2024.10]

- **DFQ-SAM:** Zhikai Li, Jing Zhang, Qingyi Gu.<br />
  "Privacy-Preserving SAM Quantization for Efficient Edge Intelligence in Healthcare." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.01813)] 
 [2024.10]

- **SinkSAM:** Osher Rafaeli, Tal Svoray, Ariel Nahlieli.<br />
  "SinkSAM: A Monocular Depth-Guided SAM Framework for Automatic Sinkhole Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.01473)] 
  [2024.10]

- Qingyuan Liu, Avideh Zakhor.<br />
  "Adapting Segment Anything Model to Melanoma Segmentation in Microscopy Slide Images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2410.02207)] 
  [2024.10]

- **PixelCLIP:** Heeseong Shin, Chaehyun Kim, Sunghwan Hong, Seokju Cho, Anurag Arnab, Paul Hongsuck Seo, Seungryong Kim.<br />
  "Towards Open-Vocabulary Semantic Segmentation Without Semantic Labels." NeurIPS (2024).
  [[paper](https://arxiv.org/abs/2409.19846)] 
  [[code](https://cvlab-kaist.github.io/PixelCLIP)]
  [2024.09]

- **Automatic MedSAM:** Mélanie Gaillochet, Christian Desrosiers, Hervé Lombaert.<br />
  "Automating MedSAM by Learning Prompts with Weak Few-Shot Supervision." MICCAI-MedAGI (2024).
  [[paper](https://arxiv.org/abs/2409.20293)] 
  [[code](https://github.com/Minimel/MedSAMWeakFewShotPromptAutomation)]
  [2024.09]

- Iira Häkkinen, Iaroslav Melekhov, Erik Englesson, Hossein Azizpour, Juho Kannala.<br />
  "Medical Image Segmentation with SAM-generated Annotations." ECCVW (2024).
  [[paper](https://arxiv.org/abs/2409.20253)] 
  [2024.09]

- **SCEF:** Fulong Ma, Guoyang Zhao, Weiqing Qi, Ming Liu, Jun Ma.<br />
  "Task-Oriented Pre-Training for Drivable Area Detection." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.20166)] 
  [[code](https://sites.google.com/view/task-oriented-pre-training)]
  [2024.09]

- **VideoLISA:** Zechen Bai, Tong He, Haiyang Mei, Pichao Wang, Ziteng Gao, Joya Chen, Lei Liu, Zheng Zhang, Mike Zheng Shou.<br />
  "One Token to Seg Them All: Language Instructed Reasoning Segmentation in Videos." NeurIPS (2024).
  [[paper](https://arxiv.org/abs/2409.19603)] 
  [[code](https://github.com/showlab/VideoLISA)]
  [2024.09]

- **RoboNurse-VLA:** Shunlei Li, Jin Wang, Rui Dai, Wanyu Ma, Wing Yin Ng, Yingbai Hu, Zheng Li.<br />
  "RoboNurse-VLA: Robotic Scrub Nurse System based on Vision-Language-Action Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.19590)] 
  [[code](https://robonurse-vla.github.io/)]
  [2024.09]

- **MedCLIP-SAMv2:** Taha Koleilat, Hojat Asgariandehkordi, Hassan Rivaz, Yiming Xiao.<br />
  "MedCLIP-SAMv2: Towards Universal Text-Driven Medical Image Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.19483)] 
  [[code](https://github.com/HealthX-Lab/MedCLIP-SAMv2)]
  [2024.09]

- **SAM2-VCOS:** Yuli Zhou, Guolei Sun, Yawei Li, Luca Benini, Ender Konukoglu.<br />
  "When SAM2 Meets Video Camouflaged Object Segmentation: A Comprehensive Evaluation and Adaptation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.18653)] 
  [[code](https://github.com/zhoustan/SAM2-VCOS)]
  [2024.09]

- **SAM-ICE:** Zhao, Ruhao and Zhong, Xian and Liao, Liang and Liu, Wenxuan and Huang, Wenxin and Wang, Zheng.<br />
  "Localization of Image Splicing Under Segment Anything Model With Integrated Compression and Edge Artifacts." ICIP (2024).
[[paper](https://ieeexplore.ieee.org/abstract/document/10648163?casa_token=9e4fHbYtXuwAAAAA:LuJr5uwtydtsx6VVw9ijwb_1a4wTgdRhANTk4AyaWrP7usumjXon1lWDRzefpdaDChYYPcDJbmxC)] 
  [2024.09]

- **SAM-SPB:** Zhao, Quan and Wu, Siying and Zhang, Yueyi and Sun, Xiaoyan.<br />
"Semantic-Enhanced Point-Box Joint Prompting for Video Object Segmentation" ICIP (2024).
[[paper](https://ieeexplore.ieee.org/abstract/document/10648107?casa_token=CDER8G2ujekAAAAA:q3xlO94oqrLBoVsyHZeAd85YXtRtffZLpLoQiw8nHF8N4zif9UxGlNQEUnbiaZlhxS0kQ34eVa1b)] 
[2024.09]

- **OpenDet-D:** Luo, Sheng and Zhou, Yi.<br />
  "Open World Object Detection Via Cooperative Foundation Models for Driving Scenes." ICIP (2024).  [[paper](https://ieeexplore.ieee.org/abstract/document/10647822?casa_token=RzuiYLimTAMAAAAA:NEQ7iIovZFGJ0oBs84ZvrzigA8XEOruVToYOYCDIC8ob8TmepaEZaD0lW7S1GQQFGfpMUYrEChYN)] 
  [2024.09]

- **CERM:** Zhao, Xueqiang, Zheng Wu, Yangbo Chen, Wei Zhou, and Mingan Wei..<br />
  "Fine-Grained High-Resolution Remote Sensing Image Change Detection by SAM-UNet Change Detection Model." Remote Sensing (2024).
  [[paper](https://www.mdpi.com/2072-4292/16/19/3620)] 
  [2024.09]

- **VP-SAM:** Zhixue Fang, Yuzhi Liu, Huisi Wu , and Jin Qin.<br />
  "VP-SAM: Taming Segment Anything Model for Video Polyp Segmentation via Disentanglement and Spatio-temporal Side Network." ECCV (2024).
  [[paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/03403.pdf)] 
  [[code](https://github.com/zhixue-fang/VPSAM)]
  [2024.09]

- **Pro2SAM:** Xi Yang, Songsong Duan, Nannan Wang, and Xinbo Gao.<br />
  "Pro2SAM: Mask Prompt to SAM with Grid Points for Weakly Supervised Object Localization." ECCV (2024).
  [[paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/08795.pdf)] 
  [2024.09]

- **EPLD:** Jing Li, Junsong Fan, and Zhaoxiang Zhang.<br />
  "Point-supervised Panoptic Segmentation via Estimating Pseudo Labels from Learnable Distance." ECCV (2024).
  [[paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/02430.pdf)] 
  [2024.09]

- **Gaussian Grouping:** Mingqiao Ye, Martin Danelljan, Fisher Yu, Lei Ke.<br />
  "Gaussian Grouping: Segment and Edit Anything in 3D Scenes —– Supplementary Material —." ECCV (2024).
  [[paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04195-supp.pdf)] 
  [2024.09]

- **GiT:** Haiyang Wang, Hao Tang, Li Jiang, Shaoshuai Shi, Muhammad Ferjad Naeem, Hongsheng Li, Bernt Schiele, Liwei Wang.<br />
  "Supplementary to GiT: Towards Generalist Vision Transformer through Universal Language Interface." ECCV (2024).
  [[paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04158-supp.pdf)] 
  [2024.09]

- **SFRecSAM:** Wanting Zhang, Huisi Wu1, and Jing Qi.<br />
  "Domesticating SAM for Breast Ultrasound Image Segmentation via Spatial-frequency Fusion and Uncertainty Correction."  ECCV (2024).
  [[paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/03309.pdf)] 
  [[code](https://github.com/dodooo1/SFRecSAM)]
  [2024.09]

- **PQ-SAM:** Xiaoyu Liu, Xin Ding, Lei Yu, Yuanyuan Xi, Wei Li, Zhijun Tu, Jie Hu, Hanting Chen, Baoqun Yin, and Zhiwei Xiong.<br />
  "PQ-SAM: Post-training Quantization for Segment Anything Model."  ECCV (2024).
  [[paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/01627.pdf)] 
  [2024.09]

- Zhi, Junjun, Lin Li, Hong Zhu, Zipeng Li, Mian Wu, Rui Dong, Xinyue Cao, Wangbing Liu, Le’an Qu, Xiaoqing Song, and et al.<br />
  "Comparison of Deep Learning Models and Feature Schemes for Detecting Pine Wilt Diseased Trees." Forests (2024).
  [[paper](https://www.mdpi.com/1999-4907/15/10/1706)] 
  [2024.09]

- Zhewei Chena, Wai Keung Wonga,b, Zuofeng Zhongb, Jinpiao Liaoa, and Ying Qu.<br />
  "Efficient Domain Knowledge Injection for Bridging the Gap Between Generalized Large Vision Models and Specialized Fabric Defect Tasks." Journal of Natural Fibers (2024).
  [[paper](https://www.tandfonline.com/doi/full/10.1080/15440478.2024.2401525)] 
  [2024.09]

- **SAM+nnUNet:** Fang, Z. and Lu, Z. and Liu, H. and Liu, Y. and Mok, G. S.P.<br />
  "SAM+nnUNet: Deep-learning-based Head and Neck Tumor Segmentation on FDG PET." IEEE Nuclear Science Symposium (NSS), Medical Imaging Conference (MIC) and Room Temperature Semiconductor Detector Conference (RTSD) (2024).
[[paper](https://ieeexplore.ieee.org/abstract/document/10657090?casa_token=2Ogf9BSaMfwAAAAA:yz-z4xL_7n50Ul-lYxf4aj6LzqNGJxt-2GYIfC3gou4-cdVE3VqPFLubFSwo4v4iRMpXuBzGzph-)] 
  [2024.09]

- Khajvand, N. and Ahmadyar, Y. and Samimi, R. and Mehrban, Q. and Kamali-Asl, A. and Arabi, H. and Zaidi, H.<br />
  "Whole-Body PET Tumor Lesion Segmentation Using a Transformer-Based Model." IEEE Nuclear Science Symposium (NSS), Medical Imaging Conference (MIC) and Room Temperature Semiconductor Detector Conference (RTSD) (2024).
[[paper](https://ieeexplore.ieee.org/abstract/document/10656988?casa_token=E9-WPGF8UBMAAAAA:N7cFSC3u4adBaZ7tU40wXzH3uSvlykv87zMlbJl_r1aNj3geKGBwb488s5ON3lcwndqXgMbrO2Tf)] 
  [2024.09]

- **Robotic-CLIP:** Nghia Nguyen, Minh Nhat Vu, Tung D. Ta, Baoru Huang, Thieu Vo, Ngan Le, Anh Nguyen.<br />
  "Robotic-CLIP: Fine-tuning CLIP on Action Data for Robotic Applications." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.17727)] 
  [2024.09]

- Jiangshan Liu, Wenlong Dong, Jiankun Wang, Max Q.-H. Meng.<br />
  "Leveraging Semantic and Geometric Information for Zero-Shot Robot-to-Human Handover." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.17621)] 
  [[code](https://sites.google.com/view/vlm-handover/)]
  [2024.09]

- **3D-SAutoMed:** Junjie Liang, Peng Cao, Wenju Yang, Jinzhu Yang, and Osmar R. Zaiane.<br />
  "3D-SAutoMed: Automatic Segment Anything Model for 3D Medical Image Segmentation from Local-Global Perspective." MICCAI (2024).
  [[paper](https://webdocs.cs.ualberta.ca/~zaiane/postscript/MICCAI-24-P2090.pdf)] 
  [2024.09]

- Rezzag Bedida T, Hammouya A.<br />
  "Improving SAM model for medical image segmentation." ArXiv (2024).
  [[paper](https://dspace.univ-ouargla.dz/jspui/handle/123456789/36824)] 
  [2024.09]

- Stiles, Nicole.<br />
  "Efficient Segment Anything on the Edge." ArXiv (2024).
  [[paper](https://dspace.mit.edu/handle/1721.1/157006)] 
  [2024.09]

- **DarkSAM:** Ziqi Zhou, Yufei Song, Minghui Li, Shengshan Hu, Xianlong Wang, Leo Yu Zhang, Dezhong Yao, Hai Jin.<br />
  "DarkSAM: Fooling Segment Anything Model to Segment Nothing." NeurIPS (2024).
  [[paper](https://arxiv.org/abs/2409.17874)] 
  [[code](https://github.com/CGCL-codes/DarkSAM)]
  [2024.09]

- **SegVLAD:** Kartik Garg, Sai Shubodh Puligilla, Shishir Kolathaya, Madhava Krishna, Sourav Garg.<br />
  "Revisit Anything: Visual Place Recognition via Image Segment Retrieval." ECCV (2024).
  [[paper](https://arxiv.org/abs/2409.18049)] 
  [[code](https://github.com/AnyLoc/Revisit-Anything)]
  [2024.09]

- **SAMAL:** Alvaro Patricio, Joao Valente, Atabak Dehban, Ines Cadilha, Daniel Reis, Rodrigo Ventura.<br />
  "AI-Powered Augmented Reality for Satellite Assembly, Integration and Test." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.18101)] 
  [2024.09]

- **GMed-SA:** Meng Wang, Yarong Feng, Yongwei Tang, Tian Zhang, Yuxin Liang, Chao Lv.<br />
  "Global-Local Medical SAM Adaptor Based on Full Adaption." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.17486)] 
  [2024.09]

- **UW-COT:** Chunhui Zhang, Li Liu, Guanjie Huang, Hao Wen, Xi Zhou, Yanfeng Wang.<br />
  "Towards Underwater Camouflaged Object Tracking: An Experimental Evaluation of SAM and SAM 2." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.16902)] 
  [[project](https://github.com/983632847/Awesome-Multimodal-Object-Tracking)]

- Illia Tsiporenko, Pavel Chizhov, Dmytro Fishman.<br />
  "Going Beyond U-Net: Assessing Vision Transformers for Semantic Segmentation in Microscopy Image Analysis." ECCVW (2024).
  [[paper](https://arxiv.org/abs/2409.16940)] 
  [2024.09]

- Xi Wang, Tianxing Chen, Qiaojun Yu, Tianling Xu, Zanxin Chen, Yiting Fu, Cewu Lu, Yao Mu, Ping Luo.<br />
  "Articulated Object Manipulation using Online Axis Estimation with SAM2-Based Tracking." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.16287)] 
  [[code](https://hytidel.github.io/video-tracking-for-axis-estimation/)]
  [2024.09]
  
- Ali Badiezadeh, Amin Malekmohammadi, Seyed Mostafa Mirhassani, Parisa Gifani, Majid Vafaeezadeh.<br />
  "Segmentation Strategies in Deep Learning for Prostate Cancer Diagnosis: A Comparative Study of Mamba, SAM, and YOLO." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.16205)] 
  [[code](http://github.com/alibdz/prostate-segmentation)]
  [2024.09]

- Sunoh Lee, Minsik Jeon, Jihong Min, Junwon Seo.<br />
  "Open-World Object Detection with Instance Representation Learning." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.16073)] 
  [[code](https://sunohlee.github.io/OWODRep/)]
  [2024.09]

- **CAD:** Joohyeok Kim, Joonhyeon Song, Seohwan Yun, Seongho Yoon, Sangmin Lee.<br />
  "CAD: Memory Efficient Convolutional Adapter for Segment Anything." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.15889)] 
  [[code](https://github.com/Kyyle2114/Convolutional-Adapter-for-Segment-Anything)]
  [2024.09]

- **UOIS-SAM:** Rui Cao, Chuanxin Song, Biqi Yang, Jiangliu Wang, Pheng-Ann Heng, Yun-Hui Liu.<br />
  "Adapting Segment Anything Model for Unseen Object Instance Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.15481)] 
  [2024.09]

- **SOS:** Christian Wilms, Tim Rolff, Maris Hillemann, Robert Johanson, Simone Frintrop.<br />
  "SOS: Segment Object System for Open-World Instance Segmentation With Object Priors." ECCV (2024).
  [[paper](https://arxiv.org/abs/2409.14627)] 
  [[code](https://github.com/chwilms/SOS)]
  [2024.09]

- **EvanySeg:** Ahjol Senbi, Tianyu Huang, Fei Lyu, Qing Li, Yuhui Tao, Wei Shao, Qiang Chen, Chengyan Wang, Shuo Wang, Tao Zhou, Yizhe Zhang.<br />
  "Towards Ground-truth-free Evaluation of Any Segmentation in Medical Images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.14874)] 
  [[code](https://github.com/ahjolsenbics/EvanySeg)]
  [2024.09]

- **SAMEdge:** Rui Lu, Siping Shi, Yanting Liu, Dan Wang.<br />
  "SAMEdge: An Edge-cloud Video Analytics Architecture for the Segment Anything Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.14784)] 
  [2024.09]

- **AdvImmu:** Wei-Bin Kou, Guangxu Zhu, Rongguang Ye, Shuai Wang, Qingfeng Lin, Ming Tang, Yik-Chung Wu.<br />
  "An Adverse Weather-Immune Scheme with Unfolded Regularization and Foundation Model Knowledge Distillation for Street Scene Understanding." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.14737)] 
  [[code](XXXXXXXXXXXXXXXXXXXXXX)]
  [2024.09]

- **VTA:** Yuchen Hu, Yu Gu, Chenxing Li, Rilin Chen, Dong Yu.<br />
  "Video-to-Audio Generation with Fine-grained Temporal Semantics." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.14709)] 
  [[code](https://sounddemos.github.io/vta-sam/)]
  [2024.09]

- Kundan Chaudhary, Subhei Shaar, Raja Muthinti.<br />
  "Deep learning for fast segmentation and critical dimension metrology & characterization enabling AR/VR design and fabrication." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.13951)] 
  [2024.09]

- **S-AModal:** Jasmin Breitenstein, Franz Jünger, Andreas Bär, Tim Fingscheidt.<br />
  "Foundation Models for Amodal Video Instance Segmentation in Automated Driving." ECCV VCAD Workshop (2024).
  [[paper](https://arxiv.org/abs/2409.14095)] 
  [[code](https://github.com/ifnspaml/S-AModal)]
  [2024.09]

- **MGLMM:** Li Zhou, Xu Yuan, Zenghui Sun, Zikun Zhou, Jingsong Lan.<br />
  "Instruction-guided Multi-Granularity Segmentation and Captioning with Large Multimodal Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.13407)] 
  [[code](https://github.com/lizhou-cs/mglmm)]
  [2024.09]

- **PointSAM:** Nanqing Liu, Xun Xu, Yongyi Su, Haojie Zhang, Heng-Chao Li.<br />
  "PointSAM: Pointly-Supervised Segment Anything Model for Remote Sensing Images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.13401)] 
  [[code](https://github.com/Lans1ng/PointSAM)]
  [2024.09]

- **MCICSAM:** Guantian Huang, Beibei Li, Xiaobing Fan, Aritrick Chatterjee, Cheng Wei, Shouliang Qi, Wei Qian, Dianning He.<br />
  "MCICSAM: Monte Carlo-guided Interpolation Consistency Segment Anything Model for Semi-Supervised Prostate Zone Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.13371)] 
  [2024.09]

- Francis Ogoke, Sumesh Kalambettu Suresh, Jesse Adamczyk, Dan Bolintineanu, Anthony Garland, Michael Heiden, Amir Barati Farimani.<br />
  "Deep Learning based Optical Image Super-Resolution via Generative Diffusion Models for Layerwise in-situ LPBF Monitoring." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.13171)] 
  [2024.09]

- Michele Carlo La Greca, Mirko Usuelli, Matteo Matteucci.<br />
  "Enhancing Agricultural Environment Perception via Active Vision and Zero-Shot Learning." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.12602)] 
  [[code](https://github.com/AIRLab-POLIMI/active-vision)]
  [2024.09]

- Ali, L., Alnajjar, F., Swavaf, M. et al.<br />
  "Evaluating segment anything model (SAM) on MRI scans of brain tumors." Scientific Reports (2024).
  [[paper](https://www.nature.com/articles/s41598-024-72342-x)] 
  [2024.09]

- **SAM-RSIS:** Luo, Muying and Zhang, Tao and Wei, Shiqing and Ji, Shunping.<br />
  "SAM-RSIS: progressively adapting SAM with box prompting to remote sensing image instance segmentation." IEEE Transactions on Geoscience and Remote Sensing (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10680168)] 
  [2024.09]

- **EmbSAM:** Cunmin Zhao, Zelin Li, Pei Zhang, Yixuan Chen, Pohao Ye, Ming-Kin Wong, Lu-Yan Chan, Hong Yan, Chao Tang, Guoye Guan,  Zhongying Zhao.<br />
  "EmbSAM: Cell boundary localization and Segment Anything Model for fast images of developing embryos." ArXiv (2024).
  [[paper](https://www.biorxiv.org/content/10.1101/2024.09.07.611795v1.abstract)] 
  [2024.09]

- Bengtsson B R, Bengs J.<br />
  "Accelerated Segmentation with Mixed-Precision Quantization of EfficientViT-SAM." ArXiv (2024).
[[paper](https://lup.lub.lu.se/luur/download?func=downloadFile&recordOId=9174462&fileOId=9174463)] 
  [2024.09]

- Pengzhou Cai, Xueyuan Zhang, Libin Lan, Ze Zhao.<br />
  "Cross-Organ and Cross-Scanner Adenocarcinoma Segmentation using Rein to Fine-tune Vision Foundation Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.11752)] 
  [[code](https://github.com/ZhiJianLife/cosas2024_Zhijian-Life)]
  [2024.09]

- Ali, L., Alnajjar, F., Swavaf, M. et al.<br />
  "Evaluating segment anything model (SAM) on MRI scans of brain tumors." Scientific Reports (2024).
  [[paper](https://www.nature.com/articles/s41598-024-72342-x)] 
  [2024.09]

- Sigurðardóttir, Andrea Rakel, Hildur Inga Sveinsdóttir, Nette Schultz, Hafsteinn Einarsson, and María Gudjónsdóttir.<br />
  "Sequence Segmentation of Nematodes in Atlantic Cod with Multispectral Imaging Data." Foods (2024).
[[paper](https://www.mdpi.com/2304-8158/13/18/2952#:~:text=VideometerLab%204,%20an%20advanced%20Multispectral%20Imaging)] 
  [2024.09]

- Kulyabin, Mikhail, Aleksei Zhdanov, Andrey Pershin, Gleb Sokolov, Anastasia Nikiforova, Mikhail Ronkin, Vasilii Borisov, and Andreas Maier.<br />
  "Segment Anything in Optical Coherence Tomography: SAM 2 for Volumetric Segmentation of Retinal Biomarkers." Bioengineering (2024).
[[paper](https://www.mdpi.com/2306-5354/11/9/940#:~:text=Optical%20coherence%20tomography%20(OCT)%20is%20a)] 
  [2024.09]

- **DAPSAM:** Zhikai Wei, Wenhui Dong, Peilin Zhou, Yuliang Gu, Zhou Zhao, Yongchao Xu.<br />
  "Prompting Segment Anything Model with Domain-Adaptive Prototype for Generalizable Medical Image Segmentation." MICCAI (2024).
  [[paper](https://arxiv.org/abs/2409.12522)] 
  [[code](https://github.com/wkklavis/DAPSAM)]
  [2024.09]

- **GraspSAM:** Sangjun Noh, Jongwon Kim, Dongwoo Nam, Seunghyeok Back, Raeyoung Kang, Kyoobin Lee.<br />
  "GraspSAM: When Segment Anything Model Meets Grasp Detection." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.12521)] 
  [[code](https://gistailab.github.io/graspsam/)]
  [2024.09]

- **FGSA-Net:** Shizhou Zhang, Dexuan Kong, Yinghui Xing, Yue Lu, Lingyan Ran, Guoqiang Liang, Hexu Wang, Yanning Zhang.<br />
  "Frequency-Guided Spatial Adaptation for Camouflaged Object Detection." IEEE TMM (2024).
  [[paper](https://arxiv.org/abs/2409.12421)] 
  [2024.09]

- **SAM4MLLM:** Yi-Chia Chen, Wei-Hua Li, Cheng Sun, Yu-Chiang Frank Wang, Chu-Song Chen.<br />
  "SAM4MLLM: Enhance Multi-Modal Large Language Model for Referring Expression Segmentation." ECCV (2024).
  [[paper](https://arxiv.org/abs/2409.10542)] 
  [[code](https://github.com/AI-Application-and-Integration-Lab/SAM4MLLM)]
  [2024.09]

- **AMRF:** Zheming Zuo, Joseph Smith, Jonathan Stonehouse, Boguslaw Obara.<br />
  "An Augmentation-based Model Re-adaptation Framework for Robust Image Segmentation." ECCVW (2024).
  [[paper](https://arxiv.org/abs/2409.09530)] 
  [2024.09]

- Xin Hu, Janet Wang, Jihun Hamm, Rie R Yotsu, Zhengming Ding.<br />
  "Enhancing Skin Disease Diagnosis: Interpretable Visual Concept Discovery with SAM Empowerment." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.09520)] 
  [2024.09]

- **YOLO-SAM 2:** Mobina Mansoori, Sajjad Shahabodini, Jamshid Abouei, Konstantinos N. Plataniotis, Arash Mohammadi.<br />
  "Self-Prompting Polyp Segmentation in Colonoscopy using Hybrid Yolo-SAM 2 Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.09484)] 
  [[code](https://github.com/sajjad-sh33/YOLO_SAM2)]
  [2024.09]

- **SAM-OCTA2:** Xinrun Chen, Chengliang Wang, Haojian Ning, Mengzhan Zhang, Mei Shen, Shiying Li.<br />
  "SAM-OCTA2: Layer Sequence OCTA Segmentation with Fine-tuned Segment Anything Model 2." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.09286)] 
  [[code](https://github.com/ShellRedia/SAM-OCTA2)]
  [2024.09]

- **TP-Mamba:** Hualiang Wang, Yiqun Lin, Xinpeng Ding, Xiaomeng Li.<br />
  "Tri-Plane Mamba: Efficiently Adapting Segment Anything Model for 3D Medical Images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.08492)] 
  [[code](https://github.com/xmed-lab/TP-Mamba)]
  [2024.09]

- Henninger, S.; Kellner, M.; Rombach, B.; Reiterer, A.<br />
  "Reducing Training Data Using Pre-Trained Foundation Models: A Case Study on Traffic Sign Segmentation Using the Segment Anything Model." Journal of Imaging (2024).
  [[paper](https://www.mdpi.com/2313-433X/10/9/220)] 
  [2024.09]

- Hayoung Lee1 , Kwangseob Kim2 , Kiwon Lee.<br />
  "Application of Geo-Segment Anything Model (SAM) Scheme to Water Body Segmentation: An Experiment Study Using CAS500-1 Images." Korean Journal of Remote Sensing (2024).
  [[paper](https://koreascience.kr/article/JAKO202424843419904.page)] 
  [2024.09]

- **YOLOv5-n and EdgeSAM-3×:** Hongtao Li,Yong Yang,Shengping Wang,Zhigao Chen &Linbang He.<br />
  "Automatic detection and extraction of lost shipping containers based on YOLO and the segment anything model."  Remote Sensing Letters (2024).
  [[paper](https://www.tandfonline.com/doi/abs/10.1080/2150704X.2024.2398814)] 
  [2024.09]

- Kulyabin M, Zhdanov A, Pershin A, et al.<br />
  "Segment Anything in OCT: SAM 2 for Volumetric Segmentation of Retinal Biomarkers." ArXiv (2024).
  [[paper](https://www.preprints.org/manuscript/202409.0703/v1)] 
  [2024.09]

- **WaterSAM:** Hong, Yang, Xiaowei Zhou, Ruzhuang Hua, Qingxuan Lv, and Junyu Dong.<br />
  "WaterSAM: Adapting SAM for Underwater Object Segmentation." Journal of Marine Science and Engineering (2024).
  [[paper](https://www.mdpi.com/2077-1312/12/9/1616)] 
  [2024.09]

- **HQHSAM:** Kerem Cekmeceli, Meva Himmetoglu, Guney I. Tombak, Anna Susmelj, Ertunc Erdil, Ender Konukoglu.<br />
  "Do Vision Foundation Models Enhance Domain Generalization in Medical Image Segmentation?." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.07960)] 
  [[code](https://github.com/kerem-cekmeceli/Foundation-Models-for-Medical-Imagery)]
  [2024.09]

- **SimMAT:** Chenyang Lei, Liyi Chen, Jun Cen, Xiao Chen, Zhen Lei, Felix Heide, Ziwei Liu, Qifeng Chen, Zhaoxiang Zhang.<br />
  "SimMAT: Exploring Transferability from Vision Foundation Models to Any Image Modality." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.08083)] 
  [[code](https://github.com/mt-cly/SimMAT)]
  [2024.09]

- Shilin Hu, Hieu Le, ShahRukh Athar, Sagnik Das, Dimitris Samaras.<br />
  "Shadow Removal Refinement via Material-Consistent Shadow Edges." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.06848)] 
  [2024.09]

- **SoftShadow:** Xinrui Wang, Lanqing Guo, Xiyu Wang, Siyu Huang, Bihan Wen.<br />
  "SoftShadow: Leveraging Penumbra-Aware Soft Masks for Shadow Removal." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.07041)] 
  [[code](https://github.com/Xinrui014/SoftShadow/)]
  [2024.09]

- **PaveSAM:** Neema Jakisa Owor, Yaw Adu-Gyamfi, Armstrong Aboah, Mark Amo-Boateng.<br />
  "PaveSAM Segment Anything for Pavement Distress." Road Materials and Pavement Design (2024).
  [[paper](https://arxiv.org/abs/2409.07295)] 
  [2024.09]

- **Swin-LiteMedSAM:** Ruochen Gao, Donghang Lyu, Marius Staring.<br />
  "Swin-LiteMedSAM: A Lightweight Box-Based Segment Anything Model for Large-Scale Medical Image Datasets." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.07172)] 
  [[code](https://github.com/RuochenGao/Swin_LiteMedSAM)]
  [2024.09]

- **Sam2Rad:** Assefa Seyoum Wahd, Banafshe Felfeliyan, Yuyue Zhou, Shrimanti Ghosh, Adam McArthur, Jiechen Zhang, Jacob L. Jaremko, Abhilash Hareendranathan.<br />
  "Sam2Rad: A Segmentation Model for Medical Images with Learnable Prompts." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.06821)] 
  [2024.09]

- **SimIRSTD:** Mingjin Zhang, Chi Zhang, Qiming Zhang, Yunsong Li, Xinbo Gao, Jing Zhang.<br />
  "Unleashing the Power of Generic Segmentation Models: A Simple Baseline for Infrared Small Target Detection." ACM MM (2024).
  [[paper](https://arxiv.org/abs/2409.04714)] 
  [[code](https://github.com/O937-blip/SimIR)]
  [2024.09]

- **SSFam:** Zhengyi Liu, Sheng Deng, Xinrui Wang, Linbo Wang, Xianyong Fang, Bin Tang.<br />
  "SSFam: Scribble Supervised Salient Object Detection Family." TMM (2024).
  [[paper](https://arxiv.org/abs/2409.04817)] 
  [[code](https://github.com/liuzywen/SSFam)]
  [2024.09]

- **TAVP:** Jiaqi Yang, Ye Huang, Xiangjian He, Linlin Shen, Guoping Qiu.<br />
  "TAVP: Task-Adaptive Visual Prompt for Cross-domain Few-shot Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.05393)] 
  [2024.09]

- **AnomalyCD:** Jingtao Li, Qian Zhu, Xinyu Wang, Hengwei Zhao, Yanfei Zhong.<br />
  "AnomalyCD: A benchmark for Earth anomaly change detection with high-resolution and time-series observations." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.05679)] 
  [2024.09]

- **GeSCF:** Jaewoo Kim, Uehwan Kim.<br />
  "Towards Generalizable Scene Change Detection." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.06214)] 
  [2024.09]
  
- Giulio Passerotti, Alberto Alberello, Marcello Vichi, Luke G. Bennetts, Alessandro Toffoli.<br />
  "Segmenting sea ice floes in close-range optical imagery with active contour and foundation models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.06641)] 
  [2024.09]

- **EGFS:** Ting-Ru Liu, Hsuan-Kung Yang, Jou-Min Liu, Chun-Wei Huang, Tsung-Chih Chiang, Quan Kong, Norimasa Kobori, Chun-Yi Lee.<br />
  "Reprojection Errors as Prompts for Efficient Scene Coordinate Regression." ECCV (2024).
  [[paper](https://arxiv.org/abs/2409.04178)] 
  [[code](https://tingru0203.github.io/egfs)]
  [2024.09]

- **FS-MedSAM2:** Yunhao Bai, Qinji Yu, Boxiang Yun, Dakai Jin, Yingda Xia, Yan Wang.<br />
  "FS-MedSAM2: Exploring the Potential of SAM2 for Few-Shot Medical Image Segmentation without Fine-tuning." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.04298)] 
  [[code](https://github.com/DeepMed-Lab-ECNU/FS_MedSAM2)]
  [2024.09]

- **M2Trans:** Ni, Zhangkai and Xiao, Runyu and Yang, Wenhan and Wang, Hanli and Wang, Zhihua and Xiang, Lihua and Sun, Liping.<br />
  "M2Trans: Multi-Modal Regularized Coarse-to-Fine Transformer for Ultrasound Image Super-Resolution." IEEE Journal of Biomedical and Health Informatics (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10663841)] 
  [2024.09]

- Pablo Delgado-Rodriguez, Roman Kinakh, Rafael Aldabe, Arrate Munoz-Barrutia.<br />
  "SAM-based Automatic Workflow for Histology Cyst Segmentation in Autosomal Dominant Polycystic Kidney Disease." ArXiv (2024).
  [[paper](https://www.biorxiv.org/content/10.1101/2024.09.02.610807v1.abstract)] 
  [2024.09]

- **pix2pixGAN:** Amir Syahmi, Xiangrong Lu, Yinxuan Li, Haoxuan Yao, Hanjun Jiang, Ishita Acharya, Shiyi Wang, Yang Nan, Xiaodan Xing, Guang Yang.<br />
  "Coupling AI and Citizen Science in Creation of Enhanced Training Dataset for Medical Image Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.03087)] 
  [[code](https://github.com/Am1rSy/SGC-Enhanced-Dataset)]
  [2024.09]

- **BF-SAM::** Zhaoya Gong, Binbo Li, Chenglong Wang, Jun Chen & Pengjun Zhao.<br />
  "BF-SAM: enhancing SAM through multi-modal fusion for fine-grained building function identification." International Journal of Geographical Information Science (2024).
  [[paper](https://www.tandfonline.com/doi/abs/10.1080/13658816.2024.2399142)] 
  [2024.09]

- **LOBSTAR:** Yanming Xiu, Tim Scargill, Maria Gorlatova.<br />
  "LOBSTAR: Language Model-based Obstruction Detection for Augmented Reality." ArXiv (2024).
  [[paper](https://www.researchgate.net/profile/Maria-Gorlatova-2/publication/383427522_LOBSTAR_Language_Model-based_Obstruction_Detection_for_Augmented_Reality/links/66cd31c575613475fe7f5d6e/LOBSTAR-Language-Model-based-Obstruction-Detection-for-Augmented-Reality.pdf)] 
  [2024.09]

- Sebastian Sepulveda, Benjamin Bustos, Ivan Sipiran.<br />
  "Repetitive Patterns Recognition in Textures of Ancient Peruvian Pottery." ACM Journal on Computing and Cultural Heritage (2024).
  [[paper](https://dl.acm.org/doi/abs/10.1145/3694789)] 
  [2024.09]

- **RoVi-Aug:** Lawrence Yunliang Chen, Chenfeng Xu, Karthik Dharmarajan, Zubair Irshad, Richard Cheng, Kurt Keutzer, Masayoshi Tomizuka, Quan Vuong, Ken Goldberg.<br />
  "RoVi-Aug: Robot and Viewpoint Augmentation for Cross-Embodiment Robot Learning." CoRL (2024).
  [[paper](https://arxiv.org/abs/2409.03403)] 
  [2024.09]

- **DecoAD:** Chenglizhao Chen, Xinyu Liu, Mengke Song, Luming Li, Xu Yu, Shanchen Pang.<br />
  "Unveiling Context-Related Anomalies: Knowledge Graph Empowered Decoupling of Scene and Action for Human-Related Video Anomaly Detection." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.03236)] 
  [[code](https://github.com/liuxy3366/DecoAD)]
  [2024.09]

- **MouseSIS:** Friedhelm Hamann, Hanxiong Li, Paul Mieske, Lars Lewejohann, Guillermo Gallego.<br />
  "MouseSIS: A Frames-and-Events Dataset for Space-Time Instance Segmentation of Mice." ECCVW (2024).
  [[paper](https://arxiv.org/abs/2409.03358)] 
  [[code](https://github.com/tub-rip/MouseSIS)]
  [2024.09]

- **FrozenSeg:** Xi Chen, Haosen Yang, Sheng Jin, Xiatian Zhu, Hongxun Yao.<br />
  "FrozenSeg: Harmonizing Frozen Foundation Models for Open-Vocabulary Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.03525)] 
  [[code](https://github.com/chenxi52/FrozenSeg)]
  [2024.09]

- **TG-LMM:** Yihao Zhao, Enhao Zhong, Cuiyun Yuan, Yang Li, Man Zhao, Chunxia Li, Jun Hu, Chenbin Liu.<br />
  "TG-LMM: Enhancing Medical Image Segmentation Accuracy through Text-Guided Large Multi-Modal Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.03412)] 
  [2024.09]

- **InstanceSAM2Eval:** Tiantian Zhang, Zhangjun Zhou, Jialun Pei.<br />
  "Evaluation Study on SAM 2 for Class-agnostic Instance-level Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.02567)] 
  [[code](https://github.com/PJLallen/InstanceSAM2Eval)]
  [2024.09]

- **Curriculum-Prompting:** Xiuqi Zheng, Yuhang Zhang, Haoran Zhang, Hongrui Liang, Xueqi Bao, Zhuqing Jiang, Qicheng Lao.<br />
  "Curriculum Prompting Foundation Models for Medical Image Segmentation." MICCAI (2024).
  [[paper](https://arxiv.org/abs/2409.00695)] 
  [[code](https://github.com/AnnaZzz-zxq/Curriculum-Prompting)]
  [2024.09]

- **SAMTooth:** Yifan Liu, Wuyang Li, Cheng Wang, Hui Chen, Yixuan Yuan.<br />
  "When 3D Partial Points Meets SAM: Tooth Point Cloud Segmentation with Sparse Labels." MICCAI (2024).
  [[paper](https://arxiv.org/abs/2409.01691)] 
  [[code](https://github.com/CUHK-AIM-Group/SAMTooth)]
  [2024.09]

- **DPDEdit:** Xiaolong Wang, Zhi-Qi Cheng, Jue Wang, Xiaojiang Peng.<br />
  "DPDEdit: Detail-Preserved Diffusion Models for Multimodal Fashion Image Editing." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.01086)] 
  [2024.09]

- Liang Geng.<br />
  "Improving Apple Object Detection with Occlusion-Enhanced Distillation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.01573)] 
  [2024.09]

- **MedSAM-U:** Nan Zhou, Ke Zou, Kai Ren, Mengting Luo, Linchao He, Meng Wang, Yidi Chen, Yi Zhang, Hu Chen, Huazhu Fu.<br />
  "MedSAM-U: Uncertainty-Guided Auto Multi-Prompt Adaptation for Reliable MedSAM." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2409.00924)] 
  [2024.09]

- **FCSAM:** He, Dongzhi and Ma, Zeyuan and Li, Chenxi and Li, Yunqi.<br />
  "Dual‑branch Fully Convolutional Segment Anything Model for Lesion Segmentation in Endoscopic Images." ACCESS (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10646334)] 
  [2024.08]

- **PMHO:** Zhang, Shun and Long, Jihui and Xu, Yaohui and Mei, Shaohui.<br />
  "PMHO: Point-supervised Oriented Object Detection Based on Segmentation-Driven Proposal Generation." TGRS (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10649581)] 
  [2024.08]

- **CSAD:** Yu-Hsuan Hsieh, Shang-Hong Lai.<br />
  "CSAD: Unsupervised Component Segmentation for Logical Anomaly Detection." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.15628)] 
  [2024.08]

- Tanner D. Harms, Steven L. Brunton, Beverley J. McKeon.<br />
  "Estimating Dynamic Flow Features in Groups of Tracked Objects." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.16190)] 
  [2024.08]

- Setu, J. H.; Islam, M.; Pasha, S. T.; Halder, N.; Hossain, E.; Mahmud, A.; Islam, A.; Alam, M. Z.; Amin, M. A.<br />
  "Segment Anything Model (SAM 2) Unveiled: Functionality, Applications, and Practical Implementation Across Multiple Domains." ArXiv (2024).
  [[paper](https://www.preprints.org/manuscript/202408.1790/v1)] 
  [2024.08]

- Mani Abedini.<br />
  "Skin Cancer Classification by Leveraging Segment Anything Model for Semantic Segmentation of Skin Lesion." IJARCCE (2024).
[[paper](https://www.researchgate.net/profile/Mani-Abedini/publication/383303969_Skin_Cancer_Classification_by_Leveraging_Segment_Anything_Model_for_Semantic_Segmentation_of_Skin_Lesion/links/66c77e1c920e05672e46371b/Skin-Cancer-Classification-by-Leveraging-Segment-Anything-Model-for-Semantic-Segmentation-of-Skin-Lesion.pdf)] 
  [2024.08]

- **Ensembled-SAMs:** Chen, Fei and Ge, Junyao and Zheng, Yang and Guo, Kaitai and Cao, Feng and Liang, Jimin.<br />
  "Ensembled-SAMs for Enhanced Small Coronary Artery Segmentation in CCTA Images." JBHI (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10652248)] 
  [2024.08]

- Deshui Miao, Yameng Gu, Xin Li, Zhenyu He, Yaowei Wang, Ming-Hsuan Yang.<br />
  "Discriminative Spatial-Semantic VOS Solution: 1st Place Solution for 6th LSVOS." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.16431)] 
  [[code](https://github.com/yahooo-m/VOS-Solution)]
  [2024.08]

- **SAM2Point:** Ziyu Guo, Renrui Zhang, Xiangyang Zhu, Chengzhuo Tong, Peng Gao, Chunyuan Li, Pheng-Ann Heng.<br />
  "SAM2Point: Segment Any 3D as Videos in Zero-shot and Promptable Manners." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.16768)] 
  [[code](https://github.com/ZiyuGuo99/SAM2Point)]
  [2024.08]

- **SlotSAM:** Luyao Tang, Yuxuan Yuan, Chaoqi Chen, Kunze Huang, Xinghao Ding, Yue Huang.<br />
  "Bootstrap Segmentation Foundation Model under Distribution Shift via Object-Centric Learning." ECCVW (2024).
  [[paper](https://arxiv.org/abs/2408.16310)] 
  [[code](http://github.com/lytang63/SlotSAM)]
  [2024.08]

- Zhirui Gao, Renjiao Yi, Chenyang Zhu, Ke Zhuang, Wei Chen, Kai Xu.<br />
  "Generic Objects as Pose Probes for Few-Shot View Synthesis." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.16690)] 
  [2024.08]

- **AL-Ref-SAM2:** Shaofei Huang, Rui Ling, Hongyu Li, Tianrui Hui, Zongheng Tang, Xiaoming Wei, Jizhong Han, Si Liu.<br />
  "Unleashing the Temporal-Spatial Reasoning Capacity of GPT for Training-Free Audio and Language Referenced Video Object Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.15876)] 
  [[code](https://github.com/appletea233/AL-Ref-SAM2)]
  [2024.08]

- **SegmentWithSAM:** Zafer Yildiz, Yuwen Chen, Maciej A. Mazurowski.<br />
  "SAM & SAM 2 in 3D Slicer: SegmentWithSAM Extension for Annotating Medical Images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.15224)] 
  [[code](https://github.com/mazurowski-lab/SlicerSegmentWithSAM)]
  [2024.08]

- **Sammese:** Kunpeng Wang, Keke Chen, Chenglong Li, Zhengzheng Tu, Bin Luo.<br />
  "Adapting Segment Anything Model to Multi-modal Salient Object Detection with Semantic Feature Fusion Guidance." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.15063)] 
  [2024.08]

- **YOLO + SAM:** Samir Kassam, Angelo Markham, Katie Vo, Yashas Revanakara, Michael Lam, Kevin Zhu.<br />
  "Intraoperative Glioma Segmentation with YOLO + SAM for Improved Accuracy in Tumor Resection." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.14847)] 
  [2024.08]

- **PropSAM:** Zifan Chen, Xinyu Nan, Jiazheng Li, Jie Zhao, Haifeng Li, Zilin Lin, Haoshen Li, Heyun Chen, Yiting Liu, Bin Dong, Li Zhang, Lei Tang.<br />
  "PropSAM: A Propagation-Based Model for Segmenting Any 3D Objects in Multi-Modal Medical Images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.13836)] 
  [2024.08]

- **FusionSAM:** Daixun Li, Weiying Xie, Mingxiang Cao, Yunke Wang, Jiaqing Zhang, Yunsong Li, Leyuan Fang, Chang Xu.<br />
  "FusionSAM: Latent Space driven Segment Anything Model for Multimodal Fusion and Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.13980)] 
  [2024.08]

- **SAMesh:** George Tang, William Zhao, Logan Ford, David Benhaim, Paul Zhang.<br />
  "Segment Any Mesh: Zero-shot Mesh Part Segmentation via Lifting Segment Anything 2 to 3D." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.13679)] 
  [[code](https://github.com/gtangg12/samesh)]
  [2024.08]

- Kai Nichols, Matthew Hauwiller, Nicholas Propes, Shaowei Wu, Stephanie Hernandez, Mike Kautzky.<br />
  "Segment Anything Model for Grain Characterization in Hard Drive Design." CVPRW (2024).
  [[paper](https://arxiv.org/abs/2408.12732)] 
  [2024.08]

- **VALE:** Purushothaman Natarajan, Athira Nambiar.<br />
  "VALE: A Multimodal Visual and Language Explanation Framework for Image Classifiers using eXplainable AI and Language Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.12808)] 
  [2024.08]

- **S3Simulator:** Kamal Basha S, Athira Nambiar.<br />
  "S3Simulator: A benchmarking Side Scan Sonar Simulator dataset for Underwater Image Analysis." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.12833)] 
  [[code](https://github.com/bashakamal/S3Simulator)]
  [2024.08]

- **frg-bgr-modeling:** Lukas Picek, Lukas Neumann, Jiri Matas.<br />
  "Animal Identification with Independent Foreground and Background Modeling." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.12930)] 
  [[code](https://github.com/BohemianVRA/frg-bgr-modeling)]
  [2024.08]

- **3DSAM-adapter:** Shizhan Gong, Yuan Zhong, Wenao Ma, Jinpeng Li, Zhao Wang, Jingyang Zhang, Pheng-Ann Heng, Qi Dou.<br />
  "3DSAM-adapter: Holistic adaptation of SAM from 2D to 3D for promptable tumor segmentation." MIA (2024).
  [[paper](https://www.sciencedirect.com/science/article/pii/S1361841524002494)] 
  [[code](https://github.com/med-air/3DSAM-adapter)]
  [2024.08]

- Xiangru Li, Yifei Zhang, Liang Zhao.<br />
  "Multi-prompt Fine-Tuning of Foundation Models for Enhanced Biomedical Image Segmentation." ArXiv (2024).
  [[paper](https://link.springer.com/chapter/10.1007/978-3-031-63592-2_7)] 
  [2024.08]

- Xinyu Liu, Jing Zhang, Kexin Zhang, Xu Liu, Lingling Li.<br />
  "LSVOS Challenge 3rd Place Report: SAM2 and Cutie based VOS." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.10469)] 
  [2024.08]

- **SAM-SP:** Chunpeng Zhou, Kangjie Ning, Qianqian Shen, Sheng Zhou, Zhi Yu, Haishuai Wang.<br />
  "SAM-SP: Self-Prompting Makes SAM Great Again." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.12364)] 
  [2024.08]

- **GSAM:** Sota Kato, Hinako Mitsuoka, Kazuhiro Hotta.<br />
  "Generalized SAM: Efficient Fine-Tuning of SAM for Variable Input Image Sizes." ECCVW (2024).
  [[paper](https://arxiv.org/abs/2408.12406)] 
  [2024.08]

- Tuyen Tran.<br />
  "The 2nd Solution for LSVOS Challenge RVOS Track: Spatial-temporal Refinement for Consistent Semantic Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.12447)] 
  [2024.08]

- **EmbodiedSAM:** Xiuwei Xu, Huangxing Chen, Linqing Zhao, Ziwei Wang, Jie Zhou, Jiwen Lu.<br />
  "EmbodiedSAM: Online Segment Any 3D Thing in Real Time." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.11811)] 
  [[code](https://xuxw98.github.io/ESAM/)]
  [2024.08]

- **NuSegDG:** Zhenye Lou, Qing Xu, Zekun Jiang, Xiangjian He, Zhen Chen, Yi Wang, Chenxin Li, Maggie M. He, Wenting Duan.<br />
  "NuSegDG: Integration of Heterogeneous Space and Gaussian Kernel for Domain-Generalized Nuclei Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.11787)] 
  [[code](https://github.com/xq141839/NuSegDG)]
  [2024.08]

- **SAM-REF:** Chongkai Yu, Anqi Li, Xiaochao Qu, Luoqi Liu, Ting Liu.<br />
  "SAM-REF: Rethinking Image-Prompt Synergy for Refinement in Segment Anything." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.11535)] 
  [2024.08]

- **VISTA:** Yufan He, Pengfei Guo, Yucheng Tang, Andriy Myronenko, Vishwesh Nath, Ziyue Xu, Dong Yang, Can Zhao, Daguang Xu, Wenqi Li.<br />
  "A Short Review and Evaluation of SAM2's Performance in 3D CT Image Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.11210)] 
  [[code](https://github.com/Project-MONAI/VISTA)]
  [2024.08]

- **SAM-COD:** Huafeng Chen, Pengxu Wei, Guangqian Guo, Shan Gao.<br />
  "SAM-COD: SAM-guided Unified Framework for Weakly-Supervised Camouflaged Object Detection." ECCV (2024).
  [[paper](https://arxiv.org/abs/2408.10760)] 
  [2024.08]

- Bin Cao, Yisi Zhang, Hanyi Wang, Xingjian He, Jing Liu.<br />
  "The Instance-centric Transformer for the RVOS Track of LSVOS Challenge: 3rd Place Solution." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.10541)] 
  [2024.08]

- **U-MedSAM:** Xin Wang, Xiaoyu Liu , Peng Huang, Pu Huang, , Shu Hu,Hongtu Zhu.<br />
  "U-MedSAM: Uncertainty-aware MedSAM for Medical Image Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/html/2408.08881v1)] 
  [[code](https://github.com/liangzw599/Co-developed-by-LiteMedSAM)]
  [2024.08]

- **SAM-driven MAE:** Dong Wang, Qi Wang, Weidong Min, Di Gai, Qing Han, Longfei Li & Yuhan Geng .<br />
  "SAM-driven MAE pre-training and background-aware meta-learning for unsupervised vehicle re-identification." CVM (2024).
  [[paper](https://link.springer.com/article/10.1007/s41095-024-0424-2)] 
  [2024.08]

- **MCA-SAM:** Ke Zhou and Zhongwei Qiu and Dongmei Fu.<br />
  "Multi-scale contrastive adaptor learning for segmenting anything in underperformed scenes." Neurocomputing (2024).
  [[paper](https://www.sciencedirect.com/science/article/pii/S0925231224011664)] 
  [2024.08]

- **SAM_MLoRA:** Lu, Xiaoyan and Weng, Qihao.<br />
  "Multi-LoRA Fine-Tuned Segment Anything Model for Urban Man-Made Object Extraction." IEEE TGRS (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10637992?casa_token=lp5kIKollDgAAAAA:zml_qFz2S7q7nn3Bb40pFTJHXO5eSDis1Lryn_b28b1oRpInn9W-Pw3G7rZsX1r8NSJIAyT0QzOT3A)] 
  [[code](https://github.com/xiaoyan07/SAM_MLoRA)]
  [2024.08]

- Wenhui Dong and Bo Du and Yongchao Xu.<br />
  "Source domain prior-assisted segment anything model for single domain generalization in medical image segmentation." Image and Vision Computing (2024).
  [[paper](https://www.sciencedirect.com/science/article/abs/pii/S0262885624003214)] 
  [2024.08]

- **SAM-UNet:** Sihan Yang, Haixia Bi, Hai Zhang, Jian Sun.<br />
  "SAM-UNet:Enhancing Zero-Shot Segmentation of SAM for Universal Medical Images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.09886)] 
  [[code](https://github.com/Hhankyangg/sam-unet)]
  [2024.08]

- **LCE:** Weiji Kong, Xun Gong, Juan Wang.<br />
  "LCE: A Framework for Explainability of DNNs for Ultrasound Image Based on Concept Discovery." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.09899)] 
  [2024.08]

- **MM-SAM:** Aoran Xiao, Weihao Xuan, Heli Qi, Yun Xing, Naoto Yokoya, Shijian Lu.<br />
  "Segment Anything with Multiple Modalities." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.09085)] 
  [[code](https://xiaoaoran.github.io/projects/MM-SAM)]
  [2024.08]

- **GoodSAM++:** Weiming Zhang, Yexin Liu, Xu Zheng, Lin Wang.<br />
  "GoodSAM++: Bridging Domain and Capacity Gaps via Segment Anything Model for Panoramic Semantic Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.09115)] 
  [2024.08]

- **IAVVC:** Jun Yan, Pengyu Wang, Danni Wang, Weiquan Huang, Daniel Watzenig, Huilin Yin.<br />
  "Segment-Anything Models Achieve Zero-shot Robustness in Autonomous Driving." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.09839)] 
  [[code](https://github.com/momo1986/robust_sam_iv)]
  [2024.08]

- **MVP-TIME:** Feiyu Pan, Hao Fang, Runmin Cong, Wei Zhang, Xiankai Lu.<br />
  "Video Object Segmentation via SAM 2: The 4th Solution for LSVOS Challenge VOS Track." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.10125)] 
  [2024.08]

- **Surgical SAM 2:** Haofeng Liu, Erli Zhang, Junde Wu, Mingxuan Hong, Yueming Jin.<br />
  "Surgical SAM 2: Real-time Segment Anything in Surgical Video by Efficient Frame Pruning." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.07931)] 
  [[code](https://github.com/jinlab-imvr/Surgical-SAM-2)]
  [2024.08]

- **SAM2-UNet:** Xinyu Xiong, Zihuang Wu, Shuangyi Tan, Wenxue Li, Feilong Tang, Ying Chen, Siying Li, Jie Ma, Guanbin Li.<br />
  "SAM2-UNet: Segment Anything 2 Makes Strong Encoder for Natural and Medical Image Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.08870)] 
  [[code](https://github.com/WZH0120/SAM2-UNet)]
  [2024.08]

- Lin Zhao, Xiao Chen, Eric Z. Chen, Yikang Liu, Terrence Chen, Shanhui Sun.<br />
  "Retrieval-augmented Few-shot Medical Image Segmentation with Foundation Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.08813)] 
  [2024.08]

- **OBMv2:** Kai Li, Jingbo Chen, Yupeng Deng, Yu Meng, Diyou Liu, Junxian Ma, Chenhao Wang.<br />
  "Extracting polygonal footprints in off-nadir images with Segment Anything Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.08645)] 
  [[code](https://github.com/likaiucas/OBM)]
  [2024.08]

- **MC-SAM SEG:** Linghao Zheng, Xinyang Pu, Feng Xu.<br />
  "Tuning a SAM-Based Model with Multi-Cognitive Visual Adapter to Remote Sensing Instance Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.08576)] 
  [2024.08]

- Sanchayan Vivekananthan.<br />
  "Comparative Analysis of Generative Models: Enhancing Image Synthesis with VAEs, GANs, and Stable Diffusion." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.08751)] 
  [2024.08]

- **DoRL:** Yongcheng Li, Lingcong Cai, Ying Lu, Cheng Lin, Yupeng Zhang, Jingyan Jiang, Genan Dai, Bowen Zhang, Jingzhou Cao, Xiangzhong Zhang, Xiaomao Fan.<br />
  "Domain-invariant Representation Learning via Segment Anything Model for Blood Cell Classification." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.07467)] 
  [[code](https://github.com/AnoK3111/DoRL)]
  [2024.08]

- **CWMV:** Pratik Vora, Sudipan Saha.<br />
  "Segment Using Just One Example." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.07393)] 
  [2024.08]

- **S-SAM:** Jay N. Paranjape, Shameema Sikder, S. Swaroop Vedula, Vishal M. Patel.<br />
  "S-SAM: SVD-based Fine-Tuning of Segment Anything Model for Medical Image Segmentation." MICCAI  (2024).
  [[paper](https://arxiv.org/abs/2408.06447)] 
  [[code](https://github.com/JayParanjape/SVDSAM)]
  [2024.08]

- Osher Rafaeli, Tal Svoray, Ariel Nahlieli.<br />
  "Prompt-Based Segmentation at Multiple Resolutions and Lighting Conditions using Segment Anything Model 2." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.06970)] 
  [2024.08]

- **BC-SAM:** Yongcheng Li, Lingcong Cai, Ying Lu, Yupeng Zhang, Jingyan Jiang, Genan Dai, Bowen Zhang, Jingzhou Cao, Xiangzhong Zhang, Xiaomao Fan.<br />
  "Towards Cross-Domain Single Blood Cell Image Classification via Large-Scale LoRA-based Segment Anything Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.06716)] 
  [[code](https://github.com/AnoK3111/BC-SAM)]
  [2024.08]

- Tahir Ahmad, Sudipan Saha.<br />
  "Specialized Change Detection using Segment Anything." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.06644)] 
  [2024.08]

- **Multi SAM 50:** Sophia J. Abraham, Jin Huang, Brandon RichardWebster, Michael Milford, Jonathan D. Hauenstein, Walter Scheirer.<br />
  "Enhancing Ecological Monitoring with Multi-Objective Optimization: A Novel Dataset and Methodology for Segmentation Algorithms." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.06356)] 
  [2024.08]

- **SAM-FNet:** Jia Wei, Yun Li, Meiyu Qiu, Hongyu Chen, Xiaomao Fan, Wenbin Lei.<br />
  "SAM-FNet: SAM-Guided Fusion Network for Laryngo-Pharyngeal Tumor Detection." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.05426)] 
  [[code](https://github.com/VVJia/SAM-FNet)]
  [2024.08]

- Athulya Sundaresan Geetha, Muhammad Hussain.<br />
  "From SAM to SAM 2: Exploring Improvements in Meta's Segment Anything Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.06305)] 
  [2024.08]

- Yosuke Yamagishi, Shouhei Hanaoka, Tomohiro Kikuchi, Takahiro Nakao, Yuta Nakamura, Yukihiro Nomura, Soichiro Miki, Takeharu Yoshikawa, Osamu Abe.<br />
  "Zero-shot 3D Segmentation of Abdominal Organs in CT Scans Using Segment Anything Model 2: Adapting Video Tracking Capabilities for 3D Medical Imaging." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.06170)] 
  [2024.08]

- **Polyp SAM 2:** Mobina Mansoori, Sajjad Shahabodini, Jamshid Abouei, Konstantinos N. Plataniotis, Arash Mohammadi.<br />
  "Polyp SAM 2: Advancing Zero shot Polyp Segmentation in Colorectal Cancer Detection." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.05892)] 
  [[code](https://github.com/sajjad-sh33/Polyp-SAM-2)]
  [2024.08]

- **One-shot-IRSTS:** Bingbing Dan, Meihui Li, Tao Tang, Jing Zhang.<br />
  "One Shot is Enough for Sequential Infrared Small Target Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.04823)] 
  [[code](https://github.com/D-IceIce/one-shot-IRSTS)]
  [2024.08]

- Andrew Seohwan Yu, Mohsen Hariri, Xuecen Zhang, Mingrui Yang, Vipin Chaudhary, Xiaojuan Li.<br />
  "Novel adaptation of video segmentation to 3D MRI: efficient zero-shot knee segmentation with SAM2." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.04762)] 
  [2024.08]

- **DuneSA:** Lu A, Jiang Z, Wu Z, et al.<br />
  "DuneSA: A SAM-based Approach with Domain-Specific Knowledge for Aeolian Dune Segmentation." GoodIT (2024).
  [[paper](https://dl.acm.org/doi/abs/10.1145/3677525.3678637)] 
  [2024.08]

- Jieming Yu, An Wang, Wenzhen Dong, Mengya Xu, Mobarakol Islam, Jie Wang, Long Bai, Hongliang Ren.<br />
  "SAM 2 in Robotic Surgery: An Empirical Evaluation for Robustness and Generalization in Surgical Video Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.04593)] 
  [2024.08]

- **SAM2-Adapter:** Tianrun Chen, Ankang Lu, Lanyun Zhu, Chaotao Ding, Chunan Yu, Deyi Ji, Zejian Li, Lingyun Sun, Papa Mao, Ying Zang.<br />
  "SAM2-Adapter: Evaluating & Adapting Segment Anything 2 in Downstream Tasks: Camouflage, Shadow, Medical Image Segmentation, and More." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.04579)] 
  [[code](http://tianrun-chen.github.io/SAM-Adaptor/)]
  [2024.08]

- **MDSAM:** Shixuan Gao, Pingping Zhang, Tianyu Yan, Huchuan Lu.<br />
  "Multi-Scale and Detail-Enhanced Segment Anything Model for Salient Object Detection." ACM MM (2024).
  [[paper](https://arxiv.org/abs/2408.04326)] 
  [[code](https://github.com/BellyBeauty/MDSAM)]
  [2024.08]

- Sourya Sengupta, Satrajit Chakrabarty, Ravi Soni.<br />
  "Is SAM 2 Better than SAM in Medical Image Segmentation?." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.04212)] 
  [2024.08]

- **PaveCap:** Blessing Agyei Kyem, Eugene Kofi Okrah Denteh, Joshua Kofi Asamoah, Armstrong Aboah.<br />
  "PaveCap: The First Multimodal Framework for Comprehensive Pavement Condition Assessment with Dense Captioning and PCI Estimation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.04110)] 
  [2024.08]

- Yiqing Shen, Hao Ding, Xinyuan Shao, Mathias Unberath.<br />
  "Performance and Non-adversarial Robustness of the Segment Anything Model 2 in Surgical Video Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.04098)] 
  [2024.08]

- **SAM2-PATH:** Mingya Zhang, Liang Wang, Limei Gu, Zhao Li, Yaohui Wang, Tingshen Ling, Xianping Tao.<br />
  "SAM2-PATH: A better segment anything model for semantic segmentation in digital pathology." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.03651)] 
  [[code](https://github.com/simzhangbest/SAM2PATH)]
  [2024.08]
  
- **MedSAM:** Jun Ma, Sumin Kim, Feifei Li, Mohammed Baharoon, Reza Asakereh, Hongwei Lyu, Bo Wang.<br />
  "Segment Anything in Medical Images and Videos: Benchmark and Deployment." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.03322)] 
  [[code](https://github.com/bowang-lab/MedSAM)]
  [2024.08]

- **BioSAM 2:** Zhiling Yan, Weixiang Sun, Rong Zhou, Zhengqing Yuan, Kai Zhang, Yiwei Li, Tianming Liu, Quanzheng Li, Xiang Li, Lifang He, Lichao Sun.<br />
  "Biomedical SAM 2: Segment Anything in Biomedical Images and Videos." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.03286)] 
  [2024.08]

- **UnderwaterSAM2Eval:** Shijie Lian, Hua Li.<br />
  "Evaluation of Segment Anything Model 2: The Role of SAM2 in the Underwater Environment." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.02924)] 
  [[code](https://github.com/LiamLian0727/UnderwaterSAM2Eval)]
  [2024.08]

- **SAM_2_Medical_3D:** Chuyun Shen, Wenhao Li, Yuhang Shi, Xiangfeng Wang.<br />
  "Interactive 3D Medical Image Segmentation with SAM 2." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.02635)] 
  [[code](https://github.com/Chuyun-Shen/SAM_2_Medical_3D)]
  [2024.08]

- **PromptSAM+:** Xingyuan Wei, Yichen Liu, Ce Li, Ning Li, Degang Sun, Yan Wang.<br />
  "PromptSAM+: Malware Detection based on Prompt Segment Anything Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.02066)] 
  [2024.08]

- **PanicleNeRF:** Xin Yang1,2 , Xuqi Lu1,2 , Pengyao Xie1,2 , Ziyue Guo1,2 , Hui Fang1 , Haowei Fu3 , Xiaochun Hu4 , Zhenbiao Sun4 , Haiyan Cen1,2*.<br />
  "PanicleNeRF: low-cost, high-precision in-field phenotypingof rice panicles with smartphone." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.02053)] 
  [2024.08]

- **TS-SAM:** Yang Yu, Chen Xu, Kai Wang.<br />
  "TS-SAM: Fine-Tuning Segment-Anything Model for Downstream Tasks." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.01835)] 
  [[code](https://github.com/maoyangou147/TS-SAM)]
  [2024.08]

- **CUB FG:** Yuetian Wang, Wenjin Hou, Qinmu Peng, Xinge You.<br />
  "What Happens Without Background? Constructing Foreground-Only Data for Fine-Grained Tasks." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.01998)] 
  [2024.08]

- Ange Lou, Yamin Li, Yike Zhang, Robert F. Labadie, Jack Noble.<br />
  "Zero-Shot Surgical Tool Segmentation in Monocular Video Using Segment Anything Model 2." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.01648)] 
  [[project](https://github.com/AngeLouCN/SAM-2_Surgical_Video)]
  [2024.08]

- **MedSAM-2:** Jiayuan Zhu, Yunli Qi, Junde Wu.<br />
  "Medical SAM 2: Segment medical images as video via Segment Anything Model 2." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.00874)] 
  [[code](https://github.com/MedicineToken/Medical-SAM2)]
  [2024.08]

- **SnapSeg:** Yu N, Cai¹ Z, Huang Y, et al.<br />
  "SnapSeg: Training-Free Few-Shot Medical Image Segmentation with Segment Anything Model." Trustworthy Artificial Intelligence for Healthcare: Second International Workshop (2024).
[[paper](https://books.google.com.hk/books?hl=zh-CN&lr=&id=x1kXEQAAQBAJ&oi=fnd&pg=PA109&ots=iJlRIa7H97&sig=03iYXwjbNdCcL7EKNAq7SR242mM&redir_esc=y#v=onepage&q&f=false)] 
  [2024.08]

- Feng Liu, Qinlong Zhang, Weijie Zhang, Deqiang Cheng, Feng Zhang, Yating Deng, Guanzhen Yu.<br />
  "An analysis on efficacy of applying β-elemene intervention on chemically -induced tongue lesions using SAM algorithm." Anatomia, Histologia, Embryologia (2024).
  [[paper](https://onlinelibrary.wiley.com/doi/abs/10.1111/ahe.13095)] 
  [2024.08]

- **MSP-MVS:** Zhenlong Yuan, Cong Liu, Fei Shen, Zhaoxin Li, Tianlu Mao, Zhaoqi Wang.<br />
  "MSP-MVS: Multi-granularity Segmentation Prior Guided Multi-View Stereo." AAAI (2024).
  [[paper](https://arxiv.org/abs/2407.19323)] 
  [2024.08]

- Sae-Jin Park, Cheonghwa Lee, Kisu Ok and Sung-Hoon Ahn.<br />
  "Enhancing Aviation Safety: An Automated System for FOD Detection and Removal in Support Vehicle Tires." AIAA Aviation Forum and ASCEND (2024).
  [[paper](https://arc.aiaa.org/doi/abs/10.2514/6.2024-3806)] 
  [2024.08]

- **Theia:** Jinghuan Shang, Karl Schmeckpeper, Brandon B. May, Maria Vittoria Minniti, Tarik Kelestemur, David Watkins, Laura Herlant.<br />
  "Theia: Distilling Diverse Vision Foundation Models for Robot Learning." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.20179)] 
  [[code](https://github.com/bdaiinstitute/theia)]
  [2024.08]

- Haoyu Dong, Hanxue Gu, Yaqian Chen, Jichen Yang, Maciej A. Mazurowski.<br />
  "Segment anything model 2: an application to 2D and 3D medical images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.00756)] 
  [2024.08]

- Xiaofeng Liu, Jonghye Woo, Chao Ma, Jinsong Ouyang, Georges El Fakhri.<br />
  "Point-supervised Brain Tumor Segmentation with Box-prompted MedSAM." IEEE NSS and MIC (2024).
  [[paper](https://arxiv.org/abs/2408.00706)]
  [2024.08]

- **DMESA:** Yesheng Zhang, Xu Zhao.<br />
  "DMESA: Densely Matching Everything by Segmenting Anything." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2408.00279)] 
  [[code](https://github.com/Easonyesheng/A2PM-MESA)]
  [2024.08]

- **CC-SAM:** Shreyank N Gowda, David A. Clifton.<br />
  "CC-SAM: SAM with Cross-feature Attention and Context for Ultrasound Image Segmentation." ECCV (2024).
  [[paper](https://arxiv.org/abs/2408.00181)] 
  [2024.07]

- **SAMCOD:** Lv Tang, Bo Li.<br />
  "Evaluating SAM2's Role in Camouflaged Object Detection: From SAM to SAM2." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.21596)] 
  [[code](https://github.com/luckybird1994/SAMCOD)]
  [2024.07]

- **FLAP-SAM:** Mothilal Asokan, Joseph Geo Benjamin, Mohammad Yaqub, Karthik Nandakumar.<br />
  "A Federated Learning-Friendly Approach for Parameter-Efficient Fine-Tuning of SAM in 3D Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.21739)] 
  [[code](https://github.com/BioMedIA-MBZUAI/FLAP-SAM)]
  [2024.07]

- **RoBox-SAM:** Yuhao Huang, Xin Yang, Han Zhou, Yan Cao, Haoran Dou, Fajin Dong, Dong Ni.<br />
  "Robust Box Prompt based SAM for Medical Image Segmentation." MICCAI MLMI (2024).
  [[paper](https://arxiv.org/abs/2407.21284)] 
  [2024.07]

- Pascal Spiegler, Amirhossein Rasoulian, Yiming Xiao.<br />
  "Weakly Supervised Intracranial Hemorrhage Segmentation with YOLO and an Uncertainty Rectified Segment Anything Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.20461)] 
  [2024.07]

- **ICH:** Pascal Spiegler, Amirhossein Rasoulian, Yiming Xiao.<br />
  "Uncertainty-Rectified YOLO-SAM for Weakly Supervised ICH Segmentation." SWITCH (2024).
  [[paper](https://arxiv.org/abs/2407.20461)] 
  [2024.07]

- **ASI-Seg:** Zhen Chen, Zongming Zhang, Wenwu Guo, Xingjian Luo, Long Bai, Jinlin Wu, Hongliang Ren, Hongbin Liu.<br />
  "ASI-Seg: Audio-Driven Surgical Instrument Segmentation with Surgeon Intention Understanding." IROS  (2024).
  [[paper](https://arxiv.org/abs/2407.19435)] 
  [[code](https://github.com/Zonmgin-Zhang/ASI-Seg)]
  [2024.07]

- **Library Dataset:** Artemis Llabrés, Arka Ujjal Dey, Dimosthenis Karatzas, Ernest Valveny.<br />
  "Image-text matching for large-scale book collections." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.19812)] 
  [[code](https://github.com/llabres/library-dataset)]
  [2024.07]

- **AdaCLIP:** Yunkang Cao, Jiangning Zhang, Luca Frittoli, Yuqi Cheng, Weiming Shen, Giacomo Boracchi.<br />
  "AdaCLIP: Adapting CLIP with Hybrid Learnable Prompts for Zero-Shot Anomaly Detection." ECCV  (2024).
  [[paper](https://arxiv.org/abs/2407.15795)] 
  [[code](https://github.com/caoyunkang/AdaCLIP)]
  [2024.07]

- **VDST-Net:** Guiqiu Liao, Matjaz Jogan, Sai Koushik, Eric Eaton, Daniel A. Hashimoto.<br />
  "Disentangling spatio-temporal knowledge for weakly supervised object detection and segmentation in surgical video." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.15794)] 
  [2024.07]

- **PixLabelCV:** Dominik Schraml, et al.<br />
  "PixLabelCV - Labeling images for semantic segmentation fast, pixel-precise and offline." WSCG (2024).
  [[paper](http://wscg.zcu.cz/WSCG2024/CSRN-2024/A41-2024.pdf)] 
  [2024.07]

- **ESOD:** Kai Liu, Zhihang Fu, Sheng Jin, Ze Chen, Fan Zhou, Rongxin Jiang, Yaowu Chen, Jieping Ye.<br />
  "ESOD: Efficient Small Object Detection on High-Resolution Images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.16424)] 
  [2024.07]

- Ren Z, Zhang Y, Wang S.<br />
  "Large Foundation Model for Cancer Segmentation." Technology in Cancer Research & Treatment (2024).
  [[paper](https://journals.sagepub.com/doi/full/10.1177/15330338241266205)] 
  [2024.07]

- Guo Y, Xu Y, Cui H, Dang M, Li S.<br />
  "Segment anything model-based crack segmentation using low-rank adaption fine-tuning." Structural Health Monitoring (2024).
  [[paper](https://journals.sagepub.com/doi/full/10.1177/14759217241261089?casa_token=WiDbsTJZpVEAAAAA%3ACtTy7rKrvANH81yjADNAqqx7PAgDEbpsInJ59M10z88P4W38Boy8Haz2M4YfAliUrYMF5Igb2Hsma5G8)] 
  [2024.07]

- **SSTD:** Zijian Zhu, Ali Zia, Xuesong Li, Bingbing Dan, Yuebo Ma, Enhai Liu, Rujin Zhao.<br />
  "SSTD: Stripe-Like Space Target Detection using Single-Point Supervision." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.18097)] 
  [2024.07]

- **KneeSegmentWithSAM:** Yaxi Chen, Aleksandra Ivanova, Shaheer U. Saeed, Rikin Hargunani, Jie Huang, Chaozong Liu, Yipeng Hu.<br />
  "Segmentation by registration-enabled SAM prompt engineering using five reference images." WBIR (2024).
  [[paper](https://arxiv.org/abs/2407.17933)] 
  [[code](https://github.com/chrissyinreallife/KneeSegmentWithSAM.git)]
  [2024.07]

- **SAM-MIL:** Heng Fang, Sheng Huang, Wenhao Tang, Luwen Huangfu, Bo Liu.<br />
  "SAM-MIL: A Spatial Contextual Aware Multiple Instance Learning Approach for Whole Slide Image Classification." ACM  MM (2024).
  [[paper](https://arxiv.org/abs/2407.17689)] 
  [[code](https://github.com/FangHeng/SAM-MIL)]
  [2024.07]

- **SAM-CP:** Pengfei Chen, Lingxi Xie, Xinyue Huo, Xuehui Yu, Xiaopeng Zhang, Yingfei Sun, Zhenjun Han, Qi Tian.<br />
  "SAM-CP: Marrying SAM with Composable Prompts for Versatile Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.16682)] 
  [[code](https://github.com/ucas-vg/SAM-CP)]
  [2024.07]

- Jiyeop Kim, Jongwoo Lim.<br />
  "Integrating Meshes and 3D Gaussians for Indoor Scene Reconstruction with SAM Mask Guidance." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.16173)] 
  [2024.07]

- **SAM2CLIP2SAM:** Dimitrios Kollias, Anastasios Arsenos, James Wingate, Stefanos Kollias.<br />
  "SAM2CLIP2SAM: Vision Language Model for Segmentation of 3D CT Scans for Covid-19 Detection." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.15728)] 
  [2024.07]

- **MedSAGa:** Navyansh Mahla, Annie D'souza, Shubh Gupta, Bhavik Kanekar, Kshitij Sharad Jadhav.<br />
  "MedSAGa: Few-shot Memory Efficient Medical Image Segmentation using Gradient Low-Rank Projection in SAM." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.15042)] 
  [2024.07]

- **ESP-MedSAM:** Qing Xu, Jiaxuan Li, Xiangjian He, Ziyu Liu, Zhen Chen, Wenting Duan, Chenxin Li, Maggie M. He, Fiseha B. Tesema, Wooi P. Cheah, Yi Wang, Rong Qu, Jonathan M. Garibaldi.<br />
  "ESP-MedSAM: Efficient Self-Prompting SAM for Universal Domain-Generalized Medical Image Segmentation." IEEE TMI (2024).
  [[paper](https://arxiv.org/abs/2407.14153)] 
  [2024.07]

- **Semantic-CC:** Yongshuo Zhu, Lu Li, Keyan Chen, Chenyang Liu, Fugen Zhou, Zhenwei Shi.<br />
  "Semantic-CC: Boosting Remote Sensing Image Change Captioning via Foundational Knowledge and Semantic Guidance." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.14032)] 
  [2024.07]

- **Seismic Fault SAM:** Ran Chen, Zeren Zhang, Jinwen Ma.<br />
  "Seismic Fault SAM: Adapting SAM with Lightweight Modules and 2.5D Strategy for Fault Detection." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.14121)] 
  [2024.07]

- **VISA:** Cilin Yan, Haochen Wang, Shilin Yan, Xiaolong Jiang, Yao Hu, Guoliang Kang, Weidi Xie, Efstratios Gavves.<br />
  "VISA: Reasoning Video Object Segmentation via Large Language Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.11325)] 
  [[code](https://github.com/cilinyan/VISA)]
  [2024.07]

- **G-SAM:** Xiaoxiao Liu, Yan Zhao, Shigang Wang & Jian Wei .<br />
  "G-SAM: GMM-based segment anything model for medical image classification and segmentation." Cluster Comput (2024).
  [[paper](https://link.springer.com/article/10.1007/s10586-024-04679-x)] 
  [2024.07]

- **UniFSS:** Shijie Chang, Youwei Pang, Xiaoqi Zhao, Lihe Zhang, Huchuan Lu.<br />
  "Beyond Mask: Rethinking Guidance Types in Few-shot Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.11503)] 
  [2024.07]

- **TeethDreamer:** Chenfan Xu, Zhentao Liu, Yuan Liu, Yulong Dou, Jiamin Wu, Jiepeng Wang, Minjiao Wang, Dinggang Shen, Zhiming Cui.<br />
  "TeethDreamer: 3D Teeth Reconstruction from Five Intra-oral Photographs." MICCAI (2024).
  [[paper](https://arxiv.org/abs/2407.11419)] 
  [[code](https://github.com/ShanghaiTech-IMPACT/TeethDreamer)]
  [2024.07]

- **Corrosion SAM:** Chengzhang Chai, Yan Gao, Haijiang Li, Xiaofeng Zhu.<br />
  "Corrosion SAM: Adapting Segment Anything Model with Parameter-Efficient Fine-Tuning for Structural Corrosion Inspection." ArXiv (2024).
  [[paper](https://orca.cardiff.ac.uk/id/eprint/170405/1/Chai%2C%20Gao%2C%20Li%2C%20Zhu%20-%202024%20-%20Corrosion%20SAM%20Adapting%20Segment%20Anything%20Model%20with%20Parameter-Efficient%20Fine-Tuning%20for%20Structural%20Corrosion%20Inspection.pdf)] 
  [2024.07]

- **PartImageNet++:** Xiao Li, Yining Liu, Na Dong, Sitian Qin, Xiaolin Hu.<br />
  "PartImageNet++ Dataset: Scaling up Part-based Models for Robust Recognition." ECCV (2024).
  [[paper](https://arxiv.org/abs/2407.10918)] 
  [[code](https://github.com/LixiaoTHU/PartImageNetPP)]
  [2024.07]

- **TeSO:** Yaoting Wang, Peiwen Sun, Yuanchao Li, Honggang Zhang, Di Hu.<br />
  "Can Textual Semantics Mitigate Sounding Object Segmentation Preference?." ECCV (2024).
  [[paper](https://arxiv.org/abs/2407.10947)] 
  [[code](https://github.com/GeWu-Lab/Sounding-Object-Segmentation-Preference)]
  [2024.07]

- **FoodMem:** Ahmad AlMughrabi, Adrián Galán, Ricardo Marques, Petia Radeva.<br />
  "FoodMem: Near Real-time and Precise Food Video Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.12121)] 
  [2024.07]

- **SeFi-CD:** Ling Zhao, Zhenyang Huang, Dongsheng Kuang, Chengli Peng, Jun Gan, Haifeng Li.<br />
  "SeFi-CD: A Semantic First Change Detection Paradigm That Can Detect Any Change You Want." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.09874)] 
  [2024.07]

- Jaime Duque-Domingo, et al.<br />
  "Segmentaci ́on sem ́antica bajo paradigmaone-shot learning utilizando SAM y CP-CVV." Visión por Computador (2024).
  [[paper](https://revistas.udc.gal/index.php/JA_CEA/article/view/10772/8237)] 
  [2024.07]

- **DriveSAM:** K Kwakye, Y Seong, S Yi, A Aboah.<br />
  "DriveSAM: Cognitive Perspective on Driving Maneuvers Based on Drivers’ Attention Using Eye Gaze Data." IEOM International Conference on Smart Mobility and Vehicle Electrification (2024).
  [[paper](https://web.archive.org/web/20240313224050id_/https://ieomsociety.org/proceedings/2023detroit/71.pdf)] 
  [2024.07]

- **Swiss DINO:** Kirill Paramonov, Jia-Xing Zhong, Umberto Michieli, Jijoong Moon, Mete Ozay.<br />
  "Swiss DINO: Efficient and Versatile Vision Framework for On-device Personal Object Search." IROS (2024).
  [[paper](https://arxiv.org/abs/2407.07541)] 
  [[code](https://github.com/SamsungLabs/SwissDINO)]
  [2024.07]

- **ECoT:** Michał Zawalski, William Chen, Karl Pertsch, Oier Mees, Chelsea Finn, Sergey Levine.<br />
  "Robotic Control via Embodied Chain-of-Thought Reasoning." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.08693)] 
  [[code](https://embodied-cot.github.io/)]
  [2024.07]

- **CLIPtra:** Tong Shao, Zhuotao Tian, Hang Zhao, Jingyong Su.<br />
  "Explore the Potential of CLIP for Training-Free Open Vocabulary Semantic Segmentation." ECCV (2024).
  [[paper](https://arxiv.org/abs/2407.08268)] 
  [[code](https://github.com/leaves162/CLIPtrase)]
  [2024.07]

- **PaveSAM:** Neema Jakisa Owor, Yaw Adu-Gyamfi, Armstrong Aboah and Mark Amo-Boateng.<br />
  "PaveSAM – segment anything for pavement distress." RMPD (2024).
  [[paper](https://www.tandfonline.com/doi/abs/10.1080/14680629.2024.2374863?casa_token=C7E7eoFYe5kAAAAA:Q-ce5Dg7H6zrpo6t1QW_j9o5EvcWtaXM3CpF3GF5AunaaAQhFMGJeb6OuI2HwQ-byxyEOM8e2M2wvdUSJw)] 
  [2024.07]

- **UCE:** Shaozhe Hao, Kai Han, Zhengyao Lv, Shihao Zhao, Kwan-Yee K. Wong.<br />
  "ConceptExpress: Harnessing Diffusion Models for Single-image Unsupervised Concept Extraction." ECCV (2024).
  [[paper](https://arxiv.org/abs/2407.07077)] 
  [[code](https://github.com/haoosz/ConceptExpress)]
  [2024.07]

- **Pseudo-RIS:** Seonghoon Yu, Paul Hongsuck Seo, Jeany Son.<br />
  "Pseudo-RIS: Distinctive Pseudo-supervision Generation for Referring Image Segmentation." ECCV (2024).
  [[paper](https://arxiv.org/abs/2407.07412)] 
  [[code](https://github.com/Seonghoon-Yu/Pseudo-RIS)]
  [2024.07]

- **MeshSegmenter:** Ziming Zhong, Yanxu Xu, Jing Li, Jiale Xu, Zhengxin Li, Chaohui Yu, Shenghua Gao.<br />
  "MeshSegmenter: Zero-Shot Mesh Semantic Segmentation via Texture Synthesis." ECCV (2024).
  [[paper](https://arxiv.org/abs/2407.13675)] 
  [[code](https://github.com/zimingzhong/MeshSegmenter)]
  [2024.07]

- **SOSS:** Mario Francisco Munoz, Hoang Vu Huy, Thanh-Dung Le.<br />
  "Hybrid Deep Learning-Based for Enhanced Occlusion Segmentation in PICU Patient Monitoring." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.13341)] 
  [2024.07]

- Xingyue Zhao, Peiqi Li, Xiangde Luo, Meng Yang, Shi Chang, Zhongyu Li.<br />
  "SAM-Driven Weakly Supervised Nodule Segmentation with Uncertainty-Aware Cross Teaching." ISBI (2024).
  [[paper](https://arxiv.org/abs/2407.13553)] 
  [2024.07]

- Fryderyk Kögl, Anna Reithmeir, Vasiliki Sideri-Lampretsa, Ines Machado, Rickmer Braren, Daniel Rückert, Julia A. Schnabel, Veronika A. Zimmer.<br />
  "General Vision Encoder Features as Guidance in Medical Image Registration." WBIR MICCAI (2024).
  [[paper](https://arxiv.org/abs/2407.13311)] 
  [[code](https://github.com/compai-lab/2024-miccai-koegl)]
  [2024.07]

- **DSAM:** Zhenni Yu, Xiaoqin Zhang, Li Zhao, Yi Bin, Guobao Xiao.<br />
  "Exploring Deeper! Segment Anything Model with Depth Perception for Camouflaged Object Detection." ACM MM (2024).
  [[paper](https://arxiv.org/abs/2407.12339)] 
  [[code](https://github.com/guobaoxiao/DSAM)]
  [2024.07]
  
- **OMG-Net:** Zhuoyan Shen, Mikael Simard, Douglas Brand, Vanghelita Andrei, Ali Al-Khader, Fatine Oumlil, Katherine Trevers, Thomas Butters, Simon Haefliger, Eleanna Kara, Fernanda Amary, Roberto Tirabosco, Paul Cool, Gary Royle, Maria A. Hawkins, Adrienne M. Flanagan, Charles-Antoine Collins Fekete.<br />
  "OMG-Net: A Deep Learning Framework Deploying Segment Anything to Detect Pan-Cancer Mitotic Figures from Haematoxylin and Eosin-Stained Slides." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.12773)] 
  [2024.07]

- **FastSAM-3DSlicer:** Yiqing Shen, Xinyuan Shao, Blanca Inigo Romillo, David Dreizin, Mathias Unberath.<br />
  "FastSAM-3DSlicer: A 3D-Slicer Extension for 3D Volumetric Segment Anything Model with Uncertainty Quantification." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.12658)] 
  [[code](https://github.com/arcadelab/FastSAM3D_slicer)]
  [2024.07]


- **Crowd-SAM:** Zhi Cai, Yingjie Gao, Yaoyan Zheng, Nan Zhou, Di Huang.<br />
  "Crowd-SAM: SAM as a Smart Annotator for Object Detection in Crowded Scenes." ECCV (2024).
  [[paper](https://arxiv.org/abs/2407.11464)] 
  [[code](https://github.com/FelixCaae/CrowdSAM)]
  [2024.07]

- **SLF:** Jianhao Li, Tianyu Sun, Zhongdao Wang, Enze Xie, Bailan Feng, Hongbo Zhang, Ze Yuan, Ke Xu, Jiaheng Liu, Ping Luo.<br />
  "Segment, Lift and Fit: Automatic 3D Shape Labeling from 2D Prompts." ECCV (2024).
  [[paper](https://arxiv.org/abs/2407.11382)] 
  [2024.07]

- Yunya Gao.<br />
  "Leveraging Segment Anything Model in Identifying Buildings within Refugee Camps (SAM4Refugee) from Satellite Imagery for Humanitarian Operations." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.11381)] 
  [2024.07]

- **WPS-SAM:** Xinjian Wu, Ruisong Zhang, Jie Qin, Shijie Ma, Cheng-Lin Liu.<br />
  "WPS-SAM: Towards Weakly-Supervised Part Segmentation with Foundation Models." ECCV (2024).
  [[paper](https://arxiv.org/abs/2407.10131)] 
  [[code](https://github.com/xjwu1024/WPS-SAM)]
  [2024.07]

- **Lite-SAM:** Jianhai Fu, Yuanjie Yu, Ningchuan Li, Yi Zhang, Qichao Chen, Jianping Xiong, Jun Yin, Zhiyu Xiang.<br />
  "Lite-SAM Is Actually What You Need for Segment Everything." ECCV (2024).
  [[paper](https://arxiv.org/abs/2407.08965)] 
  [2024.07]

- **WSESeg:** Robin Schön, Daniel Kienzle, Rainer Lienhart.<br />
  "WSESeg: Introducing a Dataset for the Segmentation of Winter Sports Equipment with a Baseline for Interactive Segmentation." CBMI (2024).
  [[paper](https://arxiv.org/abs/2407.09288)] 
  [2024.07]

- **RAT:** Zhiwen Yang, Haowei Chen, Ziniu Qian, Yang Zhou, Hui Zhang, Dan Zhao, Bingzheng Wei, Yan Xu.<br />
  "Region Attention Transformer for Medical Image Restoration." MICCAI (2024).
  [[paper](https://arxiv.org/abs/2407.09268)] 
  [[code](https://github.com/Yaziwel/Region-Attention-Transformer-for-Medical-Image-Restoration.git)]
  [2024.07]

- **RveRNet:** Seonwhee Jin.<br />
  "Knowledge distillation to effectively attain both region-of-interest and global semantics from an image where multiple objects appear." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.08257)] 
  [[code](https://github.com/Seonwhee-Genome/RveRNet)]
  [2024.07]

- **CACP:** Qiushi Guo.<br />
  "Enrich the content of the image Using Context-Aware Copy Paste." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.08151)] 
  [2024.07]

- **PRISM-placenta:** Hao Li, Baris Oguz, Gabriel Arenas, Xing Yao, Jiacheng Wang, Alison Pouch, Brett Byram, Nadav Schwartz, Ipek Oguz.<br />
  "Interactive Segmentation Model for Placenta Segmentation from 3D Ultrasound images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.08020)] 
  [[code](https://github.com/MedICL-VU/PRISM-placenta)]
  [2024.07]

- **IRSAM:** Mingjin Zhang, Yuchun Wang, Jie Guo, Yunsong Li, Xinbo Gao, Jing Zhang.<br />
  "IRSAM: Advancing Segment Anything Model for Infrared Small Target Detection." ECCV (2024).
  [[paper](https://arxiv.org/abs/2407.07520)] 
  [[code](http://github.com/IPIC-Lab/IRSAM)]
  [2024.07]

- **ProtoSAM:** Lev Ayzenberg, Raja Giryes, Hayit Greenspan.<br />
  "ProtoSAM - One Shot Medical Image Segmentation With Foundational Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.07042)] 
  [2024.07]

- **CycleSAM:** Aditya Murali, Pietro Mascagni, Didier Mutter, Nicolas Padoy.<br />
  "CycleSAM: One-Shot Surgical Scene Segmentation using Cycle-Consistent Feature Matching to Prompt SAM." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.06795)] 
  [2024.07]

- **EWMA:** Ahmed Maged, Herman Shen.<br />
  "Unsupervised Fault Detection using SAM with a Moving Window Approach." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.06303)] 
  [2024.07]

- **DiffPNG:** Danni Yang, Ruohan Dong, Jiayi Ji, Yiwei Ma, Haowei Wang, Xiaoshuai Sun, Rongrong Ji.<br />
  "Exploring Phrase-Level Grounding with Text-to-Image Diffusion Model." ECCV (2024).
  [[paper](https://arxiv.org/abs/2407.05352)] 
  [[code](https://github.com/nini0919/DiffPNG)]
  [2024.07]

- **AO-Planner:** Jiaqi Chen, Bingqian Lin, Xinmin Liu, Xiaodan Liang, Kwan-Yee K. Wong.<br />
  "Affordances-Oriented Planning using Foundation Models for Continuous Vision-Language Navigation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.05890)] 
  [2024.07]

- **MBA-Net:** Yifan Gao, Wei Xia, Wenkui Wang, Xin Gao.<br />
  "MBA-Net: SAM-driven Bidirectional Aggregation Network for Ovarian Tumor Segmentation." MICCAI (2024).
  [[paper](https://arxiv.org/abs/2407.05984)] 
  [2024.07]

- **SAM-TAPIR:** Athena Psalta, Vasileios Tsironis, Andreas El Saer, Konstantinos Karantzalos.<br />
  "Addressing single object tracking in satellite imagery through prompt-engineered solutions." IGARSS (2024).
  [[paper](https://arxiv.org/abs/2407.05518)] 
  [2024.07]

- **CPC-SAM:** Juzheng Miao, Cheng Chen, Keli Zhang, Jie Chuai, Quanzheng Li, Pheng-Ann Heng.<br />
  "Cross Prompting Consistency with Segment Anything Model for Semi-supervised Medical Image Segmentation." MICCAI (2024).
  [[paper](https://arxiv.org/abs/2407.05416)] 
  [[code](https://github.com/JuzhengMiao/CPC-SAM)]
  [2024.07]

- **SAM-Med3D-MoE:** Guoan Wang, Jin Ye, Junlong Cheng, Tianbin Li, Zhaolin Chen, Jianfei Cai, Junjun He, Bohan Zhuang.<br />
  "SAM-Med3D-MoE: Towards a Non-Forgetting Segment Anything Model via Mixture of Experts for 3D Medical Image Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.04938)] 
  [2024.07]

- Longfei Huang, Feng Yu, Zhihao Guan, Zhonghua Wan, Yang Yang.<br />
  "The Solution for the 5th GCAIAC Zero-shot Referring Expression Comprehension Challenge." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.04998)] 
  [2024.07]

- Xudong Ma, Yuqi Zhang, Chenchong Wang, Wei Xu.<br />
  "Revolutionizing Alloy Microstructure Segmentation through SAM and Domain Knowledge without Extra Training." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.04922)] 
  [2024.07]

- **SA4D:** Shengxiang Ji, Guanjun Wu, Jiemin Fang, Jiazhong Cen, Taoran Yi, Wenyu Liu, Qi Tian, Xinggang Wang.<br />
  "Segment Any 4D Gaussians." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.04504)] 
  [[code](https://jsxzs.github.io/sa4d/)]
  [2024.07]

- Weiyi Xie, Nathalie Willems, Shubham Patil, Yang Li, Mayank Kumar.<br />
  "SAM Fewshot Finetuning for Anatomical Segmentation in Medical Images." WACV (2024).
  [[paper](https://arxiv.org/abs/2407.04651)] 
  [2024.07]

- **JFS:** Seonghyeon Moon, Haein Kong, Muhammad Haris Khan.<br />
  "Success or Failure? Analyzing Segmentation Refinement with Few-Shot Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.04519)] 
  [2024.07]

- **CS3:** Yi Shi, Xu-Peng Tian, Yun-Kai Wang, Tie-Yi Zhang, Bin Yao, Hui Wang, Yong Shao, Cen-Cen Wang, Rong Zeng, De-Chuan Zhan.<br />
  "CS3: Cascade SAM for Sperm Segmentation." MICCAI (2024).
  [[paper](https://arxiv.org/abs/2407.03772)] 
  [2024.07]

- **OneSAM:** Khanh-Binh Nguyen, Chae Jung Park.<br />
  "OneSAM: One model for segment anything model in medical images on Laptop." ArXiv (2024).
  [[paper](https://openreview.net/forum?id=2xpvozuFq5)] 
  [2024.07]

- Zdravko Marinov, Alexander Jaus, Jens Kleesiek, Rainer Stiefelhagen.<br />
  "Filters, Thresholds, and Geodesic Distances for Scribble-based Interactive Segmentation of Medical Images." CVPR Workshop (2024).
  [[paper](https://openreview.net/forum?id=FT3T2Dh1fg)] 
  [2024.07]

- Zdravko Marinov, Alexander Jaus, Jens Kleesiek, Rainer Stiefelhagen.<br />
  "Taking a Step Back: Revisiting Classical Approaches for Efficient Interactive Segmentation of Medical Images." CVPR Workshop (2024).
  [[paper](https://openreview.net/forum?id=lM99O5U8SE)] 
  [2024.07]

- SONGXIAO YANG, Yizhou Li, Ye Chen, Zhuofeng Wu, Masatoshi Okutomi.<br />
  "A Light-weight Universal Medical Segmentation Network for Laptops Based on Knowledge Distillation." ArXiv (2024).
  [[paper](https://openreview.net/forum?id=T3pEt7VkGT)] 
  [2024.07]

- Raphael Stock, Yannick Kirchhoff, Maximilian Rouven Rokuss, Ashis Ravindran, Klaus Maier-Hein.<br />
  "Segment Anything in Medical Images with nnUNet." CVPR Workshop (2024).
  [[paper](https://openreview.net/forum?id=N1uNPfYHFw)] 
  [2024.07]

- **QMedSAM:** Haisheng Lu, Yujie Fu, Fan Zhang, Le Zhang.<br />
  "Efficient Quantization-Aware Training on Segment Anything Model in Medical Images and Its Deployment." ArXiv (2024).
  [[paper](https://openreview.net/forum?id=Wbfy5Tf9WA)] 
  [[code](https://github.com/AVC2-UESTC/QMedSAM)]
  [2024.07]

- **RepMedSAM:** Zehan Zhang, Rui Huang, Ning Huang.<br />
  "RepMedSAM: Segment Anything in Medical Images with Lightweight CNN." CVPR Workshop (2024).
  [[paper](https://openreview.net/forum?id=AXeZItjN2z)] 
  [2024.07]

- **DAFT:** Alexander Tobias Pfefferle, Lennart Purucker, Frank Hutter.<br />
  "DAFT: Data-Aware Fine-Tuning of Foundation Models for Efficient and Effective Medical Image Segmentation." CVPR Workshop (2024).
  [[paper](https://openreview.net/forum?id=PObXviy706)] 
  [2024.07]

- **Swin-LiteMedSAM::** Ruochen Gao, Donghang Lyu.<br />
  "Swin-LiteMedSAM: A Lightweight Mulitple-Prompt-Based Segmentation Model for Large-Scale Medical Image Datasets." CVPR Workshop (2024).
  [[paper](https://openreview.net/forum?id=YgXOPqNrjl)] 
  [[code](https://github.com}{https//github.com%7D)]
  [2024.07]

- Haotian Guan, Bingze Dai, Jiajing Zhang.<br />
  "Lite Class-prompt Tiny-VIT for Multi-Modality Medical Image Segmentation." CVPR Workshop (2024).
  [[paper](https://openreview.net/forum?id=VHcTUdz9SY)] 
  [2024.07]

- Zhi Li, YAQI WANG.<br />
  "ExpertsMedSAM: Faster Medical Image Segment Anything with Mixture-of-Experts." ArXiv (2024).
  [[paper](https://openreview.net/forum?id=PvZLfWp0RC)] 
  [2024.07]

- **GraysAnatomySAM:** YoungHwan Choi, In Kyu Lee, Jonghoe Ku.<br />
  "Gray’s Anatomy for Segment Anything Model: Optimizing Grayscale Medical Images for Fast and Lightweight Segmentation." CVPR Workshop (2024).
  [[paper](https://openreview.net/forum?id=BNrWHF5ZlC)] 
  [[code](https://github.com/Ninebell/GraysAnatomySAM)]
  [2024.07]

- Wentao Liu, weijin xu, Ruifeng Bian, Haoyuan Li, Tong Tian.<br />
  "LiteMedSAM with Low-Rank Adaptation and Multi-Box Efficient Inference for Medical Image Segmentation." ArXiv (2024).
  [[paper](https://openreview.net/forum?id=OARvqM1Xgz)] 
  [2024.07]

- Lei Yu.<br />
  "Efficient and Robust Medical Image Segmentation Using Lightweight ViT-Tiny based SAM and Model Quantization." ArXiv (2024).
  [[paper](https://openreview.net/forum?id=clVaaD4FgD)] 
  [2024.07]

- **Rep-MedSAM:** Muxin Wei, Shuqing Chen, Silin Wu, Dabin Xu.<br />
  "Rep-MedSAM: Towards Real-time and Universal Medical Image Segmentation." CVPR Workshop (2024).
  [[paper](https://openreview.net/forum?id=yqf77n9Kfw)] 
  [2024.07]

- **RepViT-MedSAM:** Muhammad Qasim Ali, Alexander Wong, Yuhao Chen.<br />
  "RepViT-MedSAM: Efficient Segment Anything in the Medical Images." CVPR Workshop (2024).
  [[paper](https://openreview.net/forum?id=7XxVOeffb6)] 
  [[code](https://github.com/icecap360/TurboMedSAM)]
  [2024.07]

- **GBMSeg:** Xueyu Liu, Guangze Shi, Rui Wang, Yexin Lai, Jianan Zhang, Lele Sun, Quan Yang, Yongfei Wu, MIng Li, Weixia Han, Wen Zheng.<br />
  "Feature-prompting GBMSeg: One-Shot Reference Guided Training-Free Prompt Engineering for Glomerular Basement Membrane Segmentation." MICCAI (2024).
  [[paper](https://arxiv.org/abs/2406.16271)] 
  [[code](https://github.com/SnowRain510/GBMSeg)]
  [2024.07]

- **MedficientSAM:** Bao-Hiep Le, Dang-Khoa Nguyen-Vu, Trong-Hieu Nguyen-Mau, Hai-Dang Nguyen, Minh-Triet Tran.<br />
  "MedficientSAM: A Robust Medical Segmentation Model with Optimized Inference Pipeline for Limited Clinical Settings." CVPR Workshop (2024).
  [[paper](https://openreview.net/forum?id=aa0f77RKI0)] 
  [[code](https://github.com/hieplpvip/medficientsam)]
  [2024.07]

- **AS-OCT:** Boyu Chen, Ameenat L. Solebo, Paul Taylor.<br />
  "Advancing Cell Detection in Anterior Segment Optical Coherence Tomography Images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.17577)] 
  [[code](https://github.com/joeybyc/cell_detection)]
  [2024.07]

- **YOLOv8n-DDA-SAM:** Zhang, Gengming, Hao Cao, Yangwen Jin, Yi Zhong, Anbang Zhao, Xiangjun Zou, and Hongjun Wang.<br />
  "YOLOv8n-DDA-SAM: Accurate Cutting-Point Estimation for Robotic Cherry-Tomato Harvesting." Agriculture (2024).
  [[paper](https://www.mdpi.com/2077-0472/14/7/1011)] 
  [2024.07]

- **MMRo:** Jinming Li, Yichen Zhu, Zhiyuan Xu, Jindong Gu, Minjie Zhu, Xin Liu, Ning Liu, Yaxin Peng, Feifei Feng, Jian Tang.<br />
  "MMRo: Are Multimodal LLMs Eligible as the Brain for In-Home Robotics?." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.19693)] 
  [[code](https://mm-robobench.github.io/)]
  [2024.07]

- **OTVP:** Takayuki Nishimura, Katsuyuki Kuyo, Motonari Kambara, Komei Sugiura.<br />
"Object Segmentation from Open-Vocabulary Manipulation Instructions Based on Optimal Transport Polygon Matching with Multimodal Foundation Models." IROS (2024).
[[paper](https://arxiv.org/abs/2407.00985)] 
[2024.07]

- **MST_MIXER:** Adnen Abdessaied, Lei Shi, Andreas Bulling.<br />
  "Multi-Modal Video Dialog State Tracking in the Wild." ECCV (2024).
  [[paper](https://arxiv.org/abs/2407.02218)] 
  [[code](https://perceptualui.org/publications/abdessaied24_eccv)]
 [2024.07]

- **MMedAgent:** Binxu Li, Tiankai Yan, Yuanting Pan, Zhe Xu, Jie Luo, Ruiyang Ji, Shilong Liu, Haoyu Dong, Zihao Lin, Yixin Wang.<br />
  "MMedAgent: Learning to Use Medical Tools with Multi-modal Agent." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.02483)] 
[2024.07]

- **U-SAM:** Shouhong Wan, hantao zhang, Weidong Guo et al.<br />
  "Tuning Vision Foundation Models for Rectal Cancer Segmentation from CT Scans: Development and Validation of U-SAM." ArXiv (2024).
  [[paper](https://www.researchsquare.com/article/rs-4476094/v1)] 
  [2024.07]

- **DisFormer:** Sanket Gandhi, Atul, Samanyu Mahajan, Vishal Sharma, Rushil Gupta, Arnab Kumar Mondal, Parag Singla.<br />
  "Learning Disentangled Representation in Object-Centric Models for Visual Dynamics Prediction via Transformers." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.03216)] 
 [2024.07]

- **BACON:** Zhantao Yang, Ruili Feng, Keyu Yan, Huangji Wang, Zhicai Wang, Shangwen Zhu, Han Zhang, Jie Xiao, Pingyu Wu, Kai Zhu, Jixuan Chen, Chen-Wei Xie, Chaojie Mao, Yue Yang, Hongyang Zhang, Yu Liu, Fan Cheng.<br />
  "BACON: Supercharge Your VLM with Bag-of-Concept Graph to Mitigate Hallucinations." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.03314)] 
  [[code](https://ztyang23.github.io/bacon-page)]
  [2024.07]

- **CADe:** Furqan Shaukat, Syed Muhammad Anwar, Abhijeet Parida, Van Khanh Lam, Marius George Linguraru, Mubarak Shah.<br />
  "Lung-CADex: Fully automatic Zero-Shot Detection and Classification of Lung Nodules in Thoracic CT Images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.02625)] 
  [2024.07]

- **ISAMS:** Katja Löwenstein, Johanna Rehrl, Anja Schuster, Michael Gadermayr.<br />
  "Virtually Objective Quantification of in vitro Wound Healing Scratch Assays with the Segment Anything Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.02187)] 
  [2024.07]

- **HRSAM:** You Huang, Wenbin Lai, Jiayi Ji, Liujuan Cao, Shengchuan Zhang, Rongrong Ji.<br />
  "HRSAM: Efficiently Segment Anything in High-Resolution Images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.02109)] 
  [[code](https://github.com/YouHuang67/High-Resolution-Segment-Anything.git)]
  [2024.07]

- **Label Anything:** Pasquale De Marinis, Nicola Fanelli, Raffaele Scaringi, Emanuele Colonna, Giuseppe Fiameni, Gennaro Vessio, Giovanna Castellano.<br />
  "Label Anything: Multi-Class Few-Shot Semantic Segmentation with Visual Prompts." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.02075)] 
  [[code](https://github.com/pasqualedem/LabelAnything)]
  [2024.07]

- **SAVE:** Khanh-Binh Nguyen, Chae Jung Park.<br />
  "SAVE: Segment Audio-Visual Easy way using Segment Anything Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.02004)] 
  [2024.07]

- Pratyush Tripathy, Kathy Baylis, Kyle Wu, Jyles Watson, Ruizhe Jiang.<br />
  "Investigating the Segment Anything Foundation Model for Mapping Smallholder Agriculture Field Boundaries Without Training Labels." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.01846)] 
  [2024.07]

- **MaskField:** Zihan Gao, Lingling Li, Licheng Jiao, Fang Liu, Xu Liu, Wenping Ma, Yuwei Guo, Shuyuan Yang.<br />
  "Fast and Efficient: Mask Neural Fields for 3D Scene Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.01220)] 
  [2024.07]

- **ASPS:** Huiqian Li, Dingwen Zhang, Jieru Yao, Longfei Han, Zhongyu Li, Junwei Han.<br />
  "ASPS: Augmented Segment Anything Model for Polyp Segmentation." MICCAI (2024).
  [[paper](https://arxiv.org/abs/2407.00718)] 
  [[code](https://github.com/HuiqianLi/ASPS)]
  [2024.07]

- Zongshuo Li, Ding Huo, Markus Meurer, Thomas Bergs.<br />
  "Efficient Cutting Tool Wear Segmentation Based on Segment Anything Model." MSEC (2024).
  [[paper](https://arxiv.org/abs/2407.01211)] 
  [2024.07]

- **HATs:** Ruining Deng, Quan Liu, Can Cui, Tianyuan Yao, Juming Xiong, Shunxing Bao, Hao Li, Mengmeng Yin, Yu Wang, Shilin Zhao, Yucheng Tang, Haichun Yang, Yuankai Huo.<br />
  "HATs: Hierarchical Adaptive Taxonomy Segmentation for Panoramic Pathology Image Analysis." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.00596)] 
  [[code](https://github.com/hrlblab/HATs)]
  [2024.07]

- **SolarSAM:** Guohao Wang.<br />
  "SolarSAM: Building-scale Photovoltaic Potential Assessment Based on Segment Anything Model (SAM) and Remote Sensing for Emerging City." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2407.00296)] 
  [2024.07]

- **Depth Anything V2:** Lihe Yang, Bingyi Kang, Zilong Huang, Zhen Zhao, Xiaogang Xu, Jiashi Feng, Hengshuang Zhao.<br />
  "Depth Anything V2." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.09414)] 
  [[project](https://depth-anything-v2.github.io/)]
  [[code](https://github.com/DepthAnything/Depth-Anything-V2)]
  [2024.06]


- **UnSAM:** XuDong Wang, Jingfeng Yang, Trevor Darrell.<br />
  "Segment Anything without Supervision." NeurIPS (2024).
  [[paper](https://arxiv.org/abs/2406.20081)] 
  [[code](https://github.com/frank-xwang/UnSAM)]
  [2024.06]

- **EVF-SAM:** Yuxuan Zhang, Tianheng Cheng, Rui Hu, ei Liu, Heng Liu, Longjin Ran, Xiaoxin Chen, Wenyu Liu, Xinggang Wang.<br />
  "EVF-SAM: Early Vision-Language Fusion for Text-Prompted Segment Anything Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.20076)] 
  [2024.06]

- Tianli Liao, Ce Wang, Lei Li, Guangen Liu, Nan Li.<br />
  "Parallax-tolerant Image Stitching via Segmentation-guided Multi-homography Warping." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.19922)] 
  [[code](https://github.com/tlliao/multi-homo-warp)]
  [2024.06]

- **RWKV-SAM:** Haobo Yuan, Xiangtai Li, Lu Qi, Tao Zhang, Ming-Hsuan Yang, Shuicheng Yan, Chen Change Loy.<br />
  "Mamba or RWKV: Exploring High-Quality and High-Efficiency Segment Anything Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.19369)] 
  [[code](https://github.com/HarborYuan/ovsam)]
  [2024.06]

- **REC:** Fuseini Mumuni, Alhassan Mumuni.<br />
  "Segment Anything Model for automated image data annotation: empirical studies using text prompts from Grounding DINO." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.19057)] 
  [2024.06]

- **UNest:** Vu Minh Hieu Phan, Yutong Xie, Bowen Zhang, Yuankai Qi, Zhibin Liao, Antonios Perperidis, Son Lam Phung, Johan W. Verjans, Minh-Son To.<br />
  "Structural Attention: Rethinking Transformer for Unpaired Medical Image Synthesis." MICCAI (2024).
  [[paper](https://arxiv.org/abs/2406.18967)] 
  [[code](https://github.com/HieuPhan33/MICCAI2024-UNest)]
  [2024.06]

- Qiushi Guo.<br />
  "A Universal Railway Obstacle Detection System based on Semi-supervised Segmentation And Optical Flow." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.18908)] 
  [2024.06]

- Mingxiao Huo, Pengliang Ji, Haotian Lin, Junchen Liu, Yixiao Wang, Yijun Chen.<br />
  "Composition Vision-Language Understanding via Segment and Depth Anything Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.18591)] 
  [[code](https://github.com/AnthonyHuo/SAM-DAM-for-Compositional-Reasoning)]
  [2024.06]

- **D2GPLan:** Jialun Pei, Ruize Cui, Yaoqian Li, Weixin Si, Jing Qin, Pheng-Ann Heng.<br />
  "Depth-Driven Geometric Prompt Learning for Laparoscopic Liver Landmark Detection." MICCAI (2024).
  [[paper](https://arxiv.org/abs/2406.17858)] 
  [[code](https://github.com/PJLallen/D2GPLand)]
  [2024.06]

- **Point-SAM:** Yuchen Zhou, Jiayuan Gu, Tung Yen Chiang, Fanbo Xiang, Hao Su.<br />
  "Point-SAM: Promptable 3D Segmentation Model for Point Clouds." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.17741)] 
  [[code](https://github.com/zyc00/Point-SAM)]
  [2024.06]

- **GIM:** Yirui Chen, Xudong Huang, Quan Zhang, Wei Li, Mingjian Zhu, Qiangyu Yan, Simiao Li, Hanting Chen, Hailin Hu, Jie Yang, Wei Liu, Jie Hu.<br />
  "GIM: A Million-scale Benchmark for Generative Image Manipulation Detection and Localization." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.16531)] 
  [[code](https://github.com/chenyirui/GIM)]
  [2024.06]

- **TP-DRSeg:** Wenxue Li, Xinyu Xiong, Peng Xia, Lie Ju, Zongyuan Ge.<br />
  "TP-DRSeg: Improving Diabetic Retinopathy Lesion Segmentation with Explicit Text-Prompts Assisted SAM." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.15764)] 
  [[code](https://github.com/wxliii/TP-DRSeg)]
  [2024.06]

- **SAM-EG:** Quoc-Huy Trinh, Hai-Dang Nguyen, Bao-Tram Nguyen Ngoc, Debesh Jha, Ulas Bagci, Minh-Triet Tran.<br />
  "SAM-EG: Segment Anything Model with Egde Guidance framework for efficient Polyp Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.14819)] 
  [2024.06]

- **TraceNet:** Mingyuan Wu, Zichuan Liu, Haozhen Zheng, Hongpeng Guo, Bo Chen, Xin Lu, Klara Nahrstedt.<br />
  "TraceNet: Segment one thing efficiently." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.14874)] 
  [2024.06]

- **MUTR:** Bin Cao, Yisi Zhang, Xuanxu Lin, Xingjian He, Bo Zhao, Jing Liu.<br />
  "2nd Place Solution for MeViS Track in CVPR 2024 PVUW Workshop: Motion Expression guided Video Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.13939)] 
  [2024.06]

- **SSAD:** Zijian Cai, Xinquan Yang, Xuguang Li, Xiaoling Luo, Xuechen Li, Linlin Shen, He Meng, Yongqiang Deng.<br />
  "SSAD: Self-supervised Auxiliary Detection Framework for Panoramic X-ray based Dental Disease Diagnosis." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.13963)] 
  [[code](https://github.com/Dylonsword/SSAD)]
  [2024.06]

- **SF-CLIP:** Sepehr Sameni, Kushal Kafle, Hao Tan, Simon Jenni.<br />
  "Building Vision-Language Models on Solid Foundations with Masked Distillation." CVPR (2024).
  [[paper](https://openaccess.thecvf.com/content/CVPR2024/html/Sameni_Building_Vision-Language_Models_on_Solid_Foundations_with_Masked_Distillation_CVPR_2024_paper.html)] 
  [2024.06]

- **LU-AVS:** Chen Liu, Peike Patrick Li, Qingtao Yu, Hongwei Sheng, Dadong Wang, Lincheng Li, Xin Yu.<br />
  "Benchmarking Audio Visual Segmentation for Long-Untrimmed Videos." CVPR (2024).
  [[paper](https://openaccess.thecvf.com/content/CVPR2024/html/Liu_Benchmarking_Audio_Visual_Segmentation_for_Long-Untrimmed_Videos_CVPR_2024_paper.html)] 
  [[code](https://yenanliu.github.io/LU-AVS/)]
  [2024.06]

- **ROSA:** Yuhan Shen, Huiyu Wang, Xitong Yang, Matt Feiszli, Ehsan Elhamifar, Lorenzo Torresani, Effrosyni Mavroudi.<br />
  "Learning to Segment Referred Objects from Narrated Egocentric Videos." CVPR (2024).
  [[paper](https://openaccess.thecvf.com/content/CVPR2024/html/Shen_Learning_to_Segment_Referred_Objects_from_Narrated_Egocentric_Videos_CVPR_2024_paper.html)] 
  [2024.06]

- **TSP-SAM:** Wenjun Hui, Zhenfeng Zhu, Shuai Zheng, Yao Zhao.<br />
  "Endow SAM with Keen Eyes: Temporal-spatial Prompt Learning for Video Camouflaged Object Detection." CVPR (2024).
  [[paper](https://openaccess.thecvf.com/content/CVPR2024/html/Hui_Endow_SAM_with_Keen_Eyes_Temporal-spatial_Prompt_Learning_for_Video_CVPR_2024_paper.html)] 
  [2024.06]

- **OV3D:** Li Jiang, Shaoshuai Shi, Bernt Schiele.<br />
  "Open-Vocabulary 3D Semantic Segmentation with Foundation Models." CVPR (2024).
  [[paper](https://openaccess.thecvf.com/content/CVPR2024/html/Jiang_Open-Vocabulary_3D_Semantic_Segmentation_with_Foundation_Models_CVPR_2024_paper.html)] 
  [2024.06]

- **FM-FSOD:** Guangxing Han, Ser-Nam Lim.<br />
  "Few-Shot Object Detection with Foundation Models." CVPR (2024).
  [[paper](https://openaccess.thecvf.com/content/CVPR2024/html/Han_Few-Shot_Object_Detection_with_Foundation_Models_CVPR_2024_paper.html)] 
  [2024.06]

- **OV-DAR:** Keyan Chen, Xiaolong Jiang, Haochen Wang, Cilin Yan, Yan Gao, Xu Tang, Yao Hu & Weidi Xie.<br />
  "OV-DAR: Open-Vocabulary Object Detection and Attributes Recognition." IJCV (2024).
  [[paper](https://link.springer.com/article/10.1007/s11263-024-02144-1)] 
  [2024.06]

- Yang Su, Shunquan Tan, Jiwu Huang.<br />
  "A Novel Universal Image Forensics Localization Model Based on Image Noise and Segment Anything Model." IH&MMSec (2024).
  [[paper](https://dl.acm.org/doi/abs/10.1145/3658664.3659639)] 
  [2024.06]

- **SGF:** Li, Guanlin and Zhao, Bin and Li, Xuelong.<br />
  "Low-light Image Enhancement with SAM-based Structure Priors and Guidance." TMM (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10557144)] 
  [[code](ttps://github.com/guanguanboy/SGF)]
  [2024.06]

- Qin Li, Yizhe Zhang, Yan Li, Jun Lyu, Meng Liu, Longyu Sun, Mengting Sun, Qirong Li, Wenyue Mao, Xinran Wu, Yajing Zhang, Yinghua Chu, Shuo Wang, Chengyan Wang.<br />
  "An Empirical Study on the Fairness of Foundation Models for Multi-Organ Image Segmentation." MICCAI (2024).
  [[paper](https://arxiv.org/abs/2406.12646)] 
  [2024.06]
  
- **S2C:** Hyeokjun Kweon, Kuk-Jin Yoon.<br />
  "From SAM to CAMs: Exploring Segment Anything Model for Weakly Supervised Semantic Segmentation." CVPR (2024).
  [[paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Kweon_From_SAM_to_CAMs_Exploring_Segment_Anything_Model_for_Weakly_CVPR_2024_paper.pdf)] 
  [[code](https://github.com/sangrockEG/S2C)]
  [2024.06]

- **SAMAug-C:** Pengfei Gu, Zihan Zhao, Hongxiao Wang, Yaopeng Peng, Yizhe Zhang, Nishchal Sapkota, Chaoli Wang, Danny Z. Chen.<br />
  "Boosting Medical Image Classification with Segmentation Foundation Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.11026)] 
  [2024.06]

- **ALPS:** Song Zhang, Qingzhong Wang, Junyi Liu, Haoyi Xiong.<br />
  "ALPS: An Auto-Labeling and Pre-training Scheme for Remote Sensing Segmentation With Segment Anything Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.10855)] 
  [[code](https://github.com/StriveZs/ALPS)]
  [2024.06]

- **EBSeg:** Xiangheng Shan, Dongyue Wu, Guilin Zhu, Yuanjie Shao, Nong Sang, Changxin Gao.<br />
  "Open-Vocabulary Semantic Segmentation with Image Embedding Balancing." CVPR (2024).
  [[paper](https://arxiv.org/abs/2406.09829)] 
  [[code](https://github.com/slonetime/EBSeg)]
  [2024.06]

- **RobustSAM:** Wei-Ting Chen, Yu-Jiet Vong, Sy-Yen Kuo, Sizhuo Ma, Jian Wang.<br />
  "RobustSAM: Segment Anything Robustly on Degraded Images." CVPR (2024).
  [[paper](https://arxiv.org/abs/2406.09627)] 
  [[project](https://robustsam.github.io/)]
  [[code](https://github.com/robustsam/RobustSAM)]
  [2024.06]

- **4M-21:** Roman Bachmann, Oğuzhan Fatih Kar, David Mizrahi, Ali Garjani, Mingfei Gao, David Griffiths, Jiaming Hu, Afshin Dehghan, Amir Zamir.<br />
  "4M-21: An Any-to-Any Vision Model for Tens of Tasks and Modalities." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.09406)] 
  [[code](http://4m.epfl.ch/)]
  [2024.06]

- **ICE-G:** Vishnu Jaganathan, Hannah Hanyun Huang, Muhammad Zubair Irshad, Varun Jampani, Amit Raj, Zsolt Kira.<br />
  "ICE-G: Image Conditional Editing of 3D Gaussian Splats." CVPR AI4CC Workshop (2024).
  [[paper](https://arxiv.org/abs/2406.08488)] 
  [[code](https://ice-gaussian.github.io/)]
  [2024.06]

- **APSeg:** Weizhao He, Yang Zhang, Wei Zhuo, Linlin Shen, Jiaqi Yang, Songhe Deng, Liang Sun.<br />
  "APSeg: Auto-Prompt Network for Cross-Domain Few-Shot Semantic Segmentatio." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.08372)] 
  [2024.06]

- **RiVEG:** Jinyuan Li, Ziyan Li, Han Li, Jianfei Yu, Rui Xia, Di Sun, Gang Pan.<br />
  "Advancing Grounded Multimodal Named Entity Recognition via LLM-Based Reformulation and Box-Based Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.07268)] 
  [[code](https://github.com/JinYuanLi0012/RiVEG)]
  [2024.06]

- Marian Longa, João F. Henriques.<br />
  "Unsupervised Object Detection with Theoretical Guarantees." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.07284)] 
  [2024.06]

- **ST-BAVA:** Juhyeong Seon, Woobin Im, Sebin Lee, Jumin Lee, Sung-Eui Yoon.<br />
  "Extending Segment Anything Model into Auditory and Temporal Dimensions for Audio-Visual Segmentation." ICIP  (2024).
  [[paper](https://arxiv.org/abs/2406.06163)] 
  [2024.06]

- **CRSTM:** Xiaoli Wei, Zhaoqing Wang, Yandong Guo, Chunxia Zhang, Tongliang Liu, Mingming Gong.<br />
  "Training-Free Robust Interactive Video Object Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.05485)] 
  [2024.06]

- **USE:** Xiaoqi Wang, Wenbin He, Xiwei Xuan, Clint Sebastian, Jorge Piazentin Ono, Xin Li, Sima Behpour, Thang Doan, Liang Gou, Han Wei Shen, Liu Ren.<br />
  "USE: Universal Segment Embeddings for Open-Vocabulary Image Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.05271)] 
  [2024.06]

- **SAM-PM:** Muhammad Nawfal Meeran, Gokul Adethya T, Bhanu Pratyush Mantha.<br />
  "SAM-PM: Enhancing Video Camouflaged Object Detection using Spatio-Temporal Attention." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.05802)] 
  [[code](https://github.com/SpiderNitt/SAM-PM)]
  [2024.06]

- Matthias Pijarowski, Alexander Wolpert, Martin Heckmann, Michael Teutsch.<br />
  "Utilizing grounded SAM for self-supervised frugal camouflaged human detection." Automatic Target Recognition XXXIV. SPIE(2024).
  [[paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13039/1303909/Utilizing-grounded-SAM-for-self-supervised-frugal-camouflaged-human-detection/10.1117/12.3021694.short#_=_)] 
  [2024.06]

- **ASDeM:** Liu, Xiaohu and Luo, Yichuang and Sun, Wei.<br />
  "ASDeM: Augmenting SAM With Decoupled Memory for Video Object Segmentation." ACCESS (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10537204)] 
  [2024.06]

- **LNDVI:** Balasundaram, Ananthakrishnan and Sharma, Alabhya and Kumaravelan, Swaathy and Shaik, Ayesha and Kavitha, Muthu Subash.<br />
  "An Improved Normalized Difference Vegetation Index (NDVI) Estimation Using Grounded Dino and Segment Anything Model for Plant Health Classification." ACCESS (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10535513)] 
  [2024.06]

- **PDM:** Dvir Samuel, Rami Ben-Ari, Matan Levy, Nir Darshan, Gal Chechik.<br />
  "Unveiling the Power of Diffusion Features For Personalized Segmentation and Retrieval." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.18025)] 
  [2024.06]

- **LeSAM:** Gu, Yunbo and Wu, Qianyu and Tang, Hui and Mai, Xiaoli and Shu, Huazhong and Li, Baosheng and Chen, Yang.<br />
  "LeSAM: Adapt Segment Anything Model for medical lesion segmentation." JBHI (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10540651?casa_token=lFrAdNHKXxIAAAAA:2Piv4lZ561FI6r0vhcLa-dNjKZEsi0wdLkoEcst9eA1ThwLSfOlIv77db8YiFuDjvGTysb5cdWGiig)] 
  [2024.06]

- **DF2LCZ-Net:** Qianqian Wu, Xianping Ma, Jialu Sui and Man-On Pun.<br />
  "A SAM-EMPOWERED DUAL-STREAM FRAMEWORK FOR SCENE-LEVEL LOCAL CLIMATE ZONE CLASSIFICATION USING GOOGLE EARTH AND SENTINEL IMAGES." IGARSS (2024).
  [[paper](https://mypage.cuhk.edu.cn/academics/simonpun/papers/IGARSS24-Qianqian.pdf)] 
  [2024.06]

- **U-SAM:** Zhang, Hantao and Guo, Weidong and Wan, Shouhong and Zou, Bingbing and Wang, Wanqin and Qiu, Chenyang and Liu, Kaige and Jin, Peiquan and Yang, Jiancheng.<br />
  "Deep-Learning-Assisted Segmentation of Rectal Cancer from CT Scans: Development and Validation of U-SAM." Available at SSRN (2024).
  [[paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4838978)] 
  [2024.06]

- **SAM-PR:** Ricardo Montoya-del-Angel, Marawan Elbatel, Joel Vidal, Robert Martí.<br />
  "SAM-PR: enhancing 3D automated breast ultrasound imaging segmentation with probabilistic refinement of SAM." IWBI  (2024).
  [[paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13174/131741P/SAM-PR--enhancing-3D-automated-breast-ultrasound-imaging-segmentation/10.1117/12.3027023.short?tab=ArticleLink)] 
  [2024.06]

- Yunho Kim, Jeong Hyun Lee, Choongin Lee, Juhyeok Mun, Donghoon Youm, Jeongsoo Park, Jemin Hwangbo.<br />
  "Learning Semantic Traversability with Egocentric Video and Automated Annotation Strategy." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.02989)] 
  [2024.06]

- Heather Doig, Oscar Pizarro, Jacquomo Monk, Stefan Williams.<br />
  "Detecting Endangered Marine Species in Autonomous Underwater Vehicle Imagery Using Point Annotations and Few-Shot Learning." IROS  (2024).
  [[paper](https://arxiv.org/abs/2406.01932)] 
  [2024.06]

- **VCP:** Kuang, Senyun and Liu, Yang and Wang, Xin and Qu, Xiaobo and Wei, Yintao.<br />
  "An Universal Crack Detection Framework for Intelligent Road-Perceptive Vehicles." TIV (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10546302?casa_token=BQZvRif7cHwAAAAA:ypzujnIPCx6bh_FWiZArFn5tzmzu40rs0vypPjMUcS9JX3Y5TeMqrCmKjGx1lkNR44kZ0KiyqCR0iQ)] 
  [2024.06]

- **SCD-SAM:** Mei, Liye and Ye, Zhaoyi and Xu, Chuan and Wang, Hongzhu and Wang, Ying and Lei, Cheng and Yang, Wei and Li, Yansheng.<br />
  "SCD-SAM: Adapting Segment Anything Model for Semantic Change Detection in Remote Sensing Imagery." TGRS (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10543161?casa_token=kmyNvSj0pqUAAAAA:d_NttqSz33V9uIFBLpEK_6z54eUyegqtMo_qWzjrb_xOLH73AYb_LzFReuR2vFkmbGfbt_r7Rtr67A)] 
  [[code](https://github.com/yzygit1230/SCD-SAM)]
  [2024.06]

- **MASA:** Siyuan Li, Lei Ke, Martin Danelljan, Luigi Piccinelli, Mattia Segu, Luc Van Gool, Fisher Yu.<br />
  "Matching Anything by Segmenting Anything." CVPR (2024).
  [[paper](https://arxiv.org/abs/2406.04221)] 
  [[project](https://matchinganything.github.io/)]
  [[code](https://github.com/siyuanliii/masa)]
  [2024.06]

- **Immunocto:** Mikaël Simard, Zhuoyan Shen, Maria A. Hawkins, Charles-Antoine Collins-Fekete.<br />
  "Immunocto: a massive immune cell database auto-generated for histopathology." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.02618)] 
  [[code](https://zenodo.org/uploads/11073373)]
  [2024.06]

- **OpenGaussian:** Yanmin Wu, Jiarui Meng, Haijie Li, Chenming Wu, Yahao Shi, Xinhua Cheng, Chen Zhao, Haocheng Feng, Errui Ding, Jingdong Wang, Jian Zhang.<br />
  "OpenGaussian: Towards Point-Level 3D Gaussian-based Open Vocabulary Understanding." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.02058)] 
  [[code](https://3d-aigc.github.io/OpenGaussian)]
  [2024.06]

- **Open-YOLO 3D:** Mohamed El Amine Boudjoghra, Angela Dai, Jean Lahoud, Hisham Cholakkal, Rao Muhammad Anwer, Salman Khan, Fahad Shahbaz Khan.<br />
  "Open-YOLO 3D: Towards Fast and Accurate Open-Vocabulary 3D Instance Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.02548)] 
  [[code](http://github.com/aminebdj/OpenYOLO3D)]
  [2024.06]

- **FastLGS:** Yuzhou Ji, He Zhu, Junshu Tang, Wuyi Liu, Zhizhong Zhang, Yuan Xie, Lizhuang Ma, Xin Tan.<br />
  "FastLGS: Speeding up Language Embedded Gaussians with Feature Grid Mapping." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.01916)] 
  [[code](https://george-attano.github.io/FastLGS/)]
  [2024.06]

- Yang Nan, Guang Yang.<br />
  "Deep asymmetric mixture model for unsupervised cell segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.01815)] 
  [2024.06]

- **SemiRES:** Danni Yang, Jiayi Ji, Yiwei Ma, Tianyu Guo, Haowei Wang, Xiaoshuai Sun, Rongrong Ji.<br />
  "SAM as the Guide: Mastering Pseudo-Label Refinement in Semi-Supervised Referring Expression Segmentation." ICML (2024).
  [[paper](https://arxiv.org/abs/2406.01451)] 
  [[code](https://github.com/nini0919/SemiRES)]
  [2024.06]

- **AlignSAM:** Duojun Huang, Xinyu Xiong, Jie Ma, Jichang Li, Zequn Jie, Lin Ma, Guanbin Li.<br />
  "AlignSAM: Aligning Segment Anything Model to Open Context via Reinforcement Learning." CVPR (2024).
  [[paper](https://arxiv.org/abs/2406.00480)] 
  [[code](https://github.com/Duojun-Huang/AlignSAM-CVPR2024)]
  [2024.06]

- **AuxOL:** Tianyu Huang, Tao Zhou, Weidi Xie, Shuo Wang, Qi Dou, Yizhe Zhang.<br />
  "Improving Segment Anything on the Fly: Auxiliary Online Learning and Adaptive Fusion for Medical Image Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.00956)] 
  [[code](https://sam-auxol.github.io/AuxOL/)]
  [2024.06]

- **SimSAM:** Benjamin Towle, Xin Chen, Ke Zhou.<br />
  "SimSAM: Zero-shot Medical Image Segmentation via Simulated Interaction." ISBI (2024).
  [[paper](https://arxiv.org/abs/2406.00663)] 
  [[code](https://github.com/BenjaminTowle/SimSAM)]
  [2024.06]

- **SAM-LAD:** Yun Peng, Xiao Lin, Nachuan Ma, Jiayuan Du, Chuangwei Liu, Chengju Liu, Qijun Chen.<br />
  "SAM-LAD: Segment Anything Model Meets Zero-Shot Logic Anomaly Detection." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.00625)] 
  [2024.06]

- Jimmy Xuekai Li, Tiancheng Zhang, Yiran Zhu, Zhongwei Chen.<br />
  "Artificial General Intelligence (AGI) for the oil and gas industry: a review." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.00594)] 
  [2024.06]

- **SAM-VMNet:** Xueying Zeng, Baixiang Huang, Yu Luo, Guangyu Wei, Songyan He, Yushuang Shao.<br />
  "SAM-VMNet: Deep Neural Networks For Coronary Angiography Vessel Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2406.00492)] 
  [2024.06]

- **DISAM:** Ruipeng Zhang, Ziqing Fan, Jiangchao Yao, Ya Zhang, Yanfeng Wang.<br />
  "Domain-Inspired Sharpness-Aware Minimization Under Domain Shifts." ICLR (2024).
  [[paper](https://arxiv.org/abs/2405.18861)] 
  [[code](https://github.com/MediaBrain-SJTU/DISAM)]
  [2024.05]

- **SAM-E:** Junjie Zhang, Chenjia Bai, Haoran He, Wenke Xia, Zhigang Wang, Bin Zhao, Xiu Li, Xuelong Li.<br />
  "SAM-E: Leveraging Visual Foundation Model with Sequence Imitation for Embodied Manipulation." ICML  (2024).
  [[paper](https://arxiv.org/abs/2405.19586)] 
  [[project](https://sam-embodied.github.io/)]
 [[code](https://github.com/pipixiaqishi1/SAM-E)]
  [2024.05]

- Haodi He, Colton Stearns, Adam W. Harley, Leonidas J. Guibas.<br />
  "View-Consistent Hierarchical 3D SegmentationUsing Ultrametric Feature Fields." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.19678)] 
  [[code](https://github.com/hardyho/ultrametric_feature_fields)]
  [2024.05]

- **FMARS:** Edoardo Arnaudo, Jacopo Lungo Vaschetti, Lorenzo Innocenti, Luca Barco, Davide Lisi, Vanina Fissore, Claudio Rossi.<br />
  "FMARS: Annotating Remote Sensing Images for Disaster Management using Foundation Models." IGARSS (2024).
  [[paper](https://arxiv.org/abs/2405.20109)] 
  [[code](https://github.com/links-ads/igarss-fmars)]
  [2024.05]

- **Finetuned-SAM:** FNU Shivam, Megan Leight, Mary Kate Kelly, Claire Davis, Kelsey Clodfelter, Jacob Thrasher, Yenumula Reddy, Prashnna Gyawali.<br />
  "Segmentation of Maya hieroglyphs through fine-tuned foundation models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.16426)] 
  [2024.05]

- Qi Zhang, Guanyu Xing, Jianwei Zhang, Yanli Liu.<br />
  "Adaptive active contours driven by the squared Hellinger distance and local correlation features for inhomogeneous image segmentation." Multimed Tools Appl (2024).
  [[paper](https://link.springer.com/article/10.1007/s11042-024-19407-1)] 
  [2024.05]

- **FocSAM:** You Huang, Zongyu Lan, Liujuan Cao, Xianming Lin, Shengchuan Zhang, Guannan Jiang, Rongrong Ji.<br />
  "FocSAM: Delving Deeply into Focused Objects in Segmenting Anything." CVPR (2024).
  [[paper](https://arxiv.org/abs/2405.18706)] 
  [[code](https://github.com/YouHuang67/focsam)]
  [2024.05]

- **Reasoning3D:** Tianrun Chen, Chunan Yu, Jing Li, Jianqi Zhang, Lanyun Zhu, Deyi Ji, Yong Zhang, Ying Zang, Zejian Li, Lingyun Sun.<br />
  "Reasoning3D -- Grounding and Reasoning in 3D: Fine-Grained Zero-Shot Open-Vocabulary 3D Reasoning Part Segmentation via Large Vision-Language Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.19326)] 
  [[code](http://tianrun-chen.github.io/Reason3D/)]
  [2024.05]

- Aditya Gunturu, Yi Wen, Jarin Thundathil, Nandi Zhang, Rubaiat Habib Kazi, Ryo Suzuki.<br />
  "Augmented Physics: A Machine Learning-Powered Tool for Creating Interactive Physics Simulations from Static Diagrams." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.18614)] 
  [2024.05]

- **PLUG:** Zhaochen Liu, Limeng Qiao, Xiangxiang Chu, Tingting Jiang.<br />
  "PLUG: Revisiting Amodal Segmentation with Foundation Model and Hierarchical Focus." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.16094)] 
  [2024.05]

- **NIDS-Net:** Yangxiao Lu, Jishnu Jaykumar P, Yunhui Guo, Nicholas Ruozzi, Yu Xiang.<br />
  "Adapting Pre-Trained Vision Models for Novel Instance Detection and Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.17859)] 
  [[code](https://github.com/YoungSean/NIDS-Net)]
  [2024.05]

- **MemSAM:** Xiaolong Deng, Huisi Wu, Runhao Zeng, Jing Qin.<br />
  "MemSAM: Taming Segment Anything Model for Echocardiography Video Segmentation." CVPR (2024).
  [[paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Deng_MemSAM_Taming_Segment_Anything_Model_for_Echocardiography_Video_Segmentation_CVPR_2024_paper.pdf)] 
  [[code](https://github.com/dengxl0520/MemSAM)]
  [2024.05]

- **Part123:** Anran Liu, Cheng Lin, Yuan Liu, Xiaoxiao Long, Zhiyang Dou, Hao-Xiang Guo, Ping Luo, Wenping Wang.<br />
  "Part123: Part-aware 3D Reconstruction from a Single-view Image." SIGGRAPH  (2024).
  [[paper](https://arxiv.org/abs/2405.16888)] 
  [[code](https://liuar0512.github.io/part123_official_page/)]
  [2024.05]

- **PP-SAM:** Md Mostafijur Rahman, Mustafa Munir, Debesh Jha, Ulas Bagci, Radu Marculescu.<br />
  "PP-SAM: Perturbed Prompts for Robust Adaptation of Segment Anything Model for Polyp Segmentation." CVPRW (2024).
  [[paper](https://arxiv.org/abs/2405.16740)] 
  [[code](https://github.com/SLDGroup/PP-SAM)]
  [2024.05]

- **SA-GS:** Butian Xiong, Xiaoyu Ye, Tze Ho Elden Tse, Kai Han, Shuguang Cui, Zhen Li.<br />
  "SA-GS: Semantic-Aware Gaussian Splatting for Large Scene Reconstruction with Geometry Constrain." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.16923)] 
  [[code](https://saliteta.github.io/SA-GS)]
  [2024.05]

- **OV-SAM3D:** Hanchen Tai, Qingdong He, Jiangning Zhang, Yijie Qian, Zhenyu Zhang, Xiaobin Hu, Yabiao Wang, Yong Liu.<br />
  "Open-Vocabulary SAM3D: Understand Any 3D Scene." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.15580)] 
  [[project](https://hithqd.github.io/projects/OV-SAM3D/)]
  [[code](https://github.com/HanchenTai/OV-SAM3D)]
  [2024.05]

- Yuchun Guo, Zhiqing Lu, Yanling Zhou, Xin Jiang.<br />
  "Autonomous Quilt Spreading for Caregiving Robots." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.15373)] 
  [2024.05]

- **MoME:** Xinru Zhang, Ni Ou, Berke Doga Basaran, Marco Visentin, Mengyun Qiao, Renyang Gu, Cheng Ouyang, Yaou Liu, Paul M. Matthew, Chuyang Ye, Wenjia Bai.<br />
  "A Foundation Model for Brain Lesion Segmentation with Mixture of Modality Experts." MICCAI  (2024).
  [[paper](https://arxiv.org/abs/2405.10246)] 
  [2024.05]

- **OLIVINE:** Yifan Zhang, Junhui Hou.<br />
  "Fine-grained Image-to-LiDAR Contrastive Distillation with Visual Foundation Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.14271)] 
  [[code](https://github.com/Eaphan/OLIVINE.)]
  [2024.05]

- **FreeTuner:** Youcan Xu, Zhen Wang, Jun Xiao, Wei Liu, Long Chen.<br />
  "FreeTuner: Any Subject in Any Style with Training-free Diffusion." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.14201)] 
  [2024.05]

- **UroSAM:** Leng, Jixuan and Liu, Junfei and Cheng, Galen and Wang, Haohan and Quarrier, Scott Orzech and Luo, Jiebo and Jain, Rajat.<br />
  "Development of UroSAM: a machine learning model to automatically identify kidney stone composition from endoscopic video." Journal of Endourology (2024).
  [[paper](https://www.liebertpub.com/doi/abs/10.1089/end.2023.0740?casa_token=w2fwDmE_-swAAAAA%3AvQ_F2iaHPYMxOOlhV4z2iaK3X5nE9V0gsUBoD93FqbW5DJa3XkaB2d5X9lmZSeRBtjJRtqkzttM4Amx8)] 
  [2024.05]

- **DBA-CLIP:** Xiaobo Yang, Xiaojin Gong.<br />
  "Tuning-free Universally-Supervised Semantic Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.14294)] 
  [2024.05]

- **FAM:** Qijian Zhang, Junhui Hou, Wenping Wang, Ying He.<br />
  "Flatten Anything: Unsupervised Neural Surface Parameterization." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.14633)] 
  [2024.05]

- Zipeng Qi, Chenyang Liu, Zili Liu, Hao Chen, Yongchang Wu, Zhengxia Zou, Zhenwei Sh.<br />
  "Multi-view Remote Sensing Image Segmentation With SAM priors." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.14171)] 
  [2024.05]

- **DTLLM-VLT:** Xuchen Li, Xiaokun Feng, Shiyu Hu, Meiqi Wu, Dailing Zhang, Jing Zhang, Kaiqi Huang.<br />
  "DTLLM-VLT: Diverse Text Generation for Visual Language Tracking Based on LLM." CVPRW (2024).
  [[paper](https://arxiv.org/abs/2405.12139)] 

- **WorldAfford:** Changmao Chen, Yuren Cong, Zhen Kan.<br />
  "WorldAfford: Affordance Grounding based on Natural Language Instructions." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.12461)] 
  [2024.05]

- **UO-SAM:** Tingting Li, Gensheng Pei, Xinhao Cai, Huafeng Liu, Qiong Wang, Yazhou Yao.<br />
  "Universal Organizer of SAM for Unsupervised Semantic Segmentation." ICME (2024).
  [[paper](https://arxiv.org/abs/2405.11742)] 
  [[code](https://github.com/NUST-Machine-Intelligence-Laboratory/UO-SAM)]
  [2024.05]

- **TAR:** Tharun V. Puthanveettil, Fnu Obaid ur Rahman.<br />
  "Track Anything Rapter(TAR)." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.11655)] 
  [[code](https://github.com/tvpian/Project-TAR)]
  [2024.05]

- Zhiyu Xu, Qingliang Chen.<br />
  "NubbleDrop: A Simple Way to Improve Matching Strategy for Prompted One-Shot Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.11476)] 
  [2024.05]

- Mounes Zaval, Sedat Ozer.<br />
  "Improving the Explain-Any-Concept by Introducing Nonlinearity to the Trainable Surrogate Model." IEEE SIU (2024).
  [[paper](https://arxiv.org/abs/2405.11837)] 
  [2024.05]

- **SAMReg:** Shiqi Huang, Tingfa Xu, Ziyi Shen, Shaheer Ullah Saeed, Wen Yan, Dean Barratt, Yipeng Hu.<br />
  "One registration is worth two segmentations." MICCAI (2024).
  [[paper](https://arxiv.org/abs/2405.10879)] 
  [2024.05]

- **USIS10K & USIS-SAM:** Lian, Shijie and Zhang, Ziyi and Li, Hua and Li, Wenjie and Yang, Laurence Tianruo and Kwong, Sam and Cong, Runmin.<br />
  "Diving into Underwater: Segment Anything Model Guided Underwater Salient Instance Segmentation and A Large-scale Dataset." ICML (2024).
  [[paper](https://openreview.net/pdf?id=snhurpZt63)] 
  [[code](https://github.com/LiamLian0727/USIS10K/tree/main)]
  [2024.05]

- **M4oE:** Yufeng Jiang, Yiqing Shen.<br />
  "M4oE: A Foundation Model for Medical Multimodal Image Segmentation with Mixture of Experts." ArXiv (2024).
  [[paper](https://arxiv.org/pdf/2405.09446)] 
  [[code](https://github.com/JefferyJiang-YF/M4oE)]
  [2024.05]

- **SLIP:** Saaketh Koundinya Gundavarapu, Arushi Arora, Shreya Agarwal.<br />
  "Zero Shot Context-Based Object Segmentation using SLIP (SAM+CLIP)." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.07284)] 
  [2024.05]

- **SAM3D:** Trevor J. Chan, Aarush Sahni, Jie Li, Alisha Luthra, Amy Fang, Alison Pouch, Chamith S. Rajapakse.<br />
  "SAM3D: Zero-Shot Semi-Automatic Segmentation in 3D Medical Images with the Segment Anything Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.06786)] 
  [2024.05]

- Jin Kousaka, Atsuko H. Iwane, Yuichi Togashi.<br />
  "Automated Cell Structure Extraction for 3D Electron Microscopy by Deep Learning." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.06303)] 
  [2024.05]

- Elham Ravanbakhsh, Cheng Niu, Yongqing Liang, J. Ramanujam, Xin Li.<br />
  "Enhancing Weakly Supervised Semantic Segmentation with Multi-modal Foundation Models: An End-to-End Approach." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.06586)] 
  [2024.05]

- **DiffMatch:** Kaiyu Li, Xiangyong Cao, Yupeng Deng, Deyu Meng.<br />
  "DiffMatch: Visual-Language Guidance Makes Better Semi-supervised Change Detector." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.04788)] 
  [2024.05]

- **SegAD:** Aimira Baitieva, David Hurych, Victor Besnier, Olivier Bernard.<br />
  "Supervised Anomaly Detection for Complex Industrial Images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.04953)] 
  [[code](https://github.com/abc-125/segad)]
  [2024.05]

- **WBNet:** Yi Wang, et al.<br />
  "WBNet: Weakly-supervised salient object detection via scribble and pseudo-background priors." Pattern Recognition (2024).
  [[paper](https://www.sciencedirect.com/science/article/pii/S0031320324003303)] 
  [[code](https://github.com/yiwangtz/WBNet)]
  [2024.05]

- Kevin Charles Bierlich, Sagar Karki, Clara N. Bird, Alan Fern, Leigh G. Torres.<br />
  "Automated body length and body condition measurements of whales from drone videos for rapid assessment of population health." Marine Mammal Science (2024).
  [[paper](https://onlinelibrary.wiley.com/doi/full/10.1111/mms.13137)] 
  [2024.05]

- **WSPoly-SAM:** Tingting Cai and Hongping Yan and Kun Ding and Yan Zhang and Yueyue Zhou.<br />
  "WSPoly-SAM: Weakly-Supervised and Self-Guided Fine-Tuning of SAM for Colonoscopy Polyp Segmentation." ArXiv (2024).
  [[paper](https://www.preprints.org/manuscript/202405.0389/v1)] 
  [2024.05]

- **ELiTe:** Zhibo Zhang, Ximing Yang, Weizhong Zhang, Cheng Jin.<br />
  "ELiTe: Efficient Image-to-LiDAR Knowledge Transfer for Semantic Segmentation." ICME  (2024).
  [[paper](https://arxiv.org/abs/2405.04121)] 
  [2024.05]

- **PTQ4SAM:** Chengtao Lv, Hong Chen, Jinyang Guo, Yifu Ding, Xianglong Liu.<br />
  "PTQ4SAM: Post-Training Quantization for Segment Anything." CVPR (2024).
  [[paper](https://arxiv.org/abs/2405.03144)] 
  [[code](https://github.com/chengtao-lv/PTQ4SAM)]
  [2024.05]

- **UnSAMFlow:** Shuai Yuan, Lei Luo, Zhuo Hui, Can Pu, Xiaoyu Xiang, Rakesh Ranjan, Denis Demandolx.<br />
  "UnSAMFlow: Unsupervised Optical Flow Guided by Segment Anything Model." CVPR (2024).
  [[paper](https://arxiv.org/abs/2405.02608)] 
  [[code](https://github.com/facebookresearch/UnSAMFlow)]
  [2024.05]

- **YOLO-SAM:** Yu Zhu, Qiang Yang, Li Xu.<br />
  "Active Learning Enabled Low-cost Cell Image Segmentation Using Bounding Box Annotation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.01701)] 
  [2024.05]

- **M2Depth:** Yingshuang Zou, Yikang Ding, Xi Qiu, Haoqian Wang, Haotian Zhang.<br />
  "M2Depth: Self-supervised Two-Frame Multi-camera Metric Depth Estimation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.02004)] 
  [[code](https://heiheishuang.xyz/M2Depth/)]
  [2024.05]

- Prateek Verma, Minh-Hao Van, Xintao Wu.<br />
  "Beyond Human Vision: The Role of Large Vision Language Models in Microscope Image Analysis." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.00876)] 
  [2024.04]

- **ASAM:** Bo Li, Haoke Xiao, Lv Tang.<br />
  "ASAM: Boosting Segment Anything Model with Adversarial Tuning." CVPR (2024).
  [[paper](https://arxiv.org/abs/2405.00256)] 
  [[code](https://asam2024.github.io/)]
  [2024.04]

- **MoPEFT:** Rajat Sahay, Andreas Savakis.<br />
  "MoPEFT: A Mixture-of-PEFTs for the Segment Anything Model." CVPR Workshops (2024).
  [[paper](https://arxiv.org/abs/2405.00293)] 
  [2024.04]

- Shimian Zhang, Qiuhong Lu.<br />
  "Innovative Integration of Visual Foundation Model with a Robotic Arm on a Mobile Platform." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.18720)] 
  [2024.04]

- **SAGHOG:** Marco Peer, Florian Kleber, Robert Sablatnig.<br />
  "SAGHOG: Self-Supervised Autoencoder for Generating HOG Features for Writer Retrieval." ICDAR (2024).
  [[paper](https://arxiv.org/abs/2404.17221)] 
  [[code](http://github.com/marco-peer/icdar24)]
  [2024.04]

- **Auto-Generate-WLs:** Tanvi Deshpande, Eva Prakash, Elsie Gyang Ross, Curtis Langlotz, Andrew Ng, Jeya Maria Jose Valanarasu.<br />
  "Auto-Generating Weak Labels for Real & Synthetic Data to Improve Label-Scarce Medical Image Segmentation." MIDL (2024).
  [[paper](https://arxiv.org/abs/2404.17033)] 
  [[code](https://github.com/stanfordmlgroup/Auto-Generate-WLs/)]
  [2024.04]

- **Dr-SAM:** Vazgen Zohranyan, Vagner Navasardyan, Hayk Navasardyan, Jan Borggrefe, Shant Navasardyan.<br />
  "Dr-SAM: An End-to-End Framework for Vascular Segmentation, Diameter Estimation, and Anomaly Detection on Angiography Images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.17029)] 
  [[code](https://github.com/vazgenzohranyan/Dr.SAM)]
  [2024.04]

- **MAS-SAM:** Tianyu Yan, Zifu Wan, Xinhao Deng, Pingping Zhang, Yang Liu, Huchuan Lu.<br />
  "MAS-SAM: Segment Any Marine Animal with Aggregated Features." IJCAI (2024).
  [[paper](https://arxiv.org/abs/2404.15700)] 
  [[code](https://github.com/Drchip61/MAS-SAM)]
  [2024.04]

- Kuan-I Chung, Daniel Moyer.<br />
  "Does SAM dream of EIG? Characterizing Interactive Segmenter Performance using Expected Information Gain." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.16155)] 
  [2024.04]

- **OMEGAS:** Lizhi Wang, Feng Zhou, Jianqin Yin.<br />
  "OMEGAS: Object Mesh Extraction from Large Scenes Guided by Gaussian Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.15891)] 
  [[code](https://github.com/CrystalWlz/OMEGAS)]
  [2024.04]

- **HOIST-Former:** Supreeth Narasimhaswamy, Huy Anh Nguyen, Lihan Huang, Minh Hoai.<br />
  "HOIST-Former: Hand-held Objects Identification, Segmentation, and Tracking in the Wild." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.13819)] 
  [[code](https://supreethn.github.io/research/hoistformer/index.html)]
  [2024.04]

- **CLIP-GS:** Guibiao Liao, Jiankun Li, Zhenyu Bao, Xiaoqing Ye, Jingdong Wang, Qing Li, Kanglin Liu.<br />
  "CLIP-GS: CLIP-Informed Gaussian Splatting for Real-time and View-consistent 3D Semantic Understanding." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.14249)] 
  [[code](https://github.com/gbliao/CLIP-GS)]
  [2024.04]

- **X-Ray:** Tao Hu, Wenhang Ge, Yuyang Zhao, Gim Hee Lee.<br />
  "X-Ray: A Sequential 3D Representation for Generation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.14329)] 
  [2024.04]

- **BUSSAM:** Zhengzheng Tu, Le Gu, Xixi Wang, Bo Jiang.<br />
  "Ultrasound SAM Adapter: Adapting SAM for Breast Lesion Segmentation in Ultrasound Images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.14837)] 
  [[code](https://github.com/bscs12/BUSSAM)]
  [2024.04]

- **GeoDiffuser:** Rahul Sajnani, Jeroen Vanbaar, Jie Min, Kapil Katyal, Srinath Sridhar.<br />
  "GeoDiffuser: Geometry-Based Image Editing with Diffusion Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.14403)] 
  [[code](https://ivl.cs.brown.edu/research/geodiffuser.html)]
  [2024.04]

- Yuyan Shi, Jialu Ma, Jin Yang, Shasha Wang, Yichi Zhang.<br />
  "Beyond Pixel-Wise Supervision for Medical Image Segmentation: From Traditional Models to Foundation Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.13239)] 
  [2024.04]

- **PM-VIS:** Zhangjing Yang, Dun Liu, Wensheng Cheng, Jinqiao Wang, Yi Wu.<br />
  "PM-VIS: High-Performance Box-Supervised Video Instance Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.13863)] 
  [2024.04]

- **Surgical-DeSAM:** Yuyang Sheng, Sophia Bano, Matthew J. Clarkson, Mobarakol Islam.<br />
  "Surgical-DeSAM: Decoupling SAM for Instrument Segmentation in Robotic Surgery." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.14040)] 
  [2024.04]

- **UrbanCross:** Siru Zhong, Xixuan Hao, Yibo Yan, Ying Zhang, Yangqiu Song, Yuxuan Liang.<br />
  "UrbanCross: Enhancing Satellite Image-Text Retrieval with Cross-Domain Adaptation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.14241)] 
  [2024.04]

- **ELEV-VISION-SAM:** Yu-Hsuan Ho, Longxiang Li, Ali Mostafavi.<br />
  "ELEV-VISION-SAM: Integrated Vision Language and Foundation Model for Automated Estimation of Building Lowest Floor Elevation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.12606)] 
  [2024.04]

- **Uni3DR^2:** Tao Chu, Pan Zhang, Xiaoyi Dong, Yuhang Zang, Qiong Liu, Jiaqi Wang.<br />
  "Unified Scene Representation and Reconstruction for 3D Large Language Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.13044)] 
  [[code](https://chtsy.github.io/uni3drr-page/)]
  [2024.04]

- **MM-ScatterNet:** Yilong Chen, Zongyi Xu, xiaoshui Huang, Ruicheng Zhang, Xinqi Jiang, Xinbo Gao.<br />
  "Foundation Model assisted Weakly Supervised LiDAR Semantic Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.12861)] 
  [2024.04]

- **Zip:** Cheng Shi, Sibei Yang.<br />
  "The devil is in the object boundary: towards annotation-free instance segmentation using Foundation Models." ICLR (2024).
  [[paper](https://arxiv.org/abs/2404.11957)] 
  [[code](https://github.com/ChengShiest/Zip-Your-CLIP)]
  [2024.04]

- **PPT:** Qiyuan Dai, Sibei Yang.<br />
  "Curriculum Point Prompting for Weakly-Supervised Referring Image Segmentation." CVPR (2024).
  [[paper](https://arxiv.org/abs/2404.11998)] 
  [2024.04]

- **FlowSAM:** Junyu Xie, Charig Yang, Weidi Xie, Andrew Zisserman.<br />
  "Moving Object Segmentation: All You Need Is SAM (and Flow)." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.12389)] 
  [[code](https://www.robots.ox.ac.uk/~vgg/research/flowsam/)]
  [2024.04]

- **SOHES:** Shengcao Cao, Jiuxiang Gu, Jason Kuen, Hao Tan, Ruiyi Zhang, Handong Zhao, Ani Nenkova, Liang-Yan Gui, Tong Sun, Yu-Xiong Wang.<br />
  "SOHES: Self-supervised Open-world Hierarchical Entity Segmentation." ICLR (2024).
  [[paper](https://arxiv.org/abs/2404.12386)] 
  [[code](https://sohes.github.io/)]
  [2024.04]

- Yona Falinie A. Gaus, Neelanjan Bhowmik, Brian K. S. Isaac-Medina, Toby P. Breckon.<br />
  "Performance Evaluation of Segment Anything Model with Variational Prompting for Application to Non-Visible Spectrum Imagery." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.12285)] 
  [2024.04]

- Yiqun Xie, Zhihao Wang, Weiye Chen, Zhili Li, Xiaowei Jia, Yanhua Li, Ruichen Wang, Kangyang Chai, Ruohan Li, Sergii Skakun.<br />
  "When are Foundation Models Effective? Understanding the Suitability for Pixel-Level Classification Using Multispectral Imagery." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.11797)] 
  [2024.04]

- **LAECIPS:** Shijing Hu, Ruijun Deng, Xin Du, Zhihui Lu, Qiang Duan, Yi He, Shih-Chia Huang, Jie Wu.<br />
  "LAECIPS: Large Vision Model Assisted Adaptive Edge-Cloud Collaboration for IoT-based Perception System." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.10498)] 
  [2024.04]

- **ESD:** Jieming Yu, Long Bai, Guankun Wang, An Wang, Xiaoxiao Yang, Huxin Gao, Hongliang Ren.<br />
  "Adapting SAM for Surgical Instrument Tracking and Segmentation in Endoscopic Submucosal Dissection Videos." IEEE ICRA C4SR+ Workshop (2024).
  [[paper](https://arxiv.org/abs/2404.10640)] 
  [2024.04]

- **Finetune-SAM:** Hanxue Gu, Haoyu Dong, Jichen Yang, Maciej A. Mazurowski.<br />
  "How to build the best medical image segmentation algorithm using foundation models: a comprehensive empirical study with Segment Anything Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.09957)] 
  [[code](https://github.com/mazurowski-lab/finetune-SAM)]
  [2024.04]

- **Offline-evt:** Fangwei Zhong, Kui Wu, Hai Ci, Churan Wang, Hao Chen.<br />
  "Empowering Embodied Visual Tracking with Visual Foundation Models and Offline RL." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.09857)] 
  [[code](https://sites.google.com/view/offline-evt)]
  [2024.04]

- **VFMM3D:** Bonan Ding, Jin Xie, Jing Nie, Jiale Cao.<br />
  "VFMM3D: Releasing the Potential of Image by Vision Foundation Model for Monocular 3D Object Detection." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.09431)] 
  [2024.04]

- **LLM-Seg:** Junchi Wang, Lei Ke.<br />
  "LLM-Seg: Bridging Image Segmentation and Large Language Model Reasoning." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.08767)] 
  [[code](https://github.com/wangjunchi/LLMSeg)]
  [2024.04]
  
- June Moh Goo, Zichao Zeng, Jan Boehm.<br />
  "Zero-shot detection of buildings in mobile LiDAR using Language Vision Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.09931)] 
  [2024.04]

- **Auto-Prom:** Abu Bakor Hayat Arnob, Xiangxue Wang, Yiping Jiao, Xiao Gan, Wenlong Ming, Jun Xu.<br />
  "Pathological Primitive Segmentation Based on Visual Foundation Model with Zero-Shot Mask Generation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.08584)] 
  [[code](https://github.com/learner-codec/autoprom_sam)]
  [2024.04]

- Robin Schön, Julian Lorenz, Katja Ludwig, Rainer Lienhart.<br />
  "Adapting the Segment Anything Model During Usage in Novel Situations." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.08421)] 
  [2024.04]

- **S-RA & T-RA**: Yifan Shen, Zhengyuan Li, Gang Wang.<br />
  "Practical Region-level Attack against Segment Anything Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.08255)] 
  [2024.04]

- **MedRG:** Ke Zou, Yang Bai, Zhihao Chen, Yang Zhou, Yidi Chen, Kai Ren, Meng Wang, Xuedong Yuan, Xiaojing Shen, Huazhu Fu.<br />
  "MedRG: Medical Report Grounding with Multi-modal Large Language Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.06798)] 
  [2024.04]

- **O2V-Mapping:** Muer Tie, Julong Wei, Zhengjun Wang, Ke Wu, Shansuai Yuan, Kaizhao Zhang, Jie Jia, Jieru Zhao, Zhongxue Gan, Wenchao Ding.<br />
  "O2V-Mapping: Online Open-Vocabulary Mapping with Neural Implicit Representation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.06836)] 
  [2024.04]

- Liu M, Cui M, Wei W, Xu X, Sun C, Li F, Song Z, Lu Y, Zhang J, Tian F, et al.<br />
  "Sorting of Mountage Cocoons Based on MobileSAM and Target Detection." Agriculture (2024).
  [[paper](https://www.mdpi.com/2077-0472/14/4/599)] 
  [2024.04]

- **ShadowSAM:** Zeheng Qian and Wen Wu and Xian-Tao Wu and Xiao-Diao Chen.<br />
  "Omni-supervised shadow detection with vision foundation model." JVCI (2024).
  [[paper](https://www.sciencedirect.com/science/article/abs/pii/S1047320324001019)] 
  [[code](https://github.com/wuwen1994/omni-shadow)]
  [2024.04]

- Moghimi, Armin and Welzel, Mario and Celik, Turgay and Schlurmann, Torsten.<br />
  "A Comparative Performance Analysis of Popular Deep Learning Models and Segment Anything Model (SAM) for River Water Segmentation in Close-Range Remote Sensing Imagery." IEEE  Access (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10493013)]
  [[code](https://github.com/ArminMoghimi/RiverSnap)]
  [[Dataset](https://ieee-daort.org/documents/lufi-riversnap-river-water-segmentation)]
  [2024.04]

- **SAMPA:** Handi Deng, Yucheng Zhou, Jiaxuan Xiang, Liujie Gu, Yan Luo, Hai Feng, Mingyuan Liu, Cheng Ma.<br />
  "Streamlined Photoacoustic Image Processing with Foundation Models: A Training-Free Solution." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.07833)] 
  [[code](https://github.com/Adi-Deng/photoacoustic-SAM)]
  [2024.04]

- **SAM-I-Am:** Waqwoya Abebe, Jan Strube, Luanzheng Guo, Nathan R. Tallent, Oceane Bel, Steven Spurgeon, Christina Doty, Ali Jannesari.<br />
  "SAM-I-Am: Semantic Boosting for Zero-shot Atomic-Scale Electron Micrograph Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.06638)] 
  [2024.04]

- **SaLIP:** Sidra Aleem, Fangyijie Wang, Mayug Maniparambil, Eric Arazo, Julia Dietlmeier, Kathleen Curran, Noel E. O'Connor, Suzanne Little.<br />
  "Test-Time Adaptation with SaLIP: A Cascade of SAM and CLIP for Zero-shot Medical Image Segmentation." CVPR Workshops (2024).
  [[paper](https://arxiv.org/abs/2404.06362)]
  [[code](https://github.com/aleemsidra/SaLIP)]
  [2024.04]

- **CTL:** Anas Gouda, Max Schwarz, Christopher Reining, Sven Behnke, Alice Kirchheim.<br />
  "Learning Embeddings with Centroid Triplet Loss for Object Identification in Robotic Grasping." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.06277)] 
  [[code](https://github.com/AnasIbrahim/ctl_classification)]
  [2024.04]

- **Dual-SAM:** Pingping Zhang, Tianyu Yan, Yang Liu, Huchuan Lu.<br />
  "Fantastic Animals and Where to Find Them: Segment Any Marine Animal with Dual SAM." CVPR (2024).
  [[paper](https://arxiv.org/abs/2404.04996)] 
  [[code](https://github.com/Drchip61/Dual_SAM)]
  [2024.04]

- Yu Sheng, Lu Zhang, Xingchen Li, Yifan Duan, Yanyong Zhang, Yu Zhang, Jianmin Ji.<br />
  "Rendering-Enhanced Automatic Image-to-Point Cloud Registration for Roadside Scenes." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.05164)] 
  [2024.04]

- **DL-EWF:** Fatemeh Asghari, Mohammad Reza Soheili, Faezeh Gholamrezaie.<br />
  "DL-EWF: Deep Learning Empowering Women's Fashion with Grounded-Segment-Anything Segmentation for Body Shape Classification." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.04891)] 
  [2024.04]

- **MuDI :** Sangwon Jang, Jaehyeong Jo, Kimin Lee, Sung Ju Hwang.<br />
  "Identity Decoupling for Multi-Subject Personalization of Text-to-Image Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.04243)] 
  [[code](https://mudi-t2i.github.io/)]
  [2024.04]

- David Jurado-Rodr´ıguez, et al.<br />
  "SAM-Based Detection of Structural Anomalies in 3D Models for Preserving Cultural Heritage." ArXiv (2024).
  [[paper](https://www.researchgate.net/profile/Alfonso-Lopez-Ruiz-2/publication/378703243_SAM-Based_Detection_of_Structural_Anomalies_in_3D_Models_for_Preserving_Cultural_Heritage/links/65fb0552a8baf573a1c7a4e1/SAM-Based-Detection-of-Structural-Anomalies-in-3D-Models-for-Preserving-Cultural-Heritage.pdf)] 
  [2024.04]

- Liqun Shan, Yanchang Liu, Ke Du, Shovon Paul, Xingli Zhang, Xiali Hei.<br />
  "Drilling rock image segmentation and analysis using segment anything model." Advances in Geo-Energy Research (2024).
  [[paper](https://www.yandy-ager.com/index.php/ager/article/view/1105)] 
  [2024.04]

- Sen Deng, et al.<br />
  "Semi-supervised TEE Segmentation via Interacting with SAM Equipped with Noise-Resilient Prompting." AAAI (2024).
  [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/29060)] 
  [2024.04]

- **BSDSNet:** Wang, Y.; Zhang, W.; Chen, W.; Chen, C.<br />
  "BSDSNet: Dual-Stream Feature Extraction Network Based on Segment Anything Model for Synthetic Aperture Radar Land Cover Classification." Remote Sens (2024).
  [[paper](https://www.mdpi.com/2072-4292/16/7/1150)] 
  [2024.04]

- **SweepMM:** Weichen Xu; Xinxin Xu; Tianhao Fu; Jian Cao; Xiaoyang Xu; Yuetian Huang; Xixin Cao; Xing Zhang.<br />
  "SweepMM: A High-Quality Multimodal Dataset for Sweeping Robots in Home Scenarios for Vision-Language Model." ICASSP (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10447940)] 
  [2024.04]

- **3DSAM:** Shangjie Wang; Yan Zhang.<br />
  "3DSAM: Segment Anything in NeRF." ICASSP (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10445897)] 
  [2024.04]

- **SAM-GEBD:** Pranay Kashyap; Sourabh Vasant Gothe; Vibhav Agarwal; Jayesh Rajkumar Vachhani.<br />
  "SAM-GEBD: Zero-Cost Approach for Generic Event Boundary Detection." ICASSP (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10447789)] 
  [2024.04]

- **SAM-CD:** Zixuan Sun; Huihui Song; Kaihua Zhang; Gang Dong; Lingyan Liang; Yaqian Zhao.<br />
  "Segment Anything Model Guided Semantic Knowledge Learning For Remote Sensing Change Detection." ICASSP (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10448374)] 
  [2024.04]

- **SkinSAM:** Mingzhe Hu, Yuheng Li, Xiaofeng Yang.<br />
  "SkinSAM: adapting the segmentation anything model for skin cancer segmentation."  SPIE (2024).
  [[paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12929/129290U/SkinSAM--adapting-the-segmentation-anything-model-for-skin-cancer/10.1117/12.3006837.short#_=_)] 
  [2024.04]

- **BreastSAM:** Mingzhe Hu, Yuheng Li, Xiaofeng Yang.<br />
  "BreastSAM: adapting the segmentation anything model for breast tumor segmentation in ultrasound imaging." SPIE (2024).
  [[paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12932/129320V/BreastSAM--adapting-the-segmentation-anything-model-for-breast-tumor/10.1117/12.3006773.short#_=_)] 
  [2024.04]

- Yiqiao Liu, et al.<br />
  "Universal 3D CT lesion segmentation using SAM with RECIST annotation." SPIE (2024).
  [[paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12926/1292605/Universal-3D-CT-lesion-segmentation-using-SAM-with-RECIST-annotation/10.1117/12.3006527.short#_=_)] 
  [2024.04]

- **SS2V:** Xing Yao, et al.<br />
  "FNPC-SAM: uncertainty-guided false negative/positive control for SAM on noisy medical images." SPIE (2024).
  [[paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12926/1292602/FNPC-SAM--uncertainty-guided-false-negative-positive-control-for/10.1117/12.3006867.short#_=_)] 
  [[code](https://github.com/MedICL-VU/FNPC-SAM)]
  [2024.04]

- **SAM-Att:** Zhu, Yaqi and Xiong, Changchun and Zhao, Heng and Yao, Yudong.<br />
  "SAM-Att: A Prompt-free SAM-related Model with an Attention Module for Automatic Segmentation of the Left Ventricle in Echocardiography." IEEE Access (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10488364)] 
  [2024.04]

- **BarelySAM:** Ding, Yuhang and Liu, Hongmin.<br />
  "Barely-supervised Brain Tumor Segmentation via Employing Segment Anything Model." TCSVT (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10491099)] 
  [2024.04]

- **Design2Cloth:** Jiali Zheng, Rolandos Alexandros Potamias, Stefanos Zafeiriou.<br />
  "Design2Cloth: 3D Cloth Generation from 2D Masks." CVPR (2024).
  [[paper](https://arxiv.org/abs/2404.02686)] 
  [[code](https://jiali-zheng.github.io/Design2Cloth/)]
  [2024.04]

- **FBM:** Huang, Peng and Shu, Xiangbo and Yan, Rui and Tu, Zhewei and Tang, Jinhui.<br />
  "Appearance-Agnostic Representation Learning for Compositional Action Recognition." TCSVT (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10488474)] 
  [2024.04]

- Seda Camalan, Muhammad Khalid Khan Niazi, Charles Elmaraghy, Aaron C. Moberly, Metin N. Gurcan.<br />
  "Tympanic membrane segmentation of video frames to create composite images using SAM." SPIE (2024).
  [[paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12927/1292736/Tympanic-membrane-segmentation-of-video-frames-to-create-composite-images/10.1117/12.3006926.short#_=_)] 
  [2024.04]

- Meyer, A., Mazellier, JP., Dana, J. et al.<br />
  "On-the-fly point annotation for fast medical video labeling." Int J CARS (2024).
  [[paper](https://link.springer.com/article/10.1007/s11548-024-03098-y)] 
  [2024.04]

- Uygun, T., Ozguven, M.M.<br />
  "Determination of tomato leafminer: Tuta absoluta (Meyrick) (Lepidoptera: Gelechiidae) damage on tomato using deep learning instance segmentation method." Eur Food Res Technol (2024).
  [[paper](https://link.springer.com/article/10.1007/s00217-024-04516-w)] 
  [2024.04]

- **iSeg:** Itai Lang, Fei Xu, Dale Decatur, Sudarshan Babu, Rana Hanocka.<br />
  "iSeg: Interactive 3D Segmentation via Interactive Attention." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.03219)] 
  [[code](https://threedle.github.io/iSeg/)]
  [2024.04]

- **Gen3DSR:** Andreea Dogaru, Mert Özer, Bernhard Egger.<br />
  "Generalizable 3D Scene Reconstruction via Divide and Conquer from a Single View." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.03421)] 
  [[code](https://andreeadogaru.github.io/Gen3DSR)]
  [2024.04]

- **OW-VISCap:** Anwesa Choudhuri, Girish Chowdhary, Alexander G. Schwing.<br />
  "OW-VISCap: Open-World Video Instance Segmentation and Captioning." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.03657)] 
  [[code](https://anwesachoudhuri.github.io/OpenWorldVISCap/)]
  [2024.04]

- **UAD:** Jiahao Lu, Xingyi Yang, Xinchao Wang.<br />
  "Unsegment Anything by Simulating Deformation." CVPR (2024).
  [[paper](https://arxiv.org/abs/2404.02585)] 
  [[code](https://github.com/jiahaolu97/anything-unsegmentable)]
  [2024.04]

- **FIGA:** Krzysztof Jankowski, Bartlomiej Sobieski, Mateusz Kwiatkowski, Jakub Szulc, Michal Janik, Hubert Baniecki, Przemyslaw Biecek.<br />
  "Red-Teaming Segment Anything Model." CVPR Workshop (2024).
  [[paper](https://arxiv.org/abs/2404.02067)] 
  [2024.04]

- **DHR:** Sanghyun Jo, Fei Pan, In-Jae Yu, Kyungsu Kim.<br />
  "DHR: Dual Features-Driven Hierarchical Rebalancing in Inter- and Intra-Class Regions for Weakly-Supervised Semantic Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.00380)] 
  [[code](https://github.com/shjo-april/DHR)]
  [2024.04]

- **DIT:** Xiaorui Huang, Gen Luo, Chaoyang Zhu, Bo Tong, Yiyi Zhou, Xiaoshuai Sun, Rongrong Ji.<br />
  "Deep Instruction Tuning for Segment Anything Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.00650)] 
  [[code](https://github.com/wysnzzzz/DIT)]
  [2024.04]

- **SegNext:** Qin Liu, Jaemin Cho, Mohit Bansal, Marc Niethammer.<br />
  "Rethinking Interactive Image Segmentation with Low Latency, High Quality, and Diverse Prompts." CVPR (2024).
  [[paper](https://arxiv.org/abs/2404.00741)] 
  [[code](https://github.com/uncbiag/SegNext)]
  [2024.04]

- **Detect2Interact:** Jialou Wang, Manli Zhu, Yulei Li, Honglei Li, Longzhi Yang, Wai Lok Woo.<br />
  "Detect2Interact: Localizing Object Key Field in Visual Question Answering (VQA) with LLMs." IEEE Intelligent Systems (2024).
  [[paper](https://arxiv.org/abs/2404.01151)] 
  [2024.04]

- **CoCoCo:** Bojia Zi, Shihao Zhao, Xianbiao Qi, Jianan Wang, Yukai Shi, Qianyu Chen, Bin Liang, Kam-Fai Wong, Lei Zhang.<br />
  "CoCoCo: Improving Text-Guided Video Inpainting for Better Consistency, Controllability and Compatibility." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.12035)] 
  [[project](http://cococozibojia.github.io/)]
  [[code](https://github.com/zibojia/COCOCO)]
  [2024.03]

- **DeepSeek-VL:** Haoyu Lu, Wen Liu, Bo Zhang, Bingxuan Wang, Kai Dong, Bo Liu, Jingxiang Sun, Tongzheng Ren, Zhuoshu Li, Hao Yang, Yaofeng Sun, Chengqi Deng, Hanwei Xu, Zhenda Xie, Chong Ruan.<br />
  "DeepSeek-VL: Towards Real-World Vision-Language Understanding." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.05525)] 
  [[code](https://github.com/deepseek-ai/DeepSeek-VL)]
  [2024.03]

- **MedCLIP-SAM:** Taha Koleilat, Hojat Asgariandehkordi, Hassan Rivaz, Yiming Xiao.<br />
  "MedCLIP-SAM: Bridging Text and Image Towards Universal Medical Image Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.20253)] 
  [2024.03]

- **COCO-ReM:** Shweta Singh, Aayan Yadav, Jitesh Jain, Humphrey Shi, Justin Johnson, Karan Desai.<br />
  "Benchmarking Object Detectors with COCO: A New Path Forward." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.18819)] 
  [[dataset](https://cocorem.xyz/)]
  [[code](https://github.com/kdexd/coco-rem)]
  [2024.03]

- Yuiko Sakuma, Masakazu Yoshimura, Junji Otsuka, Atsushi Irie, Takeshi Ohashi.<br />
  "Mixed-precision Supernet Training from Vision Foundation Models using Low Rank Adapter." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.20080)] 
  [2024.03]

- **Total-Decom:** Xiaoyang Lyu, Chirui Chang, Peng Dai, Yang-tian Sun, Xiaojuang Qi.<br />
  "Total-Decom: Decomposed 3D Scene Reconstruction with Minimal Interaction." CVPR (2024).
  [[paper](https://arxiv.org/abs/2403.19314)] 
  [[code](https://github.com/CVMI-Lab/Total-Decom.git)]
  [2024.03]

- **SAM-dPCR:** Yuanyuan Wei, Shanhang Luo, Changran Xu, Yingqi Fu, Qingyue Dong, Yi Zhang, Fuyang Qu, Guangyao Cheng, Yi-Ping Ho, Ho-Pui Ho, Wu Yuan.<br />
  "SAM-dPCR: Real-Time and High-throughput Absolute Quantification of Biological Samples Using Zero-Shot Segment Anything Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.18826)] 
  [2024.03]

- **H-SAM:** Zhiheng Cheng, Qingyue Wei, Hongru Zhu, Yan Wang, Liangqiong Qu, Wei Shao, Yuyin Zhou.<br />
  "Unleashing the Potential of SAM for Medical Adaptation via Hierarchical Decoding." CVPR (2024).
  [[paper](https://arxiv.org/abs/2403.18271)] 
  [[code](https://github.com/Cccccczh404/H-SAM)]
  [2024.03]

- **Annolid:** Chen Yang, Thomas A. Cleland.<br />
  "Annolid: Annotate, Segment, and Track Anything You Need." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.18690)] 
  [2024.03]

- **SAMME:** Yihao Liu, Jiaming Zhang, Andres Diaz-Pinto, Haowei Li, Alejandro Martin-Gomez, Amir Kheradmand, Mehran Armand.<br />
  "Segment Any Medical Model Extended." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.18114)] 
  [2024.03]

- **EgoLifter:** Qiao Gu, Zhaoyang Lv, Duncan Frost, Simon Green, Julian Straub, Chris Sweeney.<br />
  "EgoLifter: Open-world 3D Segmentation for Egocentric Perception." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.18118)] 
  [[code](https://egolifter.github.io/)]
  [2024.03]

- David Jurado-Rodr´ıguez, et al.<br />
  "SAM-Based Detection of Structural Anomalies in 3D Models for Preserving Cultural Heritage." VISAPP (2024).
  [[paper](https://www.researchgate.net/profile/Alfonso-Lopez-Ruiz-2/publication/378703243_SAM-Based_Detection_of_Structural_Anomalies_in_3D_Models_for_Preserving_Cultural_Heritage/links/65fb0552a8baf573a1c7a4e1/SAM-Based-Detection-of-Structural-Anomalies-in-3D-Models-for-Preserving-Cultural-Heritage.pdf)] 
  [2024.03]

- **MAkE-able:** Christoph Pohl, Fabian Reister, Fabian Peller-Konrad and Tamim Asfour.<br /> 
  "MAkE-able: Memory-centered and Affordance-based Task Execution Framework for Transferable Mobile Manipulation Skills." ArXiv (2024).
  [[paper](https://h2t.iar.kit.edu/pdf/PohlReister2024v2.pdf)] 
  [[code](https://h2t-projects.webarchiv.kit.edu/software/MAkEable)]
  [2024.03]

- **GoodSAM:** Weiming Zhang, Yexin Liu, Xu Zheng, Lin Wang.<br />
  "GoodSAM: Bridging Domain and Capacity Gaps via Segment Anything Model for Distortion-aware Panoramic Semantic Segmentation." CVPR (2024).
  [[paper](https://arxiv.org/abs/2403.16370)] 
  [[code](https://vlislab22.github.io/GoodSAM/)]
  [2024.03]


- **SPF+SPD:** Quan Zhang, Xiaoyu Liu, Wei Li, Hanting Chen, Junchao Liu, Jie Hu, Zhiwei Xiong, Chun Yuan, Yunhe Wang.<br />
  "Distilling Semantic Priors from SAM to Efficient Image Restoration Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.16368)] 
  [2024.03]

- **SAM-Road:** Congrui Hetang, Haoru Xue, Cindy Le, Tianwei Yue, Wenping Wang, Yihui He.<br />
  "Segment Anything Model for Road Network Graph Extraction." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.16051)] 
  [[code](https://github.com/htcr/sam_road)]
  [2024.03]

- **SAM_DataAnnotation:** Pranav Kulkarni, Adway Kanhere, Dharmam Savani, Andrew Chan, Devina Chatterjee, Paul H. Yi, Vishwa S. Parekh.<br />
  "Anytime, Anywhere, Anyone: Investigating the Feasibility of Segment Anything Model for Crowd-Sourcing Medical Image Annotations." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.15218)] 
  [[code](https://github.com/UM2ii/https://github.com/UM2ii/SAM_DataAnnotation)]
  [2024.03]

- **CT-SAM3D:** Heng Guo, Jianfeng Zhang, Jiaxing Huang, Tony C. W. Mok, Dazhou Guo, Ke Yan, Le Lu, Dakai Jin, Minfeng Xu.<br />
  "Towards a Comprehensive, Efficient and Promptable Anatomic Structure Segmentation Model using 3D Whole-body CT Scans." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.15063)] 
  [2024.03]

- **ALC:** Hoyoung Kim, Sehyun Hwang, Suha Kwak, Jungseul Ok.<br />
  "Active Label Correction for Semantic Segmentation with Foundation Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.10820)] 
  [2024.03]

- DiffCriticEdit:Ruicheng Wang, Jianfeng Xiang, Jiaolong Yang, Xin Tong.<br />
  "Diffusion Models are Geometry Critics: Single Image 3D Editing Using Pre-Trained Diffusion Priors." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.11503)] 
  [[code](https://wangrc.site/DiffCriticEdit/)]
  [2024.03]

- Rafaela Orenga Panizza, et al.<br />
  "Labeling Construction, Renovation, and Demolition Waste through Segment Anything Model (SAM)." Construction Research Congress (2024).
  [[paper](https://ascelibrary.org/doi/abs/10.1061/9780784485262.029)] 
  [2024.03]

- **SAM-AutoMed:** Jiakang Sun, Ke Chen, Zhiyi He, Siyuan Ren, Xinyang He, Xu Liu, Cheng Peng .<br />
  "Medical Image Analysis using Improved SAM-Med2D: Segmentation and Classification Perspectives." ArXiv (2024).
  [[paper](https://www.researchsquare.com/article/rs-4021598/v1)] 
  [2024.03]

- **RASP:** Minghui Zhao, Junxi Xia, Kaiyuan Hou, Yanchen Liu, Stephen Xia, Xiaofan Jiang.<br />
  "RASP: A Drone-based Reconfigurable Actuation and Sensing Platform Towards Ambient Intelligent Systems." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.12853)] 
  [2024.03]

- **WebSAM-Adapter:** Ren, B., Qian, Z., Sun, Y., Gao, C., Zhang, C.<br />
  "WebSAM-Adapter: Adapting Segment Anything Model for Web Page Segmentation." ECIR (2024).
  [[paper](https://link.springer.com/chapter/10.1007/978-3-031-56027-9_27)] 
  [2024.03]

- **ProMamba:** Jianhao Xie, Ruofan Liao, Ziang Zhang, Sida Yi, Yuesheng Zhu, Guibo Luo.<br />
  "ProMamba: Prompt-Mamba for polyp segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.13660)] 
  [2024.03]

- **MTP:** Di Wang, Jing Zhang, Minqiang Xu, Lin Liu, Dongsheng Wang, Erzhong Gao, Chengxi Han, Haonan Guo, Bo Du, Dacheng Tao, Liangpei Zhang.<br />
  "MTP: Advancing Remote Sensing Foundation Model via Multi-Task Pretraining." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.13430)] 
  [[code](https://github.com/ViTAE-Transformer/MTP)]
  [2024.03]

- Connor Lee, Saraswati Soedarmadji, Matthew Anderson, Anthony J. Clark, and Soon-Jo Chung.<br />
  "Semantics from Space: Satellite-Guided Thermal Semantic Segmentation Annotation for Aerial Field Robots." ArXiv (2024).
  [[paper](https://arxiv.org/pdf/2403.14056.pdf)] 
  [[code](https://github.com/connorlee77/aerial-auto-segment)]
  [2024.03]

- Luna, Miguel, Philip Chikontwe, and Sang Hyun Park.<br />
  "Enhanced Nuclei Segmentation and Classification via Category Descriptors in the SAM Model." Bioengineering (2024).
  [[paper](https://www.mdpi.com/2306-5354/11/3/294)] 
  [2024.03]

- **MoCA:** Swapnil Bhosale, Haosen Yang, Diptesh Kanojia, Jiangkang Deng, Xiatian Zhu.<br />
  "Unsupervised Audio-Visual Segmentation with Modality Alignment." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.14203)] 
  [2024.03]

- **LLaVASeg:** Yuqi Yang, Peng-Tao Jiang, Jing Wang, Hao Zhang, Kai Zhao, Jinwei Chen, Bo Li.<br />
  "Empowering Segmentation Ability to Multi-modal Large Language Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.14141)] 
  [[code](https://github.com/YuqiYang213/LLaVASeg)]
  [2024.03]

- **MaskSAM:** Bin Xie, Hao Tang, Bin Duan, Dawen Cai, Yan Yan.<br />
  "MaskSAM: Towards Auto-prompt SAM with Mask Classification for Medical Image Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.14103)] 
  [2024.03]

- **SAL:** Aljoša Ošep, Tim Meinhardt, Francesco Ferroni, Neehar Peri, Deva Ramanan, Laura Leal-Taixé.<br />
  "Better Call SAL: Towards Learning to Segment Anything in Lidar." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.13129)] 
  [[code](https://research.nvidia.com/labs/dvl/projects/sal)]
  [2024.03]

- **SAMCT:** Xian Lin, Yangyang Xiang, Zhehao Wang, Kwang-Ting Cheng, Zengqiang Yan, Li Yu.<br />
  "SAMCT: Segment Any CT Allowing Labor-Free Task-Indicator Prompts." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.13258)] 
  [[code](https://github.com/xianlin7/SAMCT)]
  [2024.03]

- Efrain Torres-Lomas, Jimena Lado-Jimena, Guillermo Garcia-Zamora, Luis Diaz-Garcia.<br />
  "Segment Anything for comprehensive analysis of grapevine cluster architecture and berry properties." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.12935)] 
  [2024.03]

- Roland Gruber, Steffen Rüger, Thomas Wittenberg.<br />
  "Adapting SAM for Volumetric X-Ray Data-sets of Arbitrary Sizes." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.12066)] 
  [2024.03]

- **LocalStyleFool:** Yuxin Cao, Jinghao Li, Xi Xiao, Derui Wang, Minhui Xue, Hao Ge, Wei Liu, Guangwu Hu.<br />
  "LocalStyleFool: Regional Video Style Transfer Attack Using Segment Anything Model." SPW (2024).
  [[paper](https://arxiv.org/abs/2403.11656)] 
  [2024.03]

- **CCC++:** Mrityunjoy Gain, Avi Deb Raha, Rameswar Debnath.<br />
  "CCC++: Optimized Color Classified Colorization with Segment Anything Model (SAM) Empowered Object Selective Color Harmonization." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.11494)] 
  [2024.03]

- **CFR:** Shumeng Li, Lei Qi, Qian Yu, Jing Huo, Yinghuan Shi, Yang Gao.<br />
  "Concatenate, Fine-tuning, Re-training: A SAM-enabled Framework for Semi-supervised 3D Medical Image Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.11229)] 
  [[code](https://github.com/ShumengLI/CFR)]
  [2024.03]

- **TA-LoRA:** Xuehao Wang, Feiyang Ye, Yu Zhang.<br />
  "Task-Aware Low-Rank Adaptation of Segment Anything Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.10971)] 
  [2024.03]

- **UA-SAM:** Mingzhou Jiang, Jiaying Zhou, Junde Wu, Tianyang Wang, Yueming Jin, Min Xu.<br />
  "Uncertainty-Aware Adapter: Adapting Segment Anything Model (SAM) for Ambiguous Medical Image Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.10931)] 
  [[code](http://segmentation.it/)]
  [2024.03]

- **MS-UGCML:** Shichao Kan, Yuhai Deng, Yixiong Liang, Lihui Cen, Zhe Qu, Yigang Cen, Zhihai He.<br />
  "Unsupervised Collaborative Metric Learning with Mixed-Scale Groups for General Object Retrieval." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.10798)] 
  [[code](https://github.com/dengyuhai/MS-UGCML)]
  [2024.03]

- **SAOM:** Mariia Khan, Yue Qiu, Yuren Cong, Jumana Abu-Khalaf, David Suter, Bodo Rosenhahn.<br />
  "Segment Any Object Model (SAOM): Real-to-Simulation Fine-Tuning Strategy for Multi-Class Multi-Instance Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.10780)] 
  [2024.03]

- **FastSAM3D:** Yiqing Shen, Jingxing Li, Xinyuan Shao, Blanca Inigo Romillo, Ankush Jindal, David Dreizin, Mathias Unberath.<br />
  "FastSAM3D: An Efficient Segment Anything Model for 3D Volumetric Medical Images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.09827)] 
  [[code](https://github.com/arcadelab/FastSAM3D)]
  [2024.03]

- **CMR2D+T-SAM:** Zhennong Chen, Sekeun Kim, Hui Ren, Quanzheng Li, Xiang Li.<br />
  "Cardiac Magnetic Resonance 2D+T Short- and Long-axis Segmentation via Spatio-temporal SAM Adaptation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.10009)] 
  [2024.03]

- **Group-Mix SAM:** Wu Liang, X.-G. Ma.<br />
  "Group-Mix SAM: Lightweight Solution for Industrial Assembly Line Applications." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.10053)] 
  [2024.03]

- **TransLandSeg:** Changhong Hou, Junchuan Yu, Daqing Ge, Liu Yang, Laidian Xi, Yunxuan Pang, Yi Wen.<br />
  "TransLandSeg: A Transfer Learning Approach for Landslide Semantic Segmentation Based on Vision Foundation Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.10127)] 
  [2024.03]

- **Grasp Anything:** Malte Mosbach, Sven Behnke.<br />
  "Grasp Anything: Combining Teacher-Augmented Policy Gradient Learning with Instance Segmentation to Grasp Arbitrary Objects." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.10187)] 
  [[code](https://maltemosbach.github.io/grasp_anything)]
  [2024.03]

- **RDC:** Meixuan Li, Tianyu Li, Guoqing Wang, Peng Wang, Yang Yang, Heng Tao Shen.<br />
  "Region-aware Distribution Contrast: A Novel Approach to Multi-Task Partially Supervised Learning." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.10252)] 
  [2024.03]

- **VISE:** Tian Meng, Yang Tao, Ruilin Lyu, Wuliang Yin.<br />
  "Few-Shot Image Classification and Segmentation as Visual Question Answering Using Vision-Language Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.10287)] 
  [2024.03]

- **DiffuMatting:** Xiaobin Hu, Xu Peng, Donghao Luo, Xiaozhong Ji, Jinlong Peng, Zhengkai Jiang, Jiangning Zhang, Taisong Jin, Chengjie Wang, Rongrong Ji.<br />
  "DiffuMatting: Synthesizing Arbitrary Objects with Matting-level Annotation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.06168)] 
  [2024.03]

- **ClickVOS:** Pinxue Guo, Lingyi Hong, Xinyu Zhou, Shuyong Gao, Wanyun Li, Jinglun Li, Zhaoyu Chen, Xiaoqiang Li, Wei Zhang, Wenqiang Zhang.<br />
  "ClickVOS: Click Video Object Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.06130)] 
  [[code](https://github.com/PinxueGuo/ClickVOS)]
  [2024.03]

- Kong, L.; Huang, M.; Zhang, L.; Chan, L.W.C.<br />
  "Enhancing Diagnostic Images to Improve the Performance of the Segment Anything Model in Medical Image Segmentation." Bioengineering (2024).
  [[paper](https://www.mdpi.com/2306-5354/11/3/270)] 
  [2024.03]

- **FSViewFusion:** Rukhshanda Hussain, Hui Xian Grace Lim, Borchun Chen, Mubarak Shah, Ser Nam Lim.<br />
  "FSViewFusion: Few-Shots View Generation of Novel Objects." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.06394)] 
  [2024.03]

- **V-PRISM:** Herbert Wright, Weiming Zhi, Matthew Johnson-Roberson, Tucker Hermans.<br />
  "V-PRISM: Probabilistic Mapping of Unknown Tabletop Scenes." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.08106)] 
  [[code](https://github.com/Herb-Wright/v-prism)]
  [2024.03]

- **CCSpO2Net:** Sun, Xiantao and Wen, Tao and Chen, Weihai and Huang, Bin.<br />
  "CCSpO2Net: Camera-Based Contactless Oxygen Saturation Measurement Foundation Model in Clinical Settings." TIM (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10464344)] 
  [2024.03]

- **Unveiling the Truth:** Cartella, Giuseppe and Cuculo, Vittorio and Cornia, Marcella and Cucchiara, Rita.<br />
  "Unveiling the Truth: Exploring Human Gaze Patterns in Fake Images." APL (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10465604)] 
  [[code](https://github.com/aimagelab/unveiling-the-truth)]
  [2024.03]

- **V-PRISM:** Herbert Wright, Weiming Zhi, Matthew Johnson-Roberson, Tucker Hermans.<br />
  "V-PRISM: Probabilistic Mapping of Unknown Tabletop Scenes." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.08106)] 
  [[code](https://github.com/Herb-Wright/v-prism)]
  [2024.03]

- Stefan Denner, David Zimmerer, Dimitrios Bounias, Markus Bujotzek, Shuhan Xiao, Lisa Kausch, Philipp Schader, Tobias Penzkofer, Paul F. Jäger, Klaus Maier-Hein.<br />
  "Leveraging Foundation Models for Content-Based Medical Image Retrieval in Radiology." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.06567)] 
  [2024.03]

- Chaoyi Wang, Yaozhe Song, Yafeng Zhang, Jun Pei, Lijie Xia, Jianpo Liu.<br />
  "Video Generation with Consistency Tuning." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.06356)] 
  [2024.03]

- **Sam-Rsp:** Jiaguang Li, et al.<br />
  "Sam-Rsp: A New Few-Shot Segmentation Method Based on Segment Anything Model and Rough Segmentation Prompts." SSRN (2024).
  [[paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4756692)] 
  [[code](https://github.com/Jiaguang-NEU/SAM-RSP)]
  [2024.03]

- **Lumen:** Yang Jiao, Shaoxiang Chen, Zequn Jie, Jingjing Chen, Lin Ma, Yu-Gang Jiang.<br />
  "Lumen: Unleashing Versatile Vision-Centric Capabilities of Large Multimodal Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.07304)] 
  [[code](https://github.com/SxJyJay/Lumen)]
  [2024.03]

- **RSBuilding:** Mingze Wang, Keyan Chen, Lili Su, Cilin Yan, Sheng Xu, Haotian Zhang, Pengcheng Yuan, Xiaolong Jiang, Baochang Zhang.<br />
  "RSBuilding: Towards General Remote Sensing Image Building Extraction and Change Detection with Foundation Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.07564)] 
  [[code](https://github.com/Meize0729/RSBuilding)]
  [2024.03]

- **DragAnything:** Weijia Wu, Zhuang Li, Yuchao Gu, Rui Zhao, Yefei He, David Junhao Zhang, Mike Zheng Shou, Yan Li, Tingting Gao, Di Zhang.<br />
  "DragAnything: Motion Control for Anything using Entity Representation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.07420)] 
  [[code](https://github.com/showlab/DragAnything)]
  [[homepage](https://weijiawu.github.io/draganything_page/)]
  [2024.03]

- **ARtVista:** Trong-Vu Hoang, Quang-Binh Nguyen, Duy-Nam Ly, Khanh-Duy Le, Tam V. Nguyen, Minh-Triet Tran, Trung-Nghia Le.<br />
  "ARtVista: Gateway To Empower Anyone Into Artist." CHI (2024).
  [[paper](https://arxiv.org/abs/2403.08876)] 
  [[code](https://github.com/htrvu/ARtVista)]
  [2024.03]

- **ChemSAM:** Bowen Tang, et al.<br />
  "Automated molecular structure segmentation from documents using ChemSAM." ArXiv (2024).
  [[paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-024-00823-2)] 
  [2024.03]

- **DAL:** Zhang, Fayong and Liu, Kejun and Liu, Yuanyuan and Wang, Chaofan and Zhou, Wujie and Zhang, Hongyan and Wang, Lizhe.<br />
  "Multi-target Domain Adaptation Building Instance Extraction of Remote Sensing Imagery with Domain-common Approximation learning." TGRS (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10471580)] 
  [2024.03]

- **VisionGPT:** Chris Kelly, Luhui Hu, Bang Yang, Yu Tian, Deshun Yang, Cindy Yang, Zaoshan Huang, Zihao Li, Jiayin Hu, Yuexian Zou.<br />
  "VisionGPT: Vision-Language Understanding Agent Using Generalized Multimodal Framework." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.09027)] 
  [2024.03]

- **WeakSurg:** Qiyuan Wang, Yanzhe Liu, Shang Zhao, Rong Liu, S. Kevin Zhou.<br />
  "WeakSurg: Weakly supervised surgical instrument segmentation using temporal equivariance and semantic continuity." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.09551)] 
  [2024.03]

- **Ref LDM-Seg:** Chaoyang Wang, Xiangtai Li, Henghui Ding, Lu Qi, Jiangning Zhang, Yunhai Tong, Chen Change Loy, Shuicheng Yan.<br />
  "Explore In-Context Segmentation via Latent Diffusion Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.09616)] 
  [[code](https://wang-chaoyang.github.io/project/refldmseg)]
  [2024.03]

- **GaussianGrasper:** Yuhang Zheng, Xiangyu Chen, Yupeng Zheng, Songen Gu, Runyi Yang, Bu Jin, Pengfei Li, Chengliang Zhong, Zengmao Wang, Lina Liu, Chao Yang, Dawei Wang, Zhen Chen, Xiaoxiao Long, Meiqing Wang.<br />
  "GaussianGrasper: 3D Language Gaussian Splatting for Open-vocabulary Robotic Grasping." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.09637)] 
  [[code](https://github.com/MrSecant/GaussianGrasper)]
  [2024.03]

- Soroush Seifi, Daniel Olmeda Reino, Fabien Despinoy, Rahaf Aljundi.<br />
  "Annotation Free Semantic Segmentation with Vision Foundation Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.09307)] 
  [2024.03]

- **SLCF-Net:** Helin Cao, Sven Behnke.<br />
  "SLCF-Net: Sequential LiDAR-Camera Fusion for Semantic Scene Completion using a 3D Recurrent U-Net." ICRA (2024).
  [[paper](https://arxiv.org/abs/2403.08885)] 
  [2024.03]

- **SAM-Lightening:** Yanfei Songa, Bangzheng Pua, Peng Wanga, Hongxu Jiang, Dong Donga, Yiqing Shen.<br />
  "SAM-Lightening: A Lightweight Segment Anything Model with Dilated Flash Attention to Achieve 30 times Acceleration." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.09195)] 
  [[code](https://anonymous.4open.science/r/SAM-LIGHTENING-BC25/)]
  [2024.03]

- **DF4LCZ:** Qianqian Wu, Xianping Ma, Jialu Sui, and Man-On Pun.<br />
  "DF4LCZ: A SAM-Empowered Data Fusion Framework for Scene-Level Local Climate Zone Classification." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.09367)] 
  [[code](https://github.com/ctrlovefly/DF4LCZ)]
  [2024.03]

- **PosSAM:** Vibashan VS, Shubhankar Borse, Hyojin Park, Debasmit Das, Vishal Patel, Munawar Hayat, Fatih Porikli.<br />
  "PosSAM: Panoptic Open-vocabulary Segment Anything." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.09620)] 
  [[code](https://vibashan.github.io/possam-web/)]
  [2024.03]

- **PLM+PMM:** Hyung-Il Kim, Kimin Yun, Jun-Seok Yun, Yuseok Bae.<br />
  "Customizing Segmentation Foundation Model via Prompt Learning for Instance Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.09199)] 
  [2024.03]

- **WSI-SAM:** Hong Liu, Haosen Yang, Paul J. van Diest, Josien P.W. Pluim, Mitko Veta.<br />
  "WSI-SAM: Multi-resolution Segment Anything Model (SAM) for histopathology whole-slide images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.09257)] 
  [[code](https://github.com/HongLiuuuuu/WSI-SAM)]
  [2024.03]

- **SAMDA:** Yiran Wang, Li Xiao.<br />
  "SAMDA: Leveraging SAM on Few-Shot Domain Adaptation for Electronic Microscopy Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.07951)] 
  [2024.03]

- Zijian Wu, Adam Schmidt, Peter Kazanzides, Septimiu E. Salcudean.<br />
  "Real-time Surgical Instrument Segmentation in Video Using Point Tracking and Segment Anything." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.08003)] 
  [2024.03]

- Zijian Wu, Adam Schmidt, Peter Kazanzides, Septimiu E. Salcudean.<br />**FluoroSAM:** Benjamin D. Killeen, Liam J. Wang, Han Zhang, Mehran Armand, Russell H. Taylor, Greg Osgood, Mathias Unberath.<br />
  "FluoroSAM: A Language-aligned Foundation Model for X-ray Image Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.08059)] 
  [[code](https://github.com/arcadelab/fluorosam)]
  [2024.03]

- **ReimaginedAct:** Lan Wang, Vishnu Boddeti, Sernam Lim.<br />
  "Action Reimagined: Text-to-Pose Video Editing for Dynamic Human Actions." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.07198)] 
  [2024.03]

- **GEOBIA:** He, Tao and Chen, Jianyu and Kang, Linchong and Zhu, Qiankun.<br />
  "Evaluation of Global-Scale and Local-Scale Optimized Segmentation Algorithms in GEOBIA with SAM on Land Use and Land Cover." JSTARS (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10460074)] 
  [2024.03]

- **ObjectCompose:** Hashmat Shadab Malik, Muhammad Huzaifa, Muzammal Naseer, Salman Khan, Fahad Shahbaz Khan.<br />
  "ObjectCompose: Evaluating Resilience of Vision-Based Models on Object-to-Background Compositional Changes." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.04701)] 
  [2024.03]

- Yao Jiang, Xinyu Yan, Ge-Peng Ji, Keren Fu, Meijun Sun, Huan Xiong, Deng-Ping Fan, Fahad Shahbaz Khan.<br />
  "Effectiveness Assessment of Recent Large Vision-Language Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.04306)] 
  [2024.03]

- Giannakis, I., Bhardwaj, A., Sam, L., and Leontidis, G..<br />
  "Segment Anything Model (SAM) for Automatic Crater Detection." EGU General Assembly (2024).
  [[paper](https://meetingorganizer.copernicus.org/EGU24/EGU24-21146.html)] 
  [2024.03]

- Bocchino, F., Sergi, G., Ravanelli, R., and Crespi, M..<br />
  "Preliminary analysis of the potentialities of the Segment Anything Model (SAM) in the segmentation of Sentinel-2 imagery for water reservoir monitoring." EGU General Assembly (2024).
  [[paper](https://meetingorganizer.copernicus.org/EGU24/EGU24-11145.html)] 
  [2024.03]

- Ruiqing Yan , et al.<br />
  "Weakly-semi supervised extraction of rooftop photovoltaics from high-resolution images based on segment anything model and class activation map." Applied Energy (2024).
  [[paper](https://www.sciencedirect.com/science/article/pii/S0306261924003477)] 
  [2024.03]

- **CSFwinformer:** Xie, Zhifeng and Wang, Sen and Yu, Qiucheng and Tan, Xin and Xie, Yuan.<br />
  "CSFwinformer: Cross-Space-Frequency Window Transformer for Mirror Detection." TIP (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10462920)] 
  [[code](https://github.com/wangsen99/CSFwinformer)]
  [2024.03]

- Xiaoyuan Liu,  et al.<br />
  "Stereo Vision Meta-Lens-Assisted Driving Vision." ACS Photonics (2024).
  [[paper](https://pubs.acs.org/doi/full/10.1021/acsphotonics.3c01594)] 
  [2024.03]

- **PointSeg:** Qingdong He, Jinlong Peng, Zhengkai Jiang, Xiaobin Hu, Jiangning Zhang, Qiang Nie, Yabiao Wang, Chengjie Wang.<br />
  "PointSeg: A Training-Free Paradigm for 3D Scene Segmentation via Foundation Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.06403)] 
  [2024.03]

- **MEA:** Hairong Shi, Songhao Han, Shaofei Huang, Yue Liao, Guanbin Li, Xiangxing Kong, Hua Zhu, Xiaomu Wang, Si Liu.<br />
  "Mask-Enhanced Segment Anything Model for Tumor Lesion Semantic Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.05912)] 
  [2024.03]

- **GAM-3DSC:** Feibo Jiang, Yubo Peng, Li Dong, Kezhi Wang, Kun Yang, Cunhua Pan, Xiaohu You.<br />
  "Large Generative Model Assisted 3D Semantic Communication." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.05783)] 
  [2024.03]

- **APPLE:** Zikang Xu, Fenghe Tang, Quan Quan, Qingsong Yao, S. Kevin Zhou.<br />
  "APPLE: Adversarial Privacy-aware Perturbations on Latent Embedding for Unfairness Mitigation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.05114)] 
  [2024.03]

- **FedFMS:** Yuxi Liu, Guibo Luo, Yuesheng Zhu.<br />
  "FedFMS: Exploring Federated Foundation Models for Medical Image Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.05408)] 
  [[code](https://github.com/LIU-YUXI/FedFMS)]
  [2024.03]

- **OmniCount:** Anindya Mondal, Sauradip Nag, Xiatian Zhu, Anjan Dutta.<br />
  "OmniCount: Multi-label Object Counting with Semantic-Geometric Priors." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.05435)] 
  [2024.03]

- **P^2SAM:** Chenhui Zhao, Liyue Shen.<br />
  "Part-aware Personalized Segment Anything Model for Patient-Specific Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.05433)] 
  [2024.03]

- **SAM-PD:** Tao Zhou, Wenhan Luo, Qi Ye, Zhiguo Shi, Jiming Chen.<br />
  "SAM-PD: How Far Can SAM Take Us in Tracking and Segmenting Anything in Videos by Prompt Denoising." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.04194)] 
  [[code](https://github.com/infZhou/SAM-PD)]
  [2024.03]

- **SA-ICM:** Takahiro Shindo, Kein Yamada, Taiju Watanabe, Hiroshi Watanabe.<br />
  "Image Coding for Machines with Edge Information Learning Using Segment Anything." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.04173)] 
  [2024.03]

- **ProMISe:** Jinfeng Wang, Sifan Song, Xinkun Wang, Yiyi Wang, Yiyi Miao, Jionglong Su, S. Kevin Zhou.<br />
  "ProMISe: Promptable Medical Image Segmentation using SAM." ArXiv (2024).
  [[paper](https://arxiv.org/pdf/2403.04164.pdf)] 
  [2024.03]

- **Popeye:** Wei Zhang, Miaoxin Cai, Tong Zhang, Guoqiang Lei, Yin Zhuang, Xuerui Mao.<br />
  "Popeye: A Unified Visual-Language Model for Multi-Source Ship Detection from Remote Sensing Imagery." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.03790)] 
  [2024.03]

- Kevin Shen, Surabhi S Nath, Aenne Brielmann, Peter Dayan.<br />
  "Simplicity in Complexity." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.03134)] 
  [2024.03]

- **CCC:** Mrityunjoy Gain, Avi Deb Raha, Rameswar Debnath.<br />
  "CCC: Color Classified Colorization." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.01476)] 
  [2024.03]

- **CAC:** Yuhao Lin, Haiming Xu, Lingqiao Liu, Javen Qinfeng Shi.<br />
  "A Simple-but-effective Baseline for Training-free Class-Agnostic Counting." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.01418)] 
  [2024.03]

- Khatua, A., Bhattacharya, A., Goswami, A.K. et al.<br />
  "Developing approaches in building classification and extraction with synergy of YOLOV8 and SAM models." 
Spatial Information Research (2024).
  [[paper](https://link.springer.com/article/10.1007/s41324-024-00574-0)] 
  [2024.03]

- Toki Tahmid Inan, Mingrui Liu, Amarda Shehu.<br />
  "Beyond Single-Model Views for Deep Learning: Optimization versus Generalizability of Stochastic Optimization Algorithms." AAAI (2024).
  [[paper](https://arxiv.org/abs/2403.00574)] 
  [2024.03]

- Xu, Binwei and Jiang, Qiuping and Zhao, Xing and Lu, Chenyang and Liang, Haoran and Liang, Ronghua.<br />
  "Multidimensional Exploration of Segment Anything Model for Weakly Supervised Video Salient Object Detection." TCSVT  (2024).
  [[paper](https://ieeexplore.ieee.org/document/10443051)] 
  [2024.02]

- **GVA:** Xinqi Liu, Chenming Wu, Jialun Liu, Xing Liu, Jinbo Wu, Chen Zhao, Haocheng Feng, Errui Ding, Jingdong Wang.<br />
  "GVA: Reconstructing Vivid 3D Gaussian Avatars from Monocular Videos." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.16607)] 
  [[code](https://3d-aigc.github.io/GVA/)]
  [2024.02]

- **OHTA:** Xiaozheng Zheng, Chao Wen, Zhuo Su, Zeran Xu, Zhaohu Li, Yang Zhao, Zhou Xue.<br />
  "OHTA: One-shot Hand Avatar via Data-driven Implicit Priors." CVPR (2024).
  [[paper](https://arxiv.org/abs/2402.18969)] 
  [[code](https://zxz267.github.io/OHTA)]
  [2024.02]
  
- **FusionVision:** Safouane El Ghazouali, Youssef Mhirit, Ali Oukhrid, Umberto Michelucci, Hichem Nouira.<br />
  "FusionVision: A comprehensive approach of 3D object reconstruction and segmentation from RGB-D cameras using YOLO and fast segment anything." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2403.00175)] 
  [[code](https://github.com/safouaneelg/FusionVision/)]
  [2024.02]

- **GROUNDHOG:** Yichi Zhang, Ziqiao Ma, Xiaofeng Gao, Suhaila Shakiah, Qiaozi Gao, Joyce Chai.<br />
  "GROUNDHOG : Grounding Large Language Models to Holistic Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.16846)] 
  [[code](https://groundhog-mllm.github.io/)]
  [2024.02]

- **POC:** Pau de Jorge, Riccardo Volpi, Puneet K. Dokania, Philip H. S. Torr, Gregory Rogez.<br />
  "Placing Objects in Context via Inpainting for Out-of-distribution Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.16392)] 
  [[code](https://github.com/naver/poc)]
  [2024.02]

- **GEA:** Xinqi Liu, Chenming Wu, Xing Liu, Jialun Liu, Jinbo Wu, Chen Zhao, Haocheng Feng, Errui Ding, Jingdong Wang.<br />
  "GEA: Reconstructing Expressive 3D Gaussian Avatar from Monocular Video." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.16607)] 
  [[code](https://3d-aigc.github.io/GEA/)]
  [2024.02]

- **Surgment:** Jingying Wang, Haoran Tang, Taylor Kantor, Tandis Soltani, Vitaliy Popov, Xu Wang.<br />
  "Surgment: Segmentation-enabled Semantic Search and Creation of Visual Question and Feedback to Support Video-Based Surgery Learning." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.17903)] 
  [2024.02]

- **sViT:** Young Kyung Kim, J. Matías Di Martino, Guillermo Sapiro.<br />
  "Vision Transformers with Natural Language Semantics." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.17863)] 
  [2024.02]

- Huang, Wenjun, Anzhu Yu, Qing Xu, Qun Sun, Wenyue Guo, Song Ji, Bowei Wen, and Chunping Qiu.<br />
  "Sea Ice Extraction via Remote Sensing Imagery: Algorithms, Datasets, Applications and Challenges." Remote Sensing (2024).
  [[paper](https://www.mdpi.com/2072-4292/16/5/842)] 
  [2024.02]

- **OpenMEDLab:** Xiaosong Wang, Xiaofan Zhang, Guotai Wang, Junjun He, Zhongyu Li, Wentao Zhu, Yi Guo, Qi Dou, Xiaoxiao Li, Dequan Wang, Liang Hong, Qicheng Lao, Tong Ruan, Yukun Zhou, Yixue Li, Jie Zhao, Kang Li, Xin Sun, Lifeng Zhu, Shaoting Zhang.<br />
  "OpenMEDLab: An Open-source Platform for Multi-modality Foundation Models in Medicine." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.18028)] 
  [[code](https://github.com/openmedlab)]
  [2024.02]

- **RSAM-Seg:** Jie Zhang, Xubing Yang, Rui Jiang, Wei Shao, Li Zhang.<br />
  "RSAM-Seg: A SAM-based Approach with Prior Knowledge Integration for Remote Sensing Image Semantic Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.19004)] 
  [[code](https://chief-byte.github.io/RSAM-Seg-Site)]
  [2024.02]

- **STLM:** Chenghao Li, Lei Qi, Xin Geng.<br />
  "A SAM-guided Two-stream Lightweight Model for Anomaly Detection." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.19145)] 
  [2024.02]

- Kanyifeechukwu J. Oguine, Roger D. Soberanis-Mukul, Nathan Drenkow, Mathias Unberath.<br />
  "From Generalization to Precision: Exploring SAM for Tool Segmentation in Surgical Environments." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.17972)] 
  [2024.02]

- **VRP-SAM:** Yanpeng Sun, Jiahui Chen, Shan Zhang, Xinyu Zhang, Qiang Chen, Gang Zhang, Errui Ding, Jingdong Wang, Zechao Li.<br />
  "VRP-SAM: SAM with Visual Reference Prompt." CVPR (2024).
  [[paper](https://arxiv.org/abs/2402.17726)] 
  [2024.02]

- **SAM-DiffSR:** Chengcheng Wang, Zhiwei Hao, Yehui Tang, Jianyuan Guo, Yujie Yang, Kai Han, Yunhe Wang.<br />
  "SAM-DiffSR: Structure-Modulated Diffusion Model for Image Super-Resolution." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.17133)] 
  [[code](https://github.com/lose4578/SAM-DiffSR)]
  [2024.02]

- Jintao Ren, Mathis Rasmussen, Jasper Nijkamp, Jesper Grau Eriksen, Stine Korreman.<br />
  "Segment anything model for head and neck tumor segmentation with CT, PET and MRI multi-modality images." ICCR (2024).
  [[paper](https://arxiv.org/abs/2402.17454)] 
  [2024.02]

- **AdaSEEM:** Jia Wan, Qiangqiang Wu, Wei Lin, Antoni B. Chan.<br />
  "Robust Unsupervised Crowd Counting and Localization with Adaptive Resolution SAM." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.17514)] 
  [2024.02]

- **BLO-SAM:** Li Zhang, Youwei Liang, Pengtao Xie.<br />
  "BLO-SAM: Bi-level Optimization Based Overfitting-Preventing Finetuning of SAM." ICML (2024).
  [[paper](https://arxiv.org/abs/2402.16338)] 
  [[code](https://github.com/importZL/BLO-SAM)]
  [2024.02]
  
- **UN-SAM:** Zhen Chen, Qing Xu, Xinyu Liu, Yixuan Yuan.<br />
  "UN-SAM: Universal Prompt-Free Segmentation for Generalized Nuclei Images." TMI (2024).
  [[paper](https://arxiv.org/abs/2402.16663)] 
  [[code](https://github.com/CUHK-AIM-Group/UN-SAM)]
  [2024.02]

- **TV-SAM:** Zekun Jiang, Dongjie Cheng, Ziyuan Qin, Jun Gao, Qicheng Lao, Kang Li, Le Zhang.<br />
  "Increasing SAM Zero-Shot Performance on Multimodal Medical Images Using GPT-4 Generated Descriptive Prompts Without Human Annotation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.15759)] 
  [[code](https://github.com/JZK00/TV-SAM)]
  [2024.02]

- **CoFRIDA:** Peter Schaldenbrand, Gaurav Parmar, Jun-Yan Zhu, James McCann, Jean Oh.<br />
  "CoFRIDA: Self-Supervised Fine-Tuning for Human-Robot Co-Painting." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.13442)] 
  [[code](https://pschaldenbrand.github.io/cofrida/)]
  [2024.02]

- **CVLM:** Yunxin Li, Xinyu Chen, Baotian Hu, Haoyuan Shi, Min Zhang.<br />
  "Cognitive Visual-Language Mapper: Advancing Multimodal Comprehension with Enhanced Visual Knowledge Alignment." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.13561)] 
  [2024.02]

- **SAM-EDA:** Wang, Ziquan, Yongsheng Zhang, Zhenchao Zhang, Zhipeng Jiang, Ying Yu, Li Li, and Lei Li.<br />
  "Exploring Semantic Prompts in the Segment Anything Model for Domain Adaptation." Remote Sensing (2024).
  [[paper](https://www.mdpi.com/2072-4292/16/5/758)] 
  [2024.02]

- **DSAIL-TreeVision:** Cedric Kiplimo and Collins Emasi Epege and Ciira wa Maina and Billy Okal.<br />
  "DSAIL-TreeVision: A software tool for extracting tree biophysical parameters from stereoscopic images." SoftwareX (2024).
  [[paper](https://www.sciencedirect.com/science/article/pii/S2352711024000323)] 
  [[code](https://github.com/DeKUT-DSAIL/TreeVision)]
  [2024.02]

- Xia, Jiahao and Gong, Gavin and Liu, Jiawei and Zhu, Zhigang and Tang, Hao.<br />
  "Pedestrian-Accessible Infrastructure Inventory: Enabling and Assessing Zero-Shot Segmentation on Multi-Mode Geospatial Data for All Pedestrian Types." Journal of Imaging (2024).
  [[paper](https://www.mdpi.com/2313-433X/10/3/52)] 
  [2024.02]

- **LIMP:** Benedict Quartey, Eric Rosen, Stefanie Tellex, George Konidaris.<br />
  "Verifiably Following Complex Robot Instructions with Foundation Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.11498)] 
  [[code](https://robotlimp.github.io/)]
  [2024.02]

- **LMPC:** Jacky Liang, Fei Xia, Wenhao Yu, et al.<br />
  "Learning to Learn Faster from Human Feedback with Language Model Predictive Control." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.11450)] 
  [[code](https://robot-teaching.github.io/)]
  [2024.02]

- Chong Di, Jie Gong.<br />
  "An AI-based approach to create spatial inventory of safety-related architectural features for school buildings." DBE (2024).
  [[paper](https://www.sciencedirect.com/science/article/pii/S2666165924000577)] 
  [2024.02]

- **WeakSAM:** Lianghui Zhu, Junwei Zhou, Yan Liu, Xin Hao, Wenyu Liu, Xinggang Wang.<br />
  "WeakSAM: Segment Anything Meets Weakly-supervised Instance-level Recognition." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.14812)] 
  [[code](https://github.com/hustvl/WeakSAM)]
  [2024.02]

- **SeqAE:** Delong Chen, Samuel Cahyawijaya, Jianfeng Liu, Baoyuan Wang, Pascale Fung.<br />
  "Subobject-level Image Tokenization." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.14327)] 
  [[code](https://github.com/ChenDelong1999/subobjects)]
  [2024.02]

- **DeiSAM:** Hikaru Shindo, Manuel Brack, Gopika Sudhakaran, Devendra Singh Dhami, Patrick Schramowski, Kristian Kersting.<br />
  "DeiSAM: Segment Anything with Deictic Prompting." NeurIPS (2024).
  [[paper](https://arxiv.org/abs/2402.14123)] 
  [2024.02]

- **OBJ-GSP:** Wenxiao Cai, Wankou Yang.<br />
  "Object-level Geometric Structure Preserving for Natural Image Stitching." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.12677)] 
  [[code](https://github.com/RussRobin/OBJ-GSP)]
  [2024.02]

- **ISCUTE:** Shir Kozlovsky, Omkar Joglekar, Dotan Di Castro.<br />
  "ISCUTE: Instance Segmentation of Cables Using Text Embedding." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.11996)] 
  [2024.02]

- **MATT:** James E. Gallagher, Aryav Gogia, Edward J. Oughton.<br />
  "A Multispectral Automated Transfer Technique (MATT) for machine-driven image labeling utilizing the Segment Anything Model (SAM)." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.11413)] 
  [2024.02]

- **DPSM:** Xin Zhang, Keren Fu, Qijun Zhao.<br />
  "Dynamic Patch-aware Enrichment Transformer for Occluded Person Re-Identification." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.10435)] 
  [2024.02]

- **LaserSAM:** Alexander Krawciw, Sven Lilge, Timothy D. Barfoot.<br />
  "LaserSAM: Zero-Shot Change Detection Using Visual Segmentation of Spinning LiDAR." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.10321)] 
  [2024.02]

- **Zero SAM:** Tal Shaharabany, Lior Wolf.<br />
  "Zero Shot Medical Image Segmentation Based on Sparse Prompt Using Finetuned SAM." ArXiv (2024).
  [[paper](https://openreview.net/forum?id=TEYGCx02p3)] 
  [2024.02]

- Aviad Dahan, Tal Shaharabany, Raja Giryes, Lior Wolf.<br />
  "Video Polyp Segmentation using Implicit Networks." ArXiv (2024).
  [[paper](https://openreview.net/forum?id=7gFODPjwOe)] 
  [2024.02]

- Gurunath Reddy, Dattesh D. Shanbhag, Deepa Anand, Uday Patil.<br />
  "Data Adaptive few-shot multi label segmentation with Foundation models." ArXiv (2024).
  [[paper](https://openreview.net/forum?id=EJL0MxcMo1)] 
  [2024.02]

- Jiesi Hu, Yang Shang, Yanwu Yang, Guo Xutao, Hanyang Peng, Ting Ma.<br />
  "Synergizing In-context Learning Model and SAM in Medical Image Segmentation." ArXiv (2024).
  [[paper](https://openreview.net/forum?id=Y1BeK8dTno)] 
  [2024.02]

- **UnCLe SAM:** Amin Ranem, Mohamed Afham Mohamed Aflal, Moritz Fuchs, Anirban Mukhopadhyay.<br />
  "UnCLe SAM: Unleashing SAM’s Potential for Continual Prostate MRI Segmentatio." ArXiv (2024).
  [[paper](https://openreview.net/forum?id=jRtUQ2VnNi)] 
  [2024.02]

- **Lester:** Ruben Tous.<br />
  "Lester: rotoscope animation through video object segmentation and tracking." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.09883)] 
  [2024.02]

- **Fine-Tune Distillation:** .<br />
  "Domain Adaptable Fine-Tune Distillation Framework For Advancing Farm Surveillance." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.07059)] 
  [[code](https://github.com/Razaimam45/Fine-Tune-Distillation)]
  [2024.02]

- **YOLO + SAM:** Henry Gann, Josiah Bull, Trevor Gee, Mahla Nejati.<br />
  "Improving Pallet Detection Using Synthetic Data." ACRA (2023).
  [[paper](https://arxiv.org/abs/2402.07098)] 
  [2024.02]

- **EfficientViT-SAM:** Zhuoyang Zhang, Han Cai, Song Han.<br />
  "EfficientViT-SAM: Accelerated Segment Anything Model Without Performance Loss." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.05008)] 
  [[code](https://github.com/mit-han-lab/efficientvit)]
  [2024.02]

- **ClickSAM:** Aimee Guo, Gace Fei, Hemanth Pasupuletic, Jing Wang.<br />
  "ClickSAM: Fine-tuning Segment Anything Model using click prompts for ultrasound image segmentation." SPIE Medical Imaging Conference (2024).
  [[paper](https://arxiv.org/abs/2402.05902)] 
  [2024.02]

- **Iris-SAM:** Parisa Farmanifard, Arun Ross.<br />
  "Iris-SAM: Iris Segmentation Using a Foundational Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.06497)] 
  [2024.02]

- **CAT-SAM:** Aoran Xiao, Weihao Xuan, Heli Qi, Yun Xing, Ruijie Ren, Xiaoqin Zhang, Shijian Lu.<br />
  "CAT-SAM: Conditional Tuning Network for Few-Shot Adaptation of Segmentation Anything Model." ECCV (2024).
  [[paper](https://arxiv.org/abs/2402.03631)] 
  [[code](https://xiaoaoran.github.io/projects/CAT-SAM)]
  [2024.02]

- **COMRP:** Zihan Ma, Yongshang Li, Ronggui Ma, Chen Liang.<br />
  "Unsupervised semantic segmentation of high-resolution UAV imagery for road scene parsing." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.02985)] 
  [2024.02]

- **SAM+SLIC:** Michal Shlapentokh-Rothman, Ansel Blume, Yao Xiao, Yuqun Wu, Sethuraman T V, Heyi Tao, Jae Yong Lee, Wilfredo Torres, Yu-Xiong Wang, Derek Hoiem.<br />
  "Region-Based Representations Revisited." CVPR (2024).
  [[paper](https://arxiv.org/abs/2402.02352)]
  [[website](https://regionreps.web.illinois.edu/)]
  [[code](https://github.com/michalsr/regions)]
  [2024.02]

- **Polyp-DAM:** Zhuoran Zheng, Chen Wu, Wei Wang, Yeying Jin, Xiuyi Jia.<br />
  "Polyp-DAM: Polyp segmentation via depth anything model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.02298)] 
  [[code](https://github.com/zzr-idam/Polyp-DAM)]
  [2024.02]

- **AnyChange:** Zhuo Zheng, Yanfei Zhong, Liangpei Zhang, Stefano Ermon.<br />
  "Segment Any Change." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2402.01188)] 
  [2024.02]

- Sureka Thiruchittampalam, Bikram P. Banerjee, Nancy F. Glenn, Simit Raval.<br />
  "Comparative Evaluation of Traditional and Deep Learning-Based Segmentation Methods for Spoil Pile Delineation Using UAV Images." ArXiv (2024).
  [[paper](https://browse.arxiv.org/abs/2402.00295)] 
  [2024.02]

 - **Hi-SAM:** Maoyuan Ye, Jing Zhang, Juhua Liu, Chenyu Liu, Baocai Yin, Cong Liu, Bo Du, Dacheng Tao.<br />
  "Hi-SAM: Marrying Segment Anything Model for Hierarchical Text Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.17904)] 
  [[code](https://github.com/ymy-k/Hi-SAM)]
  [2024.01]

- **Conv-LoRA:** Zihan Zhong, Zhiqiang Tang, Tong He, Haoyang Fang, Chun Yuan.<br />
  "Convolution Meets LoRA: Parameter Efficient Finetuning for Segment Anything Model." ICLR  (2024).
  [[paper](https://arxiv.org/abs/2401.17868)] 
  [2024.01]

- Kangcheng Liu, Xinhu Zheng, Chaoqun Wang, Hesheng Wang, Ming Liu, Kai Tang.<br />
  "Online Robot Navigation and and Manipulation with Distilled Vision-Language Models." ICRA  (2024).
  [[paper](https://arxiv.org/abs/2401.17083)] 
  [2024.01]

- **MouSi:** Xiaoran Fan, Tao Ji, Changhao Jiang, Shuo Li, Senjie Jin, Sirui Song, Junke Wang, Boyang Hong, Lu Chen, Guodong Zheng, Ming Zhang, Caishuang Huang, Rui Zheng, Zhiheng Xi, Yuhao Zhou, Shihan Dou, Junjie Ye, Hang Yan, Tao Gui, Qi Zhang, Xipeng Qiu, Xuanjing Huang, Zuxuan Wu, Yu-Gang Jiang.<br />
  "MouSi: Poly-Visual-Expert Vision-Language Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.17221)] 
  [[code](https://github.com/FudanNLPLAB/MouSi)]
  [2024.01]


- **SA-GS:** Xu Hu, Yuxi Wang, Lue Fan, Junsong Fan, Junran Peng, Zhen Lei, Qing Li, Zhaoxiang Zhang.<br />
  "Semantic Anything in 3D Gaussians." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.17857)] 
  [2024.01]

- **SimAda:** Yiran Song, Qianyu Zhou, Xuequan Lu, Zhiwen Shao, Lizhuang Ma.<br />
  "SimAda: A Simple Unified Framework for Adapting Segment Anything Model in Underperformed Scenes." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.17803)] 
  [[code](https://github.com/zongzi13545329/SimAda)]
  [2024.01]

- **MESA:** Yesheng Zhang, Xu Zhao.<br />
  "MESA: Matching Everything by Segmenting Anything." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.16741)] 
  [2024.01]

- **MixSup:** Yuxue Yang, Lue Fan, Zhaoxiang Zhang.<br />
  "MixSup: Mixed-grained Supervision for Label-efficient LiDAR-based 3D Object Detection." ICLR (2024).
  [[paper](https://arxiv.org/abs/2401.16305)] 
  [[code](https://github.com/BraveGroup/PointSAM-for-MixSup)]
  [2024.01]

- **GEM:** Jing Hao, Moyun Liu, Kuo Feng Hung.<br />
  "GEM: Boost Simple Network for Glass Surface Segmentation via Segment Anything Model and Data Synthesis." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.15282)] 
  [[code](https://github.com/isbrycee/GEM-Glass-Segmentor)]
  [2024.01]

- **LoRA-SAM:** Zehao Ye, Lucy Lovell, Asaad Faramarzi, Jelena Ninic.<br />
  "SAM-based instance segmentation models for the automation of masonry crack detection." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.15266)] 
  [2024.01]

- **SSR:** Yanqi Ge, Ye Huang, Wen Li, Lixin Duan.<br />
  "SSR: SAM is a Strong Regularizer for domain adaptive semantic segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.14686)] 
  [2024.01]

- **ScaleFlow:** Chengbo Yuan, Chuan Wen, Tong Zhang, Yang Gao.<br />
  "General Flow as Foundation Affordance for Scalable Robot Learning." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.11439)] 
  [[code](https://general-flow.github.io/)]
  [2024.01]

- **HAZARD:** Qinhong Zhou, Sunli Chen, Yisong Wang, Haozhe Xu, Weihua Du, Hongxin Zhang, Yilun Du, Joshua B. Tenenbaum, Chuang Gan.<br />
  "HAZARD Challenge: Embodied Decision Making in Dynamically Changing Environments." ICLR (2024).
  [[paper](https://arxiv.org/abs/2401.12975)] 
  [[code](https://vis-www.cs.umass.edu/hazard/)]
  [2024.01]

- Laura J. Brooks , Daniel Pearce, Kenton Kwok , Nikhil Jawade , Man Qi, Erola Fenollosa , Deniz Beker, James Whicker, Katrina Davis, Roberto Salguero-G´omez, Robin Wang, and Steve Chappell.<br />
  "A video-rate hyperspectral camera for monitoring plant health and biodiversity." ArXiv (2024).
  [[paper](https://www.biorxiv.org/content/10.1101/2024.01.18.576183v1.abstract)] 
  [2024.01]

- **SAM-OBC:** Hu, Yixin and Qi, Zhixin and Zhou, Zhexun and Qin, Yan.<br />
  "Detection of Benggang in Remote Sensing Imagery through Integration of Segmentation Anything Model with Object-Based Classification." ArXiv (2024).
  [[paper](https://www.mdpi.com/2072-4292/16/2/428)] 
  [2024.01]

- **OK-Robot:** Peiqi Liu,Yaswanth Orru, Chris Paxton, Nur Muhammad Mahi Shafiullah, Lerrel Pinto.<br />
  "OK-Robot: What Really Matters in Integrating Open-Knowledge Models for Robotics." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.12202)] 
  [[code](https://ok-robot.github.io/)]
  [2024.01]

- Bowei Xue, Han Cheng, Qingqing Yang, Yi Wang, and Xiaoning He.<br />
  "Adapting Segment Anything Model to Aerial Land Cover Classification with Low Rank Adaptation." IEEE LGRS (2024).
  [[paper](https://ieeexplore.ieee.org/document/10412208)] 
  [2024.01]

- Peng Qian,Tomer Ullman.<br />
  "Shape Guides Visual Pretense." ArXiv (2024).
[[paper](https://files.osf.io/v1/resources/zv8nb/providers/osfstorage/65af0bbb97381903dd396c22?action=download&direct&version=1)] 
  [2024.01]

- **MultiDance-Zero:** Zhe Xu, Kun Wei, Xu Yang, Cheng Deng.<br />
  "Do You Guys Want to Dance: Zero-Shot Compositional Human Dance Generation with Multiple Persons." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.13363)] 
  [2024.01]

- **Vary-toy:** Haoran Wei, Lingyu Kong, Jinyue Chen, Liang Zhao, Zheng Ge, En Yu, Jianjian Sun, Chunrui Han, Xiangyu Zhang.<br />
  "Small Language Model Meets with Reinforced Vision Vocabulary." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.12503)] 
  [[code](https://varytoy.github.io/)]
  [2024.01]

- **WildRGB-D:** Hongchi Xia, Yang Fu, Sifei Liu, Xiaolong Wang.<br />
  "RGBD Objects in the Wild: Scaling Real-World 3D Object Learning from RGB-D Videos." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.12592)] 
  [[code](https://wildrgbd.github.io/)]
  [2024.01]

- **Tyche:** Marianne Rakic, Hallee E. Wong, Jose Javier Gonzalez Ortiz, Beth Cimini, John Guttag, Adrian V. Dalca.<br />
  "Tyche: Stochastic In-Context Learning for Medical Image Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.13650)] 
  [[code](https://github.com/mariannerakic/tyche/)]
  [2024.01]

- **Grounded SAM:** Tianhe Ren, Shilong Liu, Ailing Zeng, Jing Lin, Kunchang Li, He Cao, Jiayu Chen, Xinyu Huang, Yukang Chen, Feng Yan, Zhaoyang Zeng, Hao Zhang, Feng Li, Jie Yang, Hongyang Li, Qing Jiang, Lei Zhang.<br />
  "Grounded SAM: Assembling Open-World Models for Diverse Visual Tasks." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.14159)] 
  [[code](https://github.com/IDEA-Research/Grounded-Segment-Anything)]
  [2024.01]

- **TriSAM:** Jia Wan, Wanhua Li, Atmadeep Banerjee, Jason Ken Adhinarta, Evelina Sjostedt, Jingpeng Wu, Jeff Lichtman, Hanspeter Pfister, Donglai Wei.<br />
  "TriSAM: Tri-Plane SAM for zero-shot cortical blood vessel segmentation in VEM images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.13961)] 
  [2024.01]

- Kesi Xu, Lea Goetz, Nasir Rajpoot.<br />
  "On generalisability of segment anything model for nuclear instance segmentation in histology images." MIUA (2023).
  [[paper](https://arxiv.org/abs/2401.14248)] 
  [2024.01]

- **PA-SAM:** Zhaozhi Xie, Bochen Guan, Weihao Jiang, Muyang Yi, Yue Ding, Hongtao Lu, Lei Zhang.<br />
  "PA-SAM: Prompt Adapter SAM for High-Quality Image Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.13051)] 
  [[code](https://github.com/xzz2/pa-sam)]
  [2024.01]

- **SAC:** Saiyang Na, Yuzhi Guo, Feng Jiang, Hehuan Ma, Junzhou Huang.<br />
  "Segment Any Cell: A SAM-based Auto-prompting Fine-tuning Framework for Nuclei Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.13220)] 
  [2024.01]

- **ClipSAM:** Shengze Li, Jianjian Cao, Peng Ye, Yuhan Ding, Chongjun Tu, Tao Chen.<br />
  "ClipSAM: CLIP and SAM Collaboration for Zero-Shot Anomaly Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.12665)] 
  [[code](https://github.com/Lszcoding/ClipSAM)]
  [2024.01]

- **SegmentAnyBone:** Hanxue Gu, Roy Colglazier, Haoyu Dong, Jikai Zhang, Yaqian Chen, Zafer Yildiz, Yuwen Chen, Lin Li, Jichen Yang, Jay Willhite, Alex M. Meyer, Brian Guo, Yashvi Atul Shah, Emily Luo, Shipra Rajput, Sally Kuehn, Clark Bulleit, Kevin A. Wu, Jisoo Lee, Brandon Ramirez, Darui Lu, Jay M. Levin, Maciej A. Mazurowski.<br />
  "SegmentAnyBone: A Universal Model that Segments Any Bone at Any Location on MRI." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.12974)] 
  [[code](https://github.com/mazurowski-lab/SegmentAnyBone)]
  [2024.01]

- Reda Bensaid, Vincent Gripon, François Leduc-Primeau, Lukas Mauch, Ghouthi Boukli Hacene, Fabien Cardinaux.<br />
  "A Novel Benchmark for Few-Shot Semantic Segmentation in the Era of Foundation Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.11311)] 
  [2024.01]

- **Tunnel SAM Adapter:** Chen, Junxin and Yu, Xiaojie and Liu, Shichang and Chen, Tao and Wang, Wei and Jeon, Gwanggil and He, Ben-Guo.<br />
  "Tunnel SAM Adapter: Adapting Segment Anything Model for Tunnel Water Leakage Inspection." Geohazard Mechanics (2024).
  [[paper](https://www.sciencedirect.com/science/article/pii/S2949741824000013)] 
  [2024.01]

- **GEMO:** Yinuo Zhao, Kun Wu, Tianjiao Yi, Zhiyuan Xu, Xiaozhu Ju, Zhengping Che, Qinru Qiu, Chi Harold Liu, Jian Tang.<br />
  "An Efficient Generalizable Framework for Visuomotor Policies via Control-aware Augmentation and Privilege-guided Distillation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.09258)] 
  [2024.01]

- Zhan, Youyi and Wang, Tuanfeng Y. and Shao, Tianjia and Zhou, Kun.<br />
  "Pattern Guided UV Recovery for Realistic Video Garment Texturing." ArXiv (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10400917?casa_token=9UPxBTineFYAAAAA:WM3NcynIUd8rFkPE8GUzl5uh5ryqCkHgBsOR8wG3iPrClzFJ1E8hlPir_G0IQkw_I8A8BPq4Lo6X)] 
  [2024.01]

- **Efficient4D:** Zijie Pan, Zeyu Yang, Xiatian Zhu, Li Zhang.<br />
  "Fast Dynamic 3D Object Generation from a Single-view Video." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.08742)] 
  [[code](https://fudan-zvg.github.io/Efficient4D)]
  [2024.01]

- Hangbin Zheng, Shimin Liu, Hengjun Zhang, Jiayi Yu and Jinsong Bao.<br />
  "Visual-triggered contextual guidance for lithium battery disassembly: a multi-modal event knowledge graph approach." ArXiv (2024).
  [[paper](https://www.tandfonline.com/doi/pdf/10.1080/09544828.2024.2301876?casa_token=7COSjhYxn_8AAAAA:VPlW-3ISu60vumHZ-FaQsA5ToOmw-FPtL2nrBYZLhq0kdvPjeSNFnxIOYpgRcMBUEY7SMIxuIwQ1eIAu)] 
  [2024.01]

- Chenghao Lu , Emmanuel Nnadozie, Moritz Paul Camenzind, Yuncai Hu and Kang Yu.<br />
  "Maize plant detection using UAV-based RGB imaging and YOLOv5." Frontiers in Plant Science (2024).
  [[paper](https://www.researchgate.net/profile/Chenghao-Lu-9/publication/377400920_Maize_plant_detection_using_UAV-based_RGB_imaging_and_YOLOv5/links/65a4ec0abc30165e6e3937ff/Maize-plant-detection-using-UAV-based-RGB-imaging-and-YOLOv5.pdf)] 
  [2024.01]

- **OMG-Seg:** Xiangtai Li, Haobo Yuan, Wei Li, Henghui Ding, Size Wu, Wenwei Zhang, Yining Li, Kai Chen, Chen Change Loy.<br />
  "OMG-Seg: Is One Model Good Enough For All Segmentation?." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.10229)] 
  [[code](https://github.com/lxtGH/OMG-Seg)]
  [2024.01]

- **RAP-SAM:** Shilin Xu, Haobo Yuan, Qingyu Shi, Lu Qi, Jingbo Wang, Yibo Yang, Yining Li, Kai Chen, Yunhai Tong, Bernard Ghanem, Xiangtai Li, Ming-Hsuan Yang.<br />
  "RAP-SAM: Towards Real-Time All-Purpose Segment Anything." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.10228)] 
  [[code](https://xushilin1.github.io/rap_sam/)]
  [2024.01]

- **PRS:** Chen-Bin Feng, Qi Lai, Kangdao Liu, Houcheng Su, Chi-Man Vong.<br />
  "Boosting Few-Shot Semantic Segmentation Via Segment Anything Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.09826)] 
  [2024.01]

- Wenwen Li, Chia-Yu Hsu, Sizhe Wang, Yezhou Yang, Hyunho Lee, Anna Liljedahl, Chandi Witharana, Yili Yang, Brendan M. Rogers, Samantha T. Arundel, Matthew B. Jones, Kenton McHenry, Patricia Solis.<br />
  "Segment Anything Model Can Not Segment Anything: Assessing AI Foundation Model's Generalizability in Permafrost Mapping." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.08787)] 
  [2024.01]

- **SAM-MCD:** Hongruixuan Chen, Jian Song, Naoto Yokoya.<br />
  "Change Detection Between Optical Remote Sensing Imagery and Map Data via Segment Anything Model (SAM)." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.09019)] 
  [2024.01]

- **GARField:** Chung Min Kim, Mingxuan Wu, Justin Kerr, Ken Goldberg, Matthew Tancik, Angjoo Kanazawa.<br />
  "GARField: Group Anything with Radiance Fields." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.09419)] 
  [[code](https://www.garfield.studio/)]
  [2024.01]

- **CPAB:** Hexiang Wang, Fengqi Liu, Qianyu Zhou, Ran Yi, Xin Tan, Lizhuang Ma.<br />
  "Continuous Piecewise-Affine Based Motion Model for Image Animation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.09146)] 
  [[code](https://github.com/DevilPG/AAAI2024-CPABMM)]
  [2024.01]

- **SAM4UDASS:** Weihao Yan, Yeqiang Qian, Xingyuan Chen, Hanyang Zhuang, Chunxiang Wang, Ming Yang.<br />
  "SAM4UDASS: When SAM Meets Unsupervised Domain Adaptive Semantic Segmentation in Intelligent Vehicles." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.08604)] 
  [[code](https://github.com/ywher/SAM4UDASS)]
  [2024.01]

- **Forge_VFM4AD:** Xu Yan, Haiming Zhang, Yingjie Cai, Jingming Guo, Weichao Qiu, Bin Gao, Kaiqiang Zhou, Yue Zhao, Huan Jin, Jiantao Gao, Zhen Li, Lihui Jiang, Wei Zhang, Hongbo Zhang, Dengxin Dai, Bingbing Liu.<br />
  "Forging Vision Foundation Models for Autonomous Driving: Challenges, Methodologies, and Opportunities." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.08045)] 
  [[code](https://github.com/zhanghm1995/Forge_VFM4AD)]
  [2024.01]

- Ho Hin Lee, Yu Gu, Theodore Zhao, Yanbo Xu, Jianwei Yang, Naoto Usuyama, Cliff Wong, Mu Wei, Bennett A. Landman, Yuankai Huo, Alberto Santamaria-Pang, Hoifung Poon.<br />
  "Foundation Models for Biomedical Image Segmentation: A Survey." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.07654)] 
  [2024.01]

- **SAM-OIL:** Wenhui Wu, Man Sing Wong, Xinyu Yu, Guoqiang Shi, Coco Yin Tung Kwok, Kang Zou.<br />
  "Compositional Oil Spill Detection Based on Object Detector and Adapted Segment Anything Model from SAR Images." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.07502)] 
  [2024.01]

- **UV-SAM:** Xin Zhang, Yu Liu, Yuming Lin, Qingming Liao, Yong Li.<br />
  "UV-SAM: Adapting Segment Anything Model for Urban Village Identification." AAAI (2024).
  [[paper](https://arxiv.org/abs/2401.08083)] 
  [[code](https://github.com/tsinghua-fib-lab/UV-SAM)]
  [2024.01]

- **“AttEN”:** Ching-Hao Chiu, Yu-Jen Chen, Yawen Wu, Yiyu Shi, Tsung-Yi Ho.<br />
  "Achieve Fairness without Demographics for Dermatological Disease Diagnosis." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.08066)] 
  [2024.01]

- **LandmarkBreaker:** Yuezun Li and Pu Sun and Honggang Qi and Siwei Lyu.<br />
  "LandmarkBreaker: A proactive method to obstruct DeepFakes via disrupting facial landmark extraction." CVIU (2024).
  [[paper](https://www.sciencedirect.com/science/article/pii/S107731422400016X)] 
  [2024.01]

- **GSC:** Luis Bolanos, Shih-Yang Su, Helge Rhodin.<br />
  "Gaussian Shadow Casting for Neural Characters." ArXiv (2024).  
   [[paper](https://arxiv.org/abs/2401.06116)] 
  [2024.01]

- Liu, Yue, Tao Sun, Kaixing Wu, Hongwei Zhang, Jingwei Zhang, Xinwen Jiang, Quanwei Lin, and Mei Feng..<br />
  "Fractal-Based Pattern Quantification of Mineral Grains: A Case Study of Yichun Rare-Metal Granite." Fractal and Fractional (2024).
  [[paper](https://www.mdpi.com/2504-3110/8/1/49)] 
  [2024.01]

- **SD-MVS:** Zhenlong Yuan, Jiakai Cao, Zhaoxin Li, Hao Jiang, Zhaoqi Wang.<br />
  "SD-MVS: Segmentation-Driven Deformation Multi-View Stereo with Spherical Refinement and EM optimization." AAAI (2024).
  [[paper](https://arxiv.org/abs/2401.06385)] 
  [2024.01]
  
- **SamLP:** Haoxuan Ding, Junyu Gao, Yuan Yuan, Qi Wang.<br />
  "SamLP: A Customized Segment Anything Model for License Plate Detection." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.06374)] 
  [[code](https://github.com/Dinghaoxuan/SamLP)]
  [2024.01]

- **RePLan:** Marta Skreta, Zihan Zhou, Jia Lin Yuan, Kourosh Darvish, Alán Aspuru-Guzik, Animesh Garg.<br />
  "RePLan: Robotic Replanning with Perception and Language Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.04157)] 
  [[code](https://replan-lm.github.io/replan.github.io/)]
  [2024.01]

- **SOS-SLAM:** Jouko Kinnari, Annika Thomas, Parker Lusk, Kota Kondo, Jonathan P. How.<br />
  "SOS-SLAM: Segmentation for Open-Set SLAM in Unstructured Environments." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.04791)] 
  [[code](https://acl.mit.edu/SOS-SLAM/)]
  [2024.01]

- **LRV:** Yunhua Zhang, Hazel Doughty, Cees G.M. Snoek.<br />
  "Low-Resource Vision Challenges for Foundation Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.04716)] 
  [[code](https://xiaobai1217.github.io/Low-Resource-Vision/)]
  [2024.01]

- **PartSTAD:** Hyunjin Kim, Minhyuk Sung.<br />
  "PartSTAD: 2D-to-3D Part Segmentation Task Adaptation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.05906)] 
  [2024.01]

- **MatSAM:** Changtai Li, Xu Han, Chao Yao, Xiaojuan Ban.<br />
  "MatSAM: Efficient Materials Microstructure Extraction via Visual Large Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.05638)] 
  [2024.01]

- Galib Muhammad Shahriar Himel, Md. Masudul Islam, Kh Abdullah Al-Aff, Shams Ibne Karim, Md. Kabir Uddin Sikder.<br />
  "Skin Cancer Segmentation and Classification Using Vision Transformer for Automatic Analysis in Dermatoscopy-based Non-invasive Digital System." IJBI (2024).
  [[paper](https://arxiv.org/abs/2401.04746)] 
  [2024.01]

- **SSPrompt:** Learning to Prompt Segment Anything Models.<br />
  "Learning to Prompt Segment Anything Models." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.04651)] 
  [2024.01]

- **SBSM:** Zizhang Li, Dor Litvak, Ruining Li, Yunzhi Zhang, Tomas Jakab, Christian Rupprecht, Shangzhe Wu, Andrea Vedaldi, Jiajun Wu.<br />
  "Learning the 3D Fauna of the Web." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2401.02400)] 
  [[code](https://kyleleey.github.io/3DFauna/)]
  [2024.01]

- **DeepBID:** Binglin Shen, Chenggui Luo, Wen Pang, Yajing Jiang, Wenbo Wu, Rui Hu, Junle Qu, Bobo Gu, Liwei Liu.<br />
  "Surmounting photon limits and motion artifacts for biological dynamics imaging via dual-perspective self-supervised learning." PhotoniX (2024).
  [[paper](https://link.springer.com/article/10.1186/s43074-023-00117-0)] 
  [2024.01]

- **DSALVANet:** Jinghui He, Bo Liu, Fan Cao, Jian Xu, Yanshan Xiao.<br />
  "Few-Shot Object Counting with Dynamic Similarity-Aware in Latent Space." TGRS (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10381743)] 
  [[code](https://github.com/kadvinj/DSALVANet)]
  [2024.01]

- Fengtian Lu, Yuzhi Li, Feng Tian.<br />
  "Exploring challenge and explainable shot type classification using SAM-guided approaches." SIVP (2024).
  [[paper](https://link.springer.com/article/10.1007/s11760-023-02928-x)] 
  [2024.01]

- **RoboFusion:** Ziying Song, Guoxing Zhang, Lin Liu, Lei Yang, Shaoqing Xu, Caiyan Jia, Feiyang Jia, Li Wang.<br />
  "RoboFusion: Towards Robust Multi-Modal 3D obiect Detection via SAM." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.03907)] 
  [2024.01]

- **SAM4MIS:** Yichi Zhang, Zhenrong Shen, Rushi Jiao.<br />
  "Segment Anything Model for Medical Image Segmentation: Current Applications and Future Directions." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.03495)] 
  [[code](https://github.com/YichiZhang98/SAM4MIS)]
  [2024.01]

- **OV-SAM:** Haobo Yuan, Xiangtai Li, Chong Zhou, Yining Li, Kai Chen, Chen Change Loy.<br />
  "Open-Vocabulary SAM: Segment and Recognize Twenty-thousand Classes Interactively." ECCV (2024).
  [[paper](https://arxiv.org/abs/2401.02955)] 
  [[project page](https://www.mmlab-ntu.com/project/ovsam)]
  [[code](https://github.com/HarborYuan/ovsam)]
  [2024.01]

- **DSR :** Yanni Wang, Hecheng Jia, Shilei Fu, Huiping Lin, Feng Xu.<br />
  "Reinforcement Learning for SAR View Angle Inversion with Differentiable SAR Renderer." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.01165)] 
  [2024.01]

- Thomas Lips, Victor-Louis De Gusseme, Francis wyffels.<br />
  "Learning Keypoints for Robotic Cloth Manipulation using Synthetic Data." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.01734)] 
  [[code](https://github.com/tlpss/synthetic-cloth-data)]
  [2024.01]

- **SwinSAM:** Zhoushan Feng, Yuliang Zhanga, Yanhong Chenc, Yu Liua, Wen Sunc , Lili Dua, Dunjin Chen.<br />
  "SwinSAM: Fine-Grained Polyp Segmentation in Colonoscopy Images via Segment Anything Model Integrated with a Swin Transformer Decoder." ArXiv (2024).
  [[paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4673046)] 
  [2024.01]

- **BA-SAM:** Yiran Song, Qianyu Zhou, Xiangtai Li, Deng-Ping Fan, Xuequan Lu, Lizhuang Ma.<br />
  "BA-SAM: Scalable Bias-Mode Attention Mask for Segment Anything Model." CVPR (2024).
  [[paper](https://arxiv.org/abs/2401.02317)] 
  [2024.01]

- **SAMMed:** Hanhui Wang, Huaize Ye, Yi Xia, Xueyan Zhang.<br />
  "Leveraging SAM for Single-Source Domain Generalization in Medical Image Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.02076)] 
  [[code](https://github.com/SARIHUST/SAMMed)]
  [2024.01]

- **CWSAM:** Xinyang Pu, Hecheng Jia, Linghao Zheng, Feng Wang, Feng Xu.<br />
  "ClassWise-SAM-Adapter: Parameter Efficient Fine-tuning Adapts Segment Anything to SAR Domain for Semantic Segmentation." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.02326)] 
  [[code](https://github.com/xypu98/CWSAM)]
  [2024.01]

- **UCAD:** Jiaqi Liu, Kai Wu, Qiang Nie, Ying Chen, Bin-Bin Gao, Yong Liu, Jinbao Wang, Chengjie Wang, Feng Zheng.<br />
  "Unsupervised Continual Anomaly Detection with Contrastively-learned Prompt." AAAI (2024).
  [[paper](https://arxiv.org/abs/2401.01010)] 
  [[code](https://github.com/shirowalker/UCAD)]
  [2024.01]

- **TrackGPT:** Jiawen Zhu, Zhi-Qi Cheng, Jun-Yan He, Chenyang Li, Bin Luo, Huchuan Lu, Yifeng Geng, Xuansong Xie.<br />
  "Tracking with Human-Intent Reasoning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.17448)] 
  [[code](https://github.com/jiawen-zhu/TrackGPT)]
   [2023.12]


- **Wild2Avatar:** Tiange Xiang, Adam Sun, Scott Delp, Kazuki Kozuka, Li Fei-Fei, Ehsan Adeli.<br />
  "Wild2Avatar: Rendering Humans Behind Occlusions." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2401.00431)] 
  [[code](https://cs.stanford.edu/~xtiange/projects/wild2avatar/)]
   [2023.12]

- **IS5Net:** Xianjie Liu, Keren Fu, Qijun Zhao.<br />
  "Promoting Segment Anything Model towards Highly Accurate Dichotomous Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2401.00248)] 
  [2023.12]

- **DN-SLAM:** Chenyu Ruan; Qiuyu Zang; Kehua Zhang; Kai Huang.<br />
  "DN-SLAM: A Visual SLAM with ORB Features and NeRF Mapping in Dynamic Environments." IEEE Sensors Journal (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10376402/authors#authors)] 
  [2023.12]

- **ZONE:** Shanglin Li, Bohan Zeng, Yutang Feng, Sicheng Gao, Xuhui Liu, Jiaming Liu, Li Lin, Xu Tang, Yao Hu, Jianzhuang Liu, Baochang Zhang.<br />
  "ZONE: Zero-Shot Instruction-Guided Local Editing." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.16794)] 
  [2023.12]

- **Segment3D:** Rui Huang, Songyou Peng, Ayca Takmaz, Federico Tombari, Marc Pollefeys, Shiji Song, Gao Huang, Francis Engelmann.<br />
  "Segment3D: Learning Fine-Grained Class-Agnostic 3D Segmentation without Manual Labels." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.17232)] 
  [[code](http://segment3d.github.io/)]
  [2023.12]

- **Unified-IO 2:** Jiasen Lu, Christopher Clark, Sangho Lee, Zichen Zhang, Savya Khosla, Ryan Marten, Derek Hoiem, Aniruddha Kembhavi.<br />
  "Unified-IO 2: Scaling Autoregressive Multimodal Models with Vision, Language, Audio, and Action." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.17172)] 
  [[code](https://unified-io-2.allenai.org/)]
  [2023.12]

- **EventSAM:** Zhiwen Chen, Zhiyu Zhu, Yifan Zhang, Junhui Hou, Guangming Shi, Jinjian Wu.<br />
  "Segment Any Events via Weighted Adaptation of Pivotal Tokens." CVPR (2024).
  [[paper](https://arxiv.org/abs/2312.16222)] 
  [[code](http://github.com/happychenpipi/EventSAM)]
  [2023.12]

- **SCM:** Xiaoliang Tan, Guanzhou Chen, Tong Wang, Jiaqi Wang, Xiaodong Zhang.<br />
  "Segment Change Model (SCM) for Unsupervised Change detection in VHR Remote Sensing Images: a Case Study of Buildings." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.16410)] 
  [[code](https://github.com/StephenApX/UCD-SCM)]
  [2023.12]

- **SAM-G:** Ziyu Wang, Yanjie Ze, Yifei Sun, Zhecheng Yuan, Huazhe Xu.<br />
  "Generalizable Visual Reinforcement Learning with Segment Anything Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.17116)] 
  [[code](https://yanjieze.com/SAM-G/)]
  [2023.12]

- **SAT-Nano:** Ziheng Zhao, Yao Zhang, Chaoyi Wu, Xiaoman Zhang, Ya Zhang, Yanfeng Wang, Weidi Xie.<br />
  "One Model to Rule them All: Towards Universal Segmentation for Medical Images with Text Prompts." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.17183)] 
  [[code](https://zhaoziheng.github.io/MedUniSeg)]
  [2023.12]

- **TTP:** Keyan Chen, Chengyang Liu, Wenyuan Li, Zili Liu, Hao Chen, Haotian Zhang, Zhengxia Zou, Zhenwei Shi.<br />
  "Time Travelling Pixels: Bitemporal Features Integration with Foundation Model for Remote Sensing Image Change Detection." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.16202)] 
  [[code](https://kychen.me/TTP)]
  [2023.12]

- **UniRef++:** Jiannan Wu, Yi Jiang, Bin Yan, Huchuan Lu, Zehuan Yuan, Ping Luo.<br />
  "UniRef++: Segment Every Reference Object in Spatial and Temporal Spaces." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.15715)] 
  [[code](https://github.com/FoundationVision/UniRef)]
  [2023.12]

- **LangSplat:** Minghan Qin, Wanhua Li, Jiawei Zhou, Haoqian Wang, Hanspeter Pfister.<br />
  "LangSplat: 3D Language Gaussian Splatting." CVPR (2024).
  [[paper](https://arxiv.org/abs/2312.16084)]
  [[project](https://langsplat.github.io/)]
  [[code]([https://langsplat.github.io/](https://github.com/minghanqin/LangSplat))]
  [2023.12]

- **HRFFM:** Yan Han, Xiaogang Xu, Yingqi Lin, Jiafei Wu, Zhe Liu.<br />
  "Video Frame Interpolation with Region-Distinguishable Priors from SAM." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.15868)] 
  [2023.12]

- **MSCL:** Ruoqing Zhao, Xi Wang, Hongliang Dai, Pan Gao, Piji Li.<br />
  "Medical Report Generation based on Segment-Enhanced Contrastive Representation Learning." NLPCC (2023).
  [[paper](https://arxiv.org/abs/2312.15869)] 
  [2023.12]

- **SAPNet:** Zhaoyang Wei, Pengfei Chen, Xuehui Yu, Guorong Li, Jianbin Jiao, Zhenjun Han.<br />
  "Semantic-aware SAM for Point-Prompted Instance Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.15895)] 
  [2023.12]

- Dingkun Guo.<br />
  "Learning Multi-Step Manipulation Tasks from A Single Human Demonstration." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.15346)] 
  [[code](https://robot-dishwashing.github.io/)]
  [2023.12]

- **ASSISTGUI:** Difei Gao, Lei Ji, Zechen Bai, Mingyu Ouyang, Peiran Li, Dongxing Mao, Qinchen Wu, Weichen Zhang, Peiyi Wang, Xiangwu Guo, Hengxu Wang, Luowei Zhou, Mike Zheng Shou.<br />
  "ASSISTGUI: Task-Oriented Desktop Graphical User Interface Automation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.13108)] 
  [2023.12]

- **VStar:** Penghao Wu, Saining Xie.<br />
  "V∗: Guided Visual Search as a Core Mechanism in Multimodal LLMs." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.14135)] 
  [[code](https://github.com/penghao-wu/vstar)]
  [2023.12]

- **FM-OV3D:** Dongmei Zhang, Chang Li, Ray Zhang, Shenghao Xie, Wei Xue, Xiaodong Xie, Shanghang Zhang.<br />
  "FM-OV3D: Foundation Model-based Cross-modal Knowledge Blending for Open-Vocabulary 3D Detection." AAAI (2024).
  [[paper](https://arxiv.org/abs/2312.14465)] 
  [[code](https://github.com/dmzhang0425/FM-OV3D.git)]
  [2023.12]

- **SP-SAM:** Wenxi Yue, Jing Zhang, Kun Hu, Qiuxia Wu, Zongyuan Ge, Yong Xia, Jiebo Luo, Zhiyong Wang.<br />
  "Part to Whole: Collaborative Prompting for Surgical Instrument Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.14481)] 
  [[code](https://github.com/wenxi-yue/SurgicalPart-SAM)]
  [2023.12]

- **Customize-It-3D:** Nan Huang, Ting Zhang, Yuhui Yuan, Dong Chen, Shanghang Zhang.<br />
  "Customize-It-3D: High-Quality 3D Creation from A Single Image Using Subject-Specific Knowledge Prior." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.11535)] 
  [[code](https://nnanhuang.github.io/projects/customize-it-3d/)]
  [2023.12]

- **Ins-HOI:** Jiajun Zhang, Yuxiang Zhang, Hongwen Zhang, Boyao Zhou, Ruizhi Shao, Zonghai Hu, Yebin Liu.<br />
  "Ins-HOI: Instance Aware Human-Object Interactions Recovery." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.09641)] 
  [[code](https://jiajunzhang16.github.io/ins-hoi)]
  [2023.12]

- **GPS:** Zhi Zhang, Qizhe Zhang, Zijun Gao, Renrui Zhang, Ekaterina Shutova, Shiji Zhou, Shanghang Zhang.<br />
  "Gradient-based Parameter Selection for Efficient Fine-Tuning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.10136)] 
  [2023.12]

- **PixelLLM:** Jiarui Xu, Xingyi Zhou, Shen Yan, Xiuye Gu, Anurag Arnab, Chen Sun, Xiaolong Wang, Cordelia Schmid.<br />
  "Pixel Aligned Language Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.09237)] 
  [[code](https://jerryxu.net/PixelLLM/)]
  [2023.12]

- **VectorTalker:** Hao Hu, Xuan Wang, Jingxiang Sun, Yanbo Fan, Yu Guo, Caigui Jiang.<br />
  "VectorTalker: SVG Talking Face Generation with Progressive Vectorisation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.11568)] 
  [2023.12]

- **Open3DIS:** Phuc D.A. Nguyen, Tuan Duc Ngo, Chuang Gan, Evangelos Kalogerakis, Anh Tran, Cuong Pham, Khoi Nguyen.<br />
  "Open3DIS: Open-vocabulary 3D Instance Segmentation with 2D Mask Guidance." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.10671)] 
  [[code](https://open3dis.github.io/)]
  [2023.12]

- **RadOcc:** Haiming Zhang, Xu Yan, Dongfeng Bai, Jiantao Gao, Pan Wang, Bingbing Liu, Shuguang Cui, Zhen Li.<br />
  "RadOcc: Learning Cross-Modality Occupancy Knowledge through Rendering Assisted Distillation." AAAI (2024).
  [[paper](https://arxiv.org/abs/2312.11829)] 
  [2023.12]

- **CreativeConnect:** DaEun Choi, Sumin Hong, Jeongeon Park, John Joon Young Chung, Juho Kim.<br />
  "CreativeConnect: Supporting Reference Recombination for Graphic Design Ideation with Generative AI." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.11949)] 
  [2023.12]

- Fei Pan, Sangryul Jeon, Brian Wang, Frank Mckenna, Stella X. Yu.<br />
  "Zero-Shot Building Attribute Extraction From Large-Scale Vision and Language Models." WACV (2024).
  [[paper](https://openaccess.thecvf.com/content/WACV2024/html/Pan_Zero-Shot_Building_Attribute_Extraction_From_Large-Scale_Vision_and_Language_Models_WACV_2024_paper.html)] 
  [2023.12]

- **MSFM:** Shijian Zheng and Rujing Wang and Shitao Zheng and Fenmei Wang and Liusan Wang and Zhigui Liu.<br />
  "A Multi-scale feature modulation network for efficient underwater image enhancement." JKSUCI (2023).
  [[paper](https://www.sciencedirect.com/science/article/pii/S1319157823004421)] 
  [[code](https://github.com/zhengshijian1993/MFMN)]
  [2023.12]

- Pranjay Shyam, HyunJin Yoo.<br />
  "Lightweight Thermal Super-Resolution and Object Detection for Robust Perception in Adverse Weather Conditions." WACV (2024).
  [[paper](https://openaccess.thecvf.com/content/WACV2024/html/Shyam_Lightweight_Thermal_Super-Resolution_and_Object_Detection_for_Robust_Perception_in_WACV_2024_paper.html)] 
  [2023.12]

- Weiyi Xie, Nathalie Willems, Shubham Patil, Yang Li, Mayank Kumar.<br />
  "SAM Fewshot Finetuning for Anatomical Segmentation in Medical Images." WACV (2024).
  [[paper](https://openaccess.thecvf.com/content/WACV2024/html/Xie_SAM_Fewshot_Finetuning_for_Anatomical_Segmentation_in_Medical_Images_WACV_2024_paper.html)] 
  [2023.12]

- **PMVC:** Chushan Zhang, Jinguang Tong, Tao Jun Lin, Chuong Nguyen, Hongdong Li.<br />
  "PMVC: Promoting Multi-View Consistency for 3D Scene Reconstruction." WACV (2024).
  [[paper](https://openaccess.thecvf.com/content/WACV2024/html/Zhang_PMVC_Promoting_Multi-View_Consistency_for_3D_Scene_Reconstruction_WACV_2024_paper.html)] 
  [2023.12]

- **BBPM:** Colbert, Zachery Morton and Arrington, Daniel and Foote, Matthew and Gårding, Jonas and Fay, Dominik and Huo, Michael and Pinkham, Mark and Ramachandran, Prabhakar.<br />
  "Repurposing Traditional U-Net Predictions for Sparse SAM Prompting in Medical Image Segmentation." BPEE (2023).
  [[paper](https://iopscience.iop.org/article/10.1088/2057-1976/ad17a7/meta)] 
  [2023.12]

- **Hi-Viscont:** Weiwei Gu, Anant Sah, Nakul Gopalan.<br />
  "Interactive Visual Task Learning for Robots."  AAAI (2024).
  [[paper](https://arxiv.org/abs/2312.13219)] 
  [2023.12]

- Sushil Sharma, Aryan Singh, Ganesh Sistu, Mark Halton, Ciarán Eising.<br />
  "Optimizing Ego Vehicle Trajectory Prediction: The Graph Enhancement Approach." EI-AVM (2024).
  [[paper](https://arxiv.org/abs/2312.13104)] 
  [2023.12]

- **Loitering:** Johnny Núñez, Zenjie Li, Sergio Escalera, Kamal Nasrollahi.<br />
  "Identifying Loitering Behavior with Trajectory Analysis." WACV Workshop (2024).
  [[paper](https://openaccess.thecvf.com/content/WACV2024W/RWS/html/Nunez_Identifying_Loitering_Behavior_With_Trajectory_Analysis_WACVW_2024_paper.html)] 
  [[code](https://github.com/johnnynunez/RS-WACV24_Loitering)]
  [2023.12]

- **Emu2:** Quan Sun, Yufeng Cui, Xiaosong Zhang, Fan Zhang, Qiying Yu, Zhengxiong Luo, Yueze Wang, Yongming Rao, Jingjing Liu, Tiejun Huang, Xinlong Wang.<br />
  "Generative Multimodal Models are In-Context Learners." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.13286)] 
  [[homepage](https://baaivision.github.io/emu2)]
  [[code](https://github.com/baaivision/Emu)] 
  [2023.12]

- Giorgos Savathrakis, Antonis Argyros.<br />
  "An Automated Method for the Creation of Oriented Bounding Boxes in Remote Sensing Ship Detection Datasets." WACV Workshop (2024).
  [[paper](https://openaccess.thecvf.com/content/WACV2024W/MaCVi/html/Savathrakis_An_Automated_Method_for_the_Creation_of_Oriented_Bounding_Boxes_WACVW_2024_paper.html)] 
  [2023.12]

- **TinySAM:** Han Shu, Wenshuo Li, Yehui Tang, Yiman Zhang, Yihao Chen, Houqiang Li, Yunhe Wang, Xinghao Chen.<br />
  "TinySAM: Pushing the Envelope for Efficient Segment Anything Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.13789)] 
  [[code](https://github.com/xinghaochen/TinySAM)]
  [[weights](https://gitee.com/mindspore/models/tree/master/research/cv/TinySAM)]
  [2023.12]

- **SRIN:** Haoxing Chen, Yaohui Li, Zhangxuan Gu, Zhuoer Xu, Jun Lan, Huaxiong Li.<br />
  "Segment Anything Model Meets Image Harmonization." ICASSP  (2024).
  [[paper](https://arxiv.org/abs/2312.12729)] 
  [2023.12]

- José Guilherme de Almeida, Nuno M. Rodrigues, Sara Silva, Nickolas Papanikolaou.<br />
  "Testing the Segment Anything Model on radiology data." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.12880)] 
  [2023.12]

- **WSOVOD:** Jianghang Lin, Yunhang Shen, Bingquan Wang, Shaohui Lin, Ke Li, Liujuan Cao.<br />
  "Weakly Supervised Open-Vocabulary Object Detection." AAAI (2024).
  [[paper](https://arxiv.org/abs/2312.12437)] 
  [[code](https://github.com/HunterJ-Lin/WSOVOD)]
  [2023.12]

- **SAI3D:** Yingda Yin, Yuzheng Liu, Yang Xiao, Daniel Cohen-Or, Jingwei Huang, Baoquan Chen.<br />
  "SAI3D: Segment Any Instance in 3D Scenes." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.11557)] 
  [[code](https://yd-yin.github.io/SAI3D)]
  [2023.12]

- **SAMBA:** Mohannad Barakat, Noha Magdy, Jjuuko George William, Ethel Phiri, Raymond Confidence, Dong Zhang, Udunna C Anazodo.<br />
  "Towards SAMBA: Segment Anything Model for Brain Tumor Segmentation in Sub-Sharan African Populations." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.11775)] 
  [2023.12]

- **EVI-SAM:** Weipeng Guan, Peiyu Chen, Huibin Zhao, Yu Wang, Peng Lu.<br />
  "EVI-SAM: Robust, Real-time, Tightly-coupled Event-Visual-Inertial State Estimation and 3D Dense Mapping." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.11911)] 
  [2023.12]

- **GSVA:** Zhuofan Xia, Dongchen Han, Yizeng Han, Xuran Pan, Shiji Song, Gao Huang.<br />
  "GSVA: Generalized Segmentation via Multimodal Large Language Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.10103)] 
  [[code](https://github.com/LeapLabTHU/GSVA)]
  [2023.12]

- **ABR:** Junyu Xie, Weidi Xie, Andrew Zisserman.<br />
  "Appearance-based Refinement for Object-Centric Motion Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.11463)] 
  [2023.12]

- Yixin Zhang, Shen Zhao, Hanxue Gu, Maciej A. Mazurowski.<br />
  "How to Efficiently Annotate Images for Best-Performing Deep Learning Based Segmentation Models: An Empirical Study with Weak and Noisy Annotations and Segment Anything Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.10600)] 
  [2023.12]

- Isabelle Tingzon, Nuala Margaret Cowan, Pierre Chrzanowski.<br />
  "Mapping Housing Stock Characteristics from Drone Images for Climate Resilience in the Caribbean." NeurIPS  Workshop (2023).
  [[paper](https://arxiv.org/abs/2312.10306)] 
  [2023.12]

- **TIFace:** Ruijie Zhu, Jiahao Chang, Ziyang Song, Jiahuan Yu, Tianzhu Zhang.<br />
  "TIFace: Improving Facial Reconstruction through Tensorial Radiance Fields and Implicit Surfaces." ICCV  Workshop (2023).
  [[paper](https://arxiv.org/abs/2312.09527)] 
  [[code](https://github.com/RuijieZhu94/TI-Face)]
  [2023.12]

- **Osprey:** Yuqian Yuan, Wentong Li, Jian Liu, Dongqi Tang, Xinjie Luo, Chi Qin, Lei Zhang, Jianke Zhu.<br />
  "Osprey: Pixel Understanding with Visual Instruction Tuning." CVPR (2024).
  [[paper](https://arxiv.org/abs/2312.10032)] 
  [[code](https://github.com/CircleRadon/Osprey)]
  [2023.12]

- **SQA-SAM:** Yizhe Zhang, Shuo Wang, Tao Zhou, Qi Dou, Danny Z. Chen.<br />
  "SQA-SAM: Segmentation Quality Assessment for Medical Images Utilizing the Segment Anything Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.09899)] 
  [[code](https://github.com/yizhezhang2000/SQA-SAM)]
  [2023.12]

- **CLOUDS:** Yasser Benigmim, Subhankar Roy, Slim Essid, Vicky Kalogeiton, Stéphane Lathuilière.<br />
  "Collaborating Foundation models for Domain Generalized Semantic Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.09788)] 
  [[code](https://github.com/yasserben/CLOUDS)]
  [2023.12]

- **MobileSAMv2:** Chaoning Zhang, Dongshen Han, Sheng Zheng, Jinwoo Choi, Tae-Ho Kim, Choong Seon Hong.<br />
  "MobileSAMv2: Faster Segment Anything to Everything." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.09579)] 
  [[code](https://github.com/ChaoningZhang/MobileSAM)]
  [2023.12]

- **Alpha-CLIP:** Zeyi Sun, Ye Fang, Tong Wu, Pan Zhang, Yuhang Zang, Shu Kong, Yuanjun Xiong, Dahua Lin, Jiaqi Wang.<br />
  "Alpha-CLIP: A CLIP Model Focusing on Wherever You Want." CVPR (2024).
  [[paper](https://arxiv.org/abs/2312.03818)] 
  [[homepage](https://aleafy.github.io/alpha-clip)]
  [[code](https://github.com/SunzeY/AlphaCLIP)]
  [2023.12]

- **WonderJourney:** Hong-Xing Yu, Haoyi Duan, Junhwa Hur, Kyle Sargent, Michael Rubinstein, William T. Freeman, Forrester Cole, Deqing Sun, Noah Snavely, Jiajun Wu, Charles Herrmann.<br />
  "WonderJourney: Going from Anywhere to Everywhere." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.03884)] 
  [[code](https://kovenyu.com/WonderJourney/)]
  [2023.12]

- **MobileSAM-Track:** Liu, Yehui, Yuliang Zhao, Xinyue Zhang, Xiaoai Wang, Chao Lian, Jian Li, Peng Shan, Changzeng Fu, Xiaoyong Lyu, Lianjiang Li, and et al.<br />
  "MobileSAM-Track: Lightweight One-Shot Tracking and Segmentation of Small Objects on Edge Devices." Remote Sensing (2023).
  [[paper](https://www.mdpi.com/2072-4292/15/24/5665)] 
  [2023.12]

- **IT3DEgo:** Yunhan Zhao, Haoyu Ma, Shu Kong, Charless Fowlkes.<br />
  "Instance Tracking in 3D Scenes from Egocentric Videos." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.04117)] 
  [[code](https://github.com/IT3DEgo/IT3DEgo/)]
  [2023.12]

- **Rein:** Zhixiang Wei, Lin Chen, Yi Jin, Xiaoxiao Ma, Tianle Liu, Pengyang Lin, Ben Wang, Huaian Chen, Jinjin Zheng.<br />
  "Stronger, Fewer, & Superior: Harnessing Vision Foundation Models for Domain Generalized Semantic Segmentation." CVPR (2024).
  [[paper](https://arxiv.org/abs/2312.04265)] 
  [[code](https://github.com/w1oves/Rein.git)]
  [2023.12]

- **MR.HARM:** Hongzhan Lin, Ziyang Luo, Jing Ma, Long Chen.<br />
  "Beneath the Surface: Unveiling Harmful Memes with Multimodal Reasoning Distilled from Large Language Models." EMNLP (2023).
  [[paper](https://arxiv.org/abs/2312.05434)] 
  [2023.12]

- **ControlRoom3D:** Jonas Schult, Sam Tsai, Lukas Höllein, Bichen Wu, Jialiang Wang, Chih-Yao Ma, Kunpeng Li, Xiaofang Wang, Felix Wimbauer, Zijian He, Peizhao Zhang, Bastian Leibe, Peter Vajda, Ji Hou.<br />
  "ControlRoom3D: Room Generation using Semantic Proxy Rooms." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.05208)] 
  [[code](https://jonasschult.github.io/ControlRoom3D/)]
  [2023.12]

- **SmartEdit:** Yuzhou Huang, Liangbin Xie, Xintao Wang, Ziyang Yuan, Xiaodong Cun, Yixiao Ge, Jiantao Zhou, Chao Dong, Rui Huang, Ruimao Zhang, Ying Shan.<br />
  "SmartEdit: Exploring Complex Instruction-based Image Editing with Multimodal Large Language Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.06739)] 
  [[code](https://github.com/TencentARC/SmartEdit)]
  [2023.12]

- **COMBO:** Qi Yang, Xing Nie, Tong Li, Pengfei Gao, Ying Guo, Cheng Zhen, Pengfei Yan, Shiming Xiang.<br />
  "Cooperation Does Matter: Exploring Multi-Order Bilateral Relations for Audio-Visual Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.06462)] 
  [[code](https://combo-avs.github.io/)]
  [2023.12]

- **Vary:** Haoran Wei, Lingyu Kong, Jinyue Chen, Liang Zhao, Zheng Ge, Jinrong Yang, Jianjian Sun, Chunrui Han, Xiangyu Zhang.<br />
  "Vary: Scaling up the Vision Vocabulary for Large Vision-Language Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.06109)] 
  [[code](https://varybase.github.io/)]
  [2023.12]

- **Annolid:** Chen Yang, Jeremy Forest, Matthew Einhorn, Thomas A. Cleland.<br />
  "Automated Behavioral Analysis Using Instance Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.07723)] 
  [[code](https://github.com/cplab/annolid)]
  [2023.12]

- **FIND:** Xueyan Zou, Linjie Li, Jianfeng Wang, Jianwei Yang, Mingyu Ding, Zhengyuan Yang, Feng Li, Hao Zhang, Shilong Liu, Arul Aravinthan, Yong Jae Lee, Lijuan Wang.<br />
  "Interfacing Foundation Models’ Embeddings." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.07532)] 
  [[code](https://github.com/UX-Decoder/FIND)]
  [2023.12]

- **ScribblePrompt:** Hallee E. Wong, Marianne Rakic, John Guttag, Adrian V. Dalca.<br />
  "ScribblePrompt: Fast and Flexible Interactive Segmentation for Any Medical Image." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.07381)] 
  [[code](https://scribbleprompt.csail.mit.edu/)]
  [2023.12]

- **MWSIS:** Guangfeng Jiang, Jun Liu, Yuzhi Wu, Wenlong Liao, Tao He, Pai Peng.<br />
  "MWSIS: Multimodal Weakly Supervised Instance Segmentation with 2D Box Annotations for Autonomous Driving." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.06988)] 
  [[code](https://github.com/jiangxb98/mwsis-plugin)]
  [2023.12]

- **Mask as Supervision:** Yuchen Yang, Yu Qiao, Xiao Sun.<br />
  "Mask as Supervision: Leveraging Unified Mask Information for Unsupervised 3D Pose Estimation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.07051)] 
  [[code](https://github.com/Charrrrrlie/Mask-as-Supervision)]
  [2023.12]

- **IPSL:** Yujun Chen, Xin Tan, Zhizhong Zhang, Yanyun Qu, Yuan Xie.<br />
  "Beyond the Label Itself: Latent Labels Enhance Semi-supervised Point Cloud Panoptic Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.08234)] 
  [2023.12]

- **SESAME:** Tsung-Han Wu, Giscard Biamby, David Chan, Lisa Dunlap, Ritwik Gupta, Xudong Wang, Joseph E. Gonzalez, Trevor Darrell.<br />
  "See, Say, and Segment: Teaching LMMs to Overcome False Premises." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.08366)] 
  [[code](https://see-say-segment.github.io/)]
  [2023.12]

- **RefCOCOm:** Wenxuan Wang, Tongtian Yue, Yisi Zhang, Longteng Guo, Xingjian He, Xinlong Wang, Jing Liu.<br />
  "Unveiling Parts Beyond Objects:Towards Finer-Granularity Referring Expression Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.08007)] 
  [[code](https://github.com/Rubics-Xuan/MRES)]
  [2023.12]

- **TAP:** Ting Pan, Lulu Tang, Xinlong Wang, Shiguang Shan.<br />
  "Tokenize Anything via Prompting." ECCV (2024).
  [[paper](https://arxiv.org/abs/2312.09128)] 
  [[code](https://github.com/baaivision/tokenize-anything)]
  [2023.12]

- Josh Stein, Maxime Di Folco, Julia A. Schnabel.<br />
  "Influence of Prompting Strategies on Segment Anything Model (SAM) for Short-axis Cardiac MRI segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.08932)] 
  [2023.12]

- **SAM-Graph:** Haoyu Guo, He Zhu, Sida Peng, Yuang Wang, Yujun Shen, Ruizhen Hu, Xiaowei Zhou.<br />
  "SAM-guided Graph Cut for 3D Instance Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.08372)] 
  [[code](https://zju3dv.github.io/sam_graph)]
  [2023.12]

- **ASLseg:** Shiyun Chen, Li Lin, Pujin Cheng, Xiaoying Tang.<br />
  "ASLseg: Adapting SAM in the Loop for Semi-supervised Liver Tumor Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.07969)] 
  [2023.12]

- **GenSAM:** Jian Hu, Jiayi Lin, Weitong Cai, Shaogang Gong.<br />
  "Relax Image-Specific Prompt Requirement in SAM: A Single Generic Prompt for Segmenting Camouflaged Objects." AAAI (2024).
  [[paper](https://arxiv.org/abs/2312.07374)] 
  [[code](https://lwpyh.github.io/GenSAM/)]
  [2023.12]

- **AM-RADIO:** Mike Ranzinger, Greg Heinrich, Jan Kautz, Pavlo Molchanov.<br />
  "AM-RADIO: Agglomerative Model – Reduce All Domains Into One." CVPR (2024).
  [[paper](https://arxiv.org/abs/2312.06709)] 
  [[code](https://github.com/NVlabs/RADIO)]
  [2023.12]

- **SqueezeSAM:** Balakrishnan Varadarajan, Bilge Soran, Forrest Iandola, Xiaoyu Xiang, Yunyang Xiong, Chenchen Zhu, Raghuraman Krishnamoorthi, Vikas Chandra.<br />
  "SqueezeSAM: User friendly mobile interactive segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.06736)] 
  [2023.12]

- **EdgeSAM:** Chong Zhou, Xiangtai Li, Chen Change Loy, Bo Dai.<br />
  "EdgeSAM: Prompt-In-the-Loop Distillation for On-Device Deployment of SAM." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.06660)] 
  [[code](https://github.com/chongzhou96/EdgeSAM)]
  [2023.12]

- **SeCo:** Dong Zhao, Ruizhi Yang, Shuang Wang, Qi Zang, Yang Hu, Licheng Jiao, Nicu Sebe, Zhun Zhong.<br />
  "Semantic Connectivity-Driven Pseudo-labeling for Cross-domain Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.06331)] 
  [[code](https://github.com/DZhaoXd/SeCo)]
  [2023.12]

- **SemiSAM:** Yichi Zhang, Yuan Cheng, Yuan Qi.<br />
  "SemiSAM: Exploring SAM for Enhancing Semi-Supervised Medical Image Segmentation with Extremely Limited Annotations." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.06316)] 
  [2023.12]

- **RepViT-SAM:** Ao Wang, Hui Chen, Zijia Lin, Jungong Han, Guiguang Ding.<br />
  "RepViT-SAM: Towards Real-Time Segmenting Anything." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.05760)] 
  [[code](https://github.com/THU-MIG/RepViT)]
  [2023.12]

- **SlimSAM:** Zigeng Chen, Gongfan Fang, Xinyin Ma, Xinchao Wang.<br />
  "0.1% Data Makes Segment Anything Slim." NeurIPS (2024).
  [[paper](https://arxiv.org/abs/2312.05284)] 
  [[code](https://github.com/czg1225/SlimSAM)]
  [2023.12]

- **CAR:** Fangzhou Song, Bin Zhu, Yanbin Hao, Shuo Wang, Xiangnan He.<br />
  "CAR: Consolidation, Augmentation and Regulation for Recipe Retrieval." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.04763)] 
  [2023.12]

- **HOLD:** Zicong Fan, Maria Parelli, Maria Eleni Kadoglou, Muhammed Kocabas, Xu Chen, Michael J. Black, Otmar Hilliges.<br />
  "HOLD: Category-agnostic 3D Reconstruction of Interacting Hands and Objects from Video." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.18448)] 
  [[code](https://github.com/zc-alexfan/hold)]
  [2023.12]

- **ViP-LLaVA:** Mu Cai, Haotian Liu, Siva Karthik Mustikovela, Gregory P. Meyer, Yuning Chai, Dennis Park, Yong Jae Lee.<br />
  "Making Large Multimodal Models Understand Arbitrary Visual Prompts." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.00784)] 
  [[code](https://vip-llava.github.io/)]
  [2023.12]

- **SPEC:** Wujian Peng, Sicheng Xie, Zuyao You, Shiyi Lan, Zuxuan Wu.<br />
  "Synthesize, Diagnose, and Optimize: Towards Fine-Grained Vision-Language Understanding." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.00081)] 
  [[code](https://github.com/wjpoom/SPEC)]
  [2023.12]

- **HiFi Tuner:** Zhonghao Wang, Wei Wei, Yang Zhao, Zhisheng Xiao, Mark Hasegawa-Johnson, Humphrey Shi, Tingbo Hou.<br />
  "HiFi Tuner: High-Fidelity Subject-Driven Fine-Tuning for Diffusion Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.00079)] 
  [2023.12]

- **TrafficMOT:** Lihao Liu, Yanqi Cheng, Zhongying Deng, Shujun Wang, Dongdong Chen, Xiaowei Hu, Pietro Liò, Carola-Bibiane Schönlieb, Angelica Aviles-Rivero.<br />
  "TrafficMOT: A Challenging Dataset for Multi-Object Tracking in Complex Traffic Scenarios." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.18839)] 
  [2023.12]

- **VideoBooth:** Yuming Jiang, Tianxing Wu, Shuai Yang, Chenyang Si, Dahua Lin, Yu Qiao, Chen Change Loy, Ziwei Liu.<br />
  "VideoBooth: Diffusion-based Video Generation with Image Prompts." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.00777)] 
  [[code](https://vchitect.github.io/VideoBooth-project/)]
  [2023.12]

- **Portrait Diffusion:** Jin Liu, Huaibo Huang, Chao Jin, Ran He.<br />
  "Portrait Diffusion: Training-free Face Stylization with Chain-of-Painting." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.02212)] 
  [[code](https://github.com/liujin112/)]
  [2023.12]

- **NPGs:** Devikalyan Das, Christopher Wewer, Raza Yunus, Eddy Ilg, Jan Eric Lenssen.<br />
  "Neural Parametric Gaussians for Monocular Non-Rigid Object Reconstruction." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.01196)] 
  [2023.12]

- **Diffusion Handles:** Karran Pandey, Paul Guerrero, Matheus Gadelha, Yannick Hold-Geoffroy, Karan Singh, Niloy Mitra.<br />
  "Diffusion Handles: Enabling 3D Edits for Diffusion Models by Lifting Activations to 3D." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.02190)] 
  [[code](https://diffusionhandles.github.io/)]
  [2023.12]

- **VLTSeg:** Christoph Hümmer, Manuel Schwonberg, Liangwei Zhong, Hu Cao, Alois Knoll, Hanno Gottschalk.<br />
  "VLTSeg: Simple Transfer of CLIP-Based Vision-Language Representations for Domain Generalized Semantic Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.02021)] 
  [2023.12]

- **CustomNeRF:** Runze He, Shaofei Huang, Xuecheng Nie, Tianrui Hui, Luoqi Liu, Jiao Dai, Jizhong Han, Guanbin Li, Si Liu.<br />
  "Customize your NeRF: Adaptive Source Driven 3D Scene Editing via Local-Global Iterative Training." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.01663)] 
  [[code](https://customnerf.github.io/)]
  [2023.12]

- Yilin Ye, Qian Zhu, Shishi Xiao, Kang Zhang, Wei Zeng.<br />
  "The Contemporary Art of Image Search: Iterative User Intent Expansion via Vision-Language Model." CSCW (2024).
  [[paper](https://arxiv.org/abs/2312.01656)] 
  [2023.12]

- **StoryGPT-V:** Xiaoqian Shen, Mohamed Elhoseiny.<br />
  "Large Language Models as Consistent Story Visualizers." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.02252)] 
  [[code](https://storygpt-v.s3.amazonaws.com/index.html)]
  [2023.12]

- **PixelLM:** Zhongwei Ren, Zhicheng Huang, Yunchao Wei, Yao Zhao, Dongmei Fu, Jiashi Feng, Xiaojie Jin.<br />
  "PixelLM: Pixel Reasoning with Large Multimodal Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.02228)] 
  [[code](https://pixellm.github.io/)]
  [2023.12]

- **SAGE:** Haoran Geng, Songlin Wei, Congyue Deng, Bokui Shen, He Wang, Leonidas Guibas.<br />
  "SAGE: Bridging Semantic and Actionable Parts for GEneralizable Articulated-Object Manipulation under Language Instructions." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.01307)] 
  [[code](https://geometry.stanford.edu/projects/sage/)]
  [2023.12]

- **TranSegPGD:** Xiaojun Jia, Jindong Gu, Yihao Huang, Simeng Qin, Qing Guo, Yang Liu, Xiaochun Cao.<br />
  "TranSegPGD: Improving Transferability of Adversarial Examples on Semantic Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.02207)] 
  [2023.12]

- **MANUS:** Chandradeep Pokhariya, Ishaan N Shah, Angela Xing, Zekun Li, Kefan Chen, Avinash Sharma, Srinath Sridhar.<br />
  "MANUS: Markerless Hand-Object Grasp Capture using Articulated 3D Gaussians." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.02137)] 
  [[code](https://ivl.cs.brown.edu/research/manus.html)]
  [2023.12]

- Yao-Chih Lee, Zhoutong Zhang, Kevin Blackburn-Matzen, Simon Niklaus, Jianming Zhang, Jia-Bin Huang, Feng Liu.<br />
  "Fast View Synthesis of Casual Videos with Soup-of-Planes." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.02135)] 
  [[code](https://casual-fvs.github.io/)]
  [2023.12]

- **UniLSeg:** Yong Liu, Cairong Zhang, Yitong Wang, Jiahao Wang, Yujiu Yang, Yansong Tang.<br />
  "Universal Segmentation at Arbitrary Granularity with Language Instruction." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.01623)] 
  [[code](https://github.com/workforai/UniLSeg)]
  [2023.12]

- **LooseControl:** Shariq Farooq Bhat, Niloy J. Mitra, Peter Wonka.<br />
  "LooseControl: Lifting ControlNet for Generalized Depth Conditioning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.03079)] 
  [[code](https://shariqfarooq123.github.io/loose-control/)]
  [2023.12]

- Yankun Wu, Yuta Nakashima, Noa Garcia.<br />
  "Stable Diffusion Exposed: Gender Bias from Prompt to Image." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.03027)] 
  [2023.12]

- **Drag-A-Video:** Yao Teng, Enze Xie, Yue Wu, Haoyu Han, Zhenguo Li, Xihui Liu.<br />
  "Drag-A-Video: Non-rigid Video Editing with Point-based Interaction." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.02936)] 
  [[code](https://drag-a-video.github.io/)]
  [2023.12]

- **SAVE:** Yeji Song, Wonsik Shin, Junsoo Lee, Jeesoo Kim, Nojun Kwak.<br />
  "SAVE: Protagonist Diversification with Structure Agnostic Video Editing." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.02503)] 
  [[code](https://ldynx.github.io/SAVE/)]
  [2023.12]

- **RA-SRGT:** Mengke Song, Linfeng Li, Dunquan Wu, Wenfeng Song, Chenglizhao Chen.<br />
  "Rethinking Object Saliency Ranking: A Novel Whole-flow Processing Paradigm." IEEE TIP (2023).
  [[paper](https://arxiv.org/abs/2312.03226)] 
  [[code](https://github.com/MengkeSong/Saliency-Ranking-Paradigm)]
  [2023.12]

- **TokenCompose:** Zirui Wang, Zhizhou Sha, Zheng Ding, Yilin Wang, Zhuowen Tu.<br />
  "TokenCompose: Grounding Diffusion with Token-level Supervision." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.03626)] 
  [[code](https://mlpc-ucsd.github.io/TokenCompose)]
  [2023.12]

- **FoodFusion:** Olivia Markham, Yuhao Chen, Chi-en Amy Tai, Alexander Wong.<br />
  "FoodFusion: A Latent Diffusion Model for Realistic Food Image Generation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.03540)] 
  [[code](https://bit.ly/genai4good)]
  [2023.12]

- **CrackSAM:** Kang Ge, Chen Wang, Yutao Guo.<br />
  "Fine-tune vision foundation model for crack segmentation in civil infrastructures." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.04233)] 
  [2023.12]

- **SAMBA:** Ronan Docherty, Isaac Squires, Antonis Vamvakeros, Samuel J. Cooper.<br />
  "SAMBA: A Trainable Segmentation Web-App with Smart Labelling." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.04197)] 
  [[code](https://www.sambasegment.com/)]
  [2023.12]

- Israt Zarin Era, Imtiaz Ahmed, Zhichao Liu, Srinjoy Das.<br />
  "An unsupervised approach towards promptable defect segmentation in laser-based additive manufacturing by Segment Anything." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.04063)] 
  [2023.12]

- **PartSLIP++:** Yuchen Zhou, Jiayuan Gu, Xuanlin Li, Minghua Liu, Yunhao Fang, Hao Su.<br />
  "PartSLIP++: Enhancing Low-Shot 3D Part Segmentation via Multi-View Instance Segmentation and Maximum Likelihood Estimation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.03015)] 
  [[code](https://github.com/zyc00/PartSLIP2)]
  [2023.12]

- **Sambor:** Xumeng Han, Longhui Wei, Xuehui Yu, Zhiyang Dou, Xin He, Kuiran Wang, Zhenjun Han, Qi Tian.<br />
  "Boosting Segment Anything Model Towards Open-Vocabulary Learning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.03628)] 
  [[code](https://github.com/ucas-vg/Sambor)]
  [2023.12]

- **SAMS:** Xiaobo Yang, Xiaojin Gong.<br />
  "Foundation Model Assisted Weakly Supervised Semantic Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.03585)] 
  [2023.12]

- **WeSAM:** Haojie Zhang, Yongyi Su, Xun Xu, Kui Jia.<br />
  "Improving the Generalization of Segmentation Foundation Model under Distribution Shift via Weakly Supervised Adaptation." CVPR (2024).
  [[paper](https://arxiv.org/abs/2312.03502)] 
  [[code](https://github.com/Zhang-Haojie/WeSAM)]
  [2023.12]

- **Feature 3DGS:** Shijie Zhou, Haoran Chang, Sicheng Jiang, Zhiwen Fan, Zehao Zhu, Dejia Xu, Pradyumna Chari, Suya You, Zhangyang Wang, Achuta Kadambi.<br />
  "Feature 3DGS: Supercharging 3D Gaussian Splatting to Enable Distilled Feature Fields." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.03203)] 
  [[code](https://feature-3dgs.github.io/)]
  [2023.12]

- **AI-SAM:** Yimu Pan, Sitao Zhang, Alison D. Gernand, Jeffery A. Goldstein, James Z. Wang.<br />
  "AI-SAM: Automatic and Interactive Segment Anything Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.03119)] 
  [[code](https://github.com/ymp5078/AI-SAM)]
  [2023.12]

- **SSRS:** Xianping Ma, Qianqian Wu, Xingyu Zhao, Xiaokang Zhang, Man-On Pun, Bo Huang.<br />
  "SAM-Assisted Remote Sensing Imagery Semantic Segmentation with Object and Boundary Constraints." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.02464)] 
  [[code](https://github.com/sstary/SSRS)]
  [2023.12]


- **GranSAM:** Rohit Kundu, Sudipta Paul, Rohit Lal, Amit K. Roy-Chowdhury.<br />
  "Towards Granularity-adjusted Pixel-level Semantic Annotation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.02420)] 
  [2023.12]

- **SAGA:** Jiazhong Cen, Jiemin Fang, Chen Yang, Lingxi Xie, Xiaopeng Zhang, Wei Shen, Qi Tian.<br />
  "Segment Any 3D Gaussians." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.00860)] 
  [[homepage](https://jumpat.github.io/SAGA/)]
  [2023.12]

- **APE:** Yunhang Shen, Chaoyou Fu, Peixian Chen, Mengdan Zhang, Ke Li, Xing Sun, Yunsheng Wu, Shaohui Lin, Rongrong Ji.<br />
  "Aligning and Prompting Everything All at Once for Universal Visual Perception." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.02153)] 
  [[code](https://github.com/shenyunhang/APE)]
  [2023.12]

- **SANeRF-HQ:** Yichen Liu, Benran Hu, Chi-Keung Tang, Yu-Wing Tai.<br />
  "SANeRF-HQ: Segment Anything for NeRF in High Quality." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.01531)] 
  [[code](https://lyclyc52.github.io/SANeRF-HQ/)]
  [2023.12]

- **ObjectChangeDetection:** Aikaterini Adam, Konstantinos Karantzalos, Lazaros Grammatikopoulos, Torsten Sattler.<br />
  "Has Anything Changed? 3D Change Detection by 2D Segmentation Masks." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.01148)] 
  [[code](https://github.com/katadam/ObjectChangeDetection)]
  [2023.12]

- **SCA:** Xiaoke Huang, Jianfeng Wang, Yansong Tang, Zheng Zhang, Han Hu, Jiwen Lu, Lijuan Wang, Zicheng Liu.<br />
  "Segment and Caption Anything." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.00869)] 
  [[code](https://xk-huang.github.io/segment-caption-anything/)]
  [2023.12]

- **EfficientSAM:** Yunyang Xiong, Bala Varadarajan, Lemeng Wu, Xiaoyu Xiang, Fanyi Xiao, Chenchen Zhu, Xiaoliang Dai, Dilin Wang, Fei Sun, Forrest Iandola, Raghuraman Krishnamoorthi, Vikas Chandra.<br />
  "EfficientSAM: Leveraged Masked Image Pretraining for Efficient Segment Anything." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.00863)] 
  [2023.12]

- **U-BDD++:** Yiyun Zhang, Zijian Wang, Yadan Luo, Xin Yu, Zi Huang.<br />
  "Learning Efficient Unsupervised Satellite Image-based Building Damage Detection." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.01576)] 
  [[code](https://github.com/fzmi/ubdd)]
  [2023.12]

- **Gaussian Grouping:** Mingqiao Ye, Martin Danelljan, Fisher Yu, Lei Ke.<br />
  "Gaussian Grouping: Segment and Edit Anything in 3D Scenes." ECCV (2024).
  [[paper](https://arxiv.org/abs/2312.00732)] 
  [[code](https://github.com/lkeab/gaussian-grouping)]
  [2023.12]

- **SAM-CLNet:** Yiming Zhao, Tao Zhou, Yunqi Gu, Yi Zhou, Yizhe Zhang, Ye Wu, Huazhu Fu.<br />
  "Segment Anything Model-guided Collaborative Learning Network for Scribble-supervised Polyp Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2312.00312)] 
  [2023.12]

- **S2M:** Wenjie Zhao, Jia Li, Xin Dong, Yu Xiang, Yunhui Guo.<br />
  "Segment Every Out-of-Distribution Object." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.16516)] 
  [2023.11]

- **ZeroPS:** Yuheng Xue, Nenglun Chen, Jun Liu, Wenyun Sun.<br />
  "ZeroPS: High-quality Cross-modal Knowledge Transfer for Zero-Shot 3D Part Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.14262)] 
  [2023.11]

- **GigaPose:** Van Nguyen Nguyen, Thibault Groueix, Mathieu Salzmann, Vincent Lepetit.<br />
  "GigaPose: Fast and Robust Novel Object Pose Estimation via One Correspondence." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.14155)] 
  [[code](https://github.com/nv-nguyen/gigaPose)]
  [2023.11]

- **ToddlerDiffusion:** Eslam Mohamed Bakr, Liangbing Zhao, Vincent Tao Hu, Matthieu Cord, Patrick Perez, Mohamed Elhoseiny.<br />
  "ToddlerDiffusion: Flash Interpretable Controllable Diffusion Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.14542)] 
  [2023.11]

- **GaussianEditor:** Yiwen Chen, Zilong Chen, Chi Zhang, Feng Wang, Xiaofeng Yang, Yikai Wang, Zhongang Cai, Lei Yang, Huaping Liu, Guosheng Lin.<br />
  "GaussianEditor: Swift and Controllable 3D Editing with Gaussian Splatting." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.14521)] 
  [[code](https://buaacyw.github.io/gaussian-editor)]
  [2023.11]

- **SEGIC:** Lingchen Meng, Shiyi Lan, Hengduo Li, Jose M. Alvarez, Zuxuan Wu, Yu-Gang Jiang.<br />
  "SEGIC: Unleashing the Emergent Correspondence for In-Context Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.14671)] 
  [[code](https://github.com/MengLcool/SEGIC)]
  [2023.11]

- Nguyen, Le Quan, Jihye Shin, Sanghuyn Ryu, L. Minh Dang, Han Yong Park, O New Lee, and Hyeonjoon Moon.<br />
  "Innovative Cucumber Phenotyping: A Smartphone-Based and Data-Labeling-Free Model." ArXiv (2023).
  [[paper](https://www.mdpi.com/2079-9292/12/23/4775)] 
  [2023.11]

- Nicholas Lui, Bryan Chia, William Berrios, Candace Ross, Douwe Kiela.<br />
  "Leveraging Diffusion Perturbations for Measuring Fairness in Computer Vision." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.15108)] 
  [2023.11]

- **RO-LLaMA:** Kwanyoung Kim, Yujin Oh, Sangjoon Park, Hwa Kyung Byun, Jin Sung Kim, Yong Bae Kim, Jong Chul Ye.<br />
  "RO-LLaMA: Generalist LLM for Radiation Oncology via Noise Augmentation and Consistency Regularization." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.15876)] 
  [2023.11]

- **SiTH:** Hsuan-I Ho, Jie Song, Otmar Hilliges.<br />
  "SiTH: Single-view Textured Human Reconstruction with Image-Conditioned Diffusion." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.15855)] 
  [[code](https://ait.ethz.ch/sith)]
  [2023.11]

- **GaussianEditor:** Jiemin Fang, Junjie Wang, Xiaopeng Zhang, Lingxi Xie, Qi Tian.<br />
  "GaussianEditor: Editing 3D Gaussians Delicately with Text Instructions." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.16037)] 
  [[homepage](https://gaussianeditor.github.io/)]
  [2023.11]

- **VLPrompt:** Zijian Zhou, Miaojing Shi, Holger Caesar.<br />
  "VLPrompt: Vision-Language Prompting for Panoptic Scene Graph Generation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.16492)] 
  [2023.11]

- **MotionZero:** Sitong Su, Litao Guo, Lianli Gao, Hengtao Shen, Jingkuan Song.<br />
  "MotionZero:Exploiting Motion Priors for Zero-shot Text-to-Video Generation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.16635)] 
  [2023.11]

- **SEED-Bench-2:** Bohao Li, Yuying Ge, Yixiao Ge, Guangzhi Wang, Rui Wang, Ruimao Zhang, Ying Shan.<br />
  "SEED-Bench-2: Benchmarking Multimodal Large Language Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.17092)] 
  [[code](https://github.com/AILab-CVC/SEED-Bench)]
  [2023.11]

- **MLKG:** Shupeng Cheng, Ge-Peng Ji, Pengda Qin, Deng-Ping Fan, Bowen Zhou, Peng Xu.<br />
  "Large Model Based Referring Camouflaged Object Detection." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.17122)] 
  [2023.11]

- **APAP:** Seungwoo Yoo, Kunho Kim, Vladimir G. Kim, Minhyuk Sung.<br />
  "As-Plausible-As-Possible: Plausibility-Aware Mesh Deformation Using 2D Diffusion Priors." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.16739)] 
  [[homepage](https://as-plausible-as-possible.github.io/)]
  [2023.11]

- **ROSO:** Yusuke Miyashita, Dimitris Gahtidis, Colin La, Jeremy Rabinowicz, Jurgen Leitner.<br />
  "ROSO: Improving Robotic Policy Inference via Synthetic Observations." ACRA (2023).
  [[paper](https://arxiv.org/abs/2311.16680)] 
  [[code](https://yusuke710.github.io/roso.github.io/)]
  [2023.11]

- **Exo2EgoDVC:** Takehiko Ohkawa, Takuma Yagi, Taichi Nishimura, Ryosuke Furuta, Atsushi Hashimoto, Yoshitaka Ushiku, Yoichi Sato.<br />
  "Exo2EgoDVC: Dense Video Captioning of Egocentric Procedural Activities Using Web Instructional Videos." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.16444)] 
  [2023.11]

- **ESAM:** Chengwen Zhang, Yingwei Zhao.<br />
  "Efficient SAM for Medical Image Analysis." ArXiv (2023).
  [[paper](https://www.researchgate.net/profile/Yingwei-Zhao-4/publication/375895620_EFFICIENT_SAM_FOR_MEDICAL_IMAGE_ANALYSIS/links/6561c43bb1398a779db369d5/EFFICIENT-SAM-FOR-MEDICAL-IMAGE-ANALYSIS.pdf)] 
  [2023.11]

- **MMA-Diffusion:** Yijun Yang, Ruiyuan Gao, Xiaosen Wang, Nan Xu, Qiang Xu.<br />
  "MMA-Diffusion: MultiModal Attack on Diffusion Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.17516)] 
  [2023.11]

- **LLM-State:** Siwei Chen, Anxing Xiao, David Hsu.<br />
  "LLM-State: Expandable State Representation for Long-horizon Task Planning in the Open World." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.17406)] 
  [2023.11]

- Narendra Dev, J. John Soundar Jerome, Hélène Scolan, Jean-Philippe Matas.<br />
  "Liquid inertia versus bubble cloud buoyancy in circular plunging jet experiments." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.17572)] 
  [2023.11]

- **HUGS:** Muhammed Kocabas, Jen-Hao Rick Chang, James Gabriel, Oncel Tuzel, Anurag Ranjan.<br />
  "HUGS: Human Gaussian Splats." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.17910)] 
  [[code](https://github.com/apple/ml-hugs)]
  [2023.11]

- **SAM-ILP:** Aayush Kumar Tyagi, Vaibhav Mishra, Prathosh A. P., Mausam.<br />
  "Guided Prompting in SAM for Weakly Supervised Cell Segmentation in Histopathological Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.17960)] 
  [[code](https://github.com/dair-iitd/Guided-Prompting-SAM)]
  [2023.11]

- **SAMPro3D:** Mutian Xu, Xingyilang Yin, Lingteng Qiu, Yang Liu, Xin Tong, Xiaoguang Han.<br />
  "SAMPro3D: Locating SAM Prompts in 3D for Zero-Shot Scene Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.17707)] 
  [[code](https://mutianxu.github.io/sampro3d/)]
  [2023.11]

- **SAM-COBOT:** Zelin Peng, Zhengqin Xu, Zhilin Zeng, Lingxi Xie, Qi Tian, Wei Shen.<br />
  "Parameter Efficient Fine-tuning via Cross Block Orchestration for Segment Anything Model." CVPR (2024).
  [[paper](https://arxiv.org/abs/2311.17112)] 
  [2023.11]

- **SemReID:** Siyuan Huang, Yifan Zhou, Ram Prabhakar Kathirvel, Rama Chellappa, Chun Pong Lau.<br />
  "Self-Supervised Learning of Whole and Component-Based Semantic Representations for Person Re-Identification." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.17074)] 
  [2023.11]

- **I-MedSAM:** Xiaobao Wei, Jiajun Cao, Yizhu Jin, Ming Lu, Guangyu Wang, Shanghang Zhang.<br />
  "I-MedSAM: Implicit Medical Image Segmentation with Segment Anything." ECCV (2024).
  [[paper](https://arxiv.org/abs/2311.17081)] 
  [2023.11]

- **RAH-Bench:** Zhiyang Chen, Yousong Zhu, Yufei Zhan, Zhaowen Li, Chaoyang Zhao, Jinqiao Wang, Ming Tang.<br />
  "Mitigating Hallucination in Visual Language Models with Visual Supervision." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.16479)] 
  [2023.11]

- Fei He, Zhiyuan Yang, Mingyue Gao, Biplab Poudel, Newgin Sam Ebin Sam Dhas, Rajan Gyawali, Ashwin Dhakal, Jianlin Cheng, Dong Xu.<br />
  "Adapting Segment Anything Model (SAM) through Prompt-based Learning for Enhanced Protein Identification in Cryo-EM Micrographs." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.16140)] 
  [2023.11]

- **Obj-NeRF:** Zhiyi Li, Lihe Ding, Tianfan Xue.<br />
  "Obj-NeRF: Extract Object NeRFs from Multi-view Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.15291)] 
  [[code](https://objnerf.github.io/)]
  [2023.11]

- Ming Li, Guang Yang.<br />
  "Where to Begin? From Random to Foundation Model Instructed Initialization in Federated Learning for Medical Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.15463)] 
  [2023.11]

- **SAM-6D:** Jiehong Lin, Lihua Liu, Dekun Lu, Kui Jia.<br />
  "SAM-6D: Segment Anything Model Meets Zero-Shot 6D Object Pose Estimation." CVPR (2024).
  [[paper](https://arxiv.org/abs/2311.15707)] 
  [[code](https://github.com/JiehongLin/SAM-6D)]
  [2023.11]

- **MARIS:** Mengxi Zhang, Yiming Liu, Xiangjun Yin, Huanjing Yue, Jingyu Yang.<br />
  "MARIS: Referring Image Segmentation via Mutual-Aware Attention Features." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.15727)] 
  [2023.11]

- **Stable-SAM:** Qi Fan, Xin Tao, Lei Ke, Mingqiao Ye, Yuan Zhang, Pengfei Wan, Zhongyuan Wang, Yu-Wing Tai, Chi-Keung Tang.<br />
  "Stable Segment Anything Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.15776)] 
  [[code](https://github.com/fanq15/Stable-SAM)]
  [2023.11]

- **PromptNucSeg:** Zhongyi Shui, Yunlong Zhang, Kai Yao, Chenglu Zhu, Yuxuan Sun, Lin Yang.<br />
  "Unleashing the Power of Prompt-driven Nucleus Instance Segmentation." ECCV (2024).
  [[paper](https://arxiv.org/abs/2311.15939)] 
  [[code](https://github.com/windygoo/PromptNucSeg)]
  [2023.11]

- Rutuja Gurav, Het Patel, Zhuocheng Shang, Ahmed Eldawy, Jia Chen, Elia Scudiero, Evangelos Papalexakis.<br />
  "Can SAM recognize crops? Quantifying the zero-shot performance of a semantic segmentation foundation model on generating crop-type maps using satellite imagery for precision agriculture." NeurIPS (2023).
  [[paper](https://arxiv.org/abs/2311.15138)] 
  [[code](http://reliable.to/)]
  [2023.11]

- Francesco Croce, Matthias Hein.<br />
  "Segment (Almost) Nothing: Prompt-Agnostic Adversarial Attacks on Segmentation Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.14450)] 
  [2023.11]

- **P2RBox:** Guangming Cao, Xuehui Yu, Wenwen Yu, Xumeng Han, Xue Yang, Guorong Li, Jianbin Jiao, Zhenjun Han.<br />
  "P2RBox: A Single Point is All You Need for Oriented Object Detection." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.13128)] 
  [2023.11]

- **PG-Video-LLaVA:** Shehan Munasinghe, Rusiru Thushara, Muhammad Maaz, Hanoona Abdul Rasheed, Salman Khan, Mubarak Shah, Fahad Khan.<br />
  "PG-Video-LLaVA: Pixel Grounding Large Video-Language Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.13435)] 
  [[code](https://github.com/mbzuai-oryx/Video-LLaVA)]
  [2023.11]

- **MetaDreamer:** Lincong Feng, Muyu Wang, Maoyu Wang, Kuo Xu, Xiaoli Liu.<br />
  "MetaDreamer: Efficient Text-to-3D Creation With Disentangling Geometry and Texture." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.10123)] 
  [[code](https://metadreamer3d.github.io/)]
  [2023.11]

- **Emu Edit:** Shelly Sheynin, Adam Polyak, Uriel Singer, Yuval Kirstain, Amit Zohar, Oron Ashual, Devi Parikh, Yaniv Taigman.<br />
  "Emu Edit: Precise Image Editing via Recognition and Generation Tasks." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.10089)] 
  [[homepage](https://emu-edit.metademolab.com/)]
  [2023.11]

- Duy Minh Ho Nguyen, Tan Ngoc Pham, Nghiem Tuong Diep, Nghi Quoc Phan, Quang Pham, Vinh Tong, Binh T. Nguyen, Ngan Hoang Le, Nhat Ho, Pengtao Xie, Daniel Sonntag, Mathias Niepert.<br />
  "On the Out of Distribution Robustness of Foundation Models in Medical Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.11096)] 
  [2023.11]

- Yu Ando, Nora Jee-Young Park and, Gun Oh Chong, Seokhwan Ko, Donghyeon Lee, Junghwan Cho, Hyungsoo Han.<br />
  "Interpretable pap smear cell representation for cervical cancer screening." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.10269)] 
  [2023.11]

- **GT-Maps:** Yimeng Li, Navid Rajabi, Sulabh Shrestha, Md Alimoor Reza, Jana Kosecka.<br />
  "Labeling Indoor Scenes with Fusion of Out-of-the-Box Perception Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.10883)] 
  [2023.11]

- Nam V. Nguyen, Hieu Trung Huynh, and Phuc-Lu Le.<br />
  "Deep Learning Techniques for Segmenting Breast Lesion Regions and Classifying Mammography Images." ArXiv (2023).
  [[paper](https://link.springer.com/chapter/10.1007/978-981-99-8296-7_34)] 
  [2023.11]

- Ren Li, Corentin Dumery, Benoît Guillard, Pascal Fua.<br />
  "Garment Recovery with Shape and Deformation Priors." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.10356)] 
  [2023.11]

- **MROS:** Kechen Song, Hongwei Wen, Xiaotong Xue, Liming Huang, Yingying Ji, Yunhui Yan .<br />
  "Modality Registration and Object Search Framework for UAV-based Unregistered RGB-T Image Salient Object Detection." ArXiv (2023).
  [[paper](https://www.researchgate.net/profile/Ke-Chen-Song/publication/375623798_Modality_Registration_and_Object_Search_Framework_for_UAV-based_Unregistered_RGB-T_Image_Salient_Object_Detection/links/65558ed9b1398a779d9086ed/Modality-Registration-and-Object-Search-Framework-for-UAV-Based-Unregistered-RGB-T-Image-Salient-Object-Detection.pdf)] 
  [[code](https://github.com/VDT-2048/UAV-RGB-T-2400)]
  [2023.11]

- **CPVLF:** Lv Tang, Peng-Tao Jiang, Zhihao Shen, Hao Zhang, Jinwei Chen, Bo Li.<br />
  "Generalization and Hallucination of Large Vision-Language Models through a Camouflaged Lens." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.11273)] 
  [2023.11]

- Zixuan Xie, Rengan Xie, Rong Li, Kai Huang, Pengju Qiao, Jingsen Zhu, Xu Yin, Qi Ye, Wei Hua, Yuchi Huo, Hujun Bao.<br />
  "Holistic Inverse Rendering of Complex Facade via Aerial 3D Scanning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.11825)] 
  [2023.11]

- **Clarity ChatGPT:** Yanyan Wei, Zhao Zhang, Jiahuan Ren, Xiaogang Xu, Richang Hong, Yi Yang, Shuicheng Yan, Meng Wang.<br />
  "Clarity ChatGPT: An Interactive and Adaptive Processing System for Image Restoration and Enhancement." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.11695)] 
  [2023.11]

- **GCDSS:** Zhengyuan Peng, Qijian Tian, Jianqing Xu, Yizhang Jin, Xuequan Lu, Xin Tan, Yuan Xie, Lizhuang Ma.<br />
  "Generalized Category Discovery in Semantic Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.11525)] 
  [[code](https://github.com/JethroPeng/GCDSS)]
  [2023.11]

- **Few-shot SLVM:** Xiyu Qi, Yifan Wu, Yongqiang Mao, Wenhui Zhang, Yidan Zhang.<br />
  "Self-guided Few-shot Semantic Segmentation for Remote Sensing Imagery Based on Large Vision Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.13200)] 
  [2023.11]

- **OCT-mosaicking:** Jiacheng Wang, Hao Li, Dewei Hu, Yuankai K. Tao, Ipek Oguz.<br />
  "Novel OCT mosaicking pipeline with Feature- and Pixel-based registration." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.13052)] 
  [[code](https://github.com/MedICL-VU/OCT-mosaicking)]
  [2023.11]

- **PseCo:** Huang Zhizhong, Dai Mingliang, Zhang Yi, Zhang Junping, Shan Hongming.<br />
  "Point, Segment and Count: A Generalized Framework for Object Counting." CVPR (2024).
  [[paper](https://arxiv.org/abs/2311.12386)] 
  [[code](https://github.com/Hzzone/PseCo)]
  [2023.11]

- **FreeKD:** Yuan Zhang, Tao Huang, Jiaming Liu, Tao Jiang, Kuan Cheng, Shanghang Zhang.<br />
  "FreeKD: Knowledge Distillation via Semantic Frequency Prompt." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.12079)] 
  [2023.11]

- Rohit Bharadwaj, Muzammal Naseer, Salman Khan, Fahad Shahbaz Khan.<br />
  "Enhancing Novel Object Detection via Cooperative Foundational Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.12068)] 
  [[code](https://github.com/rohit901/cooperative-foundational-models)]
  [2023.11]

- **GMISeg:** Jing Xu.<br />
  "GMISeg: General Medical Image Segmentation without Re-Training." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.12539)] 
  [2023.11]

- Tian Meng, Yang Tao, Wuliang Yin.<br />
  "Few-Shot Classification & Segmentation Using Large Language Models Agent." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.12065)] 
  [2023.11]

- **MorSeg-CAM-SAM:** Xin Yue, Qing Zhao, Jianqiang Li, Xiaoling Liu, Changwei Song, Suqin Liu, Guanghui Fu.<br />
  "Morphology-Enhanced CAM-Guided SAM for weakly supervised Breast Lesion Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.11176)] 
  [[code](https://github.com/YueXin18/MorSeg-CAM-SAM)]
  [2023.11]

- **SA-Med2D-20M:** Jin Ye, Junlong Cheng, Jianpin Chen, Zhongying Deng, Tianbin Li, Haoyu Wang, Yanzhou Su, Ziyan Huang, Jilong Chen, Lei Jiang, Hui Sun, Min Zhu, Shaoting Zhang, Junjun He, Yu Qiao.<br />
  "SA-Med2D-20M Dataset: Segment Anything in 2D Medical Imaging with 20 Million masks." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.11969)] 
  [[code](https://github.com/OpenGVLab/SAM-Med2D)]
  [2023.11]

- **OmniSeg3D:** Haiyang Ying, Yixuan Yin, Jinzhi Zhang, Fan Wang, Tao Yu, Ruqi Huang, Lu Fang.<br />
  "OmniSeg3D: Omniversal 3D Segmentation via Hierarchical Contrastive Learning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.11666)] 
  [[homepage](https://oceanying.github.io/OmniSeg3D/)]
  [2023.11]

- **GeoSAM:** Rafi Ibn Sultan, Chengyin Li, Hui Zhu, Prashant Khanduri, Marco Brocanelli, Dongxiao Zhu.<br />
  "GeoSAM: Fine-tuning SAM with Sparse and Dense Visual Prompting for Automated Segmentation of Mobility Infrastructure." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.11319)] 
  [2023.11]

- **CellSAM :** Uriah Israel, Markus Marks, Rohit Dilip, Qilin Li, Morgan Schwartz, Elora Pradhan, Edward Pao, Shenyi Li, Alexander Pearson-Goulart, Pietro Perona, Georgia Gkioxari, Ross Barnowski, Yisong Yue, David Van Valen.<br />
  "A Foundation Model for Cell Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.11004)] 
  [[code](https://label-dev.deepcell.org/)]
  [2023.11]

- **RockSAM:** Zhaoyang Ma, Xupeng He, Shuyu Sun, Bicheng Yan, Hyung Kwak, Jun Gao.<br />
  "Zero-Shot Digital Rock Image Segmentation with a Fine-Tuned Segment Anything Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.10865)] 
  [2023.11]

- **DMV3D:** Yinghao Xu, Hao Tan, Fujun Luan, Sai Bi, Peng Wang, Jiahao Li, Zifan Shi, Kalyan Sunkavalli, Gordon Wetzstein, Zexiang Xu, Kai Zhang.<br />
  "DMV3D: Denoising Multi-View Diffusion using 3D Large Reconstruction Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.09217)] 
  [[code](https://justimyhxu.github.io/projects/dmv3d/)]
  [2023.11]

- **InterpAny-Clearer:** Zhihang Zhong, Gurunandan Krishnan, Xiao Sun, Yu Qiao, Sizhuo Ma, Jian Wang.<br />
  "Clearer Frames, Anytime: Resolving Velocity Ambiguity in Video Frame Interpolation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.08007)] 
  [[homepage](https://zzh-tech.github.io/InterpAny-Clearer/)]
  [[code](https://github.com/zzh-tech/InterpAny-Clearer)]
  [2023.11]

- **OSM:** Qihang Yu, Xiaohui Shen, Liang-Chieh Chen.<br />
  "Towards Open-Ended Visual Recognition with Large Language Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.08400)] 
  [[code](https://github.com/bytedance/OmniScient-Model)]
  [2023.11]

- **UR-SAM:** Yichi Zhang, Shiyao Hu, Chen Jiang, Yuan Cheng, Yuan Qi.<br />
  "Segment Anything Model with Uncertainty Rectification for Auto-Prompting Medical Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.10529)] 
  [2023.11]

- **DefectSAM:** Bozhen Hu, Bin Gao, Cheng Tan, Tongle Wu, Stan Z. Li.<br />
  "Segment Anything in Defect Detection." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.10245)] 
  [2023.11]

- **UnifiedVisionGPT:** Chris Kelly, Luhui Hu, Cindy Yang, Yu Tian, Deshun Yang, Bang Yang, Zaoshan Huang, Zihao Li, Yuexian Zou.<br />
  "UnifiedVisionGPT: Streamlining Vision-Oriented AI through Generalized Multimodal Framework." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.10125)] 
  [[code](https://github.com/LHBuilder/SA-Segment-Anything)]
  [2023.11]

- **Slide-SAM:** Quan Quan, Fenghe Tang, Zikang Xu, Heqin Zhu, S. Kevin Zhou.<br />
  "Slide-SAM: Medical SAM Meets Sliding Window." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.10121)] 
  [2023.11]

- **MM-Navigator:** An Yan, Zhengyuan Yang, Wanrong Zhu, Kevin Lin, Linjie Li, Jianfeng Wang, Jianwei Yang, Yiwu Zhong, Julian McAuley, Jianfeng Gao, Zicheng Liu, Lijuan Wang.<br />
  “GPT-4V in Wonderland: Large Multimodal Models for Zero-Shot Smartphone GUI Navigation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.07562)] 
  [[code](https://github.com/zzxslp/MM-Navigator)]
  [2023.11]

- **TriDental:** Tomáš Kunzo, Viktor Kocur, Lukáš Gajdošech, Martin Madaras.<br />
  "Processing and Segmentation of Human Teeth from 2D Images using Weakly Supervised Learning." DISA (2023).
  [[paper](https://arxiv.org/abs/2311.07398)] 
  [2023.11]

- Hyungeun Lee, Ung Hwang, Seungwon Yu, Chang-Hun Lee, Kijung Yoon.<br />
  "Processing and Segmentation of Human Teeth from 2D Images using Weakly Supervised Learning." ML4H (2023).
  [[paper](https://arxiv.org/abs/2311.06834)] 
  [2023.11]

- **AdapterShadow:** Leiping Jie, Hui Zhang.<br />
  "AdapterShadow: Adapting Segment Anything Model for Shadow Detection." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.08891)] 
  [[code](https://github.com/LeipingJie/AdapterShadow)]
  [2023.11]

- **Uni-COAL:** Zhiyun Song, Zengxin Qi, Xin Wang, Xiangyu Zhao, Zhenrong Shen, Sheng Wang, Manman Fei, Zhe Wang, Di Zang, Dongdong Chen, Linlin Yao, Qian Wang, Xuehai Wu, Lichi Zhang.<br />
  "Uni-COAL: A Unified Framework for Cross-Modality Synthesis and Super-Resolution of MR Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.08225)] 
  [2023.11]

- **SAMIHS:** Yinuo Wang, Kai Chen, Weimin Yuan, Cai Meng, XiangZhi Bai.<br />
  "SAMIHS: Adaptation of Segment Anything Model for Intracranial Hemorrhage Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.08190)] 
  [[code](https://github.com/mileswyn/SAMIHS)]
  [2023.11]

- Virmarie Maquiling, Sean Anthony Byrne, Diederick C. Niehorster, Marcus Nyström, Enkelejda Kasneci.<br />
  "Zero-Shot Segmentation of Eye Features Using the Segment Anything Model (SAM)." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.08077)] 
  [2023.11]
  
- **GlanceSeg:** Hongyang Jiang, Mengdi Gao, Zirong Liu, Chen Tang, Xiaoqing Zhang, Shuai Jiang, Wu Yuan, Jiang Liu.<br />
  "GlanceSeg: Real-time microaneurysm lesion segmentation with gaze-map-guided foundation model for early detection of diabetic retinopathy." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.08075)] 
  [2023.11]

- **EviPrompt:** Yinsong Xu, Jiaqi Tang, Aidong Men, Qingchao Chen.<br />
  "EviPrompt: A Training-Free Evidential Prompt Generation Method for Segment Anything Model in Medical Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.06400)] 
  [2023.11]

- **FDNet:** Xiang Feng, Chengkai Wang, Chengyu Wu, Yunxiang Li, Yongbo He, Shuai Wang, Yaiqi Wang.<br />
  "FDNet: Feature Decoupled Segmentation Network for Tooth CBCT Image." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.06551)] 
  [2023.11]

- **GISCup23:** Xuanshu Luo, Paul Walther, Wejdene Mansour, Balthasar Teuscher, Johann Maximilian Zollner, Hao Li, Martin Werner.<br />
  "Exploring GeoAI Methods for Supraglacial Lake Mapping on Greenland Ice Sheet." ArXiv (2023).
  [[paper](https://www.bgd.ed.tum.de/pdf/2023_giscup_Luo.pdf)] 
  [[code](https://github.com/tum-bgd/GISCup23)]
  [2023.11]

- **u-LLaVA:** Jinjin Xu, Liwu Xu, Yuzhe Yang, Xiang Li, Yanchun Xie, Yi-Jie Huang, Yaqian Li.<br />
  "u-LLaVA: Unifying Multi-Modal Tasks via Large Language Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.05348)] 
  [2023.11]

- **LLaVA-Plus:** Shilong Liu, Hao Cheng, Haotian Liu, Hao Zhang, Feng Li, Tianhe Ren, Xueyan Zou, Jianwei Yang, Hang Su, Jun Zhu, Lei Zhang, Jianfeng Gao, Chunyuan Li.<br />
  "LLaVA-Plus: Learning to Use Tools for Creating Multimodal Agents." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.05437)] 
  [[code](https://llava-vl.github.io/llava-plus/)]
  [2023.11]

- **EVA-VOS:** Thanos Delatolas, Vicky Kalogeiton, Dim P. Papadopoulos.<br />
  "Learning the What and How of Annotation in Video Object Segmentation." WACV  (2023).
  [[paper](https://arxiv.org/abs/2311.04414)] 
  [[code](https://eva-vos.compute.dtu.dk/)]
  [2023.11]

- **NExT-Chat:** Ao Zhang, Liming Zhao, Chen-Wei Xie, Yun Zheng, Wei Ji, Tat-Seng Chua.<br />
  "NExT-Chat: An LMM for Chat, Detection and Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.04498)] 
  [[code](https://next-chatv.github.io)]
  [2023.11]


- **SAMVG:** Haokun Zhu, Juang Ian Chong, Teng Hu, Ran Yi, Yu-Kun Lai, Paul L. Rosin.<br />
  "SAMVG: A Multi-stage Image Vectorization Model with the Segment-Anything Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.05276)] 
  [2023.11]

- Danielle Ferreira, Rima Arnaout.<br />
  "Are foundation models efficient for medical image segmentation?" ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.04847)] 
  [[code](github.com/ArnaoutLabUCSF/CardioML)]
  [2023.11]

- **VFMV:** Kejun Wu, Qiong Liu, Kim-Hui Yap, and You Yang.<br />
  "High dimensional optical data — varifocal multiview imaging, compression and evaluation." Optics Express (2023).
  [[paper](https://opg.optica.org/oe/fulltext.cfm?uri=oe-31-24-39483&id=541443)] 
  [2023.11]

- **T-NT:** Zhenjun Yu, Wenqiang Xu, Siqiong Yao, Jieji Ren, Tutian Tang, Yutong Li, Guoying Gu, Cewu Lu.<br />
  "Precise Robotic Needle-Threading with Tactile Perception and Reinforcement Learning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.02396)] 
  [[code](https://sites.google.com/view/tac-needlethreading)]
  [2023.11]

- **GLaMM:** Hanoona Rasheed, Muhammad Maaz, Sahal Shaji, Abdelrahman Shaker, Salman Khan, Hisham Cholakkal, Rao M. Anwer, Erix Xing, Ming-Hsuan Yang, Fahad S. Khan.<br />
  "GLaMM: Pixel Grounding Large Multimodal Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.03356)] 
  [[code](https://mbzuai-oryx.github.io/groundingLMM)]
  [2023.11]

- **Masking:** Elias Arbash, Andréa de Lima Ribeiro, Sam Thiele, Nina Gnann, Behnood Rasti, Margret Fuchs, Pedram Ghamisi, Richard Gloaguen.<br />
  "Masking Hyperspectral Imaging Data with Pretrained Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.03053)] 
  [[code](https://github.com/hifexplo/Masking)]
  [2023.11]

- Yiran Li, Junpeng Wang, Prince Aboagye, Michael Yeh, Yan Zheng, Liang Wang, Wei Zhang, Kwan-Liu Ma.<br />
  "Visual Analytics for Efficient Image Exploration and User-Guided Image Captioning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.01016)] 
  [2023.11]

- **CSF:** Shichao Dong, Fayao Liu, Guosheng Lin.<br />
  "Leveraging Large-Scale Pretrained Vision Foundation Models for Label-Efficient 3D Point Cloud Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.01989)] 
  [2023.11]

- **RegionSpot:** Haosen Yang, Chuofan Ma, Bin Wen, Yi Jiang, Zehuan Yuan, Xiatian Zhu.<br />
  "Recognize Any Regions." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.01373)] 
  [[code](https://github.com/Surrey-UPLab/Recognize-Any-Regions)]
  [2023.11]

- **MSMedCap:** Gaoang Wang, Zhenyu Zhang, Benlu Wang, Weijie Liang, Yizhi Li, Xuechen Guo, Guanhong Wang, Shiyan Li.<br />
  "Sam-Guided Enhanced Fine-Grained Encoding with Mixed Semantic Learning for Medical Image Captioning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.01004)] 
  [2023.11]

- **MVS:** Mykhailo Shvets, Dongxu Zhao, Marc Niethammer, Roni Sengupta, Alexander C. Berg.<br />
  "Joint Depth Prediction and Semantic Segmentation with Multi-View SAM." WACV (2024).
  [[paper](https://arxiv.org/abs/2311.00134)] 
  [2023.11]

- **EditAnything:** Shanghua Gao, Zhijie Lin, Xingyu Xie, Pan Zhou, Ming-Ming Cheng, Shuicheng Yan.<br />
  "EditAnything: Empowering Unparalleled Flexibility in Image Editing and Generation." ACM  MM (2023).
  [[paper](https://dl.acm.org/doi/abs/10.1145/3581783.3612680)] 
  [[code](https://github.com/sail-sg/EditAnything)]
  [2023.10]

- **ImEW:** ImEW: A Framework for Editing Image in the Wild.<br />
  "Tasnim Mohiuddi, Tianyi Zhang, Maowen Nie, Jing Huang, Qianqian Chen, Wei Shi." LGM3A Workshop (2023).
  [[paper](https://dl.acm.org/doi/abs/10.1145/3607827.3616840)] 
  [2023.10]
  
- Fen Fang, Yi Cheng, Ying Sun, Qianli Xu.<br />
  "Team I2R-VI-FF Technical Report on EPIC-KITCHENS VISOR Hand Object Segmentation Challenge 2023." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.20120)] 
  [2023.10]

- **InsDet :** Qianqian Shen, Yunhan Zhao, Nahyun Kwon, Jeeeun Kim, Yanan Li, Shu Kong.<br />
  "A High-Resolution Dataset for Instance Detection with Multi-View Instance Capture." NeurIPS Datasets and Benchmarks Track (2023).
  [[paper](https://arxiv.org/abs/2310.19257)] 
  [[code](https://github.com/insdet/instance-detection)]
  [2023.10]

- Deepa Anand, Gurunath Reddy M, Vanika Singhal, Dattesh D. Shanbhag, Shriram KS, Uday Patil, Chitresh Bhushan, Kavitha Manickam, Dawei Gui, Rakesh Mullick, Avinash Gopal, Parminder Bhatia, Taha Kass-Hout.<br />
  "One-shot Localization and Segmentation of Medical Images with Foundation Models." NeurIPS Workshop (2023).
  [[paper](https://arxiv.org/abs/2310.18642)] 
  [2023.10]

- **AVIS :** Ruohao Guo, Yaru Chen, Yanyu Qi, Wenzhen Yue, Dantong Niu, Xianghua Ying.<br />
  "Audio-Visual Instance Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.18709)] 
  [2023.10]

- **ProMISe:** Hao Li, Han Liu, Dewei Hu, Jiacheng Wang, Ipek Oguz.<br />
  "Promise:Prompt-driven 3D Medical Image Segmentation Using Image Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.19721)] 
  [[code](https://github.com/MedICL-VU/ProMISe)]
  [2023.10]

- Joana Palés Huix, Adithya Raju Ganeshan, Johan Fredin Haslum, Magnus Söderberg, Christos Matsoukas, Kevin Smith.<br />
  "Are Natural Domain Foundation Models Useful for Medical Image Classification?." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.19522)] 
  [2023.10]

- **OBM:** Kai Li, Yupeng Deng, Yunlong Kong, Diyou Liu, Jingbo Chen, Yu Meng, Junxian Ma.<br />
  "Rebuild City Buildings from Off-Nadir Aerial Images with Offset-Building Model (OBM)." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.16717)] 
  [[code](https://github.com/likaiucas)]
  [2023.10]

- **TGVE:** Jay Zhangjie Wu, Xiuyu Li, Difei Gao, Zhen Dong, Jinbin Bai, Aishani Singh, Xiaoyu Xiang, Youzeng Li, Zuwei Huang, Yuanxi Sun, Rui He, Feng Hu, Junhua Hu, Hai Huang, Hanyu Zhu, Xu Cheng, Jie Tang, Mike Zheng Shou, Kurt Keutzer, Forrest Iandola.<br />
  "CVPR 2023 Text Guided Video Editing Competition." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.16003)] 
  [[code](https://sites.google.com/view/loveucvpr23/track4)]
  [2023.10]

- **ViewControl:** Jinbin Bai, Zhen Dong, Aosong Feng, Xiao Zhang, Tian Ye, Kaicheng Zhou, Mike Zheng Shou.<br />
  "Integrating View Conditions for Image Synthesis." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.16002)] 
  [2023.10]
  
- **SparseDFF:** Qianxu Wang, Haotong Zhang, Congyue Deng, Yang You, Hao Dong, Yixin Zhu, Leonidas Guibas.<br />
  "SparseDFF: Sparse-View Feature Distillation for One-Shot Dexterous Manipulation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.16838)] 
  [2023.10]

- **SAMPOT:** Rachana Sathish, Rahul Venkataramani, K S Shriram, Prasad Sudhakar.<br />
  "Task-driven Prompt Evolution for Foundation Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.17128)] 
  [2023.10]

- **SonoSAM:** Hariharan Ravishankar, Rohan Patil, Vikram Melapudi, Parminder Bhatia, Kass-Hout Taha, Pavan Annangi.<br />
  "SonoSAM -- Segment Anything on Ultrasound Images." ASMUS (2023).
  [[paper](https://arxiv.org/abs/2310.16872)] 
  [2023.10]

- Bertrand Chauveau, Pierre Merville.<br />
  "Segment Anything by Meta as a foundation model for image segmentation: a new era for histopathological images." Pathology (2023).
  [[paper](https://www.pathologyjournal.rcpa.edu.au/article/S0031-3025(23)00242-8/fulltext)] 
  [2023.10] 
 
- **MAFT:** Siyu Jiao, Yunchao Wei, Yaowei Wang, Yao Zhao, Humphrey Shi.<br />
  "Learning Mask-aware CLIP Representations for Zero-Shot Segmentation." NeurIPS (2023).
  [[paper](https://arxiv.org/pdf/2310.00240.pdf)] 
  [[code](https://github.com/jiaosiyu1999/MAFT.git)]
  [2023.10] 

- Ardiansyah Koeshidayatullah.<br />
  "Riding the Wave: One-Touch Automatic Salt Segmentation by Coupling SAM and SegGPT ." ArXiv (2023).
  [[paper](https://onepetro.org/SPEADIP/proceedings-abstract/23ADIP/2-23ADIP/534677)] 
  [2023.10] 

- **LuGSAM:** Dhanush Babu Ramesh, Rishika Iytha Sridhar, Pulakesh Upadhyaya and Rishikesan Kamaleswaran.<br />
  "Lung Grounded-SAM (LuGSAM): A Novel Framework for Integrating Text prompts to Segment Anything Model (SAM) for Segmentation Tasks of ICU Chest X-Rays." ArXiv (2023).
  [[paper](https://www.techrxiv.org/articles/preprint/Lung_Grounded-SAM_LuGSAM_A_Novel_Framework_for_Integrating_Text_prompts_to_Segment_Anything_Model_SAM_for_Segmentation_Tasks_of_ICU_Chest_X-Rays/24224761)] 
  [2023.10] 
  
- **Zero123++:** Ruoxi Shi, Hansheng Chen, Zhuoyang Zhang, Minghua Liu, Chao Xu, Xinyue Wei, Linghao Chen, Chong Zeng, Hao Su.<br />
  "Zero123++: a Single Image to Consistent Multi-view Diffusion Base Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.15110)] 
  [[code](https://github.com/SUDO-AI-3D/zero123plus)]
  [2023.10] 

- **CoralVOS:** Zheng Ziqiang, Xie Yaofeng, Liang Haixin, Yu Zhibin, Sai-Kit Yeung.<br />
  "CoralVOS: Dataset and Benchmark for Coral Video Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.01946)] 
  [2023.10]

- **ConceptFusion:** Krishna Murthy Jatavallabhula, Alihusein Kuwajerwala, Qiao Gu, Mohd Omama, Tao Chen, Alaa Maalouf, Shuang Li, Ganesh Iyer, Soroush Saryazdi, Nikhil Keetha, Ayush Tewari, Joshua B. Tenenbaum, Celso Miguel de Melo, Madhava Krishna, Liam Paull, Florian Shkurti, Antonio Torralba.<br />
  "ConceptFusion: Open-set Multimodal 3D Mapping." RSS (2023).
  [[paper](https://arxiv.org/abs/2302.07241)] 
  [[code](https://github.com/concept-fusion/concept-fusion)]
  [2023.10] 
  
- **CryoSegNet:** Rajan Gyawali, Ashwin Dhakal, Liguo Wang, Jianlin Cheng.<br />
  "Accurate cryo-EM protein particle picking by integrating the foundational AI image segmentation model and specialized U-Net." ArXiv (2023).
  [[paper](https://www.biorxiv.org/content/10.1101/2023.10.02.560572v1.abstract)] 
  [2023.10] 
  
- **CISRU:** Silvia Romero-Azpitartea, Cristina Lunaa, Alba Guerraa, Mercedes Alonsoa, Pablo Romeo Manriquea, Marina L. Seoanea, Daniel Olayoa, Almudena Morenoa, Pablo Castellanosa, Fernando Gandíaa, Gianfranco Visentinb.<br />
  "Enabling In-Situ Resources Utilisation by leveraging collaborative robotics and astronaut-robot interaction." IAC (2023).
  [[paper](https://www.researchgate.net/profile/Cristina-Luna-10/publication/374451757_Enabling_In-Situ_Resources_Utilisation_by_leveraging_collaborative_robotics_and_astronaut-robot_interaction/links/651eb2bdd717ef1293cedaa1/Enabling-In-Situ-Resources-Utilisation-by-leveraging-collaborative-robotics-and-astronaut-robot-interaction.pdf)] 
  [2023.10] 
  
- **DiffPrompter:** Sanket Kalwar, Mihir Ungarala, Shruti Jain, Aaron Monis, Krishna Reddy Konda, Sourav Garg, K Madhava Krishna.<br />
  "DiffPrompter: Differentiable Implicit Visual Prompts for Semantic-Segmentation in Adverse Conditions." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.04181)] 
  [[code](https://diffprompter.github.io/)]
  [2023.10] 

- Alessandro Saviolo, Pratyaksh Rao, Vivek Radhakrishnan, Jiuhong Xiao, Giuseppe Loianno.<br />
  "Unifying Foundation Models with Quadrotor Control for Visual Tracking Beyond Object Categories." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.04781)] 
  [2023.10] 

- Ruoqing Zhao, Xi Wang, Hongliang Dai, Pan Gao, Piji Li.<br />
  "Medical Report Generation Based on Segment-Enhanced Contrastive Representation Learning." NLPCC (2023).
  [[paper](https://link.springer.com/chapter/10.1007/978-3-031-44696-2_65)] 
  [2023.10] 

- Robin Karlsson, Francisco Lepe-Salazar, Kazuya Takeda.<br />
  "Compositional Semantics for Open Vocabulary Spatio-semantic Representations." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.04981)] 
  [2023.10] 
 
- **InstructDET :** Ronghao Dang, Jiangyan Feng, Haodong Zhang, Chongjian Ge, Lin Song, Lijun Gong, Chengju Liu, Qijun Chen, Feng Zhu, Rui Zhao, Yibing Song.<br />
  "InstructDET: Diversifying Referring Object Detection with Generalized Instructions." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.05136)] 
  [[code](https://github.com/jyFengGoGo/InstructDet)]
  [2023.10] 

- **HICOME:** Peng Zheng.<br />
  "Discriminative Consensus Mining with A Thousand Group for More Accurate Co-Salient Object Detection." ArXiv (2023).
  [[paper](https://aaltodoc.aalto.fi/handle/123456789/124134)] 
  [[code](https://github.com/ZhengPeng7/CoSINe)]
  [2023.10] 

- **Ferret:** Haoxuan You, Haotian Zhang, Zhe Gan, Xianzhi Du, Bowen Zhang, Zirui Wang, Liangliang Cao, Shih-Fu Chang, Yinfei Yang.<br />
  "." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.07704)] 
  [[code](https://github.com/apple/ml-ferret)]
  [2023.10] 

- **OVTracktor:** Wen-Hsuan Chu, Adam W. Harley, Pavel Tokmakov, Achal Dave, Leonidas Guibas, Katerina Fragkiadaki.<br />
  "Zero-Shot Open-Vocabulary Tracking with Large Pre-Trained Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.06992)] 
  [[code](https://wenhsuanchu.github.io/ovtracktor/)]
  [2023.10] 

- **OpenAnnotate3D:** Yijie Zhou, Likun Cai, Xianhui Cheng, Zhongxue Gan, Xiangyang Xue, Wenchao Ding.<br />
  "OpenAnnotate3D: Open-Vocabulary Auto-Labeling System for Multi-modal 3D Data." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.13398)] 
  [[code](https://github.com/Fudan-ProjectTitan/OpenAnnotate3D)]
  [2023.10] 

- **SSC:** Francisco Eiras, Kemal Oksuz, Adel Bibi, Philip H.S. Torr, Puneet K. Dokania.<br />
  "Segment, Select, Correct: A Framework for Weakly-Supervised Referring Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.13479)] 
  [[code](https://github.com/fgirbal/segment-select-correct)]
  [2023.10] 

- Shichang Liu, Junxin Chen, Ben-Guo He, Tao Chen, Gwanggil Jeon, Wei Wang.<br />
  "Adapting Segment Anything Model for Shield Tunnel Water Leakage Segmentation." AMC-SME Workshop (2023).
  [[paper](https://dl.acm.org/doi/abs/10.1145/3606042.3616453)] 
  [2023.10] 

- Sofia H. Gelado, César Quilodrán-Casas, Loïc Chagot.<br />
  "Enhancing Microdroplet Image Analysis with Deep Learning." Micromachines (2023).
  [[paper](https://www.mdpi.com/2072-666X/14/10/1964)] 
  [2023.10] 
  
- **EdgeCalib:** Xingchen Li, Yifan Duan, Beibei Wang, Haojie Ren, Guoliang You, Yu Sheng, Jianmin Ji, Yanyong Zhang.<br />
  "EdgeCalib: Multi-Frame Weighted Edge Features for Automatic Targetless LiDAR-Camera Calibration." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.16629)]
  [2023.10]   

- **Open-NeRF:** Hao Zhang, Fang Li, Narendra Ahuja.<br />
  "Open-NeRF: Towards Open Vocabulary NeRF Decomposition." WACV (2024).
  [[paper](https://arxiv.org/abs/2310.16383)] 
  [2023.10] 

- **SAM-CLIP:** Haoxiang Wang, Pavan Kumar Anasosalu Vasu, Fartash Faghri, Raviteja Vemulapalli, Mehrdad Farajtabar, Sachin Mehta, Mohammad Rastegari, Oncel Tuzel, Hadi Pouransari.<br />
  "SAM-CLIP: Merging Vision Foundation Models towards Semantic and Spatial Understanding." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.15308)] 
  [2023.10] 

- **SAM-Med3D:** Haoyu Wang, Sizheng Guo, Jin Ye, Zhongying Deng, Junlong Cheng, Tianbin Li, Jianpin Chen, Yanzhou Su, Ziyan Huang, Yiqing Shen, Bin Fu, Shaoting Zhang, Junjun He, Yu Qiao.<br />
  "SAM-Med3D." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.15161)] 
  [[code](https://github.com/uni-medical/SAM-Med3D)]
  [2023.10] 

- **SAMCLR:** Benjamin Missaoui, Chongbin Yuan.<br />
  "SAMCLR: Contrastive pre-training on complex scenes using SAM for view sampling." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.14736)] 
  [2023.10] 

- Zhaozheng Chen, Qianru Sun.<br />
  "Weakly-Supervised Semantic Segmentation with Image-Level Labels: from Traditional Models to Foundation Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.13026)] 
  [2023.10] 

- Sumit Pandey, Kuan-Fu Chen, Erik B. Dam.<br />
  "Comprehensive Multimodal Segmentation in Medical Imaging: Combining YOLOv8 with SAM and HQ-SAM Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.12995)] 
  [2023.10] 

- **Mammo-SAM:** Xinyu Xiong, Churan Wang, Wenxue Li, Guanbin Li.<br />
  "Mammo-SAM: Adapting Foundation Segment Anything Model for Automatic Breast Mass Segmentation in Whole Mammograms." ResearchGate (2023).
  [[paper](https://www.researchgate.net/publication/374739539_Mammo-SAM_Adapting_Foundation_Segment_Anything_Model_for_Automatic_Breast_Mass_Segmentation_in_Whole_Mammograms)] 
  [2023.10] 

- Dongshen Han, Sheng Zheng, Chaoning Zhang.<br />
  "Segment Anything Meets Universal Adversarial Perturbation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.12431)] 
  [2023.10] 

- **SoM-GPT4V:** Jianwei Yang, Hao Zhang, Feng Li, Xueyan Zou, Chunyuan Li, Jianfeng Gao.<br />
  "Set-of-Mark Prompting Unleashes Extraordinary Visual Grounding in GPT-4V." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.11441)] 
  [[homepage](https://som-gpt4v.github.io/)]
  [[code](https://github.com/microsoft/SoM)]
  [2023.10] 

- **IPSeg:** Lv Tang, Peng-Tao Jiang, Hao-Ke Xiao, Bo Li.<br />
  "Towards Training-free Open-world Segmentation via Image Prompting Foundation Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.10912)] 
  [2023.10] 

- **SAM_Interactive_Histopathology:** SeungKyu Kim, Hyun-Jic Oh, Seonghui Min, Won-Ki Jeong.<br />
  "Evaluation and improvement of Segment Anything Model for interactive histopathology image segmentation." MICCAI Workshop (2023).
  [[paper](https://arxiv.org/abs/2310.10493)] 
  [[code](https://github.com/hvcl/SAM_Interactive_Histopathology)]
  [2023.10] 

- Yao Qianxiang, Bin Jiang.<br />
  "Recursive Segmentation Living Image: An eXplainable AI (XAI) Approach for Computing Structural Beauty of Images or the Livingness of Space." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.10149)] 
  [2023.10] 

- Sheng Zheng, Chaoning Zhang.<br />
  "Black-box Targeted Adversarial Attack on Segment Anything (SAM)." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.10010)] 
  [2023.10] 

- Jiahao Xia, Gavin Gong 2, Jiawei Liu, Zhigang Zhu, Hao Tang.<br />
  "Segment Anything Model for Pedestrian Infrastructure Inventory: Assessing Zero-Shot Segmentation on Multi-Mode Geospatial Data." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.09918)] 
  [2023.10] 

- **PUCD :** Youngtack Oh, Minseok Seo, Doyi Ki, Junghoon Seo.<br />
  "Prototype-oriented Unsupervised Change Detection for Disaster Management." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.09759)] 
  [2023.10] 

- **SAM-guided UDA:** Xidong Peng, Runnan Chen, Feng Qiao, Lingdong Kong, Youquan Liu, Tai Wang, Xinge Zhu, Yuexin Ma.<br />
  "SAM-guided Unsupervised Domain Adaptation for 3D Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.08820)] 
  [2023.10] 

- **SemCom:** Avi Deb Raha, Md. Shirajum Munir, Apurba Adhikary, Yu Qiao, Choong Seon Hong.<br />
  "Generative AI-driven Semantic Communication Framework for NextG Wireless Network." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.09021)] 
  [2023.10] 

- Christian A. Schiller.<br />
  "Virtual Augmented Reality for Atari Reinforcement Learning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.08683)]
  [2023.10]   

- **MCREA:** Xu Chen, Yunde Jia, Yuwei Wu.<br />
  "Fine-Grained Annotation for Face Anti-Spoofing." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.08142)] 
  [2023.10] 

- **SAM-OCTA:** Xinrun Chen, Chengliang Wang, Haojian Ning, Shiying Li.<br />
  "SAM-OCTA: Prompting Segment-Anything for OCTA Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.07183)] 
  [[code](https://github.com/ShellRedia/SAM-OCTA)]
  [2023.10] 

- **MED:** Haijie Ren, Weiqiang Wang, Wentao Tang, Rui Zhang.<br />
  "Machine Eye for Defects: Machine Learning-Based Solution to Identify and Characterize Topological Defects in Textured Images of Nematic Materials." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.06406)] 
  [2023.10] 

- Mohammad Peivandi, Jason Zhang, Michael Lu, Dongxiao Zhu, Zhifeng Kou.<br />
  "Empirical Evaluation of the Segment Anything Model (SAM) for Brain Tumor Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.06162)] 
  [2023.10] 

- **Tree-GPT:** Siqi Du, Shengjun Tang, Weixi Wang, Xiaoming Li, Renzhong Guo.<br />
  "Tree-GPT: Modular Large Language Model Expert System for Forest Remote Sensing Image Understanding and Interactive Analysis." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.04698)] 
  [2023.10] 

- **TiC:** Song Zhang, Qingzhong Wang, Jiang Bian, Haoyi Xiong.<br />
  "TiC: Exploring Vision Transformer in Convolution." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.04134)] 
  [[code](https://github.com/zs670980918/MSA-Conv)]
  [2023.10] 

- **SLP:** David Balaban, Justin Medich, Pranay Gosar, Justin Hart.<br />
  "Propagating Semantic Labels in Video Data." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.00783)] 
  [[homepage](https://dataverse.tdl.org/dataverse/robotics)]
  [2023.10] 

- Amin Ranem, Niklas Babendererde, Moritz Fuchs, Anirban Mukhopadhyay.<br />
  "Exploring SAM Ablations for Enhancing Medical Segmentation in Radiology and Pathology." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.00504)] 
  [2023.10] 

- Xiangru Li, Yifei Zhang, Liang Zhao.<br />
  "Multi-Prompt Fine-Tuning of Foundation Models for Enhanced Medical Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.02381)] 
  [2023.10] 

- Ali Mayladan, Hasan Nasrallah, Hasan Moughnieh, Mustafa Shukor, Ali J. Ghandour.<br />
  "Zero-Shot Refinement of Buildings' Segmentation Models using SAM." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.01845)] 
  [2023.10] 

- **GroupPrompter:** Yichuang Luo, Fang Wang, Jing Xing, Xiaohu Liu.<br />
  "GroupPrompter: A Prompting Method for Semantic Segmentation Based on SAM." IEEE Access  (2023).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10265054)] 
  [2023.09] 
  
- **GAVS:** Yaoting Wang, Weisong Liu, Guangyao Li, Jian Ding, Di Hu, Xi Li.<br />
  "Prompting Segmentation with Sound is Generalizable Audio-Visual Source Localizer." AAAI (2024).
  [[paper](https://arxiv.org/abs/2309.07929)] 
  [2023.09] 

- Raha, Avi Deb and Adhikary, Apurba and Munir, Md. Shirajum and Qiao, Yu and Hong, Choong Seon.<br />
  "Segment Anything Model Aided Beam Prediction for the Millimeter Wave Communication." APNOMS (2023).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10258199)] 
  [2023.09]
  
- **PVLFF:** Haoran Chen, Kenneth Blomqvist, Francesco Milano, Roland Siegwart.<br />
  "Panoptic Vision-Language Feature Fields." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.05448)] 
  [[code](https://github.com/ethz-asl/autolabel)]
  [2023.09] 

- **SAMStyler:** Psychogyios, Konstantinos and Leligou, Helen C. and Melissari, Filisia and Bourou, Stavroula and Anastasakis, Zacharias and Zahariadis, Theodore.<br />
  "SAMStyler: Enhancing Visual Creativity With Neural Style Transfer and Segment Anything Model (SAM)." IEEE Access (2023).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10250775)]
  [2023.09]   
 
- Aneesh Rangnekar, Jue Jiang, Harini Veeraraghavan.<br />
  "3D Swin Transformer for Partial Medical Auto Segmentation." MICCAI-FLARE (2023).
  [[paper](https://openreview.net/forum?id=IlQQU5Pp5p)] 
  [2023.09] 

- **ASA:** Yaqin Li, Dandan Wang, Cao Yuan, Hao Li, Jing Hu.<br />
  "Enhancing Agricultural Image Segmentation with an Agricultural Segment Anything Model Adapter." Sensors (2023).
  [[paper](https://www.mdpi.com/1424-8220/23/18/7884)] 
  [2023.09] 



- **SCROD:** Valentyn Boreiko, Matthias Hein, Jan Hendrik Metzen.<br />
  "Identifying Systematic Errors in Object Detectors with the SCROD Pipeline." ICCV Workshop (2023).
  [[paper](https://openaccess.thecvf.com/content/ICCV2023W/BRAVO/html/Boreiko_Identifying_Systematic_Errors_in_Object_Detectors_with_the_SCROD_Pipeline_ICCVW_2023_paper.html)] 
  [2023.09] 

- Iraklis Giannakis, Anshuman Bhardwaj, Lydia Sam, Georgios Leontidis.<br />
  "A flexible deep learning crater detection scheme using Segment Anything Model (SAM)." ICARUS (2023).
  [[paper](https://www.sciencedirect.com/science/article/pii/S0019103523003755)] 
  [2023.09] 
  
- **SuPerPM:** Shan Lin, Albert J. Miao, Ali Alabiad, Fei Liu, Kaiyuan Wang, Jingpei Lu, Florian Richter, Michael C. Yip.<br />
  "SuPerPM: A Large Deformation-Robust Surgical Perception Framework Based on Deep Point Matching Learned from Physical Constrained Simulation Data" ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.13863)] 
  [2023.09] 
  
- **Bi-SAM:** Ying Zhao, Kechen Song, Wenqi Cui, Hang Ren, Yunhui Yan.<br />
  "MFS enhanced SAM: Achieving superior performance in bimodal few-shot segmentation." JVCIR (2023).
  [[paper](https://www.sciencedirect.com/science/article/pii/S1047320323001967)] 
  [[code](https://github.com/VDT-2048/Bi-SAM)]
  [2023.09] 

- **BaDLAD:** Kazi Reyazul Hasan, Mubasshira Musarrat, Sadif Ahmed, Shahriar Raj.<br />
  "Framework and Model Analysis on Bengali Document Layout Analysis Dataset: BaDLAD." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.16700)] 
  [2023.09] 

- **SAM-Adapter:** Tianrun Chen, Lanyun Zhu, Chaotao Deng, Runlong Cao, Yan Wang, Shangzhan Zhang, Zejian Li, Lingyun Sun, Ying Zang, Papa Mao.<br />
  "SAM-Adapter: Adapting Segment Anything in Underperformed Scenes." ICCV Workshop (2023).
  [[paper](https://openaccess.thecvf.com/content/ICCV2023W/VCL/html/Chen_SAM-Adapter_Adapting_Segment_Anything_in_Underperformed_Scenes_ICCVW_2023_paper.html)] 
  [[code](http://research.kokoni3d.com/sam-adapter)]
  [2023.09] 

- **UniQuadric:** Linghao Yang, Yanmin Wu, Yu Deng, Rui Tian, Xinggang Hu, Tiefeng Ma.<br />
  "UniQuadric: A SLAM Backend for Unknown Rigid Object 3D Tracking and Light-Weight Modeling." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.17036)] 
  [2023.09] 

- **SAMFeat:**  Jingqian Wu, Rongtao Xu, Zach Wood-Doughty, Changwei Wang.<br />
  "Segment Anything Model is a Good Teacher for Local Feature Learning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.16992)] 
  [[code](https://github.com/vignywang/SAMFeat)]
  [2023.09] 

- **nnSAM:** Yunxiang Li, Bowen Jing, Xiang Feng, Zihan Li, Yongbo He, Jing Wang, You Zhang.<br />
  "nnSAM: Plug-and-play Segment Anything Model Improves nnUNet Performance." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.16967)] 
  [[code](https://github.com/Kent0n-Li/Medical-Image-Segmentation)]
  [2023.09] 

- Mayara E. Bonani, Max Schwarz, Sven Behnke.<br />
  "Learning from SAM: Harnessing a Segmentation Foundation Model for Sim2Real Domain Adaptation through Regularization." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.15562)] 
  [2023.09] 


- Khoa Dang Nguyen, Thanh-Hai Phung, Hoang-Giang Cao.<br />
  "A SAM-based Solution for Hierarchical Panoptic Segmentation of Crops and Weeds Competition." ICCV Workshop (2023).
  [[paper](https://arxiv.org/abs/2309.13578)] 
  [2023.09] 
  
- **MediViSTA-SAM:** Sekeun Kim, Kyungsang Kim, Jiang Hu, Cheng Chen, Zhiliang Lyu, Ren Hui, Sunghwan Kim, Zhengliang Liu, Aoxiao Zhong, Xiang Li, Tianming Liu, Quanzheng Li.<br />
  "MediViSTA-SAM: Zero-shot Medical Video Analysis with Spatio-temporal SAM Adaptation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.13539)] 
  [[code](https://github.com/kimsekeun/MediViSTA-SAM)]
  [2023.09] 

- **PointSSC:** Yuxiang Yan, Boda Liu, Jianfei Ai, Qinbu Li, Ru Wan, Jian Pu.<br />
  "PointSSC: A Cooperative Vehicle-Infrastructure Point Cloud Benchmark for Semantic Scene Completion." ICRA (2024).
  [[paper](https://arxiv.org/abs/2309.12708)] 
  [2023.09] 
  
- **NOC:** Xiaobao Wei, Renrui Zhang, Jiarui Wu, Jiaming Liu, Ming Lu, Yandong Guo, Shanghang Zhang.<br />
  "NOC: High-Quality Neural Object Cloning with 3D Lifting of Segment Anything." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.12790)] 
  [2023.09] 
  
- **SAM-OCTA:** Chengliang Wang, Xinrun Chen, Haojian Ning, Shiying Li.<br />
  "SAM-OCTA: A Fine-Tuning Strategy for Applying Foundation Model to OCTA Image Segmentation Tasks." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.11758)] 
  [[code](https://github.com/ShellRedia/SAM-OCTA)]
  [2023.09] 

- **MoPA:**  Haozhi Cao, Yuecong Xu, Jianfei Yang, Pengyu Yin, Shenghai Yuan, Lihua Xie.<br />
  "MoPA: Multi-Modal Prior Aided Domain Adaptation for 3D Semantic Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.11839)] 
  [[code](https://github.com/AronCao49/MoPA)]
  [2023.09] 

- **Deshadow-Anything:** Xiao Feng Zhang, Tian Yi Song, Jia Wei Yao.<br />
  "Deshadow-Anything: When Segment Anything Model Meets Zero-shot shadow removal." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.11715)] 
  [2023.09] 

- **3D-U-SAM:** Yifu Zhang, Zuozhu Liu, Yang Feng, Renjing Xu.<br />
  "3D-U-SAM Network For Few-shot Tooth Segmentation in CBCT Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.11015)] 
  [2023.09] 

- **OCTA-FRNet:** Haojian Ning, Chengliang Wang, Xinrun Chen, Shiying Li.<br />
  "An Accurate and Efficient Neural Network for OCTA Vessel Segmentation and a New Dataset." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.09483)] 
  [[code](https://github.com/nhjydywd/OCTA-FRNet)]
  [2023.09] 

- **MA-SAM:** Cheng Chen, Juzheng Miao, Dufan Wu, Zhiling Yan, Sekeun Kim, Jiang Hu, Aoxiao Zhong, Zhengliang Liu, Lichao Sun, Xiang Li, Tianming Liu, Pheng-Ann Heng, Quanzheng Li.<br />
  "MA-SAM: Modality-agnostic SAM Adaptation for 3D Medical Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.08842)] 
  [[code](https://github.com/cchen-cc/MA-SAM)]
  [2023.09] 

- **samgeo:** Qiusheng Wu and Lucas Prado Osco.<br />
  "samgeo: A Python package for segmenting geospatial data with the Segment Anything Model (SAM)." JOSS (2023).
  [[paper](https://joss.theoj.org/papers/10.21105/joss.05663)] 
  [[code](https://github.com/opengeos/segment-geospatial)]
  [2023.09] 

- Peng Zhang, Yaping Wang.<br />
  "Segment Anything Model for Brain Tumor Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.08434)] 
  [2023.09] 


- **SAMUS:** Xian Lin, Yangyang Xiang, Li Zhang, Xin Yang, Zengqiang Yan, Li Yu.<br />
  "SAMUS: Adapting Segment Anything Model for Clinically-Friendly and Generalizable Ultrasound Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.06824)] 
  [[code](https://github.com/xianlin7/SAMUS)]
  [2023.09] 
  
- **CMSF:** Swapnil Bhosale, Haosen Yang, Diptesh Kanojia, Xiatian Zhu.<br />
  "Leveraging Foundation models for Unsupervised Audio-Visual Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.06728)] 
  [2023.09] 

- Xiaodan Xing, Chunling Tang, Yunzhe Guo, Nicholas Kurniawan, Guang Yang.<br />
  "SegmentAnything helps microscopy images based automatic and quantitative organoid detection and analysis." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.04190)] 
  [2023.09]

- Chenbin Liu, Zhengliang Liu, Jason Holmes, Lu Zhang, Lian Zhang, Yuzhen Ding, Peng Shu, Zihao Wu, Haixing Dai, Yiwei Li, Dinggang Shen, Ninghao Liu, Quanzheng Li, Xiang Li, Dajiang Zhu, Tianming Liu, Wei Liu.<br />
  "Artificial General Intelligence for Radiation Oncology." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.02590)] 
  [2023.09]

- **DEVA:** Ho Kei Cheng, Seoung Wug Oh, Brian Price, Alexander Schwing, Joon-Young Lee.<br />
  "Tracking Anything with Decoupled Video Segmentation." ICCV (2023).
  [[paper](https://arxiv.org/abs/2309.03903)] 
  [[project page](https://hkchengrex.com/Tracking-Anything-with-DEVA/)]
  [[code](https://github.com/hkchengrex/Tracking-Anything-with-DEVA)]
  [2023.09] 

- **SAM3D:** Nhat-Tan Bui, Dinh-Hieu Hoang, Minh-Triet Tran, Ngan Le.<br />
  "SAM3D: Segment Anything Model in Volumetric Medical Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.03493)] 
  [2023.09] 

- **CropFormer:** Lu Qi, Jason Kuen, Weidong Guo, Tiancheng Shen, Jiuxiang Gu, Jiaya Jia, Zhe Lin, Ming-Hsuan Yang.<br />
  "High-Quality Entity Segmentation." ICCV (2023).
  [[paper](https://openaccess.thecvf.com/content/ICCV2023/html/Qi_High_Quality_Entity_Segmentation_ICCV_2023_paper.html)] 
  [[project page](https://github.com/qqlu/Entity/tree/main/Entityv2)]
  [[code](https://github.com/qqlu/Entity/blob/main/Entityv2/README.md)]
  [[中文解读](https://mp.weixin.qq.com/s/wa_AfAM4xRb1tX3vyU7a6w)]
  [2023.09] 

- **CIP-WPIS:** Qingtao Yu, Heming Du, Chen Liu, Xin Yu.<br />
  "When 3D Bounding-Box Meets SAM: Point Cloud Instance Segmentation with Weak-and-Noisy Supervision." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.00828)] 
  [2023.09] 

- **SAM-Deblur:** Siwei Li, Mingxuan Liu, Yating Zhang, Shu Chen, Haoxiang Li, Hong Chen, Zifei Dou.<br />
  "SAM-Deblur: Let Segment Anything Boost Image Deblurring." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.02270)] 
  [[code](https://github.com/HPLQAQ/SAM-Deblur)]
  [2023.09] 

- Hassan El-Hajj, Matteo Valleriani.<br />
  "Prompt me a Dataset: An investigation of text-image prompting for historical image dataset creation using foundation models." ICIAP  (2023), AI4DH workshop.
  [[paper](https://arxiv.org/abs/2309.01674)] 
  [2023.09] 

- **SAM-CD:** Lei Ding, Kun Zhu, Daifeng Peng, Hao Tang, Haitao Guo.<br />
  "Adapting Segment Anything Model for Change Detection in HR Remote Sensing Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.01429)] 
  [2023.09] 

- **SAM-LIV:** Junyao Shi, Jianing Qian, Yecheng Jason Ma, Dinesh Jayaraman.<br />
  "Plug-And-Play Object-Centric Representations From “What” and “Where” Foundation Models." ArXiv (2023).
  [[paper](https://mit-spark.github.io/robotRepresentations-RSS2023/assets/papers/17.pdf)]
  [2023.08]   

- **UGainS:** Alexey Nekrasov, Alexander Hermans, Lars Kuhnert, Bastian Leibe.<br />
  "UGainS: Uncertainty Guided Anomaly Instance Segmentation." GCPR (2023).
  [[paper](https://arxiv.org/abs/2308.02046)] 
  [[code](https://vision.rwth-aachen.de/ugains)]
  [2023.08] 
  
- Chaoqin Huang, Aofan Jiang, Ya Zhang, Yanfeng Wang.<br />
  "Multi-Scale Memory Comparison for Zero-/Few-Shot Anomaly Detection." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.04789)] 
  [2023.08] 

- Dwith Chenna, Suyash Bhogawar.<br />
  "Segment Anything Model (SAM) For Brain Extraction in fMRI Studies." IJAIMED (2023).
  [[paper](https://www.researchgate.net/profile/Yn-Dwith-Chenna/publication/373013991_Segment_Anything_Model_SAM_For_Brain_Extraction_in_fMRI_Studies/links/64d40025c80b930269fb88cb/Segment-Anything-Model-SAM-For-Brain-Extraction-in-fMRI-Studies.pdf)] 
  [2023.08] 

- **OSTRA :** Jiexiong Xu, Weikun Zhao, Zhiyan Tang, Xiangchao Gan.<br />
  "A One Stop 3D Target Reconstruction and multilevel Segmentation Method." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.06974)] 
  [[code](https://github.com/ganlab/OSTRA)]
  [2023.08] 

- **ROSGPT_Vision:** Bilel Benjdira, Anis Koubaa, Anas M. Ali.<br />
  "ROSGPT_Vision: Commanding Robots Using Only Language Models' Prompts." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.11236)] 
  [[code](https://github.com/bilel-bj/ROSGPT_Vision)]
  [2023.08] 

- **CoDeF:** Hao Ouyang, Qiuyu Wang, Yuxi Xiao, Qingyan Bai, Juntao Zhang, Kecheng Zheng, Xiaowei Zhou, Qifeng Chen, Yujun Shen.<br />
  "CoDeF: Content Deformation Fields for Temporally Consistent Video Processing." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.07926)] 
  [[code](https://qiuyu96.github.io/CoDeF/)]
  [2023.08] 

- **WALL-E:** Tianyu Wang, Yifan Li, Haitao Lin, Xiangyang Xue, Yanwei Fu.<br />
  "WALL-E: Embodied Robotic WAiter Load Lifting with Large Language Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.15962)] 
  [[code](https://star-uu-wang.github.io/WALL-E/)]
  [2023.08] 

- **Ref-Diff:** Minheng Ni, Yabo Zhang, Kailai Feng, Xiaoming Li, Yiwen Guo, Wangmeng Zuo.<br />
  "Ref-Diff: Zero-shot Referring Image Segmentation with Generative Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.16777)] 
  [[code](https://github.com/kodenii/Ref-Diff)]
  [2023.08] 

- Anwai Archit, Sushmita Nair, Nabeel Khalid, Paul Hilt, Vikas Rajashekar, Marei Freitag, Sagnik Gupta, Andreas Dengel, Sheraz Ahmed, Constantin Pape.<br />
  "Segment Anything for Microscopy." ResearchGate (2023).
  [[paper](https://www.biorxiv.org/content/10.1101/2023.08.21.554208v1.full.pdf)] 
  [2023.08] 
  

- Su Myat Noe.<br />
  "Efficient Segment-Anything Model for Automatic Mask Region Extraction in Livestock Monitoring." IEEE ICCT(2023).
  [[paper](https://www.researchgate.net/publication/373265261_Efficient_Segment-Anything_Model_for_Automatic_Mask_Region_Extraction_in_Livestock_Monitoring)] 
  [2023.08] 

- **SSM-SAM:** Yiming Zhang, Tianang Leng, Kun Han, Xiaohui Xie.<br />
  "Self-Sampling Meta SAM: Enhancing Few-shot Medical Image Segmentation with Meta-Learning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.16466)] 
  [2023.08] 

- **SAM-Med2D:** Junlong Cheng, Jin Ye, Zhongying Deng, Jianpin Chen, Tianbin Li, Haoyu Wang, Yanzhou Su, Ziyan Huang, Jilong Chen, Lei Jiang, Hui Sun, Junjun He, Shaoting Zhang, Min Zhu, Yu Qiao.<br />
  "SAM-Med2D." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.16184)] 
  [[code](https://github.com/uni-medical/SAM-Med2D)]
  [2023.08] 

- **AutoSAM Adapter:** Chengyin Li, Prashant Khanduri, Yao Qiang, Rafi Ibn Sultan, Indrin Chetty, Dongxiao Zhu.<br />
  "Auto-Prompting SAM for Mobile Friendly 3D Medical Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.14936)] 
  [2023.08] 

- Leo Fillioux, Emilie Gontran, Jérôme Cartry, Jacques RR Mathieu, Sabrina Bedja, Alice Boilève, Paul-Henry Cournède, Fanny Jaulin, Stergios Christodoulidis, Maria Vakalopoulou.<br />
  "Spatio-Temporal Analysis of Patient-Derived Organoid Videos Using Deep Learning for the Prediction of Drug Efficacy." ICCV Workshop (2023).
  [[paper](https://arxiv.org/abs/2308.14461)] 
  [2023.08] 

- **SAM-PARSER:** Zelin Peng, Zhengqin Xu, Zhilin Zeng, Xiaokang Yang, Wei Shen.<br />
  "SAM-PARSER: Fine-tuning SAM Efficiently by Parameter Space Reconstruction." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.14604)] 
  [2023.08] 

- Weijia Feng, Lingting Zhu, Lequan Yu.<br />
  "Cheap Lunch for Medical Image Segmentation by Fine-tuning SAM on Few Exemplars." MICCAI BrainLes Workshop (2023).
  [[paper](https://arxiv.org/abs/2308.14133)] 
  [2023.08] 
 

- Zihan Dong, ZhengDong Zhang.<br />
  "Enhancing Bloodstain Analysis Through AI-Based Segmentation: Leveraging Segment Anything Model for Crime Scene Investigation." KDD Workshop (2023).
  [[paper](https://arxiv.org/abs/2308.13979)] 
  [[code](https://github.com/Zdong104/Bloodstain_Analysis_Ai_Tool)]
  [2023.08] 

- **SCESAME:** Hiroaki Yamagiwa, Yusuke Takase, Hiroyuki Kambe, Ryosuke Nakamoto.<br />
  "Zero-Shot Edge Detection With SCESAME: Spectral Clustering-Based Ensemble for Segment Anything Model Estimation." WACV Workshop (2024).
  [[arXiv](https://arxiv.org/abs/2308.13779)]
  [[paper](https://openaccess.thecvf.com/content/WACV2024W/Pretrain/html/Yamagiwa_Zero-Shot_Edge_Detection_With_SCESAME_Spectral_Clustering-Based_Ensemble_for_Segment_WACVW_2024_paper.html)]
  [[code](https://github.com/ymgw55/SCESAME)]
  [2023.08] 

- **SamDSK:** Yizhe Zhang, Tao Zhou, Shuo Wang, Ye Wu, Pengfei Gu, Danny Z. Chen.<br />
  "SamDSK: Combining Segment Anything Model with Domain-Specific Knowledge for Semi-Supervised Learning in Medical Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.13759)] 
  [[code](https://github.com/yizhezhang2000/SamDSK)]
  [2023.08] 

- **RSISeg:** Zhe Wang, Shoukun Sun, Xiang Que, Xiaogang Ma.<br />
  "Interactive segmentation in aerial images: a new benchmark and an open access web-based tool." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.13174)] 
  [2023.08] 


- **DiffSeg:** Junjiao Tian, Lavisha Aggarwal, Andrea Colaco, Zsolt Kira, Mar Gonzalez-Franco.<br />
  "Diffuse, Attend, and Segment: Unsupervised Zero-Shot Segmentation using Stable Diffusion." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.12469)] 
  [2023.08]

- **SPPNet:** Qing Xu, Wenwei Kuang, Zeyu Zhang, Xueyao Bao, Haoran Chen, Wenting Duan.<br />
  "SPPNet: A Single-Point Prompt Network for Nuclei Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.12231)] 
  [[code](https://github.com/xq141839/SPPNet)]
  [2023.08]

- **SAMSNeRF:** Ange Lou, Yamin Li, Xing Yao, Yike Zhang, Jack Noble.<br />
  "SAMSNeRF: Segment Anything Model (SAM) Guides Dynamic Surgical Scene Reconstruction by Neural Radiance Field (NeRF)." Image-Guided Procedures, Robotic Interventions, and Modeling (2024).
  [[paper](https://arxiv.org/abs/2308.11774)] 
  [[code](https://github.com/AngeLouCN/SAMSNeRF)]
  [2023.08]

- **SS2V:** Xing Yao, Han Liu, Dewei Hu, Daiwei Lu, Ange Lou, Hao Li, Ruining Deng, Gabriel Arenas, Baris Oguz, Nadav Schwartz, Brett C Byram, Ipek Oguz.<br />
  "False Negative/Positive Control for SAM on Noisy Medical Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.10382)] 
  [[code](https://github.com/xyimaging/FNPC)]
  [2023.08]

- **SurgicalSAM:** Wenxi Yue, Jing Zhang, Kun Hu, Yong Xia, Jiebo Luo, Zhiyong Wang.<br />
  "SurgicalSAM: Efficient Class Promptable Surgical Instrument Segmentation." AAAI (2024).
  [[paper](https://arxiv.org/abs/2308.08746)] 
  [[code](https://github.com/wenxi-yue/SurgicalSAM)]
  [2023.08]

- **SAMedOCT:** Botond Fazekas, José Morano, Dmitrii Lachinov, Guilherme Aresta, Hrvoje Bogunović.<br />
  "SAMedOCT: Adapting Segment Anything Model (SAM) for Retinal OCT." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.09331)] 
  [2023.08]

- **U-SAM:** Hantao Zhang, Weidong Guo, Chenyang Qiu, Shouhong Wan, Bingbing Zou, Wanqin Wang, Peiquan Jin.<br />
  "CARE: A Large Scale CT Image Dataset and Clinical Applicable Benchmark Model for Rectal Cancer Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.08283)] 
  [2023.08]

- **Few-Shot-Self-Prompt-SAM:** Qi Wu, Yuyao Zhang, Marawan Elbatel.<br />
  "Self-Prompting Large Vision Models for Few-Shot Medical Image Segmentation." MICCAI DART Workshop (2023).
  [[paper](https://arxiv.org/abs/2308.07624)] 
  [[code](https://github.com/PeterYYZhang/few-shot-self-prompt-SAM)]
  [2023.08]

- **Dancing Avatar:** Bosheng Qin, Wentao Ye, Qifan Yu, Siliang Tang, Yueting Zhuang.<br />
  "Dancing Avatar: Pose and Text-Guided Human Motion Videos Synthesis with Image Diffusion Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.07749)] 
  [2023.08]

- **SurgicalSAM:** An Wang, Mobarakol Islam, Mengya Xu, Yang Zhang, Hongliang Ren.<br />
  "SAM Meets Robotic Surgery: An Empirical Study on Generalization, Robustness and Adaptation." MICCAI MedAGI Workshop (2023).
  [[paper](https://arxiv.org/abs/2308.07156)] 
  [2023.08]

- **OSTRA:** Jiexiong Xu, Weikun Zhao, Zhiyan Tang, Xiangchao Gan.<br />
  "A One Stop 3D Target Reconstruction and multilevel Segmentation Method." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.06974)] 
  [[code](https://github.com/ganlab/OSTRA)]
  [2023.08]

- **CEmb-SAM:** Dongik Shin, Beomsuk Kim, Seungjun Baek.<br />
  "CEmb-SAM: Segment Anything Model with Condition Embedding for Joint Learning from Heterogeneous Datasets." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.06957)] 
  [2023.08]

- **CLE Diffusion:** Yuyang Yin, Dejia Xu, Chuangchuang Tan, Ping Liu, Yao Zhao, Yunchao Wei.<br />
  "CLE Diffusion: Controllable Light Enhancement Diffusion Model." ACM MM (2023).
  [[paper](https://arxiv.org/abs/2308.06725)] 
  [[code](https://yuyangyin.github.io/CLEDiffusion/)]
  [2023.08]

- **Polyp-SAM++:** Risab Biswas.<br />
  "Polyp-SAM++: Can A Text Guided SAM Perform Better for Polyp Segmentation?" ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.06623)] 
  [[code](https://github.com/RisabBiswas/Polyp-SAM++)]
  [2023.08]

- **TongueSAM:** Shan Cao, Qunsheng Ruan, Qingfeng Wu.<br />
  "TongueSAM: An Universal Tongue Segmentation Model Based on SAM with Zero-Shot." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.06444)] 
  [[code](https://github.com/cshan-github/TongueSAM)]
  [2023.08]

- **FoodSAM:** Xing Lan, Jiayi Lyu, Hanyu Jiang, Kun Dong, Zehai Niu, Yi Zhang, Jian Xue.<br />
  "FoodSAM: Any Food Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.05938)] 
  [[code](https://github.com/jamesjg/FoodSAM)]
  [2023.08]

- **SAM-L:** Xueyuan Li, Ruining Deng, Yucheng Tang, Shunxing Bao, Haichun Yang, Yuankai Huo.<br />
  "Leverage Weakly Annotation to Pixel-wise Annotation via Zero-shot Segment Anything Model for Molecular-empowered Learning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.05785)] 
  [2023.08]

- **FAn:** Alaa Maalouf, Ninad Jadhav, Krishna Murthy Jatavallabhula, Makram Chahine, Daniel M. Vogt, Robert J. Wood, Antonio Torralba, Daniela Rus.<br />
  "Follow Anything: Open-set detection, tracking, and following in real-time." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.05737)] 
  [[code](https://github.com/alaamaalouf/FollowAnything)]
  [[demo](https://www.youtube.com/watch?v=6Mgt3EPytrw)]
  [2023.08]

- **SSOM:** Ruikai Cui, Siyuan He, Shi Qiu.<br />
  "Adaptive Low Rank Adaptation of Segment Anything to Salient Object Detection." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.05426)] 
  [2023.08]

- **AquaSAM:** Muduo Xu, Jianhao Su, Yutao Liu.<br />
  "AquaSAM: Underwater Image Foreground Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.04218)] 
  [2023.08]

- **AdaptiveSAM:** Jay N. Paranjape, Nithin Gopalakrishnan Nair, Shameema Sikder, S. Swaroop Vedula, Vishal M. Patel.<br />
  "AdaptiveSAM: Towards Efficient Tuning of SAM for Surgical Scene Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.03726)] 
  [[code](https://github.com/JayParanjape/biastuning)]
  [2023.08]

- Ziyi Huang, Hongshan Liu, Haofeng Zhang, Fuyong Xing, Andrew Laine, Elsa Angelini, Christine Hendon, Yu Gan.<br />
  "Push the Boundary of SAM: A Pseudo-label Correction Framework for Medical Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.00883)] 
  [2023.08]

- Cheng-Yu Hsieh, Si-An Chen, Chun-Liang Li, Yasuhisa Fujii, Alexander Ratner, Chen-Yu Lee, Ranjay Krishna, Tomas Pfister.<br />
  "Tool Documentation Enables Zero-Shot Tool-Usage with Large Language Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.00675)] 
  [2023.08]

- **DEFT:** Aditya Kannan.<br />
  "Learning from Human Videos for Robotic Manipulation." ArXiv (2023).
  [[paper](http://reports-archive.adm.cs.cmu.edu/anon/anon/usr/ftp/2023/CMU-CS-23-124.pdf)] 
  [[code](https://github.com/adityak77/masters-thesis)]
  [2023.07] 

- **FOCUS :** Stefano Ferraro, Pietro Mazzaglia, Tim Verbelen, Bart Dhoedt.<br />
  "FOCUS: Object-Centric World Models for Robotics Manipulation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.02427)] 
  [[code](https://focus-manipulation.github.io/)]
  [2023.07] 

- **DisCo:** Tan Wang, Linjie Li, Kevin Lin, Yuanhao Zhai, Chung-Ching Lin, Zhengyuan Yang, Hanwang Zhang, Zicheng Liu, Lijuan Wang.<br />
  "DisCo: Disentangled Control for Realistic Human Dance Generation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.00040)] 
  [[code](https://disco-dance.github.io/)]
  [2023.07] 
  
- Vaibhav Vavilala, David Forsyth.<br />
  "Applying a Color Palette with Local Control using Diffusion Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.02698)] 
  [2023.07] 
  
- **SegAnimeChara:** Andy Yu-Hsiang Tseng, Wen-Fan Wang, Bing-Yu Chen.<br />
  "SegAnimeChara: Segmenting Anime Characters Generated by AI." ACM  SIGGRAPH (2023).
  [[paper](https://dl.acm.org/doi/abs/10.1145/3588028.3603685)] 
  [2023.07] 
 
- **TASS:** Mengqi He, Jing Zhang, Zhaoyuan Yang, Mingyi He, Nick Barnes, Yuchao Dai.<br />
  "Transferable Attack for Semantic Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.16572)] 
  [[code](https://github.com/anucvers/TASS)]
  [2023.07] 

- **SAM zero-shot segmentator:** Loris Nanni, Carlo Fantozzi, Alberto Pretto , Daniel Fusaro.<br />
  "Improving Existing Segmentators Performance with Zero-Shot Segmentators." ArXiv (2023).
  [[paper](https://www.preprints.org/manuscript/202307.1729/v1)] 
  [2023.07]
  
- **SAMFlow:** Shili Zhou, Ruian He, Weimin Tan, Bo Yan.<br />
  "SAMFlow: Eliminating Any Fragmentation in Optical Flow with Segment Anything Model." AAAI (2024).
  [[paper](https://arxiv.org/abs/2307.16586)] 
  [2023.07]

- **HQTrack:** Jiawen Zhu, Zhenyu Chen, Zeqi Hao, Shijie Chang, Lu Zhang, Dong Wang, Huchuan Lu, Bin Luo, Jun-Yan He, Jin-Peng Lan, Hanyuan Chen, Chenyang Li.<br />
  "Tracking Anything in High Quality." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.13974)] 
  [[code](https://github.com/jiawen-zhu/HQTrack)]
  [2023.07]

- **Fashion Matrix:** Zheng Chong, Xujie Zhang, Fuwei Zhao, Zhenyu Xie, Xiaodan Liang.<br />
  "Fashion Matrix: Editing Photos by Just Talking." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.13240)] 
  [[homepage](https://zheng-chong.github.io/FashionMatrix/)]
  [[code](https://github.com/Zheng-Chong/FashionMatric)]
  [2023.07]

- **RoboChop:** Atharva Dikshit, Alison Bartsch, Abraham George, Amir Barati Farimani.<br />
  "RoboChop: Autonomous Framework for Fruit and Vegetable Chopping Leveraging Foundational Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.13159)] 
  [2023.07]

- **Industrial-SA:** Keno Moenck, Arne Wendt, Philipp Prünte, Julian Koch, Arne Sahrhage, Johann Gierecker, Ole Schmedemann, Falko Kähler, Dirk Holst, Martin Gomse, Thorsten Schüppstuhl, Daniel Schoepflin.<br />
  "Industrial Segment Anything -- a Case Study in Aircraft Manufacturing, Intralogistics, Maintenance, Repair, and Overhaul." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.12674)] 
  [2023.07]


- **CNOS:** Van Nguyen Nguyen, Tomas Hodan, Georgy Ponimatkin, Thibault Groueix, Vincent Lepetit.<br />
  "CNOS: A Strong Baseline for CAD-based Novel Object Segmentation." ICCV Workshop (2023).
  [[paper](https://arxiv.org/abs/2307.11067)] 
  [[code](https://github.com/nv-nguyen/cnos)]
  [2023.07]

- **SAM-Path:** Jingwei Zhang, Ke Ma, Saarthak Kapse, Joel Saltz, Maria Vakalopoulou, Prateek Prasanna, Dimitris Samaras.<br />
  "SAM-Path: A Segment Anything Model for Semantic Segmentation in Digital Pathology." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.09570)] 
  [2023.07]

- **BuboGPT:** Yang Zhao, Zhijie Lin, Daquan Zhou, Zilong Huang, Jiashi Feng, Bingyi Kang.<br />
  "BuboGPT: Enabling Visual Grounding in Multi-Modal LLMs." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.08581)] 
  [[code](https://bubo-gpt.github.io)]
  [2023.07]

- **OpenSU:** Ruiping Liu, Jiaming Zhang, Kunyu Peng, Junwei Zheng, Ke Cao, Yufan Chen, Kailun Yang, Rainer Stiefelhagen.<br />
  "Open Scene Understanding: Grounded Situation Recognition Meets Segment Anything for Helping People with Visual Impairments." ICCV Workshop (2023).
  [[paper](https://arxiv.org/abs/2307.07757)] 
  [[code](https://github.com/RuipingL/OpenSU)]
  [2023.07]

- **OG:** Zichao Dong, Hang Ji, Weikun Zhang, Xufeng Huang, Junbo Chen.<br />
  "OG: Equip vision occupancy with instance segmentation and visual grounding." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.05873)] 
  [2023.07]

- **$SAM^{Med}$:** Chenglong Wang, Dexuan Li, Sucheng Wang, Chengxiu Zhang, Yida Wang, Yun Liu, Guang Yang.<br />
  $SAM^{Med}$: A medical image annotation framework based on large vision model. ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.05617)] 
  [2023.07]

- **SAM-U:** Guoyao Deng, Ke Zou, Kai Ren, Meng Wang, Xuedong Yuan, Sancong Ying, Huazhu Fu.<br />
  "SAM-U: Multi-box prompts triggered uncertainty estimation for reliable SAM in medical image." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.04973)] 
  [2023.07]

- **Semantic-SAM:** Feng Li, Hao Zhang, Peize Sun, Xueyan Zou, Shilong Liu, Jianwei Yang, Chunyuan Li, Lei Zhang, Jianfeng Gao.<br />
  "Semantic-SAM: Segment and Recognize Anything at Any Granularity." ECCV (2024).
  [[paper](https://arxiv.org/abs/2307.04767)] 
  [[code](https://github.com/UX-Decoder/Semantic-SAM)]
  [2023.07]

- **SAM-IQA:** Xinpeng Li, Ting Jiang, Haoqiang Fan, Shuaicheng Liu.<br />
  "SAM-IQA: Can Segment Anything Boost Image Quality Assessment?." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.04455)] 
  [[code](https://github.com/Hedlen/SAM-IQA)]
  [2023.07]

- **Cross-SAM:** Xiaoyu Bai, Fan Bai, Xiaofei Huo, Jia Ge, Tony C. W. Mok, Zi Li, Minfeng Xu, Jingren Zhou, Le Lu, Dakai Jin, Xianghua Ye, Jingjing Lu, Ke Yan.<br />
  "Matching in the Wild: Learning Anatomical Embeddings for Multi-Modality Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.03535)] 
  [2023.07]

- **LAM-SC:** Feibo Jiang, Yubo Peng, Li Dong, Kezhi Wang, Kun Yang, Cunhua Pan, Xiaohu You.<br />
  "Large AI Model-Based Semantic Communications." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.03492)] 
  [2023.07]

- **MSDeAOT:** Yuanyou Xu, Jiahao Li, Zongxin Yang, Yi Yang, Yueting Zhuang.<br />
  "ZJU ReLER Submission for EPIC-KITCHEN Challenge 2023: TREK-150 Single Object Tracking." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.02508)] 
  [2023.07]

- **EM-SAM:** Ao Cheng, Guoqiang Zhao, Lirong Wang, Ruobing Zhang.<br />
  "AxonCallosumEM Dataset: Axon Semantic Segmentation of Whole Corpus Callosum cross section from EM Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.02464)] 
  [2023.07]

- **SAM-PT:** Frano Rajič, Lei Ke, Yu-Wing Tai, Chi-Keung Tang, Martin Danelljan, Fisher Yu.<br />
  "Segment Anything Meets Point Tracking." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.01197)] 
  [[code](https://github.com/SysCV/sam-pt)]
  [2023.07]

- **SAMAug:** Haixing Dai, Chong Ma, Zhengliang Liu, Yiwei Li, Peng Shu, Xiaozheng Wei, Lin Zhao, Zihao Wu, Dajiang Zhu, Wei Liu, Quanzheng Li, Tianming Liu, Xiang Li.<br />
  "SAMAug: Point Prompt Augmentation for Segment Anything Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.01187)] 
  [2023.07]

- **SAM-DA:** Liangliang Yao, Haobo Zuo, Guangze Zheng, Changhong Fu, Jia Pan.<br />
  "SAM-DA: UAV Tracks Anything at Night with SAM-Powered Domain Adaptation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.01024)] 
  [[code](https://github.com/vision4robotics/SAM-DA)]
  [2023.07]

- **RefSAM:** Yonglin Li, Jing Zhang, Xiao Teng, Long Lan, Xinwang Liu.<br />
  "RefSAM: Efficiently Adapting Segmenting Anything Model for Referring Video Object Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.00997)] 
  [[code](https://github.com/LancasterLi/RefSAM)]
  [2023.07]

- **All-in-SAM:** Can Cui, Ruining Deng, Quan Liu, Tianyuan Yao, Shunxing Bao, Lucas W. Remedios, Yucheng Tang, Yuankai Huo.<br />
  "All-in-SAM: from Weak Annotation to Pixel-wise Nuclei Segmentation with Prompt-based Finetuning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.00290)] 
  [2023.07]
  
- Zenglin Shi, Ying Sun, Mengmi Zhang.<br />
  "Training-free Object Counting with Prompts." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.00038)] 
  [[code](https://github.com/shizenglin/training-free-object-counter)]
  [2023.07]

- Xiaoyu Shi, Shurong Chai, Yinhao Li, Jingliang Cheng, Jie Bai, Guohua Zhao, Yen-Wei Chen.<br />
  "Cross-modality Attention Adapter: A Glioma Segmentation Fine-tuning Method for SAM Using Multimodal Brain MR Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.01124)] 
  [2023.07]

- **TDA:** Ruben Glatt, Shusen Liu.<br />
  "Topological Data Analysis Guided Segment Anything Model Prompt Optimization for Zero-Shot Segmentation in Biological Imaging." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.17400)] 
  [2023.06]
 
- Xavier F. Cadet, Ranya Aloufi, Alain Miranville, Sara Ahmadi-Abhari, Hamed Haddadi.<br />
  "Evaluating The Robustness of Self-Supervised Representations to Background/Foreground Removal." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.01398)] 
  [2023.06]
  
- **3D Shape Match:** Ahmed Abdelreheem, Abdelrahman Eldesokey, Maks Ovsjanikov, Peter Wonka.<br />
  "Zero-Shot 3D Shape Correspondence." SIGGRAPH ASIA (2023).
  [[paper](https://arxiv.org/abs/2306.03253)] 
  [[code](https://samir55.github.io/3dshapematch/)]
  [2023.06]

- Siddharth Shankar, Leigh A. Stearns, Cornelis J. van der Veen.<br />
  "Segment Anything in Glaciology: An initial study implementing the Segment Anything Model (SAM)." ArXiv (2023).
  [[paper](https://www.researchsquare.com/article/rs-3011246/v1)] 
  [2023.06]

- Xiang Li, Lu Zhang, Zihao Wu, Zhengliang Liu, Lin Zhao, Yixuan Yuan, Jun Liu, Gang Li, Dajiang Zhu, Pingkun Yan, Quanzheng Li, Wei Liu, Tianming Liu, Dinggang Shen.<br />
  "Artificial General Intelligence for Medical Imaging." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.05480)] 
  [2023.06]
 
- **ViDA:** Jiaming Liu, Senqiao Yang, Peidong Jia, Renrui Zhang, Ming Lu, Yandong Guo, Wei Xue, Shanghang Zhang.<br />
  "ViDA: Homeostatic Visual Domain Adapter for Continual Test Time Adaptation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.04344)] 
  [[code](https://github.com/Yangsenqiao/vida)]
  [2023.06]

- **FGVP:** Lingfeng Yang, Yueze Wang, Xiang Li, Xinlong Wang, Jian Yang.<br />
  "Fine-Grained Visual Prompting." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.04356)]
  [2023.06]  

- **AssistGPT:** Difei Gao, Lei Ji, Luowei Zhou, Kevin Qinghong Lin, Joya Chen, Zihan Fan, Mike Zheng Shou.<br />
  "AssistGPT: A General Multi-modal Assistant that can Plan, Execute, Inspect, and Learn." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.08640)] 
  [[code](https://showlab.github.io/assistgpt/)]
  [2023.06]

- Matthew Baugh, James Batten, Johanna P. Müller, Bernhard Kainz.<br />
  "Zero-Shot Anomaly Detection with Pre-trained Segmentation Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.09269)] 
  [2023.06]

- Guochen Ning, Hanyin Liang, Zhongliang Jiang, Hui Zhang, Hongen Liao.<br />
  "The potential of 'Segment Anything' (SAM) for universal intelligent ultrasound image guidance." BioScience Trends (2023).
  [[paper](https://www.jstage.jst.go.jp/article/bst/advpub/0/advpub_2023.01119/_article/-char/ja/)] 
  [2023.06] 
  
- **SeaDronesSee-3D and BOArienT:** Benjamin Kiefer, Timon Höfer, Andreas Zell.<br />
  "Stable Yaw Estimation of Boats from the Viewpoint of UAVs and USVs." ECMR  (2023).
  [[paper](https://arxiv.org/abs/2306.14056)] 
  [2023.06] 

- **DADF:** Yingxin Lai, Zhiming Luo, Zitong Yu.<br />
  "Detect Any Deepfakes: Segment Anything Meets Face Forgery Detection and Localization." Chinese Conference on Biometric Recognition (2023).
  [[paper](https://arxiv.org/abs/2306.17075)] 
  [[code](https://github.com/laiyingxin2/DADF)]
  [2023.06]

- Lucas Prado Osco, Qiusheng Wu, Eduardo Lopes de Lemos, Wesley Nunes Gonçalves, Ana Paula Marques Ramos, Jonathan Li, José Marcato Junior.<br />
  "The Segment Anything Model (SAM) for Remote Sensing Applications: From Zero to One Shot." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.16623)] 
  [2023.06]

- **RSPrompter:** Keyan Chen, Chenyang Liu, Hao Chen, Haotian Zhang, Wenyuan Li, Zhengxia Zou, Zhenwei Shi.<br />
  "RSPrompter: Learning to Prompt for Remote Sensing Instance Segmentation based on Visual Foundation Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.16269)] 
  [[code](https://kyanchen.github.io/RSPrompter)]
  [2023.06]

- Zhewei Chen, Wai Keung Wong, Zuofeng Zhong, Jinpiao Liao, Ying Qu.<br />
  "Effective Transfer of Pretrained Large Visual Model for Fabric Defect Segmentation via Specifc Knowledge Injection." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.16186)] 
  [2023.06]

- Zheyan Jin, Shiqi Chen, Yueting Chen, Zhihai Xu, Huajun Feng.<br />
  "Let Segment Anything Help Image Dehaze." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.15870)] 
  [2023.06]

- **CLIP-SAM:** Evan Kellener, Ihina Nath, An Ngo, Thomas Nguyen, Joshua Schuman, Coen Adler, Arnav Kartikeya.<br />
  "Utilizing Segment Anything Model For Assessing Localization of GRAD-CAM in Medical Imaging." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.15692)] 
  [2023.06]
 
- **MESS:** Benedikt Blumenstiel, Johannes Jakubik, Hilde Kühne, Michael Vössing.<br />
  "What a MESS: Multi-Domain Evaluation of Zero-Shot Semantic Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.15521)] 
  [[code](https://github.com/blumenstiel/MESS)]
  [2023.06]

- **MMPM:** Jiange Yang, Wenhui Tan, Chuhao Jin, Bei Liu, Jianlong Fu, Ruihua Song, Limin Wang.<br />
  "Pave the Way to Grasp Anything: Transferring Foundation Models for Universal Pick-Place Robots." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.05716)] 
  [[YouTube](https://www.youtube.com/watch?v=1m9wNzfp_4E)]
  [[Bilibili](https://www.bilibili.com/video/BV178411Z7H2/)]
  [2023.06]

- **CellViT:** Fabian Hörst, Moritz Rempe, Lukas Heine, Constantin Seibold, Julius Keyl, Giulia Baldini, Selma Ugurel, Jens Siveke, Barbara Grünwald, Jan Egger, Jens Kleesiek.<br />
  "CellViT: Vision Transformers for Precise Cell Segmentation and Classification." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.15350)] 
  [[code](https://github.com/TIO-IKIM/CellViT)]
  [2023.06]

- **MedLSAM:** Wenhui Lei, Xu Wei, Xiaofan Zhang, Kang Li, Shaoting Zhang.<br />
  "MedLSAM: Localize and Segment Anything Model for 3D Medical Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.14752)] 
  [[code](https://github.com/openmedlab/MedLSAM)]
  [2023.06]

- **MobileSAM:** Chaoning Zhang, Dongshen Han, Yu Qiao, Jung Uk Kim, Sung-Ho Bae, Seungkyu Lee, Choong Seon Hong.<br />
  "Faster Segment Anything: Towards Lightweight SAM for Mobile Applications." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.14289)] 
  [[code](https://github.com/ChaoningZhang/MobileSAM)]
  [2023.06]

- **SonarSAM:** Lin Wang, Xiufen Ye, Liqiang Zhu, Weijie Wu, Jianguo Zhang, Huiming Xing, Chao Hu.<br />
  "When SAM Meets Sonar Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.14109)] 
  [[code](https://github.com/wangsssky/SonarSAM)]
  [2023.06]

- **AutoSAM:** Xinrong Hu, Xiaowei Xu, Yiyu Shi.<br />
  "How to Efficiently Adapt Large Segmentation Model(SAM) to Medical Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.13731)] 
  [[code](https://github.com/xhu248/AutoSAM)]
  [2023.06]

- **3DSAM-adapter:** Shizhan Gong, Yuan Zhong, Wenao Ma, Jinpeng Li, Zhao Wang, Jingyang Zhang, Pheng-Ann Heng, Qi Dou.<br />
  "3DSAM-adapter: Holistic Adaptation of SAM from 2D to 3D for Promptable Medical Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.13465)] 
  [[code](https://github.com/med-air/3DSAM-adapter)]
  [2023.06]

- Xinru Shan, Chaoning Zhang.<br />
  "Robustness of Segment Anything Model (SAM) for Autonomous Driving in Adverse Weather Conditions." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.13290)] 
  [2023.06]

- **SAM-LST:** Shurong Chai, Rahul Kumar Jain, Shiyu Teng, Jiaqing Liu, Yinhao Li, Tomoko Tateyama, Yen-wei Chen.<br />
  "Ladder Fine-tuning approach for SAM integrating complementary network." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.12737)] 
  [[code](https://github.com/11yxk/SAM-LST)]
  [2023.06]

- Mohsen Ahmadi, Masoumeh Farhadi Nia, Sara Asgarian, Kasra Danesh, Elyas Irankhah, Ahmad Gholizadeh Lonbar, Abbas Sharifi.<br />
  "Comparative Analysis of Segment Anything Model and U-Net for Breast Tumor Detection in Ultrasound and Mammography Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.12510)] 
  [2023.06]

- **FastSAM:** Xu Zhao, Wenchao Ding, Yongqi An, Yinglong Du, Tao Yu, Min Li, Ming Tang, Jinqiao Wang.<br />
  "Fast Segment Anything." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.12156)] 
  [[code](https://github.com/CASIA-IVA-Lab/FastSAM)]
  [2023.06]

- **Seal:** Youquan Liu, Lingdong Kong, Jun Cen, Runnan Chen, Wenwei Zhang, Liang Pan, Kai Chen, Ziwei Liu.<br />
  "Segment Any Point Cloud Sequences by Distilling Vision Foundation Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.09347)] 
  [[code](https://github.com/youquanl/Segment-Any-Point-Cloud)]
  [[homepage](https://ldkong.com/Seal)]
  [2023.06]

- Lian Zhang, Zhengliang Liu, Lu Zhang, Zihao Wu, Xiaowei Yu, Jason Holmes, Hongying Feng, Haixing Dai, Xiang Li, Quanzheng Li, Dajiang Zhu, Tianming Liu, Wei Liu.<br />
  "Segment Anything Model (SAM) for Radiation Oncology." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.11730)] 
  [2023.06]

- **Enlighten-Anything:** Qihan Zhao, Xiaofeng Zhang, Hao Tang, Chaochen Gu, Shanying Zhu.<br />
  "Enlighten-anything:When Segment Anything Model Meets Low-light Image Enhancement." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.10286)] 
  [[code](https://github.com/zhangbaijin/enlighten-anything)]
  [2023.06]

- **SAA+:** Yunkang Cao, Xiaohao Xu, Chen Sun, Yuqi Cheng, Liang Gao, Weiming Shen.<br />
  "Winning Solution for the CVPR2023 Visual Anomaly and Novelty Detection Challenge: Multimodal Prompting for Data-centric Anomaly Detection." CVPR2023 Workshop.
  [[paper](https://arxiv.org/abs/2306.09067)] 
  [[code](https://github.com/caoyunkang/Segment-Any-Anomaly)]
  [2023.06]

- **TEPO:** Chuyun Shen, Wenhao Li, Ya Zhang, Xiangfeng Wang.<br />
  "Temporally-Extended Prompts Optimization for SAM in Interactive Medical Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.08958)]
  [2023.06]  

- **TomoSAM:** Federico Semeraro, Alexandre Quintart, Sergio Fraile Izquierdo, Joseph C. Ferguson.<br />
  "TomoSAM: a 3D Slicer extension using SAM for tomography segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.08609)] 
  [[code](https://github.com/fsemerar/SlicerTomoSAM)]
  [2023.06]
  
- Madeline Chantry Schiappa, Sachidanand VS, Yunhao Ge, Ondrej Miksik, Yogesh S. Rawat, Vibhav Vineet.<br />
  "Robustness Analysis on Foundational Segmentation Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.09278)] 
  [[code](https://tinyurl.com/fm-robust)]
  [2023.06]

- Yu Qiao, Chaoning Zhang, Taegoo Kang, Donghun Kim, Shehbaz Tariq, Chenshuang Zhang, Choong Seon Hong.<br />
  "Robustness of SAM: Segment Anything Under Corruptions and Beyond." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.07713)] 
  [2023.06]

- **AutoSAM:** Tal Shaharabany, Aviad Dahan, Raja Giryes, Lior Wolf.<br />
  "AutoSAM: Adapting SAM to Medical Images by Overloading the Prompt Encoder." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.06370)]
  [2023.06]  
 
- **SAM-shadow:** Xiaofeng Zhang, Chaochen Gu, Shanying Zhu.<br />
  "SAM-helps-Shadow:When Segment Anything Model meet shadow removal." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.06113)] 
  [[code]( https://github.com/zhangbaijin/SAM-helps-Shadow)]
  [2023.06]

- Chaoning Zhang, Sheng Zheng, Chenghao Li, Yu Qiao, Taegoo Kang, Xinru Shan, Chenshuang Zhang, Caiyan Qin, Francois Rameau, Sung-Ho Bae, Choong Seon Hong.<br />
  "A Survey on Segment Anything Model (SAM): Vision Foundation Model Meets Prompt Engineering." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.06211)]
  [2023.06]

- **MAM:** Jiachen Li, Jitesh Jain, Humphrey Shi.<br />
  "Matting Anything." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.05399)] 
  [[code](https://chrisjuniorli.github.io/project/Matting-Anything/)]
  [2023.06]

-  Haochen Xue, Mingyu Jin, Chong Zhang, Yuxuan Huang, Qian Weng, Xiaobo Jin.<br />
  "Automatic Image Blending Algorithm Based on SAM and DINO." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.05382)] 
  [2023.06]

- **MatAny:** Jingfeng Yao, Xinggang Wang, Lang Ye, Wenyu Liu.<br />
  "Matte Anything: Interactive Natural Image Matting with Segment Anything Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.04121)] 
  [[code](https://github.com/hustvl/Matte-Anything)]
  [2023.06]

- **CNS:** Runnan Chen, Youquan Liu, Lingdong Kong, Nenglun Chen, Xinge Zhu, Yuexin Ma, Tongliang Liu, Wenping Wang.<br />
  "Towards Label-free Scene Understanding by Vision Foundation Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.03899)] 
  [[code](https://github.com/runnanchen/Label-Free-Scene-Understanding)]
  [2023.06]

- **SAM3D:** Yunhan Yang, Xiaoyang Wu, Tong He, Hengshuang Zhao, Xihui Liu.<br />
  "SAM3D: Segment Anything in 3D Scenes." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.03908)] 
  [[code](https://github.com/Pointcept/SegmentAnything3D)]
  [2023.06]

- **Calib-Anything:** Zhaotong Luo, Guohang Yan, Yikang Li.<br />
  " Calib-Anything: Zero-training LiDAR-Camera Extrinsic Calibration Method Using Segment Anything." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.02656)] 
  [[code](https://github.com/OpenCalib/CalibAnything)]
  [2023.06]

-  Shijie Chang, Zeqi Hao, Ben Kang, Xiaoqi Zhao, Jiawen Zhu, Zhenyu Chen, Lihe Zhang, Lu Zhang, Huchuan Lu.<br />
  " 3rd Place Solution for PVUW2023 VSS Track: A Large Model for Semantic Segmentation on VSPW." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.02291)] 
  [2023.06]

- **USD:** Yulin He, Wei Chen, Yusong Tan, Siqi Wang.<br />
  " USD: Unknown Sensitive Detector Empowered by Decoupled Objectness and Segment Anything Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.02275)] 
  [2023.06]

- **SAM3D:** Dingyuan Zhang, Dingkang Liang, Hongcheng Yang, Zhikang Zou, Xiaoqing Ye, Zhe Liu, Xiang Bai.<br />
  "SAM3D: Zero-Shot 3D Object Detection via Segment Anything Model." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2306.02245)] 
  [[code]( https://github.com/DYZhang09/SAM3D)]
  [2023.06]

-  Shehbaz Tariq, Brian Estadimas Arfeto, Chaoning Zhang, Hyundong Shin.<br />
  "Segment Anything Meets Semantic Communication." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.02094)] 
  [2023.06]

- **HQ-SAM:** Lei Ke, Mingqiao Ye, Martin Danelljan, Yifan Liu, Yu-Wing Tai, Chi-Keung Tang, Fisher Yu.<br />
  "Segment Anything in High Quality." NeurIPS (2023).
  [[paper](https://arxiv.org/abs/2306.01567)] 
  [[code](https://github.com/SysCV/SAM-HQ)]
  [2023.06]

- **DeSAM:** Yifan Gao, Wei Xia, Dingdu Hu, Xin Gao.<br />
  "DeSAM: Decoupling Segment Anything Model for Generalizable Medical Image Segmentation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2306.00499)] 
  [[code]( https://github.com/yifangao112/DeSAM)]
  [2023.06]
  
- **SAM-Track:** Yangming Cheng, Liulei Li, Yuanyou Xu, Xiaodi Li, Zongxin Yang, Wenguan Wang, Yi Yang.<br />
  "Segment and Track Anything." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.06558)] 
  [[code](https://github.com/z-x-yang/Segment-and-Track-Anything)]
  [2023.05]

- **SAMText:** Haibin He, Jing Zhang, Mengyang Xu, Juhua Liu, Bo Du, Dacheng Tao.<br />
  "Scalable Mask Annotation for Video Text Spotting." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.01443)] 
  [[code](https://github.com/ViTAE-Transformer/SAMText)]
  [2023.05] 

- **NP-SAM:** Rasmus Larsen, Torben L. Villadsen, Jette K. Mathiesen, Kirsten M. Ø. Jensen, Espen D. Bøjesen.<br />
  "NP-SAM: Implementing the Segment Anything Model for Easy Nanoparticle Segmentation in Electron Microscopy Images." ArXiv (2023).
  [[paper](https://chemrxiv.org/engage/chemrxiv/article-details/6463c10aa32ceeff2dc08c49)] 
  [[code](https://gitlab.au.dk/disorder/np-sam.git)]
  [2023.05]

- **EfficientViT:** Han Cai, Junyan Li, Muyan Hu, Chuang Gan, Song Han.<br />
  "EfficientViT: Multi-Scale Linear Attention for High-Resolution Dense Prediction." ICCV (2023).
  [[paper](https://arxiv.org/abs/2205.14756)] 
  [[code](https://github.com/mit-han-lab/efficientvit)]
  [2023.05] 

- **POPE:** Zhiwen Fan, Panwang Pan, Peihao Wang, Yifan Jiang, Dejia Xu, Hanwen Jiang, Zhangyang Wang.<br />
  "POPE: 6-DoF Promptable Pose Estimation of Any Object, in Any Scene, with One Reference." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.15727)] 
  [[code](https://paulpanwang.github.io/POPE/)]
  [2023.05]

- **Bridge3D:** Zhimin Chen, Bing Li.<br />
  "Bridging the Domain Gap: Self-Supervised 3D Scene Understanding with Foundation Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.08776)] 
  [2023.05]

- **Make-A-Protagonist:** Yuyang Zhao, Enze Xie, Lanqing Hong, Zhenguo Li, Gim Hee Lee.<br />
  "Make-A-Protagonist: Generic Video Editing with An Ensemble of Experts." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.08850)] 
  [[code](https://make-a-protagonist.github.io/)]
  [2023.05]
  
- **ZeroPose:** Jianqiu Chen, Mingshan Sun, Tianpeng Bao, Rui Zhao, Liwei Wu, Zhenyu He.<br />
  "ZeroPose: CAD-Model-based Zero-Shot Pose Estimation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.17934)] 
  [2023.05]
 
- **IIR-Net:** Zhongping Zhang, Jian Zheng, Jacob Zhiyuan Fang, Bryan A. Plummer.<br />
  "Text-to-image Editing by Image Information Removal." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.17489)] 
  [2023.05]

- Chaoning Zhang, Yu Qiao, Shehbaz Tariq, Sheng Zheng, Chenshuang Zhang, Chenghao Li, Hyundong Shin, Choong Seon Hong.<br />
  "Understanding segment anything model: Sam is biased towards texture rather than shape." ArXiv (2023).
  [[paper](https://www.researchgate.net/profile/Yu-Qiao-52/publication/371070480_Understanding_Segment_Anything_Model_SAM_is_Biased_Towards_Texture_Rather_than_Shape/links/6470de25a25e543829cedeee/Understanding-Segment-Anything-Model-SAM-is-Biased-Towards-Texture-Rather-than-Shape.pdf)] 
  [2023.05] 
 
- **FineRewards:** Guian Fang, Zutao Jiang, Jianhua Han, Guangsong Lu, Hang Xu, Xiaodan Liang.<br />
  "Boosting Text-to-Image Diffusion Models with Fine-Grained Semantic Rewards." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.19599)] 
  [[code](https://github.com/Enderfga/FineRewards)]
  [2023.05]

- **InstructEdit:** Qian Wang, Biao Zhang, Michael Birsak, Peter Wonka.<br />
  "InstructEdit: Improving Automatic Masks for Diffusion-based Image Editing With User Instructions." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.18047)] 
  [[code]( https://github.com/QianWangX/InstructEdit)]
  [2023.05]

- **AIMS:** Lu Qi, Jason Kuen, Weidong Guo, Jiuxiang Gu, Zhe Lin, Bo Du, Yu Xu, Ming-Hsuan Yang.<br />
  "AIMS: All-Inclusive Multi-Level Segmentation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.17768)] 
  [[code](https://github.com/dvlab-research/Entity)]
  [2023.05]

- **ShadowSAM:** Yonghui Wang, Wengang Zhou, Yunyao Mao, Houqiang Li.<br />
  "Detect Any Shadow: Segment Anything for Video Shadow Detection." TCSVT (2023).
  [[paper]( https://arxiv.org/abs/2305.16698)] 
  [[code](https://github.com/harrytea/Detect-AnyShadow)]
  [2023.05]

- **ISA-NeRF:** Xiaokang Chen, Jiaxiang Tang, Diwen Wan, Jingbo Wang, Gang Zeng.<br />
  "Interactive Segment Anything NeRF with Feature Imitation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.16233)] 
  [[homepage]( https://me.kiui.moe/san/)]
  [2023.05]

- Yihao Huang, Yue Cao, Tianlin Li, Felix Juefei-Xu, Di Lin, Ivor W. Tsang, Yang Liu, Qing Guo.<br />
  "On the Robustness of Segment Anything." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.16220)] 
  [2023.05]

- **SAMScore:** Yunxiang Li, Meixu Chen, Wenxuan Yang, Kai Wang, Jun Ma, Alan C. Bovik, You Zhang.<br />
  "SAMScore: A Semantic Structural Similarity Metric for Image Translation Evaluation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.15367)] 
  [[code]( https://github.com/Kent0n-Li/SAMScore)]
  [2023.05]

- **SAD:** Jun Cen, Yizheng Wu, Kewei Wang, Xingyi Li, Jingkang Yang, Yixuan Pei, Lingdong Kong, Ziwei Liu, Qifeng Chen.<br />
  "SAD: Segment Any RGBD." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.14207)] 
  [[code](https://github.com/Jun-CEN/SegmentAnyRGBD)]
  [2023.05]

- **SPT:** Zeyu Xiao, Jiawang Bai, Zhihe Lu, Zhiwei Xiong.<br />
  "A Dive into SAM Prior in Image Restoration." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.13620)] 
  [2023.05]

- **Matcher:** Yang Liu, Muzhi Zhu, Hengtao Li, Hao Chen, Xinlong Wang, Chunhua Shen.<br />
  "Matcher: Segment Anything with One Shot Using All-Purpose Feature Matching." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.13310)] 
  [[code](https://github.com/aim-uofa/Matcher)]
  [2023.05]

- **RAP:** Jiaxi Jiang, Christian Holz.<br />
  "Restore Anything Pipeline: Segment Anything Meets Image Restoration." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.13093)] 
  [[code](https://github.com/eth-siplab/RAP)]
  [2023.05]

- **UVOSAM:** Zhenghao Zhang, Zhichao Wei, Shengfan Zhang, Zuozhuo Dai, Siyu Zhu.<br />
  "UVOSAM: A Mask-free Paradigm for Unsupervised Video Object Segmentation via Segment Anything Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.12659)] 
  [2023.05]

- **BreastSAM:** Mingzhe Hu, Yuheng Li, Xiaofeng Yang.<br />
  "BreastSAM: A Study of Segment Anything Model for Breast Tumor Detection in Ultrasound Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.12447)] 
  [2023.05]

- **SAMSh:** Leiping Jie, Hui Zhang.<br />
  "When SAM Meets Shadow Detection." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.11513)] 
  [[code](https://github.com/LeipingJie/SAMSh)]
  [2023.05]

- **Instruct2Act:** Siyuan Huang, Zhengkai Jiang, Hao Dong, Yu Qiao, Peng Gao, Hongsheng Li.<br />
  "Instruct2Act: Mapping Multi-modality Instructions to Robotic Actions with Large Language Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.11176)] 
  [[code](https://github.com/OpenGVLab/Instruct2Act)]
  [2023.05]

- **WS-SAM:** Chunming He, Kai Li, Yachao Zhang, Guoxia Xu, Longxiang Tang, Yulun Zhang, Zhenhua Guo, Xiu Li.<br />
  "Weakly-Supervised Concealed Object Segmentation with SAM-based Pseudo Labeling and Multi-scale Feature Grouping." NeurIPS (2023).
  [[paper](https://arxiv.org/abs/2305.11003)] 
  [2023.05]

- **SAA+:** Yunkang Cao, Xiaohao Xu, Chen Sun, Yuqi Cheng, Zongwei Du, Liang Gao, Weiming Shen.<br />
  "Segment Any Anomaly without Training via Hybrid Prompt Regularization." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.10724)] 
  [[code](https://github.com/caoyunkang/Segment-Any-Anomaly)]
  [2023.05]

- **OR-NeRF:** Youtan Yin, Zhoujie Fu, Fan Yang, Guosheng Lin.<br />
  "OR-NeRF: Object Removing from 3D Scenes Guided by Multiview Segmentation with Neural Radiance Fields." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.10503)] 
  [2023.05]

- **PromptUNet:** Junde Wu.<br />
  "PromptUNet: Toward Interactive Medical Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.10300)] 
  [[code](https://github.com/WuJunde/PromptUNet)]
  [2023.05]

- **EAC:** Ao Sun, Pingchuan Ma, Yuanyuan Yuan, Shuai Wang.<br />
  "Explain Any Concept: Segment Anything Meets Concept-Based Explanation." NeurIPS (2023).
  [[paper](https://arxiv.org/abs/2305.10289)] 
  [2023.05]
  
- Xiao Yang, Haixing Dai, Zihao Wu, Ramesh Bist, Sachin Subedi, Jin Sun, Guoyu Lu, Changying Li, Tianming Liu, Lilong Chai.<br />
  "SAM for Poultry Science." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.10254)] 
  [2023.05]

- **Leaf Only SAM:** Dominic Williams, Fraser MacFarlane, Avril Britten.<br />
  "Leaf Only SAM: A Segment Anything Pipeline for Zero-Shot Automated Leaf Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.09418)] 
  [2023.05]
  
- **KD-SAM:** Sahib Julka, Michael Granitzer.<br />
  "Knowledge distillation with Segment Anything (SAM) model for Planetary Geological Mapping." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.07586)] 
  [2023.05]
  
- **SAM-Track:** Yangming Cheng, Liulei Li, Yuanyou Xu, Xiaodi Li, Zongxin Yang, Wenguan Wang, Yi Yang.<br />
  "Segment-and-Track Anything." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.06558)] 
  [[code](https://github.com/z-x-yang/Segment-and-Track-Anything)]
  [2023.05]
  
- **SEEM:** Zhihe Lu, Zeyu Xiao, Jiawang Bai, Zhiwei Xiong, Xinchao Wang.<br />
  "Can SAM Boost Video Super-Resolution?" ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.06524)] 
  [2023.05]
	
-  Yuqing Wang, Yun Zhao, Linda Petzold.<br />
  "An Empirical Study on the Robustness of the Segment Anything Model (SAM)." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.06422)] 
  [2023.05]
  
- **SAM-WSSS:** Tianle Chen, Zheda Mai, Ruiwen Li, Wei-lun Chao.<br />
  "Segment Anything Model (SAM) Enhanced Pseudo Labels for Weakly Supervised Semantic Segmentation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.05803)] 
  [[code]( https://github.com/cskyl/SAM_WSSS)]
  [2023.05]
  
- **SAM4MIS:** Yichi Zhang, Rushi Jiao.<br />
  "How Segment Anything Model (SAM) Boost Medical Image Segmentation?" ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.03678)] 
  [[code]( https://github.com/YichiZhang98/SAM4MIS)]
  [2023.05]
  
- **BadSAM:** Zihan Guan, Mengxuan Hu, Zhongliang Zhou, Jielu Zhang, Sheng Li, Ninghao Liu.<br />
  "BadSAM: Exploring Security Vulnerabilities of SAM via Backdoor Attacks." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.03289)] 
  [2023.05]
  
- **PerSAM:** Renrui Zhang, Zhengkai Jiang, Ziyu Guo, Shilin Yan, Junting Pan, Hao Dong, Peng Gao, Hongsheng Li.<br />
  "Personalize Segment Anything Model with One Shot." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.03048)] 
  [[code]( https://github.com/ZrrSkywalker/Personalize-SAM)]
  [2023.05]

- **CAT:** Teng Wang, Jinrui Zhang, Junjie Fei, Hao Zheng, Yunlong Tang, Zhe Li, Mingqi Gao, Shanshan Zhao.<br />
  "Caption Anything: Interactive Image Description with Diverse Multimodal Controls." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.02677)] 
  [[code]( https://github.com/ttengwang/Caption-Anything)]
  [2023.05]

- **SAMRS:** Di Wang, Jing Zhang, Bo Du, Dacheng Tao, Liangpei Zhang.<br />
  "Scaling-up Remote Sensing Segmentation Dataset with Segment Anything Model." NeurIPS 2023 Datasets and Benchmarks Track (2023).
  [[paper]( https://arxiv.org/abs/2305.02034)] 
  [[code]( https://github.com/ViTAE-Transformer/SAMRS)]
  [2023.05]

- **AV-SAM:** Shentong Mo, Yapeng Tian.<br />
  "AV-SAM: Segment Anything Model Meets Audio-Visual Localization and Segmentation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.01836)]
  [2023.05]

- **SAMA-AVS:** Jinxiang Liu, Yu Wang, Chen Ju, Chaofan Ma, Ya Zhang, Weidi Xie.<br />
  "Annotation-free Audio-Visual Segmentation." WACV (2024).
  [[paper]( https://arxiv.org/pdf/2305.11019v3.pdf)] 
  [[code]( https://github.com/jinxiang-liu/anno-free-AVS)]
  [2023.05]

- **WSSS:** Weixuan Sun, Zheyuan Liu, Yanhao Zhang, Yiran Zhong, Nick Barnes.<br />
  "An Alternative to WSSS? An Empirical Study of the Segment Anything Model (SAM) on Weakly-Supervised Semantic Segmentation Problems." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.01586)] 
  [2023.05]

- **PLG-SAM:** Peng-Tao Jiang, Yuqi Yang.<br />
  "Segment Anything is A Good Pseudo-label Generator for Weakly Supervised Semantic Segmentation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.01275)] 
  [2023.05]

- **Attack-SAM:** Chenshuang Zhang, Chaoning Zhang, Taegoo Kang, Donghun Kim, Sung-Ho Bae, In So Kweon.<br />
  "Attack-SAM: Towards Attacking Segment Anything Model With Adversarial Examples." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.00866)] 
  [2023.05]

- **Polyp-SAM:** Yuheng Li, Mingzhe Hu, Xiaofeng Yang.<br />
  "Polyp-SAM: Transfer SAM for Polyp Segmentation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.00293)] 
  [[code]( https://github.com/ricklisz/Polyp-SAM)]
  [2023.05]

- Dongsheng Han, Chaoning Zhang, Yu Qiao, Maryam Qamar, Yuna Jung, SeungKyu Lee, Sung-Ho Bae, Choong Seon Hong.<br />
  "Segment Anything Model (SAM) Meets Glass: Mirror and Transparent Objects Cannot Be Easily Detected." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.00278)] 
  [2023.05]

- **DSEC-MOS:** Zhuyun Zhou, Zongwei Wu, Rémi Boutteau, Fan Yang, Dominique Ginhac.<br />
  "DSEC-MOS: Segment Any Moving Object with Moving Ego Vehicle." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.00126)] 
  [[code]( https://github.com/ZZY-Zhou/DSEC-MOS)]
  [2023.05]

- Christian Mattjie, Luis Vinicius de Moura, Rafaela Cappelari Ravazio, Lucas Silveira Kupssinskü, Otávio Parraga, Marcelo Mussi Delucis, Rodrigo Coelho Barros.<br />
  "Zero-shot performance of the Segment Anything Model (SAM) in 2D medical imaging: A comprehensive evaluation and practical guidelines." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.00109)] 
  [[code]( https://github.com/Malta-Lab/SAM-zero-shot-in-Medical-Imaging)]
  [2023.05]

- Dongjie Cheng, Ziyuan Qin, Zekun Jiang, Shaoting Zhang, Qicheng Lao, Kang Li.<br />
  "SAM on Medical Images: A Comprehensive Study on Three Prompt Modes." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.00035)] 
  [2023.05]

- **Expedit-SAM:** Weicong Liang, Yuhui Yuan, Henghui Ding, Xiao Luo, Weihong Lin, Ding Jia, Zheng Zhang, Chao Zhang, Han Hu.<br />
  "Expediting Large-Scale Vision Transformer for Dense Prediction without Fine-tuning." NeurIPS (2022).
  [[paper](https://arxiv.org/abs/2210.01035)] 
  [[code](https://github.com/Expedit-LargeScale-Vision-Transformer/Expedit-SAM)]
  [2023.04] 
  
- An Wang, Mobarakol Islam, Mengya Xu, Yang Zhang, Hongliang Ren.<br />
  "SAM Meets Robotic Surgery: An Empirical Study in Robustness Perspective." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.14674)] 
  [2023.04]

- Yuhao Huang, Xin Yang, Lian Liu, Han Zhou, Ao Chang, Xinrui Zhou, Rusi Chen, Junxuan Yu, Jiongquan Chen, Chaoyu Chen, Haozhe Chi, Xindi Hu, Deng-Ping Fan, Fajin Dong, Dong Ni.<br />
  "Segment Anything Model for Medical Images?" ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.14660)] 
  [2023.04]

- **Edit Everything:** Defeng Xie, Ruichen Wang, Jian Ma, Chen Chen, Haonan Lu, Dong Yang, Fobo Shi, Xiaodong Lin.<br />
  "Edit Everything: A Text-Guided Generative System for Images Editing." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.14006)] 
  [[code]( https://github.com/DefengXie/Edit_Everything)]
  [2023.04]

- **SkinSAM:** Mingzhe Hu, Yuheng Li, Xiaofeng Yang.<br />
  "SkinSAM: Empowering Skin Cancer Segmentation with Segment Anything Model." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.13973)]
  [2023.04]  

- **GazeSAM:** Bin Wang, Armstrong Aboah, Zheyuan Zhang, Ulas Bagci.<br />
  "GazeSAM: What You See is What You Segment." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.13844)] 
  [[code]( https://github.com/ukaukaaaa/GazeSAM)]
  [2023.04]

- **SAMed:** Kaidong Zhang, Dong Liu.<br />
  "Customized Segment Anything Model for Medical Image Segmentation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.13785)] 
  [[code]( https://github.com/hitachinsk/SAMed)]
  [2023.04]

- **LearnablePromptSAM:** Zhongxi Qiu, Yan Hu, Heng Li, Jiang Liu.<br />
  "Learnable Ophthalmology SAM." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.13425)] 
  [[code]( https://github.com/Qsingle/LearnablePromptSAM)]
  [2023.04]

- Simiao Ren, Francesco Luzi, Saad Lahrichi, Kaleb Kassaw, Leslie M. Collins, Kyle Bradbury, Jordan M. Malof.<br />
  "Segment anything, from space?." WACV (2024).
  [[paper]( https://arxiv.org/abs/2304.13000)] 
  [2023.04]

-  Peilun Shi, Jianing Qiu, Sai Mu Dalike Abaxi, Hao Wei, Frank P. -W. Lo, Wu Yuan.<br />
  "Generalist Vision Foundation Models for Medical Imaging: A Case Study of Segment Anything Model on Zero-Shot Medical Segmentation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.12637)] 
  [2023.04]

- **MSA:** Junde Wu, Yu Zhang, Rao Fu, Huihui Fang, Yuanpei Liu, Zhaowei Wang, Yanwu Xu, Yueming Jin.<br />
  "Medical SAM Adapter: Adapting Segment Anything Model for Medical Image Segmentation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.12620)] 
  [[code]( https://github.com/WuJunde/Medical-SAM-Adapter)]
  [2023.04]

- Mohsen Ahmadi, Ahmad Gholizadeh Lonbar, Abbas Sharifi, Ali Tarlani Beris, Mohammadsadegh Nouri, Amir Sharifzadeh Javidi.<br />
  "Application of Segment Anything Model for Civil Infrastructure Defect Assessment." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.12600)] 
  [2023.04]

- **SA3D:** Jiazhong Cen, Zanwei Zhou, Jiemin Fang, Wei Shen, Lingxi Xie, Dongsheng Jiang, Xiaopeng Zhang, Qi Tian.<br />
  "Segment Anything in 3D with NeRFs." NeurIPS (2023).
  [[paper]( https://arxiv.org/abs/2304.12308)] 
  [[code]( https://jumpat.github.io/SA3D/)]
  [2023.04]

- **MedSAM:** Jun Ma, Yuting He, Feifei Li, Lin Han, Chenyu You, Bo Wang.<br />
  "Segment Anything in Medical Images." Nature Communications (2024).
  [[paper]( https://arxiv.org/abs/2304.12306)] 
  [[code]( https://github.com/bowang-lab/MedSAM)]
  [2023.04]

- **TAM:** Jinyu Yang, Mingqi Gao, Zhe Li, Shang Gao, Fangjing Wang, Feng Zheng.<br />
  "Track Anything: Segment Anything Meets Videos." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2304.11968)] 
  [[code](https://github.com/gaomingqi/Track-Anything)]
  [2023.04]

- **HFGFA:** Rongsheng Wang, Yaofei Duan, YuKun Li.<br />
  "Segment anything also detect anything." ArXiv (2023).
  [[paper](https://easychair.org/publications/preprint/T1rc)]
  [2023.04]

- **SNA:** Yongcheng Jing, Xinchao Wang, Dacheng Tao.<br />
  "Segment Anything in Non-Euclidean Domains: Challenges and Opportunities." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.11595)] 
  [2023.04]
  
- **SAMAug:** Yizhe Zhang, Tao Zhou, Peixian Liang, Danny Z. Chen.<br />
  "Input Augmentation with SAM: Boosting Medical Image Segmentation with Segmentation Foundation Model." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.11332)] 
  [2023.04]
  
- **Count-Anything:** Zhiheng Ma, Xiaopeng Hong, Qinnan Shangguan.<br />
  "Can SAM Count Anything? An Empirical Study on SAM Counting." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.10817)] 
  [[code]( https://github.com/Vision-Intelligence-and-Robots-Group/count-anything)]
  [2023.04]

- **Text2Seg:** Jielu Zhang, Zhongliang Zhou, Gengchen Mai, Lan Mu, Mengxuan Hu, Sheng Li.<br />
  "Text2Seg: Remote Sensing Image Semantic Segmentation via Text-Guided Visual Foundation Models." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.10597)] 
  [[code]( https://github.com/Douglas2Code/Text2Seg)]
  [2023.04]

- Maciej A. Mazurowski, Haoyu Dong, Hanxue Gu, Jichen Yang, Nicholas Konz, Yixin Zhang.<br />
  "Segment Anything Model for Medical Image Analysis: an Experimental Study." MIA (2023).
  [[paper]( https://arxiv.org/abs/2304.10517)] 
  [2023.04]

- **Anything-3D:** Qiuhong Shen, Xingyi Yang, Xinchao Wang.<br />
  "Anything-3D: Towards Single-view Anything Reconstruction in the Wild." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.10261)] 
  [[code]( https://github.com/Anything-of-anything/Anything-3D)]
  [2023.04]

- **Any-to-Any Transfer:** Songhua Liu, Jingwen Ye, Xinchao Wang.<br />
  "Any-to-Any Style Transfer: Making Picasso and Da Vinci Collaborate." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.09728)] 
  [[code]( https://github.com/Huage001/Transfer-Any-Style)]
  [2023.04]

- Sheng He, Rina Bao, Jingpeng Li, Jeffrey Stout, Atle Bjornerud, P. Ellen Grant, Yangming Ou.<br />
  "Computer-Vision Benchmark Segment-Anything Model (SAM) in Medical Images: Accuracy in 12 Datasets." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.09324)] 
  [2023.04]

- **SAM-Adapter:** Tianrun Chen, Lanyun Zhu, Chaotao Ding, Runlong Cao, Yan Wang, Zejian Li, Lingyun Sun, Papa Mao, Ying Zang.<br />
  "SAM Fails to Segment Anything? -- SAM-Adapter: Adapting SAM in Underperformed Scenes: Camouflage, Shadow, Medical Image Segmentation, and More." ICCVW (2023).
  [[paper]( https://arxiv.org/abs/2304.09148)] 
  [2023.04]

- Chuanfei Hu, Tianyi Xia, Shenghong Ju, Xinde Li.<br />
  "When SAM Meets Medical Images: An Investigation of Segment Anything Model (SAM) on Multi-phase Liver Tumor Segmentation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.08506)]
  [2023.04]  

- **SATIR:** Junzhang Chen, Xiangzhi Bai.<br />
  "Learning to "Segment Anything" in Thermal Infrared Images through Knowledge Distillation with a Large Scale Dataset SATIR." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.07969)] 
  [[code]( https://github.com/chenjzBUAA/SATIR)]
  [2023.04]

- Florian Putz, Johanna Grigo, Thomas Weissmann, Philipp Schubert, Daniel Hoefler, Ahmed Gomaa, Hassen Ben Tkhayat, Amr Hagag, Sebastian Lettmaier, Benjamin Frey, Udo S. Gaipl, Luitpold V. Distel, Sabine Semrau, Christoph Bert, Rainer Fietkau, Yixing Huang.<br />
  "The Segment Anything foundation model achieves favorable brain tumor autosegmentation accuracy on MRI to support radiotherapy treatment planning." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.07875)] 
  [2023.04]

-  Iraklis Giannakis, Anshuman Bhardwaj, Lydia Sam, Georgios Leontidis.<br />
  "Deep learning universal crater detection using Segment Anything Model (SAM)." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.07764)] 
  [2023.04]

- **SAMPolyp:** Tao Zhou, Yizhe Zhang, Yi Zhou, Ye Wu, Chen Gong.<br />
  "Can SAM Segment Polyps?" ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.07583)] 
  [[code]( https://github.com/taozh2017/SAMPolyp)]
  [2023.04]

- **Inpaint-Anything:** Tao Yu, Runseng Feng, Ruoyu Feng, Jinming Liu, Xin Jin, Wenjun Zeng, Zhibo Chen.<br />
  "Inpaint Anything: Segment Anything Meets Image Inpainting." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.06790)] 
  [[code]( https://github.com/geekyutao/Inpaint-Anything)]
  [2023.04]

- Ge-Peng Ji, Deng-Ping Fan, Peng Xu, Ming-Ming Cheng, Bowen Zhou, Luc Van Gool.<br />
  " SAM Struggles in Concealed Scenes -- Empirical Study on "Segment Anything"." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.06790)] 
  [2023.04]

- Wei Ji, Jingjing Li, Qi Bi, Tingwei Liu, Wenbo Li, Li Cheng.<br />
  "Segment Anything Is Not Always Perfect: An Investigation of SAM on Different Real-world Applications." Machine Intelligence Research (2024).
  [[paper](https://link.springer.com/article/10.1007/s11633-023-1385-0)]
  [[code](https://github.com/LiuTingWed/SAM-Not-Perfect)]
  [2024.04]

- Wei Ji, Jingjing Li, Qi Bi, Wenbo Li, Li Cheng.<br />
  "Segment Anything Is Not Always Perfect: An Investigation of SAM on Different Real-world Applications." CVPRW Oral (2023).
  [[paper]( https://arxiv.org/abs/2304.05750)]
  [[code](https://github.com/LiuTingWed/SAM-Not-Perfect)]
  [2023.04]

- **CLIP Surgery:** Yi Li, Hualiang Wang, Yiqun Duan, Xiaomeng Li.<br />
  "CLIP Surgery for Better Explainability with Enhancement in Open-Vocabulary Tasks." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.05653)] 
  [[code]( https://github.com/xmed-lab/CLIP_Surgery)]
  [2023.04]

- **SAMM:** Yihao Liu, Jiaming Zhang, Zhangcong She, Amir Kheradmand, Mehran Armand.<br />
  "SAMM (Segment Any Medical Model): A 3D Slicer Integration to SAM." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.05622)] 
  [[code]( https://github.com/bingogome/samm)]
  [2023.04]

- **SAM.MD:** Saikat Roy, Tassilo Wald, Gregor Koehler, Maximilian R. Rokuss, Nico Disch, Julius Holzschuh, David Zimmerer, Klaus H. Maier-Hein.<br />
  "SAM.MD: Zero-shot medical image segmentation capabilities of the Segment Anything Model." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.05396)] 
  [2023.04]


- **SAM vs BET:** Sovesh Mohapatra, Advait Gosai, Gottfried Schlaug.<br />
  "SAM vs BET: A Comparative Study for Brain Extraction and Segmentation of Magnetic Resonance Images using Deep Learning." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.04738)] 
  [2023.04]

- **SAMCOD:** Lv Tang, Haoke Xiao, Bo Li.<br />
  "Can SAM Segment Anything? When SAM Meets Camouflaged Object Detection." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.04709)] 
  [[code]( https://github.com/luckybird1994/SAMCOD)]
  [2023.04]


## Open Source Projects
| No. | Project | Title | Project page | Code base | Affiliation | Description |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 001 | SAM | Segment Anything | [Project page](https://segment-anything.com/)  | [Code](https://github.com/facebookresearch/segment-anything) | Meta | A foundation model for general segmentation. |
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
| 070  | LiteMedSAM  |LiteMedSAM   |  [Project page](https://github.com/bowang-lab/MedSAM/tree/LiteMedSAM)  |  [Code](https://github.com/bowang-lab/MedSAM/tree/LiteMedSAM)  | - | A lightweight version of MedSAM for fast training and inference. |



## Awesome Repositories for SAM
- [VainF/Awesome-Anything](https://github.com/VainF/Awesome-Anything)
- [Hedlen/Awesome Segment Anything](https://github.com/Hedlen/awesome-segment-anything)
- [Vision-Intelligence-and-Robots-Group/Awesome-Segment-Anything](https://github.com/Vision-Intelligence-and-Robots-Group/Awesome-Segment-Anything)
- [JerryX1110/Awesome-segment-anything-extensions](https://github.com/JerryX1110/awesome-segment-anything-extensions)
- [dk-liang/Awesome-Segment-Anything](https://github.com/dk-liang/Awesome-Segment-Anything)


## License
This project is released under the MIT license. Please see the [LICENSE](LICENSE) file for more information.

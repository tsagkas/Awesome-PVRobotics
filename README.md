 

# :robot: Awesome Pre-Trained Visual Representations for Motor Control and Robot Learning
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
<img src="https://img.shields.io/badge/Contributions-Welcome-009A00" alt="Contrib"/> <img src="https://img.shields.io/badge/Number%20of%20Items-21-59b5f7" alt="PaperNum"/>



Pre-trained visual representations (PVRs) are reshaping the landscape of robotic control by moving beyond the traditional tabula-rasa paradigm, where visuo-motor policies are trained from scratch. By leveraging powerful pre-trained foundation models from the domain of vision, researchers can harness rich, high-level abstractions to accelerate training and improve the generalization of robot policies across diverse environments. This repository compiles pioneering research on how PVRs are being utilized to enhance control learning and robotic performance without relying on task-specific or in-domain data.

Feel free to [cite](#citing-pvrobotics) and/or [contribute](https://github.com/tsagkas/Awesome-PVRobotics/pulls).
<!-- Ignore everything above this comment -->
# Table of Contents
- [All Papers](#all-papers):
   - [2022](#2022), [2023](#2023), [2024](#2024).
- [Other Useful Sources](#other-useful-sources):
  - [Benchmarks](#benchmarks), [Fine-Tuning](#fine-tuning--training-from-scratch), [Language Integration](#language-integration).
 


# All Papers
## 2022
1. **The Unsurprising Effectiveness of Pre-Trained Vision Models for Control**  
   *Simone Parisi, Aravind Rajeswaran, Senthil Purushwalkam, Abhinav Gupta*  
   [:page_facing_up:](https://arxiv.org/abs/2203.03580) [:globe_with_meridians:](https://sites.google.com/view/pvr-control) [:octocat:](https://github.com/sparisi/pvr_habitat) (ICML 2022)

2. **Masked Visual Pre-training for Motor Control**  
   *Tete Xiao, Ilija Radosavovic, Trevor Darrell, Jitendra Malik*  
   [:page_facing_up:](https://arxiv.org/abs/2203.06173) [:globe_with_meridians:](https://tetexiao.com/projects/mvp) [:octocat:](https://github.com/ir413/mvp) (ArXiv PrePrint 2022) 

3. **R3M: A Universal Visual Representation for Robot Manipulation**  
   *Suraj Nair, Aravind Rajeswaran, Vikash Kumar, Chelsea Finn, Abhinav Gupta*  
   [:page_facing_up:](https://arxiv.org/abs/2203.12601) [:globe_with_meridians:](https://sites.google.com/view/robot-r3m/) [:octocat:](https://github.com/facebookresearch/r3m) (CoRL 2022)

4. **VIP: Towards Universal Visual Reward and Representation via Value-Implicit Pre-Training**  
   *Yecheng Jason Ma, Shagun Sodhani, Dinesh Jayaraman, Osbert Bastani, Vikash Kumar, Amy Zhang*  
   [:page_facing_up:](https://arxiv.org/abs/2210.00030) [:globe_with_meridians:](https://sites.google.com/view/vip-rl) [:octocat:](https://github.com/facebookresearch/vip) (ICLR 2023)

5. **Real-World Robot Learning with Masked Visual Pre-training**  
   *Ilija Radosavovic, Tete Xiao, Stephen James, Pieter Abbeel, Jitendra Malik, Trevor Darrell*  
   [:page_facing_up:]() [:globe_with_meridians:](https://tetexiao.com/projects/real-mvp) [:octocat:](https://github.com/ir413/mvp) (CoRL 2022)


## 2023
1. **Where are we in the search for an Artificial Visual Cortex for Embodied Intelligence?**  
   *Arjun Majumdar, Karmesh Yadav, Sergio Arnaud, Yecheng Jason Ma, Claire Chen, Sneha Silwal, Aryan Jain, Vincent-Pierre Berges, Pieter Abbeel, Jitendra Malik, Dhruv Batra, Yixin Lin, Oleksandr Maksymets, Aravind Rajeswaran, Franziska Meier*  
   [:page_facing_up:](https://arxiv.org/abs/2303.18240) [:globe_with_meridians:](https://eai-vc.github.io/) [:octocat:](https://github.com/facebookresearch/eai-vc) (NeurIPS 2023)

2. **For Pre-Trained Vision Models in Motor Control, Not All Policy Learning Methods are Created Equal**  
   *Yingdong Hu, Renhao Wang, Li Erran Li, Yang Gao*  
   [:page_facing_up:](https://arxiv.org/abs/2304.04591v2) [:globe_with_meridians:](https://yingdong-hu.github.io/PVM-control/) [:octocat:](https://github.com/Yingdong-Hu/PVM-Robotics) (ICML 2023)


3. **Exploring Visual Pre-training for Robot Manipulation: Datasets, Models and Methods**  
    *Ya Jing, Xuelin Zhu, Xingbin Liu, Qie Sima, Taozheng Yang, Yunhai Feng, Tao Kong*  
    [:page_facing_up:](https://arxiv.org/abs/2308.03620) [:globe_with_meridians:](https://explore-pretrain-robot.github.io/) (IROS 2023)

4. **An Unbiased Look at Datasets for Visuo-Motor Pre-Training**  
*Sudeep Dasari, Mohan Kumar Srirama, Unnat Jain, Abhinav Gupta*  
[:page_facing_up:](https://arxiv.org/abs/2310.09289) [:globe_with_meridians:](https://data4robotics.github.io/) [:octocat:](https://github.com/SudeepDasari/data4robotics) (CoRL 2023)
    
5. **What Makes Pre-Trained Visual Representations Successful for Robust Manipulation?**  
    *Kaylee Burns, Zach Witzel, Jubayer Ibn Hamid, Tianhe Yu, Chelsea Finn, Karol Hausman*  
    [:page_facing_up:](https://arxiv.org/abs/2312.12444) [:globe_with_meridians:](https://kayburns.github.io/segmentingfeatures/) [:octocat:](https://github.com/stanford-iris-lab/segmenting_feats/tree/eval) 
    (ArXiv Preprint 2023)

## 2024
1. **SpawnNet: Learning Generalizable Visuomotor Skills from Pre-trained Networks**  
    *Xingyu Lin, John So, Sashwat Mahalingam, Fangchen Liu, Pieter Abbeel*  
    [:page_facing_up:](https://arxiv.org/abs/2307.03567) [:globe_with_meridians:](https://xingyu-lin.github.io/spawnnet/) [:octocat:](https://github.com/johnrso/spawnnet) (ICRA 2024)

2. **What do we learn from a large-scale study of pre-trained visual representations in sim and real environments?**  
    *Sneha Silwal, Karmesh Yadav, Tingfan Wu, Jay Vakil, Arjun Majumdar, Sergio Arnaud, Claire Chen, Vincent-Pierre Berges, Dhruv Batra, Aravind Rajeswaran, Mrinal Kalakrishnan, Franziska Meier, Oleksandr Maksymets*  
    [:page_facing_up:](https://arxiv.org/abs/2310.02219) [:globe_with_meridians:](https://pvrs-sim2real.github.io/) (ICRA 2024)

3. **Decomposing the Generalization Gap in Imitation Learning for Visual Robotic Manipulation**  
    *Annie Xie, Lisa Lee, Ted Xiao, Chelsea Finn*  
    [:page_facing_up:](https://arxiv.org/abs/2307.03659) 
    [:globe_with_meridians:](https://sites.google.com/view/generalization-gap)[:octocat:](https://github.com/RLAgent/factor-world) (ICRA 2024) 


4. **Spatiotemporal Predictive Pre-training for Robotic Motor Control**  
    *Jiange Yang, Bei Liu, Jianlong Fu, Bocheng Pan, Gangshan Wu, Limin Wang*  
    [:page_facing_up:](https://arxiv.org/abs/2403.05304) (ArXiv Preprint 2024)

5. **Pre-trained Text-to-Image Diffusion Models Are Versatile Representation Learners for Control**  
    *Gunshi Gupta, Karmesh Yadav, Yarin Gal, Dhruv Batra, Zsolt Kira, Cong Lu, Tim G. J. Rudner*  
    [:page_facing_up:](https://arxiv.org/abs/2405.05852) [:octocat:](https://github.com/ykarmesh/stable-control-representations) (ArXiv Preprint 2024)

6. **Theia: Distilling Diverse Vision Foundation Models for Robot Learning**
    *Jinghuan Shang, Karl Schmeckpeper, Brandon B. May, Maria Vittoria Minniti, Tarik Kelestemur, David Watkins, Laura Herlant*  
    [:page_facing_up:](https://arxiv.org/abs/2405.05852) [:globe_with_meridians:](https://theia.theaiinstitute.com/) [:octocat:](https://github.com/bdaiinstitute/theia) (ArXiv Preprint 2024)


# Other Useful Sources
## Benchmarks
1. **CortexBench** 
[:octocat:](https://github.com/facebookresearch/eai-vc/tree/main/cortexbench) 
2. **Voltron**
[:octocat:](https://github.com/siddk/voltron-robotics) 


## Fine-Tuning & Training from Scratch
1. **On Pre-Training for Visuo-Motor Control: Revisiting a Learning-from-Scratch Baseline**  
   *Nicklas Hansen, Zhecheng Yuan, Yanjie Ze, Tongzhou Mu, Aravind Rajeswaran, Hao Su, Huazhe Xu, Xiaolong Wang*  
   [:page_facing_up:](https://arxiv.org/abs/2212.05749) [:octocat:](https://github.com/gemcollector/learning-from-scratch) (CoRL 2022 - Workshop on Pre-training Robot Learning)

2. **Lossless Adaptation of Pretrained Vision Models For Robotic Manipulation**  
    *Mohit Sharma, Claudio Fantacci, Yuxiang Zhou, Skanda Koppula, Nicolas Heess, Jon Scholz, Yusuf Aytar*  
    [:page_facing_up:](https://arxiv.org/abs/2304.06600) [:globe_with_meridians:](https://sites.google.com/view/robo-adapters/) (ICLR 2023)

## Language Integration
1. **Language-Driven Representation Learning for Robotics**  
   *Siddharth Karamcheti, Suraj Nair, Annie S. Chen, Thomas Kollar, Chelsea Finn, Dorsa Sadigh, Percy Liang* 
   [:page_facing_up:](https://arxiv.org/abs/2302.12766) [:globe_with_meridians:](https://sites.google.com/view/voltron-robotics) [:octocat:](https://github.com/siddk/voltron-evaluation) (RSS 2023)

2. **LIV: Language-Image Representations and Rewards for Robotic Control**  
    *Yecheng Jason Ma, William Liang, Vaidehi Som, Vikash Kumar, Amy Zhang, Osbert Bastani, Dinesh Jayaraman*  
    [:page_facing_up:](https://arxiv.org/abs/2306.00958) [:globe_with_meridians:](https://penn-pal-lab.github.io/LIV/) [:octocat:](https://github.com/penn-pal-lab/LIV) (ICML 2023)

3. **Vision-Language Foundation Models as Effective Robot Imitators**  
    *Xinghang Li, Minghuan Liu, Hanbo Zhang, Cunjun Yu, Jie Xu, Hongtao Wu, Chilam Cheang, Ya Jing, Weinan Zhang, Huaping Liu, Hang Li, Tao Kong*  
    [:page_facing_up:](https://arxiv.org/abs/2311.01378) [:globe_with_meridians:](https://roboflamingo.github.io/) [:octocat:](https://github.com/RoboFlamingo/RoboFlamingo) (ICCV 2023)





# Citing PVRobotics
```
@misc{tsagkas2024awesome,
  author={Tsagkas, Nikolaos},
  title={Awesome Pre-Trained Visual Representations for Motor Control and Robot Learning},
  howpublished={\url{https://github.com/tsagkas/Awesome-PVRobotics}},
  year={2024}
}
```

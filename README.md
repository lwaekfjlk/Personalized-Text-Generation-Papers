# Personalized Text Generation

This repo collects papers for personalized text generation.

Currently we focus on personalized dialog generation, other personalized text generation forms are still under construction.



## Personalized Dialog Generation 

Currently contains 55 papers.

#### Non-neural Methods

1. Franc ̧ois Mairesse and Marilyn Walker "PERSONAGE: Personality Generation for Dialogue" ACL-2007
2. Yonghee Kim, Jeesoo Bang, Junhwi Choi and Seonghan Ryu "Acquisition and Use of Long-Term Memory for Personalized Dialog Systems" Workshop on Multimodel Analyses Enabling Artificial Agents in Human-Machine Interaction-2014
3. Jeesoo Bang, Hyungjong Noh, Yonghee Kim and Gary Geunbae Lee "Example-based chat-oriented dialogue system with personalized long-term memory" BIGCOMP-2015



#### Use persona utterance to model users

##### Use user ID embedding

1. Jiwei Li, Michel Galley, Chris Brockett, Georgios P. Spithourakis, Jianfeng Gao, Bill Dolan, "A Persona-Based Neural Conversation Model" ACL-2016
2. Rami Al-Rfou, Marc Pickett, Javier Snaider, Yun-hsuan Sung, Brian Strope and Ray Kurzweil "Conversational Contextual Cues: The Case of Personalization and History for Response Ranking" arxiv-2016
3. Satwik Kottur, Xiaoyu Wang and Vitor R. Carvalho "Exploring Personalized Neural Conversational Models" IJCAI-2017
4. Feng-Guang Su, Aliyah R. Hsu, Yi-Lin Tuan and Hung-Yi Lee "Personalized Dialogue Response Generation Learned from Monologues" Interspeech-2019
5. JinYeong Bak and Alice Oh "Variational Hierarchical User-based Conversation Model" EMNLP-2019
6. Bowen Wu, Mengyuan Li, Zongsheng Wang, Yifu Chen, Derek F. Wong, Qihang Feng, Junhong Huang, Baoxun Wang "Guiding Variational Response Generator to Exploit Persona" ACL-2020
7. Zhenghui Wang, Lingxiao Luo and Diyi Yang, "Personalized Response Generation with Tensor Factorization" GEM workshop-2021

##### Use transfer learning

1. Wei-Nan Zhang, Ting Liu, Yifa Wang, Qingfu Zhu "Neural Personalized Response Generation as Domain Adaptation" arxiv-2017
2. Min Yang, Zhou Zhao, Wei Zhao, Xiaojun Chen, Jia Zhu, Lianqiang Zhou and Zigang Cao "Personalized Response Generation via Domain adaptation" SIGIR-2017

##### Use multi-task learning

1. Yi Luan, Chris Brockett, Bill Dolan, Jianfeng Gao, Michel Galley "Multi-Task Learning for Speaker-Role Adaptation in Neural Conversation Models" ACL-2017
2. Orianna DeMasi, Yu Li and Zhou Yu "A Multi-Persona Chatbot for Hotline Counselor Training" EMNLP-2020

##### Use self-learned persona feature

1. Yizhe Zhang, Xiang Gao, Sungjin Lee, Chris Brockett, Michel Galley, Jianfeng Gao, Bill Dolan "Consistent Dialogue Generation with Self-supervised Feature Learning" arxiv-2019

##### Use personalized architecture

1. Yiping Song, Zequn Liu, Wei Bi, Rui Yan and Ming Zhang "Learning to Customize Model Structures for Few-shot Dialogue Generation Tasks" ACL-2020
2. Andrea Madotto, Zhaojiang Lin , Yejin Bang and Pascale Fung "The Adapter-Bot: All-In-One Controllable Conversational Model" AAAI-2021

##### Use GAN

1. Oluwatobi O. Olabiyi, Anish Khazane and Erik T. Mueller "A Persona-based Multi-turn Conversation Model in an Adversarial Learning Framework" IEEE  International Conference on Machine Learning and Applications-2018
2. Zhangming Chan, Juntao Li, Xiaopeng Yang, Xiuying Chen, Wenpeng Hu, Dongyan Zhao and Rui Yan "Modeling Personalization in Continuous Space for Response Generation via Augmented Wasserstein Autoencoders" ACL-2019

##### Use RL

1. Min Yang, Qiang Qu, Kai Lei, Jia Zhu, Zhou Zhao, Xiaojun Chen and  Joshua Z. Huang "Investigating Deep Reinforcement Learning Techniques in Personalized Dialogue Generation" Proceedings of the 2018 SIAM International Conference on Data Mining (SDM)-2018
2. Kaixiang Mo, Yu Zhang, Shuangyin Li, Jiajun Li, Qiang Yang "Personalizing a Dialogue System with Transfer Reinforcement Learning" AAAI-2018
3. Runzhe Yang, Jingxiao Chen and Karthik Narasimhan "Improving Dialog Systems for Negotiation with Personality Modeling" ACL-2021



#### Use explicit persona profile to help model users

##### Use copy mechanism

1. Semih Yavuz, Abhinav Rastogi, Guan-Lin Chao and Dilek Hakkani-Tür "DEEPCOPY: Grounded Response Generation with Hierarchical Pointer Networks" ACL-2019

##### Use NLI to improve consistency

1. **Sean Welleck, Jason Weston, Arthur Szlam and Kyunghyun Cho "Dialogue Natural Language Inference" ACL-2019**
2. Margaret Li, Stephen Roller, Ilia Kulikov, Sean Welleck, Y-Lan Boureau, Kyunghyun Cho, Jason Weston, "Don’t Say That! Making Inconsistent Dialogue Unlikely with Unlikelihood Training" ACL-2020
3. Haoyu Song, Wei-Nan Zhang, Jingwen Hu and Ting Liu "Generating Persona Consistent Dialogues by Exploiting Natural Language Inference" AAAI-2020
4. Haoyu Song, Yan Wang, Wei-Nan Zhang, Zhengyu Zhao, Ting Liu and Xiaojiang Liu "Profile Consistency Identification for Open-domain Dialogue Agents" EMNLP-2020
5. Hyunwoo Kim, Byeongchang Kim and  Gunhee Kim ""*Will I Sound Like Me*? Improving Persona Consistency in Dialogues through Pragmatic Self-Consciousness" EMNLP-2020

##### Use profile fusion

1. Chaitanya K. Joshi, Fei Mi, and Boi Faltings “Personalization in Goal-oriented Dialog” NIPS-2017
2. Qiao Qian, Minlie Huang, Haizhou Zhao, Jingfang Xu and Xiaoyan Zhu "Assigning Personality/Identity to a Chatting Machine for Coherent Conversation Generation" IJCAI-2018
3. Yury Zemlyanskiy and Fei Sha "Aiming to Know You Better Perhaps Makes Me a More Engaging Dialogue Partner" ACL-2018
4. **Saizheng Zhang, Emily Dinan, Jack Urbanek, Arthur Szlam, Douwe Kiela and Jason Weston "Personalizing Dialogue Agents: I have a dog, do you have pets too?" ACL-2018**
5. Pierre-Emmanuel Mazare, Samuel Humeau, Martin Raison and Antoine Bordes "Training Millions of Personalized Dialogue Agents" EMNLP-2018
6. Jason Weston, Emily Dinan and Alexander H. Miller "Retrieve and Refine: Improved Sequence Generation Models For Dialogue" EMNLP-workshop-SCAI-2018
7. Thomas Wolf, Victor Sanh, Julien Chaumond and Clement Delangue "TransferTransfo: A Transfer Learning Approach for Neural Network Based Conversational Agents" arxiv-2019
8. Liangchen Luo, Wenhao Huang, Qi Zeng, Zaiqing Nie and Xu Sun "Learning Personalized End-to-End Goal-Oriented Dialog" AAAI-2019
9. Andrea Madotto, Zhaojiang Lin, Chien-Sheng Wu and Pascale Fung "Personalizing Dialogue Agents via Meta-Learning" ACL-2019
10. Haoyu Song , Wei-Nan Zhang, Yiming Cui, Dong Wang and Ting Liu, "Exploiting Persona Information for Diverse Generation of Conversational Responses" IJCAI-2019
11. Yinhe Zheng, Rongsheng Zhang, Xiaoxi Mao, Minlie Huang "A Pre-training Based Personalized Dialogue Generation Model with Persona-sparse Data" arxiv-2019
12. Jia-Chen Gu, Zhen-Hua Ling, Xiaodan Zhu, Quan Liu, "Dually Interactive Matching Network for Personalized Response Selection in Retrieval-Based Chatbots" ACL-2019
13. Sergey Golovanov, Rauf Kurbanov, Sergey Nikolenko, Kyryl Truskovskyi, Alexander Tselousov, and Thomas Wolf, "Large-Scale Transfer Learning for Natural Language Generation" ACL-2019
14. Yinhe Zheng, Guanyi Chen, Minlie Huang, Song Liu and Xuan Zhu "Personalized Dialogue Generation with Diversified Traits" arxiv-2019
15. Xiang Gao, Yizhe Zhang, Sungjin Lee, Michel Galley, Chris Brockett, Jianfeng Gao and Bill Dolan "Structuring Latent Spaces for Stylized Response Generation" EMNLP-2019
16. Michael Shum, Stephan Zheng, Wojciech Krys ́cin ́ski, Caiming Xiong and Richard Socher "Sketch-Fill-A-R: A Persona-Grounded Chit-Chat Generation Framework" ACL-workshop-2020
17. Peixiang Zhong, Chen Zhang, Hao Wang, Yong Liu, Chunyan Miao "Towards Persona-Based Empathetic Conversational Models" EMNLP-2020
18. Haoyu Song, Yan Wang, Wei-Nan Zhang, Xiaojiang Liu, Ting Liu "Generate, Delete and Rewrite: A Three-Stage Framework for Improving Persona Consistency of Dialogue Generation" ACL-2020
19. Xu, Minghong, Piji Li, Haoran Yang, Pengjie Ren, Zhaochun Ren, Zhumin Chen and Jun Ma" A Neural Topical Expansion Framework for Unstructured Persona-Oriented Dialogue Generation.” arxiv-2020
20. Bodhisattwa Prasad Majumder, Harsh Jhamtani, Taylor Berg-kirkpatrick and Julian McAuley "Like hiking? You probably *enjoy nature*: Persona-grounded Dialog with Commonsense Expansions" EMNLP-2020
21. Thomas Scialom, Serra Sinem Tekirog ̆lu, Jacopo Staiano, Marco Guerini "Toward Stance-based Personas for Opinionated Dialogues" EMNLP-2020
22. [C/R+O+R] Hongjin Qian, Zhicheng Dou, Yutao Zhu, Yueyuan Ma, Ji-Rong Wen "Learning Implicit User Profiles for Personalized Retrieval-Based Chatbot" CIKM2021-IMPChat
23. Haoyu Song, Yan Wang, Kaiyan Zhang, Wei-Nan Zhang and Ting Liu "BoB: BERT Over BERT for Training Persona-based Dialogue Models from Limited Personalized Data" ACL-2021
24. Bodhisattwa Prasad Majumder, Taylor Berg-Kirkpatrick, Julian McAuley and Harsh Jhamtani "Unsupervised Enrichment of Persona-grounded Dialog with Background Stories" ACL-2021
25. Bin Li, Bin Sun, *Member, IEEE* and Shutao Li "Bilateral Personalized Dialogue Generation with Dynamic Persona-Aware Fusion" arxiv-2021
26. Zhengyi Ma, Zhicheng Dou, Yutao Zhu, Hanxun Zhong, and Ji-Rong Wen "One Chatbot Per Person: Creating Personalized Chatbots based on Implicit User Profiles" arxiv-2021
27. Yuwei Wu, Xuezhe Ma, Diyi Yang "Personalized Response Generation via Generative Split Memory Network" NAACL-2021

##### Use RL

1. Qian Liu , Yihong Chen, Bei Chen, Jian-Guang Lou, Zixuan Chen, Bin Zhou, Dongmei Zhang "You Impress Me: Dialogue Generation via Mutual Persona Perception" ACL-2020
2. Min Yang , Weiyi Huang, Wenting Tu, Qiang Qu , Ying Shen, and Kai Lei "Multitask Learning and Reinforcement Learning for Personalized Dialog Generation: An Empirical Study"  IEEE Transactions on neural networks and learning systems-2021



## Personalized Machine Translation

Currently contains 2 papers.

1. Joern Wuebker, Patrick Simianer, John DeNero "Compact Personalized Models for Neural Machine Translation" ACL-2018
2. Paul Michel and Graham Neubig "Extreme Adaptation for Personalized Neural Machine Translation" ACL-2018



## Personalized Review Generation

Currently contains 2 papers.

1. Jianmo Ni and Julian McAuley "Personalized Review Generation by Expanding Phrases and Attending on Aspect-Aware Representations" ACL-2018
2. Pan Li and Alexander Tuzhilin "Towards Controllable and Personalized Review Generation" EMNLP-2019



## Personalized Story Generation

Currently contains 1 papers.

1. Chandu, Khyathi, Shrimai Prabhumoye, Ruslan Salakhutdinov, and Alan W Black “‘My Way of Telling a Story’: Persona Based Grounded Story Generation.” ACL-workshop-2021



## Personalized Word Embedding

Currently contains 2 papers.

1. Daisuke Oba, Naoki Yoshinaga, Shoetsu Sato, Satoshi Akasaki and Masashi Toyoda "Modeling Personal Biases in Language Use by Inducing Personalized Word Embeddings"  ACL-2019
2. Guangneng Hu "Personalized Neural Embeddings for Collaborative Filtering with Text" ACL-2019


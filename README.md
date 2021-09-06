# Personalized Text Generation

Personalized text generation can be considered as a sub-topic under knowledge-grounded text generation and controllabel text generation.

Personalized text generation includes topics like :

1. personalized dialogue generation 
2. personalized machine translation
3. personalized summarization 
4. personalized review generation 
5. personalized QA generation
6. personalized product descritpion generation / recipe generation and other generation topic

For each paper, we pay attention to four themes mentioned in these papers: 

1. how to do personalized train/inference 
2. how to model personality
3. which dataset do they use
4. how to evaluate personalized performance

As a result, we organize the paperlist based on their generation task and classify them according to answer the four questions.

This paperlist not only includes papers aiming at solving personalized problems, but also contains papers including techniques suitable for personalized text generation.





## Part1 List and classify representative papers on personalized text generation

Papers in part1 are listed according to answer the four questions mentioned above.

1. Personalized Methods

   1. personalized model architecture

      1. Attention Fusion

         [arxiv2019] [Personalized Dialogue Generation with Diversified Traits](https://arxiv.org/pdf/1901.09672.pdf)

         [AAAI2020] [A Pre-training Based Personalized Dialogue Generation Model with Persona-sparse Data](https://arxiv.org/pdf/1911.04700.pdf)

         [arxiv2021] [Bilateral Personalized Dialogue Generation with Dynamic Persona-Aware Fusion](https://arxiv.org/pdf/2106.07857.pdf)

      2. Memory Network

         [EMNLP2018] [Training Millions of Personalized Dialogue Agents](https://aclanthology.org/D18-1298.pdf)

         [NAACL2021] [Personalized Response Generation via Generative Split Memory Network](https://aclanthology.org/2021.naacl-main.157.pdf)

      3. Pointer Network

         [SIGDAIL2019] [DEEPCOPY: Grounded Response Generation with Hierarchical Pointer Networks](http://aclanthology.lst.uni-saarland.de/W19-5917.pdf)

      4. AutoEncoder-based

         [EMNLP2019] [Modeling Personalization in Continuous Space for Response Generation via Augmented Wasserstein Autoencoders](https://aclanthology.org/D19-1201.pdf)

         [IJCAI2019] [Exploiting Persona Information for Diverse Generation of Conversational Responses](https://www.ijcai.org/proceedings/2019/0721.pdf)

         [ACL2020] [Guiding Variational Response Generator to Exploit Persona](https://aclanthology.org/2020.acl-main.7.pdf)

      5. Adapter-based

         [AAAI2021] [The Adapter-Bot: All-In-One Controllable Conversational Model](https://www.aaai.org/AAAI21Papers/DEMO-233.LinZ.pdf)

   2. personalized learning and inference

      1. multi-task learning

         [IJCNLP2017] [Multi-Task Learning for Speaker-Role Adaptation in Neural Conversation Models](http://aclanthology.lst.uni-saarland.de/I17-1061.pdf)

         [EMNLP2020] [A Multi-Persona Chatbot for Hotline Counselor Training](https://aclanthology.org/2020.findings-emnlp.324.pdf)

      2. interpolation personalized model and global model

         [NLI2020] [Examination and Extension of Strategies for Improving Personalized Language Modeling via Interpolation](https://aclanthology.org/2020.nli-1.3.pdf)

      3. domain adaptation on global model

         [SIGIR2017] [Personalized Response Generation via Domain adaptation](https://dl.acm.org/doi/10.1145/3077136.3080706)

         [AAAI2021] [The Adapter-Bot: All-In-One Controllable Conversational Model](https://www.aaai.org/AAAI21Papers/DEMO-233.LinZ.pdf)

         [arxiv2021] [Prefix-Tuning: Optimizing Continuous Prompts for Generation](https://arxiv.org/pdf/2101.00190.pdf)

      4. consistency augmented

         [ACL2019] [Dialogue Natural Language Inference](https://aclanthology.org/P19-1363.pdf)

         [AAAI2020] [Generating Persona Consistent Dialogues by Exploiting Natural Language Inference](https://arxiv.org/pdf/1911.05889.pdf)

      5. Rational Speech Acts-based

2. Personality Modeling

   1. Model personality in continious space

      1. independent user embedding

         [ACL2016] [A Persona-Based Neural Conversation Model](https://aclanthology.org/P16-1094.pdf) 

         [IJCAI2017] [Exploring Personalized Neural Conversational Models](https://www.ijcai.org/proceedings/2017/0521.pdf)

         [ACL2020] [Guiding Variational Response Generator to Exploit Persona](https://aclanthology.org/2020.acl-main.7.pdf)

         [GEMworkshop2021] [Personalized Response Generation with Tensor Factorization](https://aclanthology.org/2021.gem-1.5.pdf)

      2. personal linguistic style extracted from annotated utterance

         [arxiv2019] [Consistent Dialogue Generation with Self-supervised Feature Learning](https://arxiv.org/pdf/1903.05759.pdf)

         [EMNLP2020] [A Multi-Persona Chatbot for Hotline Counselor Training](https://aclanthology.org/2020.findings-emnlp.324.pdf)

         [ACL2020] [Learning to Customize Model Structures for Few-shot Dialogue Generation Tasks](https://aclanthology.org/2020.acl-main.517.pdf)

   2. Model personality in a concrete media

      1. raw text profile

         [ACL2018] [Personalizing Dialogue Agents: I have a dog, do you have pets too?](https://aclanthology.org/P18-1205.pdf)

      2. key-value profile

         [IJCAI2018] [Assigning Personality/Identity to a Chatting Machine for Coherent Conversation Generation](https://www.ijcai.org/proceedings/2018/0595.pdf)

      3. expanded text profile

         [EMNLP2020] [Like hiking? You probably *enjoy nature*: Persona-grounded Dialog with Commonsense Expansions](https://arxiv.org/pdf/2010.03205.pdf)

         [EMNLP2020] [Toward Stance-based Personas for Opinionated Dialogues](https://aclanthology.org/2020.findings-emnlp.238.pdf)

         [ACL2021] [Unsupervised Enrichment of Persona-grounded Dialog with Background Stories](https://arxiv.org/pdf/2106.08364.pdf)

   3. Model personality in an interactive action

      1. Reinforcement Learning interaction

         [AAAI2018] [Personalizing a Dialogue System with Transfer Reinforcement Learning](https://arxiv.org/pdf/1610.02891.pdf)

         [ACL2021] [Improving Dialog Systems for Negotiation with Personality Modeling](https://aclanthology.org/2021.acl-long.56.pdf)

      2. feedback from users

         [ACL2017] [Joint Optimization of User-desired Content in Multi-document Summaries by Learning from User Feedback](https://aclanthology.org/P17-1124.pdf)

         [PBML2017] [Continuous Learning from Human Post-Edits for Neural Machine Translation](https://core.ac.uk/download/pdf/226078161.pdf)

3. Personalized Dataset

   1. contains text with annotated persona attributes

      Twitter / Reddit / Opensubtitles / Malluba

   2. contains text with persona profile

      PERSONACHAT

4. Personalized Evaluation
   1. Automatic Evaluation

      PPL / BLEU / ROUGE-L / METEOR / Distinct / Entropy /  Consistency score / word-embedding level metric

   2. Human Evaluation

      consistency / fluency / informativeness / relevance / appropriateness / agreement / fact-inclusion

      cohen's k score



## Part2 List all related or inspiring papers regarding to personalized text generation

Papers in part2 are listed according to their generation task instead of methods or dataset. Papers might not be directly related to personalized text generation but at least, from my perspective, can provide some interesing insight into this topic. 

1. Related survey and PhD thesis

   [PhD Thesis] [Controllable Text Generation](https://www.lti.cs.cmu.edu/sites/default/files/prabhomoye%2C%20shrimai%20-%20CMU-LTI-21-001.pdf)

   [PhD Thesis] [Neural Generation of open-ended text and dialogue](https://stacks.stanford.edu/file/druid:hw190jq4736/AbigailSeeThesis-augmented.pdf)

   [survey] [Pretrained Language Models for Text Generation: A Survey](https://arxiv.org/pdf/2105.10311.pdf)

   [survey] [Neural Approaches to Conversational AI](https://dl.acm.org/doi/abs/10.1145/3209978.3210183)

   [survey] [A Survey of Knowledge-Enhanced Text Generation](https://arxiv.org/pdf/2010.04389.pdf)

   

2. Personalized Dialog Generation

   [ACL2007] [PERSONAGE: Personality Generation for Dialogue](https://aclanthology.org/P07-1063.pdf)

   [ACL2012] [Personalized Normalization for a Multilingual Chat System](https://aclanthology.org/P12-3006.pdf)

   [ICML2015] [A Neural Conversational Model](https://arxiv.org/pdf/1506.05869.pdf)

   [SIGDAIL2016] [Analyzing Post-dialogue Comments by Speakers – How Do Humans Personalize Their Utterances in Dialogue? –](https://aclanthology.org/W16-3619.pdf)

   [arxiv2016] [Conversational Contextual Cues: The Case of Personalization and History for Response Ranking](https://arxiv.org/pdf/1606.00372.pdf)

   **[ACL2016]** [A Persona-Based Neural Conversation Model](https://aclanthology.org/P16-1094.pdf) 

   [arxiv2017] [Neural Personalized Response Generation as Domain Adaptation](https://arxiv.org/pdf/1701.02073.pdf)

   [IJCAI2017] [Exploring Personalized Neural Conversational Models](https://www.ijcai.org/proceedings/2017/0521.pdf)

   [NIPS2017] [Personalization in Goal-oriented Dialog](https://arxiv.org/pdf/1706.07503.pdf)

   [INLG2017] [Neural Response Generation for Customer Service based on Personality Traits](https://aclanthology.org/W17-3541.pdf)

   [IJCNLP2017] [Multi-Task Learning for Speaker-Role Adaptation in Neural Conversation Models](http://aclanthology.lst.uni-saarland.de/I17-1061.pdf)

   [SIGIR2017] [Personalized Response Generation via Domain adaptation](https://dl.acm.org/doi/10.1145/3077136.3080706)

   [EMNLP2017] [Steering Output Style and Topic in Neural Response Generation](https://aclanthology.org/D17-1228.pdf)

   [AAAI2018] [Personalizing a Dialogue System with Transfer Reinforcement Learning](https://arxiv.org/pdf/1610.02891.pdf)

   [EMNLP2018] [Learning Personas from Dialogue with Attentive Memory Networks](https://aclanthology.org/D18-1284.pdf)

   [EMNLP2018] [Training Millions of Personalized Dialogue Agents](https://aclanthology.org/D18-1298.pdf)

   [EMNLPwokshop2018] [Retrieve and Refine: Improved Sequence Generation Models For Dialogue](https://aclanthology.org/W18-5713.pdf)

   [SIAM2018] [Investigating Deep Reinforcement Learning Techniques in Personalized Dialogue Generation](https://epubs.siam.org/doi/abs/10.1137/1.9781611975321.71?mobileUi=0)

   [IJCAI2018] [Assigning Personality/Identity to a Chatting Machine for Coherent Conversation Generation](https://www.ijcai.org/proceedings/2018/0595.pdf)

   [LREC2018] [Towards Neural Speaker Modeling in Multi-Party Conversation: The Task, Dataset, and Models](https://aclanthology.org/L18-1496.pdf)

   **[ACL2018]** [Personalizing Dialogue Agents: I have a dog, do you have pets too?](https://aclanthology.org/P18-1205.pdf)

   [EMNLP2019] [Dually Interactive Matching Network for Personalized Response Selection in Retrieval-Based Chatbots](https://aclanthology.org/D19-1193.pdf)

   [EMNLP2019] [Modeling Personalization in Continuous Space for Response Generation via Augmented Wasserstein Autoencoders](https://aclanthology.org/D19-1201.pdf)

   [EMNLP2019] [Structuring Latent Spaces for Stylized Response Generation](https://aclanthology.org/D19-1190.pdf)

   [EMNLP2019] [Variational Hierarchical User-based Conversation Model](https://aclanthology.org/D19-1202.pdf)

   [SIGDAIL2019] [DEEPCOPY: Grounded Response Generation with Hierarchical Pointer Networks](http://aclanthology.lst.uni-saarland.de/W19-5917.pdf)

   [AAAI2019] [Learning Personalized End-to-End Goal-Oriented Dialog](https://arxiv.org/pdf/1811.04604.pdf)

   [NIPSworkshop2019] [Persona-aware Dialogue Generation with Enriched Profile](https://arxiv.org/pdf/1901.09672.pdf)

   [IJCAI2019] [Exploiting Persona Information for Diverse Generation of Conversational Responses](https://www.ijcai.org/proceedings/2019/0721.pdf)

   [NAACL2019] [An Adversarial Learning Framework For A Persona-Based Multi-Turn Dialogue Model](https://aclanthology.org/W19-2301.pdf)

   **[ACL2019]** [Dialogue Natural Language Inference](https://aclanthology.org/P19-1363.pdf)

   [ACL2019] [Large-Scale Transfer Learning for Natural Language Generation](https://aclanthology.org/P19-1608.pdf)

   [ACL2019] [Know More about Each Other: Evolving Dialogue Strategy via Compound Assessment](https://aclanthology.org/P19-1535.pdf)

   [ACL2019] [Personalizing Dialogue Agents via Meta-Learning](https://aclanthology.org/P19-1542.pdf)

   [ACL2019] [Persuasion for Good: Towards a Personalized Persuasive Dialogue System for Social Good](https://aclanthology.org/P19-1566.pdf)

   [arxiv2019] [Personalized Dialogue Generation with Diversified Traits](https://arxiv.org/pdf/1901.09672.pdf)

   [arxiv2019] [Consistent Dialogue Generation with Self-supervised Feature Learning](https://arxiv.org/pdf/1903.05759.pdf)

   [arxiv2019] [TransferTransfo: A Transfer Learning Approach for Neural Network Based Conversational Agents](https://arxiv.org/pdf/1901.08149.pdf)

   [AAAI2020] [Generating Persona Consistent Dialogues by Exploiting Natural Language Inference](https://arxiv.org/pdf/1911.05889.pdf)

   [AAAI2020] [A Pre-training Based Personalized Dialogue Generation Model with Persona-sparse Data](https://arxiv.org/pdf/1911.04700.pdf)

   [ACL2020] [Don’t Say *That*! Making Inconsistent Dialogue Unlikely with Unlikelihood Training](https://aclanthology.org/2020.acl-main.428.pdf)

   [ACL2020] [Generate, Delete and Rewrite: A Three-Stage Framework for Improving Persona Consistency of Dialogue Generation](https://aclanthology.org/2020.acl-main.516.pdf)

   [ACL2020] [Guiding Variational Response Generator to Exploit Persona](https://aclanthology.org/2020.acl-main.7.pdf)

   [ACL2020] [Improving Disentangled Text Representation Learning with Information-Theoretic Guidance](https://aclanthology.org/2020.acl-main.673.pdf)

   [ACL2020] [Learning to Customize Model Structures for Few-shot Dialogue Generation Tasks](https://aclanthology.org/2020.acl-main.517.pdf)

   [ACL2020] [You Impress Me: Dialogue Generation via Mutual Persona Perception](https://aclanthology.org/2020.acl-main.131.pdf)

   [ACLworkshop2020] [Sketch-Fill-A-R: A Persona-Grounded Chit-Chat Generation Framework](https://aclanthology.org/2020.nlp4convai-1.14.pdf)

   [EMNLP2020] [A Multi-Persona Chatbot for Hotline Counselor Training](https://aclanthology.org/2020.findings-emnlp.324.pdf)

   [EMNLP2020] [Like hiking? You probably *enjoy nature*: Persona-grounded Dialog with Commonsense Expansions](https://arxiv.org/pdf/2010.03205.pdf)

   [EMNLP2020] [Profile Consistency Identification for Open-domain Dialogue Agents](https://aclanthology.org/2020.emnlp-main.539.pdf)

   [EMNLP2020] [Toward Stance-based Personas for Opinionated Dialogues](https://aclanthology.org/2020.findings-emnlp.238.pdf)

   [EMNLP2020] [Towards Persona-Based Empathetic Conversational Models](https://aclanthology.org/2020.emnlp-main.531.pdf)

   [EMNLP2020] [Will I Sound Like Me? Improving Persona Consistency in Dialogues through Pragmatic Self-Consciousness](https://aclanthology.org/2020.emnlp-main.65.pdf)

   [ECAI2020] [A Neural Topical Expansion Framework for Unstructured Persona-oriented Dialogue Generation](https://ecai2020.eu/papers/345_paper.pdf)

   [arxiv2020] [Recipes for building an open-domain chatbot](https://arxiv.org/pdf/2004.13637.pdf)

   [arxiv2020] [Towards a Human-like Open-Domain Chatbot](https://arxiv.org/pdf/2001.09977.pdf)

   [GEMworkshop2021] [Personalized Response Generation with Tensor Factorization](https://aclanthology.org/2021.gem-1.5.pdf)

   [CIKM2021] [Learning Implicit User Profiles for Personalized Retrieval-Based Chatbot](https://arxiv.org/pdf/2108.07935.pdf) 

   [ACL2021] [BoB: BERT Over BERT for Training Persona-based Dialogue Models from Limited Personalized Data](https://aclanthology.org/2021.acl-long.14.pdf)

   [ACL2021] [Improving Dialog Systems for Negotiation with Personality Modeling](https://aclanthology.org/2021.acl-long.56.pdf)

   [ACL2021] [Unsupervised Enrichment of Persona-grounded Dialog with Background Stories](https://arxiv.org/pdf/2106.08364.pdf)

   [AAAI2021] [The Adapter-Bot: All-In-One Controllable Conversational Model](https://www.aaai.org/AAAI21Papers/DEMO-233.LinZ.pdf)

   [NNLS2021] [Multitask Learning and Reinforcement Learning for Personalized Dialog Generation: An Empirical Study](https://ieeexplore.ieee.org/document/9025776)

   [SIGIR2021] [One Chatbot Per Person: Creating Personalized Chatbots based on Implicit User Profiles](https://arxiv.org/pdf/2108.09355.pdf)

   [NAACL2021] [Personalized Response Generation via Generative Split Memory Network](https://aclanthology.org/2021.naacl-main.157.pdf)

   [arxiv2021] [Bilateral Personalized Dialogue Generation with Dynamic Persona-Aware Fusion](https://arxiv.org/pdf/2106.07857.pdf)

   [arxiv2021] [Content Selection Network for Document-grounded Retrieval-based Chatbots](https://arxiv.org/pdf/2101.08426.pdf)

   [EMNLP2021] [Detecting Speaker Personas from Conversational Texts](https://arxiv.org/pdf/2109.01330.pdf)

   

3. Personalized Summarization

   [AH2008] [Aspect-Based Personalized Text Summarization](https://link.springer.com/chapter/10.1007/978-3-540-70987-9_31)

   [EMNLP2011] [Summarize What You Are Interested In: An Optimization Framework for Interactive Personalized Summarization](https://aclanthology.org/D11-1124.pdf)

   [COLING2012] [Context­Enhanced Personalized Social Summarization](https://aclanthology.org/C12-1075.pdf)

   [INLG2014] [Adapting graph summaries to the users reading levels](https://aclanthology.org/W14-4409.pdf)

   [ACL2017] [Joint Optimization of User-desired Content in Multi-document Summaries by Learning from User Feedback](https://aclanthology.org/P17-1124.pdf)

   [NAACL2018] [Towards Generating Personalized Hospitalization Summaries](https://aclanthology.org/N18-4011.pdf)

   [arxiv2020] [Adaptive Summaries: A Personalized Concept-based Summarization Approach by Learning from Users’ Feedback](https://arxiv.org/abs/2012.13387)



4. Personalized Machine Translation

   [IJCNLP2008] [Statistical Machine Translation Models for Personalized Search](https://aclanthology.org/I08-1068.pdf)

   [EACL2014] [Learning from Post-Editing: Online Model Adaptation for Statistical Machine Translation](https://aclanthology.org/E14-1042.pdf)

   [EMNLP2015] [Personalized Machine Translation: Predicting Translational Preferences](https://aclanthology.org/D15-1238.pdf)

   [EACL2017] [Personalized Machine Translation: Preserving Original Author Traits](https://aclanthology.org/E17-1101.pdf)

   [PBML2017] [Continuous Learning from Human Post-Edits for Neural Machine Translation](https://core.ac.uk/download/pdf/226078161.pdf)

   [EMNLP2018] [Compact Personalized Models for Neural Machine Translation](https://aclanthology.org/D18-1104.pdf)

   [ACL2018] [Extreme Adaptation for Personalized Neural Machine Translation](https://aclanthology.org/P18-2050.pdf)

   [ALTA2018] [Improved Neural Machine Translation using Side Information](https://aclanthology.org/U18-1001.pdf)

   [EMNLP2019] [Simple, Scalable Adaptation for Neural Machine Translation](https://aclanthology.org/D19-1165.pdf)

   [MTSummit2019] [Interactive-Predictive Neural Machine Translation through Reinforcement and Imitation](https://aclanthology.org/W19-6610.pdf)

   [ACL2021] [Towards User-Driven Neural Machine Translation](https://aclanthology.org/2021.acl-long.310.pdf)



5. Personalized Review Generation

   [CIKM2014] [Knowledge-Enhanced Personalized Review Generation with Capsule Graph Neural Network](https://arxiv.org/pdf/2010.01480.pdf)

   [IJCNLP2017] [Estimating Reactions and Recommending Products with Generative Models of Reviews](https://aclanthology.org/I17-1079.pdf)

   [ACL2018] [Personalized Review Generation by Expanding Phrases and Attending on Aspect-Aware Representations](https://aclanthology.org/P18-2112.pdf)

   [ACLworkshop2019] [Automatic Generation of Personalized Comment Based on User Profile]()

   [WWW2019] [Persona-Aware Tips Generation](https://arxiv.org/abs/1903.02156)

   [EMNLP2019] [Towards controllable and personalized review generation](https://aclanthology.org/D19-1319.pdf)



6. Personalized Questions and Answering

   [COLING2008 workshop] [Personalized, Interactive Question Answering on the Web](https://aclanthology.org/W08-1605.pdf)

   [INLG2017] [Personalized Questions, Answers and Grammars: Aiding the Search for Relevant Web Information](https://aclanthology.org/W17-3530.pdf)



7. General Personalized Generation

   [CL2011] [Controlling user perceptions of linguistic style: Trainable generation of personality traits](https://aclanthology.org/J11-3002.pdf)

   [SLT2012] [Personalized language modeling by crowd sourcing with social network data for voice access of cloud applications](https://ieeexplore.ieee.org/document/6424220)

   [ACL2014] [Enriching Cold Start Personalized Language Model Using Social Network Information](https://aclanthology.org/P14-2100.pdf)

   [TASLP2016] [Personalizing Recurrent Neural Network Based Language Model by Social Network](https://dl.acm.org/doi/10.1109/TASLP.2016.2635445)

   [ACL2018] [Personalized Language Model for Query Auto-Completion](https://aclanthology.org/P18-2111.pdf)

   [EMNLP2019] [Generating Personalized Recipes from Historical User Preferences](https://arxiv.org/pdf/1909.00105.pdf)

   [KDD2019] [Towards Knowledge-Based Personalized Product Description Generation in E-commerce](https://arxiv.org/pdf/1903.12457.pdf)

   [ACLworkshop2019] [“My Way of Telling a Story”: Persona based Grounded Story Generation](https://arxiv.org/pdf/1906.06401.pdf)

   [NLI2020] [Examination and Extension of Strategies for Improving Personalized Language Modeling via Interpolation](https://aclanthology.org/2020.nli-1.3.pdf)

   [COLING2020] [Personalized Multimodal Feedback Generation in Education](https://aclanthology.org/2020.coling-main.166.pdf)

   [WSDM2021] [Personalized Food Recommendation as Constrained Question Answering over a Large-scale Food Knowledge Graph](https://dl.acm.org/doi/abs/10.1145/3437963.3441816)

   [ACL2021] [PENS: A Dataset and Generic Framework for Personalized News Headline Generation](https://aclanthology.org/2021.acl-long.7.pdf)

   [arxiv2021] [Prefix-Tuning: Optimizing Continuous Prompts for Generation](https://arxiv.org/pdf/2101.00190.pdf)



8. Personalized Generation Evaluation

   [EMNLP2016] [How NOT To Evaluate Your Dialogue System: An Empirical Study of Unsupervised Evaluation Metrics for Dialogue Response Generation](https://arxiv.org/pdf/1603.08023.pdf)

   [LREC2020] [Evaluating Approaches to Personalizing Language Models](https://aclanthology.org/2020.lrec-1.299.pdf)

   [CORR2020] [XPersona: Evaluating Multilingual Personalized Chatbot](https://arxiv.org/pdf/2003.07568.pdf)

   












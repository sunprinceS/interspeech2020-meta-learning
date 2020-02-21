+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active =  true # Activate this widget? true/false
weight = 25  # Order that this section will appear.

title = "Reading"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "#F7F7F7"
  
  # Background gradient.
  # gradient_start = "#FFFFFF"
  # gradient_end = "#FFFFFF"
  
  # Background image.
  # image = "image.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = false

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

Meta learning is one of the fastest growing research areas in the deep learning scope. However there is no standard definition for meta learning. Usually the main goal is to design models that can learn new tasks rapidly with few in domain training examples, by having models to pre-learn from many, relevant or not, training tasks in a way that the models are easy to be generalized to new tasks. For better understanding the scope of meta learning, we provide several online courses and papers describing the works falling into the area. These works are just for showcasing, and we definitely encourage people with research not covered here but sharing the same goal mentioned above to submit.


### Online Courses

* [CS 330: Deep Multi-Task and Meta Learning](http://cs330.stanford.edu/)
* [Hung-Yi Lee's Lecture](https://youtu.be/wurPYalweeo) (in Mandarin)

### Papers
#### Meta Learning Technology

* Learning to Initialize:
  * Chelsea Finn, Pieter Abbeel, and Sergey Levine, “Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks”, ICML, 2017
  * Sebastian Flennerhag, Pablo G. Moreno, Neil D. Lawrence, Andreas Damianou, Transferring Knowledge across Learning Processes, ICLR, 2019
* Learning to optimize:
  * Sachin Ravi, Hugo Larochelle, Optimization as a model for few-shot learning, ICLR, 2017
  * Marcin Andrychowicz, Misha Denil, Sergio Gomez, Matthew W. Hoffman, David Pfau, Tom Schaul, Brendan Shillingford, Nando de Freitas, Learning to learn by gradient descent by gradient descent, NIPS, 2016
* Learning to compare   
  * Jake Snell, Kevin Swersky, Richard S. Zemel, Prototypical Networks for Few-shot Learning, NIPS, 2017
  * Oriol Vinyals, Charles Blundell, Timothy Lillicrap, Koray Kavukcuoglu, Daan Wierstra, Matching Networks for One Shot Learning, NIPS, 2016
  * Flood Sung, Yongxin Yang, Li Zhang, Tao Xiang, Philip H.S. Torr, Timothy M. Hospedales, Learning to Compare: Relation Network for Few-Shot Learning, CVPR, 2018
* Learning the whole learning algorithm 
  * Adam Santoro, Sergey Bartunov, Matthew Botvinick, Daan Wierstra, Timothy Lillicrap, Meta-Learning with Memory-Augmented Neural Networks, ICML, 2016
  * Nikhil Mishra, Mostafa Rohaninejad, Xi Chen, Pieter Abbeel, A Simple Neural Attentive Meta-Learner, ICLR, 2018
* Network architecture search:
  * RL based 
    * Barret Zoph, Quoc V. Le, Neural Architecture Search with Reinforcement Learning, ICLR 2017
    * Barret Zoph, Vijay Vasudevan, Jonathon Shlens, Quoc V. Le,  Learning Transferable Architectures for Scalable Image Recognition, CVPR, 2018
    * Hieu Pham, Melody Guan, Barret Zoph, Quoc Le, Jeff Dean, Efficient Neural Architecture Search via Parameter Sharing, ICML, 2018
  * Evolution based 
    * Esteban Real, Sherry Moore, Andrew Selle, Saurabh Saxena, Yutaka Leon Suematsu, Jie Tan, Quoc Le, Alex Kurakin, Large-Scale Evolution of Image Classifiers, ICML 2017 
    * Esteban Real, Alok Aggarwal, Yanping Huang, Quoc V Le, Regularized Evolution for Image Classifier Architecture Search, AAAI, 2019
    * Hanxiao Liu, Karen Simonyan, Oriol Vinyals, Chrisantha Fernando, Koray Kavukcuoglu, Hierarchical Representations for Efficient Architecture Search, ICLR, 2018
  * Supernetwork based 
    * Hanxiao Liu, Karen Simonyan, Yiming Yang, DARTS: Differentiable Architecture Search, ICLR, 2019

#### Applications to Human Language Technology: 

|                         |                                                                                                                                                          |                                                                                                                                                             |                                                              |
|:-----------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------:|
|                         |                                                                             **Learning to initialize**                                                                             |                                                                               **Learning to compare**                                                                              |                                                              **Other**                                                             |
|  <br> <br> **Speech Recognition**   |                                                            <br>[Hsu, et al., ICASSP’20]<br><br>[Klejch, et al., ASRU’19]                                                           |                                                                                                                                                                                |    [Klejch , et al., INTERSPEECH’18]<br> (Learning to optimize)<br><br>[Baruwa , et al., IJSER’19]<br> (Network architecture search)   |
|   <br><br>    **Voice Cloning**      |                                                                                                                                                                                |                                                                                                                                                                                | [Chen, et al., ICLR’19]<br> (Learning the learning algorithm)<br><br>[Serrà, et al., NeurIPS’19]<br> (Learning the learning algorithm) |
|   **Speaker Recognition**   |                                                                                                                                                                                |                                                                            [Anand, et al., arXiv’19]                                                                           |                                                                                                                                |
|    **Keyword Spotting**    |                                                                            [Chen, et al., arXiv’18]                                                                            |                                                                                                                                                                                |                                 [Mazzawi, et al., INTERSPEECH’19]<br> (Network architecture search)                                |
| <br><br> **Sound Event Detection**  |                                                                                                                                                                                |                                       [Shimada, et al., arXiv’19]<br><br>[Chou, et al., ICASSP’19]<br><br>[Zhang, et al., INTERSPEECH’19]                                      |                                                                                                                                |
|  <br> **Machine Translation**   |                                                           [Gu, et al., EMNLP’18]<br><br>[Indurthi, et al., arXiv’19]                                                           |                                                                                                                                                                                |                                                                                                                                |
|   <br><br><br>     **Dialogue**        |                              [Qian, et al., ACL’19]<br><br>[Madotto, et al., ACL’19]<br><br>[Mi, et al., IJCAI’19]<br><br>[Song, et al., arXiv’19]                             |                                                                                                                                                                                |                                   <br> <br><br> [Chien, et al., INTERSPEECH’19]<br> (Learning to optimize)                                     |
| <br><br><br>**Relation Classification** |                            [Obamuyide, et al., ACL’19]<br><br>[Bose, et al., arXiv’19]<br><br>[Lv, et al., EMNLP’19]<br><br>[Wang, et al., EMNLP’19]                           |                               [Ye, et al., ACL’19]<br><br>[Chen, et al., EMNLP’19]<br><br>[Xiong, et al., EMNLP’18]<br><br>[Gao, et al., AAAI’19]                              |                                                                                                                                |
|     **Word Embedding**     |                                                                              [Hu, et al., ACL’19]                                                                              |                                                                             [Sun, et al., EMNLP’18]                                                                            |                                                                                                                                |
| <br><br><br><br><br> **More NLP Applications**  | [Guo, et al., ACL’19]<br><br>[Wu, et al., AAAI’20] <br><br>[Zhao, EMNLP’19]<br><br>[Bansal, et al., arXiv’19]<br><br>[Dou, et al., EMNLP’19] <br><br>[Huang, et al., NAACL’18] | [Guo, et al., ACL’19]<br><br>[Wu, et al., AAAI’20] <br><br>[Zhao, EMNLP’19]<br><br>[Bansal, et al., arXiv’19]<br><br>[Dou, et al., EMNLP’19] <br><br>[Huang, et al., NAACL’18] |                                 <br><br><br><br>    [Wu, et al., EMNLP’19]<br>(Learning the learning algorithm)                                    |
|      **Multi-model**       |                                                                                                                                                                                |                                                                           [Eloff, et al., ICASSP’19]                                                                           |                                   [Surís, et al., arXiv’19]<br> (Learning the learning algorithm)                                  |


* **[Anand, et al., arXiv’19]** Prashant Anand, Ajeet Kumar Singh, Siddharth Srivastava, Brejesh Lall, Few Shot Speaker Recognition using Deep Neural Networks, arXiv, 2019
* **[Bansal, et al., arXiv’19]** Trapit Bansal, Rishikesh Jha, Andrew McCallum, Learning to Few-Shot Learn Across Diverse Natural Language Classification Tasks, arXiv, 2019 
* **[Bose, et al., arXiv’19]** Avishek Joey Bose, Ankit Jain, Piero Molino, William L. Hamilton, Meta-Graph: Few shot Link Prediction via Meta Learning, arXiv, 2019 
* **[Chen, et al., arXiv’18]** Yangbin Chen, Tom Ko, Lifeng Shang, Xiao Chen, Xin Jiang, Qing Li, An Investigation of Few-Shot Learning in Spoken Term Classification, arXiv, 2018 
* **[Chen, et al., ICLR’19]** Yutian Chen, Yannis Assael, Brendan Shillingford, David Budden, Scott Reed, Heiga Zen, Quan Wang, Luis C. Cobo, Andrew Trask, Ben Laurie, Caglar Gulcehre, Aäron van den Oord, Oriol Vinyals, Nando de Freitas, Sample Efficient Adaptive Text-to-Speech, ICLR, 2019
* **[Chen, et al., EMNLP’19]** Mingyang Chen, Wen Zhang, Wei Zhang, Qiang Chen, Huajun Chen, Meta Relational Learning for Few-Shot Link Prediction in Knowledge Graphs, EMNLP 2019 
* **[Chien, et al., INTERSPEECH’19]** Jen-Tzung Chien, Wei Xiang Lieow, Meta Learning for Hyperparameter Optimization in Dialogue System, INTERSPEECH, 2019 
* **[Chou, et al., ICASSP’19]** Szu-Yu Chou, Kai-Hsiang Cheng, Jyh-Shing Roger Jang, Yi-Hsuan Yang, Learning to match transient sound events using attentional similarity for few-shot sound recognition, ICASSP 2019 
* **[Dou, et al., EMNLP’19]** Zi-Yi Dou, Keyi Yu, Antonios Anastasopoulos, Investigating Meta-Learning Algorithms for Low-Resource Natural Language Understanding Tasks, EMNLP 2019 
* **[Eloff, et al., ICASSP’19]** Ryan Eloff, Herman A. Engelbrecht, Herman Kamper, MULTIMODAL ONE-SHOT LEARNING OF SPEECH AND IMAGES, ICASSP 2019 
* **[Geng, et al., EMNLP’19]** Ruiying Geng, Binhua Li, Yongbin Li, Xiaodan Zhu, Ping Jian, Jian Sun, Induction Networks for Few-Shot Text Classification, EMNLP, 2019 
* **[Gao, et al., AAAI’19]** Tianyu Gao, Xu Han, Zhiyuan Liu, Maosong Sun, Hybrid Attention-Based Prototypical Networks for Noisy Few-Shot Relation Classification, AAAI 2019 
* **[Gu, et al., EMNLP’18]** Jiatao Gu, Yong Wang, Yun Chen, Kyunghyun Cho, Victor O.K. Li, Meta-Learning for Low-Resource Neural Machine Translation, EMNLP, 2018 
* **[Guo, et al., ACL’19]** Daya Guo, Duyu Tang, Nan Duan, Ming Zhou, Jian Yin, Coupling Retrieval and Meta-Learning for Context-Dependent Semantic Parsing, ACL, 2019
* **[Hsu, et al., ICASSP’20]** Jui-Yang Hsu, Yuan-Jui Chen, Hung-yi Lee, Meta Learning for End-to-End Low-Resource Speech Recognition, ICASSP 2020 
* **[Hu, et al., ACL’19]** Ziniu Hu, Ting Chen, Kai-Wei Chang, Yizhou Sun,  Few-Shot Representation Learning for Out-Of-Vocabulary Words, ACL 2019  
* **[Huang, et al., NAACL’18]** Po-Sen Huang, Chenglong Wang, Rishabh Singh, Wen-tau Yih, Xiaodong He, Natural Language to Structured Query Generation via Meta-Learning, NAACL 2018 
* **[Indurthi, et al., arXiv’19]** Sathish Indurthi, Houjeung Han, Nikhil Kumar Lakumarapu, Beomseok Lee, Insoo Chung, Sangha Kim, Chanwoo Kim, Data Efficient Direct Speech-to-Text Translation with Modality Agnostic Meta-Learning, arXiv’19
* **[Klejch, et al., INTERSPEECH’18]** Ondřej Klejch, Joachim Fainberg, Peter Bell, Learning to adapt: a meta-learning approach for speaker adaptation, INTERSPEECH 2018 
* **[Klejch, et al., ASRU’19]** Ondřej Klejch, Joachim Fainberg, Peter Bell, Steve Renals, Speaker Adaptive Training using Model Agnostic Meta-Learning, ASRU 2019 
* **[Lv, et al., EMNLP’19]** Xin Lv, Yuxian Gu, Xu Han, Lei Hou, Juanzi Li, Zhiyuan Liu,Adapting Meta Knowledge Graph Information for Multi-Hop Reasoning over Few-Shot Relations, EMNLP 2019 
* **[Madotto, et al., ACL’19]** Andrea Madotto, Zhaojiang Lin, Chien-Sheng Wu, Pascale Fung, Personalizing Dialogue Agents via Meta-Learning, ACL 2019 
* **[Mi, et al., IJCAI’19]** Fei Mi, Minlie Huang, Jiyong Zhang, Boi Faltings, Meta-Learning for Low-resource Natural Language Generation in Task-oriented Dialogue Systems, IJCAI 2019 
* **[Obamuyide, et al., ACL’19]** Abiola Obamuyide, Andreas Vlachos, Model-Agnostic Meta-Learning for Relation Classification with Limited Supervision, ACL 2019 
* **[Qian, et al., ACL’19]** Kun Qian, Zhou Yu, Domain Adaptive Dialog Generation via Meta Learning, ACL 2019 
* **[Serrà, et al., NeurIPS’19]** Joan Serrà, Santiago Pascual, Carlos Segura, Blow: a single-scale hyperconditioned flow for non-parallel raw-audio voice conversion, NeurIPS 2019 
* **[Sun, et al., EMNLP’18]** Jingyuan Sun, Shaonan Wang, Chengqing Zong, Memory, Show the Way: Memory Based Few Shot Word Representation Learning, EMNLP 2018
* **[Shimada, et al., arXiv’19]** Kazuki Shimada, Yuichiro Koyama, Akira Inoue, Metric Learning with Background Noise Class for Few-shot Detection of Rare Sound Events, arXiv, 2019 
* **[Song, et al., arXiv’19]** Yiping Song, Zequn Liu, Wei Bi, Rui Yan, Ming Zhang, earning to Customize Language Model for Personalized Conversation Systems, arXiv, 2019 
* **[Sun, et al., EMNLP’19]** Shengli Sun, Qingfeng Sun, Kevin Zhou, Tengchao Lv, Hierarchical Attention Prototypical Networks for Few-Shot Text Classification, EMNLP 2019 
* **[Surís, et al., arXiv’19]** Dídac Surís, Dave Epstein, Heng Ji, Shih-Fu Chang, Carl Vondrick, Learning to Learn Words from Narrated Video, arXiv, 2019 
* **[Tan, et al., EMNLP’19]** Ming Tan, Yang Yu, Haoyu Wang, Dakuo Wang, Saloni Potdar, Shiyu Chang, Mo Yu, Out-of-Domain Detection for Low-Resource Text Classification Tasks, EMNLP 2019 
* **[Wang, et al., EMNLP’19]** Zihao Wang, Kwun Ping Lai, Piji Li, Lidong Bing, Wai Lam, Tackling Long-Tailed Relations and Uncommon Entities in Knowledge Graph Completion, EMNLP 2019 
* **[Wu, et al., EMNLP’19]** Jiawei Wu, Wenhan Xiong, William Yang Wang, Learning to Learn and Predict: A Meta-Learning Approach for Multi-Label Classification, EMNLP 2019 
* **[Wu, et al., AAAI’20]** Qianhui Wu, Zijia Lin, Guoxin Wang, Hui Chen, Börje F. Karlsson, Biqing Huang, Chin-Yew Lin, Enhanced Meta-Learning for Cross-lingual Named Entity Recognition with Minimal Resources, AAAI 2020 
* **[Xiong, et al., EMNLP’18]** Wenhan Xiong, Mo Yu, Shiyu Chang, Xiaoxiao Guo, William Yang Wang, One-Shot Relational Learning for Knowledge Graphs, EMNLP 2018 
* **[Ye, et al., ACL’19]** Zhi-Xiu Ye, Zhen-Hua Ling, Multi-Level Matching and Aggregation Network for Few-Shot Relation Classification, ACL 2019 
* **[Yu, et al., ACL’18]** Mo Yu, Xiaoxiao Guo, Jinfeng Yi, Shiyu Chang, Saloni Potdar, Yu Cheng, Gerald Tesauro, Haoyu Wang, Bowen Zhou, Diverse Few-Shot Text Classification with Multiple Metrics, ACL 2018 
* **[Zhang, et al., INTERSPEECH’19]** Shilei Zhang, Yong Qin, Kewei Sun, Yonghua Lin, Few-Shot Audio Classification with Attentional Graph Neural Networks, INTERSPEECH 2019 
* **[Zhao, EMNLP’19]** Zhenjie Zhao, Xiaojuan Ma, Text Emotion Distribution Learning from Small Sample: A Meta-Learning Approach, EMNLP 2019


<!--* ASR-->
  <!--* Jui-Yang Hsu, Yuan-Jui Chen, Hung-yi Lee, Meta Learning for End-to-End Low-Resource Speech Recognition, ICASSP 2020 -->
  <!--* Ondřej Klejch, Joachim Fainberg, Peter Bell, Learning to adapt: a meta-learning approach for speaker adaptation, INTERSPEECH 2018 -->
  <!--* Ondřej Klejch, Joachim Fainberg, Peter Bell, Steve Renals, Speaker Adaptive Training using Model Agnostic Meta-Learning, ASRU 2019 -->
<!--* Voice cloning-->
  <!--* Yutian Chen, Yannis Assael, Brendan Shillingford, David Budden, Scott Reed, Heiga Zen, Quan Wang, Luis C. Cobo, Andrew Trask, Ben Laurie, Caglar Gulcehre, Aäron van den Oord, Oriol Vinyals, Nando de Freitas, Sample Efficient Adaptive Text-to-Speech, ICLR, 2019 -->
  <!--* Joan Serrà, Santiago Pascual, Carlos Segura, Blow: a single-scale hyperconditioned flow for non-parallel raw-audio voice conversion, NeurIPS 2019-->
<!--* Speaker Recognition:-->
  <!--* Prashant Anand, Ajeet Kumar Singh, Siddharth Srivastava, Brejesh Lall, Few Shot Speaker Recognition using Deep Neural Networks, arXiv, 2019 -->
<!--* Keyword spotting: -->
  <!--* Yangbin Chen, Tom Ko, Lifeng Shang, Xiao Chen, Xin Jiang, Qing Li, An Investigation of Few-Shot Learning in Spoken Term Classification, arXiv, 2018-->
  <!--* Hanna Mazzawi, Javier Gonzalvo, Aleks Kracun, Prashant Sridhar, Niranjan Subrahmanya, Ignacio Lopez Moreno, Hyun Jin Park, Patrick Violette, Improving Keyword Spotting and Language Identification via Neural Architecture Search at Scale, INTERSPEECH, 2019 -->
<!--* Sound event detection:-->
  <!--* Kazuki Shimada, Yuichiro Koyama, Akira Inoue, Metric Learning with Background Noise Class for Few-shot Detection of Rare Sound Events, arXiv, 2019 -->
  <!--* Szu-Yu Chou, Kai-Hsiang Cheng, Jyh-Shing Roger Jang, Yi-Hsuan Yang, Learning to match transient sound events using attentional similarity for few-shot sound recognition, ICASSP 2019-->
  <!--* Shilei Zhang, Yong Qin, Kewei Sun, Yonghua Lin, Few-Shot Audio Classification with Attentional Graph Neural Networks, INTERSPEECH 2019 -->
<!--* Translation: -->
  <!--* Jiatao Gu, Yong Wang, Yun Chen, Kyunghyun Cho, Victor O.K. Li, Meta-Learning for Low-Resource Neural Machine Translation, EMNLP, 2018 -->
<!--* Dialogue Generation:-->
  <!--* Kun Qian, Zhou Yu, Domain Adaptive Dialog Generation via Meta Learning, ACL 2019 -->
  <!--* Andrea Madotto, Zhaojiang Lin, Chien-Sheng Wu, Pascale Fung, Personalizing Dialogue Agents via Meta-Learning, ACL 2019 -->
  <!--* Fei Mi, Minlie Huang, Jiyong Zhang, Boi Faltings, Meta-Learning for Low-resource Natural Language Generation in Task-oriented Dialogue Systems, IJCAI 2019 -->
  <!--* Yiping Song, Zequn Liu, Wei Bi, Rui Yan, Ming Zhang, earning to Customize Language Model for Personalized Conversation Systems, arXiv, 2019 -->
  <!--* Jen-Tzung Chien, Wei Xiang Lieow, Meta Learning for Hyperparameter Optimization in Dialogue System, INTERSPEECH, 2019 -->
<!--* Relation Classification-->
  <!--* Abiola Obamuyide, Andreas Vlachos, Model-Agnostic Meta-Learning for Relation Classification with Limited Supervision, ACL 2019 -->
  <!--* Zhi-Xiu Ye, Zhen-Hua Ling, Multi-Level Matching and Aggregation Network for Few-Shot Relation Classification, ACL 2019 -->
  <!--* Mingyang Chen, Wen Zhang, Wei Zhang, Qiang Chen, Huajun Chen, Meta Relational Learning for Few-Shot Link Prediction in Knowledge Graphs, EMNLP 2019-->
  <!--*  Avishek Joey Bose, Ankit Jain, Piero Molino, William L. Hamilton, Meta-Graph: Few shot Link Prediction via Meta Learning, arXiv, 2019 -->
  <!--* Xin Lv, Yuxian Gu, Xu Han, Lei Hou, Juanzi Li, Zhiyuan Liu,Adapting Meta Knowledge Graph Information for Multi-Hop Reasoning over Few-Shot Relations, EMNLP 2019 -->
  <!--* Wenhan Xiong, Mo Yu, Shiyu Chang, Xiaoxiao Guo, William Yang Wang, One-Shot Relational Learning for Knowledge Graphs, EMNLP 2018 -->
  <!--* Tianyu Gao, Xu Han, Zhiyuan Liu, Maosong Sun, Hybrid Attention-Based Prototypical Networks for Noisy Few-Shot Relation Classification, AAAI. 2019 -->
<!--* Learning word embedding:-->
  <!--* Ziniu Hu, Ting Chen, Kai-Wei Chang, Yizhou Sun,  Few-Shot Representation Learning for Out-Of-Vocabulary Words, ACL 2019 -->
  <!--* Jingyuan Sun, Shaonan Wang, Chengqing Zong, Memory, Show the Way: Memory Based Few Shot Word Representation Learning, EMNLP 2018      -->
<!--* More NLP applications:-->
  <!--* Daya Guo, Duyu Tang, Nan Duan, Ming Zhou, Jian Yin, Coupling Retrieval and Meta-Learning for Context-Dependent Semantic Parsing, ACL, 2019 -->
  <!--* Qianhui Wu, Zijia Lin, Guoxin Wang, Hui Chen, Börje F. Karlsson, Biqing Huang, Chin-Yew Lin, Enhanced Meta-Learning for Cross-lingual Named Entity Recognition with Minimal Resources, AAAI 2020 -->
  <!--* Zhenjie Zhao, Xiaojuan Ma, Text Emotion Distribution Learning from Small Sample: A Meta-Learning Approach, EMNLP 2019  -->
  <!--* Trapit Bansal, Rishikesh Jha, Andrew McCallum, Learning to Few-Shot Learn Across Diverse Natural Language Classification Tasks, arXiv, 2019 -->
  <!--* Jiawei Wu, Wenhan Xiong, William Yang Wang, Learning to Learn and Predict: A Meta-Learning Approach for Multi-Label Classification, EMNLP 2019 -->
  <!--* Shengli Sun, Qingfeng Sun, Kevin Zhou, Tengchao Lv, Hierarchical Attention Prototypical Networks for Few-Shot Text Classification, EMNLP 2019 -->
  <!--* Ruiying Geng, Binhua Li, Yongbin Li, Xiaodan Zhu, Ping Jian, Jian Sun, Induction Networks for Few-Shot Text Classification, EMNLP, 2019 -->
  <!--* Mo Yu, Xiaoxiao Guo, Jinfeng Yi, Shiyu Chang, Saloni Potdar, Yu Cheng, Gerald Tesauro, Haoyu Wang, Bowen Zhou, Diverse Few-Shot Text Classification with Multiple Metrics, ACL 2018 -->
  <!--* Ming Tan, Yang Yu, Haoyu Wang, Dakuo Wang, Saloni Potdar, Shiyu Chang, Mo Yu, Out-of-Domain Detection for Low-Resource Text Classification Tasks, EMNLP 2019 -->
  <!--* Po-Sen Huang, Chenglong Wang, Rishabh Singh, Wen-tau Yih, Xiaodong He, Natural Language to Structured Query Generation via Meta-Learning, NAACL 2018 -->
  <!--* Zi-Yi Dou, Keyi Yu, Antonios Anastasopoulos, Investigating Meta-Learning Algorithms for Low-Resource Natural Language Understanding Tasks, EMNLP 2019 -->
<!--* Multi-model-->
  <!--* Ryan Eloff, Herman A. Engelbrecht, Herman Kamper, MULTIMODAL ONE-SHOT LEARNING OF SPEECH AND IMAGES, ICASSP 2019 -->
  <!--* Dídac Surís, Dave Epstein, Heng Ji, Shih-Fu Chang, Carl Vondrick, Learning to Learn Words from Narrated Video, arXiv, 2019-->

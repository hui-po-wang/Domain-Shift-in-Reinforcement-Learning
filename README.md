# Domain-Shift-in-Reinforcement-Learning
A compilation of domain-shift related papers in reinforcement learning

## Contents
- [Domain Adaption](#domain-adaption)
- [Domain Shift in Reinforcement Learning](#domain-shift-in-reinforcement-learning)
  - [Inverse Dynamic Model](#inverse-dynamic-model)
  - [Domain Randomization](#domain-randomization)
- [Segmentation](#segmentation)
- [Hierarchical Reinforcement Learning](#hierarchical-reinforcement-learning)
- [Meta-Learning](#meta-learning)
- [Transfer-Learning](#transfer-learning)
- [Few-Shot Learning](#few-shot-learning)
- [Evaluating Performance of Policies](#evaluating-performance-of-policies)
- [Self-Training](#self-training)
- [Research Blogs](#research-blogs)
- [Datasets](#datasets)
- [Clustering](#clustering)
- [Others](#others)
- [Key Papers](#key-papers)
- [TO-DOs](#to-dos)

## Domain Adaption
- Awesome Transfer Learning [[github]](https://github.com/artix41/awesome-transfer-learning)
- (HP) A DIRT-T Approach to Unsupervised Domain Adaptation [[pdf]](https://openreview.net/forum?id=H1q-TM-AW&noteId=H1q-TM-AW)[[slides]](https://drive.google.com/open?id=1UIoeAMqClAcPnXTZIpLaX3pUUqB2dVLD)
  - Rui Shu, Hung Bui, Hirokazu Narui, Stefano Ermon. ICLR'18
- Learning Transferrable Representations for Unsupervised Domain Adaptation [[pdf]](https://papers.nips.cc/paper/6360-learning-transferrable-representations-for-unsupervised-domain-adaptation)
  - Ozan Sener, Hyun Oh Song, Ashutosh Saxena, Silvio Savarese. NIPS'16
- (WC) Domain Separation Networks [[pdf]](https://arxiv.org/abs/1608.06019)
  - Konstantinos Bousmalis, George Trigeorgis, Nathan Silberman, Dilip Krishnan, Dumitru Erhan. NIPS'16
- Unsupervised Domain Adaptation with Residual Transfer Networks [[pdf]](https://arxiv.org/abs/1602.04433)
  - Mingsheng Long, Han Zhu, Jianmin Wang, Michael I. Jordan. NIPS'16
- (HP) Multi-Adversarial Domain Adaptation. [[pdf]](http://ise.thss.tsinghua.edu.cn/~mlong/doc/multi-adversarial-domain-adaptation-aaai18.pdf)[[slides]](https://drive.google.com/file/d/1yWJSIg8uDGwo36FgHIv4uQKjF02HysTi/view?usp=sharing)
   - Zhongyi Pei, Zhangjie Cao, Mingsheng Long, and Jianmin Wang. AAAI'18
- (HP) Multimodal Unsupervised Image-to-Image Translation [[pdf]](https://arxiv.org/abs/1804.04732)[[slides]](https://drive.google.com/file/d/1T0_5RWP8rNW7DTqmmD38D1PKI1agaYlc/view?usp=sharing)
  - Xun Huang, Ming-Yu Liu, Serge Belongie, Jan Kautz. arXiv'18
- Learning to cluster in order to transfer across domains and tasks [[pdf]](https://arxiv.org/abs/1711.10125) ---> already presented by Prof.Chiu
  - Yen-Chang Hsu, Zhaoyang Lv, Zsolt Kira. ICLR'18
- (HP) Unupervised Domain Adaptation by Backpropagation [[pdf]](https://arxiv.org/abs/1409.7495)
  - Yaroslav Ganin, Victor Lempitsky. arXiv'14  - Eric Tzeng, Judy Hoffman, Kate Saenko, Trevor Darrell. CVPR'17
- (WC) Unsupervised Pixel-Level Domain Adaptation with Generative Adversarial Networks [[pdf]](https://arxiv.org/abs/1612.05424)
  - Konstantinos Bousmalis, Nathan Silberman, David Dohan, Dumitru Erhan, Dilip Krishnan. CVPR'17
- (BS) Revisiting Batch Normalization For Practical Domain Adaptation [[pdf]](https://arxiv.org/abs/1603.04779) [[ppt]](https://drive.google.com/open?id=1BuamHVPxgzEk-EJFurmg2YOd1NtOK2_F)
  - Yanghao Li, Naiyan Wang, Jianping Shi, Jiaying Liu, Xiaodi Hou. ICLR'17 WorkShop
- (WC) CyCADA: Cycle-Consistent Adversarial Domain Adaptation [[pdf]](https://arxiv.org/abs/1711.03213)
  - Judy Hoffman, Eric Tzeng, Taesung Park, Jun-Yan Zhu, Phillip Isola, Kate Saenko, Alexei A. Efros, Trevor Darrell. arXiv'17
- (HP) Arbitrary Style Transfer in Real-time with Adaptive Instance Normalization [[pdf]](https://arxiv.org/abs/1703.06868)
  - Xun Huang, Serge Belongie. ICCV'17
- Curriculum Domain Adaptation for Semantic Segmentation of Urban Scenes [[pdf]](https://arxiv.org/abs/1707.09465)
  - Yang Zhang, Philip David, Boqing Gong. ICCV'17
- (HP) Associative Domain Adaptation [[pdf]](https://arxiv.org/abs/1708.00938)[[slides]](https://drive.google.com/file/d/1vAAd87nyKIuXgL0RsPqVjhmg4o-EKJXW/view?usp=sharing)
  - Philip Haeusser, Thomas Frerix, Alexander Mordvintsev, Daniel Cremers. ICCV'17
- (WC) Cross-Domain Self-supervised Multi-task Feature Learning using Synthetic Imagery [[pdf]](https://arxiv.org/pdf/1711.09082.pdf)
  - Zhongzheng Ren and Yong Jae Lee. CVPR'18
- (BS) Simulated+Unsupervised Learning With Adaptive Data Generation and Bidirectional Mappings [[pdf]](https://openreview.net/forum?id=SkHDoG-Cb)
  - Kangwook Lee, Hoon Kim, Changho Suh. ICLR'18
- (WC) Deep CORAL: Correlation Alignment for Deep Domain Adaptation [[pdf]](https://arxiv.org/abs/1607.01719)
  - Baochen Sun, Kate Saenko. ECCV'16
- Self-ensembling for visual domain adaptation [[pdf]](https://openreview.net/forum?id=rkpoTaxA-)
  - Geoff French, Michal Mackiewicz, Mark Fisher. ICLR'18
- (WC) Minimal-Entropy Correlation Alignment for Unsupervised Deep Domain Adaptation [[pdf]](https://openreview.net/forum?id=rJWechg0Z)
  - Pietro Morerio, Jacopo Cavazza, Vittorio Murino. ICLR'18
- Multiple Source Domain Adaptation with Adversarial Learning [[pdf]](https://openreview.net/forum?id=ryDNZZZAW)
  - Han Zhao, Shanghang Zhang, Guanhang Wu, Jo\~{a}o P. Costeira, Jos\'{e} M. F. Moura, Geoffrey J. Gordon. ICLR'18
- Generalizing Across Domains via Cross-Gradient Training [[pdf]](https://openreview.net/forum?id=r1Dx7fbCW)
  - Shiv Shankar*, Vihari Piratla*, Soumen Chakrabarti, Siddhartha Chaudhuri, Preethi Jyothi, Sunita Sarawagi. ICLR'18
- Identifying Analogies Across Domains [[pdf]](https://openreview.net/forum?id=BkN_r2lR-)
  - Yedid Hoshen, Lior Wolf. ICLR'18
- AdaDepth: Unsupervised Content Congruent Adaptation for Depth Estimation [[pdf]](https://arxiv.org/pdf/1803.01599)
  - Jogendra Nath Kundu, Phani Krishna Uppala, Anuj Pahuja, R. Venkatesh Babu. CVPR'18
- (WC) Maximum Classifier Discrepancy for Unsupervised Domain Adaptation [[pdf]](https://arxiv.org/pdf/1712.02560)
  - Kuniaki Saito, Kohei Watanabe, Yoshitaka Ushiku, Tatsuya Harada. CVPR'18
- Boosting Domain Adaptation by Discovering Latent Domains [[pdf]](http://research.mapillary.com/img/publications/CVPR18b.pdf)
  - Massimiliano Mancini, Lorenzo Porzi, Samuel Rota Bulò, Barbara Caputo, Elisa Ricci. CVPR'18
- Collaborative and Adversarial Network for Unsupervised Domain Adaptation (pdf-404)
  - Weichen Zhang, Wanli Ouyang, Wen Li, Dong Xu. CVPR'18
- (WC) Generate To Adapt: Aligning Domains using Generative Adversarial Networks [[pdf]](https://arxiv.org/pdf/1704.01705)
  - Swami Sankaranarayanan, Yogesh Balaji, Carlos D. Castillo, Rama Chellappa. CVPR'18
- (WC) Detach and Adapt: Learning Cross-Domain Disentangled Deep Representation [[pdf]](https://arxiv.org/pdf/1705.01314)
  - Yen-Cheng Liu, Yu-Ying Yeh, Tzu-Chien Fu, Sheng-De Wang, Wei-Chen Chiu, Yu-Chiang Frank Wang. CVPR'18
- (WC) Learning from Synthetic Data: Addressing Domain Shift for Semantic Segmentation [[pdf]](https://arxiv.org/pdf/1711.06969)
  - Swami Sankaranarayanan, Yogesh Balaji, Arpit Jain, Ser Nam Lim, Rama Chellappa. CVPR'18
- Image-Image Domain Adaptation With Preserved Self-Similarity and Domain-Dissimilarity for Person Re-Identification [[pdf]](https://arxiv.org/pdf/1711.07027)
  - Weijian Deng, Liang Zheng, Guoliang Kang, Yi Yang, Qixiang Ye, Jianbin Jiao. CVPR'18
- (WC) Duplex Generative Adversarial Network for Unsupervised Domain Adaptation [[pdf]](http://vipl.ict.ac.cn/uploadfile/upload/2018041610083083.pdf)
  - Lanqing Hu, Meina Kan, Shiguang Shan, Xilin Chen. CVPR'18
- Real-Time Monocular Depth Estimation Using Synthetic Data With Domain Adaptation via Image Style Transfer [[pdf]](http://breckon.eu/toby/publications/papers/abarghouei18monocular.pdf)
  - Amir Atapour-Abarghouei, Toby P. Breckon. CVPR'18
- Domain Adaptive Faster R-CNN for Object Detection in the Wild [[pdf]](https://arxiv.org/pdf/1803.03243)
  - Yuhua Chen, Wen Li, Christos Sakaridis, Dengxin Dai, Luc Van Gool. CVPR'18
- Aligning Infinite-Dimensional Covariance Matrices in Reproducing Kernel Hilbert Spaces for Domain Adaptation (pdf-404)
  - Zhen Zhang, Mianzhi Wang, Yan Huang, Arye Nehorai. CVPR'18
- Deep Cocktail Network: Multi-Source Unsupervised Domain Adaptation With Category Shift [[pdf]](https://arxiv.org/pdf/1803.00830)
  - Ruijia Xu, Ziliang Chen, Wangmeng Zuo, Junjie Yan, Liang Lin. CVPR'18
- Residual Parameter Transfer for Deep Domain Adaptation [[pdf]](https://arxiv.org/pdf/1711.07714)
  - Artem Rozantsev, Mathieu Salzmann, Pascal Fua. CVPR'18
- (Stefanie) Image to Image Translation for Domain Adaptation [[pdf]](https://arxiv.org/pdf/1712.00479)
  - Zak Murez, Soheil Kolouri, David Kriegman, Ravi Ramamoorthi, Kyungnam Kim. CVPR'18
- Cross-Domain Weakly-Supervised Object Detection Through Progressive Domain Adaptation [[pdf]](https://arxiv.org/pdf/1803.11365)
  - Naoto Inoue, Ryosuke Furuta, Toshihiko Yamasaki, Kiyoharu Aizawa. CVPR'18
- Camera Style Adaptation for Person Re-Identification [[pdf]](https://arxiv.org/pdf/1711.10295)
  - Zhun Zhong, Liang Zheng, Zhedong Zheng, Shaozi Li, Yi Yang. CVPR'18
- Adversarial Feature Augmentation for Unsupervised Domain Adaptation [[pdf]](https://arxiv.org/pdf/1711.08561)
  - Riccardo Volpi, Pietro Morerio, Silvio Savarese, Vittorio Murino. CVPR'18
- Fully Convolutional Adaptation Networks for Semantic Segmentation [[pdf]](https://arxiv.org/pdf/1804.08286)
  - Yiheng Zhang, Zhaofan Qiu, Ting Yao, Dong Liu, Tao Mei. CVPR'18
- ROAD: Reality Oriented Adaptation for Semantic Segmentation of Urban Scenes [[pdf]](https://arxiv.org/pdf/1711.11556)
  - Yuhua Chen, Wen Li, Luc Van Gool. CVPR'18
- Re-Weighted Adversarial Adaptation Network for Unsupervised Domain Adaptation (pdf-404)
  - Qingchao Chen, Yang Liu, Zhaowen Wang, Ian Wassell, Kevin Chetty. CVPR'18
- Unsupervised Domain Adaptation with Similarity Learning [[pdf]](https://arxiv.org/pdf/1711.08995)
  - Pedro O. Pinheiro. CVPR'18
- People, Penguins and Petri Dishes: Adapting Object Counting Models To New Visual Domains And Object Types Without Forgetting [[pdf]](https://arxiv.org/pdf/1711.05586)
  - Mark Marsden, Kevin McGuinness, Suzanne Little, Ciara E. Keogh, Noel E. O'Connor. CVPR'18
- From Source to Target and Back: Symmetric Bi-Directional Adaptive GAN [[pdf]](https://arxiv.org/pdf/1705.08824)
    - Paolo Russo, Fabio Maria Carlucci, Tatiana Tommasi, Barbara Caputo. CVPR'18
- Importance Weighted Adversarial Nets for Partial Domain Adaptation [[pdf]](https://arxiv.org/pdf/1803.09210)
  - Jing Zhang, Zewei Ding, Wanqing Li, Philip Ogunbona. CVPR'18
- (WC) Cross-Domain Self-Supervised Multi-Task Feature Learning Using Synthetic Imagery [[pdf]](https://arxiv.org/pdf/1711.09082.pdf)
  - Zhongzheng Ren, Yong Jae Lee. CVPR'18
- Zoom and Learn: Generalizing Deep Stereo Matching to Novel Domains [[pdf]](https://arxiv.org/pdf/1803.06641)
  - Jiahao Pang, Wenxiu Sun, Chengxi Yang, Jimmy Ren, Ruichao Xiao, Jin Zeng, Liang Lin. CVPR'18
- Efficient parametrization of multi-domain deep neural networks [[pdf]](https://arxiv.org/pdf/1803.10082)
  - Sylvestre-Alvise Rebuffi, Hakan Bilen, Andrea Vedaldi. CVPR'18
- Domain Generalization With Adversarial Feature Learning (pdf-404)
  - Haoliang Li, Sinno Jialin Pan, Shiqi Wang, Alex C. Kot. CVPR'18
- (HP) Label Efficient Learning of Transferable Representations acrosss Domains and Tasks [[pdf]](https://arxiv.org/abs/1712.00123)
  - Zelun Luo, Yuliang Zou, Judy Hoffman, Li Fei-Fei. NIPS'17
- Adversarial Discriminative Domain Adaptation [[pdf]](https://arxiv.org/abs/1702.05464)
  - Eric Tzeng, Judy Hoffman, Kate Saenko, Trevor Darrell. CVPR'17
- AugGAN: Cross Domain Adaptation with GAN-based Data Augmentation [[pdf]](http://openaccess.thecvf.com/content_ECCV_2018/html/Sheng-Wei_Huang_AugGAN_Cross_Domain_ECCV_2018_paper.html)
  - Sheng-Wei Huang, Che-Tsung Lin, Shu-Ping Chen, Yen-Yi Wu, Po-Hao Hsu, Shang-Hong Lai. ECCV'18
- Partial Adversarial Domain Adaptation [[pdf]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Zhangjie_Cao_Partial_Adversarial_Domain_ECCV_2018_paper.pdf)
  - Zhangjie Cao, Lijia Ma, Mingsheng Long, Jianmin Wang. ECCV'18
- DeepJDOT: Deep Joint Distribution Optimal Transport for Unsupervised Domain Adaptation [[pdf]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Bharath_Bhushan_Damodaran_DeepJDOT_Deep_Joint_ECCV_2018_paper.pdf)
  - Bharath Bhushan Damodaran, Benjamin Kellenberger, Remi Flamary, Devis Tuia, Nicolas Courty. ECCV'18
- Domain Adaptation through Synthesis forUnsupervised Person Re-identification [[pdf]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Slawomir_Bak_Domain_Adaptation_through_ECCV_2018_paper.pdf)
  - Slawomir Bak, Peter Carr, Jean-Francois Lalonde. ECCV'18
- Open Set Domain Adaptation by Backpropagation [[pdf]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Kuniaki_Saito_Adversarial_Open_Set_ECCV_2018_paper.pdf)
  - Kuniaki Saito, Shohei Yamamoto, Yoshitaka Ushiku, Tatsuya Harada. ECCV'18
- Deep Adversarial Attention Alignment forUnsupervised Domain Adaptation:the Benefit of Target Expectation Maximization [[pdf]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Guoliang_Kang_Deep_Adversarial_Attention_ECCV_2018_paper.pdf)
  - Guoliang Kang, Liang Zheng, Yan Yan, Zikun Liu, Yi Yang. ECCV'18
  
## Segmentation
- Blazingly Fast Video Object Segmentation with Pixel-Wise Metric Learning [[pdf]](https://arxiv.org/abs/1804.03131)
  - Yuhua Chen, Jordi Pont-Tuset, Alberto Montes, Luc Van Gool. CVPR'18
- Learning a Discriminative Feature Network for Semantic Segmentation [[pdf]](https://arxiv.org/abs/1804.09337)
  - Changqian Yu, Jingbo Wang, Chao Peng, Changxin Gao, Gang Yu, Nong Sang. CVPR'18
- Revisiting Dilated Convolution: A Simple Approach for Weakly- and Semi-Supervised Semantic Segmentation [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/html/Wei_Revisiting_Dilated_Convolution_CVPR_2018_paper.html)
  - Yunchao Wei, Huaxin Xiao, Honghui Shi, Zequn Jie, Jiashi Feng, Thomas S. Huang. CVPR'18
### Semantic Segmentation
- DenseASPP for Semantic Segmentation in Street Scenes [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/html/Yang_DenseASPP_for_Semantic_CVPR_2018_paper.html)
  - Maoke Yang, Kun Yu, Chi Zhang, Zhiwei Li, Kuiyuan Yang. CVPR'18
- Dense Decoder Shortcut Connections for Single-Pass Semantic Segmentation [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/html/Bilinski_Dense_Decoder_Shortcut_CVPR_2018_paper.html)
  - Piotr Bilinski, Victor Prisacariu. CVPR'18
- Context Encoding for Semantic Segmentation [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/html/Zhang_Context_Encoding_for_CVPR_2018_paper.html)
  - Hang Zhang, Kristin Dana, Jianping Shi, Zhongyue Zhang, Xiaogang Wang, Ambrish Tyagi, Amit Agrawal. CVPR'18
- 3D Semantic Segmentation With Submanifold Sparse Convolutional Networks [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Graham_3D_Semantic_Segmentation_CVPR_2018_paper.pdf)
  - Benjamin Graham, Martin Engelcke, Laurens van der Maaten. CVPR'18
- ExFuse: Enhancing Feature Fusion for Semantic Segmentation [[pdf]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Zhenli_Zhang_ExFuse_Enhancing_Feature_ECCV_2018_paper.pdf)
   - Zhenli Zhang, Xiangyu Zhang, Chao Peng, Xiangyang Xue, Jian Sun. ECCV'18
### Domain Transfer for Semantic Segmentation
- (HP) Learning from Synthetic Data: Addressing Domain Shift for Semantic Segmentation [[pdf]](https://arxiv.org/abs/1711.06969)
  - Swami Sankaranarayanan, Yogesh Balaji, Arpit Jain, Ser Nam Lim, Rama Chellappa. CVPR'18
- (HP) Fully Convolutional Adaptation Networks for Semantic Segmentation [[pdf]](https://arxiv.org/abs/1804.08286)
  - Yiheng Zhang, Zhaofan Qiu, Ting Yao, Dong Liu, Tao Mei. CVPR'18
- (HP) Conditional Generative Adversarial Network for Structured Domain Adaptation [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/html/Hong_Conditional_Generative_Adversarial_CVPR_2018_paper.html)
  - Weixiang Hong, Zhenzhen Wang, Ming Yang, Junsong Yuan. CVPR'18
- (WC, HP) Learning to Adapt Structured Output Space for Semantic Segmentation [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/html/Tsai_Learning_to_Adapt_CVPR_2018_paper.html)
  - Yi-Hsuan Tsai, Wei-Chih Hung, Samuel Schulter, Kihyuk Sohn, Ming-Hsuan Yang, Manmohan Chandraker. CVPR'18
- (HP) ROAD: Reality Oriented Adaptation for Semantic Segmentation of Urban Scenes [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/html/Chen_ROAD_Reality_Oriented_CVPR_2018_paper.html)
  - Yuhua Chen, Wen Li, Luc Van Gool. CVPR'18
- (WC, HP) DCAN: Dual Channel-wise Alignment Networks for Unsupervised Scene Adaptation [[pdf]](http://openaccess.thecvf.com/content_ECCV_2018/html/Zuxuan_Wu_DCAN_Dual_Channel-wise_ECCV_2018_paper.html)
  - Zuxuan Wu, Xintong Han, Yen-Liang Lin, Mustafa Gokhan Uzunbas, Tom Goldstein, Ser Nam Lim, Larry S. Davis. ECCV'18
- (WC, HP) Effective Use of Synthetic Data forUrban Scene Semantic Segmentation [[pdf]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Fatemeh_Sadat_Saleh_Effective_Use_of_ECCV_2018_paper.pdf)
  - Fatemeh Sadat Saleh, Mohammad Sadegh Aliakbarian, Mathieu Salzmann, Lars Petersson, Jose M. Alvarez. ECCV'18
- (WC, HP) Penalizing Top Performers: Conservative Loss for Semantic Segmentation Adaptation [[pdf]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Xinge_Zhu_Penalizing_Top_Performers_ECCV_2018_paper.pdf)
  - Xinge Zhu, Hui Zhou, Ceyuan Yang, Jianping Shi, Dahua Lin. ECCV'18
- (WC, HP) Unsupervised Domain Adaptation for Semantic Segmentation via Class-Balanced Self-Training [[pdf]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yang_Zou_Unsupervised_Domain_Adaptation_ECCV_2018_paper.pdf)
  - Yang Zou, Zhiding Yu, B.V.K. Vijaya Kumar, Jinsong Wang. ECCV'18
  
### Domain Transfer for Depth Estimation
- AdaDepth: Unsupervised Content Congruent Adaptation for Depth Estimation [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/html/Kundu_AdaDepth_Unsupervised_content_cvpr_2018_paper.html)
  - Jogendra Nath Kundu, Phani Krishna Uppala, Anuj Pahuja, R. Venkatesh Babu. CVPR'18
- Real-Time Monocular Depth Estimation Using Synthetic Data With Domain Adaptation via Image Style Transfer [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/html/Atapour-Abarghouei_Real-Time_Monocular_Depth_CVPR_2018_paper.html)
  - Amir Atapour-Abarghouei, Toby P. Breckon. CVPR'18
### From higher level information (classification) to lower level information (segmentation)
- Multi-Evidence Filtering and Fusion for Multi-Label Classification, Object Detection and Semantic Segmentation Based on Weakly Supervised Learning [[pdf]](https://arxiv.org/abs/1802.09129)
  - Weifeng Ge, Sibei Yang, Yizhou Yu. CVPR'18
- Weakly-Supervised Semantic Segmentation by Iteratively Mining Common Object Features [[pdf]](https://arxiv.org/abs/1806.04659)
  - Xiang Wang, Shaodi You, Xi Li, Huimin Ma. CVPR'18
- Bootstrapping the Performance of Webly Supervised Semantic Segmentation [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/html/Shen_Bootstrapping_the_Performance_CVPR_2018_paper.html)
  - Tong Shen, Guosheng Lin, Chunhua Shen, Ian Reid. CVPR'18
- On the Importance of Label Quality for Semantic Segmentation [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/html/Zlateski_On_the_Importance_CVPR_2018_paper.html)
  - Aleksandar Zlateski, Ronnachai Jaroensri, Prafull Sharma, Frédo Durand. CVPR'18
- Normalized Cut Loss for Weakly-supervised CNN Segmentation [[pdf]](https://arxiv.org/abs/1804.01346)
  - Meng Tang, Abdelaziz Djelouah, Federico Perazzi, Yuri Boykov, Christopher Schroers. CVPR'18
- Weakly Supervised Instance Segmentation using Class Peak Response [[pdf]](https://arxiv.org/abs/1804.00880)
  - Yanzhao Zhou, Yi Zhu, Qixiang Ye, Qiang Qiu, Jianbin Jiao. CVPR'18
- Learning Pixel-level Semantic Affinity with Image-level Supervision for Weakly Supervised Semantic Segmentation [[pdf]](https://arxiv.org/abs/1803.10464)
  - Jiwoon Ahn, Suha Kwak. CVPR'18
- Instance Embedding Transfer to Unsupervised Video Object Segmentation [[pdf]](https://arxiv.org/abs/1801.00908)
  - Siyang Li, Bryan Seybold, Alexey Vorobyov, Alireza Fathi, Qin Huang, C.-C. Jay Kuo. CVPR'18
- Weakly-Supervised Semantic Segmentation Network with Deep Seeded Region Growing [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Huang_Weakly-Supervised_Semantic_Segmentation_CVPR_2018_paper.pdf)
  - Zilong Huang, Xinggang Wang, Jiasi Wang, Wenyu Liu, Jingdong Wang. CVPR'18
  
## Domain Shift in Reinforcement Learning
- DARLA: Improving Zero-Shot Transfer in Reinforcement Learning [[pdf]](https://arxiv.org/abs/1707.08475)
  - Irina Higgins, Arka Pal, Andrei A. Rusu, Loic Matthey, Christopher P Burgess, Alexander Pritzel, Matthew Botvinick, Charles Blundell, Alexander Lerchner. ICML'17
- Learning to Imagine Manipulation Goals for Robot Task Planning [[pdf]](https://arxiv.org/abs/1711.02783)
  - Chris Paxton, Kapil Katyal, Christian Rupprecht, Raman Arora, Gregory D. Hager. arXiv'17
- (Stanley)Hierarchical and Interpretable Skill Acquisition in Multi-task Reinforcement Learning [[pdf]](https://openreview.net/forum?id=SJJQVZW0b)
  - Tianmin Shu, Caiming Xiong, Richard Socher. ICLR'18
- (WC) Learning Robust Rewards with Adverserial Inverse Reinforcement Learning [[pdf]](https://openreview.net/forum?id=rkHywl-A-)
  - Justin Fu, Katie Luo, Sergey Levine. ICLR'18
- (WC) Adapting Deep Visuomotor Representations with Weak Pairwise Constraints [[pdf]](https://arxiv.org/abs/1511.07111) [[ppt]](https://drive.google.com/file/d/1w9jSR7tRiUAQhKRjkiOZUPB0XPU_uAYv/view?usp=sharing)
  - Eric Tzeng, Coline Devin, Judy Hoffman, Chelsea Finn, Pieter Abbeel, Sergey Levine, Kate Saenko, Trevor Darrell. WAFR'16
- Virtual to Real Reinforcement Learning for Autonomous Driving
  - Y You, X Pan, Z Wang, C Lu. arXiv'17
- From virtual demonstration to real-world manipulation using LSTM and MDN [[pdf]](https://arxiv.org/abs/1603.03833)
  - Rouhollah Rahmatizadeh, Pooya Abolghasemi, Aman Behal, Ladislau Bölöni. AAAI'18
- (HP) Bridging the Gap Between Simulation and Reality [[pdf]](http://www.ifaamas.org/Proceedings/aamas2017/pdfs/p1834.pdf)
  - Josiah P. Hanna
- Grounded Action Transformation for Robot Learning in Simulation [[pdf]](http://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/download/14993/14107)
  - JP Hanna, P Stone. AAAI'17
 - (BS)Learning to Navigate in Cities Without a Map [[pdf]](https://arxiv.org/pdf/1804.00168.pdf) [[ppt]](https://drive.google.com/open?id=1X_6918HuXCG69fEWdg0mQNewzn6o3vZd)
    - DeepMind. arXiv'18
### Inverse Dynamic Model
- (HP) Transfer from Simulation to Real World through Learning Deep Inverse Dynamics Model [[pdf]](https://arxiv.org/abs/1610.03518) [[slides]](https://www.cs.toronto.edu/~duvenaud/courses/csc2541/slides/deeprl-inverse.pdf)
  - Paul Christiano, Zain Shah, Igor Mordatch, Jonas Schneider, Trevor Blackwell, Joshua Tobin, Pieter Abbeel, Wojciech Zaremba. arXiv'16
### Domain Randomization
- (HP) Domain Randomization for Transferring Deep Neural Networks from Simulation to the Real World [[pdf]](https://arxiv.org/abs/1703.06907)
  - Josh Tobin, Rachel Fong, Alex Ray, Jonas Schneider, Wojciech Zaremba, Pieter Abbeel. IROS'17

## Hierarchical Reinforcement Learning
- (Stanley)Hierarchical Deep Reinforcement Learning: Integrating Temporal Abstraction and Intrinsic Motivation [[pdf]](https://arxiv.org/abs/1604.06057)
  - Tejas D. Kulkarni, Karthik R. Narasimhan, Ardavan Saeedi, Joshua B. Tenenbaum. NIPS'16
- Learning an Embedding Space for Transferable Robot Skills [[pdf]](https://openreview.net/forum?id=rk07ZXZRb)
  - Karol Hausman, Jost Tobias Springenberg, Ziyu Wang, Nicolas Heess, Martin Riedmiller. ICLR'18

## Meta-Learning
- **Awesome meta-learning** [[link]](https://github.com/songrotek/Meta-Learning-Papers)
- Meta Learning Shared Hierachies [[pdf]](https://openreview.net/forum?id=SyX0IeWAW)
  - Kevin Frans, Jonathan Ho, Xi Chen, Pieter Abbeel, John Schulman. ICLR'18
- (WC) Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks [[pdf]](http://arxiv.org/abs/1703.03400) [[ppt]](https://drive.google.com/file/d/1R4mPfeLyvHeHUP4TI0-7Sp33JNhqvZTp/view?usp=sharing)
  - Chelsea Finn, Pieter Abbeel, Sergey Levine. ICML'17
- (Stefanie) Prototypical Networks for Few-shot Learning [[pdf]](https://arxiv.org/abs/1703.05175)
  - Jake Snell, Kevin Swersky, Richard S. Zemel. arXiv'17
- (Stefanie) Meta-Learning for Semi-Supervised Few-Shot Classification [[pdf]](https://openreview.net/forum?id=HJcSzz-CZ)
  - Mengye Ren, Eleni Triantafillou, Sachin Ravi, Jake Snell, Kevin Swersky, Joshua B. Tenenbaum, Hugo Larochelle, Richard S. Zemel. ICLR'18
- Learning to learn by gradient descent by gradient descent [[pdf]](https://arxiv.org/abs/1606.04474)
  - Marcin Andrychowicz, Misha Denil, Sergio Gomez, Matthew W. Hoffman, David Pfau, Tom Schaul, Brendan Shillingford, Nando de Freitas. arXiv'16

## Transfer Learning
- Learning Invariant Feature Spaces to Transfer Skills with Reinforcement Learning [[pdf]](https://arxiv.org/abs/1703.02949)
  - Abhishek Gupta, Coline Devin, YuXuan Liu, Pieter Abbeel, Sergey Levine. ICLR'17
- Improving Deep Reinforcement Learning with Knowledge Transfer [[pdf]](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14787)
  - Ruben Glatt, Anna Helena Reali Costa. AAAI'17
- Towards Knowledge Transfer in Deep Reinforcement Learning [[pdf]](http://ieeexplore.ieee.org/document/7839568/)
  - Ruben Glatt, Felipe Leno da Silva, and Anna Helena Reali Costa.
- Pose-Robust Face Recognition via Deep Residual Equivariant Mapping [[pdf]](https://arxiv.org/abs/1803.00839)
  - Kaidi Cao, Yu Rong, Cheng Li, Xiaoou Tang, Chen Change Loy. CVPR'18
- (BS) Simultaneous Deep Transfer Across Domains and Tasks [[pdf]](https://arxiv.org/abs/1510.02192) [[ppt]](https://drive.google.com/open?id=1ER1esKm0TE_nN2-x7h43PJIAR8qdfaHr)
  - Eric Tzeng, Judy Hoffman, Trevor Darrell, Kate Saenko. ICCV'15
- How transferable are features in deep neural networks? [[pdf]](https://arxiv.org/abs/1411.1792)
  - Jason Yosinski, Jeff Clune, Yoshua Bengio, Hod Lipson. NIPS'14
- (BS) Partial Transfer Learning With Selective Adversarial Networks. [[pdf]](https://arxiv.org/pdf/1707.07901.pdf)
  - Zhangjie Cao, Mingsheng Long, Jianmin Wang, Michael I. Jordan. CVPR'18
- (HP) Taskonomy: Disentangling Task Transfer Learning. [[pdf]](https://arxiv.org/pdf/1804.08328)
  - Amir Zamir, Alexander Sax, William Shen, Leonidas Guibas, Jitendra Malik, Silvio Savarese. CVPR'18-oral
- Unsupervised Cross-dataset Person Re-identification by Transfer Learning of Spatial-Temporal Patterns [[pdf]](https://arxiv.org/pdf/1803.07293)
  - Jianming Lv, Weihang Chen, Qing Li, Can Yang. CVPR'18
- Learning Transferable Architectures for Scalable Image Recognition [[pdf]](https://arxiv.org/pdf/1707.07012)
  - Barret Zoph, Vijay Vasudevan, Jonathon Shlens, Quoc V. Le. CVPR'18-oral
- Deep Cross-media Knowledge Transfer [[pdf]](https://arxiv.org/pdf/1803.03777)
  - Xin Huang, Yuxin Peng. CVPR'18-oral
- Feature Space Transfer for Data Augmentation [[pdf]](https://arxiv.org/pdf/1801.04356)
  - Bo Liu, Mandar Dixit, Roland Kwitt, Nuno Vasconcelos. CVPR'18-oral
- Large Scale Fine-Grained Categorization and Domain-Specific Transfer Learning [[pdf]](https://vision.cornell.edu/se3/wp-content/uploads/2018/03/FGVC_CVPR_2018.pdf)
  - Yin Cui, Yang Song, Chen Sun, Andrew Howard, Serge Belongie. CVPR'18

## Few-Shot Learning
- (WC) Matching Networks for One Shot Learning [[pdf]](https://arxiv.org/abs/1606.04080)
  - Oriol Vinyals, Charles Blundell, Tim Lillicrap, koray kavukcuoglu, Daan Wierstra. NIPS'16
- (WC) Learning to Compare Relation Network for Few Shot Learning [[pdf]](https://arxiv.org/abs/1711.06025) 
  - Flood Sung, Yongxin Tang, Li Zhang, Tao Xiang, Philip H.S. Torr, Timothy M. Hospedales
- Optimization as a Model for Few-Shot Learning [[pdf]](https://openreview.net/forum?id=rJY0-Kcll)
  - Sachin Ravi, Hugo Larochelle. ICLR'17
- (HP) Siamese Neural Networks for One-shot Image Recognition [[pdf]](https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf)
  - Koch, Gregory, Richard Zemel, and Ruslan Salakhutdinov. ICML workshop'15
- Generative Adversarial Residual Pairwise Networks for One Shot Learning [[pdf]](https://arxiv.org/abs/1703.08033)
  - Akshay Mehrotra, Ambedkar Dukkipati. arXiv'17
- Few-Shot Learning Through an Information Retrieval Lens [[pdf]](https://arxiv.org/abs/1707.02610)
  - Eleni Triantafillou, Richard Zemel, Raquel Urtasun. NIPS'17

## Evaluating performance of policies
- Bootstrapping with models: Confidence intervals for off-policy evaluation [[pdf]](http://delivery.acm.org/10.1145/3100000/3091205/p538-hanna.pdf?ip=140.113.194.48&id=3091205&acc=ACTIVE%20SERVICE&key=AF37130DAFA4998B%2E7DDA227B4DBFAC43%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&__acm__=1520396005_74ef752694d46f6b30d4f9ba8d52b904)
  - Josiah P. Hanna, Peter Stone, and Scott Niekum. AAMAS'17

## Self-Training
- Learning How to Self-Learn: Enhancing Self-Training Using Neural Reinforcement Learning [[pdf]](https://arxiv.org/pdf/1804.05734.pdf)
  - Chenhua Chen, Yue Zhang. arXiv'18
- A SELF-TRAINING METHOD FOR SEMI-SUPERVISED GANS [[paf]](https://arxiv.org/pdf/1710.10313.pdf)
  - Alan Do-Omri, Dalei Wu & Xiaohua Liu. arXiv'17
- Domain Adaptation for Learning from Label Proportions Using Self-Training [[pdf]](http://cs.iit.edu/~culotta/pubs/ehsan16domain.pdf)
  - Ehsan Mohammady Ardehaly, Aron Culotta. IJCAI'16

## Research Blogs
- Closing the Simulation-to-Reality Gap for Deep Robotic Learning [[link]](https://research.googleblog.com/2017/10/closing-simulation-to-reality-gap-for.html)
  - Google, 2017.
  
## Datasets
- Vision Meets Drones: A Challenge [[pdf]](https://arxiv.org/abs/1804.07437)
  - Pengfei Zhu, Longyin Wen, Xiao Bian, Haibing Ling, Qinghua Hu. arXiv'18

## Clustering
- Unsupervised Deep Embedding for Clustering Analysis [[pdf]](https://arxiv.org/abs/1511.06335)[[slides]](https://drive.google.com/file/d/15TWAtdw42BavBT9WQLz8aZMXn08V7oFX/view?usp=sharing)
  - Junyuan Xie, Ross Girshick, Ali Farhadi. ICML'16
- Deep divergence-based clustering [[pdf]](https://ieeexplore.ieee.org/document/8168158/)
  - M. Kampffmeyer, S. Løkse, F. M. Bianchi, L. Livi, A.-B. Salberg and R. Jenssen. MLSP'17
  
## Others
- Decorrelated Batch Normalization [[pdf]](https://arxiv.org/abs/1804.08450?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%253A+StatArxiv+%2528arXiv.org%2529)
  - Lei Huang, Dawei Yang, Bo Lang, Jia Deng. CVPR'18
- Recurrent Environment Simulators [[pdf]](https://arxiv.org/abs/1704.02254)
  - Silvia Chiappa, Sébastien Racaniere, Daan Wierstra, Shakir Mohamed. arXiv'17
- (BS) Explaining How a Deep Neural Network Trained with End-to-End Learning Steers a Car [[pdf]](https://arxiv.org/pdf/1704.07911) [[ppt]](https://drive.google.com/open?id=1sXfvd10CJ6rMx-Yq9H7fx-8318HfPJni)
  - Mariusz Bojarski, Philip Yeres, Anna Choromanska, Krzysztof Choromanski, Bernhard Firner, Lawrence Jackel, Urs Muller. arXiv'17
- (HP) Generating a Fusion Image: One's Identity and Another's Shape [[pdf]](https://arxiv.org/abs/1804.07455)
  - Donggyu Joo, Doyeon Kim, Junmo Kim. CVPR'18
- Disentangling Structure and Aesthetics for Style-Aware Image Completion [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Gilbert_Disentangling_Structure_and_CVPR_2018_paper.pdf)
  - Andrew Gilbert, John Collomosse, Hailin Jin, Brian Price. CVPR'18
- (HP) Self-Attention Generative Adversarial Networks [[pdf]](https://arxiv.org/abs/1805.08318)
  - Han Zhang, Ian Goodfellow, Dimitris Metaxas, Augustus Odena. ArXiv'18
  
  
## Key Papers
- (JJ) Using Simulation and Domain Adaptation to Improve Efficiency of Deep Robotic Grasping [[pdf]](https://arxiv.org/abs/1709.07857)
  - Konstantinos Bousmalis, Alex Irpan, Paul Wohlhart, Yunfei Bai, Matthew Kelcey, Mrinal Kalakrishnan, Laura Downs, Julian Ibarz, Peter Pastor, Kurt Konolige, Sergey Levine, Vincent Vanhoucke. ICRA'18
- (BS) ADAPT: Zero-Shot Adaptive Policy Transfer for Stochastic Dynamical Systems [[pdf]](https://arxiv.org/abs/1707.04674) [[ppt]](https://drive.google.com/open?id=1DfT_gwLEievx4ef_aIkp1PhQ7rF79_y1)
  - James HarMatching Networks for One Shot Learrison, Animesh Garg, Boris Ivanovic, Yuke Zhu, Silvio Savarese, Li Fei-Fei, Marco Pavone. arXiv'17  ISRR'17
- (Stanley)Transferring End-to-End Visuomotor Control from Simulation to Real World for a Multi-Stage Task [[pdf]](https://arxiv.org/abs/1707.02267)
  - Stephen James, Andrew J. Davison, Edward Johns. CoRL'17
- Using Simulation and Domain Adaptation to Improve Efficiency of Deep Robotic Grasping [[pdf]](https://arxiv.org/abs/1709.07857)
  - Konstantinos Bousmalis, Alex Irpan, Paul Wohlhart, Yunfei Bai, Matthew Kelcey, Mrinal Kalakrishnan, Laura Downs, Julian Ibarz, Peter Pastor, Kurt Konolige, Sergey Levine, Vincent Vanhoucke
- (JJ) Modular Continual Learning in a Unified Visual Environment [[pdf]](https://openreview.net/forum?id=rkPLzgZAZ)
  - Kevin T. Feigelis, Blue Sheffer, Daniel L. K. Yamins. ICLR'18
- (HP) Continuous Adaptation via Meta-Learning in Nonstationary and Competitive Environments [[pdf]](https://openreview.net/forum?id=Sk2u1g-0-) [[slides]](https://drive.google.com/file/d/11KYEYO9gvQcjGJKIHne-UMkLZtk7lRNZ/view?usp=sharing)
  - Maruan Al-Shedivat, Trapit Bansal, Yura Burda, Ilya Sutskever, Igor Mordatch, Pieter Abbeel. ICLR'18 Oral
- (WC) Recasting Gradient-Based Meta-Learning as Hierarchical Bayes [[pdf]](https://openreview.net/forum?id=BJ_UL-k0b)
  - Erin Grant, Chelsea Finn, Sergey Levine, Trevor Darrell, Thomas Griffiths. ICLR'18
- (BS) Universal Agent for Disentangling Environments and Tasks [[pdf]](https://openreview.net/forum?id=B1mvVm-C-) [[ppt]](https://drive.google.com/open?id=1ucDKum1mzeM3YUdBQ3SzBA0WBDDi8HOR)
  - Jiayuan Mao, Honghua Dong, Joseph J. Lim. ICLR'18

## TO-DOs

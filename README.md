# Domain-Shift-in-Reinforcement-Learning 
A compilation of domain-shift related papers in reinforcement learning

## Contents
- [Domain Adaption](#domain-adaption)
- [Domain Shift in Reinforcement Learning](#domain-shift-in-reinforcement-learning)
- [Hierarchical Reinforcement Learning](#hierarchical-reinforcement-learning)
- [Meta-Learning](#meta-learning)
- [Transfer-Learning](#transfer-learning)
- [Few-Shot Learning](#few-shot-learning)
- [Evaluating Performance of Policies](#evaluating-performance-of-policies)
- [Research Blogs](#research-blogs)
- [Others](#others)
- [Key Papers](#key-papers)
- [TO-DOs](#to-dos)

## Domain Adaption
- Awesome Transfer Learning [[github]](https://github.com/artix41/awesome-transfer-learning)
- (HP) A DIRT-T Approach to Unsupervised Domain Adaptation [[pdf]](https://openreview.net/forum?id=H1q-TM-AW&noteId=H1q-TM-AW)
  - Rui Shu, Hung Bui, Hirokazu Narui, Stefano Ermon. ICLR'18
- Learning Transferrable Representations for Unsupervised Domain Adaptation [[pdf]](https://papers.nips.cc/paper/6360-learning-transferrable-representations-for-unsupervised-domain-adaptation)
  - Ozan Sener, Hyun Oh Song, Ashutosh Saxena, Silvio Savarese. NIPS'16
- Domain Separation Networks [[pdf]](https://arxiv.org/abs/1608.06019)
  - Konstantinos Bousmalis, George Trigeorgis, Nathan Silberman, Dilip Krishnan, Dumitru Erhan. NIPS'16
- Unsupervised Domain Adaptation with Residual Transfer Networks [[pdf]](https://arxiv.org/abs/1602.04433)
  - Mingsheng Long, Han Zhu, Jianmin Wang, Michael I. Jordan. NIPS'16
- (HP) Multi-Adversarial Domain Adaptation. [[pdf]](http://ise.thss.tsinghua.edu.cn/~mlong/doc/multi-adversarial-domain-adaptation-aaai18.pdf) 
   - Zhongyi Pei, Zhangjie Cao, Mingsheng Long, and Jianmin Wang. AAAI'18
  

## Domain Shift in Reinforcement Learning
- DARLA: Improving Zero-Shot Transfer in Reinforcement Learning [[pdf]](https://arxiv.org/abs/1707.08475)
  - Irina Higgins, Arka Pal, Andrei A. Rusu, Loic Matthey, Christopher P Burgess, Alexander Pritzel, Matthew Botvinick, Charles Blundell, Alexander Lerchner. ICML'17
- Learning to Imagine Manipulation Goals for Robot Task Planning [[pdf]](https://arxiv.org/abs/1711.02783)
  - Chris Paxton, Kapil Katyal, Christian Rupprecht, Raman Arora, Gregory D. Hager. arXiv'17
- Universal Agent for Disentangling Environments and Tasks [[pdf]](https://openreview.net/forum?id=B1mvVm-C-)
  - Jiayuan Mao, Honghua Dong, Joseph J. Lim. ICLR'18
- (Stanley)Hierarchical and Interpretable Skill Acquisition in Multi-task Reinforcement Learning [[pdf]](https://openreview.net/forum?id=SJJQVZW0b)
  - Tianmin Shu, Caiming Xiong, Richard Socher. ICLR'18
- Learning Robust Rewards with Adverserial Inverse Reinforcement Learning [[pdf]](https://openreview.net/forum?id=rkHywl-A-)
  - Justin Fu, Katie Luo, Sergey Levine. ICLR'18
- Continuous Adaptation via Meta-Learning in Nonstationary and Competitive Environments [[pdf]](https://openreview.net/forum?id=Sk2u1g-0-)
  - Maruan Al-Shedivat, Trapit Bansal, Yura Burda, Ilya Sutskever, Igor Mordatch, Pieter Abbeel. ICLR'18 oral
- (WC) Adapting Deep Visuomotor Representations with Weak Pairwise Constraints [[pdf]](https://arxiv.org/abs/1511.07111)
  - Eric Tzeng, Coline Devin, Judy Hoffman, Chelsea Finn, Pieter Abbeel, Sergey Levine, Kate Saenko, Trevor Darrell. WAFR'16
- Virtual to Real Reinforcement Learning for Autonomous Driving
  - Y You, X Pan, Z Wang, C Lu. arXiv'17
- From virtual demonstration to real-world manipulation using LSTM and MDN [[pdf]](https://arxiv.org/abs/1603.03833)
  - Rouhollah Rahmatizadeh, Pooya Abolghasemi, Aman Behal, Ladislau Bölöni. AAAI'18
- (HP) Bridging the Gap Between Simulation and Reality [[pdf]](http://www.ifaamas.org/Proceedings/aamas2017/pdfs/p1834.pdf)
  - Josiah P. Hanna
- Grounded Action Transformation for Robot Learning in Simulation [[pdf]](http://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/download/14993/14107)
  - JP Hanna, P Stone. AAAI'17
  
## Hierarchical Reinforcement Learning
- (Stanley)Hierarchical Deep Reinforcement Learning: Integrating Temporal Abstraction and Intrinsic Motivation [[pdf]](https://arxiv.org/abs/1604.06057)
  - Tejas D. Kulkarni, Karthik R. Narasimhan, Ardavan Saeedi, Joshua B. Tenenbaum. NIPS'16
- Learning an Embedding Space for Transferable Robot Skills [[pdf]](https://openreview.net/forum?id=rk07ZXZRb)
  - Karol Hausman, Jost Tobias Springenberg, Ziyu Wang, Nicolas Heess, Martin Riedmiller. ICLR'18
  
## Meta-Learning
- Meta Learning Shared Hierachies [[pdf]](https://openreview.net/forum?id=SyX0IeWAW)
  - Kevin Frans, Jonathan Ho, Xi Chen, Pieter Abbeel, John Schulman. ICLR'18
- (WC) Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks [[pdf]](http://arxiv.org/abs/1703.03400)
  - Chelsea Finn, Pieter Abbeel, Sergey Levine. ICML'17
- Prototypical Networks for Few-shot Learning [[pdf]](https://arxiv.org/abs/1703.05175)
  - Jake Snell, Kevin Swersky, Richard S. Zemel. arXiv'17
- Meta-Learning for Semi-Supervised Few-Shot Classification [[pdf]](https://openreview.net/forum?id=HJcSzz-CZ)
  - Mengye Ren, Eleni Triantafillou, Sachin Ravi, Jake Snell, Kevin Swersky, Joshua B. Tenenbaum, Hugo Larochelle, Richard S. Zemel. ICLR'18
- Meta-Learning Shared Hierachies [[pdf]](https://openreview.net/forum?id=SyX0IeWAW)
  - Kevin Frans, kevinfrans2@gmail.com, Jonathan Ho, Xi Chen, Pieter Abbeel, John Schulman. ICLR'18
  
## Transfer Learning
- Learning Invariant Feature Spaces to Transfer Skills with Reinforcement Learning [[pdf]](https://arxiv.org/abs/1703.02949)
  - Abhishek Gupta, Coline Devin, YuXuan Liu, Pieter Abbeel, Sergey Levine. ICLR'17
- Improving Deep Reinforcement Learning with Knowledge Transfer [[pdf]](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14787)
  - Ruben Glatt, Anna Helena Reali Costa. AAAI'17
- Towards Knowledge Transfer in Deep Reinforcement Learning [[pdf]](http://ieeexplore.ieee.org/document/7839568/)
  - Ruben Glatt, Felipe Leno da Silva, and Anna Helena Reali Costa. 
- Pose-Robust Face Recognition via Deep Residual Equivariant Mapping [[pdf]](https://arxiv.org/abs/1803.00839)
  - Kaidi Cao, Yu Rong, Cheng Li, Xiaoou Tang, Chen Change Loy. CVPR'18
  
## Few-Shot Learning
- Matching Networks for One Shot Learning [[pdf]](https://arxiv.org/abs/1606.04080)
  - Oriol Vinyals, Charles Blundell, Tim Lillicrap, koray kavukcuoglu, Daan Wierstra. NIPS'16

## Evaluating performance of policies
- Bootstrapping with models: Confidence intervals for off-policy evaluation [[pdf]](http://delivery.acm.org/10.1145/3100000/3091205/p538-hanna.pdf?ip=140.113.194.48&id=3091205&acc=ACTIVE%20SERVICE&key=AF37130DAFA4998B%2E7DDA227B4DBFAC43%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&__acm__=1520396005_74ef752694d46f6b30d4f9ba8d52b904)
  - Josiah P. Hanna, Peter Stone, and Scott Niekum. AAMAS'17

## Research Blogs
- Closing the Simulation-to-Reality Gap for Deep Robotic Learning [[link]](https://research.googleblog.com/2017/10/closing-simulation-to-reality-gap-for.html)
  - Google, 2017.
  
## Others
- Recurrent Environment Simulators [[pdf]](https://arxiv.org/abs/1704.02254)
  - Silvia Chiappa, Sébastien Racaniere, Daan Wierstra, Shakir Mohamed. arXiv'17
  
## Key Papers
- (HP) Transfer from Simulation to Real World through Learning Deep Inverse Dynamics Model [[pdf]](https://arxiv.org/abs/1610.03518) [[slides]](https://www.cs.toronto.edu/~duvenaud/courses/csc2541/slides/deeprl-inverse.pdf)
  - Paul Christiano, Zain Shah, Igor Mordatch, Jonas Schneider, Trevor Blackwell, Joshua Tobin, Pieter Abbeel, Wojciech Zaremba. arXiv'16
- (JJ) Using Simulation and Domain Adaptation to Improve Efficiency of Deep Robotic Grasping [[pdf]](https://arxiv.org/abs/1709.07857)
  - Konstantinos Bousmalis, Alex Irpan, Paul Wohlhart, Yunfei Bai, Matthew Kelcey, Mrinal Kalakrishnan, Laura Downs, Julian Ibarz, Peter Pastor, Kurt Konolige, Sergey Levine, Vincent Vanhoucke. ICRA'18
- (BS) ADAPT: Zero-Shot Adaptive Policy Transfer for Stochastic Dynamical Systems [[pdf]](https://arxiv.org/abs/1707.04674)
  - James HarMatching Networks for One Shot Learrison, Animesh Garg, Boris Ivanovic, Yuke Zhu, Silvio Savarese, Li Fei-Fei, Marco Pavone. arXiv'17  ISRR'17
- (HP) Domain Randomization for Transferring Deep Neural Networks from Simulation to the Real World [[pdf]](https://arxiv.org/abs/1703.06907)
  - Josh Tobin, Rachel Fong, Alex Ray, Jonas Schneider, Wojciech Zaremba, Pieter Abbeel. IROS'17
- (Stanley)Transferring End-to-End Visuomotor Control from Simulation to Real World for a Multi-Stage Task [[pdf]](https://arxiv.org/abs/1707.02267)
  - Stephen James, Andrew J. Davison, Edward Johns. CoRL'17
- Using Simulation and Domain Adaptation to Improve Efficiency of Deep Robotic Grasping [[pdf]](https://arxiv.org/abs/1709.07857)
  - Konstantinos Bousmalis, Alex Irpan, Paul Wohlhart, Yunfei Bai, Matthew Kelcey, Mrinal Kalakrishnan, Laura Downs, Julian Ibarz, Peter Pastor, Kurt Konolige, Sergey Levine, Vincent Vanhoucke
- Modular Continual Learning in a Unified Visual Environment [[pdf]](https://openreview.net/forum?id=rkPLzgZAZ)
  - Kevin T. Feigelis, Blue Sheffer, Daniel L. K. Yamins. ICLR'18
- Continuous Adaptation via Meta-Learning in Nonstationary and Competitive Environments [[pdf]](https://openreview.net/forum?id=Sk2u1g-0-)
  - Maruan Al-Shedivat, Trapit Bansal, Yura Burda, Ilya Sutskever, Igor Mordatch, Pieter Abbeel. ICLR'18 Oral
- Recasting Gradient-Based Meta-Learning as Hierarchical Bayes [[pdf]](https://openreview.net/forum?id=BJ_UL-k0b)
  - Erin Grant, Chelsea Finn, Sergey Levine, Trevor Darrell, Thomas Griffiths. ICLR'18
- Universal Agent for Disentangling Environments and Tasks [[pdf]](https://openreview.net/forum?id=B1mvVm-C-)
  - Jiayuan Mao, Honghua Dong, Joseph J. Lim. ICLR'18

## TO-DOs


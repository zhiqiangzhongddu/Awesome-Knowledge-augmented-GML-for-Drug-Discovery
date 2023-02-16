# Awesome-Knowledge-augmented-GML-for-Drug-Discovery

![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Stars](https://img.shields.io/github/stars/zhiqiangzhongddu/Awesome-Knowledge-augmented-GML-for-Drug-Discovery?color=yellow)  ![Forks](https://img.shields.io/github/forks/zhiqiangzhongddu/Awesome-Knowledge-augmented-GML-for-Drug-Discovery?color=blue&label=Fork)

This is a collection of resources related with ***Knowledge-augmented Graph Machine Learning for Drug Discovery***.

## Contents

- [Survey papers](#surveypapers)
- [Papers](#papers)
  - [Incorporating Knowledge in *Preprocessing*](#preprocessing)
    - [Feature augmentation](#feature-augmentation)
    - [Graph structure augmentation](#generative-sample-pretraining)
  - [Incorporating Knowledge in *Pretraining*](#pretraining)
    - [Knowledge transfer pretraining](#pretraining-knowledge-transfer)
    - [Generative-sample pretraining](#pretraining-generative-sample)
    - [Contrastive-sample pretraining](#pretraining-contrastive-sample)
  - [Incorporating Knowledge in *Training*](#training)
    - [Auxiliary task-enhanced training](#training-auxiliary-task-enhanced)
    - [Auxiliary knowledge-enhanced training](#training-auxiliary-knowledge-enhanced)
  - [Incorporating Knowledge in *Interpretability*](#interpretability)
    - [Attention summarisation](#interpretability-attenntion-summarisation)
    - [Pathway extraction](#interpretability-pathway-extraction)
- [Resources](#resources)
  - [Knowledge Database](#knowledge-database)
  - [Knowledge Graph](#knowledge-graph)

<a name="surveypapers" />

## Survey papers

1. **Knowledge-augmented Graph Machine Learning for Drug Discovery: A Survey from Precision to Interpretability.** arxiv 2023. [paper](link-to-paper) 

    *Zhiqiang Zhong, Anastasia Barkova, Davide Mottin.*

<a name="surveypapers" />

## Papers

1. **Neural Message Passing for Quantum Chemistry.** ICML 2017. [paper](https://arxiv.org/abs/1704.01212)

    *Justin Gilmer, Samuel S. Schoenholz, Patrick F. Riley, Oriol Vinyals, and George E. Dahl.*

1. **Analyzing Learned Molecular Representations for Property Prediction.** JCIM 2019. [paper](https://arxiv.org/abs/1904.01561)

    *Kevin Yang, Kyle Swanson, Wengong Jin, Connor Coley, Philipp Eiden, Hua Gao, Angel Guzman-Perez, Timothy Hopper, Brian Kelley, Miriam Mathea, Andrew Palmer, Volker Settels, Tommi Jaakkola, Klavs Jensen, Regina Barzilay.*

1. **Communicative representation learning on attributed molecular graphs.** IJCAI 2020. [paper](https://dl.acm.org/doi/pdf/10.5555/3491440.3491832)

    *Ying Song, Shuangjia Zheng, Zhangming Niu, Zhang-Hua Fu, Yutong Lu, Yuedong Yang.*

1. **KGNN: Knowledge Graph Neural Network for Drug-Drug Interaction Prediction.** IJCAI 2020. [paper](https://www.ijcai.org/proceedings/2020/380)

    *Xuan Lin, Zhe Quan, Zhi-Jie Wang, Tengfei Ma, Xiangxiang Zeng.*

1. **Deciphering interaction fingerprints from protein molecular surfaces using geometric deep learning.** Nat. Methods 2020. [paper](https://www.nature.com/articles/s41592-019-0666-6)

    *P. Gainza, F. Sverrisson, F. Monti, E. Rodolà, D. Boscaini, M. M. Bronstein, B. E. Correia.*

1. **Knowledge-Embedded Message-Passing Neural Networks: Improving Molecular Property Prediction with Human Knowledge.** ACS Omega 2021. [paper](https://pubs.acs.org/doi/10.1021/acsomega.1c03839)

    *Tatsuya Hasebe.*

1. **SumGNN: Multi-typed Drug Interaction Prediction via Efficient Knowledge Graph Summarization.** Bioinform. 2021. [paper](https://arxiv.org/abs/2010.01450)

    *Yue Yu, Kexin Huang, Chao Zhang, Lucas M. Glass, Jimeng Sun, Cao Xiao.*

1. **FraGAT: a fragment-oriented multi-scale graph attention model for molecular property prediction.** Bioinform. 2021. [paper](https://academic.oup.com/bioinformatics/article/37/18/2981/6189082)

    *Ziqiao Zhang, Jihong Guan, Shuigeng Zhou.*

1. **Equivariant message passing for the prediction of tensorial properties and molecular spectra.** ICML 2021. [paper](https://arxiv.org/abs/2102.03150)

    *Kristof T. Schütt, Oliver T. Unke, Michael Gastegger.*

1. **MDNN: A Multimodal Deep Neural Network for Predicting Drug-Drug Interaction Events.** IJCAI 2021. [paper](https://www.ijcai.org/proceedings/2021/487)

    *Tengfei Lyu, Jianliang Gao, Ling Tian, Zhao Li, Peng Zhang, Ji Zhang.*

1. **MoCL: Data-driven Molecular Fingerprint via Knowledge-aware Contrastive Learning from Molecular Graph.** KDD 2021. [paper](https://arxiv.org/abs/2106.04509)

    *Mengying Sun, Jing Xing, Huijun Wang, Bin Chen, Jiayu Zhou.*

1. **Highly accurate protein structure prediction with AlphaFold.** Nature 2021. [paper](https://www.nature.com/articles/s41586-021-03819-2)

    *John Jumper, Richard Evans, Alexander Pritzel, Tim Green, Michael Figurnov, Olaf Ronneberger, Kathryn Tunyasuvunakool, Russ Bates, Augustin Žídek, Anna Potapenko, Alex Bridgland, Clemens Meyer, Simon A. A. Kohl, Andrew J. Ballard, Andrew Cowie, Bernardino Romera-Paredes, Stanislav Nikolov, Rishub Jain, Jonas Adler, Trevor Back, Stig Petersen, David Reiman, Ellen Clancy, Michal Zielinski, Martin Steinegger, Michalina Pacholska, Tamas Berghammer, Sebastian Bodenstein, David Silver, Oriol Vinyals, Andrew W. Senior, Koray Kavukcuoglu, Pushmeet Kohli, Demis Hassabis.*

1. **A unified drug–target interaction prediction framework based on knowledge graph and recommendation system.** Nat. Commun. 2021. [paper](https://www.nature.com/articles/s41467-021-27137-3)

    *Qing Ye, Chang-Yu Hsieh, Ziyi Yang, Yu Kang, Jiming Chen, Dongsheng Cao, Shibo He, Tingjun Hou.*

1. **scGCN is a graph convolutional networks algorithm for knowledge transfer in single cell omics.** Nat. Commun. 2021. [paper](https://www.nature.com/articles/s41467-021-24172-y)

    *Qianqian Song, Jing Su, Wei Zhang.*

1. **Out-of-the-box deep learning prediction of pharmaceutical properties by broadly learned knowledge-based molecular representations.** Nat. Mach. Intell. 2021. [paper](https://www.nature.com/articles/s42256-021-00301-6)

    *Wan Xiang Shen, Xian Zeng, Feng Zhu, Ya li Wang, Chu Qin, Ying Tan, Yu Yang Jiang, Yu Zong Chen.*

1. **GemNet: Universal Directional Graph Neural Networks for Molecules.** NeurIPS 2021. [paper](https://arxiv.org/abs/2106.08903)

    *Johannes Gasteiger, Florian Becker, Stephan Günnemann.*

1. **Multi-Scale Representation Learning on Proteins.** NeurIPS 2021. [paper](https://arxiv.org/abs/2204.02337)

    *Vignesh Ram Somnath, Charlotte Bunne, Andreas Krause.*

1. **Directional Message Passing on Molecular Graphs via Synthetic Coordinates.** NeurIPS 2021. [paper](https://arxiv.org/abs/2111.04718)

    *Johannes Gasteiger, Chandan Yeshwanth, Stephan Günnemann.*

1. **Molecular Contrastive Learning with Chemical Element Knowledge Graph.** AAAI 2022. [paper](https://arxiv.org/abs/2112.00544)

    *Yin Fang, Qiang Zhang, Haihong Yang, Xiang Zhuang, Shumin Deng, Wen Zhang, Ming Qin, Zhuo Chen, Xiaohui Fan, Huajun Chen.*

1. **Structured Multi-task Learning for Molecular Property Prediction.** AISTATS 2022. [paper](https://arxiv.org/abs/2203.04695)

    *Shengchao Liu, Meng Qu, Zuobai Zhang, Huiyu Cai, Jian Tang.*

1. **scGraph: a graph neural network-based approach to automatically identify cell types.** Bioinform. 2022. [paper](https://academic.oup.com/bioinformatics/article/38/11/2996/6565313)

    *Qijin Yin, Qiao Liu, Zhuoran Fu, Wanwen Zeng, Boheng Zhang, Xuegong Zhang, Rui Jiang, Hairong Lv.*

1. **DTI-HETA: prediction of drug–target interactions based on GCN and GAT on heterogeneous graph.** Brief. Bioinform. 2022. [paper](https://academic.oup.com/bib/article-abstract/23/3/bbac109/6563180?redirectedFrom=fulltext)

    *Kanghao Shao, Yunhao Zhang, Yuqi Wen, Zhongnan Zhang, Song He, Xiaochen Bo.*

1. **PEMP: Leveraging Physics Properties to Enhance Molecular Property Prediction.** CIKM 2022. [paper](https://arxiv.org/abs/2211.01978)

    *Yuancheng Sun, Yimeng Chen, Weizhi Ma, Wenhao Huang, Kang Liu, Zhiming Ma, Wei-Ying Ma, Yanyan Lan.*

1. **Graph Neural Networks Pretraining Through Inherent Supervision for Molecular Property Prediction.** CIKM 2022. [paper](https://dl.acm.org/doi/10.1145/3511808.3557085)

    *Roy Benjamin, Uriel Singer, Kira Radinsky.*

1. **Pre-training Molecular Graph Representation with 3D Geometry.** ICLR 2022. [paper](https://arxiv.org/abs/2110.07728)

    *Shengchao Liu, Hanchen Wang, Weiyang Liu, Joan Lasenby, Hongyu Guo, Jian Tang.*

1. **OntoProtein: Protein Pretraining With Gene Ontology Embedding.** ICLR 2022. [paper](https://openreview.net/forum?id=yfe1VMYAXa4)

    *Ningyu Zhang, Zhen Bi, Xiaozhuan Liang, Siyuan Cheng, Haosen Hong, Shumin Deng, Qiang Zhang, Jiazhang Lian, Huajun Chen.*

1. **Spherical Message Passing for 3D Graph Networks.** ICLR 2022. [paper](https://arxiv.org/abs/2102.05013)

    *Yi Liu, Limei Wang, Meng Liu, Xuan Zhang, Bora Oztekin, Shuiwang Ji.*

1. **3D Infomax improves GNNs for Molecular Property Prediction.** ICML 2022. [paper](https://arxiv.org/abs/2110.04126)

    *Hannes Stärk, Dominique Beaini, Gabriele Corso, Prudencio Tossou, Christian Dallago, Stephan Günnemann, Pietro Liò.*

1. **DRPreter: Interpretable Anticancer Drug Response Prediction Using Knowledge-Guided Graph Neural Networks and Transformer.** Int. J. Mol. Sci. 2022. [paper](https://www.mdpi.com/1422-0067/23/22/13919)

    *Jihye Shin, Yinhua Piao, Dongmin Bang, Sun Kim, Kyuri Jo.*

1. **DENVIS: Scalable and High-Throughput Virtual Screening Using Graph Neural Networks with Atomic and Surface Protein Pocket Features.** J. Chem. Inf. Model. 2022. [paper](https://pubs.acs.org/doi/10.1021/acs.jcim.2c01057)

    *Agamemnon Krasoulis, Nick Antonopoulos, Vassilis Pitsikalis, Stavros Theodorakis.*

1. **ReLMole: Molecular Representation Learning Based on Two-Level Graph Similarities.** J. Chem. Inf. Model. 2022. [paper](https://pubs.acs.org/doi/10.1021/acs.jcim.2c00798)

    *Zewei Ji, Runhan Shi, Jiarui Lu, Fang Li, and Yang Yang.*

1. **KPGT: Knowledge-Guided Pre-training of Graph Transformer for Molecular Property Prediction.** KDD 2022. [paper](https://arxiv.org/abs/2206.03364)

    *Han Li, Dan Zhao, Jianyang Zeng.*

1. **E(3)-equivariant graph neural networks for data-efficient and accurate interatomic potentials.** Nat. Commun. 2022. [paper](https://www.nature.com/articles/s41467-022-29939-5)

    *Simon Batzner, Albert Musaelian, Lixin Sun, Mario Geiger, Jonathan P Mailoa, Mordechai Kornbluth, Nicola Molinari, Tess E Smidt, Boris Kozinsky..*

1. **Geometry-enhanced molecular representation learning for property prediction.** Nat. Mach. Intell. 2022. [paper](https://www.nature.com/articles/s42256-021-00438-4)

    *Xiaomin Fang, Lihang Liu, Jieqiong Lei, Donglong He, Shanzhuo Zhang, Jingbo Zhou, Fan Wang, Hua Wu, Haifeng Wang.*

1. **ComENet: Towards Complete and Efficient Message Passing for 3D Molecular Graphs.** NeurIPS 2022. [paper](https://arxiv.org/abs/2206.08515)

    *Limei Wang, Yi Liu, Yuchao Lin, Haoran Liu, Shuiwang Ji.*

1. **Knowledge-guided deep learning models of drug toxicity improve interpretation.** Patterns 2022. [paper](https://pubmed.ncbi.nlm.nih.gov/36124309/)

    *Yun Hao, Joseph D Romano, Jason H Moore.*

1. **Robust deep learning–based protein sequence design using ProteinMPNN.** Science 2022. [paper](https://www.science.org/doi/10.1126/science.add2187)

    *J. Dauparas, I. Anishchenko, N. Bennett, H. Bai, R. J. Ragotte, L. F. Milles, B. I. M. Wicky, A. Courbet, R. J. de Haas, N. Bethel, P. J. Y. Leung, T. F. Huddy, S. Pellock, D. Tischer, F. Chan, B. Koepnick, H. Nguyen, A. Kang, B. Sankaran, A. K. Bera, N. P. King, D. Baker.*

1. **A Knowledge-Enhanced Multi-View Framework for Drug-Target Interaction Prediction.** TKDE 2022. [paper](https://ieeexplore.ieee.org/document/9324998)

    *Ying Shen, Yilin Zhang, Kaiqi Yuan, Dagang Li, Haitao Zheng.*

1. **KG-MTL: Knowledge Graph Enhanced Multi-Task Learning for Molecular Interaction.** TKDE 2022. [paper](https://ieeexplore.ieee.org/document/9815157)

    *Tengfei Ma, Xuan Lin, Bosheng Song, Philip S. Yu, Xiangxiang Zeng.*


<a name="preprocessing" />

## Incorporating Knowledge in *Preprocessing*

<a name="preprocessing-feature-augmentation" />

### Feature augmentation

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*


<a name="preprocessing-graph-structure-augmentation" />

### Graph structure augmentation

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

<a name="pretraining" />

## Incorporating Knowledge in *Pretraining*

<a name="pretraining-knowledge-transfer" />

### Knowledge transfer pretraining

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

<a name="pretraining-generative-sample" />

### Generative sample pretraining

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

<a name="pretraining-contrastive-sample" />

### Contrastive-sample pretraining

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

<a name="training" />

## Incorporating Knowledge in *Training*

<a name="training-auxiliary-task-enhanced" />

### Auxiliary task-enhanced training

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

<a name="training-auxiliary-knowledge-enhanced" />

### Auxiliary knowledge-enhanced training

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

<a name="interpretability" />

## Incorporating Knowledge in *Interpretability*

<a name="interpretability-attenntion-summarisation" />

### Attention summarisation

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

<a name="interpretability-pathway-extraction" />

### Pathway extraction

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

<a name="resources" />

## Resources

<a name="knowledge-database" />

### Knowledge Database

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

<a name="knowledge-graph" />

### Knowledge Graph

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

1. **Paper Title.** Venue Year. [paper](link-to-paper)

    *Authors.*

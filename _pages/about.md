---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently a Postdoc at the Department of Computer Science, Hong Kong Baptist University, working with [Prof. Hong-Ning Dai](https://www.comp.hkbu.edu.hk/~henrydai/), [Prof. Byron Choi](https://www.comp.hkbu.edu.hk/~bchoi/) and [Prof. William Kwok-Wai Cheung](https://www.comp.hkbu.edu.hk/~william/).
I received my Ph.D. degree from the College of Computer and Data Science, Fuzhou University, in 2024, supervised by [Prof. Wenzhong Guo](https://ccds.fzu.edu.cn/info/1202/4993.htm) and [Prof. Shiping Wang](https://ccds.fzu.edu.cn/info/1202/8958.htm). Before that, I majored in software engineering and obtained my B.E. degree from the College of Mathematics and Computer Science, Fuzhou University, in 2019. From Oct 2022 to Oct 2023, I was also a joint Ph.D. student in Faculty of Computer Science, University of Vienna, Austria, supervised by [Prof. Claudia Plant](https://dm.cs.univie.ac.at/team/person/59835/). My research interests include graph neural networks, optimization-inspired deep learning and their applications. My studies have led to over 20 scientific publications (<a href='https://scholar.google.com/citations?user=LM0QNdQAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>) on top-tier conferences and journals, including AAAI, IEEE TPAMI, IEEE TNNLS, IEEE TMM, IEEE TSP, ACM TKDD, Information Fusion, Neural Networks, etc.

# 🔥 News
- *2024.12*: &nbsp;🎉🎉 One paper has been accepted by AAAI 2025 (CCF-A)!

# 📖 Educations
- *2019.09 - 2024.06*, Ph.D., College of Computer and Data Science, Fuzhou University, China.
- *2022.10 - 2023.10*, Joint Ph.D. Student, Faculty of Computer Science, University of Vienna, Austria.
- *2015.09 - 2019.06*, B.E., College of Mathematics and Computer Science, Fuzhou University, China

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NN</div><img src='images/AMOGCN.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Attributed Multi-order Graph Convolutional Network for Heterogeneous Graphs](https://doi.org/10.1016/j.neunet.2024.106225)**,<br />
   **Zhaoliang Chen**, Zhihao Wu, Luying Zhong, Claudia Plant, Shiping Wang, Wenzhong Guo <br />
   *Neural Networks, 2024, Volume 174, Page 106225*. (CCF B, SCI Q1) \| [\[code\]](https://github.com/chenzl23/AMOGCN)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TNNLS</div><img src='images/AGNN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[AGNN: Alternating Graph-Regularized Neural Networks to Alleviate Over-Smoothing](https://doi.org/10.1109/TNNLS.2023.3271623)**,<br />
   **Zhaoliang Chen**, Zhihao Wu, Zhenghong Lin, Shiping Wang, Claudia Plant, Wenzhong Guo <br />
   *IEEE Transactions on Neural Networks and Learning Systems, 2024*. (CCF B, SCI Q1) \| [\[code\]](https://github.com/chenzl23/AGNN)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/DLRGAE.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Dual Low-Rank Graph Autoencoder for Semantic and Topological Networks](https://doi.org/10.1609/aaai.v37i4.25536)**,<br />
   **Zhaoliang Chen**, Zhihao Wu, Shiping Wang, Wenzhong Guo <br />
   *AAAI Conference on Artificial Intelligence, 2023*. (CCF A) \| [\[code\]](https://github.com/chenzl23/DLRGAE)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INF</div><img src='images/LGCN.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
    
**[Learnable Graph Convolutional Network and Feature Fusion for Multi-view Learning](https://doi.org/10.1016/j.ins.2023.120012)**,<br />
   **Zhaoliang Chen**, Lele Fu, Jie Yao, Wenzhong Guo, Claudia Plant, Shiping Wang <br />
   *Information Fusion, 2023*. (CCF B, SCI Q1) \| [\[code\]](https://github.com/chenzl23/LGCNFF)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TKDD</div><img src='images/MGCNDNS.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Multi-view Graph Convolutional Networks with Differentiable Node Selection](https://dl.acm.org/doi/abs/10.1145/3628162)**,<br />
   **Zhaoliang Chen**, Lele Fu, Shunxin Xiao, Shiping Wang, Claudia Plant, Wenzhong Guo <br />
   *ACM Transactions on Knowledge Discovery from Data, 2023*. (CCF B)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TMM</div><img src='images/DLRL.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Efficient and Differentiable Low-rank Matrix Completion with Back Propagation](https://doi.org/10.1109/TMM.2021.3124087)**,<br />
   **Zhaoliang Chen**, Jie Yao, Guobao Xiao, Shiping Wang <br />
   *IEEE Transactions on Multimedia, 2023*. (CCF B, SCI Q1) \| [\[code\]](https://github.com/chenzl23/DLRL)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TPAMI</div><img src='images/DSRL.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Learning Deep Sparse Regularizers With Applications to Multi-View Clustering](https://doi.org/10.1109/TPAMI.2021.3082632)**,<br />
   Shiping Wang, **Zhaoliang Chen**, Shide Du, Zhouchen Lin <br />
   *IEEE Transactions on Pattern Analysis and Machine Intelligence, 2022*. (CCF A, SCI Q1) \| [\[code\]](https://github.com/chenzl23/DSRL)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KAIS</div><img src='images/review.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[A review on matrix completion for recommender systems](https://doi.org/10.1007/s10115-021-01629-6)**,<br />
   **Zhaoliang Chen**, Shiping Wang <br />
   *Knowledge and Information Systems, 2022*. (CCF B, SCI Q3)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ESWA</div><img src='images/MKMC.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Kernel meets recommender systems: A multi-kernel interpolation for matrix completion](https://doi.org/10.1016/j.eswa.2020.114436)**,<br />
   **Zhaoliang Chen**, Wei Zhao, Shiping Wang <br />
   *Expert Systems with Applications, 2021*. (CCF B, SCI Q1)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/GRAND.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Refine then Classify: Robust Graph Neural Networks with Reliable Neighborhood Contrastive Refinement](https://www.aaai.org/AAAI25)**,<br />
    Shuman Zhuang, Zhihao Wu, **Zhaoliang Chen**, Hong-Ning Dai, Ximeng Liu <br />
    *AAAI Conference on Artificial Intelligence, 2025*. (CCF A)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM</div><img src='images/ECMGD.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Towards Multi-view Consistent Graph Diffusion](https://openreview.net/forum?id=2AnSGzLiGs)**,<br />
    Jielong Lu, Zhihao Wu, **Zhaoliang Chen**, Zhiling Cai, Shiping Wang <br />
    *ACM Multimedia, 2024*. (CCF A, Oral 3.97%) \| [\[pdf\]](https://openreview.net/pdf?id=2AnSGzLiGs)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TMM</div><img src='images/GEGCN.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Generative Essential Graph Convolutional Network for Multi-view Semi-supervised Classification](https://ieeexplore.ieee.org/document/10456789)**,<br />
    Jielong Lu, Zhihao Wu, Luying Zhong, **Zhaoliang Chen**, Hong Zhao, Shiping Wang <br />
    *IEEE Transactions on Multimedia, 2024*. (CCF B, SCI Q1) \| [\[code\]](https://github.com/long319/GEGCN)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">BMC genomics</div><img src='images/DeepMoIC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[DeepMoIC: multi-omics data integration via deep graph convolutional networks for cancer subtype classification](https://doi.org/10.1186/s12864-024-10473-1)**,<br />
    Jiecheng Wu, **Zhaoliang Chen**, Shunxin Xiao, Genggeng Liu, Wenjie Wu, Shiping Wang <br />
    *BMC Genomics, 2024*. (SCI Q2)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ESWA</div><img src='images/ESWA2024MESG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
    
**[Multi-scale structure-guided graph generation for multi-view semi-supervised classification](https://doi.org/10.1016/j.eswa.2024.125677)**,<br />
    Yilin Wu, **Zhaoliang Chen**, Ying Zou, Shiping Wang, Wenzhong Guo <br />
    *Expert Systems with Applications, 2025*. (CCF C, SCI Q1)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PR</div><img src='images/GCNet.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Graph Convolutional Network with Elastic Topology](https://doi.org/10.1016/j.patcog.2024.110567)**,<br />
    Zhihao Wu, **Zhaoliang Chen**, Shide Du, Sujia Huang, Shiping Wang <br />
    *Pattern Recognition, 2024*. (CCF B, SCI Q1) \| [\[code\]](https://github.com/ZhihaoWu99/GCNet)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INS</div><img src='images/GLGCN.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Geometric Localized Graph Convolutional Network for Multi-view Semi-supervised Classification](https://doi.org/10.1016/j.ins.2024.120769)**,<br />
    Aiping Huang, Jielong Lu, Zhihao Wu, **Zhaoliang Chen**, Yuhong Chen, Shiping Wang, Hehong Zhang <br />
    *Information Sciences, 2024*. (CCF B, SCI Q1)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TNNLS</div><img src='images/SGIB.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Learnable Graph Convolutional Network With Semisupervised Graph Information Bottleneck](https://doi.org/10.1109/TNNLS.2023.3322739)**,<br />
    Luying Zhong, **Zhaoliang Chen**, Zhihao Wu, Shide Du, Zheyi Chen, Shiping Wang <br />
    *IEEE Transactions on Neural Networks and Learning Systems, 2023*. (CCF B, SCI Q1)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INS</div><img src='images/AMCGCN.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Adaptive Multi-channel Contrastive Graph Convolutional Network with Graph and Feature Fusion](https://doi.org/10.1016/j.ins.2023.120012)**,<br />
    Luying Zhong, Jielong Lu, **Zhaoliang Chen**, Na Song, Shiping Wang <br />
    *Information Sciences, 2024*. (CCF B, SCI Q1)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NN</div><img src='images/JFGCN.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Joint learning of feature and topology for multi-view graph convolutional network](https://doi.org/10.1016/j.neunet.2023.09.006)**,<br />
    Yuhong Chen, Zhihao Wu, **Zhaoliang Chen**, Mianxiong Dong, Shiping Wang <br />
    *Neural Networks, 2023*. (CCF B, SCI Q1) \| [\[code\]](https://github.com/YuhongChen2320/JFGCN)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TMM</div><img src='images/IMVGCN.jpg' alt="sym" width="100%"></div></div
<div class='paper-box-text' markdown="1">
  
**[Interpretable Graph Convolutional Network for Multi-View Semi-Supervised Learning](https://doi.org/10.1109/TMM.2023.3260649)**,<br />
    Zhihao Wu, Xincan Lin, Zhenghong Lin, **Zhaoliang Chen**, Yang Bai, Shiping Wang <br />
    *IEEE Transactions on Multimedia, 2023*. (CCF B, SCI Q1) \| [\[code\]](https://github.com/ZhihaoWu99/IMvGCN)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TSP</div><img src='images/CGCN.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Contrastive Graph Convolutional Networks with Generative Adjacency Matrix](https://doi.org/10.1109/TSP.2023.3254888)**,<br />
    Luying Zhong, Jinbin Yang, **Zhaoliang Chen**, Shiping Wang <br />
    *IEEE Transactions on Signal Processing, 2023*. (CCF B, SCI Q1)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TMM</div><img src='images/DFPGNN.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Dual Fusion-Propagation Graph Neural Network for Multi-View Clustering](https://doi.org/10.1109/TMM.2023.3248173)**,<br />
    Shunxin Xiao, Shide Du, **Zhaoliang Chen**, Yunhe Zhang, Shiping Wang <br />
    *IEEE Transactions on Multimedia, 2023*. (CCF B, SCI Q1) \| [\[code\]](https://github.com/Xiaoshunxin/DFP-GNN)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TMM</div><img src='images/ULTLSE.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Unified Low-Rank Tensor Learning and Spectral Embedding for Multi-View Subspace Clustering](https://doi.org/10.1109/TMM.2022.3185886)**,<br />
    Lele Fu, **Zhaoliang Chen**, Yongyong Chen, Shiping Wang <br />
    *IEEE Transactions on Multimedia, 2022*. (CCF B, SCI Q1)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INS</div><img src='images/DDMF.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Diversity embedding deep matrix factorization for multi-view clustering](https://doi.org/10.1016/j.ins.2022.07.177)**,<br />
    Zexi Chen, Pengfei Lin, **Zhaoliang Chen**, Dongyi Ye, Shiping Wang <br />
    *Information Sciences, 2022*. (CCF B, SCI Q1)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2021</div><img src='images/MLLTO.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Multi-View Learning Via Low-Rank Tensor Optimization](https://doi.org/10.1109/ICME51207.2021.9428291)**,<br />
    Lele Fu, **Zhaoliang Chen**, Sujia Huang, Sheng Huang, Shiping Wang <br />
    *IEEE International Conference on Multimedia and Expo, 2021*. (CCF B)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INS</div><img src='images/DRWDR.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Deep random walk of unitary invariance for large-scale data representation](https://doi.org/10.1016/j.ins.2020.11.039)**,<br />
    Shiping Wang, **Zhaoliang Chen**, William Zhu, Fei-Yue Wang <br />
    *Information Sciences, 2021*. (CCF B, SCI Q1)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TSP</div><img src='images/EDBMC.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Differentiable bi-Sparse multi-View co-clustering](https://doi.org/10.1109/TSP.2021.3101979)**,<br />
    Shide Du, Zhanghui Liu, **Zhaoliang Chen**, Wenyuan Yang, Shiping Wang <br />
    *IEEE Transactions on Signal Processing, 2021*. (CCF B, SCI Q1)
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PRCV 2021</div><img src='images/EDBMC.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[A unified modular framework with deep graph convolutional networks for multi-label image recognition](https://doi.org/10.1007/978-3-030-88007-1\_5)**,<br />
    Qifan Lin, **Zhaoliang Chen**, Shiping Wang, Wenzhong Guo <br />
    *Pattern Recognition and Computer Vision, 2021*. (CCF C)
</div></div>




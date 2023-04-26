---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Preprints      
**Transferable Fairness for Cold-Start Recommendation**      
**Yunqi Li**, Dingxian Wang, Hanxiong Chen, Yongfeng Zhang.      
[paper](https://arxiv.org/pdf/2301.10665.pdf)

**Causal Inference for Recommendation: Foundations, Methods and Applications**      
Shuyuan Xu, Jianchao Ji, **Yunqi Li**,Yingqiang Ge, Juntao Tan, Yongfeng Zhang.      
[paper](https://arxiv.org/pdf/2301.04016.pdf)

**A Survey on Trustworthy Recommender Systems**      
Yingqiang Ge, Shuchang Liu, Zuohui Fu, Juntao Tan, Zelong Li, Shuyuan Xu, **Yunqi Li**, Yikun Xian, Yongfeng Zhang.       
[paper](https://arxiv.org/pdf/2207.12515.pdf)

**Fairness in Recommendation: A Survey**      
**Yunqi Li**, Hanxiong Chen, Shuyuan Xu, Yingqiang Ge, Juntao Tan, Shuchang Liu, Yongfeng Zhang.      
[paper](https://arxiv.org/pdf/2205.13619.pdf)
 
**Counterfactual Evaluation for Explainable AI**      
Yingqiang Ge, Shuchang Liu, Zelong Li, Shuyuan Xu, Shijie Geng, **Yunqi Li**, Juntao Tan, Fei Sun, Yongfeng Zhang.      
[paper](https://arxiv.org/abs/2109.01962)
  
**Causal Collaborative Filtering**      
Shuyuan Xu, Yingqiang Ge, **Yunqi Li**, Zuohui Fu, Xu Chen, and Yongfeng Zhang. arXiv preprint arXiv:2102.01868 (2021)       
[paper](https://arxiv.org/pdf/2102.01868.pdf)

## Conference    
**Learn Basic Skills and Reuse: Modularized Adaptive Neural Architecture Search (MANAS)**       
Hanxiong Chen, **Yunqi Li**, He Zhu, Yongfeng Zhang. In *Proceedings of the 31st ACM International Conference on Information and Knowledge Management (**CIKM**)*, 2022.       
[paper](https://arxiv.org/pdf/2208.11083.pdf)

**Causal Factorization Machine for Robust Recommendation**       
**Yunqi Li**, Hanxiong Chen, Juntao Tan, Yongfeng Zhang. In *The ACM/IEEE Joint Conference on Digital Libraries (**JCDL**)*, 2022.      
[paper](https://dl.acm.org/doi/pdf/10.1145/3529372.3530921)

**Graph Collaborative Reasoning**       
Hanxiong Chen, **Yunqi Li**, Shaoyun Shi, Shuchang Liu, He Zhu, Yongfeng Zhang. In *Proceedings of the 15th ACM International Conference on Web Search and Data Mining in  (**WSDM**)*, 2022.      
[paper](https://dl.acm.org/doi/pdf/10.1145/3488560.3498410)

**Learning and Evaluating Explanations for Graph Neural Networks based on Counterfactual and Factual Reasoning**       
Juntao Tan, Shijie Geng, Zuohui Fu, Yingqiang Ge, Shuyuan Xu, **Yunqi Li**, Yongfeng Zhang. In *Proceedings of the Web Conference (**WWW**)*, 2022.       
[paper](https://arxiv.org/pdf/2202.08816.pdf)

**Towards Personalized Fairness based on Causal Notion**      
**Yunqi Li**, Hanxiong Chen, Shuyuan Xu, Yingqiang Ge, Yongfeng Zhang. In *Proceedings of the 44th International ACM SIGIR Conference
on Research and Development in Information Retrieval (**SIGIR**)*, 2021.      
[paper](https://dl.acm.org/doi/pdf/10.1145/3404835.3462966)

**User-oriented Fairness in Recommendation**      
**Yunqi Li**, Hanxiong Chen, Zuohui Fu, Yingqiang Ge, Yongfeng Zhang. In *Proceedings of the Web Conference (**WWW**)*, 2021.      
[paper](https://arxiv.org/pdf/2104.10671.pdf)

**Neural Collaborative Reasoning**       
Hanxiong Chen, Shaoyun Shi, **Yunqi Li**, Yongfeng Zhang. In *Proceedings of the Web Conference (**WWW**)*, 2021.      
[paper](https://arxiv.org/pdf/2005.08129.pdf)

**Counterfactual Explainable Recommendation**        
Juntao Tan, Shuyuan Xu, Yingqiang Ge, **Yunqi Li**, Xu Chen and Yongfeng Zhang. In *Proceedings of the 30th ACM International Conference on Information and Knowledge Management (**CIKM**)*, 2021.        
[paper](https://dl.acm.org/doi/pdf/10.1145/3459637.3482420)

**Towards Long-term Fairness in Recommendation**       
Yingqiang Ge, Shuchang Liu, Ruoyuan Gao, Yikun Xian, **Yunqi Li**, Xiangyu Zhao, Changhua Pei et al. In *Proceedings of the 14th ACM International Conference on Web Search and Data Mining (**WSDM**)*, 2021.      
[paper](https://arxiv.org/pdf/2101.03584.pdf)

## Workshop      
**Fairness in Job Recommendation under Quantity Constraints**      
**Yunqi Li**, Michiharu Yamashita, Hanxiong Chen, Dongwon Lee, Yongfeng Zhang. In *Proceedings of the AAAI-23 Workshop on AI for Web Advertising.*     
[paper](https://pike.psu.edu/publications/aaai23-fair.pdf)

**Looking Further into the Future: Career Pathway Prediction**       
Michiharu Yamashita, **Yunqi Li**, Thanh Tran, Yongfeng Zhang, Dongwon Lee. In *the First International Workshop on Computational Jobs Marketplace at  (**WSDM**)*, 2022.      
[paper](https://pike.psu.edu/publications/wsdmw22.pdf)

**Learning Post-Hoc Causal Explanations for Recommendation**       
Shuyuan Xu, **Yunqi Li**, Shuchang Liu, Zuohui Fu, Xu Chen and Yongfeng Zhang. In *Proceedings of the 1st International Workshops on Causality in Search and Recommendation (CSR) at SIGIR-21*, 2021.     
[paper](https://arxiv.org/pdf/2006.16977.pdf)

**Discrete Knowledge Graph Embedding Based on Discrete Optimization**      
**Yunqi Li**, Shuyuan Xu, Bo Liu, Zuohui Fu, Shuchang Liu, Xu Chen, and Yongfeng Zhang. In *Proceedings of the AAAI-20 Workshop on Knowledge Discovery from Unstructured Data in Financial Services.*     
[paper](https://aaai-kdf2020.github.io/assets/pdfs/kdf2020_paper_20.pdf)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

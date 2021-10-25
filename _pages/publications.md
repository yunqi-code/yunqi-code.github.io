---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Preprints      
 
**Counterfactual Evaluation for Explainable AI**      
Yingqiang Ge, Shuchang Liu, Zelong Li, Shuyuan Xu, Shijie Geng, **Yunqi Li**, Juntao Tan, Fei Sun, Yongfeng Zhang.      
[paper](https://arxiv.org/abs/2109.01962)
  
**Causal Collaborative Filtering**      
Shuyuan Xu, Yingqiang Ge, **Yunqi Li**, Zuohui Fu, Xu Chen, and Yongfeng Zhang. arXiv preprint arXiv:2102.01868 (2021)       
[paper](https://arxiv.org/pdf/2102.01868.pdf)

## 2022     
**Graph Logic Reasoning for Recommendation and Link Prediction**       
Hanxiong Chen, **Yunqi Li**, Shaoyun Shi, Shuchang Liu, He Zhu, Yongfeng Zhang. In *Proceedings of the 15th ACM International Conference on Web Search and Data Mining in  (**WSDM**)*, 2022.       

## 2021
**Towards Personalized Fairness based on Causal Notion**      
**Yunqi Li**, Hanxiong Chen, Shuyuan Xu, Yingqiang Ge, Yongfeng Zhang. In *Proceedings of the 44th International ACM SIGIR Conference
on Research and Development in Information Retrieval (**SIGIR**)*, 2021.

**User-oriented Fairness in Recommendation**      
**Yunqi Li**, Hanxiong Chen, Zuohui Fu, Yingqiang Ge, Yongfeng Zhang. In *Proceedings of the Web Conference (**WWW**)*, 2021.      
[paper](https://arxiv.org/pdf/2104.10671.pdf)

**Neural Collaborative Reasoning**       
Hanxiong Chen, Shaoyun Shi, **Yunqi Li**, Yongfeng Zhang. In *Proceedings of the Web Conference (**WWW**)*, 2021.      
[paper](https://arxiv.org/pdf/2005.08129.pdf)

**CountER: Counterfactual Explainable Recommendation**        
Juntao Tan, Shuyuan Xu, Yingqiang Ge, **Yunqi Li**, Xu Chen and Yongfeng Zhang. In *Proceedings of the 30th ACM International Conference on Information and Knowledge Management (**CIKM**)*, 2021.        

**Towards Long-term Fairness in Recommendation**       
Yingqiang Ge, Shuchang Liu, Ruoyuan Gao, Yikun Xian, **Yunqi Li**, Xiangyu Zhao, Changhua Pei et al. In *Proceedings of the 14th ACM International Conference on Web Search and Data Mining (**WSDM**)*, 2021.      
[paper](https://arxiv.org/pdf/2101.03584.pdf)

**Learning Post-Hoc Causal Explanations for Recommendation**       
Shuyuan Xu, **Yunqi Li**, Shuchang Liu, Zuohui Fu, Xu Chen and Yongfeng Zhang. In *Proceedings of the 1st International Workshops on Causality in Search and Recommendation (CSR) at SIGIR-21*, 2021.     
[paper](https://arxiv.org/pdf/2006.16977.pdf)


## 2020
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

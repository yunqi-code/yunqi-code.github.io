---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Preprints  
  
  
  
**Causal Collaborative Filtering**    
Shuyuan Xu, Yingqiang Ge, **Yunqi Li**, Zuohui Fu, Xu Chen, and Yongfeng Zhang. arXiv preprint arXiv:2102.01868 (2021)      
[paper](https://arxiv.org/pdf/2102.01868.pdf)

**Learning Post-Hoc Causal Explanations for Recommendation**       
Shuyuan Xu, **Yunqi Li**, Shuchang Liu, Zuohui Fu, and Yongfeng Zhang. arXiv preprint arXiv:2006.16977 (2020).     
[paper](https://arxiv.org/pdf/2006.16977.pdf)

## 2021
**User-oriented Fairness in Recommendation**      
**Yunqi Li**, Hanxiong Chen, Zuohui Fu, Yingqiang Ge, Yongfeng Zhang. In *Proceedings of the Web Conference (WWW)*, 2021.

**Neural Collaborative Reasoning**       
Hanxiong Chen, Shaoyun Shi, **Yunqi Li**, Yongfeng Zhang. In *Proceedings of the Web Conference (WWW)*, 2021.

**Towards Long-term Fairness in Recommendation**       
Yingqiang Ge, Shuchang Liu, Ruoyuan Gao, Yikun Xian, **Yunqi Li**, Xiangyu Zhao, Changhua Pei et al. In *Proceedings of the 14th ACM International Conference on Web Search and Data Mining (WSDM)*, 2021.      
[paper](https://arxiv.org/pdf/2101.03584.pdf)


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

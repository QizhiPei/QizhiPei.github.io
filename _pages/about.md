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

Kaiyuan Gao (高开元 in Chinese) is currently a member of the joint Ph.D. program between [Huazhong University of Science and Technology (HUST)](https://www.hust.edu.cn/) and [Microsoft Research AI4Science](https://www.microsoft.com/en-us/research/lab/microsoft-research-ai-for-science/) (Asia), advised by [Prof. Kun He](http://faculty.hust.edu.cn/hekun/en/index.htm) and [Dr. Tie-Yan Liu](https://www.microsoft.com/en-us/research/people/tyliu/). He got the B.S. degree from [School of Artificial Intelligence and Automation](https://aia.hust.edu.cn/), HUST in 2021. He currently is a member of [AI4Science Research Project](https://ai4sci-research.github.io), mentored by [Dr. Lijun Wu](https://apeterswu.github.io/). He also works closely with [Qizhi Pei](https://qizhipei.github.io/).

His researches focus on AI4science, geometric deep learning, and multi-modal learning for biomolecule. 

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat. -->

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.05*: &nbsp;🎉🎉 BioT5+ is accepted by ACL 2024 (Findings). Thanks for all collaborators!
- *2023.10*: &nbsp;🎉🎉 BioT5 is accepted by EMNLP 2023. Thanks for all collaborators!
- *2023.09*: &nbsp;🎉🎉 FABind is accepted by NeurIPS 2023. Thanks for all collaborators!
- *2023.08*: &nbsp;🎉🎉 ABGNN is accepted by KDD 2023. Thanks for all collaborators!
- *2023.02*: &nbsp;🎉🎉 NAGphormer is accepted by ICLR 2023. Thanks for all collaborators!

# 📝 Publications
("*": equal contribution; "†": correspondence)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/fabind.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[FABind: Fast and Accurate Protein-Ligand Binding](https://arxiv.org/pdf/2310.06763.pdf) \\
Qizhi Pei<sup>* </sup>, **Kaiyuan Gao**<sup>* </sup>, Lijun Wu<sup>† </sup>, Jinhua Zhu, Yingce Xia, Shufang Xie, Tao Qin, Kun He, Tie-Yan Liu, Rui Yan<sup>† </sup>

[**Project**](https://neurips.cc/virtual/2023/poster/71739) \| [![](https://img.shields.io/github/stars/QizhiPei/FABind?style=social&label=Code+Stars)](https://github.com/QizhiPei/FABind) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Model)](https://huggingface.co/QizhiPei/FABind_model/tree/main)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2023</div><img src='images/biot5.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BioT5: Enriching Cross-modal Integration in Biology with Chemical Knowledge and Natural Language Associations](https://arxiv.org/abs/2310.07276) \\
Qizhi Pei, Wei Zhang, Jinhua Zhu, Kehan Wu, **Kaiyuan Gao**, Lijun Wu, Yingce Xia, Rui Yan

[**Project**](https://github.com/QizhiPei/BioT5) \| [![](https://img.shields.io/github/stars/QizhiPei/BioT5?style=social&label=Code+Stars)](https://github.com/QizhiPei/BioT5) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Model)](https://huggingface.co/QizhiPei/biot5-base/tree/main) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Data)](https://huggingface.co/datasets/QizhiPei/BioT5_finetune_dataset)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024 (Findings)</div><img src='images/biot5_plus.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BioT5+: Towards Generalized Biological Understanding with IUPAC Integration and Multi-task Tuning](https://arxiv.org/abs/2402.17810) \\
Qizhi Pei, Lijun Wu, **Kaiyuan Gao**, Xiaozhuan Liang, Yin Fang, Jinhua Zhu, Shufang Xie, Tao Qin, Rui Yan

[**Project**](https://github.com/QizhiPei/BioT5) \| [![](https://img.shields.io/github/stars/QizhiPei/BioT5?style=social&label=Code+Stars)](https://github.com/QizhiPei/BioT5)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2024</div><img src='images/cmbl_survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Leveraging Biomolecule and Natural Language through Multi-Modal Learning: A Survey](https://arxiv.org/abs/2403.01528) \\
Qizhi Pei, Lijun Wu, **Kaiyuan Gao**, Jinhua Zhu, Yue Wang, Zun Wang, Tao Qin, Rui Yan

[**Project**](https://github.com/QizhiPei/Awesome-Biomolecule-Language-Cross-Modeling) \| [![](https://img.shields.io/github/stars/QizhiPei/Awesome-Biomolecule-Language-Cross-Modeling?style=social&label=Code+Stars)](https://github.com/QizhiPei/Awesome-Biomolecule-Language-Cross-Modeling)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2024</div><img src='images/fabind_plus.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FABind+: Enhancing Molecular Docking through Improved Pocket Prediction and Pose Generation](https://arxiv.org/abs/2403.20261) \\
**Kaiyuan Gao**$^*$, Qizhi Pei$^*$, Gongbo Zhang, Jinhua Zhu, Tao Qin, Kun He, Lijun Wu$^†$

[**Project**](https://github.com/QizhiPei/FABind) \| [![](https://img.shields.io/github/stars/QizhiPei/FABind?style=social&label=Code+Stars)](https://github.com/QizhiPei/FABind)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2023</div><img src='images/gpt_alter_survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Examining User-Friendly and Open-Sourced Large GPT Models: A Survey on Language, Multimodal, and Scientific GPT Models](https://arxiv.org/abs/2308.14149) \\
**Kaiyuan Gao**, Sunan He, Zhenyu He, Jiacheng Lin, Qizhi Pei, Jie Shao, Wei Zhang

[**Project**](https://github.com/GPT-Alternatives/gpt_alternatives) \| [![](https://img.shields.io/github/stars/GPT-Alternatives/gpt_alternatives?style=social&label=Code+Stars)](https://github.com/GPT-Alternatives/gpt_alternatives)
</div>
</div>

<!-- # 🎖 Honors and Awards
- *2023* Doctoral Scholarship for Elite Innovative Talents of Renmin University of China (中国人民大学拔尖创新人才).
- *2022*, Excellent Graduation Thesis, USTC.
- *2022*, Outstanding Undergraduate Awards, USTC.
- *2018~2021*, Outstanding Student Scholarship, USTC. -->

<!-- # 📖 Educations
- *2022.09 - Now*, Ph.D. student in the Gaoling School of Artificial Intelligence, Renmin University of China.
- *2018.09 - 2022.06*, undergraduate student in the School of Computer Science and Technology, University of Science and Technology of China. -->

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2023.07 - Now*, [Microsoft Research AI4Science](https://www.microsoft.com/en-us/research/lab/microsoft-research-ai4science/), Beijing, China.
- *2021.07 - 2023.01*, [Microsoft Research Asia](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/), Beijing, China. -->
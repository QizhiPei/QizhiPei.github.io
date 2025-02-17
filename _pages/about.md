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

Qizhi Pei (裴启智 in Chinese) is currently a third year Ph.D. student at the [ALOHA group](https://aloha.show) of [Gaoling School of Artificial Intelligence (GSAI)](http://ai.ruc.edu.cn/) in [Renmin University of China (RUC)](https://www.ruc.edu.cn/), supervised by [Prof. Rui Yan](https://gsai.ruc.edu.cn/ruiyan). He got the B.S. degree from [School of Computer Science and Technology](https://cs.ustc.edu.cn/), [University of Science and Technology of China (USTC)](https://www.ustc.edu.cn/) in 2022. He currently is an intern of [Shanghai Artificial Intelligent Laboratory](https://www.shlab.org.cn/), mentored by [Dr. Lijun Wu](https://apeterswu.github.io/). He is also a member of [AI4Science Research Project](https://ai4sci-research.github.io).

His researches focus on AI4science, multi-modal learning for molecule, and data synthesis for NLP.

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat. -->

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.02*: &nbsp;🔥🔥 [NatureLM](https://arxiv.org/abs/2502.07527) is made public. See [project page](https://naturelm.github.io/) for more information.
- *2025.01*: &nbsp;🎉🎉 [3D-MolT5](https://openreview.net/forum?id=eGqQyTAbXC) is accepted by ICLR 2025. Thanks for all collaborators!
- *2024.12*: &nbsp;🔥🔥 [Mol-StrucTok](https://arxiv.org/abs/2412.01564) is submitted to Arxiv.
- *2024.11*: &nbsp;🎉🎉 [FABind+](https://arxiv.org/abs/2403.20261) is accepted by KDD 2025. Congrats to Kaiyuan!
- *2024.07*: &nbsp;🎉🎉 The enhanced version of BioT5+ achieves remarkable results in [Language + Molecule @ ACL2024 Workshop/Competition](https://language-plus-molecules.github.io/#leaderboard): 
  - 🥇 1st Place in the Text-based Molecule Generation Track.
  - 🥈 2nd Place in the Molecular Captioning Track.
  - 🎤 [Oral presentation](https://openreview.net/forum?id=Fib0IJt8YW) in the workshop.
- *2024.07*: &nbsp;🎉🎉 [kNN-DTA](https://dl.acm.org/doi/abs/10.1145/3627673.3679704) is accepted by CIKM 2024. Thanks for all collaborators!
- *2024.06*: &nbsp; [3D-MolT5](https://arxiv.org/abs/2406.05797) is submitted to Arxiv.
- *2024.05*: &nbsp;🎉🎉 [BioT5+](https://arxiv.org/abs/2402.17810) is accepted by ACL 2024 (Findings). Thanks for all collaborators!
- *2024.03*: &nbsp; [FABind+](https://arxiv.org/abs/2403.20261) is submitted to Arxiv.
- *2024.03*: &nbsp; A [survey](https://arxiv.org/abs/2403.01528) about cross-modal learning for biomolecule is submitted to Arxiv.
- *2023.10*: &nbsp;🎉🎉 [BioT5](https://arxiv.org/abs/2310.07276) is accepted by EMNLP 2023. Thanks for all collaborators!
- *2023.10*: &nbsp;🎉🎉 [SSM-DTA](https://doi.org/10.1093/bib/bbad386) is accepted by Briefings in Bioinformatics 2023. Thanks for all collaborators!
- *2023.09*: &nbsp;🎉🎉 [FABind](https://arxiv.org/pdf/2310.06763.pdf) is accepted by NeurIPS 2023. Thanks for all collaborators!

# 📝 Publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/3d_molt5.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[3D-MolT5: Leveraging Discrete Structural Information for Molecule-Text Modeling](https://openreview.net/forum?id=eGqQyTAbXC) \\
**Qizhi Pei**, Lijun Wu, Kaiyuan Gao, Jinhua Zhu, Rui Yan

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024 (Findings)</div><img src='images/biot5_plus.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BioT5+: Towards Generalized Biological Understanding with IUPAC Integration and Multi-task Tuning](https://arxiv.org/abs/2402.17810) \\
**Qizhi Pei**, Lijun Wu, Kaiyuan Gao, Xiaozhuan Liang, Yin Fang, Jinhua Zhu, Shufang Xie, Tao Qin, Rui Yan

[**Project**](https://github.com/QizhiPei/BioT5) \| [![](https://img.shields.io/github/stars/QizhiPei/BioT5?style=social&label=Code+Stars)](https://github.com/QizhiPei/BioT5) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Model)](https://huggingface.co/QizhiPei/biot5-plus-base/tree/main) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Data)](https://huggingface.co/datasets/QizhiPei/BioT5_finetune_dataset)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2023</div><img src='images/biot5.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BioT5: Enriching Cross-modal Integration in Biology with Chemical Knowledge and Natural Language Associations](https://arxiv.org/abs/2310.07276) \\
**Qizhi Pei**, Wei Zhang, Jinhua Zhu, Kehan Wu, Kaiyuan Gao, Lijun Wu, Yingce Xia, Rui Yan

[**Project**](https://github.com/QizhiPei/BioT5) \| [![](https://img.shields.io/github/stars/QizhiPei/BioT5?style=social&label=Code+Stars)](https://github.com/QizhiPei/BioT5) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Model)](https://huggingface.co/QizhiPei/biot5-base/tree/main) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Data)](https://huggingface.co/datasets/QizhiPei/BioT5_finetune_dataset)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/fabind.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FABind: Fast and Accurate Protein-Ligand Binding](https://arxiv.org/pdf/2310.06763.pdf) \\
**Qizhi Pei**(co-first author), Kaiyuan Gao, Lijun Wu, Jinhua Zhu, Yingce Xia, Shufang Xie, Tao Qin, Kun He, Tie-Yan Liu, Rui Yan

[**Project**](https://neurips.cc/virtual/2023/poster/71739) \| [![](https://img.shields.io/github/stars/QizhiPei/FABind?style=social&label=Code+Stars)](https://github.com/QizhiPei/FABind) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Model)](https://huggingface.co/QizhiPei/FABind_model/tree/main)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Language + Molecules @ ACL 2024 Workshop (Oral)</div><img src='images/lpm24_workshop.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enhanced BioT5+ for Molecule-Text Translation: A Three-Stage Approach with Data Distillation, Diverse Training, and Voting Ensemble](https://aclanthology.org/2024.langmol-1.6.pdf) \\
**Qizhi Pei**, Lijun Wu, Kaiyuan Gao, Jinhua Zhu, Rui Yan

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIKM 2024</div><img src='images/knn_dta.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploiting Pre-trained Models for Drug Target Affinity Prediction with Nearest Neighbors](https://dl.acm.org/doi/abs/10.1145/3627673.3679704) \\
**Qizhi Pei**(co-first author), Lijun Wu, Zhenyu He, Jinhua Zhu, Yingce Xia, Shufang Xie, Rui Yan

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Briefings in Bioinformatics 2023</div><img src='images/ssm_dta.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SSM-DTA: Breaking the Barriers of Data Scarcity in Drug-Target Affinity Prediction](https://doi.org/10.1093/bib/bbad386) \\
**Qizhi Pei**, Lijun Wu, Jinhua Zhu, Yingce Xia, Shufang Xie, Tao Qin, Haiguang Liu, Tie-Yan Liu, Rui Yan

[**Project**](https://github.com/QizhiPei/SSM-DTA) \| [![](https://img.shields.io/github/stars/QizhiPei/SSM-DTA?style=social&label=Code+Stars)](https://github.com/QizhiPei/SSM-DTA)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2024</div><img src='images/fabind_plus.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FABind+: Enhancing Molecular Docking through Improved Pocket Prediction and Pose Generation](https://arxiv.org/abs/2403.20261) \\
Kaiyuan Gao, **Qizhi Pei**, Jinhua Zhu, Tao Qin, Kun He, Lijun Wu

[**Project**](https://github.com/QizhiPei/FABind) \| [![](https://img.shields.io/github/stars/QizhiPei/FABind?style=social&label=Code+Stars)](https://github.com/QizhiPei/FABind)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Nature Communications 2024</div><img src='images/tamgen.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TamGen: drug design with target-aware molecule generation through a chemical language model](https://www.nature.com/articles/s41467-024-53632-4) \\
Kehan Wu, Yingce Xia, Pan Deng, Renhe Liu, Yuan Zhang, Han Guo, Yumeng Cui, **Qizhi Pei**, Lijun Wu, Shufang Xie, Si Chen, Xi Lu, Song Hu, Jinzhi Wu, Chi-Kin Chan, Shawn Chen, Liangliang Zhou, Nenghai Yu, Enhong Chen, Haiguang Liu, Jinjiang Guo, Tao Qin, Tie-Yan Liu 

[**Project**](https://github.com/SigmaGenX/TamGen) \| [![](https://img.shields.io/github/stars/SigmaGenX/TamGen?style=social&label=Code+Stars)](https://github.com/SigmaGenX/TamGen)
</div>
</div>

# 📝 Preprints
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2024</div><img src='images/cmbl_survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Leveraging Biomolecule and Natural Language through Multi-Modal Learning: A Survey](https://arxiv.org/abs/2403.01528) \\
**Qizhi Pei**, Lijun Wu, Kaiyuan Gao, Jinhua Zhu, Yue Wang, Zun Wang, Tao Qin, Rui Yan

[**Project**](https://github.com/QizhiPei/Awesome-Biomolecule-Language-Cross-Modeling) \| [![](https://img.shields.io/github/stars/QizhiPei/Awesome-Biomolecule-Language-Cross-Modeling?style=social&label=Code+Stars)](https://github.com/QizhiPei/Awesome-Biomolecule-Language-Cross-Modeling)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2024</div><img src='images/mol_structok.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Tokenizing 3D Molecule Structure with Quantized Spherical Coordinates](https://arxiv.org/abs/2412.01564) \\
Kaiyuan Gao, Yusong Wang, Haoxiang Guan, Zun Wang, **Qizhi Pei**, John E. Hopcroft, Kun He, and Lijun Wu.

[**Project**](https://github.com/KyGao/Mol-StrucTok) \| [![](https://img.shields.io/github/stars/KyGao/Mol-StrucTok?style=social&label=Code+Stars)](https://github.com/KyGao/Mol-StrucTok)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2023</div><img src='images/gpt_alter_survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Examining User-Friendly and Open-Sourced Large GPT Models: A Survey on Language, Multimodal, and Scientific GPT Models](https://arxiv.org/abs/2308.14149) \\
Kaiyuan Gao, Sunan He, Zhenyu He, Jiacheng Lin, **Qizhi Pei**, Jie Shao, Wei Zhang

[**Project**](https://github.com/GPT-Alternatives/gpt_alternatives) \| [![](https://img.shields.io/github/stars/GPT-Alternatives/gpt_alternatives?style=social&label=Code+Stars)](https://github.com/GPT-Alternatives/gpt_alternatives)
</div>
</div>

# 🎖 Honors and Awards
- *2023* Doctoral Scholarship for Elite Innovative Talents of Renmin University of China (中国人民大学拔尖创新人才).
- *2022*, Excellent Graduation Thesis, USTC.
- *2022*, Outstanding Undergraduate Awards, USTC.
- *2018~2021*, Outstanding Student Scholarship, USTC.

# 📖 Educations
- *2022.09 - Now*, Ph.D. student in the Gaoling School of Artificial Intelligence, Renmin University of China.
- *2018.09 - 2022.06*, undergraduate student in the School of Computer Science and Technology, University of Science and Technology of China.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2024.09 - now*, [Shanghai Artificial Intelligent Laboratory](https://www.shlab.org.cn/), Beijing, China
- *2023.07 - 2024.06*, [Microsoft Research AI4Science](https://www.microsoft.com/en-us/research/lab/microsoft-research-ai4science/), Beijing, China.
- *2021.07 - 2023.01*, [Microsoft Research Asia](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/), Beijing, China.
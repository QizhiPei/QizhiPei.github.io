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

Qizhi Pei (裴启智 in Chinese) is currently a fourth year Ph.D. student at the [ALOHA group](https://aloha.show) of [Gaoling School of Artificial Intelligence (GSAI)](http://ai.ruc.edu.cn/) in [Renmin University of China (RUC)](https://www.ruc.edu.cn/), supervised by [Prof. Rui Yan](https://gsai.ruc.edu.cn/ruiyan). He got the B.S. degree from [School of Computer Science and Technology](https://cs.ustc.edu.cn/), [University of Science and Technology of China (USTC)](https://www.ustc.edu.cn/) in 2022. He currently is an intern of [OpenDataLab](https://opendataarena.github.io) in [Shanghai Artificial Intelligent Laboratory](https://www.shlab.org.cn/), mentored by [Dr. Lijun Wu](https://apeterswu.github.io/).
His researches focus on 
* AI4science, including scientific foundation model ([BioT5](https://arxiv.org/abs/2310.07276), [BioT5+](https://arxiv.org/abs/2402.17810), [3D-MolT5](https://openreview.net/forum?id=eGqQyTAbXC), [NatureLM](https://arxiv.org/abs/2502.07527)) and biomolecule interaction ([FABind](https://arxiv.org/pdf/2310.06763.pdf), [FABind+](https://arxiv.org/abs/2403.20261), [kNN-DTA](https://dl.acm.org/doi/abs/10.1145/3627673.3679704), [SSM-DTA](https://doi.org/10.1093/bib/bbad386))
* LLMs, including mathematical reasoning ([MathFusion](https://arxiv.org/abs/2503.16212), [LEMMA](https://arxiv.org/abs/2503.17439), [MetaLadder](https://arxiv.org/abs/2503.14891), [REST](https://arxiv.org/abs/2507.10541)) and data synthesis ([Middo](https://arxiv.org/abs/2508.21589), [GRA](https://arxiv.org/abs/2504.12322))

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat. -->

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.08*: &nbsp;🔥🔥 [ScaleDiff](https://arxiv.org/abs/2509.21070) is made public.
- *2025.08*: &nbsp;🎉🎉 [MetaLadder](https://arxiv.org/abs/2503.14891) and [Middo](https://arxiv.org/abs/2508.21589) is accepted by EMNLP 2025. Congrats to Honglin and Zinan!
- *2025.08*: &nbsp;🔥🔥 We release [OpenDataArena](https://opendataarena.github.io/) -- a fair, open, and transparent arena for data.
- *2025.07*: &nbsp;🔥🔥 [REST](https://arxiv.org/abs/2507.10541) is made public. See [project page](https://opendatalab.github.io/REST/) for more information.
- *2025.05*: &nbsp;🎉🎉 [MathFusion](https://arxiv.org/abs/2503.16212) is accepted by ACL 2025 (main). Thanks for all collaborators!
- *2025.02*: &nbsp;🔥🔥 [NatureLM](https://arxiv.org/abs/2502.07527) is made public. See [project page](https://naturelm.github.io/) for more information.
- *2025.01*: &nbsp;🎉🎉 [3D-MolT5](https://openreview.net/forum?id=eGqQyTAbXC) is accepted by ICLR 2025. Thanks for all collaborators!
- *2024.11*: &nbsp;🎉🎉 [FABind+](https://arxiv.org/abs/2403.20261) is accepted by KDD 2025. Congrats to Kaiyuan!
- *2024.07*: &nbsp;🎉🎉 The enhanced version of BioT5+ achieves remarkable results in [Language + Molecule @ ACL2024 Workshop/Competition](https://language-plus-molecules.github.io/#leaderboard): 
  - 🥇 [1st Place in the Text-based Molecule Generation Track](https://language-plus-molecules.github.io/#leaderboard:~:text=Text%2DBased%20Molecule%20Generation).
  - 🥈 [2nd Place in the Molecular Captioning Track](https://language-plus-molecules.github.io/#leaderboard:~:text=Molecular%20Captioning).
  - 🎤 [Oral presentation](https://openreview.net/forum?id=Fib0IJt8YW) in the workshop.

# 📝 AI4Science
1. `EMNLP 2023`: [BioT5: Enriching Cross-modal Integration in Biology with Chemical Knowledge and Natural Language Associations](https://arxiv.org/abs/2310.07276), **Qizhi Pei**, Wei Zhang, Jinhua Zhu, Kehan Wu, Kaiyuan Gao, Lijun Wu, Yingce Xia, Rui Yan, \| [![](https://img.shields.io/github/stars/QizhiPei/BioT5?style=social&label=Code+Stars)](https://github.com/QizhiPei/BioT5) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/collections/QizhiPei/biot5-67582fe5a72313e29a0dd779) (**>12W model downloads**)

2. `ACL 2024 (Findings)`: [BioT5+: Towards Generalized Biological Understanding with IUPAC Integration and Multi-task Tuning](https://arxiv.org/abs/2402.17810), **Qizhi Pei**, Lijun Wu, Kaiyuan Gao, Xiaozhuan Liang, Yin Fang, Jinhua Zhu, Shufang Xie, Tao Qin, Rui Yan \| [![](https://img.shields.io/github/stars/QizhiPei/BioT5?style=social&label=Code+Stars)](https://github.com/QizhiPei/BioT5) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/collections/QizhiPei/biot5-67582fe5a72313e29a0dd779)

3. `ICLR 2025`: [3D-MolT5: Leveraging Discrete Structural Information for Molecule-Text Modeling](https://openreview.net/forum?id=eGqQyTAbXC), **Qizhi Pei**, Lijun Wu, Kaiyuan Gao, Jinhua Zhu, Rui Yan \| [![](https://img.shields.io/github/stars/QizhiPei/3D-MolT5?style=social&label=Code+Stars)](https://github.com/QizhiPei/3D-MolT5) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/collections/QizhiPei/3d-molt5-68b561939178c4b5a349b45f)

4. `NeurIPS 2023`: [FABind: Fast and Accurate Protein-Ligand Binding](https://arxiv.org/pdf/2310.06763.pdf), **Qizhi Pei** (co-first author), Kaiyuan Gao, Lijun Wu, Jinhua Zhu, Yingce Xia, Shufang Xie, Tao Qin, Kun He, Tie-Yan Liu, Rui Yan \| [Project Page](https://qizhipei.github.io/fabind) \| [![](https://img.shields.io/github/stars/QizhiPei/FABind?style=social&label=Code+Stars)](https://github.com/QizhiPei/FABind) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/QizhiPei/FABind_model/tree/main)

5. `Language + Molecules @ ACL 2024 Workshop (Oral)`: [Enhanced BioT5+ for Molecule-Text Translation: A Three-Stage Approach with Data Distillation, Diverse Training, and Voting Ensemble](https://aclanthology.org/2024.langmol-1.6.pdf), **Qizhi Pei**, Lijun Wu, Kaiyuan Gao, Jinhua Zhu, Rui Yan
   1. 🥇 **1st Place** in the [Text-based Molecule Generation Track](https://language-plus-molecules.github.io/#leaderboard:~:text=Text%2DBased%20Molecule%20Generation).
   2. 🥈 **2nd Place** in the [Molecular Captioning Track](https://language-plus-molecules.github.io/#leaderboard:~:text=Molecular%20Captioning).

6. `CIKM 2024`: [Exploiting Pre-trained Models for Drug Target Affinity Prediction with Nearest Neighbors](https://dl.acm.org/doi/abs/10.1145/3627673.3679704), **Qizhi Pei** (co-first author), Lijun Wu, Zhenyu He, Jinhua Zhu, Yingce Xia, Shufang Xie, Rui Yan

7. `Briefings in Bioinformatics 2023`: [SSM-DTA: Breaking the Barriers of Data Scarcity in Drug-Target Affinity Prediction](https://doi.org/10.1093/bib/bbad386), **Qizhi Pei**, Lijun Wu, Jinhua Zhu, Yingce Xia, Shufang Xie, Tao Qin, Haiguang Liu, Tie-Yan Liu, Rui Yan \| [![](https://img.shields.io/github/stars/QizhiPei/SSM-DTA?style=social&label=Code+Stars)](https://github.com/QizhiPei/SSM-DTA)

8. `KDD 2025`: [FABind+: Enhancing Molecular Docking through Improved Pocket Prediction and Pose Generation](https://arxiv.org/abs/2403.20261) \\
Kaiyuan Gao, **Qizhi Pei**, Jinhua Zhu, Tao Qin, Kun He, Lijun Wu \| [![](https://img.shields.io/github/stars/QizhiPei/FABind?style=social&label=Code+Stars)](https://github.com/QizhiPei/FABind)

1. `Nature Communications 2024`: [TamGen: drug design with target-aware molecule generation through a chemical language model](https://www.nature.com/articles/s41467-024-53632-4), Kehan Wu, Yingce Xia, Pan Deng, Renhe Liu, Yuan Zhang, Han Guo, Yumeng Cui, **Qizhi Pei**, ... , Tao Qin, Tie-Yan Liu \| [![](https://img.shields.io/github/stars/SigmaGenX/TamGen?style=social&label=Code+Stars)](https://github.com/SigmaGenX/TamGen)

2.  `Preprint`: [Leveraging Biomolecule and Natural Language through Multi-Modal Learning: A Survey](https://arxiv.org/abs/2403.01528), **Qizhi Pei**, Lijun Wu, Kaiyuan Gao, Jinhua Zhu, Yue Wang, Zun Wang, Tao Qin, Rui Yan \| [![](https://img.shields.io/github/stars/QizhiPei/Awesome-Biomolecule-Language-Cross-Modeling?style=social&label=Code+Stars)](https://github.com/QizhiPei/Awesome-Biomolecule-Language-Cross-Modeling)

3.  `Preprint`: [Nature Language Model: Deciphering the Language of Nature for Scientific Discovery](https://arxiv.org/abs/2502.07527), Yingce Xia, Peiran Jin, Shufang Xie, Liang He, Chuan Cao, ... , **Qizhi Pei**, ... , Tie-Yan Liu, Haiguang Liu, Tao Qin \| [Project](https://naturelm.github.io/) \| [![](https://img.shields.io/github/stars/microsoft/SFM?style=social&label=Code+Stars)](https://github.com/microsoft/SFM) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/collections/microsoft/naturelm-685142a78ede3cd04391af4f)

4.  `Preprint` [Tokenizing 3D Molecule Structure with Quantized Spherical Coordinates](https://arxiv.org/abs/2412.01564), Kaiyuan Gao, Yusong Wang, Haoxiang Guan, Zun Wang, **Qizhi Pei**, John E. Hopcroft, Kun He, and Lijun Wu \| [![](https://img.shields.io/github/stars/KyGao/Mol-StrucTok?style=social&label=Code+Stars)](https://github.com/KyGao/Mol-StrucTok)

# 📝 LLMs
1. `ACL 2025`: [MathFusion: Enhancing Mathematic Problem-solving of LLM through Instruction Fusion](https://arxiv.org/abs/2503.16212), **Qizhi Pei**, Lijun Wu, Zhuoshi Pan, Yu Li, Honglin Lin, Chenlin Ming, Xin Gao, Conghui He, Rui Yan \| [![](https://img.shields.io/github/stars/QizhiPei/mathfusion?style=social&label=Code+Stars)](https://github.com/QizhiPei/mathfusion) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/collections/QizhiPei/mathfusion-67d92b8e505635db1baf20bb)

2. `ACL 2025`: [A Strategic Coordination Framework of Small LLMs Matches Large LLMs in Data Synthesis](https://arxiv.org/abs/2504.12322), Xin Gao, **Qizhi Pei**, Zinan Tang, Yu Li, Honglin Lin, Jiang Wu, Lijun Wu, Conghui He \| [![](https://img.shields.io/github/stars/GX-XinGao/GRA?style=social&label=Code+Stars)](https://github.com/GX-XinGao/GRA)

3. `ACL 2025 (Findings)`: [CipherBank: Exploring the Boundary of LLM Reasoning Capabilities through Cryptography Challenges](https://arxiv.org/abs/2504.19093), Yu Li, **Qizhi Pei**, Mengyuan Sun, Honglin Lin, Chenlin Ming, Xin Gao, Jiang Wu, Conghui He, Lijun Wu \| [![](https://img.shields.io/github/stars/Goodman-liyu/CipherBank?style=social&label=Code+Stars)](https://github.com/Goodman-liyu/CipherBank)

4. `ACL 2025 (Findings)`: [LEMMA: Learning from Errors for MatheMatical Advancement in LLMs](https://arxiv.org/abs/2503.17439), Zhuoshi Pan, Yu Li, Honglin Lin, **Qizhi Pei**, Zinan Tang, Wei Wu, Chenlin Ming, H. Vicky Zhao, Conghui He, Lijun Wu \| [![](https://img.shields.io/github/stars/pzs19/LEMMA?style=social&label=Code+Stars)](https://github.com/pzs19/LEMMA) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/collections/panzs19/lemma-68620ced6bedc62fff843e43)

5. `EMNLP 2025`: [Middo: Model-Informed Dynamic Data Optimization for Enhanced LLM Fine-Tuning via Closed-Loop Learning](https://arxiv.org/abs/2508.21589), Zinan Tang, Xin Gao, **Qizhi Pei**, Zhuoshi Pan, Mengzhang Cai, Jiang Wu, Conghui He, Lijun Wu

6. `EMNLP 2025 (Findings)`: [MetaLadder: Ascending Mathematical Solution Quality via Analogical-Problem Reasoning Transfer](https://arxiv.org/abs/2503.14891), Honglin Lin, Zhuoshi Pan, Yu Li, **Qizhi Pei**, Xin Gao, Mengzhang Cai, Conghui He, Lijun Wu \| [Project](https://github.com/LHL3341/MetaLadder) \| [![](https://img.shields.io/github/stars/LHL3341/MetaLadder?style=social&label=Code+Stars)](https://github.com/LHL3341/MetaLadder)

7. `Preprint`: [ScaleDiff: Scaling Difficult Problems for Advanced Mathematical Reasoning](https://arxiv.org/abs/2509.21070), **Qizhi Pei**, Zhuoshi Pan, Honglin Lin, Xin Gao, Yu Li, Zinan Tang, Conghui He, Rui Yan, Lijun Wu \| [![](https://img.shields.io/github/stars/QizhiPei/ScaleDiff?style=social&label=Code+Stars)](https://github.com/QizhiPei/ScaleDiff) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/collections/QizhiPei/scalediff-68a71cc18839c1cc1471187e)

8. `Preprint`: [Stress Testing Large Reasoning Models by Asking Multiple Problems at Once](https://arxiv.org/abs/2507.10541), Zhuoshi Pan, **Qizhi Pei** (co-first author), Yu Li, Qiyao Sun, Zinan Tang, H. Vicky Zhao, Conghui He, Lijun Wu \| [Project](https://opendatalab.github.io/REST/) \| [![](https://img.shields.io/github/stars/opendatalab/REST?style=social&label=Code+Stars)](https://github.com/opendatalab/REST)

9. `Preprint`: [IDEAL: Data Equilibrium Adaptation for Multi-Capability Language Model Alignment](https://arxiv.org/abs/2505.12762), Chenlin Ming, Chendi Qu, Mengzhang Cai, **Qizhi Pei**, Zhuoshi Pan, Yu Li, Xiaoming Duan, Lijun Wu, Conghui He

10. `Preprint`: [Examining User-Friendly and Open-Sourced Large GPT Models: A Survey on Language, Multimodal, and Scientific GPT Models](https://arxiv.org/abs/2308.14149), Kaiyuan Gao, Sunan He, Zhenyu He, Jiacheng Lin, **Qizhi Pei**, Jie Shao, Wei Zhang \| [![](https://img.shields.io/github/stars/GPT-Alternatives/gpt_alternatives?style=social&label=Code+Stars)](https://github.com/GPT-Alternatives/gpt_alternatives)

# 🎖 Honors and Awards
- *2023*, Doctoral Scholarship for Elite Innovative Talents of Renmin University of China (中国人民大学拔尖创新人才).
- *2022*, Excellent Graduation Thesis, USTC.
- *2022*, Outstanding Undergraduate Awards, USTC.
- *2018~2021*, Outstanding Student Scholarship, USTC.

# 💬 Academic Service
- Reviewer: NeurIPS, ACL, EMNLP, KDD, ICLR

# 📖 Educations
- *2022.09 - Now*, Ph.D. student in the Gaoling School of Artificial Intelligence, Renmin University of China.
- *2018.09 - 2022.06*, undergraduate student in the School of Computer Science and Technology, University of Science and Technology of China.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2024.08 - now*, [OpenDataLab](https://opendataarena.github.io), [Shanghai Artificial Intelligent Laboratory](https://www.shlab.org.cn/), Beijing, China
- *2023.07 - 2024.06*, [Microsoft Research AI4Science](https://www.microsoft.com/en-us/research/lab/microsoft-research-ai4science/), Beijing, China.
- *2021.07 - 2023.01*, [Microsoft Research Asia](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/), Beijing, China.
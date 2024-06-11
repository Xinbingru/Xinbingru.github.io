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

# 👨‍🎓 About Me

Welcome! I am now a master student in the School of Chemical Engineering of Sichuan University. My current work focuses on the material intersection of machine learning and molecular simulation. I am interested in the prediction and discovery of properties of porous materials (MOF/COF/PNN) and polymer materials through a combination of machine learning (deep learning), molecular simulation, and materials informatics.

From 2018 to 2022, I completed my Bachelor of Engineering degree from School of Chemical Engineering, Sichuan University (四川大学化学工程学院). In 2022, I embarked on my journey towards a master's degree in the School of Chemical Engineering of Sichuan University, dedicated to the research of Process Systems Engineering (PSE). I anticipate completing my studies and earning my master's degree in 2025.

In 2024, I joined Dow Chemical<img src='./images/Dow.png' style='width: 4em;'> as part of the "Advanced Digital Intern for Science and Engineering" program (one of 14 in Asia Pacific). I will use computer vision technology to detect anomalies in photovoltaic panel luminescence.

My research interest includes machine learning and deep learning for chemical engineering materials and processes. At present, I have published four SCI papers, of which one is the first author, one is the co-first author, one is the second author and one is the other author. This is my <a href='https://scholar.google.com/citations?user=H7oehLIAAAAJ&hl=zh-CN'>google scholar<strong><span id='total_cit'></span></strong></a>.

**Especially! I am looking for a possible PhD opportunity (25fall).** If you are looking for the right candidate or for any kind of academic exchange and collaboration, please do not hesitate to email me: [xinbingru@gmail.com](mailto:xinbingru@gmail.com).

<!-- 
(You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). 
-->

# 📖 Educations

- *2022.06 - 2025.06 (expected)*, Sichuan University(SCU), School of Chemical Engineering
  - M.Phil in Chemical Engineering, advised by [Yiyang Dai (戴一阳)](https://scholar.google.com/citations?user=Upz3KwYAAAAJ&hl=zh-CN) and [Zhongde Dai (代忠德)](https://scholar.google.com/citations?user=VzwDPxYAAAAJ&hl=zh-CN)
  - GPA: 3.92/4.0, Ranking: top 3% of 230+
- *2018.09 - 2022.06*, Sichuan University(SCU), School of Chemical Engineering
  - B.Eng in process Equipment & Control Engineering
  - GPA: 3.67/4.0, Ranking: 7/81
- *2015.09 - 2018.06*, Kang jie Middle School, Yuncheng


# 🔥 News
- *2024.06*: &nbsp;🎉 Go to Florence, Italy for poster presentation at [ESCAPE34-PSE24](https://aidic.it/escape34-pse24/programma/pro.html) Academic Conference.
- *2024.04*: &nbsp;🎉🎉 The paper ['Combining interpretable machine learning and molecular simulation to advance the discovery of COF-based membrane for acid gas separation'](#ML & MS for COF-based membranes) was accepted by IECR!
- *2024.03*: &nbsp;🎉 I join Dow <img src='./images/Dow.png' style='width: 4em;'> as a digital intern in Shanghai, China.
- *2024.01*: &nbsp;🎉🎉 The paper ['A novel triage-based fault diagnosis method for chemical process'](#A novel triage-based fault diagnosis method for chemical process) was accepted by PSEP!
- *2023.07*: &nbsp; Go to the University of Macau (UM) for a two-week Summer School to take courses on artificial intelligence and Big Data.
- *2023.05*: &nbsp;🎉🎉 The paper ['Troger's base polymeric membranes for CO<sub>2</sub> separation: a review'](#Troger's base polymeric membranes for CO<sub>2</sub> separation: a review) was accepted by JMCA. I hope this is a good start.
- *2023.04*: &nbsp; I created [my academic website](https://xinbingru.github.io/) on Github. Welcome to visit! 😀


# 📝 Publications 

<a name="ML & MS for COF-based membranes"></a>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IECR 2024</div><img src='images/COFsML_toc.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**<u>Bingru Xin</u>**, Minggao Feng, Min Cheng, et al. [Combining interpretable machine learning and molecular simulation to advance the discovery of COF-based membrane for acid gas separation [J]](https://doi.org/10.1021/acs.iecr.4c00855), Industrial & Engineering Chemistry Research, 2024, 63, 18, 8369–8382.

- In this paper, we propose a method combining interpretable machine learning and molecular simulation to discover the optimal acid gas separation membrane materials from more than 70,000 covalent organic frameworks(COFs)-based membranes. Based on GCMC and MD simulation to calculate gas permeability data, an automated machine learning model is constructed by extracting 20 feature descriptors. Chemical insights of membrane separation were obtained based on the characteristic contribution of SHAP analysis.
- [**Github Project**](https://github.com/Xinbingru/COFsMembraneML.git)
- [See pdf paper](file/xin-et-al-2024-combining-interpretable-machine-learning-and-molecular-simulation-to-advance-the-discovery-of-cof-based.pdf)

</div>
</div>

<a name="A novel triage-based fault diagnosis method for chemical process"></a>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PSEP 2024</div><img src='images/TrCNN_toc.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Qucheng Tao, **<u>Bingru Xin</u>**, Yifang Zhang, et al. [A novel triage-based fault diagnosis method for chemical process [J]](https://doi.org/10.1016/j.psep.2024.01.072),Process Safety and Environmental Protection, 2024, 183: 1102-1116.

- This paper presents a classification based convolutional neural network fault diagnosis method for chemical processes. The model architecture is divided into classification layer and diagnosis layer, and the fault set is divided into different types to the corresponding subnet layer, and the fault diagnosis model is developed for each subnetwork. The model can adapt to various fault types of chemical processes and has high diagnostic accuracy.
- [See pdf paper](file/A novel triage-based fault diagnosis method for chemical precess.pdf)

</div>
</div>

<a name="Troger's base polymeric membranes for CO<sub>2</sub> separation: a review"></a>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JMCA 2023</div><img src='images/TB polymer_toc.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Qingbo Xu†, **<u>Bingru Xin† (Co-first)</u>**, Jing Wei, et al. [Troger's base polymeric membranes for CO<sub>2</sub> separation: a review [J]](https://doi.org/10.1039/D3TA03017B), Journal of Materials Chemistry A, 2023, 11, 15600-15634.
- This paper reviews and introduces gas separation membranes based on  Troger's base(TB) polymers for CO<sub>2</sub> separation. TB polymer is a polymer material connected by rigid V-shaped bridging bicyclic groups, which can enhance the rigidity of the polymer and prevent chain stacking. This paper focuses on the application of pure TB polymer membrane, functional TB polymer membrane, TB polymer-based mixed matrix membrane (MMM) and high temperature modified carbon molecular sieve(CMS)/thermal rearrangement(TR) membrane in the field of CO<sub>2</sub> separation. In addition, the future possible applications and improvement methods of TB polymer membranes are also proposed, further emphasizing the importance of data-driven for membrane separation.
- [See pdf paper](file/Troger’s base polymeric membranes for CO2 separation a review.pdf)
</div>
</div>

<!-- other paper -->
<br>
Zikang Qin, Xuan Feng, Dengguo Yin, **<u>Bingru Xin</u>**, et al. [Impact of Humidity on the CO<sub>2</sub>/N<sub>2</sub> Separation Performance of Pebax-MOF Mixed Matrix Membranes [J]](https://doi.org/10.1021/acs.iecr.3c02308). Industrial & Engineering Chemistry Research, 2023, 62(35): 14034-14046.
<br>
<br>
Guixin Wang, Nana Jing, **<u>Bingru Xin</u>**, Feiyang Wang. A method for regulating heat and deformation to improve the performance and safety of batteries and capacitors. (Chinese Patents: CN115882031A).2023, China National Intellectual Property Administration. 
<br>

# 🎖 Honors and Awards
- *2023.10*, [Brunp Scholarship](https://ce.scu.edu.cn/info/1013/13471.htm)
- *2023.10*, Outstanding graduate student (Top 10%)
- *2022.10*, [First-class Postgraduate Scholarship](https://gs.scu.edu.cn/info/1147/5256.htm) (Full scholarship, Top 5%)
- *2021.10*, [The 12th Process Equipment Practice and Innovation Competition National First Prize](http://www.gczbds.org/Web/Show?w=29&p=27&f=1957) (Top 3% in China).
- *2020.10*, Outstanding Graduates (Top 10%)
- *2019.10*, Outstanding student of the university for three consecutive years (2019-2021,Top 10%)
- *2019.10*, First-class Scholarship (Top 5%)


# 💬 Talks
- *2024.06*, Combining automated machine learning and molecular simulation to advance the discovery of COF-based membrane for acid gas separation, [ESCAPE34-PSE24](https://aidic.it/escape34-pse24/programma/pro.html),[Poster P/297](file/poster.pdf), Florence, ITALY.
- *2023.10*, Machine learning in gas separation membranes, Interconnected Chemical Engineering young Scholars Seminar, Emeishan, Sichuan, China.


# 💻 Internships
- *2024.04 - 2024.10*, Dow<img src='./images/Dow.png' style='width: 4em;'>, **A**dvanced **D**igital **I**nternship for **S**cience and **E**ngineering (**ADISE**), Shanghai, China.
- *2022.06 - 2022.10*, Tsingyun Intelligence Technology Co., Ltd, Chengdu, China.

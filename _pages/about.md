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

# 👤 Short Bio
Jiayi Wu is a member of the RoboPI lab, he is a master’s student in ECE Department of the University of Florida. His research focus is on low-cost 3D reconstruction and depth estimation in scattering medium. He is currently working on wraping up his master thesis project under the supervision of Prof. Islam. The primaly research goal of his thesis is to formulate a fast and robust underwater 3D reconstruction algorithm based on the fusion of SfM algorithm and deep learning. He is also collaboraing with other students across the lab to make it lightweight and deployable on low-power robotic systems. <a href='https://scholar.google.com/citations?user=xoZE1GsAAAAJ&hl'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

My research interest includes: 
- General Environment Vision: Make computer vision systems more robust to the environment (scattering media, bad weather)
- Low-cost 3D reconstruction and depth estimation in scattering medium
- The application of computer vision in the medical field (including but not limited to medical image processing, pathological image segmentation, image enhancement)
- AI-based Surgical Navigation: Make AI have the ability to generate structured diagnostic reports through medical images, and combine NLP algorithms and computer vision technology to achieve surgical navigation
- Surgical robot: Enable surgical robots to have accurate multi-modal fusion perception ability and precise motion control and can perform precise surgery according to the instructions analyzed by doctors or AI

# 📰 News

- 2022/09/15: The paper “UDepth: Fast Monocular Depth Estimation for Visually-guided Underwater Robots” I collaborated with Boxiao Yu and Prof. Islam was submitted to ICRA 2023.

- 2022/08/23: Completed the summer internship at Vobile and got a return offer (recommended by Dr. Zhao).

- 2022/05/23: Joined the team of Dr. Zhao (CTO of Vobile) of Vobile as an audio and video algorithm development engineer (summer internship).

- 2022/01/10: Join Professor Judge's Remote Sensing Lab (as Graduate Student Assistant) and be responsible for the development of a large-scale automated generation of 3D plant models.

# 🎓 Educations 
><a href="https://www.ece.ufl.edu/"><img class="svg" src="/images/UFL_logo.png" width="45pt"></a>  ***University of Florida***
>>- ***M.S.(Thesis) in Electrical and Computer Engineering*** --------- *Aug. 2021- Present*  
Supervised by Prof. Islam.

><a href="https://mechanical.zstu.edu.cn/"><img class="svg" src="/images/ZSTU_logo.png" width="45pt"></a>   ***Zhejiang Sci-Tech University (ZSTU)***
>>- ***B.E. in Mechatronic Engineering*** --------- *Sept. 2017- Jun. 2021*
 

# 📝 Publications 

### Preprints 
---
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2023 (under review)</div><img src='images/udepth.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	Yu, Boxiao, `Wu, Jiayi`, Islam, Md Jahidul. UDepth: Fast Monocular Depth Estimation for Visually-guided Underwater Robots. *ICRA*. 2023, 10.48550/ARXIV.2209.12358  
[[arXiv]](https://arxiv.org/abs/2209.12358) [[Code]](https://github.com/uf-robopi/UDepth) [[pre-print]](/pdf/2209.12358.pdf)

</div>
</div>

# 📃 Projects 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">A Collaborative Project</div><img src='images/Depth_estimation_project.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

### UDepth
- A monocular underwater depth estimation pipeline, using RMI as the input space, constructs a lightweight domain projection module, a lightweight CNN feature extraction module, and a lightweight Transformer-based depth estimation network. And the depth estimation network is supervised with knowledge of underwater light attenuation as a prior. The results show that our depth estimation accuracy is close to the SOTA model, and much faster than them.  
This is a collaborative project on underwater depth estimation with Boxiao Yu, a Ph.D. student in RoboPI lab.  
[[arXiv]](https://arxiv.org/abs/2209.12358) [[Code]](https://github.com/uf-robopi/UDepth) [[pre-print]](/pdf/2209.12358.pdf)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Master's Thesis</div><img src='images/FU-SfM_project.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

### FU-SfM
- A fast underwater 3D reconstruction pipeline without a deep learning model. Underwater image restoration is implemented through RMI channel and underwater imaging model to improve the number of feature matches. Reduce the computational complexity of feature extraction by using the depth map as a mask. The depth map is used as the supervision to refine the 3D point cloud and remove noise. To achieves higher quality underwater 3D reconstruction.  
This project is my master's thesis, the overall framework has been determined, and some subsystems have obtained good results. It is expected that the project will be completed and submitted to IROS in Spring 2023.  

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">R&D Internship Project</div><img src='images/FU-SfM_project.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

### Learning-based Infringing Video Retrieval
- An learning-based infringing video retrieval system based on the fusion of global features and local features. I did a summer internship in the Vobile’s R&D department under the supervision of Dr. Zhao, CTO of Vobile. I built a learning-based infringing video retrieval system based on the fusion of global features and local features. I used Vobile's video database to train the model, and achieved good performance. Before I ended my internship, I put it together into a python package and organize each component in the system into an easy-to-use python toolkit. I also wrote the manual of the package and a document about future optimization steps to finally handed over to the person who took over the project.  

</div>
</div>

### Chinese
---

-	`Jian Tang`, Rongbiao Wang, Yihua Kang. Magnetic flux leakage nondestructive testing with large lift-off. *Nondestructive Testing*. 2022,44(4): 67.  
唐健, 王荣彪, 康宜华. 大提离漏磁无损检测方法. *无损检测*. 2022,44(4): 67.  
[[HTML]](https://dx.doi.org/10.11973/wsjc202204000) [[Preview]](https://github.com/tangjyan/tangjyan.github.io/blob/main/pdf/%E5%94%90%E5%81%A5-2022-%E5%A4%A7%E6%8F%90%E7%A6%BB%E6%BC%8F%E7%A3%81%E6%97%A0%E6%8D%9F%E6%A3%80%E6%B5%8B%E6%96%B9%E6%B3%95.pdf) [[PDF]](/pdf/%E5%94%90%E5%81%A5-2022-%E5%A4%A7%E6%8F%90%E7%A6%BB%E6%BC%8F%E7%A3%81%E6%97%A0%E6%8D%9F%E6%A3%80%E6%B5%8B%E6%96%B9%E6%B3%95.pdf)  


# 🏅 Honors and Awards
- *2015.11*  Win the `1st Prize` in the 14th "Challenge Cup" National Undergraduate Curricular Academic Science and Technology Works Competition.
- *2015.06* Win the `1st Prize` in the 13rd  "Challenge Cup" Sichuan Undergraduate Curricular Academic Science and Technology Works Competition. [[Newsreport]](https://www.sc.gov.cn/10462/10778/10876/2015/7/1/10341562.shtml)
- *2014.12* Win the `1st Prize` in the 4th National Undergraduate Engineering Training Integration Ability Competition (Sichuan Division).

# 💬 Conferences

- *2021.10*, National Seminar on Electromagnetic Nondestructive Testing Technology and the 14th Plenary Session of the 11th Session of the Electromagnetic Professional Technology Conference of China, Xian China, Oral.
- *2019.09*, The 19th International Symposium on Applied Electromagnetics and Mechanics (ISEM 2019), Nanjing China, Poster.
- *2017.10*, The 6th China International Pipeline Conference (CIPC 2017), Langfang China, Visit.


# 🏭 Internships
- *2018.05 - 2020.02*, Chongqing Changjiang Bearing Co., Ltd., Chongqing China.
- *2020.11.25 - 2020.12.02*, Hubei Xinyegang Steel Ltd., Huangshi China.
- *2017.6 - 2021.1*, Wuhan Huayu-M Testing Equipment Co., Ltd., Wuhan China.
  

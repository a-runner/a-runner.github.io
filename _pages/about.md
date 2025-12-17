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

I am Jiawang Liu, a Ph.D. candidate at the College of Information Science and Electronic Engineering, Zhejiang University (2022–present), under the supervision of Prof. [Lu Yu](https://person.zju.edu.cn/yul). I received my B.Eng. in Information Engineering from Jilin University.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISCAS 2025</div><img src='images/ISCAS_2025_v2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Assessing the Reusability of Cloud-Received Feature Streams on Advanced Networks](https://ieeexplore.ieee.org/document/11044016/) [poster]

**Jiawang Liu**, Ao Liu, Hualong Yu, Heming Sun,Lu Yu

IEEE ISCAS, 2025

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISCAS 2025</div><img src='images/ISCAS_2025_v1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Learning-based Image Coding for Machine Intelligence with Variable-Rate](https://ieeexplore.ieee.org/document/11043320/) [**oral**]

Ao Liu, Hualong Yu, **Jiawang Liu**, Qiqi He, Lu Yu

IEEE ISCAS, 2025

</div>
</div>



<div class='paper-box' id="VCIP_2023"><div class='paper-box-image'><div><div class="badge">VCIP 2023</div><img src='images/VCIP_2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Evaluation on the generalization of coded features across neural networks of different tasks](https://ieeexplore.ieee.org/document/10402702/) [**oral**]

**Jiawang Liu**, Ao Liu, Ke Jia, Hualong Yu, Lu Yu

IEEE VCIP, 2023 \| Relevant work has been adopted by <a href="#VCIP_2023_DCM">DCM</a>.

</div>
</div>



# 📄 Proposals

## 📋 Summary

* Chinese National Standard (DCM): **13** proposals submitted (<span style="color:red;">12</span> as first author, <span style="color:red;">3</span> adopted, <span style="color:red;">1</span> collaborative work adopted)
* International Standards (VCM, FCM): **15** proposals submitted (<span style="color:red;">6</span> as first author, <span style="color:red;">1</span> adopted by FCM)

<!-- ---- -->

## <img src="images/esi.jpg" width="20"> Data Coding for Machine (DCM)
---


### ✅ Adopted Proposals

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">DCM 2025</div><img src='images/Infrared_visualization.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<span style="color: #224B8D;">EE3：DCM在二维可见光红外视频数据集上的压缩性能探究</span>

**刘佳旺**、于化龙、虞露（浙江大学）、林晓东（芯福科技）

DCM-I-0170, DCM第19次会议，2025年7月

**Pre- and Post-processing Modules Adapted for Thermal Images** have been adopted.

[Project Page]()
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">DCM 2025</div><img src='images/overall.drawio.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<span style="color: #224B8D;">DCM定点化算法改进及相应标准文本修改建议</span>

**刘佳旺**、于化龙、虞露

DCM-I-162, DCM第18次会议，2025年4月

**Fixed-point Algorithm** has been adopted.

</div>
</div>


<div class='paper-box' id="VCIP_2023_DCM"><div class='paper-box-image'><div><div class="badge">DCM 2023</div><img src='images/decoupled_context.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<span style="color: #224B8D;">解析解码分离的高效图像编码方法</span>

何淇淇、**刘佳旺**、于化龙、虞露

DCM-I-0116， DCM第13次会议，2023年11月

**Decoupled Context Model** has been adopted.

</div>
</div>


<div class='paper-box' id="VCIP_2023_DCM"><div class='paper-box-image'><div><div class="badge">DCM 2023</div><img src='images/VCIP_2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<span style="color: #224B8D;">DTM-V CE2：验证解码特征的通用性</span>

**刘佳旺**、于化龙、虞露

DCM-I-0077,  DCM第10次会议，2023年2月

**Feature Adapter** has been adopted. \| Relevant work has been accepted by <a href="#VCIP_2023">VCIP 2023</a>.

</div>
</div>




### 📝 Other Selected Proposals

<!-- <div class="scroll-list-container"> -->

* **刘佳旺**、于化龙、虞露, “DTM-V CE2补充实验：验证解码特征在实例分割任务上的泛化性”，DCM-I-0086， DCM第11次会议，2023年5月。
* **刘佳旺**、于化龙、虞露, “DCM-I-147-DTM特征在基于Trasnformer的目标检测网络上的泛化性验证”, DCM-I-147, DCM第16次会议，2024年9月。
* **刘佳旺**、于化龙、虞露, “DCM-I-163-DCM参考软件在开发板上的部署展示”, DCM-I-163, DCM第18次会议，2025年4月。
* **刘佳旺**，“DCM-O-0089-TSUCA 024.2《信息技术面向机器智能图像编码第2版：草案》团标修订版草案”，DCM-O-0089, DCM第18次会议，2025年4月。

<!-- </div> -->



## <img src="images/mpeg.drawio.png" width="80"> MPEG-Video/Feature Coding for Machine (VCM/FCM)
---

### ✅ Adopted Proposals
<div class='paper-box' id="VCIP_2023_DCM"><div class='paper-box-image'><div><div class="badge">FCM 2024</div><img src='images/symmetrioc_flipping.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<span style="color: #224B8D;">Jiawang Liu, Ao Liu, Chao Wang, Hualong Yu, Lu Yu (Zhejiang University)], "[FCVCM] Feature Coding scheme for Video Coding for Machine from Zhejiang University", ISO/IEC JTC 1/SC 29/WG2  m65221, Hannover, October, 2023.</span>

**Jiawang Liu**, Ao Liu, Chao Wang, Hualong Yu, Lu Yu

**Symmetric Feature Channel Flipping** has been adopted by FCM (FCTM V2) in 2024.

(I originally proposed the technique, while the relevant CE was done by my classmates.)

</div>
</div>


### 📝 Other Selected Proposals
<!-- <div class="scroll-list-container"> -->

* **Jiawang Liu**, Hualong Yu, Lu Yu (ZJU), "[FCM] Suggestions on keeping alignment between FCM requirements and FCM CTTC", ISO/IEC JTC 1/SC 29/WG4  m66509, OnLine, January 2024.
* **Jiawang Liu**, Ao Liu, Kejia, Hualong Yu, Lu Yu (Zhejiang University), "[FCVCM] Analysis on Feature Generalization for Multi-tasks", ISO/IEC JTC 1/SC 29/WG2  m65225, Hannover, October, 2023.
* **Jiawang Liu**, Ao Liu, Chao Wang, Hualong Yu, Lu Yu (Zhejiang University)], "[FCVCM] Feature Coding scheme for Video Coding for Machine from Zhejiang University", ISO/IEC JTC 1/SC 29/WG2  m65221, Hannover, October, 2023.
* **Jiawang Liu**, Ao Liu, [Hualong Yu](mailto:hlyu@zju.edu.cn), Lu Yu, "[VCM] Dealing with non-monotonic distributed R-D points",  ISO/IEC JTC 1/SC 29/WG4 m64389, Geneva, July 2023.

<!-- </div> -->

# Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">DCM 2025</div><img src='images/system_deploy2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<span style="color: #224B8D;">Distributed System Deployment of Machine-Intelligence-Oriented Codecs</span>

**Jiawang Liu**, Ao Liu, Hualong Yu, Lu Yu


[Project Page]()

</div>
</div>


<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2022.09 - now*, Ph.D. in Information and Communication Engineering, College of Information Science and Electronic Engineering, <img src="images/zju_logo.png" width="60"> Zhejiang University.
- *2018.09 - 2022.06*, B.Eng. in Information Engineering, <img src="images/jlu_logo.jpg" width="35"> Jilin University.


<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
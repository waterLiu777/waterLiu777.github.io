---
permalink: /
title: "Qiguang Chen (陈麒光)"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
    .navA{
      display: inline-block;
      margin-right: 13px;
      font-size: 16px;
      font-weight: 700;
      color: #000;
      text-decoration: none;
      padding: 5px ;
      text-decoration-line: none;
      border: #000 1px solid;
    }
    .navA:hover{
      color: #fff;
      text-decoration-line: none;
      background-color: #000;
    }
    td {
        border-style: none;
    	border-bottom: none;
    }
  </style>


![visitors](https://visitor-badge.glitch.me/badge?page_id=lightchen233.github.io&right_color=green)

Hello! I'm a fourth-year undergraduate of [Harbin Institute of Technology](http://www.hit.edu.cn/), majoring in Software Engineering, at [Computing Faculty](http://cs.hit.edu.cn/). My research interests includes Task-oriented Dialogue System, Contrastive Learning and Natural Language Processing.

Currently, I am a research intern at [Baidu NLP](https://nlp.baidu.com/homepage/index) , supervised by [Lijie Wang](https://scholar.google.com/citations?user=bMsGAi0AAAAJ) and [Dr. Jing Liu](https://scholar.google.com/citations?hl=zh-CN&user=_NtB74oAAAAJ). At the same time, I am also an associate master at [SCIR](http://ir.hit.edu.cn/) supervised by [Dr. Libo Qin](http://ir.hit.edu.cn/~lbqin/) and [Prof. Wanxiang Che](http://ir.hit.edu.cn/~car/).

Other than my work, I'm honored as the president of HIT Software Competition Club, and Deputy Secretary-General for MLNLP.

<a href="#news" class="navA">News</a> <a href="#publications" class="navA">Publications</a> <a href="#honors&awards" class="navA">Honors&Awards</a>

# News

- \[2022.10\] Fortunately, I win the CCF Excellent College Students  Price!  
- \[2022.10\] Lead by [Dr. Bo Zheng](https://scholar.google.com/citations?hl=zh-CN&user=PpYQpzoAAAAJ)  and [Prof. Wanxiang Che](http://ir.hit.edu.cn/~car/), our paper achieves achieve the **Best Paper** in EMNLP MMNLU2022 WorkShop.
- \[2022.09\] I formally join SCIR, HIT.
- \[2022.08\] Our follow-up work on inconsistency in task-oriented dialogue systems is accepted by COLING2022. Thanks for co-authors from HIT, HKU, BUAA, CUMC! More exciting, with the guidance of [Prof. Wanxiang Che](http://ir.hit.edu.cn/~car/), our team, lead by [Dr. Bo Zheng](https://scholar.google.com/citations?hl=zh-CN&user=PpYQpzoAAAAJ), win the first price in [MMNLU-22 Competition](https://mmnlu-22.github.io/Competition/).
- \[2022.05\] I join Baidu NLP, Baidu Inc.
- \[2022.04\] [Our work](https://arxiv.org/abs/2204.08325) on multi-lingual SLU is accepted by ACL 2022. Thanks for co-authors from HIT, MSRA and NUS!
- \[2021.09\] [Our work](https://arxiv.org/abs/2109.11292) on inconsistencies in Task-oriented Dialogue System is accepted by EMNLP 2021. Thanks for co-authors from HIT!

# Publications

<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;">
<tbody>
      <tr>
        <td style="padding:20px;width:25%;vertical-align:middle">
          <img src="images/cgim.jpg" alt="CGIM" width="160" height="140" style="border-style: none">
        </td>
        <td width="75%" valign="middle">
          <!-- <a href="http://www.personal.psu.edu/dux19/" id="3DSP"> -->
          <papertitle><b>CGIM: A Cycle Guided Interactive Learning Model for Consistency Identification in Task-oriented Dialogue</b></papertitle>
          <br>
          Libo Qin, <b>Qiguang Chen</b>, Tianbao Xie, Qian Liu, Shijue Huang, Wanxiang Che, Zhou Yu.
          <br>
          <em><b>[COLING 2022]</b></em> 
            <!-- <i>The 36th Conference on Neural Information Processing Systems</i> -->
          <br>
          <a href="https://aclanthology.org/2022.coling-1.37.pdf">PDF</a> / <a href="#">Code</a> / <a href="#">Supp</a> / <a href="#">Slides</a>
          <p> This work aims to solve CI-ToD task by introducing an explicit interaction paradigm, Cycle Guided Interactive learning Model (CGIM), which achieves to make information exchange explicitly from all the three tasks. </p>
        </td>
      </tr>
    <tr>
        <td style="padding:20px;width:25%;vertical-align:middle">
          <img src="images/glclef.jpg" alt="GLCLeF" width="160" height="140" style="border-style: none">
        </td>
        <td width="75%" valign="middle">
          <!-- <a href="http://www.personal.psu.edu/dux19/" id="3DSP"> -->
          <papertitle><b>GL-CLeF: A Global-Local Contrastive Learning Framework for Cross-lingual Spoken Language Understanding. </b></papertitle>
          <br>
          Libo Qin, <b>Qiguang Chen</b>, Tianbao Xie, Qixin Li, Jian-Guang Lou, Wanxiang Che, Min-Yen Kan.
          <br>
          <em><b>[ACL 2022]</b></em> 
            <!-- <i>The 36th Conference on Neural Information Processing Systems</i> -->
          <br>
          <a href="https://aclanthology.org/2022.acl-long.191.pdf">PDF</a> / <a href="#">Code</a> / <a href="#">Supp</a> / <a href="#">Slides</a>
          <p>We present Global-Local Contrastive Learning Framework (GL-CLeF) to address this shortcoming. Specifically, we employ contrastive learning, leveraging bilingual dictionaries to construct multilingual views of the same utterance, then encourage their representations to be more similar than negative example pairs, which achieves to explicitly align representations of similar sentences across languages. </p>
        </td>
      </tr>
    <tr>
        <td style="padding:20px;width:25%;vertical-align:middle">
          <img src="images/citod.jpg" alt="CIToD" width="160" height="140" style="border-style: none">
        </td>
        <td width="75%" valign="middle">
          <!-- <a href="http://www.personal.psu.edu/dux19/" id="3DSP"> -->
          <papertitle><b>Don't be Contradicted with Anything! CI-ToD: Towards Benchmarking Consistency for Task-oriented Dialogue System.</b></papertitle>
          <br>
          Libo Qin, Tianbao Xie, Shijue Huang, <b>Qiguang Chen</b>, Xiao Xu, Wanxiang Che.
          <br>
          <em><b>[EMNLP2021]</b></em> 
            <!-- <i>The 36th Conference on Neural Information Processing Systems</i> -->
          <br>
          <a href="https://aclanthology.org/2021.emnlp-main.182.pdf">PDF</a> / <a href="#">Code</a> / <a href="#">Supp</a> / <a href="#">Slides</a>
          <p>We introduce CI-ToD, a novel dataset for Consistency Identification in Task-oriented Dialog system. In addition, we not only annotate the single label to enable the model to judge whether the system response is contradictory, but also provide more fine-grained labels (i.e., Dialogue History Inconsistency, User Query Inconsistency and Knowledge Base Inconsistency) to encourage model to know what inconsistent sources lead to it.</p>
        </td>
      </tr>
    </tbody>
</table>

# Honors&Awards

- **Bachelor of Engineering (B.E.)**
	- CCF Excellent College Students  Price (Only 1% students in HIT CS were invited), 2022
	- National Second Prize in Contemporary Undergraduate Mathematical Contest in Modeling, China, 2021
	- Provincial Gold Award in "Challenge" Cup, 2022

# Patent Applications

- 预训练对偶注意力神经网络语义推断对话检索方法及系统、检索设备、存储介质。

	梁晨; **陈麒光**; 耿健; 唐亚锋; 辛宇鑫

	ZL 2021 1 0795247.7, 2022.09.09.

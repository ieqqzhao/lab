---
title: " Publications"
layout: gridlay
excerpt: "Publications."
sitemap: false
permalink: /publications/
---


# Publications

## Group highlights

(For a full list see [below](#full-list) or go to [Google Scholar](https://scholar.google.com/citations?user=7mZV_YsAAAAJ&hl=zh-TW))

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>


## Full List

Journal Publications
------
## Journal Publications

1. **Zhao, Q. Q.**, & Yun, W. Y. (2018). Determining the inspection intervals for one-shot systems with support equipment. **Reliability Engineering & System Safety**, 169, 63–75.

2. **Zhao, Q. Q.**, & Yun, W. Y. (2019). Storage availability of one-shot system under periodic inspection considering inspection error. **Reliability Engineering & System Safety**, 186, 120–133.

3. Yun, W. Y., Jeon, W., & **Zhao, Q. Q.** (2018). Spare parts provisioning under multi-echelon and multi-level systems. **Journal of Applied Reliability**, 18(4), 370–379.

4. Han, Y. J., **Zhao, Q. Q.**, & Yun, W. Y. (2019). Optimal inspection and replacement strategy of 145kV GIS. **Proceedings of the Institution of Mechanical Engineers, Part O: Journal of Risk and Reliability**.

5. **Zhao, Q. Q.**, & Yun, W. Y. (2020). A sampling plan for one-shot systems considering destructive inspection. **Journal of Communications in Statistics – Theory and Methods**.

6. Dui, H. Y., Zheng, X., **Zhao, Q. Q.**, & Fang, Y. (2021). Preventive maintenance of multiple components for hydraulic tension systems. **Eksploatacja i Niezawodnosc – Maintenance and Reliability**, 23(3), 489–497.

7. Shi, Y., Zhou, Y., Ye, W., & **Zhao, Q. Q.** (2020). A relative robust optimization for a vehicle routing problem with time-window and synchronized visits considering greenhouse gas emissions. **Journal of Cleaner Production**, 275, 124112.

8. Xu, C., Jing, Y., Shen, B., Zhou, Y., & **Zhao, Q. Q.** Cost-sharing contract design between manufacturer and dealership considering the customer low-carbon preferences. **Expert Systems with Applications**, 213(8), 118877.

9. 赵倩倩, 周艳杰. (2023). “生产系统建模与仿真”课程教学改革——基于CDIO标准教育教学论坛. **教育教学论坛**, (13), 46–50.

10. **Zhao, Q. Q.**, Yoo, J. Y., Dohi, T., & Yun, W. Y. (2024). Optimum maintenance units in multi-indenture systems. **Quality and Reliability Engineering International**, 40, 2792–2821.

11. 兑红炎, 宋佳颖, 赵倩倩, 王宁. (2024). 考虑两类错误的贮存系统两阶段检测模型和成本分析. **数理统计与管理**, 4(3), 656–666.

12. Ye, Z., Cai, Z., Yang, H., Si, S., & **Zhao, Q. Q.** Enhancing adaptive failure risk prognosis for cutting tools in heterogeneous working environments: A comprehensive modeling framework. **Expert Systems with Applications**, 280, 127527.

13. Zhou, Y., Luo, L., **Zhao, Q. Q.**, Chen, H., Qian, Z., & Leng, S. Influence index analysis of inland waterway ports along the Yangtze River. **European Journal of Industrial Engineering**, 20(2), 183–215.

14. **Zhao, Q. Q.**, Kim, J. W., Chung, I. H., & Yun, W. Y. (2026). Optimal redundancy allocation in multi-indenture systems considering human error-induced common cause failures. **Machines**, 14(6), 627, 1–14.


Conference Publications
------
1. **Q.Q. Zhao,** W. Jeon & W.Y. Yun. Spare part inventory problem for multi-indenture systems with two-echelon inventory system.  2019 International Conference on Quality, Reliability, Risk, Maintenance, and Safety Engineering (QR2MSE 2019), (QR2MSE 2019), Zhangjiajie, Hunan, China (Aug. 6 ~ 9, 2019). <font color="green"> Best Paper Award <font>
1. **Q.Q. Zhao,** Y.J. Han and W.Y. Yun. Optimal inspection and replacement strategy of 145kV GIS, The 3th international symposium on stochastic models in reliability engineering, life sciences and operations management (SMRLO 2019), Beijing, China (May. 28 ~ 31, 2019). 
1. **Q.Q. Zhao,** A.J. Endharta and W.Y. Yun. Inspection scheduling problem of one-shot systems with nondestructive and destructive inspections. The 3th International Symposium on Stochastic Models in Reliability Engineering, Life Sciences and Operations Management (SMRLO2019), Beijing, China (May. 28 ~ 31, 2019). 
1. **Q.Q. Zhao,** N.T.T. Mo and Won Young Yun. Simulation-based resilience analysis of mobile telecommunication network, 2019 Joint Workshop of Hiroshima University and Pusan National University (HU-PNU 2019), Hiroshima University, Japan (Jan. 18, 2019). 
1. W.Y. Yun, A.J. Endharta and **Q.Q. Zhao,** 2018. A maintenance model of circular k-out-ofn: G balanced systems, 5th East Asia Workshop on Industrial Engineering (EAWIE 2018), Seoul, South Korea (Nov. 8 ~ 9, 2018). 
1. W.Y. Yun, **Q.Q. Zhao,** An optimal inspection interval for a one-shot system, Reliability Engineering Association of Japan, Tokyo, Japan (Oct. 29, 2018). 
1. **Q.Q. Zhao,** A.J. Endharta and W.Y. Yun. A preventive maintenance scheduling problem with random interval time. 2018 Spring Conference of the Korean Institute of Industrial Engineers, Gyeongju, South Korea (Apr. 7, 2018). 
1.  **Q.Q. Zhao,** W.Y. Yun. Two-stage inspection policy for a one-shot system with two types of inspection errors. Proceedings of 2018 Asia-Pacific International Symposium on Advanced Reliability and Maintenance Modeling and 2018 international conference
on quality reliability, risk, maintenance, and safety engineering, Qingdao, China (Aug. 21 ~ 24, 2018). 
1. **Q.Q. Zhao,** W.Y. Yun. Storage availability with inspection error. Proceedings of the 4th East Asia Workshop on Industrial Engineering, Pacifica Yokohama, Japan (Nov. 2 ~ 3, 2017). 
1. Y.J. Han, H.B. Park, J.J. Kim, **Q.Q. Zhao,** H.A. Jang and W.Y. Yun. Simulation-based optimal replacement model for a PCS in the ESS under combination warranty policy, Proceeding of the Asia Pacific Industrial Engineering & Management Systems Conference, Taipei, Taiwan (Dec. 07 ~ 10, 2016) 
1. **Q.Q. Zhao,** D.K. Park, J.W. Kim, and W.Y. Yun. A case study on determining the reliability target value of railway vehicle service, 2015 Autumn Conference of the Applied Reliability, Seoul, South Korea (Nov. 20, 2015). 
1. **Q.Q. Zhao,** W.Y. Yun. Determining inspection intervals for one-shot systems with support equipment, Proceedings of the 2nd East Asia Workshop on Industrial Engineering, Yonsei University, Korea (Nov. 6 ~ 7, 2015). 
1. **Q.Q. Zhao,** H.W. Kim and W.Y. Yun. Optimal inspection schedules for one-shot systems in storage with deployment plan, Proceedings of the 6th Asia-Pacific International Symposium on Advanced Reliability and Maintenance Modeling, Sapporo, Japan (Aug. 21 ~ 23, 2014). 

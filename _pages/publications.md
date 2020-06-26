---
title: "CIEG - Publications"
layout: gridlay
excerpt: "CIEG -- Publications."
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

1. **Zhou, Y.**, & Kim, K. H. (2020). Optimal parameters in concession contracts between container terminal operators and investors. **International Journal of Logistics Research and Applications.** **[PDF]( https://ieyjzhou.github.io/files/IJLRA2020.pdf)**
1. **Zhou, Y.**, & Kim, K. H. (2020). A game theoretic model and a coevolutionary solution procedure to determine the terminal handling charges for container terminals. **Computer & Industrial Engineering**, 144, 106466 **[PDF](https://ieyjzhou.github.io/files/CIE2020_coevolutionary.pdf)**
1. **Zhou, Y.**, & Kim, K. H. (2019). Optimal concession contract between a port authority and container-terminal operators by revenue-sharing schemes with quantity discount. **Maritime Policy & Management.** **[PDF](https://ieyjzhou.github.io/files/online_version%20with_SP.pdf)** Supplemental material [PDF](https://ieyjzhou.github.io/files/Supplemental_Material_MPM_2019.pdf).
1. Gu, J., **Zhou, Y.**, Das, A., Moon, I., & Lee, G. M. (2018). Medical relief shelter location problem with patient severity
under a limited relief budget. **Computers & Industrial Engineering**, 125, 720–728. **[PDF](https://ieyjzhou.github.io/CIEG/Paper/CIE2018_correct_proof_version.pdf)**
1. **Zhou, Y.**, & Lee, G. M. (2018). Linking soft computing to art: Introduction of efficient k-continuous line drawing. **Applied Soft Computing**, 68, 932–943. **[PDF](https://ieyjzhou.github.io/CIEG/Paper/KCLD_2018_Published_Version.pdf)**
1. Gao, X., **Zhou, Y.**, Amir, M. I. H., Rosyidah, F. A., & Lee, G. M. (2017). A hybrid genetic algorithm for multi-emergency
medical service centers location-allocation problem in disaster response. **International Journal of Industrial Engineering:
Theory, Applications and Practice**, 24(6), 663–679. **[PDF](https://ieyjzhou.github.io/CIEG/Paper/IJIE%202017.pdf)**
1. Gao, Y., **Zhou, Y.**, Zhou, B., Shi, L., & Zhang, J. (2017). Handling data skew in mapreduce cluster by using partition tuning. **Journal of Healthcare Engineering**, 2017. **[PDF](https://ieyjzhou.github.io/CIEG/Paper/JHE2017.pdf)**
1. **Zhou, Y.**, & Lee, G. M. (2017). A lagrangian relaxation-based solution method for a green vehicle routing problem to
minimize greenhouse gas emissions. **Sustainability**, 9(5), 776 **[PDF](https://ieyjzhou.github.io/CIEG/Paper/sustainability-09-00776.pdf)**

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

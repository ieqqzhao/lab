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
1. **Q.Q. Zhao,**, W. Jeon & W.Y. Yun. (2019). Spare part inventory problem for multi-indenture systems with two-echelon inventory system.  2019 International Conference on Quality, Reliability, Risk, Maintenance, and Safety Engineering (QR2MSE 2019), (QR2MSE 2019), Zhangjiajie, Hunan, China (Aug. 6 ~ 9, 2019)  <font color="red"> Best Paper Award <font>
1. **Zhou, Y.**, & Kim, K. H. (2019). A note on optimizing the concession contracts for landlord port authorities to max-
imise fee revenues. In The 4 th international conference of supply chain and technology innovation (ICOSTI 2019). (August
13-15, 2019, Busan, Korea.)
1. **Zhou, Y.**, & Kim, K. H. (2019). Competition and collaboration among express delivery companies. In The 9th international conference on logistics and maritime systems (LOGMS 2019). (August 14-16, 2019, Singapore, Singapore.)
1. **Zhou, Y.**, & Kim, K. H. (2019). Optimal rental charge schedule between the port authority and container terminals
under various contract schemes. In The 27th annual conference of the international association of maritime economists
2019 (IAME 2019 ). (June 25-28, 2019, Athens, Greece.)
1. **Zhou, Y.**, & Kim, K. H. (2019). Terminal location and sharing problem in a competitive environment. In The 4th belt
and road initiative conference 2019(BRI 2019). (August 1-3, 2019, Bangkok, Thailand.)
1. Gao, Y., Zhou, B., **Zhou, Y.**, Shi, L., Tao, Y., & Zhang, J. (2018). Transfer learning-based behavioural task decoding from
brain activity. In The international conference on healthcare science and engineering (pp. 71–81). Springer. doi:10.1007/
978-981-13-6837-0_6. (June 1-3, 2018, Guangxi, China.)
1. **Zhou, Y.**, Choi, S.-H., & Kim, K. H. (2018). Determining rental charges by a port authority considering container han-
dling prices by terminals. In The 19th asia pacific industrial engineering and management systems (APIEMS 2018). (December 5-8, 2018, Hong Kong, China.)
1. **Zhou, Y.**, & Kim, K. H. (2018). Optimal concession contract between the port authority and container terminals by a
royalty fee scheme. In The 8th international conference on logistics and maritime systems (LOGMS 2018). (December 9-12,
2018, Guangzhou, China.)
1. **Zhou, Y.**, Kim, K. H., & Kim, J. G. (2018). A coevolutionary approach to pricing container handles by container termi-
nals. In The seventh international conference on transportation and logistics (7th T-LOG). (September 8-10, 2018, Dalian,
China.)
1. **Zhou, Y.**, & Lee, G. M. (2018). A robust mathematical model for capacity planning in semiconductor industry under
demand uncertainty. In 2018 ieee international conference on smart manufacturing, industrial & logistics engineering.
(February 7-9, 2018, Hsinchu, Taiwan.)
1. Tuladhar, U. M., **Zhou, Y.**, Lee, G. M., & Ahn, S. (2017). Design and implementation of segmentation algorithm for artistic drawing using 2-axis computer numerical controller. In The 7th international conference on manufacturing, machine
design and tribology. (April 19-22, 2017, Jeju, Korea.)
1. **Zhou, Y.**, Das, A., Gao, X., & Lee, G. M. (2017). A biobjective mathematical programming for medical relief shelter lo-
cation problem. In The second global conference on theory and applications of or & om for sustainability. (September 6-8,
2017, Beijing, China.) <font color="red">Best Paper Award<font>
1. Gu, J., **Zhou, Y.**, & Lee, G. M. (2016). Medical relief shelter location considering the severity of patients under limited
relief budget. In The 46th international conference on computers & industrial engineering. (October 29-31, 2016, Tianjin,
China.) <font color="red">Best Student Paper Award<font> 
1. **Zhou, Y.**, & Lee, G. M. (2016). Linking the optimization to the art; an efficient k-continuous line drawing using image
segmentation, stippling, and the traveling salesman problem. In The 2016 international symposium on semiconductor
manufacturing intelligence. (August 7-10, 2016, Hsinchu, Taiwan.)
1. Zhou, B., **Zhou, Y.**, Xu, M., & Wu, F. (2014). Computation-aware motion estimation algorithm based on qoe control. In
2014 ieee computers communications and it applications conference (pp. 261–265). IEEE. doi:10.1109/ComComAp.2014.7017207. (October 20-22, 2014, Beijing, China.)

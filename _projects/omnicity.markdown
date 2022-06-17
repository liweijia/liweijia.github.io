---
layout: page
title: OmniCity
description: Omnipotent City Understanding with Multi-level and Multi-view Images
img: /assets/img/omnicity-icon.png
importance: 3
---




<center>
<td colspan="5" id="authors">
<a href="http://liweijia.github.io">Weijia Li</a><sup>1,3</sup> &nbsp;&nbsp;&nbsp;
<a href="https://liweijia.github.io/projects/omnicity/">Yawen Lai</a><sup>2,4</sup> &nbsp;&nbsp;&nbsp;
<a href="https://eveneveno.github.io/lnxu/">Linning Xu</a><sup>3</sup> &nbsp;&nbsp;&nbsp;
<a href="https://liweijia.github.io/projects/omnicity/">Yuanbo Xiangli</a><sup>3</sup> &nbsp;&nbsp;&nbsp;
<a href="https://liweijia.github.io/projects/omnicity/">Conghui He</a><sup>4</sup> &nbsp;&nbsp;&nbsp;
<a href="http://www.captain-whu.com/xia_En.html">Gui-song Xia</a><sup>5</sup> &nbsp;&nbsp;&nbsp;
<a href="https://dahua.site">Dahua Lin</a><sup>3,6</sup> &nbsp;&nbsp;&nbsp;
</td>
</center>

<center>
<td colspan="5" id="affiliation">
<sup>1</sup>Sun Yat-sen University &nbsp;
<sup>2</sup>Peking University &nbsp;
<sup>3</sup>The Chinese University of Hong Kong &nbsp;
<sup>4</sup>Sensetime Research &nbsp;
<sup>5</sup>Wuhan University &nbsp;
<sup>6</sup>Shanghai AI Laboratory

</td>
</center>



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/omnicity-teasor.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>

<div class="caption">

</div>

<p style="text-align:justify; text-justify:inter-ideograph;">
In this work, we introduce OmniCity, a novel benchmark for omnipotent city understanding with multi-level and multi-view images. OmniCity contains multi-view satellite images as well as street-level panorama and mono-view images, which are well aligned and collected from 25,000 viewpoint geo-locations in New York City. To reduce the human annotation efforts, we propose an efficient annotation pipeline for labeling the street-view panorama images at pixel level, via leveraging the existing label maps of satellite view and the transformation rules between different views (satellite, panorama, and mono-view). Based on our OmniCity dataset, we conduct baseline experiments for a variety of tasks on satellite and street-level images, including building footprint extraction, height estimation, and building plane / instance / land use segmentation. We also analyze the impact of view on each task, the performance of different models, limitations of existing methods, etc. Compared with the existing multi-view and multi-level benchmarks, our OmniCity provides richer annotation types for street-level images and more baseline results obtained from state-of-the-art models, and introduces a novel task for land use segmentation of building instances on street-level panorama images. Moreover, OmniCity provides new problem settings to promote novel methods for existing tasks, such as cross-view image matching, synthesis, segmentation, detection, etc., and facilitates novel tasks and methods for large-scale city understanding, reconstruction, and simulation. OmniCity will be released soon.</p>

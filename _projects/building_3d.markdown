---
layout: page
title: 3D Building Reconstruction
description: 3D Building Model Reconstruction from Monocular Remote Sensing Images
img: /assets/img/building3d.jpg
importance: 1
---




<center>
<td colspan="5" id="authors">
<a href="http://liweijia.github.io">Weijia Li</a><sup>1,2</sup> &nbsp;&nbsp;&nbsp;
<a href="https://liweijia.github.io/projects/building_polyseg/">Lingxuan Meng</a><sup>2,3</sup> &nbsp;&nbsp;&nbsp;
<a href="https://liweijia.github.io/projects/building_polyseg/">Jinwang Wang</a><sup>2,4</sup> &nbsp;&nbsp;&nbsp;
<a href="https://conghui.github.io/">Conghui He</a><sup>2</sup> &nbsp;&nbsp;&nbsp;
<a href="https://dahua.me">Dahua Lin</a><sup>1,2</sup> &nbsp;&nbsp;&nbsp;
</td>
</center>

<center>
<td colspan="5" id="affiliation">
<sup>1</sup>The Chinese University of Hong Kong &nbsp;
<sup>2</sup>Sensetime Group Limited &nbsp;
<sup>3</sup>University of Electronic Science and Technology of China &nbsp;
<sup>4</sup>Wuhan University

</td>
</center>



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/building3d-teasor.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>

<div class="caption">

</div>

<p style="text-align:justify; text-justify:inter-ideograph;">
3D building reconstruction from monocular remote sensing imagery is an important research problem and an economic solution to large-scale city modeling, compared with reconstruction from LiDAR data and multi-view imagery. However, several challenges such as the partial invisibility of building footprints and facades, the serious shadow effect, and the extreme variance of building height in large-scale areas, have restricted the existing monocular image based building reconstruction studies to certain application scenes, i.e., modeling simple low-rise buildings from near-nadir images. In this study, we propose a novel 3D building reconstruction method for monocular remote sensing images, which not only solves the above challenges but is applicable to complicated scenarios. We design a multi-task neural network to learn the intrinsic property of oblique images, the key components of a 3D building model and their relations via five relevant tasks, i.e., roof and facade segmentation, visible skeleton segmentation, image-wise offset angle prediction, pixel-wise offset field prediction, and skeleton orientation prediction. The five types of outputs are further integrated to produce the the final vectorized 3D building models. Results on a novel public dataset demonstrate that our proposed method improves the footprint extraction F1-score by 3.2% to 13.4%, and reduces the height estimation endpoint errors of high-rise buildings by over 10% compared with current state-of-the-art.
</p>

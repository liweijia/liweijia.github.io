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
<a href="https://liweijia.github.io/projects/omnicity/">Jinhua Yu</a><sup>1</sup> &nbsp;&nbsp;&nbsp;
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
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/omnicity-teasor.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>

<div class="caption">

</div>

<br>
<center><h2><a id="downloads">Abstract</a></h2></center>


<p style="text-align:justify; text-justify:inter-ideograph;">

This paper presents OmniCity, a new dataset for omnipotent city understanding from multi-level and multi-view images. More precisely, the OmniCity contains multi-view satellite images as well as street-level panorama and mono-view images, constituting over 100K pixel-wise annotated images that are well-aligned and collected from 25K geo-locations in New York City. To alleviate the substantial pixel-wise annotation efforts, we propose an efficient street-view image annotation pipeline that leverages the existing label maps of satellite view and the transformation relations between different views (satellite, panorama, and mono-view).  
With the new OmniCity dataset, we provide benchmarks for a variety of tasks including building footprint extraction, height estimation, and building plane/instance/fine-grained segmentation. We also analyze the impact of view on each task, the performance of different models, limitations of existing methods, etc. Compared with the existing multi-level and multi-view benchmarks, our OmniCity contains a larger number of images with richer annotation types and more views, provides more baseline results obtained from state-of-the-art models, and introduces a novel task for fine-grained building instance segmentation on street-level panorama images. Moreover, OmniCity provides new problem settings for existing tasks, such as cross-view image matching, synthesis, segmentation, detection, etc., and facilitates the developing of new methods for large-scale city understanding, reconstruction, and simulation. The OmniCity dataset as well as the benchmarks will be released soon.</p>



<br>
<center><h2><a id="downloads">Comparison with Current Benchmarks</a></h2></center>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/omnicity-table.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>

<div class="caption">

</div>

<p style="text-align:justify; text-justify:inter-ideograph;">


A comparison of our proposed dataset and existing city-related datasets. The # Images column represents the number of annotated images. The street view column shows whether the dataset contains no / mono-view (mono) / panorama (pano) street-level images. The satellite view column shows whether the dataset contains no / single / multiple satellite images. The annotation level column indicates which level of tasks the dataset is designed for, i.e., semantic segmentation, object detection (bbox), instance segmentation, plane segmentation, and image classification. The last two columns indicate whether the dataset contains fine-grained land use or height labels. Compared with the existing benchmarks, our OmniCity contains a larger number of images, more types of views, and richer annotation types at a finer annotation level.</p>


<br>
<center><h2><a id="downloads">The Proposed Annotation Tool</a></h2></center>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/omnicity-gui.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>

<div class="caption">

</div>

<p style="text-align:justify; text-justify:inter-ideograph;">

The annotator is first required to drag the floor line to fit the bottom boundary of all buildings. Next, the annotator needs to add the split line and adjust the top line to fit the roof boundary for each building plane. In the bottom-right sub-window, we provide auxiliary information indicating the approximate locations of the split lines, which is generated by transforming the building footprint split lines in the satellite view to panorama view using a geo-transformation method. The annotators should consider both auxiliary information and building appearance (e.g. texture discrepancy, doors, etc.) to decide the accurate location of each split line. During the attribute assignment stage, the annotator needs to add the attributes (instance ID, block-lot id and land use type) for each building plane labeled in the previous stage, which are demonstrated in the bottom-middle sub-window. The building planes that belong to the same building instance will be set as the same instance ID (in the crossroads scene); Otherwise, the plane will be set as a specific instance ID successively. When a building instance is selected by the annotator (the yellow one in the panorama image), the surrounding auxiliary lines of its corresponding footprint in the bottom-right sub-window will turn red. Then the annotators assign the lot-block id and the land use type according to the numbers shown in the bottom-right sub-window, which can be switched between the land use mode and the block-lot mode. </p>


<br>
<center><h2><a id="downloads">Example Results</a></h2></center>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/omnicity-results.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>

<div class="caption">







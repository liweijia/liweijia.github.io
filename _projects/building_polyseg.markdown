---
layout: page
title: Polygonal Building Segmentation
description: Joint Semantic-Geometric Learning for Polygonal Building Segmentation
img: /assets/img/buildingseg.jpg
importance: 2
---

<center><b>AAAI Conference on Artificial Intelligence (AAAI), 2021</b></center>


<center>
<td colspan="5" id="authors">
<a href="http://liweijia.github.io">Weijia Li</a><sup>1,2</sup> &nbsp;&nbsp;&nbsp;
<a href="https://liweijia.github.io/projects/building_polyseg/">Wenqian Zhao</a><sup>1</sup> &nbsp;&nbsp;&nbsp;
<a href="https://liweijia.github.io/projects/building_polyseg/">Huaping Zhong</a><sup>2</sup> &nbsp;&nbsp;&nbsp;
<a href="https://conghui.github.io/">Conghui He</a><sup>2</sup> &nbsp;&nbsp;&nbsp;
<a href="https://dahua.me">Dahua Lin</a><sup>1,2</sup> &nbsp;&nbsp;&nbsp;
</td>
</center>

<center>
<td colspan="5" id="affiliation">
<sup>1</sup>The Chinese University of Hong Kong &nbsp;
<sup>2</sup>Sensetime Group Limited
</td>
</center>



<br>



<table align=center width=720px>
			<tr>
				<table align=center width=720px>
					<tr>
						<td align=center width=720px>
							<iframe width="720" height="405" src="https://www.youtube.com/embed/Kcnr22Wy02w" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
						</td>
					  </tr>
					<tr>
						<td align=center width=720px>
						   </td>
					  </tr>
					 </table>
			  </tr>
		  </table>


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The video presentation at AAAI 2021 conference. You can alternatively watch it on [bilibili](https://www.bilibili.com/video/BV1Br4y1P7bh?pop_share=1).




<center><h2><a id="Abstract">Abstract</a></h2></center>

<p style="text-align:justify; text-justify:inter-ideograph;">
Building extraction from aerial or satellite images has been an important research issue in remote sensing and computer vision domains for decades. Compared with pixel-wise semantic segmentation models that output raster building segmentation map, polygonal building segmentation approaches produce more realistic building polygons that are in the desirable vector format for practical applications. Despite the substantial efforts over recent years, state-of-the-art polygonal building segmentation methods still suffer from several limitations, e.g., (1) relying on a perfect segmentation map to guarantee the vectorization quality; (2) requiring a complex post-processing procedure; (3) generating inaccurate vertices with a fixed quantity, a wrong sequential order, inter-sections, etc. To tackle the above issues, in this paper, we propose a polygonal building segmentation approach and make the following contributions: (1) We design a multi-task segmentation network for joint semantic and geometric learning via three tasks, i.e., pixel-wise building segmentation, multi-class corner prediction, and edge orientation prediction. (2) We propose a simple but effective vertex generation module for transforming the segmentation contour into high-quality polygon vertices. (3) We further propose a polygon refinement network that automatically moves the polygon vertices into more accurate locations. Results on two popular building segmentation datasets demonstrate that our approach achieves significant improvements for both building instance segmentation (with 2% F1-score gain) and polygon vertex prediction (with 6% F1-score gain) compared with current state-of-the-art methods.
</p>



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/buildingseg-teasor.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>

<div class="caption">
Examples of polygonal building segmentation results of our method. Our method produces vectorized building polygons with accurate vertices and edges, even for buildings with complex shapes.
</div>


<br>


<center><h2><a id="downloads">Downloads</a></h2></center>
<br>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
	 <center>
	  <a href="/assets/pdf/AAAI-21-paper.pdf"><img class="rounded" onmouseover="this.src='/assets/img/icon_paper.png';" onmouseout="this.src='/assets/img/icon_paper.png';" src = "/assets/img/icon_paper.png" height = "150px"></a><br>
	  <span style="font-size:16px">Paper</span><br>
    </center>
    </div>
    <div class="col-sm mt-3 mt-md-0">
	 <center>
	  <a href="/assets/pdf/AAAI-21-slides-20min.pdf"><img class="rounded" onmouseover="this.src='/assets/img/icon_slide.png';" onmouseout="this.src='/assets/img/icon_slide.png';" src = "/assets/img/icon_slide.png" height = "150px"></a><br>
	  <span style="font-size:16px">Slides</span><br>
    </center>
    </div>
    <div class="col-sm mt-3 mt-md-0">
	 <center>
	  <a href="https://www.youtube.com/watch?v=Kcnr22Wy02w&ab_channel=WeijiaLi"><img class="rounded" onmouseover="this.src='/assets/img/icon_video.png';" onmouseout="this.src='/assets/img/icon_video.png';" src = "/assets/img/icon_video.png" height = "150px"></a><br>
	  <span style="font-size:16px">Video</span><br>
    </center>
    </div>
</div>





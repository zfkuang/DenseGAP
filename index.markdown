---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

## **Abstract**
Establishing dense correspondence between two images is a fundamental computer vision problem, which is typically tackled by matching local feature descriptors. However, without global awareness, such local features are often insufficient for disambiguating similar regions. And computing the pairwise feature correlation across images is both computation-expensive and memory-intensive. To make the local features aware of the global context and improve their matching accuracy, we introduce *DenseGAP*, a new solution for efficient *Dense* correspondence learning with a *G*raph-structured neural network conditioned on *A*nchor *P*oints. Specifically, we first propose a graph structure that utilizes *anchor points* to provide sparse but reliable prior on inter- and intra-image context and propagates them to all image points via directed edges. We also design a graph-structured network to broadcast multi-level contexts via light-weighted message-passing layers and generate high-resolution feature maps at low memory cost. Finally, based on the predicted feature maps, we introduce a coarse-to-fine framework for accurate correspondence prediction using cycle consistency. Our feature descriptors capture both local and global information, thus enabling a continuous feature field for querying arbitrary points at high resolution. Through comprehensive ablative experiments and evaluations on large-scale indoor and outdoor datasets, we demonstrate that our method advances the state-of-the-art of correspondence learning on most benchmarks.


## **Architecture**
<center><img src="/figures/concept.png" width="1152"></center>
<center><img src="/figures/structure.png" width="1152"></center>

## **Application 1:** Sparse Correspondence.
<center><img src="/figures/app_anime_style_transfer.jpg" width="1152" >
<figcaption>The left column shows four input examples of two different
artists.</figcaption></center>

## **Application 2:** Dense Correspondence
<center><img src="/figures/app_portrait_relighting.jpg" width="1152" ></center>

## **Application 3:** Dense Correspondence 2
<iframe width="100%" height="100%" style="margin: none; display: block;"
src="https://www.youtube.com/embed/BN6LLJpw-v0">
</iframe>

## **BibTeX**
<div style="background-color:rgba(0, 0, 0, 0.0470588); text-align:center; vertical-align: middle; padding:30px 60px;">
<p>@article{xiang2021disunknown,</p>
<p>title = {DisUnknown: Distilling Unknown Factors for Disentanglement Learning},</p>
<p>author = {Xiang, Sitao and Gu, Yuming and Xiang, Pengda and Chai, Menglei and Li, 
Hao and Zhao, Yajie and He, Mingming},</p>
<p>journal = {arXiv preprint arXiv:2109.08090},</p>
<p>year = {2021}</p>
<p>}</p>
</div>

<!-- ## **Architexture**
<center><img src="/figures/train_stage.jpg" width="1152"></center>

## **Application 1:** Anime Style Transfer.
Disentanglement of the artists' identity (*known factor*) and the content 
(*unknown factor*) in anime images,
and its application in anime style transfer.
<center><img src="/figures/app_anime_style_transfer.jpg" width="1152" >
<figcaption>The left column shows four input examples of two different
artists.</figcaption></center>

## **Application 2:** Portrait Relighting
Disentanglement of the lighting (*known factor*) and the remaining content 
(unknown factor) in portrait images,
and its application for portrait relighting.
<center><img src="/figures/app_portrait_relighting.jpg" width="1152" ></center>

## **Application 3:** Landmark-Based Face Reenactment
Disentanglement of the identity (*known factor*), the pose (*known factor*) 
and the expression (*unknown factor*) in 2D face landmarks,
and its application in face reenactment.
<iframe width="100%" height="100%" style="margin: none; display: block;"
src="https://www.youtube.com/embed/BN6LLJpw-v0">
</iframe>

## **Application 4:** Skeleton-Based Body Motion Retargeting
Disentanglement of the identity (*known factor*), the view (*known factor*) 
and the motion (*unknown factor*) in 2D skeletons,
and its application in body motion retargeting.
<center><img src="/figures/app_motion_retargeting.jpg" width="1152" ></center>

## **BibTeX**
<div style="background-color:rgba(0, 0, 0, 0.0470588); text-align:center; vertical-align: middle; padding:30px 60px;">
<p>@article{xiang2021disunknown,</p>
<p>title = {DisUnknown: Distilling Unknown Factors for Disentanglement Learning},</p>
<p>author = {Xiang, Sitao and Gu, Yuming and Xiang, Pengda and Chai, Menglei and Li, 
Hao and Zhao, Yajie and He, Mingming},</p>
<p>journal = {arXiv preprint arXiv:2109.08090},</p>
<p>year = {2021}</p>
<p>}</p>
</div> -->


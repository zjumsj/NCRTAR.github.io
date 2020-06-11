# <center> Neural Compositing for Real-Time Augmented Reality Rendering in Low-Frequency Lighting Environments </center>
<center> Shengjie Ma<sup>1*</sup>, Qian Shen<sup>1</sup>, Qiming Hou<sup>1,2</sup>, Zhong Ren<sup>1,2</sup>, Kun Zhou<sup>1,2*</sup> </center>  

<center> <sup>1</sup>State Key Lab of CAD&CG, Zhejiang University, China; </center>  

<center> <sup>2</sup> ZJU-FaceUnity Joint Lab of Intelligent Graphics, China. </center>  

### Abstruct

<p style="text-align:justify;"> We present <i>neural compositing</i>, a deep-learning based method for augmented reality rendering, which uses convolutional neural networks to composite rendered layers of a virtual object with a real photograph to emulate shadow and reflection effects. The method starts from estimating the lighting and roughness information from the photograph using neural networks, renders the virtual object with a virtual floor into color, shadow and reflection layers by applying the estimated lighting, and finally refines the reflection and shadow layers using neural networks and blends them with the color layer and input image to yield the output image. We assume low-frequency lighting environments and adopt PRT (Precomputed Radiance Transfer) for layer rendering, which makes the whole pipeline differentiable and enables fast end-to-end network training with synthetic scenes. Working on a single photograph, our method can produce realistic reflections in a real scene with spatially-varying material and cast shadows on background objects with unknown geometry and material at real-time frame rates. </p>

### Download urls
[Supplementary video](./edition_scis_final_720p.mp4)
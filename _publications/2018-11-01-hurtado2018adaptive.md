---
title: "Adaptive patches for mesh denoising"
collection: publications
permalink: /publication/hurtado2018adaptive
excerpt: ''
image: ../images/hurtado2018adaptive.png
smallimage: ../images/hurtado2018adaptive-small.png
date: 2018-11-01
venue: '2018 31st SIBGRAPI Conference on Graphics, Patterns and Images'
paperurl: 'https://ieeexplore.ieee.org/document/8614304'
citation: 'Hurtado, J., Gattass, M., Raposo, A., & Coelho, J. (2018, October). Adaptive patches for mesh denoising. In 2018 31st SIBGRAPI Conference on Graphics, Patterns and Images (SIBGRAPI) (pp. 1-8). IEEE.'
paper: 'http://janhurtado.github.io/files/hurtado2018adaptive.pdf'
slides: 'https://drive.google.com/file/d/1dVTaH-bDtHsMT8j0cLAi38bordCeJ3bP/view?usp=sharing'
talk: 'https://youtu.be/6p6D2L9j2kw'
video: 'https://youtu.be/e8DpA9s0QUU'
code: ''
bin: 'https://drive.google.com/file/d/1198aTmpCj49sQIUX2SP19R4ojAPHeF20/view?usp=sharing'
supplementary: 'https://drive.google.com/drive/folders/1i7oLscN_NlEDHAR-bGV9W4DyTq-vOhsZ?usp=sharing'
---


### Abstract

The generation of triangular meshes typically introduces undesired noise which comes from different sources. Mesh denoising is a geometry processing task to remove this kind of distortion. To preserve the geometric fidelity of the desired mesh, a mesh denoising algorithm must maintain the object details while removing artificial high-frequencies from the surface. In this work, we propose a two-step algorithm which uses adaptive patches and bilateral filtering to denoise the normal vector field, and then update vertex positions fitting the faces to the denoised normals. The computation of the adaptive patches is our main contribution. We formulate this computation as local quadratic optimization problems that can be controlled by a set of parameters to obtain the desired behavior. We compared our proposal with several algorithms proposed in the literature using synthetic and real data. Our algorithm yields better results in general and is based on a formal mathematical formulation.

Bibtex: 

```
@inproceedings{hurtado2018adaptive,
  title={Adaptive patches for mesh denoising},
  author={Hurtado, Jan and Gattass, Marcelo and Raposo, Alberto and Coelho, J{\'e}ferson},
  booktitle={2018 31st SIBGRAPI Conference on Graphics, Patterns and Images (SIBGRAPI)},
  pages={1--8},
  organization={IEEE}
}
```

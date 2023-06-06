<div align="center">

# HeadSculpt: Crafting 3D Head Avatars with Text
  
<a href="https://brandonhanx.github.io/">Xiao Han</a><sup>\*</sup>,
<a href="https://yukangcao.github.io/">Yukang Cao</a><sup>\*</sup>,
<a href="https://www.kaihan.org/">Kai Han</a>,
<a href="https://surrey-uplab.github.io/">Xiatian Zhu</a>,
<a href="https://jiankangdeng.github.io/">Jiankang Deng</a>,
<a href="http://personal.ee.surrey.ac.uk/Personal/Y.Song/">Yi-Zhe Song</a>,
<a href="http://personal.ee.surrey.ac.uk/Personal/T.Xiang/index.html">Tao Xiang</a><sup>†</sup>,
<a href="https://i.cs.hku.hk/~kykwong/">Kwan-Yee K. Wong</a><sup>†</sup>


[![Paper](http://img.shields.io/badge/Paper-arxiv.2306.03038-B31B1B.svg)](https://arxiv.org/abs/2306.03038)
<a href="https://brandonhan.uk/HeadSculpt"><img alt="page" src="https://img.shields.io/badge/Webpage-0054a6?logo=Google%20chrome&logoColor=white"></a>

<img src="https://github.com/brandonhanx/headsculpt/blob/main/docs/static/gif/saul.gif?raw=true" width="220px">
<img src="https://github.com/brandonhanx/headsculpt/blob/main/docs/static/gif/saul_normal.gif?raw=true" width="220px">
<img src="https://github.com/brandonhanx/headsculpt/blob/main/docs/static/gif/saul_clown.gif?raw=true" width="220px">
<img src="https://github.com/brandonhanx/headsculpt/blob/main/docs/static/gif/saul_clown_normal.gif?raw=true" width="220px">
  
Please refer to our webpage for more visualizations.
</div>

## Abstract
Recently, text-guided 3D generative methods have made remarkable advancements in producing high-quality textures and geometry, capitalizing on the proliferation of large vision-language and image diffusion models. However, existing methods still struggle to create high-fidelity 3D head avatars in two aspects: (1) They rely mostly on a pre-trained text-to-image diffusion model whilst missing the necessary 3D awareness and head priors. This makes them prone to inconsistency and geometric distortions in the generated avatars. (2) They fall short in fine-grained editing. This is primarily due to the inherited limitations from the pre-trained 2D image diffusion models, which become more pronounced when it comes to 3D head avatars. In this work, we address these challenges by introducing a versatile coarse-to-fine pipeline dubbed HeadSculpt for crafting (i.e., generating and editing) 3D head avatars from textual prompts. Specifically, we first equip the diffusion model with 3D awareness by leveraging landmark-based control and a learned textual embedding representing the back view appearance of heads, enabling 3D-consistent head avatar generations. We further propose a novel identity-aware editing score distillation strategy to optimize a textured mesh with a high-resolution differentiable rendering technique. This enables identity preservation while following the editing instruction. We showcase HeadSculpt's superior fidelity and editing capabilities through comprehensive experiments and comparisons with existing methods.
<!-- 
## Pipeline
We craft high-resolution 3D head avatars in a coarse-to-fine manner. At the core of our network are: **(a) prior-driven score distillation** empowered by a landmark-based ControlNet as well as a view-dependent textual inversion. **(b) identity-aware editing score distillation** which maintains a controlled editing direction that respects both the original identity and the editing instruction.
 -->
<img src="https://github.com/brandonhanx/headsculpt/blob/main/docs/static/img/pipeline.png?raw=true">

## Code
We are working on releasing the code... 🏗️ 🚧 🔨 Please stay tuned!

## Misc.
If you want to cite our work, please use the following bib entry:
```
@article{han2023headsculpt,
         title={HeadSculpt: Crafting 3D Head Avatars with Text},
         author={Xiao Han and Yukang Cao and Kai Han and Xiatian Zhu and Jiankang Deng and Yi-Zhe Song and Tao Xiang and Kwan-Yee K. Wong},
         journal={arXiv preprint arXiv:2306.03038},
         year={2023}
}
```

<div align="center">

[![Star History Chart](https://api.star-history.com/svg?repos=BrandonHanx/HeadSculpt&type=Date)](https://star-history.com/#BrandonHanx/HeadSculpt&Date)

</div>

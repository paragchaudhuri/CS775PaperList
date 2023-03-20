# CS775 Paper Reading Ideas
Paper reading ideas for the advanced computer graphics course

## Physics-based animation

1. Kitchen physics - simulate the physics and process of cooking. How to simulate a chapati rising, or simple dal-rice?
   1. Anyone can cook (http://graphics.pixar.com/library/AnyoneCanCook/paper.pdf)
   2. Non-newtonian fluids (http://physbam.stanford.edu/~fedkiw/papers/stanford2015-01.pdf)
  
2. Detailed cloth simulation from data - take the help of data to produce detailed cloth sims. Can data help with collisions too?
   1. Subspace clothing (http://graphics.pixar.com/library/SubspaceClothing/paper.pdf)
   2. Data-driven clothing (http://physbam.stanford.edu/~fedkiw/papers/stanford2018-03.pdf)

3. Fluid Simulation 
   1. Covector Fluids (SIGGRAPH 2022) - Simulates Euler equations for inviscid fluids by using a novel formulation based on covectors.
   (https://cseweb.ucsd.edu/~ravir/covectorfluids.pdf)
   2. Unified Particle System for Multiple-fluid Flow and Porous Material (SIGGRAPH 2021) - An SPH-based simulation scheme for multiple-fluid liquid flow interacting with sponge-like porous materials. 
   (https://dl.acm.org/doi/pdf/10.1145/3450626.3459764)
   3. Lagrangian Neural Style Transfer for Fluids (SIGGRAPH 2020) - A neural style transfer approach from images to 3D fluids formulated in a
Lagrangian viewpoint.
   (https://arxiv.org/pdf/2005.00803.pdf)

 
## Modelling

1. Lego technic design (https://appsrv.cse.cuhk.edu.hk/~haoxu/projects/compute_technic/)
2. Authoring Consistent Landscapes With Flora and Fauna (SIGGRAPH 2021) - The algorithm outputs a steady-state ecosystem in the form of density maps for each species, their daily circuits, and a modified terrain with eroded trails from a terrain, climatic conditions, and species with related biological information. (https://dl.acm.org/doi/pdf/10.1145/3450626.3459952)

  
## Art

1. Simulating painting
   1. Wetbrush: GPU-based 3D painting simulation at the bristle level (http://www.zhilichen.com/projects/#wetbrush-pub)
2. VToonify: Controllable High-Resolution Portrait Video Style Transfer (SIGGRAPH Asia 2022) - A framework for style controllable high-resolution video toonification.
(https://arxiv.org/pdf/2209.11224.pdf)
3. CLIPasso: Semantically Aware Object Sketching (SIGGRAPH 2022) - A method for sketching objects at different levels of abstraction. The abstraction degree is controlled by varying the number of strokes.
(https://arxiv.org/abs/2202.05822)
4. ARF: Artistic Radiance Fields (ECCV 2022)
Description: Method for reconstructing artistic radiance fields from photorealistic radiance fields given user-specified style exemplars.
(https://arxiv.org/pdf/2206.06360.pdf)

  
  
## Character Animation

1. Learning by mimicing - DeepMimic (https://xbpeng.github.io/projects/DeepMimic/index.html)
2. Transflower: probabilistic autoregressive dance generation with multimodal attention (SIGGRAPH 2021) - A probabilistic autoregressive architecture that models the distribution over future poses with a normalizing flow conditioned on previous poses as well as music context, using a multimodal transformer encoder. (https://arxiv.org/pdf/2106.13871.pdf)
3. Neural Animation Layering for Synthesizing Martial Arts Movements (SIGGRAPH 2021) - A deep learning framework to produce a large variety of martial arts movements in a controllable manner from raw motion capture data. (https://www.ipab.inf.ed.ac.uk/cgvu/starke2021.pdf)
4. Learned Motion Matching (SIGGRAPH 2020) - A learned alternative to the Motion Matching algorithm. (https://dl.acm.org/doi/pdf/10.1145/3386569.3392440)

   
   
## Rendering and Inverse Rendering

1. Deep Shading: Convolutional Neural Networks for Screen-Space Shading (https://arxiv.org/pdf/1603.06078.pdf)
2. Neural Supersampling for Real-time Rendering (SIGGRAPH 2020) - Method for neural upsampling of rendered video content.
(https://dl.acm.org/doi/pdf/10.1145/3386569.3392376)
3. Differentiable Rendering of Neural SDFs through Reparameterization (SIGGRAPH Asia 2022) - A method to automatically compute correct gradients with respect to geometric scene parameters in neural SDF renderers (https://people.csail.mit.edu/sbangaru/projects/dsdf-2022/dsdf-2022.pdf)
4. Instant Neural Graphics Primitives With a Multiresolution Hash Encoding (SIGGRAPH 2022) - An approach that makes it extremely efficient to train and perform inference on neural networks acting as high-quality representations of graphics primitives (eg. signed distance functions, light fields, textures etc.). This makes the use of such primitives in the inner loops of graphics algorithms feasible. (https://arxiv.org/pdf/2201.05989.pdf)
5. Path-space differentiable rendering (SIGGRAPH 2020) - Formulation of a theoretical framework to estimate derivatives of radiometric measurements with respect to arbitrary scene parameters (e.g., material properties and object geometries). (https://shuangz.com/projects/psdr-sg20/psdr-sg20.pdf)

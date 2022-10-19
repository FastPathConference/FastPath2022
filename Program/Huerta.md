## [Eliu A. Huerta](https://www.anl.gov/profile/eliu-a-huerta)
### Lead for Translational AI and Computational Scientist -- Data Science and Learning Division
Argonne National Laboratory

<img src="https://www.anl.gov/sites/www/files/styles/profile_teaser_square_350px/public/eliu_portrait.jpg?h=2a479378&itok=7RvkFAIB" width="250">

### Invited Talk:  *AI4Physics:  From Conceptualization to AI-Driven Discovery at Scale*

### [Slides](https://fastpathconference.github.io/FastPath2022/Program/FastPath2022_Eliu_Huerta.pdf)

### [Video](https://youtu.be/6wFTOOJ4n9A)

**Abstract:**

AI can provide valuable analysis and insight of key problems in physics.  This talk will focus on one such use case:  gravitational wave astrophysics.  In January 2017, one of my graduate students, Daniel George, and I introduced a novel approach to search for and find gravitational waves.  The idea consisted of using convolutional neural networks to enable rapid classification and regression of gravitational wave signals in noisy time-series data streams and we developed several ideas that have played a central role in the design, training and use of deep learning for gravitational wave astrophysics.

However, this initial work had a number of challenges, e.g. our AI models were reporting 1 misclassification for every 200 seconds of searched data and they applied only for 2-D signal manifolds (the masses of the binary components).  We realized that training AI models that describe quasi-circular, spinning, non-precessing compact binary systems (equivalent to the 4-D signal manifold considered for low-latency gravitational wave searches) would require novel advances at the interface of AI and supercomputing. This is because the training dataset needed to densely sample a 4-D signal manifold had millions of modeled waveforms, and our benchmarks indicated that this computing challenge translated into an entire month of training using one NVIDIA V100 GPU.

To address this challenge, we started using the Hardware-Accelerated Learning (HAL) deep learning cluster at the National Center for Supercomputing Applications. Using the entire cluster, 64 NVIDIA V100 GPUs, we were able to reduce the training stage to 12 hours.  Later, working with colleagues at Oak Ridge National Laboratory and NVIDIA, we were able to deploy new optimizers in Summit to accelerate the training of AI models using thousands of NVIDIA V100 GPUs. Once we achieved the milestone of training physics-inspired AI models that describe a 4-D signal manifold in just over one hour using 1536 NVIDIA V100 GPUs in Summit, we focused on developing algorithms to process long batches of advanced LIGO noise (Laser Interferometer Gravitational-Wave Observatory).

**Biography:**

Dr. Eliu Huerta is Lead for Translational AI and Computational Scientist in the Data Science and Learning Division at Argonne National Laboratory.  He is a theoretical astrophysicist, mathematician and computer scientist with broad research interests.  He has done pioneering work at the interface of physics-inspired AI, scientific visualization and extreme scale computing for multi-messenger astrophysics, cosmology, observational astronomy, and large scale simulations that describe multi-scale and multi-physics phenomena. 
Huerta received a Master of Advanced Study in Applied Mathematics and Theoretical Physics and a PhD in Theoretical Astrophysics from the University of Cambridge, United Kingdom. He leads several NSF- and DOE-funded interdisciplinary and multi-institutional projects that focus on disruptive AI applications and advanced computing for big-data experiments. He enjoys doing translational AI research across disciplines, industry, finance and tech. He has published hundreds of publications, available in [Google Scholar](https://scholar.google.com/citations?user=CZQuCS0AAAAJ&hl=en) and [INSPIRE HEP](https://inspirehep.net/authors/1024644).

----
**[FastPath 2022 Program](https://fastpathconference.github.io/FastPath2022/)**

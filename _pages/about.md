---
layout: about
title: About
permalink: /
#subtitle:
profile:
  align: right
  image: quack.gif
  image_circular: false # crops the image to make it circular
  address: >
    <p> <tt>Figure 1. Kelvin Chen</tt> </p>

news: true  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

---
<p style="text-align: justify;">I am a third-year undergraduate at <a href='https://www.virginia.edu/'>UVA</a> majoring in neuroscience and chemistry with a minor in bioethics. I am respectively advised by Drs. <a href='https://med.virginia.edu/bims/faculty/?facbio=1&id=48788'>Petr Tvrdik</a> and <a href='https://www.barrowneuro.org/person/richard-dortch-phd/'>Richard Dortch</a> in the Departments of Neurosurgery and Translational Neuroscience at <a href='https://med.virginia.edu/'>UVA School of Medicine</a> and <a href='https://www.barrowneuro.org/'>Barrow Neurological Institute</a>, where I conduct neurologic disease-oriented preclinical research.</p>

<p style="text-align: justify;">My main research focuses on translating pathophysiological biomarkers and mechanisms of neurovascular diseases into novel diagnostic and therapeutic tools for clinical applications via the integration of computational and experimental methods.</p>

<p style="text-align: justify;">Please direct emails to <a href='mailto:ddw4hp@virginia.edu'><tt>ddw4hp [AT] virginia [DOT] edu</tt></a>.</p>

<details>
<summary> <b>Research Summary</b></summary>
<br>
Fundamentally, my work considers the following aspects of the SW distance:

<br><br>

<b><i>Slicing distributions.</i></b> The vanilla sliced Wasserstein (SW) distance naively treats all one-dimensional projections the same and independently by using the uniform distribution over projecting directions. To improve and generalize the SW, I propose to search for the best distribution over projecting distributions (or the slicing distribution) which can maximize the expected projected distance.

In particular, a regularized implicit family of distributions is introduced in ICLR'21 and explicit families (von Mises-Fisher and Power Spherical) are introduced in ICLR'21. Moreover, I introduce the usage of amortized optimization to predict the optimal slicing distribution given two input probability measures in the setting which has various pairs of probability measures in NeurIPS'22 and ICML'23. To enhance further the quality of projecting directions, I break the independence between them by imposing the first order Markov structure in NeurIPS'23.

To avoid unstable optimization and model misspecification in designing slicing models, I propose the energy-based slicing distribution that is parameter-free and has the density proportional to an energy function of the projected one-dimensional Wasserstein distance in NeurIPS'23. To push forward further the optimization-free direction, I propose the random-path projecting direction in ICML'24.

<br><br>

<b><i>Projecting operators.</i></b> The vanilla sliced Wasserstein distance utilizes the Radon Transform as the projecting operator. The Radon Transform simply takes the inner product between the supports of a probability measure and a projecting direction as the supports of the one-dimensional projected probability measure. To generalize the projecting operator to tensor spaces, I use the convolution operator to project probability measures over tensors to one-dimension in NeurIPS'22. In addition, I connect deep learning (neural networks) techniques to sliced Wasserstein by proposing Overparameterized Radon Transform and Hierarchical Radon Transform in ICLR'23. Recently, I proposed hierarchical hybrid Radon Transform and hierarchical hybrid sliced Wasserstein distance for dealing with heterogeneous joint distributions in Arxiv'24.

<br><br>

<b><i>Numerical approximation.</i></b> The SW distance is usually estimated by Monte Carlo integration due to the intractable expectation with respect to the slicing distribution. To reduce the variance of the Monte Carlo estimator, I first propose control variates which are based on the closed-form of the Wasserstein-2 distance between two Gaussians in ICLR'24. Importantly, the proposed control variates have linear time complexity and space complexity. In addition, I propose to use low-discrepancy sequences on the sphere (Quasi-Monte Carlo) to approximate sliced Wasserstein in ICLR'24. Moreover, we propose Randomized Quasi-sliced Wasserstein, an unbiased estimation of sliced Wasserstein which is based on randomizing low-discrepancy sequences.

<br><br>

On the application side, my works adopt optimal transport, Wasserstein distance, and sliced Wasserstein distance in point-clouds applications ICML'23, 3D mesh deformation ICLR'24, generative models (GANs, Diffusion Models) NeurIPS'22 Arxiv'24, domain adaptation ICML'22, ICML'22, multimodal representation learning ICLR'24, 3D shape correspondence learning CVPR'24, and other tasks that need to deal with probability measures.

</details>

<hr>

<blockquote style="text-align: justify;">
    <font size="3"><i>"It is strange to see how the populace, which nourishes its imagination with tales of witches or saints, mysterious events and extraordinary occurrences, disdains the world around it as commonplace, monotonous and prosaic, without suspecting that at bottom it is all secret, mystery, and marvel."</i> ― Santiago Ramón y Cajal, <i>Recollections of My Life</i></font>
</blockquote>

<hr>

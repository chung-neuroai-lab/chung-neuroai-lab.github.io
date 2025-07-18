---
layout: default
---

<div class="container">

<h1> Publications </h1>

(*:co-first, +:co-last)

<hr>
<div class="pub-card">
<div class="pub-card-text">    
   <div class="pub-card-title"> <!----Title---> Variations in neuronal selectivity create efficient representational geometries for perception </div>
    <div class="pub-card-subtitle"> <!----Title---> Sonica Saraf, J. Anthony Movshon, SueYeon Chung </div> 
    <div class="pub-card-body"> <!----Description---> Our visual capabilities depend on neural response properties in visual areas of our brains. Neurons exhibit a wide variety of selective response properties, but the reasons for this diversity are unknown. Here, we related the distribution of neuronal tuning properties to the information capacity of the population. Our results from theory, simulations, and analysis of recordings from macaque primary visual cortex (V1) reveal that diversity of amplitude and bandwidth drive complementary changes to the representational geometry of a population. Amplitude diversity pushes the centers of the representations further apart, whereas bandwidth heterogeneity decorrelates the center locations. These geometric changes separate out representations for distinct stimuli, creating more efficient encoding. [<a id="external-link" href="https://www.biorxiv.org/content/10.1101/2025.06.26.661754v1">pdf</a>] [<a id="external-link" href="assets/bib/saraf2025variations.html">bib</a>] <i> bioRxiv, 2025 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/pub_imgs/saraf2025variations.png" />
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">    
   <div class="pub-card-title"> <!----Title---> Estimating Neural Representation Alignment from Sparsely Sampled Inputs and Features </div>
    <div class="pub-card-subtitle"> <!----Title---> Chanwoo Chun, Abdulkadir Canatar, SueYeon Chung, Daniel D. Lee</div> 
    <div class="pub-card-body"> <!----Description---> In both artificial and biological systems, the centered kernel alignment (CKA) has become a widely used tool for quantifying neural representation similarity. While current CKA estimators typically correct for the effects of finite stimuli sampling, the effects of sampling a subset of neurons are overlooked, introducing notable bias in standard experimental scenarios. Here, we provide a theoretical analysis showing how this bias is affected by the representation geometry. We then introduce a novel estimator that corrects for both input and feature sampling. We use our method for evaluating both brain-to-brain and model-to-brain alignments and show that it delivers reliable comparisons even with very sparsely sampled neurons. We perform within-animal and across-animal comparisons on electrophysiological data from visual cortical areas V1, V4, and IT data, and use these as benchmarks to evaluate model-to-brain alignment. [<a id="external-link" href="https://arxiv.org/abs/2502.15104">pdf</a>] [<a id="external-link" href="assets/bib/chun2025estimating.html">bib</a>] <i> Cognitive Computational Neuroscience (CCN), 2025 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/pub_imgs/chun2025estimating.png" />
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">    
   <div class="pub-card-title"> <!----Title---> Geometry linked to untangling efficiency reveals structure and computation in neural populations </div>
    <div class="pub-card-subtitle"> <!----Title---> Chi-Ning Chou, Royoung Kim, Luke A Arend, Yao-Yuan Yang, Brett D Mensh, Won Mok Shim, Matthew G Perich, SueYeon Chung </div> 
    <div class="pub-card-body"> <!----Description---> From an eagle spotting a fish in shimmering water to a scientist extracting patterns from noisy data, many cognitive tasks require untangling overlapping signals. Neural circuits achieve this by transforming complex sensory inputs into distinct, separable representations that guide behavior. Data-visualization techniques convey the geometry of these transformations, and decoding approaches quantify performance efficiency. However, we lack a framework for linking these two key aspects. Here we address this gap by introducing a data-driven analysis framework, which we call Geometry Linked to Untangling Efficiency (GLUE) with manifold capacity theory, that links changes in the geometrical properties of neural activity patterns to representational untangling at the computational level. We applied GLUE to over seven neuroscience datasets—spanning multiple organisms, tasks, and recording techniques—and found that task-relevant representations untangle in many domains, including along the cortical hierarchy, through learning, and over the course of intrinsic neural dynamics. [<a id="external-link" href="https://pmc.ncbi.nlm.nih.gov/articles/PMC11996410/">pdf</a>] [<a id="external-link" href="assets/bib/chou2025geometry.html">bib</a>] <i> bioRxiv, 2025 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/pub_imgs/chou2025geometry.png" />
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">    
   <div class="pub-card-title"> <!----Title---> Feature Learning beyond the Lazy-Rich Dichotomy: Insights from Representational Geometry </div>
    <div class="pub-card-subtitle"> <!----Title---> Chi-Ning Chou*, Hang Le*, Yichen Wang, SueYeon Chung </div> 
    <div class="pub-card-body"> <!----Description---> Integrating task-relevant information into neural representations is a fundamental ability of both biological and artificial intelligence systems. Recent theories have categorized learning into two regimes: the rich regime, where neural networks actively learn task-relevant features, and the lazy regime, where networks behave like random feature models. Yet this simple lazy–rich dichotomy overlooks a diverse underlying taxonomy of feature learning, shaped by differences in learning algorithms, network architectures, and data properties. To address this gap, we introduce an analysis framework to study feature learning via the geometry of neural representations. Rather than inspecting individual learned features, we characterize how task-relevant representational manifolds evolve throughout the learning process. We show, in both theoretical and empirical settings, that as networks learn features, task-relevant manifolds untangle, with changes in manifold geometry revealing distinct learning stages and strategies beyond the lazy–rich dichotomy. [<a id="external-link" href="https://openreview.net/forum?id=gKdjHLrHDS">pdf</a>][<a id="external-link" href="assets/bib/choufeature2025.html">bib</a>] <i> Spotlight paper, ICML, 2025 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/pub_imgs/choufeature2025.png" />
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">    
   <div class="pub-card-title"> <!----Title---> Spectral Analysis of Representational Similarity with Limited Neurons </div>
    <div class="pub-card-subtitle"> <!----Title---> Hyunmo Kang, Abdulkadir Canatar, SueYeon Chung </div> 
    <div class="pub-card-body"> <!----Description---> Measuring representational similarity between neural recordings and computational models is challenging due to constraints on the number of neurons that can be recorded simultaneously. In this work, we investigate how such limitations affect similarity measures, focusing on Canonical Correlation Analysis (CCA) and Centered Kernel Alignment (CKA). Leveraging tools from Random Matrix Theory, we develop a predictive spectral framework for these measures and demonstrate that finite neuron sampling systematically underestimates similarity due to eigenvector delocalization. To overcome this, we introduce a denoising method to infer population-level similarity, enabling accurate analysis even with small neuron samples. [<a id="external-link" href="https://arxiv.org/pdf/2502.19648">pdf</a>][<a id="external-link" href="assets/bib/kang2025spectral.html">bib</a>] <i> arXiv, 2025 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/pub_imgs/kang2025spectral.png" />
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">    
   <div class="pub-card-title"> <!----Title---> Statistical Mechanics of Support Vector Regression </div>
    <div class="pub-card-subtitle"> <!----Title---> Abdulkadir Canatar, SueYeon Chung </div> 
    <div class="pub-card-body"> <!----Description---> A key problem in deep learning and computational neuroscience is relating the geometrical properties of neural representations to task performance. Here, we consider this problem for continuous decoding tasks where neural variability may affect task precision. Using methods from statistical mechanics, we study the average-case learning curves for ε-insensitive Support Vector Regression (ε-SVR) and discuss its capacity as a measure of linear decodability. Our analysis reveals a phase transition in the training error at a critical load, capturing the interplay between the tolerance parameter ε and neural variability. We uncover a double-descent phenomenon in the generalization error, showing that ε acts as a regularizer, both suppressing and shifting these peaks. [<a id="external-link" href="https://arxiv.org/pdf/2412.05439">pdf</a>][<a id="external-link" href="assets/bib/canatar2024statistical.html">bib</a>] <i> Physical Review E, 2025 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/pub_imgs/canatar2024statistical.png" />
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">    
   <div class="pub-card-title"> <!----Title---> The Geometry of Prompting: Unveiling Distinct Mechanisms of Task Adaptation in Language Models </div>
    <div class="pub-card-subtitle"> <!----Title---> Artem Kirsanov, Chi-Ning Chou, Kyunghyun Cho, SueYeon Chung </div> 
    <div class="pub-card-body"> <!----Description---> Decoder-only language models have the ability to dynamically switch between various computational tasks based on input prompts. Despite many successful applications of prompting, there is very limited understanding of the internal mechanism behind such flexibility. In this work, we investigate how different prompting methods affect the geometry of representations in these models. Employing a framework grounded in statistical physics, we reveal that various prompting techniques, while achieving similar performance, operate through distinct representational mechanisms for task adaptation. Our analysis highlights the critical role of input distribution samples and label semantics in few-shot in-context learning. [<a id="external-link" href="https://arxiv.org/pdf/2502.08009">pdf</a>][<a id="external-link" href="assets/bib/kirsanov2025geometry.html">bib</a>] <i> NAACL, 2025 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/pub_imgs/kirsanov2025geometry.png" />
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">    
   <div class="pub-card-title"> <!----Title---> Nonlinear classification of neural manifolds with contextual information </div>
    <div class="pub-card-subtitle"> <!----Title---> Francesca Mignacco, Chi-Ning Chou, SueYeon Chung </div> 
    <div class="pub-card-body"> <!----Description---> Understanding how neural systems efficiently process information through distributed representations is a fundamental challenge at the interface of neuroscience and machine learning. Recent approaches analyze the statistical and geometrical attributes of neural representations as population-level mechanistic descriptors of task implementation. In particular, manifold capacity has emerged as a promising framework linking population geometry to the separability of neural manifolds. However, this metric has been limited to linear readouts. To address this limitation, we introduce a theoretical framework that leverages latent directions in input space, which can be related to contextual information. We derive an exact formula for the context-dependent manifold capacity that depends on manifold geometry and context correlations, and validate it on synthetic and real data. [<a id="external-link" href="https://journals.aps.org/pre/pdf/10.1103/PhysRevE.111.035302">pdf</a>][<a id="external-link" href="assets/bib/mignacco2025nonlinear.html">bib</a>] <i> Physical Review E, 2025, Editors' Suggestion </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/pub_imgs/mignacco2025nonlinear.png" />
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">    
   <div class="pub-card-title"> <!----Title---> Estimating the Spectral Moments of the Kernel Integral Operator from Finite Sample Matrices </div>
    <div class="pub-card-subtitle"> <!----Title---> Chanwoo Chun, SueYeon Chung, Daniel D. Lee </div> 
    <div class="pub-card-body"> <!----Description---> Analyzing the structure of sampled features from an input data distribution is challenging when constrained by limited measurements in both the number of inputs and features. Traditional approaches often rely on the eigenvalue spectrum of the sample covariance matrix derived from finite measurement matrices; however, these spectra are sensitive to the size of the measurement matrix, leading to biased insights. In this paper, we introduce a novel algorithm that provides unbiased estimates of the spectral moments of the kernel integral operator in the limit of infinite inputs and features from finitely sampled measurement matrices. Our method, based on dynamic programming, is efficient and capable of estimating the moments of the operator spectrum.[<a id="external-link" href="https://arxiv.org/pdf/2410.17998">pdf</a>][<a id="external-link" href="assets/bib/chun2024estimating.html">bib</a>] <i> AISTATS, 2025 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/pub_imgs/chun2024estimating.png" />
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">    
   <div class="pub-card-title"> <!----Title---> Contrastive-Equivariant Self-Supervised Learning Improves Alignment with Primate Visual Area IT </div>
    <div class="pub-card-subtitle"> <!----Title---> Thomas Yerxa, Jenelle Feather, Eero Simoncelli, SueYeon Chung </div> 
    <div class="pub-card-body"> <!----Description---> Models trained with self-supervised learning objectives have recently matched or surpassed models trained with traditional supervised object recognition in their ability to predict neural responses of object-selective neurons in the primate visual system. However, typical self-supervised objectives may result in network representations that are overly invariant to changes in the input. We introduce a novel framework for converting standard invariant SSL losses into “contrastive-equivariant” versions that encourage preservation of input transformations without supervised access to the transformation parameters. We demonstrate that our proposed method systematically increases the ability of models to predict responses in macaque inferior temporal cortex. [<a id="external-link" href="https://openreview.net/pdf?id=AiMs8GPP5q">pdf</a>][<a id="external-link" href="assets/bib/yerxa2024contrastive.html">bib</a>] <i> NeurIPS, 2024 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/pub_imgs/yerxa2024contrastive.png" />
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">    
   <div class="pub-card-title"> <!----Title---> Representational Learning by Optimization of Neural Manifolds in an Olfactory Memory Network </div>
    <div class="pub-card-subtitle"> <!----Title---> Bo Hu, Nesibe Z. Temiz, Chi-Ning Chou, Peter Rupprecht, Claire Meissner-Bernard, Benjamin Titze, SueYeon Chung, Rainer W. Friedrich </div> 
    <div class="pub-card-body"> <!----Description---> Higher brain functions depend on experience-dependent representations of relevant information that may be organized by attractor dynamics or by geometrical modifications of continuous “neural manifolds”. To explore these scenarios we analyzed odor-evoked activity in telencephalic area pDp of juvenile and adult zebrafish, the homolog of piriform cortex. No obvious signatures of attractor dynamics were detected. Rather, olfactory discrimination training selectively enhanced the separation of neural manifolds representing task-relevant odors from other representations, consistent with predictions of autoassociative network models endowed with precise synaptic balance. [<a id="external-link" href="https://www.biorxiv.org/content/10.1101/2024.11.17.623906v1">pdf</a>][<a id="external-link" href="assets/bib/hu2024representational.html">bib</a>] <i> bioRxiv, 2024 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/pub_imgs/hu2024representational.png" />
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">    
   <div class="pub-card-title"> <!----Title---> Neural Population Geometry and Optimal Coding of Tasks with Shared Latent Structure </div>
    <div class="pub-card-subtitle"> <!----Title---> Albert J. Wakhloo, Will Slatton, and SueYeon Chung </div> 
    <div class="pub-card-body"> <!----Description---> Humans and animals can recognize latent structures in their environment and apply this information to efficiently navigate the world. Several recent works argue that the brain supports these abilities by forming neural representations that encode such latent structures in flexible, generalizable ways. However, it remains unclear what aspects of neural population activity are contributing to these computational capabilities. Here, we develop an analytical theory linking the mesoscopic statistics of a neural population’s activity to generalization performance on a multi-task learning problem.  [<a id="external-link" href="https://arxiv.org/pdf/2402.16770.pdf">pdf</a>] <i> arXiv, 2024 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/wakhloo2024.png" />
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">    
   <div class="pub-card-title"> <!----Title---> Probing Biological and Artificial Neural Networks with Task-dependent Neural Manifolds </div>
    <div class="pub-card-subtitle"> <!----Title---> Michael Kuoch*, Chi-Ning Chou*, Nikhil Parthasarathy, Joel Dapello, James J. DiCarlo, Haim Sompolinsky, SueYeon Chung </div> 
    <div class="pub-card-body"> <!----Description---> Recently, growth in our understanding of the computations performed in both biological and artificial neural networks has largely been driven by either low-level mechanistic studies or global normative approaches. However, concrete methodologies for bridging the gap between these levels of abstraction remain elusive. In this work, we investigate the internal mechanisms of neural networks through the lens of neural population geometry, aiming to provide understanding at an intermediate level of abstraction, as a way to bridge that gap [<a id="external-link" href="https://proceedings.mlr.press/v234/kuoch24a/kuoch24a.pdf">pdf</a>] [<a id="external-link" href="assets/bib/kuoch2024.html">bib</a>] <i> Conference on Parsimony and Learning, 2024 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/kuoch2024.png" />
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">    
   <div class="pub-card-title"> <!----Title---> Unsupervised learning on spontaneous retinal activity leads to efficient neural representation geometry </div>
    <div class="pub-card-subtitle"> <!----Title---> Andrew Ligeralde, Yilun Kuang, Thomas Edward Yerxa, Miah N. Pitcher, Marla Feller, SueYeon Chung </div> 
    <div class="pub-card-body"> <!----Description--->  Prior to the onset of vision, neurons in the developing mammalian retina spontaneously fire in correlated activity patterns known as retinal waves. Experimental evidence suggests that retinal waves strongly influence the emergence of sensory representations before visual experience. We aim to model this early stage of functional development by using movies of neurally active developing retinas as pre-training data for neural networks [<a id="external-link" href="https://arxiv.org/pdf/2312.02791.pdf">pdf</a>] <i> UniReps workshop, NeurIPS, 2023 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/ligeralde2023.png" />
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">    
   <div class="pub-card-title"> <!----Title---> A Spectral Theory of Neural Prediction and Alignment </div>
    <div class="pub-card-subtitle"> <!----Title---> Abdulkadir Canatar*, Jenelle Feather*, Albert Wakhloo, SueYeon Chung </div> 
    <div class="pub-card-body"> <!----Description--->  Many different state-of-the-art deep neural networks yield similar neural predictions, but it remains unclear how to differentiate among models that perform equally well at predicting neural responses. To gain insight into this, we use a recent theoretical framework that relates the generalization error from regression to the spectral bias of the model activations and the alignment of the neural responses onto the learnable subspace of the model. [<a id="external-link" href="https://openreview.net/pdf?id=5B1ZK60jWn">pdf</a>] [<a id="external-link" href="assets/bib/canatar2023.html">bib</a>] [<a id="external-link" href="https://github.com/chung-neuroai-lab/SNAP">code</a>] <i> Spotlight paper, NeurIPS, 2023 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/canatar2023.png" />
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">    
   <div class="pub-card-title"> <!----Title---> Learning Efficient Coding of Natural Images with Maximum Manifold Capacity Representations </div>
    <div class="pub-card-subtitle"> <!----Title---> Thomas Yerxa, Yilun Kuang, Eero Simoncelli, SueYeon Chung </div> 
    <div class="pub-card-body"> <!----Description--->  Self-supervised Learning (SSL) provides a strategy for constructing useful representations of images without relying on hand-assigned labels. Many such methods aim to map distinct views of the same scene or object to nearby points in the representation space, while employing some constraint to prevent representational collapse. Here we recast the problem in terms of efficient coding by adopting manifold capacity.[<a id="external-link" href="https://openreview.net/pdf?id=og9V7NgOrQ">pdf</a>][<a id="external-link" href="assets/bib/yerxa2023.html">bib</a>] <i> NeurIPS, 2023 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/yerxa2023.png" />
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">    
   <div class="pub-card-title"> <!----Title---> Social learning enhances stimulus representations in the auditory cortex </div>
    <div class="pub-card-subtitle"> <!----Title---> Nihaad Paraouty, Justin D. Yao, Léo Varnet, Chi-Ning Chou, SueYeon Chung, Dan H. Sanes </div> 
    <div class="pub-card-body"> <!----Description--->  Social learning (SL) through experience with conspecifics can facilitate the acquisition of many behaviors. Thus, when Mongolian gerbils are exposed to a demonstrator performing an auditory discrimination task, their subsequent task acquisition is facilitated, even in the absence of visual cues. Here, we show that transient inactivation of auditory cortex (AC) during exposure caused a significant delay in task acquisition during the subsequent practice phase, suggesting that AC activity is necessary for SL. [<a id="external-link" href="https://www.nature.com/articles/s41467-023-41641-8">pdf</a>][<a id="external-link" href="assets/bib/paraouty2023.html">bib</a>] <i> Nature Communications, 2023 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/paraouty2023.png" />
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">    
   <div class="pub-card-title"> <!----Title---> Linear Classification of Neural Manifolds with Correlated Variability </div>
    <div class="pub-card-subtitle"> <!----Title---> Albert J. Wakhloo, Tamara J. Sussman, and SueYeon Chung </div> 
    <div class="pub-card-body"> <!----Description--->  In this letter, we calculate how correlations between object representations affect the capacity, a measure of linear separability. We show that for spherical object manifolds, introducing correlations between centroids effectively pushes the spheres closer together, while introducing correlations between the spheres’ axes effectively shrinks their radii, revealing a duality between neural correlations and geometry [<a id="external-link" href="https://drive.google.com/file/d/1f4Uk1yirrsmLKnwK8xEDGft6SLK1EKJD/view">pdf</a>][<a id="external-link" href="assets/bib/wakhloo.html">bib</a>][<a id="external-link" href="https://github.com/awakhloo/correlated_capacity">code</a>] <i>  Physical Review Letters, 2023, Editors' Suggestion, Featured in Physics </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/wakhloo.png" />
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">    
   <div class="pub-card-title"> <!----Title---> Unveiling the benefits of multitasking in disentangled representation formation </div>
    <div class="pub-card-subtitle"> <!----Title---> Jenelle Feather, SueYeon Chung </div> 
    <div class="pub-card-body"> <!----Description--->  [<a id="external-link" href="https://www.cell.com/action/showPdf?pii=S1364-6613%2823%2900127-4">pdf</a>][<a id="external-link" href="assets/bib/feather2023.html">bib</a>] <i> Trends in Cognitive Sciences, 2023 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/feather2023.png" />
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">
    <div class="card-title">Transformation of acoustic information to sensory decision variables in the parietal cortex. </div> 
    <div class="card-subtitle"> Justin D. Yao*, Klavdia O. Zemlianova*, David L. Hockera, Cristina Savina, Christine M. Constantinople, SueYeon Chung,  and Dan H. Sanes. </div> 
    <div class="pub-card-body"> [<a id="external-link" href="https://www.pnas.org/doi/epdf/10.1073/pnas.2212120120">pdf</a>] [<a id="external-link" href="assets/bib/yao2022.html">bib</a>] <i> PNAS, 2023 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/yao-et-al.png"/>
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">
<div class="pub-card-title"> The Implicit Bias of Gradient Descent on
Generalized Gated Linear Networks </div> 
<div class="pub-card-subtitle"> Samuel Lippl, L.F. Abbott, and SueYeon Chung, </div> 
<div class="pub-card-body"> Understanding the asymptotic behavior of gradient-descent training of deep neural networks is essential for revealing inductive biases and improving network performance. We derive the infinite-time training limit of a mathematically tractable class of deep nonlinear neural networks, gated linear networks (GLNs), and generalize these results to gated networks described by general homogeneous polynomials.  [<a id="external-link" href="https://arxiv.org/pdf/2202.02649.pdf">pdf</a>] [<a id="external-link" href="assets/bib/lippl2022.html">bib</a>] <i> arXiv, 2022 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/lippl-et-al.png"/>
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">
<div class="pub-card-title"> Divisive Feature Normalization Improves Image Recognition Performance in AlexNet</div> 
<div class="pub-card-subtitle"> Michelle Miller, SueYeon Chung, Kenneth D. Miller </div> 
<div class="pub-card-body"> Local divisive normalization provides a phenomenological description of many nonlinear response properties of neurons across visual cortical areas. To gain insight into the utility of this operation, we studied the effects on AlexNet of a local divisive normalization between features, with learned parameters.   [<a id="external-link" href="https://openreview.net/pdf?id=aOX3a9q3RVV">pdf</a>] [<a id="external-link" href="assets/bib/miller2022.html">bib</a>] <i> ICLR, 2022</i> </div>
</div>
<img class="pub-card-img"/>
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">
    <div class="pub-card-title"> Neural population geometry: An approach for understanding biological and artificial neural networks</div> 
    <div class="pub-card-subtitle"> SueYeon Chung, Larry Abbott </div> 
    <div class="pub-card-body"> We highlight recent studies of neural population geometry: untangling in perception, classification theory of manifolds, abstraction in cognitive systems, topology underlying cognitive maps, dynamic untangling in motor systems, and a dynamic approach to cognition.   [<a id="external-link" href="https://reader.elsevier.com/reader/sd/pii/S0959438821001227?token=A35A4C64517A0C79DEC5D1818739BAABEB465C461F9E49F7DED819CB2B8B6A37596F353C4C04FA8C561E9CD86D2C1B2D&originRegion=us-east-1&originCreation=20230118192945">pdf</a>] [<a id="external-link" href="assets/bib/chung-and-abbott.html">bib</a>] <i> Current Opinion in Neurobiology, 2021</i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/chung-and-abbott.png"/>
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">
    <div class="pub-card-title"> Credit Assignment Through Broadcasting a Global Error Vector </div> 
    <div class="pub-card-subtitle"> David G. Clark, L.F. Abbott, SueYeon Chung</div> 
    <div class="pub-card-body"> Here, we explore the extent to which a globally broadcast learning signal, coupled with local weight updates, enables training of DNNs. We present both a learning rule, called global error-vector broadcasting (GEVB), and a class of DNNs, called vectorized nonnegative networks (VNNs), inwhich this learning rule operates.  [<a id="external-link" href="https://arxiv.org/pdf/2106.04089.pdf">pdf</a>] [<a id="external-link" href = "https://github.com/davidclark1/VectorizedNets">code</a>] [<a id="external-link" href="assets/bib/clark2021.html">bib</a>] <i> NeurIPS, 2021 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/clark-et-al.png"/>
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">
   <div class="pub-card-title"> <!----Title---> Neural Population Geometry Reveals the Role of Stochasticity in Robust Perception </div> 
    <div class="pub-card-subtitle"> <!----Title---> Joel Dapello*, Jenelle Feather*, Hang Le*, Tiago Marques, David D. Cox, Josh H. McDermott, James J. DiCarlo, SueYeon Chung  </div> 
    <div class="pub-card-body"> <!----Description---> Using recently developed geometrical techniques from computational neuroscience, we investigate how adversarial perturbations influence the internal representations of standard, adversarially trained, and biologically-inspired stochastic networks. We find distinct geometric signatures for each type of network, revealing different mechanisms for achieving robust representations. [<a id="external-link" href="https://proceedings.neurips.cc/paper/2021/file/8383f931b0cefcc631f070480ef340e1-Paper.pdf">pdf</a>] [<a id="external-link" href="https://github.com/chung-neuroai-lab/adversarial-manifolds">code</a>] [<a id="external-link" href="assets/bib/dapello.html">bib</a>] <i> NeurIPS, 2021</i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/dapello.png"/>
</div>


<hr>
<div class="pub-card">
<div class="pub-card-text">
<div class="pub-card-title"> Syntactic Perturbations Reveal Representational Correlates of Hierarchical Phrase Structure in Pretrained Language Models </div> 
<div class="pub-card-subtitle"> Matteo Alleman, Jonathan Mamou, Miguel A Del Rio, Hanlin Tang, Yoon Kim+, SueYeon Chung+ </div> 
<div class="pub-card-body"> It is not entirely clear what aspects of sentence-level syntax are captured by  vector-based language representations, nor how (if at all) they are built along the stacked layers of the network. In this paper, we aim to address such questions with a general class of interventional, input perturbation-based analyses of representations from pretrained language models. Importing from computational and cognitive neuroscience the notion of representational invariance, we perform a series of probes designed to test the sensitivity of these representations to several kinds of structure in sentences.  [<a id="external-link" href="https://aclanthology.org/2021.repl4nlp-1.27.pdf">pdf</a>] [<a id="external-link" href="assets/bib/alleman-et-al.html">bib</a>] <i> ACL Workshop, Representation Learning for NLP, 2021 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/alleman-et-al.png"/>
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">
<div class="pub-card-title"> Understanding the Logit Distributions of Adversarially-Trained Deep Neural Networks</div> 
<div class="pub-card-subtitle"> Landan Seguin, Anthony Ndirango, Neeli Mishra, SueYeon Chung, Tyler Lee </div> 
<div class="pub-card-body"> Although adversarial training is successful at mitigating adversarial attacks, the behavioral differences between adversarially-trained (AT) models and standard models are still poorly understood. Motivated by a recent study on learning robustness without input perturbations by distilling an AT model, we explore what is learned during adversarial training by analyzing the distribution of logits in AT models.   [<a id="external-link" href="https://arxiv.org/pdf/2108.12001.pdf">pdf</a>] [<a id="external-link" href="assets/bib/seguin-et-al.html">bib</a>] <i> arXiv, 2021</i> </div>
</div>
<img class="pub-card-img"/>
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">
<div class="pub-card-title"> On the geometry of generalization and memorization in deep neural networks</div> 
<div class="pub-card-subtitle"> Cory Stephenson*, Suchismita Padhy*, Abhinav Ganesh, Yue Hui, Hanlin Tang, and SueYeon Chung </div> 
<div class="pub-card-body"> To examine the structure of when and where memorization occurs in a deep network, we use a recently developed replica-based mean field theoretic geometric analysis method. We find that all layers preferentially learn from examples which share features, and link this behavior to generalization performance.[<a id="external-link" href="https://openreview.net/pdf?id=V8jrrnwGbuc">pdf</a>] [<a id="external-link" href="assets/bib/stephensen-memorization-2020.html">bib</a>] <i> ICLR, 2021 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/stephensen-memorization-2020.png"/>
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">
<div class="pub-card-title"> Emergence of Separable Manifolds in Deep Language Representations</div> 
<div class="pub-card-subtitle"> Jonathan Mamou*, Hang Le*, Miguel A Del Rio, Cory Stephenson, Hanlin Tang, Yoon Kim, SueYeon Chung </div> 
<div class="pub-card-body"> We utilize mean-field theoretic manifold analysis, a recent technique from computational neuroscience that connects geometry of feature representations with linear separability of classes, to analyze language representations from large-scale contextual embedding models. We explore representations from different model families (BERT, RoBERTa, GPT, etc.) and find evidence for emergence of linguistic manifolds across layer depth (e.g., manifolds for part-of-speech tags), especially in ambiguous data (i.e, words with multiple part-of-speech tags, or part-of-speech classes including many words). [<a id="external-link" href="http://proceedings.mlr.press/v119/mamou20a/mamou20a.pdf">pdf</a>] [<a id="external-link" href="https://github.com/schung039/contextual-repr-manifolds">code</a>] [<a id="external-link" href="assets/bib/mamou.html">bib</a>] <i> ICML, 2020 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/mamou.png"/>
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">
   <div class="pub-card-title"> <!----Title---> Separability and geometry of object manifolds in deep neural networks </div> 
    <div class="pub-card-subtitle"> <!----Title---> Uri Cohen*, Sueyeon Chung*, Daniel D. Lee, Haim Sompolinsky </div> 
    <div class="pub-card-body"> <!----Description---> We demonstrate that changes in the geometry of the associated object manifolds underlie this improved capacity, and shed light on the functional roles different levels in the hierarchy play to achieve it, through orchestrated reduction of manifolds’ radius, dimensionality and inter-manifold correlations. [<a id="external-link" href="https://www.nature.com/articles/s41467-020-14578-5.pdf">pdf</a>] [<a id="external-link" href="https://github.com/sompolinsky-lab/dnn-object-manifolds">code</a>] [<a id="external-link" href="assets/bib/cohen2020.html">bib</a>] <i> Nature Communications, 2020 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/cohen-et-al.png"/>
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">
<div class="pub-card-title"> On 1/n neural representation and robustness</div> 
<div class="pub-card-subtitle"> Josue Nassar*, Piotr Aleksander Sokol*, SueYeon Chung, Kenneth D. Harris, Il Memming Park</div> 
<div class="pub-card-body">  In this work, we investigate the robustness to perturbations in neural networks by juxtaposing experimental results regarding the covariance spectrum of neural representations in the mouse V1 (Stringer et al) with artificial neural networks. We use adversarial robustness to probe Stringer et al's theory regarding the causal role of a 1/n covariance spectrum. [<a id="external-link" href="https://proceedings.neurips.cc/paper/2020/file/44bf89b63173d40fb39f9842e308b3f9-Paper.pdf">pdf</a>] [<a id="external-link" href="assets/bib/nassar.html">bib</a>] <i> NeurIPS, 2020 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/nassar.png"/>
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">
   <div class="pub-card-title"> <!----Title---> Untangling in Invariant Speech Recognition </div> 
    <div class="pub-card-subtitle"> <!----Title---> Cory Stephenson, Jenelle Feather, Suchismita Padhy, Oguz Elibol, Hanlin Tang, Josh McDermott, SueYeon Chung </div> 
    <div class="pub-card-body"> <!----Description---> Deep neural networks have achieved impressive performance in audio processing applications, both as sub-components of larger systems and as complete end-to-end systems by themselves. Despite their empirical successes, comparatively little is understood about how these audio models accomplish these tasks.In this work, we employ a recently developed statistical mechanical theory that connects geometric properties of network representations and the separability of classes to probe how information is untangled within neural networks trained to recognize speech. [<a id="external-link" href="https://proceedings.neurips.cc/paper/2019/file/e2db7186375992e729165726762cb4c1-Paper.pdf">pdf</a>] [<a id="external-link" href="https://github.com/schung039/neural_manifolds_replicaMFT">code</a>] [<a id="external-link" href="assets/bib/stephensen2020.html">bib</a>] <i> NeurIPS, 2019 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/stephensen2020.png"/>
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">
    <div class="pub-card-title"> <!----Title---> Classification and Geometry of General Perceptual Manifolds </div> 
    <div class="pub-card-subtitle"> <!----Title---> Sueyeon Chung, Daniel D. Lee, Haim Sompolinsky  </div> 
    <div class="pub-card-body"> <!----Description---> We develop a statistical mechanical theory for the linear classification of manifolds with arbitrary geometry, revealing a remarkable relation to the mathematics of conic decomposition. We show how special anchor points on the manifolds can be used to define novel geometrical measures of radius and dimension, which can explain the classification capacity for manifolds of various geometries. [<a id="external-link" href="https://journals.aps.org/prx/pdf/10.1103/PhysRevX.8.031003">pdf</a>] [<a id="external-link" href="assets/bib/chung2018.html">bib</a>]<i> Physical Review X, 2018 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/chung2018.png"/>
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">
    <div class="pub-card-title"> <!----Title---> Learning Data Manifolds with a Cutting Plane Method </div> 
    <div class="pub-card-subtitle"> <!----Title---> Sueyeon Chung, Uri Cohen, Daniel D. Lee, Haim Sompolinsky  </div> 
    <div class="pub-card-body"> <!----Description---> [<a id="external-link" href="https://www.researchgate.net/profile/Sueyeon-Chung/publication/317230192_Learning_Data_Manifolds_with_a_Cutting_Plane_Method/links/5bac583b92851ca9ed292ebd/Learning-Data-Manifolds-with-a-Cutting-Plane-Method.pdf">pdf</a>] [<a id="external-link" href="assets/bib/chung-cutplane2018.html">bib</a>] <i> Neural Computation, 2018 </i> </div>
</div>
<img class="pub-card-img"/>
</div>

<hr>
<div class="pub-card">
<div class="pub-card-text">
    <div class="pub-card-title"> <!----Title---> Linear readout of object manifolds </div> 
    <div class="pub-card-subtitle"> <!----Title---> Sueyeon Chung, Daniel D. Lee, Haim Sompolinsky  </div> 
    <div class="pub-card-body"> <!----Description---> We present a theory that characterizes the ability of a linear readout network, the perceptron, to classify objects from variable neural responses. We show how the readout perceptron capacity depends on the dimensionality, size, and shape of the object manifolds in its input neural representation. [<a id="external-link" href="https://drive.google.com/file/d/1rtsSztFNUG5NcDcotVp5cJGfqIO59gqY/view">pdf</a>] [<a id="external-link" href="assets/bib/chung2016.html">bib</a>] <i> Physical Review E, 2016 </i> </div>
</div>
<img class="pub-card-img" src="{{site.baseurl | prepend:site.url}}assets/img/chung2016.png"/>
</div>

</div>
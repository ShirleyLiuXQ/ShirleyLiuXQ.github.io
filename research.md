---
layout: default
title: Research
---
# Research

Empirical advances in machine learning continue to outpace our theoretical understanding, leaving open fundamental questions about when, why, and how modern learning systems work. My research aims to develop <span class="kw">statistical and information-theoretic foundations</span> that help answer these questions and guide the design of more efficient and reliable learning systems.

An important consideration in pursuing this goal is learning from <span class="kw">heterogeneous data</span>. Real-world data often varies across time, latent groups, and problem instances, challenging the stationarity and homogeneity assumptions underlying much of classical learning theory.

With these questions and challenges in mind,  my recent and ongoing work draws on ideas from statistics, optimisation, and information theory to explore three interconnected research directions:

<details class="box">
<summary><span class="box-title">Understanding learning and generalisation</span></summary>
<div class="box-body" markdown="1">

A central goal of learning theory is to understand how model structure, learning objectives, and training procedures jointly determine the learned solution and its generalisation properties. 

Studying canonical models such as linear classifiers and two-layer neural networks allows us to characterise these relationships precisely and uncover the mechanisms underlying phenomena such as <span class="kw">early stopping</span>, <span class="kw">benign overfitting</span>, and <span class="kw">feature learning</span>. These insights help explain empirical observations and inform the design of more effective learning methods. Some of my recent works contribute to this direction:

</div>
<ul class="refs">
<li><a href="https://arxiv.org/abs/2608.06250">Minimax Optimal Early-Stopped Gradient Descent for Gaussian Mixture Classification</a>, NeurIPS 2026 <a class="tag" href="Early_stopped_GD_45mins_10QA.pdf">slides</a></li>
<li><a href="https://arxiv.org/abs/2611.30798">Precise Asymptotics of Non-Convex M-Estimators</a>, preprint, 2026</li>
</ul>
</details>

<details class="box">
<summary><span class="box-title">Sequential decision-making with heterogeneous data</span></summary>
<div class="box-body" markdown="1">

Sequential decision-making arises when actions must be chosen one at a time, often under <span class="kw">partial information</span>. For example:

- a doctor observes the outcome of a prescribed treatment but not what alternative treatments would have achieved;
- a language model cascade routes a query through increasingly costly models, deciding at each stage whether to answer or defer, without knowing in advance whether a cheaper model would suffice.

Limited information, compounded by heterogeneity across samples, makes optimal decision-making challenging. My work addresses these difficulties by developing principled methods with <span class="kw">provable performance guarantees</span>:

</div>
<ul class="refs">
<li><a href="https://proceedings.neurips.cc/paper_files/paper/2025/file/5eaa54503005d9125ad6aa3044e912d8-Paper-Conference.pdf">Non-stationary Bandit Convex Optimization: A Comprehensive Study</a>, NeurIPS 2025 <a class="tag" href="CDT_bandits_talk(20mins).pdf">slides</a> <a class="tag" href="neurips_poster_bandits.pdf">poster</a></li>
<li><a href="https://arxiv.org/abs/2610.39709">Bayes-Consistent Losses for Adaptive Inference in Classification</a>, preprint, 2026</li>
</ul>
</details>

<details class="box">
<summary><span class="box-title">Uncertainty quantification under minimal assumptions</span></summary>
<div class="box-body" markdown="1">

As machine learning (ML) systems, particularly <span class="kw">generative models</span>, are increasingly deployed in high-stakes settings, quantifying uncertainty is essential for assessing their reliability. This line of work develops statistical methods that provide rigorous guarantees under weak or no distributional assumptions. I am particularly interested in three tools suited to different challenges:

- <span class="kw">e-values</span>, a nascent alternative to p-values, for monitoring sequentially generated outputs, allowing evidence to accumulate over time while maintaining validity under flexible, data-dependent stopping rules;

  - Bayes-Assisted Confidence Sequences for CDFs <a class="tag" href="SAVI_2026_poster.pdf">poster</a>
  - Tutorials on sequential anytime-valid inference using e-values <a class="tag" href="Ramdas_Wang_ebook_chapter7-2.pdf">slides 1</a> <a class="tag" href="SAVI_tutorial_shirley.pdf">slides 2</a>
  - Tutorial on tight confidence sequences from universal portfolio <a class="tag" href="Reading_group_talk_on_universal_portfolio.pdf">slides</a>
  {: .refs}


- <span class="kw">conformal prediction</span> for constructing prediction sets with finite-sample coverage, treating complex ML models as black boxes and making no assumptions about the form of the data distribution;

- <span class="kw">prediction-powered inference (PPI)</span> for statistically  valid inference by using abundant ML-based predictions (e.g., AlphaFold-predicted  protein structures) in place of costly  gold-standard manually-obtained labels, while correcting for  their  prediction errors.

  - <a href="https://arxiv.org/abs/2610.39709">Bayes-Consistent Losses for Adaptive Inference in Classification</a> (Section 4), preprint, 2026
  {: .refs}

</div>
</details>


Much of my research is guided by a way of thinking rooted in information theory, the field of my [PhD study](https://www.repository.cam.ac.uk/items/81566d3e-5628-4936-a9d0-a23883808ef9): first understand and characterise the <span class="kw">fundamental performance limits</span> of a problem (i.e., what is achievable by any method), and then try to design <span class="kw">efficient methods to  approach these limits</span>.


## Preprints & publications

<ol class="pubs">
<li><a class="pub-title" href="https://arxiv.org/abs/2611.30798">Precise Asymptotics of Non-Convex M-Estimators</a><span class="pub-meta"><b>S.X. Liu</b>, T. Adhikari, P. Pandit. Preprint, 2026.</span></li>
<li><a class="pub-title" href="https://arxiv.org/abs/2608.06250">Minimax Optimal Early-Stopped Gradient Descent for Gaussian Mixture Classification</a><span class="pub-meta">A. Buna, <b>S.X. Liu</b>, P. Rebeschini. NeurIPS 2026. <a class="tag" href="talk_on_early_stopped_GD(10mins).pdf">slides</a></span></li>
<li><a class="pub-title" href="https://arxiv.org/abs/2610.39709">Bayes-Consistent Losses for Adaptive Inference in Classification</a><span class="pub-meta"><b>S.X. Liu</b>*, F. Regol*, A. Valkanas*, P. Rebeschini, M. Coates. Preprint, 2026.</span></li>
<li><a class="pub-title" href="https://www.nature.com/articles/s41586-025-10042-w">Laser Writing in Glass for Dense, Fast and Efficient Archival Data Storage</a><span class="pub-meta">J. Allison†, P. Anderson†, …, <b>X. Liu</b>†, … <i>Nature</i>, 2026.</span></li>
<li><a class="pub-title" href="https://proceedings.neurips.cc/paper_files/paper/2025/file/5eaa54503005d9125ad6aa3044e912d8-Paper-Conference.pdf">Non-stationary Bandit Convex Optimization: A Comprehensive Study</a><span class="pub-meta"><b>X. Liu</b>, D. Baudry, J. Zimmert, P. Rebeschini, A. Akhavan. NeurIPS 2025. <a class="tag" href="CDT_bandits_talk(20mins).pdf">slides</a> <a class="tag" href="neurips_poster_bandits.pdf">poster</a></span></li>
<li><a class="pub-title" href="https://ieeexplore.ieee.org/document/11206438">Many-User Multiple Access with Random User Activity: Achievability Bounds and Efficient Schemes</a><span class="pub-meta"><b>X. Liu</b>, P. Pascual Cobo, R. Venkataramanan. <i>IEEE Transactions on Information Theory</i>, 2025. <a class="tag" href="https://ieeexplore.ieee.org/abstract/document/10619669">conference version</a> <a class="tag" href="RA_isit2024(17mins).pdf">slides</a> <a class="tag" href="ESIT_GMAC_poster_final.pdf">poster</a></span></li>
<li><a class="pub-title" href="https://arxiv.org/pdf/2402.05625">Coded Many-User Multiple Access via Approximate Message Passing</a><span class="pub-meta"><b>X. Liu</b>, K. Hsieh, R. Venkataramanan. <i>Festschrift in Honor of Andrew Barron</i>, 2025. <a class="tag" href="https://ieeexplore.ieee.org/abstract/document/10619478">conference version</a> <a class="tag" href="CDMA_isit2024(17mins).pdf">slides</a></span></li>
<li><a class="pub-title" href="https://www.jmlr.org/papers/volume26/24-1789/24-1789.pdf">Inferring Change Points in High-Dimensional Regression via Approximate Message Passing</a><span class="pub-meta">G. Arpino, <b>X. Liu</b>, J. Gontarek, R. Venkataramanan. <i>JMLR</i>, 2025. <a class="tag" href="changepoint_ICML_slides.pdf">slides</a> <a class="tag" href="https://github.com/gabrielarpino/AMP_chgpt_lin_reg">code</a></span></li>
<li><a class="pub-title" href="https://proceedings.mlr.press/v235/arpino24a.html">Inferring Change Points in High-Dimensional Linear Regression via Approximate Message Passing</a><span class="pub-meta">G. Arpino, <b>X. Liu</b>, R. Venkataramanan. ICML 2024. <a class="tag" href="changepoints_poster.pdf">poster</a></span></li>
<li><a class="pub-title" href="https://ieeexplore.ieee.org/document/10120641">Sketching Sparse Low-Rank Matrices With Near-Optimal Sample- and Time-Complexity Using Message Passing</a><span class="pub-meta"><b>X. Liu</b>, R. Venkataramanan. <i>IEEE Transactions on Information Theory</i>, 2023. <a class="tag" href="https://ieeexplore.ieee.org/document/9834693">conference version</a></span></li>
</ol>

<p class="fine">* Equal contribution. † Alphabetical order.</p>

## Service
I routinely review papers for   conferences and journals including   NeurIPS (top reviewer 2024), ICML, ICLR, TMLR, ISIT, and ITW.
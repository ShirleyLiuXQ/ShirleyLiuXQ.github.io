<h1 style="font-size:30px">Research</h1>


Empirical advances in machine learning have outpaced our theoretical understanding, leaving open central questions about when, why, and how modern machine learning systems work. My research aims to develop <span style="color:darkred">statistical and information-theoretic foundations</span> for machine learning that help address these questions. A recurring theme is learning under <span style="color:darkred">data heterogeneity</span> since real-world data varies across time, latent groups, and problem instances, violating the stationarity and homogeneity assumptions on which much of classical theory rests.

Drawing on statistical learning theory, high-dimensional statistics, information theory, probability theory, and optimisation, my recent work is organised around three inter-connected threads: 

<ul>
<li>
<details markdown="1">
<summary><strong>Training dynamics of canonical statistical & machine learning models</strong> <span style="font-size: 0.8em;">▶</span></summary>
A key question in learning theory is how the model class and training procedure jointly  determine the learned solution  and its generalisation properties. Current theory, both asymptotic and finite-sample,  extends only to  canonical models such as  Gaussian mixtures and multi-index models (i.e., two-layer neural networks), since precise analyses are technically demanding and intricate even in these cases. Nevertheless, such analyses  have *repeatedly* sharpened  our understanding of phenomena including   <span style="color:darkred">early stopping</span>, <span style="color:darkred">benign overfitting</span>, and <span style="color:darkred">feature learning</span>, and informed practical choices of model and training procedure. Two of my recent and ongoing projects contribute to this area.
</details>
</li>
<li>
<details markdown="1">
<summary><strong>Sequential decision-making under data heterogeneity</strong> <span style="font-size: 0.8em;">▶</span></summary>
Sequential decision-making arises  wherever actions must be taken one at a time, under <span style="color:darkred">partial feedback</span>, with each action shaping what is  observed next:  clinical trials allocating patients as evidence accrues, recommender systems learning preferences from the choices they elicit, or inference pipelines escalating a query through a cascade of increasingly costly models, deciding at each stage whether to exit or defer. What makes such problems hard is that the information needed to act optimally is *unavailable* at the time of action, so practical systems rely heavily on heuristics. My work develops procedures with provable optimality guarantees that can <span style="color:darkred">inform or supersede heuristics</span>.
</details>
</li>
<li>
<details markdown="1">
<summary><strong>Uncertainty quantification under weak  distributional assumptions</strong> <span style="font-size: 0.8em;">▶</span></summary>
Quantifying uncertainty is relatively straightforward when the model is well-specified and much harder otherwise. My ongoing research asks what can *still* be certified when the usual distributional assumptions are withdrawn. <span style="color:darkred">E-values and e-processes</span>, <span style="color:darkred">conformal prediction</span>, and <span style="color:darkred">prediction-powered inference</span> deliver inference that remains valid at arbitrary, data-dependent  sample sizes, under  minimal data distributional assumptions.  
</details>
</li>
</ul>

During my PhD, I focused on <span style="color:darkred">message passing algorithms</span> for high-dimensional statistical estimation and inference: a family of computationally efficient, iterative algorithms that provably achieve statistical optimality across a range of problems. I applied these to changepoint localisation, sketching of sparse low-rank matrices, and reliable communication for large user networks.

## Interests:
- Training dynamics: early stopping, benign overfitting, feature learning. 
- First-order optimisation methods: gradient descent, approximate message passing
- Sequential decision-making: bandits, online learning, adaptive inference
- Uncertainty quantification: e-values, conformal prediction, prediction-powered inference
- Information theory and communication systems

## Selected publications:

1. **X. Liu**, D. Baudry, J. Zimmert, P. Rebeschini, A. Akhavan, "[Non-stationary Bandit Convex Optimization: A Comprehensive Study](https://arxiv.org/abs/2506.02980)", *Proceedings of the 39th Annual Conference on Neural Information Processing Systems*, 2025. ([talk](CDT_bandits_talk(20mins).pdf), [poster](neurips_poster_bandits.pdf))
2. In alphabetical order: J. Allison, P. Anderson, E. Aranas, Y. Assaf, M. Caballero, J. Chattaway, A Chatzieleftheriou, J. Clegg, B. Cooper, T. Deegan, A. Donnelly, R. Drevinskas, C. Gkantsidis, A. G. Diaz, I. Haller, F. Hong, T. Ilieva, R. Joyce, V. Kapitany, W. Kunkel, D. Lara, T. Lawson, S. Legtchenko, F. Liu, **X. Liu**, B. Magalhaes, S. Nowozin, H. Overweg, A. Rowstron, M. Sakakura, N. Schreiner, A. Smith, O. Snowdon, I. Stefanovici, D. Sweeney, G. Verkes, P. Wainman, C. Whittaker, P. W. Berenguer, H. Williams, T. Winkler, S. Winzeck, R. Black, B. Canakci, D. Cletheroe, Z. Feng, "[Laser writing in glass for dense, fast and efficient archival data storage](https://www.nature.com/articles/s41586-025-10042-w)", *Nature* 650, 606–612, 2026.
3. **X. Liu**, P. Pascual Cobo and R. Venkataramanan, "[Many-user multiple access with random user activity: achievability bounds and efficient schemes](https://ieeexplore.ieee.org/document/11206438)", *IEEE Transactions on Information Theory*, vol. 72, no. 1, pp. 383-414, Jan. 2026, doi: 10.1109/TIT.2025.3622969. ([conference version](https://ieeexplore.ieee.org/abstract/document/10619669), [talk](RA_isit2024(17mins).pdf), [poster](ESIT_GMAC_poster_final.pdf))
4. **X. Liu**, K. Hsieh and R. Venkataramanan, "[Coded many-user multiple access via Approximate Messsage Passing](https://arxiv.org/abs/2402.05625)", to appear in *Information Theory, Probability and Statistical Learning: A Festschrift in Honor of Andrew Barron*, 2025. ([conference version](https://ieeexplore.ieee.org/abstract/document/10619478), [talk](CDMA_isit2024(17mins).pdf))
5. **X. Liu**, "[Message Passing Algorithms for Statistical Estimation and Communication](https://doi.org/10.17863/CAM.112616)", PhD thesis, Apollo-University of Cambridge Repository, 2024.
6. G. Arpino, **X. Liu**, J. Gontarek and R. Venkataramanan, "[Inferring Change Points in High-Dimensional Regression via Approximate Message Passing](https://arxiv.org/abs/2404.07864)", *Journal of Machine Learning Research*, 26(225), pp.1-49, 2025.
7. G. Arpino, **X. Liu** and R. Venkataramanan, "[Inferring Change Points in High-Dimensional Linear Regression via Approximate Message Passing](https://proceedings.mlr.press/v235/arpino24a.html)", *Proceedings of the 41st International Conference on Machine Learning*, PMLR 235:1841-1864, 2024. ([talk](changepoint_ICML_slides.pdf), [poster](changepoints_poster.pdf), [code](https://github.com/gabrielarpino/AMP_chgpt_lin_reg))
8. **X. Liu** and R. Venkataramanan, "[Sketching Sparse Low-Rank Matrices With Near-Optimal Sample- and Time-Complexity Using Message Passing](https://ieeexplore.ieee.org/document/10120641)", *IEEE Transactions on Information Theory*, vol. 69, no. 9, pp. 6071-6097, Sept. 2023, doi: 10.1109/TIT.2023.3273181. ([conference version](https://ieeexplore.ieee.org/document/9834693)) 

## Selected talks:

1. "Bayes-Assisted Confidence Sequences for CDFs", *Safe Anytime-Valid Inference (SAVI) Conference*, University of Twente, July 2026.
2. "Mind the U Curve: Why We Stop Gradient Descent Early", *Meet Our Group Seminar Series*, Department of Statistics, University of Oxford, May 2026.
3. ["Learning Under Non-Stationarity: Statistical Inference & Bandit Convex Optimization"](warwick_stats_seminar_final.pdf), *Warwick Algorithms and Computationally Intensive Inference Seminar*, Department of Statistics, University of Warwick, March 2026.
4. "A Friendly Talk on Bandit Convex Optimization in Changing Environments", *Oxford Young Statisticians Seminar*, Department of Statistics, University of Oxford, March 2026.
5. ["Tight Confidence Sequences From Universal Portfolio"](Reading_group_talk_on_universal_portfolio.pdf), *Hypothesis Testing with E-values Reading Group*, Department of Statistics, University of Oxford, March 2026.
6. ["Tutorial on Sequential Anytime-Valid Inference Using E-processes"](SAVI_tutorial_shirley.pdf), *Statistics in AI CDT Module*, Department of Statistics, University of Oxford, November 2025.
7. ["Sequential Anytime-Valid Inference Using E-processes"](Ramdas_Wang_ebook_chapter7-2.pdf), *Hypothesis Testing with E-values Reading Group*, Department of Statistics, University of Oxford, October 2025.)
8. ["Loss landscapes and optimizaton in over-parameterized non-linear systems and neural networks"](learning_theory_reading_group.pdf), *Learning Theory and Statistical Optimization Reading Group*, Department of Statistics, University of Oxford, November 2024.
9. ["Communication over many-user channels via Approximate Message Passing"](IT_seminar_GMAC_220524_github.pdf), *Information Theory Seminar*, Department of Mathematics, University of Cambridge, May 2024.

## Service:
I review papers for several conferences and journals including the Conference on Neural Information Processing Systems (NeurIPS) (top reviewer 2024), International Conference on Machine Learning (ICML), Transactions on Machine Learning Research (TMLR), and International Symposium on Information Theory (ISIT).
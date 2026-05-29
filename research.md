<h1 style="font-size:30px">Research</h1>

My research develops <span style="color:darkred">statistical and information-theoretic foundations</span> for machine learning, with a particular focus on learning under <span style="color:darkred">data heterogeneity</span> as real-world datasets often vary across geographic locations, time periods, and user populations. I believe that as empirical advances in machine learning continue to outpace our theoretical understanding, characterising fundamental limits for learning problems and designing principled algorithms with provable guarantees becomes increasingly important, both for building more effective systems and for understanding when and why existing ones work. 

My current work spans three directions. 

- I study <span style="color:darkred">training dynamics</span> of canonical models, including shallow neural networks and linear classifiers, with a focus on phenomena such as early stopping, benign overfitting, and feature learning that shed light on the behaviour of large-scale systems. 

- I design algorithms with rigorous guarantees for <span style="color:darkred">sequential decision-making</span> including bandits and adaptive inference. 

- I work on <span style="color:darkred">uncertainty quantification</span> using distribution-free and assumption-lean tools such as e-values, conformal prediction, and prediction-powered inference.

During my PhD, I focused on <span style="color:darkred">message passing algorithms</span> for high-dimensional statistical estimation: a family of computationally efficient, iterative methods that provably achieve statistical optimality across a range of problems. I applied these to changepoint detection in heterogeneous data, sketching of sparse low-rank matrices, and reliable communication for large user networks.

## Interests:
- Training dynamics: early stopping, benign overfitting, feature learning. 
- First-order optimisation methods: gradient descent, approximate message passing
- Sequential decision-making: bandits, online learning, adaptive inference
- Uncertainty quantification: e-values, conformal prediction, prediction-powered inference
- Information theory and communication systems

## Preprints:

**X. Liu**, K. Hsieh and R. Venkataramanan, "[Coded many-user multiple access via Approximate Messsage Passing](https://arxiv.org/abs/2402.05625)", to appear in *Information Theory, Probability and Statistical Learning: A Festschrift in Honor of Andrew Barron*, 2025. ([conference version](https://ieeexplore.ieee.org/abstract/document/10619478), [talk](CDMA_isit2024(17mins).pdf))

## Publications:

J. Allison, P. Anderson, E. Aranas, Y. Assaf, M. Caballero, J. Chattaway, A Chatzieleftheriou, J. Clegg, B. Cooper, T. Deegan, A. Donnelly, R. Drevinskas, C. Gkantsidis, A. G. Diaz, I. Haller, F. Hong, T. Ilieva, R. Joyce, V. Kapitany, W. Kunkel, D. Lara, T. Lawson, S. Legtchenko, F. Liu, **X. Liu**, B. Magalhaes, S. Nowozin, H. Overweg, A. Rowstron, M. Sakakura, N. Schreiner, A. Smith, O. Snowdon, I. Stefanovici, D. Sweeney, G. Verkes, P. Wainman, C. Whittaker, P. W. Berenguer, H. Williams, T. Winkler, S. Winzeck, R. Black, B. Canakci, D. Cletheroe, Z. Feng, "[Laser writing in glass for dense, fast and efficient archival data storage](https://www.nature.com/articles/s41586-025-10042-w)", *Nature* 650, 606–612, 2026.

**X. Liu**, D. Baudry, J. Zimmert, P. Rebeschini, A. Akhavan, "[Non-stationary Bandit Convex Optimization: A Comprehensive Study](https://arxiv.org/abs/2506.02980)", *Proceedings of the 39th Annual Conference on Neural Information Processing Systems*, 2025. ([poster](neurips_poster_bandits.pdf), [talk](CDT_bandits_talk(20mins).pdf))

G. Arpino, **X. Liu**, J. Gontarek and R. Venkataramanan, "[Inferring Change Points in High-Dimensional Regression via Approximate Message Passing](https://arxiv.org/abs/2404.07864)", *Journal of Machine Learning Research*, 26(225), pp.1-49, 2025.

**X. Liu**, P. Pascual Cobo and R. Venkataramanan, "[Many-user multiple access with random user activity: achievability bounds and efficient schemes](https://ieeexplore.ieee.org/document/11206438)", *IEEE Transactions on Information Theory*, vol. 72, no. 1, pp. 383-414, Jan. 2026, doi: 10.1109/TIT.2025.3622969. ([conference version](https://ieeexplore.ieee.org/abstract/document/10619669), [poster](ESIT_GMAC_poster_final.pdf), [talk](RA_isit2024(17mins).pdf))

G. Arpino, **X. Liu** and R. Venkataramanan, "[Inferring Change Points in High-Dimensional Linear Regression via Approximate Message Passing](https://proceedings.mlr.press/v235/arpino24a.html)", *Proceedings of the 41st International Conference on Machine Learning*, PMLR 235:1841-1864, 2024. ([poster](changepoints_poster.pdf), [code](https://github.com/gabrielarpino/AMP_chgpt_lin_reg))

**X. Liu** and R. Venkataramanan, "[Sketching Sparse Low-Rank Matrices With Near-Optimal Sample- and Time-Complexity Using Message Passing](https://ieeexplore.ieee.org/document/10120641)", *IEEE Transactions on Information Theory*, vol. 69, no. 9, pp. 6071-6097, Sept. 2023, doi: 10.1109/TIT.2023.3273181. ([conference version](https://ieeexplore.ieee.org/document/9834693), <a href="/ISIT_talk_Shirley_Liu_website_version.pdf">talk</a>) 

## PhD thesis:
**X. Liu**, "[Message Passing Algorithms for Statistical Estimation and Communication](https://doi.org/10.17863/CAM.112616)", Apollo-University of Cambridge Repository.

## Service:
I review papers for several conferences and journals including the Conference on Neural Information Processing Systems (NeurIPS) (top reviewer 2024), International Conference on Machine Learning (ICML), Transactions on Machine Learning Research (TMLR), and International Symposium on Information Theory (ISIT).

## Talks:

"Mind the U Curve: Why We Stop Gradient Descent Early", *Meet Our Group Seminar Series*, Department of Statistics, University of Oxford, May 2026.

["Learning Under Non-Stationarity: Statistical Inference & Bandit Convex Optimization"](warwick_stats_seminar_final.pdf), *Warwick Algorithms and Computationally Intensive Inference Seminar*, Department of Statistics, University of Warwick, March 2026.

"A Friendly Talk on Bandit Convex Optimization in Changing Environments", *Oxford Young Statisticians Seminar*, Department of Statistics, University of Oxford, March 2026.

["Tight Confidence Sequences From Universal Portfolio"](Reading_group_talk_on_universal_portfolio.pdf), *Hypothesis Testing with E-values Reading Group*, Department of Statistics, University of Oxford, March 2026.

["Tutorial on Sequential Anytime-Valid Inference Using E-processes"](SAVI_tutorial_shirley.pdf), *Statistics in AI CDT Module*, Department of Statistics, University of Oxford, November 2025.

["Sequential Anytime-Valid Inference Using E-processes"](Ramdas_Wang_ebook_chapter7-2.pdf), *Hypothesis Testing with E-values Reading Group*, Department of Statistics, University of Oxford, October 2025. ([Reference](https://arxiv.org/abs/2410.23614).)

["Loss landscapes and optimizaton in over-parameterized non-linear systems and neural networks"](learning_theory_reading_group.pdf), *Learning Theory and Statistical Optimization Reading Group*, Department of Statistics, University of Oxford, November 2024.

["Communication over many-user channels via Approximate Message Passing"](IT_seminar_GMAC_220524_github.pdf), *Information Theory Seminar*, Department of Mathematics, University of Cambridge, May 2024.
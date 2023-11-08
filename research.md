<h1 style="font-size:30px">Research</h1>

My research focus lies in [**information theory**](https://en.wikipedia.org/wiki/Information_theory), [**coding theory**](https://en.wikipedia.org/wiki/Coding_theory#:~:text=Coding%20theory%20is%20the%20study,data%20transmission%20and%20data%20storage.), and [**statistical learning**](https://en.wikipedia.org/wiki/Statistical_learning_theory). 
Specifically, I am interested in applying tools from information theory and coding theory to (high-dimensional) statistical inference problems such as  compressed sensing, low-rank matrix estimation, changepoints detection and communications in large user networks. 
An emphasis of my research has been to develop fast  algorithms for these inference problems, and provide mathematical guarantees on their performance (in terms of certain error metrics, or memory and time complexties). 

I've been particularly interested in studying **message passing algorithms** for the inference problems mentioned above. There, we represent the statistical relationships between variables in the problem by a sparse or dense factor graph; the algorithm then iteratively updates estimates of the variables by passing messages along the graph edges. (Chapter 2 of [*Modern Coding Theory*](https://www.mathematik.uni-muenchen.de/~kpanagio/ModernCodingTheory/mct-new.pdf) contains a nice  introduction to   message passing.)

I review papers for International Symposium on Information Theory (ISIT) and International Symposium on Topics in Coding (ISTC).

## Key words:
- Message passing algorithms, [Approximate Message Passing (AMP)](https://ieeexplore.ieee.org/document/9785928)
- Compressed sensing / sparse recovery
- Combinatorial analysis (e.g. [Wormald's differential equation method](https://projecteuclid.org/journals/annals-of-applied-probability/volume-5/issue-4/Differential-Equations-for-Random-Processes-and-Random-Graphs/10.1214/aoap/1177004612.full))
- Many-user communications
- Bayesian changepoint detection
- Information-theoretic proofs of achievability and converse

## Publications:
X. Liu and R. Venkataramanan, "[Sketching Sparse Low-Rank Matrices With Near-Optimal Sample- and Time-Complexity Using Message Passing](https://ieeexplore.ieee.org/document/10120641)," in *IEEE Transactions on Information Theory*, vol. 69, no. 9, pp. 6071-6097, Sept. 2023, doi: 10.1109/TIT.2023.3273181.

X. Liu and R. Venkataramanan, "[Sketching sparse low-rank matrices with near-optimal sample- and time-complexity](https://ieeexplore.ieee.org/document/9834693)," *2022 IEEE International Symposium on Information Theory (ISIT)*, Espoo, Finland, 2022, pp. 3138-3143, doi: 10.1109/ISIT50566.2022.9834693. (<a href="/ISIT_talk_Shirley_Liu_website_version.pdf">presentation slides</a>)

The two papers above consider nxn matrices with singular vectors each containing at most k ![\ll](https://latex.codecogs.com/svg.latex?\ll) n non-zero entries.  In this paper, we proposed an algorithm based on coding theory and message passing that  can recover a sparse, low-rank matrix with O(k<sup>2</sup>) sample complexity and O(k<sup>3</sup>) runtime instead of the O(polylog(n)) and O(poly(n)) required by most existing state-of-the-art algorithms.  


## In preparation: 
The progress curve of my PhD has been highly super-linear, with a substantial amount of my recent work still in the write-up stage. I've been concurrently working on the following preprints which hopefully will appear on arXiv around the end of 2023/ beginning of 2024.

X. Liu, P. Cobo, K. Hsieh and R. Venkataramanan (2023) Massive multiple access with random user activity and coding ([poster](ESIT_GMAC_poster_final.pdf) at [IEEE European School of Information Theory 2023 (ESIT)](https://www.bristol.ac.uk/maths/events/2023/esit-2023.html))

The article above considers communications over **Gaussian Multiple Access Channels (GMAC)** with **random user activity**, where users are active in a sporadic and uncoordinated manner. This is particularly pertinent to Internet of Things (IoT) and machine-type communications. We propose an efficient coding scheme based on random linear models with Approximate Message Passing (AMP) decoding, and derive theoretical achievability and converse bounds to compare with our devised practical scheme. 

G, Arpino, X. Liu and R. Venkataramanan (2023) Changepoints detection in high-dimensional linear regression 

The article above studies an important branch of **sequential analysis**: **changepoint detection**, where the goal is to detect changes in the state
of a phenomenon (e.g. detection of deterioration in quality of the output from a continuous production process). We propose an efficient Bayesian algorithm for this task and demonstrate its versatility in integrating signal priors and number of changepoints over existing state-of-the-art methods. 

X. Liu and R. Venkataramanan (2023) On generalising Wormald's differential equation theorem

The above is an exciting work where we generalise the celebrated **Wormald's differential equation theorem** for characterising **discrete random processes** with higher rates of change. The extended method can be used to analyse a variety of randomised combinatorial algorithms,
including the widely used message passing algorithms. We demonstrate the utility of the theorem through examples.






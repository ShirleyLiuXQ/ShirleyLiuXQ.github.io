<h1 style="font-size:30px">Research</h1>

My research focus lies in [**information theory**](https://en.wikipedia.org/wiki/Information_theory), [**coding theory**](https://en.wikipedia.org/wiki/Coding_theory#:~:text=Coding%20theory%20is%20the%20study,data%20transmission%20and%20data%20storage.), and [**statistical learning**](https://en.wikipedia.org/wiki/Statistical_learning_theory). 
Specifically, I am interested in applying tools from information theory and coding theory to (high-dimensional) statistical inference problems such as  compressed sensing, low-rank matrix estimation, and communication across multiple access channels. 
An emphasis of my research has been to develop fast  algorithms for these inference problems, and provide mathematical guarantees on their performance (in terms of certain error metrics, or memory and time complexties). 

I've been particularly interested in studying **message passing algorithms** for the inference problems mentioned above. There, we represent the statistical relationships between variables in the problem by a sparse or dense factor graph; the algorithm then iteratively updates estimates of the variables by passing messages along the graph edges. (Chapter 2 of [*Modern Coding Theory*](https://www.mathematik.uni-muenchen.de/~kpanagio/ModernCodingTheory/mct-new.pdf) contains a nice  introduction to   message passing.)



## Key words:
- Low density parity check (LDPC) codes/ sparse graph codes
- Message passing algorithms (on sparse or dense graphs; Approximate Message Passing)
- Compressed sensing/ sparse recovery
- Combinatorial analysis
- Multiple access channels

## Publication:
Our recent paper titled **"Sketching sparse low-rank matrices with near-optimal sample- and time-complexity"** [(arXiv:2205.06228)](https://arxiv.org/abs/2205.06228) was accepted to appear in [IEEE Transactions on Information Theory](https://ieeexplore.ieee.org/xpl/aboutJournal.jsp?punumber=18). Consider n-by-n matrices with singular vectors each containing at most k ![\ll](https://latex.codecogs.com/svg.latex?\ll) n non-zero entries.  In this paper, we proposed an algorithm based on coding theory and message passing that  can recover a sparse, low-rank matrix with O(k<sup>2</sup>) sample complexity and O(k<sup>3</sup>) runtime instead of the O(polylog(n)) and O(poly(n)) required by most existing state-of-the-art algorithms.  The shorter version of this paper has been presented at [2022 IEEE International Symposium on Information Theory (ISIT)](https://www.isit2022.org/). Here are <a href="/ISIT_talk_Shirley_Liu_website_version.pdf">my slides</a>.


<img src="stage_A_graph.png" 
width="180" height=auto ALIGN="left">
Bipartite graphs like the one on the left are used to illustrate and analyse our proposed message passing algorithm. 

<img src="nl_runtime_rank3_sym_disjoint.jpg" 
width="220" height=auto ALIGN="right">

The figure on the right is excerpted from the paper, which plots the runtime of the algorithm in simulations against the ambient dimension n of the matrix, for different sparsity levels k. As we can see, the runtime only scales with k and is independent from n. More details including a rigorous proof of this result can be found in the paper.



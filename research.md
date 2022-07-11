<h1 style="font-size:30px">Research</h1>

My research focus lies in **information theory**, **coding theory**, and **statistical learning**. 
Specifically, I am interested in applying tools from information theory and coding theory to (high-dimensional) inference problems such as  compressed sensing, low-rank matrix estimation, and communication across multiple access channels. 
An emphasis of my research has been to develop fast  algorithms for these inference problems, and provide mathematical guarantees on their performance (in terms of memory and time complexties). 

I've been particularly interested in studying **message passing algorithms**, which are a class of algorithms designed for statistical inference on models based on sparse or dense factor graphs. In such models, the statistical relationships between variables are represented by a factor graph. The message passing algorithm iteratively updates estimates of the variables by passing messages along the graph edges.

## Key words:
- Low density parity check (LDPC) codes/ sparse graph codes
- Message passing algorithms (on sparse or dense graphs)
- Compressed sensing/ sparse recovery
- Combinatorial analysis
- Multiple access channels

Our recent paper is titled "Sketching sparse low-rank matrices with near-optimal sample- and time-complexity" [(arXiv preprint)](https://arxiv.org/abs/2205.06228). In this paper, we proposed an algorithm based on coding theory that (under certain assumptions) can recover a sparse, low-rank matrix with sublinear sample complexity and runtime instead of the logarithmic sample complexity and polynomial runtime required by most existing state-of-the-art algorithms.  The shorter version of this paper has been presented at [2022 IEEE International Symposium on Information Theory (ISIT)](https://www.isit2022.org/). Here are <a href="/ISIT_talk_Shirley_Liu_website_version.pdf">my slides</a>.


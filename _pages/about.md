---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a postdoctoral researcher at the School of Management, University of Science and Technology of China. My research interest includes financial econometrics, asset pricing, high-dimensional statistical inference, risk management, and artificial intelligence. I received my Ph.D. from the University of Science and Technology of China in 2023, under the supervision of Professors Yaohua Wu (deceased) and [Wuyi Ye](https://bs.ustc.edu.cn/chinese/profile-86.html).

My research focuses on developing statistical methods for application in financial data and developing generative AI algorithms (diffusion models and reinforcement learning) for application in finance and management. My work is divided into three streams: big data issues in empirical asset pricing, missing data in high-dimensional datasets, and causal inference, along with diffusion model applications for data augmentation.

My work has been appeared in the European Journal of Operational Research, Journal of Futures Markets, and International Review of Financial Analysis. Moreover, I have multiple manuscripts under revision at journals such as Journal of the American Statistical Association, Management Science, Journal of Banking and Finance, and Quantitative Finance.

Research Interest
======
My research interests include:
- Financial Econometrics: **High-Frequency Analysis**; Factor Model; Quantile Analysis; **Discrete Choice Model**; 
- High-Dimensional Statistics: **Dimension Reduction (PCA)**; Matrix Completion; High-Dimensional Non-Stationary Data Analysis.
- Finance: **Empirical Asset Pricing**; Portfolio Allocation; Systemic Risk; Jump Risk; **Intra-Horizon Risk**; Financial Derivatives Pricing.
- Artificial Intelligence: **Diffusion Model**; Flow Matching; Transfer Learning; Supervised/Unsupervised Learning.

Selected Publications
======
1. **Wu B**, Chen P, Ye W*. Variance swaps with mean reversion and multi-factor variance. **European Journal of Operational Research**, 2024, 315(1): 191-212. [[pdf](https://www.sciencedirect.com/science/article/pii/S0377221723009451)]
1. Ye W, Zhou Y, Chen P, **Wu B**. A simulation-based method for estimating systemic risk measures. **European Journal of Operational Research**, 2024, 313(1): 312-324. [[pdf](https://www.sciencedirect.com/science/article/pii/S0377221723006616)]
1. **Wu B**, Chen P, Ye W*. Jump activity analysis of the equity index and the corresponding volatility: Evidence from the Chinese market. **Journal of Futures Markets**, 2021, 41(7): 1055-1073. [[pdf](https://onlinelibrary.wiley.com/doi/full/10.1002/fut.22209)]
1. Ye W, **Wu B**, Chen P*. Pricing VIX derivatives using a stochastic volatility model with a flexible jump structure. **Probability in the Engineering and Informational Sciences**, 2023, 31(7): 245-274. [[pdf](https://www.cambridge.org/core/journals/probability-in-the-engineering-and-informational-sciences/article/pricing-vix-derivatives-using-a-stochastic-volatility-model-with-a-flexible-jump-structure/6C4C46FE4B9703FF790CB351D2E909C2)]
1. Ye W, Xia W, **Wu B***, Chen P*. Using implied volatility jumps for realized volatility forecasting: Evidence from the Chinese market. **International Review of Financial Analysis**, 2022, 83: 102277. [[pdf](https://www.sciencedirect.com/science/article/pii/S1057521922002320)]

**Note:** denote the corresponding author

Working Papers
------
1. Kong X, **Wu B***, Ye W. Staleness Factors and Volatility Estimation at High Frequencies. **Journal of the American Statistical Association**, major revision required. [[arXiv:2410.07607](https://arxiv.org/pdf/2410.07607)]
1. Kong X, Liu C, **Wu B***. Data Synchronization at High Frequencies. **Management Science**, under review. [[arXiv:2507.12220](https://arxiv.org/pdf/2507.12220)]
1. Kong X, **Wu B***, Ye W. High-Dimensional Binary Variates: Maximum Likelihood Estimation with Nonstationary Covariates and Factors. **Journal of Econometrics**, under review. [[arXiv:2505.22417](https://arxiv.org/pdf/2505.22417)]
1. Xia W, Ye W, **Wu B***, Zhou Y. Option-implied systemic risk measures. **Journal of Banking and Finance**, major revision required.
1. Xia W, Ye W, **Wu B***. Quadratic diffusion or time-varying jump for VIX term structure? **Quantitative Finance**, minor revision required.
1. Ye W, Yun Y, **Wu B***. The Information Content of Volatility Factors. **International Journal of Forecasting**, under review.
1. Chen P, Song Y*, **Wu B**, Ye W. Intra-Horizon Risk: The Role of Stochastic Volatility.
1. Cao C, Chen P, **Wu B***. How to Invest and When to Adjust: A Real Options Model for Cybersecurity Investment Decisions.

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

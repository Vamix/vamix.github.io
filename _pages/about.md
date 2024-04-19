---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


My name is Guodong Liu, I am currently a Ph.D. candidate in the [Institute of Computing Technology (ICT)](http://english.ict.cas.cn), [Chinese Academy of Sciences (CAS)](http://english.cas.cn),  supervised by [Prof. Yungang Bao](http://acs.ict.ac.cn/baoyg/) and [Prof. Sa Wang](https://sooner.github.io). I received my bachelor degree in Computer Science from [University of Chinese Academy of Sciences (UCAS)](http://english.ucas.ac.cn) in 2019. My full CV is available here: [**[CV]**](/files/guodong_liu.pdf)

My research interest lies in the intersection of machine learning and systems. This website is for posting some of my surveys and thoughts on recent research. If you are interested on similar topics, please contact me and have a talk. 

<span style="color:green; font-style:italic">I am on the job market for 2025. Please feel free to reach out if you have openings.</span>  

## Selected Research

**Aceso: Efficient Parallel DNN Training through Iterative Bottleneck Alleviation**  
**Guodong Liu**, Youshan Miao, Zhiqi Lin, Xiaoxiang Shi, Saeed Maleki, Fan Yang, Yungang Bao, Sa Wang  
<span style="color:green; font-style:italic">EuroSys 2024</span>  

<img src="/images/publications/aceso-overview.jpg" />

Aceso is a scalable parallel-mechanism auto-configuring system that operates iteratively. For a given parallel configuration, Aceso identifies a performance bottleneck and then, by summarizing all possible configuration adjustments with their resource consumption changes, infers their performance impacts to the bottleneck and selects one that mitigates the bottleneck. Aceso significantly reduces configuration searching cost by taking the approach of resolving one bottleneck at a time. We implemented and tested Aceso on representative DNN models. Evaluations show that it can scale to 1K-layer models. Compared to state-of-the-art systems, Aceso achieves up to 1.33x throughput improvement with less than 5% of the searching cost.

**SEER: A Time Prediction Model for CNNs from GPU Kernel's View**  
**Guodong Liu**, Sa Wang, Yungang Bao  
<span style="color:green; font-style:italic">PACT 2021</span>  

<img src="/images/publications/seer-overview.jpg"/>

SEER is an iteration time prediction model for CNNs, targeting on GPU platforms. We propose to categorize convolution kernels into three different types: Compute-bound, DRAM-bound and Under-utilized, then we build performance model for each type respectively. We combined analytical models and learning-based models to make the performance model accurate and in line with GPU execution model. Experimental results show that, our model achieves 14.71% prediction error on convolution kernels and up to 1.79% prediction error for the overall computation time in one iteration of common CNNs. Besides, when used for selecting the best convolution algorithm, our model shows 7.14% lower error rate than cuDNN's official algorithm picker.

[>> More publications](/publications/)

## Featured Article
**March 2022**: Interviewed by Microsoft Research Asia:

[![](/images/publications/interview.jpg)](https://www.msra.cn/zh-cn/news/outreach-articles/星跃重洋-刘国栋：非典型理工男在微软亚洲研究)

## Arts
**July 2022**: My painting "World on Silicon" got selected as cover of the journal ***Science Writing Review***:

<a href="https://sw.kpcswa.org.cn/Catalog/202202/covers/0F94B2022.html"><img src="/images/publications/world-on-silicon.jpg" alt="world on silicon" width="300" class="center"></a>



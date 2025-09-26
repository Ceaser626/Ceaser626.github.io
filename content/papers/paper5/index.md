---
title: "[5] Enhanced moving finite element method based on error geometric estimation for simultaneous trajectory optimization" 
#date: 2023-02-01
author: ["Y Gao, Z. Wei, Z. Shao, W. Chen, Z. Song, L.T. Biegler (2023)"]
description: "We proposed a moving finite-element method to locate the breakpoints of singular control problems and reduce non-collocation-point error." 
summary: "We proposed a moving finite-element method to locate the breakpoints of singular control problems and reduce non-collocation-point error." 
cover:
    image: "paper5.png"
    alt: "Iteration of adaptive bilevel decomposition strategy"
    relative: false
#editPost:
 #   URL: "https://doi.org/10.1073/pnas.1816454115"
 #   Text: "Other Journal Name"

---

##### Abstract

The direct method has been widely used in various fields of trajectory optimization due to the need to optimize the performance of a controlled dynamic system. An essential issue in the development of the direct method is the selection of the finite element mesh. Although there have been many pieces of research on adaptive mesh refinement, few works focused on finite element layout optimization before the refinement. This paper proposes an enhanced moving finite element method (EMFE), taking the length of each finite element as a variable, based on the geometric estimation of non-collocationpoint error (NCPE) and generalized finite element length (GFEL). The features of EMFE include flexible problem reformulation, stable numerical calculation and the ability to locate breakpoints for singular control problems (the control variables appear linearly in the problems) and finding the local minimum numerical error. The theoretical basis of the ability to locate the breakpoints for singular control problems and the feature of NCPE estimate has also been investigated. Three numerical examples, two of which are singular control problems for lunar landing and the other is a multi-phase nonlinear problem for launch vehicles, demonstrated the performance and features of the proposed EMFE method.

---

##### Iteration of adaptive bilevel decomposition strategy

![](paper5.png)


---
##### Information
**Z. Wei**, Y Gao, Z. Shao, C. Wang, “Dynamic-model-based closed-loop guidance and control for heavy parafoil system precision landing,” *Aerospace Science and Technology*, 2024. DOI: 10.1016/j.ast.2024.108964. [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S127096382400097X)


<!-- 



```BibTeX
@article{AAYY,
author = {Author 1 and Author 2},
doi = {paper_doi},
journal = {Journal},
number = {Issue},
pages = {XXX--YYY},
title ={Title},
volume = {Volume},
year = {Year}}
```

---

##### Related material

+ [Presentation slides](presentation2.pdf)
 -->

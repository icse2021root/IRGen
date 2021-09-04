# IRGen
This is a anonymous repo 



## setup

1. install the requirements for the base projects.
2. make sure that the data are put in the right dir. The default dir should be /ir_origin for files compiled with option -O0.
3. install LLVM 11.1.0. From source is better.
4. install tree-sitter from their website.
5. download the resource cutoff_stmts_pickle and dic_pickle from ncc website.
6. run ```python genetic_test.py  ```to get the result table and pictures.


## based projects


```ncc``` (Neural Code Comprehension) is a general Machine Learning technique to learn semantics from raw code in virtually any programming language. It relies on ```inst2vec```, an embedding space and graph representation of LLVM IR statements and their context. 
```tree-sitter``` search in github
```llvm```   a modern compiler framework

## special reminder

Due to the policy of production license, we are very regret that we cannot provide the exact script for graph_compare.py. 

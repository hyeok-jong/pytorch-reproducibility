# pytorch-reproducibility  
### pytorch set seed for reproducibility  

It is important that yields the same result for every single trial.  
To do so, random seed have to be fixed.  
Since pytorch builds on python, numpy etc. , just fix torch seed, one cannot get same results.  
Moreover when using single or multi GPUs, the problem extended.  
Thus some fixing works must be done first.  



## reference 

[torch docs](https://pytorch.org/docs/stable/notes/randomness.html)  
[blog (ko)](https://hoya012.github.io/blog/reproducible_pytorch/)  




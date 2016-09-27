# Homework 4
### Parallel Processing Comparison
- Serial
- Multiprocessing
- dask
- numpy (just for fun, since this will easily be the fastest for this assignment)

#### Summary
Serialization was the fastest method by far even when compared to numpy when ```N<100```, this seems to be expected due to the overhead required to setup exotic data structures and parallel processes. However with proper use and more darts numpy is by far the fastest when it is not parallelized. Some interesting behavior is seen when comparing 

![Alt Text](https://github.com/mike-a-yen/python-ay250-homeworks/raw/master/plots/darts-exectime-ci.png)

* 2.6 GHz Intel Core i7, 4 independent cores

# analyzer
AP University College research project to measure the evolvability and stability of java software.
Several measurements are calculated on a forked repository :
1/ amount of commits per class
2/ amount of times a class is referenced by another class
3/ size of the classes in lines of code
4/ amount of functions per class

These measurements are featurized and machine learning is then applied to these feature vectors. A learning model is constructed so that repositories can be gauged for their evolvability when modifications are applied.

To allow for potentially large codebases, an IPython notebook is used as front-end for a Spark instance.

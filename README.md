# Analyzer (previously normalized systems)
AP University College research project to measure the evolvability and stability of java software.
Several measurements are calculated on a forked repository :
* commit frequency. This can find the 'hotspots' in code where many changes were performed and which can be problem zones. This idea was proposed by Adam Tornhill in 'Your Code as a Crime Scene'.
* Class reference count. This metric measures the degree of coupling betweem classes by counting the references to them.
* Inheritance count. This is a measure of the coupling that exists because of inheritance.
* Lines of code. A rather crude metric that tries to measure the length of our software system.
* Number of methods. This is a measure of the complexity of the system.
* Halstead complexity measures : https://en.wikipedia.org/wiki/Halstead_complexity_measures
* Cyclomatic Complexity : https://en.wikipedia.org/wiki/Cyclomatic_complexity

Clustering is applied so that repositories can be gauged for their evolvability when modifications are applied.

To allow for potentially large codebases, an IPython notebook is used so that in the future Spark can be plugged in.

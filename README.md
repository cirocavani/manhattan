MinCost Algorithms
------------------

http://www-di.inf.puc-rio.br/~laber/OtimCombinat2014-2.htm

http://www-di.inf.puc-rio.br/~laber/Trabalho1-2014-2.pdf

O objetivo deste trabalho é implementar e analisar o desempenho
 de algoritmos para computar fluxos de custo mínimo.

Implementation:

* Cycle Canceling
* Cycle Canceling Minimum Mean Cost
* Successive Shortest Path
* Successive Shortest Path Capacity Scaling

**Julia**

http://julialang.org/

Julia is a high-level, high-performance dynamic programming language for technical computing,
with syntax that is familiar to users of other technical computing environments.

**Setup**

Dowloading data.

    julia setup.jl

**Running**

    julia -L test/graph.jl
    
    testmaxflow()
    testmaxflow8()
    testmaxflowdata()
    testmincost_cyclecanceling()
    testmincost_cyclecanceling6()
    testmincostdata_cyclecanceling()

**Notebook**

(using version 3.0)

http://ipython.org/notebook.html

https://github.com/JuliaLang/IJulia.jl

    julia -e 'Pkg.add("IJulia")'
    (...)
    ipython notebook --no-browser --notebook-dir notebook
    (...)
    http://localhost:8888/

Notebook view:

[01 - Cycle Canceling](http://nbviewer.ipython.org/github/cirocavani/puc-inf2912-t1/blob/master/notebook/01%20-%20Cycle%20Canceling.ipynb)


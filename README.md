# Monte-Carlo-integration

This repository contains the implementations of Monte Carlo integration of the function $f(x,y)=\sin{\sqrt{x^2 + y^2}}$ over the domain 

$$\Omega=\begin{cases}
      x^2 + y^2\le4\pi^2\\
      x^2 + y^2\ge\pi^2\\
    \end{cases}\.$$

More details on Monte Carlo integration technique can be found in [Monte Carlo integration](https://en.wikipedia.org/wiki/Monte_Carlo_integration).

The resulting program is written in Python inside a Jupyter Notebook ([Monte Carlo integration.ipynb](https://github.com/radubuzatu/Monte-Carlo-integration/blob/main/Monte%20Carlo%20integration.ipynb))

<h3>The following packages are used: </h3>

- numpy

- matplotlib
  
- mpl_toolkits

<h3>The surface plot of the function </h3>

<img align="center" width="60%" height="50%" src="https://github.com/radubuzatu/Monte-Carlo-integration/blob/main/img/function_surface.png">

<h3>Integration domain and distribution of inner and outer points</h3>

<img align="center" width="60%" height="50%" src="https://github.com/radubuzatu/Monte-Carlo-integration/blob/main/img/domain_points.png">

<h3>Monte Carlo integration convergence</h3>

<img align="center" width="80%" height="80%" src="https://github.com/radubuzatu/Monte-Carlo-integration/blob/main/img/convergence.png">

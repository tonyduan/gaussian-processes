### Gaussian processes in Python

Last update: February 2019.

---

Lightweight implementation of Gaussian processes [1] in Python.

At the core, a Gaussian process is a collection of jointly Gaussian random variables specified by a mean and covariance function.

<p align="center"><img src="https://rawgit.com/in	git@github.com:tonyduan/gaussian-processes/master/svgs/94c0b8af2d1d5c2f050c9d22036a4eca.svg?invert_in_darkmode" align=middle width=275.93443844999996pt height=17.031940199999998pt/></p>

Predictions are made by conditioning on a subset of variables.

<p align="center"><img src="https://rawgit.com/in	git@github.com:tonyduan/gaussian-processes/master/svgs/77b67b39f8b8d7daa8104d6075a5c7d3.svg?invert_in_darkmode" align=middle width=53.7272703pt height=16.438356pt/></p>

We implement as well a greedy selection algorithm for near-optimal sensor placement in Gaussian processes [2]. 

#### Usage

Todo.

For further details the `examples/` folder.

#### References

[1] Carl Edward Rasmussen and Christopher K. I. Williams. 2005. Gaussian Processes for Machine Learning (Adaptive Computation and Machine Learning). The MIT Press.

[2] Andreas Krause, Ajit Singh, and Carlos Guestrin. 2008. Near-Optimal Sensor Placements in Gaussian Processes: Theory, Efficient Algorithms and Empirical Studies. J. Mach. Learn. Res. 9 (June 2008), 235-284.

#### License

This library is available under the MIT License.

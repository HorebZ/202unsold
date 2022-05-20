[![GitHub contributors](https://img.shields.io/github/contributors/HorebParraud/202unsold?style=for-the-badge)](https://github.com/HorebParraud/202unsold/graphs/contributors)
[![GitHub forks](https://img.shields.io/github/forks/HorebParraud/202unsold?style=for-the-badge)](https://github.com/HorebParraud/202unsold/network)
[![GitHub stars](https://img.shields.io/github/stars/HorebParraud/202unsold?style=for-the-badge)](https://github.com/HorebParraud/202unsold/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/HorebParraud/202unsold?style=for-the-badge)](https://github.com/HorebParraud/202unsold/issues)
[![GitHub license](https://img.shields.io/github/license/HorebParraud/202unsold?style=for-the-badge)](https://github.com/HorebParraud/202unsold)
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a>
    <img src="Mathematics.png" alt="Logo">
  </a>

  <h1 align="center">202unsold</h1>

  <p align="center">
    EPITECH project - Mathematics
    <br />
    <br />
    <a href="https://github.com/HorepParraud/202unsold/issues">Report Bug</a>
    ·
    <a href="https://github.com/HorebParraud/202unsold/issues">Request Feature</a>
  </p>
</p>


<!-- IMPORTANT -->
## Important!
**If you are seeing this repository, please just ⭐ it! It will not take much time! :)**

<!-- ABOUT THE PROJECT -->
## About The Project

> This project was realized during my second year at EPITECH in 2019

To deduce from his past results the probability to sell a **$x** jacket
and **$y** trousers together. It appears that the probability is defined by the following formula *(**a** and **b** beingintegers greater than **50**, depending on the economic climate)*:

<!-- ### `((a − x) * (b − y)) / ((5a − 150) * (5b − 150))` -->
$$ (a - x) * (b - y) \over (5a - 150) * (5b - 150) $$

Let’s call `X`, `Y` and `Z`, respectively, the random variables that represent *“the price of a sold jacket”*, *“the price of sold trousers” and “the price of a sold suit”*.
Given the values of ***a*** and ***b***, your software must print:
* an array summing up the joint law of `(X, Y)`, and the marginal laws of `X` and `Y`,
* an array summing up the law of `Z`,
* expected values and variances of `X`, `Y` and `Z`.

### Built With
* Python 3.8

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Example of an expected response

```sh
∼/HorebParraud/202unsold> ./202unsold 60 70
--------------------------------------------------------------------------------
      X=10  X=20  X=30  X=40  X=50  Y law
Y=10  0.100 0.080 0.060 0.040 0.020 0.300
Y=20  0.083 0.067 0.050 0.033 0.017 0.250
Y=30  0.067 0.053 0.040 0.027 0.013 0.200
Y=40  0.050 0.040 0.030 0.020 0.010 0.150
Y=50  0.033 0.027 0.020 0.013 0.007 0.100
X law 0.333 0.267 0.200 0.133 0.067 1.000
--------------------------------------------------------------------------------
z       20      30      40      50      60      70      80      90      100
p(Z=z)  0.100   0.163   0.193   0.193   0.167   0.100   0.053   0.023   0.007
--------------------------------------------------------------------------------
expected value of X:    23.3
variance of X:          155.6
expected value of Y:    25.0
variance of Y:          175.0
expected value of Z:    48.3
variance of Z:          330.6
--------------------------------------------------------------------------------
```
<!--USEFULL LINKS-->
##
[![LinkedIn][linkedin-shield]][linkedin-url] [![GitHub][github-shield]][github-url]

<!-- MARKDOWN LINKS, ALIAS & IMAGES -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/horeb-parraud/
[github-shield]: https://img.shields.io/badge/-other_repositories-black.svg?style=for-the-badge&logo=github&colorB=555
[github-url]: https://github.com/HorebParraud?tab=repositories

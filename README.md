# tec-iDADmm
### what can it do?
tec1 MINT running a digital to analog to digital repeating loop to speed calculations, eg matrix multiplication

- integer 8x8 DAC/ADC to matrix multiply 
- 8 bytes drive 8 DACs to drive 8 bias voltages into an 8x8 transistor matrix cct (88T)
- the 88T amplifies and sums the currents to derive 8 new voltages that represent and 8x8 matrix multiplication 
- then decoded into 8 ADC to get 8 bytes 
- this accomplishes a crude 8x8 matrix multiplication using analog current/voltage/resistor network

![](https://github.com/SteveJustin1963/tec-iDADmm/blob/main/pics/1.png)

### info
In mathematics, matrix multiplication is the operation of multiplying two matrices, usually denoted by matrices A and B, to produce a third matrix C = AB. Matrix multiplication is associative, meaning that the order of matrix multiplication does not affect the result: A(BC) = (AB)C.list the steps for matrix multiplication

There is no standard order of matrix multiplication, so the steps will depend on the order in which the matrices are multiplied. However, the basic steps are to multiply each element in the first matrix by each element in the second matrix, and then add up all of the products.

The matrix derivative is a convenient notation for keeping track of partial derivatives for doing calculations. The Fréchet derivative is the standard way in the setting of functional analysis to take derivatives with respect to vectors.

Matrix integration is the process of calculating the integral of a function with respect to a matrix argument. This can be done using a variety of methods, such as the matrix exponential or the matrix logarithm.and can be used to solve problems in physics and engineering.give an example of a function that could be integrated with respect to a matrix:

The function `f(x) = x^2` could be integrated with respect to a matrix A as follows:

`f(A) = \int_0^A f(x) \, dx = \int_0^A x^2 \, dx`

This could be done using the matrix exponential, which would give

`f(A) = e^{-A} \int_0^A e^x x^2 \, dx`

or using the matrix logarithm, which would give

`f(A) = \log(A) \int_0^A \frac{1}{\log(x)} x^2 \, dx`

## Iterate

build matrix modules for the other analog fuctions

base 
- operational amplifiers
- multipliers
- potentiometers
- function generators osc

higher order
- differentiation, 
- addition
- integration with respect to time
- inversion
- multiplication
- exponentiation
- logarithm
- division
- quanta





## Ref
- https://www.youtube.com/watch?v=GVsUOuSjvcg
- https://en.wikipedia.org/wiki/Analog_computer
- https://en.wikipedia.org/wiki/Matrix_(mathematics)
- https://en.wikipedia.org/wiki/Quantum_logic
- 

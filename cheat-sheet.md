# Cheat Sheet
## Elementary functions
f | f'
-|-
$\sin(x)$ | $\cos(x)$
$\cos(x)$ | $-\sin(x)$
$\tan(x)$ | $\sec^2(x)$
$\sec(x)$ | $\sec(x)\tan(x)$
$\csc(x)$ | $-\csc(x)\cot(x)$
$\cot(x)$ | $-\csc^2(x)$
$\arcsin(x)$ | $\frac{1}{\sqrt{1-x^2}}$
$\arccos(x)$ | $\frac{-1}{\sqrt{1-x^2}}$
$\arctan(x)$ | $\frac{1}{1+x^2}$
$a^x$ | $a^x*ln(a)$
$\log_a(x)$ | $\frac{1}{x\ln(a)}$
## Trig stuff
### Trig Integrals
## Strategy for Evaluating $\int \sin^mx \cos^n x dx$
### Power of cosine is odd
$n=2k+1$, save one cosine factor and use $\cos^2(x)=1-\sin^2(x)$ to express the remaining factors in terms of sine:
$$\int\sin^m (x)\cos^{2k+1}(x)dx$$
$$=\int\sin^m (x)(\cos^2x)^k\cos(x)dx$$
$$=\int\sin^m (x)(1-\sin^2 x)^k \cos(x)dx$$
then substitute $u=\sin(x)$

### Power of sine is odd
$(m=2k+1)$ save one sine factor and use $\sin^2(x)=1-\cos^2(x)$ to express the remaining factors in terms of cosine:
$$\int\sin^{2k+1}(x)\cos^n(x)dx$$
$$=\int(\sin^2(x))^k\cos^n(x)\sin(x)dx$$
$$=\int(1-\cos^2(x))^k\cos^n(x)\sin(x)dx$$
#### Strategy for $\int\tan^m(x)\sec^n(x)dx$
##### If power of secant is even:
$(n=2x,k>=2)$ save a factor of $\sec^2(x)$ and use $\sec^2(x)=1+\tan^2(x)$ to express the remaining factors in terms of $\tan(x)$
$$\int\tan^m(x)\sec^{2k}(x)dx$$
$$=\int\tan^m(x)(\sec^2(x))^{k-1}\sec^2(x)dx$$
$$=\int\tan^m(x)(1+\tan^2(x))^{k-1}\sec^2(x)$$

##### If power of tangent is odd
$(m=2k+1)$ save a factor of $\sec(x)\tan(x)$ and use $\tan^2(x)=\sec^2(x)-1$ to express the remaining factors in terms of $\sec x$
$$\int\tan^{2k+1}(x)\sec^n(x)dx$$
$$=\int(\tan^2(x))^k\sec^{n-1}(x)\sec(x)\tan(x)dx$$
$$=\int(\sec^2(x)-1)^k\sec^{n-1}(x)\sec(x)\tan(x)dx$$
then sub $u=\sec(x)$
#### secant and tangent integrals
$\int\tan(x)dx=\ln|\sec(x)|+C$
$\int\sec(x)dx=\ln|\sec(x)+\tan(x)|+C$
### Half Angle Identities
$\sin^2(x)=\frac{1}{2}(1-\cos(2x))$
$\cos^2(x)=\frac{1}{2}(1+\cos(2x))$
$\sin(x)\cos(x)=\frac{1}{2}\sin(2x)$
### 
## Arc Length
arc length of f from a to b = $\int_a^b\sqrt{1+(f')^2}$
## Series
$r=\frac{a_2}{a_1}$
Sum of inf geo series: $\frac{a_1}{1-r}$
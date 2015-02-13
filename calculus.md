# CH1 Preparaton

### Elementary functions 

Elementary functions can represent many real world phenomena, concluded by mathematicians&scientists in 18th century.

1. Algebraic functions (polynomia, radical, rational)
2. Trigonometric functions (sine, cosine, tangent, etc.)
3. Exponential and logarithmic functions


# CH2 Limits and their properties

### Limits fail to exist
1. Different right & left behavior
2. Unbounded behavior
3. Oscillating behavior

### Calculation of limits
1. we use substitute method 
2. if f(x)=g(x) except when x=c, then limit(fx)|x->c == limit(gx)|x->c (common dividor, rationalizing)
3. squeenze theorem (f(x)=xsin(x) )

### Continuity at x = c means
1. if f(c) is defined
2. if ![\lim_{x\rightarrow c}f(x)](http://latex.codecogs.com/gif.latex?%5Clim_%7Bx%5Crightarrow%20c%7Df%28x%29)is defined
3. if ![\lim_{x\rightarrow c}f(x)](http://latex.codecogs.com/gif.latex?%5Clim_%7Bx%5Crightarrow%20c%7Df%28x%29) = f(c)

### Left&Right limits
1. the limit at a exists if and only if the left and right limit equals at a
2. the function is continuous on [a, b] if and only the function is continous on (a, b), and its left limit at b equals f(b) and its right limit at a equals f(a)

### The intermediate value theorem
if f is continous on [a, b], and k is any number between f(a) and f(b), then there is at least one number c in [a, b], such that f(x)=k


### infinite limit
1. ![\lim_{x\rightarrow c}f(x)=\infty](http://latex.codecogs.com/gif.latex?%5Clim_%7Bx%5Crightarrow%20c%7Df%28x%29%3D%5Cinfty) means for any M, there exist a delta > 0 such that if 0 <= |x-c| <= delta then f(x) > M
2. be sure to know that this mean the limit fail to exist

### Vertical Asymptote
1. Defition: if f(x) approaches infinity as x approaches c, then x=c is said to be a vertical asymptote of f(x)
2. Theorem: let g and f continous on an open interval containing c. if f(c)!=0 and g(c)=0, and there exists and open iterval containing c such that g(x) != 0 for all x in that interval, then h(x)=f(x)/g(x) has vertical asymptote at x = c.



# Deferentiation

### Tangent line with slop m
If f is defined on a open interval containing c, and if the limit ![\lim_{\Delta x\rightarrow 0}\frac{\Delta y}{\Delta x}=\frac{f(x+\Delta x)-f(x)}{\Delta x}=m](http://latex.codecogs.com/gif.latex?%5Clim_%7B%5CDelta%20x%5Crightarrow%200%7D%5Cfrac%7B%5CDelta%20y%7D%7B%5CDelta%20x%7D%3D%5Cfrac%7Bf%28x&plus;%5CDelta%20x%29-f%28x%29%7D%7B%5CDelta%20x%7D%3Dm) exists,, then the line passing through (c, f(c)) with slop m is the **tangent line** to the f at x = c.


### Derivative definition
the **derivative** of f at x is ![f'(x)=\lim_{\Delta x\rightarrow 0}\frac{f(x+\Delta x)-f(x)}{\Delta x}](http://latex.codecogs.com/gif.latex?f%27%28x%29%3D%5Clim_%7B%5CDelta%20x%5Crightarrow%200%7D%5Cfrac%7Bf%28x&plus;%5CDelta%20x%29-f%28x%29%7D%7B%5CDelta%20x%7D) provided the limits exists. For all x for which this limit exists, f' is a function of x.

### Note
1. the **process** of finding derivative of function is called **differentiation**
2. the derivative dose not cover the vertical tangent. should consider when the infinite limit exists.

### Note2 (we can infer from down to up)
1. unbound function, infinite limit
2. has one side limit
3. has 2 side limit (has limit)
4. is continous
5. is diffrentiable


### cases when continous but not differentiable
1. f(x)=|x|
2. derivative is infinite

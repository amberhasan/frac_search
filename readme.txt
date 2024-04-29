Usage: java FracSearch <prime> <power> <f-degree> <g-degree> <options>
options:
     -v     verbose output of nFPPs

Finds Fractional Permutation Polynomials in the form f(x)/g(x)

Normalization:
GCD(f(x), g(x)) = 1
f(x) and g(x) are monic
f(0) = 0, g(0) != 0
if prime does not divide the degree of g(x), second coefficient of g(x) is 0
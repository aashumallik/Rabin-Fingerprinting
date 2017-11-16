# Rabin-Fingerprinting
The Rabin fingerprinting scheme is a method for implementing fingerprints using polynomials over a finite field

Given an n-bit message m0,...,mn-1, we view it as a polynomial of degree n-1 over the finite field GF(2).

f(x)=m{0}+m{1}x+... +m{n-1}x^{n-1}} 
We then pick a random irreducible polynomial  p(x) of degree k over GF(2), and we define the fingerprint of the message m to be the remainder r(x) after division of f(x) by p(x) over GF(2) which can be viewed as a polynomial of degree k-1 or as a k-bit number.

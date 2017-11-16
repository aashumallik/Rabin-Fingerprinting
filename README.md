# Rabin-Fingerprinting
The Rabin fingerprinting scheme is a method for implementing fingerprints using polynomials over a finite field

Given an n-bit message m0,...,mn-1, we view it as a polynomial of degree n-1 over the finite field GF(2).

{\displaystyle f(x)=m_{0}+m_{1}x+\ldots +m_{n-1}x^{n-1}} f(x)=m_{0}+m_{1}x+\ldots +m_{{n-1}}x^{{n-1}}
We then pick a random irreducible polynomial {\displaystyle p(x)} p(x) of degree k over GF(2), and we define the fingerprint of the message m to be the remainder {\displaystyle r(x)} r(x) after division of {\displaystyle f(x)} f(x) by {\displaystyle p(x)} p(x) over GF(2) which can be viewed as a polynomial of degree k-1 or as a k-bit number.

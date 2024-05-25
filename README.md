# Zeta
Exploration of Rimeanns Zeta function using visualisations in OpenFrameworks(C++)
In this file, I will share my methodology and steps taken to complete this project.
I would like to acknowledge the book Music of the Primes by Marcus du Sautoy for inspiring me to explore this topic . 

## The Zeta Function ##
What is the zeta function? good question 
The zeta function is a somewhat regular-looking mathematical function denoted as 
$$\zeta(s) = \sum_{n=1}^\infty \frac{1}{n^s}$$
 s = σ + it, where σ and t are real numbers
Yet this function underlies so much of our world, deeply affecting number theory and life in all forms. 
It is the central function in the Riemann hypothesis, a conjecture that has been unable to be proved by centuries of mathematicians. 
Though given its probable truth and its use to underpin other proofs, it has earned the title of hypothesis, a rare acceptance of a non-proof in the world of number theory. 
The hypothesis says that all non-trivial zeros lie on a small strip, the critical strip; we are yet to find a zero not on this line. 
These zeroes are necessary as the values of the zeroes tell us about the error bound of the prime number theorem, which tells us about the number of primes below a given number.
Though that will not be the central focus of this project, I plan to extend it to explore prime Numbers in the future.


### Riemann–Siegel formula ###

### Dirichlet Function ###

## Plotting The Zeta Function ##
Due to the complex nature of the zeta function, there are many ways in which plotting it can be considered. However, we will begin by plotting the zeta function around the critical strip. A) Because it is notably beautiful here and B) this area of the function os of the most significant interest due to its relation to the Riemann Hypothesis. As an example of the end goal see the below from: https://mathworld.wolfram.com/RiemannZetaFunction.html 
<img width="960" alt="Screenshot 2024-05-26 at 00 03 18" src="https://github.com/Lambxx/Zeta/assets/71773712/98ba5ca3-1990-421f-90dd-20efff2d7057">
The plot above shows the real and imaginary parts of zeta(1/2+iy) (i.e., values of zeta(z) along the critical line) as y is varied from 0 to 35 (Derbyshire 2004, p. 221).
However, as we are using the openFrameworks Libary, we will be able to see this dynamically. 

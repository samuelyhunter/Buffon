# Buffon

My second side project as I get a better handle on Python:

Buffon's Needle Problem poses the following question: A needle is randomly dropped on a floor made up of evenly spaced floorboards. Determine the probability that the needle lands on a line separating floorboards. Either through some clever integration, or geometric intuition, it can be shown that this probability is directly related to pi. In the special case of the floorboards being twice as wide as the length of the needles, the probability is simply 1/pi.\
Thus, a simulation of Buffon's Needle Problem can be used (although quite inefficiently) as a Monte Carlo method for approximating pi.

To adjust the parameters of the simulation, simply modify the global constants at the top of the python file.\
I've only run the program up to 10,000 needles before my laptop started to freeze up, although after a certain point the approximated value of pi doesn't converge much at all; the error falls into a cycle of growth and reduction.

I first came across this problem in [How Not to Be Wrong: The Power of Mathematical Thinking, by Jordan Ellenberg](https://sergeyvalexeev.files.wordpress.com/2017/12/ellenberg_how_not_to_be_wrong_the_power_of_mathema.pdf).\
I may write programs to simulate questions from another fascinating book, [Fifty Challenging Problems in Probability with Solutions, by Frederick Mosteller](https://mbapreponline.files.wordpress.com/2013/07/fifty_challenging_problems_in__2.pdf).

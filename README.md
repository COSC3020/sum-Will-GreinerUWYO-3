# Sums

The program to compute the sum of a list of numbers in `code.js` is incorrect
(and the tests in `code.test.js` are failing). Correct the code such that it
passes the tests.

Sources used:
I was confused on what to do so I asked fellow student in this course Daniel Collins for a vague hint to put me on the right track. He told me that the solution was in deleting, not necessarily adding.

After a few tries of adding things to fix the code, I realized that the problem came from the way the for loop was constructed. So there were two options, either set sum to 0 initially, or start the for loop at i = 1. I decided to choose the former and set var sum = 0 instead of var sum = a[0]. This passed the checks.

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.

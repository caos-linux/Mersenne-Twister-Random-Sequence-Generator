# Mersenne Twister Random Sequence Generator
The form in random.html allows you to generate randomized sequences of integers by mean of a Mersenne Twister implementation in javascript. It lets you specify a seed value. 

The sequence does not contain duplicates (the numbers are like raffle tickets drawn from a hat).

The seed allows you to replay a given sequence of numbers at a later stage, and allows multiple parties in different locations to get the same numbers in a predictable fashion.

This generator is based on  banksean javascript Mersenne Twister implementation https://gist.github.com/banksean/300494 .

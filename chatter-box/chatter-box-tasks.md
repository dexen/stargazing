# Chatter Box
> aka much ado about nonsense

### Not really
- program that outputs a variable, pseudo-random uint

### Yes really
- program that outputs a variable, random uint

### Not quite
- program that takes exactly one argument, uint
- outputs a pseudo-random uint
- uses the argument number to initialize the pseudo-random number generator
- so that for the same argument, the same output is given

### You shouldn't
- program that outputs a variable, pseudo-random uint
- using your own algorithm for generating pseudo-random numbers
- using your implementation of your algorithm

### You shouldn't, redux
- program that takes one CLI argument, an uint
- outputs a variable, pseudo-random uint
- using your own algorithm for generating pseudo-random numbers
- using your implementation of your algorithm
- using the argument to seed the pseudo-random number generator

### You shouldn't, early and often
- program that outputs about 300MB of pseudo-random uints, one per line
- using your own algorithm for generating pseudo-random numbers
- using your implementation of your algorithm
- save output to 'my-pseudo.txt'

### But why?
- program that calculates period of pseudo-random number generator
- read input data from text file, one uint per line
- read the data from 'my-pseudo.txt'

### Tell me why?
- program that estimates period of pseudo-random number generator
- read input data from text stream, one uint per line, without ability to scroll

### You shouldn't, once and for all
- program that outputs pseudo-random uints, one per line
- using your own algorithm for generating pseudo-random numbers
- using your implementation of your algorithm
- output one whole, but only one, period of the pseudo-random number generator
- write it to 'my-pseudo-once.txt'

### You should
- program that takes exactly one or two arguments
- the first argument, an uint, sets the period of pseudo-random number generator
- the second argument (if present), an uint, seeds the pseudo-random number generator
- outputs about 300MB of pseudo-random uints, one per line
- write it to 'my-pseudo-twice.txt'

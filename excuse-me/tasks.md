# Excuse Me
> aka interfacing with OS and other programs

### Argument
- program that takes exactly one command line argument
- errors out if the number of arguments is different than one
- prints the argument to stdout

### Arguments
- program that takes any number of command line arguments
- in case of no arguments, prompts & reads one line from stdin instead
- outputs the arguments or the input

### Argumentative words
- program that takes any number of command line arguments
- in case of no arguments, prompts & reads one word from stdin instead
- outputs the arguments or the input word

### Hosing
- program that takes any amount of data on stdin
- copies the data to stdout

### Doubly hosing
- program that takes any amount of data on stdin
- copies the data to stdout and stderr

### Careful now
- program that takes any amount of data on stdin
- copies the data to stdout
- stops copying upon a NUL byte on input

### Lets Roll
- program that takes any amount of UTF-16 text on stdin
- copies the text in UTF-8 to stdout

### Fishy fishy
- program that takes any amount of data on stdin
- copies the data to stdout
- displays a dot (".") on stderr for every MB of data copied

### How much is the fish
- program that takes any amount of data on stdin
- copies the data to stdout
- upon quitting displays on stderr the average MB/s

### How much are the fishes
- program that takes any amount of data on stdin
- copies the data to stdout
- upon quitting displays on stderrs the average MB/s and the peak MB/s

### This much is the fish
- program that takes one argument on command line: an uint
- absent the argument, or with wrong argument, output help & quit
- interprets the argument as maximum bandwidth, in MB/s (or kB/s, if you prefer)
- copy data from stdin to stdout, while
- enforcing the maximum bandwidth
- averaged over spans of no more than 2 seconds

### Call me maybe
- program that runs "git init"

### Call now
- program that takes any number of command line arguments
- runs "git add" with the arguments

### Can you hear me now
- program that takes any number of command line arguments
- execs "git add" with the arguments

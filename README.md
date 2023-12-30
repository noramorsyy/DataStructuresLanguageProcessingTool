# Language Processing Tool: Hapax Legomena
The project involves developing a natural language processing tool in C to identify hapax legomena (words occurring only once) in a document, showcasing proficiency in programming, data structures, and command line processing. Implemented features include word extraction, linked list manipulation, and tallying word occurrences, demonstrating practical programming skills and problem-solving abilities.

## Getting Started
clone this repository to your local machine

Ensure you have a C compiler installed on your system, and use the provided makefile for building the executable. 

##Usage
To run the program, use the following command:
```
./hapax [<options>] <datafile> [ <datafile> ...]
```

### Options

- `-d`: Print out all data loaded before printing hapax legomena.
- `-h`: Display help.
- `-l <N>`: Only print hapax legomena of length `<N>`. If not specified, all hapax legomena are printed.

### Sample Data Files

- `smalldata.txt`: Tiny text file for testing purposes.
- `jabberwocky.txt`: The famous poem from Alice in Wonderland.

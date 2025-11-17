# 42_Push_Swap

Simple implementation of the push_swap project (42 School).  
The goal is to sort integers sent as command-line arguments using a limited set of stack operations and to output a sequence of operations that sorts the list.

## Features
- Implements the push_swap algorithm to produce a sequence of operations.
- Aims to minimize the number of operations while keeping the solution readable and maintainable.
- Typical operations: sa, sb, ss, pa, pb, ra, rb, rr, rra, rrb, rrr (depending on implementation).

## Build
If a Makefile is present:
```
make
```

This should produce the push_swap binary (and optionally a checker binary if included).

## Usage
Run the program with a list of integers as arguments:
```
./push_swap 3 2 1 6 5 4
```
The program prints a sequence of operations (one per line) that, when applied to the input, results in a sorted list.

## Notes
- Input validation for duplicates / non-integer values should be handled by the program.
- Behavior and performance depend on the chosen algorithm and optimizations.

## Author
andrelencart

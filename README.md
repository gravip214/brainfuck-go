Brainfuck in go
Brainfuck compiler in Go - well not quite. A compiler outputs binaries. It's in between an interpreter and a compiler.

Intro
This is the possible implementation of a Brainfuck interpreter by any means. Nor it is the fastest.

The goal from this was to learn a bit about how interpreters and compilers work. Using Brainfuck looked to be the simplest way to achieve this.


 try this `go get github.com/gravip214/brainfuck-go`

`./BF_Interpreter -h`
Usage of ./BF_Interpreter:
  -filename string
    	Enter input file name to interpret (default "input.bf")
  -input string
    	Enter input character if required
      
To run the script

`./BF_Interpreter -filename input.bf -input m`

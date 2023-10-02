# Hello World

## Learning Goals

- Create a new Ruby file.
- Write syntactically valid code to produce "Hello World!"
- Run a Ruby file.

## Introduction

We're going to make a file that will print ["Hello
World!"](http://en.wikipedia.org/wiki/%22Hello,_World!%22_program) to your
terminal.

## Instructions

Begin by forking and cloning this repo to your local environment and open the
directory in VS Code.

### Creating a File

Start by creating a text file called `hello_world.rb` within the lab's
directory. The `.rb` file extension is a common convention for specifying the
language of the file — in this case, Ruby.

### Writing Code

In the file `hello_world.rb` that you created, you need to write a single line
of code that prints the string Hello World! to your terminal. To print in Ruby,
you need to use the method `puts` which is short for "out**put s**tring." And
because Hello World! is a string, you need to surround your text with `""`.

File: `hello_world.rb`

```ruby
puts "Hello World!"
```

Anytime you make changes to a file (like the one you've just made) you need to
save the file, so your changes are preserved. If you forget to save the file
before you run your tests, the last saved version of the file will be run
— without your changes — and this can be very confusing! In this case, if you
forget to save, what gets run might be just an empty document (which won't do
anything very exciting). Always remember to save the file every time you make
changes by selecting Save from the File menu.

### Executing Your File

Execute this file by typing `ruby hello_world.rb` into your terminal and
pressing `enter`. The `ruby` part of that command tells your computer to use the
Ruby interpreter when reading and executing the code in your file. The second
part of the command, `hello_world.rb` is the path to the file you want to run.

Reminder: be sure to save your file before trying to run it.

You should see:

```bash
$ ruby hello_world.rb
Hello World!
```

### Running the Tests

Confirm everything is working by running the `rspec` command. You should see
that all tests are passing (e.g. no red error text). Once you have the tests
passing, submit your work using CodeGrade.

## Hello World History

A small piece of coding history — a handwritten version of Hello World in C (an
early programming language).

![Hello World! Art](https://d32dm0rphc51dk.cloudfront.net/b6JQ66-0nHij79irJT-Pdg/large.jpg)

[Hello World! by Brian
Kernighan](https://www.artsy.net/artwork/brian-kernighan-hello-world), from
Artsy's Algorythm Auction. Based on a 1974 Bell Laboratories internal memorandum
by Brian Kernighan, _Programming in C: A Tutorial_, which contains the first
known version.

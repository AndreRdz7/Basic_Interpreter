# Basic Interpreter

This will be the project for my **Compilers** course, since it will be the same, to avoid plagiarism, I will only push to this repository, once deadlines have met.

# Prerequisites

- [Flex]([http://dinosaur.compilertools.net/flex/manpage.html](http://dinosaur.compilertools.net/flex/manpage.html))

If you have a **Debian-based** distro, simply install flex:

`sudo apt-get install flex
`

Otherwise (Windows), a C compiler must be installed first and Flex pagckage should be searched on SourceForge.

## Compile and run

Once in the folder where **interpreter.txt** exists:

`flex interpreter.txt`

`gcc lex.yy.c -lfl`

`./a.out text.txt`

One text file is provided for testing purposes.

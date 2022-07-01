# JLOX #

## Intro to Writing Interpreters

JLOX is a dynamically typed and interpreted language.
The JLOX interpreter is completely developed in Java following the book [*Crafting Interpreters*](https://craftinginterpreters.com/)


## Parts of an Interpreter ##

* ### Scanning
    Also known as lexical analysis. Chunks the linear stream of characters to tokens for the language.
* ### Parsing
    Similar to a grammer check for our language
* ### Static Analysis
    Processes involving binding and scoping.

* ### Middle End
    Storing the code as an intermediate representation
* ### Code Generation
    Converting the intermediate code to run on the specific architecture


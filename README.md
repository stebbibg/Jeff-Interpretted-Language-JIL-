# Current Functionality and progress
Wooo! Version 0.00000001 is done! JIL can now support arithmetic operations preserving order of operations for the four basic operators, MDAS (not the full PEMDAS yet)
VariableNames can be placed on the left hand side of an "=" operator, in order to store that variable. If the variable is stored, you can then use that variable on the right side of an "=" operator to use it in arithmetic.
## Example
### Valid ```.jil``` File at this point. 
```
 x=20+1-4/2
 y=x*2
 c = y*x
```
 
So far, white space between the operators is not 
 
### Usage
```> .\JILInterpreter.exe \PATH\TO\testJILFile.jil```
 
# Jeff-Interpreted-Language-JIL-
Development of an interpreted language for use in future projects, but mostly as a learning exercise. 

## Welcome!

What is this? I am embarking on a journey to develop a general purpose interpreted language in c++, mostly for educational purposes. I have many goals
for doing this. One goal is to just become more familiar with modern and optimized c++ and OO principles to improve my craft. Another (albeit lofty) goal
is to create a fun and engaging open-source community working to build something fun. Looking to have other contributors, and be welcoming to people who want 
to start contributing to an open source project. 

## Where to start?
This project is built using CMake. I will add in build details shortly, but I am currently developing this on both MacOS, and Windows. There will be some pains getting your build environment set up
however I will eventually put some installation and build instructions up. 

## Dev Tasks
Current Development tasks can be found [at the Trello Board](https://trello.com/b/UHF9wIE2/jil-dev)

The Discord is going to be built up as well, in hopes of boosting the community engagement. I first need to actually get contributors first! There are many opporunities for contributing, so just message me on here!


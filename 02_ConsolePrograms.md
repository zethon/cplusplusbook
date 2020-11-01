# Chapter 2

This chapter will walk through the basics of Console Programs such as:

To get started, here is the world famous "Hello World" program in C++:

```cpp
#include <iostream>

int main()
{
    std::cout << "Hello World!\n";
}
```

Ok great, wat does that mean. How do we turn this into an `.EXE` file that you can run from the command line to actually print this out? This is where **compilation** comes into the picture. We have to take the text above, save it to a text file and then compile it. 

Great, let's go!

Unfortunately it's not that straight forward. "Why the fuck not?" I can hear you screaming... because I fucking said so!

No.

It's because C is a really old language. Like really old. When C was originally written, Richard Nixon was President of the United States. When C++ was written as an *extension* of C, Ronald Reagan was President. Back then there was no real concept of standardization of something like a computer language. Apple was still in its infancy, Windows had yet to be written and cell phones were called "car phones".

* setup with CMake and Command Line
* printing output
* getting input
* ASCII Art
* NCurses (and PDCurses)

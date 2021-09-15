# Hello World
 git clone <git@github.com:CodecoolGlobal/hello-world-python-Adrenalex21.git> : [<C:\Users\Anast\OneDrive\Desktop\s
## Story

No debate that your first programming exercise must be a [Hello, World!](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program) implementation. However, we don't want to bore you - let's be bold and and make your "Hello, World!" shine!

!> This is a **guided project**, a regular project with a step-by-step guide
   (see the Background materials). To learn the most, try and implement it on
   your own first, and check the solution only when you feel your version is ready.
   However, if you feel completely stuck, feel free to check the guide for hints.

## What are you going to learn?

- Write strings to the console (that is, _printing_).
- Define and call functions.
- Use return values.
- Get user input.
- Call functions with arguments.
- Separate concerns.

## Tasks

1. Modify `helloworld.py` so that it prints out `Hello, World!` to the console. Do not write any functions yet.
    - Running `helloworld.py` prints out `Hello, World!` to the console.
    - The source code of `helloworld.py` contains no function definitions.

2. Create and call a function in `hellofunction.py` which prints `Hello, World!` to the console.
    - Running `hellofunction.py` prints out `Hello, World!` to the console.
    - The source code of `hellofunction.py` defines and calls a `say_hello()` function which is responsible for printing the `Hello, World!` message.

3. Create and call two functions in `helloreturn.py` - one should return the `Hello, World!` string to the another which prints this message to the console.
    - Running `helloreturn.py` prints out `Hello, World!` to the console.
    - The source code of `helloreturn.py` defines a `get_hello_message()` function which does not print anything but returns the `Hello, World!` message.
    - The source code of `helloreturn.py` defines and calls a `say_hello()` function which is responsible for printing the message returned by `get_hello_message()`.

4. Create and call two functions in `helloinput.py` - one should ask for the name of the user and an another which prints the custom greeting message to the console.
    - Running `helloinput.py` prints `What's your name?`, asks for user input, and using the input prints `Hello, <name>!` to the console.
    - Running `helloinput.py` asks `What's your name?`, and if the user does not enter anything, it prints `Hello, World!` to the console.
    - The source code of `helloinput.py` defines a `get_hello_message()` function which prints `What's your name?`, and returns `Hello, <name>!` using the user input (or `Hello, World!` for an empty input).
    - The source code of `helloinput.py` defines and calls a `say_hello()` function which is responsible for printing the message returned by `get_hello_message()`.

5. Capitalize the user's diplayed name in a reorganized `helloargument.py` that separates the input collection and the message assembly parts.
    - Running `helloargument.py` prints `What's your name?`, asks for user input, and using the input prints `Hello, <Name>!` to the console (`<Name>` is capitalized).
    - Running `helloargument.py` asks `What's your name?`, and if the user does not enter anything, it prints `Hello, World!` to the console.
    - The source code of `helloinput.py` defines a `get_user_name()` function which prints `What's your name?`, and returns the capitalized version of the user's input string.
    - The source code of `helloinput.py` defines a `get_hello_message(name)` function which returns `Hello, <name>!` using the incoming argument (or `Hello, World!` for an empty argument).
    - The source code of `helloinput.py` defines and calls a `say_hello()` function which is responsible for printing the message after collecting the returned values from the other two functions.

## General requirements

None

## Hints



## Background materials

- <i class="far fa-exclamation"></i> [How to approach learning Python?](project/curriculum/materials/competencies/python-basics/about-python.md.html)
- <i class="far fa-exclamation"></i> [Strings](project/curriculum/materials/competencies/python-basics/python-strings.md.html)
- <i class="far fa-exclamation"></i> [Functions](project/curriculum/materials/competencies/python-basics/python-functions.md.html)
- <i class="far fa-exclamation"></i> [A step-by-step solution guide](project/curriculum/materials/pages/python/hello-world-step-by-step-python.md) to this project


<h3 align="center">Mini Java Compiler</h3>

</div>

<!-- ABOUT THE PROJECT -->

## About The Project

A mini Java compiler , built using Flex and Yacc (also known as Lex and Bison) , is a project that involves implementing a subset of the Java language using the Flex lexical analyzer and Yacc parser generator.

<!-- GETTING STARTED -->

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

- python

  1- Update the repositories:

  ```sh
  sudo apt-get update
  ```

  2- Install Python

  ```sh
  sudo apt-get install python
  ```

- virtualenv

  1- Install virtualenv using pip

  ```sh
  pip install virtualenv
  ```

### Installation

1.  Go into the project folder
    ```sh
    cd Compilation
    ```
2.  Create a python virtual environment
    ```sh
    virtualenv compiler
    ```
3.  Start the virtual environment
    ```sh
    source compiler/bin/activate
    ```
4. Install the required libraries
    ```sh
    pip install -r requirements.txt
    ```
5. Start the flask server
    ```sh
    python -m GUI.GUI
    ```
6. Navigate to the url `http://127.0.0.1:5000`
    <p align="right">(<a href="#readme-top">back to top</a>)</p>


### Demo
<p align="center">
  <img src="demo/demo.gif" alt="animated" />
</p>

## Code generation

The structure for the each instruction:

![](code_gen/screenshots/1.png)

The method for creation of an instruction:

![](code_gen/screenshots/2.png)


The method for the insertion of an instruction into the array of code:

![](code_gen/screenshots/2.png)

### Examples:


Source code             |  Generated Code
:-------------------------:|:-------------------------:
![](code_gen/screenshots/1_code.png)  |  ![](code_gen/screenshots/1_code_gen.png)
![](code_gen/screenshots/2_code.png)  |  ![](code_gen/screenshots/2_code_gen.png)


### Demo
![](demo/code_gen.gif)


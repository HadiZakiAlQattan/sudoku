<h1 align="center">Welcome to Sudoku game 👋</h1>
<p>
  <a href="https://www.python.org/"><img alt="Python version: 3.x" src="https://img.shields.io/badge/python-python%203.x-blue.svg">
  </a>
  <a href="https://github.com/HadiZakiAlQattan/sudoku-solver/blob/master/LICENSE" target="_blank">  
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://docutils.sourceforge.io/rst.html"><img alt="Docstrings: reStructuredText" src="https://img.shields.io/badge/docstrings-reStructuredText-gree.svg">
  </a>
  <a href="https://github.com/psf/black"><img alt="Code style: black" src="https://img.shields.io/badge/code%20style-black-000000.svg">
  </a>
</p>

> GUI desktop [Sudoku game](https://en.wikipedia.org/wiki/Sudoku) using [pygame](https://www.pygame.org/wiki/GettingStarted) include [Sudoku solver](https://github.com/HadiZakiAlQattan/sudoku-solver/blob/master/src/solver/solver.py) and [random Sudoku board generator](https://github.com/HadiZakiAlQattan/sudoku-solver/blob/master/src/generator/generator.py).

# Demo ([Full demo](https://github.com/HadiZakiAlQattan/sudoku-solver/tree/master/docs/DEMO.md)) 🧮

![Normal Playing](https://github.com/HadiZakiAlQattan/sudoku-solver/tree/master/docs/gif/normal.gif)

![Wrong](https://github.com/HadiZakiAlQattan/sudoku-solver/tree/master/docs/gif/wrong.gif)

# Usage 🗝
### There's two way to use this project: 
* Without any prerequisites : 
  + download whole [executable directory](https://github.com/HadiZakiAlQattan/sudoku-solver/tree/master/executable)
  + run [executable/exe/sudoku.exe](https://github.com/HadiZakiAlQattan/sudoku-solver/tree/master/executable/exe/sudoku.exe)

* With prerequisites : 
  + clone this repo : 
    ```shell 
    $ git clone https://github.com/HadiZakiAlQattan/sudoku-solver.git
    ```
  + [install prerequisites](#prerequisites%20🔩)
  + Run src/main.py : 
    ```shell
    $ python3 main.py
    ```

# Prerequisites 🔩

* [Python 3.x](https://www.python.org/downloads/)
* Python libraries from [requirements.txt](https://github.com/HadiZakiAlQattan/sudoku-solver/blob/master/requirements.txt)
  ```shell 
  $ sudo pip3 install -r requirements.txt
  ```

# Tests 🧪

### Unit tests @ [tests directory](https://github.com/HadiZakiAlQattan/sudoku-solver/tree/master/tests) include tests only for :
* [src.solver.sovler.Solver](https://github.com/HadiZakiAlQattan/sudoku-solver/blob/master/src/solver/solver.py) class (not include auto_solver function) @ [tests/test_01_solver.py](https://github.com/HadiZakiAlQattan/sudoku-solver/blob/master/tests/test_01_solver.py) using [tests/IO.py](https://github.com/HadiZakiAlQattan/sudoku-solver/blob/master/tests/IO.py) data.
* [src.generator.generator.Generator](https://github.com/HadiZakiAlQattan/sudoku-solver/blob/master/src/generator/generator.py) class @ [tests/test_02_generator.py](https://github.com/HadiZakiAlQattan/sudoku-solver/blob/master/tests/test_02_generator.py).

### Run instructions:

* All tests :
  ``` shell
  $ pytest -v
  ```

* Specific tests :
  + only solver tests :
    ``` shell
    $ pytest -v test_01_solver.py
    ```

  + only generator tests :
    ```shell
    $ pytest -v test_02_generator.py
    ```

# Copyright ©

👤 **Hadi Zaki AlQattan**

* Github: [@HadiZakiAlQattan](https://github.com/HadiZakiAlQattan)
* Email: [alqattanhadizaki@gmail.com]()

📝 **License**

Copyright © 2020 [Hadi Zaki AlQattan](https://github.com/HadiZakiAlQattan).<br />
This project is [MIT](https://github.com/HadiZakiAlQattan/sudoku-solver/blob/master/LICENSE) licensed.

***
Give a ⭐️ if this project helped you!
# ClassStuff

Low-level C++ war zone from school.

No fancy frameworks.  
No hand-holding abstractions.  
Just structs, pointers, manual memory, bit twiddling, and occasional segfaults.

## What's inside

- `lab1/`             
- `lab2/`, `lab2b/`, `lab2/qua/`   
- `Lab3a/`, `Lab3b/`, `Lab3c/`     
- `Lab4a/`, `Lab4b/`, `Lab4c/`     — endgame boss fights
- `function/`          — probably cursed function pointer gymnastics

## Tech stack (if you can call it that)

- C++ (probably C++11/14 — whatever allowed)
- gcc / clang
- valgrind (highly recommended)
- prayer

## Build & run (example — adapt per lab)

```bash
cd Lab3b
g++ -Wall -Wextra -g -o main *.cpp
valgrind --leak-check=full ./main

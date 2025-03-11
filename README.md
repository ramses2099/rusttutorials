# rusttutorials

Rust Programming Full Course

# Rust

- A language empowering everyone to build reliable and efficient software.

# Advantages

- Speed
- Safety
- Concurrency
- Portability

# Data Types

- Memory only stores binary data

# Basic Data Types

- Boolean
- Integer
- Double / Float
- Character
- String

# Variables

# Functions

- Name, Parameter, Return Type, Body

# The println macro

- Macro expand into additional code
- println "prints" displays information to the terminal

```
# debug println
println!("{:?}", "test")
```

# Control flow

- if else

# Repetition

- Called "looping" or "iteration"
- loop

```
let mut a = 0;
    loop {
        if a == 5 {
            break;
        }
        println!("{:?}", a);
        a += 1;
    }

```

- while loop

```
let mut a = 0;
    while a != 5 {
        println!("{:?}", a);
        a += 1;
    }
```

# Comments

```
// This comment in single line.
```

# Add external library

```
cargo add [libname]
```

# Crates

- A crate is the smallest amount of code that the Rust compiler considers at a time.

# Memory Management

- Stack
- Heap

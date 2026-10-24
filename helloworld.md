### Helloworld Programs

## Hello, World!

We list below Helloworld programs for diff erent programming languages, i.e. programs that print "Hello, World!". Thespecifi ed compiler or interpreter is required for each programming languages.

The table below summarizes the programs:

| Language | Language (Spec) Site | Section | Build / RunToolchain | Debian / UbuntuPackages |
| :--- | :--- | :--- | :--- | :--- | 
| C | [ The Standard - C ](https://www.iso-9899.info/wiki/The_Standard) | [C](#c) | GCC | build-essential |
| C++ | [  The Standard - C++ ](https://isocpp.org/std/the-standard) | [C++](#c--) | GCC / G++ | build-essential, g++ |
| Dlang | [ D Programming Language:Home ](https://dlang.org/) | [Dlang](#dlang) | GCC / GDC | build-essential, gdc |
| Go | [ The Go Programming Language ](https://go.dev/) | [Go](#go) | Go | golang |
| Rust | [ Rust ](https://rust-lang.org/) | [ Programming Language ](#rust) | Rust | Rust (Crate) | rustlang |
| Java | [Java Programming Language](https://docs.oracle.com/javase/8/docs/technotes/guides/language/) | [Java](https://www.oracle.com/java/) | JDK | openjdk-17-jdk |
| x86_64 assembly | [x86 and amd64 instruction reference](https://www.felixcloutier.com/x86/) | [x86_64 Assembly](https://www.felixcloutier.com/x86/) | GCC / GAS | `build-essential |
| ARM64 assembly | [Arm A64 Instruction Set Architecture](https://support.arm.com/documentation/ddi0596/latest/) | [ARM64 Assembly](https://en.wikipedia.org/wiki/ARM_architecture) | GCC / GAS (AArch64) | build-essential |
| Bash | [Bash Reference Manual](https://www.gnu.org/software/bash/manual/bash.html) | [Bash](https://www.gnu.org/software/bash/manual/) | Bash | bash |
| Python | [Welcome to Python.org](https://www.python.org/) | [Python](https://www.python.org/) | Python | python |
| Ruby | [Ruby Programming Language](https://www.ruby-lang.org/en/) | [Ruby](https://www.ruby-lang.org/) | Ruby | ruby |
| PHP | [PHP: Hypertext Preprocessor ](https://www.php.net/) | [PHP](https://www.php.net/) | PHP | php |
| Perl | [The Perl Programming Language](https://www.perl.org/) | [Perl](#perl) | Perl | perl |
| Lua | [The Programming Language Lua](https://www.lua.org/) | [Lua](#lua) | Lua | lua |


### C

```
#include <stdio.h>

int main(void)
{
    puts("Hello, World!");
    return 0;
}
```

Build with:

```
gcc -Wall -o helloworld helloworld.c
```

Run with:

```
./helloworld
```

### C++

```
#include <iostream>

int main()
{
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```

Build with:

```
g++ -Wall -o helloworld helloworld.cpp
```

Run with:

```
./helloworld
```

### Dlang

```
import std.stdio;

void main()
{
    writeln("Hello, World!");
}
```

Build with:

```
gdc -Wall -o helloworld helloworld.d
```

Run with:

```
./helloworld
```

### Go

```
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```

Build and run with:

```
go run helloworld.go
```

### Rust

```
fn main() {
    println!("Hello, World!");
}
```

Build with:

```
rustc hello.rs
```

Run with:

```
./helloworld
```

### Java

```
public class Helloworld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

Build with:

```
javac Helloworld.java
```

Run with:

```
java Helloworld
```

### x86_64 Assembly

Build with:

```
TODO
```

Run with:

```
./helloworld
```

```
TODO
```

### ARM64 Assembly

Build with:

```
TODO
```

Run with:

```
./helloworld
```

### Bash

```
echo "Hello, World!"
```

Run with:

```
bash helloworld.sh
```

### Python

```
print("Hello, World!")
```

Run with:

```
python helloworld.py
```

### Ruby

```
puts "Hello, World!"
```

Run with:

```
ruby helloworld.rb
```

### PHP

```
<?php
echo "Hello, World!\n";
?>
```

Run with:

```
./helloworld
```

### Perl

```
print("Hello, World!\n")
```

Run with:

```
perl helloworld.pl
```

### Lua

```
print("Hello, World!")
```

Run with:

```
lua helloworld.lua
```
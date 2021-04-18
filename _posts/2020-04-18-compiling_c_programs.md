# Using g++

Here are the basics needed to compile and run a c++ program with one file. 

# Step 1: Create your file
```c
// main.cpp
#include <stdio.h>
int main(){
    printf("Hello World!\n")
    return 0;
}
```

# Step 2: Compile
The general format to compile code with g++: 

```shell
g++ -o [executable_name] [file_name]
```

In this case, we will create the executable hello from main.cpp: 

```shell
username$ g++ -o hello main.cpp
```

The **-o** flag tells g++ the name of the **outfile** will follow. 

# Step 3: Run
```shell
username$ ./hello
Hello World!
username$
```
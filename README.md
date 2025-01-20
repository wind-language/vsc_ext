# Wind Lang Syntax Highlighting

This is a syntax highlighting package for the Wind programming language. Check it out [here](https://github.com/wind-language/wind)


## Example code

```wind
@include "#types.wi"

func calculate_sum(x: int, y: int): int {
   return x + y;
}

func main() {
    branch [
        x == 0: puts("x is zero");
        else: puts("x is not zero");
    ]

    asm {
        mov eax, 10;
        add eax, 20;
    }

    return 0;
}
```
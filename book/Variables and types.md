### Variables and types
So imagine this situation: you have a small guessing game that selects a random number between 1 - 10, and you want to see if the number the user types into the console is the same as the one you generated. How would the program store the number the user has typed?

Variables, as their name say, are places that can store values to be modified later at any time.

For example, we can type...

```lua
a = 5
b = 10
print(a + b)
```

instead of...

```lua
print(5 + 10)
```

Because both will output...

```bash
15
```

Variables can be defined according to their types, which are:
- **numbers**: `0`, `1`, `3.14`, ...
- **booleans**: `true`, `false`
- **strings**: `"Hello"`, `"Hey"`, `"Sup"`, ...
- **tables**: `{ "Banana", "Apple", "Orange" }`

There are other types, of course, but I will not explain them for now since they are a little more complex.

## Some exercises:
- Add two numbers inside a variable and print it
- Multiply `a` by `b` and put it inside the variable `c`
- Merge two strings inside a variable and print it

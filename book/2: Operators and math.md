# Chapter 2: Operators and math
Let's start with some math and logic... but don't worry, it won't hurt and it's not really difficult!

## Arithmetical
These are basically, just math operations with different characters for making easier to type on a conventional keyboard.
The arithmetical operators are the following:
- `+` addition
- `-` subtraction
- `*` multiplication
- `/` division
- `%` modulo (remainder of an division)
- `^` exponentiation

But, how it would work in a real example? Let's see:

```lua
print(1 + 1)
```

```bash
2
```

As you can see, the result of 1 + 1 appeared on the console! Now let's try something more complicated:

```lua
print(3 + 2 * 2)
```

```bash
7
```

As you may have noticed, Lua follows the precedence rule when reading mathematical expressions, so `3 + 2 * 2` does not equals `10`, it equals `7`.

And what if I want it to equal to 10? We can try this:

```lua
print((3 + 2) * 2)
```

```bash
10
```

As normal mathematics, it will first solve everything inside the parenthesis to then solve the rest of the expression.

## Conditionals
We also have conditional operators, which check if a specific condition is true or false. 
They consist of the following:
- `==` ... is equal to ...
- `~=` ... is not equal to ...
- `>` ... is higher than ...
- `<` ... is smaller than ...
- `>=` ... is higher or equal to ...
- `<=` ... is smaller or equal to ...

```lua
print(1 == 1)
```

```bash
true
```

Does 1 equals to 1? Obviously, yes, so it returns true.
But what if we change it to 1 = 2?

```lua
print(1 == 2)
```

```bash
false
```

False, because, of course, 1 does not equal to 2 (and why it would? like seriously don't try to be the rule breaker here, please).

Now, let's try to make some conditions that are actually good and not just dumb talk:

```lua
print(69 < 420)
print(10 + 9 == 21)
print(6 / 2 * (1 + 2) == 9)
```

```bash
true
false
true
```

As you can see:
- 69 is smaller than 420
- 10 + 9 is not 21 :(
- 6 / 2 (1 + 2) is 9, end of the debate.

Also, notice that you can include arithmetics inside conditional operators!
## Special operators
Lua has also some very uncommon operators that you wouldn't usually find in a normal language, but this does not mean they are unuseful! 
They consist of the following:
- `#` length of ...
- `..` concatenate text ... with ...

Let's say you want to count how many characters the text `"Hi!"` has, using the `#` operator:

```lua
print(#"Hi!")
```

```bash
3
```

Now, let's say you want to write some text to accompany `3`, so we doesn't just let the little guy be sitting here alone:

```lua
print("The text has " .. #"Hi!" .. " characters.")
```

```bash
The text has 3 characters.
```

Cool huh?

### Some exercises
- Check if two conditions are both true
- Concatenate text with an arithmetical operation and print it

# Decision making
Now imagine that you want to run a piece of code if something is true, and else, run another piece of code.
This is where `if`, `elseif` and `else` comes in!

So let's take a look at a very simple example:

```lua
a = 5
if a > 0 then
  print("a is higher than 0!")
```

```bash
a is higher than 0!
```

As you can see, the text was shown because `a` is higher than 0... but what if it wasn't?
Let's try again...

```lua
a = -5
if a > 0 then
  print("a is higher than 0!")
```

```bash

```

Nothing was printed because `a` is -5 (which is, obviously, less than 0).

## Counter conditions
Now let's say that you want to print text if something is true, and another text if it's false: how could you do that?
By using `else`!

Take a look at the following example:

```lua
a = -5
if a > 0 then
  print("a is higher than 0!")
else
  print("a is lesser than 0.")
```

```bash
a is lesser than 0.
```

The second part of the statement get run because `a` is lesser than 0!

But what if we would like to print if multiple different conditions are met? You could write code in this way:

```lua
a = -5
if a > 0 then
  print("a is higher than 0!")
else
  if a == 0
    print("a is equal 0!")
  else
    print("a is lesser than 0.")
```

But *eek*, that's very ugly! We could do something way nicer using `elseif`

```lua
a = -5
if a > 0 then
  print("a is higher than 0!")
elseif a == 0
  print("a is equal 0!")
else
  print("a is lesser than 0.")
```

Way better, shall we? :D

## Some exercises
- Check if a number is between 0 and 10

[The solutions are avaliable here.](solutions/4.md)

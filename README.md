# The Monkey Programming Language

This repository contains the code I've written while going through [Writing An Interpreter in Go](https://interpreterbook.com/).

It finally works! Here's a small excerpt of what you can do with the Monkey Interpreter.

```
>> let makeAdder = fn(x) { fn(y) { x + y}}
>> let addTwo = makeAdder(2)
>> addTwo(6)
8
```

### TODO

- Chapter 4: Extending the Parser

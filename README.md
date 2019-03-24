# coffee-ci
A efficient workflow for continuous integration with coffee machine.

# What is a coffee-ci should be like?
A coffee-ci workflow:

1. Write your code.
2. Commit via git.
3. Emit a building on Travis/Circle/Jakins/Whatever...
4. At the same time, coffee machine start to make coffee for you.
5. Walk to your coffee machine and enjoy your coffee.
6. When the building is finished, coffee machine will remind you with tip on screen.
7. Return to your work. Or you may be fired.

# What do we need to do?

I thought we need a GUI for coffee machine. But then I found it not neccessary.

We can just use a terminal to control the machine and show tips.

For example:

```
---------------------------
Your building is finished!
And you have an error?
Unexpected Token blabla...
---------------------------
```

I think it is cool indeed.

# What more can we do?

We can show some ASCII art on this coffee machine.

How about Bad Apple? https://github.com/LeoEatle/Bad-Apple-Console. (Of course we need a Linux versin for coffee machine)
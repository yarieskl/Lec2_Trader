# Boundaries

In your team, explore the code. Start at class `Main`.

Read the code line by line and discuss with your team:
- What are the types?
- What is the code doing?

Now look at `Tradable`. That means "able to be traded".
In order to be tradable, an object must have a name and a value.

# Discovering a boundary

Discuss `Hatchimal`. Notice that it implements `Tradable`.
That means a `Hatchimal` is a `Tradable` object.

Discuss `Pebble`. Where is it similar in structure to `Hatchimal`?
Every `Tradable` will share the similarities.

Discuss `Trader`. What are the two instance variables?
How are objects added to a `Trader`? Where in `Main.main` does that happen?

In what situations would `evaluateTrade` return `true`?

What is the type — `Pebble` or `Hatchimal` — of the object the first time that
`getTradeValue` is called?

> If you like, verify your answer by setting a breakpoint on the first statement
in method `getTradeValue`, then running the debugger.
 
# Extending the program

For extra discussion, think about:

- What code we would write if we wanted traders to evaluate trades in different ways.

- What about if we wanted to expand this program to further model the domain
of trading and commerce? What classes, interfaces, methods, or variables might we add?

- What if we wanted to add a GUI? How might the GUI look?

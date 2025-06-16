There might be times when you want a specific part of your program to run **only** when a certain condition is met. In programming, this is called **selection**.

In MakeCode, the most important block you will use for selection is the `if`{:class='microbitlogic'} block.

### Using an if block

You will find the `if`{:class='microbitlogic'} block in the `Logic`{:class='microbitlogic'} menu.

<img src="images/if-block-location.png" alt="The Logic menu with the `if` block highlighted." width="350"/>

You have to put `if`{:class='microbitlogic'} blocks inside other blocks, like `forever`{:class='microbitbasic'} loops or an `on button pressed`{:class='microbitinput'} block.

You can place other blocks **inside** an `if`{:class='microbitlogic'} block, and they will only run **if** the condition is `true`.

### The condition

An important part of the `if`{:class='microbitlogic'} block is the **condition**. The blocks inside an `if`{:class='microbitlogic'} will only run if a condition is `true`.

You can find the condition blocks in the `Logic`{:class='microbitlogic'} menu of the Toolbox.

<img src="images/comparison-blocks.png" alt="The Comparison section of the Logic menu, with three blocks showing: 0 = 0, 0 >

A condition has two parts:

1. Data
2. An operator

**Data**

There has to be data on either side of your condition. This can be a variable, a sensor reading, a `true/false`, or a number.

**Operator**

The operators is **how** you are comparing the two pieces of data.

You can think of the operator like a question you are asking about your two pieces of data.

The operators you can use are:

- `=` — are the two sides **equal**?
- `≠` — are the two sides **not equal**?
- `>` — is the first piece of data **greater than** the second?
- `<` — is the first piece of data **less than** the second?
- `≥` — is the first piece of data **greater than or equal to** the second?
- `≤` — is the first piece of data **less than or equal to** the second?

You can choose an operator by dragging a comparison block into your `if`{:class='microbitlogic'} block and clicking on the drop-down menu.

<img src="images/changing-operator.gif" alt="A demonstration of using the drop-down menu on a comparison block to change the operator." width="300"/>

#### else if and else

You can also add more possible outcomes to your `if`{:class='microbitlogic'} block with `else`{:class='microbitlogic'} and `else if`{:class='microbitlogic'} blocks.

**else**

Sometimes you might want some code to run if the condition in your `if`{:class='microbitlogic'} block is `false`. To do this, you can use an `else`{:class='microbitlogic'}.

The blocks inside the `else`{:class='microbitlogic'} part will run **only** when the condition is `false`.

To add an `else`{:class='microbitlogic'}, you need to click the `+` symbol at the bottom of your `if`{:class='microbitlogic'} block.

There is also an `if else`{:class='microbitlogic'} block that you can use if you know you will need to do one thing if a condition is true and another if a condition is false.

**else if**

An `else if`{:class='microbitlogic'} block allows you to add another condition to check.

**It will only check the second condition if the first condition is `false`. If you always want both conditions to be checked, you have to add a second `if`{:class='microbitlogic'} block.**

To add an `else if`{:class='microbitlogic'} block, you click the `+` symbol at the bottom of the `if`{:class='microbitlogic'} block.

<img src="images/elseif-blocks.gif" alt="An animation showing the + symbol being used to add three 'else if' sections. Finally, the 'else' is removed from the end by clicking the '-' symbol next to it." width="350"/>

If you just want an `else if`{:class='microbitlogic'}, you will have to click the `+` twice and then `-` the `else`{:class='microbitlogic'}.

You will then have to add another `condition`.

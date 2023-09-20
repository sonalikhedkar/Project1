<h2>Don't Repeat Yourself (DRY)</h2>
<h3>DRY stands for Don’t Repeat Yourself. It’s a software development principle with the goal of removing logic duplication.</h3>

Duplication of code can make code very difficult to maintain. Any change in logic can make the code prone to bugs or can make the code change difficult. This can be fixed by doing code reuse (DRY Principle).

The DRY principle is stated as "Every piece of knowledge must have a single, unambiguous, authoritative representation within a system".

The way to achieve DRY is by creating functions and classes to make sure that any logic should be written in only one place.
DRY was first introduced in the book The Pragmatic Programmer and ensures that a particular logic appears only once in the codebase.

For example, writing a function that contains a specific logic and then calling it multiple times in our code is a form of applying the DRY principle.

Here is a pseudocode that receives two temperatures in Fahrenheit and converts them into Celsius before applying DRY:

![image](https://github.com/sonalikhedkar/Project1/assets/110111616/46ec181b-ec73-459a-b0ff-195c59bc3e13)

Now here is the same program after applying DRY:
![image](https://github.com/sonalikhedkar/Project1/assets/110111616/4ff382c9-cf19-45a0-83e8-469898065139)

We can see that, after applying DRY, the logic that converts Fahrenheit to Celsius appears only once in our code.

<h1>Objects and Their Internal Representation</h1>

In JavaScript, objects serve as fundamental data structures. They differ from primitive data types (such as numbers, strings, and booleans) because objects can contain a combination of primitive values and reference data types. Here are some key points:

1. <b>Object Basics:</b>
    - An object is an unordered collection of related data stored as key-value pairs.
    - Each key (property) can be a variable or a function (method).
    - For example, consider an object representing a person:

<center>
<img src="https://miro.medium.com/v2/resize:fit:4096/1*GA7toY-Y3a3l0nlewOxIAw.png">
</center>


2. <b>Properties and Methods:</b>
    - Properties define the characteristics of an object (e.g., name, age, courses).
    - Methods are functions associated with the object (e.g., greet).
    - You can access properties using dot notation (perso.name) or bracket notation (person ['age']).

3. <b>Internal Representation:</b>
    - JavaScript engines represent objects using data structures like hash tables.
    - Keys (property names) are hashed for efficient property access.
    - When you access a property, the engine performs a hash lookup to retrieve the value.

4. <b>Creating Objects:</b>
    - You can create objects using literal notation ({}) or the new Object() constructor.
    - Example:

<center>
<img src="https://dotnettutorials.net/wp-content/uploads/2021/04/word-image-15.png">
</center>


5. <b>Prototypes and Inheritance:</b>
    - Every object has an associated prototype (except the root object).
    - Prototypes allow inheritance of properties and methods.
    - Constructor functions create objects with shared prototypes.

<h3>Conclusion</h3>

Understanding how JavaScript represents objects internally is essential for effective programming. Whether you’re building web applications or working with APIs, mastering objects empowers you to write cleaner, more maintainable code. Happy coding..!
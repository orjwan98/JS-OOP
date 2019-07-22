# What are Classes and Why do we use them?

Classes are the recipe, or a blueprint for an object. For example, a car is an object, and though the functionality is the same for all cars, we have different models, numbers, colors, speed and number of seats or windows. 

# Classes are only ES6 syntactic sugar. 

Classes were newly presented in ES6 to emulate dealing with Classes in other languages. It's a way to write better and cleaner code too. 

# How do we make a Class?

By using the **`class`** keyword, and a first letter capitalized name. Here's an example:

```js
class Person {
     constructor(name, age, occupation){
        this.name = name;
        this.age = age;
        this.occupation = occupation;
     }

}
```

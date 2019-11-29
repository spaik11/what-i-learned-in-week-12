# What I Learned In Week 12
### Functions & Methods
Arrow Function
``` javascript
const printTodo = para => console.log(todo);
```
`arr.filter()` - this method will filter out whatever condition you pass to create a new array.

---
### Object Oriented Programming (OOP)
* A way to organize your information so everything has a type of something.
* The short hand and it's very common to have the same key and variable in an object.
``` javascript
const todo = {
    name,
    date,
    complete,
}
```

* A dynamic way to add data to an object. If you put an equal as a part of the parameter, it will make it optional.
``` javascript
const student = function(first, last, age, grades = []) {
    return {  
        firstName: first,
        lastName: last,
        age,
        grades,
        getFullName: function() { 
            return `${this.firstName} ${this.lastName}` 
        },
    }
}
```

---
### Tools for Design
The most commonly used design app is **Bootstrap**. You can either pull the CSS online or download it locally and save it as a CSS file.

---
### Notes
`new Date()` - is an object that can be used for various reasons.
* CRUD App - Create, Read, Update, Delete app
* Queue - First In First Out (FIFO)
* Stack - First In Last Out (FILO)
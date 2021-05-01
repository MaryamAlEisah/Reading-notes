# HTML Tables; JS Constructor Functions, JS OOP

## HTML Tables

### why using Tables ?

**HTML tables**  allow web developers to arrange data into rows and columns.

 ![](https://images.slideplayer.com/34/8357994/slides/slide_4.jpg)

 ### Example
A simple *HTML table*:

 ![](https://www.usna.edu/Users/cs/wcbrown/courses/F02SI204/projects/P01/T3.gif)

  ![](https://www.usna.edu/Users/cs/wcbrown/courses/F02SI204/projects/P01/T4.gif)


### *Long Tables* in In HTML?

For **long tables** you can split the table into a :
* `<thead>`
* `<tbody>`
* `<tfoot>`


## WHAT IS AN OBJECT In JS?
An **object** is represented as a collection of key-value pairs in Javascript. In an object, variables are known as **properties** of the object; functions are known as **methods** of the object.


### How to create a JavaScript Object ?
There are different ways to create new objects:

1. Define and create a single object, using an *object literal*.
2. Define and create a single object, with the *keyword new*.
3. Define an object constructor, and then create objects of the *constructed type*.

![](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/How-to-Create-JavaScript-Objects.jpg)  


 ### Example:

 ![](https://csawesome.runestone.academy/runestone/books/published/csawesome/_images/worldConstructors.png)


 ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1576395857500/Him6j7txy.png)


![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSaKqzaQK2Fg2sCENBQeq_kuytyG-rb92ry4g&usqp=CAU.png)


### What is **`this`**?

The JS this keyword refers to the object it belongs to. It has different values depending on where it is used:

* In a method,it refers to the owner object.
* Alone,it refers to the global object.
* In a function,it refers to the global object.
* In a function, in strict mode,it is undefined.
* In an event,it refers to the element that received the event.
* Methods like *call()*, and *apply()* can refer this to any object.


### Arrays & objects :

**Arrays** are a special type of objects. The typeof operator in JavaScript returns "object" for arrays. But, JavaScript arrays are best described as arrays.

![](https://res.cloudinary.com/practicaldev/image/fetch/s--rJeH0yGE--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/t52ni02srb8688lh3eh8.png)


### What are BUILT-IN Objects? 

The **built-in objects** are *Date*, *Math*, *String*, *Array*, and *Object*. Each is used in a unique and not-quite-consistent way. Furthermore, newer versions of JavaScript implement several of these objects in a different manner than in Netscape.


[For more information 🙂](https://www.infoworld.com/article/2077150/using-javascript-s-built-in-objects.html#:~:text=Learning%20JavaScript&text=The%20built%2Din%20objects%20are,manner%20than%20in%20Netscape%202.0.)


## Domain Modeling

**Domain modeling** is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

Some tips to follow when building your own domain models:

- When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
- Model its attributes with a constructor function that defines and initializes properties.
- Model its behaviors with small methods that focus on doing one job well.
- Create instances using the new keyword followed by a call to a constructor function.
- Store the newly created object in a variable so you can access its properties and methods from outside.
- Use the -this variable- within methods so you can access the object's properties and methods from inside.


 ![](https://miro.medium.com/max/875/1*QMu3QLuDKGyBNI2UJ2bKOA.png)

&copy; 2021
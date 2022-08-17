# Read: Class 03

##  HTML Lists, Control Flow with JS, and the CSS Box Model

HTML lists are useful when you need bullet style points or an ordered list. In CSS the box model helps us picture what tweaking the padding, margin, etc will do in our heads. JS doesn't perform the way you expect code is out of order.  

### 1. When should you use an unordered list in your HTML document?

An unordered list should be used when you the order of a list isn't important.

### 2. How do you change the bullet style of unordered list items?

The bullet style of an unordered list by using the list-style-type property. 

### 3. When should you use an ordered list vs an unorder list in your HTML document?

An ordered list should be used when the order of the list matters. If the meaning of the list changes when the order is changed use ordered list.

### 4. Describe two ways you can change the numbers on list items provided by an ordered list?

Numbers can be chaned on list items by having the type attribute assign "i" for Roman numerals or by the start attribute assign the number you want the list to start at.

### Sources

[https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

[https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)

[https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)

## The Box Model

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

Margin is the bouncer at the club The Box Model. Padding is the body gaurd for the VIP in The Box Model. Margin's role it to prevent anyone from entering the club. Padding's role is to stand inside the club and preventing anyone from touching the VIP.

### 2. List and describe the four parts of an HTML elements box as referred to by the box model.
    * Content is text or image.
    * Padding is the transparent area around the content.
    * The border goes around the content. This can be visible.
    * Margin is the transparent area around the border.

### Sources

[https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)

### 1. What data types can you store inside of an Array?

    * strings
    * numbers
    * objects
    * other arrays

### 2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

People array is a valid array. You can access it by chaining two sets of brackests and using the index numbers.

console.log(people[3][3]); would display the string artist in the console.

### 3. List five shorthand operators for assignment in javascript and describe what they do.

* Addition assignment: x += f() changes the value of x to x + f()
* Subrtraction assignment: x -= f() changes the value of x to x - f()
* Multiplication assignment: x *= f() changes the value of x to x * f()
* Division assignment: x /= f() changes the value of x to x / f()
* Remainder assignment: x %= f() changes the value of x to x % f(). It returns how many times the first value can go into the right operand.

### 4. Read the code below and evaluate the last expression and explain what the result would be and why.

The result would be 10dog because the data type of c is a boolean.

### 5. Describe a real world example of when a conditional statement should be used in a JavaScript program.

An if statement could be used when trying to enter a room. If the door is closed then proceed to knock. If someone responds with come in, enter the door. Else if someone responds with don't come, leave and comeback later. Else enter the door.  

### 6. Give an example of when a Loop is useful in JavaScript.

A loop is useful in JS when a code needs to be repeated until a condition is met. For example a while statement can be used to repeat a question until the answer is correct.

### Sources

[https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)

[https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

[https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)

[https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)


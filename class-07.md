# Object-Oriented Programming, HTML Tables

## Object-Oriented Programming:
An object is a thing that we interact with, it has properties and methods. The object is the heart of object-oriented programming.
Here’s a list of concepts that are most often used when talking about object-oriented programming (OOP):
* Object, property, and method
* Class
* Encapsulation
* Abstraction
* Reusability/inheritance
* Polymorphism
* Association
* Aggregation
* Composition
### Object, property, and method
Object literal
Create a new object in JavaScript by setting its properties inside curly braces. Object literals property values can be any data types, like function literals, arrays, strings, numbers, or boolean.
Let’s create an object with a named book, with properties such as author, published year, title, and a method — summary.

Example:

const book = { 

title: "Hippie",    
   author: "Paulo Coelho",  
   year: "2018"
}


## Table in HTML:
The <table> tag defines an HTML table.

Each table row is defined with a <tr> tag. Each table header is defined with a <th> tag. Each table data/cell is defined with a <td> tag.

By default, the text in <th> elements are bold and centered.

By default, the text in <td> elements are regular and left-aligned.
 
example:
- <table style="width:100%">
 -  <tr>
  *  <th>Firstname</th>
   * <th>Lastname</th>
    * <th>Age</th>
  * </tr>
  * <tr>
    * <td>Jill</td>
    * <td>Smith</td>
    * <td>50</td>
  * </tr>
  * <tr>
    * <td>Eve</td>
    * <td>Jackson</td>
    * <td>94</td>
  * </tr>
* </table>
#Arrays

What is an array?
: An array is basically a container that holds other "items". Those items can be strings, numbers, other arrays, objects, functions, and booleans.  Each item that is stored in the array can be referenced by an index, with the first item being located at a 0 index.  If the array contains 3 items, its length is 3, but the indexs for those items are 0, 1, & 2.  An array has many methods that can be called on it to access and/or update information within it.  

---
#Creating
---
```javascript
const friends = ["Peter", "Paul", "Mary"];
console.log(friends); //['Peter', 'Paul', 'Mary'];
//because friends was declared with const, I cannot reassign the value of friends, but I can use other methods to manipulate it. 
//friends = ["Tim", "Addie", "Ryan"] would result in an error

//declare empty array
let fruits = [];
//because this was declared with 'let', I can reassing the value
fruits = ["carrots", "peppers", "mushrooms"];
console.log(fruits); //['carrots', 'peppers', 'mushrooms'];
//oh wait...that's not right
fruits = ["grapes", "strawberries", "kiwi"];


```
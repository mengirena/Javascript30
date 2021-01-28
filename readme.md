# JavaScript30

This is cloned from [Wes Bos's awesome challenge (free!)](https://github.com/wesbos/JavaScript30)

## My learning progress
![Current progress](https://progress-bar.dev/3/?title=completed)

## 04 Array Cardio Day 1 (01/24/2021 - 01/26/2021)
### **Highlights**

* `sort()` method will modify the array
* Expanding the toggle of an object's result in the Chrome console will evaluate the object at the time when it's expanded. 

    A small `i` showing next to the object displays:

    > Value below was evaluated just now.

    [Question asked about this behavior on stackoverflow](https://stackoverflow.com/questions/23429203/weird-behavior-with-objects-console-log)

* Use DOM to get data from a webpage: the result gotten from `document.querySelector()` can be chained by another `querySelector()` or `querySelectorAll()`

* The result gotten from `document.querySelector()` is not a list. It's a nodeList.

* Use `Array.from(arrayLike)` to create an array of an iterable object 

* Use [spread operator](https://dev.to/sagar/three-dots---in-javascript-26ci) `[...nodeList]` can also make the nodeList to be a list

* Use [destructuring assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment) to unpack values from an array.

* The initial value as a parameter of a `reduce()` function can be an object.

## 01 JavaScript Drum Kit (01/27/2021 - on-going)
### **Highlights**

* `addEventListener()` can also listen to keyboard events such as `keydown`
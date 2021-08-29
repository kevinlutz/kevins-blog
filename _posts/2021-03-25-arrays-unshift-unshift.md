---
layout: post
title:  "Unshift & Shift"
date:   2021-03-25 10:46:05 -0400
categories: jekyll update
---




{% highlight ruby %}

//UNSHIFT (add an element to the **beginning** of an array)
array1 = [2,3,4,5]
array1.unshift(1);

console.log(array1)  //[1,2,3,4,5]

Remember:
- [x] When you add as element, you have to tell the computer what you would like to add, hence we placed the 1 inside of the parenthesis (1)


//SHIFT (removes the first element from the *beginning* of an array)
array2 = [1,2,3,4,5]
array2.shift()

console.log(array2)   //[2,3,4,5]

Remember:
- [x] When you want to remove the first element, you do no have to specifically name, inside oft he paraenthesis, what you want the computer to remove. The inside of the parenthesis can be left blank, and the computer will automatically remove and give to you the first element that appears in the array.

{% endhighlight %}


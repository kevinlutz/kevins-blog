---
layout: post
title: "Event Listeners"
date: 2021-09-10 10:46:05 -0400
categories: jekyll update
visible: false
---

The three pillars of a web application are the following:

Summary:

**The Three Pillars**

1. Manipulating the DOM
2. Recognizing JavaScript events
3. Communicating the the server

Today we will be taking a look at the second pillar: **recognizing JavaScript events**.

Events listeners are composed of two parts. The first is called an 'event listener'. You may have encountered using many event listeners while browsing the internet without even knowing it. An event listener is an **action** of the user, that the computer waits, or 'listens', for. It is something that **happens**. A commmon event listener you may very well be acquainted with, is the 'click' event.

When you click a button on a website, that in essence is a command for something to now be **executed**. Which brings us two the second part of recognizing a JavaScript event: handlers. The handler is the change that should take place when the event listener tells it to.

A simple example would be deleting a photo from your computer. Firstly you would click the delete button, that would be the **action** that the computer was waiting for. It was 'listening' for that command. Once it hears the command of the event listener, the computer would **execute** the deletion of your photo. The very act of deleting the photo is the event 'handler'.

**Let's compose the entire element to see what it looks like:**

Firstly we need to attach our event listener & handler to an HTML element.
For our element, let's choose to grab a generic delete button, from generic HTML, with an id of 'delete-btn' and place it in a variable called 'deleteButton'. At this time let's also grab what we would like to delete, which in this case would be an image. Let's do this similarly to that of grabbing the deleteButton. That would look like this:

const deleteButton = document.querySelector('#delete-btn)
const image = document.querySelector('#image-of-me')

Now we can procede to add the event listener to our deleteButton variable:

deleteButton.addEventListener()

Then we need to add the **action** or **listener** that we want to 'listen' for. In this case we want to listen for a 'click':

deleteButton.addEventListener('click', )

Next we want to include what we would like to be **executed** once the 'click' occurs. Remember, this is called our event **handler**.

deleteButton.addEventListener('click', () => image.remove())

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

This is a photo: ![alt surfer guy](Surfer1.jpg)

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(kevin)
puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]: https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

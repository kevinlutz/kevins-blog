---
layout: post
title:  "Markdown"
date:   2021-03-25 10:46:05 -0400
categories: jekyll update
---

**Bold Subheadings**
This is how I create my **bold** subheadings: ** bold **

**How To Highlights Certain Words In Your Text**
Use backticks (\`). Like this: I want to `highlight` this word.

**How To Write Code In Your Markdown Text**
Use {% highlight ruby %} & {% endhighlight %}




**Previous Command Line Commands**
kevinlutz@Kevins-MacBook-Pro kevins-blog % pwd
/Users/kevinlutz/kevins-blog
kevinlutz@Kevins-MacBook-Pro kevins-blog % git init
Initialized empty Git repository in /Users/kevinlutz/kevins-blog/.git/
kevinlutz@Kevins-MacBook-Pro kevins-blog % git add .
kevinlutz@Kevins-MacBook-Pro kevins-blog % git commit -m "first commit"

kevinlutz@Kevins-MacBook-Pro kevins-blog % git remote add origin https://github.com/kevinlutz/kevins-blog.git
kevinlutz@Kevins-MacBook-Pro kevins-blog % git branch
* master
kevinlutz@Kevins-MacBook-Pro kevins-blog % git push -u origin master



**Stop and Start Server**
stop: ctrl + c
start: bundle exec jekyll serve (or up arrow to repeat last command)


**To Create a Link**
Use [underlined text with brackets]



You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

**this should be bold**

1. this is important
2. this is also important
2. so is this
3. this is too

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

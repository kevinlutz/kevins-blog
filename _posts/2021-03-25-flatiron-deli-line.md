---
layout: post
title:  "Deli Line"
date:   2021-03-25 10:46:05 -0400
categories: jekyll update
---



{% highlight ruby %}
const takeANumber = (currentLine, newPerson ) => {
  //current length
  currentLine.push(newPerson);
  const currentLengthOfLine = currentLine.length
  // add a newPerson to the line
  return `Welcome, ${newPerson}. You are number ${currentLengthOfLine} in line.`

}

const nowServing = (currentLine) => {
  if(currentLine.length > 0){
      return `Currently serving ${currentLine.shift()}.`
  } else {
    return "There is nobody waiting to be served!"
  }
}

// The line is currently:   1. Ada, 2. Grace"
// currline = ["Ada", "Grace"]

const currentLine = (currLine) => {

  if (currLine.length === 0) return "The line is currently empty."

  let sentence = "The line is currently: "
  for (let i = 0; i < currLine.length; i++) {
    const name = currLine[i]  //ADA
    const num = i + 1 + '.'  //1.
    const nameAndNum = num + " " + name + "," + " "// 1. ADA
    sentence += nameAndNum
  }
  return sentence.slice(0,sentence.length-2);
}
{% endhighlight %}
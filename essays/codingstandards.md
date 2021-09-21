---
layout: essay
type: essay
title: 
# All dates must be YYYY-MM-DD format!
date: 2021-09-23
labels:
  - Intellij
  - Coding Standards
  - ESLint
---

## What are Coding Standards

Coding standards is a set of rules and practices that aid in writing code that is neat and orderly.

## My Opinion on Coding Standards

This is not my first experience with coding standards. My first ever class in coding was called EE160 which is where I first learned the C programming language. My professor always stressed that it was important to have your code to be clean with comments, the right amound of indentations, and spaces. There were points taken off if we did not follow the standard. However, as my college career continued to where I am today, it has not been enforced as heavily as it was before so to come in contact with coding standards again felt kind of like a wake up call.

I would not say that after my EE160 class I just dropped everything I learned about the coding standard and wrote code that was messy and hard to follow. However, when I did see the code I wrote on Intellij, there was a red mark in almost every line. It did feel terrible to see and think that I had to fix all those lines of code. I will be honest and say that I thought some coding standards based on ESLint were kind of ridiculous and I did not agree that it was "messy."

In the following example, we see code that does not follow the coding standards. The lack of indentations and spaces between the words or between conditional cases has made this bad code.

```js
function sumWhile(list){
let sum = 0;
let i = 0;
  while (i<list.length){
  sum += list[i];i++;
  }
      return sum;
}
```
By following the coding standard, the code turns into this:
```js
function sumWhile(list) {
  let sum = 0; let i = 0;
  while (i < list.length) {
    sum += list[i];
    i++;
  }
  return sum;
}
```

## Conclusion

I think that following the coding standard is something that I need to become used to doing again. My honest opinion on coding standards is that it can be tough and tedious to do at first, but once you get familiar with the rules and the process, it will be beneficial when you are debugging, reading through code, and even asking someone for help.

---
layout: essay
type: essay
title: Own the Coding Standard
# All dates must be YYYY-MM-DD format!
date: 2021-09-23
labels:
  - Intellij
  - Coding Standards
  - ESLint
---

**Coding standards** are a set of rules and practices that aid in writing code that is neat and orderly.

## Another Encounter with Coding Standards

This is not my first experience with coding standards. My first ever class in coding was called EE160 which is where I first learned the C programming language. My professor always stressed that it was important to have your code to be clean with comments and the right amount of indentations and spaces. There were also points taken off if we did not follow the standard. The practice of following the coding standard has helped me when I first learned how to program in C as it made my code neat and easy to follow. However, as my college career continued to where I am today, it has not been enforced as heavily as it was before, so to come in contact with coding standards again felt like a wake up call. 

I would not say that after my EE160 class I just dropped everything I learned about the coding standard and wrote code that was messy and hard to follow, but my code did become less clean and orderly once I stopped adhering to it. Upon seeing the code I wrote on Intellij, which I thought was fairly clean, I ended up seeing a red mark in almost every line. It didn't feel so great to see and think that I had to fix all those lines of code. However, ESLint has been extremely helpful in showing me exactly where my errors are and assisting me in fixing them. I do think that some of the errors I received based on the ESLint coding standards I did not agree with as I felt that writing code in that way was not a problem. Right now for me it feels tiresome to follow and keep up with, but I know that it is a practice that will turn out to be profitable in the end.

## Why You Should Follow the Coding Standard

It is good to practice coding standards and to start from the very beginning when you first start learning a new coding language so that the practice will carry on as you begin to write larger programs that require multiple lines of code. From my experience in writing and reading large files of code, I notice a difference when the code is well documented. The code that is well documented improves its readability, while one that is not makes it hard to follow and dreadful to go through especially when you encounter errors and problems in your code and can't find where the problem originates. It is also helpful to have clean code when you want to ask someone to review your code as a courtesy to them and to produce quality code that follows the standard.

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
Obviously, from looking at the two examples we can see that the code that follows the coding standard is much better. It is easier to read and follow, while the version with missing indentations and lack of spaces between words and statements make it more difficult to read. Although the importance of this may not be seen in this small function, it will be especially important once we start writing larger programs that consist of many lines of code and multiple files.

## Conclusion

I think that following the coding standard is something that I need to become used to following strictly again especially as I am learning new coding languages and styles. It has helped me in the past when I first learned how to code in C, so I believe that it can be beneficial when learning other coding languages. Although it can be tough and mundane to do in the beginning, as you keep practicing, and become familiar with the rules and the process, it will turn into something you do regularly. Following the coding standards will be worthwhile especially when the time comes that you have a problem with your code and need to debug, review your code, or even ask someone for help in checking your code.

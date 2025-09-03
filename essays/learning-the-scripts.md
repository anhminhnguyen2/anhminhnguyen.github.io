---
layout: essay
type: essay
title: "Learning the Scripts"
# All dates must be YYYY-MM-DD format!
date: 2025-09-03
published: true
labels:
  - Typescript
  - Javascript
  - Learning
  - Reflection
---

With previous knowledge of Java from high school, as well as ICS 111 and ICS 211, JavaScript and TypeScript do not feel completely unfamiliar. When it comes to the syntax of common data structures that I practiced many times in ICS 111 and ICS 121, such as arrays, classes, or maps, I feel familiar with TypeScript. I also believe that I do not have a deep understanding and grasp of how huge Java’s built-in library is, just from introductory classes, so I cannot make a detailed comparison between the two languages. From my knowledge and observations, I can see how Typescript can be a good programming language for software engineering tasks.

## Offers flexibility when it comes to structure, types, and parameters

One thing that surprised me when going through the modules on JavaScript and TypeScript is how diverse arrays and parameters can be. For example, a tuple is a type of array with a defined length and type. An interesting characteristic (at least for me) is that there can be multiple different types of data in one tuple, while in Java, a standard array can only contain a single specific type.

```ts
// define our tuple
let ourTuple: [number, boolean, string];

// initialize correctly
ourTuple = [3, true, 'Hello'];
```

Another mind-blowing feature of Typescript is Union Types, when a value can be of more than a single type.
```ts
function print(x : sting | number) {
  console.log (‘x is ${x}’);
}
print(4); 
print(‘4’);
//Both calls of ‘print’ function are valid

```
These are just a few examples of new features that JavaScript and TypeScript offer while going through the modules. I hope to get more familiar with this new language so that I can use it to its full potential in the future through this class.

## Training the thinking muscle

WODs (Workout of the Day) are designed to evoke problem-solving and critical thinking skills by solving a coding problem in a limited amount of time, helping students get used to the nature of job interviews. The first WOD I did was from home, and I was able to go through it in a decent amount of time. As I attempted to do a WOD in class as a group, I got a little pressured and rushed through and ended up with my partner helping me resolve an error in the code. I hope to get used to this learning style, since I really like the purpose of it and know that it will benefit me in the future, so that I can do better, either by myself or with others. 

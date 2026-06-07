---
layout: essay
type: essay
title: "Typescript First Impressions"
# All dates must be YYYY-MM-DD format!
date: 2026-06-06
published: true
labels:
  - Typescript
---

<img width="200px" class="rounded float-start pe-4" src="../img/TypeJava.jpg">

*“Anyone who keeps learning stays young.” – Henry Ford*

## Preface: My personal history with coding

My prior experience with coding is pretty limited. In my previous ICS classes, I have worked with various C, C++, Java and a bit of Javascript. I wouldn't say that I'm fully confident in any of these languages, but I do feel comfortable with the basic consepts: variables, functions, classes, and even some loop functions. When I started working with TypeScript, I immediately noticed both familiar patterns as well as a few differences. Some of these similarities made the transition smoother, while the differences made my first few attempts feel clumsy. Still, the learning curve has been interesting, especially when comparing TypeScript to my past coding knowledge.

## Similarities: What felt familiar

Let's start with some similarities. When first going into TypeScript, I was surprised by how similar much of the language felt. Which shouldn't be surprising since TypeScript is a subset of JavaScript. As I was working, I recognized a lot of the commands that I had used in my past experience. Commands such as; number, string, and boolean. This gave me a sence of familiarity that would be the structure of my TypeScript journey. 

TypeScript’s class syntax also made the transition easier. Concepts like constructors, inheritance, and access modifiers were things I was already used to, so reading and writing TypeScript classes didn’t feel like starting from square one. For example:

*Class in TypeScript*
```
class Student {
  name: string;
  constructor(name: string) {
    this.name = name;
  }
}
```

*Class in Java*
```
class Student {
  String name;
  Student(String name) {
    this.name = name;
  }
}
```

The same was true for functions. Writing a function with typed parameters and a typed return value felt almost identical to writing a method in C++ or Java. These similarities helped me get comfortable with the language faster than I expected.

## Differences: What challenged me

Despite the familiar commands, TypeScript also introduced several differences that took some time to adjust to. The biggest challenge was understanding that TypeScript’s type system only exists at compile time. Coming from C++ and Java, where types matter at runtime, this was confusing at first. SUch as:

```
console.log("5" + 1); // "51"
```

Another challenge was learning TypeScript‑specific features like interfaces and type aliases. They look similar to Java interfaces, but they serve a different purpose: describing the “shape” of data rather than defining behavior. It took a while to understand when to use an interface versus when to use a class. 

## Conclusion

Overall, my first experience with TypeScript has been a mix of comfort and challenge. The similarities to C/C++ and Java gave me a solid foundation to build on, especially when it came to typing and object‑oriented programming. At the same time, TypeScript’s connection to JavaScript introduced new ideas and behaviors that pushed me outside my usual way of thinking about code. 

Even though I had a few hiccups along the way, I can already see why TypeScript is valued in modern software engineering: it brings structure and clarity to JavaScript without taking away its flexibility. I wish to continue learning more about TypeScript. Hopefuly by practicing and learning more about this coding language, I will learn to appreciate how TypeScript encourages both discipline and adaptability. It’s not always easy, but it’s definitely helping me grow as a programmer.

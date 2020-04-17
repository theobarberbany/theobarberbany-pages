---
title: "100 Days of Swift Days 2-4"
date: 2020-04-17T20:38:30+01:00
draft: false 
---
I'm going to chunk these as the first 12 days are a recap of programming language concepts and constructs that are common to a lot of modern languages. I found the `repeat` loops to be interesting, having not come across them before. 

```swift
// condition checked last, first iteration of loop always runs
var number = 1

repeat {
    print(number)
    number+= 1
} while number <= 20

print("Ready or not, here I come!")
```



---
title: "Common Code Smells"
date: 2020-09-15T11:30:03+00:00
draft: true
author: "Greg Peddle"
tags: ["code", "quality"]
---

Many software developers know that some of their code smells bad, but have become used to it over time.


Mysterious Name: functions, modules, variables or classes that are named in a way that does not communicate what they do or how to use them.

Duplicated code: identical or very similar code that exists in more than one location.
Contrived complexity: forced usage of overcomplicated design patterns where simpler design patterns would suffice.
Shotgun surgery: a single change that needs to be applied to multiple classes at the same time.
Uncontrolled side effects: side effects of coding that commonly cause runtime exceptions, with unit tests unable to capture the exact cause of the problem.
Variable mutations: mutations that vary widely enough that refactoring the code becomes increasingly difficult, due to the actual value's status as unpredictable and hard to reason about.
Boolean blindness: easy to assert on the opposite value and still type checks.
---
layout: essay
type: essay
title: "Follow the Rules"
# All dates must be YYYY-MM-DD format!
date: 2025-09-24
published: true
labels:
  - Standards
  - Coding
---

<img width="300px" class="rounded float-start pe-4" src="../img\codestan\ESLint_logo.png">

Coding standards. Love them or hate them, I believe they provide those learning to code with a structure to follow, getting them accustomed to reading code in a way that other people are likely write in. However, learning coding standards from a documentation website is a drag. It's hard to learn from these platforms in any major capacity without sinking large amounts of time into it. That's where tools such as ESLint come in. These tools are meant to do most of the heavy lifting when refactoring or restructuring code. They already come pre-initialized with some standard ruleset and apply them equally across your workspace. This is incredibly useful since all you have to do is pull your hair out until you get rid of all of the red squiggly lines in your code that aren't a real bug. That does sound like a pain, but the end result is a well structured file that is generally easy to read. However, I still have my gripes.

## My Experience with ESLint

Having messed around with it for the past week or so, I can confidently say, I'm not a big fan. I do think it's useful in theory, but in application, I feel like it gets in my way more than it helps. Even though I'm writing code in a standard, readable way, ESLint already has its own idea of what "standard" is and forces its way into my flow. If I wrote exactly how ESLint wanted me to all the time it'd be no problem. In fact, most of it is actually reasonable to me. However certain rules are a bit unnecessary in my opinion. For example, trailing spaces after a line causing ESLint to throw a fit, or requiring an empty new line at the end of a file. It seems like something tiny, but when you're trying to figure out why your code isn't working and your linter is always yelling at you saying that you accidentally added whitespace, it can get distracting. And sure, you can disable settings and options to make it feel less like you're wrestling with the grammar police of code, but then what's the point of having it? After you're accustomed to writing "readable" code, there seems to be no point to having an assistant looking over your shoulder saying "Oh, you missed a spot," forcing you to go back and fix it. It personally interrupted my flow and made it hard to find actual bugs that my compiler would throw instead.

## Disregarding my Whining

Despite my gripes, I'd still recommend any new programmer to install ESLint or another similar program. Having a framework to fall back to when you need guidance can be a life saver when trying to learn new structures. However, if someone has been coding for a while and has their own style of coding that works for them and their team, I feel that the adjustment curve that you will face when attempting to integrate ESLint into that workflow will simply hinder progress a lot more than it would increase productivity. Although coding standards are necessary to learn in the early stages, later on in your career I feel that tools such as ESLint, although very useful, can be unnecessary.
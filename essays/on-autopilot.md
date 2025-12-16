---
layout: essay
type: essay
title: "All About Timing"
# All dates must be YYYY-MM-DD format!
date: 2025-12-15
published: true
labels:
  - Engineering
  - Ai
---

<img width="200px" class="rounded float-start pe-4" src="https://engineering.fb.com/wp-content/uploads/2019/05/grid-AI.jpg">

Ai is an incredibly powerful tool, however, there are definitely some limitation to it. If you want it to help you with troubleshooting, it can be your best friend. However, it can be frustrating if you are trying to get it to write your code. That is why I've tried my best to avoid using it to produce direct code.

1. WODs

When it came to WODs, I tried to avoid the use of Ai entirely. This was due to me treating WODs as if they were tests of my own knowledge. I took them as I would a leetcode problem and tried to use only what I knew already to write code for it. Due to that, I didn't use AI to generate code, however I did have autosuggestion through intellicode.

2. Essays

I never used AI on essays since it never sounds like I wrote any of it.

3. Final project

AI was particularly useful throughout the entire process of the final project. Like I mentioned before, I tried to avoid the use of AI to write code as much as possible, however, when troubleshooting, it was amazing as a tool to pinpoint issues and explain *why* things were going wrong, and either giving me an idea of where to start. A lot of error messages we received over the course of the project were *far* from descriptive or specific, never pointing to a specific file or line. This was where tools like Copilot really shone, as they were able to read the context of the issue and direct you where you need to be to troubleshoot it. Usually this will also give you suggestions of what to change and optionally allows you to generate a solution and automatically integrate it. This tool, albeit useful, doesn't really teach you much if you automatically fill it in. However, the explanations that it provides is immensely helpful in learning how to troubleshoot similar problems on your own. 

4. Explaining code

Sometimes we had to look over code that a teammate wrote, and sometimes they used a new technology that I hadn't had experience with yet. In these cases, using AI to explain what a new file or section of code did was sometimes useful to solve. Most of the time it was something I could figure out relatively easily on my own, however AI makes it a little more efficient and lifting that processing off of my shoulders. Again, I think this is a bad practice in the long run, since the AI isn't always accurate, and so it was more important to me that I read through it first and tried to learn what the code did using the skill's I'd already developed.

5. Asking or answering a smart-question

I used AI to answer a few questions. A specific example was when I tried to figure out how to route file inputs in an HTML element to a file system or database. The answer that it provided me did in fact *work* however there was a glaring security issue in its solution. The solution it provided me routed the raw file directly into the project directory, meaning it could be accessible via the repo if it weren't ignored. The problem was that we had no choice but to include the files if we wanted the functionality to work, so we had to find another method to store files without risking user files from being exposed.

## Overall

These were the main use cases I had found for AI. I wasn't able to form an opinion on AI in other scopes as I hadn't attempted to use it in other ways. However, for the times that I did use it, it proved itself to be a reliable *tool* to assist me in my projects. However, I still do not trust it to create reliable and safe code 100% of the time, since it can sometimes create code with questionable functionality, outdated structures, or vulnerabilities. I would be cautious to not become reliant on the use of AI in code, as it is never a perfect solution. Coders should always be aware of what the AI is writing and learn to identify bad practices or structures that may need to be tampered with to work entirely as intended.

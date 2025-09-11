---
layout: essay
type: essay
title: "Smart Questions, Good Answers"
# All dates must be YYYY-MM-DD format!
date: 2025-09-10
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

<img width="300px" class="rounded float-start pe-4" src="../img/smart-questions/rtfm.png">

# "Smart" Questions

What even constitutes a "smart" question? And if smart questions exist, that implies the existence of stupid questions as well. So, what are their differences? Well, I'd say that anything that makes you go "isn't that just common sense?" could probably fall into the category of a stupid question. Why do we jump to these conclusions? They could be honestly confused about something that we already know and we could simply be courteous and answer it for them. However, that doesn't always happen for these types of situations. That's because there is a time, place, and a method to asking questions.

## How do you ask a smart question?

There are many places online that are dedicated to asking questions: forums. Stack Overflow is a website dedicated to asking and answering programming questions, most of which that you find can be considered good questions. They're specific, concise, and tend to provide snippets of code to help others get on the same page when answering. 

Here is an example I found of a simple, but smart question:


Q: [How to confine plot region to exact area](https://stackoverflow.com/questions/60750125/how-to-confine-plot-region-to-exact-area)
```
I would like to plot a box with a grid as in the code below:
```
plot(rnorm(10), rnorm(10), type = "n", asp = 1, xlim = c(0, 1), ylim = c(0, 1), axes = FALSE, pty = "s", bty = "o", xlab = "", ylab = "")
abline(h = seq(0, 1, 0.2), v = seq(0, 1, 0.2), col = "lightgray")
abline(a = 0, b = 1, col = "lightgray")
axis(1, seq(0, 1, 0.2), seq(0, 1, 0.2), pos = 0)
axis(2, seq(0, 1, 0.2), seq(0, 1, 0.2), pos = 0)
```
but the lines exceed the area (0, 0) to (1, 1). Is it a problem with the plot region?

How can I confine the plot region to an exact area, for example from (0, 0) to (1, 1)?
```


---
layout: essay
type: essay
title: "Ask Smart Questions"
# All dates must be YYYY-MM-DD format!
date: 2025-09-10
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

<img width="300px" class="rounded float-start pe-4" src="../img/smart-questions/sendev.png">

# "Smart" Questions

What even constitutes a "smart" question? And if smart questions exist, that implies the existence of stupid questions as well. So, what are their differences? Well, I'd say that anything that makes you go "isn't that just common sense?" could probably fall into the category of a stupid question. Why do we jump to these conclusions? They could be honestly confused about something that we already know and we could simply be courteous and answer it for them. However, that doesn't always happen for these types of situations. That's because there is a time, place, and a method to asking questions.

## How do you ask a smart question?

There are many places online that are dedicated to asking questions: forums. Stack Overflow is a website dedicated to asking and answering programming questions, most of which that you find can be considered good questions. They're specific, concise, and tend to provide snippets of code to help others get on the same page when answering. 

Here is an example I found of a simple, but smart question:  


Q: [How to confine plot region to exact area](https://stackoverflow.com/questions/60750125/how-to-confine-plot-region-to-exact-area)
```
I would like to plot a box with a grid as in the code below:

    plot(rnorm(10), rnorm(10), type = "n", asp = 1, xlim = c(0, 1), ylim = c(0, 1), axes = FALSE, pty = "s", bty = "o", xlab = "", ylab = "")
    abline(h = seq(0, 1, 0.2), v = seq(0, 1, 0.2), col = "lightgray")
    abline(a = 0, b = 1, col = "lightgray")
    axis(1, seq(0, 1, 0.2), seq(0, 1, 0.2), pos = 0)
    axis(2, seq(0, 1, 0.2), seq(0, 1, 0.2), pos = 0)

but the lines exceed the area (0, 0) to (1, 1). Is it a problem with the plot region?

How can I confine the plot region to an exact area, for example from (0, 0) to (1, 1)?
```  

This question was concise and was posted in the right place with the correct tags to incite relevant users to interact. It even included their implementation and specified the intended and unintended outcomes. There are a few points you could make that might make it a weaker posting, such as the yes or no question in the second to last line, but in general, it still gets its job done and there are no hard feelings anywhere.

Because it was a relatively well structured question, they received a concise, yet clear answer:

A: 
```
    plot(rnorm(10), rnorm(10), type = "n", asp = 1, xlim = c(0, 1), ylim = c(0, 1), 
        axes = FALSE, pty = "s", bty = "o", xlab = "", ylab = "")

    axis(1, seq(0, 1, 0.2), seq(0, 1, 0.2), pos = 0)
    axis(2, seq(0, 1, 0.2), seq(0, 1, 0.2), pos = 0, las=1)


You can use *clip* to prevent annotations extending beyond the clip region. The four arguments determine the two coordinates of the rectangle for clipping.

    clip(0,1,0,1)
    abline(h = seq(0, 1, 0.2), v = seq(0, 1, 0.2), col = "lightgray")
    abline(a = 0, b = 1, col = "lightgray")

```

This answer gets the point across quickly and clearly. They provide an implementation example using the original code and the proposed solution, which in this case is a function, and a small explanation of how it is defined and what it does. In response to this answer, the poster replied and thanked the stranger for their input.

Here is an example of a bad question:

A: [Can one checkbox uncheck the other one automatically?](https://stackoverflow.com/questions/79761613/can-one-checkbox-uncheck-the-other-one-automatically)
```
How to get to the point where in libreoffice calc after checking one checkbox the other one with similar name uncheckes itself automatically?

Eg. checkboxes that represent dimentions of product - so the dimentions 1 and 2 cannot be picked at the same time.

I have checkboxes directly in the sheet.

I literally tried everything. In excel the whole thing took me like 1min, but libre seems not getting my point at all
```  

There's a lot that could be said is wrong about this question. First of all, it's not even clear what they're actually asking. There are multiple ways that first statement may be interpreted. Another thing is their grammar. It is more likely to deter someone from wanting to answer the question because it takes more effort to read it. There's also no images or examples of what they're attempting to do and they end the message with the amazing statement "I literally tried everything." Now, what does that mean? What exactly have you already tried so others know where you stand in your troubleshooting process? Not stating the things you've tried at all is also a big error. It shows that you truly have no clue what is happening and simply want someone else to do it for you.

As you might expect, this question actually got locked from being answered before even receiving an answer. And so, I asked ChatGPT to give me a response that matches the quality of this question and it gave me:

> “Just use a macro. You know, maybe use If CheckBox1 = True Then CheckBox2 = False somewhere. It should work. Good luck!”

Which tells me that it doesn't meet standard because it is simply too vague of an answer to be intuitively applicable as a solution. It doesn't provide any code examples or instructions on how to set it up to work, it simply says, "just do it" and leaves the poster to figure the rest out on their own. It may be a clue, if the poster didn't think about it, but otherwise, it's no help.

## In the end

Knowing the way to ask a question can more often than not save you from humiliation or from dealing with abrasive behavior. The most important thing to consider when asking a question is being as specific as you can be when describing your issue and what lead you to encounter it. Doing so allows responders to see the problem from a better perspective and give an answer thats closer to your specific case. It also helps to be polite and express your gratitude to anyone answering your questions on their own time. They don't need to be answering them. So, if you ever need to ask a question, it's in your best interest to make it a smart one.
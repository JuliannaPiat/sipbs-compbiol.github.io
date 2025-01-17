---
title: "How to Ask Good (Computational) Questions and Make Good Bug Reports"
categories: Student
tags: [advice, studentships, MSc students, Internships, supervision]
toc: true
toc_label: "Table of Contents"
toc_icon: "book-reader"
toc_sticky: true
author: Leighton Pritchard
---

This post is based on the excellent "How to report bugs effectively" by Simon Tatham, which can be read [here](https://www.chiark.greenend.org.uk/%7Esgtatham/bugs.html). Please do read it!
{: .notice--success}

## tldr;

- Be precise
- Write or speak clearly
- Be kind and helpful
- Provide at least enough information to solve the problem. Too much information is also good
- Avoid speculation, stick to facts
- Check elsewhere for answers first

## You want an answer, so be kind and helpful

When you ask a question, it's probably because you want or need an answer. There's less chance of getting the answer you need if the person you're asking is disengaged, and a quick way to disengage people is to make the process frustrating or unpleasant for them. It might be their fault that your problem exists, and you might be right to
be angry with them, but being obviously angry is a quick way to make people disengage. If you don't provide the pertinent facts, or are unhelpful, people are likely to become frustrated and disengage.

## Pretend that you're the one answering the question

Put yourself in that other person's place. Imagine that you've been asked the question you want answered. What information do you think you would need to see what the problem was? How would you want the information presented to you? How much information would you need?

The person you're asking is probably intelligent, but they might not have all the information you do and, without it, be unable to answer your question. They need information, and more information is almost always better than less.

## Write, or speak, clearly

If the person you're asking your question of can't tell what you mean, they can't answer your question. Or they may answer the wrong question. So:

- _Be specific_: It may be there are two (or more) options for how to do something. Say which one you mean precisely.
- _Be verbose_: Give as much information as you can, not as little as you think is necessary.
- _Use nouns, not pronouns_: In [Simon Tatham's post](https://www.chiark.greenend.org.uk/%7Esgtatham/bugs.html) he gives this example: "I started FooApp. It put up a warning window. I tried to close it and it
crashed." So, what crashed? If you're using pronouns like "it", you can't tell. It's better to write something like "I started FooApp, which put up a
warning window. I tried to close the warning window, and FooApp crashed."
- _Read your writing back to yourself_: If, after writing your question down, you can't understand what you were asking, how well is the persion you ask likely to understand it? If you gave any instructions for how to reproduce a problem, try them yourself - do you see the same problem?

## Distinguish between fact and speculation

When describing your problem, be clear to distinguish between _fact_ ("I typed this command, and got this error message.") and _speculation_ ("I think that the data file might be misformatted.") Your question might well be answerable if you don't speculate, but unless you share the facts, there's nothing concrete to work with. [As Simon Tatham notes](https://www.chiark.greenend.org.uk/%7Esgtatham/bugs.html):

> [You wouldn't go to a doctor and say:] "Doctor, I need a prescription for Hydroyoyodyne." People know not to say that to a doctor: you describe the symptoms, the actual discomforts and aches and pains and rashes and fevers, and you let the doctor do the diagnosis of what the problem is and what to do about it. Otherwise the doctor dismisses you as a hypochondriac or crackpot, and quite rightly so.

## Have you checked elsewhere to see if your question is answered

Broadly: have you Googled it? There are few questions that haven't been asked before, and many of them have answers online. One challenge in finding an answer online might be phrasing the question so that the search gives you something useful, and it's OK to ask for help with this, too! If you have already checked elsewhere for help, include that information when you're asking your question - it can save time if people don't need to revisit those resources to find the same unhelpful "solution" you did.

## Can you show the person what you're asking the question about?

Language is powerful, but imperfect. We omit small (but possibly important) details. We elide concepts together. We use inaccurate or ambiguous words. If you have an error message you're asking about, include it or show it. If you can demonstrate the problem you're having, do that. This gives the person you're asking more information than a verbal description could provide.

If you can't show the problem directly to the person you're asking, make your problem _reproducible_ so they can show themselves. Email the input data, your script, and an example of the output you see. Tell them the sequence of commands you ran, and what operating system you use. Give them all the information they need to see the problem you see.
{: .notice--primary}


---
layout: essay
type: essay
title: "Reflecting on Coding Standards"
# All dates must be YYYY-MM-DD format!
date: 2026-09-25
published: true
labels:
  - Coding Standards
  - ESLint
  - Software Engineering
  - ICS 314
---

## More Than Just Making Code Look Nice

Before using ESLint in ICS 314, I honestly thought coding standards were mostly about making everyone's code look the same.

Things like indentation, spaces, semicolons, naming conventions, and where curly braces go seemed important, but not necessarily important enough to affect whether someone was actually a good programmer.

After using ESLint for the first few weeks of ICS 314, I have started to look at coding standards differently.

I still think some of the rules can feel extremely picky, especially when I have a program that works perfectly but VSCode is still covered in red and yellow lines. At the same time, I am starting to understand that coding standards are not only about making code look pretty.

They force me to pay attention to how I am actually writing my programs.

And sometimes that is more useful than I expected.

<img width="1138" height="845" alt="image" src="https://github.com/user-attachments/assets/91ac61f7-161b-4303-8ab2-eafb15d2bc76" />


## The Program Works, So Why Is ESLint Mad?

One of my first reactions to ESLint was basically, "If the code works, why does this matter?"

I could run my program, get the correct output, and still have ESLint telling me that something was wrong.

That can be frustrating.

When I am trying to finish a WOD or assignment, my main goal is usually to get the program working. When I finally get the correct output, the last thing I want to see is another list of problems that I have to fix.

Sometimes it feels like finishing the program and then being told, "Actually, you're not done yet."

However, after dealing with ESLint more, I have realized that there is a difference between code that *works* and code that is actually written well.

A program can technically produce the correct answer while still being confusing, inconsistent, or harder to maintain than it needs to be.

That is where I think ESLint has started becoming useful for me.

## ESLint Is Annoying for a Reason

The red squiggly lines are probably the most noticeable part of ESLint.

At first, I treated them almost like obstacles. My goal was just to make them disappear so that I could say the assignment was finished.

Now I usually try to understand *why* ESLint is complaining before immediately changing something.

Sometimes it is something simple, such as an unused variable or inconsistent formatting. Other times, it makes me reconsider how I structured part of my code.

The interesting part is that ESLint sometimes points out things that would not necessarily stop the program from running.

That means it is teaching a different type of programming skill.

The compiler is mostly concerned with whether my program can actually be understood and executed. ESLint is also making me think about whether another programmer could understand what I wrote.

That distinction has become more important as our ICS 314 programs have gotten larger.

When an assignment is only a few lines long, messy code might not seem like a big problem. When there are multiple classes, functions, and files involved, it becomes much easier to lose track of what is happening.

## Coding Standards Can Actually Teach You

Something I did not expect is that coding standards can actually help with learning a programming language.

When I started TypeScript, I already understood a lot of the basic programming concepts from other languages. Variables, loops, functions, arrays, and classes were not completely new ideas.

What was different was how TypeScript expected me to express those ideas.

TypeScript is much more specific about types, and ESLint adds another layer by encouraging a consistent way of writing the language.

Because of that, I cannot always just write something in whatever way happens to work.

I have to think about whether the way I wrote it matches the expectations of the language and the project.

I noticed this especially during assignments such as the Jamba Juice exercises. As the programs became more complicated and started involving different classes such as menu items, drinks, orders, inventory, and stores, organization became much more important.

If every class and method were written in a completely different style, the program would become harder to follow very quickly.

Coding standards help prevent that.

They create expectations about what the code should look like before I even start reading it.

## Standards Matter More When Other People Read Your Code

I think coding standards make even more sense when I stop thinking about programming as something that only I am going to see.

If I write a program for an assignment and nobody else ever touches it, I can probably understand my own weird formatting and naming choices.

But software engineering is not normally like that.

Someone else might have to read, debug, update, or completely change the code later.

Even I might come back to something I wrote several months later and wonder what I was thinking.

Having consistent standards makes that situation easier.

If everyone on a team follows similar conventions, you do not have to relearn someone's personal programming style every time you open another file.

I think this is one reason coding standards are more important than I originally gave them credit for.

They are not only telling programmers how many spaces to use.

They are creating a common language for how a project should be written.

## The Painful Part Is Also the Useful Part

I would not say I suddenly enjoy fixing ESLint errors.

There are still times when I think I am completely finished with an assignment, run ESLint, and discover that apparently I have more work to do.

That is especially annoying when the mistake feels extremely small.

But I also think that inconvenience is part of why it works.

Without ESLint, I would probably ignore many of those smaller problems because the program already runs.

Having the editor immediately point them out prevents me from building the habit of saying, "That's good enough."

It also gives me feedback while I am programming instead of waiting until somebody reviews my code later.

That feedback is useful because I can usually connect the warning directly to whatever I just wrote.

Over time, I have noticed that I am starting to avoid certain problems before ESLint even has to tell me.

That is probably the biggest sign that it is actually teaching me something.

## Correct Code Is Not the Entire Goal

One thing ICS 314 has been making me realize is that software engineering involves more than getting the correct output.

The WODs have already shown me that requirements matter. A solution can return the correct answer but still be wrong if it ignores an important requirement.

I think coding standards work in a similar way.

A program can run correctly while still being poorly organized or difficult for someone else to understand.

Before this class, I probably would have judged most code by one question:

"Does it work?"

Now I think there are more questions that matter.

Is it readable? Is it consistent? Would another programmer understand it? Could I come back six months later and understand it? Would changing one part of the program create unnecessary problems somewhere else?

Coding standards do not automatically solve all of those problems, but they push programmers in the right direction.

## Getting Used to the Red Squiggles

My opinion of ESLint after using it in VSCode is somewhere between annoying and useful.

It can definitely be frustrating.

There are moments where I wish it would just accept that my code works and leave me alone.

At the same time, I would rather have ESLint point out a problem immediately than develop bad habits and discover them much later.

The more I use it, the less it feels like ESLint is simply criticizing my code.

It feels more like another form of feedback.

I still care about getting my programs to work, but I am starting to understand that software engineering asks for more than that.

Writing code is partly about communicating instructions to a computer, but it is also about communicating ideas to the programmers who will eventually read that code.

Coding standards help with both.

So I do not think I am ever going to be excited when VSCode suddenly fills my screen with red squiggles.

But at least now, when they appear, I understand that they are probably trying to tell me something worth fixing.

## AI Use

I used ChatGPT to help me draft and organize this essay based on my experiences using ESLint, VSCode, TypeScript, and coding standards in ICS 314. I also used it to help improve the grammar, flow, and structure of my writing. I reviewed and edited the essay so that the experiences and opinions discussed reflect my own perspective from the course.

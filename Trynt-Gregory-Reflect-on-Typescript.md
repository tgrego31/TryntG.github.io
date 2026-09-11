---
layout: essay
type: essay
title: "Learning Type Script WOD after WOD"
# All dates must be YYYY-MM-DD format!
date: 2026-09-10
published: true
labels:
  - Typescript
  - Software Engineering
  - ICS 314
---

## Getting Comfortable With Being Uncomfortable

When I first started doing the TypeScript WODs in ICS 314, I thought the hardest part would be learning TypeScript itself. I already had some programming experience, so I figured that once I understood the syntax, everything else would be pretty straightforward.

That was not really what happened.

The syntax was not the biggest problem. The harder part was being given a problem, understanding what it wanted, writing the code correctly, testing it, and doing all of that while thinking about how much time I was taking.

There were a few times where I looked at a quiz and thought it would be easy, only to spend way more time on one small part than I expected. Other times, my code was technically working, but I misunderstood what the output was actually supposed to represent.

After doing more of these quizzes, I started realizing something: getting better at programming does not necessarily mean the problems suddenly become easy. Sometimes you just get more comfortable dealing with the difficult parts.

## In the context of TypeScript

So far, I actually like TypeScript.

A lot of it feels familiar because ideas like variables, functions, arrays, conditions, and classes are things I have already seen in programming. The main difference is that TypeScript is a lot more specific about what kind of data I am using.

At first, writing things like `string`, `number`, or `string[]` felt like extra work. If I already know that a variable is supposed to hold a number, why do I need to say it again?

After working through more assignments, though, I started understanding why that can be useful.

The Jamba Juice quizzes were probably the best example of this for me. At first, we were representing simple things like menu items. Then we started adding drinks, orders, inventory, and stores.

Once the program became larger, having everything clearly defined started making more sense. A `MenuItem` has its own information. A `Drink` represents something a customer actually orders. The inventory has another responsibility.

Instead of putting everything into one giant function, the program is separated into different parts that each have a purpose.

I think this is where TypeScript started feeling less like just another language and more like something that makes sense for software engineering.

## In the context of programming

One of the things I have learned from these quizzes is that mistakes are not always where I expect them to be.

The Wind Chill quiz is one example.

I remember putting in a temperature and getting an answer that was much colder than the temperature I entered. My first thought was basically, there has to be something wrong with this code.

But the code was doing what it was supposed to do.

The problem was that I was thinking about the original air temperature instead of what the wind chill formula was actually calculating. The output was supposed to represent how cold it feels because of the wind.

That was kind of a simple mistake, but it taught me something important. Sometimes debugging is not about immediately changing the program. Sometimes I need to stop and make sure I actually understand the problem.

The Heat Index quiz caused a different issue. The formula itself looked horrible because it was so long, but the thing that gave me more trouble was actually the categories afterward.

If one category ends at a certain number and another begins right after it, I have to be careful about where I use `<`, `<=`, `>` or `>=`.

Being off by one number can make the whole test case wrong.

Before these assignments, I probably would have looked at those boundary values as a small detail. Now I realize those small details are usually where problems show up.

## In the context of requirements

The Surf Scoring quiz also made me realize that getting the correct answer is only part of programming.

The scoring idea itself was not too crazy. Five judges give scores, the highest and lowest are removed, and the middle three are averaged.

But then there was another requirement: we were not allowed to use functional programming methods like `.map()` or `.reduce()`.

That changed how I had to think about the solution.

Technically, I could probably write different versions of the program that all return the same answer. But if one of those versions ignores the requirements, then it is still wrong for the assignment.

The Cornhole quiz made me think about this too. Scoring a few bags seems simple until you start thinking about multiple rounds, cancellation scoring, or what happens if someone goes past the winning score before all the rounds are finished.

There always seems to be one extra condition hiding somewhere.

I am starting to think that this is probably closer to actual software engineering than just solving random coding problems. In real projects, you cannot just say, "Well, my program works." It has to work according to what someone actually asked you to build.

## In the context of WODs

The WODs are probably the part of this module that I have the most mixed feelings about.

I understand why we do them.

I also do not exactly enjoy watching a timer while I am trying to remember why my code is not working.

When I normally program, I like being able to try something, run it, change it, and think about the problem for a while. When I am doing a WOD, there is always the thought in the back of my head that I am taking too long.

Sometimes that makes an easy problem feel harder than it actually is.

At the same time, I have noticed that repeating WODs really does make a difference.

The first time I see a problem, a lot of my time goes into figuring out how I am even going to start. After practicing similar problems, I spend less time staring at the screen and more time actually writing the solution.

The `isUnique` WOD is a good example. Once I understood what the problem was asking and had practiced the general idea, it became much easier to approach.

The problem did not magically change. I just became more familiar with it.

The estimation logs have also been interesting because they show me how bad I can be at predicting how long programming will take.

Sometimes I think something will be quick, and then one little bug takes up most of my time.

I guess that is another part of the athletic software engineering idea. It is not just about getting faster. It is also about understanding how you work.

## In the context of software engineering

At the beginning of the module, I thought being good at these WODs would mostly come down to knowing TypeScript really well.

Now I think it is a combination of things.

I need to understand TypeScript, obviously, but I also need to read the requirements carefully, recognize patterns, test boundary cases, and avoid panicking when the first thing I try does not work.

I still think the WODs are stressful. I do not think I am ever going to look at a timer while coding and think, "This is relaxing."

But I do think they are helping.

The Wind Chill and Heat Index quizzes made me more careful about understanding formulas and ranges. The Jamba Juice assignments made classes and objects feel more useful instead of just being concepts from a textbook. Surf Scoring and Cornhole made me pay more attention to requirements and edge cases.

And after doing all of them, TypeScript itself is starting to feel more normal.

So if I had to describe my experience with this module so far, I would not say that programming has gotten easier.

I think I am just getting better at being uncomfortable when something is difficult.

And maybe that is the point.

## AI Use

I used ChatGPT to help me organize my ideas, remember some of the ICS 314 quizzes I worked on, and improve the grammar and structure of this essay. The experiences and opinions discussed in the essay are based on my own work in ICS 314.

---
layout: post
title: TCS Overview
date: 2024-03-26
description: my take on Theoretical Computer Science
tags: TCS
categories: TCS
---

Here is my take on Theoretical Computer Science:

One misconception I had before coming to CMU about *computer science* was that it was just about writing code. Although I do spend a lot of time programming, computer science is a lot more than just code. The way we define computer science is that it is a study of *computation*. Well, what is computation? 

Computation could be many things. Like the name suggests, our computers (laptops, phones, etc) are performing computation when we run our Python code, browse the internet, or watch YouTube. It is also valid to talk about calculators since they can "compute" the answer to your math equation. You could also argue that our brains are performing computation as the neurons fire signals to each other and the brain processes information given by the senses. However, in the most general sense, computation is defined to be the manipulation of information. This is very concise, general, and simple in a sense that all the examples above can still be described as computation. 

Visually, you can imagine giving some input information to a computation. Then, the computation will manipulate the information and produce some output, which, hopefully, is something useful. The device or machine that performs the computation is called a *computer*. Another big term used frequently in CS and in real life is an *algorithm*. The word fits our formalization well in that an *algorithm* is the description or specification of how the computer works. Just like when writing Python code, we need to give the computer specific instructions on how to manipulate information. Based on these instructions, the computer will take the input, manipulate it, and produce the output according to our algorithm. 

Great! Now, we defined *computer science* as the study of *computation*. And we have *computers* that perform computation based on its specification, *algorithm*. What now? What is a computer good for? 

In real life, we use computers (aka devices that perform computation like our phones) to generate some output that we desire. More specifically, we have some problem that we would like to solve, and we would like to use computers to solve them. This leads to the idea of a *computational problem*. In mathematical terms, we can see a computational problem as a function that maps inputs to outputs. Given some input, there is some specific output (or answer) that we would like to derive. So, a computational problem specifies what these input, output pairs are. We would like to use a computer by feeding it inputs, so that it outputs the desired "answer". If such a machine exists, then we can say that the computer *solves* the computational problem. A good example is the multiplication problem. This problem expects that given two numbers as input, the correct output be the product of those numbers. 

This leads to a very logical question. Which problems can we solve? Which problems can't we solve? Clearly, the multiplication problem can be solved. Just use the grade school method of multiplying two numbers. But are there more complex problems? What are the limits of our computers? This is the study of computability. 

Then, the next question might be: which problems can we solve *efficiently*? The keyword is *efficiently*. This is important because in real life, there are feasible limits to how much computational resources we have. Thus, we would like to reason about different problems and their inherent computational complexity. There are many different "computational resources" that we can reason about. The main ones are time and space. Overall, this branch of study is the study of complexity theory. 

Another good question to ask is: how do you actually solve these problems? In other words, what is the algorithm to solve the multiplication problem, for instance? How "good" is the algorithm (in terms of resource usage like time and space)? Can we come up with better algorithms? This describes the subfield of algorithm design and analysis. 

All the definitions said above are general, but it is not specific in a sense that we don't know how to concretely reason about these ideas. The field of *theoretical computer science* formalizes these ideas using *mathematical models*. By doing so, we can logically reason about computation and come up with insightful conclusions. The best example for this is a *Turing machine*. A Turing machine is a powerful model of computation that happens to capture all of the computation physically realizable in the universe. Using Turing machines as a mathematical model, we can reason about questions like which problems can be solved, and which problems can be solved efficiently. 

This is my understanding of the field of *theoretical computer science*, described in general, non-technical terms. Computer science overall is a very big area of study that has connections to all aspects of study and life. And theoretical computer science is the very backbone of all of it!

Resources:
- CMU 15-251
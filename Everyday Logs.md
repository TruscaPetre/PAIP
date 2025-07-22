## Goal: AGI - Artificial General Intelligence - day 1

Current systems: Empirical, Alchemy, No clear Explanation of how the system works. We don't understand how current systems work. - Not sustainable. ie the development will plateau. 

Let's think about this problem from first principles. 

## LLM problems - day 2

Classical Machine Learning can be compared to a look-up table. This is limiting the reasoning to the training dataset. 

Current system are not optimizing towards thinking, they are only modeling existing knowledge. 
Giving an answer that a human likes does not solve creativity. 
Learning from your own mistakes allows you to achieve a goal as a human. A language model does not try and fail to solve a problem. It what it learns and tries and fails is to model. 

Key insights into thinking are found in:
- The working memory. 
- Working with abstractions, building abstractions. 
- Asking the right questions.

## LLM problems - day 3
Asking for clarification is a problem for GenAI sometimes not asking enough, sometimes asking too much for clarifications. The underlying problem is how the system is treating ambiguity of language. 

Richard Feynman - "I am smart enough to know that I am dumb." 

Hallucinations - Confidently answering wrong.
- Wrong answers are fine because they are better than no answer in solving a problem. 
- SOMETIMES You can iterate on top of the wrong answer to arrive eventually to the correct answer.
	- On difficult complex problems can get stuck, more details and context does not unblock the model, and iterations cannot continue progress.

## Iteration 4 - Knowing versus Solving

LLMs don't know what they don't know. 

Asking a human: "Do you know X?". A human will answer:
- I don't know X ( more like a feeling )
- I don't know X now to describe, but I know a place where I can find it
- I know X
	- Recalling it from memory. 
	- I know that I knew X in the past, but I forgot it. But I know how to find it out. When I find I would have a high confidence in its truth. ( feeling for a human )
- I can try to find what X is
- I can try to build X 

Problem Solving - of difficult complex scenarios which AI models can't solve yet require cognitive skills which we are also using during the development of the project. We will pay attention to the methods and skills of the thinking used in trying to solve this problem, we will make them explicit, than we will add those during the development of the system. 
- Experiments should be the engine of discovery and Creativity for difficult problems, propose an assumption or a theory and than try to prove it wrong. Falsifiable theory that you test. #ThinkingPrinciple

## Iteration 5 - Review and Restructure

#ThinkingPrinciple 
For the purpose of integrating new ideas into the structure of the project we are doing : Review the ideas which we have collected during the idea gathering phase. For example brainstorming, field research, sota research, review papers of the field, and so on. 

## Iteration 6 - Review and Integrate
Apple example of the tower of hanoi. I may be wrong. But the idea is that the model gives the most popular answer in the dataset instead of the "best answer". 
An example - in software development, if you use generative AI for creating code, many times you have to review and edit the code yourself. 

#FirstPrinciple
I want the system to be able to debug software, build software. 
#FirstPrinciple 
The system will answer the questions of the user in language if prompted.

## Iteration 7 - Metacognitive abilities
When we are integrating new ideas into a structure. We gain some benefits for dealing with those ideas as humans. 
- Knowing what ideas to ignore and what ideas are important. 
- Faster navigate the text/content, to find things faster, to search for them. 
- It easier communicate the main ideas
- Avoid getting lost in the details 

When integrate ideas into a model, the model gets better. 

LLMs perform a needle in a haystack. Instead of requiring a structure in the text they have to process.

Humans escape the loop of getting stuck doing the same thing because they get bored. 

## Iteration 8 - Metacognitive skills

Humans prefer to see a small part of the project or any text materials and prefer to see that part at the same level of abstraction. Because we a very limited working memory. Maybe this skill and other skills that humans use to handle a large text, are not only useful for humans to work with complex knowledge, but they could also be absolutely necessary for LLMs to further increase their performance. 

LLMs take things to extreme, for example: staying unbiased taken to extreme makes you lazy, having unlimited energy taken to extreme makes you stay stuck in doing the same thing which is failing. Maybe we can let go of taking things to extreme by the system. Instead of manually explaining the behavior of the system, there should be an internal regulating system, like homeostasis based on many external perceptions. 

## Iteration 9 - What are first principles

Sometimes human come up with more ideas and better ideas make easier connections if we eliminate possible predictions for a solution instead of looking for the correct solution. 
eg: when you a multiple choice test, 
Through negation, inverting the problem the problem. 

### First principles
Having a lot of examples, and those examples are contrastive, not identical examples. If you filter out the differences between the examples, and you are left only with essence, that is a first principle.

***"Always?" - "Is this always true?"***
- If you find Exceptions in an explanation/idea => not a first principle
- You can't find an exception, you can't find a contradiction, you can't take it into a context where it becomes false, taking it to extreme still doesn't make it false => a first principle in a more general and perfect sense and absolute
	- Even if you find ways in which something is sometimes false, but those never occur in reality and in practical that => we need just practical first principles

## Iteration 10 - Confidence, Complexity, Abstraction

ChatGPT, sometimes goes and searches the web before answering an idea, but sometimes it is able to just come with an answer. That must be based somehow in a confidence metric for answering the question correctly. 
The concept of confidence should exist in a system to give better answers. Even if better means "I don't know". 

Complexity is something that humans struggle with. Humans use techniques to manage the complexity of a problem. This is really obvious in programming. Maybe the most important concept in software engineering is managing layers of abstraction. We hide the complexity in abstractions and only deal with a few components which are necessary for the part of the system that we want to build at the moment. 
We can navigate those layers of abstraction, and make incremental progress by hiding what is not necessary at the moment. Because of our limited working memory, we forget, it is outside of our working memory everything that is not necessary at the moment to make a tiny increment in the progress of the problem. 

LLMs keep everything in the working memory in the context window. They don't have to deal with abstraction layers. So maybe because they don't use those abstraction layers, they fail to solve problems that humans can. 

## Iteration 11

#TODO How do we build and abstraction? What part of the content do you hide? How much of it do you hide? 
- We should think about first principles, taking a lot of examples, and selecting only the common part among them, and what remains are details that can be hidden by an abstraction. 

Testing is an essential part of thinking, and when ideas are tested, the goal is used to validate the test. If the proposal makes the solution get closer to the goal, than it "passes the test".
IE, ***"Is this useful?"***


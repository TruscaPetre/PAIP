# Welcome Fellow Science Heretics!
My youtube channel: [Petre's AI Project - YouTube](https://www.youtube.com/@P.A.I.P)

This project is based on Obsidian editor. Use it in your fork.
[[Everyday Logs]]
## Goal
- Revolutionize AI by thinking from first principles
- Eliminate the Problems, Limitations of current systems

## Limitations & Problems of existing systems (LLMs)
- Creativity is limited
	- The capability of the system is bounded by the training dataset
		- Addressed a little bit by in context learning, but if the problem is too complex the system breaks
	- Doesn't Try new ways to approach a problem
- Stopping criteria for providing an answer is not sufficient. 
	- Stopping answering even if improvements can be made to the answer
- Not Treating ambiguity with asking questions
- Hallucinations - Confidence
	- Doesn't know what it doesn't know, and tries to give answers even if it cannot
	- Failed solution and to hallucinations, is that the style of the answer is forcefully "nuanced"
		- Consequence is that LLMs become lazy and they just all the possible answers(good and bad) and let the user decide for himself.
		- Failing to answer obvious questions because of trying to remain unbiased. 
- Getting stuck in back and forth user interactions
	- Not being able to explain our problem in such a way that we get what we want out of the system. Ie The system is not capable of understanding the problem such that it can solve and deliver what the user wants.
	- They don't get bored
- Sycophant

### Failing to navigate abstraction layers
- LLMs fall of a cliff when problems start to become more complex, 
	- catastrophic failure with just a little bit more complex problems

## Principles for AI thinking, Metacognitive skills

#FirstPrinciple

- Making Proposals
	- There is an idea gathering phase
	- The idea gathering can be from many sources, such as memory, observation, internet, search, discussions and dialogue. 
	- Not always necessary, but powerful #TODO decide when is necessary and when it is not for our system
- Testing - Making experiments
	- We try things because we can't know the outcome for sure, so in the process of pursuing a new thing which we don't know how will turn out in the end, we can discover new things.
		- Potentially overcoming the limitation of creativity of LLMs
	- Making mistakes even if giving wrong answers, being able to iterate on those and improve the answers, instead of doing one shot on the problem
		- This already a little bit addressed by OpenAI o1 and o3, deepseek r1 kind of models, so called reasoning models
- Review 
	- Looking at ideas with fresh eyes after some time.
	- Looking for mistakes
	- The result of reviewing ideas is a feedback. Positive feedback is kind of useless. Negative feedback shows us a way in which we can improve the proposals 
- Abstractions
	- What ideas you ignore and what ideas you focus on, what ideas are important and what are the just details, is in the scope of abstractions. Building abstractions allow us to hide complexity.

## Theories of Improvements
These ideas are experiments to be tested in the system which we develop and implement.

### Making models use Abstractions
Theory: Maybe our limitations have pushed us to develop abstractions in problem solving which LLMs don't have by default as a tool, just implicitly use it. So Maybe if we create a framework to use abstractions the reasoning would get better?

Working memory of humans is very limited, but context window, is very large for LLMs. Humans have developed other skills to deal with difficult problems which require a larger working memory. Those other skills, are like:
- Abstraction allow us to solve problems which LLMs can't solve, 
	- deconstruction of the problem into smaller problems which are easier to solve [[README#Failing to navigate abstraction layers]]
	- Analogy with - Chain of Thought 
- A problem can be solved in multiple ways ( Analogy with - Tree of Thought)

### Making models get bored
Theory: Maybe making models get bored, will help them escape from the loops in which they get stuck.


## Other ideas 
PDF - structure
- P = Problem / Pain , Goal, Need, Want
- D = Details / Data , Context, Constraints, Limitations, Prerequisites
- F = Fix, Solution, Value, Implementation

## Implementation
These ideas are a must have in the system which we will work on.

At the moment the best natural language interface technology are LLMs. They are good for formatting the answer and ingesting the answer. We will have an API call to an LLM to ingest questions, deliver answers to the user.

Since the system should be competent programmer. It should also be able to program itself, since itself is software, so in order to program itself, it should be similar to cursor, codex. 


--- 

TODO List:
- Integrate day 7
- Finish Integrating until yesterday
- Clarify and improve the goal
- Read my notes about first principles and bring them into a next iteration - maybe on iteration 12
- After exploring "enough" the concepts of : layers of abstraction, first principles thinking, PDF framework, creativity, we will start developing the system in software
- Find the new ideas that will solve the limitations of current systems

--- 

Iteration Structure
- General Thoughts
- Create a new iteration in [[Everyday Logs]]
- Integrate the last previous iteration
	- Metacognitive skills used in the development of PAIP become skills of the AI system we create
- Any new thoughts that come up in the iteration at the moment add new notes for them
- Add todos for next ideas
- Start some practical software development
# Agent-Based Modeling
## Overview
My personal notes and projects from the [Introduction to Agent-Based Modeling class](https://www.complexityexplorer.org/courses/121-introduction-to-agent-based-modeling) offered online through the [Santa Fe Institute](https://santafe.edu).

# Notes
## Unit 4
### BehaviorSpace
A built-in tool within NetLogo to allow repeated runs over a range of parameter inputs.
It can be run headless to improve speed.
The instructor shows how to analyze the data output from BehaviorSpace in R. There's not a lot of context or lead up to this R section (4.5 video).

# Final Project
I want to build a model to answer questions related to (engineering) team management and movement between teams as the workloads change. One potential way to do this would be to have an A and B team with different strategies for team management based on when people are requested to move to the team based on the currently available work.

* Based off of Sugarscape.
* Use the same idea of two high points in the environment for the work stream of each team
    * I'd like to add more variety to the environment, such that the work streams can fluctuate over time.
    * One simple way to add variety is to create the environment with random distribution of work
    * In the case the landscape is random then I think agents need some cohesion through links to move as a unit
* I'd like to either use breeds or color-coding to indicate the different teams that each agent is a member of.
    * I think they need links to force some level of cohesive movement. Basically to visually constrain their search area for work.
* One of the central ideas I started on this subject with is the question about time to ramp up on domain knowledge. So I think new agents who join a team need to have some time delay in getting to the maximum work rate. 
* On the reverse side I think agents probably need to either be "fired" or in some way penalized for having an empty work queue for too long.
* What's the limiting factor in the model from hiring tons of workers? There has to be some counter balance to infinite hiring.
    * Maybe whenever a new member joins the team it costs all the members of that breed a small amount of maximum work potential - they work a little slower for a period of time

## Strategies?
* Fire based on FIFO?
* Fire whenever work queue is empty for X number of turns?

## Roadmap
* [x] Create 2 teams
* [x] Make the environment sparser. Agents don't have to actually search, work is everywhere.
* [x] Measure team output in a graph
* [ ] Allow different strategies for each team
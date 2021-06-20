# Agent-Based Modeling
## Overview
My personal notes and projects from the [Introduction to Agent-Based Modeling class](https://www.complexityexplorer.org/courses/121-introduction-to-agent-based-modeling) offered online through the [Sante Fe Institute](https://santafe.edu).

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
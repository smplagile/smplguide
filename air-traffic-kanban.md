Consider the following:

You're an air traffic controller. You are given a kanban (board with multiple columns). You are asked to design this board to minimize the number of air traffic incidents and maximize on time and safe landing outcomes.

Go!

The typical kanban consists of a few columns. The usual suspects look something like:
1. To do
1. In progress
1. Blocked
1. Done

With that in mind, it would make sense to relable the columns so that we have the following:
1. To do --> In flight
1. In progress --> Approaching
1. Blocked --> Circling?
1. Done --> Landed

At first glance, this seems to be a workable solution. It's a state macchine. In fact, it's a basic state. It maintains 4 states. But the reality is that quantitative data, the direct measurement data is 

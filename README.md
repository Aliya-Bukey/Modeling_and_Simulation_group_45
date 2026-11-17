# Cooking Process

Group: **45**
Course: Modeling and Simulation, TU Wien

## Idea

Simulation of a cooking recipe (tasks, resources, prerequisites) and search for the task order with the shortest total cooking time.

## Team

- Student 1
- Student 2
- Student 3
- Student 4

## Questions
1. Is there a required length for the report, and do we have to use a specific template?
2. How detailed should the recipes be? Is there a minimum or maximum number of steps?
3. Can we implement the model in Python, and may we use a simulation library like SimPy, or should we write the event handling ourselves?
4. Should identical resources (e.g. 4 burners) be modelled as a pool with a count ("any free burner"), or strictly as separate resource IDs as in the spec?
5. Can a task have no resources at all (e.g. "dough rises for 60 min"), and is it fine to split tasks, e.g. "put in oven" (cook + oven) and "baking" (oven only)?
6. How should we handle constraints the model can't express, like a pan staying busy between two tasks or maximum waiting times (dough must not over-rise)? Should we extend the model or simplify the recipes?
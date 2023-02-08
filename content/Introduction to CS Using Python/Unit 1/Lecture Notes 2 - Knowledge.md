# 600.1 - Video: Knowledge

**Computers Have Two Types of Knowledge:**

- **Declarative**
	- 'Statements of Facts/Truth'
	- It declares or states that something is a fact
	- Eg. The pipe is leaking. -> It doesn't tell why it's leaking or how to fix it

- **Imperative**
	- Is a recipe.
	- it gives a step-by-step guideline of how to perform a task
	- The knowledge of the *how* to information
	- *A sequence of steps to a solution*
	- Very mechanical

**Numerical Example:**

**Square root of number:**
- Declarative approach
$$let \space \sqrt{x} \space = y \space | \space y^2 \space = x$$

- Imperative approach

 Old 'recipe'[^1] for imperatively determining the square root
 1. let *g* = guess
 2. if g * g is close to x -> stop, return g
 3. else -> make new guess by averaging g and x/g
 4. Repeat prior steps until right guess is made, using result of step 3 as step 1's guess
___

[^1]: [Hero of Alexandria - Wikipedia](https://en.wikipedia.org/wiki/Hero_of_Alexandria)
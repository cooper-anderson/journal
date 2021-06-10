# journal

## Week 1

### Summary

> TODO: upon week completion

### Goals

- [x] Grasp a deeper understanding of the research project’s underlying concepts
- [x] Develop a CTRNN library in JavaScript/TypeScript
- [ ] Provide a visualization of the library for demonstration purposes

<!-- ### 2021-06-11 -->

<!-- > **Day 5 `Friday June 11th, 2021` `hr`** -->

<!-- - -->

<!-- ### 2021-06-10 -->

<!-- > **Day 4 `Thursday June 10th, 2021` `hr`** -->

<!-- - -->

### 2021-06-09

> **Day 3 `Wednesday June 9th, 2021` `7hr`**

- Organized journal to log my progress
  - Time tracking is still done manually, I hope to make it more streamline
- Began brainstorming a `rl-ctrnn` library that runs on top of [`ctrnn.js`]
- Skimmed through some of the references Dr. Yoder linked to for the research
- Continued work on the interface for [`ctrnn-visualizer`]
  - I want to get a working version first that does supports basic
    non-reinforcement learning CTRNN models
  - I plan to incorporate the oscillating weights RL model after this prototype

### 2021-06-08

> **Day 2 `Tuesday June 8th, 2021` `6hr`**

[`ctrnn.js`]: https://github.com/cooper-anderson/ctrnn.js
[`ctrnn-visualizer`]: https://github.com/cooper-anderson/ctrnn-visualizer

- Looked into how "common" CTRNN libraries allow the user to interface
- Created a custom [`ctrnn.js`] library outline tailored to our needs
  - Not fully completed yet, and still needs more test cases
- Started work on [`ctrnn-visualizer`] to go along with [`ctrnn.js`]
  - Mainly waiting for the completion of the backend

### 2021-06-07

> **Day 1 `Monday June 7th, 2021` `7hr`**

- Read through research proposal document
- Read documentation on existing CTRNN implementations in JS
- Decided to write a library from scratch as no existing libraries fit our
  needs without a decent amount of integration
- Began brainstorming different ways of displaying information to the user for
  the CTRNN visualizer
- Began brainstorming which aspects/parameters the user should be able to
  control in the visualizer

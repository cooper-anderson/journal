# journal

## Week 2

### Summary

> TODO: upon week completion

### Goals

- [x] Provide a visualization of the library for demonstration purposes
- [x] Write a PhasePortrait React component
- [x] Replace live neuron view with phase portrait
- [ ] Begin reading about Microbial Genetic Algorithms

### 2022-06-18

> **Day 9 `Friday June 18th, 2021` `4hr`**

- Read through The Microbial Genetic Algorithm multiple times to verify my
  understanding of the concept before putting it to use.


### 2021-06-17

> **Day 8 `Thursday June 17th, 2021` `10hr`**

- Rewrote code to accept new external node activation array system
- Wrote a React component that renders a phase portrait using HTML canvas
- Made visualizer iterate over a 20x20 grid of starting activations, and graph
  their outputs from the ctrnn on the phase portrait
- Made the phase portrait update in realtime on changes to the parameters

### 2021-06-16

> **Day 7 `Wednesday June 16th, 2021` `9hr`**

- Began rewriting ctrnn library to use an external node activation array
  - This is preferable as it allows for an easy way to test what the outcome
    would be from all possible states.
- Began using this new external node activation array for the phase portrait
- Began working on the visuals of the phase portrait
- (now there is an empty space on the visualizer, perhaps we can put some other
  statistic/view there in the future)

### 2021-06-14

> **Day 6 `Monday June 14th, 2021` `10hr`**

[`cooperuser.dev/ctrnn-visualizer`]: https://cooperuser.dev/ctrnn-visualizer

- Provided a realtime view of the oscillatory behavior in the visualizer
- Created a parameters panel that allows the user to configure the network
- Created a static view of the first seconds of simulation of the network
  - Smooth continuous updates when the user alters a parameter
- Expose at a public url [`cooperuser.dev/ctrnn-visualizer`]
  - Secure with an SSL certificate (HTTPS protocol)

## Week 1

### Summary

> TODO: upon week completion

### Goals

- [x] Grasp a deeper understanding of the research project’s underlying concepts
- [x] Develop a CTRNN library in JavaScript/TypeScript
- [ ] Provide a visualization of the library for demonstration purposes

### 2021-06-11

> **Day 5 `Friday June 11th, 2021` `7hr`**

- Succeeded in having [`ctrnn.js`] mimic the behavior of [`madvn/CTRNN`]
  - Network now allows for sinusoidal behavior instead of steady state
- Started integrating the graph/histogram for [`ctrnn-visualizer`]
- Read/skimmed through the next 2 resources

### 2021-06-10

> **Day 4 `Thursday June 10th, 2021` `5hr`**

[`madvn/CTRNN`]: https://github.com/madvn/CTRNN

- Read/skimmed through the first 5 resources supplied by Dr. Yoder
- Analyzed the [`madvn/CTRNN`] python library
  - Started using the readme's example as a model for [`ctrnn.js`]

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

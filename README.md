# neuroforge

NeuroForge is an exploratory project focused on building and training biologically inspired neural models from scratch. The project centers on leaky integrate-and-fire (LIF) neurons and surrogate gradient learning, with the long-term goal of applying these models to embodied systems like simulated robotic arms.

Rather than optimizing for performance, NeuroForge emphasizes understanding neural dynamics, temporal behavior, and the practical challenges of training spiking models.

---

## What’s Implemented

* Leaky Integrate-and-Fire (LIF) neuron model
* Surrogate gradient method for training through spikes
* End-to-end training loop for simple temporal tasks
* Visualization of membrane potentials and spike activity

All functionality is currently implemented in a single Python file to keep experimentation lightweight and easy to iterate on.

---

## Tech Stack

* Python
* NumPy
* Matplotlib

---

## Key Takeaways

* How LIF neurons accumulate, leak, and spike over time
* Why surrogate gradients are necessary for training spiking models
* The difficulty of debugging and stabilizing temporal neural systems

---

## Next Steps

* Extend tasks to simulated robotic arm control
* Add animations of agent behavior
* Experiment with alternative neuron models and learning rules

---

*NeuroForge is an evolving research-driven project built to develop intuition at the intersection of neuroscience, ML, and robotics.*

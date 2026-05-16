# Vishal Joshua Meesala
Machine Learning Researcher

Inference-time control · Multi-agent coordination · Autonomous space systems

---

## Research

I design control mechanisms that operate at inference time, monitoring the internal reasoning dynamics of foundation models and intervening when structural instability is detected, without retraining and without added computational overhead.

The foundation of this work is making a precise signal explicit: where in its latent trajectory a model is operating within structurally reliable regions, and where it is not. Drawing on nonlinear dynamics and Lyapunov stability theory, I build architectures that carry this awareness intrinsically, enabling adaptive modulation of computational depth at the moment it is needed. The target setting is high-stakes deployment where inference precision directly determines outcome quality.

This work extends into multi-agent systems operating under hard physical constraints: communication dropout, hardware degradation, and the absence of centralized control. The application domain is space robotics, including swarm coordination for lunar surface operations, distributed aperture synthesis, and autonomous subsurface mapping.

---

## Perspective

The unifying principle across this work is that robustness should be intrinsic to an architecture rather than imposed from outside. Autonomous systems operating in physically constrained environments perform most reliably when the sensor pipeline, the state estimator, and the decision layer are designed as a coherent whole. My work is oriented toward that integration, building from signal-level foundations upward through coordination and control.

---

## Methods and Tools

**Machine learning:** Inference-time control, meta-learning, multi-agent RL, invariant representation learning, foundation model internals

**Mathematics:** Nonlinear dynamical systems, Lyapunov stability theory, latent geometry, discrete-time ODEs, constraint projection

**Systems and software:** PyTorch, NumPy/SciPy, Hugging Face, RLlib, PettingZoo, FastAPI, Linux/Bash

---

## Connect

Open to connect with researchers and teams working on autonomous space systems, multi-robot coordination, or resilient distributed inference, particularly in the context of NASA CADRE-adjacent architectures, lunar autonomy, or space-based distributed sensing.

*Active repositories are in early development. This profile reflects current research direction, not completed systems.*

# hopfion-propulsion-sim
High-performance Rust simulation of topological Hopfion solitons for emergent spacetime metric engineering.

Overview

⁠hopfion-propulsion-sim⁠ is a high-performance simulation engine written in Rust, designed to model the interaction between topological defect structures (Hopfions) and emergent spacetime geometry. This project explores the theoretical possibility of engineering metric gradients at the quantum-mechanical substrate level to achieve non-classical propulsion.
Key Features


 Topological Soliton Dynamics: Implements a full chiral Hopfion ansatz using an N \times N \times N lattice.

 
 Metric Engineering: Features an integrated gradient generator that couples Hopfion topology to Regge curvature tensors.

 
 Resonant Stability: Utilizes a custom damping/chirality constant (0.618) to maintain self-sustaining limit cycles.
 
 
 High-Performance Compute: Optimized for ⁠ndarray⁠ to handle complex lattice updates and Landau-Lifshitz-Gilbert (LLG) evolution.


Technical Architecture

This simulation treats gravity not as a fundamental force, but as an emergent property of information density. By applying a propulsion gradient, the engine forces a localized redistribution of momentum, effectively creating a "topological hill" that the system center-of-mass traverses.


 Lattice Size: Configurable N.
 Dynamics: LLG update cycle with exchange and DMI approximations.
 Validation: Monitors Jacobson equivalence (G/8\pi T) to ensure physical consistency with General Relativity.

 
Getting Started
1. Dependencies: Ensure ⁠rust⁠ and ⁠cargo⁠ are installed.
2. Build: ⁠cargo build --release⁠
3. Run: ⁠cargo run⁠

   
License
This project is licensed under the GPLv3 License.


Research Context
This simulator is a core module of the ONIX (Universal Simulation AGI) ecosystem, developed to bridge the gap between quantum-substrate information dynamics and macro-scale propulsion hardware.

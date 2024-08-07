---
name: 'Coq Formalization of Orientation Representation: Matrix, Euler Angles, Axis-Angle and Quaternion'
speakers:
  - Zhengpu Shi
  - Gang Chen
categories:
  - Verification and Testing
links:
  - name: https://
    absolute_url: https://
    icon: newspaper
---

**Presenter**: TBA
**Session Chair**: TBA

Rotation matrices, Euler angles, axis-angle, and unit quaternions are common models for representing object pose in space.
Each offers distinct advantages and disadvantages regarding handling singularities, computational complexity, and storage requirements, motivating their interchangeability and conversion algorithms.
However, these models and their associated algorithms involve complex matrix operations, trigonometric computations, and geometric reasoning, making manual derivation and verification error-prone.
To guarantee algorithm correctness, we present a formal verification of these models and their conversion algorithms within the Coq proof assistant, focusing on pure rotational orientation representation.
We establish a formal foundational mathematical library, including vector and matrix theories on abstract elements, additional real matrix properties, and quaternion theory.
Building upon this foundation, we formalize all four rotation models and their conversion algorithms, emphasizing invariants of special orthogonal groups, Rodrigues' rotation formula, and the quaternion rotation formula.
Our formally verified library offers significant benefits in reusability, scalability, and readability.
It enhances developer understanding and serves as a solid foundation for verifying more advanced kinematics algorithms.
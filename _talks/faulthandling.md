---
name: 'Verified fault handling for modern BMCs'
speakers:
  - Ben Fiedler
  - Zikai Liu
  - David Cock
  - Timothy Roscoe
categories:
  - Verification and Testing
links:
  - name: https://
    absolute_url: https://
    icon: newspaper
---

**Presenter**: TBA
**Session Chair**: TBA

Fault handling is the timely and crash-free response to critical changes in a
system's operating characteristics, such as rapid temperature
increases, or electrical shorts. In a typical computer system, it is the board
management controller's job to correctly respond to such anomalous
situations.
We develop an Isabelle/HOL model of a state machine for fault handling and define
semantics for correctness of this procedure. Additionally, we formalize a notion
of refinement that allows us to prove the correctness of implementations of this
state machine.
We also provide the first verified implementation of a C-based fault handler for
board management controllers. Furthermore, we successfully deploy our verified
fault handler on top of the seL4 microkernel and alongside a production-grade,
open source software stack widely deployed today, applying the cyber-retrofit
approach to securing board management controllers in practice. The
implementation and proof effort required is moderate, and our efforts indicate
that already a small team of a handful of people can significantly raise the
level of assurance of a modern, highly privileged software system.
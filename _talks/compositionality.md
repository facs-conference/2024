---
name: 'Testing Compositionality'
speakers:
  - Gijs van Cuyck
  - Jan Tretmans
  - Lars van Arragon
categories:
  - Verification and Testing
links:
  - name: https://
    absolute_url: https://
    icon: newspaper
---

**Presenter**: TBA
**Session Chair**: TBA

Compositionality supports the manipulation of large systems by working on their components. For model-based testing, this means that large systems can be tested by modelling and testing their compo-nents: passing tests for all components imply passing tests for the whole system. In previous work [12], we defined mutual acceptance for specification models and proved that this is a sufficient condition for compositionality in model-based testing.
In this paper, we present an algorithm for verifying mutual acceptance on specifications and a sound and exhaustive model-based test procedure for checking mutual acceptance on black-box implementations, both in-spired by the idea of environmental conformance [7,8]. The result is that correctness of large systems can be determined by testing the component implementations for conformance to their component specification and for environmental conformance to the specification of their environment.
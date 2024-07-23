---
name: 'Comparing Reactive Models and Cyclic Components of Robotic Systems: The RoboStar approach to model-based testing'
speakers:
  - Ana Cavalcanti
categories:
  - Invited Talks
  - Plenary Talks
---

We present support for automatic generation of simulation tests based on reactive models described in RoboChart, a domain-specific notation for verification of reactive designs of control software for robotic systems. The soundness and completeness of our approach are established using RoboChart's process algebraic semantics, formalised in tock-CSP, a discrete-time variant of CSP. 

RoboChart employs state machines enriched with time constructs and a component model to specify timed, platform-independent behavioural models. The RoboChart semantics defines processes that characterise the reactive behaviour of robotic control software through interactions representing sensor outputs and actuator inputs. Support for modelling, model checking, and test generation based on RoboChart is available via [RoboTool](https://robostar.cs.york.ac.uk/robotool/). RoboChart is part of the RoboStar framework for design and verification of mobile and autonomous robots. 

The testing theory for tock-CSP involves constructing tests from forbidden traces of a process, including input and output events and a special event, namely, tock, representing the passage of time. RoboTool automates the process of generating forbidden traces and constructing tests from them.

Simulations are widely used in robotics for early testing. While RoboChart models are reactive, however, simulations often follow an idealised cyclic paradigm. In each cycle, the simulation under test (SUT) evolves by accepting inputs, processing them, and providing outputs, infinitely fast, before advancing time to the next cycle. Our work with RoboChart involves comparing reactive and cyclic models using a conformance relation defined and formalised in tock-CSP. Test generation and execution must adapt to this notion of conformance.

In our work, we identify the reactive tests based on forbidden traces that are meaningful, define a process to convert those tests, provide an algorithm to execute the tests, and prove the soundness and completeness of our approach. The testing approach we present is a significant advancement in current testing practices within the field of robotics, where simulations are widely used.

---
name: 'Formalising Requirements for Systems Verification'
speakers:
  - Rosemary Monahan
categories:
  - Plenary Talks
---

The verification of software systems often relies on a combination of formal methods, testing and simulation based approaches. Knowing what to specify for verification cannot be achieved without clear, unambiguous descriptions of the system requirements. This makes detailed requirements elicitation and formalisation a crucial step in the process. In this talk, I will share experiences from case studies where we have used NASA’s Formal Requirement Elicitation Tool (FRET) to formalise natural language requirements, enabling the use of mathematically-based techniques to guarantee that the system obeys certain properties. These formalised requirements subsequently guide the systems verification using a combination of paradigms, providing for system-level modelling and verification using model checkers and deductive verifiers. Insights gained during this process are shared, and we explore the expressiveness and the potential interoperability of these approaches.

Our experience confirms FRET’s suitability as a framework for the elicitation and understanding of requirements and for providing traceability from requirements to specification. In addition to providing requirements traceability, we have provided extensions to FRET with adaptations of software code refactoring’s for requirements, making requirements more manageable. We support this in Mu-FRET, a version of FRET which enables refactoring of requirements and proof that the refactored requirements have the same behaviour as the original requirements.
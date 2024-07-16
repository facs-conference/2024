---
name: 'Extracting formal smart-contract specifications from natural language with LLMs'
speakers:
  - Gabriel Leite
  - Filipe Arruda
  - Pedro Antonino
  - Augusto Sampaio
  - Andrew Roscoe
categories:
  - Security and Blockchain
links:
  - name: https://
    absolute_url: https://
    icon: newspaper
---

**Presenter**: TBA
**Session Chair**: TBA

Developers tend to be reluctant to provide formal specifica-
tions for software components; even well-established design-by-contract
(DbC) properties like invariants, pre- and postconditions are neglected.
This has hindered a more widely practical dissemination of the DbC
paradigm. In this paper, we employ state-of-the-art NL processing tech-
nologies, using Large Language Models (LLMs), particularly, ChatGPT,
to automatically infer formal specifications from component textual be-
havioural descriptions. More specifically, we implemented a framework
(DbC-GPT), parameterised by a context, which is able to generate post-
condition specifications for smart contract functions implemented in So-
lidity. The output of DbC-GPT is in the notation of the solc-verify tool
(a verifier for Solidity) that is used to: (i) check the syntax of the in-
ferred specification; and (ii) verify whether a reference implementation
conforms to this specification. This is carried out in a loop in such a
way that the DbC-GPT context is iteratively improved with verification
counterexamples. To evaluate DbC-GPT, we have used some Ethereum
standards (ERC20, ERC721, and ERC1155) and compared the precision
of the generated specifications for several GPT contexts that consider
information of these standards in isolation as well as their combination.
# Claudia’s Labyrinth

A message-mixing architecture for research and experimentation.

## Disclaimer
This project is provided **for research and educational purposes only**.

It does **not** implement, facilitate, or support:
- cryptocurrency or digital asset transfers
- value mixing or financial obfuscation
- custodial services of any kind

Any resemblance to financial or transactional systems is unintentional. Use of this software in production, financial, or regulated contexts is **out of scope**.

---

## Nomenclature

Claudia’s Labyrinth uses mythological names to describe conceptual roles within the architecture.
The terminology is symbolic and intended to aid understanding of system behavior and message flow.

**Echo**  
A message outside the Labyrinth boundary. Echoes represent messages before entry into the system and after exit from it.

**Soul**  
A transformed message within the Labyrinth. Souls exist only inside the network and represent encoded and protected message units during traversal.

**Janus**  
The admission layer of the Labyrinth. Janus evaluates incoming Echoes and determines whether they are admitted into the system for processing or redirected away.

**Thoth**  
The transformation layer responsible for encoding, encryption, and decoding. Thoth mediates the conversion between Echoes and Souls at the boundaries of the Labyrinth.

**Mnemosyne**  
The queueing and transient storage layer. Mnemosyne provides buffering, batching, and short-lived retention for Souls as they move through the system.

**Hermóðr**  
Intermediary relay nodes. Hermóðr components forward Souls across internal paths using multi-hop routing while maintaining minimal persistent state.

**Heimdall**  
The lifecycle and oversight layer. Heimdall observes network conditions and coordinates the operational state of internal components.

**Odin**  
The authority responsible for instantiating and retiring internal nodes as directed by lifecycle governance.

**Dogon**  
The delivery layer. Dogon components guide Souls out of the Labyrinth and return them to the external domain as Echoes.

This nomenclature reflects conceptual responsibilities rather than concrete implementations.

---

*Claudia’s Labyrinth is an experimental architecture, not a service.*

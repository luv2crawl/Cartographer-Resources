# About
This repo contains various resources related to Cartographer, including talk slides, recorded talks, related resources, and research notes.

# x33fcon 2023

## Talk Abstract

**Mapping Uncharted Territory: Predicting Evasive Tradecraft with Cartographer**

Have you ever wondered if an offensive technique's MITRE ATT&CK page lists every possible execution procedure? What is a procedure? Which procedure is the most "evasive"? How can I detect all of them? Cartographer is a newly released project that answers these questions and more!

Information security is an inherently adversarial discipline where attackers and defenders are locked in a reactive cycle of innovation and evasion in pursuit of dominance over one another.

For defenders, the question of what a given attacker might do with access to your environment is inherently slippery, nuanced, and subject to uncertainty in every direction. The subsequent questions surrounding the observability of those actions are similarly fraught with uncertainty and opacity, frustrating our ability to make accurate predictions in the form of detection rules. On the other hand, red teams struggle to thoroughly identify the granular details of the telemetry their tooling leaves behind as they move through target environments, let alone predict likely opportunities for evasion when those environments employ diverse approaches to protective controls and detection strategies.

This talk will discuss a conceptual model to describe offensive tradecraft that builds on the common understanding of Tactics, Techniques, and Procedures (TTPs) in an attempt to further flush out a clear definition of the Procedure layer. This model is intended to help defenders and red teamers identify the lower-level operations that attack tooling abstracts, the telemetry those actions are likely to generate, the evasion opportunities that telemetry presents, and the detection strategies that seek to tie it all together.

In addition to outlining my approach to describing and categorizing offensive tradecraft, this talk will announce and introduce Cartographer, a web application that displays detailed information about the lower-level operations that make up common TTPs. Cartographer is designed to package granular observations about how offensive tradecraft interacts with operating system components in a way that directly informs decisions about detection engineering and the development of more evasive attack tooling. Cartographer is primarily geared towards Windows-specific tradecraft at the moment, but the data model could be expanded to cover additional operating systems in the future.

[Slides PDF](slides/x33fcon_2023_slides.pdf)

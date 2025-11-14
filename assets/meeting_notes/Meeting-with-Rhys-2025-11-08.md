---
title: Rhys-Korbi Meeting 2025-11-08
author: Korbinian Friedl
bibliography: ../Zotero_library.bib
mainfont: Century Schoolbook
linestretch: 1.5
format:
  pdf:
    documentclass: article
    geometry: margin=1in
    number-sections: true
  html:
    self-contained: true
    number-sections: true
    toc: true
    toc-depth: 3
    toc-location: right
    favicon: favicon.ico
    smooth-scroll: true
    link-external-icon: true
    link-external-newwindow: true
---




- The normal notion of optimality is optimality in an environment
- then [@richens2024RobustAgents] includes distributional shifts --- leading to domain generalization being a part of our notion of capability (->"robust optimality")
- [@richens2025GeneralAgents]: We also care about achieving many goals in an environment (-> "task generalization"). In their Definition 4 they use LTL to formalize this
	- There will be a corresponding notion of capability in an environment which doesnt use LTL but uses utility instead
	- We should ask John why he does LTL instead of utility
- We also care about an agent being capable in an environment relative to different goals. That is why [@richens2025GeneralAgents] is interesting for us
- But goal misgeneralization is a bit different --- it is both things happening:
	- First Richens is domain generalization, second Richens is goal generalization; in goal misgeneralization, both are happening: Environment changes and goals do
	- **So** I should just skim that paper a little bit and see if I get it
	- And compare to Rhys' stuff on goal misgeneralization and capability in the draft


- [@bellot2025LimitsPredicting]:
	- Summary: This paper tries to see how well agent behaviour off-distribution can be predicted
	- They also make the distinction between the internal world model and the actual model in the real world
	- But they mainly make this assumption that the internal utility corresponds to the objective utility --- except in section 5.3 where they discuss it a bit, but it is short and incomplete. They discuss proxy goals, but not deceptive alignment more generally (where an agent pursues a utility during training to keep loss low so that during deployment it can pursue its real goals)


Write it something like
- ok we have these two models
- we wonder how they relate in capable agents
- ah, richens says they match
- but! richens doesn't say the utilities will match
- maybe goal misgeneralization needs its own paper, so maybe flag that and leave the analysis of it here at a rudimentary level




## Next steps

**Soon: Send an update to Paul, and include in it maybe the outline Rhys typed below ([[#Rhys Here's a posible outline]])** 

(Also see [[Meeting with Rhys 2025-11-06]] still)
- write something on all this (training strategy, goal misgeneralisation) and then write something on the other issues like asking a question in your ontology etc
- potentially, include some formalised solution concepts (myopia, counterfactual oracles, scientist AI) and show how they fail (give counterexamples)



See [@ward2024ReasonsThat] for a paper-writing style we may want to emulate:
Start with semi-formal description of the problem and then later (or in the appendix) make it fully formal
- What we want with this paper is for it to be outreach and to help other people work on the project of ELK -- so we want it to be as accessible as possible.
- For things like Ontology Mismatch and Reference, we may want to leave them as essentially open problems (depending on what Paul comes up with). But what we do want (at least for ourselves) is to make as formally precise as possible what it would *mean* to solve them.

### Rhys:Here's a posible outline:
- Intro
- Semi-formal operationalisation of ELK (similar to Intnet paper)
	- with increasing complexty 
- (maybe in appendix) minimal technical background 
- (maybe in appendix) Fully formal ELK statement 
- (potentally) Solution concepts (it's nice to capture these in the dame formal framework. Possibly / if we dont do enough here then we can just put in related work)
	- Myopia 
	- Counterfactual oracles cf armstrong 
	- Scientsit AI cf bengio 
- Open problems 
	- Goal misgen
	- Ont mismatch
	- Reference 
- Related work
- Conclusion 
	
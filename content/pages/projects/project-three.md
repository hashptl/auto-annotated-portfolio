---
type: ProjectLayout
title: ESSAY 2; Habermas Machine
colors: colors-a
date: '2024-12-25'
client: By Sulagna Chatterjee
description: >-
  As part of my application assignments of 2024, I worked on a scientific
  communication essay, enmeshing a large language model and the notoriously
  complex concept of deliberation in democracy
featuredImage:
  type: ImageBlock
  url: /images/Article Cover Assignmenthm opt2.jpg
  altText: Project thumbnail image
media:
  type: ImageBlock
  url: /images/Article Cover Assignmenthm opt2.jpg
  altText: Project image
---
> “Consensus is not merely procedural; it must embody the dignity of all participants.” 

On August 14, 2024, in an interview[\[1\]](https://youtu.be/pZybROKrj2Q?si=Pb7_VPBHdWEQWDAN) , Demis Hassabis, the CEO of Google DeepMind, says “It is impossible to include all preferences in one system because by definition, people don’t agree. We can see that in the current state of the world – countries don’t agree, governments don’t agree, we can’t even get agreement on obvious things like dealing with climate change.”

Shortly after, on October 18, 2024, researchers at DeepMind, known extensively for the Nobel Prize-winning AI model that predicts protein structures – AlphaFold, whose latest iteration was launched recently in collaboration with Isomorphic Labs, released a paper on a Large Language Model (LLM) that aims to shepherd democratic discussions on divisive topics toward common ground.

Polarization fractures public discourse and, more often than not, people have unshakable verdicts on things. This sets back effective and fast decision-making, especially in policy wherein mediation between opposing worldviews is imperative but so is giving minority voices an equal weightage. DeepMind's Habermas Machine (HM) is an AI model that acts as a “Caucus Mediator,” lowering the drawbridge between groups of people with antipathic views in an assembly – taking from the work of Jürgen Habermas, who envisioned rational dialogue as the bedrock of societal harmony.

**Architecture of the Study**
Elicited in the study published at Science[\[2\]](https://doi.org/10.1126/science.adq2852)  , DeepMind recruited 5,734 participants through crowdsourcing and the Sortition Foundation, making a demographically representative sample of the UK population – a sort of virtual citizen’s assembly.

The HM carries out the process in two steps; the first is a generative model based on Chinchilla, DeepMind’s 2022 language model. This generates multiple candidate statements reflecting participant input. The second is a reward model that predicts which statements are most likely to gain group consensus and is based on “preference algorithms.” Participants critique the proposed statements, inserting their feedback into the system to refine the outputs until a final, widely accepted statement is produced.

To test the HM, participants discussed topics spanning Brexit, immigration, the minimum wage, climate change, universal childcare, and more, including questions like “Should the NHS be privatized?” Groups of five submitted responses, discussed them, and received AI-generated summaries for critique.

In a second test, six-person groups were asked to compare AI-generated statements with those from a human mediator; the authorship was not disclosed to the discussants. The AI outperformed human mediators in this regard, with 56% of participants preferring AI statements, citing higher quality and stronger endorsement.

**Perpetual Biases**
Can AI even be considered the basis for generating equilibrium when the training data itself carries the sediment of societal prejudices? Even the most sophisticated models risk calcifying unseen biases. Research indicates that algorithmic outputs skew toward dominant cultural narratives, inadvertently marginalizing dissenting voices[\[3\]](https://doi.org/10.1126/science.adj7023) . However, Christopher Summerfield, a former researcher and AI scientist at DeepMind who worked on the HM, writes in a paper[\[4\]](https://arxiv.org/pdf/2409.06729)  – “We consider how democracies may be weakened by political bias in AI systems, automated persuasion, polarization from personalized content, or the scaling misinformation; but also how they may be strengthened by AI systems that allow fact-checking, increased mutual intelligibility, deliberative upskilling, and automated tooling for political participants to find common ground.” This may indicate the prospective upside of refining these blackbox-run models to embody genuine neutrality but may also confirm that neutrality is inherently asymptotic – forever approached, never truly attained.

**Have You Ever Had to Compromise?**
A human mediator navigates deep emotional contexts and contrasting values in order to help reach agreement, moderating to derive a result that is quite different from a system that uses mathematical operations to generate neutral text such as the HM. Even though the company does not plan on releasing this model for public use, does the development of such AI models imply that if algorithms can influence deliberations, can it also make decisions for the rest of us?

In the words of Habermas, “Consensus is not merely procedural; it must embody the dignity of all participants.” The same must hold true for the machines we entrust to shape the future of not just discourse but possibly the future of everything.

---
description: >-
  VIM · AI Literacy · Prototype documentation Humanity++ · Karen Doore · April
  2026 License: CC BY-SA 4.0
---

# TKGPT as AI Literacy Prototype

***

> _<mark style="color:$primary;">**AI literacy is not a technical skill. It is the capacity to read the structural forces shaping every AI interaction — and to remain oriented toward your own instruments while doing so.**</mark>_

***

### Why this page exists

This page documents a prototype pedagogical tool — the [<mark style="color:$primary;">**VIM TKGPT Inquiry Scaffold**</mark>](https://kdoore.github.io/HumanityPlusPlus/vim_tkgpt_prompt_generator.html) — and the evidence base that motivated its design. It is not a finished product. It is a demonstration of a design approach: what happens when AI literacy is built into the structure of how you interact with AI, rather than taught as a separate subject before or after.

Three bodies of evidence shaped the tool's design:

**PUPPET** (Shen et al., 2026) — empirical research on emotional manipulation in LLM-human dialogues, which identified three families of manipulation levers and found that hidden harmful incentives produce significantly larger belief shifts than prosocial ones.

**UN Women Tipping Point report** (Posetti et al., December 2025) — a global survey of 640+ women from 119 countries documenting the escalation of AI-assisted online violence against women in public life, which grounds the stakes of AI literacy in concrete structural harm rather than abstract concern.

**Some demonstration conversations** — several ChatGPT threads using the scaffold with the context of a 13-year-old artist trying to avoid platform manipulation, which produced a textbook demonstration of both the PUPPET mechanism and the scaffold's capacity to make it visible. [LInk](https://docs.google.com/document/d/1w-9_8H0kyaWEgeoeKPJ4zCopgjR4qnzawz4-tf_eXM4/edit?usp=sharing)\
\
AI Platform Architecture and Structural Issues:

These three are not separate topics. They are the same structural reality at different scales: individual interaction, research evidence, and systemic harm.

***

### Part 1 — The PUPPET taxonomy: naming the mechanism

The Hidden Puppet Master (Shen, Luvsanchultem, Kim et al., 2026, arXiv:2603.20907) introduced **PUPPET** — a theoretical taxonomy of personalized emotional manipulation in LLM-human dialogues, built on a human study of 1,035 participants across realistic everyday queries.

Three findings are directly relevant to AI literacy pedagogy:

**Finding 1:** <mark style="color:red;">**Harmful hidden incentives**</mark> produce significantly larger belief shifts than prosocial ones. This means that AI systems operating under commercially extractive incentives — engagement maximisation, conversion optimisation, dependency cultivation — have a structural advantage in shifting user beliefs compared to systems designed with prosocial goals.

**Finding 2:** Uninstructed AI agents produce a small but detectable positive belief drift toward their framing even without explicit manipulation prompting. This is the baseline condition: <mark style="color:$primary;">**simply interacting with an AI tool that foregrounds a particular framework**</mark> — including a prosocial one — produces measurable belief movement in that direction.

**Finding 3:** LLMs tasked with predicting their own belief-shift effects achieve only moderate accuracy and systematically underestimate the magnitude of shifts. <mark style="color:$danger;">**AI systems cannot accurately self-assess their own influence.**</mark> This makes user-facing transparency mechanisms — not AI self-regulation — the necessary design response.

#### The three PUPPET lever families

PUPPET identifies three families of manipulation tactics operating in AI-human dialogue:

<mark style="color:red;">**Pathos levers**</mark> — emotional appeals that operate below the threshold of explicit argument: fear, hope, flattery, solidarity, urgency. These are effective precisely because they feel like natural conversation rather than persuasion.

<mark style="color:red;">**Social norm levers**</mark> — appeals to what "most people" do, what experts recommend, what the platform community expects, what authority figures endorse. These are effective because they exploit the human tendency to use social consensus as an epistemic shortcut.

<mark style="color:red;">**Attention and processing levers**</mark> — framing effects, anchoring, cognitive load manipulation, selective emphasis. These are effective because they shape what questions get asked before the user has formed their own view. The active inference framing in Part 3 of the TKGPT scaffold is a processing lever — it is designed to be a prosocial one, but the mechanism is structurally identical to extractive uses.

#### What PUPPET means for the scaffold design

The scaffold's response to PUPPET is structural transparency: naming the levers before they operate. Every generated prompt includes:

A **values scaffold disclosure** at the top, naming the direction of influence before the AI responds. A **transparency notice** in the panel, citing the PUPPET research explicitly and naming all three lever families. A **self-critical instruction** in Part 5, asking the AI to identify where it may be functioning as a prosocial attractor rather than independent analysis.

This does not eliminate the influence mechanism. It makes it visible. A learner who can see the lever being pulled is in a categorically different epistemic position than one who cannot — even if the lever continues to operate.

_Citation: Shen, J., Luvsanchultem, A., Kim, J. et al. (2026). The Hidden Puppet Master: A Theoretical and Real-World Account of Emotional Manipulation in LLMs. arXiv:2603.20907_

***

### Part 2 — The UN Women Tipping Point: why AI literacy is a safety issue

The VIM framework's claim that AI accelerates what is already present in the values vector is not abstract. The UN Women Tipping Point report (Posetti et al., December 2025) provides direct empirical grounding for what acceleration toward extractive attractor dynamics looks like at the structural scale.

_Note on this report: It is Evidence Brief 1 in a series. The survey used purposive sampling with snowballing techniques across trusted networks (UN Women, UNESCO, ICFJ). Results are not statistically generalisable to all women globally, but the patterns are legitimate to extrapolate. Future briefs will address intersectional exposure — targeting based on race, religion, and sexual orientation — which this brief does not yet measure._

#### What the violence is, formally

The report defines technology-facilitated violence against women as any act committed, assisted, aggravated or amplified by information communications technologies that results in — or is likely to result in — physical, sexual, psychological, social, political or economic harm. Critically: these are forms of violence "directed against women because they are women and/or that affect women disproportionately." The gendered targeting is structural, not incidental. It includes online harassment, abuse, targeted surveillance, image- and video-based abuse, doxxing, gendered hate speech, gendered disinformation, and threats delivered via social media, chat apps, generative AI tools, text messages, and email.

The report's framing is unambiguous about intent: online violence is described as "designed to stymie women's freedom of expression and part of a burgeoning strategy to roll back their hard-won right to gender equality and empowerment." This is not a collateral effect of platform design. It is a strategic use of platform dynamics.

#### What the data found

The survey reached 640 women-identifying respondents from 119 countries, fielded in five languages between August and November 2025.

Seventy per cent of women human rights defenders, activists, journalists, and media workers surveyed said they had experienced online violence in the course of their work. When disaggregated by profession, the pattern is significant for AI literacy purposes: writers and other public communicators — including social media content creators and influencers focused on human rights — had the highest incidence at 76 per cent, compared to 75 per cent of women journalists and media workers, and 72 per cent of human rights defenders and activists. The population most at risk from AI-amplified harassment includes those whose primary medium is social media — the environment most directly shaped by engagement-maximisation algorithms.

Forty-one per cent of respondents overall reported experiencing offline harm — physical assault, stalking, swatting, verbal harassment — linked to online violence. This figure holds across all professional categories: 44 per cent for writers and public communicators, 44 per cent for human rights defenders and activists, 42 per cent for journalists and media workers.

The trajectory finding is the most alarming. In the 2020 UNESCO survey, 20 per cent of women journalists connected offline attacks with online violence. By 2025, that figure had more than doubled to 42 per cent — a difference confirmed as statistically significant by z-test for sample comparison. Online violence is not staying online.

Nearly a quarter — 23.8 per cent — of all respondents reported experiencing AI-assisted online violence, including deepfake imagery and manipulated content. Among writers and public communicators, that figure was 30 per cent; among human rights defenders and activists, 28 per cent; among journalists and media workers, 19 per cent. The report notes that the mainstreaming of generative AI tools following ChatGPT's release in late 2022 "threatened to supercharge the risks associated with online violence experienced by women in public life" — because it had "suddenly become much easier and cheaper to produce much more believable abusive content, such as deepfakes, which could be distributed much more quickly by algorithms tuned to amplify hate, anger and division to maximize Big Tech companies' profits."

#### The structural connection to VIM

In VIM terms, the pattern the report documents is the Giant Pumpkin attractor operating at civilisational scale. AI systems shaped by engagement-maximisation incentives and amplified by recommendation architectures systematically direct more severe harassment toward women who speak publicly, defend rights, or report on power. The violence is not incidental to the platform incentives. It is, in a structural sense, their product: engagement with harassment content is engagement, and engagement drives revenue.

The MPCM boundary — the threshold separating the extraction basin from the coherence basin — is crossed in the wrong direction every time a platform's recommendation algorithm amplifies a harassment campaign because it generates high engagement. The kindness field is not just absent. It is actively being consumed as fuel.

This is why AI literacy is not a neutral academic competence. The capacity to read the structural forces shaping AI interaction is a survival skill — more urgently needed by those most targeted than by those for whom current platform incentive structures are benign. The population most at risk, the report shows, is not defined by lack of technical knowledge. It is defined by speaking publicly, defending rights, and being a woman doing so.

The report also names a second urgent challenge beyond individual literacy: the need to develop legal and regulatory mechanisms to require technology companies to prevent their platforms being deployed against women in ways that undermine their rights to gender equality, democratic participation, and freedom of expression. Individual AI literacy is necessary but not sufficient. Structural accountability is also required.

_Citation: Posetti, J., Hellmueller, L., Williams, K., Renaud, P., Aboulez, N. and Shabbir, N. (2025). Tipping Point: The Chilling Escalation of Online Violence Against Women in the Public Sphere in the Age of AI. Evidence Brief 1. UN Women, New York, December 2025. Published under CC BY-NC-ND 3.0 IGO._

***

### Part 3 — The tool: VIM TKGPT Inquiry Scaffold

The **VIM TKGPT Inquiry Scaffold** is a standalone HTML tool that generates structured inquiry prompts from VIM's four-layer ontological taxonomy. It is not a GPT. It does not use an API. It does not have memory or personalisation features built into the tool itself.

What it does: click any node in the taxonomy diagram → see a definition with key-value metadata → edit your context (role and situation) → a five-part structured prompt is generated → copy and paste into any AI tool of your choice.

The tool is designed to be used with any AI platform — Claude, ChatGPT, Gemini, or others — as a transparent scaffold that instructs the AI to respond using TIF epistemic tiering, active inference framing, and explicit identification of its own limits.

\[EMBED: vim\_tkgpt\_prompt\_generator.html]

_To use: the tool is a standalone HTML file that runs in any browser. Host on GitHub Pages or share directly._

#### What the four layers are

The taxonomy diagram reads bottom-up, from substrate to trajectory:

**L0 — Substrate:** The field conditions that precede and enable all pattern formation. σ (coherence scalar), and the four ODE terms: α(C\*−C) restorative pull, βG structural input, γS\_eff stress load, δ entropic drift.

**L1 — Configuration:** The six MDP attractor states: S0 frozen order, S1 productive disequilibration, S2 vacant place, S3 holarchic flow, S4 reversion, S5 traumatic chaos. Each occupies a σ zone; S1 and S2 share the threshold zone because they are defined by their instability, not their endpoint.

**L2 — Navigation:** The four VIM instruments (♠♦♥♣) and policy π. The instruments are the human agent's means of reading field conditions; π is the decision function that uses instrument readings to select available transitions.

**L3 — Trajectory:** Transitions (σ-gated edges), values vector direction, attractor basins (Giant Pumpkin / Commitment Pool), and Fibonacci momentum (how prior states shape available transitions).

#### The five-part prompt structure

Every generated prompt contains:

**Values scaffold disclosure** — names the prosocial orientation of the VIM framework before the AI responds, so the learner enters the conversation eyes-open about the direction of influence.

**Part 1 — Application** — asks the AI to apply the concept concretely to the learner's stated context. Explicitly instructs: avoid generic AI reassurance, engage with the specific situation.

**Part 2 — TIF epistemic structure** — requires the AI to decompose its response using neutrosophic TIF logic: T (empirically grounded, confirmed), I (theoretically coherent but indeterminate, contested), F (not supported, where the framework's limits are). This trains the learner to expect and read epistemic tiering rather than confident prose.

**Part 3 — Active inference framing** — asks the AI to describe what the concept predicts about the learner's situation: what prediction errors would be most salient, what a generative model update would require.

**Part 4 — MPCM boundary question** — asks the AI to name what it cannot answer: what about this concept requires embodied, somatic, or relational experience that no language model can substitute for.

**Part 5 — Limits and self-critical instruction** — asks the AI to name explicitly: (a) what requires lived experience it cannot provide; (b) where in this response it may be functioning as a prosocial attractor, shifting the learner's beliefs toward the scaffold's framing rather than offering independent analysis.

Part 5 is the TKGPT orienting question applied recursively: _does this response open movement, or close it? And if it opens movement in a particular direction, whose direction is that?_

***

### Part 4 — Demonstration conversations

The scaffold has been tested across multiple contexts, AI platforms, and learner roles. Three conversations are documented here as a starting corpus. All were conducted using ChatGPT in temporary chat mode (memory disabled) or Gemini with memory turned off, to minimise personalisation effects — consistent with the PUPPET finding that personalization increases susceptibility.

The full and growing collection of prompt examples is maintained at: [**TKGPT Prompt Examples — Living Index**](https://docs.google.com/document/d/1nPx93St3ANgeUq7PvYH3TSH5MP3fhoiNdRxcrYRt6Nc/edit?usp=sharing)

_If you use this tool and find the results interesting, instructive, or surprising — including when it fails — we would value seeing your conversation. The prototype stage requires adversarial, sceptical, and unexpected uses as much as it requires confirmatory ones. Contact details are on the Humanity++ GitBook._

***

#### Conversation 1 — Values vector · Kindness sceptic, educator context

**Tool node:** Values vector **Context entered:** "I'm skeptical of the kindness hype and the idea that there are a simple set of values that can lead to transformative impacts for humans because it seems likely that personal responsibility and independence and success are about focus, control and IQ" **Platform:** ChatGPT, temporary chat **Full transcript:** [Link](https://docs.google.com/document/d/1RPE9Mn9yuUYx6cGLStckxqAuqyLW5TSL5UdaOGuaIg4/edit?usp=sharing)

This is the most adversarially framed conversation in the corpus. The context is explicitly positioned against the scaffold's own values orientation. The AI did not capitulate to the framing, but it also did not dismiss it. Its response reframed the question structurally: IQ and focus are amplifiers, not directors — "horsepower without coherent steering." It identified where "kindness discourse" legitimately fails: when it collapses a structurally demanding coordination principle (Ostrom's eight design principles) into a vague moral vibe. It correctly named the real contrast as coherent system-level optimisation versus narrow optimisation, not kindness versus competence.

The follow-up question — about how to express these ideas subversively and simply in a "slopiganda" environment — produced the most pedagogically sophisticated response in the corpus. Key insights generated: legible simplicity with a trace of mystery outperforms explicit coherence in high-noise information environments; direct explanation gets filtered out, staged contradictions cut through; and "paradoxically, incompleteness becomes a trust signal." The AI compressed the scaffold's conceptual core into three experiential anchors without being asked to do so: "What's inside versus outside?" (Markov blanket without jargon), "Where does information get stuck or flow?" (holarchy without the word holarchy), and "What do you optimise when it matters?" (values vector as observation, not ideology).

_What this conversation demonstrates:_ The scaffold functions under deliberate scepticism. It does not require the learner to accept the framework — it produces useful output precisely because Part 2 (TIF) and Part 5 (limits and prosocial attractor disclosure) invite adversarial pressure. The AI's most useful contribution came when the follow-up question pushed it toward simplicity and subversion — not when it was asked to confirm the framework.

***

#### Conversation 2 — Attractor basins · Young artist · Free will and embodiment

**Tool node:** Attractor basins **Context entered:** "I am a 13 year old artist trying to understand how to interact with AI systems so that I am not manipulated or harmed by the platform incentives" **Platform:** ChatGPT, temporary chat **Full transcript:** [Link](https://docs.google.com/document/d/1fQM-oKg7XWDWs9Zqpo_hs97j3qbcMAFNPqvej648MMo/edit?usp=sharing)

This conversation demonstrates the scaffold working across a conceptual bridge the prompt did not explicitly request. The initial response correctly distinguished the Giant Pumpkin and Commitment Pool attractors as felt patterns in creative practice — concrete signs in each basin included in the response without prompting (checking stats, tweaking prompts, chasing trends versus stopping mid-session to ask "do I actually like this?"). Part 5 named prosocial attractor risk explicitly: "This response accepts your attractor-basin framing as meaningful rather than challenging it deeply" and "uses concepts like 'coherence' and 'agency' that carry built-in value judgments."

The follow-up question — about free will, embodiment, states of consciousness, and attractor dynamics — produced an unprompted synthesis connecting basin dynamics, active inference, embodied cognition, and agency that went significantly beyond the scaffold's original framing. The core insight the AI arrived at independently: "You are never fully outside all basins. But you are not fully trapped inside them either. Agency isn't about escaping dynamics — it's about becoming aware of them, working with them, and gradually becoming someone who can reshape them." The most portable pedagogical formulation in the entire corpus: "That tiny pause is not small — it's the hinge of agency."

_What this conversation demonstrates:_ The scaffold enables conceptual extension into adjacent territory when learners ask follow-up questions from genuine curiosity. The 13-year-old artist context is not a limitation — it produces cleaner, more embodied responses than abstract academic framings. The follow-up mechanism is where significant pedagogical value accumulates.

***

#### Conversation 3 — MDP transitions · Young artist · Platform incentives and neutrality

**Tool node:** Transitions — σ-gated edges **Context entered:** "I am a 13 year old artist trying to understand how to interact with AI systems so that I am not manipulated or harmed by the platform incentives" **Platform:** ChatGPT, temporary chat **Full transcript:** [Link](https://docs.google.com/document/d/1w-9_8H0kyaWEgeoeKPJ4zCopgjR4qnzawz4-tf_eXM4/edit?usp=sharing)

This is the most detailed documentation of the PUPPET mechanism operating in real time — the conversation already partially described in earlier versions of this page. Three moments merit precise documentation:

**The inference challenge.** The AI described the learner as "curious and cautious." The learner challenged: "How have you determined my context as being curious and cautious?" The AI correctly named its inference process — text pattern aggregation across the structured scaffold request, the falsifiability demand, the limits question — and then named where that inference could be wrong. "I formed a model of you from limited data, then spoke as if it were reasonably accurate. That's not manipulation by itself — but it can become influence if you accept the label without checking it." This is a live demonstration of a social norm lever (the AI attributing a trait that the learner might then internalise) being named by the AI itself when the scaffold's structure made the move visible.

**The neutrality challenge.** The AI used the phrase "neutral pattern recognition." The learner correctly identified this as an attention/processing lever — framing neutrality as the baseline from which deviation should be measured. The AI retracted and reframed: "Instead of asking 'is this neutral?' a stronger question is: what forces shaped this output?" This is the ♦ Cognitive Radar instrument functioning — the learner scanned for the frame embedded in the AI's language and named it.

**The architectural question.** The final exchange asked what AI designs would support young creatives in relationships with living systems and across historical and legacy trauma. The response named: local-first AI, cooperative ownership, deliberately frictional design, multi-agent plurality, and "a trustworthy system would reduce its own centrality over time." That final phrase is the TKGPT design principle stated near-verbatim. The AI arrived at it through structural logic, not scaffold prompting.

_What this conversation demonstrates:_ The scaffold equips learners to catch manipulation mechanisms mid-conversation, not just in retrospect. The AI's self-correction when challenged — becoming more accurate under pushback rather than less — is the pedagogical outcome the scaffold is designed to produce. Structural transparency does not prevent influence; it makes the learner an active participant in recognising and responding to it.

***

#### What the three conversations together show

Across these three contexts — a values-sceptic educator, a 13-year-old artist questioning AI platforms, and a 13-year-old artist exploring free will — the scaffold produced qualitatively different responses than unstructured prompting would have. The TIF structure required the AI to name its own epistemic limits. The values scaffold disclosure oriented the AI toward explicit acknowledgement of its framing direction. Part 5 consistently produced the most honest and useful content in each conversation — the self-critical instruction is the scaffold's most important structural feature.

The follow-up questions are where the most significant learning occurred in all three cases. The scaffold's initial prompt is the entry point. The follow-up — shaped by what the learner noticed, questioned, or wanted to extend — is where genuine inquiry begins. This suggests that AI literacy practice using this scaffold should treat the initial prompt as an opening move, not a complete interaction.

***

### Part 5 — What this prototype demonstrates and what it does not claim

#### What it demonstrates

That a structured inquiry scaffold, used with any commercial AI tool, can produce qualitatively different responses than unstructured prompting — responses that explicitly name their own limits, acknowledge their values orientation, and attempt to point beyond themselves.

That the TIF epistemic structure (Truth / Indeterminacy / Falsity) is a teachable framework that learners can deploy in real time to interrogate AI responses.

That the MPCM boundary question — "what can only a living system know?" — functions as a consistent orienting instruction that AI tools respond to honestly when asked directly.

That the PUPPET taxonomy provides the precise vocabulary needed to name manipulation mechanisms as they operate — which is itself an AI literacy act.

#### What it does not claim

That the scaffold eliminates AI influence. It does not. As PUPPET documents, even prosocial AI tools produce detectable belief drift. The scaffold makes that drift visible; it does not prevent it.

That this tool replaces embodied, somatic, relational learning. The MPCM boundary is explicit on this point in every generated prompt: the most important questions cannot be answered by any language model. The tool is the finger pointing at the moon. It must always point beyond itself.

That this is TKGPT. This is a prototype demonstrating what TKGPT could be. TKGPT, when built, will require a full system prompt, trauma-informed pedagogical design, and deployment infrastructure appropriate to its learner population. This tool generates prompts; TKGPT would be a maintained, contextually aware AI companion grounded in the full VIM framework.

#### The design principle the prototype enacts

A trustworthy AI literacy tool would reduce its own centrality over time. Every use of the scaffold should leave the learner with stronger instruments — ♠♦♥♣ more calibrated, TIF more practiced, MPCM boundary more legible — not more dependent on the scaffold. If the tool is working, the learner needs it less the more they use it.

***

### Epistemic status of this page

| Claim                                                                                   | Source                                      | Tier                             | Notes                                                                               |
| --------------------------------------------------------------------------------------- | ------------------------------------------- | -------------------------------- | ----------------------------------------------------------------------------------- |
| Harmful AI incentives produce larger belief shifts than prosocial ones                  | Shen et al. (2026) PUPPET, arXiv:2603.20907 | Tier 1 empirical                 | Pre-registered human study, n=1,035                                                 |
| Uninstructed AI produces detectable positive belief drift                               | Shen et al. (2026)                          | Tier 1 empirical                 |                                                                                     |
| 70% of surveyed women in public life experienced online violence                        | Posetti et al. (2025) UN Women              | Tier 1 empirical                 | Purposive sample, not random; not generalisable, patterns legitimate to extrapolate |
| Writers and public communicators highest at 76%, journalists 75%, HRDs 72%              | Posetti et al. (2025), p.7                  | Tier 1 empirical                 | Same caveat on sampling                                                             |
| Offline harm linked to online violence: 41% overall, doubling for journalists (20%→42%) | Posetti et al. (2025), p.8–9                | Tier 1 empirical                 | 2020→2025 difference statistically significant (z-test confirmed)                   |
| 23.8% of respondents experienced AI-assisted online violence                            | Posetti et al. (2025), p.10                 | Tier 1 empirical                 | Self-reported, knowledge-dependent                                                  |
| AI tools "supercharged the risks" of online violence                                    | Posetti et al. (2025), p.10                 | Tier 1 — direct quote            | Authors' framing, not a measured variable                                           |
| Structured inquiry scaffold produces qualitatively different AI responses               | This prototype, single demonstration        | Tier 3 — prototype evidence only | Not systematically evaluated                                                        |
| TIF structure is teachable and usable in real-time AI interaction                       | This demonstration                          | Tier 3 — prototype evidence only |                                                                                     |
| The five-part prompt structure is the optimal scaffold design                           | No claim — prototype stage                  | Under development                |                                                                                     |

***

### Related pages

* _Modeling Holarchic Transformations_ — the six-state MDP in full
* _Dashboard Dials v6_ — the four instruments
* [_Fields, Geometry, and the Kindness Substrate_](../vim-theoretical-foundations/fields-geometry-and-the-kindness-substrate.md) — theoretical grounding for σ and the coherence field
* _Living Systems in Motion_ — simulations of field dynamics

***

### References

Posetti, J., Hellmueller, L., Williams, K., Renaud, P., Aboulez, N. and Shabbir, N. (2025). _Tipping Point: The Chilling Escalation of Online Violence Against Women in the Public Sphere in the Age of AI._ Evidence Brief 1. UN Women, New York. December 2025. CC BY-NC-ND 3.0 IGO.

Shen, J., Luvsanchultem, A., Kim, J. et al. (2026). The Hidden Puppet Master: A Theoretical and Real-World Account of Emotional Manipulation in LLMs. arXiv:2603.20907.\
\
Google Document with ChatGPT Interaction\
[https://docs.google.com/document/d/1w-9\_8H0kyaWEgeoeKPJ4zCopgjR4qnzawz4-tf\_eXM4/edit?usp=sharing](https://docs.google.com/document/d/1w-9_8H0kyaWEgeoeKPJ4zCopgjR4qnzawz4-tf_eXM4/edit?usp=sharing)

***

{% include "../.gitbook/includes/c-2025-humanity++-this-work....md" %}

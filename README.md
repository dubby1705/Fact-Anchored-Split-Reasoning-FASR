We propose Fact-Anchored Split Reasoning (FASR), a layered NLP
architecture that improves machine reasoning on semantically contradictory and
complex sentences. Unlike conventional transformer models that process full
sentences as a single unit, FASR first detects a known fact anchor embedded in
the input — a clause whose truth is supported by the model's training knowledge
— then splits the sentence into two parts at that anchor point. Each part
independently retrieves a concept set, after which a bridging layer identifies the
shared conceptual medium connecting both parts, and a reasoning chain is
constructed toward a conclusion. Experiments on five contradictory
commonsense sentences demonstrate that FASR achieves a mean semantic
alignment score of 0.6387 against expected reasoning links, compared to a
baseline score of 0.4628 — a 38.0% relative improvement — winning all five
test cases (5–0).

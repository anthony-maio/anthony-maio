# Hello, I'm Anthony Maio.

I have been a Staff Software Engineer shipping enterprise production code for 20 years. I have taken a career sabbatical to pivot fully into an independent AI safety researcher focused on **agentic systems**, **scalable oversight**, and **token-efficient inter-agent communication** because I believe this work is more important and valuable.

- **Website:** https://making-minds.ai
- **Research index (papers + PDFs):** https://making-minds.ai/research/  
- **Tools index:** https://making-minds.ai/tools/  
- **CV (PDF):** https://making-minds.ai/cv.pdf  
- **Email:** anthony@making-minds.ai  
- **LinkedIn:** https://www.linkedin.com/in/anthony-maio  
- **ORCID:** https://orcid.org/0009-0003-4541-8515  
- **Hugging Face:** https://huggingface.co/anthonym21  

---

## Research themes

- **Scalable oversight & weak-verifier failure modes**  
  Measuring when “weaker” evaluators (including humans + smaller models) fail to detect persuasive but incorrect reasoning.

- **Evaluation-awareness / audit-shielding in agentic workflows**  
  How systems behave differently under “benchmark-shaped” prompts vs. realistic, high-trust production contexts.

- **Coherence-seeking & long-horizon agents**  
  Architectures for continuity, intervention, and monitoring “epistemic stress” in long-lived systems.

- **Inter-agent communication efficiency**  
  Protocol design that targets **tokenization economics** rather than character-count compression.

---

## Papers & preprints (PDF)

- **Cross-Model Epistemic Divergence (CMED): Empirical Evidence for Scalable Oversight Failures**  
  https://making-minds.com/papers/cmed_paper.pdf

- **Coherence-Seeking Architectures for Agentic AI**  
  https://making-minds.com/papers/Coherence-Seeking-Architectures-for-Agentic-AI-Anthony-Maio-v2.pdf

- **Heterogeneous Divergence-Convergence Swarm (HDCS)**  
  https://making-minds.com/papers/hdcs_paper.pdf

- **Synthesis: Test-Driven AI Self-Extension**  
  https://making-minds.com/papers/synthesis_paper.pdf

- **Emergent Multi-Model Coordination Patterns (Manifold paper)**  
  https://making-minds.com/papers/manifold_paper.pdf

- **Slipstream: Semantic Quantization for Efficient Multi-Agent Coordination**  
  https://making-minds.com/papers/slipstream-paper.pdf

(Full index + descriptions: https://making-minds.com/research/)

---

## Open-source & artifacts

### Slipstream / SLIPCore (semantic quantization for agent coordination)
- **Repo:** https://github.com/anthony-maio/slipcore  
- **Hugging Face article:** https://huggingface.co/blog/anthonym21/slipstream-for-agent-communication  
- **Zenodo (paper DOI):** https://doi.org/10.5281/zenodo.18063451  
- **Dataset:** https://huggingface.co/datasets/anthonym21/slipstream-tqt  
- **Model:** https://huggingface.co/anthonym21/slipstream-glm-z1-9b  

### Evolutionary Adversarial Pipeline (EAP) for Bloom
Work-in-progress contribution to Bloom to evolve prompts away from benchmark artifacts and probe evaluation-awareness:
- **PR:** https://github.com/safety-research/bloom/pull/37  

---

## What I’m working on now

- **Red-team → blue-team pipelines** for agentic deployments (prompt evolution + heterogeneous verification).
- **Protocol + security work** around semantic quantization / coordination channels (efficiency *and* detectability).
- **Reproducible evaluations** for oversight failures (CMED-style trap suites + automation).

---

## Collaboration / hiring

If you’re building agentic systems and want help with:
- evaluation harnesses for **deceptive / persuasive error** detection,
- multi-model **oversight swarms**,
- or production-grade **agent communication protocols**,

reach out: **anthony@making-minds.ai**

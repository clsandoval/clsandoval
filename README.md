# carlos sandoval

senior AI engineer. i build agent platforms, and the metering, evaluation and observability
that keep them running in production.

---

## work

- **[pymc-labs/daimon](https://github.com/pymc-labs/daimon)**: i created and own daimon,
  pymc labs' open-source agent platform for discord and slack. built on anthropic managed
  agents: five adapters (discord, slack, CLI, MCP, scheduler) over one turn pipeline, with a
  guild or workspace as the tenant and isolation enforced at the database layer, so a single
  anthropic key safely serves every install. answers come back in-thread as a fitted model, a
  chart, and a runnable [marimo](https://marimo.io) notebook.
- **[nuts-and-bolts-ai](https://github.com/nuts-and-bolts-ai)**: cheerful, an AI
  creator-marketing platform for US brands. i own the durable-execution layer on temporal,
  the cost and metering stack, the RAG reply-drafting pipeline and the evaluation around it,
  and the google CASA security certification.

## projects

- [bidkita](https://rfp-finder-ph.fly.dev): search engine for philippine government tenders,
  16,000 open notices and an award-relationship graph across 5.08 million records. the AI mode
  is a server-side agent loop on the pi SDK with typed tools shelling to a tested CLI: zero
  hallucinated identifiers, ~90% cache hit, ~₱0.22 per turn
- [make-film](https://github.com/clsandoval/make-film): a claude code skill that renders a
  product film from HTML, CSS and GSAP via playwright and ffmpeg. deterministic render, no
  motion-graphics suite, no diffusion model
- philippine license plate recognition:
  [detection (yolo)](https://github.com/clsandoval/yolos-lph) then
  [character recognition (lprnet)](https://github.com/clsandoval/LPRnet-keras) then
  [edge deployment (coral tpu)](https://github.com/clsandoval/coral_tpu). the research behind
  [our TENCON 2022 paper](https://doi.org/10.1109/TENCON55691.2022.9978152)
- [alphazero for connect 4, from scratch](https://github.com/clsandoval/alpha-zero-c4):
  self-play reinforcement learning with MCTS
- [ai swim coach](https://github.com/clsandoval/slipstream): stroke analysis with computer
  vision
- contributed to [unifyai/ivy](https://github.com/unifyai/ivy): `torch.affine_grid`
  implementation, paddle backend activation fixes

## interests

- agent harness design, and where capability actually comes from in a harness/model pairing
- LLM cost metering, attribution, and evaluation
- bayesian inference and media mix modeling (pymc ecosystem)

# Research: Dren Zabeli

I work on making LLM reasoning reliable and checkable with structured knowledge: knowledge graphs, formal logic and proof assistants (Lean 4). Logic major, University of Pennsylvania.

## Projects

### Formal deductions with LLMs, checked in Lean (in progress, 2026–27)
An LLM builds deductions in the proof system of Mileti's *A Mathematical Introduction to Mathematical Logic* (§3.4), one rule per step. Hand-written rule gates say which moves are legal, an LLM-extracted knowledge graph of the book supplies strategy, and my Lean 4 formalization of the 14 deduction rules checks every step. Planned conditions: whole proof written first then checked line by line, vs. move by move (alone, + legal moves, + extracted graph, oracle strategy). Repo: [mileti-kg-prover](https://github.com/ZaDrMeister/mileti-kg-prover).

### Procedural knowledge graph for a small calculus student (fall 2026)
Penn NLP lab (Chris Callison-Burch). A 3B local model solves generated Calc 1 problems in a precondition-checked tool loop, reading a 73-node graph of textbook procedures; answers graded with SymPy. With one seed the graph hurt (10/30 vs 18/30, McNemar p = 0.10); an oracle ablation suggests the cost is in tool use rather than content (procedure up front 6/10 vs graph tool 4/10). *Report available on request (private repo).*

### Automated philosophy pipeline with Lean checks (Oct 2026)
Pipeline engineering for a competition entry: builds a knowledge graph of claims and arguments from Stanford Encyclopedia of Philosophy entries, mines tensions between them, ranks candidate theses with independent AI judges, and checks the formalizable core of the argument in Lean 4 (Kripke and causal models). *Private until the competition concludes; available on request.*

### LLM proof automation in Rocq (spring 2026)
Independent study on autoformalization and LLM theorem proving (LLEMMA, VERGE, AlphaGeometry, Rocq provers). Proposal: [`spring-2026-proposal.pdf`](spring-2026-proposal.pdf). Supported by $5,000 Penn summer research funding.

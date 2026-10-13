# Constrained Cross-Lingual Embeddings

Code, evaluation dictionaries and aligned embeddings for the paper
**Anchors, Not Capacity: Constrained Nonlinear Refinement for Cross-Lingual
Word Embedding Alignment**, SACAIR 2026 (Springer CCIS).

## Summary

We test cross-lingual embedding alignment on English–Sepedi (Northern Sotho),
a typologically distant, low-resource Bantu pair. Three findings:

- Fully unsupervised alignment fails for linear and nonlinear methods alike —
  the failure is in initialisation, not mapping capacity.
- Anchoring is the binding constraint: identical-string seeding recovers a
  working map at zero bilingual cost, and 437 gold pairs reach 18.3% P@1.
- MUSE fails across all three supervision regimes; an ablation isolating the
  refinement update identifies its mutual-nearest-neighbour procedure as the
  common cause.

We propose **VecMap + NL-MUSE**: a global linear rotation from anchors,
followed by a single strongly-constrained nonlinear refinement pass.

## Contents

Being populated following publication:

- Two-stage alignment pipeline (VecMap + NL-MUSE)
- Diagnostics and analysis scripts
- Human-annotated evaluation dictionary and the held-out evaluation split
- Aligned embeddings — released on HuggingFace, linked here once available

## Citation

Citation details will be added once the proceedings volume is published.

## Contact

Abebe Tamrat Tegene — abebe.tegene@up.ac.za
Data Science for Social Impact, University of Pretoria

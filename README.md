# CleanedCAG_Zarakovitis
# Cleaned Greek Texts from the *Commentaria in Aristotelem Graeca* (CAG)

This repository contains cleaned Open Access Greek texts of late ancient Aristotelian commentaries from the *Commentaria in Aristotelem Graeca* (CAG) series. The texts were originally provided by the OGL project of the University of Leipzig (https://www.opengreekandlatin.org/) and then cleaned manually. the original XML can be found in the Github repository of the OGL project (https://opengreekandlatin.github.io/cag-dev/).

The texts follow the style of the pages, where I have connected every split word in the first line that the word occurs.

This work is part of a research project funded by the European Union's Horizon Europe research and innovation programme under the Marie Skłodowska-Curie Actions (Grant Agreement No. 101120349), project name MECANO.

## Repository Structure

Each section contains three subdirectories:
- `/plain-text/`: Clean Greek text stripped of line and page numbers (optimized for NLP, LLMs, and computational linguistics).
- `/referenced-text/`: Greek text retaining original CAG page `(P.xxx)` and line `(Lxx)` numbers for academic citation.
- `/JsonLine/`: Jsonline in Markdown files, ready for being run on PASSIM. Every Jsonline is one paragraph. 

```text
├── Categories_Isagoge/    # Porphyrius, Ammonius, Simplicius, Olympiodorus, Elias, David, etc.
├── Metaphysics/            # Alexander of Aphrodisias, Asclepius, Syrianus
└── Philoponus/             # Philoponus' individual commentaries (In Cat, In An. Pr., etc.)


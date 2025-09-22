MEDAKA KG — Dataset Files
==============================

medaka_raw.csv: This is the raw, unfiltered version that includes all triples without any confidence or majority-vote thresholding.
Schema: Subject, Relation, Object, Count, Confidence

medaka_v1.csv: This is the cleaned and filtered version that retains triples with confidence ≥ 0.5 and majority-vote support (≥ 3 occurrences across 5 generations). This version has been used for evaluation, reporting graph statistics and is recommended for general use.
Schema: Subject, Relation, Object

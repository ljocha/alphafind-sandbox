## Ljocha's AlphaFind sandbox

Experimental work on top of AlphaFind, done standalone to make things a bit easier.

[Implementation of the "bag of domain" search](multi-domain-search.ipynb):
- split query structure to TED domains,
- lookup targets with at least one matching domain
- compute "meta TM score" based on the number of matched domains and their overall RMSD
- sort the targets according to this score
- let the user choose the target and a domain pair to align
- visualize

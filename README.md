# Ljocha's AlphaFind sandbox

Experimental work on top of AlphaFind, done standalone to make things a bit easier.

Binder should work in general, you can spawn it directly at:
- [Mybinder](https://mybinder.org/v2/gh/ljocha/alphafind-sandbox/HEAD) -- public but rather limited resources and lifetime
- [CERIT-SC](https://binderhub.cloud.e-infra.cz/v2/gh/ljocha/alphafind-sandbox/HEAD) -- more resources, [eInfra-CZ](e-infra.cz) account required

## Implementation of the "bag of domain" search

All in [multi-domain-search.ipynb]:
- split query structure to TED domains,
- lookup targets with at least one matching domain
- compute "meta TM score" based on the number of matched domains and their overall RMSD
- sort the targets according to this score
- let the user choose the target and a domain pair to align
- visualize

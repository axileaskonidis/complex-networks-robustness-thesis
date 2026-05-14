# Complex Networks Robustness Thesis Code

This repository contains the Python code used for the undergraduate thesis:

**Title:** Ανθεκτικότητα πολύπλοκων δικτύων σε επιθέσεις, μέσω τεχνικών ανοσοποίησης ευαίσθητων κόμβων ή/και δημιουργίας εναλλακτικών διαδρομών σε αυτά

## Description

The code performs analysis of directed, weighted, signed and temporal networks, including:

- construction of yearly network snapshots,
- computation of weakly and strongly connected components,
- centrality measures,
- community detection,
- robustness analysis under random failures and targeted attacks,
- comparison with randomized/null network models.

## Requirements

The main Python libraries used are:

- pandas
- networkx
- matplotlib
- scikit-learn
- python-louvain
- igraph
- leidenalg

Install dependencies with:

```bash
pip install -r requirements.txt

Data
https://snap.stanford.edu/data/soc-sign-bitcoin-otc.html
https://snap.stanford.edu/data/soc-sign-bitcoin-alpha.html


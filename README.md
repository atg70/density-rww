# DAWN: Density-aware Walks for Detecting Ephemeral Astroturfing in Engagement Networks

## Overview

Our work focuses on detecting ephemeral astroturfing, a tactic where bots rapidly promote a topic to trend before deleting their tweets to erase traces. We propose a random weighted walk (RWW) approach where node transitions are biased by local density measures such as degree, core number, or truss number. Our model framework is given below.



Our model is trained on the LEN dataset, available [here](https://erdemub.github.io/large-engagement-network/). In order to get the k-truss values, use the code available in [A.E. Sariyuce et al.](https://sariyuce.com/codes/nucleus_master.zip).

## Environmental setup

To install the required packages, use the following command:
```sh
pip install -r requirements.txt
```

## References
Sariyüce, A. E., Seshadhri, C., Pinar, A., & Çatalyürek, Ü. V. (2017). Nucleus decompositions for identifying hierarchy of dense subgraphs. ACM Transactions on the Web (TWEB), 11(3), 1-27.

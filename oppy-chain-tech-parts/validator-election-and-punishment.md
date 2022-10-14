# Validator Election & Punishment

OPPY, has a dynamic active validator set, which means that every week, the OPPY chain brings new nodes into the active validator set while we remove the older nodes. This creates immense equality within the validators, as participants within the block generation. In OPPY, we have selected the active validators not only based on the user's deposit but also based on their age as an active validator.

### EXAMPLE: VALIDATOR CHURN

In the diagram below, we have an example of the OPPY chain using nodes 1 to 8. For the round **t**, nodes 2, node 3, and node 4 are elected as the active validators, they will be the active nodes that participants in the block generation.

Note: OPPY in reality, will begin with up to 11 nodes, we go into detail with how this would work [here](https://github.com/joltify-finance/documents/blob/en/joltify-techs/joltify-chain-techs/broken-reference/README.md).

A week later, OPPY will trigger the validator set to churn, all the candidates' voting power will be re-calculated, the node 2 will quit the validator set and node 5 is brought into the validator set. Node 2 will be in the candidate validator set and waiting for the incoming churn to join the active validator set once again.

<figure><img src="../.gitbook/assets/validators.png" alt=""><figcaption></figcaption></figure>

### Validator Punishment

In the rare occurrence that the validators have not performed correctly, or were not executed properly, we must protect our OPPY ecosystem from this happening consistently.

In the OPPY chain, once a node has been identified as not performing correctly (i.e. if an incorrect block was submitted in a proposal), it will be accumulated with the slashing points. Once the slashing points exceed the threshold, the node will then be put into 'jail' for a certain period of time. If the node still fails to perform correctly, the node has the risk of losing a certain amount of staking OPPY.

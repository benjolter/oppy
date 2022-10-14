# Key Terminologies

### Key Terminologies:

**Active Validators:** Active validators are the nodes participants in the block generation.

**Candidate Validators:** Candidate validators are the nodes that maybe choose to be the validators in the coming validator election.

**Inactive Validators:** Inactive validators are the nodes that are ineligible to participate in the Oppy block generation.

In each churn round, the voting power of the validator is calculated as follows:

$$
voting power = permanetpower+temporarypower
$$

​**Temporary power:** Is the value that is reduced based on the age of a validator. For all the validator candidates, the initial temporary voting power for all the nodes is the same. Each churn round, the temporary voting power of an active validator is deducted with a given digit. Once a validator is kicked out from the active validator set, its temporary power will be reset.

**Permanent power:** Is the value calculated based on the staking of a given node. It will not be affected by the transferring of the validator status. The permanent power is updated according to the updates of the validators' staking balance.

**Slashing Point:** Is a mechanism that is built within the proof of stake blockchain protocol, that then discourages the misbehavior. Slashing is essentially designed to incentivize nodes that are secure, available and participating within the network.

Each Churn, all the of the validators voting power will be calculated, the up to top 11 nodes will be the active validators that participant in the block generation while the rest of the candidates need to wait for the next churn.

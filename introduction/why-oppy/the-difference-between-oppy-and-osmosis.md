# The Difference Between OPPY And Osmosis

Osmosis is by far the largest interchain DEX. It is the first IBC-enabled automated market marker decentralized exchanged. Osmosis brings in a lot of creativity, innovations to the Cosmos ecosystem.&#x20;

OPPY has no intention to reinvent the wheels, on the contrary, OPPY wants to add its strength on the shoulders of the pioneers. OPPY forked some codes from Osmosis for swapping, pool functions etc. But there are some key differences between OPPY and Osmosis.

&#x20;****&#x20;

### **OPPY has its own Bridge between OPPY and BSC and other EVM based chains.**

Oppy developed its own bridges between Oppy and BSC and Ethereum chains.  It is very natural to transfer tokens from BSC, Ethereum such as BNB, ETH, BUSD, USDT to Oppy chain for swapping with each other.  Osmosis introduces bridge function from a third party.  **** &#x20;

****

### **Greatly reduces COST for bridging. Inbound fees are**

### &#x20;** **<mark style="color:red;">**ZERO**</mark>**.**

Since Oppy has its own bridge. It gives Oppy the great freedom to control the cost to benefit the users. For example, Oppy charges **ZERO for inbounds fees** while the third party bridge for Osmosis charges around $20 USDC for the inbound fees including gas fees for Ethereum chain (the moment when this document is written).   &#x20;

&#x20;****&#x20;

### **OPPY has the Bridge between OPPY and BSC.**

Oppy has already connected with BSC chain to import BNB, BUSD etc. to swap in Oppy DEX. Osmosis does not have this function yet even though Osmosis introduce the third party because this third party does not connect with BSC.

&#x20;****&#x20;

### OPPY is used as the universal liquidity pairing token.



Instead of setting up large amount of pools between every two assets, Oppy is used as the universal liquidity pairing token in Oppy decentralized exchange and pools are only set between Oppy and another token. &#x20;



There are some reasons behind this design.

****

**To make OPPY more valuable.**  If Oppy is used as the universal liquidity pairing token, it gives Oppy more usage, volume and liquidity **which is good for the Oppy holders**.



It is good for the liquidity providers in the pools if the total incentives for the LPs are fixed. For example, assume there are 100 tokens in Oppy DEX, it needs to have 100\*(100-1)/2= 4950 pools if Oppy sets up pools between every two tokens.  Thus, the LPs incentives will be shared among these 4950 pools. &#x20;

&#x20;

| No. Of Assets (e.g., BTC, ATOM) | No. Of Pool (Arbitrary Pairs) | <p>No. of Pools</p><p>(OPPY Pairs)</p><p> </p> |
| ------------------------------- | ----------------------------- | ---------------------------------------------- |
| n                               | No of Pools =n\*(n-1)/2       | No of Pools=n                                  |
| 10                              | 45                            | 10                                             |
| 100                             | 4950                          | 100                                            |
| 200(IBC tokens alone)           | 19900                         | 200                                            |

&#x20;****&#x20;

In the current design, OPPY is the universal liquidity pairing token. It only needs 100 pools comparing to the 4950 pools in the previous design. Given the same amount of LPs incentives, LPs will get far better returns when divided by **100 rather than 4950**.

&#x20;****&#x20;

&#x20;****&#x20;

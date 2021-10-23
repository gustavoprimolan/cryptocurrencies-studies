## Blockchain Consensus: What is it and Why do We need it?

* Consensus mechanism in blockchains
    * Two limitations appear once a system becomes decentralized
    * 1 - Assume all nodes are honest
        * Different nodes might receive different information
            * Transactions are not propagated to all nodes at the same time due to network latency
            * Each node has its own timestamp
    * At any points in time, different nodes will have different data records
        * Need to make sure all network nodes have the same information
    * 2 - Some of nodes might be outright malicious
        * No restricition on becoming a node in public blockchains
        * Bad nodes might broadcast bad information hoping to make it on the chain
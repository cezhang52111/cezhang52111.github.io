---
title: "SlimChain: Scaling Blockchain Transactions through Off-Chain Storage and Parallel Processing"
collection: publications
category: manuscripts
permalink: /publication/VLDB
date: 2021-07-01
venue: 'Proceedings of the VLDB Endowment (PVLDB)'
slidesurl: 'https://xuc.me/file/slides/PVLDB21.pdf'
paperurl: 'http://www.vldb.org/pvldb/vol14/p2314-xu.pdf'
citation: 'Cheng Xu, Ce Zhang, Jianliang Xu, and Jian Pei. (2021). &quot;SlimChain: Scaling Blockchain Transactions through Off-Chain Storage and Parallel Processing.&quot; <i>VLDB 21</i>.'
---

Blockchain technology has emerged as the cornerstone of many decentralized applications operating among otherwise untrusted peers. However, it is well known that existing blockchain systems do not scale well. Transactions are often executed and committed sequentially in order to maintain the same view of the total order. Furthermore, it is necessary to duplicate both transaction data and their executions in every node in the blockchain network for integrity assurance. Such storage and computation requirements put significant burdens on the blockchain system, not only limiting system scalability but also undermining system security and robustness by making the network more centralized. To tackle these problems, in this paper, we propose SlimChain, a novel blockchain system that scales transactions through off-chain storage and parallel processing. Advocating a stateless design, SlimChain maintains only the short commitments of ledger states on-chain while dedicating transaction executions and data storage to off-chain nodes. To realize SlimChain, we propose new schemes for off-chain smart contract execution, on-chain transaction validation, and state commitment. We also propose optimizations to reduce network transmissions and a new sharding technique to improve system scalability further. Extensive experiments are conducted to validate the performance of the proposed SlimChain system. Compared with the existing systems, SlimChain reduces the on-chain storage requirements by 97% ~ 99%, while also improving the peak throughput by 1.4X ~ 15.6X.
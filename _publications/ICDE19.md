---
title: "GEM^2-Tree: A Gas-Efficient Structure for Authenticated Range Queries in Blockchain"
collection: publications
category: conferences
permalink: /publication/ICDE19
date: 2019-04-01
venue: '35th IEEE International Conference on Data Engineering (ICDE 19)'
slidesurl: 'https://xuc.me/file/slides/ICDE19b.pdf'
paperurl: 'https://doi.org/10.1109/ICDE.2019.00080'
citation: 'Ce Zhang, Cheng Xu, Jianliang Xu, Yuzhe Tang, and Byron Choi. (2019). &quot;GEM^2-Tree: A Gas-Efficient Structure for Authenticated Range Queries in Blockchain.&quot; <i>ICDE 19</i>.'
---

Blockchain technology has attracted much attention due to the great success of the cryptocurrencies. Owing to its immutability property and consensus protocol, blockchain offers a new solution for trusted storage and computation services. To scale up the services, prior research has suggested a hybrid storage architecture, where only small meta-data are stored on-chain and the raw data are outsourced to off-chain storage. To protect data integrity, a cryptographic proof can be constructed online for queries over the data stored in the system. However, the previous schemes only support simple key-value queries. In this paper, we take the first step toward studying authenticated range queries in the hybrid-storage blockchain. The key challenge lies in how to design an authenticated data structure (ADS) that can be efficiently maintained by the blockchain, in which a unique gas cost model is employed. By analyzing the performance of the existing techniques, we propose a novel ADS, called $$GEM^2$$-tree, which is not only gas-efficient but also effective in supporting authenticated queries. To further reduce the ADS maintenance cost without sacrificing much the query performance, we also propose an optimized structure, $$GEM^{2*}$$-tree, by designing a two-level index structure. Theoretical analysis and empirical evaluation validate the performance of the proposed ADSs.
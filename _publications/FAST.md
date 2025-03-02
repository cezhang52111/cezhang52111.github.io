---
title: "COLE: A Column-based Learned Storage for Blockchain Systems"
collection: publications
category: conferences
permalink: /publication/FAST
date: 2024-03-01
venue: '22nd USENIX Conference on File and Storage Technologies (FAST 24)'
slidesurl: 'https://www.usenix.org/system/files/fast24_slides-zhang_ce.pdf'
paperurl: 'https://www.usenix.org/system/files/fast24-zhang_ce.pdf'
citation: 'Ce Zhang, Cheng Xu, Haibo Hu, and Jianliang Xu. (2024). &quot;COLE: A Column-based Learned Storage for Blockchain Systems.&quot; <i>FAST 24</i>.'
---

Blockchain systems suffer from high storage costs as every node needs to store and maintain the entire blockchain data. After investigating Ethereum's storage, we find that the storage cost mostly comes from the index, i.e., Merkle Patricia Trie (MPT). To support provenance queries, MPT persists the index nodes during the data update, which adds too much storage overhead. To reduce the storage size, an initial idea is to leverage the emerging learned index technique, which has been shown to have a smaller index size and more efficient query performance. However, directly applying it to the blockchain storage results in even higher overhead owing to the requirement of persisting index nodes and the learned index's large node size. To tackle this, we propose COLE, a novel column-based learned storage for blockchain systems. We follow the column-based database design to contiguously store each state's historical values, which are indexed by learned models to facilitate efficient data retrieval and provenance queries. We develop a series of write-optimized strategies to realize COLE in disk environments. Extensive experiments are conducted to validate the performance of the proposed COLE system. Compared with MPT, COLE reduces the storage size by up to 94% while improving the system throughput by 1.4×-5.4×.
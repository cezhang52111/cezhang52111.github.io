---
title: "vChain: Enabling Verifiable Boolean Range Queries over Blockchain Databases"
collection: publications
category: conferences
permalink: /publication/SIGMOD19
date: 2019-06-30
venue: '2019 ACM SIGMOD International Conference on Management of Data (SIGMOD 19)'
slidesurl: 'https://xuc.me/file/slides/SIGMOD19.pdf'
paperurl: 'https://doi.org/10.1145/3299869.3300083'
citation: 'Cheng Xu, Ce Zhang, and Jianliang Xu. (2019). &quot;vChain: Enabling Verifiable Boolean Range Queries over Blockchain Databases.&quot; <i>SIGMOD 19</i>.'
---

Blockchains have recently been under the spotlight due to the boom of cryptocurrencies and decentralized applications. There is an increasing demand for querying the data stored in a blockchain database. To ensure query integrity, the user can maintain the entire blockchain database and query the data locally. However, this approach is not economic, if not infeasible, because of the blockchain's huge data size and considerable maintenance costs. In this paper, we take the first step toward investigating the problem of verifiable query processing over blockchain databases. We propose a novel framework, called vChain, that alleviates the storage and computing costs of the user and employs verifiable queries to guarantee the results' integrity. To support verifiable Boolean range queries, we propose an accumulator-based authenticated data structure that enables dynamic aggregation over arbitrary query attributes. Two new indexes are further developed to aggregate intra-block and inter-block data records for efficient query verification. We also propose an inverted prefix tree structure to accelerate the processing of a large number of subscription queries simultaneously. Security analysis and empirical study validate the robustness and practicality of the proposed techniques.
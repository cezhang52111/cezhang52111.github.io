---
title: "Authenticated Keyword Search in Scalable Hybrid-Storage Blockchains"
collection: publications
category: conferences
permalink: /publication/ICDE21
date: 2021-04-01
venue: '37th IEEE International Conference on Data Engineering (ICDE 21)'
slidesurl: 'https://xuc.me/file/slides/ICDE21.pdf'
paperurl: 'https://ieeexplore.ieee.org/document/9458753/'
citation: 'Ce Zhang, Cheng Xu, Haixin Wang, Jianliang Xu, and Byron Choi. (2021). &quot;Authenticated Keyword Search in Scalable Hybrid-Storage Blockchains.&quot; <i>ICDE 21</i>.'
---

Blockchain has emerged as a promising solution for secure data storage and retrieval for decentralized applications. To scale blockchain systems, a prevailing approach is to employ a hybrid storage model, where only small meta-data are stored on-chain while the raw data are outsourced to an off-chain storage service provider. The key issue for query processing in such a system is the design of gas-efficient authenticated data structure (ADS) to authenticate the query results. In this paper, we study novel ADS schemes for authenticated keyword search in hybrid-storage blockchains. We first propose the suppressed Merkle inverted ($$Merkle^{inv}$$) index, which maintains only a partial ADS structure on-chain that can be securely updated with a logarithm-sized cryptographic proof. Moreover, we propose a Chameleon inverted ($$Chameleon^{inv}$$) index that leverages the chameleon vector commitment to achieve a constant maintenance cost. It is further optimized with Bloom filters to enhance the query and verification performance. We prove the security of the proposed ADS schemes and evaluate their performance using real datasets on the Ethereum platform. Experimental results show that, compared to a baseline solution, the proposed $$Merkle^{inv}$$ and $$Chameleon^{inv}$$ indexes reduce the average on-chain maintenance cost from US$11.21 down to US$2.69 and US$0.24, respectively, without sacrificing much the query performance.
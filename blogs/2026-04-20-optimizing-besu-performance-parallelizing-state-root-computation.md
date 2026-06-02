---
title: 'Optimizing Besu Performance: Parallelizing State Root Computation'
url: https://www.lfdecentralizedtrust.org/blog/optimizing-besu-performance-parallelizing-state-root-computation
date: '2026-04-20'
author: Karim Taam and Ameziane Hamlat, Besu Maintainers at Consensys
feed_url: https://lfdecentralizedtrust.org/blog/rss.xml
---
In the ever-evolving blockchain landscape, optimizing execution performance is essential. State root computation is one of the primary bottlenecks in Ethereum execution clients, becoming critical only recently as scaling efforts pushed gas limits higher. Besu tackles this bottleneck by introducing parallel state root computation within its Bonsai Trie storage implementation. This innovation fully exploits multi-core architectures and enables nodes to keep pace with increasing block capacity. In this article, we explore the technical aspects and performance benefits of this parallelization strategy.

---
title: Honey Badger BFT
tags: [blockchain_projects]
keywords: consensus, asynchronous, byzantine
last_updated: September 10, 2018
summary: "Honey Badger BFT is a Rust implementation of the Honey Badger consensus algorithm proposed by Miller et al"
sidebar: mydoc_sidebar
permalink: mydoc_hbbft.html
folder: mydoc
---

## Honey Badger BFT

The Honey Badger consensus algorithm allows nodes in a distributed, potentially asynchronous environment to achieve agreement on transactions. The agreement process does not require a leader node, tolerates corrupted nodes, and makes progress in adverse network conditions. Example use cases are decentralized databases and blockchains.

- Honey Badger is Byzantine Fault Tolerant. The protocol can reach consensus with a number of failed nodes f (including complete takeover by an attacker), as long as the total number N of nodes is greater than 3 * f.

- Honey Badger is asynchronous. It does not make timing assumptions about message delivery. An adversary can control network scheduling and delay messages without impacting consensus.

{% include links.html %}

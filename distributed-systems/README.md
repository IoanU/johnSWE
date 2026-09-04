# Distributed Systems

Learn distributed systems by building nodes, injecting failures, watching messages move, and observing what happens when the network stops behaving nicely.

## Resources

| Resource | Description |
|---|---|
| [Gossip Glomers](https://fly.io/dist-sys/) | A free series of distributed-systems challenges built around Maelstrom. Implement nodes and test them against message delays, partitions, retries, and failures. |
| [System Design Simulator](https://www.systemdesignsimulator.in/) | Interactive browser simulator where you assemble architectures, trace requests through components, experiment with load, and observe failure behavior. |
| [Distributed Systems Visualizer](https://sys.parvsharma.in/) | Interactive visualizations for concepts such as consistent hashing, quorums, vector clocks, CRDTs, replication, and leader election. |

## Core concepts

- partial failure
- network partitions
- replication
- consistency models
- CAP theorem
- consensus
- leader election
- quorums
- logical clocks
- vector clocks
- idempotency
- deduplication
- retries and timeouts
- distributed transactions
- eventual consistency
- consistent hashing
- message queues
- event-driven systems
- fault tolerance
- distributed observability

## Important mindset

A distributed system is not just a normal program running on multiple machines.

Messages can be **late, duplicated, reordered, or lost**, and individual components can fail independently.

[← Back to main README](../README.md)

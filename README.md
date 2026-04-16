# MIT 6.824 Self-Study Journey

This repository is my self-study journey for MIT 6.824 Distributed Systems.

## Lesson 1 Notes

### Topic

Introduction to Distributed Systems

### English Summary

Lecture 1 explains that distributed systems are built because they can achieve things a single centralized machine usually cannot. Their main achievements are higher throughput through parallelism, better fault tolerance through replication, higher availability when machines fail, support for geographically distributed users or devices, and stronger isolation for security. In short, distributed systems let us build services that are bigger, more reliable, and more scalable than a single computer.

The lecture also stresses that these benefits come with serious costs. Distributed systems are harder to design, debug, and reason about because of concurrency, partial failures, and communication delays. The key message is that fault tolerance, consistency, and performance often conflict with each other. A distributed system can do more than a centralized one, but it pays for that power with complexity and difficult tradeoffs.

### 中文摘要

第一堂課的重點是：分散式系統之所以重要，是因為它能做到單一集中式電腦通常做不到的事情。它的主要成就是透過平行化提升整體吞吐量、透過複製提升容錯能力、在部分機器故障時仍維持高可用性、支援地理上分散的使用者與裝置，以及用隔離方式增強安全性。簡單說，分散式系統讓我們能建立更大、更穩定、也更能擴展的服務。

但老師也特別強調，這些好處不是免費的。分散式系統更難設計、更難除錯，也更難推理，因為你必須處理並行、局部失敗、以及網路通訊延遲等問題。課程的核心訊息是：容錯性、一致性、和效能三者之間常常彼此衝突。分散式系統比集中式系統更有能力，但代價就是更高的複雜度與更困難的取捨。

## Key Takeaways

- Distributed systems improve scalability and availability.
- Replication helps systems survive failures.
- Communication across machines creates complexity.
- Consistency, fault tolerance, and performance require tradeoffs.

## Next Steps

- Add notes for each lecture.
- Build small experiments for labs such as MapReduce and Raft.
- Record questions, confusions, and insights after each study session.

## Structure

- `lesson-01/notes.md`: lecture notes and reflections
- `lesson-01/experiments/`: small experiments and lab preparation

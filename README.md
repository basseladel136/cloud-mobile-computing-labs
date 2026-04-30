# Cloud and Mobile Computing Labs

**Student:** Bassel Adel  
**Group:** SE3  

## Overview
This repository contains the implementation and reports for the Cloud and Mobile Computing course labs.

---

## Lab 1 — Cloud Virtualization & Data Center Architecture
- Multipass VM vs Docker container resource comparison (namespaces, cgroups)
- AWS EC2 instance exploration (Nitro hypervisor)
- Tail latency simulation with Flask + latency histogram

## Lab 2 — Distributed Consistency and Consensus
- Redis master-replica replication
- Network partition simulation (CAP theorem)
- Raft consensus with etcd (leader election)

## Lab 3 — Containerization and Cluster Orchestration
- Docker multi-stage image builds
- Kubernetes deployment with kind (3 replicas)
- Node scheduling, self-healing, and health probes

## Lab 4 — Microservices and Cloud-Native Design
- product-service and order-service built with Flask
- Docker Compose orchestration with health checks
- Failure injection and resilience observation (503 handling)

## Lab 5 — Local Serverless & Event-Driven Image Pipeline
- Event-driven pipeline using Docker, Redis Streams, Python Flask, and Pillow
- 5 containerized services: Redis, event-source, event-router, image-resizer, notifier
- Folder watcher publishes image.uploaded events to Redis Stream
- Event router implements fan-out to multiple function destinations
- Cold start experiment comparing warm vs restarted container response times
- No cloud account required — fully local simulation of serverless architecture

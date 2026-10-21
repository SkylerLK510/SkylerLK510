<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img src="assets/header-light.svg" width="1200" alt="Question. Measure. Refine. Header for Skyler Kendrick's working notes on models, measurements and systems; the branching lines are an illustration, not data.">
</picture>

# Skyler Kendrick

My interests center on machine learning research and how machine learning can be applied to finance and medicine, where a result is only as good as the assumptions and measurements behind it. I care about accuracy, efficiency and clear code: assumptions stated, bottlenecks measured before they are optimized, and limits written down.

[Selected work](#selected-work) · [In development: Ringo](#in-development)

## Selected work

Four projects, from numerical models through training pipelines and job coordination to practical scheduling.

### [quantmc](https://github.com/SkylerLK510/quantmc) · option pricing and risk

A Monte Carlo simulation engine for option pricing and risk, built from scratch in Python.

### [med-clip-profiling](https://github.com/SkylerLK510/med-clip-profiling) · training-pipeline efficiency

Profiling-driven optimization of a CLIP-style medical image/text training pipeline on a single GPU. Controlled measurements separate compute bottlenecks from decoding bottlenecks. It is pipeline research, not a model validated to a published retrieval metric.

### [personal-compute-lab](https://github.com/SkylerLK510/personal-compute-lab) · durable job coordination

An early, local-only Python/SQLite job coordinator with a durable queue, expiring leases, heartbeats and stale-result rejection. GPU inference, training, model sharding and large checkpoint transfer are future work.

### [berth-scheduler](https://github.com/SkylerLK510/berth-scheduler) · waterfront reservations

A reservation application for a marine-research waterfront: a monthly schedule, overlap and fit checks, spreadsheet import, public browsing and account-restricted writes.

## In development

**Ringo** is an in-development council-guided harness. Its research reliability is not yet established.

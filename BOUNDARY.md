# TASK-3563 authority boundary

This repository is a disposable public fixture for an attributed TESTRADE
evaluation of stock Zuul 14.2.0.

Zuul receives no GitHub credential. Events are replayed locally into the stock
GitHub webhook endpoint, results leave Zuul through its stock MQTT reporter,
and no Zuul reporter is configured to merge or otherwise mutate this
repository. TESTRADE production, promotion, deployment, Vault, and runtime
authority are outside the experiment.

# Lip2Speech

## About

Combines VALL-E, AV-HuBERT and Encodec methods to synthesis speech from lip movements.

## Method

1. Produce 1024-dim embedding at 75Hz using AV-HuBERT
2. Predict EnCodec audio tokens at 25 Hz using AV-HuBERT frame embeddings
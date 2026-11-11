# CacheLab

> Semantic caches save money but can silently return wrong answers. CacheLab measures that risk and automatically finds the safest similarity threshold for each type of query.

## What is CacheLab

CacheLab is an open-source tool that evaluates semantic caches for LLM applications. Instead of building another cache, it tests an existing one and recommends a similarity threshold backed by measured data.

## The problem

AI apps send user questions to an LLM, and every call costs money and time. A semantic cache reuses an old answer when a new question has the same meaning. It decides this using a similarity threshold. If the threshold is too low, different questions get the wrong answer. If it is too high, almost nothing is reused. Most teams pick a value like 0.85 and never check it.

## How it works

Coming soon.

## Architecture

Coming soon.

## How to run

Coming soon.

## Results

Coming soon.

## Decisions

Coming soon.
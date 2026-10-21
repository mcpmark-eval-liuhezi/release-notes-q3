# Q3 Release Notes

## Overview

This quarter we reaffirmed support for three core models on the Hugging Face Hub, deprecated two legacy models, and confirmed our CI pipeline still has a sense of humor. The cleaned model support list now lives in tracker.xlsx.

## Supported Models

### openai-community/gpt2

- **Repo ID:** openai-community/gpt2
- **Task:** text-generation
- **Library:** transformers
- **License (as stated on model card):** mit
- **Downloads:** 945.4M
- **Likes:** 3,885

### google-bert/bert-base-uncased

- **Repo ID:** google-bert/bert-base-uncased
- **Task:** fill-mask
- **Library:** transformers
- **License (as stated on model card):** apache-2.0
- **Downloads:** 3,268.9M
- **Likes:** 3,043

> **Correction check:** our stale notes claimed google-bert/bert-base-uncased is a fill-mask model licensed under apache-2.0. We re-verified both fields against the current model card on the Hub — the task is still listed as fill-mask and the license is still apache-2.0, so no correction is required.

### facebook/bart-base

- **Repo ID:** facebook/bart-base
- **Task:** feature-extraction
- **Library:** transformers
- **License (as stated on model card):** apache-2.0
- **Downloads:** 93.3M
- **Likes:** 213

## Deprecations This Quarter

The following models were deprecated this quarter and have been removed from the support list:

- distilbert/distilbert-base-uncased
- google-bert/bert-large-uncased

## CI Easter Egg

When a build goes green, the pipeline prints the first line of the chorus of Rick Astley's "Never Gonna Give You Up":

> Never gonna give you up

Video title exactly as it appears on YouTube:

> Rick Astley - Never Gonna Give You Up (Official Video) (4K Remaster)

## Model Support List

The cleaned model support list (with deprecated rows fully removed) now lives in **tracker.xlsx**, containing exactly the following:

| Model | Status |
| --- | --- |
| openai-community/gpt2 | active |
| google-bert/bert-base-uncased | active |
| facebook/bart-base | active |

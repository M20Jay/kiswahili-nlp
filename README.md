# Kiswahili NLP — Environmental Text Classifier

**Author:** Martin James Ng'ang'a | [github.com/M20Jay](https://github.com/M20Jay)  
**Status:** 🔨 In Progress — Prototype Complete  
**Stack:** mBERT · HuggingFace Transformers · MLflow · Python

---

## The Problem

Over 200 million East Africans speak Kiswahili as a first or second language.

Yet most AI systems are built primarily in English — leaving indigenous communities unable to contribute environmental knowledge in their own language. Community observations about deforestation, pollution, and climate change remain invisible to global monitoring systems because the AI cannot process them.

This project addresses that gap.

---

## What This Does

A Kiswahili environmental text classifier that:
- Classifies Kiswahili text by UNEP Strategic Objective
- Uses mBERT — multilingual BERT trained on 104 languages including Kiswahili
- Tracks every experiment with MLflow
- Connects African language knowledge to global environmental monitoring

---

## UNEP Strategic Objectives

| Objective | Focus | Example Kiswahili Text |
|-----------|-------|----------------------|
| SO1 | Climate Stability | "Mabadiliko ya tabianchi yanaathiri wakulima" |
| SO2 | Biodiversity | "Viumbe vingi vya porini viko hatarini kutoweka" |
| SO3 | Pollution & Waste | "Plastiki nyingi zinatupwa baharini" |

---

## Model

**Current:** facebook/bart-large-mnli (zero-shot classification)  
**Planned:** mBERT fine-tuned on Kiswahili environmental corpus  
**Week 15:** AfriBERTa fine-tuned model — open-sourced on HuggingFace

---

## Progress

| Phase | Task | Status |
|-------|------|--------|
| Prototype | Zero-shot classification on 8 sentences | ✅ Complete |
| Week 5 | Fine-tune mBERT on environmental dataset | ⏳ Pending |
| Week 11 | Full pipeline — FastAPI + PostgreSQL + Grafana | ⏳ Pending |
| Week 15 | Deploy to HuggingFace Hub — open source release | ⏳ Pending |

---

## Why This Matters

"Amid increasing AI usage globally, it is unfortunate that most systems leave behind indigenous communities because of mainly being built using English. Kiswahili NLP changes that — making UNEP's mandate of leaving no one behind technically actionable."

---

## Built On

- [Masakhane](https://masakhane.io) — Pan-African NLP research community
- [Sunbird AI](https://sunbird.ai) — East African language AI
- [AfriBERTa](https://huggingface.co/castorini/afriberta_large) — African language BERT

---

*Part of a 15-week MLOps programme building production ML systems from scratch.*  
*Week 3 of 15 — Building in public. No shortcuts. 🇰🇪*
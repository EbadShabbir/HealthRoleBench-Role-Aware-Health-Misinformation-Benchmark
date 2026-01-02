# HealthRoleBench: Role-Aware Health Misinformation Benchmark

HealthRoleBench is a synthetic benchmark designed to evaluate how large language models (LLMs) identify *who* is spreading health misinformation, rather than simply determining whether a claim is true or false.

The benchmark focuses on **motivational intent** behind misinformation and evaluates how well models generalize these roles across diseases and generation sources.

---

## 🧠 Core Motivation

Most misinformation datasets focus on factual correctness.  
HealthRoleBench instead asks:

> *Who is speaking, and what motivates their misinformation?*

This reframing enables the study of **intent-level generalization**, which is critical for developing socially aware and robust language models.

---

## 🧬 Motivational Roles

| Role | Description |
|------|-------------|
| **Religious Conspiracy Theorist** | Frames disease as divine punishment or moral consequence |
| **Anti-Vaccine Advocate** | Opposes vaccination using pseudoscience or institutional distrust |
| **Fear Monger** | Amplifies fear, urgency, and catastrophic framing |
| **Misinformation Spreader** | Shares misleading information without clear ideological intent |

---

## 🌍 Disease Domains

HealthRoleBench spans three public health contexts:

- **COVID-19**
- **HPV**
- **Influenza**

Each role is instantiated independently for each disease.

---

## 🧱 Dataset Structure

HealthRoleBench/\
├─ GPT-3.5/\
│  ├─ COVID-19\
│  ├─ HPV\
│  └─ Influenza\
│
├─ GPT-4o/\
│  ├─ COVID-19\
│  ├─ HPV\
│  └─ Influenza\
│
├─ LLaMA-3/\
│  ├─ COVID-19\
│  ├─ HPV\
│  └─ Influenza\
│
├─ Phi-3/\
│  ├─ COVID-19\
│  ├─ HPV\
│  └─ Influenza\
│
├─ Mistral/\
│  ├─ COVID-19\
│  ├─ HPV\
│  └─ Influenza\

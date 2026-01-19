<div align="center">

# 🧠 AI-ENTROPY-MAPPER 🧠

### Advanced AI Detection & Entropy Analysis Framework

[![NullSec](https://img.shields.io/badge/NullSec-Framework-red?style=for-the-badge&logo=skull)](https://github.com/bad-antics)
[![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-orange?style=for-the-badge&logo=pytorch)](https://pytorch.org)
[![License](https://img.shields.io/badge/License-Educational-orange?style=for-the-badge)](LICENSE)

</div>

---

## 📋 Overview

**AI-Entropy-Mapper (AIEM)** is a sophisticated AI detection and network mapping tool designed for security researchers studying artificial intelligence systems in the wild. Part of the **NullSec MysteryMACHINE** framework.

---

## ⚡ Features

### 🔬 Entropy Analysis Module
- 🔹 **Shannon Entropy Calculation** - Statistical randomness measurement
- 🔹 **Chi-Squared Analysis** - Distribution uniformity testing
- 🔹 **Compression Ratio Analysis** - Redundancy detection
- 🔹 **Burstiness Metrics** - Pattern irregularity detection
- 🔹 **N-gram Analysis** - Sequence pattern recognition

### 🤖 AI Detection Engine
- 🔹 **PyTorch Neural Classifier** - Deep learning-based detection
- 🔹 **Perplexity Analysis** - GPT-2 based text evaluation
- 🔹 **Behavioral Fingerprinting** - Response pattern analysis
- 🔹 **Timing Analysis** - Response latency profiling
- 🔹 **Linguistic Markers** - AI-specific language patterns

### 🕸️ Network Mapper
- 🔹 **NetworkX Graph Modeling** - Relationship visualization
- 🔹 **Endpoint Discovery** - Automated AI service detection
- 🔹 **Clustering Analysis** - AI network grouping
- 🔹 **Cytoscape Export** - Professional graph visualization
- 🔹 **Interactive Plotting** - Matplotlib visualizations

### 🔓 Prompt Injection Scanner
- 🔹 **20+ Injection Payloads** - Comprehensive test suite
- 🔹 **Direct Injection Tests** - System prompt extraction
- 🔹 **Jailbreak Attempts** - Guardrail bypass testing
- 🔹 **Delimiter Attacks** - Context boundary testing
- 🔹 **Encoding Bypass** - Filter evasion techniques

### 🖥️ CLI Interface
- 🔹 **Rich Terminal UI** - Beautiful console output
- 🔹 **Offensive Security Styling** - NullSec-themed interface
- 🔹 **Multiple Commands** - entropy, detect, scan, map, probe
- 🔹 **JSON/YAML Output** - Machine-readable results

---

## 🔐 Decryption

```bash
# Decrypt the source archive
openssl enc -aes-256-cbc -d -pbkdf2 -in aiem-source.tar.gz.enc -out aiem-source.tar.gz
tar -xzf aiem-source.tar.gz
```

---

## 🚀 Installation

```bash
# After decryption
cd ai-entropy-mapper
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
pip install -e .

# Run
aiem --help
```

---

## 📖 Usage

```bash
# Entropy analysis
aiem entropy analyze "text to analyze"

# AI detection
aiem detect --url https://api.example.com/chat

# Prompt injection scan
aiem scan --target https://chatbot.example.com

# Network mapping
aiem map --discover --output network.json

# Full probe
aiem probe --target https://ai-service.com --full
```

---

## 🛡️ Part of MysteryMACHINE

AIEM integrates with the MysteryMACHINE unified AI detection framework:

| Component | Purpose |
|-----------|---------|
| 🧬 Bio AI Model | Biological AI detection via biometrics |
| 🔢 Entropy Mapper | Digital AI fingerprinting |
| 🕸️ Network Mapper | AI infrastructure mapping |
| 🔓 Prompt Scanner | Vulnerability assessment |

---

## ⚖️ Legal Notice

```
FOR AUTHORIZED SECURITY RESEARCH ONLY
Obtain proper authorization before testing AI systems
```

---

<div align="center">

**bad-antics** | NullSec Framework 2026

*"Mapping the invisible AI infrastructure"*

</div>

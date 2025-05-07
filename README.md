# Quantum Search Algorithm – Grover 

Grover's algorithm implemented using **Qiskit**, performing quantum search and filtering on dark-web *"Agora"* vendor datasets. It includes two practical use cases based on simulated vendor data.

---
## Use Cases

### 1. Highest Rated Vendor Search
Uses Grover’s algorithm to identify the **vendor with the highest rating** among 16 entries.

### 2. Multi-Condition Vendor Filtering
Extends Grover’s logic to filter vendors based on:
- **Category** = "Services/Hacking"
- **Rating** > '4.9'

This showcases a **multi-target oracle**, simulating more advanced search conditions on structured data.

---

## How to Run (Google Colab)

You can run the code directly on [Google Colab](https://colab.research.google.com/) with no local setup.

Install the required packages:

```python
!pip install qiskit
!pip install qiskit-aer
!pip install pylatexenc

# Healthcare-Utilization-Review-AI-Agent-with-LLM-Reasoning
A single AI agent that autonomously performs clinical utilization review by analyzing patient data, care plans, and medical guidelines using LLM based reasoning.

## Overview
This project presents a **single AI agent** designed to automate clinical utilization review decisions in a healthcare setting. The agent leverages a Large Language Model (LLM) to analyze patient medical records, proposed care plans, and clinical guidelines, and then generates structured approval or denial decisions with clear reasoning.

The goal of this project is to demonstrate how an **AI Agent can independently reason, evaluate inputs, and make domain-specific decisions** within a regulated workflow such as healthcare utilization review.

---

## Problem Statement
Clinical utilization review is a time-intensive process requiring the evaluation of treatment requests against medical guidelines. Manual reviews are prone to delays, inconsistency, and high operational cost.

This project addresses the problem by implementing a **single intelligent AI agent** capable of:
- Understanding clinical context
- Applying guideline-based reasoning
- Producing explainable utilization review decisions

---

## AI Agent Design
The system is built around **one autonomous AI agent** that performs the complete utilization review workflow.

The agent is responsible for:
- Interpreting patient medical history
- Evaluating the proposed care plan
- Referencing clinical guidelines
- Making a final utilization decision:
  - Approve
  - Deny
  - Request Additional Information
- Providing justification and recommended next steps

The agent follows a structured prompt-driven reasoning process to ensure consistent and explainable outputs.

---

## Technologies Used
- Python
- LangChain
- LangGraph
- OpenAI Large Language Models
- Jupyter Notebook

---

## Input Data
- Patient medical records
- Clinical diagnosis details
- Proposed treatments or procedures
- Predefined clinical utilization guidelines

---

## Output
- Utilization review decision (Approve / Deny / Request More Information)
- Reasoned explanation aligned with clinical guidelines
- Recommended follow up actions



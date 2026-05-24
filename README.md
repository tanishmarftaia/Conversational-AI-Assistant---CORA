# Conversational-AI-Assistant---CORA

An adaptive multi-agent AI assistant built with Flask that uses OpenAI,
LangChain, YOLOv5, and external APIs to answer product queries, detect
objects in images, provide weather forecasts, and track financial data
all in one interface.

---

# APEX – Adaptive Product Experience Assistant

**APEX** is an enterprise-grade AI assistant built with **Flask**, designed
to serve as a unified interface for product intelligence, image recognition,
and real-time data retrieval. It leverages a modular agent architecture to
handle diverse query types from natural language document search to live
financial feeds — within a single conversational system.

---

## Core Capabilities

APEX integrates four specialized agents, each responsible for a distinct domain:

- **Document Intelligence** — LangChain + OpenAI GPT-4o with RAG over structured documents and OCR content
- **Vision Agent** — Fine-tuned YOLOv5 model for toilet model identification from uploaded images
- **Weather Agent** — Real-time forecasts for U.S. states and cities via external APIs
- **Financial Agent** — Live S&P 500 data for market-aware conversations

---

## Technology Stack

| Component        | Technology                  |
|------------------|-----------------------------|
| Backend          | Flask                       |
| Orchestration    | LangChain                   |
| Language Model   | OpenAI GPT-4o               |
| Vector Database  | Chroma Vector DB            |
| Object Detection | YOLOv5                      |
| Web Search       | Brave Search API            |

---

## Use Case

> Designed to assist customers and field agents in identifying, comparing,
> and evaluating toilet models and specifications — using both **text** and
> **images** — reducing lookup time and improving decision accuracy in the field.


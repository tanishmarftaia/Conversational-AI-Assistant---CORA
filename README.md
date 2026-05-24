# Conversational-AI-Assistant---CORA
CORA is an intelligent multi-agent chatbot built with Flask, designed to serve as a unified interface for product intelligence, image recognition, and real-time data retrieval. It leverages a modular agent architecture to handle diverse query types — from natural language document search to live financial feeds — within a single conversational system.

Core Capabilities

CORA integrates four specialized agents, each responsible for a distinct domain. The document intelligence agent uses LangChain with OpenAI GPT-4o and a Chroma vector database to perform Retrieval-Augmented Generation (RAG) over structured product documents and OCR-extracted content. The vision agent employs a fine-tuned YOLOv5 model to identify and classify toilet models directly from uploaded images. The weather agent queries external APIs to deliver accurate forecasts for U.S. states and cities. The financial agent retrieves real-time S&P 500 data, enabling market-aware conversations alongside product queries.

Technology Stack

The system is built on Flask and orchestrated through LangChain, with OpenAI GPT-4o as the primary language model. Document embeddings are stored and retrieved via Chroma Vector DB. Object detection is handled by YOLOv5, and web-based query augmentation is powered by the Brave Search API.

Use Case

CORA is purpose-built to assist customers and field agents in identifying, comparing, and evaluating toilet models and specifications — using both text descriptions and product images — reducing lookup time and improving decision accuracy in the field.

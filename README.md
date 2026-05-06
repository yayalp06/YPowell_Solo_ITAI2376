# FitBot
FitBot is an AI personal trainer prototype. It takes daily activity data like steps, active minutes, and sedentary minutes, predicts calories burned, and recommends workouts based on the user’s goal, equipment, experience level, and limitations. I designed it to work even without an API key, but it is also ready to connect to LangChain 
FitBot LangChain AI Agent


FitBot is a Retrieval-Augmented Generation (RAG) AI fitness assistant that provides personalized workout and wellness recommendations using LangChain, ChromaDB, and large language models.

---

## Team Information

Solo Project — Y. Powell

---

## Problem Statement

Many users collect health and fitness data but struggle to interpret that information into actionable workout guidance. FitBot solves this problem by combining retrieval-based AI with fitness knowledge documents to provide intelligent and personalized recommendations.

### Target Users
- Fitness beginners
- Gym users
- Individuals seeking workout guidance
- Users wanting AI-powered coaching assistance

---

## Project Type

Single Agent Architecture

Original midterm plans included a more advanced multi-agent workflow, but the final implementation focused on a robust and explainable single-agent RAG system.

---

## Architecture Overview

FitBot uses Retrieval-Augmented Generation (RAG) to retrieve relevant fitness knowledge before generating responses. User prompts are embedded into vector space using HuggingFace embeddings and stored in ChromaDB. LangChain orchestrates retrieval and conversation memory while the LLM generates final personalized recommendations.

[Architecture Diagram](architecture.png)

---

## Frameworks and Tools Used

- Python 3.11
- LangChain
- ChromaDB
- HuggingFace Embeddings
- OpenAI API
- Sentence Transformers
- Jupyter Notebook
- Gradio
- Retrieval-Augmented Generation (RAG)

---

## Installation Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yayalp06/FitBot.git


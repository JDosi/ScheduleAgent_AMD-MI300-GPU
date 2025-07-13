# Agentic AI Scheduling Assistant

Welcome to our solution for the **AMD Hackathon 2025**! This project is an **Agentic AI-powered scheduling assistant** that autonomously parses meeting requests, checks calendars, resolves conflicts, and schedules meetings with minimal human intervention.

---

## Project Overview

Traditional scheduling involves endless back-and-forth emails, timezone mismatches, and missed preferences. Our AI assistant eliminates all of this by:

- Understanding natural language meeting requests.
- Extracting participants, duration, and time constraints via LLMs.
- Checking real-time calendar availability using Google Calendar API.
- Suggesting optimal meeting slots and resolving conflicts.
- Returning structured responses for integration into any scheduling system.

---

## Tech Stack

| Component              | Description |
|------------------------|-------------|
| **Backend Framework**  | Flask (Python) |
| **LLM Inference**      | vLLM server with Meta-LLaMA 3.1-8B and DeepSeek-LLM |
| **Language Models**    | Meta-LLaMA 3.1-8B Instruct, DeepSeek 7B Chat |
| **Calendar Integration** | Google Calendar API (OAuth2 token-based) |
| **Inference Serving**  | MI300 GPU provided by AMD |
| **Data Format**        | JSON (for both input and output)

---



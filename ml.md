---
title: 🤖 AI & Automation Projects
layout: page
---

<div style="background: url('Images/StreamScraper.JPG') no-repeat center center; background-size: contain; box-shadow: 0 4px 4px rgba(0,0,0,0.1); text-align: center; padding: 300px 0;">
</div>

# StreamScraper: AI-Assisted Web Content Extraction Tool

[GitHub Repository](https://github.com/wahidupal/StreamScraper)

## Project Overview

StreamScraper is a Python-based web extraction and content analysis application designed to collect information from websites and transform unstructured web content into meaningful summaries.

The project started as a traditional web scraping application and evolved into an AI-assisted workflow by integrating a locally hosted Llama model through Ollama.

The application combines:

- Web automation
- HTML parsing
- Data extraction
- Local LLM-based text summarization
- Interactive user interfaces

---

# Project Evolution

## Version 1: Web Scraping Pipeline

The initial version focused on extracting and processing web content automatically.

Key capabilities:

- Website content extraction using Selenium
- HTML parsing using BeautifulSoup
- Removal of unnecessary elements such as scripts and styles
- Preparation of cleaned text data for further processing

Technologies:

- Python
- Selenium
- BeautifulSoup

---

## Version 2: Local LLM Integration

The project was extended by integrating a locally hosted Llama model using Ollama.

The objective was to explore how locally deployed AI models can assist data processing workflows while keeping the processing environment private and independent from external APIs.

Additional capabilities:

- Automated text summarization
- AI-assisted content interpretation
- Local LLM inference through LangChain integration

Technologies:

- Ollama
- Llama
- LangChain

---

## Version 3: Interactive Streamlit Application

The latest version introduced a user-friendly interface for managing the scraping and analysis workflow.

Features:

- Multi-page Streamlit application
- Different scraping workflows
- Interactive URL input
- Integrated extraction and summarization pipeline
- User-friendly error handling

Technologies:

- Streamlit
- Python

---

# Application Workflow

```
Website URL
      |
      ↓
Web Scraping Layer
(Selenium + BeautifulSoup)
      |
      ↓
Content Cleaning
      |
      ↓
Local LLM Processing
(Ollama + Llama)
      |
      ↓
Generated Summary
```

---

# Technical Challenges

## Processing Unstructured Web Data

Web pages contain a mixture of useful content and unnecessary elements.

The application handles:

- HTML extraction
- Content cleaning
- Removing irrelevant page elements
- Preparing text for AI processing

## Local AI Deployment Constraints

Running LLMs locally introduces hardware limitations.

The application was designed to remain lightweight by focusing on targeted summarization rather than large-scale model operations.

---

# Technology Stack

- Python
- Streamlit
- Selenium
- BeautifulSoup
- LangChain
- Ollama
- Llama
- HTML Parsing

---

# Skills Demonstrated

- Web Scraping
- Data Extraction Pipelines
- Automation
- Unstructured Data Processing
- LLM Integration
- Python Application Development
- AI-assisted Workflow Design

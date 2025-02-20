# Multimodal Ingestion with Azure Foundry API and New Agent Service

## Overview

This repository demonstrates how to use **Azure Foundry APIs** for **multimodal data ingestion** and **New Agent Service** for orchestrating parallel processing of multiple data types (text, images, etc.). The workshop will guide you through setting up the **Foundry APIs**, ingesting **text and image data**, and processing them in parallel using **GPT-4** for text generation and a **vision agent** for image analysis.

### **Objective**:
- Learn how to set up **Azure Foundry APIs** for **multimodal data ingestion**.
- Orchestrate parallel workflows using **New Agent Service**.
- Process **text data** (customer queries) with **GPT-4** and **image data** with **image recognition** agents.
- Build and execute a multimodal AI pipeline that processes text and images simultaneously.

---

## Pre-requisites

Before starting, ensure you have access to the following:

1. **Azure Subscription**:
   - Access to **Azure Machine Learning** and **Foundry APIs**.
   - You must have an **Azure OpenAI account** for **GPT-4**.

2. **OpenAI API Key**:
   - Sign up at [OpenAI](https://beta.openai.com/signup/) to get your **API key** for **GPT-4**.

3. **GitHub Repository Setup**:
   - Clone this repository to your local machine:
     ```bash
     git clone https://github.com/yourusername/multimodal-azure-demo.git
     cd multimodal-azure-demo
     ```

4. **Development Environment**:
   - **Python 3.8+** installed.
   - Create a **virtual environment**:
     ```bash
     python -m venv venv
     source venv/bin/activate  # On Windows use `venv\Scripts\activate`
     ```

---

## Setup Instructions

### Step 1: Clone the Repository
Clone this repository to your local machine:
```bash
git clone https://github.com/yourusername/multimodal-azure-demo.git
cd multimodal-azure-demo




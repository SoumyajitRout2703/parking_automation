# 🚗 Parking Automation System

An automated parking management solution leveraging Google Colab, Groq AI, and computer vision to streamline vehicle tracking and spot management.

---

## 📌 Project Overview
This project automates parking lot operations by processing visual or numerical data and leveraging LLM capabilities via Groq to handle decision-making, logging, or reporting.

### Key Features
* 📷 **Data Processing:** Handles parking lot inputs and vehicle details.
* ⚡ **Groq Llama 3 Integration:** High-speed AI inference for automated classification and text responses.
* ☁️ **Cloud Native:** Designed to run seamlessly inside Google Colab environments.

---

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Platform:** Google Colab
* **AI Model API:** [Groq Cloud Console](https://console.groq.com)
* **Libraries Used:** `groq`, `pandas`, `numpy`

---

## 🚀 Quick Start Guide

### 1. Prerequisites
You need a Groq API Key to run the inference model. 
1. Go to [Groq Console](https://console.groq.com).
2. Create a free account and generate a key under the **API Keys** tab.

### 2. Running in Google Colab
1. Download the `Parking_Automation.ipynb` file from this repository.
2. Upload and open it in [Google Colab](https://colab.research.google.com).
3. Set your Groq API key inside the Colab secrets manager (🔑 tab) or directly in your environment variables:
   ```python
   import os
   os.environ["GROQ_API_KEY"] = "your_groq_api_key_here"

   

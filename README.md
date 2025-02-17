# **Agentic Retrieval-Augmented Generation (RAG) with Real-Time APIs**

## **Project Overview**

This project demonstrates an **Agentic Retrieval-Augmented Generation (RAG)** approach that combines **retrieved knowledge from a custom document** with **real-time data** fetched via external APIs. The system answers **multi-step queries** by:

- Retrieving factual information from private documents.
- Using **OpenStreetMap API** to convert location names into latitude and longitude.
- Fetching real-time weather data using the **Open-Meteo API**.

This project was part of an **LLM training session** aimed at showcasing how RAG can dynamically combine retrieved knowledge with real-world data to provide accurate and contextually aware responses.

## **Use Case Example**

**Query**:  
*"Where is the headquarters of Grad Ascent Technologies, and what’s the weather there now?"*

**Steps**:
1. The **RAG system** retrieves the headquarters location of Grad Ascent Technologies from a custom document.
2. The **OpenStreetMap API** converts the location name into latitude and longitude.
3. The **Open-Meteo API** fetches the real-time weather for that location.

### **Output**:
A dynamic and intelligent chatbot that provides the location of the headquarters and real-time weather data in a seamless manner.

## **Technologies Used**

- **Langchain**: Used for building the RAG framework and integrating APIs.
- **OpenAI**: For generating responses using LLMs.
- **OpenStreetMap (Nominatim API)**: To fetch latitude and longitude from location names.
- **Open-Meteo API**: To retrieve real-time weather data.

## **Setup Instructions**

### Requirements
pip install langchain openai faiss-cpu chromadb tiktoken
 

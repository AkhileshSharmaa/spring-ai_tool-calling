# Spring AI Tool Calling

This project demonstrates **AI Tool Calling** using **Spring Boot** and **Spring AI**. It shows how Large Language Models (LLMs) can dynamically invoke backend tools (Java methods/APIs) to perform real actions such as calculations, data retrieval, or custom business logic based on user prompts.

## 🚀 Features

* Spring Boot backend with clean, modular architecture
* Spring AI integration for LLM interactions
* Tool Calling (Function Calling) implementation
* Automatic tool selection based on user queries
* REST APIs for interacting with the AI
* Easy to extend with new tools and models

## 🛠️ Tech Stack

* Java
* Spring Boot
* Spring AI
* LLM Provider (Ollama / OpenAI / Gemini – configurable)
* Maven

## 📌 How It Works

1. User sends a prompt via a REST API.
2. Spring AI forwards the prompt to the LLM.
3. The LLM decides whether a tool is needed.
4. Spring Boot executes the mapped Java tool method.
5. The result is returned to the LLM.
6. Final, context-aware response is sent back to the user.

## ▶️ Running the Project

1. Clone the repository
2. Configure application properties (model, API keys if required)
3. Build the project:

   ```bash
   mvn clean install
   ```
4. Run the application:

   ```bash
   mvn spring-boot:run
   ```

## 📡 API Usage

* Send a prompt to the exposed REST endpoint
* The AI may call backend tools automatically based on intent

## 🎯 Use Cases

* AI-powered assistants
* Backend automation via natural language
* Smart APIs with reasoning + actions
* Learning Spring AI Tool Calling concepts

Feel free to fork, explore, and extend 🚀


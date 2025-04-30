# IT AI Ticketing Chatbot with Semantic Kernel and Ollama

This project is an AI-powered ticketing chatbot designed to assist with IT support requests. It integrates the **Semantic Kernel** and **Ollama** to create a scalable, intelligent system capable of managing and automating IT ticket creation, query handling, and task assignment.

## Features

- **Ticket Management**: Automates the creation and management of IT support tickets.
- **Natural Language Understanding**: Uses Semantic Kernel to understand and process user requests in natural language.
- **Ollama Integration**: Leverages Ollama's advanced capabilities for AI interaction and ticketing logic.
- **Real-time Assistance**: Provides real-time IT support for common queries like password resets, software installations, and issue reporting.
- **Scalable Architecture**: Built with modular components to ensure easy extension and maintenance.
- **Semantic Search**: Uses the Semantic Kernel for efficient and accurate ticket querying, categorization, and response generation.

## Architecture

The chatbot is built on a clean, modular architecture, making it easy to manage and extend. Below are the key components:

### 1. **Bot Interface**
   - **User Interface**: Interacts with users, takes input, and displays responses.
   - **Channel Integration**: Supports integration with various messaging platforms (e.g., Slack, Microsoft Teams, Web).

### 2. **AI Layer**
   - **Semantic Kernel**: Powers the NLP (Natural Language Processing) engine to interpret and understand user requests.
   - **Ollama AI**: Implements logic for automating IT ticket creation, resolution, and routing based on user input.

### 3. **Ticket Management System**
   - **Ticket Creation**: Automatically generates tickets based on user queries.
   - **Ticket Assignment**: Routes tickets to appropriate IT support teams.
   - **Ticket Tracking**: Tracks the status and progress of each ticket.
  
### 4. **Database**
   - **User Data**: Stores user profiles, ticket history, and other relevant details.
   - **Ticket Data**: Stores ticket information such as issue types, descriptions, priority levels, and resolutions.

### 5. **External Integrations**
   - **External APIs**: For system diagnostics, network checks, etc.
   - **Authentication**: Uses OAuth2 or similar methods to verify users before submitting sensitive ticket information.

## Prerequisites

Before running this chatbot, ensure you have the following installed:

- Python 3.8+ (for the backend logic)
- **Ollama** (Ensure you have access to Ollama's API or SDK)
- **Semantic Kernel** (Make sure you have access to the Semantic Kernel libraries)
- Node.js (for frontend if you plan to run it with a web interface)
- A ticket management system (e.g., Jira, ServiceNow) or a custom database for storing tickets

## Installation

### Backend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/bahtyarr/Basic-AIChatbot-Netcore/tree/main
   cd it-ai-ticketing-chatbot

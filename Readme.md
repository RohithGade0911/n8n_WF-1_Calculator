# WF-1: Calculator – n8n Workflow

## 📌 Overview
This **n8n workflow**, `WF-1: Calculator`, is designed to process chat messages and respond with AI-powered calculations. It integrates OpenAI's **GPT-4o-mini** and a **calculator tool** to handle mathematical queries.

## 🔧 Workflow Components
### 🏗️ Core Modules
1. **🛎️ Chat Trigger** – Captures incoming messages to initiate the workflow.
2. **🤖 AI Agent** – Routes the input to the appropriate processing nodes.
3. **🧠 OpenAI Chat Model** – Uses `GPT-4o-mini` to process natural language inputs.
4. **💾 Memory Buffer** – Retains conversational context for improved interactions.
5. **🧮 Calculator Tool** – Performs arithmetic operations based on user queries.

## ⚙️ How It Works
1. ✉️ A user sends a message.
2. 🔍 The **AI Agent** processes the input using OpenAI and stored memory.
3. ➗ If a calculation is needed, the **Calculator Tool** executes it.
4. 📤 The response is sent back to the user.

## 🚀 Setup Instructions
- 📥 **Import the workflow** into `n8n`.
- 🔑 **Ensure your OpenAI API credentials** are configured.
- ✅ **Activate the workflow** to start handling chat-based calculations.

## 📝 Notes
- ⚠️ The workflow is **inactive by default**.
- 🛠️ Modify as needed to fit specific requirements.

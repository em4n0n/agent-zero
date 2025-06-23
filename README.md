# agent zero

🧠 LangGraph AI Assistant with Calculator Tool
This project is a command-line AI assistant powered by LangChain, LangGraph, and OpenAI. It can chat with users and perform basic arithmetic calculations using a custom tool.

🔧 Features
Conversational AI using OpenAI's chat model via LangChain

Custom @tool: a calculator for basic arithmetic

Streaming output with interactive responses

Command-line interface with graceful exit

🧪 Example Interaction
Welcome! I'm your AI assistant. Type 'quit' to exit.
You can ask me to perform calculations or chat with me

You: What is the sum of 3 and 5?
Assistant: The sum of 3.0 and 5.0 is 8.0

You: quit
Goodbye!

📦 Installation
Clone the repo:

git clone https://github.com/your-username/langgraph-calculator-agent.git
cd langgraph-calculator-agent

Install dependencies:
pip install -r requirements.txt

If you don't have a requirements.txt, install manually:
pip install langchain langgraph langchain-openai python-dotenv

Set up your .env file:

Create a .env file with your OpenAI API key:
OPENAI_API_KEY=your_openai_key_here

🚀 Run the App
python app.py

📁 Project Structure

app.py               # Main script
.env                 # Your OpenAI key (not tracked by Git)
requirements.txt     # Python dependencies (optional)

🛠️ Built With
LangChain

LangGraph

OpenAI API

Python
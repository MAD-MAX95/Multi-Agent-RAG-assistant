# Multi-Agent RAG Assistant

A powerful AI assistant that leverages Retrieval-Augmented Generation (RAG) alongside a multi-agent architecture to effectively process queries, retrieve relevant context, and synthesize accurate responses.

## 📁 Project Structure

- **`app.py`**: The main entry point and user interface for the application.
- **`agents.py`**: Contains the definitions, roles, and configurations for the different AI agents.
- **`pipeline.py`**: Orchestrates the RAG workflow, managing how data flows between retrieval systems and agents.
- **`tools.py`**: Defines custom tools and functions that the agents can use to execute specific tasks.
- **`requirements.txt`**: Lists all the Python dependencies required to run the project.

## 🚀 Getting Started

### Prerequisites

Ensure you have Python installed (preferably Python 3.10+).

### Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/MAD-MAX95/Multi-Agent-RAG-assistant.git](https://github.com/MAD-MAX95/Multi-Agent-RAG-assistant.git)
   cd Multi-Agent-RAG-assistant

2. Create and activate a virtual environment (optional but highly recommended):
python -m venv venv
# On macOS/Linux
source venv/bin/activate  
# On Windows
venv\Scripts\activate

3. Install the required dependencies:

pip install -r requirements.txt
Set up your environment variables:
Create a .env file in the root directory and add your required API keys (e.g., OpenAI, Anthropic, or vector database keys) depending on your setup.

🛠️ Usage
To start the assistant, run the main application:

Bash
python app.py



  

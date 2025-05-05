# Prompt-Engineering
Jupyter Notebook demonstrating 10 powerful prompt engineering techniques using LLaMA 3.2, applied to an AI assistant that generates personalized cover letters from resumes and job descriptions. Techniques include zero-shot, few-shot, chain-of-thought, ReAct, prompt chaining, and more.

### Use virtual environment for smooth installing
python3 -m venv myenv
if using linux/Mac
source myenv/bin/activate
if using windows
Run ./Scripts/activate.bat

###  Prerequisites
To run this project locally, you'll need:

- Python 3.8+
- pip
- [Ollama](https://ollama.com/) — for running LLaMA 3.2 locally


### Step 1: Install Ollama

Use the official installer:

### Step 2: Pull the LLaMA 3.2 Model
ollama pull llama3.2

### Step 3: Install Python Dependencies
pip install ollama

### Step 4: Run the model
pip run llama3.2

# Prompt Engineering 

## Project Overview

This project demonstrates different Prompt Engineering techniques using a Large Language Model (LLM) through the Groq API. Users can enter a task, select a prompting technique, and generate responses through a simple Streamlit web application.

Live Demo

https://prompt-engineering-6q5qxuvmq9dh8suitwr3ny.streamlit.app/

## Objectives

* Understand different Prompt Engineering techniques.
* Generate responses using a Large Language Model.
* Compare how different prompting techniques structure prompts.
* Provide an interactive interface using Streamlit.

## Prompting Techniques

1. **Zero-shot Prompting:** Generates responses without examples.
2. **One-shot Prompting:** Uses one example to guide the response.
3. **Few-shot Prompting:** Uses multiple examples to guide the response.
4. **Chain-of-Thought (CoT):** Encourages structured problem-solving with a concise explanation.
5. **Manual CoT:** Uses predefined steps to organize the solution.
6. **Tree-of-Thought (ToT):** Considers multiple possible approaches before selecting a suitable answer.

## Technologies Used

* Python
* Streamlit
* Groq API
* Large Language Models (LLM)

## Project Structure

```text
Prompt-Engineering/
│
├── app.py
├── llm.py
├── prompt_templates.py
├── requirements.txt
├── README.md
└── .streamlit/
    └── secrets.toml
```

## Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd Prompt-Engineering
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure the API Key

Create a Groq API key from [Groq Console](https://console.groq.com/keys).

Create `.streamlit/secrets.toml` and add:

```toml
GROQ_API_KEY = "YOUR_GROQ_API_KEY"
```

Replace the placeholder with your own API key. Never upload your API key to GitHub.

### 4. Run the Application

```bash
python -m streamlit run app.py
```

## How to Use

1. Open the application in your browser.
2. Select a prompting technique.
3. Enter a task in the text area.
4. Adjust the temperature and maximum token settings.
5. Click **Generate Response**.
6. View the generated prompt and the LLM response.

## Expected Output

The application displays the selected prompting technique's generated prompt and the response produced by the Groq LLM.

## Conclusion

This project provides practical experience with Prompt Engineering techniques and demonstrates how different prompt structures can guide LLM responses. It also introduces API integration and interactive application development using Streamlit.



# LCEL Chain using LangChain and Groq

## Overview
This project demonstrates a basic implementation of LangChain Expression Language (LCEL) using the Groq API. It combines prompt templates, a language model, and an output parser into a simple and reusable AI pipeline.

## Features
- Integration with Groq LLM using ChatGroq
- Prompt creation using ChatPromptTemplate
- LCEL chain composition using the pipe (|) operator
- Response processing using StrOutputParser
- Chain execution using the invoke() method
- Environment variable management using python-dotenv

## Technologies Used
- Python
- LangChain
- Groq API
- Jupyter Notebook
- python-dotenv

## Project Structure
```text
LCEL-CHAIN/
├── LCEL_chain(1).ipynb
├── .env
├── .gitignore
└── README.md
```

## Installation

### 1. Clone the repository
```bash
git clone https://github.com/PHANIKUMAR00/LCEL-CHAIN.git
cd LCEL-CHAIN
```

### 2. Install dependencies
```bash
pip install langchain langchain-core langchain-groq python-dotenv jupyter
```

### 3. Configure the API key
Create a `.env` file in the project directory:
```env
GROQ_API_KEY=your_groq_api_key_here
```

Replace the placeholder with your own Groq API key. Never upload your `.env` file to GitHub.

### 4. Run the notebook
Start Jupyter Notebook:
```bash
jupyter notebook
```

Open `LCEL_chain(1).ipynb` and execute the cells in order.

## LCEL Workflow

User Input → Prompt Template → Groq LLM → Output Parser → Response

## Learning Objectives
- Understand the fundamentals of LCEL
- Learn how to create prompt templates
- Integrate an LLM into a LangChain pipeline
- Process model responses using output parsers
- Build reusable AI workflows

## Author
Phani Kumar

## License
This project is intended for educational and learning purposes.

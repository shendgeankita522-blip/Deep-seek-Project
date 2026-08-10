# DeepSeek AI Project

## About the Project

This project explores Generative AI using DeepSeek, OpenRouter, and Claude models.

It contains Python programs and Jupyter notebooks for experimenting with Large Language Models (LLMs), API integration, prompt-based interaction, and model responses.

## Technologies Used

- Python
- DeepSeek
- OpenRouter
- Claude
- Jupyter Notebook
- Generative AI
- Large Language Models (LLMs)
- API Integration

## Project Structure

DEEP-SEEK-PROJECT/

├── deep-seek.py
├── openrouter.py
├── notebooks/
│   ├── 1_Code.ipynb
│   ├── Claude_Sonnet_5_.ipynb
│   ├── deepseek_with_openrouter.ipynb
│   └── Openrouter.ipynb
├── README.md
├── requirements.txt
└── .gitignore

## Files Description

### deep-seek.py

Python implementation for experimenting with DeepSeek models.

### openrouter.py

Python implementation for interacting with models through the OpenRouter API.

### 1_Code.ipynb

Initial experimentation with Generative AI and LLM-based interactions.

### Claude_Sonnet_5_.ipynb

Experiments with Claude Sonnet models.

### deepseek_with_openrouter.ipynb

Experiment using DeepSeek through the OpenRouter API.

### Openrouter.ipynb

Experiments with the OpenRouter API and different AI models.

## How the Project Works

The basic workflow is:

User Prompt
    ↓
Python Program
    ↓
OpenRouter API
    ↓
AI Model
    ↓
Generated Response

The project demonstrates how Python applications can communicate with Large Language Models through APIs.

## Installation

Clone the repository:

git clone https://github.com/YOUR-USERNAME/DEEP-SEEK-PROJECT.git

Go to the project folder:

cd DEEP-SEEK-PROJECT

Install the required packages:

pip install -r requirements.txt

## API Key Setup

Create a `.env` file in the project directory.

Add your API keys:

DEEPSEEK_API_KEY=your_api_key
OPENROUTER_API_KEY=your_api_key

Do not upload your `.env` file to GitHub.

## .gitignore

Make sure your `.gitignore` contains:

.env
*.env
__pycache__/
*.pyc
.ipynb_checkpoints/
venv/
.venv/

## Running the Project

Run the DeepSeek Python file:

python deep-seek.py

Run the OpenRouter Python file:

python openrouter.py

For notebooks, open the `notebooks` folder using Jupyter Notebook or VS Code.

## Learning Outcomes

Through this project, I learned:

- Working with Large Language Models
- DeepSeek model integration
- OpenRouter API integration
- Claude model experimentation
- Python API integration
- Prompt engineering
- Generative AI concepts
- Secure API key management
- Working with Jupyter Notebooks

## Future Improvements

- Add a Streamlit interface
- Add chatbot functionality
- Add conversation history
- Add model comparison
- Add response evaluation
- Add token and cost tracking
- Add more LLM providers
- Deploy the application

## Author

Ankita Shendge

B.Tech in Artificial Intelligence and Data Science

### Interests

- Artificial Intelligence
- Machine Learning
- Generative AI
- Data Science
- Large Language Models

## License

This project is created for educational and experimental purposes.

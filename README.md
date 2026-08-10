
├── README.md
├── requirements.txt
└── .gitignore
📄 File Description
File	Description
deep-seek.py	Python implementation for experimenting with DeepSeek
openrouter.py	Python implementation for interacting with OpenRouter
1_Code.ipynb	Initial experimentation and model interaction
Claude_Sonnet_5_.ipynb	Experiments using Claude Sonnet
deepseek_with_openrouter.ipynb	DeepSeek experiments through OpenRouter
Openrouter.ipynb	OpenRouter API experimentation
requirements.txt	Required Python dependencies
.gitignore	Prevents sensitive/unnecessary files from being uploaded
README.md	Project documentation
🛠️ Technologies Used
Python
DeepSeek
OpenRouter
Claude / Anthropic
Jupyter Notebook
Large Language Models (LLMs)
Generative AI
API Integration
🔄 Project Workflow
                 User Prompt
                     │
                     ▼
              Python Application
                     │
                     ▼
              OpenRouter API
                     │
          ┌──────────┴──────────┐
          │                     │
          ▼                     ▼
     DeepSeek Model       Other LLM Models
          │                     │
          └──────────┬──────────┘
                     │
                     ▼
              Generated Response
                     │
                     ▼
                   User
🚀 Getting Started
1. Clone the Repository
git clone https://github.com/YOUR-USERNAME/DEEP-SEEK-PROJECT.git

Move into the project directory:

cd DEEP-SEEK-PROJECT
2. Create a Virtual Environment

Windows:

python -m venv venv

Activate it:

venv\Scripts\activate

For macOS/Linux:

python3 -m venv venv
source venv/bin/activate
3. Install Dependencies
pip install -r requirements.txt
🔑 API Key Configuration

This project requires API access for the models/services being used.

Never upload your API keys directly to GitHub.

Create a .env file in the project directory:

DEEPSEEK_API_KEY=your_api_key_here
OPENROUTER_API_KEY=your_api_key_here

If your implementation uses different environment-variable names, use the names expected by your Python code.

Your .gitignore should contain:

.env
*.env
__pycache__/
*.pyc
.ipynb_checkpoints/
venv/
.venv/
▶️ Running the Python Files

Run the DeepSeek implementation:

python deep-seek.py

Run the OpenRouter implementation:

python openrouter.py
📓 Running the Notebooks

Start Jupyter Notebook:

jupyter notebook

Then open the notebooks/ directory and run the notebooks individually.

Available Experiments

1. 1_Code.ipynb

Initial experiments and exploration of LLM-based interactions.

2. Openrouter.ipynb

Experiments with OpenRouter API and model interaction.

3. deepseek_with_openrouter.ipynb

Exploration of DeepSeek models through OpenRouter.

4. Claude_Sonnet_5_.ipynb

Experiments with Claude Sonnet and comparison of generated responses.

🧠 What I Learned

Through this project, I explored:

How Large Language Models are accessed through APIs
How to integrate LLM APIs with Python
How OpenRouter provides access to multiple AI models
How DeepSeek can be integrated into an application
How to work with prompts and generated responses
How different LLMs can produce different responses
How to manage API credentials securely
How to structure Generative AI experiments using Python and Jupyter Notebook
🔍 DeepSeek + OpenRouter

One of the key experiments in this project is connecting DeepSeek models through OpenRouter.

The general flow is:

Python
   │
   ▼
OpenRouter API
   │
   ▼
DeepSeek Model
   │
   ▼
Generated Response

This approach makes it possible to interact with supported models using an API-based workflow without directly managing separate integration logic for every model.

🤖 Claude Sonnet Experiment

The project also includes experiments with Claude Sonnet.

The purpose is to explore how different LLMs respond to similar prompts and understand differences in:

Response quality
Reasoning
Explanation style
Accuracy
Response structure

These experiments provide practical exposure to working with multiple Generative AI models.

📊 Model Experimentation

The project can be extended to compare models using the same prompts.

For example:

              Same Prompt
                   │
        ┌──────────┼──────────┐
        ▼          ▼          ▼
     DeepSeek   Claude     Other LLM
        │          │          │
        ▼          ▼          ▼
     Response   Response   Response
        │          │          │
        └──────────┼──────────┘
                   ▼
              Comparison
🔐 Security

API keys are sensitive credentials.

Do not commit:

.env
API keys
Access tokens
Secret keys
Credentials

Use environment variables instead.

If an API key is accidentally pushed to GitHub, revoke/rotate it immediately.

🚧 Future Improvements

Possible improvements include:

Build a Streamlit user interface

Add side-by-side model comparison

Add conversation history

Add prompt templates

Add response evaluation

Add token/cost tracking

Add error handling and retry mechanisms

Add logging

Add support for additional LLM providers

Deploy the application

Add automated evaluation of model responses

🎯 Use Cases

This project can serve as a foundation for:

AI Chatbots
Generative AI applications
LLM experimentation
Model comparison
AI assistants
Prompt engineering
API-based AI applications
AI research and prototyping
📚 Learning Outcomes

This project provided hands-on experience with:

Generative AI → LLMs → API Integration → Prompt Engineering → DeepSeek → OpenRouter → Claude → Python

It demonstrates the practical process of experimenting with modern AI models and integrating them into Python-based applications.

👩‍💻 Author

Ankita Shendge

B.Tech — Artificial Intelligence & Data Science

Interested in:

Artificial Intelligence
Machine Learning
Generative AI
Data Science
Large Language Models
AI Application Development
⭐ Acknowledgements

This project was created as part of hands-on exploration and learning in Generative AI and Large Language Models.

If you find this project useful, consider giving the repository a ⭐.

📜 License

This project is intended for educational and experimental purposes.

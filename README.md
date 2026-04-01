🤖 AI-Powered Interview Coach

An intelligent AI-based Interview Coach that helps users prepare for job interviews through role-specific question generation and automated answer evaluation using LLMs.

🚀 Features
🎯 Role-based interview question generation
🧠 AI-powered answer evaluation with detailed feedback
📊 Structured JSON output for scoring and insights
🔁 Multi-model fallback for high reliability
⚙️ Prompt-engineered workflows for consistent results
🔐 Secure API integration using environment variables
🧩 Modular architecture supporting multiple LLMs
🛠️ Tech Stack
LLM: Cohere API
Backend: Python
Architecture: Modular, multi-LLM support
Data Format: JSON-based structured responses
📂 Project Structure
ai-interview-coach/
│── main.py
│── prompts/
│   ├── question_prompt.txt
│   ├── evaluation_prompt.txt
│── models/
│   ├── cohere_model.py
│   ├── fallback_model.py
│── utils/
│   ├── parser.py
│   ├── postprocess.py
│── .env
│── requirements.txt
│── README.md
⚙️ Installation
# Clone the repository
git clone https://github.com/your-username/ai-interview-coach.git

# Navigate into the project
cd ai-interview-coach

# Install dependencies
pip install -r requirements.txt
🔑 Environment Variables

Create a .env file and add your API key:

COHERE_API_KEY=your_api_key_here
▶️ Usage
python main.py
Enter job role (e.g., Data Scientist, Backend Developer)
Get AI-generated interview questions
Submit your answers
Receive score + feedback instantly
🧠 How It Works
User inputs role and preferences
LLM generates tailored interview questions
User submits answers
System evaluates answers using structured prompts
JSON output provides:
Score
Strengths
Improvements
Suggested better answers
🔄 Reliability Strategy
Multi-model fallback ensures continuous availability
Response post-processing improves consistency
Deterministic outputs using structured prompts
📌 Future Improvements
UI dashboard for performance tracking
Support for voice-based interviews
Integration with more LLM providers
Real-time mock interview simulations
🤝 Contributing

Contributions are welcome! Feel free to fork, open issues, or submit pull requests.

📜 License

This project is open-source and available under the MIT License.

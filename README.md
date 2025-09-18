**📝 AI Website Summarizer**
A simple Python tool that:
- 🌐 Downloads a webpage
- 🧹 Cleans and extracts visible text using BeautifulSoup
- 🤖 Uses OpenAI GPT to generate a short, human-like summary
- 🖼️ Displays the summary in a beautiful Markdown card (perfect for Jupyter)
Great for quickly summarizing blogs, news articles, and long announcements.

website-summarizer-llm/
│
├── summarizer.ipynb       # Jupyter notebook (step-by-step version)
├── requirements.txt       # Dependencies
├── .env.example           # Example API key setup
└── README.md              # This file

🛠️Tech Stack
- Python 3.x
- Requests
 (for fetching webpages)
- BeautifulSoup4
 (for HTML parsing)
- python-dotenv
 (for API key management)
- OpenAI Python SDK
 (for GPT models)
- IPython Display
 (for nice Markdown rendering)

 **Installation**
 
1️⃣ Clone this repository

"git clone https://github.com/<your-username>/website-summarizer-llm.git"

"cd website-summarizer-llm"

Setup your OpenAI API key, 
You can get an API key from OpenAI

▶️ Usage
Jupyter Notebook (recommended)
- Open summarizer.ipynb in Jupyter.
  
- Run all cells step by step.
  
- Pass any URL you want:

  
🌐 Website Summary

- Minimal personal blog with articles on AI and software.
- Includes news and project updates.
- Clean design focused on content readability.

🧠 What I Learned

- How to use BeautifulSoup to extract visible text from webpages

- How to manage secrets with .env files

- How to send structured prompts to OpenAI GPT models

- How to render output nicely inside Jupyter Notebook

- Output (beautifully rendered in Jupyter):

👨‍💻 Author

Your Name
📧 Email: chauhanabhishek9761@email.com

🔗 LinkedIn 
www.linkedin.com/in/abhishek-chauhan-8962b7261

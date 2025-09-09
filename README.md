<img width="919" height="800" alt="Screenshot 2025-09-09 080948" src="https://github.com/user-attachments/assets/81c94121-0fd9-485d-9cc3-a60f81bea4db" />📚 Library ChatBot

A simple web-based chatbot designed for library assistance. Users can interact with the chatbot through a clean HTML/CSS interface to ask questions and receive intelligent responses.
The chatbot is powered by Flask (Python) on the backend and OpenAI’s Chat Completion API for generating responses. It also fetches additional data from the Internet Archive API.

✨ Features

💬 Interactive chatbot interface for library-related queries.

🌐 Web-based app built using HTML, CSS, and Flask.

🤖 Smart responses generated with OpenAI’s Chat Completion API.

📚 Integration with Internet Archive API for book/library data.

🎨 Simple and user-friendly design.

🛠️ Technologies Used

HTML → Structuring the chatbot interface.

CSS → Styling the web page for a better user experience.

Python → Backend logic and API integration.

Flask → Lightweight Python web framework.

OpenAI’s Chat Completion API → For generating chatbot responses.

Internet Archive API → As an additional data source.

📂 Project Structure
Library_ChatBot/
│── app.py          # Flask application with chatbot logic
│── index.html  # Main chatbot interface
│── style.css   # CSS styles for UI
│── requirements.txt # Dependencies
│── README.md       # Project documentation

🚀 Deployment

The chatbot is deployed using Render and can be accessed here:
👉 https://library-chatbot.onrender.com/

⚡ Getting Started (Run Locally)

Clone the repository:

git clone https://github.com/kkasliwal05/Library_ChatBot.git
cd Library_ChatBot

Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows


Install dependencies:

pip install -r requirements.txt


Add your OpenAI API key in app.py.

Run the Flask app:

python app.py


Open your browser and visit:

http://127.0.0.1:5000/


👩‍💻 Author
Developed by Khushi Kasliwal
GitHub: kkasliwal05

Acknowledgments

A huge thanks to everyone who contributed to this project! 🌟

Special appreciation goes to:
Mentors & Guides for their constant support and valuable insights.
Collaborators & Peers who encouraged brainstorming and shared creative ideas.
Open-source communities & libraries that provided the foundation and resources to bring this project to life.

Your guidance, feedback, and contributions made this chatbot possible. 🙌

📬 Stay Connected: LinkedIn – https://www.linkedin.com/in/khushi-kasliwal-953692260/
💬 Feedback or Suggestions? Open a discussion in GitHub Discussions
📧 Contact: khushikasliwal4@gmail.com

⭐ If you like this project, don’t forget to star the repo to show your support! ⭐

🚀 Let’s build the future of AI-powered accessibility together! 🎤🤖

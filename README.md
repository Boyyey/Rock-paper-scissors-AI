Rock-Paper-Scissors AI 🤖✊✋✌️

This is a Python-based Rock-Paper-Scissors game where you play against an AI that learns and improves over time using a Markov Chain approach. The AI predicts your moves based on past patterns and adapts to counter your choices! 🎮

Features 🚀

AI that learns 📈: Uses Markov chains to analyze your move sequences and predict the next one.

Interactive GUI 🖥️: Built with Tkinter for a simple and fun user experience.

Memory Persistence 💾: AI memory is stored in ai_memory.json and evolves over multiple games.

Reset Option 🔄: Clear AI's memory at any time to start fresh.

Installation 🛠️

Prerequisites:

Ensure you have Python installed on your system (Python 3.x recommended). If you don’t have it yet, download it from python.org.

Clone the Repository:

git clone https://github.com/Boyyey/Rock-paper-scissors-AI.git
cd Rock-paper-scissors-AI

Install Dependencies:

This project only requires Tkinter, which is built into Python. However, if you need to ensure all dependencies are met, install them using:

pip install -r requirements.txt

(Optional: Create a virtual environment before installing dependencies)

Run the Game:

python rps_ai.py

How It Works ⚙️

The AI tracks the last two moves you played.

It stores and updates transition probabilities in ai_memory.json.

The AI predicts your next move and selects the best counter-move.

You challenge the AI and try to outsmart its learning process!

Reset AI Memory 🧠

If you want to erase AI's memory and start fresh:

Click the "Reset Memory" button in the game UI.

Or manually delete ai_memory.json.

Future Improvements 🌟

Adding difficulty levels (Beginner, Intermediate, Expert)

Implementing a deep learning model for better prediction

Integrating multiplayer mode

Contributing 🤝

Pull requests are welcome! Feel free to fork this repo and improve the AI. 😊

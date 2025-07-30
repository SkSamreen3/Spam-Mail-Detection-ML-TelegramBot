📧Spam-Mail-Detection-ML-TelegramBot :
A practical ML project using Logistic Regression and TF-IDF to detect spam emails. Integrated with a Telegram bot, it classifies messages as "spam" or "ham" in real-time. Built with Python, scikit-learn, and python-telegram-bot, showcasing NLP and ML in real-world communication.

🚀 Features:
-Classifies messages as spam or ham
-Uses TF-IDF for text vectorization
-Trained using Logistic Regression
-Real-time prediction via Telegram Bot
-Built with Python, scikit-learn, and python-telegram-bot

🛠️ Tech Stack:
-Python
-Libraries: pandas, numpy, scikit-learn
-Techniques: TF-IDF Vectorization, Logistic Regression

📂 Dataset:
The dataset used is a labeled email dataset with two categories:
spam → 0
ham → 1

Example format:
Category,Message
spam,Win money now!
ham,Hey, how are you?

⚙️ Things to Install:
Make sure to install the following dependencies before running the project-
pip install numpy pandas scikit-learn python-telegram-bot==13.7

🧠 Model Training Steps:
-Load and clean the dataset
-Encode labels (spam = 0, ham = 1)
-Vectorize messages using TF-IDF
-Split into training and test sets
-Train using Logistic Regression
-Evaluate model accuracy on test data

🤖 Telegram Bot Usage:
The Telegram bot classifies messages as spam or ham.

Commands:
🔁 /start — Start the bot
💬 Type any message — Bot replies with prediction

Sample Outputs:
1.Input:Congratulations! You've won a free iPhone.
Output:Spam mail
2.Input:Let’s catch up for lunch tomorrow.
Output:Ham mail

📈 Accuracy:
-Training Accuracy: ~97%
-Test Accuracy: ~96%


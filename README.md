<h1>WhatsApp Chat Analyzer</h1>

A WhatsApp Chat Analyzer built using Streamlit, Python 3.7, and several data visualization and text processing libraries. This tool helps analyze WhatsApp chat data by extracting insights such as the most active users, word frequency, emoji usage, and message trends.

<h3>🚀 Features</h3>

📊 User Activity Analysis – Identify the most active participants in a group chat.

📅 Chat Timeline – Visualize messages sent over time.

📝 Most Frequent Words – Display common words used in chats.

😊 Emoji Analysis – Extract and visualize emoji usage.

🔗 Link Extraction – Identify shared links using urlextract.

🌥 Word Cloud Generation – Generate word clouds from chat data.

📈 Data Visualizations – Utilize Matplotlib and Seaborn for graphical insights.

🛠️ Technologies Used

Python 3.7

Streamlit – For interactive UI

Pandas – For data manipulation

Matplotlib & Seaborn – For data visualization

re (Regular Expressions) – For text processing

urlextract – For extracting URLs from messages

WordCloud – For generating word clouds

emoji – For analyzing emoji usage

<h3>📦 Installation</h3>

1️⃣ Clone the repository:

git clone https://github.com/yourusername/whatsapp-chat-analyzer.git
cd whatsapp-chat-analyzer

2️⃣ Create a virtual environment:

python -m venv venv  # or use conda
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate  # Windows

3️⃣ Install dependencies:

pip install -r requirements.txt

<h3>🎯 Usage</h3>

1️⃣ Export your WhatsApp Chat:

Open WhatsApp

Select a chat > Tap More > Export Chat > Without Media

Save the .txt file

2️⃣ Run the Streamlit App:

streamlit run app.py

3️⃣ Upload the WhatsApp Chat .txt file

4️⃣ Explore Insights! 📊

<h3>📌 Example Outputs</h3>

Most Active Users Bar Chart 📊

Message Trends Over Time 📈

Top Used Emojis 😊

Frequently Used Words WordCloud 🌥

<h3>📝 Contributing</h3>

Contributions are welcome! Feel free to submit issues or pull requests.

<h3>🌟 Acknowledgments</h3>

Inspired by data analytics projects and WhatsApp data exploration.

Thanks to the open-source community for amazing Python libraries!

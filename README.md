# Whatsapp Chat Analysis

This project is a **Whatsapp Chat Analyzer** built with Python and Streamlit. It provides insightful analysis on chat logs, including statistics, activity patterns, word usage, emoji usage, and sentiment analysis. The tool supports both individual and group-level analysis.

## 🚀 Features

1. **Top Statistics**  
   Displays the total number of messages, total words, media shared, and links shared.

2. **Activity Timelines**  
   Visualizes chat activity over time with monthly and daily timelines.

3. **Activity Maps**  
   Highlights the most active days and months, along with the most active users.

4. **Word Cloud**  
   Generates a word cloud of the most frequently used words in the chat.

5. **Most Common Words**  
   Lists commonly used words, excluding stopwords.

6. **Emoji Analysis**  
   Displays the most frequently used emojis in the chat.

7. **Sentiment Analysis**  
   Analyzes the sentiment of the chat based on text and emoji usage.

## 🛠 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/divyanshusaini47/Whatsapp-chat-analysis
   ```

2. Navigate to the project directory:
   ```bash
   cd Whatsapp-chat-analysis
   ```

3. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

## 📈 Usage

1. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

2. Open your web browser and visit:
   ```
   http://localhost:8501
   ```

3. Upload a chat log file using the sidebar file uploader.

4. Select a user from the dropdown menu (or choose “Overall” for group analysis).

5. Click the **Show Analysis** button to view insights.

## 📁 Project Structure

- `app.py` – Main Streamlit application script.  
- `preprocessor.py` – Contains the function to clean and format raw chat data.  
- `helper.py` – Includes utility functions for statistical and visual analysis.  
- `stopwords.txt` – List of stopwords to exclude in word-based visualizations.

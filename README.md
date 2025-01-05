
# **Cipher-Chat Analyzer**

**Cipher-Chat Analyzer** is a sophisticated Python-based tool designed to analyze WhatsApp chat data and extract meaningful insights. The application processes chat logs to generate visualizations and statistical reports, helping users understand message patterns, user activity, and content trends. The tool is particularly valuable for **security agencies**, **law enforcement**, or **businesses** seeking to efficiently analyze communication data, spot irregularities, and identify emerging trends in conversations.

By transforming raw chat data into actionable insights, **Cipher-Chat Analyzer** assists in identifying key participants, most common words, active periods, and even sentiment through visual representations.

## Features

- **Comprehensive Message Analysis:** Provides statistics on total messages, word count, media messages, and links shared.
- **User Activity Insights:** Visualize activity trends to identify the most active users and their communication patterns.
- **Interactive Timelines:** Generate daily and monthly timelines to explore trends in message frequency over time.
- **Word Cloud Generation:** Displays the most frequently used words in a visually appealing word cloud.
- **Emoji Usage Analysis:** Analyzes emoji usage and identifies the most frequently used ones.
- **Media and Link Tracking:** Tracks the number of media files and links shared in the conversation.
- **Group and Personal Messaging:** Identifies the balance between personal messages and group messages.

## Technologies Used

- **Python 3.x**: Primary programming language used for data processing and backend operations.
- **Streamlit**: Web framework used to build the interactive user interface.
- **Pandas**: For efficient data manipulation and analysis of chat data.
- **Matplotlib/Seaborn**: Visualization libraries used to create insightful charts and graphs.
- **WordCloud**: Used to generate word clouds based on the frequency of words in the chat.
- **URLExtract**: A library for extracting URLs from chat messages.
- **Emoji**: A library for detecting and analyzing emoji usage in the chat.
- **Regular Expressions (Regex)**: Utilized for processing and parsing the WhatsApp chat data.

## Installation Guide

### Prerequisites

- Python 3.x
- Pip (Python's package manager)

### Installation Steps

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/Cipher-Chat-Analyzer.git
   cd Cipher-Chat-Analyzer
   ```

2. Create a virtual environment (recommended for project isolation):

   ```bash
   python -m venv venv
   source venv/bin/activate  # For Windows: venv\Scripts\activate
   ```

3. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

## Usage Instructions

1. Run the application with:

   ```bash
   streamlit run app.py
   ```

2. Once the app is up and running, upload a WhatsApp chat file (in `.txt` format) via the file uploader in the sidebar.
3. Choose the user you would like to analyze, or select "Overall" to analyze all participants.
4. Click **"Show Analysis"** to generate visualizations and insights based on the chat data.

## How It Works

- The application processes WhatsApp chat logs to extract metadata such as timestamps, user names, and message content.
- The extracted data is used to create various reports, including:
  - Message frequency timelines (daily and monthly)
  - Word clouds for common terms
  - User activity insights, highlighting the most active participants
  - Emoji usage analysis and media tracking
- The results are presented in interactive graphs, enabling users to easily navigate and explore communication trends.

## Planned Enhancements

- Expand the chat data parsing capabilities to handle a broader range of chat formats.
- Integrate sentiment analysis to gauge the tone of conversations.
- Develop additional features like topic modeling, conversation summarization, and keyword tracking.

## License

This project is licensed under the MIT License. Please see the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- **Streamlit** for its powerful framework to create real-time interactive applications.
- **Pandas**, **Matplotlib**, **Seaborn**, and **WordCloud** for simplifying data analysis and visualization.
- **URLExtract** for extracting links from the chat messages.
- **Emoji** for detecting and analyzing emojis in the conversation.

---


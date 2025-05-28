- AI Chat Log Summarizer

The "AI Chat Log Summarizer" is a Python-based NLP tool that reads ".txt" chat logs between a user and an AI assistant, analyzes them, and generates a concise summary. The summary includes total messages, counts by speaker, and the most frequently used keywords, helping understand the key topics in the conversation.

This project was built using Google Colab and basic Natural Language Processing techniques (e.g., "nltk", and "Counter").

---

- Project Files

| File                         | Description                                         |
|------------------------------|-----------------------------------------------------|
| `main AI-Chat-Log-Summarizer.ipynb` | Google Colab-compatible Jupyter notebook (main code) |
| `chat.txt`                   | Sample chat log input                               |
| `README.md`                  | Documentation and about this project                         |
| `screenshots/sample-output.png` | Sample screenshot of notebook output             |

- How to Run (Google Colab)

  - Steps:

1. **Open the Notebook**  
    [Open in Google Colab](https://colab.research.google.com)  
 

2. **Upload the Chat Log File**  
   You'll be prompted to upload a `.txt` file (like `chat.txt`) using:
   ```python
   from google.colab import files
   uploaded = files.upload()
   
3. ** Run All Cells**
   
    Execute all the cells in order. The script will:
    
    1.Parse the chat log
    
    2.Count messages from User and AI
    
    3.Extract top 5 keywords (excluding stopwords)

    4.Print a summary report
   
4. Sample Input (chat.txt)
    User: Hello!
    AI: Hi! How can I assist you today?
    User: Can you explain what machine learning is?
    AI: Certainly! Machine learning is a field of AI that allows systems to learn from data.

5.  Sample Output (Notebook)
 Summary
   -The conversation had exchanges. Total exchanges: 4
  
   -User messages (2):
  - Hello!
  - Can you explain what machine learning is?
  
   -AI messages (2):
  - Hi! How can I assist you today?
  - Certainly! Machine learning is a field of AI that allows systems to learn from data.
  
   -Most common keywords: learning, machine, machine learning
  
  -Topic Summary: The user asked mainly about machine learning and its definition.
  
  Top 5 Most Frequent Words/Phrases:
    1. machine learning (Frequency: 2)
    2. machine (Frequency: 2)
    3. learning (Frequency: 2)
    4. learning assist (Frequency: 1)
    5. assist today (Frequency: 1)



 AI News Summarizer

 Overview

AI News Summarizer is an intelligent workflow automation project developed using **n8n** and **Google Gemini AI**.

The system automatically collects news from multiple RSS feeds and Search APIs, merges and processes the articles, generates concise AI-powered summaries using Google Gemini, and sends the summarized news directly to the user's email.

This reduces the time required to read multiple news articles while keeping users informed with the most important updates.

 Features

- Automated News Collection
- RSS Feed Integration
- Search API Integration
- AI-powered News Summarization
- Google Gemini AI Integration
- Daily Scheduled Execution
- Automatic Email Delivery
- No Manual News Reading Required

Problem Statement

People consume news from multiple websites every day. Reading every article is time-consuming and often leads to information overload.

This project automates the process by collecting news from multiple sources, summarizing the important information using Artificial Intelligence, and delivering a concise report directly to the user's inbox.



 Solution

The workflow performs the following operations:

1. Schedule Trigger starts automatically.
2. Collects news from RSS feeds.
3. Fetches additional news through Search API.
4. Merges all collected news.
5. Aggregates the articles.
6. Uses Google Gemini AI to summarize the content.
7. Sends the summarized report through Gmail.



 Workflow Architecture

Schedule Trigger

↓

RSS Feed

+

Search API

↓

Merge

↓

Data Aggregator

↓

Google Gemini AI

↓

Gmail

↓

Daily AI News Summary

---

## Tech Stack

- n8n
- Google Gemini AI
- RSS Feed
- Search API
- Gmail
- JavaScript



 Project Structure

AI-News-Summarizer/

├── README.md

├── workflow/

│ └── ai-news-summarizer.json

├── screenshots/

│ └── workflow.png

└── docs/



Installation

1. Clone the repository.

2. Install n8n.

3. Import the workflow JSON.

4. Configure:
   - Google Gemini API Key
   - Gmail Credentials
   - Search API Key

5. Activate the workflow.



 Future Improvements

- Multi-language summaries
- Topic-wise categorization
- Personalized news preferences
- Web dashboard
- Mobile notifications
- AI keyword filtering
- News sentiment analysis



 Author:

Vishnu D

Electronics & Communication Engineering Student

AI & Automation Enthusiast


## License

MIT License

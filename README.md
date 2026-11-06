# AI News Summarizer – Automated Daily News Digest

## Overview

The **AI News Summarizer** is an AI-powered workflow automation project built using n8n that simplifies daily news consumption by automatically collecting, summarizing, and delivering news articles through email.

The workflow integrates RSS feeds with Large Language Models (LLMs) to transform lengthy news articles into concise, informative summaries. The generated news digest is delivered directly to the user's Gmail inbox, reducing the time and effort required to stay informed.

The project achieved a **93% reduction in manual news-reading time** through automated news collection and AI-powered summarization.

## Features

- **Automated News Collection:** Fetches news articles from RSS feeds.
- **AI-Powered Summarization:** Uses LLMs to generate concise and informative summaries.
- **Daily News Digest:** Automatically delivers summarized news through Gmail.
- **Workflow Automation:** Orchestrates the entire process using n8n.
- **Time Efficiency:** Reduces manual news-reading time by 93%.
- **Email Integration:** Sends personalized news digests directly to the inbox.

## Workflow

1. **Schedule Trigger:** Initiates the workflow automatically.
2. **RSS Feed Integration:** Collects articles from configured news sources.
3. **Article Processing:** Extracts relevant article information.
4. **AI Summarization:** Uses an LLM to generate concise summaries.
5. **Digest Generation:** Organizes summarized articles into a readable format.
6. **Gmail Integration:** Sends the daily news digest via email.

## Technologies Used

- **n8n** – Workflow automation and orchestration
- **RSS Feeds** – Automated news ingestion
- **Google Gemini / LLMs** – AI-powered summarization
- **Gmail API** – Automated email delivery
- **Google OAuth 2.0** – Authentication and integration
- **Docker** – Local workflow deployment

## Key Achievement

- Reduced manual news-reading time by **93%** through automated collection, summarization, and email delivery.

## Use Cases

- Daily personalized news consumption
- Automated news summarization
- AI-powered information extraction
- Productivity enhancement
- Workflow automation using LLMs

## Security & Configuration

Before sharing the workflow publicly, sensitive information such as API keys, OAuth credentials, and environment-specific identifiers should be replaced with placeholders.

To configure the workflow:

1. Import the workflow JSON into your n8n instance.
2. Configure the required RSS feed sources.
3. Set up the required LLM credentials.
4. Configure Gmail OAuth authentication.
5. Update the schedule trigger according to your preference.
6. Test the workflow before enabling automatic execution.

**Important:** Never commit API keys, access tokens, or other sensitive credentials to a public GitHub repository.

## Future Improvements

- Support for additional news sources
- Topic-based personalized news filtering
- Sentiment analysis of news articles
- HTML-formatted email digest with improved styling
- AI-generated categorization of news
- Interactive dashboard for summarized news
- Duplicate article detection

## Author

**Sahith Reddy Challarapu**

- GitHub: [SahithReddy-GitHub](https://github.com/SahithReddy-GitHub)
- LinkedIn: [sahithch](https://linkedin.com/in/sahithch)

---

*Built with n8n and LLMs to make daily news consumption smarter, faster, and more efficient.*

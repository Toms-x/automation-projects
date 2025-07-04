# AI-Powered YouTube Content Research Workflow

*Automated daily content research and script generation for finance YouTube channels*

## Overview

This n8n workflow automatically researches trending finance topics from multiple sources and generates complete YouTube content packages including scripts, titles, and thumbnail hooks.

## How It Works

### **Daily Automation**
- Runs automatically every 24 hours
- Zero manual intervention required for research phase

### **AI Research Agent**
- GPT-4o powered research agent
- Equipped with 3 specialized data collection tools:
  - **Reddit Monitor**: Trending topics from finance subreddits
  - **Google Trends**: Popular finance search terms
  - **News Aggregator**: Latest headlines from financial news sites

### **Human-AI Collaboration**
- System sends curated topics to Slack for approval
- Workflow pauses until human review is complete
- Maintains quality control while leveraging AI speed

### **Content Generation**
Once approved, the system generates:
- **Full Video Script** (1900-2200 words)
- **3 SEO-Optimized Titles**
- **3 Thumbnail Text Hooks**
- **Audio Voiceover** (via ElevenLabs)

### **Organization & Logging**
- All content logged to Google Sheets
- Organized file structure for easy access
- Complete audit trail of generated content

## Results

- **Zero decision fatigue** - Wake up to curated topic suggestions
- **Trend accuracy** - Content aligns with real audience interests  
- **Fast production** - Topic to script in under 1 hour
- **Competitive advantage** - Cover trends before competitors

## Technical Stack

- **n8n** - Workflow orchestration
- **OpenAI GPT-4o** - AI research and content generation
- **ElevenLabs** - Text-to-speech conversion
- **Google Sheets** - Data logging and organization
- **Slack** - Human approval interface
- **Multiple APIs** - Reddit, Google Trends, News sources

## Setup Requirements

1. n8n instance (cloud or self-hosted)
2. OpenAI API key
3. ElevenLabs API key
4. Google Sheets integration
5. Slack workspace
6. API access for data sources (Reddit, Google Trends, etc.)

## Use Cases

- **Content Creators**: Automated topic research and script generation
- **Marketing Teams**: Trend monitoring and content planning
- **Finance Educators**: Stay current with market discussions
- **Social Media Managers**: Multi-platform content pipeline

## Future Enhancements

- Sentiment analysis integration
- Visual content generation (charts, infographics)
- Multi-platform content adaptation
- Performance feedback loop with analytics


*Built with ❤️ for AI, automation, and finance content*
<p align="center">
  <a href="https://brightdata.com/">
    <img src="https://mintlify.s3.us-west-1.amazonaws.com/brightdata/logo/light.svg" width="300" alt="Bright Data Logo">
  </a>
</p>

# Review Intelligence Agent 🕵️‍♂️✨

**A powerful tool for collecting, analyzing, and generating insights from customer reviews across multiple platforms using AI agents. 🤖💡**

<div align="center">
  <img src="https://img.shields.io/badge/python-3.8+-blue"/>
  <img src="https://img.shields.io/badge/License-MIT-blue"/>
</div>

---

## Features 🚀

- **Multi-platform Review Collection**: Scrape reviews from various platforms including Trustpilot 🌐
- **Sentiment Analysis**: Analyze customer sentiment across key aspects (Support, Pricing, Ease of Use) 📊
- **Actionable Insights**: Generate business intelligence from review data 📈✨
- **Aspect-based Analysis**: Deep dive into specific aspects of your product/service 🔍

## Prerequisites 🛠️

- Python 3.8+ 🐍
- pip (Python package manager) 📦
- [Bright Data](https://brightdata.com/) API token 🔑
- [Nebius](https://studio.nebius.com/) API key 🔑

## Installation ⚙️

1. Clone the repository:
    
        git clone <repository-url>
        cd review-intelligence-agent

2. Install dependencies:
    
        pip install -r requirements.txt

3. Create a `.env` file in the project root with your API keys:
    
        NEBIUS_API_KEY=your_nebius_api_key
        BRIGHT_DATA_API_TOKEN=your_bright_data_token
        WEB_UNLOCKER_ZONE=your_web_unlocker_zone
        BROWSER_ZONE=your_browser_zone

## Usage ▶️

1. Update the `product_urls` list in `review_intelligence.py` with your target review pages 📝
2. Run the script:
    
        python review_intelligence.py

## Output 📤

The script will output a JSON analysis containing:
- Extracted reviews with metadata 🗂️
- Sentiment analysis scores for key aspects 🎯
- Business insights and recommendations 🧠💡

## Configuration ⚙️📝

You can customize the analysis by modifying the agent configurations in `review_intelligence.py`:
- Adjust the LLM model parameters 🧩
- Modify aspect categories and keywords 📝
- Configure task parameters and expected outputs 🎛️


# AI-Based Automated Content Marketing Optimizer

An all-in-one AI-powered system designed to streamline and optimize your content marketing efforts. This project generates engaging social media posts, analyzes their sentiment, runs A/B tests to identify top performers, tracks key campaign metrics, and integrates seamlessly with tools like Google Sheets and Slack for real-time updates and automated reporting.

---

## 🚀 Features

### Intelligent Content Generation  
Leverages cutting-edge AI models (Groq LLaMA 3.3 and Gemini 1.5) to create trend-relevant, optimized content tailored for social media platforms.

### Dynamic Trend Analysis  
Continuously gathers and processes trending topics from sources like Google Trends and Reddit to inform content creation with the latest market interests.

### Advanced Sentiment Evaluation  
Assesses the emotional tone and polarity of each generated post variant, providing a sentiment score to help gauge audience reception.

### Robust A/B Testing Framework  
Automatically compares different versions of content to determine which performs better based on engagement metrics.

### Comprehensive Metrics Tracking  
Monitors impressions, click-through rates, conversions, user engagement, and trend relevance scores to measure campaign success accurately.

### Automated Machine Learning Updates  
Retrains underlying ML models on fresh campaign data to improve future content recommendations and predictions.

### Integration with Google Sheets  
Logs generated content, sentiment data, and campaign metrics directly into Google Sheets for easy access and collaborative analysis.

### Slack Notification System  
Sends timely alerts to your Slack workspace about A/B test winners, model retraining completions, and other important updates.

---

## 🧰 Technology Stack

- **Python** — Core programming language
- **Streamlit** — Interactive UI framework
- **Groq & Gemini APIs** — AI content generation backends
- **Google Sheets API** — Data logging and integration
- **Slack Webhooks** — Real-time notification delivery
- **scikit-learn** — Machine learning and model training
- **NLP Libraries** — TextBlob, spaCy, TextStat for sentiment and text analysis
- **PyTrends & Reddit API** — Real-time trend extraction

---

## 📁 Project Structure

```plaintext
content_engine/      # Handles content creation and trend-driven optimization
sentiment_engine/    # Sentiment and emotion detection modules
ab_testing/          # A/B test logic and scoring
metrics_engine/      # Tracks and analyzes campaign metrics, triggers retraining
integrations/        # Connectors for Google Sheets and Slack
ml_engine/           # Machine learning training and retraining components
app4.py              # Streamlit user interface entrypoint
.env                 # Environment variables (excluded from repo for security)

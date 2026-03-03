# BME-HackNight-Day
This is a hackathon project of Team Watt for BME HackNight&amp;Day

# <center>RiskLens AIt</center>

### RiskLens AI: Real-Time Sentiment & Regulatory Early Warning System
*	Institutional investors and asset managers face significant risks from sudden news cycles or sudden regulatory shifts, especially in highly volatile sectors like fintech and crypto-assets. 

*	RiskLens AI is a real-time early warning micro-agent designed to protect portfolios by analyzing unstructured data. 

*	The system continuously monitors predefined financial news feeds, social sentiment, and regulatory announcements regarding specific assets. 

*	Instead of a complex, bloated dashboard, RiskLens uses Natural Language Processing (LLMs) to instantly analyze the sentiment and extract risk-related entities from the text.

*	When a specific asset's negative sentiment or regulatory risk threshold is breached, the system immediately generates a contextual alert. 

*	It does not just provide a "red flag"; it provides a concise AI-generated summary explaining why the risk score spiked. 

*	This allows portfolio managers to make proactive decisions minutes or hours before traditional quantitative market indicators reflect the price drop.

*	Ultimately, RiskLens acts as an automated, intelligent filter against market noise, focusing strictly on actionable risk mitigation.


### Please describe why do you think your solution will be innovative
*	Current financial monitoring platforms are often heavily reliant on reactive, quantitative price data. 

*	RiskLens is innovative because it is purely proactive, focusing entirely on qualitative, unstructured data before it impacts the market price. 

*	Instead of trying to predict the entire market direction—which is prone to high error rates—it acts as a highly specialized risk filter for specific assets or compliance rules. 

*	By integrating Generative AI directly into the alert pipeline, it solves the "black box" problem of traditional sentiment analysis. 

*	When an alert is triggered, the portfolio manager receives human-readable reasoning alongside the alert, saving crucial time that would otherwise be spent manually verifying the news. 

*	Furthermore, its modular design means it can be narrowly focused on niche, emerging markets (like crypto regulations) where traditional institutional tools are currently lagging.

### Please describe how do you intend to achieve the goal and your experience with these technologies
*	We will utilize a system; backend data pipeline will be built using Python and FastAPI for robust, high-speed data handling. We will simulate real-time unstructured data ingestion using the News API (or targeted RSS feeds). The core logic will rely on integrating the OpenAI API (or similar LLM) with strictly crafted prompt engineering to perform rapid sentiment analysis and risk-entity extraction. Finally, we will build a interface using Streamlit to demonstrate the real-time alert feed and risk dashboards directly to the jury. Our team have engineering background includes advanced Python programming, complex algorithm implementation, and mathematical data transformations. This technical foundation, combined with a strong understanding of AI integration and logic design, ensures that we can efficiently manage the backend data flow, API calls, and system architecture under tight time pressure.



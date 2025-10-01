📊 Stock Market Research – Event Study Project

This repository contains my work on an academic industry-sponsored project completed as part of the LSE Data Analytics Career Accelerator (2025).

The project explored how stock markets react to key firm-specific and macro-economic events. The goal was to analyze price movements, investor reactions, and cumulative returns around these events, and to generate insights that could inform timing strategies for investments.

⚠️ Note: All data used is publicly available (financial markets & macroeconomic indicators). To respect confidentiality, no proprietary company data or internal reports are included.

⸻

🔍 Problem Statement

Financial markets are influenced by corporate announcements (e.g., earnings surprises) and macro events (e.g., FOMC, CPI releases).
The challenge was to quantify how different events impact stock returns and identify patterns that may guide better decision-making.

⸻

🛠 Tools & Methods
	•	Python (pandas, numpy, matplotlib, seaborn) → data wrangling, calculations, event windows
	•	Event Study Methodology → measuring abnormal returns around event dates
	•	Cumulative Abnormal Returns (CAR) → quantifying investor reactions
	•	Data Sources:
	•	Yahoo Finance (stock OHLC data)
	•	FRED (macroeconomic series)
	•	SEC EDGAR (institutional ownership data)

⸻

📂 Repository Structure
stock-market-research/
│
├── datasets/        # Public datasets used for analysis

├── visuals/         # Charts & visualizations generated
├── README.md        # Project overview (this file)
📊 Key Visuals

Here are a few sample outputs from the analysis (see /visuals/ for more):
	•	Stock price reaction around earnings announcements
	•	Cumulative abnormal returns (CAR) during event windows
	•	Impact of FOMC & CPI events on tech stocks
	•	Institutional ownership & stock volatility trends

⸻

✅ General Findings
	•	Earnings surprises tend to generate significant short-term abnormal returns, with stronger effects in high-volatility stocks.
	•	Macroeconomic events (e.g., interest rate changes, inflation releases) influence not only returns but also investor sentiment, often leading to short-term overreactions.
	•	Institutional ownership data showed correlations with post-event recovery speed, suggesting that large investors stabilize market response.
	•	Dashboards and charts helped highlight optimal event windows (e.g., D-2 to D+10) where market reactions are most pronounced.

⸻

🎯 Skills Demonstrated
	•	Event study design & implementation
	•	Data wrangling and cleaning of large financial datasets
	•	Statistical analysis of abnormal returns and CAR
	•	Data visualization (charts, dashboards, storytelling)
	•	Transforming raw market data into business-relevant investment insights

⸻

📌 Disclaimer

This project was conducted for academic purposes as part of the LSE Data Analytics Career Accelerator employer project.
	•	All data included here is publicly available.
	•	No proprietary information or confidential company outputs are shared.





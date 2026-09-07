# Order-to-Cash-CRM-ERP-Analytics

📊 End-to-End Order-to-Cash (O2C) Analytics: Optimizing B2B Revenue Operations
🏢 Business Context
In this simulation, I acted as the lead Data & Business Analyst for a mid-sized B2B company. The executive team was experiencing friction between Sales (pushing for more leads), Operations (struggling with fulfillment bottlenecks), and Finance (concerned about delayed cash flow).
My objective was to design a relational CRM/ERP database, extract cross-departmental data, and identify actionable bottlenecks in the "Order-to-Cash" lifecycle to improve revenue operations.
🛠️ Technical Stack
Data Engineering: Python (Faker, Pandas) to generate 5,000+ rows of synthetic, relational data with intentional process anomalies.
Database Management: SQLite/PostgreSQL relational schema design (6 normalized tables).
Data Extraction: Advanced SQL utilizing CTEs, Window Functions (RANK()), and Date Math.
Data Visualization: Power BI (Interactive 3-tab dashboard).
💡 Key Business Insights & Recommendations
After analyzing the O2C lifecycle, three major findings were identified:
Sales Rep Performance Anomaly (The "Enterprise Closer"):
Finding: While Rep Lisa Collier had the lowest win rate (36%), she generated the highest total revenue ($146k). Analysis revealed her average deal size was $3,658, compared to the team average of ~$2,800.
Recommendation: Restructure lead routing. Assign high-value, complex enterprise leads to Lisa, while routing high-volume, smaller leads to reps with higher win rates (e.g., Anita Richard at 52%).
Trapped Cash in the Tech Sector:
Finding: The Tech industry holds the highest amount of Outstanding Accounts Receivable ($27k+ in the West region alone), despite having 0 officially "overdue" invoices.
Recommendation: Implement proactive "Net-30" payment reminders 5 days prior to the due date specifically for Tech and Healthcare accounts to accelerate cash flow.
Marketing Channel Efficiency:
Finding: "Website" leads convert at 40.95% and close 1 day faster on average than Cold Calls.
Recommendation: Maintain current marketing spend, but optimize the website UX to shave that 1 day off the sales cycle, which compounds to significant operational savings.

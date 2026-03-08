AI Data Analyst Agent

During my final year, I wanted to build something that goes beyond just analyzing data — something that actually does the work for you. This project is an automated data analysis pipeline that takes a raw CSV file, cleans it, crunches the numbers, builds visual charts, and sends a full HTML report straight to your inbox — all without manual intervention.


💡 Why I Built This


I noticed that data analysis workflows are often repetitive — clean the data, compute metrics, make charts, share the report. I automated the entire cycle using n8n, so it happens in one seamless pipeline.

🚀 What It Does

Ingests and cleans raw CSV datasets automatically
Computes KPIs and key metrics from the data
Generates 3 chart types (Bar, Pie, Line) via QuickChart.io
Assembles a clean, visual HTML report with embedded charts
Delivers the report and chart attachments via Gmail API (OAuth 2.0)

🛠️ Built With

n8n — Workflow automation
JavaScript — Data processing and logic
QuickChart.io — Chart generation
Gmail API (OAuth 2.0) — Automated email delivery

⚙️ How to Run It

Import workflow.json into your n8n instance
Set up your Gmail API credentials (OAuth 2.0)
Upload your CSV file and trigger the workflow
Check your inbox for the report!

📸 Screenshots
 
 Workflow
 <img width="1920" height="1080" alt="Screenshot 2026-03-08 214704" src="https://github.com/user-attachments/assets/85c7bf44-4fa6-4354-abd1-062098629cce" />
 Email Delivery
 <img width="1920" height="1080" alt="Screenshot 2026-03-08 215237" src="https://github.com/user-attachments/assets/e98a58cc-6a98-440f-97ba-dcf836ade299" />
 Output Report
 <img width="1920" height="1080" alt="Screenshot 2026-03-08 214854" src="https://github.com/user-attachments/assets/88070b8a-94ed-4183-ad4e-76f633f7b870" />
<img width="1920" height="1080" alt="Screenshot 2026-03-08 214842" src="https://github.com/user-attachments/assets/78651d01-e585-4bb3-881f-8b4ce49b06e5" />
<img width="1920" height="1080" alt="Screenshot 2026-03-08 214832" src="https://github.com/user-attachments/assets/b5d7adf4-ea8f-4ae4-859e-ca5932d30f75" />



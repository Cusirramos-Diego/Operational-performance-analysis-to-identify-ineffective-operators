# Operational performance analysis to identify ineffective operators

📌 Project Description:  
An analysis was conducted to identify underperforming operators within a virtual telephony service using indicators such as missed calls, wait times, and call volume, with the aim of supporting supervisors in operational decision-making.

🔍 Methodology:  
•	Performed an exploratory analysis on over 300,000 call records, cleaning data inconsistencies, constructing operator-specific metrics, and segmenting performance by call type, client, and communication direction.  
•	Defined operational inefficiency indicators and validated differences using statistical tests, complementing the analysis with visualizations designed to identify patterns.

🛠️ Technical Tools:  
Python | Pandas | NumPy | SciPy | SQL | Matplotlib | Seaborn

🏆 Achievements:  
•	Analyzed the performance of over 1,000 operators using operational indicators derived from the company database, identifying those with the highest and lowest activity levels.  
•	Developed a classification model based on four key KPIs to detect low-performing operators.  

📈 Graphical visualization:  
•	Correlation matrix between operational metrics:  
<img width="1204" height="921" alt="image" src="https://github.com/user-attachments/assets/3bf065d3-1281-4e99-b981-29deda0e5dc0" />

•	Distribution of efficient and inefficient operators based on average call waiting time:  
<img width="1544" height="766" alt="image" src="https://github.com/user-attachments/assets/bd985809-69fb-4aae-90b5-ea6554064413" />

🎯 KPIs to change:  
•	Missed call rate.  
•	Average wait time.  
•	Average handling time.  
•	Calls handled by an operator.  
•	Service Level.  

🤔 Subsequent hypothesis worth evaluating:  
If supervisors receive automated alerts regarding underperforming operators and redistribute the call load in a timely manner, the proportion of missed calls and the average wait time will decrease.

💡 Recommended decision for the Product Manager:  
Based on the analysis, it is proposed to incorporate a real-time monitoring dashboard into the platform that automatically identifies operators with high missed-call rates, long wait times, or low outbound activity. This would allow supervisors to intervene before performance impacts the customer experience.

🚀 Expected impact:  
•	Reduction in missed calls.  
•	Improved customer satisfaction.  
•	Greater operational efficiency.  
•	Better utilization of agent capacity.  

💭 General recommendations:  
Proposed redistributing the operational workload, continuously monitoring critical indicators, and establishing alerts for operators with high missed-call rates.

▶️ How to Run:  
•	Clone the repository: git clone https://github.com/Cusirramos-Diego/Operational-performance-analysis-to-identify-ineffective-operators.git  
• Open the notebook in Jupyter Notebook or Jupyter Lab.  
• Run the cells sequentially to reproduce the analysis and visualizations.  
• Review insights, conclusions, and recommendations.

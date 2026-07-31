# Operational performance analysis to identify ineffective operators

📌 Project Description:  
An analysis was conducted to identify underperforming operators within a virtual telephony service using indicators such as missed calls, wait times, and call volume, with the aim of supporting supervisors in operational decision-making.

❓ Business Challenge:  
The virtual telephony platform generated large volumes of operational data but lacked a systematic way to identify underperforming operators before service quality deteriorated. The objective of this project was to transform operational records into actionable performance indicators that enable supervisors to detect inefficiencies early, prioritize corrective actions, and improve customer service.

🔍 Methodology:  
•	Performed an exploratory analysis on over 300,000 call records, cleaning data inconsistencies, constructing operator-specific metrics, and segmenting performance by call type, client, and communication direction.  
•	Defined operational inefficiency indicators and validated differences using statistical tests, complementing the analysis with visualizations designed to identify patterns.

🧠 Why this analytical approach?:  
Operator performance cannot be accurately assessed using a single operational metric. For this reason, I adopted a multidimensional evaluation approach that combines missed calls, waiting times, handled call volume, and outbound activity. This framework provides a more comprehensive assessment of operational efficiency and supports decisions based on overall performance rather than isolated indicators.

⚙️ Main analytical decisions:  
•	Removed duplicate records and validated data consistency before performing any analysis.  
•	Distinguished inbound, outbound, internal, and external calls to avoid mixing operational contexts.  
•	Designed four operational KPIs that capture different dimensions of operator performance.
•	Combined exploratory analysis with statistical hypothesis testing to validate whether observed differences between operator groups were statistically significant.
•	Prioritized business interpretability so that every metric could be directly used by supervisors for operational monitoring.

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

🔮 What I would do next:  
To extend this project, I would develop an operational performance score that updates automatically using real-time call data. I would also evaluate predictive models capable of identifying operators at risk of becoming inefficient before service quality declines. Finally, I would assess the impact of implementing automated supervisor alerts through controlled experiments to quantify improvements in missed-call rates and customer satisfaction.

▶️ How to Run:  
•	Clone the repository: git clone https://github.com/Cusirramos-Diego/Operational-performance-analysis-to-identify-ineffective-operators.git  
• Open the notebook in Jupyter Notebook or Jupyter Lab.  
• Run the cells sequentially to reproduce the analysis and visualizations.  
• Review insights, conclusions, and recommendations.

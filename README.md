🚀 Summer Analytics Capstone: Dynamic Pricing for Urban Parking Lots
📌 Project Overview
This repository contains the Summer Analytics Capstone Project implementing demand-based dynamic pricing for urban parking lots using real-world data. The project uses occupancy, traffic conditions, queue length, special day indicators, and vehicle type to dynamically adjust parking prices, demonstrating practical use of data analytics for smart city management.

⚙️ Tech Stack Used
Python: pandas, matplotlib

Google Colab / Jupyter Notebook

Git and GitHub for version control and submission

🏗️ Architecture Diagram
mermaid
Copy
Edit
flowchart TD
    A[Data Collection: CSV] --> B[Preprocessing with pandas]
    B --> C[Calculate Demand Factors]
    C --> D[Apply Dynamic Pricing Formula]
    D --> E[Generate Visualization with matplotlib]
    E --> F[Report & Submission]
📝 Project Workflow
Data Preprocessing:

Merge date and time into timestamps.

Map categorical features (traffic, vehicle type) to numerical values.

Sort dataset by time.

Demand Calculation:

Calculate demand based on occupancy, traffic factor, queue length, special day, vehicle type factor.

Dynamic Pricing:

Formula: Price = Base Price * (1 + λ * Normalized Demand)

Base Price = ₹10, λ = 0.5.

Visualization:

Plot generated using matplotlib to visualize price trends over time.

Report:

Documents methodology, results, and future scope for the project.

📂 Repository Contents
summer_analytics_dynamic_pricing.ipynb - Final working notebook with preprocessing, pricing model, and visualization.

advanced_dynamic_pricing_plot.png - Pricing trend visualization.

Summer_Analytics_Capstone_Report.pdf - Detailed optional report for documentation.

✅ Submission Checklist
 Public GitHub repository with all code files and documentation.

 Required repositories starred with screenshots for submission.

 All files documented and clean for evaluation.

📬 Contact
Name: Gagandeep



✨ This project fulfills the Summer Analytics Capstone requirements and demonstrates practical application of data analytics for smart city parking management.



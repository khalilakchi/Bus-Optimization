# Bus-Optimization
🚌 Bus Route Optimization in Greater Venice
This project was developed as part of the Managerial Decision Making & Modeling course during the first year of the Master’s in Data Analytics for Business and Society at Ca' Foscari University of Venice. It aims to optimize public bus routes operated by ACTV in the Veneto region, balancing profitability, service quality, and environmental considerations.

📌 Objective
The goal is to develop a multi-objective linear programming model that helps the transport authority allocate routes and resources more efficiently. The optimization problem seeks to:

Maximize profit from selected routes

Maximize public service utility based on route desirability

Ensure minimum service coverage

Minimize environmental impact

📊 Data & Sources
Data was manually collected from ISTAT and ACTV websites and includes:

8 bus routes in the Veneto region (origins, destinations, costs, revenues)

Demand levels and ticket pricing

Operational costs and utility scores

Bus availability and policy constraints

🔍 Methodology
Mathematical model formulated using Mixed-Integer Linear Programming (MILP)

Implemented in Python using PuLP

Three core optimization scenarios analyzed:

Profit maximization

Utility maximization

Environmental and minimum service requirements


🛠️ Tools
Python (PuLP, Pandas, NumPy)

Google Colab for development and visualization

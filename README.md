**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: Shivaprasad Bhat M

**INTERN ID**: CTIS7640

**DOMAIN**: DATA SCIENCE
**DURATION**: 12 WEEKS

**MENTOR**: NEELA SANTOSH

Supply Chain Cost Optimization using Linear Programming and PuLP
Overview

This project focuses on solving a real-world business problem in supply chain management using optimization techniques. The objective is to minimize transportation and operational costs while satisfying supply and demand constraints. The project is implemented using Python and the PuLP library for Linear Programming.

Business Problem

In supply chain management, companies often face challenges in minimizing transportation costs while ensuring that customer demand is met efficiently. This project optimizes supplier allocation and distribution planning to reduce overall logistics expenses.

Objective
Minimize total transportation cost
Optimize supplier-to-location allocation
Satisfy supply and demand constraints
Improve operational efficiency using Linear Programming
Technologies Used
Python
PuLP
Pandas
Matplotlib
Jupyter Notebook
Project Structure
supply-chain-cost-optimization/
│
├── Optimization Model.ipynb
├── supply_chain_data.csv
├── README.md
└── requirements.txt
Dataset

The dataset contains supply chain information including:

Supplier names
Locations
Transportation costs
Product availability
Order quantities
Optimization Technique

This project uses Linear Programming to solve the optimization problem.

Constraints
Supply should not exceed supplier availability
Demand requirements must be satisfied
Shipment quantities cannot be negative
Features
Data preprocessing using Pandas
Linear Programming model using PuLP
Transportation cost minimization
Optimization result analysis
Graphical visualization of optimized distribution
Output

The model generates:

Optimal transportation plan
Minimum total transportation cost
Supplier allocation insights
Visualization charts

Install Dependencies
pip install -r requirements.txt
Run the Project
jupyter notebook

Open:
Optimization Model.ipynb
Results


<img width="744" height="356" alt="Image" src="https://github.com/user-attachments/assets/6801065a-ad25-46dc-bb76-fe3d8b76ae51" />
<img width="989" height="688" alt="Image" src="https://github.com/user-attachments/assets/67067639-6ff1-4ab4-88f9-6bce4fd0946c" />


The optimization model successfully reduced transportation costs by selecting the most cost-effective supplier distribution strategy while meeting business constraints.

Business Insights
Lower-cost suppliers were prioritized
Transportation efficiency improved
Supply and demand were balanced effectively
Operational decision-making became more data-driven

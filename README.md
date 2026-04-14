# Optimizing maize distribution logistics in Rwanda using the Minimum Cost Capacitated Flow Problem (MCCFP)

This project was completed as part of my final year undergraduate studies in Mathematics and Statistics at the University of Rwanda.

## Project Overview

The objective of this project was to optimize maize distribution across different regions in Rwanda by minimizing transportation costs while satisfying supply, demand, and storage constraints. This is a case study of Eastern Province and Kigali City through East Africa Exchange (EAX) warehousing infrastructure.

The model considers:
- Supply districts: Nyagatare, Kirehe, Gatsibo, Kayonza, Rwamagana, Ngoma and Bugesera.
- Warehouses: Kayonza, Bugesera, and Rwamagana  
- Demand districts: Nyarugenge, Gasabo, and Kicukiro  

## Methodology

The problem was formulated as a **Minimum Cost Capacitated Flow Problem (MCCFP)**.

In this model:
- Nodes represent supply points, warehouses, and demand points  
- Edges represent transport routes with associated costs and capacity limits  
- The objective is to determine how much maize should flow through each route in order to minimize total cost  

The model ensures that:
- Supply from each production area is not exceeded  
- Demand at each destination is satisfied  
- Warehouse capacities are respected  

The model was implemented in Python.

## My Contribution

This was a group project carried out by two students. My contributions included:
- Formulating the mathematical model (decision variables, constraints, and objective function)  
- Implementing the model in Python  
- Running the optimization and analyzing the results  
- Interpreting how changes in parameters affect the solution  

## Data Challenges

One of the main challenges was the lack of a complete dataset.

- Data on production, transport cost, and storage capacity were not available in one place  
- We used available national data and introduced assumptions where necessary  
- Care was taken to ensure the model still reflects realistic conditions  

## Project Files

- [FYP_MCCFP_Maize_Distribution.pdf](FYP_MCCFP_Maize_Distribution.pdf)
  Full final year project report containing the problem description, model formulation, methodology, and results.

- [mccfp_network_visualization.pdf](mccfp_network_visualization.pdf)  
  Visualization of the initial network showing all possible flows between supply points, warehouses, and demand locations.

- [mccfp_optimal_solution_flows.pdf](mccfp_optimal_solution_flows.pdf)  
  Visualization of the optimized network showing the selected routes and flow quantities that minimize total transportation cost.

- [Maizeflow_dataset.xlsx](Maizeflow_dataset.xlsx)  
  Dataset used in the project, including supply quantities, demand values, transportation costs, and warehouse capacities.

- [fixed_mccfp_model.py](fixed_mccfp_model.py)  
  Python implementation of the MCCFP model used to compute the optimal distribution of maize. 

## Citation

Shimimana, Jean de la Croix. (2025). Optimizing maize distribution logistics in Rwanda using the Minimum Cost Capacitated Flow Problem (MCCFP). Final Year Project, University of Rwanda, College of Science and Technology.

## Acknowledgement

This project was completed in collaboration with Esther Mahoro as part of our final year undergraduate studies at the University of Rwanda, College of Science and Technology (UR-CST). 

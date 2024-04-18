# Semiconductor Supply Chain Engineering Report

## Key Achievements:
1. Utilized anyLogistix for greenfield analysis and optimized distribution center locations, resulting in:
   - 15% increase in revenue.
   - 2-day reduction in lead time through transportation and warehouse adjustments.
2. Designed a 4-level Bill of Materials (BOM) tree and utilized Linear Programming (LP) models in MRP for make-or-buy decisions. Strategies were validated through Excel calculations.
3. Formulated mixed-integer LP models for aggregated planning strategy, resulting in:
   - 13% increase in objective value.
   - Better alignment with manufacturing capacity by allocating specialized labor forces to distinct operations.

## Detailed Analysis and Validation:
1. Network Planning and MRP Make-or-Buy Decision:
   - Refer to “Semiconductor supply planning.pdf” for network planning details.
   ![Image 1](https://github.com/Johnlee19990908/Semiconductor_Supply_Chain_Engineering/raw/main/readme_image/1.png)

   ![Image 2](https://github.com/Johnlee19990908/Semiconductor_Supply_Chain_Engineering/raw/main/readme_image/2.png)
   - Utilized Lingo model “BOM B_or_M.lg4” for make-or-buy decision, validated in Excel calculation “BOM B_or_M.xlsx”.
   
   ![Image 3](https://github.com/Johnlee19990908/Semiconductor_Supply_Chain_Engineering/raw/main/readme_image/3.png)
   ![Image 4](https://github.com/Johnlee19990908/Semiconductor_Supply_Chain_Engineering/raw/main/readme_image/4.png)
   ![Image 5](https://github.com/Johnlee19990908/Semiconductor_Supply_Chain_Engineering/raw/main/readme_image/5.png)


3. Aggregation Planning Strategy:
   - Refer to “Aggregate planning question.png” for an overview.
   - Utilized mixed-integer linear regression models in “Aggregate planning.lg4”.
   - Extension on planning strategy with specialized labor force constraints detailed in LP model “Aggregate planning extend.lg4”.

## Extension on Planning Strategy and Worker Allocation Analysis:
Conducted analysis comparing two scenarios based on the LP model:
1. Original scenario: Total workers performing three different processes simultaneously, resulting in an objective value of 553211.

![Image 6](https://github.com/Johnlee19990908/Semiconductor_Supply_Chain_Engineering/raw/main/readme_image/6.png)

2. Modified scenario: Workers split into 3 processes with specialized labor force constraints, resulting in an objective value increase to 626203.2.

![Image 7](https://github.com/Johnlee19990908/Semiconductor_Supply_Chain_Engineering/raw/main/readme_image/7.png)

## Conclusion:
The modified scenario with specialized labor force allocation aligns more closely with manufacturing capacity and provides clearer insights into hiring and firing strategies.


# Optimizing Marketing Budget Allocation Using Linear Programming

## Project Overview
This project involves developing a marketing budget allocation strategy using linear programming, considering return on investment (ROI) estimates for various advertising platforms. The objective is to recommend an optimal budget distribution while adhering to specific constraints imposed by the chief marketing officer.

## Content & Technologies Covered
1. **Python Code File:** Python code file utilizing packages like Pandas, Numpy for database, Gurobi for optimization process by Linear Programming, and Matplotlib, Seaborn for data visualization.
3. **Report:** A well-written report detailing the problem, solution approach, and results.

## Problem Description
The marketing department is tasked with recommending a budget distribution for a $10 million marketing budget across different mediums based on ROI estimates. Constraints include budget limits for each platform and specific relationships between the budgets of different mediums.

## Project Steps
1. **Formulation of Linear Program:**
   - Define the marketing budget allocation problem as a linear program.
   - Utilize Gurobi to find the optimal budget allocation.

2. **Comparison of ROI Data:**
   - Assess two sets of ROI estimates from different consulting firms.
   - Compare optimal allocations based on each set of ROI data.

3. **Sensitivity Analysis:**
   - Explore how optimal allocation changes with variations in ROI data.
   - Determine the range within which ROI for each advertising medium can vary while maintaining the same optimal allocation.

4. **Dynamic Budget Allocation:**
   - Incorporate the possibility of reinvesting half of the return on investment each month.
   - Determine the optimal allocation for each month while adhering to specific constraints.

5. **Stability Check:**
   - Evaluate the stability of the allocation by checking if monthly changes in spending stay within $1 million per platform.
   - Propose modifications to the model if instability is detected.

6. **Documentation and Generalization:**
   - Document the entire process in a PDF file, including detailed analysis, relevant graphs, and code chunks.
   - Ensure code generalization to accommodate new ROI data without hard-coded values.

## Conclusion
This project aims to provide a data-driven and optimized marketing budget allocation strategy, considering various constraints and potential variations in ROI data. The comprehensive report and accompanying Python code demonstrate the analytical approach and decision-making process involved in achieving an optimal solution.

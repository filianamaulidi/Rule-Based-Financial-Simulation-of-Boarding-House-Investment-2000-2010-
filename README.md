# Rule-Based Financial Simulation of Boarding House Investment 2000-2010

## Overview
This project implements a rule-based financial simulation to model the business performance of boarding house (kos) investments over a 10-year period (2000–2010).
The simulation evaluates how initial capital, investment decisions, operational costs, and dynamic business rules influence the final number of rooms and remaining balance for each investor.

The project focuses on translating textual business rules into a deterministic computational model and ensuring consistent, reliable financial calculations.

## Problem Statement
The main challenge of this project is the limited and loosely-defined business rules provided in textual form.
Key difficulties include:
+ Sparse rule definitions
+ Multiple conditional changes across time
+ Interdependencies between investment actions and operational costs
+ The need to infer hidden patterns from example outputs

The core task is to carefully interpret these rules and convert them into a robust simulation engine capable of producing accurate yearly financial outcomes.

# Steps to Do
The simulation is implemented through the run_simulation() function, which performs the following steps:
+ Initialize each investor’s financial state
+ Apply yearly investment and cost rules
+ Update the number of rooms and financial balance
+ Incorporate dynamic rule changes over time
+ Produce final financial outcomes after 10 years

The system applies rule parsing, financial modeling, and iterative simulation logic to ensure consistent computation.

# Output & Results
| Nama  | Saldo | Kamar |
|------ |-------|-------|
|Susi   |3532163122|  150  |
|Budi   |5387916000|  115  |
|Siti   |12122350|  214  |
|Bambang|5914754400|  197  |

For each investor, the simulation produces:
+ Final number of boarding rooms
+ Final financial balance after 10 years
+ Complete yearly transaction history
These outputs allow direct comparison of business strategies and long-term financial performance.

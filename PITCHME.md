@snap[west]
# Query Tuning: 
## The art of easing the pain!
@snapend

---
@snap[west span]
## Content by Johan Kangasniemi 

(and Cyanne Wilcox!)

---
@snap[west span]
## Contents

An overview of how to tune queries on SQL Server using the available tools in SSMS
@snapend

---
@snap[north-west]
## Why query tune?
@snapend
@snap[centre]
@ul
- Less resource requirement
- Lighter queries tend to run faster
- Lighter queries can allow more queries to run at the same time
- Reduces locking
- Makes best use of the server
@ulend
@snapend

---
@snap[north-west]
## What are we looking for?
@snapend

@snap[centre]
@ul
- Mismatch between Expected and Actual Rows
- "Strange" operators
- Warnings 
@ulend
@snapend

---
@snap[north-west]
## Tools we'll use:
@snapend
@snap[centre]
@ul
- Live Query Stats
- Stats Time and Stats IO
- Estimated and Actual Query plans
@ulend
@snapend

---

@snap[north-west]
## Live Query Stats
@snapend
@snap[centre]
@ul
- "Living" version of the query plan; similar to SSIS flows
- Visual aid to see bottle necks in queries
@ulend
@snapend

---

@snap[north-west]
## Set Statistics Time, Set Statistics IO
@snapend
@snap[centre]
@ul
- Toggle {ON|OFF} in session
- Provide evidence
- Observer effect should be considered
- Easy, Quick, Effective
@ulend
@snapend

---

# DEMO no. 1

---

@snap[north-west]
## What's in a query plan?
@snapend
@snap[centre]
@ul
- Tells what SQL will do
- Estimated/Actual
- Operators
- Pipes/Paths
- Properties
@ulend
@snapend

---

@snap[north-west]
## Query plan: Overview
@snapend
@snap[centre]
![QueryPlan](assets/images/QueryPlan.PNG)
@snapend

---

@snap[north-west]
## Query plan: Operator
@snapend
@snap[centre]
![QueryPlan](assets/images/QueryPlan_Operator.PNG)
@snapend

---

@snap[north-west]
## Query plan: Pipes/Paths
@snapend
@snap[centre]
![QueryPlan](assets/images/QueryPlan_Pipe.PNG)
@snapend

---

@snap[north-west]
## Query plan: Tooltips (Hover over)
@snapend
@snap[centre]
![QueryPlan](assets/images/QueryPlan_Tooltip.PNG)
@snapend

---

@snap[north-west]
## Query plan: Properties (F4 in SSMS)
@snapend
@snap[centre]
![QueryPlan](assets/images/QueryPlan_Properties.PNG)
@snapend

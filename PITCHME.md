@snap[west]
# Snippets: 
## Quickly reusable code
@snapend

---
@snap[west span]
## Content by Johan Kangasniemi

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

# DEMO!

---


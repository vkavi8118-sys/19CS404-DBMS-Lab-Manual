# Experiment 4: Aggregate Functions, Group By and Having Clause

## AIM
To study and implement aggregate functions, GROUP BY, and HAVING clause with suitable examples.

## THEORY

### Aggregate Functions
These perform calculations on a set of values and return a single value.

- **MIN()** – Smallest value  
- **MAX()** – Largest value  
- **COUNT()** – Number of rows  
- **SUM()** – Total of values  
- **AVG()** – Average of values

**Syntax:**
```sql
SELECT AGG_FUNC(column_name) FROM table_name WHERE condition;
```
### GROUP BY
Groups records with the same values in specified columns.
**Syntax:**
```sql
SELECT column_name, AGG_FUNC(column_name)
FROM table_name
GROUP BY column_name;
```
### HAVING
Filters the grouped records based on aggregate conditions.
**Syntax:**
```sql
SELECT column_name, AGG_FUNC(column_name)
FROM table_name
GROUP BY column_name
HAVING condition;
```

**Question 1**
--
-- Paste Question 1 here
<img width="1373" height="651" alt="Screenshot 2026-09-02 220314" src="https://github.com/user-attachments/assets/c10fff62-170e-4cc5-a420-6ec1e1764522" />
<img width="876" height="240" alt="Screenshot 2026-09-02 220324" src="https://github.com/user-attachments/assets/ca4ea84c-c544-4db5-b132-4a6f69114fc2" />


**Output:**
<img width="1157" height="805" alt="Screenshot 2026-09-02 220338" src="https://github.com/user-attachments/assets/86638e7d-455f-4605-b8dd-7c398c20a989" />


**Question 2**
---
-- Paste Question 2 here
<img width="1381" height="800" alt="Screenshot 2026-09-02 220355" src="https://github.com/user-attachments/assets/e0ac0568-7269-4843-b35a-23189f449480" />

**
**Output:**
<img width="1170" height="547" alt="Screenshot 2026-09-02 220501" src="https://github.com/user-attachments/assets/0c890255-96a7-4d2a-9d13-4d6565b1fc87" />

**Question 3**
---
-- Paste Question 3 here
<img width="1198" height="826" alt="Screenshot 2026-09-02 220533" src="https://github.com/user-attachments/assets/cf73631d-22d4-48fd-b93a-bb0f6559c38a" />

**Output:**

<img width="1162" height="806" alt="Screenshot 2026-09-02 220548" src="https://github.com/user-attachments/assets/cbfe26ce-6ccc-4fda-baa7-ddcf10ecff91" />

**Question 4**
---
-- Paste Question 4 here

<img width="1092" height="750" alt="Screenshot 2026-09-02 220601" src="https://github.com/user-attachments/assets/cb713d8b-60d3-402a-aa73-eb7d26ad43b6" />


**Output:**
<img width="1167" height="423" alt="Screenshot 2026-09-02 220615" src="https://github.com/user-attachments/assets/c55644d0-cb4b-41ef-9c3a-7c0205b1f94d" />

**Question 5**
---
-- Paste Question 5 here

<img width="1352" height="796" alt="Screenshot 2026-09-02 220718" src="https://github.com/user-attachments/assets/7e4f4cf3-c1a0-41b0-a7cb-179cef86ae3a" />


**Output:**
<img width="1168" height="418" alt="Screenshot 2026-09-02 220728" src="https://github.com/user-attachments/assets/98b95b7f-4482-41c9-b267-99e1857a5f18" />

**Question 6**
---
-- Paste Question 6 here
<img width="1366" height="772" alt="Screenshot 2026-09-02 220759" src="https://github.com/user-attachments/assets/60419f1c-c7f8-4def-ab72-0bd31da0345b" />

**Output:**
<img width="1157" height="422" alt="Screenshot 2026-09-02 220813" src="https://github.com/user-attachments/assets/42059220-e9c1-49c4-8f25-aefeabef4bc0" />

**Question 7**
---
-- Paste Question 7 here

<img width="1360" height="807" alt="Screenshot 2026-09-02 220828" src="https://github.com/user-attachments/assets/efb30166-0964-4cd5-962b-97388e0b2ca3" />

**Output:**
<img width="1172" height="472" alt="Screenshot 2026-09-02 220841" src="https://github.com/user-attachments/assets/d6c48f77-9cf5-4fba-9f47-40cd5b94f202" />

**Question 8**
---
-- Paste Question 8 here
<img width="1361" height="826" alt="Screenshot 2026-09-02 220904" src="https://github.com/user-attachments/assets/4a1546cc-6643-4e2e-a413-3100d554006b" />


**Output:**
<img width="1162" height="477" alt="Screenshot 2026-09-02 220923" src="https://github.com/user-attachments/assets/02eda07d-cf64-4fe0-8a48-0d2120511d0b" />

**Question 9**
---
-- Paste Question 9 here
<img width="1357" height="827" alt="Screenshot 2026-09-02 220945" src="https://github.com/user-attachments/assets/e30ff5bd-1369-4b1d-b4fb-7aa7afa34f1b" />


**Output:**

<img width="1165" height="572" alt="Screenshot 2026-09-02 221001" src="https://github.com/user-attachments/assets/0b77e11e-bf2f-4100-8fed-5fcc73de4d68" />


**Question 10**
---
-- Paste Question 10 here
<img width="1361" height="826" alt="Screenshot 2026-09-02 221027" src="https://github.com/user-attachments/assets/eb75c894-2b78-49b5-9063-1d8b007b5766" />


**Output:**

<img width="1167" height="567" alt="Screenshot 2026-09-02 221040" src="https://github.com/user-attachments/assets/b46057e2-ecae-4015-82bf-5fa35ee4359e" />

**GRADE**
<img width="1252" height="152" alt="Screenshot 2026-09-02 221833" src="https://github.com/user-attachments/assets/798217da-45ef-4662-8c8b-62446f05eb5a" />

## RESULT
Thus, the SQL queries to implement aggregate functions, GROUP BY, and HAVING clause have been executed successfully.

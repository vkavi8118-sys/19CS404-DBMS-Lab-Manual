# Experiment 5: Subqueries and Views

## AIM
To study and implement subqueries and views.

## THEORY

### Subqueries
A subquery is a query inside another SQL query and is embedded in:
- WHERE clause
- HAVING clause
- FROM clause

**Types:**
- **Single-row subquery**:
  Sub queries can also return more than one value. Such results should be made use along with the operators in and any.
- **Multiple-row subquery**:
  Here more than one subquery is used. These multiple sub queries are combined by means of ‘and’ & ‘or’ keywords.
- **Correlated subquery**:
  A subquery is evaluated once for the entire parent statement whereas a correlated Sub query is evaluated once per row processed by the parent statement.

**Example:**
```sql
SELECT * FROM employees
WHERE salary > (SELECT AVG(salary) FROM employees);
```
### Views
A view is a virtual table based on the result of an SQL SELECT query.
**Create View:**
```sql
CREATE VIEW view_name AS
SELECT column1, column2 FROM table_name WHERE condition;
```
**Drop View:**
```sql
DROP VIEW view_name;
```

**Question 1**
--
-- Paste Question 1 here
<img width="1427" height="765" alt="Screenshot 2026-09-03 002536" src="https://github.com/user-attachments/assets/a31fcca5-5175-40be-a4b4-2ed8a05dd929" />
 <img width="1047" height="333" alt="Screenshot 2026-09-03 002624" src="https://github.com/user-attachments/assets/1f084802-7af3-49ea-b4e2-6007177f0a25" />

**Output:**
<img width="1235" height="592" alt="Screenshot 2026-09-03 002642" src="https://github.com/user-attachments/assets/5d6cb8bf-9408-4685-8e44-02ee495626fb" />


**Question 2**
---
-- Paste Question 2 here

<img width="1387" height="692" alt="Screenshot 2026-09-03 002703" src="https://github.com/user-attachments/assets/bc46688a-7eb3-403a-9646-261a44dd1eb3" />
<img width="1077" height="275" alt="Screenshot 2026-09-03 002715" src="https://github.com/user-attachments/assets/bc6210d4-e395-45f3-abde-468c65de51b3" />

**Output:**
<img width="1232" height="597" alt="Screenshot 2026-09-03 002759" src="https://github.com/user-attachments/assets/cbdafd8c-474d-4724-8e32-a877182c5cb2" />


**Question 3**
---
-- Paste Question 3 here

<img width="1433" height="797" alt="Screenshot 2026-09-03 002828" src="https://github.com/user-attachments/assets/4fb504e6-6860-4d9f-bb98-11ff5185bd04" />
<img width="831" height="217" alt="Screenshot 2026-09-03 002847" src="https://github.com/user-attachments/assets/47b677e5-afa5-4f6d-9fd8-b699ecce04ca" />


**Output:**
 <img width="1220" height="620" alt="Screenshot 2026-09-03 002907" src="https://github.com/user-attachments/assets/b522a694-83b6-4f75-9712-efdbc348f977" />

**Question 4**
---
-- Paste Question 4 here
<img width="1403" height="682" alt="Screenshot 2026-09-03 002939" src="https://github.com/user-attachments/assets/76ff9fca-9b21-4fa4-8c8e-dbfba57d400d" />
<img width="898" height="251" alt="Screenshot 2026-09-03 003000" src="https://github.com/user-attachments/assets/7fcbb0dc-24f7-4a17-9fab-195447621373" />


**Output:**
<img width="1230" height="650" alt="Screenshot 2026-09-03 003017" src="https://github.com/user-attachments/assets/ca409acf-99c4-438f-b80a-424732c3e88d" />


**Question 5**
---
-- Paste Question 5 here
<img width="1452" height="795" alt="Screenshot 2026-09-03 003035" src="https://github.com/user-attachments/assets/0e020eeb-b3d8-4c19-a7ef-6030dbcb0bbe" />


**Output:**
<img width="1230" height="525" alt="Screenshot 2026-09-03 003107" src="https://github.com/user-attachments/assets/caf906f7-73d2-4b48-ac96-7388e0c2f0e1" />

**Question 6**
---
-- Paste Question 6 here
<img width="1415" height="666" alt="Screenshot 2026-09-03 003133" src="https://github.com/user-attachments/assets/f9147113-9657-4cdc-b114-75206a7cbad9" />
<img width="855" height="245" alt="Screenshot 2026-09-03 003148" src="https://github.com/user-attachments/assets/96fa1bae-31be-4e95-b30d-0e3286b9fe76" />


**Output:**

<img width="1217" height="601" alt="Screenshot 2026-09-03 003238" src="https://github.com/user-attachments/assets/07d59dc5-aa78-4ddd-aa40-80a238ecbfe8" />

**Question 7**
---
-- Paste Question 7 here

<img width="1400" height="752" alt="Screenshot 2026-09-03 003258" src="https://github.com/user-attachments/assets/8ec63df2-533e-410c-8c26-2486bb85bee4" />
<img width="1067" height="208" alt="Screenshot 2026-09-03 003317" src="https://github.com/user-attachments/assets/e1f52262-306c-4d3d-bbea-051b8e2d8174" />


**Output:**
<img width="1220" height="610" alt="Screenshot 2026-09-03 003334" src="https://github.com/user-attachments/assets/42ec87e5-9dd0-4e7c-8ae9-19cc866b2996" />

**Question 8**
---
-- Paste Question 8 here

<img width="1393" height="782" alt="Screenshot 2026-09-03 003401" src="https://github.com/user-attachments/assets/87d2fc08-d9d6-4767-9cdd-9ade8f2eafd4" />
<img width="522" height="221" alt="Screenshot 2026-09-03 003417" src="https://github.com/user-attachments/assets/1771c4c7-aa5c-4456-af68-9365c23dd626" />


**Output:**

<img width="1235" height="587" alt="Screenshot 2026-09-03 003449" src="https://github.com/user-attachments/assets/2344c486-c87e-4919-9d14-e30c2bfcc3eb" />

**Question 9**
---
-- Paste Question 9 here
<img width="1448" height="801" alt="Screenshot 2026-09-03 003512" src="https://github.com/user-attachments/assets/ecbab286-da40-4118-9d86-2f95da4bf229" />
 <img width="927" height="161" alt="Screenshot 2026-09-03 003531" src="https://github.com/user-attachments/assets/f0452067-e78c-49c4-86b8-596f27d1c777" />

**Output:**
<img width="1232" height="795" alt="Screenshot 2026-09-03 003552" src="https://github.com/user-attachments/assets/fd4f215b-eeb1-4cbd-83b2-6853afe7493b" />

**Question 10**
---
-- Paste Question 10 here

<img width="1427" height="767" alt="Screenshot 2026-09-03 003622" src="https://github.com/user-attachments/assets/d82d6c7e-48bf-4f45-9a3e-4b6e28281e93" />
<img width="747" height="220" alt="Screenshot 2026-09-03 003640" src="https://github.com/user-attachments/assets/94a56695-f099-43fd-98b1-0be1f0c548df" />


**Output:**
<img width="1233" height="568" alt="Screenshot 2026-09-03 003701" src="https://github.com/user-attachments/assets/fe2d5f89-84bb-44aa-8f8f-cf5ff06fe3da" />
**GRADE**
<img width="1295" height="110" alt="Screenshot 2026-09-03 003822" src="https://github.com/user-attachments/assets/80d0922c-a282-42fc-8f0c-93d0a75457bc" />

## RESULT
Thus, the SQL queries to implement subqueries and views have been executed successfully.

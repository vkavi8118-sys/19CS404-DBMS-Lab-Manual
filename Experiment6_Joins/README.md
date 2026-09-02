# Experiment 6: Joins

## AIM
To study and implement different types of joins.

## THEORY

SQL Joins are used to combine records from two or more tables based on a related column.

### 1. INNER JOIN
Returns records with matching values in both tables.

**Syntax:**
```sql
SELECT columns
FROM table1
INNER JOIN table2
ON table1.column = table2.column;
```

### 2. LEFT JOIN
Returns all records from the left table, and matched records from the right.

**Syntax:**

```sql
SELECT columns
FROM table1
LEFT JOIN table2
ON table1.column = table2.column;
```
### 3. RIGHT JOIN
Returns all records from the right table, and matched records from the left.

**Syntax:**

```sql
SELECT columns
FROM table1
RIGHT JOIN table2
ON table1.column = table2.column;
```
### 4. FULL OUTER JOIN
Returns all records when there is a match in either left or right table.

**Syntax:**

```sql
SELECT columns
FROM table1
FULL OUTER JOIN table2
ON table1.column = table2.column;
```

**Question 1**
--
-- Paste Question 1 here
<img width="1427" height="710" alt="Screenshot 2026-09-03 003938" src="https://github.com/user-attachments/assets/c520311e-2aac-49c0-a493-f8400c63cb5b" />
<img width="1217" height="501" alt="Screenshot 2026-09-03 003953" src="https://github.com/user-attachments/assets/06927146-38c9-40f0-afbc-6c3a6656209b" />

**Output:**
<img width="1231" height="557" alt="Screenshot 2026-09-03 004008" src="https://github.com/user-attachments/assets/504713a2-3d9b-4124-bfd3-ab66f6a2635b" />

**Question 2**
---
-- Paste Question 2 here

<img width="1432" height="817" alt="Screenshot 2026-09-03 004029" src="https://github.com/user-attachments/assets/fc1bbf26-d9db-422b-bfe3-4c1616e83026" />
<img width="1222" height="817" alt="Screenshot 2026-09-03 004102" src="https://github.com/user-attachments/assets/d6599919-a1e9-4f5e-94a3-a0e266ca5ec7" />
<img width="1067" height="370" alt="Screenshot 2026-09-03 004116" src="https://github.com/user-attachments/assets/0571ab44-aacc-4c69-8f02-73519273ac2f" />


**Output:**

<img width="1227" height="801" alt="Screenshot 2026-09-03 004134" src="https://github.com/user-attachments/assets/110587ec-4ad1-440b-90f6-e780a75d56ce" />

**Question 3**
---
-- Paste Question 3 here
<img width="1433" height="820" alt="Screenshot 2026-09-03 004154" src="https://github.com/user-attachments/assets/f14bfe65-f43a-4ea3-b71c-9438d06fe51a" />
<img width="1236" height="818" alt="Screenshot 2026-09-03 004212" src="https://github.com/user-attachments/assets/0fe7a8c8-6403-429c-947a-1107e31bcd99" />
 <img width="1078" height="358" alt="Screenshot 2026-09-03 004243" src="https://github.com/user-attachments/assets/f3571db8-cc2a-4054-a35a-cb26b84f6ba8" />

**Output:**

<img width="1235" height="818" alt="Screenshot 2026-09-03 004311" src="https://github.com/user-attachments/assets/8149ad19-8dff-4974-bf8c-cc1a98219271" />

**Question 4**
---
-- Paste Question 4 here
<img width="1412" height="740" alt="Screenshot 2026-09-03 004334" src="https://github.com/user-attachments/assets/936a3145-d8be-4ac7-8105-e9b1019fecf6" />
<img width="1205" height="626" alt="Screenshot 2026-09-03 004355" src="https://github.com/user-attachments/assets/e130555d-aa20-4dfa-8f75-0e07198789d8" />


**Output:**

<img width="1208" height="818" alt="Screenshot 2026-09-03 004425" src="https://github.com/user-attachments/assets/0efa0e2f-8f2b-4213-84d6-af189b5cda55" />


**Question 5**
---
-- Paste Question 5 here
<img width="1462" height="822" alt="Screenshot 2026-09-03 004459" src="https://github.com/user-attachments/assets/c6518d8e-683d-4b09-b6e8-80b0abf74460" />
<img width="888" height="220" alt="Screenshot 2026-09-03 004542" src="https://github.com/user-attachments/assets/d0c923a0-a83c-4f0e-a797-b625983a2ede" />


**Output:**

<img width="1223" height="525" alt="Screenshot 2026-09-03 004559" src="https://github.com/user-attachments/assets/fc838c89-fd04-4b8d-8423-6d25762ce9ec" />

**Question 6**
---
-- Paste Question 6 here

<img width="1407" height="732" alt="Screenshot 2026-09-03 004625" src="https://github.com/user-attachments/assets/28ea8b75-84f0-453c-a025-8c14d913f0e2" />
<img width="1151" height="777" alt="Screenshot 2026-09-03 004643" src="https://github.com/user-attachments/assets/8e73a130-f7fd-42ad-bbc2-f52b229e4abc" />


**Output:**
<img width="1220" height="811" alt="Screenshot 2026-09-03 004718" src="https://github.com/user-attachments/assets/31ddfdc5-cd44-498f-8b59-60d1e59c744b" />

**Question 7**
---
-- Paste Question 7 here

<img width="1440" height="822" alt="Screenshot 2026-09-03 004746" src="https://github.com/user-attachments/assets/6aeb3ebc-4c9e-4cb2-a1b2-df093443f549" />
<img width="1011" height="208" alt="Screenshot 2026-09-03 004756" src="https://github.com/user-attachments/assets/e317d680-b483-49d0-995d-8ea60f8ce861" />

**Output:**

<img width="1227" height="543" alt="Screenshot 2026-09-03 004811" src="https://github.com/user-attachments/assets/e9537349-e7a6-4efc-8980-b57ce4483189" />

**Question 8**
---
-- Paste Question 8 here
<img width="1416" height="652" alt="Screenshot 2026-09-03 004857" src="https://github.com/user-attachments/assets/d18b1ffb-5c08-4d6e-92e8-48db658296bd" />
<img width="787" height="247" alt="Screenshot 2026-09-03 004907" src="https://github.com/user-attachments/assets/be8b4f51-2fca-4394-a132-92edf6e1eae9" />


**Output:**
<img width="1212" height="820" alt="Screenshot 2026-09-03 004925" src="https://github.com/user-attachments/assets/62468cd5-0f68-4984-86b1-fc23e6d61aa2" />

**Question 9**
---
-- Paste Question 9 here


<img width="1418" height="823" alt="Screenshot 2026-09-03 005011" src="https://github.com/user-attachments/assets/fca79c38-b028-4e8b-82e9-ccfd4488fe70" />

**Output:**

<img width="1222" height="648" alt="Screenshot 2026-09-03 005033" src="https://github.com/user-attachments/assets/e2a0c414-6be4-4890-92db-296d895ac64a" />

**Question 10**
---
-- Paste Question 10 here
<img width="1420" height="757" alt="Screenshot 2026-09-03 005114" src="https://github.com/user-attachments/assets/4be3b23e-5004-4225-8ab2-cbcf55a6b5f5" />
<img width="1072" height="737" alt="Screenshot 2026-09-03 005128" src="https://github.com/user-attachments/assets/4a7ae775-87bf-4d9b-994d-83264c629387" />


**Output:**
<img width="1222" height="810" alt="Screenshot 2026-09-03 005147" src="https://github.com/user-attachments/assets/bdfb0ee7-2af9-4aed-9fdf-000fba49d0c5" />

**GRADE**
<img width="1308" height="77" alt="Screenshot 2026-09-03 005228" src="https://github.com/user-attachments/assets/9a3e3a34-ce46-4410-82f6-d94074a4e9c0" />

## RESULT
Thus, the SQL queries to implement different types of joins have been executed successfully.

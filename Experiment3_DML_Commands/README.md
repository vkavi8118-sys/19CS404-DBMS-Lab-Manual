# Experiment 3: DML Commands

## AIM
To study and implement DML (Data Manipulation Language) commands.

## THEORY

### 1. INSERT INTO
Used to add records into a relation.
These are three type of INSERT INTO queries which are as
A)Inserting a single record
**Syntax (Single Row):**
```sql
INSERT INTO table_name (field_1, field_2, ...) VALUES (value_1, value_2, ...);
```
**Syntax (Multiple Rows):**
```sql
INSERT INTO table_name (field_1, field_2, ...) VALUES
(value_1, value_2, ...),
(value_3, value_4, ...);
```
**Syntax (Insert from another table):**
```sql
INSERT INTO table_name SELECT * FROM other_table WHERE condition;
```
### 2. UPDATE
Used to modify records in a relation.
Syntax:
```sql
UPDATE table_name SET column1 = value1, column2 = value2 WHERE condition;
```
### 3. DELETE
Used to delete records from a relation.
**Syntax (All rows):**
```sql
DELETE FROM table_name;
```
**Syntax (Specific condition):**
```sql
DELETE FROM table_name WHERE condition;
```
### 4. SELECT
Used to retrieve records from a table.
**Syntax:**
```sql
SELECT column1, column2 FROM table_name WHERE condition;
```
**Question 1**
--
-- Paste Question 1 here
<img width="1175" height="588" alt="Screenshot 2026-08-24 105658" src="https://github.com/user-attachments/assets/f44890a5-0d3d-4994-b9d2-150788a2a605" />



**Output:**
<img width="1155" height="680" alt="Screenshot 2026-08-24 105709" src="https://github.com/user-attachments/assets/82913c5b-8f4c-48e4-8450-f245e3859e53" />

**Question 2**
---
-- Paste Question 2 here
<img width="1176" height="460" alt="Screenshot 2026-08-24 105753" src="https://github.com/user-attachments/assets/c13cb215-f700-402f-b625-6d8a5a6d7a4a" />

**Output:**
<img width="1150" height="339" alt="Screenshot 2026-08-24 105807" src="https://github.com/user-attachments/assets/f8c947c8-8327-4467-a215-d834060c75a9" />

**Question 3**
---
-- Paste Question 3 here
<img width="1126" height="820" alt="Screenshot 2026-08-24 105821" src="https://github.com/user-attachments/assets/0e97ec53-1818-46f7-a7ea-8c2b6f5ed87e" />

<img width="488" height="138" alt="Screenshot 2026-08-24 105833" src="https://github.com/user-attachments/assets/82c7428e-e56d-4063-ac31-c5c8d8f76e6c" />

**Output:**
<img width="1160" height="601" alt="Screenshot 2026-08-24 105845" src="https://github.com/user-attachments/assets/563f1fd7-5b16-4c7e-ba01-0773c1a96a18" />

**Question 4**
---
-- Paste Question 4 here
<img width="1162" height="824" alt="Screenshot 2026-08-24 105903" src="https://github.com/user-attachments/assets/f4bccfe4-d937-4a5c-84f0-e51b46e40238" />


**Output:**
<img width="1155" height="532" alt="Screenshot 2026-08-24 105920" src="https://github.com/user-attachments/assets/4cb33c05-4cca-42e9-9585-6a39f7b35f92" />

**Question 5**
---
-- Paste Question 5 here

<img width="1163" height="771" alt="Screenshot 2026-08-24 105937" src="https://github.com/user-attachments/assets/61984271-41b8-4e7f-94c2-ea008897fcfd" />


**Output:**

<img width="1145" height="516" alt="Screenshot 2026-08-24 105950" src="https://github.com/user-attachments/assets/5f32c31f-846c-450c-ac2f-ee487cb1e46d" />

**Question 6**
---
-- Paste Question 6 here

<img width="1148" height="810" alt="Screenshot 2026-08-24 110009" src="https://github.com/user-attachments/assets/33ffd8c5-90aa-473b-86cf-a16d359755da" />
<img width="473" height="88" alt="Screenshot 2026-08-24 110021" src="https://github.com/user-attachments/assets/d8616690-917a-440b-9a58-26389396071b" />


**Output:**
<img width="1121" height="719" alt="Screenshot 2026-08-24 110030" src="https://github.com/user-attachments/assets/103367e7-c7c9-4c87-8484-eda4136a90f1" />

**Question 7**
---
-- Paste Question 7 here
<img width="1159" height="820" alt="Screenshot 2026-08-24 110854" src="https://github.com/user-attachments/assets/8035b2e6-2dcf-4371-8ee7-94c07689d1c6" />


**Output:**
<img width="1122" height="418" alt="Screenshot 2026-08-24 110902" src="https://github.com/user-attachments/assets/db3bf687-a1fd-4d1c-9d5f-0202c7c401a0" />

**Question 8**
---
-- Paste Question 8 here
<img width="1169" height="793" alt="Screenshot 2026-08-24 110048" src="https://github.com/user-attachments/assets/09c005bb-9698-416f-a92a-66e809ae4371" />
<img width="372" height="61" alt="Screenshot 2026-08-24 110100" src="https://github.com/user-attachments/assets/357e630c-b60d-4423-b81a-5273dd240673" />


**Output:**

<img width="1149" height="729" alt="Screenshot 2026-08-24 110110" src="https://github.com/user-attachments/assets/8a3d00d2-9cbe-4c2a-adb1-f987fa06e20c" />


**Question 9**
---
-- Paste Question 9 here

<img width="1165" height="808" alt="Screenshot 2026-08-24 110123" src="https://github.com/user-attachments/assets/8e6b8dcb-0420-4c67-9ad2-63ebb8225038" />


**Output:**

<img width="1154" height="828" alt="Screenshot 2026-08-24 110138" src="https://github.com/user-attachments/assets/725af04d-1220-498f-a293-1aa4bf5e9047" />

**Question 10**
---
-- Paste Question 10 here
<img width="974" height="700" alt="Screenshot 2026-08-24 110151" src="https://github.com/user-attachments/assets/be5f78e6-f345-4d14-9abd-073283b9c039" />


**Output:**
<img width="1124" height="810" alt="Screenshot 2026-08-24 110217" src="https://github.com/user-attachments/assets/995fe9b7-beb3-48a0-a540-88197da287de" />

**GRADE:**
<img width="854" height="137" alt="Screenshot 2026-08-24 111021" src="https://github.com/user-attachments/assets/4441b4b3-bf2c-47ce-a9c1-743cec0e2b38" />

## RESULT
Thus, the SQL queries to implement DML commands have been executed successfully.

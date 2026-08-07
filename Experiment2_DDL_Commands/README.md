# Experiment 2: DDL Commands

## AIM
To study and implement DDL commands and different types of constraints.

## THEORY

### 1. CREATE
Used to create a new relation (table).

**Syntax:**
```sql
CREATE TABLE (
  field_1 data_type(size),
  field_2 data_type(size),
  ...
);
```
### 2. ALTER
Used to add, modify, drop, or rename fields in an existing relation.
(a) ADD
```sql
ALTER TABLE std ADD (Address CHAR(10));
```
(b) MODIFY
```sql
ALTER TABLE relation_name MODIFY (field_1 new_data_type(size));
```
(c) DROP
```sql
ALTER TABLE relation_name DROP COLUMN field_name;
```
(d) RENAME
```sql
ALTER TABLE relation_name RENAME COLUMN old_field_name TO new_field_name;
```
### 3. DROP TABLE
Used to permanently delete the structure and data of a table.
```sql
DROP TABLE relation_name;
```
### 4. RENAME
Used to rename an existing database object.
```sql
RENAME TABLE old_relation_name TO new_relation_name;
```
### CONSTRAINTS
Constraints are used to specify rules for the data in a table. If there is any violation between the constraint and the data action, the action is aborted by the constraint. It can be specified when the table is created (using CREATE TABLE) or after it is created (using ALTER TABLE).
### 1. NOT NULL
When a column is defined as NOT NULL, it becomes mandatory to enter a value in that column.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) NOT NULL
);
```
### 2. UNIQUE
Ensures that values in a column are unique.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) UNIQUE
);
```
### 3. CHECK
Specifies a condition that each row must satisfy.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) CHECK (logical_expression)
);
```
### 4. PRIMARY KEY
Used to uniquely identify each record in a table.
Properties:
Must contain unique values.
Cannot be null.
Should contain minimal fields.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) PRIMARY KEY
);
```
### 5. FOREIGN KEY
Used to reference the primary key of another table.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size),
  FOREIGN KEY (column_name) REFERENCES other_table(column)
);
```
### 6. DEFAULT
Used to insert a default value into a column if no value is specified.

Syntax:
```sql
CREATE TABLE Table_Name (
  col_name1 data_type,
  col_name2 data_type,
  col_name3 data_type DEFAULT 'default_value'
);
```

**Question 1**
--
-- Paste Question 1 here
<img width="1382" height="580" alt="Screenshot 2026-08-08 000920" src="https://github.com/user-attachments/assets/c20de183-49ca-4819-bb50-2c0a38f47eef" />


**Output:**

<img width="1212" height="377" alt="Screenshot 2026-08-08 000938" src="https://github.com/user-attachments/assets/d37cee0f-0f4f-45db-ae91-2031702709de" />


**Question 2**
---
-- Paste Question 2 here
**<img width="1387" height="782" alt="Screenshot 2026-08-08 001000" src="https://github.com/user-attachments/assets/35cdcf56-b44e-43a8-ae16-7b95e4290502" />
**

**Output:**

<img width="1237" height="458" alt="Screenshot 2026-08-08 001025" src="https://github.com/user-attachments/assets/954f28c6-8344-4665-84b0-f155b04b81d5" />

**Question 3**
---
-- Paste Question 3 here

**<img width="1385" height="737" alt="Screenshot 2026-08-08 001043" src="https://github.com/user-attachments/assets/bbce62ce-81fb-4b73-8353-65851c14b61c" />
**
**Output:**
<img width="1181" height="371" alt="Screenshot 2026-08-08 001056" src="https://github.com/user-attachments/assets/afcfe925-59ac-4565-9550-1483db9d6501" />



**Question 4**
---
-- Paste Question 4 here
<img width="1402" height="747" alt="Screenshot 2026-08-08 001121" src="https://github.com/user-attachments/assets/d1b7e60a-8bc2-49ad-8321-d2e78f034b1c" />


**Output:**

<img width="1207" height="410" alt="Screenshot 2026-08-08 001227" src="https://github.com/user-attachments/assets/211fdc98-ede0-40f8-afa0-2f3d15ca61ce" />

**Question 5**
---
-- Paste Question 5 here
**<img width="1393" height="678" alt="Screenshot 2026-08-08 001244" src="https://github.com/user-attachments/assets/6b4b2305-1e5a-4a1d-a32f-d19ba0b55769" />
**

**Output:**
 <img width="1232" height="450" alt="Screenshot 2026-08-08 001313" src="https://github.com/user-attachments/assets/4254c631-0b45-4076-9f61-6a40bf4cca3f" />

**Question 6**
---
-- Paste Question 6 here

<img width="1383" height="792" alt="Screenshot 2026-08-08 001333" src="https://github.com/user-attachments/assets/5b1a677e-2f38-4f2a-a2d5-5b26de7efc9e" />


**Output:**

**<img width="1170" height="476" alt="Screenshot 2026-08-08 001344" src="https://github.com/user-attachments/assets/cdd47ae9-d87b-4da0-9274-4cf4c9bce010" />
**
**Question 7**
---
-- Paste Question 7 here

**<img width="1396" height="708" alt="Screenshot 2026-08-08 001359" src="https://github.com/user-attachments/assets/4407e28c-bd00-4da0-aea1-cb62dd81d765" />
**

**Output:**

<img width="1193" height="427" alt="Screenshot 2026-08-08 001419" src="https://github.com/user-attachments/assets/2e8b8fa4-66d5-49db-ac41-f4e5987ee123" />

**Question 8**
---
-- Paste Question 8 here
<img width="1388" height="662" alt="Screenshot 2026-08-08 001447" src="https://github.com/user-attachments/assets/59f40133-406a-4252-ba12-87c07a040bb6" />



**Output:**

<img width="1202" height="512" alt="Screenshot 2026-08-08 001525" src="https://github.com/user-attachments/assets/f6ff0336-f9a6-4660-ad40-4ac2202a4dd1" />

**Question 9**
---
-- Paste Question 9 here

<img width="1366" height="821" alt="Screenshot 2026-08-08 001548" src="https://github.com/user-attachments/assets/bf0cac7d-940a-4226-81e0-eaf7eda4bd8a" />


**Output:**
 <img width="1186" height="537" alt="Screenshot 2026-08-08 001602" src="https://github.com/user-attachments/assets/b3d1f8da-2c11-449b-90de-f755a8185b44" />

**Question 10**
---
-- Paste Question 10 here
<img width="1386" height="802" alt="Screenshot 2026-08-08 001705" src="https://github.com/user-attachments/assets/94abe02f-293c-4ada-af4d-4d680b20848a" />



**Output:**
<img width="1202" height="542" alt="Screenshot 2026-08-08 001717" src="https://github.com/user-attachments/assets/52be5efc-6a7a-4a77-8dff-b16602a9d50c" />

<img width="1325" height="117" alt="Screenshot 2026-08-08 002859" src="https://github.com/user-attachments/assets/b0bc8ba7-9053-44f2-b97a-fb474d2e5955" />


## RESULT
Thus, the SQL queries to implement different types of constraints and DDL commands have been executed successfully.

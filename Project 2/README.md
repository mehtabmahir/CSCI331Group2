
# ✅ Final Task Distribution – CSCI331 Project 2  
**Submission format: `Group2_CSCI331_Project2.vhdx`**  


## 🟦 **Pair 1 – Schema, Sequences, and Dimension Loading**

### 👤 **Person A: Mehtab Mahir**
1. Create database `G10_2`  
2. Create schemas:
   - `CH01-01-Dimension`, `CH01-01-Fact`, `DbSecurity`
3. Create tables:
   - `DimCustomer`
   - `DimProduct`
   - `DimTerritory`
   - `DimOccupation`
   - `Fact.Data`
4. Add audit columns to all tables  
5. Create `DbSecurity.UserAuthorization`  
6. Create tables:
   - `DimProductCategory`
   - `DimProductSubcategory`
7. Create sequence objects for all dimension and fact tables  
8. Create stored procedures:
   - `LoadDimCustomer`
   - `LoadDimProduct`
   - `LoadDimTerritory`  
9. Backup database as `.bak` from WSL

---

### 👤 **Person B**
1. Create `Process.WorkflowSteps` table  
2. Create `Process.usp_TrackWorkflow`  
3. Create stored procedures:
   - `LoadDimOccupation`
   - `LoadDimProductCategory`
   - `LoadDimProductSubcategory`  
4. Add tracking logic using `usp_TrackWorkflow`

---

## 🟩 **Pair 2 – Fact Table and Data Integration**

### Person A
1. Create stored procedure `LoadFactData`  
2. Join all dimension tables to load surrogate keys  
3. Insert into `Fact.Data` using sequences  
4. Include workflow tracking logic

### Person B
5. Test data integrity and FK joins  
6. Validate row counts before and after  
7. Help with `.bak` backup for this phase

---

## 🟥 **Pair 3 – Orchestration and Workflow Execution**

### Person A
1. Create stored procedure `LoadStarSchemaData`  
2. Add logic to:
   - Drop foreign keys
   - Truncate all star schema tables
   - Call all `LoadDim*` and `LoadFactData` procedures  
3. Recreate foreign keys at the end

### Person B
4. Create stored procedure `usp_ShowWorkflowSteps`  
5. Validate row count and log entries  
6. Test foreign key integrity and schema relationships

---

## 🟨 **Pair 4 – Documentation and Submission**

### Person A
1. Create to-do list, meeting notes, and Gantt chart  
2. Create PowerPoint slides:
   - Team roles and assignments
   - SQL lifecycle and stored procedure execution  
3. Record MP4 **Lifecycle Walkthrough Video** (12+ min):
   - Shows schema creation
   - Stored procedures
   - Logging
   - Output verification in SSMS

### Person B
4. Generate Redgate SQLDoc PDF from final database  
5. Organize final project structure:
   ```
   /SQL/
   /Docs/
   /Media/
   /Backup/
   ```
6. Package everything into a `.vhdx` named:
   ```
   G10_2_Spring2025_0915.vhdx
   ```

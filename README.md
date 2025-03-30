# PROJECT DOCUMENTATION

### REQUIREMENTS
#### INSTRUCTIONS
Develop a Spring Boot Payroll Application with the following capabilities:
- Register Users with either of the roles APPROVER, INITIATOR
- Login Page for the registered users.
- Capture individual entry of salary record for employee and save to a database.
- Bulk upload of these salaries in a csv or Excel sheet that also saves to a database.
- Show a list of all salaries pending approval by the APPROVER.
- The APPROVER should be able to change the state of a payment from PENDING to APPROVED or from PENDING to REJECTED.
- Search salary payments by their status, i.e. PENDING, APPROVED or REJECTED salaries, search salary entry by <br>destination account number.
- Have a report page/tab showing total salaries entered for the day with total batch value. Show Reports of payments <br>that are in PENDING STATUS for approval by the APPROVER.
- Include unit tests for core components used and share the code coverage.

### ENTITIES
After analysing the [requirements,](#requirements) the following entities were derived:
- User
- SalaryRecord
- Employee
- SalaryBatch
- SalaryPayment
- Report

### USE CASES
After analysing the [requirements,](#requirements) the following use-cases were derived:
- RegisterUser
- DeRegisterUser
- CaptureSalaryRecord
- UpdateSalaryRecord
- RemoveSalaryRecord
- UploadSalaryBatch
- UpdateSalaryBatch
- RemoveSalaryBatch
- SearchSalaryRecords
- SearchSalaryPayments
- FetchReports

### ARCHITECTURE
The architecture spawned in the process of analysing [requirements,](#requirements) deriving [entities,](#entities) and developing the [use cases](#use_cases).
<br>




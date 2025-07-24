# Hospital_Management-SQL_Final_Project-
This is a mini Hospital Management System project using  "SQLite" and "DBeaver". 
It helps to manage "patients, doctors, appointments (visits), billing", and "reporting" in a simple and structured way.


##  Features in it

-  Patient & Doctor Records
-  Visit/Appointment Tracking
-  Billing and Payment Management
-  Auto Discharge on Full Payment (Trigger)
-  Reports for Visits and Billing
-  View for Billing Summary

---

##  Tools Used

- "SQLite" – lightweight database engine  
- "DBeaver" – open-source database client for writing and running SQL  
- SQL queries and logic are written using standard "SQLite syntax"

---

##  Database Schema created

- `Patients(PatientID, Name, Age, Gender, Contact, Status)`
- `Doctors(DoctorID, Name, Specialty, Contact)`
- `Visits(VisitID, PatientID, DoctorID, VisitDate, Diagnosis, Treatment)`
- `Bills(BillID, VisitID, Amount, Paid, Due, BillingDate)`




## Functionalities

- Automatically update patient status to `'Discharged'` when full bill is paid
- Track unpaid bills and visit history
- Generate visit and billing reports


  

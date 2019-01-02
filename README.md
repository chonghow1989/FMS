# Fleet Management System (FMS)

  Fleet Management is a function which allows companies which rely on transportation in business to remove or minimize the risks associated with vehicle investment, improving efficiency, productivity, transparency and reducing their overall transportation and staff costs.

  Fleet management is the management of:
  
    - Commercial motor vehicles such as cars, vans, trucks, specialist vehicles, and trailers
    
    - In-house fleet-management department Management
    
    - Corporate Customer Management
    
    - GPS Vehicle tracking system
    
    - Billing 

# Modules
    •	Job & Operation
    •	Customer
    •	Billing
    •	Finance
    
    

# Requirements
    - Internet Connection
    - Modern Web Browser(Google Chrome, Firefox)

# Get Started
    URL : http://csa.yhi.com.sg/JOB/list.php
    Login with account provided.

# Documentation (User Manual)
## Index
### 1. OPERATION
  - `a. Job List`
  - `b. Create New Job / Edit Job`
  - `c. Maintenance`
  - `d. Map`
  - `e. Fleet Record`
  - `f. Technician Route`
  - `g. Daily Routine List`
  
  
### 2. CUSTOMER MANAGEMENT
  - `a. Customer`
  - `b. Vehicle`
  - `c. Apps User`
  - `d. Admin`
### 3. CSD SECTION
### 4. HR SECTION
### 5. SALES SECTION
### 6. FINANCE SECTION

# 1  OPERATION
## a. Job List (Realtime update)
### To view all the Jobs record.
### There are 14 columns in the job list to provide a glance view of every jobs :
- `ID`  FMS system unique Job ID  
* `Action`  Several action can be perform to extend the funtionality of job:
  - `Details`  To view Job detail, Job photos captured, vehicle position and Vehicle Details. 
  - `Edit`  Edit Job Information.
  - `Delete`  Delete Job, only user authorised can view this action.
  - `Quotation`  To create quotation for this job.
  - `Reassign`  Reassign job to another technician. 
  - `Track Technician`  Track technician current location and duration to reach job's location 
  - `Whatsapp`  To send job detail to customer via whatsapp
  - `Follow Up` 
  - `Claim` 
  - `Transport Charge FOC` 
  - `Rotation & balancing FOC` 
- `Customer`  Customer basic details such as Company Name, Company Code, Vehicle No. and Remark
- `Type`  Indoor Job or Outdoor Job
- `SD No.`  Service Docker Number
- `Notif No.`  Notification Number (From SAP)
- `Address`  Job Location
- `Sent On`  Time Job Created
- `Technician Receive on`  Time Technician received the Job on Mobile Apps
- `Start On`  Time Technician Start the job
- `Complete On`  Time Technician finish the job
- `Schedule`  Time future pre schedule job 
- `Technician Indoor`  Indoor Technician responsible for this job
- `Assigned To`  Outdoor Technician responsible for this job

### Filter Job on top based on several criteria: 
- `SD No.`
- `Notification No.`
- `Completed`
- `Assigned`
- `Claim`
- `FollowUp`

### Job list row color definition:
- `Red`  Technicain cannot receive job
- `Green`  Technician receive job
- `Light Green`  Technician start job
- `Orange`  New Job Incoming
- `White`  Completed Job

## b. Create New Job / Edit Job

There is 3 ways to create a new job:
###  1. Web 
###  2. Apps 
###  3. Customer Admin Portal 

Operation team will edit the job and furnish all the informations before posting to SAP Notification:

## c. Maintenance (In-house Operation Team Management)
###  1. Driver 
* `In-House Technician Maintenance`  For Login into Mobile Apps & Job Assigned   
- `Technician List`  
- `Registration Form to create new Technician`  


###  2. Vehicle 
* `In-House Vehicle Maintenance`  For use by Technician and in-house tracking.
- `Vehicle List`  
- `Vehicle Form to create new Vehicle`  
###  3. Milleage & Servicing
* `Milleage & Servicing List` To keep track every in-house vehicle Servicing Due Date	and Mileage

## d. Map (Realtime Update)
- `Glance view for all technician movement`

## e. Fleet Record
###  1. Fleet Report  
Summary view for no. of jobs completed by each technician.


###  2. Customer Report 
Summary view for no. of jobs for specific customer.


## f. Technician Route
Routes travelled by specific technician. (Day view)

## g. Daily Routine List
To track and monitor timing of tasks carry out by the technician.


# 2  CUSTOMER MANAGEMENT
## a. Customer
### - Customer List
Division 06  Customer List (From SAP)
There are 11 columns in the customer list to provide a glance view of every customers :

* `Action`  Several action can be perform to view more further informations of customer:
  - `Aging`  To view owing up to 150 days and pending invoices.
  
  - `Monthly Sales Result`  Sales Summary Statistic & Chart       
  
  - `Purchase History`  Complete Job Detail From Job Order Date, Items, and Invoice. 
  
  - `Price Maintenance`  YT1P Division 06 Pricing Maintenance from SAP.(Daily Update)
  
  - `Price History`  Historical Price Summary for every items.
  
  - `Customer Stock`  Stock sold to customer that park at YHI premise.
  
- `SAP Code`  SAP Code for each Customer.  
- `Name`  Customer basic details such as Company Name, Company Code, Vehicle No. and Remark.
- `Salesman`  Salesperson responsible.
- `Address`  Customer registered address in SAP system.
- `Postal`  Customer registered postalcode in SAP system.
- `Email`  Customer registered email in SAP system.
- `Billing Type`  Collective, Comprehensive or Direct Billing.
- `Suspend`  Suspend status. Block from create a new job when customer is suspended.
- `Quotation Required`  Link to Quotation. Compulsory to create quotation before billing.
- `Remark`  Free text.
### - Advanti Customer List
- `SAP` 
- `Tecsys` 
- `From Landing Page` 
### - Suspended List
- Customer banned from New Job


## b. Vehicle
### - Vehicle List
### - Create new Vehicle
### - Vehicle Activities

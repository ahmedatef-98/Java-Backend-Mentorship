# Vacation Tracking System Analysis & Design

## Requirements

### Vision

VTS system to empower employees to manage their time off (vacation, sick, time permissions, ...etc) time without need to master the company policy and reduce the prevent the repetitive work on the HR team and enable them to focus more on developing policies

### Function

 - Employees must have visibility on their available vacation balances 
 - System validates the time off requests based on employee balances & company policy 
 - Enable manager approvals for their employees’ requests 
 - Email notification for employee and manager with the requests and their updates 
 - Employee can access the history of the vacation requests for previous year
 - Employee can apply for vacation for the next 18 months 
 - Allow HR clerk to override/edit requests or balances manually within certain limits
 - The system must be a web based
 - The system must depend on the existing hardware middleware
 - Using single sign in authentication from the company portal 
 - Access to the system from the company portal
 - Allow managers to award personal leave time based on provided company policy
 - Integrated with HR legacy systems to retrieve employee information & changes 
 - Manager has visibility to his/her team’s leave balances, plans, requests 
 - The sick leave to allow employee to upload supporting document & to be approved by company doctor as well if exceeded certain number of days

### Non-Function

- Easy to use, intuitive, and intelligent
- Clear screen distribution items that show employee available/consumed/planned balances

### Constraints (Validations)

- Once leave request is approve the employee nor manager can cancel it themselves
- Employee can take +4 working days off continuously once a year
- The sick leave manager approval limit is 2 days per month
- Doctor approves sick leaves exceeding 2 days per month
- There must be al least one of the team members working (all the team cannot take leave at once)

### Problem Definition (Domain)

A lot of informal communication between manager & employees to handle vacation time in addition to multiple interaction with the HR team to ensure that the employee is following the company policies these issues rise with the increasing of employee numbers and consumes many of the company human resources to manage

### List of actors

- Employee
	- Apply for leave requests
	- Review his/her available balances
	- Receive notification about their requests’ status
- Manager
	- Same Employee’s role
	- Approve his/her team leave requests
	- Award employee a leave personal leave time
	- Some high-level managers take the leave without requests as they need no approval
- HR Clerk
	- Manage leave categories & update them
	- Override leave records when needed
	- Update employee data when needed a manual change
	- Ensure employee data is up to date across all HR systems
- System Admin
	- System data backups
	- System Maintenance
## Use Cases Diagrams
### Manage Time
#### Flow Diagram
<img width="1021" height="1562" alt="VTS Manage Time drawio" src="https://github.com/user-attachments/assets/f281bb3b-6972-437e-8ecb-e28ad865eeaa" />
#### 


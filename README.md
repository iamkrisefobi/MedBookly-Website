___
## Background and Strategic Fit
*The objective of this project* is to streamline the process of booking a medical appointment by the users and managing the volume of appointments by the hospital Admins. Patients can easily book an appointment, be notified about it, provide relevant information to the doctor beforehand, and also reschedule or cancel the appointment and enable the clinic to streamline its appointments and daily tasks. It also enables the hospital Admin to reduce the mundane tasks of scheduling appointments for patients manually. The application is developed with two dashboards, one for the patient to create their profile and another for the hospital admin to have an overview of the appointments booked and manage the process seamlessly. 

---
## Purpose
MedBookly will be an application that can assist people in booking medical appointments, get notification about it, and management of hospitals to streamline their mundane tasks of confirming and rebooking all scheduled appointment.
#### Target users 
 

 - Adults: (18-above) the tech-savvy, who can navigate through the application and able to book appointments. 
 - Hospital Admin: covers the hospital admins who want to monitor and streamline the booking and rebooking of all appointments. 
---
## Success Metrics 

|Goal| Metrics |
|--|--|
| Increase adoption rate by 50% from launch date| 1. Number of Signups 2. Number of appointments booked 3. Number of Patients attended to. |
|Increase Customer retention rate by 20% every quarter| 1. Active Users - Daily and Monthly. 2. User reviews 3. The rate of booking completion 4. Repeat transactions and how often users use the application.|
---
## System Specifications 

 - Default location: Nigeria. 
 - Currency: primary currency is Naira. 
 - Geolocation: automatically changes settings based on the user’s location. 
  - Localized format: ensures local date and time format, phone number, and account number formats. 
   - Push notification and alerts: embed call-to-action and non-intrusive notification using message inbox, pop-up, dynamic banner, carousel. 
   - Data privacy: compliance with relevant regulations and data privacy. 
   - Audit trail: recording and retrieval of all user activities that can alter/create/delete system information or affect system behavior. 
  -  Insight and intelligence: the system must be designed to provide business insights and aid data-driven decision-making.
---
 ## Structure, Availability, and Recovery 

● Disaster Recovery: The solution should be replicated to ensure business continuity in the event of an unanticipated disaster or event. 
● Data Backup: Data must be collected and backed up for both transactional and non\-transactional data that occurs in the booking application. 
● Database Structure: The tables in the admin database should not have null tables; every required details must be supplied at the time of creation of profile. 
● Database Update: The database build should be developed using the latest version and must be set to auto-update with the latest patches available at intervals. 


---
## Requirements (Users) 
#### Feature 1: Sign Up Page. 

**Description:** Users can sign up for the app on the signup page. 

**Acceptance Criteria:**

 1. Users should be able to sign up
 2. There should be a sign-up page 
 3. Sign up page to collect information like name, email, password, phone number, and age 
4. Users should be asked to verify their email address once they register. 

#### Feature 2: Sign-in Page 
**Description:** The sign-in page allows the user to sign in to their MedBookly account. 
**Acceptance Criteria:** 
 1. User should be able to sign in with their email/phone number and password 
 2. There should be a sign-in page. 

#### Feature 3: Forgot Password 

**Description:**  Users should be able to retrieve their password in the event that they forget it. 
**Acceptance Criteria:**
	1. Users should be able to reset their password on the sign-in page with either an OTP or one-time email link. 

#### Feature 4: Profile Page 
**Description:** Users should have access to a profile page where they can add additional personal details about themselves. 

 **Acceptance Criteria**
  1. Users should have a profile page 
  2. Users should have permission to edit their profile whenever they wish.

#### Feature 5: Dashboard 

**Description:** the dashboard shows all related information to the primary activities of a user on the app, which is not limited to booking of appointment, available hospital, or transaction history. 

**Acceptance Criteria:**
 1. Every user should have a dashboard 
 2. The dashboard should contain information about booking of appointment, transaction history, available hospital in your location, and time scheduled for user appointment. 
 3. Map feature that points to the location of the hospital.

#### Feature 6: Settings Page 

**Description:** The user can adjust several things from the settings page such as changing their location, changing their color scheme, adjusting security and privacy options. 
**Acceptance Criteria**
1. Users can reset their password 
2. Users can reset their location 
3. Users can change their color scheme 
4. Users can adjust privacy options. 
5. Users can determine how often they want to receive notification. 

---
## Requirements (Hospital Admin) 

#### Feature 1: Sign Up Page. 

**Description:** The admin can sign up for the app on the signup page. 

**Acceptance Criteria** 
1. Users should be able to sign up 
2. There should be a sign-up page 
3. Sign up page to collect information like hospital name, hospital email, password, hospital phone number, 
4. Users should be asked to verify their email address once they register. 

#### Feature 2: Sign-in Page 
**Description:** The sign-in page allows the admin to sign in to their MedBookly account. 

**Acceptance Criteria:** 
1. User should be able to sign in with their email/phone number and password 
2. There should be a sign-in page. 

#### Feature 3: Forgot Password 

**Description:** The admin should be able to retrieve their password in the event that they forget it. 

** Acceptance Criteria** 
1. Users should be able to reset their password on the sign-in page with either an OTP or one-time email link.   

#### Feature 4: Profile Page 

**Description:** Users should have access to a profile page where they can add additional personal details about themselves. 

**Acceptance Criteria** 
1. Users should have a profile page 
2. Users should have permission to edit their profile whenever they wish. 
3. Users profile page should contain the Hospital name, email details, hospital phone number. 

#### Feature 5: Dashboard 

**Description:** the dashboard shows all related information to the primary activities of the app, which is not limited to booking of appointments, available hospital, or transaction history. 
**Acceptance Criteria:** 
1. Every admin should have a dashboard 
2. The dashboard should contain information about booking of appointment, transaction history, available specialists, time scheduled for a patient appointment, number of people already booked for appointment (1-50 in a day). 
3. The dashboard should contain a section for vetting and verification of doctors who will be working under the hospital. 
4. Each hospital will include a section to update their consultation fees. 
5. Profile creation for doctors on the app 

#### Feature 6: Settings Page 

**Description:** The admin can adjust several things from the settings page such as changing their color scheme, adjusting security and privacy options, and adjusting the number of people to be attended to on a particular day. 
**Acceptance Criteria** 
1. Users can reset their password 
2. Users can adjust the total number of patients to be attended to on a particular day.
3. Users can change their color scheme

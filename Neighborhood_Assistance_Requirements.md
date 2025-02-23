# Neighborhood Assistance Board - Requirements

## **Table of Contents**
1. [Functional Requirements](#functional-requirements)
   - [User Requirements](#user-requirements)
     - [Registration/Login](#registrationlogin)
     - [Guest User](#guest-user)
     - [Registered User](#registered-user)
     - [Administrator](#administrator)
     - [User Interactions](#user-interactions)
     - [Personal Page](#personal-page)
     - [Leaderboard](#leaderboard)
     - [Program](#program)
     - [Feed](#feed)
   - [System Requirements](#system-requirements)
     - [Notification](#notification)
     - [Search](#search)
     - [Labels](#labels)
     - [Verification](#verification)
2. [Non-Functional Requirements](#non-functional-requirements)
   - [Performance](#performance)
   - [Accessibility/Availability](#accessibilityavailability)
   - [Privacy](#privacy)
   - [UI/UX (Usability)](#uiux-usability)
3. [Glossary](#glossary)

---

<a name="functional-requirements" />
## **1. Functional Requirements**

<a name="user-requirements"></a>
### **1.1 User Requirements**

<a name="registrationlogin"></a>
#### **1.1.1 Registration/Login**
- 1.1.1.1 Users shall be able to **register** using their email address or social media accounts.
- 1.1.1.2 Registered users shall be able to **log in** using their credentials.
- 1.1.1.3 The system shall provide **password recovery** options for users.

<a name="guest-user"></a>
#### **1.1.2 Guest User**
- 1.1.2.1 Guest users shall be able to **view public assistance requests** but cannot interact with them.
- 1.1.2.2 To **post a request** or **volunteer**, users must **register and log in**.

<a name="registered-user"></a>
#### **1.1.3 Registered User**
- 1.1.3.1 Registered users shall be able to **post new assistance requests**.
- 1.1.3.2 Registered users shall be able to **volunteer for available tasks**.
- 1.1.3.3 Users shall have access to a **dashboard** displaying their active and past activities.

<a name="administrator"></a>
#### **1.1.4 Administrator**
- 1.1.4.1 Administrators shall be able to **manage user accounts**, including suspension or deletion.
- 1.1.4.2 The system shall allow administrators to **monitor and moderate content** posted on the platform.

<a name="user-interactions"></a>
#### **1.1.5 User Interactions**
- 1.1.5.1 Users shall be able to **communicate** through a built-in messaging system.
- 1.1.5.2 The system shall allow users to **rate and review** each other after task completion.

<a name="personal-page"></a>
#### **1.1.6 Personal Page**
- 1.1.6.1 Each user shall have a **profile page** displaying their information and activity history.
- 1.1.6.2 Users shall be able to **edit their personal information** and **privacy settings**.

<a name="leaderboard"></a>
#### **1.1.7 Leaderboard**
- 1.1.7.1 The system shall feature a **leaderboard** showcasing top volunteers based on completed tasks and ratings.

<a name="program"></a>
#### **1.1.8 Program**
- 1.1.8.1 The platform shall support the creation of **assistance programs** (e.g., weekly grocery runs) that users can subscribe to.

<a name="feed"></a>
#### **1.1.9 Feed**
- 1.1.9.1 Users shall have a **personalized feed** displaying relevant assistance requests based on their location and past interactions.
- 1.1.9.2 Users shall be able to **filter** requests by categories (e.g., grocery shopping, tutoring, home repairs).

---

<a name="system-requirements"></a>
## **1.2 System Requirements**

<a name="notification"></a>
### **1.2.1 Notification**
- 1.2.1.1 The system shall send **real-time notifications** when a user’s request is accepted or updated.
- 1.2.1.2 Users shall have the ability to **customize notification settings** (e.g., email, push notifications).

<a name="search"></a>
### **1.2.2 Search**
- 1.2.2.1 The system shall provide a **search function** allowing users to find assistance requests based on keywords, location, and category.
- 1.2.2.2 The search function shall support **auto-suggestions** to improve usability.

<a name="labels"></a>
### **1.2.3 Labels**
- 1.2.3.1 Users shall be able to add **tags/labels** to their assistance requests to improve discoverability.
- 1.2.3.2 The system shall allow filtering based on **popular labels** (e.g., "urgent," "long-term").

<a name="verification"></a>
### **1.2.4 Verification**
- 1.2.4.1 The system shall implement a **verification process** for volunteers to enhance reliability.
- 1.2.4.2 Verified users shall have a **special badge** displayed on their profiles.

---

<a name="non-functional-requirements"></a>
## **2. Non-Functional Requirements**

<a name="performance"></a>
### **2.1 Performance**
- 2.1.1 The system shall handle at least **10,000 concurrent users** without performance degradation.
- 2.1.2 Response time for searching and filtering tasks shall be **under 2 seconds**.

<a name="accessibilityavailability"></a>
### **2.2 Accessibility/Availability**
- 2.2.1 The system shall be **available 24/7** with a maximum downtime of **1% per month**.
- 2.2.2 The platform shall support **screen readers and accessibility standards** to accommodate disabled users.

<a name="privacy"></a>
### **2.3 Privacy**
- 2.3.1 User data shall be **encrypted** using industry-standard SSL/TLS protocols.
- 2.3.2 Users shall be able to **delete their accounts and personal data** at any time.

<a name="uiux-usability"></a>
### **2.4 UI/UX (Usability)**
- 2.4.1 The platform shall be **mobile-responsive**, supporting desktop and mobile browsers.
- 2.4.2 The user interface shall be **intuitive**, requiring no more than **3 clicks** to complete common tasks.

---

<a name="glossary"></a>
## **3. Glossary**
- **Assistance Request** – A post created by a user asking for help with a task.
- **Volunteer** – A registered user who offers help for posted requests.
- **Verified User** – A user who has completed identity verification.
- **Leaderboard** – A ranking system for top volunteers based on activity and reviews.
- **Task Category** – A classification system for different types of help requests (e.g., groceries, tutoring, home repairs).

---

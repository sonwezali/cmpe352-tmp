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

## **1. Functional Requirements**

### **1.1 User Requirements**

#### **1.1.1 Registration/Login**
1.1.1.1 Users shall be able to **register** using their email address or social media accounts.
1.1.1.2 Registered users shall be able to **log in** using their credentials.
1.1.1.3 The system shall provide **password recovery** options for users.

#### **1.1.2 Guest User**
- Guest users shall be able to **view public assistance requests** but cannot interact with them.
- To **post a request** or **volunteer**, users must **register and log in**.

#### **1.1.3 Registered User**
- Registered users shall be able to **post new assistance requests**.
- Registered users shall be able to **volunteer for available tasks**.
- Users shall have access to a **dashboard** displaying their active and past activities.

#### **1.1.4 Administrator**
- Administrators shall be able to **manage user accounts**, including suspension or deletion.
- The system shall allow administrators to **monitor and moderate content** posted on the platform.

#### **1.1.5 User Interactions**
- Users shall be able to **communicate** through a built-in messaging system.
- The system shall allow users to **rate and review** each other after task completion.

#### **1.1.6 Personal Page**
- Each user shall have a **profile page** displaying their information and activity history.
- Users shall be able to **edit their personal information** and **privacy settings**.

#### **1.1.7 Leaderboard**
- The system shall feature a **leaderboard** showcasing top volunteers based on completed tasks and ratings.

#### **1.1.8 Program**
- The platform shall support the creation of **assistance programs** (e.g., weekly grocery runs) that users can subscribe to.

#### **1.1.9 Feed**
- Users shall have a **personalized feed** displaying relevant assistance requests based on their location and past interactions.
- Users shall be able to **filter** requests by categories (e.g., grocery shopping, tutoring, home repairs).

---

## **1.2 System Requirements**

### **1.2.1 Notification**
- The system shall send **real-time notifications** when a user’s request is accepted or updated.
- Users shall have the ability to **customize notification settings** (e.g., email, push notifications).

### **1.2.2 Search**
- The system shall provide a **search function** allowing users to find assistance requests based on keywords, location, and category.
- The search function shall support **auto-suggestions** to improve usability.

### **1.2.3 Labels**
- Users shall be able to add **tags/labels** to their assistance requests to improve discoverability.
- The system shall allow filtering based on **popular labels** (e.g., "urgent," "long-term").

### **1.2.4 Verification**
- The system shall implement a **verification process** for volunteers to enhance reliability.
- Verified users shall have a **special badge** displayed on their profiles.

---

## **2. Non-Functional Requirements**

### **2.1 Performance**
- The system shall handle at least **10,000 concurrent users** without performance degradation.
- Response time for searching and filtering tasks shall be **under 2 seconds**.

### **2.2 Accessibility/Availability**
- The system shall be **available 24/7** with a maximum downtime of **1% per month**.
- The platform shall support **screen readers and accessibility standards** to accommodate disabled users.

### **2.3 Privacy**
- User data shall be **encrypted** using industry-standard SSL/TLS protocols.
- Users shall be able to **delete their accounts and personal data** at any time.

### **2.4 UI/UX (Usability)**
- The platform shall be **mobile-responsive**, supporting desktop and mobile browsers.
- The user interface shall be **intuitive**, requiring no more than **3 clicks** to complete common tasks.

---

## **3. Glossary**
- **Assistance Request** – A post created by a user asking for help with a task.
- **Volunteer** – A registered user who offers help for posted requests.
- **Verified User** – A user who has completed identity verification.
- **Leaderboard** – A ranking system for top volunteers based on activity and reviews.
- **Task Category** – A classification system for different types of help requests (e.g., groceries, tutoring, home repairs).

---

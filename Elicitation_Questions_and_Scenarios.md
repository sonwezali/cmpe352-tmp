# Elicitation Questions and Scenarios

## Elicitation Questions

### For Residents (Requesters)
1. What types of assistance do you typically need in your neighborhood?
2. How important is location-based filtering for you when requesting help?
3. Do you prefer direct messaging, email notifications, or phone calls for communication?
4. What kind of information would you like to see about a volunteer before accepting their help?
5. How should we handle cancellations or missed tasks?

### For Volunteers
6. What motivates you to volunteer for community assistance?
7. Would you like the ability to set preferences for the types of tasks you want to accept?
8. How would you prefer to receive notifications about new requests?
9. Should there be an option to temporarily pause receiving requests?
10. What security or verification steps would make you feel comfortable using this platform?

### For Admins/Moderators
11. What kind of moderation tools are necessary for maintaining a trustworthy platform?
12. Should the system have a dispute resolution mechanism in case of conflicts?
13. How should the review system be designed to prevent fake reviews?
14. What level of access should admins have over user data?
15. Should there be an emergency contact system for sensitive requests?

---

## Scenarios

### Scenario 1: Requesting Assistance for Grocery Shopping
**Actors:** Resident (Requester), Volunteer, System  
**Precondition:** The user has signed up and logged into the system.  

**Steps:**
1. The resident logs in and clicks "Post a New Request."
2. The resident selects "Grocery Shopping for Seniors" as the task type.
3. The resident enters task details (e.g., list of items, store preference).
4. The system suggests nearby volunteers based on location.
5. The request is posted, and volunteers get notifications.
6. A volunteer accepts the request.
7. The system notifies the resident and enables chat communication.
8. The volunteer completes the shopping and delivers the groceries.
9. The resident marks the task as "Completed" and leaves a review.

**Postcondition:** The request is archived, and both users receive a success notification.

---

### Scenario 2: Volunteer Signing Up for a Task
**Actors:** Volunteer, Resident, System  
**Precondition:** The volunteer has signed up and verified their account.  

**Steps:**
1. The volunteer logs into the platform and views available tasks.
2. The volunteer filters tasks by location and selects one of interest.
3. The volunteer clicks "Accept Task," and the system notifies the requester.
4. A chat window opens for coordination.
5. The volunteer completes the task and marks it as "Completed."
6. The system asks the resident to confirm the task completion.
7. Both the requester and volunteer leave reviews.

**Postcondition:** The volunteer gains a completed task badge, and the task is removed from the active list.

---

### Scenario 3: Handling a Cancellation
**Actors:** Resident, Volunteer, System  
**Precondition:** A task has been assigned to a volunteer.  

**Steps:**
1. The resident decides to cancel the request before the volunteer starts.
2. The resident clicks "Cancel Task" and selects a reason.
3. The system notifies the volunteer about the cancellation.
4. If the cancellation happens too frequently, the system flags the requester for review.

**Postcondition:** The task is marked as canceled and removed from the system.

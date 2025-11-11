First QA Review of the FRIMUV APP.

1. "As a student driver, I want to register using my institutional account so that I can verify that I belong to the university and am eligible to offer rides."

Does not meet the requirement. Although the part about using an institutional email is correct, it does not actually verify that the institutional email is being used to access the system.

---

2. "As a student passenger, I want to register using my institutional account so that I can verify my identity and access the platform securely."

Does not meet the requirement. Although the part about using an institutional email is correct, it does not actually verify that the institutional email is being used to access the system.

---

3. "As a student (driver or passenger), I want to log in on my Android device so that I can access my account and use the application."

---

4. "As a student (driver or passenger), I want to log out of the application so that I can protect my account when I’m not using it."
   Meets the requirement. Sessions can be logged out from the profile section.

---

5. "As a student driver, I want to publish a trip with route and time details so that passengers can join and plan their transportation."

The student driver can access the “publish a trip” option from the main screen by selecting “to campus” or “from campus.” Meets the requirement.

Depending on the option selected (to or from campus), the system automatically sets the trip’s default origin or destination. Meets the requirement.

The publishing form allows the student driver to enter: starting point, destination, date, time, number of available seats, meeting points, and route details. Meets the requirement.

If the trip departs from campus, the driver must specify the destination. Although the system assumes the starting point is within the university, the driver must select a specific meeting point (within the faculty). Does not meet the requirement, as there is no option to specify a meeting point within the faculty.

If the trip is to campus, the system automatically sets the destination as the university, but the driver can optionally specify a particular entrance within the campus. Does not meet the requirement, as there is no option to choose a specific entrance (e.g., FMAT, FIS, or Engineering parking entrance).

The driver can view a summary of the trip before confirming publication. Meets the requirement.

After publishing, the trip should be available for student passengers in the list of available trips. Unable to confirm if it meets the requirement.
A confirmation message should appear after successfully publishing the trip. Does not meet the requirement. No confirmation message is generated. This condition could be ignored or removed as it does not affect functionality.

The published trip can be edited or canceled by the student driver before it starts. Does not meet the requirement. There is no button to cancel trips.

The system verifies that all required fields are completed before allowing publication. Meets the requirement.

Only verified student drivers can publish trips. Meets the requirement.

---

6. "As a student passenger, I want to view the available trips so that I can choose the one that best fits my route and schedule."

The student passenger can access the list of available trips from the main screen by selecting “to campus” or “from campus.” Meets the requirement.

The resulting list is automatically filtered by the system according to the direction chosen by the student: to or from campus. Meets the requirement.

The student passenger can apply filters by date, time, origin, destination (if the trip is from the faculty), and available seats. Does not meet the requirement. A button should be added allowing the user to prioritize filters (e.g., by preferred time or number of available seats).

The trip list displays relevant information: driver, route, date, time, available seats, and meeting point. Meets the requirement.

The student passenger can view complete trip details before requesting to join. Meets the requirement.

If no trips match the selected filters, an informational message is displayed. Does not meet the requirement, as there is currently no filtering option.

The trip list updates in real time when new trips are published. Unable to verify.

---

7. "As a student (driver or passenger), I want to recover my account password so that I can regain access if I lose or forget it."
   Does not meet the user story or acceptance criteria.

---

8. "As a student (driver or passenger), I want to update my personal information and preferences so that my account remains accurate and reflects my current needs."

The student (driver or passenger) can access the “Edit Profile” section from the main screen.

The student (driver or passenger) can modify personal information such as:

• Username
• Phone number
• Profile photo
• Location
• University degree type
• Personal description
• Usage preferences

The system validates that all required fields meet the criteria before saving changes.
The student can update their role (driver or passenger).
When the student updates their documents (e.g., license or ID), these must be verified by the system.

If the student switches their role from passenger to driver, the system requests the required documents.
A confirmation message appears after saving the changes.

Changes are immediately reflected in the student’s profile after saving. Meets the requirement.

However:

• There is no option to edit the full profile.
• Only profile photo and phone number can be changed.
• The user cannot switch roles between driver and passenger.
• No confirmation message is displayed after saving changes.
• The system does not validate that fields meet the requirements.

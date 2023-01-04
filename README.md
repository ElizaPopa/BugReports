# BugReports

## Below you can see some of the bugs I found on the projects I worked on

**Description:** My Info/ Emergency Contacts/ User is not able to add a new contact
without a phone number (not a required field)

**Preconditions:** Go to https://opensource-demo.orangehrmlive.com/index.php/pim/viewEmergencyContacts/empNumber/65; 
Log in with admin credentials

**Steps to Reproduce:** 

1. Go to "My Info" section
2. Click on "Emergency Contacts"
3. Click on "Add" button 
4. Add "Maria" to the "Name" field
5. Add "daughter" into "Relationship" field
6. Click on "Save" button

**Expected results:** The new information has been added

**Actual results:** The new information hasn't been saved and a message error appear: "At least one phone number is required" despite no mandatory symbol (*) is displayed 

**Severity:** Low

**Priority:** Low

**Environment:** Google Chrome

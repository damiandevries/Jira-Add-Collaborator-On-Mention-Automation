# Summary
This project is an automation for Jira Cloud which allows users to add other users to the Collaborators field (Multi-User field) based on the people that have been mentioned in the last comment made.

I have created this automation because of the demand that it had in our situation at work, we are changing a big portion of our projects and the way we work. I will explain this further in the usage section.

# Usage
Users can add another Jira user or multiple Jira users to the Collaborators field based on the amount of people that are mentioned in the most recent comment made. We needed to add this automation, because we thought it would come in handy and we had external users addded to our newly made project for increased efficiency. I created a new Issue Security Scheme with an automation where based on the user present in the Assignee, Reporter and/or Collaborator fields an external user could access the issue. With that in mind I created the Add Collaborator on Mention Automation.

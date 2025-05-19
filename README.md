# osticket-ticket.lifecycle.examples

## 🛠️ osTicket Workflow Scenarios

This repository provides four detailed scenarios demonstrating how osTicket functions in a real-world IT help desk environment. Each scenario includes the perspectives of:

End-User (person requesting help)

Help Desk Agent (frontline support)

Admin (system administrator managing osTicket)

---

### 🎯 Scenario 1: Password Reset Request
🎫 End-User
User visits the osTicket support portal.

Clicks on “Open a New Ticket.”

Fills out the form with the issue: "Cannot log into my account. Please reset my password."

Submits the ticket.

📸 Example Screenshot:

🎧 Help Desk Agent
Logs into the agent panel.

Navigates to Open Tickets and sees the new ticket.

Opens the ticket and clicks “Post Reply.”

Responds: “We are processing your password reset request.”

Escalates the ticket to Level 2.

📸 Example Screenshot:

👨‍💼 Admin
Receives the escalated ticket.

Resets the user’s password via Active Directory.

Updates the ticket with: “Password has been reset. Temporary password: [provided].”

Closes the ticket and marks it as Resolved.

📸 Example Screenshot:

---

### 💼 Scenario 2: Software Installation Request
🎫 End-User
Opens a new ticket requesting Adobe Acrobat installation.

Provides asset tag of their computer and reason for request.

🎧 Help Desk Agent
Validates that software license is available.

Creates a task under the ticket for software deployment.

Assigns task to IT Technician.

👨‍💼 Admin
Approves license use and deploys Adobe via SCCM.

Marks task and ticket as complete.

---

### 🖨️ Scenario 3: Printer Not Working
🎫 End-User
Reports that the printer in Room 205 is jammed and won’t print.

Includes photo of printer error.

🎧 Help Desk Agent
Assigns technician to visit the location.

Updates user with estimated time of arrival.

👨‍💼 Admin
Reviews ticket notes and identifies recurring printer issue.

Logs incident in asset history.

Schedules maintenance or replacement.

---

### 🔒 Scenario 4: Account Locked Out
🎫 End-User
Reports being locked out after multiple login attempts.

🎧 Help Desk Agent
Checks AD for lockout status.

Unlocks account.

Replies to user and suggests enabling MFA to reduce future lockouts.

👨‍💼 Admin
Configures alert rule for repetitive lockouts.

Creates automation to notify IT team of frequent lockouts.


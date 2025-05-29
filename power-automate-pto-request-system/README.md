# Power Automate: PTO Request and Approval System

##  Overview
This Power Automate flow simplifies and automates the **PTO (Paid Time Off)** request process using SharePoint and email notifications. It was built to reduce manual follow-up, streamline approvals, and provide a clear record of time-off requests.

##  Flow Summary
- **Trigger:** New item added to a SharePoint list (PTO request submitted)
- **Steps:**
  - Send an approval request to the manager or designated approver
  - Capture their response (Approved or Rejected)
  - Send a confirmation email to the requester with the outcome
  - Optionally log the approval in the SharePoint list or another data source

##  Impact
This system:
- Reduced back-and-forth emails for PTO
- Created a reliable audit trail for time-off requests
- Improved turnaround time for approvals and team visibility

##  Files
- `PTOAuto_20250529150639.zip` — exported Power Automate flow package

##  Notes
- Requires a SharePoint list with fields like Name, Dates, Comments, Status
- Uses standard Power Automate approval actions and dynamic content
- Can be extended with calendar integration or dashboards

##  How to Use
1. Import the `.zip` file into [Power Automate](https://make.powerautomate.com)
2. Reconnect the SharePoint and Outlook connectors
3. Customize fields to match your own SharePoint list
4. Test with a sample entry to verify the flow


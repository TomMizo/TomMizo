# PTO Request & Approval Flow

This is a Power Automate flow I built to handle PTO requests through SharePoint. When someone submits a new request, the flow sends an approval to their manager and then notifies the requester based on the response.

---

### What It Does

- Triggered when a new item is added to a SharePoint list  
- Sends an approval request to the manager  
- Sends an email back to the requester once approved or rejected  
- Updates the request status in the list (if needed)

---

### Why I Made It

This helped cut down on email chains and made the approval process clearer for everyone. We also get a record of each request in the SharePoint list, which makes tracking easier.

---

### Notes

- You’ll need a SharePoint list with fields like Name, Start Date, End Date, Comments, etc.
- You’ll also need to reconnect the SharePoint and Outlook connectors when importing
- Could be improved with calendar integration or Teams notifications

---

### File

- `PTOAuto_20250529150639.zip` — exported from Power Automate

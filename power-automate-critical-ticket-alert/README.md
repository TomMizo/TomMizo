# Power Automate: Critical Ticket Alert Flow

##  Overview
This flow was built to automatically notify our IT team when a **High** or **Critical** priority ticket enters our support queue. It's designed to improve responsiveness and ensure SLA targets are met for time-sensitive issues.

## ⚙ Flow Summary
- **Trigger:** (Configured in production — likely connected to a SharePoint list or ticketing system)
- **Condition:** If ticket priority is "High" or "Critical"
- **Action:** Send alert email to the support team with ticket details

##  Impact
This flow helped reduce response time and improved SLA tracking by ensuring that critical tickets are immediately visible to the right people.

##  Files
- `CriticalTicketAlert_20250529145752.zip` — exported Power Automate flow (ready for import)

##  Notes
- Built using Power Automate’s condition/branch logic
- Email message includes dynamic content like ticket priority and description
- Can be extended to integrate with Teams, ServiceNow, or other systems

##  How to Use
To use this flow:
1. Import into [Power Automate](https://make.powerautomate.com)
2. Reconnect or re-authenticate any services used
3. Customize trigger based on your environment (e.g., SharePoint, Forms, ServiceNow)

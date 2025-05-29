# Power Automate: GTS Communications Alert Flow

##  Overview
This flow was created to ensure that important messages or alerts from the **GTS (Global Technology Services)** and **MI (Managed Infrastructure)** teams are immediately visible to the support team. It monitors communication channels and sends real-time notifications when key updates are received.

##  Flow Summary
- **Trigger:** (Likely tied to email, SharePoint, or a monitored source)
- **Logic:** Detects specific subject lines, keywords, or sources associated with GTS/MI alerts
- **Action:** Sends a notification or email to the IT team with the relevant message content

##  Impact
This automation helps reduce the chance of missing critical communications from infrastructure or global support teams, allowing for quicker response and better alignment during incident escalations or system changes.

##  Files
- `GTSCommunications_20250529150307.zip` — exported Power Automate flow package

##  Notes
- May use filters for senders, keywords, or categories
- Can be extended to post alerts in Microsoft Teams or Slack
- Designed for simple, low-maintenance alerting

##  How to Use
1. Import the `.zip` file into [Power Automate](https://make.powerautomate.com)
2. Update or reconnect any service accounts
3. Customize the filter logic based on your organization's communication patterns

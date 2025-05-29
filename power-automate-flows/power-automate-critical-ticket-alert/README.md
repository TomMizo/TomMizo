# Critical Ticket Alert Flow

This flow sends an email to our IT team when a new ticket comes in with "High" or "Critical" priority. It helps make sure we don’t miss anything urgent.

---

### What It Does

- Triggered by a new ticket (SharePoint list or external system)
- Checks ticket priority
- Sends alert email to the team if priority is High or Critical

---

### Why I Made It

We had a few cases where urgent tickets weren’t seen right away. This fixed that.

---

### Notes

- Simple condition logic — easy to adapt for other alerting use cases
- You’ll need to reconnect the email service after importing

---

### File

- `CriticalTicketAlert_20250529145752.zip`

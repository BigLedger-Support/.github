---
name: Request access for a colleague
about: Ask us to give a colleague from your company access to this support repo (O35, request-gated)
title: "Access request: <colleague name>"
labels: ["access-request"]
---

<!--
This is the ONLY way to add a colleague (you cannot invite people yourself).
We (the support robot / staff) will VERIFY the person belongs to your company,
then add them as an outside collaborator on the correct repo only.
Please do NOT share passwords or any sensitive data in this issue.
-->

**Colleague's full name:**

**Colleague's email** (the email they will use for the GitHub invite):

**Area they need** (tick one):
- [ ] Finance (`<tenant>-finance`)
- [ ] Operations (`<tenant>-operations`)

**Their role / why they need access:**

**Can your company's owner/admin confirm this person?** (yes / who):

---
_Deployment note (for robot/staff, not customers): copy this file into each customer repo at
`.github/ISSUE_TEMPLATE/access-request.md`, or place once in the org `.github` repo's
`.github/ISSUE_TEMPLATE/` to apply org-wide as a default. Ensure an `access-request` label exists
on the repo. See sop/rules.md O35 + sop/playbooks/customer-transition.md._

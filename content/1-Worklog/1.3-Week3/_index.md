---
title: "Week 3 Worklog"
weight: 3
chapter: false
pre: "<b>1.3. </b>"
---

### Week 3 Objectives:

* Learn how AWS IAM manages access to AWS resources.
* Distinguish IAM Users, Groups, Policies, and Roles.
* Understand the steps for creating users, assigning permissions, and switching roles in the guide.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Wednesday | - Read the AWS IAM introduction and distinguish the root user from an IAM user.<br>- Study Users, Groups, Policies, and Roles, including permission management through user groups.<br>- Read the steps for creating AdminGroup and AdminUser and signing in as an IAM user.<br>- Learn how to create AdminRole and OperatorUser and grant `sts:AssumeRole` permission for role switching.<br>- Read the cleanup instructions for IAM resources used in the lab. | 21/10/2026 | 21/10/2026 | [Access management with AWS IAM](https://000002.awsfcaj.com/) |

### Week 3 Achievements:

* Distinguished IAM Users, Groups, Policies, and Roles and understood their purposes in access management.
* Understood how users receive permissions from policies attached to their groups and why the root user should not be used for everyday tasks.
* Learned the steps for creating users, groups, and roles in the guide.
* Understood that switching roles provides the role's permissions during a session and requires appropriate role-switching permissions and a trust relationship.
* Recognized the need to grant permissions based on actual requirements and remove unused test IAM resources.

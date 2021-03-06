---
# required metadata

title: Assign a role to an Intune user
description: Learn how to assign a built-in or custom role to a user in Microsoft Intune.
keywords:
author: ErikjeMS
ms.author: erikje
manager: dougeby
ms.date: 03/26/2019
ms.topic: conceptual
ms.service: microsoft-intune
ms.subservice: fundamentals
ms.localizationpriority: high
ms.technology:
ms.assetid: 

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: pjain
ms.suite: ems
search.appverid: MET150
#ms.tgt_pltfrm:
ms.custom: intune-azure; get-started
ms.collection: M365-identity-device-management
---

# Assign a role to an Intune user

You can assign a [built-in](role-based-access-control.md#built-in-roles) or [custom](create-custom-role.md) role to an Intune user.

To create, edit, or assign roles, your account must have one of the following permissions in Azure AD:
- **Global Administrator**
- **Intune Service Administrator**

1. In the [Microsoft Endpoint Manager Admin Center](https://go.microsoft.com/fwlink/?linkid=2109431), choose **Tenant administration** > **Roles** > **All roles**.

2. On the **Intune roles - All roles** blade, choose the built-in role you want to assign.

3. On the <*role name*> - **Overview** blade, choose **Manage** > **Assignments**.

4. On the custom role blade, choose **Assign**.

5. On the **Role Assignments** blade, enter an **Assignment name** and optional **Assignment description** for the assignment.

6. For **Members (Groups)**, choose a group that contains the user you want to give the permissions to.

7. For **Scope (Groups)**, choose a group containing the users/devices that the member above will be allowed to manage.

8. For **Scope (Tags)**, choose tags where this role assignment will be applied.

9. When you're done, choose **OK**. The new assignment is displayed in the list of assignments.


## Next steps
- [Learn more about role-based access control in Intune](role-based-access-control.md)
- [Create a custom role](create-custom-role.md)

---
title: Accessing Git
seo-title: Accessing Git
description: This page describes how you can access and manage Git repository.
seo-description: Follow this page to learn how to access and manage your Git repository.
exl-id: 0c0671a3-e400-46f3-ad86-166a6cfdd44b
---
# Accessing Git {#accessing-git}

You can access and manage your Git Repository using Self-Service Git Account Management from Cloud Manager UI.

## Using Self-Service Git Account Management {#self-service-git}

Use the **Manage Git** button available from the Cloud Manager UI, most prominently on the pipeline card.

1. Navigate to your *Program's Overview* page and to Pipelines card.

1. You will view the **Manage Git** option to access and manage your Git Repository.

   ![](assets/manage-git1.png)

   Additionally, if you select the **Non-Production** pipeline tab, you will view the **Manage Git** option there too.

   ![](assets/manage-git-new2.png)

>[!NOTE]
>The **Manage Git** option is visible to users in the Developer or Deployment Manager role. Clicking on this button opens a dialog which allows the user to find the URL to their Cloud Manager Git Repository along with their username and password.

   ![](assets/manage-git3.png)

The important considerations to manage your Git in Cloud Manager are:

* **URL**: The repository URL
* **Username**: The user name
* **Password**: The value shown when the **Generate Password** button is clicked.


>[!NOTE]
>
>A user can check out a copy of their code, and make changes in the local code repository. When ready, the user can commit their code changes back to the remote code repository in Cloud Manager.

# WordPress on Azure Setup Guide


This repository provides a step-by-step guide on how to deploy a WordPress site on Microsoft Azure. Follow these instructions to quickly set up your WordPress instance in the cloud.
You can visit my WordPress site here https://hfurkandamar.azurewebsites.net/wordpress-on-azure/

## Table of Contents

- [Prerequisites](#prerequisites)
- [Step 1: Creating the App Service](#step-1-creating-the-app-service)
- [Step 2: Basic Configuration](#step-2-basic-configuration)
- [Step 3: Network and Additional Settings](#step-3-network-and-additional-settings)
- [Step 4: Deployment and Access](#step-4-deployment-and-access)
- [WordPress Administration](#wordpress-administration)
- [Special Notes for Student Accounts](#special-notes-for-student-accounts)
- [Resources](#resources)

## Prerequisites

Before you begin, make sure you have:

- An active Microsoft Azure account
  - If you don't have one, [create it here](https://portal.azure.com)
  - Student accounts can use [Azure for Students](https://azure.microsoft.com/en-us/free/students/) for free credits

## Step 1: Creating the App Service

1. Log in to the [Azure Portal](https://portal.azure.com)
2. In the search bar, type "App Service" and select it from the results
3. Click the **Create** button in the top left corner
4. Select **WordPress on Azure** from the options

![App Service Creation](images/app-service-creation.png)

## Step 2: Basic Configuration

### Project Details

1. Select your **Subscription** from the dropdown menu
2. Choose an existing **Resource Group** or create a new one

![Image](https://github.com/user-attachments/assets/4c6321de-37e6-4500-bf49-c40b63340785)


### Hosting Details

1. Select a **Region** for your server
   - For student accounts, only 5 regions are available: 
     - Germany West Central
     - France Central
     - Poland Central
     - Sweden Central
     - Switzerland North
2. Enter a unique name for your WordPress site

![Image](https://github.com/user-attachments/assets/a07c7213-0d34-4865-98c6-5804fabc365d)


### Hosting Plans

1. Select a hosting plan:
   - **Free**: Limited features but no cost
   - **Basic**: More features with associated costs
   - Note: Student subscriptions only support Free and Basic plans

![Image](https://github.com/user-attachments/assets/96664841-9510-4142-89c5-319d2ecb8c6c)


### WordPress Setup

1. Enter your administrator credentials:
   - Admin username
   - Password (make sure it's secure)
   - Email address

![Image](https://github.com/user-attachments/assets/4fb56f52-a897-449c-a67b-a4a4b144dcd3)


## Step 3: Network and Additional Settings

1. In the **Add-ins** tab, review optional features
   - These are not required for basic installation
2. In the **Networking** tab:
   - Free plan: No virtual network options
   - Basic plan: Select or create a virtual network
3. Skip the **Deployment** and **Tag** tabs if not needed
4. Review your configuration and click **Create**


## Step 4: Deployment and Access

1. Wait for the deployment to complete
   - This may take several minutes
2. When you see "Your deployment is complete", click **Go to resource**
3. On the Web App page, click the **Browse** button
   - Alternatively, copy the default domain and paste it in your browser
     
![Image](https://github.com/user-attachments/assets/6908b2b6-0ec9-45ba-9fdc-001f9f5adc97)

4. Wait for WordPress installation to finish

![Image](https://github.com/user-attachments/assets/f93791c5-6d28-488b-9754-27f6adbf9197)


## WordPress Administration

1. To access the admin panel, add "/wp-admin" to your site URL
   - Example: `https://your-site-name.azurewebsites.net/wp-admin`
2. Log in using the credentials you created during setup

![Image](https://github.com/user-attachments/assets/ad5edcf2-6a5d-4900-bbe9-e5c3051ebc5b)


4. You can now customize your site, add content, install plugins, etc.

![Image](https://github.com/user-attachments/assets/46ad599b-a663-4b3d-b5ae-33c3435e2872)



## Special Notes for Student Accounts

If you're using an Azure for Students subscription:

- You're limited to the Free and Basic hosting plans
- You can only deploy in 5 specific regions (listed above)
- Resource quotas may be limited compared to paid subscriptions


If you want to visit my WordPress site, I leave the link here https://hfurkandamar.azurewebsites.net/wordpress-on-azure/


## Resources

- [Azure Portal](https://portal.azure.com)
- [WordPress Documentation](https://wordpress.org/documentation/)
- [Azure App Service Documentation](https://docs.microsoft.com/en-us/azure/app-service/)
- [Azure for Students FAQ](https://azure.microsoft.com/en-us/free/students/faq/)

---

Created by Halil Furkan Damar

Feel free to contribute to this guide by creating pull requests or opening issues!






# **Marketo Lead Gen Chat Starter Template**

## **Overview**

_The Marketo Lead Gen Chat Starter Template includes an example Chat configuration that will gather lead information for prospects interested in a demo and create a new lead in Marketo._

## **What’s Included**

### Chat

This template includes a Chat configuration focused on gathering lead information and creating leads in Marketo for prospects interested in a product demo.

### Plugins

This template includes a plugin with a custom typescript function to handle the programmatic creation of leads in Marketo.

## **Installation Guide**

### Pre-requisites

#### Yext

This template requires access to the following Yext products:

- Chat

#### Marketo

This template requires inputs from Marketo including a Client ID and Client Secret. This will allow access to the APIs required to create new leads. Follow the instructions below to find these values in Marketo:

1. In Marketo, navigate to **Admin** > **Integration** > **LaunchPoint**.
2. Click **View Details** for an existing REST Service that has access to the Leads API. If a REST Service with appropriate permissions does not already exist, create one following [this guide](https://developers.marketo.com/blog/quick-start-guide-for-marketo-rest-api/) from Marketo.
3. Keep the **Client ID** and **Client Secret** on hand as they will be required inputs during the installation of the template.
4. Now you’re ready to proceed with the template installation!

### How to Install

1. In the Yext platform, navigate to **Apps > Solutions**.
2. Select the **Marketo Lead Gen Chat Starter Template**.
3. Click **View Solution**. This will open up the Admin Console, an account configuration tool that will allow you to add all of the resources mentioned above to your account.
4. In the upper right corner, click **Apply**.
5. A modal window will open and prompt you to **enter your Account ID**. You can quickly find this in the URL of your Yext account, which takes the form of “[www.yext.com/s/{accountId}/…](http://www.yext.com/s/{accountId}/…)”. Enter the ID and click **Continue**.
6. In the new modal, click **Start authorization flow**. This will open a new window. When prompted, click **Authorize**. Once you receive authorization confirmation, navigate back to the Admin Console window and click **Continue**.
7. A new modal window will open and prompt you to input several values:
   1. <span style="text-decoration:underline;">Marketo Client ID</span> - This is the Client ID from your REST Service in Marketo.
   2. <span style="text-decoration:underline;">Marketo Client Secret</span> - This is the Client Secret from your REST Service in Marketo.
   3. <span style="text-decoration:underline;">Marketo URL</span> - This should be the Base URL of your Marketo Instance. [See here](https://developers.marketo.com/rest-api/base-url/) for more information on finding your Marketo Base Url.
8. Enter these values and click **Save**.
9. A window will pop up showing all of the resources that will be added / edited within your account. Click **Continue** and, when prompted, click **Confirm**.
10. In the Console, you’ll see the message “Applying resources…”. Wait while the resources are applied. You’ll see messages in the console for each resource that is applied and will eventually receive a message saying “Successfully applied resources”.
11. You’re done! All of the template’s resources have been added to your account. Jump back into your Yext account and explore your new resources!

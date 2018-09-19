
# Getting Started

This guide describes how to make your first API call with QuickBooks Online app. If you want to integrate with QuickBooks Desktop, [click here](https://developer.intuit.com/app/developer/qbdesktop/docs/get-started).

### Create an Intuit Developer account

[Sign up](https://developer.intuit.com/v2/ui#/signup?nextUrl=%2Fapp%2Fdeveloper%2Fqbo%2Fdocs%2Fget-started) for a new Intuit Developer account or sign in with any current Intuit product account such as QuickBooks,TurboTax, Mint, or ProConnect.  

**Note:** When you create an Intuit Developer account, we create a QuickBooks test company called a sandbox company. View your sandbox company [here](https://developer.intuit.com/v2/ui#/sandbox).  

You can start exploring QuickBooks Online APIs right away through the [API Explorer](https://developer.intuit.com/v2/apiexplorer?apiname=V3QBO#?id=Account)

### Create an app

Creating an app generates your development keys. Use the app for yourself, your clients, or make it available to all QuickBooks users by listing it on the QuickBooks app store.
* Select My apps and then Create an app.
* Select the Keys tab to locate your Client ID and Client Secret.

You need your **Client ID** and **Client Secret** in the next step to generate an OAuth 2.0 access token.

### Get an OAuth 2.0 access token

Your app needs an OAuth 2.0 Access Token to access QuickBooks Online data. The [OAuth 2.0 playground](https://developer.intuit.com/v2/ui#/sandbox) is the easiest way to get your access token.  

If you’d like to learn about OAuth 2.0 in detail, see [Authentication](https://developer.intuit.com/app/developer/qbo/docs/develop/authentication-and-authorization).


### Make the first API call

By now, you have your Client ID, Client Secret, and OAuth access token. Next, you can try making an API call. In the snippet below:  

* Replace `YOUR_ACCESS_TOKEN` with the OAuth access token generated in the previous step.
* Replace `YOUR_SANDBOX_COMPANY_ID` with your sandbox-company **Company ID**

GET `CompanyInfo`


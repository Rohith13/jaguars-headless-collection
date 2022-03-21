# jaguars-headless-collection



Please find the basic headless calls including the Zone &amp; Einstein API calls. Download Headless NEW API's.postman_collection.json collection and import into your Postman workspace.

Useful Docs:

https://developer.commercecloud.com/s/commerce-api-apis

https://developer.salesforce.com/docs/commerce/commerce-api/guide/auth-z-scope-catalog.html

To make this solution work for your Commerce Cloud Sandbox, do the following:

Update shortCode, OrganizationID & ClientID as per your environment on the collection.
API ClientID used for testing: 4cbbff5c-57b9-4a9c-a1c2-8d4035584a35. Clone this API client to create new one for you

When you run a specific API endpoint, ensure that you add it's scope in the body of OAuth2 BM Token Auth call.

Example: For calling Product API endpoint, we need to append scope ("sfcc.products.rw")

**KEY** scope

**Value** SALESFORCE_COMMERCE_API:{{tenant}} sfcc.products.rw

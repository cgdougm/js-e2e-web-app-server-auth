# 

## Reference 
* [Deploy MSAL-enabled Express.js - Azure | Microsoft Docs](https://docs.microsoft.com/en-us/azure/developer/javascript/how-to/with-web-app/deploy-msal-sdk-authentication-expressjs)
    * [The Azure sample demo project is [js-e2e-web-app-server-auth]](https://github.com/Azure-Samples/js-e2e-web-app-server-auth)

## Changes to example

* had to make the redirect URL in the "Web"-type under "Authentication" in the `REAL Developer Portal` App registration
* updated `appSettings.json` with the `credentials`
* `jquery` and `popper` had to be added to package.


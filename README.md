# webapp-and-mobile-app-with-authentication

<!-- TOC -->

1. [Solution Overview](#solution-overview)
2. [Template Solution Architecture ](#template-solution-architecture)
3. [Deployment Steps](#deployment-steps)

## Solution Overview 
A mobile client app for social image sharing and with a companion web app. The app backend does background image processing using an Azure Function. The mobile client app works in offline mode, allowing you to view and upload images even when you don’t have a network connection.
This solution is built on the Azure managed services : <a href="https://azure.microsoft.com/en-us/services/app-service/">App Service</a> ,<a href="https://azure.microsoft.com/en-us/services/traffic-manager/">Traffic Manager</a> ,<a href="https://azure.microsoft.com/en-us/services/cosmos-db/">Azure Cosmos DB</a> ,<a href="https://azure.microsoft.com/en-us/services/cache/">Redis Cache</a> ,<a href="https://azure.microsoft.com/en-us/services/notification-hubs/">Notification Hubs</a> ,<a href="https://azure.microsoft.com/en-us/services/active-directory/">Azure Active Directory</a> ,<a href="https://azure.microsoft.com/en-us/services/functions/S">Functions</a> ,<a href="https://azure.microsoft.com/en-us/services/application-insights/">Application Insights</a> and <a href="https://azure.microsoft.com/en-us/services/hockeyapp/">HockeyApp</a>.
These services run in a high-availability environment, patched and supported, allowing you to focus on your solution instead of the environment they run in.


## Template Solution Architecture
- Traffic Manager
- Storage Account
- App plan Service
- Application Insights
- SQL Database
- Notification Hub

<img src="./images/1.png">

# SWA Angular Demo

This project demonstrates how to build a Single Page Application (SPA) using Angular and deploy it to Azure Static Web Apps. It was pretty much created by following the following two tutroials:

- [Angular SWA](https://learn.microsoft.com/en-us/azure/static-web-apps/deploy-web-framework?tabs=bash&pivots=angular)
- [Add Auth](https://learn.microsoft.com/en-us/azure/static-web-apps/authentication-authorization?tabs=angular&pivots=programming-language-javascript)
- [Add Azure Function](https://learn.microsoft.com/en-us/azure/static-web-apps/add-api?tabs=vanilla-javascript)

# Deploy to Azure

```
npx swa deploy --env production
```

## Run locally

```
npm start
```

That will run at `http://localhost:4200/`

or

```
npx swa start
```

That will run at `http://localhost:4280/`

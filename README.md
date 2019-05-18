# Example Static Website

Super simple static website to build and deploy using Azure Pipelines.

[![Build Status](https://dev.azure.com/azuredevopsexamples/website/_apis/build/status/Website?branchName=master)](https://dev.azure.com/azuredevopsexamples/website/_build/latest?definitionId=23&branchName=master)

|  Environment  | Status  | 
| ------------- | ------------- | 
| [Dev](https://examplewebsitedev.z20.web.core.windows.net/)  | ![Dev](https://vsrm.dev.azure.com/azuredevopsexamples/_apis/public/Release/badge/cc7a6b31-8365-4906-9ee8-69df6a45c2e0/1/1)  | 
| [Staging](https://examplewebsitestage.z20.web.core.windows.net/)  | ![Staging](https://vsrm.dev.azure.com/azuredevopsexamples/_apis/public/Release/badge/cc7a6b31-8365-4906-9ee8-69df6a45c2e0/1/2)  | 
| [Prod](https://examplewebsite.z20.web.core.windows.net/)  | ![Prod](https://vsrm.dev.azure.com/azuredevopsexamples/_apis/public/Release/badge/cc7a6b31-8365-4906-9ee8-69df6a45c2e0/1/3)  | 

Website is deployed as static HTML to an Azure Blob store. The contents of `www` are directly copied as part of the deployment.


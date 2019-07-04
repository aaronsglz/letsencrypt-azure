# Let's Encrypt Azure

This project has been modified to use the GoDaddy provider as described by [sjkp](https://github.com/sjkp) in [GoDaddy Support #2](https://github.com/sjkp/letsencrypt-azure/issues/2).

# Getting Started
## GoDaddy DNS + Azure Web App 
Deployment template for setting up Let's Encrypt wild card certificate for Azure Web App (hosting plan and web app must be colocated in same resource group). Hostname must already be configured on the Web App. Unlike the original project, Azure DNS Zone is not used.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Faaronsglz%2Fletsencrypt-azure%2Fmaster%2Fsrc%2FLetsEncrypt.Azure.ResourceGroup%2FTemplates%2Fletsencrypt.functionapp.renewer.godaddy.json" target="_blank"><img src="https://azuredeploy.net/deploybutton.png"/></a>

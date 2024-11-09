## Explication des fichiers :

### azuredeploy.json :
template de déploiement d'un scaleset de machines virtuelles 

### azuredeploy.parameters.json :
paramètres utilisés par azuredeploy.json

### azuredeploy_key_vault.json :
template de déploiement d'un Azure Key vault et ajout d'un secret dedans

### azuredeploy_key_vault.parameters.json :
paramètres utilisés par azuredeploy_key_vault.json

### azure-pipelines.yml :
Pipeline de déploiement sur azure du key vault et du scaleset 

### Deploy-AzureResourceGroup.ps1 :
script powershell permettant de déployer les ressources sur Azure à partir des templates

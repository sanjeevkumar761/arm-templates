# arm-templates
Azure ARM Templates

To use helloWorld template

# create the resource group
az group create --name EXPHelloWorld --location "Central US"

# deploy the template
az group deployment create --name helloWorldDeployment --resource-group EXPHelloWorld --template-uri https://raw.githubusercontent.com/sanjeevkumar761/arm-templates/master/helloWorldTemplate.json

This is a template repo where we can get ARM templates for deploying apps

Run a what-if:
az deployment group what-if --resource-group Dev_Services_Test --name rollout01 --template-uri https://raw.githubusercontent.com/DanOliverBC/bcc-arm-template/master/template2.json --parameters parameters2.json

Run the deployment:
az deployment group create --resource-group Dev_Services_Test --name rollout01 --template-uri https://raw.githubusercontent.com/DanOliverBC/bcc-arm-template/master/template2.json --parameters parameters2.json

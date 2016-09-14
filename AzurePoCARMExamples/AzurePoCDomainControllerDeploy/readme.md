# Deploy a Domain Controller in an existing AD Forest-Domain

[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https://github.com/stijnv1/AzurePoCExamples/blob/master/AzurePoCARMExamples/AzurePoCDomainControllerDeploy/Templates/azuredeploy.json)
<a href="http://armviz.io/#/?load=https://github.com/stijnv1/AzurePoCExamples/blob/master/AzurePoCARMExamples/AzurePoCDomainControllerDeploy/Templates/azuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template creates a Domain Controller VM in an existing AD domain

Tip: To get the certData from pfx file in PowerShell you can use this: [System.Convert]::ToBase64String([System.IO.File]::ReadAllBytes("path to pfx file"))
# SSM Automation Template with PowerShell

The following is a basic template for running SSM Automation document that uses PowerShell

## [ssm-automation-pwsh](cloudformation/ssm-automation-pwsh.yml)

Deploys a simple example of using SSM Automation document that runs PowerShell commands via aws:executescript. Leverage the template by changing the role permissions, the parameters to the SSM Automation document, and the PowerShell command being executed. 

## [ssm-automation-ma-orgs](cloudfomration/ssm-automation-ma-orgs.yml)

Deploys a simple example solution that allows an SSM Automation document to conifgure Organization-integrated services.


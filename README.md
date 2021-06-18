# SSM Automation Document Templates with PowerShell

The following are a few basic templates for running SSM Automation Documents that leverage PowerShell.

## [ssm-automation-pwsh](cloudformation/ssm-automation-pwsh.yml)

Deploys a simple example of using SSM Automation document that runs PowerShell commands via aws:executescript. Leverage the template by changing the role permissions, the parameters to the SSM Automation document, and the PowerShell command being executed. 

## [ssm-automation-ma-orgs](cloudfomration/ssm-automation-ma-orgs.yml)

Deploys a simple example solution that allows an SSM Automation document to conifgure Organization-integrated services.


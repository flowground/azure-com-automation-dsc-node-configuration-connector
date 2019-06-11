# ![LOGO](logo.png) AutomationManagement **flow**ground Connector

## Description

A generated **flow**ground connector for the AutomationManagement API (version 2018-01-15).

Generated from: https://api.apis.guru/v2/specs/azure.com/automation-dscNodeConfiguration/2018-01-15/swagger.json<br/>
Generated at: 2019-06-11T18:13:24+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Retrieve a list of dsc node configurations.

*Tags:* `DscNodeConfiguration`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.
* `$filter` - _optional_ - The filter to apply on the operation.
* `$skip` - _optional_ - The number of rows to skip.
* `$top` - _optional_ - The the number of rows to take.
* `$inlinecount` - _optional_ - Return total rows.

### Delete the Dsc node configurations by node configuration.

*Tags:* `DscNodeConfiguration`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `nodeConfigurationName` - _required_ - The Dsc node configuration name.
* `api-version` - _required_ - Client Api Version.

### Retrieve the Dsc node configurations by node configuration.

*Tags:* `DscNodeConfiguration`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `nodeConfigurationName` - _required_ - The Dsc node configuration name.
* `api-version` - _required_ - Client Api Version.

### Create the node configuration identified by node configuration name.

*Tags:* `DscNodeConfiguration`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `nodeConfigurationName` - _required_ - The Dsc node configuration name.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-automation-dsc-node-configuration-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

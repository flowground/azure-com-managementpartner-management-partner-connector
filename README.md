# ![LOGO](logo.png) ACE Provisioning ManagementPartner **flow**ground Connector

## Description

A generated **flow**ground connector for the ACE Provisioning ManagementPartner API (version 2018-02-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/managementpartner-ManagementPartner/2018-02-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:20+03:00

## API Description

This API describe ACE Provisioning ManagementPartner

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Get operations.

> List all the operations.

*Tags:* `Operation`

#### Input Parameters
* `api-version` - _required_ - Supported version.

### Delete a specific `Partner`.

> Delete the management partner for the objectId and tenantId.

*Tags:* `partner`

#### Input Parameters
* `partnerId` - _required_ - Id of the Partner
* `api-version` - _required_ - Supported version.

### Get a specific `Partner`.

> Get the management partner using the partnerId, objectId and tenantId.

*Tags:* `partner`

#### Input Parameters
* `partnerId` - _required_ - Id of the Partner
* `api-version` - _required_ - Supported version.

### Update a specific `Partner`.

> Update the management partner for the objectId and tenantId.

*Tags:* `partner`

#### Input Parameters
* `partnerId` - _required_ - Id of the Partner
* `api-version` - _required_ - Supported version.

### Create a specific `Partner`.

> Create a management partner for the objectId and tenantId.

*Tags:* `partner`

#### Input Parameters
* `partnerId` - _required_ - Id of the Partner
* `api-version` - _required_ - Supported version.

## License

**flow**ground :- Telekom iPaaS / azure-com-managementpartner-management-partner-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

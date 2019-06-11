# ![LOGO](logo.png) RecoveryServicesBackupClient **flow**ground Connector

## Description

A generated **flow**ground connector for the RecoveryServicesBackupClient API (version 2017-07-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/recoveryservicesbackup-jobs/2017-07-01/swagger.json<br/>
Generated at: 2019-06-11T18:14:11+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Provides a pageable list of jobs.

*Tags:* `BackupJobs`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `vaultName` - _required_ - The name of the recovery services vault.
* `resourceGroupName` - _required_ - The name of the resource group where the recovery services vault is present.
* `subscriptionId` - _required_ - The subscription Id.
* `$filter` - _optional_ - OData filter options.
* `$skipToken` - _optional_ - skipToken Filter.

### Gets exteded information associated with the job.

*Tags:* `JobDetails`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `vaultName` - _required_ - The name of the recovery services vault.
* `resourceGroupName` - _required_ - The name of the resource group where the recovery services vault is present.
* `subscriptionId` - _required_ - The subscription Id.
* `jobName` - _required_ - Name of the job whose details are to be fetched.

## License

**flow**ground :- Telekom iPaaS / azure-com-recoveryservicesbackup-jobs-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

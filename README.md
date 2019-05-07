# ![LOGO](logo.png) StorSimpleManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the StorSimpleManagementClient API (version 2016-10-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/storSimple1200Series-StorSimple/2016-10-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:15+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List of AvailableProviderOperations

*Tags:* `AvailableProviderOperations`

#### Input Parameters
* `api-version` - _required_ - The api version

### Retrieves all the managers in a subscription.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `api-version` - _required_ - The api version

### Retrieves all the managers in a resource group.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `api-version` - _required_ - The api version

### Deletes the manager.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the properties of the specified manager name.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Updates the StorSimple Manager.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or updates the manager.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the access control records in a manager.

*Tags:* `AccessControlRecords`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Deletes the access control record.

*Tags:* `AccessControlRecords`

#### Input Parameters
* `accessControlRecordName` - _required_ - The name of the access control record to delete.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the properties of the specified access control record name.

*Tags:* `AccessControlRecords`

#### Input Parameters
* `accessControlRecordName` - _required_ - Name of access control record to be fetched.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or Updates an access control record.

*Tags:* `AccessControlRecords`

#### Input Parameters
* `accessControlRecordName` - _required_ - The name of the access control record.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the alerts in a manager.

*Tags:* `Alerts`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$filter` - _optional_ - OData Filter options

### Retrieves all the backups in a manager.

*Tags:* `Backups`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$filter` - _optional_ - OData Filter options

### Upload Vault Cred Certificate.<br/>
> Returns UploadCertificateResponse

*Tags:* `Managers`

#### Input Parameters
* `certificateName` - _required_ - Certificate Name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Clear the alerts.

*Tags:* `Alerts`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the devices in a manager.

*Tags:* `Devices`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$expand` - _optional_ - Specify $expand=details to populate additional fields related to the device.

### Deletes the device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the properties of the specified device name.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$expand` - _optional_ - Specify $expand=details to populate additional fields related to the device.

### Patches the device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device Name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the alert settings of the specified device name.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or updates the alert settings

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the backup schedule groups in a device.

*Tags:* `BackupScheduleGroups`

#### Input Parameters
* `deviceName` - _required_ - The name of the device.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Deletes the backup schedule group.

*Tags:* `BackupScheduleGroups`

#### Input Parameters
* `deviceName` - _required_ - The name of the device.
* `scheduleGroupName` - _required_ - The name of the schedule group.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the properties of the specified backup schedule group name.

*Tags:* `BackupScheduleGroups`

#### Input Parameters
* `deviceName` - _required_ - The name of the device.
* `scheduleGroupName` - _required_ - The name of the schedule group.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or Updates the backup schedule Group.

*Tags:* `BackupScheduleGroups`

#### Input Parameters
* `deviceName` - _required_ - The name of the device.
* `scheduleGroupName` - _required_ - The name of the schedule group.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the backups in a device. Can be used to get the backups for failover also.

*Tags:* `Backups`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `forFailover` - _optional_ - Set to true if you need backups which can be used for failover.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$filter` - _optional_ - OData Filter options

### Deletes the backup.

*Tags:* `Backups`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `backupName` - _required_ - The backup name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Clones the given backup element to a new disk or share with given details.

*Tags:* `Backups`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `backupName` - _required_ - The backup name.
* `elementName` - _required_ - The backup element name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the chap settings in a device.

*Tags:* `ChapSettings`

#### Input Parameters
* `deviceName` - _required_ - The name of the device.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Deletes the chap setting.

*Tags:* `ChapSettings`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `chapUserName` - _required_ - The chap user name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the properties of the specified chap setting name.

*Tags:* `ChapSettings`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `chapUserName` - _required_ - The user name of chap to be fetched.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or updates the chap setting.

*Tags:* `ChapSettings`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `chapUserName` - _required_ - The chap user name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Deactivates the device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the iSCSI disks in a device.

*Tags:* `IscsiDisks`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Downloads updates on the device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Fails over the device to another device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the devices which can be used as failover targets for the given device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$expand` - _optional_ - Specify $expand=details to populate additional fields related to the device.

### Retrieves all the file servers in a device.

*Tags:* `FileServers`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Deletes the file server.

*Tags:* `FileServers`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `fileServerName` - _required_ - The file server name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the properties of the specified file server name.

*Tags:* `FileServers`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `fileServerName` - _required_ - The file server name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or updates the file server.

*Tags:* `FileServers`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `fileServerName` - _required_ - The file server name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Backup the file server now.

*Tags:* `FileServers`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `fileServerName` - _required_ - The file server name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Gets the file server metrics.

*Tags:* `FileServers`

#### Input Parameters
* `deviceName` - _required_ - The name of the device.
* `fileServerName` - _required_ - The name of the file server name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$filter` - _optional_ - OData Filter options

### Retrieves metric definitions of all metrics aggregated at the file server.

*Tags:* `FileServers`

#### Input Parameters
* `deviceName` - _required_ - The name of the device.
* `fileServerName` - _required_ - The name of the file server.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the file shares in a file server.

*Tags:* `FileShares`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `fileServerName` - _required_ - The file server name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Deletes the file share.

*Tags:* `FileShares`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `fileServerName` - _required_ - The file server name.
* `shareName` - _required_ - The file share Name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the properties of the specified file share name.

*Tags:* `FileShares`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `fileServerName` - _required_ - The file server name.
* `shareName` - _required_ - The file share name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or updates the file share.

*Tags:* `FileShares`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `fileServerName` - _required_ - The file server name.
* `shareName` - _required_ - The file share name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Gets the file share metrics

*Tags:* `FileShares`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `fileServerName` - _required_ - The file server name.
* `shareName` - _required_ - The file share name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$filter` - _optional_ - OData Filter options

### Retrieves metric definitions of all metrics aggregated at the file share.

*Tags:* `FileShares`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `fileServerName` - _required_ - The file server name.
* `shareName` - _required_ - The file share name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Installs the updates on the device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the iSCSI in a device.

*Tags:* `IscsiServers`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Deletes the iSCSI server.

*Tags:* `IscsiServers`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `iscsiServerName` - _required_ - The iSCSI server name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the properties of the specified iSCSI server name.

*Tags:* `IscsiServers`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `iscsiServerName` - _required_ - The iSCSI server name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or updates the iSCSI server.

*Tags:* `IscsiServers`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `iscsiServerName` - _required_ - The iSCSI server name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Backup the iSCSI server now.

*Tags:* `IscsiServers`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `iscsiServerName` - _required_ - The iSCSI server name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the disks in a iSCSI server.

*Tags:* `IscsiDisks`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `iscsiServerName` - _required_ - The iSCSI server name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Deletes the iSCSI disk.

*Tags:* `IscsiDisks`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `iscsiServerName` - _required_ - The iSCSI server name.
* `diskName` - _required_ - The disk name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the properties of the specified iSCSI disk name.

*Tags:* `IscsiDisks`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `iscsiServerName` - _required_ - The iSCSI server name.
* `diskName` - _required_ - The disk name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or updates the iSCSI disk.

*Tags:* `IscsiDisks`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `iscsiServerName` - _required_ - The iSCSI server name.
* `diskName` - _required_ - The disk name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Gets the iSCSI disk metrics

*Tags:* `IscsiDisks`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `iscsiServerName` - _required_ - The iSCSI server name.
* `diskName` - _required_ - The iSCSI disk name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$filter` - _optional_ - OData Filter options

### Retrieves metric definitions for all metric aggregated at the iSCSI disk.

*Tags:* `IscsiDisks`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `iscsiServerName` - _required_ - The iSCSI server name.
* `diskName` - _required_ - The iSCSI disk name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Gets the iSCSI server metrics

*Tags:* `IscsiServers`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `iscsiServerName` - _required_ - The iSCSI server name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$filter` - _optional_ - OData Filter options

### Retrieves metric definitions for all metrics aggregated at iSCSI server.

*Tags:* `IscsiServers`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `iscsiServerName` - _required_ - The iSCSI server name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the jobs in a device.

*Tags:* `Jobs`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$filter` - _optional_ - OData Filter options

### Returns the properties of the specified job name.

*Tags:* `Jobs`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `jobName` - _required_ - The job name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves the device metrics.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The name of the appliance.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$filter` - _optional_ - OData Filter options

### Retrieves metric definition of all metrics aggregated at device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The name of the appliance.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the network settings of the specified device name.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Scans for updates on the device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or updates the security settings.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Sends a test alert email.

*Tags:* `Alerts`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the file shares in a device.

*Tags:* `FileShares`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the time settings of the specified device name.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the update summary of the specified device name.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the encryption settings of the manager.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Deletes the extended info of the manager.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the extended information of the specified manager name.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Updates the extended info of the manager.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `If-Match` - _required_ - Pass the ETag of ExtendedInfo fetched from GET call

### Creates the extended info of the manager.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the file servers in a manager.

*Tags:* `FileServers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the symmetric encryption key of the manager.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the iSCSI servers in a manager.

*Tags:* `IscsiServers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the jobs in a manager.

*Tags:* `Jobs`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$filter` - _optional_ - OData Filter options

### Gets the  manager metrics

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$filter` - _optional_ - OData Filter options

### Retrieves metric definition of all metrics aggregated at manager.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the storage account credentials in a manager.

*Tags:* `StorageAccountCredentials`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Deletes the storage account credential

*Tags:* `StorageAccountCredentials`

#### Input Parameters
* `credentialName` - _required_ - The name of the storage account credential.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the properties of the specified storage account credential name.

*Tags:* `StorageAccountCredentials`

#### Input Parameters
* `credentialName` - _required_ - The name of storage account credential to be fetched.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or updates the storage account credential

*Tags:* `StorageAccountCredentials`

#### Input Parameters
* `credentialName` - _required_ - The credential name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the storage domains in a manager.

*Tags:* `StorageDomains`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Deletes the storage domain.

*Tags:* `StorageDomains`

#### Input Parameters
* `storageDomainName` - _required_ - The storage domain name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the properties of the specified storage domain name.

*Tags:* `StorageDomains`

#### Input Parameters
* `storageDomainName` - _required_ - The storage domain name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or updates the storage domain.

*Tags:* `StorageDomains`

#### Input Parameters
* `storageDomainName` - _required_ - The storage domain name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

## License

**flow**ground :- Telekom iPaaS / azure-com-stor-simple-1200-series-stor-simple-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

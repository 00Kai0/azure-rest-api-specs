## CLI

These settings don't need to apply `--cli` on the command line.

``` yaml
cli:
  cli-name: storage
  package-name: azure-mgmt-storage
  namespace: azure.mgmt.storage
  test-scenario:
    - name: /StorageAccounts/put/StorageAccountCreate
    - name: /FileServices/put/PutFileServices
    - name: /BlobServices/put/PutBlobServices
    - name: /QueueServices/put/QueueServicesPut
    - name: /TableServices/put/TableServicesPut
    - name: /EncryptionScopes/put/StorageAccountPutEncryptionScope
    - name: /ManagementPolicies/put/StorageAccountSetManagementPolicies
    - name: /ObjectReplicationPolicies/put/StorageAccountUpdateObjectReplicationPolicyOnDestination
    - name: /ObjectReplicationPolicies/put/StorageAccountUpdateObjectReplicationPolicyOnSource
    - name: /ObjectReplicationPolicies/put/StorageAccountCreateObjectReplicationPolicyOnDestination
    - name: /FileShares/put/Create NFS Shares
    - name: /FileShares/put/PutShares
    - name: /ObjectReplicationPolicies/put/StorageAccountCreateObjectReplicationPolicyOnSource
    - name: /FileShares/put/PutShares with Access Tier
    - name: /Queue/put/QueueOperationPut
    - name: /Queue/put/QueueOperationPutWithMetadata
    - name: /Table/put/TableOperationPut
    - name: /PrivateEndpointConnections/put/StorageAccountPutPrivateEndpointConnection
    - name: /BlobContainers/put/PutContainerWithDefaultEncryptionScope
    - name: /BlobContainers/put/PutContainers
    - name: /BlobContainers/put/CreateOrUpdateImmutabilityPolicy
    - name: /BlobContainers/get/GetImmutabilityPolicy
    - name: /BlobContainers/get/GetContainers
    - name: /PrivateEndpointConnections/get/StorageAccountGetPrivateEndpointConnection
    - name: /Queue/get/QueueOperationGet
    - name: /Table/get/TableOperationGet
    - name: /ObjectReplicationPolicies/get/StorageAccountGetObjectReplicationPolicies
    - name: /FileShares/get/GetShareStats
    - name: /FileShares/get/GetShares
    - name: /BlobContainers/get/ListDeletedContainers
    - name: /ManagementPolicies/get/StorageAccountGetManagementPolicies
    - name: /BlobContainers/get/ListContainers
    - name: /Table/get/TableOperationList
    - name: /Queue/get/QueueOperationList
    - name: /EncryptionScopes/get/StorageAccountGetEncryptionScope
    - name: /FileShares/get/ListShares
    - name: /FileShares/get/ListDeletedShares
    - name: /QueueServices/get/QueueServicesGet
    - name: /TableServices/get/TableServicesGet
    - name: /BlobServices/get/GetBlobServices
    - name: /FileServices/get/GetFileServices
    - name: /PrivateEndpointConnections/get/StorageAccountListPrivateEndpointConnections
    - name: /ObjectReplicationPolicies/get/StorageAccountListObjectReplicationPolicies
    - name: /PrivateLinkResources/get/StorageAccountListPrivateLinkResources
    - name: /EncryptionScopes/get/StorageAccountEncryptionScopeList
    - name: /QueueServices/get/QueueServicesList
    - name: /TableServices/get/TableServicesList
    - name: /FileServices/get/ListFileServices
    - name: /BlobServices/get/ListBlobServices
    - name: /StorageAccounts/get/StorageAccountGetPropertiesCMKEnabled
    - name: /StorageAccounts/get/StorageAccountGetProperties
    - name: /StorageAccounts/get/StorageAccountListByResourceGroup
    - name: /Usages/get/UsageList
    - name: /StorageAccounts/get/StorageAccountList
    - name: /Skus/get/SkuList
    - name: /Operations/get/OperationsList
    - name: /BlobContainers/post/ExtendImmutabilityPolicy
    - name: /BlobContainers/post/LockImmutabilityPolicy
    - name: /BlobContainers/post/ClearLegalHoldContainers
    - name: /BlobContainers/post/SetLegalHoldContainers
    - name: /BlobContainers/post/Acquire a lease on a container
    - name: /BlobContainers/post/Break a lease on a container
    - name: /BlobContainers/patch/UpdateContainers
    - name: /FileShares/post/RestoreShares
    - name: /Queue/patch/QueueOperationPatch
    - name: /Table/patch/TableOperationPatch
    - name: /FileShares/patch/UpdateShares
    - name: /EncryptionScopes/patch/StorageAccountPatchEncryptionScope
    - name: /StorageAccounts/post/StorageAccountRevokeUserDelegationKeys
    - name: /StorageAccounts/post/BlobRangesRestore
    - name: /StorageAccounts/post/StorageAccountListServiceSAS
    - name: /StorageAccounts/post/StorageAccountListAccountSAS
    - name: /StorageAccounts/post/StorageAccountRegenerateKerbKey
    - name: /StorageAccounts/post/StorageAccountRegenerateKey
    - name: /StorageAccounts/post/StorageAccountListKeys
    - name: /StorageAccounts/post/StorageAccountFailover
    - name: /StorageAccounts/patch/StorageAccountEnableAD
    - name: /StorageAccounts/patch/StorageAccountUpdate
    - name: /StorageAccounts/patch/StorageAccountEnableCMK
    - name: /StorageAccounts/post/StorageAccountCheckNameAvailability
    - name: /BlobContainers/delete/DeleteImmutabilityPolicy
    - name: /BlobContainers/delete/DeleteContainers
    - name: /PrivateEndpointConnections/delete/StorageAccountDeletePrivateEndpointConnection
    - name: /Table/delete/TableOperationDelete
    - name: /Queue/delete/QueueOperationDelete
    - name: /ObjectReplicationPolicies/delete/StorageAccountDeleteObjectReplicationPolicies
    - name: /FileShares/delete/DeleteShares
    - name: /ManagementPolicies/delete/StorageAccountDeleteManagementPolicies
    - name: /StorageAccounts/delete/StorageAccountDelete
```
## CLI

These settings apply only when `--cli` is specified on the command line.

``` yaml
cli:
  cli-name: storagecache
  package-name: azure-mgmt-storagecache
  namespace: azure.mgmt.storagecache
  test-scenario:
    - name: Caches_CreateOrUpdate
    - name: StorageTargets_CreateOrUpdate
    - name: StorageTargets_Get
    - name: StorageTargets_List
    - name: Caches_Get
    - name: Caches_ListByResourceGroup
    - name: UsageModels_List
    - name: Caches_List
    - name: Skus_List
    - name: StorageTargets_List
    - name: Caches_UpgradeFirmware
    - name: Caches_Flush
    - name: Caches_Start
    - name: Caches_Stop
    - name: Caches_Update
    - name: StorageTargets_Delete
    - name: Caches_Delete
```
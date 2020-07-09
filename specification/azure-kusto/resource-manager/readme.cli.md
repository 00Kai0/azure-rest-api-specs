## CLI

These settings apply only when `--cli` is specified on the command line.

``` yaml $(cli)
cli:
  namespace: azure.mgmt.kusto
  flatten-all: true
  test-scenario:
    - name: /Clusters/put/KustoClustersCreateOrUpdate
    - name: /Databases/put/KustoDatabasesCreateOrUpdate
    - name: /ClusterPrincipalAssignments/put/KustoClusterPrincipalAssignmentsCreateOrUpdate
    - name: /DataConnections/put/KustoDataConnectionsCreateOrUpdate
    - name: /AttachedDatabaseConfigurations/put/AttachedDatabaseConfigurationsCreateOrUpdate
    - name: /DatabasePrincipalAssignments/put/KustoDatabasePrincipalAssignmentsCreateOrUpdate
    - name: /DatabasePrincipalAssignments/get/KustoDatabasePrincipalAssignmentsGet
    - name: /AttachedDatabaseConfigurations/get/AttachedDatabaseConfigurationsGet
    - name: /DataConnections/get/KustoDataConnectionsGet
    - name: /ClusterPrincipalAssignments/get/KustoClusterPrincipalAssignmentsGet
    - name: /DatabasePrincipalAssignments/get/KustoPrincipalAssignmentsList
    - name: /DataConnections/get/KustoDatabasesListByCluster
    - name: /AttachedDatabaseConfigurations/get/KustoAttachedDatabaseConfigurationsListByCluster
    - name: /Databases/get/KustoDatabasesGet
    - name: /ClusterPrincipalAssignments/get/KustoPrincipalAssignmentsList
    - name: /Databases/get/KustoDatabasesListByCluster
    - name: /Clusters/get/KustoClustersListResourceSkus
    - name: /Clusters/get/KustoClustersGet
    - name: /Clusters/get/KustoClustersListByResourceGroup
    - name: /Clusters/get/KustoClustersList
    - name: /Clusters/get/KustoClustersListSkus
    - name: /Operations/get/KustoOperationsList
    - name: /DataConnections/patch/KustoDataConnectionsUpdate
    - name: /DatabasePrincipalAssignments/post/KustoDatabaseCheckNameAvailability
    - name: /DataConnections/post/KustoDataConnectionValidation
    - name: /DataConnections/post/KustoDataConnectionsCheckNameAvailability
    - name: /Databases/post/KustoDatabaseRemovePrincipals
    - name: /Databases/post/KustoDatabaseListPrincipals
    - name: /Databases/post/KustoDatabaseAddPrincipals
    - name: /ClusterPrincipalAssignments/post/KustoClusterPrincipalAssignmentsCheckNameAvailability
    - name: /Databases/patch/KustoDatabasesUpdate
    - name: /Clusters/post/KustoClusterRemoveLanguageExtensions
    - name: /Clusters/post/KustoClusterDetachFollowerDatabases
    - name: /Clusters/post/KustoClusterDiagnoseVirtualNetwork
    - name: /Clusters/post/KustoClusterListLanguageExtensions
    - name: /Clusters/post/KustoClusterAddLanguageExtensions
    - name: /Clusters/post/KustoClusterListFollowerDatabases
    - name: /Databases/post/KustoDatabaseCheckNameAvailability
    - name: /Clusters/post/KustoClustersStart
    - name: /Clusters/post/KustoClustersStop
    - name: /Clusters/patch/KustoClustersUpdate
    - name: /Clusters/post/KustoClustersCheckNameAvailability
    - name: /DatabasePrincipalAssignments/delete/KustoDatabasePrincipalAssignmentsDelete
    - name: /AttachedDatabaseConfigurations/delete/AttachedDatabaseConfigurationsDelete
    - name: /DataConnections/delete/KustoDataConnectionsDelete
    - name: /ClusterPrincipalAssignments/delete/KustoClusterPrincipalAssignmentsDelete
    - name: /Databases/delete/KustoDatabasesDelete
    - name: /Clusters/delete/KustoClustersDelete
```

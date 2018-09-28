# Decreasing Read Capacity<a name="Scaling.RedisReplGrps.ScaleIn"></a>

To decrease read capacity, delete one or more read replicas from your Redis cluster with replicas \(called *replication group* in the API/CLI\)\. If the cluster is Multi\-AZ with automatic failover enabled, you cannot delete the last read replica without first disabling Multi\-AZ with automatic failover\. For more information, see [Modifying a Replication Group](Replication.Modify.md)\.

For more information, see [Deleting a Read Replica, for Redis \(cluster mode disabled\) Replication Groups ](Replication.RemoveReadReplica.md)\.
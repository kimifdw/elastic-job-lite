# 备注
1. Elastic-Job中各个策略分配的方式，都是基于AverageAllocationJobShardingStrategy，即基于平均分配算法的策略
2. job触发是将作业持久化到zookeeper

查询某一个孕龄的任务配置

select content\_id from CompanionTaskContent where task\_id in \(select a.id from CompanionTask a where a.day\_num=17 and a.s\_status=1 order by a.id desc\) limit 30;

查询最新的完成的任务

select \* from CompanionTaskComplete order by id desc limit 5;

index=gostdout-test 200328\_task\_complete\_utl task\_content\_id GetTaskContentIdList



index=nginx\* "/preg\_intf/index\_content/index\_banner" 


** 领队申请表 **`yxk_leader_apply` 

|字段名|数据类型|默认值|允许非空|自动递增|备注|
| -- | -- | -- | -- | -- | -- |
| id | mediumint(8) unsigned |  |NO | 是 | 编号 |
| lid | int(11) | 0 | NO |  | 领队id |
| cat | varchar(20) |  | yes |  | 申请的分类 |
| mdd | text |  | yes |  | 申请的目的地 |
| beizhu | varchar(11) |  | yes |  | 待删除 |
| op | varchar(20) |  | yes |  | 操作者 |
| status | int(11) | 0 | yes |  | 0,未处理 1,已通过 -1,	已拒绝 -2,已取消 |
| op_id | int(11) | 0 | yes |  | 操作者ID |
| create_time | int(11) | 0 | yes |  | 创建时间 |
| update_time | int(11) | 0 | yes |  | 更新时间 |
| day_history | text | 0 | yes |  | 历史申请天数 |
| chat01 | text |  | yes |  | 导服与领队沟通记录 |
| chat02 | text|  | yes |  | 导服与计调沟通记录 |
| notice | tinyint(1)| 1 | yes |  | 是否通知领队 |
| is_del | tinyint(1)| 0 | yes |  | 是否已删除 |
| is_read | tinyint(1) | 0 | yes |  | 是否阅读 |
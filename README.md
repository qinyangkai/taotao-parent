# taotao-parent
taotao-parent -- 管理依赖jar包的版本，全局，公司级别



后台管理系统工程结构：
taotao-parent -- 管理依赖jar包的版本，全局，公司级别
|--taotao-common  --- 通用组件、工具类
|--taotao-manager  -- 后台系统
  |--com.taotao.manage.pojo
  |--com.taotao.manage.mapper
  |--com.taotao.manage.service
  |--com.taotao.manage.web


依赖关系：
web 依赖于 service
service 依赖于 mapper
mapper 依赖于 pojo 
  

## ashop-manager-dao
ashop的mapper映射文件

### 所需依赖
- ashop-manager-pojo：接口和mapper映射文件所需要的返回值
- mybatis相关依赖
- mysql依赖
- 数据库连接池

> spring相关的依赖不需要的，因为manager工程是个聚合工程，要聚合到service下。只需要在service下加载dao的jar包即可
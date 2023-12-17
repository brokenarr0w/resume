### 技术栈：
Spring Boot + MySQL + Sa-Token + Mybatis-plus + Slf4j + Caffeine + Vue + Element-Plus
### 项目亮点：
* 使用Sa-Token配合Spring的拦截器和前端的Axios实现了整个项目的鉴权与界面拦截。
* 自定义了元数据对象处理器，实现了数据库的公共字段填充。
* 实现了自定义全局异常处理并统一封装了返回类。
* 使用Caffeine缓存了首页右侧的置顶博客和左侧的个人介绍,减轻了数据库的压力。

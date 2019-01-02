# ts-demo
typescript demo 

### 项目目录结构
    .  
    ├── build  // 编译文件
    ├── node_modules  // 模块文件
    ├── src // 资源文件
    │   ├── app.ts // 程序入口
    │   ├── config  // 配置文件
    │   │   ├── config-local.ts
    │   │   ├── config-production.ts
    │   │   ├── index.ts  // index 文件
    │   ├── controllers // 负责具体的业务模块流程的控制
    │   │   ├── index.ts
    │   │   └── user.ts
    │   ├── daos // 负责与数据库进行联络
    │   │   ├── index.ts
    │   │   └── user
    │   ├── doc // 可以存放一些文件
    │   ├── models  // 表映射
    │   │   ├── entity
    │   │   ├── enum.ts
    │   │   └── index.ts
    │   ├── router  // 处理接口请求
    │   │   ├── index.ts
    │   │   └── user.ts
    │   ├── routerToken  // 处理接口请求
    │   │   ├── basic.ts
    │   │   └── index.ts
    │   └── utils // 常用模块封装
    │       ├── index.ts
    │       └── log.ts
    ├── test // 测试文件
    │   └── test.ts
    ├── views // 视图
    ├── package.json  
    ├── tsconfig.json  // TS 配置文件
    └── tslint.json // 代码规范


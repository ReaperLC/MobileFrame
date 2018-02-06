# MobileFrame  项目搭建时的基本目录结构222222

项目目录
├── ThirdLib（三方库）
│   ├── SDWebImage
│   └── AFNetworking
├── Framework（自己封装的类库）
├── General（通用类目录）
│   ├── Class（通用的类，比如自定义父类）
│   └── Helper（通用辅助方法）
├── Main（程序单一入口，仅放AppDelegate区分其他文件）
│   ├── AppDelegate.h
│   └── AppDelegate.m
├── Model（数据模型类目录）
│   ├── Macro（宏定义目录）
│   ├── BLL（业务逻辑层目录）
│   ├── DAL（数据访问层目录）
│   ├── Entity（自定义实体目录）
│   ├── Request（网络请求类目录）
│   ├── Location（定位服务类目录）
│   └── Socket（Socket类目录）
├── Module（功能模块目录）
│   │ 
│   ├─── ModuleA
│   │      ├── ViewControllerA.h（视图控制器头文件）
│   │      └── ViewControllerA.m（视图控制器m文件）
│   ├── ModuleB
│   ├── ModuleC
│   ├── ModuleD
│   └── ModuleE
└── View（视图类目录）
    └── MyTestView


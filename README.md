# cloud-native-boot-camp

## Pre-learning

[https://learnku.com/docs/the-way-to-go](https://learnku.com/docs/the-way-to-go)

[https://draveness.me/golang/](https://draveness.me/golang/)

[https://github.com/cncamp/101](https://github.com/cncamp/101)

- readme中列举了三种办法, minikube, kubead, kind
- 对于机器配置不够好的同学，建议试一下kind
- 对于机器性能不错的同学，建议用kubeadm

[kubelet podWorker启动pod代码细节](https://pouncing-waterfall-7c4.notion.site/kubelet-go-c3b5cf9bbf4b4e3098720f61efb15e0e)

## 什么是云原生

- 在包括公有云、私有云、混合云等动态环境中构建和运行规模化应用的能力。 
- 云原生是一种思想，是技术、企业管理方法的集合。
  - 技术层面
    - 应用程序从设计之初就为在云上运行而做好准备。
    - 云平台基于自动化体系。
  - 流程层面
    - 基于 DevOps, CI/CD。
- 基于多种手段
  - 应用容器化封装;
  - 服务网格;
  - 不可变基础架构;
  - 声明式 API。
- 云原生的意义
  - 提升系统的适应性、可管理性、可观察性;
  - 使工程师能以最小成本进行频繁和可预测的系统变更。
  - 提升速度和效率，助力业务成长，缩短 I2M(Idea to Market)

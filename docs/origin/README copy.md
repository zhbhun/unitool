# unitool

## 背景介绍

### 工程化诉求

### 工具链介绍

![toolchains.jpg](./assets/toolchains.jpg)

- 开发环境：V8、Node、Deno
- 包管理器：npm、yarn、bower、pnpm、tink
- 脚手架：Vue CLI、Angular CLI、Create React APP、Yeoman
- 编译器：Babel、Closure Compiler、Prepack、haxe
- 测试工具：Mocha、Jasmine、Jest、Karma
- 构建工具：esbuild
- 调试工具： Chrome DevTools、Firebug、Webkit inspector、VS Code
- 代码格式化：JSLint、JSHint、ESLint、TSLint
- 任务管理工具：grunt、gulp
- 构建工具：webpack、rollup、parcel、browserify、esbuild
- 进程管理：nodemon、pm2、forever
- 前端框架：Angular、React、Vue、React Native、jQuery
- 后端框架：Express、Koa、Nestjs
- ...

### 开发工作流

成熟的软件项目必然有遵循良好的开发规范，也拥有属于自身独特的软件开发生命周期，编程实践只占整个开发周期的很小一部分。当一个前端被建立时通常还会遇到哪些需要解决的问题？这便涉及到了 JavaScript 项目的技术选型，而 JavaScript 生态圈的明星项目数不胜数。

![workflow.jpg](./assets/workflow.jpg)

### 前端项目现开发状

1. 技术选型碎片化

    > 虽然每个公司的技术栈可能是统一的，但具体技术选型五花八门。当团队负责的工程数量达到一定的规时，选型的碎片化无疑会让维护成本陡增。

2. 研发环节缺乏量化评估

    > 当我们寻找可以项目质量量化的研发指标时，只有测试部门提供的 Bug 率和运维部门提供的服务稳定行，而对研发环节缺乏有效的量化评估手段。比如，当我们在团队中将“提升代码的可维护性”，我们到底在讲什么呢？也许每个人都有自己的理解。

3. 开发人员学习疲倦

    > “求不要更新了，老子学不动了！”

    ![study-tired.jpg](./assets/study-tired.jpg)

    参考文献

    - [求不要更新了，老子学不动了](https://github.com/denoland/deno/issues/25)
    - [老子学不动了！](https://zhuanlan.zhihu.com/p/40980806)
    - [开篇词——技术更新的太快，真的快学不动了](https://xiaozhuanlan.com/topic/2457308916)
    - [如何看待deno项目github源码issue栏目出现“求不要更新了，老子学不动了？”？](https://www.zhihu.com/question/279356207)

## 现有“解决”方案

- [neutrinojs](https://neutrinojs.org/usage/)
- [rome](https://romefrontend.dev/)
        
    - [欲取代绝大多 JavaScript 工具链？Rome 尝鲜](https://zhuanlan.zhihu.com/p/128638932)
    - [Rome, a new JavaScript Toolchain](https://jasonformat.com/rome-javascript-toolchain/)
    - [如何评价 Facebook 推出的前端工具链 Rome？](https://www.zhihu.com/question/375769627)

## 统一前端开发工具

![architecture.jpg](./assets/architecture.jpg)

1. 规范技术选型
2. 统一技术栈
3. 工程质量管理

## 参考文献

- [如何衡量前端工程质量？我们有了平台化的解决方案](https://mp.weixin.qq.com/s?__biz=MzUxMzcxMzE5Ng==&mid=2247499390&idx=1&sn=476adc7dabb363742cbf85002e1afda7)

---

```
## 背景

工程化诉求 =》 工具链介绍 =》 开发工作流 =》 存在问题与总结 

## 目的

1. a
2. b
3. c

## 行动

1. 技术调研

  现有的解决方案

2. 架构设计
3. 开发实现
4. 实践应用

## 结果

1. 实现统一完善的前端开发工具；
2. 实现项目质量的工程化管理；
3. 完成现有项目的开发工具重构；
4. 开源与推广；
```

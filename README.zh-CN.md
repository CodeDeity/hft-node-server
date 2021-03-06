# hft-node-server

server end code for hft team

## 快速入门

egg框架的使用，参见 [egg 文档](https://eggjs.org)。

### 本地开发

```bash
$npm i
$npm dedupe (optional)
$npm run dev
$open http://localhost:7001/
```

### 调试

VS Code

#### 方法一：

- VScode Debug 选择 "Launch egg"配置
- F5启动一键启动
- 选择正确的worker程序，打断点
- 浏览器访问REST API

#### 方法二：

- 控制台命令行：npm run debug
- VScode Debug 选择Attach egg
- 选择到debug port为大于等于9230的一个进程

### 部署

```bash
$npm start
$npm stop
```

### 单元测试

- [egg-bin] 内置了 [mocha], [thunk-mocha], [power-assert], [istanbul] 等框架，让你可以专注于写单元测试，无需理会配套工具。
- 断言库非常推荐使用 [power-assert]。
- 具体参见 [egg 文档 - 单元测试](https://eggjs.org/zh-cn/core/unittest)。

### 内置指令

- 使用 `npm run lint` 来做代码风格检查。
- 使用 `npm test` 来执行单元测试。
- 使用 `npm run autod` 来自动检测依赖更新，详细参见 [autod](https://www.npmjs.com/package/autod) 。

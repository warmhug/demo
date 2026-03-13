# Demo

一个极简的 Node.js 示例项目，用于快速验证项目结构、依赖安装与基础脚本执行。

## 项目结构

```text
.
├── index.js      # 示例入口文件
├── package.json  # 项目配置与脚本定义
└── README.md     # 项目说明
```

## 环境要求

- Node.js 16+
- npm 8+

## 快速开始

1. 安装依赖：

   ```bash
   npm install
   ```

2. 运行示例（直接执行入口文件）：

   ```bash
   node index.js
   ```

   预期输出：

   ```text
   hello
   ```

3. 执行构建脚本（当前为占位脚本）：

   ```bash
   npm run build
   ```

## NPM Scripts

- `npm run build`：执行占位构建命令，当前输出 `aaa`。

## 依赖说明

- `merge2`：用于合并多个 stream 的工具库（当前示例中尚未使用，可按需扩展）。

## 后续可优化方向

- 增加 `start` / `dev` 脚本，统一运行入口。
- 引入 ESLint/Prettier，保证代码风格一致。
- 补充单元测试（如 `vitest` 或 `jest`）。
- 增加 CI 配置，自动执行安装、检查与测试流程。

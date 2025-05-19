# React + Vite 项目

这是一个基于 React 和 Vite 的前端项目模板，旨在提供一个快速开发现代 Web 应用的环境。项目集成了 ESLint 用于代码质量检查，并支持 TypeScript（可选）。

## 项目概述

本项目是一个使用 Vite 构建的 React 应用，具有以下特点：
- 使用 React 19.1.0 和 Vite 6.3.5 构建。
- 集成了 ESLint 进行代码质量检查。
- 支持 TypeScript（可选）。
- 提供了 Fast Refresh 功能，支持开发环境中的即时更新。

## 快速入门

要开始使用此项目，请按照以下步骤操作：

1. 安装依赖：
   ```bash
    yarn install
   ```
2. 启动开发服务器：
   ```bash
     yarn dev
   ```
3. 构建生产版本：
   ```bash
      yarn build
   ```
4. 预览生产构建：
   ```bash
      yarn preview
   ```

## 项目结构
/react-demo
├── public/          # 公共资源文件夹
│   ├── vite.svg     # Vite 图标
├── src/             # 源代码文件夹
│   ├── assets/      # 静态资源文件夹
│   │   ├── react.svg # React 图标
│   ├── main.jsx     # 应用入口文件
│   ├── App.jsx      # 主组件
│   ├── App.css      # 主组件样式
│   ├── index.css    # 全局样式
├── .eslintrc.js     # ESLint 配置文件
├── vite.config.js   # Vite 配置文件
├── package.json     # 项目依赖和脚本配置
├── yarn.lock        # Yarn 锁定文件
├── README.md        # 项目说明文档

## 可用脚本
在项目目录中，您可以运行以下脚本：
- yarn dev: 启动开发服务器。
- yarn build: 构建生产版本。
- yarn lint: 运行 ESLint 检查代码质量。
- yarn preview: 预览生产构建。

## 依赖说明
主要依赖包括：
- React: 用于构建用户界面的 JavaScript 库。
- Vite: 一个快速的构建工具，用于开发和构建现代 Web 应用。
- ESLint: 用于静态分析和代码质量检查。
- TypeScript (可选): 如果需要，可以集成 TypeScript 进行类型检查。
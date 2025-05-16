# ElElement - 基于Vue3的组件库

<div align="center">
  <img src="https://kstar-1253855093.cos.ap-nanjing.myqcloud.com/baguwen1.0/image-20240228153436973.png" alt="ElElement组件库" width="600">
</div>

## 项目介绍

ElElement是一个基于Vue3、TypeScript和Vite构建的现代化UI组件库，参考Element UI设计风格，提供了丰富的组件和功能。该项目旨在学习Vue3组件化开发和TypeScript在前端项目中的应用。

### 特性

- 🧩 **组件丰富** - 提供15+常用UI组件
- 🔧 **TypeScript支持** - 完全使用TypeScript开发，提供可靠的类型定义
- 📚 **完善的文档** - 使用VitePress构建的交互式文档和示例
- 🎨 **可定制的主题** - 支持自定义主题配置
- 🌐 **响应式设计** - 所有组件均采用响应式设计

## 组件列表

ElElement目前包含以下组件：

- `Alert` - 警告提示
- `Button` - 按钮
- `ButtonGroup` - 按钮组
- `Collapse` - 折叠面板
- `Container` - 布局容器
- `DatePicker` - 日期选择器
- `Dialog` - 对话框
- `Dropdown` - 下拉菜单
- `Form` - 表单
- `Icon` - 图标（集成FontAwesome）
- `Input` - 输入框
- `Link` - 链接
- `Message` - 消息提示
- `MessageBox` - 弹框
- `Rate` - 评分
- `Select` - 选择器
- `Switch` - 开关
- `Tooltip` - 文字提示

## 安装和使用

### 下载项目
```shell
git clone git@github.com:youngyangyang04/element-ui.git
cd element-ui
```

### 安装依赖
```shell
npm install
# 或使用 pnpm
pnpm install
```

### 启动项目
```shell
# 启动文档网站
npm run docs:dev

# 启动组件开发环境
npm run dev
```

### 构建项目
```shell
# 构建组件库
npm run build

# 构建文档
npm run docs:build
```

## 部署到GitHub Pages

本项目支持自动部署文档到GitHub Pages，确保在`docs/.vitepress/config.ts`中正确设置了`base`选项：

```ts
export default {
  // ...其他配置
  base: '/element-ui/' // 必须与仓库名一致
}
```

### 手动部署
1. 构建文档：`npm run docs:build`
2. 将`docs/.vitepress/dist`目录的内容推送到GitHub仓库的`gh-pages`分支

### 使用GitHub Actions自动部署
项目已配置GitHub Actions工作流，每次推送到main分支时自动构建并部署文档。

## 示例预览

<div align="center">
  <img src="https://kstar-1253855093.cos.ap-nanjing.myqcloud.com/baguwen1.0/image-20240228153506783.png" alt="组件展示" width="600">
  <br><br>
  <img src="https://kstar-1253855093.cos.ap-nanjing.myqcloud.com/baguwen1.0/image-20240228153549080.png" alt="组件展示" width="600">
</div>

## 贡献指南

1. Fork本仓库
2. 创建你的特性分支 (`git checkout -b feature/amazing-feature`)
3. 提交你的修改 (`git commit -m 'Add some amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 创建一个Pull Request

## 技术栈

- Vue 3
- TypeScript
- Vite
- VitePress
- SCSS
- FontAwesome
- ESLint

## 开源协议

MIT License

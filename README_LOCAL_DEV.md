# CVL-UESTC 实验室网站 - 本地开发文档

## 1. 项目概述

**CVL-UESTC** 是电子科技大学 (UESTC) 计算机视觉实验室的官方网站。

- **在线地址**: https://cvl-uestc.github.io/
- **技术栈**: Hugo + Hugo Blox + TailwindCSS
- **模板**: Hugo Blox Academic CV

## 2. 环境要求

| 依赖 | 版本 | 说明 |
|------|------|------|
| Hugo Extended | 0.161.x | 必须使用 Extended 版本 |
| Node.js | 22.x LTS | 推荐 LTS 版本 |
| Git | 2.x | 版本控制 |
| Go | 1.26+ | Hugo Modules 需要 |

## 3. 安装步骤

### 3.1 安装依赖（macOS）

```bash
# 安装所有基础依赖
brew install node@22 git golang hugo

# 确保使用 node@22
brew unlink node
brew link node@22 --force

# 验证版本
hugo version
node --version
go version
```

### 3.2 安装项目依赖

```bash
cd CVL-UESTC.github.io

# 清理旧依赖（如有）
rm -rf node_modules package-lock.json pnpm-lock.yaml hugo_cache resources

# 安装依赖
npm install
```

## 4. 运行开发服务器

```bash
npm run dev
```

**访问地址**: http://localhost:1313

## 5. 项目结构

```
CVL-UESTC.github.io/
├── assets/              # 静态资源
├── config/_default/     # 配置文件
├── content/             # 网站内容
├── layouts/             # HTML 模板
├── public/              # 编译后的静态站点
└── package.json         # 依赖管理
```

## 6. 常用命令

| 命令 | 说明 |
|------|------|
| `npm run dev` | 启动开发服务器 |
| `npm run build` | 构建生产版本 |
| `hugo server` | 直接使用 Hugo 启动 |
| `hugo --minify` | 构建并压缩 |

## 7. 团队信息

### 教授
- 顾舒航 (ShuHang Gu)

### 博士生
- 张乐恒、龙伟、游炜熠、张进华、周星宇

### 硕士生
- 陈恺、江世银、李珈锋、娄峻瑜、卢景博、罗嘉杰、蒙春雨、王兆旬、张子宏、赵小锐、邹佳乐

## 8. 论文成果

- CVPR 2026: 5篇
- ICLR 2026: 2篇
- ICCV 2025: 3篇
- CVPR 2025: 3篇
- NeurIPS 2024: 1篇
- CVPR 2024: 3篇

## 9. 部署

项目已配置 GitHub Actions，推送至 main 分支会自动部署到 GitHub Pages。

## 10. 参考链接

- [Hugo 官方文档](https://gohugo.io/documentation/)
- [Hugo Blox 文档](https://docs.hugoblox.com/)
- [TailwindCSS 文档](https://tailwindcss.com/docs)
- [项目在线地址](https://cvl-uestc.github.io/)

---

**成功运行时间**: 2026-04-30 11:28
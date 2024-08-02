### NextJs 14 版本官网学习项目

访问地址(需科学上网)：https://nextjs-dashboard-8ndshqv0i-zenggenghais-projects.vercel.app

根据 nextJs 官网教程项目部署学习 nextJs 14 版本

### 体验

账号：user@nextmail.com
密码：123456

### 架构

- esLink 代码检测和提示
- prettier 代码风格以及格式化
- husky git 钩子，pre-commit 执行 lint-staged 命令
- lint-staged 对 git 暂存区文件使用 prettier 格式化代码后用 esLink 检测代码情况
- vercel 云平台部署，关联 github，根据分支 main 更新自动部署

# 个人学术主页

一个无需构建工具的静态个人学术主页模板。

## 使用

直接打开 `index.html` 即可预览。

## 部署到 GitHub Pages

1. 在 GitHub 上新建一个仓库。
2. 把本目录内容推送到仓库的 `main` 分支。
3. 打开仓库 `Settings -> Pages`。
4. 在 `Build and deployment` 中选择 `Source: GitHub Actions`。
5. 推送后等待工作流执行完成，站点会自动发布。

仓库里已经包含以下部署文件：

- `.github/workflows/deploy.yml`：GitHub Pages 自动部署工作流
- `.nojekyll`：避免静态资源被 Jekyll 特殊处理
- `.gitignore`：忽略本地系统文件

## 优先修改的位置

- `index.html`
- 页面标题、姓名、机构信息
- `Hero` 区自我介绍和统计数字
- `论文与项目`、`教学与服务`、`最新动态`
- 联系方式和外部链接

## 样式与交互

- `styles.css`：整体视觉、响应式布局、动画
- `script.js`：移动端导航展开/收起、页脚年份

# KEEFLOW GitHub Profile — 安装说明

## 文件结构

- `README.md` — 个人主页内容
- `assets/banner.svg` — 自定义科技风横幅
- `.github/workflows/snake.yml` — 自动生成贡献贪吃蛇

## 安装

1. 确保 `keeflow/keeflow` 是公开仓库。
2. 将本压缩包中的 `README.md`、`assets/`、`.github/` 上传到仓库根目录，保留目录结构。
3. 打开仓库 **Settings → Actions → General → Workflow permissions**，选择 **Read and write permissions** 并保存（如果组织策略不允许，请管理员调整）。
4. 打开 **Actions → Generate contribution snake → Run workflow**，等待执行完成。工作流会创建 `output` 分支。
5. 打开 https://github.com/keeflow 查看效果。

## 注意

- 贪吃蛇图片首次运行工作流之前不会出现；后续每日自动更新。
- GitHub 统计卡片、技术图标和打字机动画依赖外部服务，服务异常时可能暂时不显示。
- 统计卡片可能无法包含私有仓库贡献。
- `SELECTED WORK` 当前只展示真实仓库列表入口，避免虚构项目；可后续替换为具体项目卡片。
- 横幅是纯 SVG，GitHub README 不支持直接执行 Vue 或 JavaScript。

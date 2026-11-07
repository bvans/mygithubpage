# My GitHub Pages

## 银行日均资产计算器

在线路径（启用 GitHub Pages 后）：

https://bvans.github.io/mygithubpage/bank-average/

源文件：[`bank-average/index.html`](bank-average/index.html)

### 首次部署

1. 打开本仓库 **Settings → Pages**。
2. 在 **Build and deployment → Source** 选择 **GitHub Actions**。
3. 打开 **Actions → Publish static calculator**，确认部署成功；首次未触发时可以执行 **Run workflow**。

### 功能与数据安全

- 基准日终资产、考核周期、银行官方日均资产和系统日终资产校准。
- 外部转入、外部转出、内部转存（内部转存不改变总资产）。
- 计算目标日日终资产、累计日均、较基准日均净增和期末预测。
- 指定目标日均净增、计划转入日期，估算还需新增的资金。
- 浏览器 `localStorage` 自动保存；JSON 导出/导入备份与迁移。

**隐私说明：** 仓库中只有静态页面源代码；不存放任何个人资金记录。用户数据留在当前浏览器，既不会自动同步到 GitHub，也不会自动跨设备同步。清理浏览器网站数据前请先导出 JSON 备份。

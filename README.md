# constellation-fortune
基于 Coze 工作流 + 前端页面的星座运势生成工具，支持选择星座/日期，调用 Coze API 生成专业的占星运势解读。

# ✨ 星座运势生成项目
## 📊 项目效果
- 核心功能：
  -- 选择星座+日期生成专属运势
  -- 拆分显示星象解读/事业/财运/幸运色
  -- 油画风UI，适配PC/移动端
  -- 真实调用 Coze 工作流 API

## 🛠 技术栈
- 前端：HTML + CSS + JavaScript（原生，无框架，由Trae生成）
- 后端：Coze 工作流 + Coze API
- 部署：VSCode Live Server（本地）/ Netlify（在线）

## 🚀 本地使用方法
### 1. 克隆仓库
```bash
git clone https://github.com/ERII00/constellation-fortune.git
cd constellation-fortune
```
### 2. 配置 Coze 参数
打开 index.html，修改以下配置（已内置我的测试参数，替换为你的）：
```
// Coze 配置项
const API_URL = "https://api.coze.cn/v1/workflow/run";
const WORKFLOW_ID = "[你的Coze工作流ID]"; // 7611915188170375209
const PAT = "[你的Coze PAT令牌]"; // pat_oh6RAY535iHobvm6odwlhrZtI1Nuv7YZahWLUAYNxNREXD8ThBXaOJNfY5AVERbk
```
### 2. 启动项目
可以直接在本地浏览器运行，也可以在VS code中运行，安装「Live Server」插件， 访问http://127.0.0.1:5500 

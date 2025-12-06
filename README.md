# 🍌 Nano BananaAI (纳米香蕉绘图站)

![GitHub stars](https://img.shields.io/github/stars/pili1121/Nano-Banana?style=flat-square)![GitHub forks](https://img.shields.io/github/forks/pili1121/Nano-Banana?style=flat-square)![GitHub issues](https://img.shields.io/github/issues/pili1121/Nano-Banana?style=flat-square)

**Nano BananaAI** 是一个轻量级、功能强大的 AI 绘图 Web 应用，一个有趣的实验性项目——其核心代码完全由 AI 编写生成。

项目支持文生图、图生图及图片二次编辑功能，并配备了完整的用户系统和超级管理员后台，非常适合新手学习和快速部署。

> 👋 **作者心声**: 我也是个编程新手，这个项目是我引导 AI 完成的。因为文件都是从宝塔直接打包，可能包含一些冗余或待优化的代码。欢迎大家一起交流、学习和改进它！

---

## ✨ 主要功能

-   🎨 **AI 绘图**:
    -   支持 **文本生成图片** (Text-to-Image) 和 **图片生成图片** (Image-to-Image)。
    -   支持 **Nano Banana Pro** 模型，可输出 2K 及 4K 高清图片。
    -   用户系统支持 **每日签到** 获取积分。
    -   用户可 **自定义配置 API Key**。
-   ✏️ **图片二次编辑**: 生成后的图片支持在线进行微调和修饰。
-   🔐 **完整的用户系统**:
    -   包含用户注册、登录、密码找回（支持邮箱验证）。
-   🛡️ **强大的后台管理**:
    -   内置超级管理员系统，可管理用户状态、查看全局绘图记录等。
-   🚀 **部署简单**:
    -   为宝塔面板优化，基于 Node.js，配置简单，一键启动。

---

## 🛠️ 技术栈与环境要求

-   **后端**: Node.js (推荐 v14.0 或更高版本)
-   **数据库**: MySQL

---

## 🚀 快速开始

### 1. 克隆项目

```bash
git clone https://github.com/pili1121/Nano-Banana.git
```

### 2. 安装依赖

进入项目目录，然后安装所需的依赖包。

```bash
cd Nano-Banana
npm install
```

### 3. 配置环境

项目可能需要一个 `.env` 配置文件来存储数据库连接信息和 API Keys。请根据项目内的示例文件（如 `.env.example`）创建并修改你的配置。

### 4. 启动项目

```bash
npm start
```

### 5. 宝塔部署 (推荐)

对于新手，最简单的方式是使用宝塔面板：
1.  在宝塔面板中创建一个新的 **Node.js 项目**。
2.  将代码上传到项目目录。
3.  在宝塔界面中执行 `npm install` 安装依赖。
4.  配置启动命令 (`npm start`) 和端口。
5.  启动并访问项目！

---

## 📈 更新日志

-   **最新更新**:
    -   ✅ 修复移动端无法生成图片的 BUG。
    -   ✅ 优化移动端主页布局，提升体验。
    -   ✅ 修复在“创作”和“灵感”页面间切换时导致的黑屏 BUG。

---

## ☕ 赞赏与交流

如果这个项目对你有帮助，欢迎请我喝杯咖啡！也欢迎添加好友，一起交流学习。

| 微信打赏 (Donate) | ➕ 加我微信 (Contact) |
| :--------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------: |
|                   <img src="https://github.com/user-attachments/assets/45a836a0-5c80-4000-94e9-4aaf14e2dbe3" width="200">                   |                   <img src="https://github.com/user-attachments/assets/d32d5ac1-b6d2-46f3-a1b9-06495cc5f95b" width="200">                   |

---

## 📄 开源许可

请添加您的项目许可证信息，例如 [MIT License](https://opensource.org/licenses/MIT)。

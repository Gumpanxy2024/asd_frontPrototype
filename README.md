# 星语助手（Star Child Partner）前端项目

这是星语助手应用的前端代码库，一个为自闭症儿童及其家长、教师提供支持的Web应用程序。

## 项目简介
星语助手是一个专为自闭症谱系障碍(ASD)儿童及其家庭设计的数字平台，旨在提供情绪管理、行为训练和社交技能发展的支持。该平台通过友好的界面和交互式工具，帮助孩子更好地表达情绪并培养必要的社交技能。

## 技术栈

- HTML5
- CSS3 
- TailwindCSS
- Font Awesome图标库
- JavaScript
- LocalStorage (用于前端数据存储)

## 项目结构

```
/
├── assets/                # 图像资源目录
│   ├── angry.png         # 情绪图标 - 生气
│   ├── happy.png         # 情绪图标 - 开心
│   ├── sadness.png       # 情绪图标 - 悲伤
│   ├── virtual.png       # 虚拟形象图片
│   └── logo.png          # 网站logo
│
├── components/           # 可复用组件
│   └── navbar.html       # 导航栏组件
│
├── css/                  # 样式文件
│   └── common.css        # 通用样式
│
├── *.html                # 页面文件
│   ├── splash.html       # 欢迎页面
│   ├── login.html        # 登录页
│   ├── personal_information.html # 个人信息设置
│   ├── home.html         # 主页
│   ├── diary.html        # 情绪日记
│   ├── moodtrend.html    # 情绪趋势分析
│   ├── chatbot.html      # AI对话助手
│   ├── training.html     # 行为训练页面
│   ├── community.html    # 社区页面
│   ├── information.html  # 信息介绍页
│   └── V1/V2_prototype.html # 原型设计页面
```

## 使用流程

### 1. 初次使用流程

1. **欢迎页面 (splash.html)**
   - 用户通过欢迎页面了解应用的基本功能
   - 可选择"进入应用"或"了解更多"

2. **用户登录 (login.html)**
   - 输入用户名和密码登录
   - 新用户可通过注册链接创建账户

3. **个人信息设置 (personal_information.html)**
   - 首次登录用户需要完成个人信息设置
   - 选择身份角色（教师/家长）
   - 家长角色需填写孩童的功能水平和兴趣信息
   - 这些信息将作为AI系统的基础记忆

4. **进入主页 (home.html)**
   - 主页展示孩子的基本信息、情绪状态和活动概览
   - 可通过主页访问其他功能模块

### 2. 日常使用流程

1. **登录应用**
   - 输入用户名和密码

2. **主页活动**
   - 查看孩子当前状态和最近活动
   - 访问推荐内容

3. **记录与互动**
   - 使用情绪日记记录孩子的情绪变化
   - 通过AI对话助手进行互动训练
   - 参与行为训练活动

4. **分析与学习**
   - 通过情绪趋势分析了解孩子的情绪规律
   - 查看专家资源，学习相关知识
   - 在社区中与其他家长交流经验

5. **信息管理**
   - 随时通过主页的"修改信息"按钮更新个人与孩童信息

## 核心功能详解

### 1. 角色分离系统
- **家长角色**：完整访问所有功能，包括孩童评估和个人兴趣设置
- **教师角色**：访问教学资源和训练模块，但无法查看或修改具体孩童的敏感信息

### 2. 个人信息与属性管理 (personal_information.html)
- **身份角色选择**：区分教师和家长不同使用场景
- **孤独症评估记录**：
  - 功能水平分类（高功能、中等功能、低功能等）
  - 主要挑战领域标记（社交互动、语言沟通、行为模式等）
- **兴趣爱好记录**：
  - 标签化记录孩童特殊兴趣
  - 详细描述喜好活动，为AI提供个性化互动基础

### 3. 情绪管理系统
- **情绪日记**：记录每日情绪变化和触发因素
- **情绪趋势分析**：通过图表直观展示情绪变化规律
- **情绪识别训练**：帮助孩子学习识别和表达不同情绪

### 4. AI对话助手
- **基于个人信息的定制对话**：根据孩子的兴趣和能力调整对话内容
- **社交情境模拟**：创建各种社交场景，帮助孩子练习应对技巧
- **渐进式难度**：根据孩子的进步自动调整互动复杂度

### 5. 行为训练模块
- **个性化训练计划**：基于孩子的评估水平制定训练内容
- **视觉化指导**：通过图片和简单动画展示期望行为
- **成就系统**：通过积分和成就徽章激励孩子完成训练

### 6. 数据安全与隐私保护
- **本地存储**：敏感信息使用localStorage仅保存在用户设备上
- **角色权限控制**：教师角色无法访问孩子的详细个人信息
- **最小化信息收集**：仅收集必要的信息用于功能实现

## 开发指南

### 本地开发

1. 克隆仓库到本地
2. 使用支持浏览器预览HTML页面，如Visual Studio Code的Live Server扩展
3. 进行页面修改后，刷新浏览器查看变更

### 设计原则

- 界面简洁明了，色彩柔和
- 避免使用闪烁或过于刺激的视觉元素
- 优先考虑易用性和无障碍设计
- 所有视觉元素都应具有明确的教育或支持目的

## 未来计划

- 多语言支持
- 离线使用功能
- 适应性学习路径
- 数据可视化增强
- 教师与家长协作功能
- 更多个性化定制选项

## 联系方式

如有任何问题或建议，请联系项目维护团队。

---

© 2025星语助手项目组 版权所有
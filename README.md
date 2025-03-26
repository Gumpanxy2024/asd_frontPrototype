 #星语助手（Star Child Partner）前端项目

这是星语助手应用的前端代码库，一个为自闭症儿童及其家长提供支持的Web应用程序。

## 项目简介
星语助手是一个专为自闭症谱系障碍(ASD)儿童及其家庭设计的数字平台，旨在提供情绪管理、行为训练和社交技能发展的支持。该平台通过友好的界面和交互式工具，帮助孩子更好地表达情绪并培养必要的社交技能。

## 技术栈

- HTML5
- CSS3 
- TailwindCSS
- Font Awesome图标库
- JavaScript

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
│   ├── home.html         # 主页
│   ├── login.html        # 登录页
│   ├── diary.html        # 情绪日记
│   ├── moodtrend.html    # 情绪趋势分析
│   ├── chatbot.html      # AI对话助手
│   ├── training.html     # 行为训练页面
│   ├── community.html    # 社区页面
│   ├── splash.html       # 欢迎页面
│   ├── information.html  # 信息介绍页
│   └── V1/V2_prototype.html # 原型设计页面
```

## 主要功能

1. **用户登录与认证** - 家长可以创建账户并管理孩子的档案
2. **情绪跟踪** - 记录和分析孩子的日常情绪变化
3. **行为训练** - 提供针对性的行为训练练习和游戏
4. **AI对话助手** - 为孩子提供沟通练习环境
5. **社区支持** - 家长之间的交流与经验分享平台
6. **专家资源** - 提供专业的文章、视频和活动推荐

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
- 更多个性化定制选项

## 联系方式

如有任何问题或建议，请联系项目维护团队。

---

© 2023星语助手项目组 版权所有

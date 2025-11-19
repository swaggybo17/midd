# 衣物回收再设计项目网站

一个基于环保理念的衣物回收再设计项目展示网站，旨在通过视觉冲击力和清晰的信息架构，引导用户参与旧衣回收、了解项目理念、使用积分系统，并通过透明化的公益流程建立用户信任。

## 项目特色

- 🌍 **环保价值** - 推动循环经济，减少纺织废料
- ❤️ **公益透明** - 全程可追踪的公益项目流程
- 🎨 **创意设计** - 专业设计师改造，展现可持续时尚
- 📱 **用户友好** - 响应式设计，支持多端访问
- 🔄 **积分系统** - 完整的积分获取和使用体系

## 功能模块

### 首页展示
- 轮播Banner展示项目核心价值
- 核心业务入口（体验店、循环市集）
- 项目理念和流程展示
- 行业痛点解决方案

### 参与系统
- 多种回收方式（线上预约、线下投递、社区回收点）
- 回收进度实时查询
- 积分获取和使用规则
- 积分计算器

### 公益展示
- 实际公益案例展示
- 行业参考案例
- 透明化公益流程

### 个人中心
- 用户信息管理
- 积分明细查看
- 捐赠历史记录
- 预约记录管理
- 公益动态更新

## 技术栈

- **前端**: HTML5, CSS3, JavaScript (ES6+)
- **样式**: 响应式设计，支持移动端
- **交互**: 原生JavaScript，无依赖框架
- **兼容性**: 现代浏览器支持

## 文件结构

```
├── index.html                 # 主页
├── personal-center.html       # 个人中心
├── styles/
│   ├── main.css              # 主样式文件
│   ├── components.css        # 组件样式
│   ├── personal-center.css   # 个人中心样式
│   └── responsive.css        # 响应式样式
├── scripts/
│   ├── main.js              # 主JavaScript文件
│   ├── personal-center.js   # 个人中心功能
│   └── components.js        # 组件功能
├── assets/
│   └── images/              # 图片资源
└── README.md
```

## 快速开始

1. **克隆项目**
   ```bash
   git clone [repository-url]
   cd clothing-recycling-website
   ```

2. **添加图片资源**
   - 参考 `assets/images/placeholder.txt` 文件
   - 添加对应的图片文件到 `assets/images/` 目录

3. **启动项目**
   - 使用本地服务器打开 `index.html`
   - 或直接在浏览器中打开文件

## 主要功能

### 导航系统
- 固定顶部导航栏
- 下拉菜单支持
- 搜索功能（实时建议）
- 快速操作按钮

### 轮播系统
- 自动轮播（3秒间隔）
- 鼠标悬停暂停
- 指示器点击切换
- 淡入淡出动画

### 表单系统
- 实时表单验证
- 模态窗口表单
- 文件上传支持
- 错误提示显示

### 积分系统
- 积分计算器
- 积分记录筛选
- 积分使用规则
- 到期提醒功能

### 个人中心
- 登录验证系统
- 多标签页切换
- 数据筛选功能
- 预约管理系统

## 响应式设计

网站采用移动优先的响应式设计：

- **手机端** (≤480px): 单列布局，简化导航
- **平板端** (481px-768px): 双列布局，优化触控
- **桌面端** (≥769px): 多列布局，完整功能

## 浏览器支持

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 开发指南

### 添加新功能
1. 在对应的HTML文件中添加结构
2. 在CSS文件中添加样式
3. 在JavaScript文件中添加交互逻辑

### 样式规范
- 使用BEM命名规范
- 移动优先的媒体查询
- CSS变量用于主题色彩

### JavaScript规范
- ES6+语法
- 模块化组织代码
- 事件委托优化性能

## 部署说明

### 静态部署
项目为纯静态网站，可部署到：
- GitHub Pages
- Netlify
- Vercel
- 任何静态文件服务器

### 生产优化
- 压缩CSS和JavaScript文件
- 优化图片格式和大小
- 启用Gzip压缩
- 配置CDN加速

## 贡献指南

1. Fork 项目
2. 创建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开 Pull Request

## 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 联系方式

- 项目维护者: [Your Name]
- 邮箱: [your.email@example.com]
- 项目链接: [https://github.com/yourusername/clothing-recycling-website]

## 更新日志

### v1.0.0 (2024-11-19)
- ✨ 初始版本发布
- 🎨 完整的UI设计和交互
- 📱 响应式布局支持
- 🔧 积分系统功能
- 👤 个人中心模块
- 📋 表单验证系统
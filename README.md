# 智能体配置原型系统

这是一个用于配置和管理数据库智能体的原型系统，包含完整的配置流程和界面原型。

## 功能特性

- 🚀 **新建智能体**: 配置基本信息、环境、数据服务类型等
- 📊 **表选择与字段配置**: 多选表、配置字段注释、AI注释生成
- 📝 **配置问题模板**: 自定义SQL问题模板和参数
- ⚙️ **构建配置表**: 定义文本替换、信息补充、SQL映射规则
- 🤖 **模型管理**: 查看、训练、部署AI模型
- 📈 **模型评测**: 测试模型效果，支持多测试集

## 在线演示

访问在线版本：[在线演示链接]

## 本地运行

1. 克隆仓库
```bash
git clone https://github.com/your-username/agent-config-prototype.git
cd agent-config-prototype
```

2. 使用本地服务器运行（避免CORS问题）
```bash
# 使用Python
python -m http.server 8000

# 使用Node.js
npx serve .

# 使用PHP
php -S localhost:8000
```

3. 在浏览器中访问 `http://localhost:8000`

## 页面说明

### 1. 新建智能体 (`create_agent.html`)
- 配置智能体基本信息
- 选择数据服务类型（MySQL、OceanBase、PostgreSQL等）
- 多选数据表名，支持搜索和全选

### 2. 表选择与字段配置 (`prototype_wireframe.html`)
- 选择数据库表
- 配置字段注释和AI注释
- 数据抽样和迁移功能

### 3. 配置问题模板 (`template_config.html`)
- 定义SQL问题模板
- 配置参数和描述
- 异步保存功能

### 4. 构建配置表 (`config_table.html`)
- 配置文本替换规则
- 信息补充规则
- SQL值映射规则
- 实时自动保存

### 5. 模型管理 (`model_management.html`)
- 查看模型列表和状态
- 训练和部署模型
- 选择生效模型

### 6. 模型评测 (`evaluate_model.html`)
- 上传测试集
- 评测模型效果
- 支持多测试集管理

## 技术栈

- **前端**: HTML5, CSS3, JavaScript (ES6+)
- **存储**: localStorage (本地存储)
- **样式**: 自定义CSS，响应式设计
- **兼容性**: 现代浏览器 (Chrome, Firefox, Safari, Edge)

## 部署说明

### GitHub Pages 部署

1. Fork 或克隆此仓库
2. 在仓库设置中启用 GitHub Pages
3. 选择部署分支 (main 或 gh-pages)
4. 访问生成的链接

### 其他平台部署

- **Vercel**: 连接GitHub仓库，自动部署
- **Netlify**: 拖拽部署或连接GitHub
- **腾讯云COS**: 上传文件到对象存储

## 协作开发

1. Fork 项目
2. 创建功能分支
3. 提交更改
4. 创建 Pull Request

## 注意事项

- 所有数据存储在浏览器的localStorage中
- 原型系统，生产环境需要后端支持
- 建议使用现代浏览器以获得最佳体验

## 许可证

MIT License

## 贡献

欢迎提交Issue和Pull Request！

## 联系方式

如有问题，请通过以下方式联系：
- 提交GitHub Issue
- 发送邮件至：[your-email@example.com]
# dbagent

# Agent Flow

智能代理工作流平台

## 功能特性

### 注册接口
- 用户名、邮箱、密码注册
- 实时邮箱格式校验
- 密码强度验证（至少8位）
- 密码显示/隐藏切换
- 注册成功/失败状态提示
- 防止重复提交

### API端点
- `POST /api/v1/register` - 用户注册接口

### 技术栈
- HTML5 + CSS3 + Vanilla JavaScript
- 响应式设计

## 开始使用

1. 打开 `index.html`
2. 填写注册表单
3. 点击"立即注册"按钮

## 开发说明

- 前端页面：`index.html`
- 样式文件：`styles.css`
- 注册页面需后端 `/api/v1/register` 接口支持
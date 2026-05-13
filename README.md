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

### 健康检查
- 实时监控 Coyle2019/agent-test 服务状态
- 自动获取 /healthz 接口数据
- 显示加载中、成功、错误状态
- 支持手动刷新检测
- 显示最后检查时间

### API端点
- `POST /api/v1/register` - 用户注册接口
- `GET /healthz` (Coyle2019/agent-test) - 服务健康检查接口

### 技术栈
- HTML5 + CSS3 + Vanilla JavaScript
- 响应式设计

## 页面导航

- `index.html` - 用户注册页面
- `health.html` - 服务健康检查页面

## 开始使用

### 注册账号
1. 打开 `index.html`
2. 填写注册表单
3. 点击"立即注册"按钮

### 健康检查
1. 打开 `health.html`
2. 页面自动检测服务状态
3. 点击"Check Again"按钮可手动刷新

## 开发说明

- 前端页面：`index.html`、`health.html`
- 样式文件：`styles.css`
- 注册页面需后端 `/api/v1/register` 接口支持
- 健康检查页面调用 Coyle2019/agent-test 的 `/healthz` 接口
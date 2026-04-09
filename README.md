# OpenClaw Config Editor

一个可视化的 JSON 配置编辑器，将 JSON 数据转换为交互式表单，便于编辑和管理 OpenClaw 配置。

## 功能特点

- **中英文切换** - 支持中文和英文界面切换
- **直观的表单编辑** - 将复杂的 JSON 结构转换为易于理解的表单
- **重点字段突出** - 加大重要字段的字号，便于识别
- **详细的字段说明** - 为重要字段提供详细的功能说明
- **语法高亮输出** - 支持格式化、压缩和高亮三种输出格式

## 新增特性 (v1.2.0)

1. **提供中英文切换按钮**
   - 界面右上角添加了中英文切换按钮
   - 支持动态语言切换，无需刷新页面

2. **去除不必要字段，让页面更直观**
   - 隐藏了一些内部状态字段（如 lastTouchedVersion, lastRunAt 等）
   - 优化了字段布局，提升用户体验

3. **加大重点字段字号**
   - 对于关键配置项（如 enabled, streaming, model, provider 等）使用更大的字体
   - 通过视觉层次突出重要配置

4. **对重点字段编写字段说明**
   - 为常用配置项提供了详细的中文和英文说明
   - 帮助用户更好地理解每个字段的作用

## 使用方法

1. 将 JSON 配置粘贴到输入框中
2. 点击"解析并生成表单"按钮
3. 在表单中编辑所需配置
4. 点击"生成 JSON"获取更新后的配置
5. 可选择复制或下载最终的 JSON 文件

## 字段说明

以下是一些重要的配置字段及其说明：

### 服务器配置
- `server.enabled` - 是否启用服务器
- `server.streaming` - 是否开启流式输出
- `server.port` - 服务器监听端口
- `server.host` - 服务器绑定的主机地址

### 模型配置
- `model.provider` - AI 模型提供商
- `model.id` - 模型标识符
- `model.contextWindow` - 上下文窗口大小
- `model.maxTokens` - 单次响应最大 token 数

### 认证配置
- `auth.mode` - 认证模式
- `auth.apiKey` - API 密钥

## English Features (v1.2.0)

1. **Bilingual Support** - Added Chinese/English toggle button
2. **Cleaner Interface** - Removed unnecessary fields for better clarity
3. **Enhanced Important Fields** - Increased font size for key configuration items
4. **Detailed Field Descriptions** - Added comprehensive explanations for important fields

## Usage

1. Paste your JSON configuration in the input area
2. Click "Parse & Build Form" button
3. Edit the desired configurations in the form
4. Click "Generate JSON" to get the updated configuration
5. Choose to copy or download the final JSON file

## License

MIT
# AI大模型与深度学习实践项目

本项目包含了多个AI大模型的实际应用示例，涵盖情感分析、运维事件处置、表格提取、天气查询等功能。

## 项目结构

- `01-情感分析-QWEN.ipynb` - 使用QWEN模型进行情感分析
- `02-天气functioan-Qwen.ipynb` - 使用QWEN模型实现天气查询功能
- `03-表格提取-Qwen.ipynb` - 使用QWEN模型进行表格数据提取
- `04-运维事件处置-Qwen.ipynb` - 使用QWEN模型处理运维事件
- `05-情感分析-deepseek阿里代理.ipynb` - 使用DeepSeek模型进行情感分析
- `06-deepseek部署.ipynb` - DeepSeek模型的部署指南

## 环境要求

- Python 3.8+
- Jupyter Notebook 或 JupyterLab
- 相关依赖包（见 requirements.txt）

## 安装步骤

1. 克隆项目到本地：
```bash
git clone https://github.com/yourusername/ai-models-practice.git
cd ai-models-practice
```

2. 安装依赖：
```bash
pip install -r requirements.txt
```

3. 配置API密钥：
   - 设置环境变量 `DASHSCOPE_API_KEY` 为你的阿里云DashScope API密钥
   - 设置其他相关API密钥（根据使用的模型）

4. 启动Jupyter Notebook：
```bash
jupyter notebook
```

## 功能介绍

### 情感分析
- 支持QWEN和DeepSeek两种模型
- 能够识别文本的情感倾向（正向/负向）

### 运维事件处置
- 智能分析运维事件
- 提供处置建议和解决方案

### 表格提取
- 从非结构化文本中提取表格数据
- 智能识别和格式化表格内容

### 天气查询
- 基于Function Calling实现天气查询
- 支持多地区天气信息获取

## 注意事项

- 请确保API密钥的安全性，不要将其提交到代码仓库
- 使用前请先测试API连接是否正常
- 建议在虚拟环境中运行项目

## 贡献指南

欢迎提交Issue和Pull Request来改进项目。

## 许可证

MIT License 
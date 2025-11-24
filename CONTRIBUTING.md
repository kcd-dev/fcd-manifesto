# 贡献指南

感谢您对 FCD Manifesto 项目的关注！我们欢迎各种形式的贡献。

## 🎯 贡献方式

### 1. 提交新的 FCD 示例

我们鼓励您分享成功的功能收敛文档案例：

```bash
# 1. Fork 本仓库
# 2. 创建功能分支
git checkout -b add-example/your-feature-name

# 3. 在 examples/ 目录下创建您的文档
cp TEMPLATE.md examples/your-feature-name.md
# 或使用简化版
cp TEMPLATE-SIMPLE.md examples/your-feature-name.md

# 4. 编写您的 FCD 文档
vim examples/your-feature-name.md

# 5. 提交更改
git add examples/your-feature-name.md
git commit -m "Add FCD example: your-feature-name"

# 6. 推送到您的 Fork
git push origin add-example/your-feature-name

# 7. 创建 Pull Request
```

### 2. 改进模板

如果您有更好的模板结构建议：

- 修改 `TEMPLATE.md` 或 `TEMPLATE-SIMPLE.md`
- 在 PR 中说明改进的理由
- 提供使用示例

### 3. 完善文档

- 改进 README.md
- 添加最佳实践
- 翻译文档（英文、日文等）
- 修复错误和拼写问题

### 4. 开发工具

如果您想为 FCD 开发配套工具：

- CLI 工具（生成、验证、统计）
- IDE 插件（VSCode、Cursor 等）
- CI/CD 集成工具

请在 `tools/` 目录下创建子项目。

## 📋 提交要求

### 文档质量标准

1. **完整性**: 包含所有必需章节
2. **真实性**: 基于实际项目经验
3. **可读性**: 清晰的结构和说明
4. **可复用性**: 其他人能够参考使用

### 提交信息格式

```
<type>: <subject>

<body>

<footer>
```

**Type 类型**:
- `feat`: 新增示例或功能
- `docs`: 文档改进
- `fix`: 修复错误
- `refactor`: 模板重构
- `style`: 格式调整
- `test`: 测试相关

**示例**:
```
feat: Add user authentication FCD example

- 完整的用户认证功能收敛文档
- 包含 OAuth 2.0 实现细节
- 测试覆盖率达 95%

Closes #123
```

## ✅ Pull Request 检查清单

提交 PR 前，请确认：

- [ ] 文档遵循模板结构
- [ ] 代码示例可运行（如有）
- [ ] 链接都是有效的
- [ ] Markdown 格式正确
- [ ] 没有敏感信息（密钥、密码等）
- [ ] 提交信息清晰明确

## 🎨 文档风格指南

### 标题层级

```markdown
# H1 - 文档标题（仅一个）
## H2 - 主要章节
### H3 - 子章节
#### H4 - 详细说明
```

### 代码块

使用语言标识：

````markdown
```bash
npm install
```

```typescript
const example = 'code';
```
````

### 表情符号使用

我们使用表情符号来增强可读性：

- 📋 概述
- 🛠️ 技术
- 📊 数据
- ✅ 测试
- 🐛 问题
- 📚 依赖
- 🎯 成功要素
- 📖 使用文档
- 🔄 维护
- 🔟 完成

### 链接格式

- 相对链接：`[示例](./examples/example.md)`
- 绝对链接：`[文档](https://example.com/docs)`
- 锚点链接：`[章节](#section)`

## 🤝 社区规范

### 行为准则

- **尊重**: 尊重所有贡献者
- **建设性**: 提供建设性的反馈
- **包容**: 欢迎不同背景的贡献者
- **耐心**: 对新手友好

### 代码审查

- 审查者应在 **3 个工作日**内回复
- 提出具体的改进建议
- 认可贡献者的努力

### 讨论礼仪

- 保持专业和友好
- 专注于技术问题
- 避免人身攻击
- 尊重不同观点

## 📊 贡献者统计

我们会在 README 中展示活跃贡献者。

## 🙋 需要帮助？

- 💬 [GitHub Discussions](https://github.com/kcd-dev/fcd-manifesto/discussions)
- 🐛 [Issues](https://github.com/kcd-dev/fcd-manifesto/issues)
- 📧 Email: [维护者邮箱]

## 📄 许可证

通过贡献代码，您同意您的贡献将在 MIT 许可证下发布。

---

感谢您的贡献！🎉

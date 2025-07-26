# 🚀 保险考试刷题平台

> 一个功能完整的保险考试在线刷题系统，支持多题库练习、会员管理、移动端适配

## 🌐 在线访问

**网站地址**: [https://你的用户名.github.io/insurance-exam](https://你的用户名.github.io/insurance-exam)

## 📱 功能特色

✅ **5个考试题库** - 覆盖保险行业各类考试  
✅ **智能刷题** - 随机出题，避免记忆答案位置  
✅ **会员系统** - 订阅制度，支持微信支付  
✅ **设备绑定** - 防止账号滥用，保护内容版权  
✅ **移动优化** - 手机、平板完美适配  
✅ **数据同步** - 云端存储，多设备同步  
✅ **管理后台** - 题库管理、用户管理、数据统计  

## 🏗️ 技术架构

- **前端**: React 18 + TypeScript + Tailwind CSS
- **后端**: Supabase (PostgreSQL + Edge Functions)
- **认证**: Supabase Auth + 设备指纹
- **支付**: 微信支付 + 管理员审核
- **部署**: GitHub Pages

## 📁 项目结构

```
📁 insurance-exam/
├── index.html              # 主页面
├── assets/
│   ├── index-*.css         # 样式文件  
│   └── index-*.js          # JavaScript逻辑
├── wechat-payment.jpg      # 微信支付二维码
├── wechat-payment.png      # 支付图片
└── README.md              # 项目说明
```

## 🎯 用户指南

### 📝 如何使用

1. **注册账号** - 邮箱注册，系统自动绑定设备
2. **选择题库** - 5个不同难度的题库可选
3. **开始练习** - 随机出题，实时显示答题进度
4. **查看统计** - 答题数量、正确率、学习进度
5. **升级会员** - 解锁更多功能和题库

### 💳 会员权益

| 功能 | 免费用户 | 会员用户 |
|------|---------|----------|
| 每日答题数量 | 20题 | 无限制 |
| 题库访问 | 基础题库 | 全部题库 |
| 错题重做 | ❌ | ✅ |
| 学习统计 | 基础 | 详细图表 |
| 离线使用 | ❌ | ✅ |

### 📱 支持的设备

- **桌面端**: Chrome, Firefox, Safari, Edge
- **移动端**: iOS Safari, Android Chrome
- **平板**: iPad, Android 平板
- **响应式**: 自适应各种屏幕尺寸

## 🔧 部署说明

### GitHub Pages 部署

1. Fork 或下载本仓库
2. 在 Settings → Pages 中启用 GitHub Pages
3. 选择 Deploy from a branch: main
4. 等待几分钟即可访问

### 本地开发

```bash
# 克隆仓库
git clone https://github.com/your-username/insurance-exam.git
cd insurance-exam

# 本地服务器（可选）
npx serve .
# 或使用 Python
python -m http.server 8000
```

## 🛡️ 安全特性

- **设备绑定**: 防止账号共享滥用
- **数据加密**: 用户信息安全存储
- **支付安全**: 微信支付 + 人工审核
- **API 安全**: JWT 认证 + 权限控制

## 📊 系统监控

- **用户数据**: Supabase Dashboard
- **错误监控**: 实时错误追踪
- **性能分析**: 网站访问统计
- **支付记录**: 完整的财务记录

## 📈 版本历史

### v1.0.0 (2025-07-26)
- ✅ 初始版本发布
- ✅ 5个题库完整集成
- ✅ 会员系统上线
- ✅ 移动端优化完成
- ✅ GitHub Pages 部署支持

## 🤝 贡献指南

### 反馈问题
- [Issues](https://github.com/your-username/insurance-exam/issues) - 报告问题或建议
- [Discussions](https://github.com/your-username/insurance-exam/discussions) - 社区讨论

### 功能建议
欢迎提出以下类型的改进建议：
- 新题库添加
- 用户体验优化
- 新功能开发
- 性能优化

## 📄 许可证

本项目仅供学习和个人使用，商业使用请联系开发者。

## 🙏 致谢

- **Supabase** - 提供后端服务
- **React** - 前端框架
- **Tailwind CSS** - 样式框架
- **GitHub Pages** - 免费托管

## 📞 联系方式

- **问题反馈**: [GitHub Issues](https://github.com/your-username/insurance-exam/issues)
- **功能建议**: [GitHub Discussions](https://github.com/your-username/insurance-exam/discussions)
- **技术支持**: 通过 Issues 联系

---

### 🌟 如果这个项目对您有帮助，请给个 Star！

**开发者**: MiniMax Agent  
**最后更新**: 2025-07-26  
**许可证**: MIT License
"
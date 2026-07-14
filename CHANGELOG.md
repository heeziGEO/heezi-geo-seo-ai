# 更新日志

所有重要更新记录在此文件中。

---

## [1.0.0] - 2026-07-14

### 🎉 首次发布

#### 核心功能
- ✅ **首页测评**：输入域名，一键生成 6 大维度 49 项指标的评测报告
- ✅ **整站测评**：从 sitemap 抓取 URL，智能采样，批量评测整站页面
- ✅ **REST API**：Bearer Token 鉴权 + 限速 + 异步排队
- ✅ **AI 文章生成**：自动生成 2000-3000 字 SEO/GEO 技术文章
- ✅ **标签系统**：文章标签聚合页 + 标签详情页
- ✅ **排行榜**：各行业网站 GEO/SEO 评分排行
- ✅ **用户系统**：注册/登录/我的评测
- ✅ **评测案例**：公开评测列表，可查看他人评测结果

#### 检测维度（49 项指标）
- 🤖 AEO（AI 引擎可见性）— 7 维度，权重 25%
- ✨ GEO（生成式引擎优化）— 5 维度，权重 25%
- 🔍 SEO（搜索引擎优化）— 10 维度，权重 20%
- 🧠 语义质量 — 9 维度，权重 15%
- 🏅 权威度 — 9 维度，权重 10%
- 📚 语料库质量 — 9 维度，权重 5%

#### GEO/SEO 优化
- ✅ robots.txt 放行 44+ AI 爬虫（GPTBot/ClaudeBot/DeepSeekBot/QwenBot 等）
- ✅ llms.txt 部署（含 API 端点、企业 NAP、FAQ、内容许可声明）
- ✅ Schema.org JSON-LD 结构化数据（WebSite/Organization/FAQPage/BreadcrumbList 等）
- ✅ Sitemap.xml 自动拆分子索引（静态/文章/报告/标签）
- ✅ Open Graph + Twitter Card 完整部署
- ✅ 全站 BreadcrumbList 面包屑导航
- ✅ 8 个主要页面独立 Meta Keywords
- ✅ Core Web Vitals 移动端响应式设计

#### API 端点
- `POST /api/v1/analyze` — 提交首页测评
- `GET /api/v1/analyze/status/<task_id>` — 查询首页测评状态
- `GET /api/v1/report/<domain>` — 获取最新首页报告
- `POST /api/v1/fullsite-audit` — 提交整站测评
- `GET /api/v1/fullsite-audit/status/<audit_id>` — 查询整站状态
- `GET /api/v1/fullsite-audit/report/<audit_id>` — 获取整站报告
- `POST /api/v1/api-keys` — 创建 API Key
- `GET /api/v1/api-keys` — 列出 API Keys
- `GET /api/v1/info` — API 信息

---

🔗 **官网**：[https://www.heezi.cn](https://www.heezi.cn)

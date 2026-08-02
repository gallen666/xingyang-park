# 荥阳数字经济产业园官网 · URL 与目录规范 v2.0

> Sprint 1 · 强制执行 · 所有新页面必须遵守 · 现有页面渐进迁移

---

## 目录约定

```
xingyang-v2/
├── index.html                          # 主门户（重构自 xingyang-digital-park/index.html）
├── assets/
│   └── css/tokens.css                  # 全站唯一设计系统
├── platforms/                          # 平台级 IP（Cobalt/Topaz 级别）
│   ├── index.html                      # 平台总览
│   ├── dtsi.html                       # DTSI · 七方35指标数字化诊断体系
│   ├── xflow.html                      # X-Flow Dynamics · 全流程流量动力学
│   ├── pdtmm.html                      # PDTMM · 数字化转型五级认证
│   └── openxx.html                     # OpenX@X · 开放开发者社区
├── services/                           # 8 大运营服务（Infosys BPM 6-tab 模板）
│   ├── index.html                      # 服务矩阵总览
│   ├── policy.html                     # 政策申报
│   ├── financing.html                  # 融资对接
│   ├── recruitment.html                # 人才招引
│   ├── space.html                      # 空间定制
│   ├── investment.html                 # 招商合作
│   ├── supply-chain.html               # 产业链撮合
│   ├── it-cloud.html                   # IT & 云
│   └── legal.html                      # 法律咨询
├── sub-brands/                         # 4 大数字子品牌（Edgeverve 12 段模板）
│   ├── index.html                      # 子品牌矩阵
│   ├── yunxi-shu.html                  # 荥数云
│   ├── yunxi-zhi.html                  # 荥智造
│   ├── yunxi-lian.html                 # 荥数链
│   └── yunxi-cai.html                  # 荥数才
├── insights/                           # 洞察中心（IKI 微站）
│   ├── index.html                      # 洞察 hub（3 维过滤）
│   ├── methodology-openxx.html         # 拆自 openxx-platform 的短文
│   ├── dtsi-seven-parties.html
│   └── ... （12-16 篇短洞察）
├── cases/                              # 案例中心（命名客户故事）
│   ├── index.html                      # 案例总览（双轴过滤）
│   ├── dahua.html                      # 大华股份
│   ├── ucloud.html                     # 优刻得
│   ├── johnson-controls.html           # 江森自控
│   ├── shengrun.html                   # 森赫
│   ├── newcapec.html                   # 新开普
│   └── dbappsecurity.html              # 安恒
├── newsroom/                           # 新闻室 + 记者素材
│   ├── index.html
│   ├── wechat-archive.html             # 微信公众号内容库
│   ├── wechat-archive.json             # 公众号内容库结构化数据
│   ├── wechat-news.json                # 新闻页最新公众号内容数据
│   ├── wechat/
│   │   ├── investment.html             # 公众号招商原文全文
│   │   ├── zhengxi-new-highland.html   # 郑西数字经济新高地全文
│   │   └── corporate-culture.html      # 企业文化全文
│   ├── press-releases/
│   └── media-kit.html
├── about/                              # 三方治理 + 团队
│   ├── index.html                      # 关于我们（含三方 lock-up）
│   ├── leadership.html                 # 公开信息核验
│   ├── governance.html                 # 七方共治
│   └── timeline.html                   # 里程碑时间线
├── boards/                             # 现有 5 个板块页（保持向后兼容）
│   ├── onboarding.html                 # ← 从 xingyang-digital-park 迁入
│   ├── enterprise-workspace.html
│   ├── smart-park-ops.html
│   ├── industrial-ecosystem.html
│   └── admin-console.html
└── legacy/                             # 原 openxx-platform 保留
    └── openxx-platform.html
```

## URL 规范

- 全部使用 `.html` 后缀（不隐藏）
- 全部小写、连字符分隔（`kebab-case`）
- 目录 index 页用 `/[dir]/` 或 `/[dir]/index.html`
- 中文品牌名用拼音（`yunxi-shu`）不用汉字 URL
- 案例：`/cases/dahua.html` 不做嵌套子目录（首批规模<20 个）

## 主导航（mega-nav）7 顶级栏目

| 顶级栏目 | 链接 | 定位 |
|---|---|---|
| **平台** | `/platforms/` | 4 个平台级 IP（v2.0 核心） |
| **服务** | `/services/` | 8 大运营服务 |
| **数字生态** | `/sub-brands/` | 4 大数字子品牌 |
| **案例** | `/cases/` | 命名客户故事 |
| **洞察** | `/insights/` | 思想领导力 |
| **新闻** | `/newsroom/` | 动态 · 政策速递 · 媒体 |
| **关于我们** | `/about/` | 三方治理 · 公开信息核验 · 里程碑 |

## 子导航模板

**Board 页（5 个原有板块）**：概览 · 服务矩阵 · 客户故事 · 洞察 · 联系
**Platform 页**：概览 · 架构 · 应用场景 · 认证/培训 · 团队 · 下载
**Service 页**（Infosys BPM 6-tab）：首页 · 概览 · 洞察 · 客户故事 · 服务清单 · 博客
**Sub-brand 页**（Edgeverve 12 段单页）：单页锚点导航

## 内容 chip 标签词汇（8 类）

政策 · 案例 · 报告 · 活动 · 洞察 · 视频 · 白皮书 · 新闻

## 商标声明

如下 5 个平台/方法论已建议注册商标（需 IP 律师复核）：
- DTSI®
- X-Flow Dynamics™
- PDTMM® 五级认证
- OpenX@X™
- 荥泽招商飞轮®

## 三方 lock-up（每页 footer 必现）

```
荥阳市人民政府 · 荥阳城投 · 太能控股
运营主体：郑州荥泽数链产业发展有限公司
```

## 迁移策略

1. **Sprint 1（本轮）**：生成新架构 + 新页面；旧目录 xingyang-digital-park/ 保留
2. **Sprint 5-8**：现有 5 板块页统一 5-tab 导航，逐步迁到 `/boards/`
3. **Sprint 9-12**：openxx-platform 内容拆到 `/insights/` 各短文；旧文件进 `/legacy/`
4. **Sprint 13+**：全站英文版 `/en/*.html`

## 部署路径

站点根路径可为：
- `https://openflowone.hk/xingyang/` （当前）
- 或独立域名 `https://xingyang.gov.cn/` / `https://park.xy.gov.cn/`

所有内部链接均为相对路径（`./`、`../`），不绑定域名。

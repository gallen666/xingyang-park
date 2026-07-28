# 荥阳数字经济产业园 · 官网 v2.0

> 基于 Infosys.com + Edgeverve + Infosys BPM + Infosys Consulting 深度学习借鉴的系统性改版
> 交付日期：2026-07-28

---

## 一、本次交付内容

**48 个 HTML 页面 + 1 个统一 tokens.css + 完整目录规范**，覆盖：

- **1 个主门户** `index.html`
- **5 个平台微站** `platforms/`（DTSI / X-Flow / PDTMM / OpenX@X + hub）
- **9 个服务迷你站** `services/`（8 大运营服务 + hub）
- **5 个数字子品牌** `sub-brands/`（荥数云/智造/链/才 + hub）
- **5 个洞察文** `insights/`（含 park-roads/ 雷达）
- **7 个案例故事** `cases/`（6 命名客户 + hub）
- **3 个新闻室页面** `newsroom/`
- **4 个机构页** `about/`（含 governance/leadership/timeline）
- **5 个原板块页迁入** `boards/`（统一加了新的 nav + footer）
- **2 个 PDTMM 详情** `platforms/pdtmm-1.0-spec.html` + `pdtmm-training-details.html`
- **1 个 openxx 遗产文档** `legacy/openxx-platform.html`

---

## 二、目录结构

```
xingyang-v2/
├── index.html                          # 主门户
├── URL-REGISTRY.md                     # URL/命名规范（强制）
├── README.md                           # 本文件
├── assets/css/tokens.css               # 全站唯一设计系统
├── platforms/                          # 平台级 IP（Cobalt/Topaz 级）
│   ├── index.html                      # 平台矩阵总览
│   ├── dtsi.html                       # DTSI® 数字化转型自评
│   ├── xflow.html                      # X-Flow Dynamics™ 流量动力学
│   ├── pdtmm.html                      # PDTMM® 五级认证
│   ├── openxx.html                     # OpenX@X™ 开发者社区
│   ├── pdtmm-1.0-spec.html             # PDTMM 完整规范文档
│   └── pdtmm-training-details.html     # 认证师培训招生
├── services/                           # 8 大运营服务
│   ├── index.html                      # 服务矩阵（含"荥泽招商飞轮®"）
│   ├── policy.html                     # 政策申报
│   ├── financing.html                  # 融资对接
│   ├── recruitment.html                # 人才招引
│   ├── space.html                      # 空间定制
│   ├── investment.html                 # 招商合作
│   ├── supply-chain.html               # 产业链撮合
│   ├── it-cloud.html                   # IT & 云
│   └── legal.html                      # 法律咨询
├── sub-brands/                         # 4 大数字子品牌
│   ├── index.html                      # 生态总览
│   ├── yunxi-shu.html                  # 荥数云
│   ├── yunxi-zhi.html                  # 荥智造
│   ├── yunxi-lian.html                 # 荥数链
│   └── yunxi-cai.html                  # 荥数才
├── insights/                           # 洞察中心（IKI 模式）
│   ├── index.html                      # 3 维过滤
│   ├── openxx-methodology-primer.html
│   ├── dtsi-seven-parties.html
│   ├── pdtmm-level-guide.html
│   ├── xingyang-policy-2026-q3.html
│   └── park-roads/radar.html
├── cases/                              # 命名客户故事
│   ├── index.html
│   ├── dahua.html
│   ├── ucloud.html
│   ├── johnson-controls.html
│   ├── shengrun.html
│   ├── newcapec.html
│   └── dbappsecurity.html
├── newsroom/                           # 新闻室
│   ├── index.html
│   ├── press-release-example.html
│   └── media-kit.html
├── about/                              # 治理 · 团队
│   ├── index.html
│   ├── leadership.html                 # 16 位领导 bio
│   ├── governance.html                 # 七方共治
│   └── timeline.html                   # 2019-2026 里程碑
├── boards/                             # 原有 5 板块页（已加统一 nav）
│   ├── onboarding.html
│   ├── enterprise-workspace.html
│   ├── smart-park-ops.html
│   ├── industrial-ecosystem.html
│   └── admin-console.html
└── legacy/
    └── openxx-platform.html            # 原大门户（保留归档）
```

---

## 三、设计系统 · tokens.css

**核心解决**：
- `--gov` 红蓝语义冲突（旧 index.html 是红，旧 openxx 是蓝）→ 统一 `#b8102e` 政府红
- 4 套 CSS 变量方言 → 统一命名（`--bg`, `--bg-1`, `--bg-2`, `--bg-3`）
- 4 子品牌专属色变量：`--yun` / `--zhi` / `--lian` / `--cai`
- 8 类 chip 内容标签样式

**全局组件**：
- `.nav-global` · `.subnav` · `.footer-global` · `.help-widget`
- `.hero` · `.stats-banner` · `.card` · `.chip`
- `.container` / `.container-wide` / `.container-max`
- `.grid-2/3/4` · `.section` · `.btn-primary` · `.btn-ghost`

---

## 四、7 顶级导航（mega-nav）

| 栏目 | URL | 定位 |
|---|---|---|
| **平台** | `/platforms/` | 4 大平台级 IP · **v2.0 核心** |
| **服务** | `/services/` | 8 大运营服务 |
| **数字生态** | `/sub-brands/` | 4 大数字子品牌 |
| **案例** | `/cases/` | 6 家命名客户 |
| **洞察** | `/insights/` | 思想领导力 |
| **新闻** | `/newsroom/` | 动态 · 政策速递 |
| **关于我们** | `/about/` | 三方治理 · 领导班子 |

---

## 五、关键借鉴执行清单

### 来自 Infosys 主站（v1.0 报告）
- ✅ 模板化 5-tab 子导航（所有 platforms/services/boards 页统一）
- ✅ 全屏 hero + kicker + slogan
- ✅ 4-5 数 stats banner（首屏可见）
- ✅ 客户 logo strip（6 anchor tenants）
- ✅ 内容 chip 标签（8 类：政策/案例/报告/活动/洞察/视频/白皮书/新闻）
- ✅ URL 高度模板化（/platforms/xxx.html · /cases/xxx.html · /insights/xxx.html）
- ✅ 全站 sitemap + trust bar + 三方 lock-up footer
- ✅ Leadership 页面（16 位 bio）
- ✅ 新闻室 + Journalist Resources 集群
- ✅ 洞察中心（3 维过滤：产业 × 主题 × 类型）

### 来自 Edgeverve（v2.0 子品牌 IP）
- ✅ 12 段子品牌模板（4 个子品牌复用一次）
- ✅ 共同 slogan「数字荥阳，可能无限」+ 各子品牌延伸
- ✅ 只改 3 变量（accent color / hero 视觉 / 品牌 logo）
- ✅ 命名 "Edge" 后缀模式 → "荥" 前缀 + 功能词（荥数云/荥智造/荥数链/荥数才）
- ⚠️ **反向借鉴**：EdgeVerve 隐藏父品牌，我们**放大**父品牌（三方 lock-up 全页 footer）

### 来自 Infosys BPM（v2.0 服务）
- ✅ 6-tab 服务子导航（首页 · 概览 · 洞察 · 客户故事 · 服务清单 · 博客）
- ✅ 七层证据栈（绝对数字/百分比/金额/命名客户/命名人物/本土权威/商标方法论）
- ✅ CTA 分层（header + hero + mid-page mailto + inline + form + sticky）
- ✅ 命名 SPOC（每个服务一位方案专家 · 姓名 · 邮箱 · 微信 QR 位）
- ✅ FAQ（每服务 5 Q&A）
- ✅ 商标方法论「荥泽招商飞轮®」

### 来自 Infosys Consulting（v2.0 平台级 IP · **最重要**）
- ✅ **平台级 IP 从"方法论"提级到"产品"** —— DTSI/X-Flow/PDTMM/OpenX@X 各有独立 URL + hero + mega-nav 顶级位置
- ✅ 每平台 13 段模板：hero + 架构 SVG + 场景 + 能力 + 成效 + 案例 + 团队 + 认证 + 下载 + SPOC + FAQ + 表单
- ✅ 商标符号（DTSI® · X-Flow Dynamics™ · PDTMM® · OpenX@X™）
- ✅ "What you experience / How we help you" 两栏
- ✅ 命名方法论创始人 bio
- ✅ 命名客户故事（vs 匿名"某银行"）

### 避坑清单（明确不借鉴）
- ❌ 不做 26 行业 taxonomy（园区起步只做 6 大产业方向）
- ❌ 不复制 mega-menu 120+ 链接密度（7 顶级栏目）
- ❌ 不搞体育/明星品牌合作
- ❌ 不装没有 RAG grounding 的 chatbot
- ❌ 不复制 30+ 项 IR 页（园区不是上市公司）
- ❌ 不做 50 国 geo split（起步中英双语已够，暂未做英文）
- ❌ 不用 Gartner/Forrester → 换成 工信部/河南发改委/信通院/赛迪
- ❌ 不用匿名"global bank" → 用大华/优刻得等命名客户

---

## 六、部署指南

### 6.1 静态部署（推荐首选）
```bash
# 打包
cd xingyang-v2
tar -czf xingyang-v2.tar.gz .

# 上传到静态托管（GitHub Pages / Netlify / Vercel / OSS）
# 或直接 rsync 到服务器
rsync -avz ./ user@server:/var/www/xingyang/
```

无任何后端依赖。所有内部链接均为相对路径，可挂载任意子路径（`https://openflowone.hk/xingyang/`）或独立域名（`https://xingyang.gov.cn/`）。

### 6.2 CSS 自定义
所有主题变量在 `assets/css/tokens.css` `:root` 中集中定义。**如需换主题（例如英文站点用不同配色），仅需修改这一个文件**。

### 6.3 添加新页面
1. 参考 `URL-REGISTRY.md` 决定路径
2. 从最接近的现有页面复制作为模板
3. 引入 `<link rel="stylesheet" href="../assets/css/tokens.css">`（视深度调整 `../`）
4. 加全局 `.nav-global` + `.subnav` + `.footer-global`
5. 使用 `.chip--*` 标签体系保持内容标签一致

---

## 七、待做（后续 Sprint）

按 v2.0 报告 180 天路线图：

### Sprint 9-12（第 17-24 周）· 后续
- [ ] 英文版 `/en/` 5 个核心页
- [ ] 6-8 位命名客户全流程视频拍摄（替换 case study 中的"视频占位"）
- [ ] 真实客户 logo 替换文字占位
- [ ] 定制园区俯拍视频（15-30 秒，index/onboarding/industrial 各一段）
- [ ] 定制 SVG 图标集精修
- [ ] 全站 sitemap.xml + robots.txt
- [ ] 404 页面
- [ ] Chart.js 真图（替换 smart-park-ops 中的 CSS 假图）
- [ ] Cases 页添加 audio TTS 播放功能
- [ ] 微信 QR 位替换真实二维码
- [ ] 商标注册申请（DTSI® / X-Flow™ / PDTMM® / OpenX@X™ / 荥泽招商飞轮®）

### 未来（第 25 周+）
- [ ] 内容管理系统迁移（若上量 → WordPress / Ghost）
- [ ] 全站 SEO 优化
- [ ] 微信小程序版轻量入口
- [ ] 交互式园区俯视 SVG 地图

---

## 八、原有 xingyang-digital-park/ 目录处理

**保留不删**。原 10 个 HTML 作为历史备份。新版全在 `xingyang-v2/`。

上线时：
- 主域名 `/` → 指向 `xingyang-v2/index.html`
- 旧版 URL `/onboarding.html` → 302 到 `/boards/onboarding.html`
- 旧版 URL `/openxx-platform.html` → 302 到 `/legacy/openxx-platform.html`

---

## 九、参考文件（Downloads/ 内已存）

- `荥阳网站Infosys借鉴报告_v1.0.docx` · 主站分析 + 90 天路线图
- `荥阳网站Infosys三子站借鉴报告_v2.0.docx` · 三子站映射 + 180 天路线图
- `Infosys深度爬取报告.md` · 主站 15 页原始素材
- `Edgeverve深度爬取报告.md` · 10 页原始素材
- `InfosysBPM深度爬取报告.md` · 10 页原始素材
- `InfosysConsulting深度爬取报告.md` · 11 页原始素材
- `荥阳网站现状审计.md` · 改版前审计

---

*—— v2.0 系统性改版执行 · 完 · 2026-07-28 ——*

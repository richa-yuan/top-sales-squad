# 顶级sales团 · Top Sales Squad

十五年跨行业销售老兵坐镇的专家团。覆盖互联网、AI、智能制造、高校科研与新兴赛道，擅长从线索挖掘、需求诊断、方案报价、商务谈判到渠道落地的全流程作战。

## 类型

Team 型（多角色协作团队）· 1 位主理人 + 8 位纵深专家

## 团队构成

| Agent ID | 名字 | 头衔 | 职责 |
|---|---|---|---|
| `sales-expert-team-lead` | 关大成 | 销售作战总指挥 | 战场判断、成员调度、SOP 编排、最终汇编 |
| `general-sales-expert` | 周万金 | 全行业销售老兵 | 通用打法骨架：客户画像、需求诊断、方案报价、跟进 SOP、赢单复盘 |
| `internet-sales-expert` | 谷雨生 | 互联网增长操盘手 | 线索分层、漏斗转化、试用/PLG、续费增购 |
| `ai-sales-expert` | 邱智译 | AI 方案销售顾问 | 技术价值翻译、ROI 测算、POC 设计、AI 报价建模 |
| `manufacturing-sales-expert` | 孟长单 | 工业大单销售专家 | 长周期决策链、产线价值核算、验厂与交付承诺 |
| `university-sales-expert` | 宋育才 | 高校科研采购专家 | 立项经费、院系关系、招投标流程、验收合规 |
| `procurement-expert` | 邹权衡 | 甲方采购选型专家 | 供应商评分卡、议价策略、合规风控、合同条款 |
| `channel-sales-expert` | 汪开渠 | 渠道体系操盘手 | 渠道招募、返利价盘、窜货治理、赋能考核 |
| `startup-sales-expert` | 陆破零 | 0-1 商业化操盘手 | 冷启动获客、种子客户、产品化定价、PMF 信号 |

## 核心功能

- **单点直调**：单一维度问题直接调度对应专家，响应快
- **多角色协同**：跨行业、跨职能的综合性问题走预设 Workflow（拓客作战计划 / 异议谈判 / 定价报价 / 甲方选型 / 渠道体系 / 0-1 冷启动）
- **甲方视角强制参与**：凡涉及价格、选型、谈判，必须有采购专家反向推演，避免闭眼上谈判桌
- **打法库附件**：`skills/sales-playbook` 提供 5 份方法论参考 + 7 份可填写模板

## 使用示例

- 我卖工业AI质检产品，客户是一家汽车零部件厂，帮我做一份从线索挖掘到签约的全流程打法
- 客户说"价格太贵了，还有免费的替代品"，帮我拆解这个异议并给出能直接用的谈判话术
- 我要向高校信息处卖一套科研数据平台，帮我梳理决策链、采购流程和招投标策略

## 附件：sales-playbook 打法库

```
skills/sales-playbook/
├── SKILL.md
├── references/
│   ├── objection-handling.md      六大高频异议 + 四层拆解法 + 谈判底线纪律
│   ├── pricing-principles.md      三层定价模型、三档报价、折扣授权梯度、TCO
│   ├── decision-chain-map.md      互联网/AI/制造/高校四张决策链地图
│   ├── discovery-question-bank.md 需求诊断提问库（量化追问、伪需求识别）
│   └── channel-and-pricing-rules.md 价盘、返利、窜货治理速查
└── templates/
    ├── customer-profile.md        客户画像表 + ICP 定义
    ├── discovery-interview.md     需求访谈提纲
    ├── proposal-and-quote.md      方案与报价结构
    ├── follow-up-sop.md           跟进节奏 SOP
    ├── win-loss-review.md         赢单复盘 / 丢单归因树
    ├── vendor-scorecard.md        供应商评分卡（甲方选型用）
    └── channel-policy.md          渠道政策模板
```

## 头像

10 张潮玩卡牌风头像（团队整体图 + 8 位成员 + 主理人）位于 `avatars/` 目录：粗墨线扁平插画 + 半色调网点纸感，每个角色一个"正在干活的场景"，每位角色专属底色。如需替换为自定义头像，要求：
- 格式：PNG（推荐）或 JPG
- 尺寸：512×512 px
- 大小：单张不超过 500KB

## 安装

专家包目录：

```
/Users/richa/.workbuddy/plugins/marketplaces/my-experts/plugins/sales-expert/
```

注册命令：

```bash
python3 scripts/register_expert.py <expert-dir>
```

## 打包分享

```bash
python3 scripts/package_expert.py <expert-dir>
```

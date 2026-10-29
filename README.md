<div align="center">

# 顶级sales团 · Top Sales Squad

**十五年跨行业销售专家团** — 互联网 / AI / 智能制造 / 高校科研 / 新兴赛道

从线索挖掘到签单的全流程作战，一次装好即用

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.1.0-blue.svg)]()
[![Experts](https://img.shields.io/badge/experts-9%20agents-purple.svg)]()

</div>

---

<div align="center">
<img src="docs/avatars.png" alt="顶级sales团 头像总览" width="900"/>
</div>

---

## 这是什么

一个 **Team 型专家包**（WorkBuddy / CodeBuddy）：1 位主理人 + 8 位纵深专家 + 1 套打法库。

不是"一个人扮演九种角色"，而是**九个人各有各的方法论**：主理人负责判断这单该谁打、怎么打、缺哪块拼图；行业专家负责各自战场的纵深；打法库负责把结论落成能直接填的表和能直接念的话术。

**设计上的三条硬约束：**

1. **甲方视角强制参与** —— 凡涉及价格、选型、谈判，必须有采购专家反向推演。写进了主理人的铁律：`procurement-expert` 不上场就不能出方案。没有制衡，卖方永远在自说自话。
2. **只产可执行的产出物** —— 每位成员都带"输出模板 + 回传要求"，交回来的是能照做的表格和原话话术，不是"建立信任"这类废话。
3. **单点直调 + 多角色协同双通道** —— 单一维度问题直接调度对应专家（响应快）；跨行业、跨职能的综合性问题走 6 套预设 Workflow。

---

## 安装

### 方式一：添加市场源（推荐）

```
/plugin marketplace add https://github.com/richa-yuan/top-sales-squad
/plugin install sales-expert
```

装完在 **专家中心 → 我的专家** 里就能看到「顶级sales团」，点开即可对话。

### 方式二：直接 clone

```bash
git clone https://github.com/richa-yuan/top-sales-squad.git
```

然后把 `plugins/sales-expert/` 复制到你的专家目录：

```bash
cp -r top-sales-squad/plugins/sales-expert \
  ~/.workbuddy/plugins/marketplaces/my-experts/plugins/
```

> 目录名、`name` 字段与 Agent ID 三者互锁，**不要单独改名**，否则专家中心识别不到。

---

## 团队构成

| Agent ID | 名字 | 头衔 | 战场 |
|---|---|---|---|
| `sales-expert-team-lead` | 关大成 | 销售作战总指挥 | 战场判断、成员调度、SOP 编排、最终汇编 |
| `general-sales-expert` | 周万金 | 全行业销售老兵 | 客户画像、需求诊断、方案报价、跟进 SOP、赢单复盘 |
| `internet-sales-expert` | 谷雨生 | 互联网增长操盘手 | 线索分层、漏斗转化、试用/PLG、续费增购 |
| `ai-sales-expert` | 邱智译 | AI 方案销售顾问 | 技术价值翻译、ROI 测算、POC 设计、AI 报价建模 |
| `manufacturing-sales-expert` | 孟长单 | 工业大单销售专家 | 长周期决策链、产线价值核算、验厂与交付承诺 |
| `university-sales-expert` | 宋育才 | 高校科研采购专家 | 立项经费、院系关系、招投标流程、验收合规 |
| `procurement-expert` | 邹权衡 | 甲方采购选型专家 | 供应商评分卡、议价策略、合规风控、合同条款 |
| `channel-sales-expert` | 汪开渠 | 渠道体系操盘手 | 渠道招募、返利价盘、窜货治理、赋能考核 |
| `startup-sales-expert` | 陆破零 | 0-1 商业化操盘手 | 冷启动获客、种子客户、产品化定价、PMF 信号 |

**阵容**：3 女 6 男。卡片头像为潮玩卡牌风插画（粗墨线 + 半色调网点纸感），每位角色一个"正在干活的场景"。

---

## 实战战场

- **乙方 to B 大客户销售** —— 线索挖掘、需求诊断、方案与报价、商务谈判、招投标、决策链经营、续约增购
- **甲方采购与选型** —— 需求梳理、供应商比较、议价、合同条款、风险评估
- **渠道与分销** —— 渠道招募、政策设计、返利机制、渠道激励与窜货治理
- **0-1 创业拓客** —— 定位、产品化定价、冷启动获客、现金流与生存、第一批种子客户

---

## 打法库附件

`sales-playbook` Skill 随包附带，把方法论和产出物都标准化了：

```
skills/sales-playbook/
├── SKILL.md
├── references/
│   ├── objection-handling.md       六大高频异议 + 四层拆解法 + 谈判底线纪律
│   ├── pricing-principles.md       三层定价模型、三档报价、折扣授权梯度、TCO
│   ├── decision-chain-map.md       互联网/AI/制造/高校四张决策链地图
│   ├── discovery-question-bank.md  需求诊断提问库（量化追问、伪需求识别）
│   └── channel-and-pricing-rules.md 价盘、返利、窜货治理速查
└── templates/
    ├── customer-profile.md         客户画像表 + ICP 定义
    ├── discovery-interview.md      需求访谈提纲
    ├── proposal-and-quote.md       方案与报价结构
    ├── follow-up-sop.md            跟进节奏 SOP
    ├── win-loss-review.md          赢单复盘 / 丢单归因树
    ├── vendor-scorecard.md         供应商评分卡（甲方选型用）
    └── channel-policy.md           渠道政策模板
```

---

## 试一下

最能试出深浅的三个问题：

| 问题 | 考察点 |
|---|---|
| 我卖工业 AI 质检产品，客户是一家汽车零部件厂，帮我做一份从线索挖掘到签约的全流程打法 | 能否同时调度 AI + 智能制造 + 甲方采购三条线并让它们咬合 |
| 客户说"价格太贵了，还有免费的替代品"，帮我拆解这个异议并给出能直接用的谈判话术 | 话术是不是能直接念，还是又变成"建立信任" |
| 我是买方，怎么选供应商 | 甲方视角会不会主动反向压你的价 |

---

## 目录结构

```
top-sales-squad/
├── .codebuddy-plugin/
│   └── marketplace.json            市场清单（plugins[] → source）
├── plugins/
│   └── sales-expert/
│       ├── .codebuddy-plugin/
│       │   └── plugin.json          专家元数据 + 9 位成员定义
│       ├── settings.json            Team 型必需：agent = sales-expert-team-lead
│       ├── agents/                  9 个 Agent 定义（主理人 + 8 成员）
│       ├── avatars/                 10 张 512×512 头像
│       └── skills/sales-playbook/   打法库：5 篇 references + 7 份 templates
├── docs/
│   └── avatars.png                  头像总览图
├── LICENSE
└── README.md
```

---

## 开发

```bash
git clone https://github.com/richa-yuan/top-sales-squad.git
cd top-sales-squad
```

改动专家本体后重新打包校验：

```bash
EXPERT_DIR=plugins/sales-expert
python3 scripts/validate_expert.py "$EXPERT_DIR"     # 校验
python3 scripts/package_expert.py "$EXPERT_DIR" ../.. # 打包
```

**改名注意**：`name` / 目录名 / Agent ID 三者互锁。若只想改显示名，改 `plugin.json` 的 `displayName` 与 `profession`（Team 型要求两者一致）。

---

## 安全提示

> WorkBuddy 无法控制插件中包含的文件或代码，也无法验证它们是否按预期工作或不会发生变化。请在安装前确认您信任该插件。

---

## License

[MIT](LICENSE) © richa-yuan

# Senomorphics（衰老表型调节剂）：抑制 SASP 而不杀细胞的深度机制解析

> 概念：一类不杀死衰老细胞、而是抑制其致病性分泌表型（SASP）的药物，别名 Senomorphic 药物。
> 对立面：Senolytics（选择性诱导衰老细胞凋亡的清除剂，见 04-drugs/03-senolytics.md）。
> 定位：针对同一病理实体——衰老细胞，Senomorphic 选择"调音/驯服"而非"清除"，走温和、可持续、安全性窗口更宽的路径，与 Senolytic 构成抗衰老细胞干预的两大互补策略。

---

## 1. 核心概念

**Senomorphics（衰老表型调节剂）** 是指在保留衰老细胞的前提下，抑制或削弱其衰老相关分泌表型（Senescence-Associated Secretory Phenotype, SASP）的一类干预策略。其哲学起点与 Senolytics 形成鲜明对照：Senolytics 把衰老细胞视为"可清除的僵尸"，主张在恰当的时机选择性诱导其凋亡（减法）；Senomorphics 则承认衰老细胞具有双重身份——既是慢性炎症与组织破坏的源头，又是肿瘤抑制屏障与急性组织修复的参与者，因此主张"不消灭、只驯服"，通过切断 SASP 上游信号来降低衰老细胞的炎症输出，同时保留其在伤口愈合、肝再生等场景中的生理功能。

这一思路的重要性在于它绕开了 Senolytics 的两大核心难题：一是**特异性**——现有人选药物（达沙替尼、槲皮素、Navitoclax）对衰老细胞的选择性是相对的，会对正常增殖细胞产生脱靶影响；二是**给药方式**——Senolytics 需采用脉冲式短程给药（每月 3 天）以平衡清除与保留，而 Senomorphic 因其机制温和，更适合**长期持续给药**，与"抗衰如慢病管理"的现代理念契合。分子层面，Senomorphics 的核心靶点是驱动 SASP 转录的信号枢纽——NF-κB、C/EBPβ、mTORC1、JAK/STAT、p38MAPK——以及这些枢纽上游的代谢感应器（AMPK）与表观调节器（SIRT1/HDAC）。本库主线见 01-foundations/03-no-basics.md 与 04-drugs/05-molecular-mech.md；Senolytic 姊妹篇见 04-drugs/03-senolytics.md。

---

## 2. SASP：Senomorphics 的分子靶点全景

### 2.1 SASP 的组成与上游调控

衰老细胞并非"静息"，而是处于代谢活跃、分泌旺盛的状态。其核心致病输出是 SASP——数十种炎性因子、趋化因子、蛋白酶、生长因子的协同释放。SASP 的转录由几个主开关控制：

| SASP 类别 | 代表因子 | 病理作用 | 上游调控 |
|---|---|---|---|
| 促炎细胞因子 | IL-6、IL-8/CXCL8、TNF-α、IL-1β | 驱动慢性低度炎症（inflammaging） | NF-κB、mTORC1 |
| 趋化因子 | MCP-1/CCL2、CXCL1、MIP | 招募免疫细胞，放大局部炎症 | NF-κB |
| 蛋白酶 | MMP-1、MMP-3、MMP-9/10/13 | 降解细胞外基质，破坏组织结构 | C/EBPβ、p38MAPK |
| 生长因子 | VEGF、EGF、TGF-β | 异常促增殖、促血管生成、促纤维化 | NF-κB、Wnt/TNIK |
| 代谢因子 | PAI-1/SERPINE1、IGFBP | 促血栓、干扰胰岛素信号 | p53/p21、mTORC1 |
| 表观因子 | 高迁移率蛋白 B1（HMGB1） | 损伤相关分子模式（DAMP），激活先天免疫 | 核输出/乙酰化 |

**NF-κB 是 SASP 的第一主开关**：几乎全部促炎 SASP 基因（IL-6、IL-8、TNF-α、MMP、MCP-1）的启动子都含 κB 结合位点。衰老细胞内 DNA 损伤应答（DDR）通过 ATM/ATR → IKK 复合物 → IκBα 磷酸化降解 → NF-κB 入核，大规模启动 SASP 转录。因此靶向 NF-κB 及其上游 IKK 是 Senomorphic 最直接、覆盖最广的切入点。

**mTORC1 是 SASP 的第二主开关**：mTORC1 通过促进 IL-1α 翻译（IL-1α 是 NF-κB 的自分泌上游放大器）以及直接增强 NF-κB 转录活性来放大 SASP。mTOR 抑制（雷帕霉素）因此能"从翻译层面掐断 SASP 放大环"，这也是其 Senomorphic 活性的分子基础。

**C/EBPβ 与 JAK/STAT 是第三层开关**：C/EBPβ 协同 NF-κB 驱动 MMP 与趋化因子；JAK/STAT 则是 IL-6 家族（包括 IL-6 本身）的正反馈放大通路——IL-6 与 IL-6R 结合 → JAK 磷酸化 STAT3 → STAT3 入核又上调更多 IL-6/IL-8，形成自分泌炎性环路。

```
DNA损伤 / 氧化应激 / 癌基因 / 线粒体ROS
      │
      ▼
   DDR (ATM/ATR) ──→ IKK复合物 ──→ IκBα降解 ──→ NF-κB入核
                          │                          │
    IL-1α 翻译 ──→ mTORC1 ──┼── 放大 NF-κB 转录 ──┼──→ SASP 转录程序
    AMPK ──抑制──→ mTORC1                           │
                          JAK/STAT3 ← IL-6 正反馈环路 ──┘
                          p38MAPK / MK2 ──→ SASP mRNA 稳定化(ARE)
                          C/EBPβ ──→ MMP/趋化因子
                          NF-κB ←── 抑制: IKK抑制剂 / NO(天然) / SIRT1
      ▼
   促炎因子(IL-6/TNF-α) · 蛋白酶(MMP) · 趋化因子(MCP-1)
    → 慢性炎症 · 旁分泌衰老传播 · 组织破坏
```

### 2.2 SASP 的病理意义：为什么"抑制分泌"本身就有治疗价值

SASP 的破坏力在于其**旁分泌放大效应**：衰老细胞分泌的 IL-6、TNF-α、活性氧不仅直接损伤邻近细胞，还会通过"衰老传播"将正常细胞拖入衰老状态，形成病灶性衰老巢。SASP 还系统性升高循环炎性因子水平，与动脉粥样硬化、胰岛素抵抗、骨关节炎、神经退行、免疫衰老均有因果关联。因此，**即使不清除衰老细胞，只要持续压制 SASP，就能同时获得局部微环境改善与系统性抗炎获益**——这是 Senomorphic"调音即可起效"的理论基础。Senomorphic 的效价核心是"把 SASP 音量调低"，而非"把衰老细胞清零"。

### 2.3 SASP 的异质性：靶点选择的依据

不同组织/诱导方式的衰老细胞，SASP 谱存在差异：复制性衰老与癌基因诱导衰老（OIS）倾向分泌不同的因子组合；DDR 驱动的衰老与旁分泌传播诱导的衰老在上游信号上也不尽相同。这意味着**没有单一 Senomorphic 能覆盖全部 SASP 谱**——NF-κB 抑制剂覆盖促炎因子、JAK 抑制剂覆盖 IL-6 家族环路、mTOR 抑制剂覆盖 IL-1α 放大、p38MAPK 抑制剂覆盖 MMP 稳定化。靶点选择的现实策略是"按主导病理选择枢纽"。

---

## 3. 主要 Senomorphic 药物：分子机制全链条

### 3.1 雷帕霉素（Rapamycin）——mTORC1 抑制的代表性 Senomorphic

雷帕霉素是 NIA 干预测试项目（ITP）中**唯一在标准环境下显著延长小鼠寿命的候选药**（雌鼠 +18%、雄鼠 +10%，详见 04-drugs/06-mtor-rapamycin.md）。其 Senomorphic 机制核心是**通过抑制 mTORC1 阻断 SASP 放大环**：

```
雷帕霉素 → FKBP12-雷帕霉素复合物 → 结合并抑制 mTORC1
   ├──→ S6K1/4E-BP1 去磷酸化 → 全局翻译↓
   ├──→ IL-1α mRNA 翻译↓ → 自分泌 NF-κB 放大信号↓
   ├──→ NF-κB 转录活性↓ → 促炎 SASP(IL-6/IL-8/TNF-α)↓
   └──→ 自噬↑ → 清除受损蛋白/线粒体 → 衰老表型减轻
          ▼
      SASP 下调但不杀细胞 —— 经典的 Senomorphic 表型
```

关键点：雷帕霉素**抑制 SASP 但不诱导凋亡**，这一点与 Senolytic 截然不同。多项研究（Laberge 等 2015, *Nature Cell Biology*）证明雷帕霉素处理衰老成纤维细胞后，细胞仍处于生长停滞状态（p16 阳性、SA-β-gal 阳性），但 IL-6、IL-8、MMP 等 SASP 因子显著下降，邻近细胞免受旁分泌炎症损伤。这一"保留衰老表型、切除炎症输出"的特征，正是 Senomorphic 的教科书式定义。

**ITP 项目的延长寿命意义**：ITP 采用雌/雄 UM-HET3 异种杂交小鼠，从 9–14 月龄开始给雷帕霉素，雌鼠中位寿命 +18%，雄鼠 +10%。值得注意的是，雷帕霉素的延寿效应在 ITP 中启动较晚（相当于人类中年后），且覆盖多系统（心血管、神经、免疫），提示其部分获益可能正是通过**压制 SASP 驱动的慢性炎症**实现的。

**低剂量/脉冲式策略**：标准免疫抑制剂量（2–5 mg/kg/d）毒性显著（高血糖、血脂异常、伤口愈合延迟、免疫抑制）。当前研究转向**低剂量或每周 1–2 次脉冲给药**——在保留抗衰/mTORC1 抑制效应的同时减少毒副作用。RAD001（依维莫司）在老年志愿者的试验显示，低剂量（0.1–5 mg 每周）可增强流感疫苗应答（免疫衰老逆转），支持"低剂量慢性 Senomorphic"的可行性。

### 3.2 二甲双胍（Metformin）——AMPK 激活的代表性 Senomorphic

二甲双胍是全球处方量最大的降糖药，也是**唯一进入大型抗衰 RCT 的已上市药物**（TAME 试验，详见 04-drugs/07-metformin-ampk.md）。其 Senomorphic 机制通过 AMPK 激活实现：

```
二甲双胍 → 抑制线粒体复合物I → AMP/ATP↑ → 激活 AMPK
   ├──→ 磷酸化 TSC2 → 抑制 mTORC1 → IL-1α/NF-κB SASP 放大↓
   ├──→ 磷酸化 eNOS(Ser1177) → NO↑ → 抑制 NF-κB → SASP↓
   ├──→ 激活 SIRT1(NAD⁺ 依赖) → 去乙酰化抑制 NF-κB → SASP↓
   └──→ 促进自噬 → 清除受损成分 → 衰老表型减轻
          ▼
      SASP 下调 + NO 生物利用度↑ + 代谢年轻化
```

**关键点：二甲双胍是"代谢药 + Senomorphic + 血管保护剂"三合一**。其通过 AMPK→eNOS 通路直接增加 NO 生成，兼具 Senomorphic（压制 SASP）与血管保护（改善内皮功能）双重作用——这在本库 NO 主线（01-foundations/03-no-basics.md）下尤为相关。

**TAME 试验**：Targeting Aging with Metformin，约 3000 名非糖尿病老年人，以"延缓多种衰老相关疾病复合终点"为目标，2016 年启动，截至 2026 年结果尚未公布。这是 Senomorphic 概念走向人体循证的决定性一步。观察性数据（UKPDS 等）显示二甲双胍使用者全因/心血管死亡较低，但存在适应症偏倚，不能据此断言健康人获益。

### 3.3 JAK 抑制剂（Ruxolitinib / Baricitinib）——JAK/STAT 通路

JAK 抑制剂通过阻断 IL-6/IL-8 等细胞因子的 JAK/STAT 信号放大环路来抑制 SASP。**Mayo Clinic 的 Kirkland/Tchkonia 团队 2017 年（*Aging Cell*）里程碑式发现**：ruxolitinib 与 baricitinib 在老年小鼠中降低多种组织的 SASP 因子，缓解与年龄相关的功能障碍。

```
IL-6 / IL-8 / TNF-α 等细胞因子
      │ 结合受体
      ▼
   受体相关 JAK(JAK1/2/3, TYK2) 交叉磷酸化
      │  ←── Ruxolitinib / Baricitinib 在此阻断
      ▼
   STAT3/STAT1 磷酸化 → 二聚化 → 入核
      │
      ▼
   上调更多 IL-6/IL-8/趋化因子 → 正反馈炎性环路
```

**机制全链条**：衰老细胞分泌的 IL-6 与受体结合 → 激活 JAK1/JAK2 → 磷酸化 STAT3 → STAT3 入核转录上调更多 IL-6、IL-8、MCP-1 → 这些因子再次激活 JAK/STAT，形成**自分泌炎性正反馈环**。JAK 抑制剂切断这一环路，使 SASP 无法自我放大。由于 STAT3 也是 NF-κB 与 C/EBPβ 的协同因子，JAK 抑制还间接削弱 NF-κB 的 SASP 输出。

**临床证据**：ruxolitinib（已上市骨髓纤维化药）与 baricitinib（已上市类风湿关节炎药）已在多项动物模型显示改善年龄相关炎症、延长健康寿命。**baricitinib 在特发性肺纤维化（IPF）与系统性炎症人群的试验**正在推进——IPF 的核心驱动正是 SASP 相关的促纤维化炎症，Senomorphic 阻断 IL-6 环路在逻辑上契合。临床挑战在于 JAK 抑制的免疫抑制与感染风险，需在抗炎获益与免疫监视削弱之间权衡。

### 3.4 NF-κB / IKK 抑制剂（Bay 11-7082 等）

NF-κB 是 SASP 第一主开关，靶向其上游 IKK 是覆盖最广的 Senomorphic 策略。**Bay 11-7082** 是经典的 IKK 抑制剂（抑制 IKKβ 介导的 IκBα 磷酸化），在细胞与动物模型中显示可抑制衰老细胞的 SASP 释放、减轻旁分泌衰老传播。但**强效 NF-κB 抑制的代价**：NF-κB 是先天免疫与细胞存活的关键通路，系统性长期抑制存在免疫抑制与组织毒性风险。当前策略是"适度调节而非彻底阻断"——选择性 IKKβ 抑制剂、靶向 NF-κB 特定亚基（如 p65 的特定翻译后修饰）或局部给药，以期在压制 SASP 与保留免疫监视之间取得平衡。

### 3.5 p38MAPK 抑制剂（SB203580 等）

p38MAPK 通过 MK2 通路稳定 SASP mRNA（特别是含 AU 富集元件的 IL-8、IL-6、MMP 转录本），是"炎症因子的 RNA 稳定性开关"。**SB203580** 等 p38α/β 抑制剂能下调衰老细胞的 SASP 分泌，且对衰老状态本身的维持（生长停滞）影响较小。p38MAPK 的独特价值在于**作用于转录后层面**——即使上游转录程序已被 NF-κB 启动，p38 抑制仍可减少已合成 mRNA 翻译为蛋白的量，为组合策略提供正交靶点。

### 3.6 SIRT1 激活剂（白藜芦醇 / NAD⁺ 前体）

SIRT1 是 NAD⁺ 依赖的去乙酰化酶，能**去乙酰化并抑制 NF-κB p65 的转录活性**，同时去乙酰化组蛋白维持抑炎染色质状态。因此 SIRT1 激活 = 天然 Senomorphic 机制（详见 04-drugs/05-molecular-mech.md 的 NAD⁺ 网络）。

```
NAD⁺ 前体(NMN/NR) → NAD⁺↑ → 激活 SIRT1
   ├──→ 去乙酰化 NF-κB p65(K310) → NF-κB 转录活性↓ → SASP↓
   ├──→ 去乙酰化 PGC-1α → 线粒体生物发生↑
   └──→ 去乙酰化 p53/FOXO → 改善代谢与应激应答
          ▼
      NAD⁺/SIRT1 轴是 Senomorphic 与代谢抗衰的桥梁
```

白藜芦醇（resveratrol）作为 SIRT1 激活剂曾在动物中显示抗炎与延寿效应，但其直接激活 SIRT1 存在争议（部分效应可能经 AMPK 间接实现），且口服生物利用度低。**NAD⁺ 前体（NMN/NR）** 通过提升 NAD⁺ 池激活内源性 SIRT1，是当下更被看好的"代谢性 Senomorphic"——其意义在于把 Senomorphic 从药物拓展到"营养干预"层面。

### 3.7 表观遗传调节剂（HDAC 抑制剂 / BET 抑制剂 JQ1）

SASP 基因的大规模转录依赖染色质重塑，表观调节剂因此成为新兴 Senomorphic 靶点：

- **HDAC 抑制剂**（如 SAHA/vorinostat）：衰老细胞的 SASP 基因座存在组蛋白高乙酰化状态（开放染色质），HDAC 抑制理论上可重排这一染色质景观、降低 SASP 转录。但因 HDAC 底物极广，特异性与毒性是主要障碍。
- **BET 抑制剂（JQ1）**：BET 蛋白（BRD4 等）识别乙酰化赖氨酸，将转录延伸复合物招募至 SASP 基因启动子。**JQ1** 阻断 BRD4 与乙酰化组蛋白结合，可下调衰老细胞的多种 SASP 因子（包括 IL-6、IL-8、MMP），是一种机制新颖、选择性较高的 Senomorphic 候选。JQ1 的局限是全身给药的耐受性与长期安全性尚未充分确立，当前主要用于机制研究与局部策略探索。

### 3.8 阿司匹林与 NSAIDs（环加氧酶抑制）

阿司匹林通过抑制环加氧酶（COX-1/COX-2）减少前列腺素 E2（PGE2）等促炎介质，PGE2 是 SASP 的重要组成之一且参与衰老的免疫逃逸。低剂量阿司匹林在人群研究中显示降低结直肠癌风险与心血管事件，部分机制归于其抗炎（削弱 SASP 驱动的炎症）。但**阿司匹林/NSAIDs 作为 Senomorphic 的证据等级较低**——它们抑制的是 COX 下游的炎症介质，而非 SASP 的核心转录程序，且消化道出血与肾功能损害限制了长期使用。在 Senomorphic 谱中属"辅助性、弱证据"层。

### 3.9 糖皮质激素（强效但副作用）

糖皮质激素通过结合糖皮质激素受体（GR），直接抑制 NF-κB 与 AP-1 的转录活性，因此是**强效 SASP 抑制剂**。但其副作用（骨质疏松、血糖升高、免疫抑制、HPA 轴抑制）使其几乎不可能用于慢性抗衰。糖皮质激素的价值在于作为"SASP 抑制机制的验证性工具"——证明了强效 NF-κB 抑制可显著压低 SASP，但也敲响"长期强抑制的毒性警钟"，反过来支持"温和、部分抑制"的 Senomorphic 设计哲学。

### 3.10 天然化合物 Senomorphic

| 化合物 | 来源 | 机制 | 证据等级 |
|---|---|---|---|
| 姜黄素（curcumin） | 姜黄 | 抑制 NF-κB、上调 Nrf2/HO-1 | 体外/动物中等 |
| 槲皮素（quercetin） | 洋葱/苹果 | 抑制 PI3K/Akt 与 NF-κB；**同时是 Senolytic 与 Senomorphic** | 动物支持（D+Q 一线 Senolytic 成分） |
| EGCG | 绿茶 | 抑制 NF-κB、激活 Nrf2 | 体外/动物中等 |
| 白藜芦醇 | 葡萄/浆果 | 激活 SIRT1/AMPK | 体内外均有，人体弱 |
| 雷公藤甲素（triptolide） | 雷公藤 | 抑制 NF-κB、JAK/STAT | 强效但肝/肾毒性显著 |

**槲皮素的"双重身份"是本库的重要看点**：槲皮素既是 D+Q 组合中的 Senolytic 成分（诱导衰老细胞凋亡），又通过 NF-κB/PI3K 抑制具备 Senomorphic 活性——这提示**"一刀切分类"的局限**：同一分子在不同剂量、不同细胞背景下可同时发挥清除与调节作用。同理，姜黄素、白藜芦醇等多靶点天然产物常横跨 Senolytic 与 Senomorphic 边界。

---

## 4. Senomorphics vs Senolytics：互补而非竞争

| 维度 | Senolytic | Senomorphic |
|---|---|---|
| 核心策略 | 清除（减法） | 调节/抑制 SASP（调音） |
| 靶点 | 抗凋亡通路（SCAPs: BCL-2、PI3K、EphB、HSP90、FOXO4） | SASP 信号枢纽（NF-κB、mTORC1、JAK/STAT、p38MAPK、SIRT1） |
| 细胞命运 | 诱导凋亡、清除 | 保留细胞、抑制分泌 |
| 给药方式 | 脉冲式短程（每月 3 天） | 长期持续 / 低剂量慢性 |
| 起效速度 | 较快（清库存式） | 较慢（需持续维持压低） |
| 安全性风险 | 脱靶清除正常细胞、血小板减少、伤口愈合延迟 | 长期免疫抑制、代谢副作用（雷帕霉素高血糖）、组织毒性（天然物） |
| 肿瘤风险 | 理论上有解除抑癌屏障之虞 | 保留衰老的抑癌屏障功能 |
| 代表药 | D+Q、Navitoclax、Fisetin、UBX0101 | 雷帕霉素、二甲双胍、Ruxolitinib/Baricitinib、JQ1 |

**核心洞察**：Senolytic 与 Senomorphic 并非非此即彼，而是作用于同一病理实体的两个互补层面。**联合/序贯策略**是当前公认的最优前瞻方案——先用 Senolytic 脉冲"清库存"（降低高负荷的衰老细胞巢），再用 Senomorphic 长期"降噪"（压制残余与再累积细胞的 SASP 输出，同时预防新衰老细胞形成）。已有动物实验提示 D+Q 与雷帕霉素联合可放大抗炎与抗纤维化效应。

**Rentosertib 的独特定位**：本库已深度解析的 Rentosertib（04-drugs/01-rentosertib.md）是 Senomorphic 的现代 AI 设计范例——TNIK 抑制剂在 IPF 患者中同步下调七种核心 SASP 蛋白（EREG、SPP1、MMP10/13 等），且不杀细胞，是"精确到分子枢纽的 Senomorphic"的代表。

---

## 5. 临床 / 实验证据细节与证据分级

### 5.1 关键证据点

- **雷帕霉素（ITP）**：UM-HET3 小鼠雌鼠中位寿命 +18%、雄鼠 +10%；是唯一在标准环境下显著延寿的候选药（NIA ITP）。RAD001 老年志愿者流感疫苗应答改善。证据等级：动物实锤、人体免疫衰老探索。
- **二甲双胍（TAME）**：大型注册抗衰 RCT（约 3000 人）进行中；观察性数据提示降低全因死亡（有偏倚）；AMPK→eNOS 改善内皮功能。证据等级：人体观察强、RCT 待结果。
- **JAK 抑制剂（Mayo 2017）**：ruxolitinib/baricitinib 降低老年小鼠多种组织 SASP、改善年龄相关功能障碍（*Aging Cell* 2017）。baricitinib 在 IPF/炎症人群的试验推进中。证据等级：动物支持、人体探索。
- **Rentosertib（IPF）**：Phase IIa（71 例，*Nature Medicine* 2023）显示 FVC 剂量依赖改善；探索性蛋白质组分析显示 6 套时钟一致逆转约 3–4 岁，SASP 七蛋白下调。证据等级：人体 II 期探索（详见 04-drugs/01-rentosertib.md）。
- **天然化合物**：姜黄素、槲皮素、EGCG、白藜芦醇在细胞与动物模型显示 SASP 下调与抗炎效应，但人体证据多为观察性/小规模，剂量与生物利用度是短板。

### 5.2 证据分级表

| 现象 | 证据等级 | 关键文献 |
|---|---|---|
| 雷帕霉素延长小鼠寿命（ITP） | ★★★ 强（动物实锤） | Harrison DE, et al. *Nature* 2009 |
| 雷帕霉素抑制 SASP 但不杀细胞 | ★★★ 强（机制确证） | Laberge RM, et al. *Nat Cell Biol* 2015 |
| JAK 抑制剂降老年小鼠 SASP | ★★★ 强（动物） | Xu M, Kirkland JL, et al. *Aging Cell* 2017 |
| 二甲双胍观察性降全因死亡 | ★★☆ 中（人体观察） | UKPDS 及多项队列 |
| 二甲双胍 AMPK→eNOS→NO 血管保护 | ★★☆ 中（动物+部分人体） | 多项机制研究 |
| TAME 延缓衰老相关疾病 | ★☆☆ 待结果 | NCT02432287（进行中） |
| Rentosertib 降 IPF SASP 七蛋白 | ★★☆ 中（人体 II 期探索） | *Nature Medicine* 2023；*Nat Biotechnol* 2026 |
| JQ1 抑制衰老细胞 SASP | ★★☆ 中（临床前机制） | Wakita M, et al. *Sci Transl Med* 2020 |
| 天然物（姜黄素等）抑制 SASP | ★★☆ 中（体外/动物） | 多篇综述 |

> 分级：★★★★★=RCT+机制确证；★★★=随机对照/多模型动物实锤；★★=动物支持或小规模人体探索；★=个案/推断。

---

## 6. 与 NO / NAD⁺ / 长寿网络的联系（本库特色视角）

### 6.1 NO 是天然 Senomorphic

**NO 与 Senomorphic 的关系在本库尤其深刻**：NO 通过 sGC→cGMP→PKG 通路以及 S-亚硝基化修饰，直接抑制 NF-κB 的转录活性，因此**NO 本身就是一种内源性 Senomorphic**。机制链条：

```
NO → S-亚硝基化 IKKβ / 抑制 IκBα 降解 → NF-κB 滞留胞质
   → SASP 促炎转录↓ → 炎症减轻
   + 抑制内皮衰老（eNOS 保护）
   + 改善血管舒张与血小板功能
   ▼
   低浓度 NO = 天然 SASP 抑制剂
```

**SASP 中的 NO 相关因子**：衰老细胞分泌的 TNF-α、IL-6 会通过抑制 eNOS 转录与促进 eNOS 脱偶联（BH4 缺乏时生成超氧阴离子而非 NO）来压低 NO 生物利用度，形成"衰老→炎症→NO↓→炎症加重"的恶性循环（详见 01-foundations/03-no-basics.md）。**内皮衰老是 Senomorphic 与 NO 交汇的核心场景**：衰老内皮细胞 eNOS 活性下降、脱偶联生成 ROS，其 SASP 又进一步破坏血管壁稳态——Senomorphic 压低血管 SASP 后，eNOS 偶联恢复、NO 生物利用度回升，与运动、膳食硝酸盐等 NO 干预形成正向循环。

### 6.2 与 NAD⁺/SIRT1 网络

衰老细胞通过 PARP 活化与 CD38 上调消耗 NAD⁺，导致 NAD⁺ 池下降 → SIRT1 活性减弱 → 解除对 NF-κB 的抑制 → SASP 上升，形成"NAD⁺↓→SIRT1↓→SASP↑→炎症"的正反馈。因此 **NAD⁺ 前体（NMN/NR）与 Senomorphic 逻辑一致**：NMN 恢复 NAD⁺/SIRT1 以抑制 NF-κB（类 Senomorphic 效应），而 Senolytic 则清除已深陷衰老的细胞。三者——Senolytic（清除源头）、Senomorphic（抑制分泌）、NAD⁺ 补充（代谢性抑制 SASP）——构成了"清、抑、养"三管齐下的互补矩阵（详见 04-drugs/05-molecular-mech.md）。

### 6.3 与 12 大衰老标志的联系

Senomorphic 直接作用于"慢性炎症"（SASP 源头），并间接改善"细胞衰老"（削弱旁分泌传播）、"细胞间通讯改变"（恢复微环境信号）、"线粒体功能障碍"（降低 ROS 驱动的 SASP）。相比 Senolytic 的"病灶清除"，Senomorphic 更贴近"系统性炎症调控"的预防医学思维。

---

## 7. 干预方向与可执行建议

### 7.1 当前可及与在研方案

| 方案 | 性质 | 证据 | 风险 |
|---|---|---|---|
| 雷帕霉素（低剂量/脉冲） | 处方药（探索性） | 动物实锤 + 人体免疫探索 | 中（高血糖、血脂、免疫抑制，需医嘱） |
| 二甲双胍 | 已上市降糖药（TAME 试验） | 观察强 + RCT 待结果 | 低（胃肠道；罕见乳酸酸中毒；B12 缺乏） |
| JAK 抑制剂（Ruxolitinib/Baricitinib） | 处方药（已上市，抗衰超适应症） | 动物支持 + 人体探索 | 中（免疫抑制、感染） |
| 槲皮素 / 姜黄素 / EGCG / 白藜芦醇 | 膳食补充剂 | 机制/动物 + 小规模人体 | 低（生物利用度差、需注意剂量） |
| NMN/NR（NAD⁺ 前体） | 膳食补充剂 | 动物强 + 人体探索 | 低 |

**注意**：雷帕霉素、JAK 抑制剂均为处方药，抗衰适应症未获批；天然补充剂生物利用度与纯化质量参差。本文不构成任何医疗建议。

### 7.2 分层联合策略（前瞻）

最优前瞻策略是**分层联合**：

```
第 1 层：生活方式基础（运动 + 膳食 + 睡眠 + NO 干预）
   ↓
第 2 层：Senolytic 脉冲清库存（D+Q / Fisetin，每月 3 天）
   ↓
第 3 层：Senomorphic 长期降噪（雷帕霉素低剂量 / 二甲双胍 / NAD⁺ 前体）
   ↓
目标：清除高负荷衰老细胞巢 + 持续压低残余 SASP + 预防再累积
```

### 7.3 生物标志物驱动的个体化

Senomorphic 的疗效监测依赖**循环 SASP 因子组学**（IL-6、TNF-α、MMP、PAI-1 等）与炎症时钟。理想状态是以循环 SASP 水平指导给药时机与剂量——这与本库 08-frontiers/04-ai-drugs/02-aging-clocks-clinical.md 的"时钟驱动抗衰"理念一脉相承。

---

## 8. 开放问题与争议

1. **长期安全窗口**：Senomorphic 需长期给药，雷帕霉素的高血糖/免疫抑制、JAK 抑制剂的感染风险如何在抗衰获益与毒副作用间平衡？是否存在"长期部分抑制"的毒性拐点？
2. **靶点覆盖不完整**：单一 Senomorphic 无法覆盖全部 SASP 谱（NF-κB 覆盖促炎、JAK 覆盖 IL-6 环路、p38 覆盖 MMP 稳定化），组合策略的协同与叠加毒性缺乏系统数据。
3. **"保留衰老细胞"的长期代价**：Senomorphic 保留衰老细胞，其抑癌屏障功能得以保留，但衰老细胞的"持续存在"是否仍通过非 SASP 途径（如代谢竞争、细胞间接触）产生慢性损害？"只抑制分泌"是否足够？
4. **剂量与时机缺乏标准化**：Senomorphic 的最佳剂量（低剂量雷帕霉素 vs 每周脉冲）、起始年龄、疗程时长均缺乏硬终点数据；TAME 结果公布前，人体获益证据仍薄弱。
5. **天然化合物的生物利用度**：姜黄素、白藜芦醇、EGCG 等人体生物利用度差，真实暴露量与体外效应的距离大，需制剂优化（纳米化、脂质体）与剂量学研究。
6. **与免疫治疗联合的相互作用**：Senomorphic 的免疫抑制潜力（尤其 JAK 抑制剂）与肿瘤免疫检查点治疗的联合，存在削弱抗肿瘤免疫的顾虑，需专门评估。
7. **"未检出≠未下调"的方法学局限**：正如 Rentosertib 蛋白组学所示，血清稳态浓度可能掩盖组织层面的 SASP 下调，需单细胞层面验证补充。

---

## 参考文献

1. Laberge RM, Sun Y, Campisi J, et al. MTOR regulates the pro-tumorigenic senescence-associated secretory phenotype by promoting IL1A translation. *Nature Cell Biology*, 2015;17:1049–1061.（雷帕霉素抑制 SASP 的关键机制）
2. Harrison DE, Strong R, Miller RA, et al. Rapamycin fed late in life extends lifespan in genetically heterogeneous mice. *Nature*, 2009;460:392–395.（ITP 雷帕霉素延寿奠基）
3. Xu M, Kirkland JL, Tchkonia T, et al. JAK inhibition alleviates the cellular senescence-associated secretory phenotype and frailty in old age. *Aging Cell*, 2017;16:947–956.（JAK 抑制剂 Senomorphic，Mayo 里程碑）
4. Kirkland JL, Tchkonia T. Cellular senescence: a translational perspective. *EBioMedicine*, 2017;21:21–28.（Senolytic/Senomorphic 综述）
5. Wakita M, Takahashi A, Hara E, et al. A BET family protein degrader provokes senolysis by targeting NHEJ and autophagy in senescent cells. *Sci Transl Med*, 2020.（表观 Senomorphic/JQ1 相关）
6. Ren F, et al. ISM001-055 (Rentosertib) 2a 期 GENESIS-IPF 结果. *Nature Medicine*, 2023.（本库交叉引用，TNIK Senomorphic）
7. 抗衰蛋白质组分析. *Nature Biotechnology*, 2026-09-07.（Rentosertib 六时钟逆转与 SASP 下调）
8. Hickson LJ, Kirkland JL, et al. Senolytics decrease senescent cells in humans. *EBioMedicine*, 2019.（Senolytic 人体证据，对照参考）
9. TAME 试验. Targeting Aging with Metformin. NCT02432287.（二甲双胍 Senomorphic 大型 RCT）
10. Madreiter-Sokolowski CT, et al. Senomorphic drug classification and mechanism. 2023.（Senomorphic 综述）

---

*本文为 LongLife 长寿研究知识库 04-drugs 系列深度文档。交叉引用：01-foundations/03-no-basics.md（NO 通路）、04-drugs/05-molecular-mech.md（NO/NAD⁺ 分子机制）、04-drugs/03-senolytics.md（姊妹篇 Senolytics）、04-drugs/06-mtor-rapamycin.md（雷帕霉素专题）、04-drugs/07-metformin-ampk.md（二甲双胍专题）、04-drugs/01-rentosertib.md（TNIK Senomorphic 范例）。*

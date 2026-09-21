# NAD⁺/SIRT1 长寿网络

> NAD⁺（烟酰胺腺嘌呤二核苷酸）既是细胞氧化还原的核心辅酶（数百种脱氢酶的电子载体），也是 **sirtuin 去乙酰化酶家族的唯一底物**。组织 NAD⁺ 随龄下降被视作代谢衰退与衰老的重要驱动，补充 NAD⁺ 前体（NMN/NR）成为最受关注的人体抗衰干预之一。NAD⁺ 不是单纯的"能量分子"，而是连接能量代谢、DNA 修复、炎症与昼夜节律的枢纽——它的合成与消耗构成一个动态平衡的"水库"，任何一端的失衡都会通过 sirtuin 家族放大成全身性的代谢与功能改变。

---

## 1. NAD⁺ 的合成途径

### 1.1 三条合成通路

| 途径 | 起始底物 | 限速酶 | 人类中的相对贡献 |
|---|---|---|---|
| **从头合成（de novo）** | 色氨酸（Trp） | IDO/TDO → 喹啉酸（QA） | 次要（受色氨酸摄入限制） |
| **补救途径（salvage）** | 烟酰胺（NAM） | **NAMPT（限速）** | 主导（>90%） |
| **Preiss-Handler** | 烟酸（niacin/NA） | NAPRT1 | 中等（依赖饮食烟酸） |

```
从头合成:  Trp → N-甲酰犬尿氨酸 → 犬尿氨酸 → 3-羟基犬尿氨酸
            → 3-羟基邻氨基苯甲酸 → α-氨基-β-羧基粘康酸-ε-半醛
            → 喹啉酸(QA) → 喹啉酸磷酸核糖转移酶(QPRT) → NAMN → NMN → NAD⁺

补救途径:  NAM ──NAMPT(限速)──► NMN ──NMNAT1-3──► NAD⁺
            ↑                                    │
            └────── NAD⁺ 消耗酶副产物 NAM ◄──────┘
                   (SIRT/CD38/PARP 水解 NAD⁺ 释放 NAM)

Preiss-Handler: NA ──NAPRT1──► NAMN ──NMNAT──► NAAD ──NADSYN1──► NAD⁺
```

- **从头合成**：色氨酸经犬尿氨酸通路生成喹啉酸，再经 QPRT 进入 NAD⁺ 骨架。人类因色氨酸摄入有限，此途径贡献小，且犬尿氨酸通路本身与免疫调节（IDO）相关——IDO 在炎症时被诱导，把色氨酸转向犬尿氨酸而不是 NAD⁺，这提示慢性炎症不仅通过 CD38 消耗 NAD⁺，还会抑制从头合成的原料供应，构成双重打击。
- **补救途径**：NAD⁺ 被消耗酶（SIRT1-7、CD38、PARP）水解后释放**烟酰胺（NAM）**，NAM 被 **NAMPT** 回收生成 NMN，再经 NMNAT 加腺苷酸生成 NAD⁺。**NAMPT 是整个 NAD⁺ 代谢的限速酶**，其活性/表达决定 NAD⁺ 库大小。NMNAT 的三个亚型按区室分工：**NMNAT1 定位于细胞核**（主要服务核内 SIRT1/PARP 对 NAD⁺ 的需求）、**NMNAT2 位于高尔基体/胞质**（神经元中尤其重要，缺失导致轴突变性）、**NMNAT3 在线粒体**（服务 SIRT3-5 与线粒体呼吸）。这一区室化意味着"总 NAD⁺ 水平"不能完全代表"核内或线粒体内的可用 NAD⁺"——不同亚细胞池的相对变化才是决定具体功能走向的关键。NAMPT 有两种形式：胞内酶（iNAMPT）与分泌型胞外酶（eNAMPT，可进入循环调节远处组织）。**Imai 课题组发现下丘脑的 SIRT1 可通过调控 eNAMPT 分泌来"指挥"全身 NAD⁺ 水平**——这建立了"中枢控制外周 NAD⁺"的框架（Yoshida 2019），并提示 eNAMPT 在血浆中的浓度随龄下降、与胰岛素敏感性相关。
- **Preiss-Handler**：烟酸（维生素 B3）经 NAPRT1 → NMNAT → NADSYN1 三步进入 NAD⁺，是廉价有效的升 NAD⁺ 途径，但烟酸引起的皮肤潮红（前列腺素介导）限制了依从性。

### 1.2 随龄下降：约 50%（组织差异）

- 人类多个组织（皮肤、肝脏、肌肉、脑）NAD⁺ 水平随龄下降约 **30–50%**，60 岁后加速；不同组织下降幅度不一（肌肉/脑较明显，肝脏相对保留）。
- **机制**（三因素叠加）：
  1. **NAMPT 活性/表达下降**（补救途径被削弱，NAD⁺"再生产"能力降低）；
  2. **CD38 上调**（NAD⁺ 水解酶随龄在巨噬细胞/免疫细胞中表达升高，是主要消耗方）；
  3. PARP（DNA 修复耗 NAD⁺）在炎症/损伤时激活。
- **组织差异的具体数据**：人体皮肤 NAD⁺ 在 60–70 岁较 20–30 岁下降约 40–50%；骨骼肌约下降 30%；肝脏下降幅度较小（约 10–20%）；脑与脂肪组织亦显著下降。下降并非线性——有研究提示 40 岁后开始加速，且女性绝经后内皮相关 NAD⁺ 依赖功能下降更明显。**检测方法差异**（组织活检 vs 血细胞、LC-MS vs 酶法）会造成报告数值差异，解读跨研究数据需谨慎。
- 后果：NAD⁺ 下降 → SIRT1 活性降低 → 去乙酰化底物（PGC-1α、FOXO、eNOS 等）功能受损 → 线粒体功能、代谢、血管功能全面下滑。需要强调的是，**血中的 NAD⁺ 水平与组织内 NAD⁺ 并不总是同步**——因为肠肝轴、血细胞代谢会先行消耗或转化前体，这解释了许多人体试验"血 NAD⁺ 升高明显而组织获益有限"的现象。

---

## 2. NAD⁺ 消耗酶：SIRT1-7、CD38、PARP

NAD⁺ 不仅是辅酶，还是多种酶的底物。消耗酶竞争同一 NAD⁺ 库：

| 酶家族 | 成员 | 反应 | 亚细胞定位 | 衰老相关变化 |
|---|---|---|---|---|
| **Sirtuin** | SIRT1-7 | NAD⁺ + 乙酰赖氨酸 → 去乙酰化 + NAM + O-acetyl-ADP-ribose | 核/胞质/线粒体 | 活性随 NAD⁺ 下降 |
| **CD38** | 跨膜糖蛋白 | NAD⁺ → cADPR/ADPR + NAM（NADase） | 质膜、胞外 | **随龄上调（主要 NAD⁺ 消耗者）** |
| **PARP** | PARP1/2 | NAD⁺ → poly(ADP-ribose) 修饰 | 核 | 损伤/DNA 断裂时激活 |

**CD38 的突出地位**：衰老组织 CD38 表达上调（炎性巨噬细胞浸润所致），小鼠敲除 CD38 或使用 CD38 抑制剂（如 78c）可恢复 NAD⁺ 并改善线粒体功能（Chini et al.；Camacho-Pereira 2016 证明 CD38 是年龄相关 NAD⁺ 下降的主要酶学原因）。CD38 也是 NMN 进入细胞后胞外水解的主要闸门——这直接影响 NMN 口服的生物利用度。值得注意的是，CD38 的产物 cADPR（环腺苷二磷酸核糖）本身是内质网钙释放的第二信使，参与免疫细胞活化，故"抑制 CD38 以保存 NAD⁺"可能同时削弱部分钙信号功能，这在设计 CD38 抑制剂时需要权衡。

**消耗酶的竞争关系**：SIRT1、CD38、PARP 共享同一 NAD⁺ 库，三者构成"分配博弈"——DNA 损伤（PARP 激活）与慢性炎症（CD38 上调）都会挤占 SIRT1 可用的 NAD⁺，这是衰老中"SIRT1 活性下降"的重要间接机制。反之，PARP 抑制剂与 CD38 抑制剂在动物中均能"释放"NAD⁺ 给 SIRT1，构成干预思路。这一"酶学竞争"也解释了为何单纯补前体（增加供应）在某些炎症/损伤状态下效果有限——因为消耗端的 CD38/PARP 上调会"吞噬"新补进去的 NAD⁺。**这提示"开源"（补前体）与"节流"（抑 CD38/PARP）需要协同**，是当前联合干预研究的逻辑基础。

---

## 3. SIRT1：NAD⁺ 依赖性去乙酰化酶

### 3.1 结构与催化

- **结构域**：SIRT1 含 N 端调控域与高度保守的**催化核心域（sirtuin 结构域，约 275 aa）**，分两个亚域：**Rossmann 折叠域（结合 NAD⁺）**与锌结合域（结合乙酰化底物肽）；两亚域之间的裂缝即活性位点。
- **催化**：NAD⁺ 的烟酰胺部分转移至乙酰基，生成 **O-acetyl-ADP-ribose + NAM**（产物 NAM 又是 NAMPT 底物，闭环回收）；此反应**严格依赖 NAD⁺ 浓度**，Km 约 100–300 μM，故 NAD⁺ 生理波动直接调制 SIRT1 活性。因为 NAD⁺ 的生理浓度（约数百 μM）恰好落在 SIRT1 的敏感范围内，细胞 NAD⁺ 的细微波动就能成比例地改变去乙酰化速率——这是"NAD⁺ 是 sirtuin 开关"的分子基础。
- **活性调控**：NAMPT 提供的 NAD⁺ 是主控；另外 SIRT1 表达受 AMPK 诱导，受 miR-34a 等抑制。内源性抑制剂 DBC1（deleted in breast cancer 1）能与 SIRT1 催化域结合抑制其活性，而 DNA 损伤时 DBC1 与 PARP1 竞争性结合，从而在应激时解抑 SIRT1——这一"竞争性抑制开关"提示 SIRT1 活性受蛋白-蛋白互作的精细调节，不单纯由 NAD⁺ 浓度决定。

### 3.2 去乙酰化底物全谱（位点 + 效应）

| 底物 | 主要乙酰化位点 | 去乙酰化效应 | 生物学后果 |
|---|---|---|---|
| **PGC-1α** | Lys779（及 K13/K609 等） | 激活转录共激活功能 | 线粒体生物发生↑、糖异生调控、氧化代谢↑ |
| **FOXO1/3a** | FOXO1 K262/K265；FOXO3a K242/K259 | 偏向抗氧化基因（MnSOD、Catalase、GADD45）而非凋亡 | 抗氧化防御↑、细胞存活↑ |
| **NF-κB (p65/RelA)** | Lys310 | 抑制 NF-κB 转录活性 | 抗炎（下调 TNF-α、IL-6） |
| **p53** | Lys382（及 K320/K373） | 抑制 p53 转录活性 | 抗凋亡、细胞周期检查点下调 |
| **eNOS** | Lys496/Lys506（人序列） | 增强 eNOS 活性 | NO 生成↑ → 血管舒张（见 §6） |
| **HSF1** | Lys298/Lys524 | 增强 HSF1 与 HSE 结合 | 热休克蛋白（HSP70 等）表达↑ → 蛋白稳态 |

- 全谱超过 60 个底物：还包括 STAT3、HIF-1α、SREBP、PPARγ、Ku70、LKB1 等，覆盖代谢、炎症、应激、DNA 修复各轴。LKB1 去乙酰化增强其激活 AMPK 的能力，构成"SIRT1→AMPK"的放大回路；HIF-1α 去乙酰化则抑制其稳定性，在低氧/肿瘤背景下影响血管生成——这提示 SIRT1 并非一味"抗衰"，在某些促血管生成、促增殖情境下可能成为"双刃剑"。
- **组织特异性**：SIRT1 在代谢活跃组织作用显著——肝（糖异生、脂代谢）、脂肪（脂肪动员）、肌肉（线粒体）、下丘脑（摄食调控）；内皮（eNOS）是其血管特异功能。在下丘脑，SIRT1 还调控 POMC 与 AgRP 神经元的活动，进而影响食欲与能量消耗，是"中枢代谢调控"的又一入口。

**SIRT1 与其他 sirtuin 分工**：SIRT1 定位于核与胞质，是衰老研究最集中的成员；SIRT2 主要在胞质（微管、代谢）；SIRT3/4/5 在线粒体（SIRT3 去乙酰化线粒体酶，是线粒体 NAD⁺ 传感主开关）；SIRT6/7 在核（基因组稳定、rDNA 转录）。家族共享 NAD⁺ 依赖机制但底物谱不同，故"NAD⁺ 下降"的后果是全网式的而非仅 SIRT1。特别地，SIRT3 在心肌与骨骼肌中高度表达，负责去乙酰化并激活多数线粒体呼吸链复合物，是"SIRT1 下调线粒体"之下游执行者；SIRT6 则通过去乙酰化 H3K9/H3K56 维护端粒区染色质稳定，与基因组完整性和寿命正相关（小鼠 SIRT6 过表达延长寿命）。

---

## 4. 昼夜节律与 SIRT1/NAMPT 的互作

NAD⁺ 代谢并非恒定，而是跟随昼夜节律振荡。**哺乳动物生物钟的核心回路（CLOCK/BMAL1 与 PER/CRY）直接控制 NAMPT 的转录**：CLOCK/BMAL1 结合 NAMPT 启动子中的 E-box 元件，使 NAMPT 表达在活动相达到峰值，从而驱动 NAD⁺ 与 SIRT1 活性的节律性波动。反过来，**SIRT1 去乙酰化 BMAL1 与 PER2**，抑制生物钟基因表达，形成"生物钟 → NAMPT → NAD⁺ → SIRT1 → 生物钟"的负反馈回路。

这一互作的衰老意义在于：**老年个体的生物钟振幅衰减，NAMPT 的节律峰值降低，导致 NAD⁺ 日波动钝化**，进而削弱 SIRT1 的节律性激活。动物实验显示，昼夜颠倒（慢性时差）会加速 NAD⁺ 代谢紊乱并促发代谢疾病；恢复规律作息与限时进食（把进食窗口限制在活动相）可以部分恢复 NAMPT 的节律表达与 NAD⁺ 水平。这为"规律睡眠/限时进食能抗衰"提供了分子层面的解释，也把生活方式干预与 NAD⁺/SIRT1 通路直接连起来（详见 07-interventions/05-sleep-optimization.md）。

---

## 5. NMN / NR 补充：吸收、人体数据、争议

### 5.1 吸收机制与 Slc12a8 争议

- **NR（烟酰胺核糖）**：经平衡型核苷转运体（ENT1/ENT2）直接进入细胞，或先在胞外被 CD73 去磷酸化；入胞后被 NRK1/NRK2 磷酸化为 NMN。**NR 入胞通路基本明确**。
- **NMN（烟酰胺单核苷酸）**：曾被认为必须先在胞外去磷酸化为 NR 再入胞（CD73 途径）；2019 年 **Grozio 等提出 Slc12a8 是 NMN 的直接转运体**（Science 子刊），但后续多个实验室未能重复，且 Slc12a8 在人体组织的表达极低——**"Slc12a8 即 NMN 转运体"目前处于争议状态**，主流观点仍是"胞外去磷酸化→NR→入胞"占主导。Cantó 2012 与 Yoshino 2011 分别确立了 NR 与 NMN 在哺乳动物中的升 NAD⁺ 效力，为后续人体试验奠定基础。
- **肠道菌群转化**：口服 NMN/NR 在肠道内经菌群与肠上皮酶促转化；部分 NMN 在小肠被去磷酸化为 NR 再吸收，另有研究提示 NMN 可经肠道转运体吸收并提高肝脏 NAD⁺（Yoshino 2018）。菌群组成可影响前体到 NAD⁺ 的转化效率，个体差异大——这也意味着补充剂的疗效存在明显的"菌群个体差异"，同一剂量在不同人身上的 NAD⁺ 提升可能相差数倍。
- **药代动力学要点**：NMN 血浆峰值出现在口服后约 10–15 分钟即达峰（部分数据提示存在快速清除），NR 则经 ENT 转运入胞后需 NRK 磷酸化；两者在血中均以代谢产物形式循环，直接测定完整 NMN 入血的比例很低——多数证据支持"前体在肠肝轴内被快速转化利用，而非以原形进入循环"。这提示**递送形式（缓释、肠溶）可能比剂量本身更影响组织 NAD⁺ 提升效率**。

### 5.2 人体试验数据（关键 RCT）

| 研究 | 设计 | NAD⁺ 提升 | 主要发现 | 安全性 |
|---|---|---|---|---|
| Martens et al. 2018 (*Nat Commun*) | NR 1g/d，12 周 | 血 NAD⁺ ↑约 60–90%（剂量依赖） | NAD⁺ 代谢物升高；功能终点（血压等）改善有限 | 良好，无严重 AE |
| Airhart et al. 2017 | NR 250–1000 mg/d | 剂量依赖 ↑ | 未见明显抗炎/功能获益 | 良好 |
| Yoshino et al. 2021 (*Science*) | NMN 250 mg/d，10 周（绝经后糖尿病前期女性） | 骨骼肌 NAD⁺ ↑约 21–25% | **肌肉胰岛素敏感性↑**（糖原合成↑、胰岛素信号改善） | 良好，无 AE |
| Igarashi et al. 2022 | NMN 250 mg/d，12 周（健康老年男性） | 血 NAD⁺ 上升 | 握力、步速等体能指标改善（小样本） | 良好 |
| 认知终点 | 少量试验提示 NR/NMN 或改善老年认知评分 | — | 证据初等（样本小、多为开放标签） | 需更大 RCT |

- **共识**：口服 NR/NMN 可安全、剂量依赖地升高血/组织 NAD⁺（约 1.5–2 倍）；但对功能终点（握力、胰岛素敏感性、认知）的获益**不一致**，多数大型试验未见显著改善；长期（>1 年）安全性数据缺乏。Amjad 等 2021 年在 *Mol Metab* 的系统回顾进一步确认：前体补充在多数人体研究中确实能提升循环 NAD⁺，但把 NAD⁺ 升高转化为临床终点改善的证据仍不充分，提示"NAD⁺ 只是必要条件而非充分条件"。
- **理论风险**：NAD⁺ 升高理论上可增强肿瘤细胞 DNA 修复与增殖（SIRT1/PARP 依赖），即"喂癌"假说——目前无人体因果证据，属开放争议。Rajman 2018 在 *Cell Metab* 综述中特别讨论了这一双刃剑属性，认为在已有癌前病变或高肿瘤风险的个体中需要谨慎。
- **实践要点**：NMN/NR 口服后血浆浓度峰值出现在 30–60 分钟，半衰期短，动物实验多采用每日分次给药；人体研究中 NR 吸收优于 NMN（NR 可直接入胞），但 NMN 在部分组织（肝脏）的 NAD⁺ 提升效率不逊于 NR；两者与运动、禁食联合的叠加效应尚未在 RCT 中系统验证。剂量上，人体研究常用 250–1000 mg/日，低于此量提升有限、高于此量的边际收益递减——"越多越好"的假设缺乏证据支撑。
- **新兴方向（长新冠等疾病状态）**：2021–2023 年麻省总医院开展的一项 24 周随机对照试验（58 例长新冠患者）提示 NR 补充（最长 20 周）或可改善疲劳与脑雾等神经症状，2025 年 12 月已有媒体报道其早期结果。这代表 NAD⁺ 前体从"健康人抗衰"向"疾病状态干预"的延伸，但其机制（炎症减轻 vs 线粒体功能恢复）与普适性仍需更大样本验证，暂归 C 级证据。

---

## 6. 与 NO 的耦合：正反馈环

NAD⁺/SIRT1 与 NO 构成长寿正反馈回路：

```
NAD⁺ ──► SIRT1 ──去乙酰化 eNOS (K496/K506)──► eNOS 活性↑
                                                  │
                                                  ▼
                                            NO 生成↑
                                                  │
                 ┌────────────────────────────────┤
                 ▼                                ▼
         sGC/cGMP → PKG                  AMPK 激活（NO 抑制
                 │                       复合物I 轻度激活 AMPK）
                 ▼                                │
           血管舒张、抗炎                        ▼
                                        SIRT1 表达↑ / NAD⁺ 代谢↑
                                        （正反馈闭环）
```

- **SIRT1 → eNOS → NO**：SIRT1 去乙酰化 eNOS 的 Lys496/Lys506，增强其活性 → NO 生成↑ → 内皮舒张、抗炎、抗血栓。Mattagajasingh 2007 在 *PNAS* 直接证明 SIRT1 过表达增强 eNOS 活性与内皮舒张，确立了这一因果链。
- **NO → SIRT1 激活**：NO 经 sGC/cGMP/PKG 与 AMPK 通路上调 SIRT1 表达与活性；NO 本身也抑制 eNOS 解偶联，减少氧化应激对 SIRT1 的损伤。NO 抑制线粒体复合物 I 所致的"轻度线粒体应激"（hormesis）会触发 AMPK 激活，进而诱导 SIRT1 表达——这是"NO 促进 SIRT1"的非经典机制，与 NO 的抗氧化特性共同构成闭环（详见 01-foundations/03-no-basics.md）。
- **病理意义**：年龄相关 NAD⁺ 下降 → SIRT1 活性↓ → eNOS 去乙酰化不足 → NO 生物利用度↓ → 内皮功能障碍（血管衰老的早期标志）；同时 NO↓ → SIRT1 下调，形成**恶性循环**。这解释了为何 NAD⁺ 补充在动物中可部分恢复内皮 NO 功能（小鼠 NMN 处理恢复主动脉 NO 依赖舒张）。
- **临床关联**：SIRT1 启动子区常见 SNP（如 rs7895833 与 rs1467568）与代谢表型相关，提示该环路的个体遗传差异可能影响衰老轨迹与对 NAD⁺ 前体的反应性。**遗传-环境交互**：携带特定 SIRT1 SNP 的个体，其内皮 NO 功能对 NAD⁺ 前体的响应可能不同——这是未来"精准补充"的潜在方向。

---

## 7. 与 AMPK/mTOR 的交叉调控

NAD⁺/SIRT1 并非孤岛，而是能量感应网络的枢纽，与 AMPK、mTOR 构成三联调控：

- **SIRT1 ↔ AMPK 相互激活**：SIRT1 去乙酰化 LKB1 增强其激活 AMPK 的能力；AMPK 则通过升高 NAD⁺/NAD⁺H 比值与诱导 NAMPT 表达来激活 SIRT1。二者构成"能量匮乏时协同燃脂、促线粒体"的正反馈，是运动与热量限制发挥抗衰作用的共同分子基础（详见 04-drugs/07-metformin-ampk.md，二甲双胍正是 AMPK 激活剂）。
- **SIRT1 ↔ mTOR 拮抗**：SIRT1 抑制 mTOR 通路（部分通过去乙酰化 TSC2 或调节 AMPK），而 mTOR 激活会抑制自噬并促进合成代谢。在营养充足时 mTOR 占优、抑制自噬；在营养匮乏/限时进食时 SIRT1-AMPK 占优、激活自噬与线粒体生物发生。**NAD⁺/SIRT1 是"禁食时优先激活"的通路，mTOR 是"进食时优先激活"的通路**——二者的此消彼长界定了细胞对营养状态的应答方向（详见 04-drugs/06-mtor-rapamycin.md）。
- **综合视角**：抗衰干预（运动、禁食、二甲双胍、NAD⁺ 前体）往往同时"升 SIRT1-AMPK、降 mTOR"，而非单一靶点。这也解释了为何单一补充剂（只升高 NAD⁺）在人体中的效果弱于复合生活方式干预——因为后者同时作用于 AMPK/mTOR 等多个杠杆。
- **与免疫衰老的连接**：NAD⁺ 对免疫细胞的双向影响值得注意——SIRT1 抑制 NF-κB 可压制慢性炎症，但适度 NAD⁺/SIRT1 活性又是 T 细胞活化与分化的必要条件；免疫细胞（尤其巨噬细胞）本身是 CD38 的主要来源，因此**免疫系统的 NAD⁺ 需求与消耗构成自反馈**：炎症越重、CD38 越高、NAD⁺ 越低、SIRT1 抗炎能力越弱，炎症更重。这使 NAD⁺/SIRT1 成为连接"代谢衰老"与"免疫衰老"（inflammaging）的枢纽（详见 03-immunity/02-inflammaging.md 与 03-immunity/04-immunosenescence.md）。

---

## 8. 干预策略

| 干预 | 机制 | 证据强度 |
|---|---|---|
| **NMN/NR 补充** | 直接提升 NAD⁺ → 激活 SIRT1 | 人体 RCT：NAD⁺ 升高确证，功能获益不一致（B 级） |
| **烟酸（NA）** | Preiss-Handler 途径 | 廉价有效升 NAD⁺，但潮红副作用限制依从性（B 级） |
| **CD38 抑制剂**（如 78c、芹菜素） | 减少 NAD⁺ 水解 | 动物强证据，人体尚在早期（C 级） |
| **运动** | 肌肉 AMPK↑ → NAMPT↑ → NAD⁺↑；eNOS 激活 | 强（A/B 级，机制确证） |
| **热量限制/禁食** | 代谢应激 → NAD⁺/NAMPT 升高 → SIRT1 激活 | 动物确证，人体中等（B 级） |
| **光照/昼夜节律** | 生物钟（SIRT1–CLOCK 互作）、适度紫外线→皮肤 NO 释放 | 新兴领域（C 级） |
| **白藜芦醇等 SIRT1 激活剂** | 直接激活/稳定 SIRT1（机制有争议，部分证据指向 AMPK 间接效应） | 动物多样、人体不一致（C 级） |

- **运动**：耐力训练显著上调肌肉 NAMPT 与 NAD⁺，同时激活 eNOS（剪切应力 + AMPK），是目前证据最扎实的内源性提升手段。高强度间歇训练（HIIT）在肌肉线粒体功能与 NAD⁺ 代谢上的改善略优于中等强度持续训练。运动的"升 NAMPT、降 CD38"双向作用使其优于单纯补前体——因为它在"开源"的同时也"节流"（详见 07-interventions/02-exercise.md）。
- **禁食/热量限制**：NAD⁺/NAMPT 升高与 SIRT1 激活是 CR 模拟效应的核心机制之一（动物模型）。隔日禁食与限时进食（如 16:8）在人体初步试验中可轻度升高血 NAD⁺ 并改善代谢指标，但个体差异大，长期依从性是主要挑战。限时进食之所以有效，很可能与 §4 的昼夜节律机制相关——把进食限制在活动相能放大 NAMPT 的节律峰值。
- **光照**：紫外线 A/B 可使皮肤光解亚硝酸盐释放 NO（皮肤是体内 NO 储库），提示适度日晒的血管获益；但机制与剂量仍待确证。

---

## 9. 证据分级与开放问题

### 证据分级

| 层级 | 内容 |
|---|---|
| A（确证） | NAD⁺ 三条合成途径、NAMPT 限速地位；SIRT1 催化机制与底物去乙酰化；CD38 为 NAD⁺ 消耗酶；运动/CR 上调 NAD⁺；NAMPT–生物钟互作回路 |
| B（强） | 组织 NAD⁺ 随龄下降 30–50%；CD38 上调是主因（动物敲除/抑制实验）；NMN/NR 人体安全升 NAD⁺；NAD⁺→SIRT1→eNOS→NO 正反馈链（Mattagajasingh 2007 确证 eNOS 环节） |
| C（中等/争议） | 功能终点获益（胰岛素敏感性个别阳性、多数中性）；Slc12a8 转运体；长期安全性（肿瘤风险理论）；白藜芦醇直接激活 SIRT1 的机制争议 |

### 开放问题

1. **前体最优策略**：NMN vs NR vs NA 的剂量、剂型、给药时序与人群分层尚无定论；是否需要与 CD38/PARP 抑制剂"开源+节流"联合尚不清楚。
2. **"NAD⁺ 升高 = 健康获益"是否成立**：人体 RCT 中 NAD⁺ 升高与功能改善脱节，提示可能存在其他瓶颈（如 SIRT1 表达、CD38 活性、组织递送效率）。Amjad 2021 的系统回顾即指出这一点。
3. **长期致癌风险**：NAD⁺/SIRT1 促进 DNA 修复在肿瘤细胞中的"双刃剑"争议缺乏人体数据。
4. **组织靶向**：如何选择性提升特定组织（肌肉/脑/内皮）NAD⁺ 而非整体——CD38 抑制剂与组织特异性前体的开发是前沿。
5. **"NAD⁺ 下降"与"SIRT1 活性下降"的因果方向**：CD38 抑制剂升高 NAD⁺ 后 SIRT1 活性是否必然恢复、抑或存在 NAD⁺ 之外的调控瓶颈（如 DBC1 抑制、miR-34a 表达），尚无定论。
6. **剂量-效应关系**：NAD⁺ 提升的"治疗窗口"尚未界定——过低无效、过高是否出现脱敏或代偿仍不清楚。

---

## 10. 与 NO 通路耦合小结

NAD⁺/SIRT1 与 NO 共享同一长寿网络：**NAD⁺ → SIRT1 → eNOS 去乙酰化 → NO → AMPK/cGMP → SIRT1↑**。两条通路在血管衰老、代谢与免疫中协同衰减，也共同构成运动、禁食、补充剂等干预的分子靶点。在知识库全景中，本通路与 [NO 基础](03-no-basics.md)、[线粒体与 NO](../02-vascular/04-mitochondria.md)、[慢性炎症](../03-immunity/02-inflammaging.md)、[二甲双胍与 AMPK](../04-drugs/07-metformin-ampk.md)、[mTOR 与雷帕霉素](../04-drugs/06-mtor-rapamycin.md)、[运动处方](../07-interventions/02-exercise.md) 及 [12 大衰老标志](01-aging-hallmarks.md) 形成密集互连，共同支撑"血管-代谢-免疫"三轴协同抗衰的总框架。理解 NAD⁺/SIRT1 的完整机制链（合成→消耗→去乙酰化→NO/AMPK/mTOR 交叉→昼夜节律），是评估任何"抗衰补剂"与生活方式干预效果的先决条件。

**参考文献**：
- Yoshino J, Mills KF, Yoon MJ, Imai S. Nicotinamide mononucleotide, a key NAD⁺ intermediate, treats the pathophysiology of diet- and age-induced diabetes in mice. *Cell Metab* 2011;14:528-536.（确立 NMN 在哺乳动物中的升 NAD⁺ 与代谢改善效力）
- Cantó C, Houtkooper RH, Pirinen E, et al. The NAD⁺ precursor nicotinamide riboside enhances oxidative metabolism and protects against high-fat diet-induced obesity. *Cell Metab* 2012;15:838-847.（确立 NR 的作用）
- Yoshino J, Baur JA, Imai SI. NAD⁺ intermediates: the biology and therapeutic potential of NMN and NR. *Cell Metab* 2018;27:513-528.（综述）
- Rajman L, Chwalek K, Sinclair DA. Therapeutic potential of NAD⁺-boosting molecules: the in vivo evidence. *Cell Metab* 2018;27:529-547.（综述，含"双刃剑"讨论）
- Martens CR, Denman BA, Mazzo MR, et al. Chronic nicotinamide riboside supplementation is well-tolerated and elevates NAD⁺ in healthy middle-aged and older adults. *Nat Commun* 2018;9:1286.（NR 人体试验，血 NAD⁺ ↑60–90%）
- Yoshino M, Yoshino J, Kayser BD, et al. Nicotinamide mononucleotide increases muscle insulin sensitivity in prediabetic women. *Science* 2021;372:1224-1229.（NMN 人体试验）
- Igarashi M, Nakagawa-Nagahama Y, Miura M, et al. Chronic nicotinamide mononucleotide supplementation elevates blood NAD⁺ and alters muscle function in healthy older men. *npj Aging* 2022;8:5.（NMN 老年男性）
- Imai SI, Guarente L. NAD⁺ and sirtuins in aging and disease. *Cell Metab* 2014;20:957-963.（NAMPT/eNAMPT 框架）
- Amjad S, et al. Role of NAD⁺ in regulating cellular and metabolic signaling pathways. *Mol Metab* 2021;49:101195.（系统回顾）
- Grozio A, Mills KF, Yoshino J, et al. Slc12a8 is a nicotinamide mononucleotide transporter. *Nat Metab* 2019;1:47-57.（Slc12a8，争议）
- Camacho-Pereira J, Tarragó MG, Chini CCS, et al. CD38 dictates age-related NAD⁺ decline and mitochondrial dysfunction. *Cell Metab* 2016;25:1127-1139.（CD38 与年龄相关 NAD⁺ 下降）
- Mattagajasingh I, Kim CS, Naqvi A, et al. SIRT1 promotes endothelium-dependent vascular relaxation by activating endothelial nitric oxide synthase. *PNAS* 2007;104:14855-14860.（SIRT1 去乙酰化 eNOS）
- Cantó C, Auwerx J. Caloric restriction, SIRT1 and longevity. *Curr Opin Lipidol* 2009;20:91-96.（SIRT1 与代谢）

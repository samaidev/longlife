# 压力管理与心率变异性（Stress Management & HRV）

## 核心概念

压力管理（stress management）与心率变异性（heart rate variability, HRV）是长寿干预谱系中"最廉价、最可量化、人人可执行"的一支。压力并非抽象情绪，而是一套进化保留下来的神经内分泌程序：急性应激通过交感-肾上腺髓质（SAM）轴与下丘脑-垂体-肾上腺（HPA）轴在数秒至数小时内动员能量、提升警觉——这是"战斗或逃跑"的适应性反应；但当压力变成慢性，皮质醇节律紊乱、交感持续亢进、迷走张力下降，会转化为端粒缩短、表观年龄加速、慢性炎症、海马萎缩与代谢紊乱，成为 12 大衰老标志中"慢性炎症""线粒体功能障碍""细胞通讯改变"的共同放大器。HRV 是这一过程最方便的门诊探针：它测量逐次心跳间隔的微小变异，本质上是迷走（副交感）对窦房结持续"刹车"作用的量化，反映自主神经系统调节的灵活性——低 HRV 与全因死亡、心血管事件、倦怠、焦虑及炎症水平升高独立相关。与抗衰的关系在于：HRV 受遗传影响但可通过呼吸、冥想、运动、睡眠显著训练提升，是少数"可干预、可监测、有生理学意义"的健康标志物；其改善路径（迷走↑→NO↑、皮质醇↓→炎症↓）与本库 NO/NAD+ 主线直接交汇（详见 01-foundations/03-no-basics.md、03-immunity/06-neuro-immune-axis.md）。

## 分子机制全链条

### 1. 应激反应的双轴架构：SAM 轴与 HPA 轴

应激反应由两条时间尺度不同的神经内分泌通路驱动：

```
应激源（生理/心理威胁）
        │
        ├──▶ SAM 轴（秒级，儿茶酚胺）
        │      下丘脑/脑干 → 交感节前纤维 → 肾上腺髓质
        │          释放肾上腺素(E)/去甲肾上腺素(NE)
        │          → α1-AR: 血管收缩、血压↑
        │          → β1-AR(心脏): 心率↑、收缩力↑
        │          → β2-AR: 支气管扩张、糖原分解、NK 细胞动员
        │
        └──▶ HPA 轴（分钟-小时级，皮质醇）
               下丘脑室旁核(PVN) → CRH → 垂体前叶 → ACTH
               → 肾上腺皮质 → 皮质醇(Cortisol)
               → 糖皮质激素受体(GR) 转位入核
               → 基因组效应: 糖异生↑、免疫调节、海马负反馈
```

- **时间动力学**：儿茶酚胺在数秒内释放、数分钟内清除，介导即时"冲刺"；皮质醇分钟级起效、半衰期约 60-90 分钟，经 GR 的基因组效应持续数小时至数天。两者的负反馈不同：皮质醇经海马与下丘脑 GR 抑制 CRH/ACTH 释放（"糖皮质激素级联"的闭环，Sapolsky 1986），而儿茶酚胺无对应长环反馈，主要靠局部再摄取与酶解失活。
- **急性应激是适应性的**：急性应激下 NK 细胞与 CD8⁺ T 细胞动员入血、吞噬活性升高、记忆巩固增强、血糖动员——这是"战斗或逃跑"下免疫与代谢的短期重分配（Segerstrom & Miller 2004 的 meta 分析证实急性应激增强固有免疫、动员细胞免疫）。
- **慢性应激的病理性转换**：当应激源持续，系统从"应激-恢复"循环滑向"非稳态负荷"（allostatic load，McEwen 1998）——皮质醇基线升高且昼夜节律扁平化、交感持续亢进、恢复机制失能。关键分子事件是**糖皮质激素受体抵抗（glucocorticoid resistance）**：慢性高皮质醇下调 GR 表达与敏感性，皮质醇"压不住"炎症基因，NF-κB 通路反而上调（Cohen 2012 PNAS；Miller 2008 Biol Psychiatry 的转录组研究显示慢性应激者外周血白细胞呈现"GR 迟钝 + NF-κB 高表达"的功能基因组指纹）。这是"慢性压力→炎症"的核心机制枢纽。

### 2. 慢性应激的衰老效应：从端粒到表观时钟

慢性应激的衰老效应在四个层面有真实证据：

```
慢性应激
  ├── 皮质醇/儿茶酚胺 → ROS↑、DNA损伤↑ → 端粒损耗↑、端粒酶↓(Epel 2004)
  ├── FKBP5 表观上调 → NF-κB 炎症通路↑ → 心血管风险(Zannas 2019)
  ├── 海马 GR 负荷↑ → 海马萎缩、记忆损害(Lupien 1998)
  ├── 慢性炎症: IL-6/CRP↑(Kiecolt-Glaser 2003)、GR抵抗(Cohen 2012)
  ├── 免疫抑制: 疫苗应答↓、NK 活性↓、初始T细胞↓(Segerstrom & Miller 2004)
  └── 代谢: 内脏脂肪↑、胰岛素抵抗 → 代谢综合征(Chandola 2006)
```

- **端粒与端粒酶**：Epel 与 Blackburn 2004 年发表于 PNAS 的开创性研究（n=39 照护慢性病患儿的母亲 vs 19 对照）首次把心理应激与细胞衰老标志直接相连——照护组外周血白细胞端粒更短（相当于额外老化约 10 年）、端粒酶活性更低，且与主观压力感知和皮质醇水平相关。机制链：糖皮质激素与儿茶酚胺升高 → 氧化应激与 DNA 损伤 → 端粒加速损耗；糖皮质激素还被机制研究表明可下调端粒酶转录。
- **表观时钟**：慢性应激可通过表观遗传修饰加速"表观年龄"。Zannas 2019（PNAS）证明衰老与应激协同表观上调 FKBP5（GR 伴侣蛋白基因），增强 NF-κB 驱动的炎症并升高心血管风险——这是"应激→表观改变→炎症→疾病"的完整通路证据。
- **海马萎缩（Sapolsky 的糖皮质激素级联假说）**：Sapolsky 1986 年提出长期高皮质醇损伤海马（GR 高密度区），形成"应激→皮质醇↑→海马损伤→负反馈减弱→皮质醇更高"的级联；Lupien 1998（Nat Neurosci）在老年人中证实高皮质醇者 4 年随访海马萎缩更快、记忆更差。
- **代谢综合征**：Whitehall II 队列（Chandola 2006，n=10,308，12 年随访）显示慢性工作压力者代谢综合征风险约为无压力者的 2 倍；机制上高皮质醇促进内脏脂肪堆积与胰岛素抵抗，脂肪组织再分泌炎症因子，形成"应激→肥胖→炎症→更多应激"的恶性循环。

### 3. 压力与 NO：交感-内皮轴

压力通过多条路径压制 NO 通路：

```
慢性应激
  ├── 交感持续激活 → α1-AR 血管收缩 → 剪切力↓ → eNOS 激活信号↓
  ├── 皮质醇↑ → GR 信号抑制 eNOS(NOS3) 表达/活性（机制研究表明）
  ├── 应激相关炎症 → iNOS/超氧↑ → ONOO⁻ → eNOS 解偶联、NO 生物利用度↓
  └── 迷走张力↓ → 内皮 M 受体刺激↓ → eNOS 激活减少（迷走-内皮轴失活）
        ──▶ 内皮功能障碍: FMD↓、动脉僵硬度↑、血压↑
```

- 应激急性发作时交感释放的 NE 经 α1-AR 收缩血管，血流剪切力下降直接减少 eNOS 激活（剪切力是 eNOS 最强的生理激活信号）；肾上腺素则升高心率与心输出量，增加血管搏动负荷。
- 慢性皮质醇经 GR 抑制 eNOS 转录与活性的机制已有动物与细胞支持，同时糖皮质激素促进血管平滑肌对缩血管物质的敏感性——"应激性高血压"与内皮功能障碍在压力人群中被反复观察到。
- 反向通路同样成立：迷走释放乙酰胆碱（ACh）作用于内皮 M3 受体 → 细胞内 Ca²⁺↑ → eNOS 激活 → NO↑ → 血管舒张。这条"迷走-内皮轴"使减压干预（慢呼吸、冥想）具备直接的血管学含义——动物实验显示迷走刺激升高血浆 NO，人的小型研究也观察到冥想/慢呼吸后 FMD 或血浆亚硝酸盐改善（详见 03-immunity/06-neuro-immune-axis.md 的 NO 章节）。

### 4. HRV 的生理学基础：自主神经如何雕刻每一次心跳

HRV 测量的是逐次心跳间隔（R-R 间期）的变异，其来源是窦房结的自主神经双重调控：

```
窦房结固有频率 ≈ 100-110 次/分（无自主神经支配时）
        │
 迷走(副交感) ── ACh → M2受体 → Gi → cAMP↓ → If电流↓ → 心率↓（快，<1s起效）
        │
 交感 ── NE → β1受体 → Gs → cAMP↑ → If电流↑ → 心率↑（慢，数秒-数十秒）
        │
 逐搏变异 = 迷走对窦房结的"呼吸性刹车"强弱
        呼吸 → 肺牵张感受器 → 迷走传出抑制(吸气) / 激活(呼气)
        → 呼吸性窦性心律不齐(RSA) —— HRV 的呼吸分量
```

- **核心概念**：迷走纤维传导快（毫秒级）且对窦房结的抑制是"逐搏"的，因此短时 HRV 几乎完全反映迷走张力；交感贡献需要数秒至数十秒，主要体现于更长窗口与特定频段。**高 HRV = 迷走刹车灵活 = 心脏"容错"能力强**；低 HRV = 交感主导、调节僵硬。
- **常用指标**：
  - **SDNN**：全部 R-R 间期的标准差，反映总变异（长时记录，如 24h；短时 5 分钟也可用），综合评估自主神经总调节能力；
  - **RMSSD**：相邻 R-R 间期差值的均方根，主要反映迷走介导的快速调节，是静息短时测量的首选；
  - **HF（高频功率，0.15-0.4 Hz）**：与呼吸频率重叠，几乎纯迷走介导；**LF（低频功率，0.04-0.15 Hz）**：受交感与迷走共同影响，0.1 Hz 附近含压力反射相关的 Mayer 波分量；
  - **LF/HF**：曾被广泛用作"交感/副交感平衡比"，但学界已明确批评——LF 并非纯交感指标，LF/HF 在静息与短时记录中的解释力有限，其"平衡比"含义已不被主流认可（见开放问题）。
- **神经内脏整合模型**（Thayer & Lane 2009）：HRV 不只是心脏指标——前额叶皮层（尤其腹内侧前额叶）对杏仁核等情绪中心的抑制性控制强度与迷走张力同源，故 HRV 同时是"自我调节灵活性""情绪调节能力""执行功能"的窗口。低 HRV 个体在压力下更难"刹车"，更容易滑向焦虑、冲动与炎症性应激反应。
- **正常参考与随龄变化**：健康成人短时 RMSSD 多在 25-60 ms 区间（<25 ms 提示迷走张力偏低），SDNN 随记录时长增加；HRV 随年龄递减（迷走张力随龄下降约每十年数个百分比），性别、体位、呼吸频率、昼夜节律均影响绝对值——这也是测量必须标准化的原因。

### 5. 低 HRV 与健康结局：从死亡风险到炎症

| 结局 | 关联方向 | 代表研究 |
|---|---|---|
| 全因死亡 | SDNN↓ → 风险↑，独立于传统危险因素 | Framingham（Tsuji 1994，老年队列） |
| 心血管事件 | 低 HRV → CHD/心源性死亡↑ | ARIC（Dekker 2000，2 分钟记录即可预测） |
| 炎症水平 | 低 HRV ↔ CRP/IL-6 升高共现 | Haensel 2008 综述 |
| 抑郁/焦虑/倦怠 | 慢性压力人群 HRV 系统性偏低 | Thayer 2010 综述 |
| 压力-恢复失衡 | 夜间 HRV 恢复不足 → 次日疲劳累积 | 压力生理学多项队列 |

Framingham 老年队列（Tsuji 1994）与 ARIC 研究（Dekker 2000）一致显示低 HRV 与全因死亡、冠心病风险升高相关——ARIC 中仅 2 分钟节律条的低 SDNN 即可预测 9 年随访的死亡与冠心病（HR 约 1.4-1.6）。机制上，低 HRV 是"自主神经失衡"（迷走不足 + 交感亢进）的读数，而自主神经失衡直接介导心律失常易感性、血压调节失灵、炎症反射制动失效（迷走抗炎通路——胆碱能抗炎通路 CAP 见 03-immunity 篇）与胰岛素抵抗。HRV 与炎症的双向关联尤其值得注意：低迷走张力 → 炎症反射失灵 → 炎症升高；炎症（TNF-α、IL-6）又可抑制迷走传出——形成"低 HRV ⇄ 炎症"的自我强化环，这使 HRV 训练（提升迷走张力）同时是抗炎策略。

## 证据分级

| 现象 | 证据等级 | 关键证据/文献 |
|---|---|---|
| 慢性应激缩短端粒、降低端粒酶（人） | 强关联（小样本经典研究+后续复制） | Epel 2004 PNAS；后续队列方向一致但效应量不一 |
| 慢性应激升高炎症（IL-6/CRP） | 实锤（前瞻队列+meta） | Kiecolt-Glaser 2003；Segerstrom & Miller 2004 |
| 慢性应激→GR 抵抗→NF-κB 上调 | 强关联（人体转录组+动物机制） | Miller 2008；Cohen 2012 |
| 高皮质醇→海马萎缩、记忆损害 | 强关联（人体纵向+动物） | Sapolsky 1986 假说；Lupien 1998 |
| 慢性压力→代谢综合征 | 强关联（大型队列） | Chandola 2006（Whitehall II） |
| 低 HRV 预测全因死亡/心血管事件 | 实锤（大型队列+meta） | Tsuji 1994/1996；Dekker 2000 |
| 低 HRV 与炎症标志物共现 | 强关联（多项横断面） | Haensel 2008 |
| 慢呼吸（~6 次/分）升高 HRV/压力反射敏感性 | 实锤（机制+人体实验） | Bernardi 2001；Zaccaro 2018 系统综述 |
| HRV 生物反馈改善压力/焦虑结局 | 中-强（meta，中小效应） | Lehrer & Gevirtz 2014；Goessl 2017 |
| 冥想降低心理压力 | 中（meta，中等证据） | Goyal 2014 |
| 冥想/静修提升端粒酶活性 | 中-弱（小样本 RCT） | Epel 2013 |
| 瑜伽降低皮质醇、改善自主神经指标 | 中（RCT 系统综述） | Pascoe & Bauer 2015 |
| 太极改善心理幸福与压力 | 中（meta，中小效应） | Wang 2010 |
| 森林浴提升副交感、降皮质醇 | 中（现场实验，样本有限） | Park 2010 |
| 呼吸+冷暴露减弱内毒素炎症反应 | 中（单中心小样本人体实验） | Kox 2014 |
| 冷暴露慢性适应升高静息 HRV | 弱-矛盾（证据异质） | 多项小型研究结论不一 |

## 临床/实验证据细节

**端粒与压力（Epel 2004）**：39 名长期照护慢性病患儿的母亲 vs 19 名健康子女母亲，按主观压力评分分组。高压力组外周血单核细胞端粒显著更短（相当于约 10 年额外老化，研究报告范围约 9-17 年）、端粒酶活性更低；压力感知与皮质醇水平呈正相关。局限：横断面、样本小、照护组为特殊人群——后续队列部分复制但效应量不一，故定级"强关联"而非实锤。

**冥想与端粒酶（Epel 2013）**：30 名受试者参加 3 个月密集冥想静修，对照组 30 人同期度假/日常。静修组外周血端粒酶活性较对照组高约 30%，并伴随心理指标改善（负面情感下降、控制感与正念上升）。样本小、无主动对照，机制（端粒酶活性变化的中介路径）未定——"冥想→端粒"证据链仍在早期。

**慢呼吸（~6 次/分）的生理学**：Bernardi 2001（BMJ）发现念玫瑰经祈祷与瑜伽诵经（均约 6 次/分的呼吸节奏）显著提高压力反射敏感性与 HRV——首次证明"呼吸节奏本身"而非内容起效。Zaccaro 2018 系统综述汇总慢呼吸（尤其 0.1 Hz 附近）的效应：肺牵张感受器激活→迷走传出增强、0.1 Hz 呼吸与 Mayer 波/压力反射共振→血压波动放大→压力反射训练、以及经 CO₂ 与中枢化学感受器的间接效应。临床衍生：心率呼吸同步（心率-呼吸共振）训练被整合进 HRV 生物反馈。

**HRV 生物反馈**：Lehrer & Gevirtz 2014 综述确立了"共振频率呼吸"方案（个体化测定约 0.1 Hz/6 次/分的呼吸频率使 HRV 最大化），报告对哮喘（肺功能与生活质量）、高血压、抑郁、焦虑、失眠的改善；Goessl 2017 meta 分析显示 HRV 生物反馈对压力相关心理结局与认知/运动表现有中小效应量（不同结局 g 约 0.3-0.8），优于等待名单对照，但与主动对照相比优势缩小。

**瑜伽与太极**：Pascoe & Bauer 2015 系统综述（RCT）显示瑜伽训练降低皮质醇、改善 HRV 与血压、减轻焦虑抑郁；Wang 2010 meta 显示太极改善抑郁、焦虑与压力感知（中小效应）。两者共同点：低-中等强度运动 + 呼吸控制 + 正念注意，是"运动-呼吸-心理"三联干预的自然组合。

**森林浴（Shinrin-yoku）**：Park 2010 在日本 24 片森林对 280 名受试者的现场实验显示，森林环境较城市环境显著降低皮质醇、降低脉率、提高副交感（HF）并降低交感（LF/HF）指标——效应在 15 分钟步行后即出现。机制推测涉及萜烯类植物挥发物、感官放松与注意力恢复。

**呼吸+冷暴露（Kox 2014）**：12 名受试者经 10 天训练（冥想+过度换气式呼吸练习+渐进冷暴露，即 Wim Hof 法核心组件）后接受静脉内毒素（LPS 2 ng/kg）挑战，较 12 名对照的细胞因子反应（TNF-α、IL-6、IL-8、IL-10）显著减弱，同时血浆肾上腺素在挑战期显著升高——提示交感-儿茶酚胺轴对固有免疫反应的主动调节。注意：该方案含过度换气，存在低碳酸血症、晕厥与低钠血症风险，且有研究者对"免疫抑制的可取性"提出质疑；不可自行模仿为常规练习。冷暴露对静息 HRV 的慢性适应证据则高度异质（急性升高交感、慢性适应研究结论矛盾），冷热交替疗法应视为"待定证据、谨慎执行"。

**压力与睡眠的恶性循环**：慢性压力升高觉醒水平、碎片化睡眠；实验性睡眠限制一致显示次日 HRV 下降、交感张力升高、炎症标志物上升；睡眠又反向调节皮质醇节律与 HPA 轴敏感性。睡眠是"压力-恢复"循环的恢复端，改善睡眠常先于任何减压训练见效（详见 07-interventions 睡眠篇目）。

## 与 NO / NAD+ / 长寿网络联系

- **迷走-内皮- NO 轴**：迷走释放 ACh → 内皮 M3 受体 → eNOS → NO → 血管舒张。慢呼吸与冥想提升迷走张力的同时即提升这条轴的输出；小型研究观察到冥想/慢呼吸后 FMD 或血浆亚硝酸盐改善。一个有趣的旁证：Weitzberg & Lundberg 2002 发现哼鸣（humming）使鼻腔 NO 升高约 15 倍（副鼻窦通气促进 NO 洗脱），提示呼吸节律与上呼吸道 NO 生物利用度存在直接物理联系——"慢呼吸→NO"的机制证据虽不完整，但方向一致。
- **压力 → NAD+ 消耗 → SIRT1 抑制**：慢性应激的氧化应激与 DNA 损伤激活 PARP1，大量消耗 NAD+；NAD+ 下降 → SIRT1 活性↓ → NF-κB p65 乙酰化↑（促炎）、eNOS 去乙酰化减少（eNOS 活性↓、NO↓）→ 内皮功能障碍与炎症。这构成"压力 → NAD+ ↓ → SIRT1 ↓ → NO ↓ / 炎症 ↑"的恶性循环，是压力管理与 NAD+ 补充（NMN/NR，详见 04-drugs 篇目）交叉的分子界面。
- **皮质醇与 SIRT1 的交互**：GR 活性受 SIRT1 去乙酰化调节，SIRT1 又是皮质醇抗炎与代谢效应的调节节点——"NO-NAD+-SIRT1-糖皮质激素"在应激系统内多点耦合（详见 03-immunity/06-neuro-immune-axis.md）。
- **双刃剑提醒**：应激相关炎症局部 iNOS 高表达产生大量 NO，与超氧生成 ONOO⁻ 介导硝化损伤；同时系统性 eNOS/NO 供给下降——与全库"NO 双刃剑"主线一致（详见 01-foundations/03-no-basics.md）。

## 干预方向与可执行建议

按证据强度与成本排序（优先级从高到低）：

1. **睡眠优先**：保证 7-8 小时、规律作息——睡眠是 HPA 轴与迷走张力的"恢复端"，效果先于一切训练。
2. **规律有氧运动**：每周 ≥150 分钟中等强度，唯一同时提升迷走张力（HRV↑）、降炎症、改善内皮功能（剪切力→eNOS）的成熟干预。
3. **慢呼吸训练**：每日 10-20 分钟、4-6 次/分（吸 4 秒呼 6-8 秒），呼气相延长尤其增强迷走；可配合心率带做 0.1 Hz 心率呼吸同步。
4. **正念/冥想（MBSR 式）**：每周 3-5 次、每次 20-40 分钟；对压力感知与焦虑有中等证据。
5. **瑜伽/太极**：每周 2-3 次，兼具运动+呼吸+注意训练。
6. **社交支持与自然接触**：每周 ≥2 小时户外/森林环境；社会联结是慢性应激的强缓冲。
7. **冷热交替**：证据待定、谨慎执行——从温水逐步过渡，心血管疾病与高血压未控者避免；不可模仿含过度换气的激进方案。
8. **HRV 监测与生物反馈**：晨起同一时间、同一姿势（静坐或平躺）测 3-5 分钟，用 RMSSD 与 7 天滚动均值看趋势而非单点；心率带（如 Polar H10）准确性优于光电手环。生物反馈设备（共振频率呼吸引导）可作进阶工具，但长期依从性决定效果。

**监测逻辑**：把 HRV 当"恢复仪表盘"而非竞赛分数——训练后次日晨起 RMSSD 低于个人基线（如 >2 周滚动均值的 20-30%）提示恢复不足，应减量；长期上升趋势提示迷走张力改善。

## 开放问题与争议

- **LF/HF 的解读争议**：LF 受迷走与交感共同影响，LF/HF 作为"交感/副交感平衡比"的经典解读已被主流生理学界质疑；商业设备普遍沿用该比值，可能误导用户。RMSSD/HF 仍是更稳妥的迷走指标。
- **HRV 是"因"还是"结果"**：低 HRV 究竟是健康恶化的驱动因、伴随标志还是结果？遗传（约 30-40%）、年龄、体位、呼吸、昼夜节律等混杂因素众多；尚无长期 RCT 证明"提升 HRV"本身转化为心血管或死亡终点获益——这是 HRV 训练最大的证据缺口。
- **冥想/生物反馈的独立效应量**：与主动对照（而非等待名单）相比，冥想与 HRV 生物反馈的效应量明显缩小（Goyal 2014；Goessl 2017），其独立于运动、睡眠、社会支持的增量获益可能被高估。
- **"减压→端粒/表观"的效应量**：Epel 2004 与 2013 的效应令人瞩目但样本小、机制中介未定；慢性压力对端粒的因果性在人体缺乏长期干预证据。
- **冷暴露证据矛盾**：冷暴露对静息 HRV 的慢性适应效应研究结论冲突，急性交感激活与慢性适应的剂量-反应关系未建立，且存在心血管风险人群的适用性争议。
- **测量的可重复性**：HRV 受姿势、呼吸频率、进食、咖啡因、月经周期、季节影响显著，跨设备可比性差；"晨起 5 分钟 RMSSD"虽是最常用的标准化方案，但不同人群的参考区间仍缺大型规范数据（本库标注：具体阈值待核实）。

## 参考文献

1. Epel ES, Blackburn EH, Lin J, et al. Accelerated telomere shortening in response to life stress. Proc Natl Acad Sci USA. 2004;101(49):17312-17315.
2. Epel E, Daubenmier J, Moskowitz JT, et al. Can meditation slow rate of cellular aging? Cognitive stress, mindfulness, and telomeres. Ann N Y Acad Sci. 2009;1172:34-53.
3. Epel ES, Puterman E, Lin J, et al. Meditation and vacation effects have an impact on disease-associated molecular phenotypes. Transl Psychiatry. 2013;3:e265.
4. Sapolsky RM, Krey LC, McEwen BS. The neuroendocrinology of stress and aging: the glucocorticoid cascade hypothesis. Endocr Rev. 1986;7(3):284-301.
5. Lupien SJ, de Leon M, de Santi S, et al. Cortisol levels during human aging predict hippocampal atrophy and memory deficits. Nat Neurosci. 1998;1(1):69-73.
6. Kiecolt-Glaser JK, Preacher KJ, MacCallum RC, et al. Chronic stress and age-related increases in the proinflammatory cytokine IL-6. Proc Natl Acad Sci USA. 2003;100(15):9090-9095.
7. Miller GE, Chen E, Sze J, et al. A functional genomic fingerprint of chronic stress in humans: blunted glucocorticoid and increased NF-κB signaling. Biol Psychiatry. 2008;64(4):266-272.
8. Cohen S, Janicki-Deverts D, Doyle WJ, et al. Chronic stress, glucocorticoid receptor resistance, inflammation, and disease risk. Proc Natl Acad Sci USA. 2012;109(16):5995-5999.
9. Segerstrom SC, Miller GE. Psychological stress and the human immune system: a meta-analytic study of 30 years of inquiry. Psychol Bull. 2004;130(4):601-630.
10. Chandola T, Brunner E, Marmot M. Chronic stress at work and the metabolic syndrome: prospective study. BMJ. 2006;332(7540):521-525.
11. Zannas AS, Jia M, Hafner K, et al. Epigenetic upregulation of FKBP5 by aging and stress contributes to NF-κB-driven inflammation and cardiovascular risk. Proc Natl Acad Sci USA. 2019;116(23):11370-11379.
12. Tsuji H, Venditti FJ Jr, Manders ES, et al. Reduced heart rate variability and mortality risk in an elderly cohort: the Framingham Heart Study. Circulation. 1994;90(2):878-883.
13. Dekker JM, Crow RS, Folsom AR, et al. Low heart rate variability in a 2-minute rhythm strip predicts risk of coronary heart disease and mortality from several causes: the ARIC Study. Circulation. 2000;102(11):1239-1244.
14. Thayer JF, Yamamoto SS, Brosschot JF. The relationship of autonomic imbalance, heart rate variability and cardiovascular disease risk factors. Int J Cardiol. 2010;141(2):122-131.
15. Haensel A, Mills PJ, Nelesen RA, et al. The relationship between heart rate variability and inflammatory markers in cardiovascular diseases. Psychoneuroendocrinology. 2008;33(10):1305-1312.
16. Bernardi L, Sleight P, Bandinelli G, et al. Effect of rosary prayer and yoga mantras on autonomic cardiovascular rhythms: comparative study. BMJ. 2001;323(7327):1446-1449.
17. Zaccaro A, Piarulli A, Laurino M, et al. How breath-control can change your life: a systematic review on psycho-physiological correlates of slow breathing. Front Hum Neurosci. 2018;12:353.
18. Lehrer PM, Gevirtz R. Heart rate variability biofeedback: a new tool for improving autonomic homeostasis and treating disease. Appl Psychophysiol Biofeedback. 2014;39(1):1-11.
19. Goessl VC, Curtiss JE, Hofmann SG. The effect of heart rate variability biofeedback on performance psychology: a systematic review and meta-analysis. Appl Psychophysiol Biofeedback. 2017;42(3):139-161.
20. Goyal M, Singh S, Sibinga EMS, et al. Meditation programs for psychological stress and well-being: a systematic review and meta-analysis. JAMA Intern Med. 2014;174(3):357-368.
21. Pascoe MC, Bauer IE. A systematic review of randomised control trials on the effects of yoga on stress measures and mood. J Psychiatr Res. 2015;68:270-282.
22. Wang C, Bannuru R, Ramel J, et al. Tai Chi on psychological well-being: systematic review and meta-analysis. BMC Complement Altern Med. 2010;10:23.
23. Park BJ, Tsunetsugu Y, Kasetani T, et al. The physiological effects of Shinrin-yoku (taking in the forest atmosphere or forest bathing): evidence from field experiments in 24 forests across Japan. Environ Health Prev Med. 2010;15(1):18-26.
24. Kox M, van Eijk LT, Zwaag J, et al. Voluntary activation of the sympathetic nervous system and attenuation of the innate immune response in humans. Proc Natl Acad Sci USA. 2014;111(20):7379-7384.
25. Weitzberg E, Lundberg JO. Humming greatly increases nasal nitric oxide. Am J Respir Crit Care Med. 2002;166(2):144-145.
26. McEwen BS. Protective and damaging effects of stress mediators. N Engl J Med. 1998;338(3):171-179.
27. Thayer JF, Lane RD. Claude Bernard and the heart-brain connection: further elaboration of a model of neurovisceral integration. Neurosci Biobehav Rev. 2009;33(2):81-88.

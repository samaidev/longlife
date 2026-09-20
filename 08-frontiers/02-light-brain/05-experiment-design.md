# 05 实验设计：验证「光照 → 下丘脑 → 逆龄」假说的研究方案

> 专题：光照-脑-逆龄（Light-Brain Rejuvenation）· 第 5 篇 / 共 5 篇
> 定位：把「光/声分层靶向 → 下丘脑 SIRT1 → 全身逆龄」假说链拆成可独立证伪的环节，给出动物与人体两级实验设计、生物标志物体系、统计方案与可行性评估
> 关联篇目：PBM 机制见本专题 01-photobiomodulation.md；频谱工程见 02-light-spectrum.md；下丘脑 SIRT1 开关见 03-hypothalamus.md；聚焦超声见 04-fus.md；NO 通路总览见 01-foundations/03-no-basics.md；NAD⁺/SIRT1 网络见 01-foundations/04-nad-sirtuin.md

---

## 一、核心概念

**一句话定义**：光照-脑-逆龄实验设计是把「特定光照（tPBM 浅层）+ 聚焦超声（FUS 深部）→ 下丘脑 SIRT1/NO 激活 → 神经-内分泌/自主神经/体液三大广播通路 → 外周代谢、炎症、节律改善 → 衰老时钟减速」这条因果链，转化为**可证伪、可重复、可归因**的验证工程的整套方法论——包括假说拆分、对照与盲法、样本量与效应量、动物与人体验证阶梯、终点指标选择、混杂控制与统计推断。

**为什么重要**：物理干预（光/声）与化学药有本质区别——剂量窗口窄（PBM 呈 Arndt-Schulz 双相曲线，低剂量刺激、高剂量抑制）、安慰剂效应强（主观终点尤其）、个体差异巨大（颅骨厚度、晶状体黄化、年龄、季节），且「光到不了下丘脑」的物理瓶颈（光衰减 >99%，详见 04-fus.md）使因果归因极易断裂。设计不当的试验既可能把安慰剂当疗效（假阳性），也可能因剂量错误否定真实效应（假阴性）。本专题前四篇给出了机制底座，本篇回答工程问题：**怎么证明它？**

**与抗衰的关系**：该设计是连接「机制假说」与「临床转化」的桥梁——若阳性结果成立，将首次把「物理能量干预 → 中枢时钟」确立为可注册的衰老干预路径；若阴性，则精确指出假说链在哪一环断裂，为后续修正提供坐标。

---

## 二、假说梳理：因果链全链条与逐环证伪

### 2.1 完整链条（五环节模型）

```
【干预层】tPBM（头皮 810nm LED）＋ LIFU（靶向 DMH/LH 邻近区，微泡辅助）
    │
    ▼ 环节 E1：能量-分子转导
浅层：光子 → 线粒体 CCO 金属中心 → NO 光解离 → 呼吸恢复、ATP↑、eNOS/NO 释放
深层：声辐射力/稳定空化 → 机械敏感通道（Piezo1）→ Ca²⁺ 内流 → AMPK 激活
    │
    ▼ 环节 E2：中枢长寿网络
SIRT1 活性↑（NAD⁺/NADH 比↑ 供底物）→ 去乙酰化 PGC-1α（代谢）、FOXO（应激）、
NF-κB p65（抗炎）、p53、时钟蛋白；DMH/LH 特异下游转录因子 Nkx2-1 上调
    │
    ▼ 环节 E3：三大广播通路
① 神经-内分泌：PVN-CRH→HPA 轴、ARC-GnRH→HPG 轴、GHRH→GH/IGF-1 轴
② 自主神经：交感/迷走张力再平衡 → 外周血管、心率变异性（HRV）、产热
③ 体液/外泌体：血浆外泌体 miRNA（如 htNSC 分泌组）、细胞因子、代谢物
    │
    ▼ 环节 E4：外周表型
代谢（糖耐量、体脂）、炎症（IL-6/TNF-α/CRP↓）、循环（FMD、脑血流）、
昼夜节律（睡眠结构）、认知（海马可塑性、BDNF）
    │
    ▼ 环节 E5：衰老终点
表观时钟减速（甲基化/转录组）、健康span 延长、生存曲线右移（动物）
```

### 2.2 每环节的证伪策略与独立验证手段

| 环节 | 核心问题 | 验证手段 | 若失败的含义 |
|---|---|---|---|
| E1 | 光/声是否真的激活目标分子？ | 体外光谱学（CCO 吸收=作用光谱）、CCO 抑制剂/NO 清除剂（cPTIO）正交验证、Piezo1 敲除细胞系 | 能量-分子转导假说错误，或剂量不对 |
| E2 | 中枢 SIRT1 是否被特异性激活？ | SIRT1-Cre 报告小鼠、下丘脑 SIRT1 活性/乙酰化组、DMH/LH 免疫组化、Nkx2-1 表达 | 干预未达中枢，或中枢无响应 |
| E3 | 中枢信号是否外传？ | 血浆外泌体 miRNA 谱、CSF NOx/细胞因子、HRV 与 HPA 轴激素（皮质醇节律） | 广播通路假设错误，需换通路 |
| E4 | 外周表型是否改善？ | 糖耐量、炎症谱、FMD、睡眠 PSG、行为学 | 表型终点选择不当或效应量不足 |
| E5 | 表型改善是否转化为逆龄？ | 表观时钟、寿命/健康span | 「逆龄」叙事需降级为「改善」 |

**设计铁律**：链条必须逐环留痕。任一环节只有「机制终点」而没有「中间机制终点」的干预，其因果主张都是不完整的——这也是本设计区别于「只测一头一尾」的普通试验的核心。

---

## 三、证据分级：假说链各环节的现有证据基础

| 现象 | 证据等级 | 关键文献 |
|---|---|---|
| 光→CCO→NO 光解离→ATP↑（体外） | 实锤（可重复生化/光谱学） | Karu 1999; Hamblin 2018; Mason 2014 |
| 670nm 红光改善老龄组织线粒体功能 | 强（动物+初步人体） | Powner 2010（果蝇视网膜）; Begum 2013（老龄小鼠）; Shinhmar 2020（人体视网膜） |
| 经颅 PBM 改善人体认知/情绪 | 部分阳性、异质（样本小） | Barrett 2013（双盲 RCT）; Saltmarche 2017（病例系列） |
| 下丘脑 SIRT1 过表达延长小鼠寿命、延缓多组织衰老 | 实锤（动物因果，DMH/LH 特异性） | Satoh 2013（Cell Metab） |
| 下丘脑 NF-κB→GnRH 通路驱动全身衰老 | 实锤（动物因果） | Zhang 2013（Nature） |
| 光/声可选择性激活**人**下丘脑 SIRT1 | 无直接证据（机制推测） | 由 Satoh 动物数据外推，待人体验证 |
| FUS→Piezo1→AMPK→SIRT1 体内因果链 | 机制推测（体外通道数据外推） | Qiu 2019（iScience，体外）; 04-fus.md |
| FUS 经颅调控/BBBD 在人体可行 | 实锤（多项人体试验） | Elias 2016（NEJM）; Lipsman 2018; Legon 2014 |
| 表观时钟回拨 ⇔ 生物学逆龄 | 争议（相关性≠因果） | Horvath 2013; 见第八节讨论 |
| 光/声干预逆转**人体**生物年龄 | 无（尚无 RCT） | — |

结论：假说链的前半段（E1）证据最硬，中段（E2/E3）动物证据扎实但人体不可直接测量，末段（E5）人体 RCT 空白——**本实验设计要填的正是从「动物中枢开关」到「人体逆龄」的鸿沟**。

---

## 四、实验设计基本原则：对照、随机、盲法、样本量与混杂控制

### 4.1 对照与安慰剂效应

物理干预的对照设计比药物更微妙：

- **假光疗设备（sham device）**：外观、重量、佩戴位置完全一致的 LED 阵列，但 LED 不发光或仅输出无生物效应的非活性波长；这是 tPBM 双盲的可行基础——受试者无法从外观分辨。
- **FUS 假手术对照**：沿用 Elias 2016（NEJM）特发性震颤试验先例——换能器正常贴附、程序正常执行，但输出低于有效阈值或焦点偏置（不达消融/调控剂量）。受试者听到相同声音、经历相同流程。
- **阳性药理对照**：NAD⁺ 前体（NMN/NR）组作为「已知可抬升 NAD⁺ 的参照系」，用于标定试验灵敏度——若 NMN 组连外周 NAD⁺ 都不升，说明检测体系失灵，各组阴性不可信。
- **自然对照（no-treatment）**：评估试验本身（就诊、采血、光照史记录）的霍桑效应。

**盲法核查（blinding check）**：试验结束询问受试者与评估者「你认为自己/对方在哪个组」，若猜中比例显著偏离 50%，提示破盲，需在分析中报告并敏感性分析。tPBM 的主观终点（睡眠自评、情绪量表）安慰剂效应可达中等以上（效应量 d≈0.3–0.5 量级），因此**主终点必须包含客观指标**（表观时钟、炎症谱、HRV），主观量表仅作次要终点。

### 4.2 随机化与分层

采用**分层区组随机（stratified block randomization）**，分层因子按混杂强度排序：①年龄（如 60–69/70–79/80+）；②基线炎症（hsCRP <2 vs ≥2 mg/L）；③睡眠质量（PSQI ≤5 vs >5）；④BMI；⑤ApoE4 携带状态（影响认知终点解读）。区组长度 4–6，随机序列由独立统计师生成、密封信封/中央随机系统分配，研究者与受试者均不知晓。

### 4.3 关键混杂控制

| 混杂源 | 控制策略 |
|---|---|
| 饮食/运动 | 入组前 2 周基线记录，试验期维持习惯稳定（不要求改变），饮食用 3 日膳食日记 + 运动用活动记录仪量化 |
| 用药 | 排除正在使用 NAD⁺ 前体、二甲双胍、激素替代者；他汀/降压药等记录为协变量 |
| 光照史与季节 | 试验期佩戴照度计（lux 日志）记录全部光照暴露；入组按季节错峰（北半球冬季昼短、晨光不足会干扰节律终点），或把「季节」作为分层/协变量 |
| 颅骨厚度/头皮血流 | 入组 MRI/CT 测量颅骨厚度与额窦，纳入协变量；FUS 需个体化颅骨相位校正（k-Wave 仿真） |
| 晶状体黄化（老年） | 影响眼内蓝光通路但**不影响经颅红光**（不经眼）；作为亚组分析的既定因素 |
| 昼夜节律相位 | 所有检测固定时间窗（如晨 8–10 点空腹采血），避免昼夜节律污染炎症/皮质醇/时钟读数 |

### 4.4 效应量预估与样本量

依据标杆数据做保守预估（详见第八节统计部分）：表观时钟主终点按 Δ=1.5 年、SD≈4 年估算，每组约需 **112 例**（α=0.05，power=0.8，双侧）；若把主终点改为「时钟+炎症」复合或加大干预效应（Δ=2.5 年），每组可降至约 60 例。**效应量不确定是物理干预试验的常态，因此设计必须包含 II 期机制臂（先小样本验证靶点参与，再决定 III 期样本量）**，而非直接押注大样本。

---

## 五、动物实验设计（整链验证 + 机制因果）

### 5.1 小鼠模型选择

| 模型 | 特点 | 在本设计中的用途 |
|---|---|---|
| 自然衰老 C57BL/6（18–24 月龄） | 衰老表型渐进、贴近人 | 主模型：寿命 + 健康span + 时钟 |
| SAMP8（快速衰老小鼠） | 认知衰退早发、氧化应激高 | 加速验证认知与神经炎症终点（PBM 干预该模型的研究提示有益，具体文献待核实） |
| LMNA G609G / Zmpste24⁻/⁻（早衰模型） | 核纤层蛋白病、表观时钟加速 | 机制验证：干预能否在「加速时钟」上显示回拨 |
| APP/PS1 或 3xTg-AD | 淀粉样病理 | 亚研究：认知与病理终点 |
| SIRT1-Cre 报告/条件敲除小鼠 | 靶点可追踪/可消融 | E2 环节因果验证：光/声效应是否依赖下丘脑 SIRT1 |

### 5.2 光照参数（依据 01/02 篇剂量学）

- **波长**：810nm（近红外，颅骨穿透最优）为主臂；660nm（浅层对照臂）——两波长并行可检验「穿透深度-效应」梯度，直接测试「浅表光→深部信号」假说；
- **功率密度**：5–50 mW/cm²（无热效应区间）；
- **能量密度**：10–20 J/cm²/次（落在 01 篇给出的 1–60 J/cm² 临床窗口的中间偏上）；
- **频率**：每周 5 次（工作日）或隔日 3 次/周，持续 8–16 周（亚急性效应）；寿命实验则为终身方案（每周 5 次直至死亡）；
- **模式**：设连续 vs 脉冲（10–40Hz、50% 占空比）子臂——脉冲光穿透与效应在文献中反复被报告优于连续光（机制待定）；
- **FUS 参数**：0.2–0.5 MHz、机械指数 MI 0.2–0.6（稳定空化区）、微泡剂量按体重、被动空化检测（PCD）闭环监控，杜绝惯性空化（详见 04-fus.md）。

### 5.3 分组设计（2×2 析因 + 对照）

```
┌─────────────┬──────────────┬──────────────┐
│             │ 无 PBM       │ tPBM 810nm   │
├─────────────┼──────────────┼──────────────┤
│ 无 FUS      │ A 假手术对照  │ B PBM 单臂    │
│ FUS (DMH/LH)│ C FUS 单臂    │ D PBM+FUS 联合│
└─────────────┴──────────────┴──────────────┘
   + E 组：NMN（阳性药理对照）   + F 组：自然对照
```

析因设计的价值：可检验**交互项**（D 组效应是否 > B+C 之和，即「浅层光 + 深部声」是否存在协同）；代价是组数多、样本量大——若以寿命为终点，每臂 40–60 只雄鼠（雌鼠另计），总规模约 300–400 只，需与 ITP 式多中心分摊（见 5.5）。若经费受限，可先跑 A/B/D/E 四臂，把 C 臂后置。

### 5.4 终点指标体系

**生存与健康span（主终点）**：中位/最大寿命（Gompertz 拟合、log-rank 检验）；健康span 采用复合量表——转棒耐力、握力、自发活动（旷场）、步态。参照 ITP（Interventions Testing Program）标准：**三中心平行、随机化、盲法终点评估**，避免单中心偏倚（Miller 2007）。

**行为学**：旷场（自发活动/焦虑）、Morris 水迷宫（空间记忆）、新物体识别（识别记忆）——干预前基线、干预中、干预后三测，防学习效应需平行版本。

**组织学/分子**：DMH/LH 免疫组化（SIRT1、Nkx2-1、Iba-1 小胶质标志）、下丘脑乙酰化组（SIRT1 底物 PGC-1α/p53/NF-κB p65 乙酰化水平）、血浆外泌体 miRNA 谱、海马 BDNF。

**衰老时钟（小鼠）**：多组织 DNA 甲基化时钟（Petkovich 2017, Aging Cell；Lu 2023 pan-mammalian 时钟）——从血液+下丘脑+肝脏三组织测时钟，验证「中枢先行、外周跟随」的时间顺序。

**时间序列采样**：每 4 周尾静脉采血（时钟 + 炎症 + NOx 轨迹），观察效应是「渐升」还是「平台」，并锚定 E3 环节的「中枢→外周」信号传播时滞。

### 5.5 中间机制终点（本设计的特色）

为把「干预 → 下丘脑 → 外周」三段连接，设置**桥梁指标**：① 下丘脑 SIRT1 活性（酶活荧光法/底物乙酰化免疫印迹）与核团激活（c-Fos）；② 血浆外泌体 miRNA 组学（对应 Zhang 2017 发现的 htNSC 外泌体介导机制）；③ CSF（若可行）NOx 与细胞因子。**阳性判据：三桥指标与下游表型按预设方向共变**——若下丘脑 SIRT1 升了但外泌体信号未变、外周表型也未变，则 E3 广播通路假说被证伪；若外泌体变了但表型未变，则是 E4 环节问题。逐环定位是本设计区别于黑箱试验的根本。

---

## 六、人体试验设计（分层推进的 RCT 阶梯）

### 6.1 受试者选择

- **预防臂（健康衰老）**：60–80 岁，MMSE ≥26（认知正常）、无重大慢病急性期；目标：表观时钟/炎症/HRV 终点。
- **治疗臂（轻度认知障碍 MCI）**：60–85 岁，MoCA 19–25（MCI 窗）、无痴呆诊断；目标：认知量表 + 时钟终点，样本量需含 ApoE4 分层。
- **排除标准**：光敏性疾病（红斑狼疮、卟啉病）、视网膜病变、癫痫史（光/声刺激风险）、颅脑手术/金属植入（FUS 禁忌）、抗凝治疗（BBBD 出血风险）、脑肿瘤/淀粉样血管病（FUS 臂）、入组前 3 月内使用 NAD⁺ 前体或认知增强药。
- **招募**：社区筛查 + 老年科门诊转介；**知情同意须明示「物理干预、安慰剂对照、可能有安慰剂分配、FUS 臂为研究性应用」**。

### 6.2 干预方案（三臂 RCT + 机制臂）

**机制臂（先导，n≈15–20/臂）**：单次 FUS 或 tPBM 后 0/0.5/1/2/4/24/72h 密集采样——血浆 NOx、炎症因子、外泌体 miRNA、HRV 时间曲线。目的：① 验证「干预→外周信号」确实发生（E3 环节人体化）；② 确定效应峰值时间窗，为疗效 RCT 的终点测量时点提供依据。

**疗效 RCT（8–12 周）**：

| 臂 | 干预 | 频率 |
|---|---|---|
| A | tPBM（810nm LED 头皮阵列，10–20 J/cm²） | 每周 5 次 |
| B | tPBM + LIFU（靶向下丘脑邻近区，MI 0.2–0.6） | tPBM 每周 5 次 + LIFU 每周 2 次 |
| C | 假设备对照（双盲） | 每周 5 次 |
| D | tPBM + NMN/NR（250–1000 mg/d，开放标签阳性参照） | 每日 |

三臂双盲（A/B/C）+ 阳性参照（D）的折中：D 臂因药物外观无法盲，明确报告为开放标签，仅作「试验灵敏度」参照，不参与主分析。

### 6.3 结局指标（由硬到软排序）

- **主终点**：① 表观遗传年龄差（ΔAge，Horvath/PhenoAge/GrimAge 三种时钟预注册主选择）；② 炎症复合评分（hsCRP + IL-6 + TNF-α z 标准化）。
- **次要终点**：HRV（5 分钟静息，SDNN/RMSSD/LF-HF）、睡眠（腕戴活动记录仪 2 周 + 亚组 PSG 过夜）、认知（MoCA 总分与子域、CANTAB 执行功能/记忆）、情绪（PHQ-9/GAD-7）、FMD（肱动脉血流介导扩张）、生活质量。
- **机制终点**：血浆 NAD⁺/NADH（LC-MS/MS）、NOx（化学发光）、外泌体 miRNA 谱、PBMC SIRT1 蛋白水平。
- **影像子研究（亚组 n≈30）**：静息态 fMRI（默认网络连接）、FDG-PET（脑代谢）、下丘脑体积与胶质增生（T2/FLAIR，Thaler 2012 方法）、FUS 靶区 MRI 随访（安全性）。
- **安全性终点**：不良事件/严重不良事件、神经影像随访（微出血、BBB 完整性）、眼科学检查。

### 6.4 时长与随访

- 8–12 周干预（表观时钟可检测窗口，参照 FitzGerald 2021 的 8 周生活方式 RCT 实现 ~3 年时钟逆转的先例——说明 8 周足够看到时钟移动，但该研究无对照设计，本设计以随机对照为准）；
- 干预结束 0/4/12/24 周随访：检验**效应持续性**（时钟回拨是维持还是回弹——回弹则提示「持续刺激才能维持」，直接影响商业化与依从性策略）；
- 长期随访 ≥24 个月：安全性 + 事件性终点（跌倒、住院、MCI→AD 转化率，若样本允许）。

### 6.5 RCT 设计要点清单

① ClinicalTrials.gov 预注册（主终点、统计计划、亚组定义先于数据）；② 独立 DSMB 定期审查安全性；③ ITT 为主分析，PP 为敏感性分析；④ 盲法核查报告；⑤ 失访率预算 15–20%（老年人群偏高）；⑥ 交叉设计原则上**不采用**——表观时钟改变存在滞后与残留效应（carryover），交叉会污染阶段二基线，平行设计更稳；HRV 等快变量可考虑交叉，但不值得为它牺牲主终点。

---

## 七、生物标志物体系：测量什么、怎么测、局限在哪

| 维度 | 标志物 | 测量方法 | 局限/注意 |
|---|---|---|---|
| 表观年龄 | Horvath 353 CpG 时钟 | 全血 DNAm 芯片/测序 | 反映「甲基化年龄」非全部生物学年龄；血细胞组成变化可伪造时钟移动（需校正免疫细胞比例） |
| 表观年龄 | PhenoAge（Levine 2018） | 血液 DNAm + 9 生化指标算法 | 临床表型加权，对炎症敏感——与本研究主终点部分重叠，作敏感性分析 |
| 表观年龄 | GrimAge（Lu 2019） | 血液 DNAm 代理吸烟等 | 与死亡风险相关性强；吸烟史需协变量 |
| 表观年龄 | DunedinPoAm（Belsky 2020） | 血液 DNAm | 反映**衰老速率**而非年龄差，对短程干预更敏感 |
| 转录年龄 | PBMC 转录组时钟 | RNA-seq/芯片 | 组织特异、噪声大，作探索性 |
| SIRT1 轴 | PBMC SIRT1 蛋白/活性 | Western blot/荧光酶活 | 外周 ≠ 下丘脑；人下丘脑 SIRT1 **不可直接测量**——只能靠 CSF 外泌体 SIRT1/乙酰化底物间接推断（局限，如实报告） |
| NAD⁺ | 全血/PBMC NAD⁺、NADH、NAD⁺/NADH 比 | LC-MS/MS（金标准，Trammell 2016 方法）；比色循环法作粗筛 | 血液 NAD⁺ 与组织 NAD⁺ 相关性有限；采样后须立即处理防降解 |
| NO | 血浆硝酸盐+亚硝酸盐（NOx） | 化学发光（钒还原）或 LC-MS/MS；Griess 法灵敏度低 | NOx 受饮食（硝酸盐食物）影响大——试验期统一低硝酸盐餐食或空腹采样 |
| NO（功能） | 肱动脉 FMD | 超声内皮功能检测（Celermajer 1992 标准流程） | 需标准化：空腹、停咖啡、室温恒定；操作者盲法 |
| NO（分子） | eNOS S1177 磷酸化、S-亚硝基化蛋白组 | WB / SNO-RAC 富集质谱 | 仅限 PBMC 等外周样本 |
| 炎症 | hsCRP、IL-6、TNF-α、GlycA | 高敏免疫法/核磁 | 单次波动大——取 3 次基线均值；晨间固定时间 |
| 线粒体 | PBMC 高分辨呼吸（Oroboros）、膜电位 | 极谱法/荧光 | 侵入性采血量要求高；作为机制子研究 |
| 自主神经 | HRV（SDNN/RMSSD/LF/HF） | 5 分钟静息 RR 间期（Shaffer 2017 标准） | 呼吸、体位、昼夜节律强影响——固定时点、标准化呼吸 |
| 睡眠 | PSG（金标准）、活动记录仪 | 过夜多导 + 2 周腕戴 | 首夜效应（需适应夜）；老年睡眠碎片化基线差异大 |
| 神经影像 | 静息态 fMRI、FDG-PET、下丘脑体积/胶质增生 | MRI/PET | FUS 臂必须含 MRI 安全随访（微出血、BBB） |

**测量时序总原则**：所有动态指标（HRV、NOx、炎症、皮质醇）固定时间窗（晨 8–10 点空腹）；表观时钟采样间隔 ≥8 周（避免短期噪声）；机制臂时间曲线用于确定峰值时点。

---

## 八、统计方法：样本量、多重比较与亚组分析

### 8.1 样本量计算（示例，用 G*Power 复核）

- **主终点 A（表观时钟 ΔAge）**：预期干预组较安慰剂 −1.5 年（对照 FitzGerald 2021 生活方式干预 ~3 年/8 周，物理干预保守取半）、SD≈4 年、α=0.05 双侧、power=0.80 → **n≈112/臂**；三臂主分析需 112×3×1.15（失访 15% 膨胀）≈ 390 例。
- **主终点 B（炎症复合 z 评分）**：预期效应 d=0.4、SD=1.0 → n≈100/臂，与 A 相当，取大者。
- **认知（MoCA）**：Δ=1.5 分、SD=3.0 → n≈63/臂（次于主终点，可作次要终点）。
- **决策**：若总样本不可及，策略是「缩臂不减质量」——先跑 A/C 两臂双盲 RCT（n≈230 含失访）确立 tPBM 效应，FUS 臂留待 II 期阳性后追加；或把主终点改为「时钟+炎症」复合终点以提升检验效能。

### 8.2 分析计划要点

- **主分析**：ITT，混合效应模型（LMM）——固定效应：组×时间交互、分层协变量（年龄、基线炎症、季节）；随机效应：受试者。报告组间最小二乘均值差与 95% CI。
- **多重比较**：多终点采用 **FDR（Benjamini-Hochberg）** 校正；主终点（≤2 个）不做校正但预注册明确主次；亚组分析全部标记为探索性。
- **亚组（预设）**：年龄 ≥70、基线 hsCRP ≥2、PSQI >5、ApoE4 携带、颅骨薄/厚（影像中位数分组）——仅报告交互 P 值，不作结论性声明。
- **生存分析（动物）**：log-rank + Cox 比例风险（含性别分层）；Gompertz 拟合报告死亡率参数变化。
- **盲法核查**：χ² 检验猜中比例 vs 50%。
- **阴性结果处理**：预注册同时承诺报告阴性——「剂量不当」与「真无效」的区分依赖机制臂数据（若机制臂已证实靶点参与而 RCT 阴性，倾向剂量/时长问题而非假说错误）。

---

## 九、与 NO / NAD⁺ / 长寿网络联系（本库特色视角）

**实验可测的 NO 轴**：① FMD（内皮功能，NO 依赖）作为 NO 通路的**功能性读数**；② 血浆 NOx（化学发光）作为**浓度读数**；③ eNOS S1177 磷酸化（PBMC）作为**酶活读数**；④ 动物下丘脑 nNOS/eNOS 表达与 S-亚硝基化蛋白组作为**中枢读数**。四点合起来回答：光/声干预的血管与代谢获益是否真的经 NO 中介（详见 01-foundations/03-no-basics.md）。

**实验可测的 NAD⁺ 轴**：LC-MS/MS 测全血/PBMC NAD⁺、NADH 与比值——区分两类候选机制：tPBM 预期**抬升 NAD⁺/NADH 比**（呼吸恢复→NADH 氧化加速，复合体 I 的 NO 抑制解除），而 NMN/NR 阳性对照预期**抬升 NAD⁺ 总量**。两臂对比可直接检验「比值效应 vs 总量效应」哪条路径贡献逆龄表型——这是本设计独有的机制辨析能力。

**闭环假设**：光→CCO→NO 解离（呼吸恢复）→NAD⁺/NADH↑→SIRT1↑→PGC-1α（线粒体生物合成）→（线粒体健康）→更稳的 NAD⁺ 振荡；FUS→剪切力→eNOS→NO→血流↑→（氧供）→同上。若动物数据同时显示下丘脑 NAD⁺/SIRT1 上移与血浆 NOx 上移，则「物理干预→NO/NAD⁺ 双轴→逆龄」的统一叙事获得首个整合证据。

---

## 十、可行性评估与路线图

### 10.1 设备与成本

- **tPBM LED 阵列**：成熟商品，单台千元级，多台并行成本可控；剂量学校准（光功率计、空间均匀性）是主要技术工作。
- **FUS 系统**：MRI 引导相控阵为百万级设备，只能中心化（1–2 个具备超声-影像团队的三甲中心）；无 MRI 的便携 LIFU（固定靶区、CT 颅骨建模）为降级替代，但精度与安全监控打折。
- **检测成本**：DNAm 时钟 ~¥500–1000/样本、LC-MS/MS NAD⁺ ~¥300–500/样本——主终点测 3 次/人，占总预算大头，需专项经费。

### 10.2 伦理与监管

- **FUS 靶向人下丘脑**：属研究性应用（off-label），需伦理委员会 + 药监部门研究性器械审批；下丘脑邻近关键结构（视交叉、垂体柄），安全窗（MI、热指数、微出血监测）必须独立审查；建议先在**灵长类**补一组安全性/靶向性数据再进人体。
- **tPBM**：多数国家按一般医疗器械/美容设备管理（眼安全必须达标）；宣称「逆龄」涉医疗宣称，监管口径需预先沟通。
- **路线图**：

```
Phase 0（0–3 月）：剂量学标定（体外双相曲线）、k-Wave 声场仿真、SIRT1-Cre 鼠靶点确认
Phase 1（3–12 月）：动物整链（四臂析因）、8–16 周亚急性终点 + 寿命实验启动、安全性
Phase 2（12–24 月）：人体 I 期安全 + 机制臂（单次 FUS/tPBM 时间曲线）→ 决定剂量与终点时点
Phase 3（24–48 月）：双盲 RCT（三臂 + 阳性参照），主终点=表观时钟+炎症谱
Phase 4（48 月+）：阳性则多中心长期随访（≥24 个月）与监管申报；阴性则按环节定位修正
```

**多中心要点**：3–5 中心、统一 SOP 与设备批次校准、中心效应作为随机效应、独立核心实验室统一检测（时钟/NAD⁺/NOx 集中测，消除批间差）。

---

## 十一、预期结果与解释（预注册时写死，防止事后合理化）

| 结果模式 | 解释 | 后续动作 |
|---|---|---|
| tPBM 臂时钟减速 + 炎症↓ + HRV↑ 一致 | 「浅表光→深部信号」假说成立（E1/E4 联动） | 扩大样本、长期随访、机制深化 |
| 仅 FUS 臂（或 FUS+联合）有效 | 效应依赖深部靶向，浅层光不足 | 推进 FUS 管线，优化 tPBM 参数后再验证 |
| 联合臂显著优于两单臂 | 浅层+深部协同（交互项显著） | 联合方案注册开发 |
| 时钟移动但功能终点（认知/FMD/HRV）无变化 | 「时钟≠功能」——逆龄叙事必须降级为表观改变 | 重新审视时钟作为替代终点的资格 |
| 全部阴性但机制臂阳性 | 剂量/时长/终点灵敏度问题，非假说证伪 | 参数再标定、延长干预、换更灵敏时钟（DunedinPoAm） |
| 全部阴性且机制臂阴性 | 假说链 E1 即断裂 | 诚实报告，转向其他干预路径 |

---

## 十二、开放问题与争议

1. **「逆龄」的定义与测量之争**：表观时钟回拨是否等于生物学逆龄，学界远未共识——时钟是「衰老的读表」还是「衰老本身」尚无定论；本设计以「时钟+功能+炎症」三联证据而非单一时钟作结论，是应对此争议的务实姿态。
2. **人体下丘脑 SIRT1 不可直接测量**：所有中枢因果主张都只能靠 CSF 外泌体、影像与动物外推——「中枢开关」在人体验证中永远是间接证据，需在论文中如实声明。
3. **FUS 靶向人下丘脑的安全窗**：邻近视交叉、垂体、三脑室，反复 BBBD 的长期后果（CAA 微出血风险）未知——安全性数据门槛应高于普通神经调控。
4. **安慰剂与盲法的极限**：即便假机对照，受试者可能从热感/声音/皮肤反应猜出分组；tPBM 的热感几乎不可避免，盲法核查结果决定证据强度。
5. **组合干预的归因困境**：PBM+FUS+NMN 三者的交互效应在可行样本量下几乎无法干净拆解——析因设计组数随因子数指数增长，长期看需要序贯试验而非单一巨试验。
6. **剂量标准化缺失**：波长/功率/时间/脉冲参数空间巨大，本文参数是「基于现有文献的合理起点」而非金标准——Phase 0 剂量标定是整个设计的成败前提。

---

## 参考文献

1. Satoh A, Brace CS, Rensing N, et al. Sirt1 extends life span and delays aging in mice through the regulation of Nk2 homeobox 1 in the DMH and LH. Cell Metab. 2013;18(3):416-430.
2. Zhang G, Li J, Purkayastha S, et al. Hypothalamic programming of systemic ageing involving IKK-β, NF-κB and GnRH. Nature. 2013;497:211-216.
3. Satoh A, Brace CS, Ben-Josef G, et al. SIRT1 promotes the central adaptive response to diet restriction through activation of the dorsomedial and lateral nuclei of the hypothalamus. J Neurosci. 2010;30(30):10220-10232.
4. Elias WJ, Lipsman N, Ondo WG, et al. A randomized trial of focused ultrasound thalamotomy for essential tremor. N Engl J Med. 2016;375(8):730-739.
5. Legon W, Sato TF, Opitz A, et al. Transcranial focused ultrasound modulates the activity of primary somatosensory cortex in humans. Nat Neurosci. 2014;17(2):322-329.
6. Horvath S. DNA methylation age of human tissues and cell types. Genome Biol. 2013;14(10):R115.
7. Levine ME, Lu AT, Quach A, et al. An epigenetic biomarker of aging for lifespan and healthspan. Aging. 2018;10(4):573-591.
8. Lu AT, Quach A, Wilson JG, et al. DNA methylation GrimAge strongly predicts lifespan and healthspan. Aging. 2019;11(2):303-327.
9. Belsky DW, Caspi A, Corcoran DL, et al. DunedinPoAm DNA methylation composite as a timelier indicator of aging. eLife. 2020;9:e54870.
10. Petkovich DA, Podolskiy DI, Lobanov AV, et al. Using DNA methylation profiling to evaluate biological age and longevity interventions. Aging Cell. 2017;16(4):924-932.
11. Lu AT, Fei Z, Haghani A, et al. Universal DNA methylation age across mammalian tissues. Nat Aging. 2023;3:1144-1166.
12. Miller RA, Austad SN, Burke D, et al. An Aging Interventions Testing Program: study design and interim report. J Gerontol A Biol Sci Med Sci. 2007;62(10):1041-1059.
13. Powner MB, Goodman T, Knott A, et al. 670nm light treatment improves mitochondrial function in aged Drosophila retina. J Gerontol A Biol Sci Med Sci. 2010;65A(9):963-969.
14. Begum R, Powner MB, Hudson N, et al. Treatment with 670 nm light up regulates cytochrome C oxidase expression and reduces inflammation in an age-related macular degeneration model. Neurobiol Aging. 2013;34(12):2782-2790.
15. Shinhmar H, Grewal M, Sivapathasuntharam C, et al. Optically improved mitochondrial function redeems aged human visual decline. J Gerontol A Biol Sci Med Sci. 2020;75(9):e49-e52.
16. Barrett DW, Gonzalez-Lima F. Transcranial infrared laser stimulation produces beneficial cognitive and emotional effects in humans. Neuroscience. 2013;230:13-23.
17. Saltmarche AE, Naeser MA, Ho KF, et al. Significant improvement in cognition in mild to moderately impaired dementia patients treated with transcranial plus intranasal photobiomodulation: case series report. Photomed Laser Surg. 2017;35(8):432-441.
18. FitzGerald KN, Hodges R, Hanes D, et al. Potential reversal of epigenetic age using a diet and lifestyle intervention: a pilot randomized clinical trial. Aging. 2021;13(7):9419-9422.
19. Yoshino M, Yoshino J, Kayser BD, et al. Nicotinamide mononucleotide increases muscle insulin sensitivity in prediabetic women. Science. 2021;372(6547):1224-1229.
20. Martens CR, Denman BA, Mazzo MR, et al. Chronic nicotinamide riboside supplementation is well-tolerated and elevates NAD+ in healthy middle-aged and older adults. Nat Commun. 2018;9:1286.
21. Trammell SAJ, Schmidt MS, Weidemann BJ, et al. Nicotinamide riboside is uniquely and orally bioavailable in mice and humans. Nat Commun. 2016;7:12948.
22. Celermajer DS, Sorensen KE, Gooch VM, et al. Non-invasive detection of endothelial dysfunction in children and adults at risk of atherosclerosis. Lancet. 1992;340(8828):1111-1115.
23. Nasreddine ZS, Phillips NA, Bédirian V, et al. The Montreal Cognitive Assessment, MoCA: a brief screening tool for mild cognitive impairment. J Am Geriatr Soc. 2005;53(4):695-699.
24. Thaler JP, Yi CX, Schur EA, et al. Obesity is associated with hypothalamic injury in rodents and humans. J Clin Invest. 2012;122(1):153-162.
25. Shaffer F, Ginsberg JP. An overview of heart rate variability metrics and norms. Front Public Health. 2017;5:258.
26. Qiu Z, Guo J, Kala S, et al. The mechanosensitive ion channel Piezo1 significantly mediates in vitro ultrasonic stimulation of neurons. iScience. 2019;21:448-457.

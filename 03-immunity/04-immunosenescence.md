# 免疫衰老 Immunosenescence

## 核心概念

免疫衰老（immunosenescence）指免疫系统随年龄发生的系统性、进行性功能衰退：胸腺退化导致初始 T 细胞输出枯竭、TCR 库多样性收窄，记忆 T 细胞（尤其终末分化型）异常累积，B 细胞抗体质量与类别转换能力下降，NK 与固有免疫细胞功能改变，同时伴随慢性低度炎症（inflammaging）。它不是单一细胞群的失灵，而是造血系统"生产端"（胸腺/骨髓造血干细胞）、"分配端"（外周稳态增殖与克隆扩张）与"效应端"（效应/记忆分化）三者的协同失调。免疫衰老直接决定衰老人群三大医学后果——感染易感性与重症化（流感、新冠）、疫苗应答下降（血清转化率低、保护衰减快）、肿瘤免疫监视削弱，是"感染-肿瘤-衰弱"风险链的免疫学枢纽，也是 12 大衰老标志中"干细胞耗竭"与"慢性炎症"两大标志在免疫系统的交汇体现（详见 01-foundations/01-aging-hallmarks.md）。与抗衰的关系在于：免疫系统是少数"可部分重建"的系统——胸腺再生、运动、药物干预均显示可逆性证据，使其成为抗衰干预的富矿靶点。

## 分子机制全链条

### 1. 胸腺退化：源头萎缩

胸腺是初始 T 细胞（naïve T cell）发育的唯一器官，其退化（thymic involution）从青春期即启动，是免疫衰老的"上游引擎"：

```
FoxN1↓ ──▶ 胸腺上皮细胞(TEC)萎缩/凋亡
                │
  性激素↑(青春期) ├──▶ 皮质/髓质结构紊乱 ──▶ 阳性/阴性选择效率↓
                │
  PPARγ↑ ──▶ 脂肪细胞浸润取代实质 ──▶ 胸腺实质体积↓（60岁时≈青春期10-15%）
                │
                └──▶ IL-7 与自身肽-MHC 信号不足 ──▶ 初始T细胞输出↓
                                                      │
                                           TREC（T细胞受体切除环）↓
```

关键分子节点：**FoxN1** 是 TEC 命运的主控转录因子，FoxN1 表达随龄下降且与 TEC 萎缩互为因果（FoxN1 条件性过表达可部分逆转老年小鼠胸腺萎缩）；**AIRE**（自身免疫调节因子）在髓质 TEC 中驱动组织限制性抗原表达以执行阴性选择，其表达随龄下降，既削弱自身耐受筛选（与老年自身免疫风险上升相关），也降低阳性选择后 T 细胞的"合格出厂率"。性激素是程序性退化的直接驱动：青春期性激素骤升加速退化，去势/性激素消融（GnRH 激动剂）在啮齿动物与男性中均可部分恢复胸腺输出（TREC 上升）。影像学（MRI/CT 脂肪分数）与组织学证据一致：60 岁时胸腺实质多为脂肪组织替代，初始 T 细胞输出降至峰值的 ~1%，TREC 含量随龄约下降 1–2 个数量级。

### 2. 初始 T 细胞耗竭

成人外周初始 T 细胞库主要由胸腺输出（早期）与**外周稳态增殖**（IL-7/IL-15 驱动的低水平分裂）共同维持——den Braber 等（2012）的人体动力学研究显示，人类成年后初始 T 细胞主要靠外周自我更新而非胸腺输入。衰老时：IL-7 与 IL-15 信号敏感性下降、稳态增殖补偿不足，且初始 T 细胞自身端粒缩短、静息态维持受损（FoxO1/miR-181a 通路下调——miR-181a 降低 TCR 信号阈值，其随龄下降使初始 T 细胞活化阈值升高、克隆扩增应答变弱）。量化数据：**CD8⁺ 初始 T 细胞每十年约下降 20–30%**，CD4⁺ 初始 T 细胞下降较缓但同样显著；健康年轻人 CD8⁺ 库中初始表型约占 40–50%，65 岁以上仅剩 5–10%。初始 T 细胞减少直接导致对新抗原（新病原体、新疫苗、肿瘤新抗原）的首次应答能力下降——这是"老年人对陌生威胁反应差、对既往记忆尚可"的免疫学根源。

### 3. TCR 库多样性收窄

TCR 库多样性（repertoire diversity）是适应性免疫"防御广度"的直接度量。高通量 TCRβ 测序证据（Britanova 等 2014；Naylor 等 2005 光谱分型）显示：

- 克隆数随龄下降：老年个体外周 TCR 库中独特克隆数较年轻人少一个数量级以上，CD8⁺ 库比 CD4⁺ 收窄更严重；
- Shannon 多样性指数随龄单调下降，且与胸腺输出（TREC）正相关；
- **克隆性扩张**：少数大克隆（>0.1% 频率）占据越来越大比例的库空间，多为 CMV/EBV 特异性记忆克隆（"memory inflation"）——CMV 血清阳性老人中，CMV 特异性 T 细胞可占 CD8⁺ 记忆库的 10–25%；
- 多样性收窄的后果：对新病原肽段与肿瘤新抗原的可用克隆前体减少，疫苗应答和免疫治疗（如 PD-1 阻断）响应率随之下降。

```
胸腺输出↓ ──▶ 初始库输入不足
IL-7/IL-15稳态增殖补偿（克隆扩张）──▶ 大克隆膨胀、小克隆丢失
CMV/EBV慢性抗原驱动 ──▶ memory inflation
        ──▶ Shannon多样性指数↓、库偏斜度↑ ──▶ 新抗原应答缺口
```

### 4. 记忆 T 细胞累积与终末分化

反复抗原刺激驱动记忆 T 细胞向终末分化方向偏移，形成 **TEMRA**（CD45RA⁺CCR7⁻CD28⁻CD27⁻）与 **CD57⁺/KLRG1⁺** 效应记忆细胞累积。机制链：慢性抗原（CMV 为主）→ 反复 TCR 刺激 → CD28 表达丢失（CD28 是共刺激分子，其启动子区甲基化后不可逆沉默）→ 共刺激信号丧失 → 增殖能力受限但分泌 IFN-γ/TNF-α/perforin 能力保留；CD57⁺ 细胞端粒极短、处于增殖性停滞（pre-senescent）但促炎分泌活跃。健康年轻人 CD28⁻CD57⁺ 细胞占 CD8⁺ 比例 <5%，CMV 阳性老年人可高达 50–80%。这类细胞兼具"免疫占位"（挤占初始/中央记忆空间）与"SASP 样促炎"双重危害，是免疫衰老与炎症衰老的直接连接点。

### 5. 克隆性造血（CHIP）

造血干细胞（HSC）随龄累积体细胞突变，其中携带 DNMT3A、TET2、ASXL1 等驱动基因突变的克隆获得选择性优势并扩张，形成克隆性造血（clonal hematopoiesis of indeterminate potential，CHIP）。机制：衰老 HSC 中 DNA 损伤修复（尤其 NHEJ）缺陷 → 突变累积；DNMT3A（甲基转移酶）失活使 HSC 自我更新偏向、分化偏向髓系（老年 HSC 髓系:淋巴系输出比升高 5–10 倍）；TET2 失活促进髓系炎症分化（巨噬细胞促炎表型）。CHIP 的免疫学后果：突变的髓系克隆持续产生促炎细胞因子（IL-6、IL-1β、TNF-α），直接放大炎症衰老并削弱淋巴系输出，形成"造血-免疫-炎症"恶性循环。流行病学：65 岁以上人群 CHIP 检出率约 10%，携带者全因死亡风险升高约 40%（HR≈1.4，Jaiswal 2014），动脉粥样硬化性心血管病风险升高的主要贡献来自 TET2/DNMT3A 克隆（HR≈1.9，Jaiswal 2017）。

### 6. B 细胞衰老

B 细胞谱系随龄出现"产量下降+质量劣化"：

- 骨髓 B 细胞生成下降（B-1 与过渡 B 细胞减少），外周 B 细胞库向记忆表型偏移；
- **类别转换重组（CSR）与体细胞高频突变（SHM）缺陷**：Frasca 等（2008）证实老年 B 细胞中转录因子 E2A 与活化诱导脱氨酶（AID）表达显著下调，IgG/IgA 类别转换效率下降、抗体亲和力成熟不足；
- 抗体库多样性收窄，分泌的抗体亲和力低、广谱性差——直接表现是**疫苗应答差**：老年人流感疫苗血清转化率较年轻人低约 30–50%，抗体滴度峰值低、衰减快；
- 自身抗体（ANA、RF 等）检出率随龄升高（自身耐受筛选失效 + B 细胞调节失衡），与老年自身免疫病风险上升相关。

### 7. NK 细胞与固有免疫改变

NK 细胞总数随龄增加（CD56^dim CD57⁺ 成熟亚群累积），但**单细胞杀伤功能下降**：脱颗粒（CD107a）与细胞毒颗粒释放效率降低、ADCC 受损；NK 对肿瘤细胞与病毒感染细胞的清除率随龄下降。其他固有免疫：中性粒细胞趋化与吞噬功能↓；巨噬细胞吞噬与 M2 修复极化受损、M1 促炎极化增强；浆细胞样树突细胞（pDC）经 TLR7/9 诱导的 IFN-α 产生随龄显著下降（Agrawal 等 2007），削弱抗病毒第一道防线。固有免疫的净效应是"**炎症输出增加、防御效率下降**"的错配。

### 8. 炎症衰老（Inflammaging）

上述各环节汇聚为慢性低度炎症：NF-κB 与 NLRP3 炎症小体慢性激活 → IL-6、IL-1β、TNF-α、CRP 轻度升高（老年较青年升高约 2–4 倍）→ 进一步驱动 T/B 细胞功能紊乱、组织损伤与 SASP 扩散，构成免疫衰老与全身衰老的正反馈环。炎症衰老既是免疫衰老的结果，也是其放大器——"免疫衰老-炎症衰老互为因果"是当前领域核心争论之一（详见开放问题）。

## 证据分级

| 现象 | 证据等级 | 关键证据/文献 |
|---|---|---|
| 胸腺退化与初始 T 输出下降 | 实锤（人体影像+免疫学） | MRI/CT 脂肪分数；TREC 随龄下降 1–2 个数量级；den Braber 2012 |
| CD8⁺ naive T 每十年降 20–30% | 实锤（流式多队列） | 多项横断面队列，65 岁后 naive CD8⁺ 占比 5–10% |
| TCR 库多样性收窄 | 实锤（高通量测序） | Britanova 2014 深度 TCRβ 测序；Shannon 指数随龄↓ |
| CMV 驱动记忆膨胀（CD28⁻/CD57⁺ 累积） | 实锤（人体观察） | Wertheimer 2014；CMV⁺ 老人 CD28⁻CD57⁺ 可达 CD8⁺ 的 50–80% |
| 免疫风险表型（IRP）预测老年死亡率 | 强关联（前瞻队列） | 瑞典 OCTO/NONA：CD4:CD8<1 + CMV⁺ + CD28⁻ 累积预测 2 年死亡 |
| CHIP 与全因死亡/心血管风险 | 强关联（万人级外显子测序） | Jaiswal 2014（HR 1.4）、2017（CHD HR≈1.9） |
| B 细胞 AID/E2A 下调与疫苗应答差 | 强关联（机制+队列） | Frasca 2008；老年流感血清转化率低 30–50% |
| 炎症标志物升高预测残疾/死亡 | 强关联（前瞻队列） | IL-6/CRP 与老年死亡风险（Harris 1999 等） |
| 雷帕霉素改善老年疫苗应答 | RCT（小样本） | Mannick 2014/2018：依维莫司使流感疫苗抗体↑约 20%、呼吸道感染率↓约 30% |
| 大剂量/佐剂流感疫苗更有效 | RCT（大型） | Fluzone HD 相对保护力↑24.2%（DiazGranados 2014）；MF59 佐剂优于标准株 |
| 胸腺再生（GH+DHEA+二甲双胍） | 小样本人体+动物 | TRIIM 试验（Fahy 2019）：9 人中 7 人胸腺密度↑、表观年龄回退 2.5 岁 |
| 免疫"回春"（重编程/异时共生） | 动物实锤，人不可行 | 部分重编程胸腺再生；Conboy 2005 异时共生 |

## 临床/实验证据细节

**疫苗应答差异（最直接的临床表型）**：老年人对流感、新冠、带状疱疹疫苗的应答全面减弱。流感疫苗：65 岁以上血清转化率较 18–49 岁低 30–50%，抗体滴度峰值低且 6 个月内衰减更快；对策证据——大剂量三价疫苗 Fluzone HD（60 μg/株 vs 15 μg/株）在 65 岁以上人群将确诊流感相对风险降低 24.2%（DiazGranados 2014，NEJM，RCT n≈31,989）；MF59 佐剂疫苗（Fluad）亦显示优于标准株；带状疱疹重组亚单位疫苗 Shingrix（AS01 佐剂）在 ≥50 岁人群保护效力达 97.2%（Lal 2015，NEJM），是佐剂系统（AS01 激活 TLR4 与 cGAS-STING 通路增强固有免疫）挽救衰老疫苗应答的教科书级证据。

**雷帕霉素/依维莫司（mTOR 抑制）**：Mannick 2014（Sci Transl Med，RCT）给 65 岁以上老年人依维莫司 0.5 mg/日或 5 mg/周（低剂量，避开免疫抑制窗），流感疫苗（Fluzone）后抗体应答较安慰剂升高约 20%（0.5 mg 组显著）；2018 年随访试验显示低剂量 TORC1 抑制使老年受试者 1 年内呼吸道感染率降低约 30%（率比≈0.7）。机制：mTORC1 抑制降低 CD28⁻ 衰老 T 细胞比例、促进初始/记忆库更新与 Th1 型应答——"轻抑 mTOR"被证实是少数有 RCT 支持的人体免疫年轻化策略。

**胸腺再生人体试验**：TRIIM 试验（Fahy 2019，Aging Cell）给 51–65 岁男性联合生长激素（重组 hGH，每周 3 次小剂量）+ DHEA（50 mg/日）+ 二甲双胍（500 mg/日）12 个月：9 名受试者中 7 人胸腺 MRI 密度/体积增加（胸腺实质再生影像证据），血浆 TREC 升高，且表观遗传年龄（Horvath 时钟）平均回退约 2.5 岁。样本小、无对照、机制混杂（三种药各自贡献不明），但提供了"人体胸腺可逆"的首个综合证据。动物层面更明确：性激素消融（GnRH 激动剂）在男性志愿者中提升胸腺输出（Sutherland 2005，J Clin Invest）；FoxN1 过表达、FGF7/KGF（帕利夫明）、IL-7 补充在老年小鼠中均恢复胸腺结构与 T 细胞输出；部分重编程（OSKM 瞬时表达）可使老年小鼠胸腺再生、免疫库年轻化（致癌风险限制转化）。

**免疫风险表型（IRP）**：瑞典 OCTO/NONA 纵向研究（Wikby 等 2006）在 85 岁以上高龄老人中定义 IRP = 倒置 CD4:CD8 比值（<1）+ CMV 血清阳性 + CD28⁻ 细胞累积，IRP 携带者 2 年内死亡率显著升高且伴随 IL-6 升高——这是"免疫衰老标志物预测死亡"的最经典人体证据。T 细胞端粒长度、CD28⁻ 比例、血清 IL-6/CRP 目前是被反复验证的免疫衰老生物标志组合。

**CHIP 流行病学**：Jaiswal 2014（NEJM，n=17,182 外显子测序）显示 70 岁以上约 10% 存在 ≥2% 变异等位基因频率的 CHIP，携带者全因死亡 HR≈1.4，血液肿瘤风险升高约 10 倍；Jaiswal 2017（NEJM）进一步发现 CHIP 携带者冠心病风险升高（HR≈1.9，TET2 贡献最大），机制为突变髓系克隆分泌 IL-1β 促动脉粥样硬化——CHIP 已从"癌前状态"升级为"炎症性衰老加速器"，催生靶向 TET2 克隆与 IL-1β（卡纳单抗）的临床试验。

**CAR-T 与过继细胞治疗在老年人**：CAR-T（抗 CD19）已常规用于老年复发/难治淋巴瘤与急性淋巴细胞白血病（获批适应证即覆盖老年人），真实世界数据显示 ≥65 岁与年轻患者缓解率相近，但 CRS 与神经毒性发生率升高、需减量预处理；其意义在于证明"衰老宿主仍可工程化重建肿瘤杀伤免疫"。肿瘤免疫治疗（PD-1/PD-L1 阻断）在老年非小细胞肺癌中有效，但响应率与 TCR 多样性正相关——免疫衰老直接制约免疫治疗天花板（详见 03-immunity 目录其他篇目）。

**免疫衰老的"多组学刻画"与免疫时钟**：免疫衰老正从"单一标志物"走向"多组学免疫年龄"——基于 T/B/NK 细胞亚群流式数据、TCR 库测序、血清炎症因子谱与免疫细胞甲基化构建的"免疫时钟"（immune clock）可输出免疫年龄（ImmAge），且与表观时钟部分独立、互为补充。Alpert 2019（*PNAS*）基于细胞亚群比例构建的免疫年龄与生存强相关；Sayed 2021（*Nat Aging*）的免疫时钟整合免疫细胞组成与功能读数。**"免疫年龄 > 实足年龄"的个体（免疫早衰）即使整体健康，疫苗应答与抗感染能力也较差**——免疫时钟为"免疫年龄体检"提供了工具基础（与 [02-aging-clocks](../01-foundations/02-aging-clocks.md) 表观时钟互补：表观看全身、免疫看防御系统）。

## 与 NO / NAD+ / 长寿网络联系

- **iNOS/NO 抗菌功能随龄下降**：巨噬细胞经 iNOS 产生 NO 杀灭胞内病原（分枝杆菌、利什曼原虫等），老年巨噬细胞 iNOS 诱导缺陷、NO 产量下降，是老年结核等胞内感染高发的机制之一——免疫防御的"NO 缺口"。
- **NO 对 T 细胞的双向剂量效应**：低浓度 NO（eNOS/nNOS 来源）经 sGC/cGMP/PKG 促 T 细胞增殖与 Th1 分化；高浓度 NO（iNOS 来源，炎症微环境）经 S-亚硝基化修饰与凋亡通路抑制 T 细胞。衰老时 eNOS 下降（NO 不足）+ 炎症灶 iNOS 过表达（局部 NO 过高）并存，形成"系统性 NO 缺乏、局部硝化应激"的失衡格局，进一步紊乱 T 细胞极化（Th1/Th17 偏移）。
- **NO 抑制 NF-κB**：NO 直接 S-亚硝基化 NF-κB p65 的 Cys38 降低其 DNA 结合，或经 SIRT1 去乙酰化 p65——NO 供给不足使 NF-κB 去抑制，放大炎症衰老（详见 01-foundations/01-aging-hallmarks.md 细胞衰老条目）。
- **eNOS 保护胸腺微环境**：eNOS/NO 维持胸腺微血管内皮功能与灌注，衰老时 eNOS 下调 → 胸腺缺血性退化加速，形成"NO↓-胸腺退化"恶性循环；NO 亦调节 HSC 静息与归巢（eNOS 敲除小鼠 HSC 自我更新受损）。
- **NAD+/SIRT1 交叉**：NAD+ 下降 → SIRT1 活性↓ → NF-κB 乙酰化升高（促炎）、T 细胞代谢适应受损（SIRT1 调控 Treg/效应平衡）——NAD+ 前体（NMN/NR）改善老年免疫的部分机制即经 SIRT1 抗炎与 T 细胞功能维护；NO 与 NAD+ 在 SIRT1 轴深度耦合（详见 01-foundations/03-no-basics.md）。ONOO⁻（NO+超氧）介导的蛋白 3-硝基酪氨酸修饰随龄在组织累积，是"NO 双刃剑"在免疫衰老中的损伤侧体现。

## 干预方向与可执行建议

**已有人体证据（按证据强度排序）**：
1. **疫苗策略**：老年人接种大剂量流感疫苗（Fluzone HD）、MF59 佐剂疫苗与 AS01 佐剂带状疱疹疫苗（Shingrix）——RCT 证实可部分弥补免疫衰老，是最成熟、可立即执行的手段；
2. **运动**：规律有氧运动（中等强度，每周 ≥150 分钟）与高心肺适能者初始 T 细胞比例更高、CD28⁻ 衰老 T 细胞更少、NK 细胞毒性更好；耐力运动员白细胞端粒更长（Werner 2009）——运动是"免疫年轻化"成本最低的干预；
3. **低剂量 mTOR 抑制**：依维莫司/雷帕霉素低剂量改善疫苗应答与降低呼吸道感染（RCT 支持），但需监测血脂、血糖与感染风险，尚未获批用于免疫重建；
4. **营养与代谢**：维持维生素 D、锌、蛋白质充足；热量限制在灵长类中保存 TCR 多样性（Messaoudi 等），间歇性禁食/二甲双胍可能经 AMPK/自噬改善免疫代谢（证据中-弱）。

**在研前沿**：胸腺再生（GH+DHEA+二甲双胍组合、性激素消融、FoxN1/FGF7/IL-7 补充、胸腺类器官与胸腺移植——DiGeorge 患者胸腺移植已临床应用）；表观重编程（动物实锤、人类远未成熟）；senolytics 清除衰老免疫细胞（达沙替尼+槲皮素等，早期人体试验）；CHIP 靶向（IL-1β 阻断卡纳单抗 CANTOS 事后分析显示可降低携带者心血管事件）；CAR-T/过继细胞治疗（已在老年肿瘤患者常规应用）。

### 免疫年龄的"体检化"：个人可执行的监测与干预

基于免疫衰老的机制与证据，个人层面的"免疫年龄管理"可按三层落地：

**1. 监测层（低成本体检项目）**：血常规中的淋巴细胞亚群分析（CD4:CD8 比值、CD28⁻ 衰老 T 细胞比例——IRP 核心组分）、hsCRP/IL-6（炎症负担）、维生素 D 与锌（免疫底物）；条件允许时加 TCR 库测序或免疫时钟检测（新兴，价格较高）。

**2. 行为层（证据最强）**：①规律有氧运动（每周 ≥150 分钟中等强度）——初始 T 细胞比例更高、CD28⁻ 细胞更少、NK 功能更好；②疫苗策略——65 岁以上优先大剂量/佐剂流感疫苗（Fluzone HD/Fluad）、带状疱疹 Shingrix、肺炎球菌疫苗（PCV20/PPSV23 联合），这是"立即生效"的免疫抗衰手段；③充足睡眠（NK 细胞与初始 T 细胞夜间动员，见 [05-sleep-optimization](../07-interventions/05-sleep-optimization.md)）；④蛋白质充足（1.2–1.5 g/kg/天）支持免疫细胞更新。

**3. 医疗层（需医生评估）**：低剂量 mTOR 抑制剂（疫苗应答增强，RCT 支持但 off-label）；胸腺再生组合（GH+DHEA+二甲双胍，TRIIM 证据但样本小）；CMV 状态评估（CMV 阳性者免疫衰老加速，抗病毒策略在争议中）；CHIP 检测（65 岁以上考虑，阳性者加强心血管与血液学随访）。

**核心信息**：免疫衰老是可干预的——**疫苗+运动+睡眠+营养**是"基础套餐"，mTOR 抑制与胸腺再生是"进阶选项"。免疫年龄管理应与表观年龄、代谢年龄管理并行，共同构成"多系统年龄体检"（呼应 [01-daily-checklist](../07-interventions/01-daily-checklist.md) 的年度监测框架）。**尽早建立免疫储备**——40 岁后免疫衰老加速，此刻开始的运动与疫苗策略将决定 70 岁时的免疫基线；越早干预，免疫储备越充足、未来获益越大。

## 开放问题与争议

- **因果方向**：免疫衰老与炎症衰老孰因孰果？多数证据支持两者互为正反馈（免疫失调 → 炎症 → 进一步免疫损伤），但"抗炎能否逆转免疫衰老"缺乏长期人体试验——卡纳单抗（抗 IL-1β）虽降心血管事件却未观察到感染率下降，提示单纯抗炎不等于免疫重建。
- **CMV 的角色**：CMV 驱动的 memory inflation 究竟有害还是免疫系统"优先级分配"的适应性反应？部分百岁老人 CMV 阳性且免疫表型良好，提示个体差异巨大，CMV 清除/疫苗预防（CMV 疫苗在研）能否延缓免疫衰老未知。
- **胸腺再生的转化风险**：GH 促生长有肿瘤风险，重编程有致畸风险，性激素消融有骨质疏松风险——人类胸腺再生的剂量-风险窗口远未明确。
- **TCR 多样性的阈值问题**：多样性恢复多少才足以临床获益（疫苗应答、免疫治疗响应）？无共识。
- **CHIP 悖论**：携带 DNMT3A/TET2 突变者寿命未必缩短（部分研究显示全因死亡增加但百岁老人中 CHIP 检出率亦高），CHIP 是"损伤标志"还是"干预靶点"仍存争议。

## 参考文献

1. López-Otín C, Blasco MA, Partridge L, Serrano M, Kroemer G. Hallmarks of aging: An expanding universe. Cell. 2023;186(2):243-278.
2. Goronzy JJ, Weyand CM. Mechanisms underlying T cell ageing. Nat Rev Immunol. 2019;19(9):573-583.
3. Nikolich-Žugich J. The twilight of immunity: emerging concepts in aging of the immune system. Nat Immunol. 2018;19(1):10-19.
4. Franceschi C, Garagnani P, Parini P, Giuliani C, Santoro A. Inflammaging: a new immune-metabolic viewpoint for age-related diseases. Nat Rev Endocrinol. 2018;14(10):576-590.
5. Pawelec G. Hallmarks of human immunosenescence. Ageing Res Rev. 2020;62:101111.
6. den Braber I, Mugwagwa T, Vrisekoop N, et al. Maintenance of peripheral naive T cells is sustained by thymus output in mice but not humans. Immunity. 2012;36(2):288-297.
7. Britanova OV, Putintseva EV, Shugay M, et al. Age-related decrease in TCR repertoire diversity measured with deep and normalized sequence profiling. J Immunol. 2014;192(6):2689-2698.
8. Jaiswal S, Fontanillas P, Flannick J, et al. Age-related clonal hematopoiesis associated with adverse outcomes. N Engl J Med. 2014;371(26):2488-2498.
9. Jaiswal S, Natarajan P, Silver AJ, et al. Clonal hematopoiesis and risk of atherosclerotic cardiovascular disease. N Engl J Med. 2017;377(2):111-121.
10. Frasca D, Landin AM, Lechner SC, et al. Aging down-regulates the transcription factor E2A, activation-induced cytidine deaminase, and Ig class switch in human B cells. J Immunol. 2008;180(8):5283-5290.
11. Mannick JB, Del Giudice G, Lattanzi M, et al. mTOR inhibition improves immune function in the elderly. Sci Transl Med. 2014;6(268):268ra179.
12. Mannick JB, Morris M, Hockey HP, et al. TORC1 inhibition enhances immune function and reduces infections in the elderly. Sci Transl Med. 2018;10(449):eaaq1564.
13. Fahy GM, Brooke RT, Watson JP, et al. Reversal of epigenetic aging and immunosenescent trends in humans. Aging Cell. 2019;18(6):e13028.
14. DiazGranados CA, Dunning AJ, Kimmel M, et al. Efficacy of high-dose versus standard-dose influenza vaccine in older adults. N Engl J Med. 2014;371(7):635-645.
15. Lal H, Cunningham AL, Godeaux O, et al. Efficacy of an adjuvanted herpes zoster subunit vaccine in older adults. N Engl J Med. 2015;372(22):2087-2096.
16. Wikby A, Nilsson BO, Forsey R, et al. The immune risk phenotype is associated with IL-6 in the terminal decline stage: findings from the Swedish NONA immune longitudinal study of very late life. Mech Ageing Dev. 2006;127(8):695-704.
17. Sutherland JS, Goldberg GL, Hammett MV, et al. Activation of thymic regeneration in mice and humans following androgen blockade. J Immunol. 2005;175(4):2741-2753.
18. Werner C, Fürster T, Widmann T, et al. Physical exercise prevents cellular senescence in circulating leukocytes and in the vessel wall. Circulation. 2009;120(24):2438-2447.
19. Agrawal A, Agrawal S, Tay J, Gupta S. Biology of dendritic cells in aging. J Leukoc Biol. 2007;82(6):1445-1454.

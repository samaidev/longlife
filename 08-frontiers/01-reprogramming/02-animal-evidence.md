# 表观重编程 02：动物证据——体内部分重编程延长寿命与恢复组织的实证链

> 专题：表观遗传重编程 · 第 2 篇 / 共 4 篇
> 定位：动物证据链（2013 视神经再生概念开创 → 2016 早衰延寿首证 → 2020 里程碑 → 2024-2026 基因治疗与毒性警示）
> 前置阅读：01-concept.md（OSKM/OSK 因子、部分 vs 完全重编程、表观时钟分子开关）；本库主线 NO/NAD⁺ 网络详见 01-foundations/03-no-basics.md

## 一、核心概念

体内部分重编程（in vivo partial reprogramming）指在活体动物中短暂、周期性或组织局限地表达山中因子（OSKM/OSK），在不抹除细胞身份的前提下回拨表观遗传时钟、恢复组织功能。动物实验承担着整个领域的核心证明任务：**"短暂、局部的因子表达能否在活体内恢复衰老组织的功能？"** 自 2013 年视神经再生概念开创以来，证据链已覆盖四大类模型——早衰小鼠（Hutchinson-Gilford 早衰综合征模型 Lmna^G609G、ZMPSTE24 缺失小鼠、端粒酶缺失 Terc^-/- 小鼠）、自然衰老野生型小鼠、组织损伤模型（视神经夹伤、青光眼、心肌梗死、肌肉损伤）与近期的大动物探索。Ocampo 2016（*Cell*）首次证明周期性 OSKM 表达可延长早衰小鼠寿命约 30%；Lu 2020（*Nature*）以 AAV-OSK 眼内注射恢复青光眼小鼠视觉功能并证明其依赖 TET 去甲基化酶；Macip 2024 将 AAV9-OSK 用于 124 周龄老年小鼠，剩余中位寿命延长约 109%。与此同时，Abad 2013、Ohnishi 2014 与 Parras 2023 反复警示：**持续、非受控表达会导致畸胎瘤、组织衰竭与早死——"周期而非持续"由此成为安全铁律**。动物证据的意义在于确立"衰老可逆性"的原理性证明：表观信息丢失不仅是衰老的标志，更是可干预的驱动因素。

## 二、分子机制全链条：从因子表达到组织功能恢复

### 2.1 两条效应通路

体内重编程的机制可拆为两条并行通路：**① 细胞自主通路**——因子进入细胞核直接改写表观基因组，使该细胞自身"变年轻"；**② 非细胞自主通路**——重编程细胞的分泌组（secretome）重塑微环境，通过旁分泌带动邻旁细胞与免疫细胞（2025 年皮肤研究显示未重编程细胞被"预激活"，详见下文）。两条通路共享同一上游：转录因子对染色质可及性的改写。

### 2.2 全链条通路图

```
递送（AAV / 转基因诱导 / mRNA / 小分子）
        │
        ▼
OSK/OSKM 入核（Oct4/Sox2 结合远端增强子；Klf4 招募染色质重塑复合物；
c-Myc 招募 BRD4 与组蛋白乙酰转移酶）
        │
        ▼
染色质开放（H3K27ac↑、H3K4me1/me3↑、异染色质 H3K9me3 部分解除）
        │
        ▼
多能性种子网络激活（NANOG、Lin28、ESRRB、Dppa 家族——低水平、非全量）
        │
        ▼
招募 TET1/2 双加氧酶：5mC → 5hmC → 5fC → 5caC → 主动/被动去甲基化
        │  （Lu 2020：敲低 TET 后再生效应消失——因果铁证）
        ▼
DNA 甲基化时钟回拨（Horvath 353 CpG 时钟 / 小鼠多组织时钟）
        │
        ▼
衰老基因沉默、年轻基因表达恢复
        ├──► 细胞自主：自噬↑、线粒体更新、SASP↓、衰老细胞清除
        └──► 非细胞自主：分泌组重塑 → 邻旁细胞预激活、免疫微环境年轻化
                        ▼
        组织功能恢复：轴突再生、心肌收缩、肌再生、肝再生、认知改善、寿命延长
```

### 2.3 逐节点拆解

**上游递送**决定"剂量×时间"的可控性，是体内实验与体外实验最大的分野。三种主流范式：① **转基因诱导系统**——四因子（4F）或六因子（6F，OSKM+Lin28a+Nanog）置于 tetO 启动子下，多西环素（doxycycline）开关控制表达时机，是剂量学研究的金标准（Ocampo 2016、Browder 2022、Parras 2023 均属此类）；② **AAV 递送**——组织特异或全身性，更接近未来人体给药方式（Lu 2020 眼内、Macip 2024 尾静脉 AAV9），但存在载体基因组持续存在与免疫原性问题；③ **非整合/瞬时递送**——游离型载体（episome，Sarkar 2020）与 mRNA（体内六因子 mRNA 递送正在探索），安全性最高但表达水平与组织覆盖受限。

**中游表观改写**的核心是"部分去甲基化"。OSK 激活多能性种子网络后，TET 双加氧酶将 5-甲基胞嘧啶逐步氧化，DNA 甲基化谱向胚胎/年轻状态回拨。关键在于**剂量-响应阈值**：低水平、短时程表达只回拨衰老相关的甲基化位点（数千个 CpG），而持续高表达会越过阈值、驱动 OCT4/NANOG 全量激活，细胞跨过"身份丢失临界点"进入去分化——这正是完全重编程与畸胎瘤的起点。体内研究还揭示衰老组织本身提供"重编程许可信号"：Mosteiro 2016（*Science*）发现组织损伤与细胞衰老（p16/p21、SASP）反而促进相邻细胞的重编程效率，提示衰老微环境是重编程的"顺风"，这解释了为何老年组织对部分重编程尤其敏感。

**下游表型恢复**包含细胞自主与非细胞自主两层。细胞自主层面：衰老细胞周期退出被逆转、自噬通量恢复、线粒体质量控制改善（Sarkar 2020 在人类细胞中观察到线粒体形态与膜电位年轻化）、SASP 细胞因子（IL-6、IL-1α 等）分泌下降。非细胞自主层面：重编程细胞改变分泌组，激活邻旁成纤维细胞、内皮与免疫细胞的"预再生"状态，这在肌肉（Wang 2021 肌纤维旁分泌重塑卫星细胞微环境）与皮肤（2025 马赛克重编程研究）中被反复证实。

### 2.4 "周期 vs 持续"的安全剂量学

动物实验确立的最重要药理学原则是**周期性脉冲给药**。Ocampo 2016 采用"2 天开、5 天关"（报道方案）的循环；Browder 2022 从 15 月龄起周期性诱导六因子；而持续表达在多个实验室被证明致命——Abad 2013（*Nature*）的持续诱导产生多器官畸胎瘤与体内 iPSC；Ohnishi 2014（*Cell*）发现持续表达导致的"重编程中途终止"细胞携带异常表观状态，进展为 Wilms 瘤样肾脏肿瘤与肝脏发育不良；Parras 2023（*Nat Aging*）证实持续 OSKM 经肝衰竭与肠衰竭导致早死。**周期性表达让细胞在"回拨表观时钟"与"重获增殖能力"之间反复震荡，却不跨越多能态阈值**——这是部分重编程区别于致癌转化的分子本质。

### 2.5 组织差异

不同组织的可重编程性差异显著：视网膜神经节细胞、心肌细胞、成熟肌纤维、肝细胞、齿状回神经元均被证明可被部分重编程；而骨髓造血系统与肠道上皮（增殖旺盛组织）对持续 OSKM 最敏感、最易衰竭（Parras 2023），肝脏则同时是毒性靶点与再生获益器官（Hishida 2022 肝再生增强 vs Parras 2023 肝衰竭），提示**组织特异性递送与组织特异性剂量窗**是临床转化的关键设计变量。

## 三、证据分级

| 现象 | 证据等级 | 关键文献 |
|---|---|---|
| 周期性 OSKM 延长早衰小鼠（Lmna^G609G）寿命约 30%，恢复皮肤/脾脏/肾脏组织学、降低 SASP | 实锤（转基因诱导、独立表型验证） | Ocampo 2016 *Cell* |
| AAV-OSK 眼内递送恢复青光眼小鼠 RGC 轴突再生与视觉功能，依赖 TET 酶 | 实锤（遗传学因果：TET 敲低对照） | Lu 2020 *Nature* |
| 周期性六因子表达逆转自然衰老小鼠血液与组织表观年龄 | 实锤（多组织甲基化组） | Browder 2022 *Nat Aging* |
| AAV9-OSK 单次注射使 124 周龄小鼠剩余中位寿命 +109% | 强关联（单中心、样本量有限） | Macip 2024 *Cell Reprogramming* |
| 心肌/肌肉/肝脏组织特异部分重编程增强再生 | 实锤（损伤模型功能终点） | Chen 2021 *Science*；Wang 2021 *Nat Commun*；Hishida 2022 *Cell Rep* |
| 体内 OSKM 恢复齿状回神经元年轻态并改善记忆 | 强关联（行为学+表观指标） | Rodríguez-Matellán 2020 *Stem Cell Rep* |
| 人类衰老细胞（含百岁老人）非整合瞬时重编程逆转表观年龄 | 实锤（体外，多细胞类型） | Sarkar 2020 *Nat Commun* |
| 持续 OSKM 表达致畸胎瘤/癌变/组织衰竭与早死 | 实锤（多实验室一致，毒性边界） | Abad 2013 *Nature*；Ohnishi 2014 *Cell*；Parras 2023 *Nat Aging* |
| 组织损伤与衰老促进体内重编程效率 | 强关联（机制研究） | Mosteiro 2016 *Science* |
| 猴等大动物体内重编程安全性/有效性 | 初步（个案报道，待核实） | ER-100 猴实验（2025，待核实） |
| 人体内 OSK 表达（基因治疗） | 未开展（监管/伦理待定） | — |

证据等级说明：实锤＝遗传学因果或多实验室独立复现；强关联＝功能终点明确但样本/中心有限；初步＝个案或预印本；未开展＝尚无公开人体数据。

## 四、临床/实验证据细节

### 4.1 早衰模型：三类"快进时钟"

① **Lmna^G609G 敲入小鼠**（Osorio 2011，*Sci Transl Med*）：模拟 Hutchinson-Gilford 早衰综合征（HGPS）的经典剪接突变，产生截短的 progerin 蛋白累积，小鼠 6-8 周龄即出现生长停滞、脱发、皮肤萎缩、骨与血管异常，中位寿命约 5-6 个月。Ocampo 2016 将其与可诱导 OSKM 品系杂交得到"LAKI"小鼠；② **Zmpste24^-/- 小鼠**（Pendás 2002，*Nat Genet*）：缺失 lamin A 前体蛋白加工蛋白酶，prelamin A 累积导致与 HGPS 高度相似的早衰表型，是机制研究的互补模型（详见 04-drugs/01-rentosertib.md 相关讨论）；③ **Terc^-/- 端粒酶缺失小鼠**：晚代（G4+）出现端粒耗竭驱动的多系统早衰。需要指出，部分重编程的延寿研究主要在前两类 lamin 突变模型完成；端粒模型给出的关键证据来自**端粒酶再激活**——Jaskelioff 2011（*Nature*）在晚代 Terc^-/- 小鼠中条件性再激活端粒酶，逆转了神经退行（嗅觉功能障碍恢复）、恢复脾/睾丸/肠道增殖并延长寿命，首次证明"成年哺乳动物的衰老表型可被分子干预逆转"。这一"可逆性原理"与表观重编程互补：完全重编程（iPSC 生成）经 TERT 上调可延长端粒，而部分重编程对端粒长度的直接效应研究尚少（待核实）。

### 4.2 Ocampo 2016（*Cell* 167:1719-1733）：体内延寿首证

Salk 研究所 Belmonte 团队以多西环素周期性诱导 OSKM（2 天开/5 天关，报道方案），在 LAKI 早衰小鼠中：① **中位寿命延长约 30%**（对照组 vs 治疗组，具体周数见原文）；② 皮肤真皮层增厚、脾脏淋巴滤泡结构与肾脏肾小球形态恢复年轻组织学；③ 血浆炎症因子谱（SASP）显著下降；④ **全转录组比较**显示治疗组多组织基因表达谱向年轻小鼠聚类。在 12 月龄野生型小鼠中，周期性 OSKM 表达 8 周即改善心肌毒素诱导的肌肉损伤恢复，并恢复链脲佐菌素诱导的糖尿病胰腺功能。全程未见畸胎瘤。同期 Ohnishi 2014 的警告与之一正一反，确立了"周期"范式。

### 4.3 Lu 2020（*Nature* 588:124-129）：表观信息论的决定性实验

哈佛 Sinclair 团队以 AAV 眼内递送 **Oct4/Sox2/Klf4 三因子（剔除 c-Myc 以降癌变风险）**：① 青光眼（微珠阻塞小梁网）与视神经夹伤模型中，视网膜神经节细胞（RGC）DNA 甲基化谱恢复年轻状态；② 轴突跨过损伤位点再生，视觉诱发电位与视动反应恢复，行为学上重获视觉功能；③ **敲低 TET1/2 后再生与去甲基化效应消失**——直接证明"恢复年轻表观信息"是功能恢复的因果机制，而非伴随现象。该文是"表观遗传信息丢失驱动衰老"假说（同年 *Nature* 封面）最强的实验支柱，也确立了 OSK 三因子+组织局限递送的标准范式。

### 4.4 Browder 2022（*Nat Aging* 2:243-253）：自然衰老的分子回拨

Belmonte 团队在多西环素诱导的**六因子（OSKM+Lin28a+Nanog）**转基因小鼠中，从约 15 月龄起周期性诱导至老龄：血液与肝脏、肾脏、皮肤等组织的 DNA 甲基化时钟显著回拨，老年基因表达特征逆转，未出现畸胎瘤或体重骤降；而持续表达组出现体重下降与早死。该研究把证据从"早衰模型"推进到"生理性自然衰老"，并首次系统展示**多组织表观年龄回拨**（具体回拨幅度与存活获益以原文为准）。

### 4.5 Macip 2024（*Cell Reprogramming* 26:24-32）：老年起始的基因治疗延寿

Rejuvenate Bio 团队以 AAV9 尾静脉递送可诱导 OSK，**单次注射**至 124 周龄（约当人 77-80 岁）雄性小鼠：剩余中位寿命从 8.86 周延长至 18.5 周（**+109%**），并改善虚弱评分与年龄相关分子标志。其意义在于：① 老年起始（而非早衰模型）仍有显著剩余寿命获益；② AAV 全身递送路径最接近人体给药方式。局限是单中心、雄性单性别、样本量有限（n 见原文）。

### 4.6 组织特异性重编程：心脏/肌肉/肝脏/皮肤/胰腺

- **心脏**：Chen 2021（*Science* 373:1537-1540，马普所 Braun 团队）以 αMHC 驱动的心肌细胞特异 OSKM 可逆表达，使成年心肌细胞可逆地去分化至胎羊状态，心肌梗死前后诱导均减轻梗死损伤、改善心功能——打破"成年心肌不可再生"教条；2021-2022 年另有预印本报告 OSKM 在心肌细胞中的表观年轻化（*bioRxiv* 2021.12.22.473302）。
- **肌肉**：Wang 2021（*Nat Commun* 12:3094）对肌纤维进行体内部分重编程，通过重塑干细胞微环境（niche）激活卫星细胞，促进肌肉再生——非细胞自主机制的典型证据。
- **肝脏**：Hishida 2022（*Cell Rep* 39:110730）显示体内部分重编程增强肝脏可塑性与损伤后再生。
- **皮肤/纤维化**：Doeser 2018（*Stem Cells* 36:1216-1225）报告部分重编程减少伤口纤维化与瘢痕形成；2025 年韩国 POSTECH（*Nat Commun*）"马赛克部分重编程/温和回溯"研究进一步显示：仅对一小部分皮肤细胞轻度重编程，经 PI3K-AKT、EGFR、HIF-1α 通路激活，整块皮肤进入"预再生模式"，愈合加快、瘢痕减少，糖尿病模型同样有效（细节待核实）。
- **胰腺**：Ocampo 2016 的 STZ 糖尿病恢复实验提供了胰腺证据；专门以胰腺为靶的组织特异 OSK 研究尚缺（待核实）。

### 4.7 脑与认知：海马重编程与人类细胞

- **小鼠**：Rodríguez-Matellán 2020（*Stem Cell Rep* 15:1056-1066，Serrano/Ávila 团队）在齿状回神经元中周期性表达 OSKM：恢复随龄下降的 H3K9me3 异染色质、改善突触可塑性，物体识别记忆显著改善。2024 年神经元限制性循环 OSKM 研究（*Commun Biol*）与巴塞罗那大学皮层神经元研究进一步支持"控制周期可恢复皮层神经元活力"。
- **人类细胞**：Sarkar 2020（*Nat Commun* 11:1545，Stanford Sebastiano 团队）用**非整合游离型载体**对老年供者与百岁老人来源的细胞做瞬时 OSKM 表达：表观时钟回拨约 2.5-3.5 岁（报告范围）、衰老与 SASP 标志逆转、线粒体功能年轻化、无多能性标志——桥接"体内小鼠证据"与"人体细胞可行"。

### 4.8 毒性警示：安全边界的反面教材

Abad 2013（*Nature* 502:340-345）：体内可诱导 OSKM 持续表达 → 多器官畸胎瘤与体内 iPSC。Ohnishi 2014（*Cell* 156:663-677）：野生型小鼠持续表达 → 肾脏 Wilms 瘤样病变与肝发育不良，"重编程中途终止"状态本身即致癌。Parras 2023（*Nat Aging* 3:1509-1520）：持续 OSKM → 体重骤降、肝肠衰竭、早死（肠道微生物参与，见 BioProject PRJEB66275）；同年配套研究（PMID 38012288）构建**避开肝脏与肠道的转基因品系**显著降低毒性——"组织豁免"成为新一代递送设计方向。2026 年进一步报道氧化应激是体内重编程肝衰竭的关键驱动（待核实原文）。

### 4.9 2025-2026 最新进展

Altos Labs（*Cell* 2025）提出"间充质漂移"理论：衰老是细胞身份维持能力下降的共性过程，部分重编程可逆转该漂移；猴实验中 ER-100 显示恢复视力潜力（个案/待核实）；mRNA 递送六因子恢复老化视神经的探索正在进行（待核实）。总体趋势：**从"证明可逆"转向"工程化安全"**——组织豁免、非整合递送、周期性脉冲成为三大设计主轴。

### 4.10 大动物模型的桥接价值

从啮齿类到人类的转化，大动物（犬、猪、猴）模型是不可或缺的中间站，其独特价值在于：

- **寿命与生理尺度**：小鼠寿命 2-3 年、再生能力强，延寿与再生效应可能被高估；犬（10-15 年）、猪（15-20 年）、猴（20-40 年）的寿命与器官尺度更接近人类，能更真实地评估"老年起始干预"的长期安全性与剂量。
- **已有大动物证据**：ER-100 的临床前验证即包含非人灵长类（猴）的眼部递送研究（个案报道显示视力相关指标改善，待正式发表核实）；犬类表观重编程探索（Dog Aging Project 框架下的重编程子研究）正在起步——犬是唯一与人类共享生活环境的大型伴侣动物，其自然衰老研究可直接迁移到人。
- **免疫原性评估**：AAV/mRNA 递送的免疫应答（中和抗体、T 细胞反应）在灵长类中的表现与小鼠差异显著，大动物数据是选择递送平台的关键依据。
- **监管要求**：FDA 对基因治疗类产品的 IND 申报通常要求至少一种大动物的毒理与生物分布数据——**猴/犬的长期安全性数据是 ER-100 类产品进入人体试验的必经关卡**。

**现状判断**：大动物重编程数据仍为零星个案（猴眼部、犬探索），远未形成系统证据链——这是表观重编程从"动物证明"到"人体注册"之间最明显的证据缺口之一，也是未来 3-5 年最值得关注的转化节点（呼应 [04-roadmap](../01-reprogramming/04-roadmap.md) 的时间线判断）。

## 五、与 NO / NAD⁺ / 长寿网络的联系

```
部分重编程 ──► 线粒体年轻化（自噬↑、mtROS↓、OXPHOS 恢复）
                  │
                  ├──► eNOS 偶联保持 ──► NO 生物利用度↑ ──► sGC/cGMP/PKG ──► 血管舒张/抗炎
                  │
                  ├──► ROS↓ ──► ONOO⁻ 生成↓（避免 NO 被超氧自由基劫持）
                  │
SASP↓ ──► 慢性炎症↓ ──► 内皮功能保护 ──► eNOS 活性↑
                  │
NO ──► S-亚硝基化 DNMT/TET（机制研究表明）──► 反馈调节 DNA 甲基化 ←──► 重编程表观改写
```

本库主线的对接点有四（前两条为机制推测，需实验验证）：① **线粒体-内皮轴**：重编程恢复线粒体质量控制→活性氧下降→eNOS 解偶联减少→NO 生物利用度回升，这可能是重编程"血管年轻化"效应的通路基础（Browder 2022 肾脏/皮肤年轻化中血管床的表观恢复可作为间接证据，待核实）；② **SASP-炎症-NO 轴**：重编程降低 SASP→慢性炎症消退→保护 eNOS，与 senolytics 的血管获益机制同源；③ **NAD⁺/SIRT1 交叉**：NAD⁺ 随龄下降→SIRT1 失活→eNOS 去乙酰化减少，而重编程若能恢复 SIRT1 网络则可放大 NO 信号（详见 01-foundations/03-no-basics.md）；④ **NO 对表观机器的反向调控**：机制研究表明 NO 经 S-亚硝基化修饰 DNMT/TET 影响甲基化，提示 NO 与重编程存在双向对话——NO 既是重编程的下游受益者，也可能是其上游调节器（双刃剑：高 NO 伴高 ROS 时 ONOO⁻ 介导硝化应激，反噬表观稳定性）。

## 六、干预方向与可执行建议

按证据强度排序：① **组织局限 + 周期脉冲**：优先选择眼部（Lu 2020 范式）、心肌（Chen 2021 范式）等"低增殖、高获益"组织，给药采用 2 天开/5 天关式循环而非持续表达；② **非整合递送优先**：mRNA/游离型载体规避插入突变与持续表达风险，是通向人体的最短路径；③ **组织豁免设计**：避开肝肠（Parras 2023 毒性靶点）或使用组织特异启动子；④ **强制机制对照**：每个适应证研究均设 TET 敲低/抑制对照，验证"表观回拨-功能恢复"因果链；⑤ **监测体系**：以血液/组织 DNA 甲基化时钟（Thompson 2018 小鼠时钟）、单细胞转录组、SASP 谱为终点，跟踪"周期-回拨-功能"量效曲线；⑥ **安全性红线**：任何方案须以畸胎瘤/去分化标志（NANOG 全量激活、OCT4 异位）为停止规则，长期致癌随访不可省略。

## 七、开放问题与争议

1. **小鼠到人的鸿沟**：小鼠寿命短、再生能力强，延寿与再生效应可能被系统性高估；大动物（猴）数据仍为零星个案；2. **"剩余寿命"计量**：Macip 2024 的 +109% 是剩余寿命延长，换算成绝对寿命与健康寿命获益需谨慎；3. **表观回拨≠功能修复**：甲基化时钟回拨是读数改变，能否转化为真实组织功能（尤其是心肌、神经元等终末分化细胞）仍缺直接证据；4. **肿瘤风险量化**：部分重编程与致癌转化的剂量阈值在体内尚无明确的安全窗口数据，"周期"的分子边界（何种表观状态不可逆）未知；5. **免疫与耐受**：病毒载体与异位转录因子的免疫原性、重复给药的耐受性未解决；6. **端粒与表观时钟脱节**：部分重编程回拨甲基化时钟但不一定延长端粒，两种"年龄读数"的分离意味着什么尚不清楚；7. **伦理与监管**：人体内改变表观基因组属于基因治疗范畴，监管路径（FDA/EMA）与长期随访框架均未建立。

### 从动物证据到人体的转化清单（关键验证节点）

综合动物证据链，向人体转化需要依次通过的验证节点（每项都有明确的证据等级要求）：

| 节点 | 验证内容 | 当前状态 | 达成标志 |
|---|---|---|---|
| 1. 安全窗口 | 周期×剂量×组织的三维安全矩阵 | 啮齿类基本建立 | 大动物确认 |
| 2. 递送平台 | 非整合载体/AAV 的免疫原性与组织覆盖 | AAV 眼内最成熟 | 大动物长期毒理 |
| 3. 功能终点 | 回拨时钟与功能恢复的因果绑定 | 眼/肌肉/心脏较强 | 大动物功能数据 |
| 4. 老年起始 | 老年（而非早衰）模型的有效性 | Browder/Macip 支持 | 大动物老年队列 |
| 5. 免疫监测 | 重复给药的耐受与中和抗体 | 缺失 | 灵长类重复给药 |
| 6. 长期随访 | 致癌/去分化的数十年安全 | 缺失 | 前瞻性注册队列 |

**核心判断**：动物证据已充分证明"部分重编程可逆衰老"的原理，人体转化的瓶颈不在原理而在**工程与监管**——递送安全、剂量窗口、长期随访三项是未来 5 年决定表观重编程能否成为"第一个真正的逆衰疗法"的关键（呼应 [01-concept](01-concept.md) 的 ER-100 讨论与 [09-immortality/02-breakthrough-candidates](../../09-immortality/02-breakthrough-candidates.md) 的 31/40 评分依据）。

## 参考文献

1. Ocampo A, Reddy P, Martinez-Redondo P, et al. In Vivo Amelioration of Age-Associated Hallmarks by Partial Reprogramming. *Cell* 2016;167:1719-1733.e12. doi:10.1016/j.cell.2016.11.052
2. Lu Y, Brommer B, Tian X, et al. Reprogramming to recover youthful epigenetic information and restore vision. *Nature* 2020;588:124-129. doi:10.1038/s41586-020-2975-4
3. Browder KC, Reddy P, Yamamoto M, et al. In vivo partial reprogramming alters age-associated molecular changes during physiological aging in mice. *Nat Aging* 2022;2:243-253. doi:10.1038/s43587-022-00183-2
4. Cano Macip C, et al. Gene Therapy-Mediated Partial Reprogramming Extends Lifespan and Reverses Age-Related Changes in Aged Mice. *Cell Reprogramming* 2024;26(1):24-32.
5. Parras A, Vílchez-Acosta A, Desdín-Micó G, et al. In vivo reprogramming leads to premature death linked to hepatic and intestinal failure. *Nat Aging* 2023;3:1509-1520. doi:10.1038/s43587-023-00528-5
6. Chen Y, Lüttmann FF, Schoger E, et al. Reversible reprogramming of cardiomyocytes to a fetal state drives heart regeneration in mice. *Science* 2021;373:1537-1540. doi:10.1126/science.abg5159
7. Wang C, et al. In vivo partial reprogramming of myofibers promotes muscle regeneration by remodeling the stem cell niche. *Nat Commun* 2021;12:3094. doi:10.1038/s41467-021-23353-z
8. Hishida T, Yamamoto M, Hishida-Nozaki Y, et al. In vivo partial cellular reprogramming enhances liver plasticity and regeneration. *Cell Rep* 2022;39:110730.
9. Rodríguez-Matellán A, Alcazar N, Hernández F, Serrano M, Ávila J. In vivo reprogramming ameliorates aging features in dentate gyrus cells and improves memory in mice. *Stem Cell Rep* 2020;15:1056-1066.
10. Sarkar TJ, Quarta M, Mukherjee S, et al. Transient non-integrative expression of nuclear reprogramming factors promotes multifaceted amelioration of aging in human cells. *Nat Commun* 2020;11:1545. doi:10.1038/s41467-020-15174-3
11. Abad M, Mosteiro L, Pantoja C, et al. Reprogramming in vivo produces teratomas and iPS cells with totipotency features. *Nature* 2013;502:340-345.
12. Ohnishi K, Semi K, Yamamoto T, et al. Premature termination of reprogramming in vivo leads to cancer development through altered epigenetic regulation. *Cell* 2014;156:663-677.
13. Mosteiro L, Pantoja C, Alcazar N, et al. Tissue damage and senescence provide critical signals for cellular reprogramming in vivo. *Science* 2016;354:aaf4445.
14. Doeser MC, Schöler HR, Wu G. Reduction of fibrosis and scar formation by partial reprogramming in vivo. *Stem Cells* 2018;36:1216-1225.
15. Jaskelioff M, Muller FL, Paik JH, et al. Telomerase reactivation reverses tissue degeneration in aged telomerase-deficient mice. *Nature* 2011;469:102-106.
16. Osorio FG, Navarro CL, Cadinanos J, et al. Splicing-directed therapy in a new mouse model of human accelerated aging. *Sci Transl Med* 2011;3:106ra107.
17. Pendás AM, Zhou Z, Cadiñanos J, et al. Defective prelamin A processing and muscular and adipocyte alterations in Zmpste24 metalloproteinase-deficient mice. *Nat Genet* 2002;31:94-99.
18. Horvath S. DNA methylation age of human tissues and cell types. *Genome Biol* 2013;14:R115.
19. Thompson MJ, Chwiałkowska K, Rubbi L, et al. A multi-tissue full lifespan epigenetic clock for mice. *Aging (Albany NY)* 2018;10:2832-2854.
20. Takahashi K, Yamanaka S. Induction of pluripotent stem cells from mouse embryonic and adult fibroblast cultures by defined factors. *Cell* 2006;126:663-676.

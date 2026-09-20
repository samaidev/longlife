# 蛋白稳态与自噬：蛋白质质量控制网络的衰老与干预 Proteostasis & Autophagy

## 核心概念

蛋白稳态（proteostasis）指细胞维持蛋白质正确折叠、定位与降解的动态平衡，由**分子伴侣（molecular chaperones）、泛素-蛋白酶体系统（UPS）与自噬-溶酶体通路（autophagy-lysosome pathway）**三大子系统构成的蛋白质质量控制网络（PQC network）协同维持。该概念由 Balch、Morimoto、Dillin 与 Kelly 于 2008 年在 *Science* 系统提出（"Adapting proteostasis for disease intervention"）：PQC 网络是一个高度集成、互为代偿的"折叠-重折叠-降解"决策系统。衰老时 PQC 网络整体崩溃（proteostasis collapse）——合成端活性下降、降解端负荷超载、内质网应激反应迟钝——错误折叠蛋白累积并聚集，直接驱动阿尔茨海默病（AD）、帕金森病（PD）、肌萎缩侧索硬化（ALS）等神经退行性疾病，是 López-Otín 等 2013/2023 年《Cell》衰老标志框架中的**第 4 号原发性损伤标志**。蛋白稳态丧失的特殊之处在于：它是目前**药物可干预性最强**的标志之一（雷帕霉素、亚精胺、NAD+ 前体均通过增强降解或修复网络起效），也是连接营养感应（mTOR/AMPK）、线粒体功能（线粒体自噬）与慢性炎症（聚集物激活 NLRP3）的核心枢纽。

## 一、分子机制全链条

### 1. 折叠网络：从新生肽到天然构象

新合成蛋白质在核糖体出口通道即以未折叠状态暴露疏水残基，极易错误聚集。折叠的第一步由**HSP70 系统**完成：Hsp40（DnaJ 家族，约 40 种）识别并递送未折叠底物给 Hsp70（HSPA1A/1B），刺激其 ATPase 活性，使 Hsp70 由 ATP 结合态（低亲和力）转变为 ADP 结合态（高亲和力），稳定底物的疏水核心防止聚集。随后底物可被**HSP90 系统**接管完成晚期折叠——HSP90 依赖 ATP 水解驱动构象成熟，经 HOP、p23 等辅助伴侣（co-chaperone）组装为成熟复合物，其客户蛋白包括类固醇激素受体、激酶（Akt、CDK4）等约 10% 的蛋白组；而**伴侣蛋白 TRiC/CCT**（含 TCP-1 的桶状结构）则负责肌动蛋白、微管蛋白等约 10% 胞质蛋白的从头折叠。折叠失败的蛋白由 E3 连接酶 CHIP（STUB1，含 TPR 域可同时结合 Hsp70/Hsp90）决定进入降解分支——**"重折叠还是降解"的分流决策即发生在 Hsp70/CHIP 节点**。

衰老使折叠网络首当其冲：HSF-1（热休克转录因子 1）活性随龄下降，导致 Hsp70/Hsp90/Hsp40 转录减少；同时聚集物以"海绵效应"大量吸附伴侣蛋白，进一步耗竭可用伴侣池（sequestration），形成恶性循环。

```
   核糖体出口 ──> Hsp40/Hsp70 ──> Hsp90 ──> 天然构象
                     │  (ADP态高亲和)      │失败
                     │ 重折叠尝试          ▼
                     └────────── CHIP(Hsp70/E3) ──> K48-多聚泛素链 ──> 26S蛋白酶体
                     （折叠-降解分流决策节点）
```

### 2. 降解通道一：泛素-蛋白酶体系统（UPS）

UPS 负责降解约 80% 的胞内蛋白（短寿命蛋白与可溶性错误折叠蛋白），是 PQC 的"主力降解器"。降解链条为三级酶促级联：

**E1（UBA1，活化酶）→ E2（约 40 种，结合酶，如 UbcH5）→ E3（连接酶，超 600 种，决定底物特异性）→ 26S 蛋白酶体。**

E3 连接酶按结构分三大类：RING 型（如 MDM2、SCF 复合体、CHIP——直接催化泛素从 E2 转移到底物）、HECT 型（如 NEDD4——先形成 E3-泛素硫酯中间体）、RBR 型（如 Parkin——RING 与 HECT 的混合机制）。底物被加上 **K48 连接的 4 条以上多聚泛素链**后，被 26S 蛋白酶体识别：19S 调节颗粒（base 的 Rpt1-6 ATPase 环负责底物去折叠与转运，lid 负责去泛素化）将底物线性化并送入 20S 核心颗粒的桶状腔，由 β1（caspase 样）、β2（trypsin 样）、β5（chymotrypsin 样）三个催化亚基降解为 3-22 个氨基酸的肽段。其中 **β5 亚基是限速环节**，也是衰老中活性下降最显著的位点（见下文）。p97/VCP 作为"segregase"将泛素化底物从内质网（ERAD 途径）或膜上提取出来送入蛋白酶体——**VCP 突变直接导致包涵体肌病伴 Paget 骨病和额颞叶痴呆（IBMPFD）**，是 UPS 缺陷致神经退行的人类遗传学证据。

### 3. 降解通道二：自噬-溶酶体系统

自噬（autophagy）处理 UPS 难以触及的货物：蛋白聚集体、受损细胞器、长寿命蛋白，分三种形式——**巨自噬（macroautophagy）、分子伴侣介导自噬（CMA）与微自噬**。

**巨自噬的分子级联（核心链条）**：

```
营养充足: mTORC1 --磷酸化--> ULK1(Ser757) ──抑制──┐
                                                ▼
能量不足/应激: AMPK --磷酸化--> ULK1(Ser317/777) ──激活──> ULK1复合体
                                             (ULK1-FIP200-ATG13-ATG101)
                                                │ 成核
                                                ▼
                                Beclin1-VPS34-VPS15-ATG14L (产生PI3P)
                                                │ 膜延伸
                                                ▼
              ATG12-ATG5-ATG16L1 偶联系统 + LC3-II(ATG4剪切proLC3,
              ATG7/ATG3催化LC3-I脂化为LC3-II锚定双层膜)
                                                │ 包裹货物
                                                ▼
                    STX17-SNAP29-VAMP8 SNARE复合体 + Rab7/HOPS
                    自噬体与溶酶体融合 ──> 酸性水解酶降解 ──> 氨基酸回收
```

关键调控节点：**ULK1 是 mTORC1 与 AMPK 的交汇点**——mTORC1 磷酸化 ULK1 Ser757 抑制自噬起始，AMPK 磷酸化 Ser317/777 激活自噬起始（Kim 等 2011 *Nat Cell Biol*），"油门与刹车"由此直接对撞。选择性自噬由货物受体介导：**p62/SQSTM1**（UBA 域结合泛素化底物、LIR 域结合 LC3）介导聚集体自噬（aggrephagy）；**PINK1-Parkin 通路**介导线粒体自噬——线粒体去极化后 PINK1 稳定于外膜，招募并磷酸化激活 Parkin，Parkin 泛素化 MFN1/2、VDAC 等外膜蛋白，经 p62/OPTN/NDP52 衔接至 LC3 完成清除；OPTN 突变同样致 ALS。**CMA** 则由胞质 HSC70 识别底物中的 KFERQ 五肽基序，经溶酶体膜受体 LAMP-2A 转位入腔降解。

### 4. 内质网应激与未折叠蛋白反应（UPR 三臂）

分泌型与跨膜蛋白（神经元受体、胰岛 β 细胞的胰岛素等）在内质网（ER）腔内折叠，对蛋白稳态失衡格外敏感。ER 腔堆积未折叠蛋白时，分子伴侣 BiP/GRP78 从三个传感器上解离，激活**三条信号臂**：

- **IRE1α 臂**：RNase 活性剪接 XBP1 mRNA 产生活性转录因子 XBP1s，上调伴侣与脂质合成基因；同时经 RIDD 机制降解 ER 上的错误 mRNA。IRE1α 是最保守、最早进化出的一臂。
- **PERK 臂**：磷酸化 eIF2α → 全局翻译暂停（减少蛋白流入）+ 选择性翻译 ATF4 → 上调 CHOP 与氨基酸代谢基因；若应激持续，CHOP 驱动促凋亡程序（CHOP/Bax 轴）。
- **ATF6 臂**：转位至高尔基体被 S1P/S2P 蛋白酶剪切释放活性转录因子，上调 ERAD 组分与伴侣。

UPR 的生物学逻辑是"先代偿、后弃车保帅"：急性应激时三臂协同恢复稳态（adaptive UPR），慢性不可逆应激则转向凋亡（terminal UPR）。**衰老使 UPR 反应迟钝（UPR 激活阈值升高、幅度减弱）**，分泌型细胞（神经元、β 细胞）的折叠负荷长期得不到代偿——Taylor 与 Dillin 发现线虫神经元特异过表达 XBP1s 即可延长寿命约 30-40%，证明 UPR 活性本身是长寿的决定因素之一（*Cell* 2013）。线粒体对应物 UPRmt（ATF5、HSP60、LONP1 等）负责线粒体基质蛋白的质量监控，与线粒体自噬构成线粒体 PQC 的双层防线。

### 5. 衰老中蛋白稳态网络的崩溃节点

综合多物种证据，PQC 随龄衰退并非均匀衰减，而是集中在以下可识别的节点：

| 节点 | 随龄变化 | 后果 |
|---|---|---|
| HSF-1 转录活性 | ↓（约 30-50%） | 伴侣蛋白合成不足 |
| 26S 蛋白酶体活性 | ↓（人体组织实测下降 30-50%，β5 亚基为主） | 短寿命蛋白降解减慢，氧化损伤蛋白堆积 |
| 溶酶体酸化 | v-ATPase 功能下降 → 溶酶体 pH 升高 | 酸性水解酶活性大降，降解"最后一公里"失效 |
| 脂褐素（lipofuscin） | 逐年累积，占据溶酶体腔（老年心肌/神经元可占体积 30-70%） | 物理性堵塞自噬体-溶酶体融合与降解 |
| CMA（LAMP-2A） | LAMP-2A 受体水平下降约 50%（Cuervo & Dice 2000） | CMA 底物（GAPDH、α-synuclein 等）清除率下降 |
| TFEB 核转位 | mTORC1 磷酸化 TFEB(Ser211) 使其滞留胞质，核转位受阻 | 溶酶体生物发生基因（溶酶体生成"总开关"）转录不足 |
| 自噬体-溶酶体融合 | SNARE（STX17）与 Rab7 功能下降 | 自噬体堆积但降解不增（通量下降的标志） |

关键概念：**自噬通量（autophagic flux）** 指"形成-融合-降解"全流程的净清除速率，而非自噬体数量——衰老与多数病理状态的特征是**自噬体形成增多（代偿）而融合降解受阻**，只测 LC3-II 总量会误判通量升高，需用氯喹/巴弗洛霉素阻断实验或 mCherry-GFP-LC3 串联荧光报告基因区分。溶酶体 pH 升高是通量下降的核心枢纽：它同时降低水解酶活性、削弱自噬体融合与 CMA 效率，且与脂褐素累积互为因果——受损溶酶体又释放组织蛋白酶入胞质激活 NLRP3 炎症小体，将蛋白稳态丧失与慢性炎症标志直接串联。

## 二、错误折叠蛋白聚集与神经退行

PQC 崩溃的最严重后果是**富含 β-折叠构象的淀粉样蛋白**跨越"可溶性-寡聚体-原纤维-成熟纤维"的能量屏障发生相分离与聚集：

- **Aβ（AD）**：APP 被 β-/γ-分泌酶顺序剪切产生 Aβ40/Aβ42，Aβ42 疏水性更强、更易聚集；APP 基因重复与 PSEN1/PSEN2 突变（增加 Aβ42/40 比例）在遗传上证实 Aβ 是 AD 的起始驱动（淀粉样级联假说）。
- **Tau（AD/FTD）**：MAPT 基因突变直接致额颞叶痴呆；AD 中 Tau 被过度磷酸化（PHF-tau）形成神经原纤维缠结，并呈"类朊病毒"的解剖学传播（Braak 分期）。
- **α-突触核蛋白（PD）**：SNCA 基因重复/三倍体与 A53T 突变致 PD；Lewy 小体以 α-synuclein 纤维为核心，S129 磷酸化为病理标志。
- **TDP-43（ALS/FTD）**：核-胞质转运异常，胞质 TDP-43 形成应激颗粒样聚集体并丢失核功能。
- **亨廷顿蛋白（HD）**：HTT 基因 CAG 重复扩增产生 polyQ 蛋白，R6/2 转基因小鼠是经典模型。

**遗传学因果链**（聚集体→神经退行）的经典证据：自噬必需基因敲除小鼠直接出现神经退行——Hara 等与 Komatsu 等 2006 年同期在 *Nature* 报道，神经特异性敲除 Atg5 或 Atg7 的小鼠出现运动障碍、泛素阳性包涵体与神经元死亡；Komatsu 2007 年进一步证明 p62 是包涵体形成的关键衔接分子。反之，**遗传性自噬增强的个体未见于人类，但 Atg7 过表达在部分小鼠模型显示改善年龄相关病理**（机制研究阶段）。毒性形式之争：多项证据指向**可溶性寡聚体**（而非成熟纤维）是主要毒性实体——寡聚体插入膜、异常激活 NMDA 受体/突触受体、募集并错误折叠天然蛋白（seeding）；这解释了为何单纯清除纤维（Aduhelm 等抗体）临床获益有限（见证据细节）。

## 三、证据分级

| 现象 | 证据等级 | 关键文献 |
|---|---|---|
| PQC 网络（伴侣/UPS/自噬）随龄整体衰退 | 实锤（多物种一致：酵母-线虫-果蝇-小鼠-人组织） | Balch 2008 Science；Cuervo & Dice 2000 |
| 自噬必需基因缺失（Atg5/Atg7 KO）致神经退行 | 实锤（小鼠遗传学因果） | Hara 2006 Nature；Komatsu 2006 Nature |
| 自噬诱导（CR/雷帕霉素/亚精胺）延长模式生物寿命 | 实锤（跨物种，雷帕霉素经 NIA ITP 双盲验证） | Harrison 2009 Nature；Eisenberg 2009 |
| 伴侣/UPR 转录因子过表达（HSF-1、XBP1s）延长寿命 | 实锤（线虫遗传学） | Hsu 2003 Science；Taylor & Dillin 2013 Cell |
| 蛋白酶体活性随龄下降 30-50% | 强关联（人体组织实测，机制方向明确） | Grune 等系列研究 |
| 聚集蛋白与神经退行因果相关 | 强（遗传学 APP/SNCA/MAPT/HTT + 病理学；但"清除即获益"转化不佳） | van Dyck 2023 NEJM（lecanemab 效果有限） |
| 自噬诱导剂改善人体认知/代谢 | 初步（小型 RCT、标志物层面，样本小待重复） | Schwarz 2022 JAMA Netw Open；Kars 2010 Diabetes |
| 重建年轻化 PQC 网络逆转衰老表型 | 中等（动物模型：恢复 CMA 改善老年肝功） | Zhang & Cuervo 2015 Sci Transl Med |

证据等级说明：I=随机对照/多物种一致；II=动物模型因果+人体关联；III=人体观察性/机制推测；IV=个案/体外。

## 四、临床/实验证据细节

**雷帕霉素（NIA ITP 项目，证据最硬的自噬诱导延寿）**：Harrison 等 2009 年在 *Nature* 报告，免疫抑制剂量雷帕霉素（14 ppm 饲料）从 600 日龄（约相当于人 60 岁）开始喂饲遗传异质（UM-HET3）小鼠，雄性中位寿命延长 9%、雌性延长 14%（Miller 2011 年报道从 9 月龄开始给药雌性延长 18%、雄性 10%）。机制上雷帕霉素与 FKBP12 结合后抑制 mTORC1，解除其对 ULK1(Ser757) 与 TFEB 的磷酸化抑制，并逆转翻译通量——这是"通过增强蛋白稳态延寿"在随机化、多中心（3 个 ITP 站点）背景下最强的人体前证据。Bjedov 等 2010 年证明雷帕霉素同样延长果蝇寿命且依赖自噬基因（Atg 突变体中失效）。

**亚精胺（spermidine）**：Eisenberg 等 2009 年在 *Nature Cell Biology* 报道亚精胺经自噬机制延长酵母（复制寿命约 4 倍）、线虫与果蝇寿命，且 Atg 缺陷时失效；机制为抑制乙酰转移酶 EP300，使自噬蛋白（如 ATG 家族）保持去乙酰化活性态（Pietrocola 等 *Cell Death Differ* 2015）。2016 年 *Nature Medicine*：饮水补充亚精胺延长小鼠寿命约 10% 并改善心脏功能（降低心肌纤维化、舒张功能改善）；人体流行病学显示膳食亚精胺摄入高者全因死亡率更低。人体 RCT（Schwarz 2022，JAMA Netw Open）：主观认知下降老年人群口服亚精胺约 300 mg/日、3 个月，情景记忆指标优于安慰剂（n 约 90，效应量中等，需更大样本重复）。

**Aβ 抗体的人体转化教训**：lecanemab（Clarity AD 试验，2022，n=1795）18 个月使 CDR-SB（临床痴呆评定量表）衰退减缓约 27%（绝对差 0.45 分），同时 PET 证实显著清除淀粉样斑块——这是**"清除聚集体"首次获得确定性临床试验阳性结果**，但幅度有限且伴随 ARIA（淀粉样相关影像学异常，脑水肿/出血）风险；Aduhelm 因获益-风险比争议被撤市。该反差支持"寡聚体毒性、清除大纤维获益有限"假说，也提示单靶点清除不足以逆转已建立的神经退行。

**UPR 药理学（人体证据）**：牛磺熊去氧胆酸（TUDCA，化学伴侣）1750 mg/日×12 周改善肥胖男性肝脏与肌肉胰岛素敏感性（Kars 等 *Diabetes* 2010）；4-苯基丁酸（4-PBA）在代谢病中显示 UPR 标志物下调。恢复 CMA：Zhang & Cuervo（2015，*Sci Transl Med*）在老年小鼠肝脏恢复 LAMP-2A 表达，改善肝细胞功能与应激抵抗——**"重建年轻化 PQC"在动物体内可行的直接证据**。二甲双胍（AMPK→ULK1）延长小鼠寿命约 6%（Martin-Montalvo 2013，*Nat Commun*，雄性），UKPDS 随访显示二甲双胍降低 2 型糖尿病老年人群全因死亡率。热量限制人体试验 CALERIE（Redman 2018，*Cell Metab*）：持续 2 年、约 12% 热量限制实现约 10% 体重下降，氧化应激损伤标志（8-oxo-dG、F2-异前列腺素）显著降低——自噬通量改善是其候选机制之一（人体直接测通量仍困难，多依赖 p62/LC3 循环标志物，待核实具体效应量）。

## 五、与 NO / NAD+ 长寿网络的联系

**NO→SIRT1→自噬轴**：SIRT1 是连接 NO 与自噬的中枢——Lee 等 2008 年（*PNAS*）证明 SIRT1 为饥饿诱导自噬所必需，直接去乙酰化 ATG5/ATG7/LC3 等自噬机器蛋白维持其活性；SIRT1 还去乙酰化 FoxO3a 上调 BNIP3 促进线粒体自噬（Kume 等 *J Biol Chem* 2010），并去乙酰化 TFEB 促进其核转位激活溶酶体生物发生。NO 侧：运动→剪切应力→eNOS→NO，NO 经 cGMP 与 AMPK 两条路径上调 SIRT1 表达与活性（内皮细胞机制研究表明），形成"运动→NO→SIRT1→自噬→蛋白稳态"的闭环；低剂量 NO 供体促进线粒体自噬，与 PGC-1α 介导的线粒体生物发生协同实现线粒体更新。NAD+ 是 SIRT1 的限速底物：NAD+ 随龄下降（人体组织中老年较青年下降约 30-50%，部位依赖）→ SIRT1 活性下降 → 自噬机器去乙酰化不足——NAD+ 前体（NMN/NR）恢复 NAD+ 后 SIRT1-自噬轴重新激活（人体 NR 试验证实 NAD+ 升高约 40-60%，Martens 2018 *Nat Commun*，n=30 中年/老年人群）。

**NO 双刃剑的另一面——ONOO⁻ 直接损伤 PQC**：高浓度 NO 与超氧反应生成过氧亚硝酸盐（ONOO⁻），硝化蛋白酪氨酸（3-硝基酪氨酸，随龄与神经退行脑中累积）直接损害伴侣与蛋白酶体功能；更经典的是 **Parkin 的 S-亚硝基化**——Chung 等 2004 年（*Science*）证明 NO 供体使 Parkin 在 Cys323 亚硝基化，抑制其 E3 连接酶活性并损害其保护功能，直接关联 PD 病理（PD 脑内亚硝基化 Parkin 增多）。α-突触核蛋白本身也是 S-亚硝基化底物，亚硝基化促进其寡聚化。因此 NO 对蛋白稳态呈典型剂量依赖：**生理低剂量（eNOS 来源）经 SIRT1/AMPK 促自噬保稳态；病理高剂量（iNOS/炎症）经 ONOO⁻/亚硝基化损伤 PQC 促聚集**——与 03-no-basics.md 的"NO 双刃剑"主线完全一致。

**长寿网络交叉点**：mTORC1（抑制自噬、磷酸化 TFEB/ULK1）与 AMPK/SIRT1（促自噬）构成"合成-分解"天平，NO、NAD+、热量限制均作用于该天平；详见 04-drugs/06-mtor-rapamycin.md 与 04-nad-sirtuin.md。中药益气活血（黄芪甲苷、人参皂苷 Rg1 等）机制研究表明可经 eNOS/NO↑ 与 AMPK 激活诱导自噬改善内皮与心肌蛋白稳态（多数为细胞/动物水平，人体证据待核实），为本库中医药交叉主线提供了 PQC 切入点。

## 六、干预方向与可执行建议

按证据强度排序的 PQC 干预策略：

1. **生活方式（证据最强、最可执行）**：热量限制/间歇性禁食（AMPK→ULK1、SIRT1 依赖）、耐力运动（eNOS/NO→SIRT1→自噬+线粒体自噬）、充足睡眠（脑内胶质淋巴系统清除 Aβ——2012 年 *Science Translational Medicine* 机制研究，待人体证实）。三者均可经 NO/NAD+ 轴叠加。
2. **已有临床数据的药物**：二甲双胍（AMPK 激活，TAME 人体抗衰试验进行中）；雷帕霉素/依维莫司低剂量脉冲给药（老年免疫改善人体试验：RAD001 提高流感疫苗应答约 20%，详见 04-drugs/06）；亚精胺（食品级补充，RCT 初步阳性）。
3. **前沿管线（人体前）**：NAD+ 前体 NMN/NR（恢复 SIRT1-自噬轴）；尿石素 A（Urolithin A，诱导线粒体自噬，老年人群 4 周试验改善肌肉线粒体标志物）；Trehalose（非 mTOR 依赖自噬诱导剂，小鼠 ALS/AD 模型改善）；USP14 抑制剂 IU1（去泛素化酶抑制→蛋白酶体降解增强，临床前）；PROTAC（靶向蛋白降解技术，已进入肿瘤临床试验，未来或用于清除病理聚集物如 tau/α-syn——尚属设想）；药理伴侣（4-PBA/TUDCA，改善 ER 折叠负荷，代谢病已有人体数据）。
4. **监测建议**：目前人体无便捷的自噬通量直接测量法；可监测的替代指标包括循环 p62/LC3 变化、氧化损伤标志（3-硝基酪氨酸、8-oxo-dG）、LAMP-2A/组织蛋白酶活性（组织活检）、神经退行血标志（p-tau217、GFAP）作为聚集负担的间接读数。

## 七、蛋白稳态与其他衰老标志的联动

蛋白稳态丧失并非孤立事件，而是与其余十一大标志形成正反馈网络：**与线粒体功能障碍**——受损线粒体既是被清除对象（线粒体自噬），又是聚集蛋白的"帮凶"（线粒体 ROS 促进错误折叠与氧化修饰蛋白累积，氧化修饰蛋白又是蛋白酶体较难降解的底物）；**与慢性炎症**——聚集蛋白可被 NLRP3 炎症小体识别（Aβ、α-synuclein 激活 NLRP3 促 IL-1β 成熟），而炎症诱导的 iNOS 高浓度 NO 又经 ONOO⁻ 损伤 PQC，形成"聚集→炎症→硝基化损伤→更聚集"的恶性循环；**与细胞衰老**——衰老细胞本身蛋白稳态负担加重（SASP 蛋白大量合成），而蛋白毒性应激又可诱导 p53/p21 促衰老；**与营养感应失调**——mTORC1 既是营养感应核心又是自噬总开关，这一枢纽让"吃得过多→mTOR 持续激活→自噬被抑制→蛋白聚积"成为代谢-蛋白稳态轴的直观因果链。理解这些交叉，才能解释为何单一 PQC 干预（如只清除 Aβ）临床获益有限：只有同时解除上游损伤（线粒体、炎症、营养信号）才能让 PQC 网络恢复代偿余量。这也呼应本库主线——NO 与 NAD+ 之所以被视为上游干预枢纽，正因其同时影响多条标志链（详见 01-aging-hallmarks.md 与 03-no-basics.md）。

## 八、开放问题与争议

1. **毒性形式之争**：寡聚体 vs 成熟纤维谁是主要毒性实体？Aβ 抗体清除斑块获益有限而风险明确，提示"清除策略"需要重新定位（预防性清除 vs 治疗性清除；多聚体特异性抗体）。
2. **自噬的"最佳窗口"**：过度自噬可致细胞器过度消耗与 II 型程序性死亡（自噬性死亡），且肿瘤细胞利用自噬维持生存——系统性强自噬诱导（如高剂量雷帕霉素）的长期风险（免疫抑制、代谢副作用）与获益的平衡点未知；"脉冲式"诱导是否优于持续诱导尚无定论。
3. **UPR 的双相性**：UPR 既是代偿机制（延寿）又是凋亡驱动（CHOP），慢性低度 ER 应激在衰老中究竟是"应激累积"还是"代偿失能"？XBP1s 过表达延寿的机制（细胞自主 vs 非自主）仍在争论。
4. **人体转化鸿沟**：所有 PQC 干预的延寿证据均来自模式生物；人体 RCT 终点（死亡/失能）缺失，且缺乏可靠的体内自噬通量生物标志物，导致"自噬诱导剂在人体到底起了多大作用"无法量化。
5. **合成致死式风险**：UPS 与自噬互为代偿，双通道同时抑制（如 Bortezomib 化疗 + 氯喹联用）可致致命性蛋白毒性——干预设计必须考虑代偿网络而非单一节点。

## 参考文献

1. López-Otín C, Blasco MA, Partridge L, Serrano M, Kroemer G. The Hallmarks of Aging. *Cell* 2013;153:1194–1217.
2. López-Otín C, Blasco MA, Partridge L, Serrano M, Kroemer G. Hallmarks of aging: An expanding universe. *Cell* 2023;186:243–278.
3. Balch WE, Morimoto RI, Dillin A, Kelly JW. Adapting proteostasis for disease intervention. *Science* 2008;319:916–919.
4. Harrison DE, Strong R, Sharp ZD, et al. Rapamycin fed late in life extends lifespan in genetically heterogeneous mice. *Nature* 2009;460:392–395.
5. Miller RA, Harrison DE, Astle CM, et al. Rapamycin, but not resveratrol or simvastatin, extends life span of genetically heterogeneous mice. *J Gerontol A Biol Sci Med Sci* 2011;66:191–201.
6. Eisenberg T, Knauer H, Schauer A, et al. Induction of autophagy by spermidine promotes longevity. *Nat Cell Biol* 2009;11:1305–1314.
7. Eisenberg T, Abdellatif M, Schroeder S, et al. Cardioprotection and lifespan extension by the natural polyamine spermidine. *Nat Med* 2016;22:1428–1438.
8. Hara T, Nakamura K, Matsui M, et al. Suppression of basal autophagy in neural cells causes neurodegenerative disease in mice. *Nature* 2006;441:885–889.
9. Komatsu M, Waguri S, Chiba T, et al. Loss of autophagy in the central nervous system causes neurodegeneration in mice. *Nature* 2006;441:880–884.
10. Komatsu M, Waguri S, Koike M, et al. Homeostatic levels of p62 control cytoplasmic inclusion body formation in autophagy-deficient mice. *Cell* 2007;131:1149–1163.
11. Lee IH, Cao L, Mostoslavsky R, et al. A role for the NAD-dependent deacetylase Sirt1 in the regulation of autophagy. *Proc Natl Acad Sci USA* 2008;105:3374–3379.
12. Cuervo AM, Dice JF. Age-related decline in chaperone-mediated autophagy. *J Biol Chem* 2000;275:31505–31513.
13. Zhang C, Cuervo AM. Restoration of chaperone-mediated autophagy in aging liver improves cellular function and hepatic stress resistance. *Sci Transl Med* 2015;7:318ra197.
14. Walter P, Ron D. The unfolded protein response: from stress pathway to homeostatic regulation. *Science* 2011;334:1081–1086.
15. Taylor RC, Dillin A. XBP-1 is a cell-nonautonomous regulator of stress resistance and longevity. *Cell* 2013;153:1435–1447.
16. Kim J, Kundu M, Viollet B, Guan KL. AMPK and mTOR regulate autophagy through direct phosphorylation of Ulk1. *Nat Cell Biol* 2011;13:132–141.
17. Hsu AL, Murphy CT, Kenyon C. Regulation of aging and age-related disease by DAF-16 and heat-shock factor. *Science* 2003;300:1142–1145.
18. Chung KKK, Thomas B, Li X, et al. S-nitrosylation of parkin regulates ubiquitination and compromises parkin's protective function. *Science* 2004;304:1328–1331.
19. van Dyck CH, Swanson CJ, Aisen P, et al. Lecanemab in early Alzheimer's disease. *N Engl J Med* 2023;388:9–21.
20. Martin-Montalvo A, Mercken EM, Mitchell SJ, et al. Metformin improves healthspan and lifespan in mice. *Nat Commun* 2013;4:2192.
21. Redman LM, Smith SR, Burton JH, et al. Metabolic slowing and reduced oxidative damage with sustained caloric restriction support the rate of living and oxidative damage theories of aging. *Cell Metab* 2018;27:805–815.
22. Sardiello M, Ballabio A, et al. A gene network regulating lysosomal biogenesis and function. *Science* 2009;325:473–477.
23. Schwarz C, Benson GS, Horn N, et al. Effect of spermidine supplementation on cognitive function in older adults with subjective cognitive decline: a randomized clinical trial. *JAMA Netw Open* 2022;5:e2213875.
24. Kars M, Yang L, Gregor MF, et al. Tauroursodeoxycholic acid may improve liver and muscle but not adipose tissue insulin sensitivity in obese men and women. *Diabetes* 2010;59:1899–1905.
25. Martens CR, Denman BA, Mazzo MR, et al. Chronic nicotinamide riboside supplementation is well-tolerated and elevates NAD+ in healthy middle-aged and older adults. *Nat Commun* 2018;9:1286.

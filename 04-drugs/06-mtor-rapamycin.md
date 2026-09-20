# mTOR 通路与雷帕霉素：营养感应核心通路与最经典抗衰药 mTOR & Rapamycin

> 本文是 LongLife 知识库"营养感应"主线的核心篇目。mTOR（mechanistic/ mammalian target of rapamycin，雷帕霉素靶蛋白）通路是感知营养、能量与生长因子的细胞"总开关"，雷帕霉素是迄今为止**动物实验中延寿证据最确凿、被 NIA ITP 项目独立双盲验证**的药物干预。本文从复合体结构、上游感知、下游效应、衰老证据、人体试验与副作用六个层面展开，并在结尾与 NO / NAD⁺ / 自噬网络对接（详见 01-foundations/06-proteostasis-autophagy.md 与 04-drugs/07-metformin-ampk.md）。

---

## 一、核心概念

mTOR 是一种丝氨酸/苏氨酸激酶（289 kDa，属 PIKK 家族），以两种结构和功能截然不同的复合体存在：**mTORC1**（营养/能量敏感、驱动合成代谢）与 **mTORC2**（细胞存活/骨架调控）。mTORC1 是细胞的"营养油门"——营养充足时推动蛋白质、脂质与核苷酸合成并抑制自噬；营养匮乏时关闭合成、开启自噬与应激抵抗。这一"油门"在进化上极度保守（酵母到人类），且与衰老直接挂钩：**mTORC1 信号随营养过剩与年龄持续走高，推动 Blagosklonny 所称的"过度功能"（hyperfunction）衰老程序；抑制 mTORC1 则模拟热量限制，是唯一在标准环境下经多中心随机对照延长哺乳动物寿命的药物靶点**。雷帕霉素（rapamycin/sirolimus）作为 mTORC1 的变构抑制剂，其 2009 年 ITP 报告是衰老干预领域的里程碑事件。

## 二、分子机制全链条

### 2.1 两大复合体的组成与分工

```
mTORC1（雷帕霉素敏感）            mTORC2（急性不敏感，慢性可被抑制）
┌───────────────────────┐        ┌───────────────────────┐
│ mTOR + Raptor         │        │ mTOR + Rictor         │
│      + mLST8(GβL)     │        │      + SIN1(MAPKAP1)  │
│      + PRAS40(抑制亚基)│        │      + Protor1/2      │
│      + DEPTOR(抑制亚基)│        │      + mLST8 + DEPTOR │
│      + TTI1/TEL2      │        │      + TTI1/TEL2      │
└───────────────────────┘        └───────────────────────┘
```

- **Raptor**：mTORC1 的支架蛋白，负责募集底物（含 TOS 基序的 S6K1、4E-BP1、TFEB 等），是 AMPK 磷酸化抑制的靶点（Ser722/792）；
- **PRAS40 与 DEPTOR**：两个内源性抑制亚基。AKT 磷酸化 PRAS40（Thr246）使其从复合体解离，解除抑制；DEPTOR 在 mTORC1/2 激活时被磷酸化降解，构成负反馈；
- **Rictor/SIN1/Protor**：mTORC2 特征亚基，介导对 AKT（Ser473）、SGK1、PKCα 的磷酸化，并调控肌动蛋白骨架。雷帕霉素-FKBP12 急性期只作用于 mTORC1 的 FRB 域；长期/高剂量暴露可因游离 mTOR 池耗竭而间接破坏 mTORC2 组装（"mTORC2 慢性抑制"），这被认为是其代谢副作用（胰岛素抵抗）的机制之一。

### 2.2 上游：四类信号输入

```
生长因子 ──► RTK ──► PI3K ──► PIP3 ──► AKT ──┐
        (胰岛素/IGF-1)          │           ├─► 磷酸化 TSC2(抑制其GAP活性)
                                │           ├─► 磷酸化 PRAS40(解除抑制)
                                ▼           ▼
氨基酸(亮氨酸/精氨酸) ──► GATOR1/GATOR2 ──► RagA/B-GTP ──► 溶酶体膜 Ragulator
        (Sestrins/GATOR 感受)        │                              │
                                    ▼                              ▼
能量(低ATP) ──► AMPK ──► 磷酸化 TSC2(激活其GAP活性)          Rheb-GTP ──► mTORC1
                    └──► 磷酸化 Raptor(Ser722/792,抑制)          (溶酶体表面激活)
缺氧 ──► REDD1/2(DDIT4) ──► 激活 TSC1/2
Wnt ──► GSK3β 抑制 ──► TSC2 磷酸化减少 ──► mTORC1 激活
```

**关键节点逐一拆解**：

1. **生长因子轴（PI3K/AKT/TSC/Rheb）**：胰岛素/IGF-1 结合受体 → PI3K 生成 PIP3 → 招募并激活 AKT。AKT 磷酸化 **TSC2**（结节性硬化复合物 2，与 TSC1 构成异二聚体），抑制其作为 **Rheb 的 GTPase 激活蛋白（GAP）** 的活性——TSC1/2 是 mTORC1 的"刹车总闸"，其功能丧失（如结节性硬化症 TSC1/2 突变）导致 mTORC1 持续激活与错构瘤形成。Rheb-GTP 在溶酶体表面直接激活 mTORC1 的激酶活性。
2. **氨基酸轴（Rag GTPase 溶酶体定位）**：亮氨酸、精氨酸等通过 GATOR1/GATOR2 与 Sestrins 复合体被感知，调节 **RagA/B（GTP 结合＝活性）与 RagC/D** 的核苷酸状态。Rag 异二聚体经 **Ragulator 复合体**锚定在溶酶体膜，将 mTORC1 招募至溶酶体表面——这是 mTORC1 被 Rheb 激活的空间前提。氨基酸缺失时 GATOR1 激活 RagA/B-GAP 活性，mTORC1 从溶酶体"撤退"失活。**"氨基酸→溶酶体定位→Rheb 激活"是 mTORC1 激活的完整空间逻辑**。
3. **能量轴（AMPK）**：AMP/ATP 比值升高激活 AMPK，AMPK 双管齐下抑制 mTORC1——磷酸化 TSC2 增强其 GAP 活性，同时磷酸化 Raptor（Ser722/792）诱导其与 14-3-3 结合而失活。AMPK 同时磷酸化 ULK1（Ser317/777）激活自噬，与 mTORC1 对 ULK1 Ser757 的抑制形成"油门对刹车"的直接对撞（Kim 等 2011 *Nat Cell Biol*）。
4. **缺氧与 Wnt**：缺氧经 REDD1/2 激活 TSC1/2 抑制 mTORC1（缺氧时关闭合成、节约能量）；Wnt 信号抑制 GSK3β（GSK3β 磷酸化 TSC2 使其激活），从而解除对 mTORC1 的抑制。

### 2.3 下游：mTORC1 的五大效应臂

```
                      ┌──► S6K1 ──► S6 核糖体蛋白 ──► 翻译延伸/核糖体生物发生
                      │       └──► IRS1 负反馈磷酸化(→胰岛素抵抗,降解)
                      ├──► 4E-BP1 磷酸化 ──► 解除对 eIF4E 抑制 ──► 帽依赖性翻译
mTORC1 ──磷酸化──►   │                 (cyclin D1/c-Myc/HIF1α 等促生长 mRNA)
                      ├──► SREBP1/2 ──► 脂肪酸与胆固醇合成基因 (脂质从头合成)
                      ├──► ULK1(Ser757) ──► 抑制自噬起始
                      ├──► TFEB(Ser211)/TFE3 ──► 滞留胞质 ──► 抑制溶酶体生物发生
                      ├──► PGC-1α/YY1 ──► 线粒体生物发生(急性促线粒体)
                      └──► HIF1α 翻译 ──► 糖酵解重编程
```

- **S6K1 → 翻译与核糖体**：S6K1 磷酸化 S6 核糖体蛋白，驱动核糖体生物发生与翻译延伸，是 mTORC1 促生长的主效应器；S6K1 还磷酸化 IRS1（Ser307/636）触发胰岛素信号负反馈——mTORC1 长期过度激活由此直接制造胰岛素抵抗。**S6K1 敲除雌鼠寿命延长且抵抗年龄相关疾病（Selman 2009 *Science*），是"翻译通量驱动衰老"的遗传学证据**；
- **4E-BP1 → 帽依赖性翻译**：4E-BP1 去磷酸化时结合并抑制 eIF4E；mTORC1 磷酸化 4E-BP1（Thr37/46、Ser65、Thr70）使其释放 eIF4E，启动 cyclin D1、c-Myc、HIF1α 等促生长 mRNA 的翻译。**果蝇中 4E-BP 是雷帕霉素延寿所必需（Bjedov 2010）**，提示"选择性翻译抑制"而非全盘抑制是抗衰关键；
- **SREBP1 → 脂质合成**：mTORC1 经 SREBP1 激活脂肪酸/胆固醇从头合成，支撑膜与脂质需求——这也解释了雷帕霉素为何降脂、而 mTORC1 过度激活与脂肪肝相关；
- **ULK1/TFEB → 自噬与溶酶体**：mTORC1 磷酸化 ULK1（Ser757）与 TFEB（Ser211），前者阻断自噬起始复合物，后者将 TFEB 扣押在胞质、抑制溶酶体生物发生。**这是 mTOR 抑制延寿最核心的机制通道：解除 ULK1/TFEB 抑制 → 自噬通量上升 → 蛋白稳态与线粒体质量控制恢复**（详见 01-foundations/06）；
- **PGC-1α/线粒体**：mTORC1 经 YY1-PGC-1α 促进线粒体生物发生；慢性抑制后的净效应是诱导线粒体自噬、提升线粒体质量而非数量——"少而精"的线粒体更新。

### 2.4 mTORC2 下游

mTORC2 磷酸化 **AKT 的疏水基序 Ser473**（与 PDK1 磷酸化 Thr308 共同构成 AKT 完全激活）、**SGK1** 与 **PKCα**，并调控肌动蛋白聚合。AKT 激活反过来磷酸化 TSC2/PRAS40 激活 mTORC1——构成"mTORC2→AKT→mTORC1"的正向串联。慢性雷帕霉素抑制 mTORC2 → AKT Ser473 下降 → 胰岛素信号受损，是雷帕霉素血糖副作用的核心机制；而肿瘤细胞经 S6K1-IRS1 负反馈解除 → AKT 过度激活，则是雷帕霉素类抗癌药耐药的主要机制。

## 三、证据分级

| 现象 | 证据等级 | 关键文献 |
|---|---|---|
| TOR 抑制延长酵母复制寿命 | 实锤（遗传学，多实验室） | Kaeberlein 2005 *Science*；Powers 2006 |
| TOR RNAi 延长线虫寿命（约 2 倍） | 实锤（遗传学） | Vellai 2003 *Nature* |
| dTOR/dS6K 抑制延长果蝇寿命 | 实锤（遗传学+药物） | Kapahi 2004 *Curr Biol*；Bjedov 2010 *Nat Cell Biol* |
| 雷帕霉素延长小鼠寿命（ITP 三中心双盲） | 实锤（随机化、多中心、老年起始仍有效） | Harrison 2009 *Nature*；Miller 2011；Miller 2014 |
| 雷帕霉素效应依赖自噬/4E-BP（果蝇/线虫） | 实锤（机制因果） | Bjedov 2010；Robida-Stubbs 2012 |
| S6K1 敲除延长雌鼠寿命 | 实锤（遗传学，雌性特异） | Selman 2009 *Science* |
| 低剂量 mTOR 抑制增强老年人疫苗应答 | 强关联（RCT，样本 200-600 级） | Mannick 2014/2018/2021 |
| 雷帕霉素逆转人体表观遗传年龄 | 初步（小样本 RCT/开放试验，方向一致） | Fahy 2019/2024；PEARL 2024 |
| 人类长期低剂量抗衰适应症 | 未批准（需更大安全性与终点数据） | EVERLAST 进行中（NCT05835999） |

证据等级说明：实锤＝多物种一致或随机化对照；强关联＝RCT 但终点为替代指标；初步＝小样本/开放标签；未批准＝监管状态。

## 四、临床/实验证据细节

### 4.1 雷帕霉素：从复活节岛土壤到 ITP 里程碑

雷帕霉素 1972 年由惠氏（Ayerst）实验室从**复活节岛（Rapa Nui）土壤的吸水链霉菌（*Streptomyces hygroscopicus*）**中分离，属 31 元**大环内酯**，最初作为抗真菌药开发，后因发现抑制 T 细胞增殖而于 1999 年获 FDA 批准为肾移植免疫抑制剂，2007 年起其衍生物替西罗莫司（temsirolimus）/依维莫司（everolimus）获批抗癌。机制上，雷帕霉素在胞内与 **FKBP12** 结合，复合物再结合 mTOR 的 **FRB 域**，**变构**抑制 mTORC1（不占据 ATP 口袋、不直接抑制激酶活性）——这使其对 mTORC1 底物（S6K1 敏感、4E-BP1 部分抵抗）呈现选择性，也解释了为何 ATP 竞争型抑制剂毒性更强。

**NIA 干预测试项目（ITP）**是抗衰药物唯一的多中心随机化金标准平台：
- **Harrison 等 2009（*Nature*）**：eRapa（肠溶包衣雷帕霉素，14 ppm 饲料）从 **600 日龄**（约当人 60 岁）开始喂饲遗传异质 UM-HET3 小鼠，三中心一致显示**雄性中位寿命 +9%、雌性 +14%**——"老年起始仍有效"打破了 CR 必须早年开始的教条；
- **Miller 等 2011**：从 9 月龄开始，雌性 +18%、雄性 +10%；4.7 ppm 无效，提示阈值效应；
- **Miller 等 2014**：剂量升至 42 ppm（3 倍），**雄性 +23%、雌性 +26%**，最大寿命同时延长——**剂量依赖**确证；雌性各剂量均优于雄性，部分归因于雌鼠血药浓度更高（性别二态性）；
- **Swindell 2017 荟萃分析**（29 项实验）：雌性死亡风险比 HR=0.41（95% CI 0.35–0.48）、雄性 HR=0.63（0.55–0.71）；杂合背景小鼠获益最大（+14.4%），纯系背景差异大——**效应量级与基因背景敏感**。

### 4.2 人体试验：免疫衰老是最先突破的适应症

- **Mannick 2014（*Sci Transl Med*）**：218 名 65 岁以上老人，依维莫司 5 mg/周×6 周后接种流感疫苗，抗体应答较安慰剂**提升约 20%**，且随访期感染率下降——首次证明 mTOR 抑制可部分逆转人类免疫衰老；
- **Mannick 2018**（n=264）：RTB101（BEZ235 衍生物，双 PI3K/mTOR 抑制剂）低剂量增强疫苗应答并降低呼吸道感染率约 30%；**Mannick 2021（*Lancet Healthy Longevity*）**：2b 期（n=652）重复验证感染率下降约 30%，但 3 期（n=1435）未达主要终点——"免疫适应症"转化受挫，但为抗衰剂量学提供了关键参考；
- **TRIIM 系列（Fahy）**：2019 年 *Aging Cell* 报告 9 名 51–65 岁男性接受 rhGH+DHEA+二甲双胍 12 个月，MRI 证实**胸腺脂肪被再生组织取代**，四种表观遗传时钟平均回拨约 **2.5 岁**且停药 6 个月仍保持；2024 年扩大样本的 TRIIM-X 加入**依维莫司**，复现胸腺再生与表观年龄改善（样本量小，待核实确切 n 与效应量）；
- **PEARL 试验（Kaeberlein 等）**：首个雷帕霉素抗衰双盲安慰剂对照 RCT，约 60 名 50–85 岁成人，雷帕霉素 5 mg/周×1 年：主要终点（内脏脂肪减少）未达标，但**次要终点表观遗传年龄减速、去脂体重增加、疼痛减轻**方向一致；药代显示定制（compounded）制剂血药浓度仅为市售品的约 1/3，提示剂型可能削弱了效应；
- **EVERLAST（NCT05835999）**：威斯康星大学 II 期，依维莫司 0.5 mg/日或 5 mg/周×24 周，入组 55–80 岁胰岛素抵抗/糖尿病前期人群，多组学评估 mTORC1/2 信号与线粒体功能，进行中；
- **犬类**：Dog Aging Project 试点（雷帕霉素 0.05–0.1 mg/kg，每周 3 次）显示老年犬心脏舒张功能改善、无显著副作用，大规模犬 RCT 进行中。

### 4.3 副作用与给药方案优化

| 副作用 | 机制 | 应对 |
|---|---|---|
| 免疫抑制/感染 | T 细胞增殖抑制（FKBP12-雷帕霉素阻断 IL-2 信号） | 低剂量脉冲给药 |
| 口腔溃疡（阿弗他溃疡） | 上皮 mTORC1 抑制（人体最常见剂量限制性毒性） | 每周一次/隔周给药、含漱 |
| 血糖升高/胰岛素抵抗 | 慢性给药抑制 mTORC2 → AKT Ser473 下降 | 间歇方案保留 S6K1 抑制而减轻 mTORC2 损伤 |
| 血脂异常 | SREBP 通路扰动的补偿性上调 | 监测血脂 |
| 伤口愈合延迟 | 成纤维细胞增殖与血管新生抑制 | 围手术期停药 |
| 小鼠：睾丸退化、肝脂肪变性 | mTORC1 抑制的生殖/代谢代价 | 剂量与周期的平衡（Gkioni 2025 *Nat Aging*） |

**关键发现：间歇给药（eRapa，隔周一次）在雌性 C57BL/6J 小鼠中仍延长寿命约 26%，且对葡萄糖代谢的副作用小于连续给药（Arriola Apelo 等 2016 *J Gerontol A*）**——"脉冲式抑制"成为人体抗衰的主流方案假设：在 S6K1 恢复窗口期保留部分合成能力，同时避免持续的 mTORC2 抑制与免疫抑制。Trametinib（MEK 抑制剂）与雷帕霉素联用在 2025 年 *Nat Aging* 中显示健康寿命与寿命加性延长约 30%，提示组合策略空间。

## 五、与 NO / NAD⁺ / 长寿网络的联系

```
营养过剩 ──► mTORC1↑ ──► S6K1 磷酸化 IRS1 ──► 胰岛素抵抗 ──► eNOS 活性↓/NO↓
能量/运动 ──► AMPK↑ ──► NAD⁺/SIRT1↑ ──► 抑制 mTORC1(TSC2/Raptor) ──► 自噬↑
NO ──► sGC/cGMP/PKG ──► AMPK↑(机制研究表明) ──► 抑制 mTORC1
雷帕霉素 ──► 自噬↑ ──► 线粒体质量控制 ──► ROS↓ ──► eNOS 偶联保持 ──► NO 生物利用度↑
```

本库主线的对接点有四：
1. **mTOR 与 NO 互为上下游**：内皮细胞中雷帕霉素可上调 eNOS 表达、改善内皮依赖的血管舒张（部分组织，机制研究表明），而 NO 经 cGMP-PKG-AMPK 与 SIRT1 两条路径抑制 mTORC1——**NO 是 mTOR 的上游刹车，mTOR 抑制又是 NO 信号的保护者**，二者构成"血管-代谢"正反馈；
2. **AMPK–mTOR–SIRT1 轴**：能量应激时 AMPK 抑制 mTORC1 并提升 NAD⁺（经 NAMPT），SIRT1 去乙酰化 TSC2/LKB1 进一步压制 mTORC1——**NAD⁺ 随龄下降 → SIRT1 失活 → mTORC1 去抑制**，是"衰老时钟"与营养感应的耦合点（详见 01-foundations/03-no-basics.md）；
3. **自噬枢纽**：mTORC1 对 ULK1(Ser757)/TFEB(Ser211) 的磷酸化抑制与 AMPK/SIRT1 对自噬的激活构成"合成-分解"天平，NO、NAD⁺、热量限制均作用于该天平（详见 01-foundations/06）；
4. **mTOR 与癌症张力**：mTORC1 促进翻译与增殖（促癌），但慢性抑制削弱免疫监视（T 细胞功能）且经 S6K1-IRS1 负反馈解除导致 AKT 过度激活（促癌耐药）——抗癌与抗衰在 mTOR 上的利益并非完全一致，需个体化权衡。

## 六、干预方向与可执行建议

按证据强度排序：
1. **生活方式（最可靠）**：热量限制/间歇性禁食（AMPK→mTORC1 抑制）、耐力运动（AMPK+eNOS/NO）、蛋白质总量与亮氨酸摄入管理（氨基酸→Rag→mTORC1）——三者均作用于同一油门，且叠加 NAD⁺ 轴；
2. **已有人体数据的药物**：依维莫司低剂量脉冲（疫苗应答 +20%，Mannick 2014）；雷帕霉素 5 mg/周方案（PEARL 次级终点阳性，表观年龄减速）——**必须在医生监测下**，重点监测血脂、血糖、口腔黏膜与感染；
3. **临床前组合管线**：雷帕霉素+二甲双胍（AMPK 协同）、雷帕霉素+trametinib（*Nat Aging* 2025 小鼠 +30%）、雷帕霉素+senolytics（自噬清衰老细胞上游）；
4. **可监测指标**：空腹血糖/胰岛素与 HOMA-IR、血脂谱、口腔溃疡与感染频率、表观遗传时钟（GrimAge/PhenoAge）、循环 p62/LC3 作为自噬通量替代读数；
5. **风险提示**：目前全球无任何监管机构批准雷帕霉素用于抗衰；所有人体方案均为 off-label 探索，长期安全数据（>2 年）尚缺。

## 七、开放问题与争议

1. **连续 vs 脉冲**：间歇给药在啮齿类保留延寿效应并减轻代谢副作用，但人类最佳周期（每周/隔周/每月）与剂量-血药浓度-效应关系未定；
2. **mTORC1 特异性**：雷帕霉素对 4E-BP1 抑制不完全（相对 S6K1），"部分 4E-BP1 抑制是否反而必要"尚无定论；ATP 竞争型（BEZ235 类）虽更强但毒性（高血糖、胃肠道）与 3 期失败使其抗衰前景存疑；
3. **免疫监视张力**：长期低剂量 mTOR 抑制在"增强疫苗应答"（促免疫）与"抑制 T 细胞增殖"（抑免疫）之间如何平衡？感染风险的真实绝对增幅未知；
4. **代谢代价**：慢性 mTORC2 抑制致胰岛素抵抗，与抗衰目标（代谢健康）存在内在矛盾——能否设计 mTORC1 特异性抑制剂（如 Raptor 降解剂、Rag 通路抑制剂）绕开？
5. **表观年龄减速的临床意义**：PEARL 与 TRIIM 的表观时钟变化幅度（约 1–2.5 年）是否对应真实的健康寿命获益，仍需以发病/失能/死亡为终点的大型试验（如未来的人体 ITP 式平台）回答。

## 参考文献

1. Harrison DE, Strong R, Sharp ZD, et al. Rapamycin fed late in life extends lifespan in genetically heterogeneous mice. *Nature* 2009;460:392–395.
2. Miller RA, Harrison DE, Astle CM, et al. Rapamycin, but not resveratrol or simvastatin, extends life span of genetically heterogeneous mice. *J Gerontol A Biol Sci Med Sci* 2011;66:191–201.
3. Miller RA, Harrison DE, Astle CM, et al. Rapamycin-mediated lifespan increase in mice is dose and sex dependent and metabolically distinct from dietary restriction. *Aging Cell* 2014;13:468–477.
4. Swindell WR. Meta-analysis of 29 experiments evaluating the effects of rapamycin on life span in the laboratory mouse. *J Gerontol A Biol Sci Med Sci* 2017;72:1024–1032.
5. Vellai T, Takacs-Vellai K, Zhang Y, et al. Genetics: influence of TOR kinase on lifespan in *C. elegans*. *Nature* 2003;426:620.
6. Kapahi P, Zid BM, Harper T, et al. Regulation of lifespan in *Drosophila* by modulation of genes in the TOR signaling pathway. *Curr Biol* 2004;14:885–890.
7. Kaeberlein M, Powers RW, Steffen KK, et al. Regulation of yeast replicative life span by TOR and Sch9 in response to nutrients. *Science* 2005;310:1193–1196.
8. Selman C, Tullet JMA, Wieser D, et al. Ribosomal protein S6 kinase 1 signaling regulates mammalian life span. *Science* 2009;326:140–144.
9. Bjedov I, Toivonen JM, Kerr F, et al. Mechanisms of life span extension by rapamycin in the fruit fly *Drosophila melanogaster*. *Cell Metab* 2010;11:35–46.
10. Kim J, Kundu M, Viollet B, Guan KL. AMPK and mTOR regulate autophagy through direct phosphorylation of Ulk1. *Nat Cell Biol* 2011;13:132–141.
11. Mannick JB, Del Giudice G, Lattanzi M, et al. mTOR inhibition improves immune function in the elderly. *Sci Transl Med* 2014;6:268ra179.
12. Mannick JB, Morris M, Hockey HP, et al. TORC1 inhibition enhances immune function and reduces infections in the elderly. *Sci Transl Med* 2018;10:eaaq1564.
13. Mannick JB, Teo G, Bernardo P, et al. Targeting the biology of aging with mTOR inhibitors to improve immune function in older adults: phase 2b and phase 3 randomised trials. *Lancet Healthy Longev* 2021;2:e250–262.
14. Fahy GM, Brooke RT, Watson JP, et al. Reversal of epigenetic aging and immunosenescent trends in humans. *Aging Cell* 2019;18:e13028.
15. Arriola Apelo SI, Pumper CP, Baar EL, et al. Intermittent administration of rapamycin extends the life span of female C57BL/6J mice. *J Gerontol A Biol Sci Med Sci* 2016;71:876–881.
16. Gkioni L, Nespital T, Baghdadi M, et al. The geroprotectors trametinib and rapamycin combine additively to extend mouse healthspan and lifespan. *Nat Aging* 2025.（DOI: 10.1038/s43587-025-00876-4）
17. Fahy GM, et al. TRIIM-X 试验（依维莫司+rhGH+DHEA+二甲双胍）. *Aging Cell* 2024.（具体效应量待核实）
18. Kaeberlein M, et al. Influence of rapamycin on safety and healthspan metrics after one year: PEARL trial results. *Aging (Albany NY)* 2024/2025.（medRxiv 2024.08.21.24312372）
19. López-Otín C, Blasco MA, Partridge L, Serrano M, Kroemer G. Hallmarks of aging: an expanding universe. *Cell* 2023;186:243–278.
20. Kim J, Guan KL. mTOR as a central hub of nutrient signalling and cell growth. *Nat Cell Biol* 2019;21:63–71.（通路综述）

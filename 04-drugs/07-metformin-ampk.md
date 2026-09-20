# 二甲双胍与AMPK：老药新用的抗衰先锋

> 本文是 LongLife 知识库"代谢类抗衰干预"的核心篇目之一，与 02-vascular/03-metabolic-aging.md（代谢衰老）、01-foundations/03-no-basics.md（NO 通路）、04-drugs/05-molecular-mech.md（eNOS/sGC 分子机制）互相引用。二甲双胍（Metformin）是唯一进入大型注册抗衰临床试验（TAME）的已上市药物，其机制核心是激活 AMPK——细胞能量感受器——并以此为枢纽牵动 mTORC1、自噬、线粒体生物发生、NO 与 NAD+ 网络。

---

## 核心概念

二甲双胍（metformin，化学名二甲基双胍）是全球处方量最大的口服降糖药，年处方量以亿计，成本低廉、安全性记录超过 60 年。它也是**唯一已进入大型注册抗衰老临床试验（TAME）的已上市药物**，被长寿研究界视为"老药新用"的旗舰候选。其标志性分子靶点是 AMPK（AMP 活化蛋白激酶，AMP-activated protein kinase）——进化上高度保守的细胞能量感受器：AMPK 感知 AMP/ATP 与 ADP/ATP 比值升高，一旦激活便关闭耗能的合成代谢（蛋白/脂质/胆固醇合成、mTORC1），打开产能的分解代谢（糖摄取、脂肪酸氧化、自噬、线粒体生物发生），并上调应激抵抗与炎症清除程序。抗衰逻辑由此而来：衰老的标志之一正是"营养感应失调"（AMPK 活性随龄下降、mTORC1 过度激活），二甲双胍以"模拟能量匮乏"的方式逆转这一失衡，同时经 AMPK→eNOS 通路增强 NO 生成，兼具血管保护效应。必须强调：其抗衰证据在人体层面仍以观察性研究为主，随机对照证据（TAME）截至 2026 年尚未公布——"降糖实锤、抗衰待证"是对它最准确的定位。

## 1. 历史：从法国紫丁香到全球畅销药

二甲双胍的故事是"民间草药→化学合成→临床再发现"的经典路径：

- **民间用药**：二甲双胍的天然前体来自**法国紫丁香（Galega officinalis，山羊豆/芸香）**，中世纪欧洲即有以该植物治疗多尿、消渴症状的记录。其活性成分为胍类生物碱——山羊豆碱（galegine），是胍（guanidine）的异戊烯衍生物。
- **化学时代**：1920s 科学家开始系统研究胍类降糖药。1922 年 Werner 与 Bell 首次化学合成二甲双胍（二甲基双胍），但真正开启临床探索的是 1929 年 Slotta 与 Tschesche 对多种双胍类化合物降糖活性的筛选。1920s–1930s 间胍及十烷双胍（synthalin）因肝毒性被弃用，双胍类一度沉寂。
- **临床再发现**：1950s 法国医生 **Jean Sterne** 于 1957 年重新评估二甲双胍（商品名 Glucophage，"噬糖者"），奠定其临床地位。同期苯乙双胍（phenformin，DBI）上市，但因高乳酸酸中毒死亡率（约 50 例/10 万人年，远高于二甲双胍）在 1970s 被各国撤市——这一事件深刻影响了二甲双胍的监管路径与"乳酸酸中毒恐惧"，其风险其实被长期高估。
- **全球普及**：1994 年美国 FDA 批准二甲双胍用于 2 型糖尿病；1998 年 UKPDS 研究发表奠定其一线地位；2016 年 TAME 试验获批设计，正式进入抗衰赛道。至今 WHO 基本药物清单在列，年花费通常不足百元人民币。

**历史教训与抗衰启示**：苯乙双胍的覆灭让整个双胍类都背上了"乳酸酸中毒"的污名，但循证数据显示二甲双胍的该风险比磺脲类或安慰剂并无显著升高（详见副作用节）。这也提醒抗衰研究者：一个分子"毒性"的判断必须以真实证据分级为准，而非同类化合物的历史包袱。

## 2. 药代动力学：转运体决定一切

二甲双胍的药代动力学特点是"水溶性极强、无蛋白结合、不经过肝脏代谢、以原形经肾排泄"，体内分布几乎完全由**有机阳离子转运体（OCT）**家族决定：

| 参数 | 数值 | 要点 |
|---|---|---|
| 口服生物利用度 | 约 50–60% | 主要在小肠上段吸收，个体差异大（25–90%） |
| 血浆峰浓度（Cmax） | 约 10–40 µM（常规剂量） | 肝内浓度可高出血浆数十倍（可达 100 µM+ 级别） |
| 达峰时间 | 1–3 h（普通片） | 缓释剂型延迟至 4–8 h |
| 分布容积 | 约 300–500 L | 组织富集于肝、肾、肠壁 |
| 血浆半衰期 | 约 6.2 h（4–8.7 h） | 组织半衰期更长，约 17.6 h |
| 排泄 | 原形经肾小球滤过 + 肾小管分泌 | 无 CYP 代谢，药物相互作用少 |

**转运体全景**（二甲双胍体内命运的"守门人"）：

```
肠道吸收: PMAT (SLC29A4, 肠上皮顶膜) + OCT3 (SLC22A3)
   ↓
肝摄取:   OCT1 (SLC22A1, 肝细胞基底膜) ← 二甲双胍降肝糖输出的主入口
   ↓
肾排泄:   OCT2 (SLC22A2, 肾近端小管基底膜) → 管腔侧 MATE1/MATE2-K (SLC47A1/A2) 分泌入尿
```

- **OCT1（肝摄取）**：基因多态性（如 R61C、G401S 等减低功能变异）导致约 7–10% 人群肝摄取下降、降糖效果减弱——这是"同样剂量疗效因人而异"的遗传基础，也提示肝内浓度（而非血浆浓度）才是药效关键。
- **OCT2/MATE（肾排泄）**：OCT2 抑制剂（如西咪替丁、某些非甾体抗炎药、度鲁特韦）减少肾小管分泌，可升高血药浓度；肾功能不全者（eGFR < 30 mL/min/1.73m²）因排泄受阻禁用，eGFR 30–45 区间需减量并谨慎使用。
- **药物相互作用**：因不依赖 CYP450，二甲双胍与其他药物的相互作用远少于多数降糖药，这也是其老年人长期使用的优势之一。

**浓度-效应悖论（重要）**：二甲双胍的血浆浓度（10–40 µM）远低于体外抑制线粒体复合物 I 所需的毫摩尔级浓度，这催生了"生理浓度下主靶点到底是什么"的长期争论（详见机制节）。药代动力学数据是理解这一悖论的前提：组织（尤其肝脏）内浓度远高于血浆，但即便如此，2022 年的 PEN2 溶酶体通路研究正是从"低浓度才有效"出发重新定位了分子靶点。

## 3. 分子机制全链条

### 3.1 AMPK：细胞的能量感受器

AMPK 是由 **α（催化）、β（支架）、γ（调节）三个亚基**组成的异源三聚体，哺乳动物各亚基有多个亚型（α1/α2、β1/β2、γ1/γ2/γ3），组合出 12 种以上三聚体，组织分布不同（如骨骼肌以 α2β2γ3 为主，肝脏以 α1/α2β1γ1 为主）。其核心调控逻辑：

- **γ 亚基**含 4 个串联的 CBS 域（胱硫醚β合酶域），形成 4 个核苷酸结合口袋（Bateman 域），可竞争性结合 **AMP、ADP 与 ATP**——这是 AMPK 感知"能量货币汇率"的分子基础。
- **α 亚基**活化环上的 **Thr172** 是被上游激酶磷酸化激活的关键位点（也存 Thr172 以外的调控，如 α 亚基自抑制域 AID 与 CBM 的相互作用）。
- **β 亚基**含糖原结合域（CBM），使 AMPK 能"锚定"在糖原颗粒上，直接感知糖原水平。

**AMP 激活 AMPK 的三重机制**（这是整个能量感应领域的教科书内容）：

```
能量匮乏(AMP↑ / ATP↓)
   │
   ▼
AMP 结合 γ 亚基 ──┬─→ ① 变构激活（酶活性小幅上升, ~2-5倍）
                  ├─→ ② 保护 Thr172 不被 PP2C/PP2A 去磷酸化（"抗去磷酸化"）
                  └─→ ③ 使 Thr172 对上游激酶 LKB1 的磷酸化更敏感（"促磷酸化"）
   │
   ▼
Thr172 磷酸化 → 激酶活性暴涨 100 倍以上 → 磷酸化下游底物
```

上游激酶有两套：**LKB1**（肿瘤抑制因子，与 STRAD/MO25 组成复合物）是能量匮乏条件下的主激酶；**CaMKK2（CaMKKβ）** 响应 Ca²⁺ 升高（如肌肉收缩、神经兴奋），实现"能量信号与钙信号"的双通道汇合。去磷酸化由 PP2Cα 等磷酸酶执行。**ADP 也有保护 Thr172 的作用（但不引起变构激活）**，ATP 则拮抗两者——因此 AMPK 实际感知的是 AMP/ATP 与 ADP/ATP 双比值。

### 3.2 经典机制：抑制复合物 I → AMP/ATP↑ → AMPK 激活

二甲双胍激活 AMPK 的经典模型（Zhou 2001; El-Mir 2000; Owen 2000）：

```
二甲双胍 (带正电荷, 依赖膜电位富集于线粒体基质)
   │
   ▼
抑制线粒体电子传递链 复合物 I (NADH:泛醌氧化还原酶)
   │  (轻微抑制, 不致死; 呼吸链"减速"而非"刹死")
   ▼
ATP 生成↓ → AMP/ATP 比值↑
   │
   ▼
AMP 结合 AMPKγ → LKB1 磷酸化 Thr172 → AMPK 激活
   │
   ├─→ 抑制合成代谢 (mTORC1/ACC/HMGCR) ← 见 3.4
   └─→ 激活分解代谢 (自噬/线粒体生物发生/糖摄取)
```

**关键细节**：二甲双胍是亲脂性阳离子，在线粒体内膜电位驱动下**富集于基质**（基质浓度可比胞质高 10–1000 倍），这是其对复合物 I 产生抑制的物理前提。抑制是"轻度、部分性"的——若完全抑制复合物 I 会导致细胞死亡，而二甲双胍只是轻微降低呼吸效率、使细胞进入"节能模式"，同时伴随**低水平线粒体 ROS 升高**——后者本身就是一种**毒物兴奋效应（hormesis）**信号，可诱导抗氧化与应激抵抗程序（线虫研究中被称为 mitohormesis，De Haes 2014）。低剂量 ROS 激活 Nrf2/SKN-1 等转录因子，是二甲双胍"以毒攻毒"式抗衰的潜在环节。

### 3.3 AMPK 非依赖机制：近年机制图景的扩容

肝脏 AMPK 敲除小鼠中二甲双胍仍能抑制糖异生（Foretz 2010），证明**降糖主效应并不完全依赖 AMPK**。目前已确认的 AMPK 非依赖通路至少有四条：

| 通路 | 机制 | 效应 | 关键文献 |
|---|---|---|---|
| Rag GTPase 通路 | 二甲双胍升高 AMP 后（或直接经 v-ATPase/Ragulator 复合物）改变 Rag 核苷酸状态，使 mTORC1 无法被招募到溶酶体膜 | 直接抑制 mTORC1，绕过 AMPK→TSC2/Raptor | Kalender 2010 Cell Metab |
| mGPD 抑制 | 抑制线粒体甘油-3-磷酸脱氢酶（mGPD, GPD2），阻断胞质 NADH 向线粒体穿梭，胞质 NADH/NAD+ 比值↑ | 抑制糖异生（乳酸/甘油→葡萄糖），快速降糖 | Madiraju 2014 Nature |
| 肠道菌群重塑 | 改变肠道菌群组成（拟杆菌门/厚壁菌门比值、Akkermansia muciniphila 增多），经菌群-宿主代谢轴改善糖稳态；线虫中二甲双胍延寿依赖细菌的叶酸/甲硫氨酸代谢 | 全身代谢改善、抗炎 | Cabreiro 2013 Cell; Shin 2014 Gut |
| 一碳代谢/叶酸 | 干扰叶酸与甲硫氨酸循环（部分经抑制 MTHFD1 等一碳酶），改变 SAM/SAH 比值与表观遗传底物供给 | 影响甲基化与核苷酸合成 | Cabreiro 2013; 机制研究 |

**PEN2 溶酶体通路（2022 年里程碑）**：Ma 等（Nature 2022）发现二甲双胍在**低浓度（接近生理浓度）**下经溶酶体膜蛋白 **PEN2 → ATP6AP1 → v-ATPase** 激活溶酶体定位的 AMPK（与 AXIN/LAMTOR 复合物偶联），而**并不显著抑制复合物 I**。这直接挑战了"复合物 I 是唯一主靶点"的经典模型，提出一个整合框架：**低剂量主要经 PEN2 溶酶体通路、高剂量才叠加复合物 I 抑制**——与 Martin-Montalvo 2013 中小鼠"低剂量延寿、高剂量有害"的剂量效应遥相呼应。截至 2026 年，两条通路在体内的相对贡献仍是活跃争论。

### 3.4 AMPK 下游效应全景：合成代谢刹车 + 分解代谢油门

AMPK 激活后通过**直接磷酸化代谢酶**（秒-分钟级）与**磷酸化转录因子/表观因子**（小时级）双时相发挥作用：

```
AMPK 激活 (Thr172-P)
   │
   ├─ 抑制合成代谢 ────────────────────────────────────
   │   ├─→ 磷酸化 Raptor(Ser792) → 14-3-3 结合 → mTORC1 底物招募↓ → 蛋白合成↓
   │   ├─→ 磷酸化 TSC2(Ser1387) → TSC1/2 激活 → Rheb-GAP → Rheb-GDP(失活) → mTORC1↓
   │   ├─→ 磷酸化 ACC1(Ser79)/ACC2(Ser221) → 丙二酰CoA↓ → 脂肪酸合成↓、β-氧化↑
   │   ├─→ 磷酸化 HMGCR(Ser872) → 胆固醇合成↓
   │   └─→ 磷酸化 SREBP1c → 脂质合成基因转录↓
   │
   └─ 激活分解代谢 ────────────────────────────────────
       ├─→ 磷酸化 ULK1(Ser317/Ser777) → 启动自噬/线粒体自噬(与PINK1-Parkin协同)
       ├─→ 磷酸化 PGC-1α(Thr177/Ser538) + 后续SIRT1去乙酰化 → 线粒体生物发生↑
       ├─→ 促进 GLUT4 转位 → 骨骼肌/脂肪葡萄糖摄取↑
       ├─→ 磷酸化 eNOS(Ser1177) → NO 生成↑ (见第 7 节)
       ├─→ 激活 TFEB → 溶酶体生物发生、自噬通量↑
       ├─→ 磷酸化 PFKFB3 → 糖酵解通量↑
       └─→ 磷酸化 p53/FOXO → 应激抵抗、细胞周期检查点
```

**与衰老标志的逐条对应**：mTORC1 抑制 → 对抗"营养感应失调"（衰老标志 8）；自噬/线粒体自噬启动 → 对抗"自噬受损"（标志 11）与"线粒体功能障碍"（标志 3）；PGC-1α → 线粒体生物发生；eNOS/NO → 血管与内皮健康；抗炎（NF-κB 抑制）→ 对抗"慢性炎症"（标志 10）与 SASP（细胞衰老标志 12 的分泌表型）。AMPK 由此成为**贯穿 12 大衰老标志的"多效枢纽"**。

## 4. 证据分级

| 现象 | 证据等级 | 关键文献 |
|---|---|---|
| 2 型糖尿病降糖、减少微血管/大血管并发症 | 实锤（RCT） | UKPDS 34, Lancet 1998 |
| 糖尿病前期预防（降低进展为糖尿病风险） | 实锤（RCT，DPP） | NEJM 2002; Diabetes Care 2019 |
| 小鼠延寿与健康期延长 | 动物支持（部分模型阳性） | Martin-Montalvo 2013 Nat Commun; Anisimov 2008 |
| 线虫延寿（依赖细菌叶酸代谢/AMPK） | 动物支持（机制与菌群依赖，存在阴性报道） | Onken 2010; Cabreiro 2013; De Haes 2014 |
| 使用者全因死亡/心血管死亡低于匹配对照 | 强关联（观察性，混杂明显） | Bannister 2014; Campbell 2017 |
| 糖尿病患者用二甲双胍后生存不差于甚至优于非糖尿病人 | 观察性（健康使用者偏倚风险高） | Bannister 2014 |
| 癌症风险降低 | 关联（荟萃约 -10%，混杂严重） | Evans 2005 BMJ; Noto 2012 |
| 健康老年人抗衰（复合终点） | 机制推测/试验进行中 | TAME（Barzilai 2016 设计；结果未公布） |
| 改善内皮功能/NO 依赖血管舒张 | 动物+小样本人体 | Mather 2001; Chen 1999 |
| 抑制 SASP/抗炎 | 体外+动物强，人体间接 | Moiseeva 2013; Cameron 2016 |
| 长期使用 B12 缺乏 | 实锤（RCT 4 年随访） | de Jager 2010 BMJ |
| 乳酸酸中毒（肾功能正常者） | 实锤为"风险极低"（非劣于安慰剂） | Salpeter 2010 Cochrane |

## 5. 抗衰证据细节：从线虫到 TAME

### 5.1 动物模型

- **线虫（C. elegans）**：Onken & Driscoll（2010）报道二甲双胍延长线虫健康期，依赖 AMPK（aak-2）与 SKN-1/Nrf2 通路，呈现类似饮食限制的状态；Cabreiro 等（2013, Cell）更揭示其延寿**依赖肠道细菌的叶酸/甲硫氨酸代谢**——无菌或叶酸代谢受阻的线虫中效应消失，首次把"菌群"写进二甲双胍的抗衰机制。需注意存在阴性/缩短寿命的报道，且效应大小受剂量、菌株与细菌基因型影响。
- **小鼠**：**Martin-Montalvo 2013（Nat Commun）**是核心文献——B6C3F1 小鼠饲喂 0.1% 二甲双胍，**雄性平均寿命延长约 5.8%、雌性约 4.3%**（健康期同样延长），并伴随抗氧化应激能力增强与线粒体功能改善；**关键发现是剂量双相：1% 高剂量反而缩短寿命**，提示"越多越好"是误区。Anisimov 2008 在 SHR 雌鼠亦观察到延寿。相反，美国 **ITP（干预测试项目）**在遗传异质小鼠（UM-HET3）中的测试未重现显著延寿效应，提示效应存在品系/遗传背景依赖性。
- **解读**：动物证据整体呈"部分支持、剂量敏感、机制复杂"的形态，与雷帕霉素在 ITP 中跨品系一致的延寿效应相比，二甲双胍的动物证据更弱也更依赖背景。

### 5.2 人体证据：UKPDS、DPP 与观察性队列

- **UKPDS 34（1998, Lancet）**：超重 2 型糖尿病患者二甲双胍强化治疗 vs 常规治疗——糖尿病相关终点风险 **-32%**（RR 0.68）、全因死亡 **-36%**（RR 0.64）、心肌梗死 **-39%**（RR 0.61）。10 年随访（Holman 2008, NEJM）显示**遗留效应（legacy effect）**：即使后续血糖控制趋同，二甲双胍组心肌梗死（RR 0.67）与全因死亡（RR 0.73）风险仍持续更低——**效应超越单纯降糖**，这是"二甲双胍可能作用于衰老本身"最重要的临床暗示。
- **DPP/DPPOS（2002 NEJM 起）**：糖尿病前期人群 850 mg 每日两次，3 年糖尿病发生率较安慰剂 **-31%**；15 年随访（DPPOS）累积发生率 -18%；**60 岁以上人群获益更大（约 -71% 级别，远高于年轻组）**——"年龄越大越受益"的反直觉发现，被抗衰界反复引用。
- **观察性队列（混杂需警惕）**：Bannister 2014 基于英国 CPRD 78,241 例——起始二甲双胍的糖尿病患者全因死亡风险**低于**匹配的非糖尿病对照（约 -15% 级别，HR≈0.85），且显著优于起始磺脲类者；Campbell 2017 在大型美国队列中类似地观察到二甲双胍使用者生存与非糖尿病对照相当甚至更优。这些结果指向"二甲双胍使用者活得比没病的对照还长"的惊人画面，但**健康使用者偏倚（healthy-user bias）与适应症偏倚**（能耐受二甲双胍者本身更健康）无法排除，不能作因果解读。
- **TAME 试验（Targeting Aging with Metformin）**：首个以抗衰为直接目的的注册 RCT，Nir Barzilai 团队设计（Cell Metab 2016），计划纳入约 3000 名 65–79 岁非糖尿病老年人，二甲双胍 1500 mg/日，主要终点为**"新发衰老相关疾病（心血管、癌症、痴呆、死亡等）复合终点"**——用"推迟多病共存（multimorbidity）"来操作化"延缓衰老"。2016 年获批设计，因招募与经费问题多次推迟，截至 2026 年结果尚未公布。它若阳性，将是"代谢药物延缓人类生物衰老"的首个注册级证据；若阴性，则把二甲双胍的抗衰叙事整体降级。

## 6. 副作用与安全性：被高估的恐惧与被低估的缺憾

| 副作用 | 发生率/风险 | 要点 |
|---|---|---|
| 胃肠道反应（腹泻、恶心、腹胀） | 约 20–30%（早期） | 最常见；低剂量起始、随餐服用、缓释剂型可缓解；多数自行耐受 |
| 维生素 B12 缺乏 | 长期使用（≥4 年）显著升高；血 B12 下降约 15–25% 级别 | 机制涉及钙依赖的 B12-内因子肠道吸收；可致周围神经病变，与糖尿病神经病变难区分；建议定期监测或预防性补充 |
| 乳酸酸中毒 | **极罕见**（约 1–4 例/10 万人年），与安慰剂/其他降糖药无显著差异（Salpeter 2010 荟萃） | 主要见于 eGFR<30、急性肾损伤、失代偿心衰、肝病、脓毒症等"乳酸清除能力崩溃"情境；肾功能正常者风险可忽略 |
| 造影剂肾损伤风险 | 需管理 | 碘造影剂前按指南暂停（eGFR<60 时通常建议停用） |
| 与运动的交互 | 争议 | Konopka 2019 提示可削弱老年人运动的线粒体适应（详见争议节） |

**监管演变**：2016 年 FDA 修订说明书，将禁忌从"肌酐异常"放宽为 eGFR<30 禁用、eGFR 30–45 减量慎用——承认此前的乳酸酸中毒禁忌过度保守。这一演变本身即是循证医学修正历史污名的案例。

## 7. 与 NO / NAD+ / 长寿网络的联系（本库特色视角）

**AMPK→eNOS→NO 轴**：AMPK 直接磷酸化内皮型一氧化氮合酶（eNOS）的 **Ser1177** 激活位点（Chen 1999, FEBS Lett），与 Akt 共享同一"主开关"磷酸化位点；二甲双胍经此通路增强内皮依赖性舒张。人体证据：Mather 2001（JACC）在 2 型糖尿病患者中观察到二甲双胍改善前臂血流介导的血管舒张（NO 依赖成分）；动物实验广泛支持二甲双胍改善内皮功能、减轻动脉粥样硬化。这使二甲双胍成为"**代谢药物兼作血管保护剂**"的典型——与中药"益气活血"治法的现代解释（见 01-foundations/03-no-basics.md）在"改善内皮 NO 供给"这一交汇点上同构。

**AMPK→NAD+→SIRT1 轴**：Cantó & Auwerx（2009, Nature）证明 AMPK 激活后上调 **NAMPT**（NAD+ 补救合成限速酶），升高 NAD+，从而激活 SIRT1；SIRT1 去乙酰化 PGC-1α 与 AMPK 的磷酸化形成"**磷酸化+去乙酰化**"双修饰协同，放大线粒体生物发生。部分研究还提示二甲双胍本身可升高 NAD+ 水平（机制涉及一碳代谢重编程，待核实具体通路细节）。由此形成**二甲双胍→AMPK→NAD+/SIRT1→PGC-1α** 的完整长寿网络闭环（详见 02-vascular/03-metabolic-aging.md 第 4 节）。

**NO 的双刃剑警示**：二甲双胍轻度升高线粒体 ROS（hormesis）与 NO 在氧化应激下生成 ONOO⁻ 的机制（见 04-drugs/05-molecular-mech.md）提示：任何"促 NO/促 ROS"干预都必须在氧化还原平衡的框架内理解——这也是本库对二甲双胍"整体获益"解释的理论锚点：适度应激诱导适应，过度应激造成损伤。

## 8. 二甲双胍与癌症：最有希望却最难证实的旁证

流行病学线索始于 Evans 2005（BMJ）——二甲双胍使用者癌症风险降低；此后数十项队列与荟萃分析总体支持"风险降低约 10% 级别"（Noto 2012, PLoS One），结直肠癌、乳腺癌、前列腺癌的亚组信号相对一致。机制上自洽：AMPK→mTORC1 抑制（mTORC1 是促癌增殖核心）、AMPK→p53 通路、二甲双胍降低胰岛素/IGF-1 水平（高胰岛素血症本身是促癌因子）、抑制炎症与 SASP（Moiseeva 2013 证明二甲双胍经 IKK/NF-κB 干扰抑制衰老细胞的 SASP）。**但观察性证据的混杂（疾病分期、用药时长、健康行为）极为严重**，Morales & Morris 2015 的综述明确指出：纳入设计更严格的研究后效应明显衰减；随机化的癌症终点试验基本缺位。结论：机制合理、关联存在、因果未证。

## 9. 干预方向与可执行建议

**适用人群优先级**（按证据强度排序）：

1. **2 型糖尿病/糖尿病前期/代谢综合征**：证据最强的合法适应症；DPP 显示 60 岁以上获益更大。
2. **肥胖/胰岛素抵抗但未达糖尿病**：降糖外改善代谢表型，证据中等。
3. **健康老年人（无代谢指征）**：仅限临床试验情境（TAME）；截至 2026 年不构成常规推荐，需等 RCT 结果。

**剂量与用法**（参考糖尿病治疗实践，抗衰剂量尚无定论）：起始 500 mg 每日 1 次随餐，1–2 周后加量，常用维持 1000–2000 mg/日分次；缓释剂型减少胃肠道反应；TAME 采用 1500 mg/日。

**监测清单**：eGFR 至少每年 1 次（eGFR<30 禁用，30–45 减量）；血清 B12 每 1–2 年（长期使用者，必要时查甲基丙二酸 MMA 更敏感），可预防性补充 B12；注意与运动训练并行的交互风险（见争议节）。

**组合逻辑（理论层面，非临床推荐）**：二甲双胍（AMPK 轴）与热量限制/运动（同一轴的内源激活）、与 NAD+ 前体（下游 SIRT1 协同）在机制上互补，但联合效应缺乏人体数据，不应自行堆叠。

## 10. 开放问题与争议

1. **TAME 结果悬而未决**：若阴性或微弱阳性，二甲双胍抗衰叙事将大幅回调；健康人自行服药（"无指征超说明书使用"）的伦理与风险-获益评估也随结果而定。
2. **健康使用者偏倚**：观察性队列中二甲双胍使用者的"超常生存"有多少是药物效应、多少是"能耐受并坚持服药者本来就健康"？孟德尔随机化（OCT1 基因型作为工具变量）提供部分支持，但无法完全解决。
3. **机制主次之争**：复合物 I 抑制 vs PEN2 溶酶体通路，生理浓度下谁是主靶点？AMPK 依赖 vs 非依赖效应各占多少权重？——这直接决定"下一代二甲双胍类似物"的设计方向。
4. **剂量双相性**：动物中低剂量延寿、高剂量缩短寿命（Martin-Montalvo 2013），人体是否存在类似的"最佳剂量窗口"？抗衰剂量是否应低于降糖剂量？
5. **与运动的交互**：Konopka 2019（Aging Cell）随机对照显示，二甲双胍**削弱**老年人运动训练诱导的线粒体适应（尽管仍改善胰岛素敏感性）；但部分研究未见此效应。对"运动+二甲双胍"这一最现实的组合，证据仍矛盾。
6. **动物模型的背景依赖**：ITP 遗传异质小鼠阴性 vs 单一品系阳性，提示抗衰效应可能依赖遗传背景——若如此，人群中的"应答者/无应答者"分层将是关键。
7. **B12 与神经病变的悖论**：二甲双胍流行病学提示降低痴呆风险，但其引起的 B12 缺乏又与周围神经病变相关——净效应取决于剂量、时长与监测管理。

## 参考文献

1. Bailey CJ. Metformin: historical overview. Diabetologia. 2017;60(9):1566-1576.
2. Werner EA, Bell J. The preparation of methylguanidine, and of ββ-dimethylguanidine by the oxidation of adrenaline. J Chem Soc Trans. 1922;121:1790-1794.
3. UK Prospective Diabetes Study (UKPDS) Group. Effect of intensive blood-glucose control with metformin on complications in overweight patients with type 2 diabetes (UKPDS 34). Lancet. 1998;352(9131):854-865.
4. Holman RR, Paul SK, Bethel MA, Matthews DR, Neil HA. 10-year follow-up of intensive glucose control in type 2 diabetes. N Engl J Med. 2008;359(15):1577-1589.
5. Zhou G, Myers R, Li Y, et al. Role of AMP-activated protein kinase in mechanism of metformin action. J Clin Invest. 2001;108(8):1167-1174.
6. El-Mir MY, Nogueira V, Fontaine E, Avéret N, Rigoulet M, Leverve X. Dimethylbiguanide inhibits cell respiration via a specific effect on the electron transport chain. J Biol Chem. 2000;275(1):223-228.
7. Owen MR, Doran E, Halestrap AP. Evidence that metformin exerts its anti-diabetic effects through inhibition of complex 1 of the mitochondrial respiratory chain. Biochem J. 2000;348(Pt 3):607-614.
8. Hardie DG, Ross FA, Hawley SA. AMPK: a nutrient and energy sensor that maintains energy homeostasis. Nat Rev Mol Cell Biol. 2012;13(4):251-262.
9. Xiao B, Sanders MJ, Underwood E, et al. Structure of mammalian AMPK and its regulation by ADP. Nature. 2011;472(7342):230-233.
10. Martin-Montalvo A, Mercken EM, Mitchell SJ, et al. Metformin improves healthspan and lifespan in mice. Nat Commun. 2013;4:2192.
11. Cabreiro F, Au C, Leung KY, et al. Metformin retards aging in C. elegans by altering microbial folate and methionine metabolism. Cell. 2013;153(1):228-239.
12. Onken B, Driscoll M. Metformin induces a dietary restriction-like state and the oxidative stress response to extend C. elegans healthspan via AMPK, LKB1 and SKN-1. PLoS One. 2010;5(1):e8758.
13. De Haes W, Frooninckx L, Van Assche R, et al. Metformin promotes lifespan through mitohormesis via the peroxiredoxin PRDX-2. Proc Natl Acad Sci USA. 2014;111(24):E2501-E2509.
14. Anisimov VN, Berstein LM, Egormin PA, et al. Metformin slows down aging and extends life span of female SHR mice. Cell Cycle. 2008;7(17):2769-2773.
15. Foretz M, Hébrard S, Leclerc J, et al. Metformin inhibits hepatic gluconeogenesis in mice independently of the LKB1/AMPK pathway via a decrease in hepatic energy state. J Clin Invest. 2010;120(7):2355-2369.
16. Madiraju AK, Erion DM, Rahimi Y, et al. Metformin suppresses gluconeogenesis by inhibiting mitochondrial glycerophosphate dehydrogenase. Nature. 2014;510(7506):542-546.
17. Kalender A, Selman A, Comb WC, et al. Metformin, independent of AMPK, inhibits mTORC1 in a rag GTPase-dependent manner. Cell Metab. 2010;11(5):390-401.
18. Ma T, Tian X, Zhang B, et al. Low-dose metformin targets the lysosomal AMPK pathway through PEN2. Nature. 2022;603(7900):159-165.
19. Shin NR, Lee JC, Lee HY, et al. An increase in the Akkermansia spp. population induced by metformin treatment improves glucose homeostasis in diet-induced obese mice. Gut. 2014;63(5):727-735.
20. Barzilai N, Crandall JP, Kritchevsky SB, Espeland MA. Metformin as a tool to target aging. Cell Metab. 2016;23(6):1060-1065.
21. Diabetes Prevention Program Research Group. Reduction in the incidence of type 2 diabetes with lifestyle intervention or metformin. N Engl J Med. 2002;346(6):393-403.
22. Diabetes Prevention Program Research Group. Long-term effects of metformin on diabetes prevention: identification of subgroups that benefited most. Diabetes Care. 2019;42(4):601-608.
23. Bannister CA, Holden SE, Jenkins-Jones S, et al. Can people with type 2 diabetes live longer than those without? Diabetes Obes Metab. 2014;16(11):1165-1173.
24. Evans JM, Donnelly LA, Emslie-Smith AM, Alessi DR, Morris AD. Metformin and reduced risk of cancer in diabetic patients. BMJ. 2005;330(7503):1304-1305.
25. Noto H, Goto A, Tsujimoto T, Noda M. Cancer risk in diabetic patients treated with metformin: a systematic review and meta-analysis. PLoS One. 2012;7(3):e33411.
26. Salpeter SR, Greyber E, Pasternak GA, Salpeter EE. Risk of fatal and nonfatal lactic acidosis with metformin use in type 2 diabetes mellitus. Cochrane Database Syst Rev. 2010;(4):CD002967.
27. de Jager J, Kooy A, Lehert P, et al. Long term treatment with metformin in patients with type 2 diabetes and risk of vitamin B-12 deficiency: randomised placebo controlled trial. BMJ. 2010;340:c2181.
28. Konopka AR, Laurin JL, Schoenberg HM, et al. Metformin inhibits mitochondrial adaptations to exercise in older adults. Aging Cell. 2019;18(1):e12880.
29. Moiseeva O, Deschênes-Simard X, St-Germain E, et al. Metformin inhibits the senescence-associated secretory phenotype by interfering with IKK/NF-κB activation. Aging Cell. 2013;12(3):489-498.
30. Cameron AR, Morrison VL, Levin D, et al. Anti-inflammatory effects of metformin irrespective of diabetes status. Circ Res. 2016;119(5):652-665.
31. Mather KJ, Verma S, Anderson TJ. Improved endothelial function with metformin in type 2 diabetes mellitus. J Am Coll Cardiol. 2001;37(5):1344-1350.
32. Chen ZP, Mitchelhill KI, Michell BJ, et al. AMP-activated protein kinase phosphorylation of endothelial NO synthase. FEBS Lett. 1999;443(3):285-289.
33. Cantó C, Gerhart-Hines Z, Feige JN, et al. AMPK regulates energy expenditure by modulating NAD+ metabolism and SIRT1 activity. Nature. 2009;458(7241):1056-1060.
34. Morales DR, Morris AD. Metformin in cancer treatment and prevention. Annu Rev Med. 2015;66:17-29.

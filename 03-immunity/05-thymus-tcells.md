# 胸腺退化与 T 细胞库 Thymic Involution & T-cell Repertoire

## 核心概念

胸腺（thymus）是初始 T 细胞（naïve T cell）发育与筛选的唯一器官，也是哺乳动物体内**最早开始衰老的器官**——其退化（thymic involution）先于所有其他器官的衰老进程，因而被称为免疫衰老的"第一战场"。胸腺退化指青春期后胸腺上皮细胞（thymic epithelial cell，TEC）进行性丢失、皮质/髓质结构萎缩、实质被脂肪组织浸润替代的不可逆过程：胸腺上皮空间（epithelial space）以每年约 3% 的速度缩减，至 60–70 岁时仅剩青春期水平的约 10–15%，初始 T 细胞输出降至峰值的 ~1%，T 细胞受体（TCR）库多样性随之指数式收窄。这直接决定适应性免疫的"防御新鲜度"——对新病原体、新疫苗抗原、肿瘤新抗原的首次应答能力——是老年感染重症化、疫苗应答差、肿瘤免疫监视削弱的共同上游。与抗衰的关系：胸腺是少数被反复证明**可部分重建**的器官（性激素消融、FGF21、生长激素轴、FoxN1 单基因再生均有人体或动物证据），使其成为免疫年轻化干预的富矿靶点（免疫衰老总论详见 03-immunity/04-immunosenescence.md）。

## 分子机制全链条

### 1. 胸腺解剖与功能分区

胸腺位于前纵隔、胸骨后方，由左右两叶构成，表面有结缔组织被膜（capsule）并伸入形成小叶间隔。每叶分两层：

- **皮质（cortex）**：外层，富含密集的发育中胸腺细胞（thymocyte）与皮质胸腺上皮细胞（cTEC），是 T 系祖细胞增殖、TCR 基因重排与阳性选择（positive selection）的场所；
- **髓质（medulla）**：内层，细胞较稀疏，含髓质胸腺上皮细胞（mTEC）、树突状细胞（DC）、巨噬细胞与胸腺 B 细胞，是阴性选择（negative selection）与初始 T 细胞"出厂"的场所；髓质还含特征性的胸腺小体（Hassall's corpuscle），由退化的 mTEC 构成，其分泌的胸腺基质淋巴细胞生成素（TSLP）参与调节性 T 细胞（Treg）诱导。

### 2. 胸腺细胞发育四阶段：DN → DP → SP

骨髓造血干细胞（HSC）→ 淋巴样祖细胞 → T 系祖细胞（经血流从皮质-髓质交界血管或被膜下进入胸腺），在胸腺内依次经历四个阶段：

```
骨髓HSC → T系祖细胞(ETP) ──进入胸腺──▶
  DN1 (CD44⁺CD25⁻)    ──▶ DN2 (CD44⁺CD25⁺)   TCRβ/γ/δ基因重排开始(RAG1/RAG2)
  DN3 (CD44⁻CD25⁺)    ──▶ β选择(pre-TCR检查,~1/4通过) ──▶ DN4 (CD44⁻CD25⁻)
  ──▶ DP (CD4⁺CD8⁺)   TCRα重排 ──▶ 阳性选择(cTEC呈递自身MHC,>90%凋亡)
  ──▶ SP (CD4⁺或CD8⁺) ──▶ 阴性选择(mTEC经AIRE呈递组织抗原,高亲和克隆删除)
  ──▶ 成熟初始T细胞 输出入血（全程仅约3–5%胸腺细胞存活出厂）
```

- **V(D)J 重组**：TCRβ 链由可变（V）、多样（D）、连接（J）基因片段经 RAG1/RAG2 介导的重组连接，TCRα 链由 V-J 连接；连接处随机插入/删减核苷酸（N/P 添加）产生连接多样性。组合多样性 × 连接多样性使 TCR 理论库容量达 10¹⁵–10²⁰，人体实际外周库约 10⁸–10¹¹ 个独特克隆——这是适应性免疫"预存防御"的分子基础。
- **阳性选择**：DP 胸腺细胞经 cTEC 表面 MHC-I/MHC-II 呈递的自身肽检验，只有能以恰当亲和力识别"自身 MHC"者获生存信号（否则 neglect 凋亡），同时决定 CD4/CD8 谱系承诺（MHC-II 识别 → CD4，MHC-I 识别 → CD8）；
- **阴性选择**：SP 胸腺细胞接受 mTEC 经 **AIRE**（自身免疫调节因子）驱动的组织限制性抗原（tissue-restricted antigen，TRA）呈递，高亲和识别自身抗原的克隆被删除（克隆删除）或分化为 Treg（克隆偏倚）——这是中枢耐受（central tolerance）的核心。AIRE 表达随龄下降，自身反应性克隆逃逸率上升，与老年自身免疫风险升高相关（机制推测为主，人体证据中等）。
- **αβ 与 γδ**：约 95% 胸腺细胞走 αβ 路径；γδ T 细胞（外周 T 细胞 1–5%）在 DN 阶段即分出，不经 MHC 限制性选择，主要定居黏膜与上皮组织，随龄变化较 αβ 库温和。

### 3. 胸腺退化的驱动机制：多因素并行

```
                    性激素↑(青春期)──▶ TEC凋亡/增殖失衡
FoxN1↓ ──▶ TEC命运维持失败 ──▶ cTEC/mTEC减少
GH/IGF-1↓(somatopause) ──▶ TEC增殖信号不足
自噬↓(mTOR↑/FGF21↓) ──▶ TEC内蛋白聚集/线粒体损伤 ──▶ NLRP3炎症
miRNA/表观改变(miR-29↑等) ──▶ TEC与祖细胞基因表达谱漂移
PPARγ↑ ──▶ TEC→脂肪细胞转分化/脂肪浸润 ──▶ 实质被脂肪替代
        ──▶ IL-7与自身肽-MHC信号不足 ──▶ 阳性/阴性选择效率↓ ──▶ 初始T输出↓(TREC↓)
```

**FoxN1 是 TEC 命运的主控转录因子**：FoxN1 缺失即裸鼠（nude）表型——无胸腺、无毛、T 细胞缺失；FoxN1 表达随龄下调且与 TEC 萎缩互为因果。Bredenkamp 等（2014，Development）证明**单一转录因子 FoxN1 的过表达即可再生老年小鼠胸腺**：TEC 数量、皮质/髓质结构与 T 细胞输出全面恢复——这是"胸腺退化可逆"最有力的机制证据。同年该团队（Nat Cell Biol）用 FoxN1 将成纤维细胞直接重编程为功能性 TEC，并组装出有组织、有功能的胸腺（见干预章节）。

**性激素**是青春期后退化的直接驱动：TEC 表达雄激素/雌激素受体，性激素抑制 TEC 增殖并促其凋亡；青春期性激素骤升与胸腺加速萎缩在时间上吻合（但 Steinmann 1985 形态学研究提示人类胸腺上皮退化在青春期前已开始，青春期后加速）；去势/性激素消融（GnRH 激动剂）在啮齿动物与人类男性中均恢复胸腺体积与 TREC 输出（Sutherland 2005）。

**脂肪浸润**由 PPARγ 驱动：胸腺内脂肪细胞部分源于骨髓来源前脂肪细胞定居，部分源于 **TEC 向脂肪细胞的转分化**（transdifferentiation）——衰老 TEC 丢失上皮命运、获得脂肪命运，这一过程受 FoxN1↓ 与 PPARγ↑ 共同调控。MRI/CT 脂肪分数随龄单调上升，60 岁时胸腺实质大部分为脂肪组织替代。

**生长激素/IGF-1 轴（somatopause）**：GH 与 IGF-1 随龄下降，TEC 表达 GH 受体与 IGF-1 受体；GH 缺陷动物胸腺发育不良，GH3 垂体瘤细胞（高分泌 GH/泌乳素）植入可逆转大鼠胸腺衰老（Kelley 1986，PNAS）。GH 的作用部分经 IGF-1 介导，部分经胸腺内局部 GH/IGF-1 旁分泌。

**自噬与代谢**：老年 TEC 自噬通量下降，损伤线粒体与蛋白聚集物堆积，激活 NLRP3 炎症小体与促炎细胞因子分泌，进一步损害 TEC 功能与胸腺微环境。FGF21（成纤维细胞生长因子 21）缺失小鼠胸腺提前退化、炎症加重（Youm 2016，PNAS），外源 FGF21 恢复 TEC 自噬并延缓胸腺衰老（详见干预章节）。

**miRNA 与表观改变**：衰老胸腺 miRNA 表达谱改变（miR-29 家族上调、miR-181a 随龄下调——miR-181a 在 T 细胞中降低 TCR 信号阈值，其下降使活化阈值升高、克隆扩增应答变弱，Li 2012，Nat Med）；TEC 与胸腺祖细胞 DNA 甲基化与组蛋白修饰漂移导致基因表达"身份"模糊，FoxN1 下游靶基因网络整体下调。

### 4. T 细胞输出与 TREC

胸腺近期输出（recent thymic emigrant，RTE）的直接分子标志是 **T 细胞受体切除环（T cell receptor excision circle，TREC）**：TCRδ 基因座在 TCRα 重排时被切除形成游离环状 DNA（sjTREC），不随细胞分裂复制，故其浓度反映胸腺近期输出。Douek 等（1998，Nature）以定量 PCR 显示：sjTREC 随龄下降约 1–2 个数量级（出生至老年），且在 HIV 感染导致的胸腺功能受损中进一步下降、抗病毒治疗恢复后回升——确立 TREC 为胸腺功能与"免疫年龄"的金标准生物标志。成人外周初始 T 库主要由胸腺输出（早期）与外周稳态增殖（IL-7/IL-15 驱动）共同维持；den Braber 等（2012，Immunity）以氘标记动力学证明**人类成年后初始 T 细胞主要靠外周自我更新而非胸腺输入**（与小鼠不同）——这解释了为何成年胸腺输出虽极低，外周初始库仍能维持数十年，但代价是稳态增殖引起的端粒缩短与克隆偏斜累积。

### 4.1 TREC 的临床应用：从科研指标到"胸腺年龄"检测

TREC 检测正从科研走向临床，应用场景逐渐清晰：

- **新生儿筛查（已应用）**：TREC 已纳入多国新生儿筛查（DBS 干血斑 qPCR），用于严重联合免疫缺陷（SCID）的早期发现——这是 TREC 最成熟的临床应用，筛查阳性者及时移植可挽救生命。
- **免疫重建监测（应用增加）**：造血干细胞移植后 TREC 回升反映胸腺输出重建；HIV 抗病毒治疗后 TREC 恢复是免疫重建的指标——临床常规监测中价值明确。
- **"胸腺年龄"评估（新兴）**：TREC 联合 T 细胞亚群、TCR 多样性构建的"胸腺年龄"可作为免疫年龄的组分（与 [04-immunosenescence](04-immunosenescence.md) 的免疫时钟互补）——"胸腺年龄超前"提示免疫衰老加速，可指导疫苗策略与免疫监测。**局限**：TREC 测量标准化（引物、拷贝数归一化）尚未统一；个体间基线差异大，纵向追踪比单次读数更有意义。

**操作建议**：40 岁后可将"淋巴细胞亚群 + TREC + hsCRP"纳入年度体检（自费项目，价格适中），作为免疫年龄的基础评估；TREC 快速下降或显著低于同龄参考时，提示胸腺功能衰退加速，应强化疫苗策略与免疫干预（详见 [04-immunosenescence](04-immunosenescence.md) 的"免疫年龄体检化"）。

### 5. TCR 库多样性收窄与克隆性扩张

高通量 TCRβ 测序（Britanova 2014，J Immunol）显示衰老的核心量化特征：

| 指标 | 年轻（20–35岁） | 老年（60–80岁） | 变化 |
|---|---|---|---|
| 外周独特 TCR 克隆数 | 10⁶–10⁷ 级 | 低一个数量级以上 | 单调下降 |
| Shannon 多样性指数 | 高 | 显著降低 | 与 TREC 正相关 |
| 大克隆（>0.1% 频率）占比 | 低 | 显著升高 | 克隆性扩张 |
| CD4/CD8 差异 | CD4 库较宽 | CD8 库收窄远重于 CD4 | 不对称 |

- **公共克隆 vs 私有克隆**：针对常见抗原（CMV、EBV、流感表位）的公共克隆（public clone，多数个体共有）在衰老中相对保留甚至扩张；个体特异的私有克隆（private clone）丢失更快——多样性收窄本质是"长尾私有克隆消失、头部公共克隆膨胀"。
- **克隆性扩张**：少数大克隆占据越来越多库空间，多为 CMV/EBV 特异性记忆克隆（memory inflation）——CMV 阳性老人中 CMV 特异性 T 细胞可占 CD8⁺ 记忆库的 10–25%，CD28⁻CD57⁺ 终末分化细胞可达 CD8⁺ 的 50–80%（详见 04-immunosenescence.md）。
- **后果**：对新病原肽段与肿瘤新抗原的可用克隆前体减少——疫苗应答下降与免疫治疗响应率受限的直接结构基础。

### 6. 初始 T 细胞稳态维持与细胞因子信号

- **IL-7**：由 TEC 与胸腺基质产生，是初始 T 细胞（尤其 CD4⁺）存活与稳态增殖的首要因子；衰老时 IL-7 产生减少（TEC↓）且 T 细胞 IL-7Rα（CD127）信号敏感性下降，稳态维持失代偿；
- **IL-15**：驱动记忆与部分初始 CD8⁺ 的稳态增殖，随龄信号效率下降但记忆库依赖增强；
- **IL-2**：低剂量经高亲和 IL-2R 支持 Treg 存活，高剂量驱动效应/记忆分化；IL-2 稳态失衡参与老年 Treg/效应失衡；
- **空巢竞争**：记忆克隆膨胀挤占初始 T 的生存龛（niche）与细胞因子份额，进一步压缩初始库——"占位效应"使初始 T 稳态增殖被抑制，形成正反馈式枯竭。

## 证据分级

| 现象 | 证据等级 | 关键证据/文献 |
|---|---|---|
| 胸腺随龄脂肪化、实质缩减至 10–15% | 实锤（人体影像+组织学） | MRI/CT 脂肪分数；Steinmann 1985；George & Ritter 1996（年萎缩 ~3%） |
| 初始 T 输出随龄指数下降（TREC↓1–2 个数量级） | 实锤（人体分子检测） | Douek 1998，Nature（HIV 模型+年龄曲线） |
| TCR 库多样性收窄、克隆性扩张 | 实锤（高通量测序） | Britanova 2014，J Immunol；Shannon 指数随龄↓ |
| 成人初始 T 主要靠外周稳态增殖维持 | 实锤（人体动力学） | den Braber 2012，Immunity（氘标记） |
| FoxN1 单因子过表达再生老年小鼠胸腺 | 动物实锤 | Bredenkamp 2014，Development |
| 性激素消融恢复胸腺输出 | 人体（小样本）+动物实锤 | Sutherland 2005，J Immunol（GnRH 激动剂） |
| FGF21 缺失加速/补充延缓胸腺退化 | 动物实锤 | Youm 2016 PNAS；2025 Nature Aging（旁分泌机制） |
| Ghrelin 促进老年小鼠胸腺生成 | 动物实锤 | Dixit 2007，J Clin Invest |
| 胸腺退化驱动老年癌症发病率陡升 | 数学模型+流行病学拟合 | Palmer 2018，PNAS（发病率-年龄曲线建模） |
| GH+DHEA+二甲双胍胸腺再生 | 小样本人体（无对照） | TRIIM 试验，Fahy 2019，Aging Cell（9 人中 7 人胸腺密度↑） |
| 胸腺移植治疗 DiGeorge | 人体（罕见病适应证） | Markert 2004，Blood |
| NO 诱导胸腺细胞凋亡 | 机制研究（细胞/动物） | Fehsel 1995，J Immunol |

## 临床/实验证据细节

**疫苗应答（最直接的临床表型）**：老年人对流感、新冠、带状疱疹疫苗应答全面减弱——初始 T 库枯竭使新抗原（疫苗表位）可用的克隆前体减少，T 滤泡辅助细胞（Tfh）帮助 B 细胞生发中心反应的能力下降。对策证据：大剂量流感疫苗 Fluzone HD（60 μg/株 vs 标准 15 μg/株）在 ≥65 岁人群将确诊流感相对风险降低 24.2%（DiazGranados 2014，NEJM，RCT n≈31,989）；AS01 佐剂带状疱疹疫苗 Shingrix 在 ≥50 岁人群保护效力达 97.2%（Lal 2015，NEJM）——佐剂通过 TLR4/cGAS-STING 激活固有免疫，部分弥补"初始 T 不足"。

**胸腺退化与癌症（Palmer 2018，PNAS）**：对多种癌症发病率-年龄曲线建模发现，"突变随龄累积"模型无法解释发病率 60 岁后陡升的模式，而"免疫监视随胸腺退化减弱"模型与数据拟合更优——提示胸腺退化导致的 T 细胞多样性下降可能是老年癌症高发的主要驱动之一（机制推测+数学模型，需谨慎解读）。该视角直接支持"TCR 多样性恢复 = 肿瘤预防"的干预逻辑。

**TRIIM 人体试验（Fahy 2019，Aging Cell）**：51–65 岁男性 9 人，联合重组人生长激素（rhGH，每周 3 次小剂量）+ 脱氢表雄酮（DHEA，50 mg/日）+ 二甲双胍（500 mg/日）共 12 个月（rhGH 间歇给药以控制 IGF-1 于安全窗）：7/9 人胸腺 MRI 密度/体积回升（胸腺实质再生影像证据），血浆 TREC 升高，Horvath 表观遗传年龄平均回退约 2.5 岁。样本小、无对照、三种药物各自贡献不明、GH 存在 IGF-1 相关肿瘤风险，但提供了"人体胸腺可逆"的首个综合证据，现已启动 TRIIM-X 扩展队列。

**性激素消融**：Sutherland 2005（J Clin Invest）在健康男性志愿者中证实 GnRH 激动剂（亮丙瑞林）抑制性激素后胸腺体积与 TREC 上升——人体层面"去性激素信号→胸腺再生"因果链的直接证据；代价是性腺功能抑制（骨质疏松、性功能下降风险），限用于前列腺癌等特定人群。

**Ghrelin（Dixit 2007，J Clin Invest）**：老年小鼠给予生长素释放肽 ghrelin 或 GHSR 激动剂，胸腺细胞数量与 TREC 样输出恢复、T 细胞库改善——机制涉及 ghrelin 经 GHSR 促进胸腺祖细胞增殖与 TEC 功能维持，为"生长激素促分泌素"类药物的胸腺再生潜力提供动物基础（人体证据缺失）。

**胸腺移植与类器官**：Markert 2004（Blood）证实培养的同种异体胸腺组织移植可重建 DiGeorge 综合征（无胸腺）患儿的 T 细胞免疫——证明"胸腺可移植、T 细胞可再教育"；类器官工程方向（iPSC 来源 TEC + FoxN1 重编程成纤维细胞形成可移植胸腺原基，Bredenkamp 2014 Nat Cell Biol）正在临床前推进。

**FGF21（Youm 2016 PNAS；2025 Nature Aging）**：FGF21 转基因或药理性升高延缓老年小鼠胸腺退化、恢复 T 细胞输出；2025 年 Nature Aging 进一步阐明**旁分泌机制**——胸腺上皮细胞与脂肪细胞局部产生的 FGF21 经 β-klotho 受体作用于 TEC，维持胸腺淋巴生成；敲除 FGF21 或 TEC 上 β-klotho 加速胸腺衰老。FGF21 类似物（如 efruxifermin）已进入代谢病临床试验，向胸腺再生转化具备成药路径。

**瘦素（Leptin）与营养-免疫联系**：瘦素是脂肪组织-免疫系统的关键纽带。Howard 等（1999，J Clin Invest）证实瘦素缺乏的 ob/ob 小鼠胸腺明显萎缩、胸腺细胞减少，外源瘦素恢复胸腺细胞数量；禁食/营养不足诱导的胸腺退化亦与瘦素下降相关——提示能量状态经瘦素-GH 轴耦合胸腺维持，也解释了慢性疾病恶液质状态下的免疫崩溃（营养-胸腺-免疫轴）。

**胸腺激素与胸腺肽**：胸腺不仅"训练"T 细胞，还分泌多种体液因子：胸腺素 α1（thymosin α1，Tα1，临床制剂 Zadaxin）、胸腺肽（thymulin，锌依赖）、胸腺生成素（thymopoietin）等，参与 T 细胞成熟与功能维持。Tα1 在慢性病毒性肝炎与部分免疫缺陷场景有临床应用数据，其对免疫衰老的价值证据弱-中；thymulin 活性随龄下降且与锌状态相关——老年人补锌部分恢复 thymulin 活性的小样本证据提示"锌-胸腺肽"轴是可操作的营养干预窗口（机制推测+小样本观察，待更大规模验证）。

## 与 NO / NAD+ / 长寿网络联系

- **NO 对胸腺细胞的双向剂量效应**：低浓度 NO（eNOS/nNOS 来源）经 sGC/cGMP/PKG 通路促进胸腺细胞增殖与分化信号；高浓度 NO（iNOS 来源，炎症微环境）诱导胸腺细胞凋亡——Fehsel 等（1995，J Immunol）直接证明 NO 供体（SNAP 等）以剂量依赖方式诱导小鼠胸腺细胞凋亡，且不依赖糖皮质激素受体。胸腺内 iNOS 在巨噬细胞/树突状细胞中表达，随龄炎症上升时 iNOS↑ → 局部 NO 过高 → 胸腺细胞凋亡增加、阳性/阴性选择紊乱，"NO 双刃剑"在胸腺内呈现为发育窗口的毒性侧。
- **eNOS 与胸腺灌注**：eNOS/NO 维持胸腺微血管内皮功能与灌注；衰老时 eNOS 下调 → 胸腺缺血性退化加速，形成"NO↓-胸腺退化"恶性循环；NO 亦调节 HSC 静息与归巢（eNOS 敲除小鼠 HSC 自我更新受损），上游牵连 T 系祖细胞的胸腺输入（详见 01-foundations/03-no-basics.md）。
- **NO 抑制 NF-κB**：NO S-亚硝基化 p65（Cys38）降低其 DNA 结合，NO 供给不足使 NF-κB 去抑制 → TEC 与胸腺细胞促炎程序放大，加速退化。
- **NAD+/SIRT1**：NAD+ 随龄下降 → SIRT1 活性↓；机制研究表明 SIRT1 参与 T 系发育（Notch 信号调控）与 Treg 稳定（Foxp3 去乙酰化调节），SIRT1 缺失小鼠胸腺与 T 细胞发育异常——NAD+ 前体（NMN/NR）改善老年免疫的部分机制即经 SIRT1 抗炎与 T 细胞功能维护。NO 与 NAD+ 在 SIRT1 轴深度耦合：eNOS 活性依赖 NAD+（SIRT1 去乙酰化 eNOS 维持其活性），构成"NAD+↓→SIRT1↓→eNOS↓→胸腺灌注↓"的叠加回路。
- **代谢-免疫交叉**：FGF21/ghrelin/GH 轴共同指向"能量代谢感知 → 胸腺维持"——长寿网络（mTOR/AMPK/自噬）与胸腺退化在 TEC 内直接交汇，使胸腺成为代谢干预（二甲双胍、雷帕霉素、禁食）的免疫获益窗口。

## 干预方向与可执行建议

**已有证据（按强度排序）**：
1. **疫苗策略**：≥65 岁接种大剂量（Fluzone HD）或佐剂（MF59）流感疫苗、AS01 佐剂带状疱疹疫苗（Shingrix）——RCT 证实可部分弥补初始 T 库不足，是当下可立即执行的最成熟手段；
2. **运动与代谢**：规律有氧运动（中等强度每周 ≥150 分钟）与高心肺适能者初始 T 比例更高、衰老 T 细胞更少；维持充足蛋白质、锌与维生素 D 支持胸腺肽（thymulin，锌依赖）功能——成本最低的免疫维持策略；
3. **低剂量 mTOR 抑制**：雷帕霉素/依维莫司低剂量改善老年疫苗应答并降低呼吸道感染（RCT 支持，Mannick 2014/2018），动物层面恢复老年小鼠胸腺结构——需监测血脂血糖与感染风险，尚未获批用于免疫重建；
4. **已有人体证据的胸腺再生组合**：GH+DHEA+二甲双胍（TRIIM 方案）与性激素消融——均证明人体胸腺可逆，但风险窗（GH 的 IGF-1 肿瘤风险、性激素消融的骨代谢代价）要求仅在严格临床监督下探索。

**在研前沿**：FGF21 类似物（已具备代谢病成药基础）、ghrelin/GHSR 激动剂、IL-7 补充（rhIL-7/CYT107 免疫重建试验）、FoxN1 基因治疗与 FoxN1 重编程类器官（动物实锤）、胸腺移植（DiGeorge 已临床）、部分重编程（动物实锤、人类远未成熟）、PPARγ 拮抗与 TEC 转分化阻断（临床前）。

## 开放问题与争议

- **程序性 vs 累积损伤**：胸腺退化是"程序性衰老"（性激素、FoxN1 内在计时）还是"累积损伤"（氧化、炎症、代谢废物）主导？Steinmann 的青春期前退化数据与 FoxN1 单基因再生证据各支持一方，两者权重无共识；
- **脂肪细胞来源**：胸腺内脂肪是 TEC 转分化还是骨髓前脂肪细胞定居？若以前者为主，阻断转分化（抗 PPARγ）即可能保留 TEC 池，干预策略完全不同；
- **胸腺外补偿**：成人是否存在可激活的胸腺外 T 生成（肝、肠相关淋巴组织）以部分代偿？证据薄弱；
- **多样性阈值**：TCR 多样性恢复多少才足以改善疫苗应答与肿瘤免疫治疗结局？无定量共识（Palmer 模型给出理论框架但缺人体验证）；
- **干预风险窗口**：GH 促生长有肿瘤风险、性激素消融有骨代谢代价、FoxN1 强制表达有致癌风险——人类胸腺再生的剂量-风险窗口远未明确；TRIIM 样本仅 9 人且无对照，结论需复制。

## 参考文献

1. George AJT, Ritter MA. Thymic involution with ageing: obsolescence or good housekeeping? Immunol Today. 1996;17(6):267-272.
2. Steinmann GG, Klaus B, Müller-Hermelink HK. The involution of the ageing human thymic epithelium is independent of puberty. A morphometric study. Scand J Immunol. 1985;22(5):563-575.
3. Douek DC, McFarland RD, Keiser PH, et al. Changes in thymic function with age and during the treatment of HIV infection. Nature. 1998;396(6712):690-695.
4. Palmer S, Albergante L, Blackburn CC, Newman TJ. Thymic involution and rising disease incidence with age. Proc Natl Acad Sci USA. 2018;115(8):1883-1888.
5. den Braber I, Mugwagwa T, Vrisekoop N, et al. Maintenance of peripheral naive T cells is sustained by thymus output in mice but not humans. Immunity. 2012;36(2):288-297.
6. Britanova OV, Putintseva EV, Shugay M, et al. Age-related decrease in TCR repertoire diversity measured with deep and normalized sequence profiling. J Immunol. 2014;192(6):2689-2698.
7. Bredenkamp N, Nowell CS, Blackburn CC. Regeneration of the aged thymus by a single transcription factor. Development. 2014;141(8):1627-1637.
8. Bredenkamp N, Ulyanchenko S, O'Neill KE, et al. An organized and functional thymus generated from FOXN1-reprogrammed fibroblasts. Nat Cell Biol. 2014;16(9):902-908.
9. Sutherland JS, Goldberg GL, Hammett MV, et al. Activation of thymic regeneration in mice and humans following androgen blockade. J Immunol. 2005;175(4):2741-2753.
10. Fahy GM, Brooke RT, Watson JP, et al. Reversal of epigenetic aging and immunosenescent trends in humans. Aging Cell. 2019;18(6):e13028.
11. Youm YH, Horvath TL, Mangelsdorf DJ, Kliewer SA, Dixit VD. Prolongevity hormone FGF21 protects against immune senescence by delaying age-related thymic involution. Proc Natl Acad Sci USA. 2016;113(4):1026-1031.
12. Youm YH, Gliniak C, Zhang Y, et al. Enhanced paracrine action of FGF21 in stromal cells delays thymic aging. Nat Aging. 2025;5(4):576-587.
13. Dixit VD, Yang H, Sun Y, et al. Ghrelin promotes thymopoiesis during aging. J Clin Invest. 2007;117(10):2778-2787.
14. Li G, Yu M, Lee WW, et al. Decline in miR-181a expression with age impairs T cell receptor sensitivity by increasing DUSP6 activity. Nat Med. 2012;18(10):1518-1524.
15. Fehsel K, Kröncke KD, Meyer KL, et al. Nitric oxide induces apoptosis in mouse thymocytes. J Immunol. 1995;155(6):2858-2865.
16. Anderson MS, Venanzi ES, Klein L, et al. Projection of an immunological self shadow within the thymus by the aire protein. Science. 2002;298(5597):1395-1401.
17. Kelley KW, Brief S, Westly HJ, et al. GH3 pituitary adenoma cells can reverse thymic aging in rats. Proc Natl Acad Sci USA. 1986;83(15):5663-5667.
18. Howard JK, Lord GM, Matarese G, et al. Leptin protects mice from starvation-induced lymphoid atrophy and increases thymic cellularity in ob/ob mice. J Clin Invest. 1999;104(8):1051-1059.
19. Markert ML, Sarzotti M, Ozaki DA, et al. Thymus transplantation in complete DiGeorge syndrome: immunologic and safety evaluations in 12 patients. Blood. 2003;102(3):1121-1130.
20. DiazGranados CA, Dunning AJ, Kimmel M, et al. Efficacy of high-dose versus standard-dose influenza vaccine in older adults. N Engl J Med. 2014;371(7):635-645.

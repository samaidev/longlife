# 慢性炎症与衰老（Inflammaging / Chronic Inflammation）

> Inflammaging（炎症性衰老）——伴随增龄的低度、慢性、无菌性、全身性炎症状态，是 12 大衰老标志之一（López-Otín 2023 扩展版），也是心血管病、2 型糖尿病、神经退行、肿瘤等年龄相关疾病共用的"土壤"。它不来自单一病原体，而来自免疫系统对自身损伤信号（DAMP、SASP、代谢应激）的持续、低效响应；理解它的分子全链条，是理解"为什么抗炎不能简单等同于抗衰"的钥匙。

---

## 核心概念

Inflammaging 一词由意大利免疫学家 Claudio Franceschi 于 2000 年正式提出（*Ann N Y Acad Sci*），其定义为：**随增龄出现的低度（low-grade）、慢性（chronic）、无菌性（sterile）、全身性（systemic）炎症状态**——无明确的病原体感染，无急性炎症的红、肿、热、痛体征，但血清促炎细胞因子（IL-6、TNF-α、IL-1β）与急性期蛋白（CRP、纤维蛋白原）的基线水平持续轻度升高，并系统性驱动组织损伤与年龄相关疾病。Franceschi 同时给出演化论解释——"抗原负荷理论"（antigenic load theory）：机体一生中累积的抗原刺激（病原体、自身抗原、损伤分子、食物成分）持续消耗免疫储备，免疫系统在"防御"与"自身损伤"之间陷入两难，最终以低度炎症作为代价维持稳态。2013 年 López-Otín 等提出 9 大衰老标志时未单列炎症，2023 年扩展版正式将**慢性炎症**列为第 12 项标志，并新增巨噬细胞极化失衡（第 10 项）——炎症不再被视为衰老的"伴随现象"，而是连接损伤、代偿与功能衰退全程的放大器与执行器（详见 01-foundations/01-aging-hallmarks.md）。

## 一、与急性炎症的本质区别

| 维度 | 急性炎症 | Inflammaging |
|---|---|---|
| 触发因素 | 病原体感染、组织创伤 | 无菌性 DAMP、SASP、代谢应激、内毒素 |
| 强度与时程 | 强烈、数天至数周，可完全消退 | 低度、持续数月乃至终身 |
| 典型体征 | 红、肿、热、痛、发热 | 无局部体征，仅实验室指标轻度升高 |
| 主导细胞 | 中性粒细胞、单核细胞浸润 | 巨噬细胞（M1 偏向）、衰老细胞、微胶质细胞 |
| 结局 | 病原清除、组织修复、稳态恢复 | 组织微损伤累积、纤维化、功能衰退 |
| 生物学意义 | 宿主防御（有益） | 免疫系统"代偿性但最终有害"的激活 |

关键认识有三：其一，inflammaging 的强度虽低，但**持续暴露于全系统**——IL-6 仅升高 2–4 倍即可预测死亡率翻倍，说明"慢性"比"强度"更具破坏性；其二，inflammaging 与免疫衰老（immunosenescence，详见 03-immunity/04-immunosenescence.md）互为表里——免疫衰老削弱病原清除与损伤修复能力，使抗原与 DAMPs 滞留，反过来持续点燃炎症；其三，近年"训练免疫"（trained immunity，Netea 2016）概念补充了其细胞基础：单核/巨噬细胞在首次刺激后经表观重编程（H3K4me3、H3K27ac 沉积于 TNF、IL-6 等促炎基因启动子）获得"先天免疫记忆"，使老年个体对后续刺激的反应更猛烈、更持久——inflammaging 因而具有"自我放大"的动力学特征。

## 二、分子机制全链条

### 2.1 炎症枢纽：NF-κB 信号通路

几乎所有炎症来源的信号最终汇聚于转录因子 NF-κB（p65/RelA–p50 异二聚体），它是炎症时钟的枢纽节点。完整链条：

```
上游刺激（TNF-α/TNFR、IL-1β/IL-1R、LPS/TLR4、DAMP/RAGE）
        │
        ▼
  接头蛋白 TRAF2/6、MyD88、TRIF
        │
        ▼
   IKK 复合物（IKKα/IKKβ/IKKγ=NEMO）──IKKβ 磷酸化 IκBα（Ser32/36）
        │
        ▼
   SCF-βTrCP E3 连接酶 → IκBα 泛素化（Lys48）→ 26S 蛋白酶体降解
        │
        ▼
   NF-κB（p65/p50）暴露核定位序列 → 入核 → 结合 κB 基序
        │
        ▼
   转录数百个炎症基因：IL-6、TNF-α、IL-1β、COX-2、iNOS、
   ICAM-1/VCAM-1、MCP-1、PAI-1、MMP-9……
```

衰老中此通路出现三重异常：(a) **上游刺激增多**——SASP 因子、氧化型 mtDNA、LPS、AGEs 持续供给；(b) **负反馈受损**——NF-κB 本身诱导 IκBα 再合成构成自限环，但衰老组织中该负反馈减弱（与 IKK 持续活化、IκBα 再合成滞后有关）；(c) **去乙酰化刹车失灵**——SIRT1/SIRT6 活性随 NAD+ 下降而降低，p65 的 K310 乙酰化升高，NF-κB 转录活性增强（见第五节）。老年大鼠心脏、肝脏、脑组织中核内 NF-κB DNA 结合活性升高数倍（Helenius 1996 等），且活性升高先于组织病理表型，提示其驱动而非跟随。NF-κB 也是 SASP 的主控转录因子（与 C/EBPβ 协同），由此把"细胞衰老"与"系统炎症"锁死在同一回路。

### 2.2 NLRP3 炎性小体：从传感器到焦亡

NLRP3 炎性小体是炎症的"分子放大器"，将多种损伤信号转化为 IL-1β/IL-18 释放与焦亡（pyroptosis）。其激活遵循**双信号模型**：

```
信号1（启动 priming）：TLR/NF-κB → 转录上调 NLRP3、pro-IL-1β、pro-IL-18
信号2（激活 activation，任一即可）：
  ├─ K⁺ 外流（通用触发器；ATP/P2X7、成孔毒素、颗粒物均经此）
  ├─ 线粒体 ROS 升高 / 氧化型 mtDNA 释放
  ├─ 溶酶体损伤 → 组织蛋白酶 B（cathepsin B）泄漏
  └─ 尿酸/胆固醇结晶、淀粉样蛋白 Aβ、明矾等颗粒物
        │
        ▼
NLRP3 招募 NEK7（K⁺ 外流下游必需）→ 寡聚 → 招募 ASC
        │
        ▼
ASC 螺旋纤维聚合 → 形成"ASC 斑点"（ASC speck，细胞质内单一大聚集体）
        │
        ▼
pro-caspase-1 招募并寡聚自剪切 → 活性 caspase-1
        │
        ├──► 剪切 pro-IL-1β → 成熟 IL-1β（主放大器）
        ├──► 剪切 pro-IL-18 → 成熟 IL-18（促 IFN-γ）
        └──► 剪切 gasdermin D（GSDMD）→ N 端结构域在质膜打孔
                 → IL-1β/IL-18 经孔释放 + 细胞焦亡（裂解性死亡）
```

要点：**K⁺ 外流是 NLRP3 激活的通用触发**（Muñoz-Planillo 2013，细菌毒素、颗粒物、ATP 均以胞内 K⁺ 下降为共同终点）；**NEK7 是 K⁺ 外流与 NLRP3 之间的必需衔接蛋白**（He 2016，Nature）；**ASC 斑点**是炎性小体激活的形态学标志，可在单个细胞内聚合成一个微米级斑点；**gasdermin D 打孔**使 IL-1β 以非经典途径释放并引发焦亡，焦亡释放的胞内容物又作为 DAMPs 进一步激活炎症——正反馈。IL-1β 是炎症网络的"主放大器"：激活内皮、招募中性粒细胞、诱导肝脏急性期蛋白（CRP 即其下游产物）。NLRP3 活性随龄在多种组织升高，与痛风、动脉粥样硬化、阿尔茨海默病、2 型糖尿病的病理直接相关；CANTOS 试验用抗 IL-1β 单抗 canakinumab 证明靶向该轴可降低人类心血管与肿瘤终点（见第四节）——NLRP3/IL-1β 轴是当前抗炎抗衰药物开发最热的靶点。

### 2.3 来源一：SASP 与细胞衰老的正反馈

衰老细胞（第 7 大衰老标志）以 SASP（衰老相关分泌表型）持续分泌 IL-6、IL-8、TNF-α、IL-1α/β、PAI-1、MMPs 及趋化因子。SASP 经旁分泌诱导邻近细胞衰老（旁观者效应），衰老细胞增多又扩大 SASP 供给——构成"炎症—衰老"自我放大的正反馈循环。SASP 的转录由 NF-κB 与 C/EBPβ 主导，且部分依赖 cGAS-STING（衰老细胞胞质中积累的染色质片段激活 cGAS）。短期 SASP 具有生理功能（伤口愈合、肿瘤抑制），慢性累积则转变为系统性炎症引擎。清除衰老细胞（senolytics）可同时降低炎症负荷并延缓衰老表型（详见 04-drugs/03-senolytics.md）；抑制 SASP 分泌而不杀细胞者称 senomorphics（详见 04-drugs/04-senomorphics.md）。

### 2.4 来源二：受损线粒体 mtDNA 泄漏激活 cGAS-STING

随龄线粒体自噬（mitophagy，PINK1/Parkin 通路）下降 → 受损线粒体堆积 → 氧化型 mtDNA 经 BAX/BAK 孔、线粒体通透性转换孔（mPTP）或外膜破裂泄漏至胞质 → 被胞质 DNA 传感器 **cGAS** 识别 → 催化生成 2'3'-cGAMP → 激活内质网上的 **STING** → 招募 TBK1 → 磷酸化并激活 IRF3 与 NF-κB → 转录 I 型干扰素（IFN-α/β）与促炎因子。同时，氧化型 mtDNA 可直接作为信号 2 激活 NLRP3（Shimada 2012）。动物实验表明 STING 通路激活随龄增强，而 cGAS/STING 缺陷可减轻老年组织炎症并部分延缓衰老表型（多项机制研究）；TFAM 减少（mtDNA 包装松弛）即可触发该通路——"线粒体应激→先天免疫激活"是炎症的深层来源。

### 2.5 来源三：肠道菌群失调与代谢性内毒素血症

随龄肠道菌群多样性下降：产短链脂肪酸（SCFA，尤其丁酸）的有益菌减少、潜在致病菌（变形菌门等）增多；同时肠上皮紧密连接破坏、通透性升高（"肠漏"）→ 革兰阴性菌外膜成分 **LPS（脂多糖）** 低剂量持续入血 → 经 TLR4-MyD88 激活单核/巨噬细胞 → IL-6、TNF-α 轻度持续升高——Cani 等（2007）在肥胖/高脂饮食模型中命名为"代谢性内毒素血症"，该机制在衰老肠道同样成立。丁酸等 SCFA 本经 GPR43 信号与组蛋白去乙酰化酶（HDAC）抑制发挥抗炎作用，菌群失调同时解除这一"刹车"。此外，巨细胞病毒（CMV）等潜伏感染终身携带、反复再激活，构成慢性抗原负荷，与免疫衰老共同抬升炎症基线。

### 2.6 来源四：脂肪组织炎症与巨噬细胞极化失衡

老年（尤其腹型肥胖）个体的脂肪组织是系统性炎症的重要来源：脂肪细胞肥大、缺氧 → 释放趋化因子 MCP-1 → 招募单核细胞 → 巨噬细胞浸润并极化为 **M1 促炎型**（NF-κB/STAT1 驱动，分泌 TNF-α、IL-1β、IL-6、iNOS），在坏死脂肪细胞周围形成"冠冕样结构"（crown-like structures）→ TNF-α 磷酸化 IRS-1 丝氨酸位点（Ser307）抑制胰岛素信号 → 胰岛素抵抗（Hotamisligil 1993 首次证明脂肪组织 TNF-α 与肥胖-糖尿病关联）。抗炎修复型 **M2**（STAT6/PPARγ 驱动，分泌 IL-10、TGF-β、精氨酸酶）随龄减少，且老年巨噬细胞清除凋亡细胞的能力（efferocytosis，MerTK/MFG-E8）下降，凋亡细胞滞留继发坏死 → 炎症持续——M1/M2 极化失衡是 2023 版新增的第 10 大衰老标志（详见 03-immunity/03-macrophage-polar.md）。内脏脂肪炎症负荷显著高于皮下脂肪。

### 2.7 炎症网络总图

```
  来源层          放大器层              效应层
┌──────────┐   ┌────────────────┐   ┌────────────────┐
│SASP/衰老细胞│──▶│                │──▶│ 动脉粥样硬化    │
│mtDNA/cGAS │──▶│  NF-κB 枢纽     │──▶│ 胰岛素抵抗/脂肪肝│
│肠道 LPS   │──▶│  (转录放大)     │──▶│ 神经退行(小胶质) │
│脂肪 M1 巨噬│──▶│  NLRP3 炎性小体  │──▶│ 肌少症/骨丢失    │
│潜伏病毒   │──▶│  (IL-1β/焦亡)   │──▶│ 肿瘤微环境      │
└──────────┘   └────────────────┘   └────────────────┘
      ↕ 正反馈：炎症诱导衰老、衰老分泌炎症、焦亡释放 DAMP
```

## 三、证据分级

| 现象 | 证据等级 | 关键文献 |
|---|---|---|
| 血清 IL-6、TNF-α、CRP 随龄升高（健康老人 IL-6 基线为年轻人的 2–4 倍） | 实锤（多个人群队列一致） | Cohen 1997; Ferrucci 1999/2005 |
| 炎症标志物预测残疾、虚弱、心血管事件与全因死亡 | 实锤（前瞻队列，独立于传统危险因素） | InCHIANTI; Whitehall II |
| 组织中 NF-κB 活性随龄升高 | 强关联（动物多组织+人体样本） | Helenius 1996 等 |
| 清除 p16⁺ 衰老细胞降低炎症并延长寿命 | 动物因果（转基因清除模型） | Baker 2016 Nature |
| 抗 IL-1β（canakinumab）降低心血管事件与肿瘤死亡率 | 人体 RCT（因果） | Ridker 2017 NEJM |
| 阿司匹林在健康老人中无残疾生存获益 | 人体 RCT（阴性结果） | ASPREE 2018/2019 |
| 低剂量秋水仙碱降低冠心病事件 | 人体 RCT | LoDoCo2 2020 |
| mtDNA-cGAS-STING 驱动衰老炎症 | 动物因果+体外机制 | Shimada 2012; Dou 2017 |
| 二甲双胍降 CRP、抑制 NF-κB | RCT/观察（代谢人群）+机制 | 多项 |
| NLRP3 抑制剂（dapansutrile） | 机制确证+早期临床 | Marchetti 2018 PNAS |
| 肠道菌群→LPS→炎症（衰老） | 动物因果+人体关联 | Cani 2007 等 |

证据等级说明：实锤=多队列/多物种一致且机制清晰；强关联=动物因果或人体一致关联；机制推测=体外或机制研究支持、人体证据待补。总体而言，**"炎症标志物随龄升高并预测不良结局"是人体观察的最高等级证据，而"抗炎干预改善衰老终点"仅在特定靶点（IL-1β、秋水仙碱）获得 RCT 支持，广谱抗炎（阿司匹林）在健康老人中为阴性**——证据图谱本身指向"炎症的异质性"。

## 四、临床/实验证据细节

**（1）炎症负荷与衰老结局（观察性）**：健康年轻人 IL-6 基线约 1–2 pg/mL，健康老人升高 2–4 倍；hsCRP 中位数从 <1 mg/L 升至 2–3 mg/L。Cohen 等（1997，社区老人队列）发现血浆 IL-6 升高与功能障碍显著相关；InCHIANTI 队列（Ferrucci 等，托斯卡纳老年人）显示 IL-6、CRP 升高独立预测行动受限与死亡——IL-6 每升高一个标准差，行动受限风险约增 60–70%。Whitehall II 等队列确认 CRP/IL-6 与全因死亡、心血管死亡独立相关。炎症与表观时钟的关联同样明确：PhenoAge 表观时钟（Levine 2018）直接把 CRP、白蛋白、葡萄糖等炎症/营养标志物编入 DNA 甲基化年龄模型——炎症被"写进"了生物学年龄，IL-6/CRP 高者表观年龄加速。

**（2）CANTOS：首次人体因果证据**（Ridker 2017，NEJM）：10,061 例心梗后 hsCRP≥2 mg/L 患者，canakinumab（抗 IL-1β 单抗）150 mg 每 3 个月一次，中位随访 3.7 年——主要不良心血管事件（MACE）HR 0.85（95%CI 0.74–0.98），且不依赖血脂下降；hsCRP 降至 <2 mg/L 者获益最大；继发分析显示肺癌发病率与死亡率分别下降（HR 0.61/0.33）。这是人类历史上第一次证明"单纯抗炎（不经降脂）"可降低心血管与肿瘤终点，直接支持炎症在年龄相关疾病中的因果地位。

**（3）ASPREE：广谱抗炎的反面教材**（McNeil 2018 NEJM / 2019 JAMA）：19,114 名 ≥70 岁健康老人，阿司匹林 100 mg/d，中位 4.7 年——无残疾生存无获益，大出血风险显著升高（HR≈1.38），全因死亡反而升高（HR 1.14，主要由癌症相关死亡驱动）。ASPREE 传递的核心信息：**健康老人的低度炎症不是"越早压越低越好"**——广谱、非靶向、长期抑制炎症的净获益为负；抗炎必须瞄准特定轴（IL-1β、NLRP3）与特定人群（炎症负荷高者）。

**（4）秋水仙碱与二甲双胍**：LoDoCo2（2020，NEJM）5,522 例慢性冠心病患者，秋水仙碱 0.5 mg/d——心血管事件 HR 0.69，提示低剂量 NLRP3 上游抑制（微管/ASC 组装相关）在二级预防中有效。二甲双胍经 AMPK 激活抑制 NF-κB 与 NLRP3，在 2 型糖尿病人群 RCT 中显著降低 CRP；以"二甲双胍抗衰老"为目标的 TAME 试验（Barzilai 主导）进行中（详见 04-drugs/07-metformin-ampk.md）。

**（5）Senolytics 人体试验**：达沙替尼+槲皮素（D+Q）在糖尿病肾病（Hickson 2019，EBioMedicine）与特发性肺纤维化（Justice 2019）患者中，单疗程即降低循环 SASP 因子（IL-6、MMP 等）并减少脂肪组织衰老细胞——从源头削减 SASP 供给的可行性首次在人体得到验证。

**（6）生活方式干预的效应量**：规律有氧+抗阻运动使静息 CRP/IL-6 中等幅度下降（多项 meta 分析，CRP 约降 15–30%），机制包括肌肉源性 IL-6 经 IL-10 的抗炎效应（运动后 IL-10 升高）与 eNOS 剪切应力激活；每日 1–3 g EPA+DHA（omega-3）使 CRP 中度下降；地中海饮食在 PREDIMED 试验中降低心血管事件并伴炎症标志物改善。

**（7）百岁老人：炎症的"自然对照"**：健康百岁老人常表现出低于普通老年人群的炎症水平，构成观察性证据的"反向验证"——意大利百岁老人研究（Franceschi 团队）显示，百岁及超百岁个体 IL-6、CRP 升高幅度小于同龄不健康老人，且其基因型中抗炎/促炎细胞因子多态呈"炎症控制型"组合（如 IL-6 -174GC、IL-10 高表达型），提示遗传决定的炎症调节能力与极端长寿相关。机制研究表明，IL-6 信号存在经膜结合受体（classic signaling，抗炎/再生）与经可溶性受体 sIL-6R 的 trans-signaling（促炎）两条路径，前者随龄相对减弱而后者增强——衰老中升高的血清 IL-6 更多经 trans-signaling 发挥作用，这也解释了为何"总 IL-6 水平"只是炎症状态的粗略代理指标；可溶性 gp130（sgp130）可中和 trans-signaling，是正在探索的干预思路。

## 五、与 NO / NAD+ / 长寿网络的联系

**NO 是内源性抗炎分子的代表，其抗炎作用有完整的分子链**：

```
低浓度 NO（eNOS/nNOS 来源）
  ├─► S-亚硝基化 IKKβ（Cys179）→ 抑制 IKK 激酶活性 → NF-κB 激活受阻（Reynaert 2004 PNAS）
  ├─► S-亚硝基化 p65（Cys38）→ 降低其 DNA 结合能力
  ├─► 激活 SIRT1 → 去乙酰化 p65（K310）→ 抑制 NF-κB 转录活性（Yeung 2004 EMBO J）
  └─► 下调 ICAM-1/VCAM-1 → 抑制白细胞-内皮粘附与浸润（De Caterina 1995）
        └─► 净效应：SASP 分泌↓、巨噬细胞 M2 维持、血管抗炎
```

**NO 不足与炎症互为因果的恶性循环**：慢性炎症 → 氧化应激 → BH4 被氧化（BH4→BH2）→ eNOS 解偶联 → NO 生成下降且转而产超氧阴离子 → 抗炎刹车失灵 → 炎症进一步放大；与此同时，NF-κB 转录诱导 **iNOS**（其启动子含多个炎症响应元件）→ 巨噬细胞持续高浓度产 NO（μM 级）→ NO 与超氧以近 1:1 反应生成过氧亚硝酸盐（ONOO⁻，扩散控制速率 ~10⁹–10¹⁰ M⁻¹s⁻¹）→ 硝化酪氨酸（3-NT）沉积、线粒体复合物抑制、NF-κB 再度激活——**NO 从抗炎转向促炎，浓度与时相决定其角色**（详见 01-foundations/03-no-basics.md）。eNOS 敲除小鼠呈现更高的炎症负荷与更快的内皮衰老，人体内皮功能障碍（FMD 下降）与 CRP/IL-6 升高平行出现，均支持"NO 生物利用度下降是炎症放大的上游条件"。

**NAD+ 轴把炎症与长寿网络焊在一起**：NAD+ 随龄下降 → SIRT1 活性↓ → p65 K310 乙酰化↑ → NF-κB 转录活性↑ → 炎症↑；SIRT6 同样在 NF-κB 靶基因启动子上去乙酰化 H3K9 以抑制其转录。反过来，NLRP3 激活与 DNA 损伤应答消耗 NAD+（PARP1 每修复一个断裂消耗一个 NAD+）——炎症本身加速 NAD+ 耗竭。动物实验中 NMN/NR 补充降低老年组织炎症标志物并改善代谢。由此形成**"炎症 ↔ 细胞衰老 ↔ NAD+/SIRT ↔ NO"四联互锁环**：提升 NO（运动、膳食硝酸盐）与补充 NAD+ 前体（NMN/NR）可视为"抗炎"的上游策略，而清除衰老细胞则是"断源"策略——两条路线共享同一网络（详见 01-foundations/03-no-basics.md 与 04-drugs/05-molecular-mech.md）。

## 六、干预方向与可执行建议

**第一层：生活方式（证据最强、零副作用，首选）**
- 规律有氧+抗阻运动（每周 ≥150 分钟中等强度）：降 CRP/IL-6、促 M2 极化、剪切应力激活 eNOS、提升 NO 与 NAD+；
- 地中海式抗炎饮食：多蔬果、橄榄油、深海鱼（omega-3 每日 1–3 g）、全谷物；限制精制糖与高 AGEs 加工食品（AGEs 经 RAGE 激活 NF-κB）；
- 热量限制/间歇性禁食：AMPK↑、mTOR↓、自噬↑ → 清除损伤线粒体与衰老细胞，抑制 NLRP3；
- 睡眠、压力与口腔管理：HPA 轴过度激活与牙周炎（慢性细菌抗原负荷）均为可干预的炎症来源。

**第二层：药物级（需医生评估，目标人群=炎症负荷高者）**
- 低剂量秋水仙碱 0.5 mg/d：冠心病二级预防（LoDoCo2 证据）；
- 二甲双胍：代谢性抗炎（AMPK/NF-κB 轴），TAME 试验进行中；
- 他汀：除降脂外直接降低 hsCRP（JUPITER 试验即按 hsCRP 入选）。

**第三层：前沿靶向（临床试验阶段）**
- NLRP3 抑制剂：dapansutrile（OLT1177）——痛风、急性心梗、骨关节炎已进入 2 期；异甘草素（isoliquiritigenin）等天然 NLRP3 抑制剂在巨噬细胞模型与小鼠炎症模型中显示抑制 ASC 组装与 IL-1β 成熟（机制研究表明，人体证据待补）；
- 抗 IL-1β（canakinumab）：CANTOS 已证概念，但感染风险升高与成本限制了推广；
- Senolytics（D+Q、fisetin）与 senomorphics（雷帕霉素、二甲双胍）：从源头削减 SASP（详见 04-drugs/03-senolytics.md、04-drugs/04-senomorphics.md）；
- 肠道菌群干预：益生元、丁酸补充、健康供体粪菌移植（动物有效，人体待验证）。

**明确不推荐**：健康老人常规服用阿司匹林或长期 NSAIDs——ASPREE 阴性且出血/GI/肾毒性明确，无任何延寿证据。

**中医视角的补充**：本库贯穿的"益气活血"策略与抗炎存在分子层面的交叉——黄芪多糖、丹参酮等中药成分被机制研究表明可下调 NF-κB 与 NLRP3 活性、抑制 IL-6/TNF-α 分泌，并上调 eNOS/NO 生物利用度；"气虚血瘀"的临床证候（乏力、舌暗、脉涩）与慢性低度炎症状态（高 CRP/IL-6、微循环障碍）高度重叠，提示益气活血方药可能部分经由"恢复 NO→抑制 NF-κB"轴实现抗炎效应（详见 06-tcm/01-yiqi-huoxue.md、06-tcm/02-herbs.md）。此类证据多为机制研究与中小样本临床观察，需更严格 RCT 验证。

**监测建议**：每年检测 hsCRP（<1 mg/L 为理想，1–3 为中度，>3 为高危）与纤维蛋白原；有条件者结合 PhenoAge 表观时钟评估"炎症年龄"；IL-6 因昼夜波动大，仅作科研级监测。

## 七、开放问题与争议

1. **因果方向仍未闭环**：炎症标志物升高究竟是衰老的原因、伴随还是结果？CANTOS（抗 IL-1β 有效）支持因果，ASPREE（广谱抗炎无效）反对简单化——两种结果并存说明"炎症"内部异质性极大，何种炎症、哪个阶段、何种手段决定成败。
2. **抗炎与免疫监视的平衡**：系统性抑制炎症可能削弱抗肿瘤免疫与抗感染能力（canakinumab 组致死性感染增多、阿司匹林组出血与癌症死亡增多）——"抗炎治疗窗"在哪里？低度炎症在损伤修复与肿瘤监视中仍有生理功能。
3. **NF-κB 枢纽 vs NLRP3 放大器 vs 源头清除**：三层次靶点孰优孰劣？NF-κB 抑制长期安全性存疑（免疫抑制风险），NLRP3/IL-1β 靶向更特异但覆盖面有限，senolytics 断源但衰老细胞清除的长期后果未知。
4. **克隆性造血（CHIP）的混杂**：TET2/DNMT3A 突变驱动的克隆性造血随龄常见，既升高炎症（IL-1β）又独立增加心血管风险——是炎症驱动克隆扩增，还是克隆扩增驱动炎症？CANTOS 事后分析显示 canakinumab 对 CHIP 携带者获益更大，提示炎症-造血轴存在双向关系。
5. **个体异质性与时间窗**：炎症轨迹存在明显个体差异（遗传、性别、肥胖、微生物组），"何时开始抗炎"（中年预防 vs 老年治疗）缺乏直接比较证据。

## 参考文献

1. Franceschi C, Bonafè M, Valensin S, et al. Inflamm-aging. An evolutionary perspective on immunosenescence. *Ann N Y Acad Sci*. 2000;908:244-254.
2. Franceschi C, Campisi J. Chronic inflammation (inflammaging) and its potential contribution to age-associated diseases. *J Gerontol A Biol Sci Med Sci*. 2014;69 Suppl 1:S4-S9.
3. López-Otín C, Blasco MA, Partridge L, Serrano M, Kroemer G. Hallmarks of aging: An expanding universe. *Cell*. 2023;186(2):243-278.
4. Ferrucci L, et al. Serum IL-6 level and the development of disability in older persons. *J Am Geriatr Soc*. 1999;47(6):639-646. ／ Ferrucci L, et al. Inflammatory markers and the risk of mobility limitation in the elderly (InCHIANTI). *J Gerontol A Biol Sci Med Sci*. 2005;60(6):729-735.
5. Cohen HJ, et al. The association of plasma IL-6 levels with functional disability in community-dwelling elderly. *J Gerontol A Biol Sci Med Sci*. 1997;52(4):M201-M208.
6. Ridker PM, et al. Antiinflammatory therapy with canakinumab for atherosclerotic disease. *N Engl J Med*. 2017;377(12):1119-1131.
7. McNeil JJ, et al. Effect of aspirin on disability-free survival in the healthy elderly (ASPREE). *N Engl J Med*. 2018;379(16):1519-1528. ／ McNeil JJ, et al. Effect of aspirin on all-cause mortality in the healthy elderly. *JAMA*. 2019;321(4):385-394.
8. Nidorf SM, et al. Colchicine in patients with chronic coronary disease (LoDoCo2). *N Engl J Med*. 2020;383(19):1838-1847.
9. Baker DJ, et al. Naturally occurring p16(Ink4a)-positive cells shorten healthy lifespan. *Nature*. 2016;530(7589):184-189.
10. Hickson LJ, et al. Senolytics decrease senescent cells in humans: Preliminary report from a clinical trial of dasatinib plus quercetin in individuals with diabetic kidney disease. *EBioMedicine*. 2019;47:446-456.
11. Muñoz-Planillo R, et al. K⁺ efflux is the common trigger of NLRP3 inflammasome activation by bacterial toxins and particulate matter. *J Immunol*. 2013;190(7):3528-3536.
12. He Y, et al. NEK7 is an essential mediator of NLRP3 activation downstream of potassium efflux. *Nature*. 2016;530(7590):354-357.
13. Shi J, et al. Cleavage of GSDMD by inflammatory caspases determines pyroptotic cell death. *Nature*. 2015;526(7575):660-665.
14. Shimada K, et al. Oxidized mitochondrial DNA activates the NLRP3 inflammasome during apoptosis. *Immunity*. 2012;36(3):401-414.
15. Dou Z, et al. Cytoplasmic chromatin triggers inflammation in senescence and cancer. *Nature*. 2017;550(7676):402-406.
16. Cani PD, et al. Metabolic endotoxemia initiates obesity and insulin resistance. *Diabetes*. 2007;56(7):1761-1772.
17. Hotamisligil GS, Shargill NS, Spiegelman BM. Adipose expression of tumor necrosis factor-α: Direct role in obesity-linked insulin resistance. *Science*. 1993;259(5091):87-91.
18. Reynaert NL, et al. Nitric oxide represses inhibitory κB kinase through S-nitrosylation. *Proc Natl Acad Sci USA*. 2004;101(24):8945-8950.
19. Yeung F, et al. Modulation of NF-κB-dependent transcription and cell survival by the SIRT1 deacetylase. *EMBO J*. 2004;23(12):2369-2380.
20. Levine ME, et al. An epigenetic biomarker of aging for lifespan and healthspan. *Aging (Albany NY)*. 2018;10(4):573-591.

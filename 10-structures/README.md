# 10 · 分子结构深潜 Molecular Structures

> **专题定位**：把知识库从"通路级"升级到"结构级"——以 PDB 晶体结构/冷冻电镜数据为锚点，解剖核心靶点蛋白的三维结构、活性位点原子细节、结合口袋与构象变化。每篇回答"机制如何在原子层面发生"。
> **主线衔接**：本专题与知识库全部板块交叉引用，是 NO/NAD⁺/mTOR/TET 等主线的"结构底座"。

## 篇目索引

| 篇目 | 靶点 | PDB 锚点 | 核心结构主题 |
|---|---|---|---|
| [01-NOS 家族](01-nos-structures.md) | eNOS/iNOS/nNOS | 3NOS/4NOS | 血红素-BH4-精氨酸口袋、解偶联、二聚界面 |
| [02-sGC/H-NOX](02-sgc-heme.md) | sGC | 3UVJ | 五配位血红素、NO 感知、Fe³⁺ 失聪 |
| [03-AMPK](03-ampk-structure.md) | AMPK | 4CFE/4ZHX | 三聚体、γ CBS 位点、ADaM 变构 |
| [04-mTORC1](04-mtor-structure.md) | mTORC1 | 4JSN/5FLC | 深埋活性位点、FRB 门卫、雷帕霉素堵门 |
| [05-TET/DNA 去甲基化](05-tet-dna.md) | TET2 | 4NM6 | Fe-2OG 活性中心、5mC 翻转、三步氧化 |
| [06-SIRT1](06-sirt1-structure.md) | SIRT1 | 4I5I/4ZZJ | NAD⁺ 依赖催化、烟酰胺反馈、STAC 变构争议 |
| [07-DNMT1](07-dnmt1-structure.md) | DNMT1 | 3PTA/4DA4 | 双锁自抑制、Cys1226 催化、5-Aza 自杀底物 |
| [08-CD38](08-cd38-structure.md) | CD38 | 3DZF | Glu226 共价催化、NAD⁺ 漏斗、三端经济 |
| [09-PARP1](09-parp1-structure.md) | PARP1 | 4DQY | 三锌指损伤感知、失稳激活、修复-消耗权衡 |
| [10-NAMPT](10-nampt-structure.md) | NAMPT | 2GVG/2H3D | 二聚体隧道、Asp219 分子尺、四端闭环 |
| [11-端粒酶](11-telomerase-structure.md) | TERT | 6D6V/5CQG | 四域缝纫机、转位循环、双刃剑 |
| [12-复合物 I](12-complex1-structure.md) | 复合物 I | 5XTD/6G2J | L 形巨无霸、FeS 电子链、ROS 主源 |
| [13-p53](13-p53-structure.md) | p53 | 1TUP/2OCJ | 三指夹 DNA、锌指环、卫士双面性 |
| [14-NF-κB](14-nfkb-structure.md) | NF-κB | 1NFK/2RAM | 二聚体钳、IκB 扣留、炎症主开关 |
| [15-Nrf2/KEAP1](15-nrf2-structure.md) | Nrf2/KEAP1 | 2FLU/3WN7 | 铰链-门闩、Cys 开关、抗氧化主开关 |
| [16-FOXO3](16-foxo3-structure.md) | FOXO3 | 3L2C/2UZK | 翼状螺旋读 DNA、PTM 编码命运、长寿基因 |
| [17-GLP-1R](17-glp1r-structure.md) | GLP-1 受体 | 6B3J/6ORV | 捕蝇草捕获、两段式激活、偏倚激动、代谢抗衰 |
| [18-LC3/自噬](18-lc3-autophagy.md) | LC3/ATG8 | 1UGM/2ZJD | 泛素样核心、LIR 疏水口袋、垃圾回收站 |

## 核心洞察

1. **结构是机制的最终证据**：每个靶点的功能描述都有 PDB 坐标支撑（原子间距离、口袋形状、构象变化）；
2. **"口袋即靶点"**：药物设计（Rentosertib/STAC/雷帕霉素）的本质是"填补/堵住/稳定特定口袋"；
3. **氧化还原敏感位点**：NOS（BH4/Zn²⁺）、sGC（Fe²⁺）、SIRT1（Zn²⁺ 3Cys+1His）、TET（Fe(II)）都有氧化敏感核心——衰老氧化应激的攻击靶点；
4. **主线交汇**：SIRT1-eNOS-NO 轴（NO 主线 × NAD⁺ 主线）、AMPK-mTOR 对抗（代谢主线）、TET-重编程（表观主线）。

## 📚 目录

- [01-一氧化氮合酶（NOS）家族三维结构](01-nos-structures.md)
  - P450 折叠超家族 + 双域架构（加氧酶域/还原酶域/CaM 铰链）
  - 活性腔解剖：血红素（Cys184 近端）、BH4（π 堆叠 3.5 Å）、精氨酸裂隙（Glu361 双齿盐桥锚点）
  - Zn²⁺ 四硫醇位点 = 二聚体"铆钉"（氧化应激 → 解聚 → 解偶联）
  - 解偶联的原子级解释：BH4 缺位 → 第二步电子漏向 O₂ → 超氧
  - PDB：3NOS（eNOS+精氨酸，2.4 Å）、4NOS（iNOS+SEITU，2.25 Å）

- [02-sGC 与 H-NOX 血红素传感器](02-sgc-heme.md)
  - H-NOX 域五配位血红素（His105 近端，第六位为 NO 预留）
  - NO 结合 → His 解离 → 26° 刚性旋转 → 活性暴增 200-400 倍
  - 双亚基活性位点（α/β 界面残基共同构成催化中心）
  - Fe³⁺ 氧化失聪 = NO 信号盲区（sGC 刺激剂 vs 激活剂的结构差异）
  - PDB：3UVJ（人 sGC 催化域，2.08 Å）

- [03-AMPK 异源三聚体](03-ampk-structure.md)
  - α（激酶+AID 自抑制域）+ β（CBM 糖原结合）+ γ（4 CBS 核苷酸位点）
  - AMP 结合 γ 位点 3 → AID 脱开 + Thr172 磷酸化增强 → 激活
  - ADaM 位点（991 结合，激酶域-β 界面）与 C2 位点（γ 表面）——小分子别构激活
  - 二甲双胍"间接激活"的结构逻辑（复合物 I → AMP↑）
  - PDB：4CFE（全长三聚体+991，3.02 Å）、4ZHX（+C2，2.99 Å）

- [04-mTORC1 深埋活性位点](04-mtor-structure.md)
  - "深埋活性位点"设计：FRB 域充当"门卫"
  - 雷帕霉素机制：FKBP12-雷帕霉素结合 FRB → "堵门"而非"堵酶"（变构抑制）
  - 4E-BP1 部分抵抗的结构解释（"挤门缝"）
  - Rheb-GTP 开门 / AMPK 关门 / 雷帕霉素堵门——门控模型
  - PDB：4JSN（mTOR-mLST8 晶体，3.2 Å）、5FLC（mTORC1 cryo-EM，5.9 Å）

- [05-TET 双加氧酶与 DNA 去甲基化](05-tet-dna.md)
  - 双锌指 + DSBH（双链 β 螺旋）催化域，Fe(II)-2OG 活性中心
  - 5mC 碱基翻转进入腔，甲基朝向 Fe(IV)=O——三步氧化 5mC→5hmC→5fC→5caC
  - TDG 切除 + BER 修复 = 完整去甲基化
  - 癌症突变图谱 = 结构功能区图谱
  - 表观重编程"时钟回拨"的分子执行者
  - PDB：4NM6（TET2-DNA，2.02 Å）

## 🎯 专题核心结论

1. **结构决定机制**：eNOS 解偶联、sGC 失聪、mTOR 雷帕霉素耐药、TET 多步氧化——全部由活性位点的原子几何决定
2. **"堵门 vs 堵酶"**：mTOR 的雷帕霉素（变构堵门）与 ATP 竞争剂（正构堵口袋）的差异，解释了抗衰剂量的设计逻辑
3. **结构-疾病-药物闭环**：TET2 癌症突变、NOS 亚型选择性、AMPK 变构激活剂——晶体结构是精准医学与 AI 药物设计的锚点

## 📌 时间线（2026-09-21 建立）

- 本专题基于 RCSB PDB 已验证晶体结构撰写（3NOS/4NOS/3UVJ/4CFE/4ZHX/4JSN/5FLC/4NM6）
- 五篇均 5000+ 纯汉字，含原子级相互作用、配位化学、构象变化与证据分级
- 结构数据均经 PDB 官网核实（分辨率、文献、关键残基）

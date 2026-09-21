# 04 聚焦超声（FUS）：无创脑深部调控与血脑屏障开放

## 核心概念

聚焦超声（Focused Ultrasound, FUS）指用声透镜或相控阵换能器将超声波在体内汇聚为毫米级焦点，在焦点处产生热、机械与空化三类生物学效应，从而实现无创的深部脑靶向干预——既可用高强度聚焦超声（HIFU）热消融病态核团，也可用低强度脉冲超声（LIPU）可逆调节神经活动，更可用"微泡 + 超声"组合瞬时开放血脑屏障（BBB），为脑内大分子药物递送与废物清除开辟通道。FUS 的价值在于它是目前唯一**不经开颅即可到达脑深部任意靶点**（丘脑、基底节、海马、下丘脑）的物理工具，且空间精度达毫米级、效应可逆可调。与抗衰的关系：FUS 兼具三条抗衰通路——①BBBD 促进 Aβ/tau 等蛋白聚集清除并增强免疫监视；②超声刺激经机械敏感通道（Piezo1）触发 Ca²⁺-AMPK-SIRT1 级联并促进脑血流与神经发生；③作为脑内递送平台，把 NAD+ 前体、senolytics、抗体等"抗衰分子"送过血脑屏障（详见 03-hypothalamus.md 的下丘脑 SIRT1 开关假说与 05-experiment-design.md 的组合干预路线图）。

## 分子机制全链条

### 1. 超声波物理基础：频率、聚焦与声学参数

超声波在脑组织中的传播速度约 1540 m/s，波长 λ = c/f。频率越低穿透越深但焦点越大：0.5 MHz 时 λ≈3.1 mm，1 MHz 时 λ≈1.5 mm，220 kHz 时 λ≈7 mm。经颅聚焦需权衡两难——低频（<0.7 MHz）颅骨吸收少、像差小，但焦点粗大；高频焦点精细却严重受颅骨衰减与相位畸变影响。临床经颅 FUS 因此集中在 0.2–1 MHz 区间：BBBD 多用 0.5 MHz，神经调控多用 0.2–0.5 MHz，HIFU 消融约 0.7–1 MHz（借助 CT 颅骨建模做个体化相位校正）。

三个核心声学参数决定生物学效应：

| 参数 | 定义 | 量级参考 |
|---|---|---|
| 机械指数 MI | 焦点负压峰值(MPa) ÷ √频率(MHz)，衡量空化风险 | 诊断限值 1.9；BBBD 需 0.2–0.6 |
| 热指数 TI | 焦点温升估计，衡量热损伤风险 | HIFU 消融焦点 >56℃ 持续 1 s 即凝固 |
| 声辐射力 | 声波动量转移产生的纯机械推力 | 微牛–毫牛级，可推动组织与膜结构 |

超声场还可用强度（空间峰值时间平均强度 ISPTA）、脉冲重复频率（PRF）、占空比（duty cycle）描述——这些参数组合直接决定"热为主"还是"机械为主"。

### 2. 三类声-生物效应

**热效应**：焦点处声能吸收转化为温升。HIFU 把焦点加热到 56–70℃ 造成蛋白变性、凝固性坏死，热消融是"一刀切"破坏；LIPU 则是亚阈值温升（<1–2℃），本身不足以损伤组织，但可借温度依赖的膜电容改变参与神经调节（见第 5 节）。

**机械效应（声辐射力）**：声辐射力对细胞膜产生微米级位移与应变，直接门控机械敏感离子通道——这是 FUS 神经调控与内皮响应的核心物理基础。机械力→通道开放的转导链条：膜张力↑ → Piezo1 等通道构象改变 → 阳离子内流。

**空化效应（cavitation）**：超声负压相使液体中气体核膨胀、正压相压缩。分两种性质截然不同的模式：

```
微泡在声场中的行为
   │
   ├── 稳定空化(stable cavitation): 微泡低频稳态振荡
   │       → 微流(microstreaming) → 内皮剪切应力
   │       → 可逆、安全 —— BBBD 的目标模式
   │
   └── 惯性空化(inertial cavitation): 负压超过阈值, 微泡急剧塌缩
           → 冲击波/微射流 → 内皮损伤、微出血 —— 必须避免
```

外源注入的脂质壳微泡（直径 1–4 μm，如 SonoVue、Definity）作为空化核，把所需声压降低约一个数量级——这就是"微泡 + 低 MI 超声"能安全开放 BBB 的原因。临床用被动空化检测（PCD）实时监听微泡回波的谐波特征，闭环调节声压，把空化锁定在稳定模式。

### 3. FUS 模式谱系：从破坏到调控

```
高强度 HIFU (数千 W/cm², 连续/长脉冲) ── 热消融 ── 震颤/PD/OCD 核团毁损
低强度 LIPU (0.1–10 W/cm², 短脉冲) ──── 机械调控 ─ 神经调控/可逆调节
微泡 + 低 MI 脉冲超声 (0.5 MHz, PRF 1–10 Hz) ─ BBBD ─ 药物递送/清除
```

四种模式对应四种临床应用逻辑：HIFU 是"毁损"（不可逆、精确破坏病态核团）；LIPU 神经调控是"调节"（可逆、兴奋或抑制取决于参数）；BBBD 是"开门"（瞬时开放屏障、数小时恢复）；超声+干细胞/基因是"递送"（借 BBBD 窗口把治疗载体送入脑实质）。

**参数的"剂量-效应"工程视角**：FUS 的临床效果高度依赖一组可调参数——频率（常用 0.2–1.5 MHz，颅骨衰减与聚焦精度权衡）、声压/机械指数（MI，决定空化模式）、脉冲重复频率与占空比（决定神经兴奋/抑制方向）、脉冲时长与总声暴露（决定热累积）。这套"参数空间"类似药物剂量学：**同一靶点用不同参数可得到相反效果**（如低占空比 tFUS 抑制皮层、高占空比兴奋），因此"FUS 处方"必须个体化定制，且需颅骨 CT 建模校正声场像差（老年颅骨骨密度下降会改变声学特性）。工程成熟度上，闭环空化监控（PCD）已能把 BBBD 锁定在稳定空化窗内，是安全性保障的关键技术——**"参数可编程 + 闭环监控"使 FUS 从实验工具走向可重复的临床处方**，这也是它区别于"光疗"（参数相对简单）的工程门槛。

### 4. 微泡介导 BBBD 的分子事件链

微泡稳定振荡产生的微流与剪切力作用于脑微血管内皮，触发一条从物理刺激到分子重排的完整链条：

```
微泡振荡 → 内皮剪切应力/牵张
   │
   ├── ① 紧密连接重塑: claudin-5 / occludin / ZO-1 磷酸化-重分布, 间隙瞬开
   ├── ② 跨细胞转运↑: 小窝(caveolae)介导的胞吞-胞吐增强 —— 近年证据提示
   │      跨细胞通路(transcytosis)是主导机制, 而非单纯细胞间隙扩大
   ├── ③ 内皮 NO 释放: 剪切力激活 eNOS(PI3K/Akt 磷酸化) → NO → sGC/cGMP
   │      → 血管舒张 + 紧密连接蛋白调节 —— BBBD 的分子签名之一
   └── ④ 下游细胞反应: 星形胶质足突回缩(短暂)、小胶质细胞活化、
           免疫细胞(单核/中性粒/T 细胞)浸润
```

关键量化特征：**可递送分子尺寸跨度极大**——从数百 Da 的小分子到 2 MDa 的葡聚糖乃至抗体（150 kDa）、纳米颗粒（数十–数百 nm）都能穿过（Choi 2010 动物实验系统测定）；**时间窗口**——啮齿类 BBB 在 2–6 小时内闭合，人脑 MRI 造影显示 24 小时内恢复（Lipsman 2018）；**空间精度**——开放区域与超声焦点一致，毫米级。免疫学后果是被开放区域出现短暂的外周免疫细胞浸润与抗原呈递增强，这既是 AD 免疫清除 Aβ 的机制基础，也是胶质瘤免疫治疗增敏的入口。

### 5. 超声神经调控的分子机制

LIPU 刺激神经元的机制假说有四条主线，证据强度递减：

| 假说 | 分子靶点 | 证据状态 |
|---|---|---|
| 机械敏感通道门控 | Piezo1、TRAAK/TREK-1、Nav1.5、TRP 家族 | 最强：Piezo1 敲低/阻断后超声刺激显著减弱（Qiu 2019；Prieto 2018） |
| 膜电容效应 | 脂双层（温升依赖） | 中等：亚阈值温升改变膜电容可致去极化（体外） |
| 辐射力牵张 | 膜骨架、细胞骨架 | 机制支持：辐射力足以产生通道激活所需应变 |
| 胶质介导 | 星形胶质细胞 Ca²⁺ 波 → 谷氨酸释放 | 动物支持：胶质参与可解释长时程效应 |

下游级联：Piezo1 开放 → Ca²⁺ 内流 → 激活 CaMK 与 AMPK → 线粒体生物合成与 SIRT1 通路（体内未直接验证，属机制推测，见开放问题）；同时超声刺激可上调 BDNF（Tufail 2010 及后续研究），促进海马神经发生——这条"机械→Ca²⁺→AMPK/SIRT1→BDNF→神经发生"链是 FUS 与抗衰网络对接的核心接口。

## 证据分级

| 现象 | 证据等级 | 关键文献 |
|---|---|---|
| HIFU 丘脑 VIM 消融改善特发性震颤 | 实锤（RCT） | Elias 2016（NEJM，n=76）：治疗组震颤评分改善 47% vs 假手术 0% |
| HIFU 消融治疗 PD 运动症状/OCD | 强关联（开放/前瞻） | Martinez-Fernández 2018（Lancet Neurol）；Kim 2018（2 年随访） |
| 微泡+FUS 可逆开放 BBB（动物→人） | 实锤（多物种） | Hynynen 2001（兔，首创）；Lipsman 2018（人，5 例 17 次开放） |
| BBBD 递送单抗入脑（AD/HER2+ 转移） | 早期人体（I 期） | Rezai 2024（NEJM，n=3）；Meng 2021（Sci Transl Med） |
| 超声清除 Aβ、恢复记忆（小鼠） | 动物实锤 | Leinenga & Götz 2015（Sci Transl Med） |
| tFUS 调节人脑皮层活动与感知 | 强关联（人体神经生理） | Legon 2014（Nat Neurosci）；Lee 2015（Sci Rep） |
| Piezo1 介导超声神经元刺激 | 实锤（体外/离体） | Qiu 2019（iScience）；Prieto 2018（UMB） |
| BBBD 促进海马神经发生与认知 | 动物支持 | Scarcelli 2014（Brain Stimul）；Lee 2020（Alzheimers Res Ther） |
| BBBD 化疗增敏（胶质母细胞瘤） | 早期人体 | Carpentier 2016（Sci Transl Med，SonoCloud） |
| 超声激活 eNOS/NO、改善脑血流 | 动物+机制研究 | LIPUS 内皮细胞 PI3K/Akt-eNOS 通路（多项机制研究） |
| FUS→Piezo1→AMPK→SIRT1 体内因果链 | 机制推测（体内未验证） | 由体外通道数据外推，待直接验证 |

## 临床/实验证据细节

**HIFU 消融特发性震颤（获批临床）**：Elias 2016 多中心 RCT（n=76，治疗 56 例 vs 假手术 20 例）显示，MRI 引导 HIFU 丘脑腹中间核（VIM）消融后 3 个月，治疗组对侧手震颤评分改善 47%（95% CI 37–57%），假手术组 0%（-4 至 5%）；12 个月时获益持续，但约 9% 出现步态障碍、14% 感觉异常（多为轻中度、部分持续）。FDA 于 2016 年批准 Exablate Neuro 用于药物难治性特发性震颤——这是 FUS 首次获批的脑内适应症，疗效与深部脑刺激（DBS）相当而免开颅、无植入物感染风险，代价是不可逆毁损（无法"关掉"）。PD 方向：Martinez-Fernández 2018 的 I 期试验对 10 例不对称 PD 患者行丘脑底核（STN）亚核 HIFU 消融，运动评分显著改善，不良事件多为短暂。OCD 方向：Kim 2018 双侧前囊热毁损 2 年随访 Y-BOCS 评分显著下降——"精神外科"正在被无创化。

**BBBD 用于阿尔茨海默病**：Lipsman 2018（Nat Commun）对 5 例轻中度 AD 患者行 17 次 MRI 引导 BBBD（靶点：额叶背外侧皮层），安全性良好、BBB 24 小时内闭合、无认知恶化。Rezai 2024（NEJM，n=3）把 BBBD 与抗 Aβ 单抗 aducanumab 联用 26 周：PET 显示**超声开放区域淀粉样沉积减少幅度大于未开放区域**，且安全性可接受——直接证明"开门 + 抗体"策略在人脑可行。动物机制侧，Leinenga & Götz 2015 用扫描超声（无微泡）清除 APP23 小鼠 Aβ 斑块并恢复空间记忆，机制涉及小胶质细胞活化吞噬与 glymphatic 外排增强——BBBD 清除蛋白聚集物不依赖外源药物，是"自清洁"假说的核心证据。

**BBBD 化疗增敏（胶质母细胞瘤）**：Carpentier 2016（Sci Transl Med）植入式 SonoCloud 装置对 15 例复发胶质母细胞瘤患者开放 BBB 后予卡铂化疗，提示无进展生存获益趋势（与历史对照比较）且毒性可接受；这是 BBBD 肿瘤适应症的里程碑，后续多中心试验（SonoCloud-9）在开展中。

**人体神经调控**：Legon 2014（Nat Neurosci）用 500 kHz tFUS 靶向初级躯体感觉皮层，改善触觉辨别精度并改变 EEG 节律——首次在人体证明经颅超声可调节皮层功能；Lee 2015 以单脉冲 tFUS 靶向初级运动皮层诱发出运动诱发电位（MEP），提示可刺激而非仅抑制。抑郁症、成瘾等精神适应症（靶向 sgACC、伏隔核等）处于早期小样本阶段。

**神经发生与递送**：Scarcelli 2014 与 Lee 2020 分别在正常成年小鼠和胆碱能退化痴呆大鼠模型证实 BBBD 增加海马齿状回神经发生并改善认知；Meng 2021 对 4 例 HER2+ 脑转移患者开放 BBB 后输注曲妥珠单抗，PET 证实脑内药物摄取增加、部分病灶缓解——BBBD 作为"脑内递送平台"的转化证据链已闭合。

**临床试验全景与 2026 进展**：FUS 的临床转化正沿三条线快速推进——①**肿瘤线**：BBBD+化疗/免疫治疗的胶质母细胞瘤多中心试验（SonoCloud-9、ExAblate 颅骨系统）持续入组，BBBD+卡铂在部分中心进入 II 期；②**神经退行线**：BBBD+抗 Aβ 单抗（aducanumab 之后 lecanemab/donanemab 的联用探索）与 BBBD 单用（tau 清除）的试验在阿尔茨海默病中扩展，Rezai 2024 的"超声区域淀粉样清除加速"为联用策略提供首个人体证据；③**精神线**：tFUS 调控抑郁（靶向 sgACC/伏隔核）与强迫症的小样本试验持续产出，参数标准化（频率/脉冲/靶区）正在多中心协作下推进。**抗衰方向的特殊价值**：FUS 是极少数"无创、可重复、可定位"的脑干预工具——若 BBBD+药物递送（NMN、senolytics、基因载体）在神经退行试验中证明可行，其向"脑抗衰"延伸的路径将非常短（详见 [05-experiment-design](05-experiment-design.md) 的路线图）。需保持审慎：多数试验仍为 I 期/小样本，长期安全性（反复 BBBD 对 BBB 结构的累积影响、微出血风险）数据尚不足。

## 与 NO / NAD+ / 长寿网络联系

- **FUS→NO 的机械转导链**：声辐射力与微泡微流产生的剪切应力是 eNOS 的经典激活信号（PI3K/Akt 磷酸化 eNOS-S1177）——LIPUS 在血管内皮、骨骼、肌腱组织中激活 eNOS/NO 已有大量机制研究；据此推断经颅 FUS 提升局部脑血流部分经"剪切力→eNOS→NO→sGC/cGMP→血管舒张"实现（详见 01-foundations/03-no-basics.md）。BBBD 本身的分子签名就包含 NO：NO 经 cGMP 通路调节紧密连接蛋白与血管通透性，是"开门"的化学伙伴，也提示**FUS 是少数能同时提供"机械信号 + NO 信号 + 血流改善"三联干预的工具**。
- **NO 双刃剑在 FUS 语境**：稳定空化介导的 eNOS/NO 是有益的；但惯性空化与组织损伤会诱发 iNOS 大量产 NO，与超氧生成 ONOO⁻ 造成硝化损伤——这与本库"NO 双刃剑"主线一致，也解释为何 BBBD 的安全窗必须锁定稳定空化。
- **NAD+/SIRT1 接口**：①Piezo1→Ca²⁺→AMPK→SIRT1 是假说链（体内未验证），若成立则 FUS 是"机械激活长寿通路"的入口；②BBBD 作为递送平台可把 NMN/NR、senolytics、NAD+ 依赖酶调节剂直接送入脑实质，绕过"外周 NAD+ 提升难以跨越 BBB"的瓶颈——这是 FUS 与 NAD+ 网络最具操作性的交叉点；③FUS-BBBD 促进神经发生与 BDNF 上调，与 NAD+/SIRT1 介导的线粒体生物合成（PGC-1α）形成下游汇合。

## FUS 与衰老：从神经退行干预到脑再青春

**蛋白聚集清除与神经退行**：Aβ、tau、α-突触核蛋白聚集是 AD/PD 的核心病理，而脑内清除系统（glymphatic、小胶质细胞吞噬、蛋白酶体/自噬）随龄全面衰退（详见 01-foundations/06-proteostasis-autophagy.md）。FUS 提供了两条独立的清除杠杆：①BBBD 本身即促进 glymphatic 对流外排与脑膜淋巴引流——开放区域间质液流动加速，Aβ/tau 随 CSF 外排；②开放窗口内小胶质细胞被激活，吞噬能力增强（Leinenga & Götz 2015 小鼠实验中 Aβ 斑块面积显著缩小即此机制）。两杠杆叠加意味着 FUS 是少数"不依赖外源药物"即可动员脑内自清洁系统的工具——这与 senolytics"清除衰老细胞"的逻辑同构，只是作用于蛋白聚集物。

**神经再生与干细胞**：BBBD 后海马齿状回神经发生增加（Scarcelli 2014；Lee 2020），机制涉及 BDNF 上调、炎症环境向修复型偏移与血流改善。更进一步，"FUS + 干细胞"策略：超声预开放 BBB 后静脉/鞘内输注神经干细胞或间充质干细胞（MSC），使干细胞在超声靶区定植分化——临床前已有报道 FUS 增强 MSC 归巢与神经元替代，若成立则是修复性神经再生而非仅清除。结合本库主线：FUS 诱导的神经发生若经 AMPK-PGC-1α 线粒体生物合成路径（NAD+/SIRT1 下游）放大，可与 NAD+ 前体干预形成"生成 + 供给"协同。

**脑血流与血管衰老**：经颅 FUS 可提升局部脑血流与氧合（超声血管舒张 + eNOS/NO），对抗老年性脑血流下降与血管僵化；BBBD 对脑微血管内皮施加的周期性剪切力本身即是内皮健康的机械训练信号——这一"血流↑→剪切力→eNOS/NO→血管舒张→血流↑"的正反馈正是本库 NO 主线在血管端的标准回路（详见 01-foundations/03-no-basics.md）。**下丘脑抗衰开关**：本专题假说链的终点是经 FUS 靶向下丘脑（详见 03-hypothalamus.md 与 05-experiment-design.md），用超声激活下丘脑 SIRT1 通路以广播式调节全身代谢——当前仅处于声场仿真与动物验证阶段，属机制推测级证据。

## FUS 与免疫：神经炎症调节与免疫监视

**小胶质细胞表型重塑**：BBBD 后靶区小胶质细胞短暂活化，向"吞噬-修复"表型偏移（M1 促炎标志短暂上升后回落、Aβ 吞噬标志 CD68 升高）；扫描超声清除 Aβ 的研究证实活化小胶质细胞是清除主力（Leinenga & Götz 2015）。但表型极化的方向与持续时间强烈依赖超声参数与组织状态——在神经炎症背景下若空化控制不当，也可能放大 M1 型炎症，这是"好免疫"与"坏免疫"的边界问题。

**免疫细胞浸润与抗原呈递**：BBBD 窗口期外周免疫细胞（单核细胞、中性粒细胞、T 细胞）浸润脑实质，脑内抗原（肿瘤新抗原、Aβ）随之被呈递到颈深淋巴结——这为脑内免疫治疗提供了两个入口：①胶质母细胞瘤：BBBD + 检查点抑制剂（anti-PD-1）在临床前显著增强肿瘤浸润淋巴细胞杀伤；②AD：外周免疫细胞入脑参与 Aβ 清除，或可解释部分 BBBD 动物模型的认知获益。**双向风险**：浸润是把双刃剑——过度开放或惯性空化可致微出血、炎症放大与自身免疫风险（如抗 Aβ 免疫应答过强），安全窗管理因此是 BBBD 免疫学的核心命题。

**神经-免疫轴的整体视角**：FUS 的免疫效应与 03-immunity/06-neuro-immune-axis.md 描述的"炎症反射、小胶质细胞衰老、glymphatic 清除"形成闭环——FUS 同时作用于小胶质细胞（脑侧免疫）、glymphatic（清除通道）、BBB（外周-中枢界面）三个节点，是少数能"一站式"干预神经免疫轴衰老的物理工具。

## 干预方向与可执行建议

**已临床可及**：HIFU 消融（特发性震颤 FDA 批准；PD、OCD、强迫症在部分中心开展）——适用于药物难治、不耐受开颅手术者，需 MRI 引导团队与个体化颅骨相位校正。

**研究前沿（证据由强到弱）**：①BBBD + 抗体/化疗（AD、胶质母细胞瘤、脑转移）——I 期数据积极，等待更大样本；②tFUS 神经调控（抑郁、焦虑、成瘾）——早期人体试验，参数标准化未完成；③BBBD + 免疫治疗（检查点抑制剂、CAR-T 脑递送）——动物证据强劲；④FUS + 干细胞/基因递送——临床前。

**抗衰视角组合建议**：把 FUS-BBBD 视为"脑内清除 + 递送"双功能平台——与 NAD+ 前体（NMN/NR）、senolytics（清除脑内衰老细胞）、抗 Aβ/tau 策略组合（详见 05-experiment-design.md 路线图）。实验侧硬性要求：k-Wave 声场仿真 + 体模验证、PCD 闭环空化监控、组织学安全终点（微出血、BBB 完整性、体温）。

**FUS 在抗衰全景中的定位（与其他干预的关系）**：在 [09-immortality/02-breakthrough-candidates](../../09-immortality/02-breakthrough-candidates.md) 的候选框架里，FUS 不是"逆转衰老"的独立候选，而是**"递送 + 清除"的赋能工具**：①作为递送平台，它把药物（抗体、NMN、基因载体、CAR-T）送进过去无法到达的脑实质——让"脑抗衰"从不可能变为可能；②作为清除工具，它动员 glymphatic 与小胶质细胞清除蛋白聚集物——与 Senolytics 清除衰老细胞、自噬诱导剂清除受损蛋白构成"三级清除体系"；③作为神经调控工具，它与 PBM（[01-photobiomodulation](01-photobiomodulation.md)）互补——光作用于线粒体/NO，声作用于机械转导/血流，二者都是"物理抗衰"路径，可组合使用（光声联合）但证据均处早期。**定位总结**：FUS 的价值不在"独立延寿"，而在**解锁大脑这个最难干预器官的抗衰可能性**——它的成败将决定"脑年轻化"能否成为现实。

## 开放问题与争议

- **神经调控的机制归因不清**：Piezo1 之外，膜电容效应、辐射力牵张、胶质介导的贡献比例未知；"兴奋还是抑制"由 PRF/占空比决定，但参数-效应映射缺乏统一理论。
- **BBBD 的长期安全性**：反复开放对 BBB 结构与 glymphatic 功能的累积影响未知；AD 患者常伴脑淀粉样血管病（CAA），微出血风险是 BBBD 推广的核心顾虑——PCD 闭环能否在人群层面消除惯性空化尚无定论。
- **剂量标准化缺失**：频率、MI、脉冲方案、微泡剂量在不同中心差异大，难以横向比较疗效。
- **FUS→Piezo1→AMPK→SIRT1 体内因果链未验证**：现有多为体外通道数据外推，活体"超声→机械转导→长寿通路"全链待直接观测。
- **颅骨像差个体差异**：CT 建模校正的鲁棒性与老年颅骨（骨密度下降）下的重校准需求未解决。
- **长期神经可塑性改变**：反复神经调控是否带来致痫、习惯化或代偿性重塑，缺乏长期随访。

## 参考文献

1. Elias WJ, Lipsman N, Ondo WG, et al. A randomized trial of focused ultrasound thalamotomy for essential tremor. N Engl J Med. 2016;375(8):730-739.
2. Lipsman N, Schwartz ML, Huang Y, et al. MR-guided focused ultrasound thalamotomy for essential tremor: a proof-of-concept study. Lancet Neurol. 2013;12(5):462-468.
3. Hynynen K, McDannold N, Vykhodtseva N, Jolesz FA. Noninvasive MR imaging-guided focal opening of the blood-brain barrier in rabbits. Radiology. 2001;220(3):640-646.
4. Lipsman N, Meng Y, Bethune AJ, et al. Blood-brain barrier opening in Alzheimer's disease using MR-guided focused ultrasound. Nat Commun. 2018;9(1):2336.
5. Rezai AR, D'Haese PF, Finomore V, et al. Ultrasound blood-brain barrier opening and aducanumab in Alzheimer's disease. N Engl J Med. 2024;390(1):55-62.
6. Leinenga G, Götz J. Scanning ultrasound removes amyloid-β and restores memory in an Alzheimer's disease mouse model. Sci Transl Med. 2015;7(278):278ra33.
7. Carpentier A, Canney M, Vignot A, et al. Clinical trial of blood-brain barrier disruption by pulsed ultrasound. Sci Transl Med. 2016;8(343):343re2.
8. Legon W, Sato TF, Opitz A, et al. Transcranial focused ultrasound modulates the activity of primary somatosensory cortex in humans. Nat Neurosci. 2014;17(2):322-329.
9. Tufail Y, Matyushov A, Baldwin N, et al. Transcranial pulsed ultrasound stimulates intact brain circuits. Neuron. 2010;66(5):681-694.
10. Tyler WJ, Tufail Y, Finsterwald M, et al. Remote excitation of neuronal circuits using low-intensity, low-frequency ultrasound. PLoS One. 2008;3(10):e3511.
11. Qiu Z, Guo J, Kala S, et al. The mechanosensitive ion channel Piezo1 significantly mediates in vitro ultrasonic stimulation of neurons. iScience. 2019;21:448-457.
12. Prieto ML, Firouzi K, Khuri-Yakub BT, Maduke M. Activation of Piezo1 but not NaV1.2 channels by ultrasound at 43 MHz. Ultrasound Med Biol. 2018;44(6):1217-1232.
13. Choi JJ, Wang S, Tung YS, Morrison B 3rd, Konofagou EE. Molecules of various pharmacologically-relevant sizes can cross the ultrasound-induced blood-brain barrier opening in vivo. Ultrasound Med Biol. 2010;36(1):58-67.
14. Scarcelli T, Jordão JF, O'Reilly MA, Ellens N, Hynynen K, Aubert I. Stimulation of hippocampal neurogenesis by transcranial focused ultrasound and microbubbles in adult mice. Brain Stimul. 2014;7(2):304-307.
15. Lee S, Kim Y, Kim E, et al. Focused ultrasound-induced blood-brain barrier opening improves adult hippocampal neurogenesis and cognitive function in a cholinergic degeneration dementia rat model. Alzheimers Res Ther. 2020;12(1):110.
16. Martinez-Fernández R, Rodríguez-Rojas R, del Álamo M, et al. Focused ultrasound subthalamotomy in patients with asymmetric Parkinson's disease: a phase 1 trial. Lancet Neurol. 2018;17(1):54-63.
17. Kim SJ, Roh D, Jung HH, Chang WS, Kim CH, Chang JW. A study of novel bilateral thermal capsulotomy with focused ultrasound for treatment-refractory obsessive-compulsive disorder: 2-year follow-up. J Psychiatry Neurosci. 2018;43(5):327-337.
18. Meng Y, Reilly RM, Pezo RC, et al. MR-guided focused ultrasound enhances delivery of trastuzumab to Her2-positive brain metastases. Sci Transl Med. 2021;13(615):eabj4011.
19. McDannold N, Vykhodtseva N, Hynynen K. Blood-brain barrier disruption induced by focused ultrasound and circulating preformed microbubbles appears to be characterized by the mechanical index. Ultrasound Med Biol. 2008;34(5):834-840.

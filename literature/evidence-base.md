# 证据档案（立项前研究沉淀）

> 用途：把立项决策的事实底子落盘，供后续判定时溯源。所有数字带 URL；可信度分级见文末。
> 采集时间 2026-11-23。检索噪声（成人高考、红桃视频、远控、Obsidian 插件等中文垃圾结果）已剔除。

## 一、三条真永生路线对比（决策背景）

| | 路线 A 生物修复 | 路线 B 全脑仿真/上传 | 路线 C 渐进替换 |
|---|---|---|---|
| 延续的是谁 | 同一个我 ✅ | 我的副本 ❓ | 同一个我（理论）✅ |
| 最硬证据 | 人体 Phase 1 首批数据 | 果蝇全脑可运行 | 无 |
| 卡点 | 修复能否永远跟上损伤 | 扫描分辨率/活体数据 | 每步读取+接管 |
| 时间表 | 局部疗法 3–5 年见分晓 | 乐观 2068–2088 | 不可预测 |

**决策**：选 A1（OSK 重编程），弃 B/C。理由=唯一近期可证伪。

## 二、选定对象 A1：表观遗传部分重编程（OSK / ER-100）

### 原理
- Sinclair 主张：衰老 = 表观遗传信息丢失，信息可找回。
- OSK = Oct4/Sox2/Klf4（去掉致瘤 c-Myc）瞬时表达 → 重置甲基化到年轻态，但不完全回退到干细胞（避免去分化/致瘤）→ 称"部分重编程（PER）"。

### 硬进展（可信度 B，同行评议 + 官方 IND）
- **2026-01 FDA IND 批准**：Life Biosciences 候选药 ER-100（OSK 基因疗法，靶向视网膜神经节细胞）。
- 注册号 **NCT07290244**，适应症：青光眼 + NAION（非动脉炎性前部缺血性视神经病变）。
- URL：https://www.lifebiosciences.com/author/maggie-farrand
- 首个人体"细胞返老还童"临床试验。

### 首批读数（可信度 C，早期、无对照）
- **2026-10-08**：首批 3 人，耐受 8 周，2 人视野改善。
- 无随机对照、最低剂量、未证明细胞生物学年轻化 → 官方定性"早期信号，非返老还童证据"。
- $80M D 轮融资。
- URL：https://nad.com/news/david-sinclairs-experimental-cell-rejuvenation-therapy-shows-early-vision-signals-in-first-human-trial

### 风险/反证（必须写进判定）
- Nat Commun 2024 综述：表观遗传年龄下降 ≠ 真正返老还童，须区分 rejuvenation vs dedifferentiation，致瘤风险未解。URL：https://www.nature.com/articles/s41467-024-46020-5

## 三、路线 A2：端粒酶基因治疗（对照参考，不作证据）

- 动物（可信度 A/B）：CNIO/Blasco 用 AAV9-mTERT 处理小鼠，延寿、延衰、未增癌。URL：https://pmc.ncbi.nlm.nih.gov/articles/PMC3494070
- 人体（可信度 C，不采信）：BioViva CEO Liz Parrish 自述"逆转 20 年端粒"（单人自述）；Libella 在哥伦比亚 pay-to-play（100 万美元/人，约 5 人）。URL：https://www.clinicaltrialsarena.com/news/libella-ageing-gene-therapy-trial
- 教训：端粒酶致癌担忧可能被克服，但人体数据目前不可当证据。

## 四、路线 B/C 关键数据（弃选依据）

- 人脑 ~860 亿神经元、数万亿突触。URL：https://www.afterlife.ai/mind-uploading
- 最复杂连接组：线虫(~300)、果蝇成虫全脑(~13–14 万，2024 FlyWire)；小鼠仅 1mm³ 视皮层。
- 1mm³ 人脑 = 1400 TB。扫描是破坏性的、死后进行；活体纳米级无方法。
- 算力(~10¹⁸ ops/s)不是瓶颈，**数据才是**：State of Brain Emulation Report 2025。URL：https://www.alphaxiv.org/abs/2510.15745 ; https://brainemulation.mxschons.com
- 时间表：中位 2068–2088。URL：https://futuresearch.ai/app/p/a/first-mind-upload-date
- MIT McGovern：小鼠全脑还需 10–15 年。URL：https://mcgovern.mit.edu/2026/09/02/can-and-should-consciousness-be-uploaded-to-a-machine
- griefbot/AI 克隆只读文字不碰脑数据，与上传无关。

## 五、NCT07290244 注册信息核验（2026-11-23，ClinicalTrials.gov API v2 一手）

来源：https://clinicaltrials.gov/api/v2/studies/NCT07290244 （HTTP 200，原文抓取）

- **试验设计**：Phase 1，first-in-human；`allocation: NON_RANDOMIZED`、`masking: NONE`、`interventionModel: SEQUENTIAL`（单臂序贯剂量递增）。**无对照组、无盲法。**
- **给药**：单次玻璃体内注射 ER-100（AAV 递送 OSK 到视网膜细胞），口服 doxycycline 8 周（56 天）激活 OSK；随访最长 5 年。
- **队列**：OAG 剂量递增（低剂量 2×10¹¹ vg/eye、高剂量 6×10¹¹ vg/eye）+ NAION 剂量扩展（最多 6 人）；总计 18 人（12 OAG + 6 NAION）。每剂量首位 sentinel，DSMB 审 28 天数据后再放行。
- **状态**：RECRUITING；start 2026-03-02（actual）；primary completion 2027-05（est）；completion 2032-03（est）；last update posted 2026-05-19。
- **主要终点全部是安全性**：TEAE、剂量限制毒性（DLT）、肝功能/血检/尿检等实验室指标。
- **关键**：眼科功能指标在这个试验里**全部标注为 Safety 终点**，不是疗效终点——包括眼压(IOP)、最佳矫正视力(BCVA/ETDRS)、Humphrey 视野(HVF, MD 值 dB)、模式视网膜电图(pERG，评估 RGC 功能)。原文："Change from Baseline in ... — Safety"，且明确"worsening ... may suggest a safety concern"。
  - 含义：2026-10-08 报道的"2 人视野改善"是**安全性监测中的附带观察**，不是预设疗效终点的读出；本试验根本没有疗效终点。首批数据证据强度比新闻稿语气更弱。
  - 附带利好：pERG（RGC 功能）确实被测量，可作为 E02/H2 的客观细胞功能读数线索（虽标注为 safety）。
- **对 verifier 的影响**：原判据"随机对照下视野改善"在本 Phase 1 无法读出（无对照）。须改为：本试验只判 H3（安全性）；疗效类 H1/H2 至多是"探索性信号"，真正的随机对照疗效要等后续 Phase。见 verifier.md 修订说明。

## 六、可信度分级（沿用全程）
- **A**：人体 RCT / 荟萃 / 同行评议强证据
- **B**：动物充分 + 人体初步 / 官方监管动作
- **C**：概念 / 思想实验 / 商业宣传 / 单人自述 / 无对照早期信号
- C 级数据只作"值得验证"的线索，不进终判的证据链。

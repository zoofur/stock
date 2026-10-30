# 来源与口径

取证截至2026-10-30收盘后（北京时间）。行情为腾讯行情10-30 15:57快照；财务为2026年三季报（未经审计）。情景估值与买入区间为分析假设，不是公司指引。

## 行情与财务接口

- [https://qt.gtimg.cn/q=sh603893,sz300458,sh688099,sh688608,sz301536](https://qt.gtimg.cn/q=sh603893,sz300458,sh688099,sh688608,sz301536)
  收盘价、PE(TTM/动/静)、PB、市值；瑞芯微PE(TTM) 47.54经净利倒推核对。脚本原把动态PE 42.62当TTM，已更正。

- akshare `stock_financial_abstract_ths`（同花顺财务摘要，按报告期）
  2024-2026Q3营收、净利、毛利率、ROE、存货周转；单季数据由累计值相减。

## 公司公告与事件

- [http://static.cninfo.com.cn/finalpage/2026-10-27/1225627336.PDF](http://static.cninfo.com.cn/finalpage/2026-10-27/1225627336.PDF)
  瑞芯微 2026 年第三季度报告（巨潮，2026-10-27 披露，董事会 10-26 审议）：Q3 营收 15.73 亿元（同比 +43.57%），归母净利 4.73 亿元（+90.49%），扣非 4.61 亿元（+92.10%）。前三季度营收 44.49 亿元（+41.64%），归母净利 13.32 亿元（+70.90%），毛利率 46.37%，加权 ROE 27.35%。经营现金流 8.82 亿元（+4.13%）。货币资金加交易性金融资产 30.66 亿元，无有息借款。前十大股东：励民 37.20%，黄旭 13.23%，香港中央结算 4.32%。Q3 环比下滑原因：H1 存储和阻容涨价传导到 Q3 终端销售市场，终端在调整消化；Q3 PCB 原材料短缺、交期拉长，AIoT 品类碎片化，受影响大于成熟产业，芯片订单滞后顺延，预计 Q4 恢复。

- [http://static.cninfo.com.cn/finalpage/2026-10-16/1225607199.PDF](http://static.cninfo.com.cn/finalpage/2026-10-16/1225607199.PDF)
  2026 年前三季度业绩情况的自愿性披露公告（巨潮，2026-10-16）：预告营收约 44.47 亿元，净利 13.1-13.5 亿元（+68.04%-73.17%），实际净利 13.32 亿元落在区间中值附近。公告原文提到：北京国际机器人展会上瑞芯微的机器人市场占有率极高；「类似 Microduck 的新质生产力爆品不断涌现」。风险提示措辞为「AI 数据中心投资继续疯狂增长」「轮番短缺」，比正式三季报的「潜在的快速增长」更激进。

- [https://datacenter-web.eastmoney.com/api/data/v1/get?reportName=RPT_BILLBOARD_DAILYDETAILSSELL&columns=ALL&filter=(TRADE_DATE='2026-10-16')(SECURITY_CODE=%22603893%22)&pageSize=10&sortColumns=BUY&sortTypes=-1](https://datacenter-web.eastmoney.com/api/data/v1/get?reportName=RPT_BILLBOARD_DAILYDETAILSSELL&columns=ALL&filter=(TRADE_DATE='2026-10-16')(SECURITY_CODE=%22603893%22)&pageSize=10&sortColumns=BUY&sortTypes=-1)
  东方财富龙虎榜明细（2026-10-16）：上榜原因：日跌幅偏离值达 7%，收盘 171.01 元（-9.99%），全天成交 39.74 亿元，换手 5.32%。榜单买入 6.65 亿元、卖出 12.52 亿元，净卖出 5.87 亿元。卖一为沪股通，卖出 8.96 亿元，但沪股通同时在买一买入 3.03 亿元，净卖出 5.93 亿元；中信上海、中金上海、高盛世纪大道、兴业武汉新华路各卖出 0.76-0.98 亿元。买方有两个机构专用席位，合计买入 2.36 亿元。买入明细接口：https://datacenter-web.eastmoney.com/api/data/v1/get?reportName=RPT_BILLBOARD_DAILYDETAILSBUY&columns=ALL&filter=(TRADE_DATE='2026-10-16')(SECURITY_CODE=%22603893%22)&pageSize=10&sortColumns=BUY&sortTypes=-1

- [http://static.cninfo.com.cn/finalpage/2026-10-27/1225627333.PDF](http://static.cninfo.com.cn/finalpage/2026-10-27/1225627333.PDF)
  利润分配预案公告（巨潮，2026-10-27）：每 10 股派 3.50 元（含税），按总股本 4.234 亿股计约 1.48 亿元，占前三季度净利 11.12%，不转增，尚需股东会审议。母公司可分配利润 25.58 亿元。按现价计股息率 0.20%；前三季度筹资活动已支付股利 6.34 亿元（2025 年度分红）。

- [http://static.cninfo.com.cn/finalpage/2026-09-04/1225545929.PDF](http://static.cninfo.com.cn/finalpage/2026-09-04/1225545929.PDF)
  股东减持股份结果公告（巨潮，2026-09-04）：持股 5% 以上股东黄旭（非实控人，IPO 前股份）于 2026-06-04 至 09-03 累计减持 642.993 万股（1.52%），其中集中竞价 420.723 万股、大宗交易 222.27 万股，价格区间 163.82-233.20 元，套现 11.98 亿元，均价约 186.3 元，计划已执行完毕。剩余持股 5600.007 万股（13.23%）。目前未检索到新的减持计划。巨潮检索显示，黄旭曾在 2024-05-15、2025-05-21、2026-05-13 三次披露减持计划，形成每年 5 月披露的规律。

- [http://static.cninfo.com.cn/finalpage/2026-07-22/1225435909.PDF](http://static.cninfo.com.cn/finalpage/2026-07-22/1225435909.PDF)
  2026 年股票期权与限制性股票激励计划首次授予结果公告（2026-07-22）及草案摘要（2026-05-26）：2026-07-20 登记股票期权 457.50 万份，行权价 159.00 元，授予 239 人，占总股本 1.08%；限制性股票 20 万股未完成登记。股份支付总费用 1.419 亿元，其中 2026 年 0.387 亿元、2027 年 0.603 亿元、2028 年 0.322 亿元、2029 年 0.107 亿元。业绩考核（草案 http://static.cninfo.com.cn/finalpage/2026-05-26/1225329912.PDF）：2026、2027、2028 年营收或净利同比增长不低于 20%。2026 年前三季度已 +41.6%/+70.9%，门槛偏低，行权确定性高。2026-10-27 另公告注销 2024 年计划期权 1.6 万份（1 人离职），影响可以忽略。

- [https://pollen-robotics.com/microduck/](https://pollen-robotics.com/microduck/)
  Pollen Robotics（Hugging Face 旗下）Microduck 官方页面；AIBase 报道：Microduck 是 Hugging Face 旗下法国 Pollen Robotics 于 2026-08-27 发布的 25cm 开源双足强化学习机器人，配备 15 个电机、摄像头、ToF、双 IMU，售价 399 美元。AIBase（https://news.aibase.com/news/30705）报道其主控为瑞芯微 RK3566，以 50Hz 控制 15 个舵机。公司在业绩预告和三季报中以它为「新质生产力爆品」的例子。

- [https://data.eastmoney.com/report/info/AP202610281831106006.html](https://data.eastmoney.com/report/info/AP202610281831106006.html)
  东吴证券三季报点评（东方财富研报中心，2026-10-28）：维持「买入」，2026-2028 年营收预测 66.03/81.22/101.52 亿元，归母净利 18.07/22.05/27.39 亿元（2027-2028 年由 21.88/26.99 亿元上调），EPS 4.27/5.21/6.47 元。由此推算隐含 Q4 营收 21.54 亿元、Q4 净利 4.75 亿元（与 Q3 基本持平，Q4 利润率假设偏保守）。同日华金证券给出 EPS 4.29/5.68 元（东财研报列表）。

- [https://web.ifzq.gtimg.cn/appstock/app/fqkline/get?param=sh603893,day,2026-07-20,2026-10-30,80,qfq](https://web.ifzq.gtimg.cn/appstock/app/fqkline/get?param=sh603893,day,2026-07-20,2026-10-30,80,qfq)
  腾讯证券前复权日 K（2026-07-20 至 10-29）：事件日涨跌：2026-08-18 半年报 -6.36%，次日 -8.05%；08-31 +10.00%（涨停，原因未检索到；Microduck 发布于 08-27）；09-22 +10.00%；10-16 业绩预告日 -9.99%；10-20 +10.00%；10-23 +8.76%；10-27 三季报 -8.18%；10-28 +6.90%；10-29 -7.86%；10-30 -5.94%。90 天内出现 5 次 ±10% 涨跌停，日波动常在 ±8% 左右，事件驱动和交易拥挤特征明显。

- [https://sns.sseinfo.com/company.do?uid=156557](https://sns.sseinfo.com/company.do?uid=156557)
  上证 e 互动 瑞芯微（uid=156557）：答复接口（https://sns.sseinfo.com/ajax/userfeeds.do?typeCode=company&type=11&pageSize=30&uid=156557&page=1）返回「近 1 个月暂无回复」。公司近期没有通过 e 互动释放增量信息，新品节奏只能以定期报告和公告措辞为准。

- [https://datacenter-web.eastmoney.com/api/data/v1/get?reportName=RPT_LIFT_STAGE&columns=ALL&filter=(SECURITY_CODE=%22603893%22)&sortColumns=FREE_DATE&sortTypes=-1&pageSize=8](https://datacenter-web.eastmoney.com/api/data/v1/get?reportName=RPT_LIFT_STAGE&columns=ALL&filter=(SECURITY_CODE=%22603893%22)&sortColumns=FREE_DATE&sortTypes=-1&pageSize=8)
  东方财富限售解禁数据；巨潮业绩预告历史：下一次解禁为 2027-05-21，股权激励限售股 4.8 万股，约 858 万元；2026-10-30 至 12-29 无解禁。年度业绩预告历史披露日：2024-01-24、2025-01-21、2026-01-27（例：http://static.cninfo.com.cn/finalpage/2026-01-27/1224949635.PDF），2026 年报预告大概率在 2027 年 1 月下旬，落在 60 天窗口之外。

## 行业与竞争

- [http://static.cninfo.com.cn/finalpage/2026-08-18/1225478618.PDF](http://static.cninfo.com.cn/finalpage/2026-08-18/1225478618.PDF)
  瑞芯微 2026 年半年度报告（巨潮资讯）：H1 营收 28.77 亿元，其中智能应用处理器芯片 26.00 亿元（占 90.37%），数模混合芯片 2.16 亿元，其他芯片 0.36 亿元。主控线：RK3588/RK3576/RV11 系列持续高增长；RK3572（八核 CPU、4TOPS NPU、支持 LPDDR5/5x/4/4x）于 2026 年 5 月发布，导入平板、AI 摄像头、NAS、零售、数字标牌；RK3538 导入海外 IPTV/OTT 客户；RK36 系列为下一代旗舰。协处理器 RK182X 已有数百个客户、几十个行业在研，首批量产客户包括高端电视、商用清洁机器人、陪伴机器人、NAS。汽车：累计赋能上百款量产车型，车载 AI BOX 超 20 个在研项目。机器人：公司自称是国内覆盖机器人品类最多、客户范围最广的芯片厂商。经营模式为经销为主、直销为辅。

- [https://www.grandviewresearch.com/industry-analysis/edge-artificial-intelligence-chips-market](https://www.grandviewresearch.com/industry-analysis/edge-artificial-intelligence-chips-market)
  Grand View Research：Edge AI Chips Market Report 2026-2033：全球边缘 AI 芯片市场 2025 年 273 亿美元，2026 年 362 亿美元，预计 2033 年 2918 亿美元，2026-2033 年 CAGR 34.7%。这是口径最宽的估计。

- [https://www.precedenceresearch.com/edge-artificial-intelligence-chips-market](https://www.precedenceresearch.com/edge-artificial-intelligence-chips-market)
  Precedence Research / Fortune Business Insights：边缘 AI 芯片/处理器市场：Precedence Research 估计 2026 年 97.7 亿美元，2034 年 361.2 亿美元，CAGR 17.75%。Fortune Business Insights（https://www.fortunebusinessinsights.com/edge-ai-processor-market-114310）估计边缘 AI 处理器 2026 年 36.8 亿美元，2034 年 135.4 亿美元，CAGR 17.69%。各机构口径相差约 10 倍，较稳健的共识是 CAGR 约 18%-35%。

- [https://www.cnx-software.com/2025/12/30/rockchip-rk1820-rk1828-so-dimm-and-m-2-llm-vlm-ai-accelerator-modules-devkits-and-benchmarks/](https://www.cnx-software.com/2025/12/30/rockchip-rk1820-rk1828-so-dimm-and-m-2-llm-vlm-ai-accelerator-modules-devkits-and-benchmarks/)
  CNX Software：RK1820/RK1828 模组与基准测试；Firefly RK1828 文档：RK1820 内置 2.5GB DRAM，面向 3B 参数模型；RK1828 内置 5GB DRAM，面向 7B 参数模型；两者均于 RKDC 2025（2025 年 7 月）发布。Firefly 文档（https://community.t-firefly.com/en/docs/products/accessories/RK1828/started）标注 RK1828 为 20 TOPS INT8，采用 3D 堆叠 DRAM。RK182X 内置 DRAM，存储涨价会推高其 BOM 成本；公司称 KGD 内置存储占比很小，指的是整体产品结构。

- [https://linuxgizmos.com/rockchip-rk3668-targets-edge-ai-with-44-tops-npu-and-pcie-5-0/](https://linuxgizmos.com/rockchip-rk3668-targets-edge-ai-with-44-tops-npu-and-pcie-5-0/)
  LinuxGizmos：Rockchip RK3668 Targets Edge AI with 44 TOPS NPU（引 Radxa 应用简报）：RK3668 采用 6nm 工艺，CPU 为 6×A725+2×A520，GPU 为 Mali-G2 Pro MC4（约 1.23 TFLOPS），NPU 44 TOPS（稀疏 INT8），支持 LPDDR6（理论带宽 128GB/s）、PCIe 5.0、双 10GbE；目标应用为 NAS、机器人、PLC、座舱、NVR。工程样品目标为 2027 年 Q1，价格与量产时间未公布。这与公司「马上投产」的表述存在时间差：投产可能指流片或投片，营收贡献大概率在 2027 年。

- [https://www.trendforce.com/presscenter/news/20260930-13258.html](https://www.trendforce.com/presscenter/news/20260930-13258.html)
  TrendForce：4Q26 存储合约价预测（2026-09-30）及 2026-10-30 Specialty DRAM 报告摘要：受 AI 服务器需求支撑，4Q26 常规 DRAM 合约价预计环比 +10%-15%，消费端压力持续。10 月 Specialty DRAM 报告（https://www.trendforce.com/research/download/RP261030HH）指出，消费 DRAM 供给仍紧，但年底观望情绪和高存储成本拖慢需求，合约价涨幅收窄至持平或小涨，现货价已从高点回落。对 AIoT 终端而言，Q4 存储成本压力仍在，但边际增速放缓。

- [https://www.mpbxchange.com/ja/research/pcb-material-shortage-2026-glass-cloth-copper-foil](https://www.mpbxchange.com/ja/research/pcb-material-shortage-2026-glass-cloth-copper-foil)
  MPBxChange：PCB 材料不足 2026（玻纤布、铜箔、基板）：据 2026 年 10 月中旬前的资料：建滔报告上半年玻纤布短缺导致部分覆铜板厂局部停产；标准 FR-4 覆铜板交期从数日延长至约 4 周，建滔在 2025 年至 2026 年 7 月间提价 10 次；2026 年 Q3 LME 铜均价同比约 +44%；日东纺新产能 2027 年初投产，规模供应在 2027 年中后期。这与公司所述 Q3 PCB 交期拉长、碎片化 AIoT 终端受影响更大的情况一致，PCB 紧张可能延续到 2027 年。

- [https://www.edge-ai-vision.com/2026/06/introducing-the-qualcomm-dragonwing-iq10-rrd-a-full-stack-robotics-reference-design/](https://www.edge-ai-vision.com/2026/06/introducing-the-qualcomm-dragonwing-iq10-rrd-a-full-stack-robotics-reference-design/)
  Edge AI and Vision Alliance / Futurum：高通 Dragonwing 机器人与工业 IoT 产品线：高通 Dragonwing IQ10 机器人参考设计在 Computex 2026 发布，生态伙伴包括 Radxa、研华、Thundercomm 等；Radxa 同时是瑞芯微核心板的主要生态伙伴。2026 年 9 月 1 日，高通又发布面向低成本边缘的 Q-2390/IQ-2390（https://futurumgroup.com/insights/what-qualcomms-focus-at-ifa-berlin-signals-about-the-companys-intelligent-edge-strategy/）。高通正从高端向中低端 AIoT 下沉，与 RK3576/RK3588 档位直接竞争，并争夺同一批板卡厂。

- [https://data.eastmoney.com/report/info/AP202608251828408776.html](https://data.eastmoney.com/report/info/AP202608251828408776.html)
  山西证券首次覆盖点评（东方财富研报中心，2026-08-25）：2026H1 毛利率 45.79%，同比 +3.5pct，其中 SoC 毛利率同比 +4.27pct 至 46%；Q2 毛利率环比 +4.73pct。券商将其归因于生态卡位带来的涨价传导、ASP 提升和提前备货。风险提示指出，主力与旗舰芯片依赖 8nm 及以下先进工艺和海外晶圆厂产能。

- [https://datacenter-web.eastmoney.com/api/data/v1/get?reportName=RPT_LICO_FN_CPD&columns=SECURITY_CODE,SECURITY_NAME_ABBR,REPORTDATE,TOTAL_OPERATE_INCOME,YSTZ,PARENT_NETPROFIT,SJLTZ,NOTICE_DATE,XSMLL&filter=(SECURITY_CODE=%22603893%22)&sortColumns=REPORTDATE&sortTypes=-1&pageSize=2](https://datacenter-web.eastmoney.com/api/data/v1/get?reportName=RPT_LICO_FN_CPD&columns=SECURITY_CODE,SECURITY_NAME_ABBR,REPORTDATE,TOTAL_OPERATE_INCOME,YSTZ,PARENT_NETPROFIT,SJLTZ,NOTICE_DATE,XSMLL&filter=(SECURITY_CODE=%22603893%22)&sortColumns=REPORTDATE&sortTypes=-1&pageSize=2)
  东方财富数据中心业绩报表（同行 2026 年三季报）：前三季度营收增速与毛利率：瑞芯微 +41.6%/46.4%；全志 +29.5%/43.2%；晶晨 +40.7%/41.9%；恒玄 -26.8%/42.3%；星宸 +111.2%/57.8%。瑞芯微营收规模 44.5 亿元，低于晶晨 71.4 亿元和星宸 45.8 亿元，但毛利率高于全志和晶晨，净利 13.32 亿元仅次于星宸 15.64 亿元。端侧 SoC 板块整体景气，恒玄所在的可穿戴/音频链条除外。

## 成本与原材料

- [https://pdf.dfcfw.com/pdf/H2_AN202604141821197102_1.pdf?1776197958000.pdf](https://pdf.dfcfw.com/pdf/H2_AN202604141821197102_1.pdf?1776197958000.pdf)
  瑞芯微2025年年度报告·成本分析表：集成电路营业成本25.55亿元，其中晶圆17.39亿元占68.05%（2024年67.65%），加工费（封装、测试）6.04亿元占23.63%（2024年22.90%），其他2.13亿元占8.32%。公司为Fabless模式，晶圆制造、封装、测试均委托代工。前五名供应商采购额26.11亿元，占年度采购总额79.62%，未披露供应商名称。

- [https://jisaku.com/glossary/rk3576-sbc](https://jisaku.com/glossary/rk3576-sbc)
  jisaku.com RK3576词条（第三方，搜索摘要）：第三方资料称RK3576采用三星8nm工艺制造。8nm属三星8LPP节点，台积电无8nm节点；据此推断8nm平台主要由三星代工，属间接证据，公司未确认。

- [https://www.tomshardware.com/tech-industry/samsung-raises-advanced-foundry-prices-by-up-to-15-percent-as-ai-demand-fills-its-4nm-lines](https://www.tomshardware.com/tech-industry/samsung-raises-advanced-foundry-prices-by-up-to-15-percent-as-ai-demand-fills-its-4nm-lines)
  Tom's Hardware（2026-08）：三星7月对4nm、5nm、8nm新订单涨价，对中美客户最高15%；受美国出口管制影响的中国芯片设计公司接受了最大涨幅。

- [https://pdf.dfcfw.com/pdf/H2_AN202610261830950116_1.pdf?1793050350000.pdf](https://pdf.dfcfw.com/pdf/H2_AN202610261830950116_1.pdf?1793050350000.pdf)
  瑞芯微2026年第三季度报告：前三季度营收44.49亿元（+41.64%），营业成本23.86亿元（占收入53.6%），综合毛利率46.37%；单季营收15.73亿元，按H1与前三季度差额推算Q3单季毛利率约47.4%。公司称产品结构中内置存储（KGD）比例很小；Q3 PCB原材料短缺、交期拉长，PCB延迟交付影响终端生产，芯片订单滞后顺延，预计四季度恢复。存货由2025年末12.54亿元增至18.84亿元。

- [https://pdf.dfcfw.com/pdf/H2_AN202608171828061362_1.pdf?1786996643000.pdf](https://pdf.dfcfw.com/pdf/H2_AN202608171828061362_1.pdf?1786996643000.pdf)
  瑞芯微2026年半年度报告：上半年存储延续短缺、价格暴涨，芯片基板、玻纤布、PCB、阻容全面紧缺、涨价；公司预计未来几个季度上述原材料供应仍大幅承压，持续战略性备货，6月末存货15.18亿元，以中高端产品和新品为主。

- [https://emweb.securities.eastmoney.com/PC_HSF10/BusinessAnalysis/PageAjax?code=SH603893](https://emweb.securities.eastmoney.com/PC_HSF10/BusinessAnalysis/PageAjax?code=SH603893)
  东方财富F10主营构成（来源为定期报告）：2026H1智能应用处理器芯片收入26.00亿元、成本14.12亿元、毛利率45.70%（2025H1为41.42%）；数模混合芯片收入2.16亿元、毛利率42.09%（2025全年48.01%）。处理器毛利率在晶圆涨价期内仍提升约4.3个百分点。

- [https://www.trendforce.com/presscenter/news/20260703-13134.html](https://www.trendforce.com/presscenter/news/20260703-13134.html)
  TrendForce新闻稿（2026-07-03）：3Q26常规DRAM合约价预计环比+13%-18%，NAND Flash合约价+10%-15%；PC、手机等消费端客户已接近承受上限。

- [https://www.trendforce.com/presscenter/news/20260331-12995.html](https://www.trendforce.com/presscenter/news/20260331-12995.html)
  TrendForce新闻稿（2026-03-31）：2Q26常规DRAM合约价预计环比上涨58%-63%。

- [https://www.pcbgogo.jp/Article/pcb-price-increase.html](https://www.pcbgogo.jp/Article/pcb-price-increase.html)
  PCBGOGO《PCB价格上昇の原因》：2026年标准PCB基材同比上涨20%-30%；韩国海关数据显示2026年3月覆铜板（CCL）进口价超过2万美元/吨，同比约+75%；原材料约占PCB成本60%，CCL占1/4以上；先进层压板交期最长140天。

## 大宗与期货替代指标

- [https://news.metal.com/en/newscontent/104186849-us-economic-resilience-strengthens-rate-hike-expectations-copper-prices-consolidate-under-pressure-smm-copper-morning-meeting-summary](https://news.metal.com/en/newscontent/104186849-us-economic-resilience-strengthens-rate-hike-expectations-copper-prices-consolidate-under-pressure-smm-copper-morning-meeting-summary)
  SMM铜晨会纪要（2026-10-29）：LME铜开盘14,350美元/吨，最高14,491，收盘14,352美元/吨，跌0.96%，持仓26.2万手。

- [https://www.kitco.com/news/off-the-wire/2026-10-22/copper-price-falls-five-week-low-lme-inventory-build-continues](https://www.kitco.com/news/off-the-wire/2026-10-22/copper-price-falls-five-week-low-lme-inventory-build-continues)
  Kitco/Reuters（2026-10-22）：LME三个月铜跌1.8%至14,089美元/吨，盘中低点14,031美元，为9月15日以来最低。

- [https://www.trendforce.com/news/2026/10/28/insights-memory-spot-price-update-nand-spot-price-cuts-accelerate-amid-china-phone-discounts-512gb-tlc-sink-9-19/](https://www.trendforce.com/news/2026/10/28/insights-memory-spot-price-update-nand-spot-price-cuts-accelerate-amid-china-phone-discounts-512gb-tlc-sink-9-19/)
  TrendForce现货价周报（2026-10-28）：主流DDR4 1Gx8 3200现货均价由10月21日46.79美元升至10月27日47.04美元（+0.55%）；512Gb TLC晶圆现货价周跌9.19%至16.883美元。

- [https://www.trendforce.com/research/download/RP261030HH](https://www.trendforce.com/research/download/RP261030HH)
  TrendForce Specialty DRAM Price Oct. 2026：消费型DRAM供应仍紧，但年末谨慎和高存储成本使需求放缓，合约价涨幅收窄至持平到小涨；现货价自高点回落并与合约价脱钩。

- [https://www.mining.com/web/gold-slides-as-higher-us-inflation-reinforces-fed-tightening-bets/](https://www.mining.com/web/gold-slides-as-higher-us-inflation-reinforces-fed-tightening-bets/)
  Mining.com/Reuters金价（2026-10）：现货金跌1.4%至4,008.76美元/盎司，12月期金收于4,031.40美元/盎司。

- [https://discoveryalert.com/analysis/gold-correction-2027-rebound-october-2026/](https://discoveryalert.com/analysis/gold-correction-2027-rebound-october-2026/)
  DiscoveryAlert转述路透（2026-10-26）：现货金10月26日为4,020.60美元/盎司，1月纪录为5,595美元，较纪录高点回落约28%。

- [https://finance.yahoo.com/technology/ai/articles/chip-index-sox-posts-longest-123436535.html](https://finance.yahoo.com/technology/ai/articles/chip-index-sox-posts-longest-123436535.html)
  Yahoo Finance（2026-10）：费城半导体指数跌3.83%至11,137.29点，连跌8个交易日，为2008年10月以来最长，较10月6日累计下跌16%。

## 宏观

- [http://static.cninfo.com.cn/finalpage/2026-04-15/1225103780.PDF](http://static.cninfo.com.cn/finalpage/2026-04-15/1225103780.PDF)
  瑞芯微2025年年度报告（巨潮资讯）：2025年境外收入19.49亿元，占主营44.28%，毛利率42.73%；境内24.52亿元(55.70%)。营业成本中晶圆17.39亿元，占总成本68.05%，加工费6.04亿元(23.63%)。年末美元货币资金4,625万美元、美元应收2,199万美元、美元应付4,425万美元（折算汇率7.0288）。年报未披露具体晶圆代工厂名称，前五名供应商采购占比79.62%。

- [https://www.trendforce.com/presscenter/news/20260907-13219.html](https://www.trendforce.com/presscenter/news/20260907-13219.html)
  TrendForce 2Q26 DRAM营收报告：2Q26 DRAM产业营收环比+59.5%；常规DRAM合约价涨幅预计放缓至13–18% QoQ，PC与手机客户进一步消化涨价的能力有限。

- [https://www.trendforce.com/presscenter/news/20260601-13070.html](https://www.trendforce.com/presscenter/news/20260601-13070.html)
  TrendForce 1Q26 DRAM营收报告：1Q26 DRAM产业营收环比+81%，预计2Q26常规DRAM合约价再涨58–63% QoQ。

- [https://www.idc.com/resource-center/blog/the-tablet-market-hits-a-wall/](https://www.idc.com/resource-center/blog/the-tablet-market-hits-a-wall/)
  IDC：Worldwide Tablet Shipments Fall 12.3% in Q2 2026：2026Q2全球平板出货同比-12.3%；三星4月全线Galaxy Tab提价40–280美元，联想提价30–70美元，存储涨价直接传导至终端价格。

- [https://counterpointresearch.com/en/insights/Smartphone-Shipments-in-2026-to-See-Sharpest-Decline-on-Record-as-Memory-Crisis-deepens](https://counterpointresearch.com/en/insights/Smartphone-Shipments-in-2026-to-See-Sharpest-Decline-on-Record-as-Memory-Crisis-deepens)
  Counterpoint：2026年智能手机出货将创纪录下滑：存储短缺与零部件涨价拖累2026年出货并延续至2027年，预计2027年末新增存储产能释放后才恢复。

- [https://tradingeconomics.com/china/interest-rate/news/593249](https://tradingeconomics.com/china/interest-rate/news/593249)
  Trading Economics：China Holds LPR Rates at Record Lows for 17th Month：2026年10月LPR连续第17个月维持历史低位（1年期3.00%、5年期以上3.50%），人民币同期走强。

- [https://en.sedaily.com/international/2026/10/28/china-pumps-record-1-trillion-yuan-in-a-day-driving-5-year](https://en.sedaily.com/international/2026/10/28/china-pumps-record-1-trillion-yuan-in-a-day-driving-5-year)
  Seoul Economic Daily：China Pumps Record 1 Trillion Yuan in a Day：2026-10-28中国10年期国债收益率降至1.615%，30年期2.052%，央行单日投放流动性创纪录。

- [https://www.worldgovernmentbonds.com/spread/united-states-10-years-vs-china-10-years/](https://www.worldgovernmentbonds.com/spread/united-states-10-years-vs-china-10-years/)
  World Government Bonds：US 10Y vs China 10Y spread：美国10年期国债收益率5.131%，中国10年期1.618%，中美利差约351bp。

- [https://note.com/china_case/n/n018986656035](https://note.com/china_case/n/n018986656035)
  CHINA CASE：中国2026年9月PMI：国家统计局2026-09-30公布9月制造业PMI 50.1，较8月49.8回升0.3点；生产加速但价格上涨、就业偏弱。

- [https://www.exchange-rates.org/zh/exchange-rate-history/cny-usd-2026](https://www.exchange-rates.org/zh/exchange-rate-history/cny-usd-2026)
  exchange-rates.org：2026年CNY/USD历史汇率：页面统计2026年内CNY/USD上升4.52%（页面时点约2026年5月，非10月30日收盘口径；10月30日汇率未检索到）。

- [https://www.trendforce.com/news/2025/02/08/news-tsmc-reportedly-halts-1416nm-chip-shipments-to-chinese-ic-firms-unless-packaged-by-approved-osats/](https://www.trendforce.com/news/2025/02/08/news-tsmc-reportedly-halts-1416nm-chip-shipments-to-chinese-ic-firms-unless-packaged-by-approved-osats/)
  TrendForce：TSMC Reportedly Halts 14/16nm Chip Shipments to Chinese IC Firms：自2025-01-31起，台积电对中国IC设计公司16/14nm及以下产品，除非由BIS认可的OSAT封装并提供证明，否则停止出货。

- [https://www.cnblogs.com/cbd7788/articles/23419552](https://www.cnblogs.com/cbd7788/articles/23419552)
  米尔RK3588开发板介绍（博客园）：RK3588采用8nm制程，四核A76+四核A55，NPU 6TOPS。代工厂名称未在公司公告中检索到。

## 政策与监管

- [https://www.gov.cn/zhengce/content/202508/content_7037861.htm](https://www.gov.cn/zhengce/content/202508/content_7037861.htm)
  中国政府网：国务院关于深入实施“人工智能+”行动的意见（国发〔2025〕11号）：到2027年新一代智能终端、智能体等应用普及率超70%，2030年超90%；明确大力发展智能网联汽车、AI手机和电脑、智能机器人、智能家居、智能穿戴等新一代智能终端，并支持人工智能芯片攻坚创新与使能软件生态培育。

- [https://www.deloitte.com/content/dam/assets-zone1/cn/en/docs/services/tax/2024/deloitte-cn-tax-taxnewsflash-bilingual-201231.pdf](https://www.deloitte.com/content/dam/assets-zone1/cn/en/docs/services/tax/2024/deloitte-cn-tax-taxnewsflash-bilingual-201231.pdf)
  德勤税务快讯：财政部等四部门2020年第45号公告解读：财政部、税务总局、发改委、工信部2020年第45号公告调整国家鼓励的集成电路和软件企业所得税优惠，符合条件企业自2020年起适用新政策；重点集成电路设计企业的具体税率条款未在该检索片段中核实，公司公告亦未披露适用重点企业优惠。

- [https://ustr.gov/sites/default/files/files/Issue_Areas/Enforcement/Section%20301/Semiconductor%20Section%20301%20FRN%20Final%20Action%2012-22-25%20for%20posting.pdf](https://ustr.gov/sites/default/files/files/Issue_Areas/Enforcement/Section%20301/Semiconductor%20Section%20301%20FRN%20Final%20Action%2012-22-25%20for%20posting.pdf)
  USTR：Section 301半导体最终行动公告（2025-12-22）：USTR认定中国半导体政策可诉，对中国半导体加征关税初始税率0%，2027-06-23起上调，税率将在不少于30天前公布。

- [https://www.congress.gov/crs-product/IF12958](https://www.congress.gov/crs-product/IF12958)
  美国国会研究服务处CRS IF12958（2026-08-20）：总结Section 301成熟制程芯片调查：维持0%至2027年6月，同时寻求与中国达成贸易协议。

- [https://www.aacb.com/trade-tariff-news/guidance-for-section-232-import-duties-on-semiconductors-and-their-derivative-products](https://www.aacb.com/trade-tariff-news/guidance-for-section-232-import-duties-on-semiconductors-and-their-derivative-products)
  CBP/AACB：Section 232半导体进口关税指引：2026-01-14公告依据Section 232对满足特定性能参数的半导体及衍生品征收25%从价关税，自1月15日生效，针对先进计算芯片。

- [https://www.wsgr.com/en/insights/new-bis-rule-expands-export-controls-and-due-diligence-requirements-for-advanced-computing-integrated-circuits.html](https://www.wsgr.com/en/insights/new-bis-rule-expands-export-controls-and-due-diligence-requirements-for-advanced-computing-integrated-circuits.html)
  Wilson Sonsini：BIS新规扩大先进计算IC尽调要求：前道晶圆厂和OSAT须推定以16/14nm及以下或非平面晶体管架构生产的逻辑IC符合ECCN 3A090参数，需尽调或许可。

- [https://media.bis.gov/](https://media.bis.gov/)
  BIS官网：2026-04-07 BIS将相关时间表延长至2026-12-31，以便企业提交Approved IC Designer申请。

- [https://www.globaltimes.cn/page/202509/1343443.shtml](https://www.globaltimes.cn/page/202509/1343443.shtml)
  Global Times：中国商务部对美模拟芯片反倾销调查：商务部2025年第27号公告自2025-09-13对原产于美国的部分模拟芯片（通用接口芯片、栅极驱动芯片）发起反倾销调查，同时发起反歧视调查。

- [https://note.com/osschina/n/n4943ed306d7b](https://note.com/osschina/n/n4943ed306d7b)
  note.com中尾貴光：智能网联新能源汽车产业发展“十五五”规划：2026-09-10工信部等9部门发布《智能网联新能源汽车产业发展“十五五”规划》，确定至2030年汽车产业方向。

- [https://note.com/zhenren63/n/n477adeea5a03](https://note.com/zhenren63/n/n477adeea5a03)
  note.com吉川真人：人形机器人与具身智能标准体系（2026版）：2026-02-28工信部人形机器人与具身智能标准化技术委员会发布《人形机器人与具身智能标准体系（2026版）》。

- [https://www.whitehouse.gov/fact-sheets/2026/10/fact-sheet-president-donald-j-trump-adjusts-imports-of-robotics-industrial-machinery-and-their-parts-and-components-into-the-united-states/](https://www.whitehouse.gov/fact-sheets/2026/10/fact-sheet-president-donald-j-trump-adjusts-imports-of-robotics-industrial-machinery-and-their-parts-and-components-into-the-united-states/)
  White House：Section 232 Robotics/Industrial Machinery Fact Sheet（2026-10）：2026年10月美国依据Section 232调整机器人、工业机械及零部件进口，涉及中国机器人整机出口美国的间接需求。

- [https://www.cnblogs.com/deepagents/articles/21330808](https://www.cnblogs.com/deepagents/articles/21330808)
  博客园：国产工控一体机推荐（瑞迅科技）：信创政策与端侧AI普及下，基于瑞芯微RK、华为昇腾架构的国产工控一体机逐步替代海外进口硬件。

## 局限

- 代工厂按8nm节点推断为三星，公司未披露；晶圆涨价入成本时点按存货周转推算。
- PE/PB 5年分位、资金流、舆情接口未取到；舆情为0属数据缺失。
- 脚本风格识别为“量化因子型”（48只量化基金前十大持仓含本股），本报告按高成长科技解读，未改脚本加权。
- 基期FCF 12亿、beta 1.3为假设，DCF三档仅作情景。

## 三季报解读补充（2026-10-30收盘后）

- [http://static.cninfo.com.cn/finalpage/2026-10-27/1225627336.PDF](http://static.cninfo.com.cn/finalpage/2026-10-27/1225627336.PDF)
  正式三季报（未经审计）原文：资产负债表、利润表、现金流量表累计数；Q3单季由此减半年报累计得出。截至10-30东财公告列表无更新的定期报告。

- [http://static.cninfo.com.cn/finalpage/2026-08-18/1225478618.PDF](http://static.cninfo.com.cn/finalpage/2026-08-18/1225478618.PDF)
  半年报累计数：营收28.77亿、营业成本15.59亿、经营现金流8.00亿、资本开支1.67亿、分红支付1.26亿、存货15.18亿、应付账款7.13亿。

- [https://web.ifzq.gtimg.cn/appstock/app/fqkline/get?param=sh603893,day,2025-06-01,2026-10-30,400,qfq](https://web.ifzq.gtimg.cn/appstock/app/fqkline/get?param=sh603893,day,2025-06-01,2026-10-30,400,qfq)
  前复权日K，截至10-29；10-30按收盘行情补入后计算MA5至MA200。

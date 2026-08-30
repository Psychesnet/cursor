# Rocket Lab (NASDAQ: RKLB) 現代價值投資報告

**資料截止：2026-08-25**  
**基準股價：$68.28（2026-08-24 收盤）**  
**市值：約 $437 億（implied shares 639.4M × $68.28）；流通普通股 598.5M 對應約 $409 億**  
**企業價值：約 $413 億（市值 − 淨現金約 $237 億）**  
**財年：曆年制（FY2025 = 2025-01-01 至 2025-12-31）**  
**最新實數：FY2025 年報、Q2 2026（截至 2026-06-30）**

> 本報告依「熟悉度 → 增長 → 估值 → 盈利 → 護城河 → 風險 → 綜合判斷」架構整理，只收錄可核對的財務與市場數據，不放百科式公司介紹。金額除非另註均為美元。本報告僅供參考，非投資建議。

---

## 1. Known｜熟悉度評估

**商業模式清晰度：中高。** 兩個報告部門（Launch Services / Space Systems）可從 10-K 對上金額、毛利與客戶集中度；但「發射服務」與「衛星製造」的認列節奏不同（Electron 多為發射時點認列、HASTE 與多數衛星合約為 overtime），單季營收波動大，不能用發射次數直接外推當季營收。

### 1.1 業務模式與產業鏈位置

Rocket Lab 不是純發射商，而是**垂直整合的上游航太製造 + 發射營運商**，正在向「發射 → 造星 → 操作星座」延伸。

| 層級 | 角色 | 對應產品 / 能力 | 產業鏈位置 |
| --- | --- | --- | --- |
| 發射（服務） | 把客戶載荷送上軌道或亞軌道 | Electron（≤300 kg LEO）、HASTE（高超音速亞軌道試驗）、開發中的 Neutron（可回收中型，約 13 t 可回收 LEO） | 發射服務商；與 SpaceX / ULA / Blue Origin / Firefly 競爭 |
| 衛星平台（產品） | 設計、製造整星並可在軌操作 | Photon、Flatellite、SDA Tracking Layer 衛星、GEO 衛星 | 從零件商升級為「新進 prime」 |
| 組件（產品） | 賣給其他衛星製造商的高值子系統 | 太陽能陣列（SolAero）、光學載荷（GEOST / OSI）、反應輪、星敏、雷射通訊（Mynaric）、推進、航電 | 上游供應商，有跨發射商的商譽收入 |
| 基礎設施 | 自有發射場與產線 | 紐西蘭 LC-1（私有，最多 120 次/年機會）、Virginia LC-2 / LC-3、Long Beach 引擎、Auckland 複合材 | 控制發射時程，不是租用公共發射槽的純服務商 |
| 應用層（尚未交割） | 自有星座服務營收 | 已宣布收購 Iridium（企業價值約 $80 億，目標 2027 年中交割） | 若完成，才真正進入衛星通訊訂閱 |

**產業鏈一句話：** 在「小型專屬發射」已證明可量產；在「衛星製造 / 國防星座」用垂直整合搶傳統 prime 的固定價格合約；Neutron 是從 300 kg 小火箭跨到 Falcon 9 級別運力的賭注；Iridium 則是把硬體公司變成有經常性收入的太空營運商。

資料：[FY2025 10-K](https://investors.rocketlabcorp.com/static-files/57a8d0da-27ff-499c-8d85-18907743b7a8)、[FY2025 Q4 新聞稿](https://investors.rocketlabcorp.com/news-releases/news-release-details/rocket-lab-announces-fourth-quarter-and-full-year-2025-financial)、[Iridium 交易新聞稿](https://www.prnewswire.com/news-releases/rocket-lab-to-acquire-iridium-in-historic-deal-creating-a-fully-vertically-integrated-space-powerhouse-primed-for-growth-302813075.html)

### 1.2 收入來源：部門、產品 vs 服務

**兩大報告部門（FY2025）**

| 部門 | 營收 | 佔比 | YoY | 毛利 | 毛利率 | 增量貢獻 |
| --- | --- | --- | --- | --- | --- | --- |
| Space Systems | **$402.8M** | **66.9%** | **+29.6%** | $125.9M | **31.3%** | +$91.9M，約 55% 的增量 |
| Launch Services | **$199.0M** | **33.1%** | **+58.8%** | $81.3M | **40.8%** | +$73.7M，約 45% 的增量 |
| **合計** | **$601.8M** | 100% | **+38.0%** | **$207.2M** | **34.4%** | +$165.6M |

對照 2024：Launch $125.4M、Space Systems $310.8M。發射毛利率從 2024 的 27.6% 拉到 40.8%；衛星系統從 26.2% 拉到 31.3%。發射是較高毛利、較波動的業務；衛星系統是較大基數、較平滑的 overtime 收入。

資料：[10-K Note 20 分部表](https://investors.rocketlabcorp.com/static-files/57a8d0da-27ff-499c-8d85-18907743b7a8)、[Via Satellite 對同一組數字的解讀](https://www.satellitetoday.com/finance/2026/02/27/rocket-lab-hits-record-revenue-in-25-but-delays-neutron-to-late-26/)

**產品 vs 服務（認列口徑，不是部門口徑）**

| | FY2025 | 佔比 | Q2 2026 | 佔比 |
| --- | --- | --- | --- | --- |
| Product（幾乎全是 Space Systems 硬體） | $371.6M | 61.8% | $181.3M | **77.5%** |
| Service（發射 + 在軌操作等） | $230.2M | 38.2% | $52.7M | 22.5% |

Q2 2026 已變成「造星公司順便有火箭」：Space Systems **$189.5M（81%）**，Launch **$44.6M（19%）**。發射營收季減約 30%，主因是當季飛的 HASTE 任務有大量收入已在先前期間按 overtime 認列，不是發射次數崩掉。

資料：[Q2 2026 新聞稿 / 8-K](https://investors.rocketlabcorp.com/news-releases/news-release-details/rocket-lab-announces-second-quarter-2026-financial-results-posts)、[Q2 2026 財報會](https://www.fool.com/earnings/call-transcripts/2026/08/17/rocket-lab-rklb-q2-2026-earnings-call-transcript/)

### 1.3 客戶群體

這是 **B2B / 政府機構業務，沒有 B2C**。

| 類型 | 證據 | 判斷 |
| --- | --- | --- |
| **美國政府及其 prime** | 2025 年約 **47%** 營收來自美國政府、政府 prime 與分包（2024 為 33%、2023 為 31%） | 國防 / 情報 / NASA 已是第一現金流來源，且佔比在升 |
| **單一政府客戶** | 2025 年一名「Government Customer」佔營收 **28%**（2024 為 11%） | 超過 10% 門檻的唯一年內客戶；2024 的 MDA（23%）已掉到 10% 以下 |
| **前五大客戶** | 約 **49%** 營收、約 **77%** 合約 backlog | 集中度高；backlog 比營收更集中 |
| **商業星座與遙測** | BlackSky、Canon、Kinéis、Capella、Planet、OHB、Synspective、QPS 等 | 專屬小發射的核心客群，要的是軌道與時程控制，不是 SpaceX rideshare 的最低單價 |
| **地域** | 美國 **79%**、日本 **11%**、加拿大 3%、其他 7% | 2024 加拿大曾因 MDA 衝到 24%，2025 回落；美國佔比一年跳升 18 個百分點 |

應收帳款端：Lockheed Martin 佔 2025 年底 AR 的 16%。固定價格政府合約為主，成本超支由公司承擔。

資料：[10-K Note 21 客戶與地域](https://investors.rocketlabcorp.com/static-files/57a8d0da-27ff-499c-8d85-18907743b7a8)、[StockTitan 10-K 摘要](https://www.stocktitan.net/sec-filings/RKLB/10-k-rocket-lab-corp-files-annual-report-3c3674924b28.html)

**商業模式一句話：**  
用 Electron 的發射頻率與 Rutherford 引擎產線當門票，把同一批政府 / 星座客戶交叉賣整星與高值組件（SDA、Space Force Flatellite、GEO）；再用 Neutron 把客單價從「一次小發射」拉到「一次中型星座部署」。目前已經不是發射故事為主——2025 年 67%、2026 Q2 已 81% 的營收來自 Space Systems。

---

## 2. Growth｜增長分析

### 2.1 總收入與 YoY

| 期間 | 營收 | YoY | GAAP 毛利率 | 營業損益 | 淨損 |
| --- | --- | --- | --- | --- | --- |
| FY2023 | $244.6M | +15.9% | — | — | −$182.6M |
| FY2024 | $436.2M | **+78.3%** | 26.6% | −$189.8M | −$190.2M |
| **FY2025** | **$601.8M** | **+38.0%** | **34.4%** | **−$228.8M** | **−$198.2M** |
| Q1 2026 | $200.3M | +63.5% | 38.2% | — | −$45.0M |
| Q2 2026 | **$234.1M** | **+62.0%** | 36.1% | −$57.5M | −$49.3M |
| H1 2026 | $434.4M | **+62.7%** | 37.1% | −$113.5M | −$94.3M |
| TTM（Q3’25–Q2’26） | **約 $769M** | 約 +52% | 約 37% | 約 −$223M | 約 −$165M |

Q3 2026 指引：**$250–265M**（中點較 Q2 再 +10%）。若 Q4 維持相近水準，FY2026 落在共識 $953M 附近。

資料：[FY2025 新聞稿](https://investors.rocketlabcorp.com/news-releases/news-release-details/rocket-lab-announces-fourth-quarter-and-full-year-2025-financial)、[Q1 2026 新聞稿](https://investors.rocketlabcorp.com/news-releases/news-release-details/rocket-lab-announces-first-quarter-2026-financial-results)、[Q2 2026 8-K](https://www.sec.gov/Archives/edgar/data/1819994/000181999426000061/rklb-08102026ex991.htm)

**成長標準判定：**

- **達到 10% 門檻：是**（FY2025 +38%；H1 2026 +63%）
- **達到 20% 門檻：是，且遠超**（連續兩年高於 20%；2024 甚至是 +78%）

這不是「剛達標」的成長，而是營收基數還小（不到 $10 億 TTM）時的爆發段。必須同步看：營業虧損絕對值在 FY2025 仍擴大到 $229M，增長目前是用研發（Neutron）與股權融資換來的。

### 2.2 未來增長指引（3 年營收 / EPS CAGR）

公司本身**不給全年指引**，只給下一季。市場用的是分析師共識。

**華爾街共識（Yahoo Finance / StockAnalysis，約 18 位分析師，2026-08）**

| 年 | 營收共識 | 營收 YoY | GAAP EPS 共識 | 覆蓋 |
| --- | --- | --- | --- | --- |
| FY2025A | $601.8M | +38.0% | −$0.37 | 實際數 |
| **FY2026E** | **$953.3M** | **+58.4%** | **−$0.27** | 營收 18 / EPS 11 |
| **FY2027E** | **$1.36B** | **+42.3%** | **−$0.07** | 營收 17 / EPS 13 |
| FY2028E（覆蓋較少） | 約 $1.57–1.61B | 約 +16–27% | 約 +$0.29（SharesGrow，僅 4 位） | 稀疏 |

資料：[Yahoo Finance Analysis](https://finance.yahoo.com/quote/RKLB/analysis/)、[StockAnalysis Forecast](https://stockanalysis.com/stocks/rklb/forecast/)、[MarketScreener](https://ca.marketscreener.com/quote/stock/ROCKET-LAB-CORPORATION-126208072/finances/)、[SharesGrow](https://sharesgrow.com/valuation/RKLB/)

**推算 CAGR：**

| 指標 | 計算 | 結果 | 相對 20% 標準 |
| --- | --- | --- | --- |
| 營收 FY25→FY27（2 年，Yahoo 完整覆蓋） | (1.36 / 0.602)^(1/2) − 1 | **約 50.3%** | **遠超 20%** |
| 營收 FY25→FY28（3 年，MarketScreener $1.565B） | (1.565 / 0.602)^(1/3) − 1 | **約 37.5%** | **遠超 20%** |
| 營收 FY25→FY28（若 2028 接 Yahoo 路徑約 $1.72B） | (1.72 / 0.602)^(1/3) − 1 | **約 42%** | **遠超 20%** |
| GAAP EPS | 2026–2027 仍為虧損 | **無法算正 CAGR** | — |

StockAnalysis 的非 GAAP EPS 共識較樂觀（2026E −$0.05、2027E +$0.05），即使採用這組數字，2027 年也只是剛轉盈。**成長故事在營收端成立，在 EPS 端尚未成立。**

### 2.3 市場空間（TAM / 大 M / 小 M / SAM）

#### 大 M｜全球太空經濟

| 市場定義 | 規模 | 增速 | 來源 |
| --- | --- | --- | --- |
| 全球太空經濟（含 backbone + reach 應用） | 2023 **$6,300 億** → 2035 **$1.8 兆** | 約 **9% CAGR** | [WEF / McKinsey](https://www.mckinsey.com/industries/aerospace-and-defense/our-insights/space-the-1-point-8-trillion-dollar-opportunity-for-global-economic-growth) |
| 另一口徑（較窄） | 2025 **$4,498 億** → 2035 **$9,356 億** | **7.6% CAGR** | [Future Market Insights](https://www.futuremarketinsights.com/reports/space-economy-market) |

大 M 極大但增速是單位數到低雙位數。RKLB 的彈性不來自「整個太空經濟」，而來自其中長得最快的兩塊：發射與衛星製造。

#### 小 M｜發射服務 + 衛星製造（真正驅動股價的賽道）

| 市場定義 | 規模 | 增速 | 來源 |
| --- | --- | --- | --- |
| 發射服務 | 2025 約 **$100 億**，佔太空經濟 ~1.8% | **約 18.6% CAGR**（至 2035） | [SpaceNexus 彙整](https://spacenexus.us/learn/space-industry-market-size) |
| 衛星製造 | 2025 約 **$220 億** | **約 14.4% CAGR** | 同上 |
| 商業衛星發射 | 2025 **$103 億** → 2034 **$240 億** | **9.8% CAGR** | [Dataintelo](https://dataintelo.com/report/commercial-satellite-launch-market) |
| 專屬小衛星發射 | 2025 **$18 億** → 2034 **$64 億** | **14.2% CAGR** | [MarketIntelo](https://marketintelo.com/report/dedicated-smallsat-launch-market) |

2025 全球軌道發射約 324 次：Falcon 9 **165 次**（約一半），中國長征系列約 69 次，Electron 軌道發射約 18 次、含 HASTE 共 21 次。Electron 是**全球發射次數第三、美國第二**，但在「公斤數 / 營收」市佔上遠小於 SpaceX——大多數小衛星仍坐 Falcon 9 Transporter rideshare。

資料：[SpaceNews 2025 發射統計](https://spacenews.com/spacex-china-drive-new-record-for-orbital-launches-in-2025/)、[KeepTrack](https://keeptrack.space/launches/2025)、[10-K](https://investors.rocketlabcorp.com/static-files/57a8d0da-27ff-499c-8d85-18907743b7a8)

#### SAM｜Rocket Lab 實際可吃到的市場

| 可服務範圍 | 現況 | 含義 |
| --- | --- | --- |
| 專屬小發射（Electron，≤300 kg、要特定軌道 / 時程） | FY2025 Launch $199M；Electron 是該細分的領導者 | SAM 不是「所有小衛星」，而是「不願意等 rideshare、要專屬軌道」的那一層 |
| 高超音速試驗（HASTE） | $190M MACH-TB 2.0（20 次）、國防優先 | 亞軌道、與軌道發射不完全重疊的增量 SAM |
| 中型發射（Neutron，~13 t 可回收 LEO） | 尚未首飛；已開始簽 Neutron 任務（含 Space Force Flatellite 搭載） | 這是把 SAM 從「數十億美元小發射」擴到「數百億美元中型發射 / 星座部署」的開關 |
| 衛星平台 + 組件 | FY2025 Space Systems $403M；SDA Tranche 3 單筆 **$816M** | 已證明能從零件商接到 18 顆飛彈預警星的 prime 合約 |
| Iridium（未交割） | 交易 EV **$80 億**；交割目標 2027 年中 | 若完成，SAM 再加一層全球 L-band 通訊與 PNT 經常性收入 |

**市場結構判斷：** 大 M 夠大但不是超高增速；小 M（發射 + 造星）是 10–20% CAGR 的擴張賽道；RKLB 當前 SAM 仍偏窄（專屬小發射 + 國防小星座），**Neutron 成敗決定它能不能從「小 M 裡的利基冠軍」變成「中型發射的第二來源」**。管理層在 Q2 電話會的原話是：現在要訂發射、尤其 2029 之後，「選項極度有限」。

### 2.4 業務部門增長與驅動力

**FY2025 部門：** Launch +58.8%、Space Systems +29.6%。發射次數 21 次（含 3 次 HASTE），100% 成功，對 2024 年 16 次。

**2026 年迄今的驅動排序：**

| 排序 | 引擎 | 數據 | 性質 |
| --- | --- | --- | --- |
| 1 | **衛星製造 / SDA 星座** | Q1 Space Systems $136.7M（+57% YoY）；Q2 $189.5M（+93.6% YoY、+38.6% QoQ）。SDA Tranche II / III 放量 | 多年度 overtime，能見度最高 |
| 2 | **國防新標** | Space Force 發射合約 **$266M / 最多 18 次**（公司史上最大發射合約）；Flatellite SB-AMTI **$397M**；GEO 三顆 **>$160M** | 打開 GEO 與空中移動目標指示新市場 |
| 3 | **發射合約預訂，不是當季發射收入** | Q1 單季簽 31 份 Electron/HASTE + 5 次 Neutron，超過 2025 全年；Q2 及季後新發射合約 **>$437M**，發射 backlog **90+ 次** | 需求強，但 Q2 發射營收幾乎持平（服務收入 +1.8% YoY） |
| 4 | **併購併入** | Q2 完成 Mynaric、Motiv；季內開始貢獻 Space Systems | 一次性格、毛利率較低 |

資料：[Q1 2026 回顧](https://mvcinvesting.substack.com/p/rocket-lab-rklb-q1-2026-earnings)、[Q2 2026 財報會](https://www.fool.com/earnings/call-transcripts/2026/08/17/rocket-lab-rklb-q2-2026-earnings-call-transcript/)

**必須拆開看的矛盾：** 2026 H1 總營收 +63%，但發射服務收入幾乎沒長。市場若只交易「發射故事」，Q2 已經給過一次懲罰（紀錄營收、股價仍從高點大幅回落）。真正在長的是造星。

### 2.5 增長持續性

**支持延續的硬證據：**

| 指標 | 數字 | 解讀 |
| --- | --- | --- |
| 合約 backlog | Q4’25 **$18.5 億**（+73% YoY）→ Q1’26 $22 億 → Q2’26 **$23.6 億**（+137% YoY） | 相當於 TTM 營收的 **3.1 年** |
| 12 個月轉換 | 約 **45.5%** backlog 預期在未來 12 個月轉成營收 | 約 $10.7 億的近端能見度，高於 FY2025 全年 |
| Backlog 結構 | Launch ~40% / Space Systems ~60% | 與當前營收結構一致，不是單一賭注 |
| 發射清單 | **90+ 次** Electron / HASTE / Neutron | CFO 曾說 2026 發射次數大約 +20% |
| 流動性 | 現金 + 有價證券約 **$24 億** | 足夠燒 Neutron 與做 M&A，前提是不再無節制 ATM |

**會打斷曲線的開關：**

1. **Neutron 首飛仍訂 Q4 2026**，已因一級貯箱測試失敗延過一次；CEO 在 Q2 說「年底窗口在收窄」。共識裡 2027 +42% 隱含 Neutron 開始貢獻，若再延到 2027，這段 CAGR 要下修。
2. **Iridium 要到 2027 年中才可能交割**，且會加入約 $36 億過橋貸款與大量新股。這是增長，也是資本結構重組。
3. 政府佔比升到 47%、單一政府客戶 28%——訂單能見度高，但受撥款、停擺與固定價格超支雙重約束。

**結論：** 近 12–24 個月的營收增長被 backlog 鎖住，**達到 20% 標準的機率高**；2027 之後的斜率取決於 Neutron 是否按時進入可重複飛行，而不是 Electron 再多飛幾次。

---

## 3. Valuation｜估值評估

基準：2026-08-24 收盤 **$68.28**；52 週區間 $37.57–$151.00（現價約為高點的 45%）。Implied 市值 **$437 億**，淨現金約 $24 億，EV 約 **$413 億**。

資料：[Yahoo Finance RKLB](https://finance.yahoo.com/quote/RKLB/)、[Yahoo Key Statistics](https://finance.yahoo.com/quote/RKLB/key-statistics/)、[StockAnalysis Statistics](https://stockanalysis.com/stocks/rklb/statistics/)

### 3.1 當前估值對比行業

航太與國防（A&D）行業（Simply Wall St，2026-08-21）：**PE 39.9x、絕對 PE 44.9x、PS 3.3x**。CSIMarket TTM 口徑更低：PE 32.8x、PS 1.86x、P/CF 37.1x。

| 倍數 | RKLB | 行業（A&D） | 差距 | 判定 |
| --- | --- | --- | --- | --- |
| **PE（TTM）** | **不適用**（虧損；若強行用 EPS −$0.26 ≈ **−263x**） | **39.9x** | 無獲利可比 | **無法用 PE 說低估；實質遠高於行業** |
| **PS（TTM）** | **56.8x**（$437 億 / $7.69 億）；普通股口徑 53.1x | **3.3x** | 約 **17 倍**行業 | **顯著高於行業** |
| **Forward PS 2026E** | **45.8x**（$437 億 / $9.53 億） | — | — | 仍是成長股極端溢價 |
| **Forward PS 2027E** | **32.1x**（$437 億 / $13.6 億） | — | — | 即使營收再翻倍以上，倍數仍是行業的 ~10 倍 |
| **EV / Sales TTM** | **約 53.7x** | 行業 EV/S 約 2.2x（CSIMarket） | — | 同樣極端 |
| **P/FCF** | **不適用**（TTM FCF −$3.71 億；levered FCF −$2.52 億） | P/CF **37.1x** | 公司在燒現金 | **無法比較；標註為劣於行業** |

太空子行業經驗倍數（SpaceNexus）：發射 2–5x EV/Revenue、衛星通訊 3–8x、國防硬體 1.5–3x。RKLB 即使用「可回收發射 + 高增長」給到區間上沿 5x，對 2027E $13.6 億營收也只支撐約 **$68 億 EV**，約為現價的六分之一。

資料：[Simply Wall St A&D](https://simplywall.st/markets/us/industrials/aerospace-and-defense)、[CSIMarket A&D Valuation](https://csimarket.com/Industry/industry_valuation_ttm.php?ind=201)、[How to Value a Space Company](https://spacenexus.us/blog/how-to-value-space-company-metrics-multiples)、[Motley Fool：59 倍營收](https://www.fool.com/investing/2026/08/22/rocket-lab-trades-at-59-times-revenue-with-neutron-still-unflown/)

**對比結論：** 三個核心倍數裡，PE 與 P/FCF 因虧損失效，**唯一能用的 PS 顯示大幅高估**。這不是「略高於行業」，是差一個數量級。

### 3.2 預期 PE（未來 1–3 年）

| 年 | GAAP EPS 共識 | 對應前瞻 PE（$68.28） | 備註 |
| --- | --- | --- | --- |
| 2026E（未來 1 年） | **−$0.27** | **不適用** | Yahoo，11 位分析師 |
| 2027E（未來 2 年） | **−$0.07** | **不適用** | 高值僅 $0.02，中值仍虧 |
| 2028E（未來 3 年，覆蓋薄） | 約 **+$0.29 至 +$0.38** | **約 180–235x** | SharesGrow $0.29；MarketScreener 淨利 $2.46 億 / ~6.4 億股 ≈ $0.38 |
| **三年平均預期 PE** | 前兩年虧損，平均**無意義** | 若只把 2028 當「轉盈 PE」≈ **208x** | 不能與 AMD/NVDA 那類「三年平均 16–32x」直接類比 |

非 GAAP 口徑（StockAnalysis）2026E −$0.05、2027E +$0.05 → 2027 前瞻 PE 仍約 **1,366x**，轉盈幅度可以忽略。

### 3.3 合理估值依據

給予倍數時同時看四件事：成長、護城河、獲利品質、執行風險。

| 因子 | 事實 | 對倍數的含義 |
| --- | --- | --- |
| 成長 | 營收 3 年 CAGR ~38–50%，遠超 20% | 應高於 A&D 成熟公司的 40x PE / 3.3x PS |
| 護城河 | 2.7 / 5.0，偏低至中等（見第 5 節） | 不能給 NVDA / 高轉換成本軟體那種 35–50x「獲利後」溢價的上沿 |
| 獲利 | GAAP 毛利率 34–38% 已過 30% 線，但營業利率 −29% TTM，FCF 仍深負 | 倍數應主要用 **前瞻 PS / EV/S**，而不是 PE |
| 執行 | Neutron 未首飛；Iridium 未交割；ATM 持續稀釋 | 必須扣執行折價 |

**合理倍數區間（本架構）：**

- **轉盈後合理 PE：45–60x。** 理由：A&D 行業 ~40x，加 40%+ 成長溢價，但扣中低護城河與固定價格國防合約的質量折價。取中點 **50x**。
- **合理前瞻 PS：12–18x 的 2027E 營收。** 理由：已是行業 3.3x 的 4–5 倍，足以反映高增長；再往上是把尚未飛行的 Neutron 與尚未交割的 Iridium 當已實現。取中點 **15x**。

對 2027E $13.6 億營收、15x PS → 合理市值約 **$204 億**（約 $32 / 現有 implied share）。對 2028E EPS $0.33（取 $0.29–0.38 中點）、50x PE → 合理股價約 **$16.5**。兩種口徑都遠低於 $68。

分析師 12 個月目標價平均 **$112.94**（低 $64 / 高 $150），隱含 +65%。那是在定價 Neutron 選擇權與 Iridium 協同，**不是**本架構用的基本面倍數。兩者應分開看，不能把目標價當成「價值空間為正」的證據。

資料：[StockAnalysis Forecast / 目標價](https://stockanalysis.com/stocks/rklb/forecast/)

### 3.4 潛在價值空間

**公式 A（架構指定，PE）：**  
(合理 PE ÷ 預期平均 PE − 1) × 100%  
= (50 ÷ 208 − 1) × 100% ≈ **−76.0%**

**公式 B（更適合未獲利公司，PS）：**  
(合理前瞻 PS ÷ 2027E PS − 1) × 100%  
= (15 ÷ 32.1 − 1) × 100% ≈ **−53.3%**

| 口徑 | 結果 | 標籤 |
| --- | --- | --- |
| PE 公式 | −76% | **當前估值過高** |
| PS 公式 | −53% | **當前估值過高** |
| 分析師目標價 | +65% | 市場在交易選擇權，與倍數結論相反 |

**結論：價值空間不足 / 估值偏高。** 即使接受「高增長應給溢價」，現價 32x 2027E 營收、轉盈後仍約 200x PE，已經把 Neutron 成功、SDA 順利放量、Iridium 交割且不嚴重稀釋，全部折進價格。要讓 15x 2027E 營收回推到現價，2027 年營收需要約 $29 億——是共識的 2.1 倍，且尚未計入 Iridium 的債務與新股。

---

## 4. Profitability｜盈利能力

### 4.1 利潤率 vs 行業

A&D 行業參考：毛利率中位 / 平均約 **25.7–29.9%**，營業利率中位約 **8.7%**，淨利率約 **4.8–5.5%**（FullRatio 67 家、CompanyGraph 193 家，2026-08）。國防 prime（LMT / RTX / NOC / GD）營業利率約 10–11%、淨利率約 7–10%。

| 指標 | RKLB FY2025 | RKLB Q2 2026 | RKLB TTM | 行業 | 判定 |
| --- | --- | --- | --- | --- | --- |
| **毛利率** | **34.4%** GAAP / **39.7%** 非 GAAP | **36.1%** GAAP / **41.5%** 非 GAAP | 約 **37%** | **29.9%** | **達到並超過 30% 標準**；優於行業平均 |
| 其中 Launch | **40.8%** | 當季被 HASTE mix 干擾 | — | — | 發射已是公司內較高毛利段 |
| 其中 Space Systems | **31.3%** | Q3 指引 GAAP 29–31%（mix 轉差） | — | — | 大型平台合約毛利偏低（管理層指 mid-30s%） |
| **營業利率** | **−38.0%** | **−24.6%** | 約 **−29%** | **8.7%** | **遠低於行業；未達標** |
| **淨利率** | **−32.9%** | **−21.0%** | 約 **−21.5%** | **4.8%** | **遠低於行業；未達標** |
| Adj. EBITDA | −$101.2M（−16.8%） | −$8.8M（−3.8%） | H1 −$20.6M | — | 虧損在收窄，Q3 指引卻又擴大到 −$17 至 −$23M |

Q2 非 GAAP 毛利率 41.5% 高於指引 38–40%，含關稅退稅的一次性利益，部分被存貨準備抵銷，**不能當成新常態**。Q3 指引 GAAP 毛利率降回 29–31%，因為 Space Systems mix。

費用結構才是虧損來源：FY2025 研發 **$270.7M（營收的 45%）**、SG&A $165.3M（27.5%），合計營業費用 $436M，是毛利 $207M 的 2.1 倍。Q2 2026 研發仍 $82.4M，主要是 Neutron。毛利率達標、營業利率慘，是「產品已能賺錢、平台還在燒下一代火箭」的典型結構。

資料：[FY2025 損益表](https://investors.rocketlabcorp.com/news-releases/news-release-details/rocket-lab-announces-fourth-quarter-and-full-year-2025-financial)、[Q2 2026 損益表](https://investors.rocketlabcorp.com/news-releases/news-release-details/rocket-lab-announces-second-quarter-2026-financial-results-posts)、[FullRatio 行業利潤率](https://fullratio.com/profit-margin-by-industry)、[CompanyGraph A&D](https://companygraph.me/en/industries/aerospace-and-defense)

### 4.2 股東回報

| 項目 | 數字 | 判定 |
| --- | --- | --- |
| 股權回購 | **無**實質回購計畫 | — |
| 流通股變化 | 2024 年底 504.5M → 2025 年底 543.6M → 2026-06-30 **598.2M** | 18 個月 **+18.6%** |
| 近一年稀釋 | StockAnalysis：**+15.68%** | **股權稀釋（加速）** |
| ATM 融資 | 2025 淨募約 **$11.2 億**；H1 2026 淨募約 **$15.1 億** | 增長與 Neutron / M&A 的主要資金來源 |
| 可轉債 | 2025 年底 $152M → 2026 年中 $13M（大量轉股） | 利息下降，但股本再被攤薄 |
| 優先股 | Peter Beck 信託持有的 Series A 可轉換優先股，Q2 仍約 41M 股計入加權股數 | implied shares 639M vs 流通 598M |
| **股息率** | **0%** | **無股息** |

資料：[Q2 2026 資產負債與現金流量](https://www.sec.gov/Archives/edgar/data/1819994/000181999426000061/rklb-08102026ex991.htm)、[StockAnalysis Statistics](https://stockanalysis.com/stocks/rklb/statistics/)

Iridium 交易的現金端還要再加約 $27 / Iridium 股，並用 **$36 億** Deutsche Bank / Wells Fargo 過橋貸款。交割後稀釋與槓桿會再上一個台階。

### 4.3 資本效率與安全

**ROIC**

FY2025 營業虧損 $228.8M；投入資本粗估 = 權益 $17.22 億 + 有息債 $1.54 億 − 現金及有價證券 $11.0 億 ≈ **$7.8 億**。  
ROIC ≈ **−29%**。H1 2026 年化仍為負（約 −20% 量級）。過去五年（上市後）沒有出現正 ROIC。

**判定：尚未為股東創造正的資本回報。** 帳上權益暴增是 ATM 進來的現金，不是留存盈餘。

**利息覆蓋率**

| | EBIT | 利息費用 | EBIT / 利息 |
| --- | --- | --- | --- |
| FY2025 | −$228.8M | $26.5M | **−8.6x** |
| Q2 2026 | −$57.5M | $0.58M | 仍為負，但利息已接近零 |
| Q2 2026 利息收入 | — | 收入 $16.5M | **淨利息收入 +$15.9M** |

傳統「利息覆蓋率 > 2 即安全」在這裡失效：分子是負的。改看資產負債表更準——

| 2026-06-30 | 金額 |
| --- | --- |
| 現金及約當現金 | $2,129M |
| 有價證券（流 + 非流） | $258M |
| 可轉債 + 長期借款 | **$15M** |
| **淨現金** | **約 $2,373M** |

**判定：槓桿意義上安全（淨現金、利息費用可忽略）；獲利意義上不安全（EBIT 仍大幅為負，FCF TTM −$3.7 億）。** 安全墊來自股權融資，不是來自經營現金流。Q3 指引仍預期非 GAAP 自由現金流為負。

---

## 5. Moat｜護城河評估

評分 0–1.0，加總滿分 5.0。分數必須能對上可驗證事實，而不是品牌故事。

### 5.1 成本優勢　**0.5 / 1.0**

- 發射毛利率 FY2025 已到 **40.8%**，非 GAAP 整體毛利率 Q2 **41.5%**，高於 A&D 平均 ~30%。垂直整合（Rutherford 3D 列印電動渦輪泵、碳複合材貯箱自製、太陽能 / 光學 / 航電內製）確實把部分成本留在體內。
- 反面：SpaceX Falcon 9 可回收把「每公斤成本」打到 RKLB 無法在中型發射上硬拼的位置；Electron 走的是專屬軌道溢價，不是成本領導。Neutron 的成本優勢**尚未被飛行證明**。公司也不是輕資產——FY2025 資本支出 $1.56 億、PPE 從 $1.95 億升到 $3.19 億，2026 年中再升到 $3.94 億。
- Mynaric 併入後管理層承認「一開始毛利率一定比較低」。大型 SDA 平台合約毛利在 mid-30s%，會稀釋組件業務的高毛利。

有規模與製程優勢，但只存在於小發射利基，且正在被低毛利國防整星合約稀釋。

### 5.2 網絡效應　**0.3 / 1.0**

- 發射本身幾乎沒有網絡效應：第 n 個客戶不會讓第 n+1 個客戶的火箭更有價值。轉換成本主要是「換發射商要重做接口與保險」，不是生態鎖死。
- 組件 / 衛星平台有中等轉換成本：反應輪、星敏、太陽陣列一旦 design-in，換供應商要重新資格認證。這是 B2B 硬體常見的黏性，不是 CUDA 那種開發者網絡。
- Iridium 交割前，公司**沒有**用戶網絡。交割後才會有全球 L-band 終端與航空監視（Aireon）裝機量。目前不能把尚未買下的網絡算進護城河。

### 5.3 品牌優勢　**0.7 / 1.0**

- 2025 年 Electron 是**全球發射次數第三、美國第二**（僅次 Falcon 9），21 次任務 100% 成功。在「專屬小發射」這個圈子，Electron 幾乎就是代名詞。
- 飛行遺產：截至 2025-12-31，75 次成功任務、200+ 艘航天器；組件飛行遺產 1,800+ 任務。NASA CAPSTONE（月球）、ESCAPADE（火星）證明能做 decadal-class 科學任務。
- Space Force VICTUS HAZE：Electron + 自製衛星 **16 小時 42 分**響應發射，這是國防品牌資產，不是行銷文案。
- 反面：對大眾與多數機構投資人，SpaceX 才是「商業發射」的絕對代名詞。品牌溢價存在於政府與星座採購官，而不是定價權覆蓋全市場。

### 5.4 技術門檻　**0.7 / 1.0**

- Rutherford：電動渦輪泵 + 3D 列印，工業界仍少見的組合；Archimedes（Neutron，液氧甲烷）累計 **400+ 次**熱試車，目標可重複使用。
- 碳複合材一級、自有私有發射場，加上美紐雙邊條約允許在紐西蘭使用美國發射技術——這是法律 / 地緣上的複製障礙，不只是工程。
- 垂直技術棧：SolAero 空間太陽能、GEOST/OSI 光學、Mynaric 雷射通訊、Photon/Flatellite 平台。SDA 選它做 18 顆 Tracking Layer 衛星，代表通過了國防資格門檻。
- 反面：中型可回收發射的真正門檻是 **飛行次數與回收節奏**，這項 SpaceX 領先十年。Neutron 的 Hungry Hippo 整流罩、一級貯箱已出過測試失敗。專利有，但 10-K 自己寫的是專利 + 營業秘密 + 飛行遺產的組合，沒有披露可與大型航太公司相比的專利牆規模。

### 5.5 業務韌性　**0.5 / 1.0**

**加分：** 兩條腿（發射 33% / 造星 67%，Q2 已是 19/81）；backlog $23.6 億；淨現金 $24 億；商業 vs 政府 backlog 約 57/43（Q2）。不再是單一火箭公司。

**減分：**

- 前五大客戶 **49%** 營收、**77%** backlog
- 美國政府相關 **47%** 營收，單一政府客戶 **28%**
- 地域美國 **79%**
- 仍未獲利，經營現金流 H1 2026 −$1.34 億
- 發射收入先天 lumpsy（Q2 就是例子）
- Iridium 交割前財務體質看起來很強，交割後會再扛數十億債務

多元化在產品端成立，在客戶端不成立。

### 5.6 護城河總評　**2.7 / 5.0（偏低至中等護城河）**

| 支柱 | 分數 |
| --- | --- |
| 成本優勢 | 0.5 |
| 網絡效應 | 0.3 |
| 品牌優勢 | 0.7 |
| 技術門檻 | 0.7 |
| 業務韌性 | 0.5 |
| **合計** | **2.7 / 5.0** |

這是「利基裡很難被新創小火箭取代、但在中型發射與整星 prime 仍要跟 SpaceX / 傳統國防承包商正面撞」的護城河。比 HIMS 樣板的 3.1 略弱，明顯低於高護城河門檻（4.0+）。**現價給的倍數卻接近高護城河成長股。**

---

## 6. 主要風險

1. **Neutron 執行風險（估值的核心假設）。** 首飛已從更早時程改到 2026 Q4，一級貯箱測試失敗過。CEO 稱年底窗口在收窄。現價 32x 2027E 營收，把「Neutron 開始貢獻」當成基本情境。再延一年，共識 CAGR 與倍數會同時崩。
2. **與 SpaceX 的結構性成本差距。** Falcon 9 2025 年 165 次；Starship 若進入可營運，中型 / 大型發射價格錨會再下移。Electron 靠專屬軌道生存，Neutron 必須證明「可回收 + 足夠頻率」才能吃星座部署，否則只是較貴的第二來源。
3. **客戶與政府集中。** 前五客戶 49% 營收、77% backlog；美國政府相關 47%；單一政府客戶 28%。固定價格合約下成本超支由 RKLB 承擔。撥款拖延、停擺、或 SDA 後續 tranche 丟標，會直接打到能見度最高的那塊營收。
4. **持續虧損 + 股權稀釋。** TTM FCF −$3.7 億；2025–2026 H1 ATM 合計淨募約 **$26 億**；流通股 18 個月 +19%。Iridium 還要再發股 + $36 億過橋貸款。股東回報目前是負的稀釋，不是回購。
5. **Iridium 交易風險。** $80 億 EV、目標 2027 年中交割，需 Iridium 股東與監管批准。Collar $67.50–$112.50 意味 RKLB 股價越低，發給 Iridium 股東的股數越多。整合衛星通訊營運商與發射製造商，是文化、監管（ITU / FCC / CFIUS 類審查）與槓桿三重風險。交易失敗則「垂直整合太空巨頭」敘事要重寫。
6. **毛利率 mix 惡化。** 增長最快的是較低毛利的整星平台與剛併入的 Mynaric；Q3 指引 GAAP 毛利率 29–31%，可能重新跌破 30% 線。發射高毛利被認列時點打亂，不能當穩定緩衝。
7. **發射與航天器失敗的尾部風險。** 2025 年 100% 成功拉高了預期。一次 Electron 失敗會停飛、保險與政府資格；一次 Neutron 首飛失敗會重創敘事。10-K 把這列為業務層級風險而非假設情境。
8. **估值自身就是風險。** 52 週高點 $151，現價已腰斬仍是 57x TTM 營收。高 beta（5 年約 2.63）、空頭佔流通股約 7.7%。任何指引失手的回撤幅度會大於基本面的實際變化。

---

## 7. 綜合分析與觀點

### 7.1 評估結果清單

| 面向 | 標籤 | 依據 |
| --- | --- | --- |
| 增長 | **增長優異** | FY2025 +38%、H1 2026 +63%、共識 2026E +58% / 2027E +42%，全面超過 20% 標準；backlog $23.6 億 |
| 價值空間 | **估值偏高** | TTM PS 56.8x vs 行業 3.3x；(50 ÷ 208 − 1) ≈ **−76%**；(15 ÷ 32.1 − 1) ≈ **−53%** |
| 護城河 | **偏低至中等護城河** | 2.7 / 5.0；小發射品牌與垂直技術成立，網絡效應弱、客戶集中 |
| 盈利能力 | **尚未轉盈** | 毛利率達標（>30%），營業 / 淨利率深度為負，ROIC −29%，無股息、持續稀釋 |

### 7.2 綜合分析

Rocket Lab 已經不是 2021 年那個「還沒證明能每月發射」的 SPAC 發射新創：FY2025 營收 $6.02 億、+38%；TTM 約 $7.7 億；Q2 單季 $2.34 億、+62%。增長的主引擎已切到 Space Systems（FY2025 佔 67%、Q2 佔 81%），SDA $8.16 億、Space Force 發射 $2.66 億、Flatellite $3.97 億把公司推進國防 prime 的外圍。毛利率跨過 30% 線、發射段甚至到 41%，證明 Electron 與組件不是永遠虧錢的玩具。Backlog $23.6 億、近 12 個月轉換 45.5%，短中期營收能見度在硬體公司裡算好。

問題在價格與利潤的錯配。$437 億市值買的是一家 TTM 仍虧約 $1.7 億、FCF −$3.7 億、利息覆蓋率為負、靠 ATM 維持 $24 億現金的公司。32x 2027E 營收、轉盈後仍約 200x PE，要求 Neutron 在 2026 Q4 前後首飛並快速爬坡、SDA 放量不踩固定價格坑、Iridium 在 2027 年中順利交割且協同大於稀釋。這些可以發生，但全部發生才撐得住現價；任何一項延遲，倍數沒有基本面墊在下面。護城河夠讓它繼續當專屬小發射與小衛星組件的首選，不夠讓它在中型發射上挑戰 SpaceX 的成本曲線。

**標的類型：高溢價趨勢成長股（執行選擇權），不是價值股，也還不是已驗證的複合機器。** 適合的是能承受 Neutron / 稀釋 / 政府合約三重二元結果、且不依賴本架構「價值空間為正」作為買入條件的成長倉位；用現代價值投資的倍數公式衡量，現價沒有安全邊際。

---

## 附錄：商業模式 × 未來展望（客人、錢流、成長路徑、觀察指標）

補充四個問題：客人是誰、錢花在哪、成長怎麼實現、該盯什麼。這是把前面七步收成一條可驗證的因果鏈。

### A. 客人是誰

現在的 RKLB 有三層買家；Iridium 交割後會再加第四層。**付錢的人已經從「商業小衛星業者」轉成「美國國防採購官 + 要專屬軌道的星座商」。**

| 客層 | 代表買家 | 他們買什麼 | 證據 |
| --- | --- | --- | --- |
| **1. 美國國防 / 情報（最大、成長最快）** | SDA、Space Force、DoW、MDA、Space Systems Command | 飛彈預警星座、空中移動目標指示星、GEO 空間態勢感知星、高超音速試驗發射、24 小時響應發射 | FY2025 美國政府相關 **47%** 營收（2024 僅 33%）；單一政府客戶 **28%**；SDA T3 **$816M**、SB-AMTI Flatellite **$397M**、HASTE Space Force **$266M**、GEO **>$160M** |
| **2. 商業星座（要軌道與時程，不只要便宜公斤價）** | QPS、BlackSky、Synspective、Kinéis、Capella、Planet；Q1 未揭露的 Neutron+Electron 大宗客戶 | 專屬 Electron 發射、未來 Neutron 星座部署 | QPS 已累計 18 次發射；Q1 單季簽的發射數超過 2025 全年；Q2 發射 backlog **90+ 次** |
| **3. 民用科學 / 其他 prime** | NASA、大學（ESCAPADE / CAPSTONE）、Lockheed（AR 的 16%） | 深空航天器、組件、少量發射 | 組件飛行遺產 1,800+ 任務；Lockheed 是應收集中戶，不一定是營收集中戶 |
| **4. 尚未交割：終端用戶網絡** | Iridium 2.537M 付費用戶；美國政府 EMSS 合約 | L-band 語音 / IoT / 航空海事安全 / PNT | Iridium FY2025 營收 **$8.72 億**、服務收入 $6.34 億；美國政府佔其總營收 **29%**（$2.57 億） |

Q2 2026 backlog 口徑約 **57% 商業 / 43% 政府**，但 FY2025 *已認列營收* 已有 47% 來自美國政府體系。差別在於：政府合約 overtime 認列較慢、金額較大；商業發射一次認列、波動大。前五大客戶仍佔營收 49%、backlog **77%**——客人名單不長，單筆合約卻越來越像國防 prime。

客人要的不是「最便宜的公斤價」（那是 SpaceX Transporter），而是三樣 SpaceX 不優先賣的東西：**特定軌道與發射窗口、高超音速試驗、把整星+發射綁在同一家。** VICTUS HAZE 16 小時 42 分響應，就是這個客層的採購邏輯。

### B. 錢花在哪裡

分兩筆帳：客人的預算進 RKLB 哪條產品線，以及 RKLB 自己把現金燒在哪。

**客人的錢 → RKLB 營收（Q2 2026 已是造星公司）**

| 客人預算科目 | 進 RKLB 哪裡 | 佔比 / 單價邏輯 |
| --- | --- | --- |
| 造星與組件 | Space Systems 產品 | Q2 **81%** 營收（$189.5M）。SDA 等大型平台毛利約 mid-30s%；商譽組件（太陽能、反應輪）毛利較高。CFO：國防專案大約走 **4 年、10/40/40/10** 認列曲線 |
| 軌道發射 | Launch / Electron | Q2 僅 **19%**。專屬小發射溢價；管理層稱 Electron ASP 多年來明顯上升 |
| 高超音速試驗 | HASTE | $190M（20 次 MACH-TB）+ $266M（最多 18 次 Space Force，內含發射場基礎設施，不能用 $266M/18 ≈ $15M 當 ASP） |
| 中型星座部署 | Neutron（大多尚未認列） | Flatellite 明確寫「搭載 Neutron」；Q1 未揭露客戶一次買多發 Neutron+Electron。這是 2027 以後的客單價跳升，不是 2026 的營收 |

**RKLB 自己的錢 → 未來產能（這才是「展望」的成本）**

| 支出 | 規模 | 用途 |
| --- | --- | --- |
| 研發 | FY2025 **$271M（營收 45%）**；Q2 2026 單季 $82M | 幾乎就是 Neutron。營業虧損的主因 |
| 資本支出 | FY2025 $156M；Q2 2026 **$26M**（主要 Neutron 測試與發射台） | LC-3、Archimedes 試車、一級貯箱；阿拉斯加 GHOST 發射台有部分由合約資助 |
| 營運資金 | H1 2026 經營現金流 **−$1.34 億**；存貨 $2.67 億 | Q2 現金消耗來自「預先製造 Neutron 後續箭體」+ 重整 Mynaric 供應鏈 |
| 併購 | GEOST、OSI、Mynaric、Motiv；Iridium EV **$80 億**（$27 現金 + 股票 + $36 億過橋） | 把光學、雷射通訊、衛星服務買進來，而不是自己從零建星座（Beck：自建要十年以上） |
| 融資來源 | 2025–H1 2026 ATM 淨募約 **$26 億** | 股東在付 Neutron 與 M&A 的帳單 |

一句話：**客人把國防與星座預算花在「整星 + 專屬發射」；公司把股東的錢花在 Neutron 與買下應用層（Iridium）。** 近兩年營收增長來自前者，市值定價的是後者。

### C. 預期如何成長

成長不是一條平滑曲線，是三段接力。共識數字：2026E **$953M（+58%）**、2027E **$1.36B（+42%）**。公司本身不給全年指引。

| 階段 | 時間 | 誰付錢、錢從哪裡來 | 成長性質 |
| --- | --- | --- | --- |
| **已鎖住** | 未來 12 個月 | 現有 $23.6 億 backlog 的 **45.5%** 轉成營收 ≈ $10.7 億 | SDA Tranche II/III overtime 放量 + Electron/HASTE 發射。不依賴 Neutron 首飛 |
| **斜率開關** | 2026 Q4–2027 | Neutron 首飛並開始吃中型任務；Flatellite / 未揭露星座客戶 | 客單價從 Electron 級跳到中型。Beck：重點不是第一次飛，是能不能無縫爬到第 10 次 |
| **模式切換** | 2027 年中起 | Iridium 交割：再加約 **$8.7 億/年**、低個位數增長、高現金流的服務收入 | 從「專案型硬體」變成「硬體 + 2.5M 用戶訂閱」。應用層擴張（IoT、D2D、PNT、航空海事）是敘事，不是 2026 的數字 |

發射端：管理層說需求「extreme」，2029 年以後能訂的發射位極少；CFO 曾指引 2026 發射次數大約 +20%。但 Q2 已示範過——發射次數沒掉，服務收入卻幾乎持平（+1.8% YoY），因為 HASTE 用 overtime。所以「飛得更勤」≠「當季發射營收成長」。

造星端：才是 2026 的實際引擎。Q2 Space Systems +93.6% YoY。風險是 mix：大型平台毛利低於組件，Q3 指引 GAAP 毛利率 **29–31%**，可能重新跌破 30% 線。

Iridium 不是高成長資產（FY2025 只 +5%），它的價值是經常性收入與 L-band 頻譜；RKLB 想靠「自己造星、自己發射」把換代成本壓下來。EMSS 政府合約固定年費約 $1.105 億，主合約到 **2026 年 9 月**（另有六個月選擇權）——交割前就要面對續約，這是交易時間表上的暗樁。

### D. 未來要觀察的關鍵數據（以及為什麼）

只盯營收 YoY 會被 overtime 與 mix 騙。下列指標分別對應「客人有沒有繼續付錢」「錢有沒有變成利潤」「展望有沒有實現」。

| 優先 | 指標 | 怎麼讀 | 為什麼是關鍵 |
| --- | --- | --- | --- |
| 1 | **Neutron 硬體是否運到 LC-3、何時熱試 / 首飛** | 管理層說一級貯箱組裝對齊 Q4 運墊；「年底窗口在收窄」。最後高風險里程碑是墊上全燃料熱試 | 市值定價的是中型發射選擇權。再延到 2027，2027E +42% 共識要下修 |
| 2 | **發射 backlog 次數 + Neutron 佔比** | Q2 已 90+ 次。要看新增裡有多少是 Neutron 而非只是 Electron/HASTE | 首飛只證明能飛；訂單簿才證明客人願意把星座預算押在未驗證的火箭上 |
| 3 | **Space Systems vs Launch 營收比，以及 GAAP 毛利率** | Q2 已 81/19；Q3 指引毛利率 29–31% | 驗證「成長是造星還是發射」。若毛利率跌破 30% 且持續，代表增量來自低毛利國防整星，不是高毛利組件 / Electron |
| 4 | **Backlog 金額、12 個月轉換率、政府 vs 商業拆分** | $23.6 億、45.5%、Q2 約 43% 政府 | 轉換率掉 = 專案延期或認列放慢；政府佔比續升 = 能見度高但撥款 / 固定價格風險升 |
| 5 | **Launch 營收 vs 實際發射次數** | Q2 發射次數相近，Launch 營收季減 30%、服務收入僅 +1.8% YoY | 避免把「飛了幾次」當成成長。HASTE overtime 會讓次數與營收脫鉤 |
| 6 | **Adj. EBITDA 與 FCF，對照指引** | Q2 Adj. EBITDA −$8.8M，Q3 指引惡化到 −$17 至 −$23M；FCF 仍負，因預建 Neutron 箭體 | 問的是：高增長有沒有開始自我供血。若 ATM 再開、股數續增，股東在為展望付費 |
| 7 | **流通股 / ATM / 淨現金** | 18 個月股數 +19%；淨現金約 $24 億 | Iridium 現金端 + $36 億過橋會改寫這張表。現在的「淨現金安全」是交割前的快照 |
| 8 | **Iridium：交割進度 + EMSS 續約** | 目標 2027 年中；EMSS 主約 2026-09 到期 | 買下的經常性收入有 29% 綁美國政府。續約條件差，協同故事要打折 |
| 9 | **SDA / Flatellite 是否按 10/40/40/10 放量** | 單筆 $816M、$397M | 這是「已鎖住成長」的實體。若 milestone 延遲，近 12 個月 $10.7 億轉換假設失效 |
| 10 | **單季指引是否繼續「營收創新高、EBITDA 指引變差」** | Q3 營收中點 +10%、EBITDA 虧損擴大 | 代表 mix 轉差或 Neutron 費用前載。可以接受一季，連兩季就要懷疑成長質量 |

**對照檢查：** 若 1+2 同時達標（Neutron 飛了且訂單續進），成長路徑的第二段成立，估值討論才從「選擇權」變成「執行」。若只有營收創新高、但 3+6 惡化（毛利掉、現金燒更快），那是用低質量國防營收與股權融資堆出來的增長，不是商業模式升級。

來源：[Q2 2026 財報會](https://www.fool.com/earnings/call-transcripts/2026/08/17/rocket-lab-rklb-q2-2026-earnings-call-transcript/)｜[10-K 客戶集中度](https://investors.rocketlabcorp.com/static-files/57a8d0da-27ff-499c-8d85-18907743b7a8)｜[Iridium FY2025 財報](https://investor.iridium.com/2026-02-12-Iridium-Announces-2025-Results-Issues-2026-Outlook)

---

## 附錄：最新財報重點、未來展望、產業趨勢（截至 2026-08-25）

最新一期為 **Q2 2026**（截至 2026-06-30，8/10 公布）。公司不給全年指引，只給下一季。

### 最新財報重點

**損益（Q2 2026 vs Q2 2025）**

| 項目 | Q2 2026 | Q2 2025 | 變化 |
| --- | --- | --- | --- |
| 營收 | **$234.1M** | $144.5M | **+62.0%** YoY、+16.8% QoQ |
| Space Systems | **$189.5M（81%）** | — | +93.6% YoY、+38.6% QoQ |
| Launch Services | **$44.6M（19%）** | — | 季減約 30%（HASTE overtime，不是次數崩掉） |
| Product / Service | $181.3M / $52.7M | $92.7M / $51.8M | 產品近乎翻倍；服務僅 **+1.8%** |
| GAAP 毛利率 | **36.1%** | 32.1% | 高於指引；非 GAAP **41.5%**（含關稅退稅，被 Neutron Flight II 存貨準備抵銷） |
| 營業虧損 | **−$57.5M** | −$59.6M | 營收多 $90M，營業虧損只改善 $2M |
| 淨損 | **−$49.3M（−$0.08）** | −$66.4M | 收窄主因利息收入 $16.5M，不是本業 |
| Adj. EBITDA | **−$8.8M** | −$27.6M | 優於指引 −$20 至 −$26M |
| H1 2026 營收 | **$434.4M** | $267.1M | **+62.7%** |

**能見度與資產負債**

- Backlog **$23.6 億**（+137% YoY）：Launch ~40% / Space Systems ~60%；約 **45.5%** 預期 12 個月內轉成營收
- Q2 及季後新簽：**發射 >$437M**（含 Space Force HASTE 最多 18 次 **$266M**）、Space Systems **>$581M**（Flatellite **$397M**、GEO **>$160M**）；合計新約 **>$10 億**，發射清單 **90+ 次**
- 現金及有價證券約 **$24 億**；有息負債僅約 $15M；H1 ATM 淨募約 $15 億
- 經營現金流 H1 **−$1.34 億**；Q2 資本支出 $26M（主要 Neutron）
- 員工人數 **3,217**（季增 439，含 Mynaric / Motiv）
- 已關閉 Mynaric、Motiv；宣布收購 Iridium（EV 約 $80 億，目標 2027 年中）

**Q3 2026 指引（市場解讀為營收優於共識、獲利指引變差）**

| 項目 | 指引 |
| --- | --- |
| 營收 | **$250–265M**（中點較 Q2 約 +10%） |
| GAAP / 非 GAAP 毛利率 | **29–31%** / 35–37%（Space Systems mix 轉差） |
| GAAP / 非 GAAP 營業費用 | $143–149M / $121–127M（Neutron 首飛相關費用） |
| 淨利息收入 | $21M |
| Adj. EBITDA | **虧損 $17–23M**（比 Q2 的 −$8.8M 擴大） |
| 加權股數 | 約 641M（含約 41M 優先股） |

來源：[Q2 新聞稿](https://investors.rocketlabcorp.com/news-releases/news-release-details/rocket-lab-announces-second-quarter-2026-financial-results-posts)｜[8-K EX-99.1](https://www.sec.gov/Archives/edgar/data/1819994/000181999426000061/rklb-08102026ex991.htm)｜[財報會](https://www.fool.com/earnings/call-transcripts/2026/08/17/rocket-lab-rklb-q2-2026-earnings-call-transcript/)

### 未來展望（公司口徑 + 共識）

公司只給一季。管理層把 2026–2028 拆成三件事：SDA 等造星放量、Neutron 從研發轉庫存再轉飛行、Iridium 把模式切到應用層。

| 時點 | 公司自己怎麼說 | 數字含義 |
| --- | --- | --- |
| **已鎖住的 12 個月** | 45.5% backlog 轉營收；國防專案約 4 年、**10/40/40/10** 認列 | 約 **$10.7 億**近端能見度，不靠 Neutron 首飛 |
| **2026 Q4** | Neutron 一級貯箱組裝對齊 **Q4 運到發射台**；「年底首飛窗口在收窄」；策略是優先 **第 10 次飛行** 而非第一次；爬坡預期類似 Electron 的 **1-3-5** | Q3 費用從研發轉入飛行硬體庫存。CFO：FCF 在首次試飛前仍會燒，之後才談 Adj. EBITDA、再談 FCF 轉正 |
| **2027 年中** | Iridium 目標交割；Beck 稱進入「space applications era」。Iridium FY2025 **$8.72 億**、2.54M 用戶。管理層預期交割後 FCF 結構會重置 | 共識尚未完整計入併表。現金 $27/股 + 股票 collar + **$36 億**過橋 |
| **華爾街共識** | 不代表公司指引 | 2026E 營收 **$953M（+58%）**、2027E **$1.36B（+42%）**；GAAP EPS 2026 −$0.27、2027 仍約 −$0.07 |

發射端：管理層稱需求 extreme，**2029 以後能訂的位子極少**；部分 Neutron 運力會留給自有應用，不是全賣給外部。歐洲：Mynaric + Rocket Lab Germany，對應德國等國尋求主權造星 / 發射（Beck 舉德國逾 $400 億飛彈預警預算為例）。

**展望的矛盾：** Q3 營收中點創新高，但毛利率指引跌回 29–31%、EBITDA 虧損擴大。這是「造星 mix + Neutron 前載費用」的組合，不是需求消失。

### 產業趨勢（RKLB 真正吃到的那幾條）

上游（發射 + 造星）長得比整個太空經濟快；國防把空間從探索改成基礎設施。RKLB 的訂單結構（SDA、HASTE、Flatellite、響應發射）對得上這些趨勢，不是對得上 Starlink 消費寬頻。

| 趨勢 | 數據 | 對 RKLB 的含義 |
| --- | --- | --- |
| 太空經濟擴張 | 2025 全球 **$6,860 億、+12%**；五年 CAGR **9.8%**；商業佔 79%（[Space Foundation 2026 年報](https://www.spacefoundation.org/wp-content/uploads/2026/07/SF-GSE-REPORT-2026July-FOR-RELEASE.pdf)） | 大盤在長；RKLB 不吃 PNT 消費盤，吃的是上游 |
| **上游爆發** | 商業衛星製造 **+67.2%**、商業發射 **+49.4%**；軌道發射價值 **$191.7 億（+33.5%）** | 這才是 Space Systems 81% 營收、SDA 放量的產業背景 |
| 發射次數創新高、供給仍緊 | 2025 全球軌道嘗試 **324 次（+28%）**；美國 193、中國 92；Falcon 9 獨佔 **165 次**。白宮 2026-08 政策要美方 2030 年支援最多 **1,000 次/年**（[Air & Space Forces](https://www.airandspaceforces.com/white-house-policy-launch-range-infrastructure-crunch/)） | 發射場與中型運力是瓶頸。解釋為何 Neutron 未飛就能收訂單，以及 GHOST / 阿拉斯加墊的戰略 |
| SpaceX 轉 Starship | SpaceX 稱 2025–2026 可能是 Falcon 高峰，之後更多任務轉 Starship | 中型商業發射出現空檔，也是 Neutron 的窗口；同時 Starship 成功會再壓價格 |
| **國防空間基礎設施化** | 全球政府太空預算 2025 約 **$1,410 億（+7.4%）**；美國政府 $783 億。Golden Dome 十年成本估計 **$1,750–1,850 億**，已有 $225 億到位、約 95% 已承諾，但 **2027 有撥款斷層風險**（[SpaceNews](https://spacenews.com/golden-dome-faces-2027-funding-cliff/)） | HASTE、SDA Tracking Layer、SB-AMTI Flatellite、VICTUS HAZE 都屬「現在就有合約的成熟能力」，不是太空攔截器那種远期概念 |
| 分散式星座取代少數大星 | SDA PWSA 持續 tranche 採購；商業造星收入一年 +67% | 有利垂直整合、能快速量產小星的廠商；也把毛利從高值組件拉向較低的平台合約 |
| 歐洲主權 | 地緣下歐洲要本國造星 / 發射能力 | Mynaric + 德國公司是對這個缺口的卡位，2026 還不是營收主軸 |
| 應用層（Iridium 在買的） | 商業衛星通訊 2025 **$284 億（+9.5%）**；D2D 有機構看到 2033 近 $100 億。L-band 不是寬頻主戰場 | Beck 明確不跟 Starlink / Amazon 搶寬頻，要的是天氣可穿透、室內可用的安全關鍵頻譜 |

**產業結論：** 2025–2026 的趨勢對 RKLB 的「現有生意」（造星 + 專屬小發射 + 高超音速試驗）是順風；對「定價用的生意」（Neutron 中型可回收 + Iridium 應用層）則是窗口存在、執行未完成。Golden Dome / SDA 是近端訂單來源，2027 撥款斷層是同一條國防線上的政策風險。

---

## 附錄：25Q3–26Q2 關鍵季度表

口徑先講清楚，避免把三組「政府佔比」混在一起：

| 指標 | 口徑 | 來源層級 |
| --- | --- | --- |
| 營收、部門佔比、部門毛利率 | GAAP；部門毛利率 = 1 − 該部 COGS / 該部營收 | 10-Q / 10-K 分部表 |
| Backlog、12 個月轉換率 | 剩餘履約義務（RPO）；轉換率是管理層對「未來 12 個月認列」的估計，不是已實現轉換 | 10-Q / 10-K；簡報多給到小數 |
| **政府 vs 商業** | **合約 backlog 客戶別**，不是當季已認列營收 | 各季 investor update 圓餅圖 |
| 「單一政府客戶」% | 當期**已認列營收**裡超過 10% 門檻的那一名顧客 | 10-Q 客戶集中度附註 |

毛利率除非另註均為 **GAAP 部門毛利率**。公司另有 non-GAAP 公司毛利率（加回 SBC 等），不拆到部門。Q4 2025 部門毛利率由 **FY2025 − 前三季** 推算，因為 10-K 只給全年分部表。

### 總表

| | **25Q3** | **25Q4** | **26Q1** | **26Q2** |
| --- | --- | --- | --- | --- |
| **營收** | **$155.1M** | **$179.7M** | **$200.3M** | **$234.1M** |
| **營收 YoY** | **+48%** | **+36%** | **+63.5%** | **+62.0%** |
| 公司 GAAP 毛利率 | 37.0% | 38.0% | 38.2% | 36.1% |
| 公司 non-GAAP 毛利率 | ~44% | 44.3% | 43.0% | 41.5% |
| **Launch 營收 / 佔比** | **$40.9M / 26.4%** | **$75.9M / 42.2%** | **$63.7M / 31.8%** | **$44.6M / 19.1%** |
| **Launch GAAP 毛利率** | **58.1%** | **47.5%**† | **44.3%** | **42.9%** |
| **Space Systems 營收 / 佔比** | **$114.2M / 73.6%** | **$103.8M / 57.8%** | **$136.7M / 68.2%** | **$189.5M / 80.9%** |
| **Space Systems GAAP 毛利率** | **29.4%** | **31.0%**† | **35.3%** | **34.6%** |
| **Backlog** | **$1.096B** | **$1.847B** | **$2.220B** | **$2.356B** |
| **Backlog YoY** | **+4.6%** | **+73%** | **+108%** | **+137%** |
| **未來 12 個月轉換率** | **57%** | **37%** | **36%** | **45%**（簡報 / 電話會 **45.5%**） |
| 近 12 個月可認列約當 | ~$624M | ~$684M | ~$799M | ~$1.06–1.07B |
| Backlog：Launch / SS | 47% / 53% | 26% / 74% | 41.5–42% / 58–58.5% | **40% / 60%** |
| **Backlog：商業 / 政府** | **57% / 43%** | **35% / 65%** | **51% / 49%** | **57% / 43%** |
| 已認列：單一政府客戶 | 9M 累計 **29%** | 全年 **28%** | 單季 **36%** | H1 累計 **42%** |

† Q4 部門毛利率 = FY2025 分部 − 前三季 10-Q，不是單獨披露的 Q4 分部表。

精確金額（千美元，取自 SEC）：

| | 25Q3 | 25Q4 | 26Q1 | 26Q2 |
| --- | --- | --- | --- | --- |
| 總營收 | 155,080 | 179,652 | 200,348 | 234,066 |
| Launch 營收 / COGS / 毛利 | 40,921 / 17,163 / 23,758 | 75,883 / 39,808 / 36,075† | 63,663 / 35,440 / 28,223 | 44,586 / 25,476 / 19,110 |
| SS 營收 / COGS / 毛利 | 114,159 / 80,603 / 33,556 | 103,769 / 71,612 / 32,157† | 136,685 / 88,415 / 48,270 | 189,480 / 124,014 / 65,466 |
| Backlog | 1,095,977 | 1,847,322 | 2,219,756 | 2,355,949 |
| 去年同期 backlog | 1,047,555 | （官方 +73%） | 1,066,946 | 995,410 |

Q2 2026 10-Q 另把期末 backlog 拆成 Space Systems **$1,415.8M**、Launch **$940.2M**（60.1% / 39.9%），與電話會「約 40 / 60」一致。

### 怎麼讀這四季

**1. 營收在長，結構已切到造星。** 四季營收 $155 → $180 → $200 → $234M，YoY 從 +48% 再加速到 +62–64%。但 Launch 佔比從 Q4 的 42%（7 次發射的高峰季）掉到 Q2 的 **19%**；Space Systems 從 58% 升到 **81%**。Q2 Launch 營收 $44.6M 甚至低於一年前的 $46.6M（−4.4% YoY、−30% QoQ）——電話會解釋是當季 HASTE 有大量收入已在先前期間按 overtime 認列，不是發射次數崩掉。

**2. 發射毛利率從異常高往下回歸，造星毛利率在抬。**

| | Launch GM | 為什麼 |
| --- | --- | --- |
| 25Q3 **58.1%** | 含 overtime Electron **$13.3M 累計追認**，分子被一次抬高 |
| 25Q4 **47.5%** | 發射量最大的一季，固定成本吸收好，但仍低於 Q3 的一次性水位 |
| 26Q1 **44.3%** | 發射季減、mix 變差 |
| 26Q2 **42.9%** | 收入更薄，固定成本吸收變弱 |

Space Systems 相反：29.4% → 31.0% → **35.3%** → 34.6%。Q2 公司 GAAP 毛利率回落到 36.1%，主因是「略低毛利的整星平台」佔比上升（SDA + 剛併入的 Mynaric），不是發射把公司毛利拖垮。Q3 2026 指引 GAAP 毛利率 **29–31%**，代表這條 mix 壓力還沒走完。

**3. Backlog 金額翻倍，但 12 個月轉換率先塌再回。** Q3→Q4 因 SDA Tranche III（$816M、多年 overtime）把 backlog 從 $1.10B 拉到 $1.85B，轉換率從 **57% 掉到 37%**——大單進簿，近端能見度的「百分比」被稀釋。Q1 仍是 36%。Q2 回升到 **45–45.5%**，約當 **$10.6–10.7 億** 未來 12 個月營收，已經高於 FY2025 全年。Q3 本身 backlog YoY 只有 +4.6%（當時還沒接到 T3），之後才是 +73% / +108% / +137%。

**4. 政府 vs 商業要看 backlog，不要和「單一政府客戶營收%」互推。**

| 季 | Backlog 商業 / 政府 | 驅動 |
| --- | --- | --- |
| 25Q3 | **57 / 43** | T3 尚未進簿；發射預訂把 Launch 佔比抬到 47% |
| 25Q4 | **35 / 65** | SDA T3 單筆政府大單，政府端一次變成多數 |
| 26Q1 | **51 / 49** | $190M HASTE（政府）+ 5 發 Neutron 與大量 Electron 商業預訂，Launch 佔比回到 ~42%，客戶結構重新接近對半 |
| 26Q2 | **57 / 43** | 商業端再超前（簡報同期有 Kepler 等 Neutron 商業單） |

已認列營收的「單一政府客戶」走的是另一條線：9M’25 的 29% → FY2025 28% → Q1’26 **36%** → H1’26 **42%**。SDA overtime 開始認列後，**當季現金流比 backlog 圓餅更政府化**。FY2025 另有一條更寬的口徑：美國政府 + prime + 分包合計約 **47%** 營收——那是「政府生態系」，不是 backlog 圓餅上的 Government 切片。

**一季一句：** Q3 是高轉換、發射毛利被追認抬高的過渡季；Q4 是政府大單進簿、發射量與公司毛利率的高峰；Q1 是營收與 backlog 再創新高、結構回到對半；Q2 是造星公司的季——營收與 backlog 都創新高，但發射佔比與公司毛利率已經在往下，Q3 指引把這條壓力寫進了 29–31%。

資料：[Q3 2025 10-Q](https://www.sec.gov/Archives/edgar/data/1819994/000181999425000021/rklb-20250930.htm)、[FY2025 10-K](https://www.sec.gov/Archives/edgar/data/1819994/000181999426000013/rklb-20251231.htm)、[Q4 2025 investor update](https://investors.rocketlabcorp.com/static-files/be9441ad-c07f-49c2-ad50-531fd77180ee)、[Q1 2026 10-Q](https://www.sec.gov/Archives/edgar/data/1819994/000181999426000028/rklb-20260331.htm)、[Q1 2026 簡報](https://investors.rocketlabcorp.com/static-files/c0bd4327-c3ff-4843-8eae-8b0d8a4d4b82)、[Q2 2026 10-Q](https://www.sec.gov/Archives/edgar/data/1819994/000181999426000062/rklb-20260630.htm)、[Q2 2026 簡報](https://investors.rocketlabcorp.com/static-files/3dde8e68-7ce6-4685-8c0b-17afc94dbb86)、[Q2 2026 電話會](https://www.fool.com/earnings/call-transcripts/2026/08/17/rocket-lab-rklb-q2-2026-earnings-call-transcript/)、[Q3 2024 10-Q（去年同期 backlog）](https://www.sec.gov/Archives/edgar/data/1819994/000095017024125529/rklb-20240930.htm)、[Q2 2025 10-Q](https://www.sec.gov/Archives/edgar/data/1819994/000162828025038936/rklb-20250630.htm)

---

## 資料來源（主要）

1. [Rocket Lab FY2025 Q4 與全年新聞稿](https://investors.rocketlabcorp.com/news-releases/news-release-details/rocket-lab-announces-fourth-quarter-and-full-year-2025-financial)
2. [Rocket Lab FY2025 Form 10-K](https://investors.rocketlabcorp.com/static-files/57a8d0da-27ff-499c-8d85-18907743b7a8)
3. [Rocket Lab Q1 2026 新聞稿](https://investors.rocketlabcorp.com/news-releases/news-release-details/rocket-lab-announces-first-quarter-2026-financial-results)
4. [Rocket Lab Q2 2026 新聞稿](https://investors.rocketlabcorp.com/news-releases/news-release-details/rocket-lab-announces-second-quarter-2026-financial-results-posts)
5. [Q2 2026 Form 8-K / EX-99.1](https://www.sec.gov/Archives/edgar/data/1819994/000181999426000061/rklb-08102026ex991.htm)
6. [Q2 2026 財報電話會逐字稿（Motley Fool）](https://www.fool.com/earnings/call-transcripts/2026/08/17/rocket-lab-rklb-q2-2026-earnings-call-transcript/)
7. [Yahoo Finance RKLB 報價與目標價](https://finance.yahoo.com/quote/RKLB/)
8. [Yahoo Finance RKLB Analysis（共識）](https://finance.yahoo.com/quote/RKLB/analysis/)
9. [Yahoo Finance RKLB Key Statistics](https://finance.yahoo.com/quote/RKLB/key-statistics/)
10. [StockAnalysis RKLB Forecast](https://stockanalysis.com/stocks/rklb/forecast/)
11. [StockAnalysis RKLB Statistics](https://stockanalysis.com/stocks/rklb/statistics/)
12. [Simply Wall St 美國航太國防行業倍數](https://simplywall.st/markets/us/industrials/aerospace-and-defense)
13. [CSIMarket A&D Valuation](https://csimarket.com/Industry/industry_valuation_ttm.php?ind=201)
14. [FullRatio 行業利潤率](https://fullratio.com/profit-margin-by-industry)
15. [WEF / McKinsey：$1.8 兆太空經濟](https://www.mckinsey.com/industries/aerospace-and-defense/our-insights/space-the-1-point-8-trillion-dollar-opportunity-for-global-economic-growth)
16. [SpaceNexus 太空產業規模拆分](https://spacenexus.us/learn/space-industry-market-size)
17. [MarketIntelo 專屬小衛星發射市場](https://marketintelo.com/report/dedicated-smallsat-launch-market)
18. [SpaceNews：2025 全球發射統計](https://spacenews.com/spacex-china-drive-new-record-for-orbital-launches-in-2025/)
19. [Iridium 收購新聞稿](https://www.prnewswire.com/news-releases/rocket-lab-to-acquire-iridium-in-historic-deal-creating-a-fully-vertically-integrated-space-powerhouse-primed-for-growth-302813075.html)
20. [Iridium 8-K 交易條款](https://www.sec.gov/Archives/edgar/data/1418819/000110465926078483/tm2619278d1_ex99-1.htm)
21. [Via Satellite：FY2025 部門增速與 Neutron 延期](https://www.satellitetoday.com/finance/2026/02/27/rocket-lab-hits-record-revenue-in-25-but-delays-neutron-to-late-26/)
22. [Motley Fool：59x 營收估值評論](https://www.fool.com/investing/2026/08/22/rocket-lab-trades-at-59-times-revenue-with-neutron-still-unflown/)

---

*第 1–2 頁架構對應：步驟 1–4 為估值與基本面；步驟 5–7 為護城河、風險與結論。僅為報告參考，非投資建議。*

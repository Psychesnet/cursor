# AVGO 現代價值投資報告

**基準日：** 2026 年 9 月 5 日  
**標的：** Broadcom Inc.（Nasdaq: AVGO）  
**股價基準：** Nasdaq 2026-09-04 收盤 US$357.90（Q3 FY2026 於 9/2 盤後公布後的最近交易日）；市值約 US$1.70 兆  
**聲明：** 僅為報告參考，非投資建議。

---

## 步驟一：Known - 熟悉度評估

分析重點：釐清賺錢方式、產業位置與受眾，判斷商業模式是否清晰。

### 業務模式

Broadcom 是**無晶圓廠（fabless）半導體設計商＋企業基礎設施軟體商**，位於半導體價值鏈的**設計／IP 整合端**，晶圓代工與先進封裝外包（主要為 TSMC 等），自身保留部分濾波器（FBAR）產能。它賣的不是消費品牌終端，而是雲端與企業「買不到替代品就不建得成」的關鍵矽與軟體：

1. **客製 AI 加速器（XPU／ASIC）**：與 Google TPU、Meta MTIA、OpenAI Jalapeno、Anthropic 等共同設計，針對特定 LLM／推理工作負載優化；管理層稱可做到「效能比肩 GPU、成本約一半」。
2. **AI 網路矽**：Tomahawk／Jericho 乙太網路交換、PCIe 交換、光學 DSP／EML／VCSEL，覆蓋 scale-out 與開始進入的 scale-up。
3. **非 AI 半導體**：寬頻、無線（含 iPhone FBAR 濾波器）、企業儲存／光纖通道、工業。
4. **基礎設施軟體**：2023 年收購 VMware 後，以 VMware Cloud Foundation（VCF）為核心，加上 Symantec 資安、CA 主機軟體，賣給 Fortune 500 與政府的私有雲／混合雲訂閱。

**模式清晰度：高。** 兩條報表分部（Semiconductor Solutions、Infrastructure Software）對得上兩種賺錢邏輯：高轉換成本的客製矽，以及高毛利、高續約的企業軟體。Q3 起 AI 半導體已佔總營收 56%，商業模式的「成長引擎」已明確切到客製加速器＋乙太網路。

來源：[FY2025 10-K](https://investors.broadcom.com/static-files/5868c796-2455-4855-9f02-3410b11e99e1)、[Q3 FY2026 新聞稿](https://investors.broadcom.com/news-releases/news-release-details/broadcom-inc-announces-third-quarter-fiscal-year-2026-financial)、[Q3 法說會整理](https://www.tradingkey.com/news/transcripts/262147548-tradingkey)

### 收入來源

**FY2025（迄 2025-11-02）總營收 US$638.87 億**

| 分部 | 營收 | 佔比 | YoY |
| --- | --- | --- | --- |
| 半導體解決方案 | US$368.58 億 | 58% | +22% |
| 基礎設施軟體 | US$270.29 億 | 42% | +26% |

其中 AI 半導體全年約 **US$203 億**（由 FY2026 AI 指引 US$580 億、+186% 反推）。

**Q3 FY2026（更能代表當前賺錢方式）總營收 US$295.91 億**

| 項目 | 營收 | 佔總營收 | YoY |
| --- | --- | --- | --- |
| 半導體 | US$208.39 億 | 70% | +127% |
| └ AI 半導體 | US$167 億 | 56% | +221%（QoQ +54%） |
| └ 非 AI 半導體 | US$42 億 | 14% | +5% |
| 基礎設施軟體 | US$87.52 億 | 30% | +29%（ARR +15%） |

AI 內部：XPU 出貨年增逾 3.5 倍、佔 AI 營收 **73%**；AI 網路年增逾 2.5 倍。軟體單季毛利率 94%、營運利潤率約 84%。

來源：[FY2025 8-K／業績](https://investors.broadcom.com/static-files/dd25b8a9-a65a-4125-b02b-b1a6eb154cde)、[Q3 FY2026 新聞稿](https://investors.broadcom.com/news-releases/news-release-details/broadcom-inc-announces-third-quarter-fiscal-year-2026-financial)

### 客戶群體

**純 B2B。** 終端買家是超大規模雲、前沿模型實驗室、電信與消費電子 OEM、以及大型企業／政府 IT。

- **AI／雲：** 六家 XPU 客戶。法說點名 Google（TPU v7 Ironwood 放量、TPU v8i 已量產，簽署未來數代 TPU＋網路的多年協議，規劃每年數百億美元級出貨）、Anthropic（2027 年 5GW TPU v8i、2028 年再 10GW，管理層預期 2027–2028 成最大 XPU 客戶）、OpenAI（Jalapeno 2027 年 1.3GW、2028 年逾 5GW）、Meta（三個世代 MTIA，至 2028 年可見 3GW）。其餘兩家未在 Q3 點名。
- **軟體：** VMware／VCF 服務約 4,500 家大型企業與多數 Fortune 500、政府機構；Q3 推出 VMware Private AI Cloud。
- **集中度：** FY2025 前五大**終端**客戶合計約 **40%** 營收；經銷商通路佔 48%；半導體分部單一客戶（通路／OEM）佔總營收 **32%**。Q3 AI 已佔 56%，集中度在上升而非下降。
- **地理（出貨地，非終端使用地）：** FY2025 美洲 29.6%、亞太 56.2%、EMEA 14.2%。美國 US$165.06 億、中國含香港 US$111.55 億、新加坡 US$107.96 億、台灣 US$64.51 億。公司明確指出大量運往中國的貨最終進入美歐終端產品。

來源：[FY2025 10-K 客戶／地區](https://investors.broadcom.com/static-files/5868c796-2455-4855-9f02-3410b11e99e1)、[Q3 法說會整理](https://www.tradingkey.com/news/transcripts/262147548-tradingkey)

---

## 步驟二：Growth - 增長分析

分析重點：成長是否強勁、是否在擴張賽道、短中長期能否延續。

### 總收入與 YoY

| 期間 | 營收 | YoY |
| --- | --- | --- |
| FY2024 | US$515.74 億 | +44.0%（含 VMware 併入） |
| FY2025 | US$638.87 億 | **+23.9%** |
| Q1 FY2026 | US$193.11 億 | +29% |
| Q2 FY2026 | US$221.87 億 | +48% |
| Q3 FY2026 | US$295.91 億 | **+86%** |
| Q4 FY2026 指引 | 約 US$348 億 | **+93%** |
| FY2026 隱含 | 約 US$1,059 億 | **約 +66%** |

YTD 三季 US$710.89 億 vs 去年同期 US$458.72 億（+55%）。**遠超過 10%／20% 成長標準。**

來源：[FY2025 8-K](https://investors.broadcom.com/static-files/dd25b8a9-a65a-4125-b02b-b1a6eb154cde)、[Q1 新聞稿](https://investors.broadcom.com/news-releases/news-release-details/broadcom-inc-announces-first-quarter-fiscal-year-2026-financial)、[Q3 新聞稿](https://investors.broadcom.com/news-releases/news-release-details/broadcom-inc-announces-third-quarter-fiscal-year-2026-financial)

### 未來增長指引

| 口徑 | 數字 | 含義 |
| --- | --- | --- |
| 公司 AI 半導體 | FY2026 **US$580 億**（+186%，由前次 US$560 億上修） | 已鎖定供給 |
| 公司 AI 半導體 | FY2027 約 **US$1,150 億**（再翻倍） | 需求高於該數字，供給為約束 |
| 公司 AI 半導體 | FY2028 約 **US$2,300 億**（再翻倍） | 供給已鎖定；Street 原約 US$1,770 億 |
| 公司 EPS | FY2028 **超過 US$30**（non-GAAP） | Street 原約 US$26.4 |
| Yahoo 共識營收 | FY2026 US$1,059.7 億（+66%）、FY2027 US$1,734.3 億（+64%） | Q3 後尚未完全消化 US$2,300 億 AI |
| Yahoo 共識 EPS | FY2026 US$11.64、FY2027 US$19.37 | 對 $357.90 → 30.8x／18.5x |
| StockAnalysis | 未來 3 年營收成長預估 **57.16%**、EPS **59.69%** | 遠超 20% 標準 |
| MarketScreener | FY2028 營收共識 US$2,322 億 | **低於**「僅 AI 就 US$2,300 億」的公司路徑 |

以 FY2025 US$638.87 億 → Street FY2028 US$2,322 億，3 年營收 CAGR 約 **53.8%**。若 AI 真走到 US$2,300 億，合計營收更接近 US$2,800 億量級（加上非 AI 半導體約 US$180 億與軟體約 US$350 億），CAGR 將更高。**遠超過 20% 標準。**

來源：[Yahoo Finance Analysis](https://finance.yahoo.com/quote/AVGO/analysis/)、[StockAnalysis Statistics](https://stockanalysis.com/stocks/avgo/statistics/)、[MarketScreener](https://www.marketscreener.com/quote/stock/BROADCOM-INC-199910242/finances/)、[Q3 法說](https://www.tradingkey.com/news/transcripts/262147548-tradingkey)

### 市場空間（TAM）與大 M／小 M／SAM

Broadcom 同時吃三條賽道：客製 XPU、AI 乙太網路（交換＋光學）、企業私有雲軟體。下面用「大盤 → 真正在打的細分 → 公司拿得到的份」拆開。舊的研究機構「客製 ASIC 2025 年僅 US$92.5 億」已失效——Broadcom 單家 FY2026 AI 指引就是 US$580 億。

| 層級 | 賽道 | 規模與增速 | 對 AVGO 的意義 |
| --- | --- | --- | --- |
| **大 M** | 全球半導體 | 2025 **US$8,090 億** → 2026 **US$1.555 兆**（+92%）→ 2027 **US$1.940 兆**（Gartner，2026-08-24） | 大盤被記憶體拉高；Broadcom 吃的是非記憶體／系統矽 |
| **大 M** | AI 資料中心半導體生態 | 2026 佔全球半導體 **36.5%**（約 US$5,680 億）→ 2030 **超過 53%**（Gartner） | 這才是 Broadcom 成長所在的「大池」 |
| **大 M** | AI 加速器晶片 | 2024 US$1,160 億 → 2033 US$6,040 億，CAGR **16%**；其中客製 ASIC CAGR **27%**（Bloomberg Intelligence，2026-01） | GPU 仍主導大盤；客製 ASIC 是更快的子曲線 |
| **小 M** | 客製 XPU／AI ASIC（Broadcom 實際在賣的加速器） | 公司路徑：FY2025 約 **US$203 億** → FY2026 **US$580 億**（+186%）→ FY2027 **US$1,150 億** → FY2028 **US$2,300 億**。內容約 **US$200–300 億／GW** | 這條小 M 已被公司訂單改寫；研究機構 2025 年「US$92 億」口徑過時，不再採用 |
| **小 M** | AI 後端交換（scale-up／scale-out／scale-across） | Dell'Oro：2026–2030 **累計接近 US$1 兆**；2026 Q1 乙太網路已佔 AI 叢集交換約 **2/3**；2026 Q2 後端交換銷售首度超過前端。650 Group：資料中心網路十年末約 **US$2,000 億／年**；AI scale-out 乙太網路 2030 **超過 US$1,000 億**；scale-up 交換 2030 **超過 US$300 億**（另加光學 US$100 億+） | 管理層稱 AI 網路未來數年增速將與 XPU 相當；Tomahawk 6／7／Ultra 同時打 scale-out 與 scale-up |
| **小 M** | 企業私有雲／SDDC 軟體 | 企業私有雲基礎設施：2025 **US$333 億** → 2034 **US$1,739 億**，CAGR **20.0%**（Research Intelo）。軟體定義資料中心：2025 **US$1,456 億** → 2030 **US$3,516 億**，CAGR **19.2%** | FY2026 軟體隱含約 US$314 億，已是私有雲軟體堆疊的核心供應商，不是「小玩家等市場長大」 |
| **SAM** | Broadcom 可服務市場 | 客製 ASIC 共設計約 **60%** 市佔（Marvell 約 35%）；高階乙太網路交換矽約 **80%**；VCF 為全球部署最廣的私有雲軟體堆疊。可服務 = XPU＋交換 ASIC＋光學 DSP／雷射＋VCF／資安，不是單賣一顆加速器 | SAM 大於「晶片 TAM」：一 GW 內容含加速器、交換、光學 |
| **SOM** | 已拿下的份額 | 六家 XPU 客戶；Q4 FY2026 AI 指引年化約 **US$868 億**；FY2028 AI 路徑 **US$2,300 億**。若對照 BI 2033 加速器 US$6,040 億，公司 2028 年單年 AI 已相當於該終點市場的約 38%——代表要嘛市佔極高、要嘛公開 TAM 仍低估客製矽＋網路 | 能見度在六家客戶的 GW，不在散戶 GPU |

**讀法：** 大 M 確認賽道夠大（AI 資料中心將吃掉半個半導體業）；小 M 確認 Broadcom 打的是增速更快的客製矽與乙太網路，不是跟 NVIDIA 搶通用 GPU；SAM／SOM 確認它已經是這兩條細分的龍頭，限制在供給與機房，不在「市場太小」。

來源：[Gartner 2026-08-24 半導體預測（TechEdgeAI 轉述）](https://techedgeai.com/gartner-forecasts-worldwide-semiconductor-revenue-to-reach-1-6-trillion-in-2026/)、[Gartner 原文](https://www.gartner.com/en/newsroom/press-releases/2026-08-24-gartner-forecasts-worldwide-semiconductor-revenue-to-reach-1-trillion-dollars-in-2026)、[Bloomberg Intelligence AI 加速器](https://www.bloomberg.com/company/press/ai-accelerator-market-looks-set-to-exceed-600-billion-by-2033-driven-by-hyperscale-spending-and-asic-adoption-according-to-bloomberg-intelligence/)、[Dell'Oro AI 後端交換 US$1 兆](https://www.prnewswire.com/news-releases/ai-back-end-switch-sales-to-approach-1-trillion-over-the-next-five-years-according-to-delloro-group-302831878.html)、[Dell'Oro 2026 Q2 後端超過前端](https://www.prnewswire.com/news-releases/ai-back-end-networks-switch-sales-surpass-front-end-networks-for-the-first-time-in-2q2026-according-to-delloro-group-302866912.html)、[650 Group 資料中心網路 US$2,000 億](https://650group.com/blog/in-the-ai-era-ethernet-set-to-surge-in-scale-out-and-ramp-in-scale-up/)、[Research Intelo 私有雲](https://researchintelo.com/report/enterprise-private-cloud-infrastructure-market)、[SDDC 市場](https://www.knowledge-sourcing.com/report/software-defined-data-center-market)、[Q3 法說 GW／內容](https://www.tradingkey.com/news/transcripts/262147548-tradingkey)

### 業務部門增長與驅動力

| 板塊 | 最新增速 | 驅動力 |
| --- | --- | --- |
| AI 半導體 | Q3 +221%；FY26 指引 +186% | XPU（Google TPU v7／v8i、OpenAI Jalapeno、Meta MTIA）＋ Tomahawk 6／Ultra |
| 非 AI 半導體 | Q3 +5%、持平 QoQ | 寬頻與伺服器儲存部分抵銷無線下滑；已不是成長引擎 |
| 基礎設施軟體 | Q3 +29%，ARR +15% | VMware 訂閱化尾聲＋ Private AI Cloud；Q1 僅 +1%，Q3 才重新加速 |
| 半導體整體 | Q3 +127%，佔比由 FY25 的 58% 升至 70% | AI 混比提升 |

**主要驅動力是客製 XPU 放量，第二引擎是 AI 網路（管理層稱未來數年增速將與 XPU 相當）。** 軟體提供現金流與利潤率緩衝，不再是併購後的一次性跳升。

### 增長持續性

支持延續的硬證據：

1. **近季指引能見度：** Q4 總營收 US$348 億、AI US$217 億；FY2026 AI US$580 億。
2. **跨年供給鎖定：** 管理層稱 FY2027 US$1,150 億與 FY2028 US$2,300 億的 AI 出貨「供給已鎖定」；兩年合計約 US$3,500 億 AI 半導體。需求高於該數字，卡點是資料中心土地／電力／機殼能否按財年窗口就緒。
3. **客戶 GW 路徑：** Anthropic 2027–2028 共 15GW、OpenAI 2027–2028 逾 6.3GW、Meta 至 2028 年 3GW，加上 Google 每年「數十億美元級」TPU。不是單一季度的現貨訂單。
4. **產品節奏：** Tomahawk 6 已在幾乎所有與 Broadcom 做 XPU 的 hyperscaler 部署（含不用其 XPU、只用交換的客戶）；Tomahawk 7（業界首款 200 Tbps）已 tape-out；新加坡基板產能 FY2027 開始貢獻。

限制項：這是「供給與機房就緒約束成長」的模式。砍單不會先表現為需求消失，而會表現為「延後提貨、少部署幾個 GW」。毛利率也會因 XPU 記憶體含量上升而被稀釋（Q4 指引合併毛利率約 73%，低於一年前 78%）。

---

## 步驟三：Valuation - 估值評估

分析重點：以成長與護城河衡量現價是否合理，並量化潛在空間。

股價與倍數基準：AVGO **US$357.90**（2026-09-04 收盤），[StockAnalysis](https://stockanalysis.com/stocks/avgo/statistics/)。盤後約 US$357.07。市值約 US$1.70 兆（47.6 億股 × $357.90），較 Q3 公布當日收盤 $367.24 回落約 2.5%。

### 當前估值對比

| 指標 | AVGO | 行業 | 判斷 |
| --- | --- | --- | --- |
| PE（TTM GAAP） | **45.71**（$357.90 ÷ EPS $7.83；StockAnalysis 刊 45.59） | 美股半導體簡單平均 **45.8x**、市值加權 Absolute PE **20.5x**（Simply Wall St, 9/4） | 對簡單平均**約略持平**；對加權平均**偏貴**（加權被超高獲利巨頭壓低） |
| PS（TTM） | **19.11**（市值 US$1.70 兆 ÷ TTM 營收 US$891 億） | **7.8x** | **高於行業**（高毛利＋高增長的典型溢價） |
| P/FCF | **43.21**（TTM FCF US$394 億） | 大型同業約 **40–47x**（NVDA 報告口徑） | **與大型同業相當** |

解讀：以 TTM GAAP PE 看，並不便宜；但 TTM 還含較低的 FY2025 基期，而 Q3 單季 non-GAAP EPS 已達 $3.32、年化遠高於 TTM。真正該看的是遠期 PE。Yahoo 仍顯示 Trailing PE 61x（EPS $5.99），那是**尚未計入 Q3** 的過期數字，本報告不用。

來源：[StockAnalysis Statistics](https://stockanalysis.com/stocks/avgo/statistics/)、[Simply Wall St US Semiconductors](https://simplywall.st/markets/us/tech/semiconductors)、[Yahoo Key Statistics](https://finance.yahoo.com/quote/AVGO/key-statistics/)

### 預期 PE

以 US$357.90 與 Yahoo／公司數字計算：

| 年度 | EPS（non-GAAP, US$） | 預期 PE |
| --- | --- | --- |
| FY2026（Yahoo 共識） | 11.64 | **30.75x** |
| FY2027（Yahoo 共識） | 19.37 | **18.48x** |
| FY2028（公司目標） | >30.00 | **約 11.93x** |
| FY2028（Q3 前 Street 約 26.38） | 26.38 | 13.57x |

**三年平均預期 PE = (30.75 + 18.48 + 11.93) / 3 = 20.38 倍。**  
StockAnalysis Forward PE 20.64 倍，與三年平均接近。PEG（18.48 ÷ 57.16% 成長）約 **0.32**，遠低於 1.0。

### 合理估值依據

給予倍數的理由：

- 未來 3 年營收／EPS CAGR 約 54–60%，AI 路徑還是連續翻倍，屬於「超高增長」而非普通半導體週期。
- 非 GAAP 毛利率約 75%、營運利潤率約 67%，軟體端 84%，現金轉換極強（Q3 FCF／營收 46%）。
- 客製 ASIC 約 60% 市佔、高階乙太網路交換約 80%，轉換成本以「晶片世代」計，不是季度標案。

扣分項：六家 XPU 客戶過濃、XPU 記憶體含量稀釋毛利率、淨負債仍約 US$354 億、FY2028 US$2,300 億取決於機房與 HBM／基板供給。因此不給 40x 以上的「AI 泡沫倍數」，而給 **28–34 倍**，中值 **31 倍**——與同架構 NVDA 報告的 31.5 倍中樞對齊，略低於其理論 35–40x 上沿。

### 潛在價值空間

\[
(31 \div 20.38 - 1) \times 100\% \approx \mathbf{52.1\%}
\]

- 若改用保守 28 倍：約 **37.4%**。
- 若改用 34 倍：約 **66.8%**。
- 49 位分析師平均目標價 **US$533.41**，隱含 **49.0%** 上檔（StockAnalysis），與 31 倍中樞接近。

**結論：價值空間充足。** 現價貴在 TTM，不便宜在「已公布的兩年 AI 路徑」。

### 情景分析：PE = 35／28／22

現價 $357.90 已經隱含 **FY2026 30.75x、FY2027 18.48x、FY2028 11.93x**。因此這三個倍數不是「三種目標價算式」而已，而是市場願意把 AVGO 放在哪一檔成長股的定價體制。先看隱含股價，再看每個體制該盯的數據。

**隱含股價矩陣（EPS 不變時，只改倍數）**

| 倍數 | × FY26 EPS $11.64 | × FY27 EPS $19.37 | × FY28 EPS $30 | 對現價的三年平均法（現 20.38x → 該倍數） |
| --- | ---: | ---: | ---: | ---: |
| **35x** | **$407**（+14%） | **$678**（+89%） | $1,050 | **$615**（+72%） |
| **28x** | **$326**（−9%） | **$542**（+52%） | $840 | **$492**（+37%） |
| **22x** | **$256**（−28%） | **$426**（+19%） | $660 | **$386**（+8%） |

讀法：近一年市場多半用 **FY26／NTM** 報價；若故事成立，資金會改看 **FY27**。現價 30.8x FY26，已經接近 35x 情景的「今年獲利」；要再漲，必須靠 **EPS 上修** 或 **市場改看明年**。跌到 22x FY26（$256）則代表市場不再願意看穿，只肯買「今年賺到的」。

Yahoo FY27 EPS 區間 $17.47–$22.44，是倍數之外第二條槓桿：28x × $17.47 = $489；35x × $22.44 = $785。

#### PE = 35：溢價成長股（上沿重評）

**市場在買什麼：** 把 AVGO 當稀缺 AI 基礎設施，願意在 NTM 給 NVIDIA 級成長溢價。現價 30.8x FY26，升到 35x 只需約 +14%；真正的 35x 紅利在「市場改用 FY27 $19.37」→ 約 $678。

**該觀察的關鍵數據（以及原因）：**

| 觀察項 | 通過標準 | 為什麼決定 35x 能不能站住 |
| --- | --- | --- |
| 單季 AI 半導體營收 | Q4 ≥ **$217 億**；FY26 落地 **$560–580 億**；FY27 年化 run-rate 明顯朝 **$1,150 億** | 35x 買的是「再翻倍兩年」；AI 美元數是唯一不可替代的驗證 |
| AI 的 QoQ | 不再出現連續兩季 QoQ <10%（Q3 才 +54%） | 倍數擴張靠加速度；QoQ 變平，市場會立刻把視線從 FY27 拉回 FY26 |
| XPU vs AI 網路拆分 | XPU 仍約 **70%+**，且網路 YoY 仍能跟 XPU「同級增速」 | 兩個引擎同時轉，才能說服市場這不是單一客戶的 ASIC 訂單 |
| non-GAAP 營運利潤率 | 守住 **≥66%**（Q4 指引 66%），即使毛利率落到 ~73% | 35x 不容許「成長但賺不到」；營運槓桿是溢價的護欄 |
| Street FY27 EPS 修正方向 | 從 $19.37 **上修**（高標 $22.44）而非下修 | 倍數 × EPS 雙升才會走出 $407 以上；只升倍數、EPS 不動，空間有限 |
| 客戶 GW／新客戶 | Google 多世代續約被複述；Anthropic／OpenAI／Meta 的 GW **未延後**；出現第 7 家或既有客戶加碼 | 35x 的核心折價是六家集中；能見度變厚，溢價才合理 |
| 超大規模雲 capex 語調 | GOOG／META／MSFT／AMZN 法說不出現「AI 基建減速」 | 買家即需求本身；他們砍 capex，35x 會在一週內崩回 28x |

**進入條件：** Q4 達標＋管理層維持 FY27／28 AI 路徑＋Street 上修 FY27。**退出條件：** AI QoQ 急減速，或單一點名客戶延後 GW。

#### PE = 28：基本／保守合理（報告下沿）

**市場在買什麼：** 「好公司、成長仍在，但要扣客戶集中與毛利率混比」。這是本報告 28–34x 的下沿。現價 30.8x FY26 **略高於 28x**，若市場把 NTM 壓回 28x 而 EPS 不變，股價先到 **$326（−9%）**；若改看 FY27，28x 仍值 **$542（+52%）**。

**該觀察的關鍵數據（以及原因）：**

| 觀察項 | 通過標準 | 為什麼決定 28x 是「合理」而不是「轉空」 |
| --- | --- | --- |
| 合併毛利率地板 | non-GAAP 停在 **72–74%**，不要從 73% 再連滑兩季到 <70% | 28x 已預扣「XPU 記憶體稀釋」；再破就是結構惡化，倍數會滑向 22x |
| FY26 AI 是否「達標但不爆」 | 全年落在 **$560–600 億**（指引 $580 億附近） | 28x 對應 in-line 執行：沒有驚喜重評，也沒有指引下修 |
| 軟體 ARR | 維持 **+10–15%**，軟體佔比不要掉到 <25% | 這是 28x 相對於純 GPU 股的「現金墊」；軟體再失速，折價要加大 |
| 前五大／六家 XPU 集中度 | 沒有單一客戶公開延後；10-K 前五大終端不要明顯升破 40% 太多 | 28x 的扣分項是集中度「已知」；變成「正在惡化」就不該再給 28x |
| FCF／營收 | 維持 **>40%**（Q3 為 46%） | 28x 還要求現金轉換證明獲利品質；FCF 掉到 30% 以下，市場會改看負債 |
| 第二供應商新聞 | 聯發科 TPU／Marvell 訂單停留在「補充」而非「取代」 | 28x 能容忍雙源；不能容忍份額被切走一整個世代 |
| 淨負債／EBITDA | 維持 **<1.5x**（目前 1.14x） | 28x 假設財務已不是故事；槓桿回升會讓防禦溢價消失 |

**進入條件：** 業績 in-line、毛利率不再急滑、沒有客戶事故。**退出向上：** Street 連兩季上修＋AI QoQ 再加速 → 往 35x。**退出向下：** 毛利率或指引失守 → 往 22x。

#### PE = 22：壓縮／不再看穿（空頭體制）

**市場在買什麼：** 不再把 AVGO 當「再翻倍兩年」的趨勢股，改當普通高獲利半導體，只肯買今年賺到的。22x × FY26 $11.64 = **$256（−28%）**——這才是真正的回撤情景。22x × FY27 仍有 $426（+19%），但空頭體制的特徵正是**市場拒絕用明年 EPS**。三年平均法下 22x 只比現價高 8%（$386），因為現價三年平均 PE 已是 20.4x。

**該觀察的關鍵數據（以及原因）：**

| 觀察項 | 危險訊號 | 為什麼會把倍數壓到 22x |
| --- | --- | --- |
| 指引 vs 共識 | Q4 AI **明顯低於 $217 億**，或 FY26 AI 被下修到 **<$500 億** | 路徑一旦從「供給鎖定」變成「需求／機房跟不上」，市場立刻去看穿溢價 |
| AI 的 QoQ | 單季 QoQ 轉平或轉負 | 成長股最怕的不是 YoY 仍高，而是加速度消失；YoY 會落後 QoQ 兩個季度 |
| 點名客戶 | Anthropic／OpenAI／Google／Meta 任一 GW **延後一個財年**，或公開導入第二供應商放量 | 六家裡少一家，FY27 $1,150 億就不再可信 |
| 超大規模雲 capex | 兩家以上 hyperscaler 同期講「優化／延後 AI 基建」 | 需求是同一群買家；這是 22x 最常見的宏觀觸發 |
| 利潤率 | non-GAAP 毛利率 **<70%** 或營運利潤率 **<60%** | 「貴在成長」變「成長把利潤吃掉」；PE 與 PEG 同時壞掉 |
| Street FY27 EPS | 從 $19.37 往 **$17.47（目前低標）以下** 連兩次下修 | 22x 往往伴隨 EPS 下修，股價是倍數 × 獲利雙殺 |
| 庫存／應收 | 庫存與 AR 增速持續快於營收（Q3 庫存已 $45 億、AR $137 億） | 分辨「真實提貨」vs「通道堆積／提前出貨」 |
| 地緣／出口 | 對先進封裝、HBM 或對中出貨的新管制 | 供給與 17% 中國出貨地同時受創，無法用降價換量 |

**進入條件：** 指引下修或客戶延後＋Street 砍 FY27。**在 22x 體制裡要看到什麼才考慮回補：** AI QoQ 重新轉正、FY26 AI 仍能守住 $500 億以上、毛利率止跌、至少一家 hyperscaler 重申 capex。在那之前，用 FY28 $30 去乘 22x（$660）會嚴重高估可實現價格。

#### 三檔之間怎麼切換（實務觀察順序）

每季財報後用同一組領先指標判斷，不要先看股價再找理由：

1. **AI 美元數與 QoQ**（決定市場看今年還是看明年）
2. **毛利率／營運利潤率**（決定溢價有沒有護欄）
3. **Street FY27 EPS 修正方向**（倍數與獲利是否同向）
4. **點名客戶 GW 與 hyperscaler capex**（需求是不是還在）
5. **軟體 ARR 與 FCF 轉換**（下跌時的緩衝有多厚）

對照：①＋③ 向上且 ② 守住 → 往 **35x**；① 達標但 ② 或客戶集中度沒改善 → 停在 **28x**；① 或 ④ 失守 → 往 **22x**，而且要改用 FY26 EPS 计价。

---

## 步驟四：Profitability - 盈利能力

分析重點：賺錢效率、成本控管與財務健康。

產業對照：NYU Stern／Damodaran（2026 年 1 月）半導體毛利率 58.97%、營運利率 40.37%、淨利率 30.45%。

### 利潤率指標

| 指標 | AVGO | 行業 | 判斷 |
| --- | --- | --- | --- |
| 毛利率 | FY2025 GAAP **67.8%**／non-GAAP **78.7%**；Q3 non-GAAP **75%**（QoQ -210bp，因 AI 混比）；TTM GAAP 約 69% | 59.0% | **遠超 30% 標準，優於行業** |
| 營運利潤率 | FY2025 GAAP 39.9%／non-GAAP **65.7%**；Q3 GAAP 53.9%／non-GAAP **67.9%**；半導體 61%、軟體約 **84%** | 40.4% | **遠優於行業**（看 non-GAAP／分部更公允，GAAP 含併購攤銷） |
| 淨利率 | FY2025 GAAP 36.2%（含一次性稅務利益）；Q3 GAAP 44.2%／non-GAAP 55.3%；TTM GAAP **42.9%** | 30.5% | **優於行業** |

Q4 指引合併毛利率約 73%、營運利潤率仍約 66%——管理層用營運槓桿對沖毛利率稀釋。這是結構性現象（XPU 帶更多 HBM），不是成本失控。

### 股東回報

- **股權回購／稀釋：** StockAnalysis 近一年股本 **+1.00%**（淨稀釋）；五年平均約 **-3.0%／年**（FY2024 VMware 換股 -11.85% 是主因）。FY2026 前三季回購 US$84.5 億（幾乎全在 Q1 的 US$78 億），Q3 未再回購、改為還債 US$56 億。SBC 仍高（FY2025 US$75.7 億、Q3 單季 US$20.2 億）。**結論：歷史因併購與 SBC 稀釋；近四季開始用 FCF 回購，但尚未穩定收縮股本。**
- **股息率：** 年化 US$2.60 ÷ $357.90 = **0.73%**。連續 15 年調升，FY2026 季息 +10% 至 US$0.65。略低於／接近半導體行業約 0.8%。屬「成長股附帶股息」，不是收益型。

### 資本效率與安全

- **ROIC：** TTM **30.54%**（FY2025 20.38% → 隨 AI 放量跳升），WACC 約 12.0%，經濟利潤為正。五年：2021 15.6% → 2022 25.6% → 2023 31.3% → 2024 11.1%（VMware 併入資本膨脹）→ 2025 20.4% → 目前 30.5%。
- **利息覆蓋率：** TTM EBIT／利息約 **14.1 倍**（StockAnalysis 14.09）；Q3 單季 GAAP 15,955／778 = **20.5 倍**。遠高於「>2 即安全」。
- **負債：** 總帶息負債約 US$594 億、現金 US$240 億、淨負債約 US$354 億。Q3 還本 US$56 億，季後再還 US$15 億。固定利率本金 US$596 億、加權票息 **4%**、平均到期 7.4 年。負債／EBITDA 已由 FY2024 的 2.65 降至目前 **1.13**。財務風險從「VMware 槓桿收購」轉為「可用一年 FCF 覆蓋淨負債」。

來源：[Q3 新聞稿資產負債與現金流](https://investors.broadcom.com/news-releases/news-release-details/broadcom-inc-announces-third-quarter-fiscal-year-2026-financial)、[StockAnalysis Ratios](https://stockanalysis.com/stocks/avgo/financials/ratios/)、[Damodaran 行業利潤率](https://christopholivierconsulting.com/profit-margin-by-industry/)

---

## 步驟五：Moat - 護城河評估

各項 0–1.0，總分 5.0。

### 成本優勢　0.9 / 1.0

無晶圓廠把重資產 CapEx 轉給代工／HBM／基板。FY2025 資本支出僅 US$6.23 億（營收的 1.0%）；FY2026 前三季 CapEx US$10.1 億，對照同期 FCF US$319.4 億。Q3 FCF 利潤率 **46%**。半導體分部 OpEx 僅佔該部營收 **6%**、營運利潤率 61%；軟體營運利潤率約 84%、毛利率 94%。VMware 併購後的成本裁減已反映在利潤率而非還在「承諾階段」。扣 0.1：XPU 記憶體含量上升使合併毛利率從 ~78% 走向 ~73%，這是產品組合代價，不是規模不經濟。

### 網絡效應　0.8 / 1.0

兩層鎖定：（1）XPU 共設計週期跨數個製程世代，客戶把編譯器、模型與叢集拓樸綁在特定架構上，轉換成本是「重做一顆晶片＋重佈機房」，Google 已簽未來數代 TPU；（2）Tomahawk 乙太網路是開放標準生態，hyperscaler 用它同時連接 XPU 與 GPU，形成「即使不用 Broadcom 加速器也要用 Broadcom 交換」的附著。VMware／VCF 有高轉換成本，但企業虛擬化並非雙邊網絡。扣 0.2：沒有 CUDA 那種百萬開發者平台；乙太網路開放性同時降低專有鎖定。

### 品牌優勢　0.7 / 1.0

在資料中心網路上，「Tomahawk」幾乎等於高階交換矽的預設規格；在客製加速器上，Broadcom 是 Google TPU 十年夥伴的代名詞。這是**採購規格品牌**，不是消費品牌，Interbrand 全球榜上的能見度遠低於 NVIDIA。AI 營收爆發強化了「能把客製矽按時量產」的商譽，但可替代敘事（Marvell、聯發科介入 TPU）仍然存在。

### 技術門檻　0.9 / 1.0

截至 2025-11-02 約 **19,000** 件已獲專利、**2,170** 件申請中；33,000 名員工中 **57%** 在研發；FY2025 R&D US$109.8 億（營收 17.2%）。管理層把護城河說成：業界領先 SerDes、晶片間互連、HBM／SRAM 整合、先進封裝，以及「從定義到量產最快」。TPU v8i 量產進度領先更早啟動的聯發科版本；Tomahawk 7 為業界首款 200 Tbps 交換；Jalapeno 在 OpenAI 工作負載上宣稱優於 Grace Blackwell Ultra（推理延遲／吞吐／功耗）。扣 0.1：單點 ASIC 可被 Marvell／內部團隊複製，護城河在「反覆按時交出複雜系統」而非單一 IP。

### 業務韌性　0.7 / 1.0

相對 NVIDIA（資料中心佔比 >90%），Broadcom 仍有 **30%** 軟體營收、ARR +15%、非 AI 半導體約 US$42 億／季的基本盤，財務上淨負債可用約一年 FCF 覆蓋，利息覆蓋 14 倍。負面：Q3 AI 已佔 **56%** 且來自六家客戶；FY2025 前五大終端客戶 40%、經銷商 48%、單一半導體通路客戶 32%；中國出貨地 US$111.6 億；製造與 CoWoS／HBM 仍在亞洲。韌性來自「第二引擎＋現金流」，不是來自客戶分散。

### 護城河總評　4.0 / 5.0 — 高護城河

弱項幾乎全部落在**客戶與供給集中**，而非產品可被下季替代。客製矽＋乙太網路＋VMware 構成三層護城河，深度不如 NVIDIA 的 CUDA 平台，但比「普通 fabless 類比／混合訊號」厚得多。

---

## 主要風險

- **客戶集中且買家即潛在替代者：** 六家 XPU 客戶驅動幾乎全部增量。Google、Meta、OpenAI 都有能力加重自研或導入第二供應商（聯發科已介入 TPU）。前五大終端客戶 40% 是 FY2025 的數字，2026 年 AI 混比上升後實際更高。
- **部署約束 ≠ 晶片需求：** 管理層自己把 FY2027／2028 指引建成「低於帳面需求」，卡點是土地、電力、機殼、HBM、基板、先進晶圓。GW 加總若無法在財年內點亮，營收會滑到下一財年，倍數會先砍。
- **毛利率結構性下移：** Q4 指引 73% vs 一年前 78%。只要 XPU（尤其高記憶體版本）佔比續升，合併毛利率不會回到軟體＋傳統半導體時代。市場若用「毛利率崩壞」叙事而非「營運槓桿仍守住 66%」，股價波動會大於基本面。
- **負債與或有融資：** 淨負債 US$354 億仍在，票息 4% 可負擔，但利率環境或評等變化會壓縮回購。與 Apollo／Blackstone 的 AI XPV 平台已關閉 Anthropic 首筆 US$350 億，Broadcom 可能提供「適度殘值保證」——這是或有負債，不是已入表的現金出資，但仍把公司與客戶 capex 週期綁得更緊。
- **地緣政治與出口管制：** 中國（含香港）出貨地營收 FY2025 US$111.6 億。終端雖多在美歐，任何擴大的實體清單、對先進封裝／HBM 的管制，或台灣產能中斷，都會同時打擊 XPU 與交換矽。
- **競爭超車：** Marvell 約 35% 客製 ASIC 市佔（Amazon Trainium、Microsoft Maia）；NVIDIA Spectrum-X 在乙太網路；聯發科介入 Google TPU。開放乙太網路降低專有鎖定，也降低新進者的生態門檻。
- **軟體執行與監管：** VMware 訂閱轉換與定價曾引發客戶反彈；歐盟／各國雲監管、對大型企業軟體捆綁的審查，可能限制軟體端的再加速。Q1 軟體僅 +1%、Q3 才 +29%，增速並不線性。

---

## 綜合分析與觀點

### 評估結果

- ✓ **增長優異**（FY2025 +24%，FY2026 隱含 +66%，AI 連續翻倍）
- ✓ **價值空間充足**（三年平均預期 PE 20.4x，31x 合理 PE 隱含約 52% 空間）
- ✓ **高護城河**（4.0 / 5.0）
- ✓ **盈利能力卓越**（non-GAAP 營運利潤率 ~67%，FCF 利潤率 46%，ROIC 31%）

### 綜合分析

Broadcom 已從「高利潤的多元半導體＋VMware 現金牛」切到「客製 AI 加速器與乙太網路的核心供應商」。FY2025 營收 US$638.87 億、+24%；Q3 單季 US$295.91 億、+86%，AI 半導體 US$167 億（+221%）已佔總營收 56%。公司給出 FY2026／2027／2028 AI 營收 US$580 億 → US$1,150 億 → US$2,300 億，並稱 FY2028 EPS 將超過 US$30。現價 US$357.90 的 TTM PE 45.7x 看起來不便宜，但三年平均遠期 PE 已壓到 20.4x；以 31 倍合理 PE 估算上檔約 52%，與分析師目標價隱含的 49% 同向。護城河的核心是「能按時量產極度複雜的客製矽＋高階乙太網路」，加上 VMware 84% 營運利潤率的現金墊；真正的折價來自集中度——六家 XPU 客戶、前五大終端 40%、供給綁在 TSMC／HBM／基板、以及機房能否在財年窗口點亮。這是典型的**趨勢成長股（基礎設施型）**：基本面與訂單路徑足以支撐中長期持有，但倉位必須對「少數客戶延後部署＋毛利率混比下移」做情景管理，而不是把 2026–2028 的翻倍外推成永續 50% CAGR。

---

## 估值基準日與關鍵計算

- 股價：US$357.90（Nasdaq 2026-09-04 收盤）；盤後約 US$357.07。市值約 US$1.70 兆；股本 47.6 億股。
- TTM 營收：FY2025 638.87 − 前三季 FY2025 458.72 ＋ 前三季 FY2026 710.89 = **US$891.04 億**。
- TTM GAAP EPS：**US$7.83**；PE = 357.90／7.83 = **45.71**。
- TTM FCF：US$394 億；P/FCF = **43.21**（StockAnalysis）。
- FY2026 隱含營收：19.311＋22.187＋29.591＋34.8 = **US$1,058.9 億**（+65.7%）。
- FY2026 AI：8.4＋10.8＋16.7＋21.7 = **US$576 億**，約公司指引 US$580 億。
- 三年平均預期 PE：(357.90／11.64 ＋ 357.90／19.37 ＋ 357.90／30)／3 = **20.38**。
- 價值空間：(31／20.38 − 1) ≈ **52.1%**。
- 利息覆蓋 TTM：StockAnalysis **14.09 倍**；Q3 單季 15,955／778 = **20.5 倍**。
- 五年股本稀釋：(−1.57% − 11.85% − 0.95% ＋ 1.35% − 1.90%)／5 ≈ **−2.98%／年**。
- Q3 GAAP 毛利率：20,456／29,591 = **69.1%**；non-GAAP：22,191／29,591 = **75.0%**。
- Q3 GAAP 營運利潤率：15,955／29,591 = **53.9%**；non-GAAP：20,095／29,591 = **67.9%**。

## 主要資料來源

- [Q3 FY2026 官方新聞稿](https://investors.broadcom.com/news-releases/news-release-details/broadcom-inc-announces-third-quarter-fiscal-year-2026-financial)
- [PR Newswire 同稿（含完整財報附表）](https://www.prnewswire.com/news-releases/broadcom-inc-announces-third-quarter-fiscal-year-2026-financial-results-and-quarterly-dividend-302868129.html)
- [Q3 FY2026 法說會整理](https://www.tradingkey.com/news/transcripts/262147548-tradingkey)
- [FY2025 Q4／全年 8-K](https://investors.broadcom.com/static-files/dd25b8a9-a65a-4125-b02b-b1a6eb154cde)
- [SEC FY2025 Exhibit 99.1](https://www.sec.gov/Archives/edgar/data/1730168/000173016825000116/avgo-11022025x8kxex99.htm)
- [FY2025 Form 10-K](https://investors.broadcom.com/static-files/5868c796-2455-4855-9f02-3410b11e99e1)
- [Q1 FY2026 新聞稿](https://investors.broadcom.com/news-releases/news-release-details/broadcom-inc-announces-first-quarter-fiscal-year-2026-financial)
- [Q2 FY2026 8-K 摘要](https://www.stocktitan.net/sec-filings/AVGO/8-k-broadcom-inc-reports-material-event-ca5d7db2f903.html)
- [Yahoo Finance Analysis](https://finance.yahoo.com/quote/AVGO/analysis/)
- [Yahoo Finance Key Statistics](https://finance.yahoo.com/quote/AVGO/key-statistics/)
- [StockAnalysis Statistics](https://stockanalysis.com/stocks/avgo/statistics/)
- [StockAnalysis Ratios](https://stockanalysis.com/stocks/avgo/financials/ratios/)
- [MarketScreener 財務預估](https://www.marketscreener.com/quote/stock/BROADCOM-INC-199910242/finances/)
- [Simply Wall St 美股半導體產業倍數](https://simplywall.st/markets/us/tech/semiconductors)
- [Gartner 全球半導體預測（TechEdgeAI 轉述）](https://techedgeai.com/gartner-forecasts-worldwide-semiconductor-revenue-to-reach-1-6-trillion-in-2026/)
- [Gartner 新聞稿原文](https://www.gartner.com/en/newsroom/press-releases/2026-08-24-gartner-forecasts-worldwide-semiconductor-revenue-to-reach-1-trillion-dollars-in-2026)
- [Bloomberg Intelligence AI 加速器 TAM](https://www.bloomberg.com/company/press/ai-accelerator-market-looks-set-to-exceed-600-billion-by-2033-driven-by-hyperscale-spending-and-asic-adoption-according-to-bloomberg-intelligence/)
- [Dell'Oro AI 後端交換 2026–2030 累計近 1 兆](https://www.prnewswire.com/news-releases/ai-back-end-switch-sales-to-approach-1-trillion-over-the-next-five-years-according-to-delloro-group-302831878.html)
- [Dell'Oro 2026 Q2 後端交換超過前端](https://www.prnewswire.com/news-releases/ai-back-end-networks-switch-sales-surpass-front-end-networks-for-the-first-time-in-2q2026-according-to-delloro-group-302866912.html)
- [Dell'Oro 乙太網路佔 AI scale-out 約 2/3](https://www.prnewswire.com/news-releases/ethernet-extends-lead-in-ai-scale-out-networks-despite-strong-infiniband-rebound-according-to-delloro-group-302788112.html)
- [650 Group 資料中心網路 TAM](https://650group.com/blog/in-the-ai-era-ethernet-set-to-surge-in-scale-out-and-ramp-in-scale-up/)
- [Research Intelo 企業私有雲基礎設施](https://researchintelo.com/report/enterprise-private-cloud-infrastructure-market)
- [SDDC 市場 2025–2030](https://www.knowledge-sourcing.com/report/software-defined-data-center-market)
- [Damodaran／行業利潤率整理](https://christopholivierconsulting.com/profit-margin-by-industry/)
- [地區營收拆分](https://bullfincher.io/companies/broadcom/revenue-by-geography)
- [10-K 營收認列／地區表](https://app.edgar.tools/companies/AVGO/disclosures/revenue)

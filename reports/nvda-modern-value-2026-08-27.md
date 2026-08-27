# NVDA 現代價值投資報告

**基準日：** 2026 年 8 月 27 日（Q2 FY2027 於 8 月 26 日盤後公布）  
**股價基準：** Nasdaq 收盤 $209.66（2026-08-26）；盤後 $219.73  
**結論標籤：** 增長優異 · 價值空間充足 · 高護城河 · 盈利能力卓越  
**標的類型：** 趨勢成長股（AI 工廠平台型）  
**聲明：** 僅為報告參考，非投資建議。

---

## 步驟一：Known - 熟悉度評估

分析重點是釐清 NVIDIA 現在怎麼賺錢，而不是複述「它做顯示卡」。

### 業務模式

NVIDIA 是無晶圓廠（fabless）的 **完整 AI 運算平台商**，位於半導體價值鏈的 **設計與系統整合端**。它同時賣：

- 加速器與 CPU：Hopper／Blackwell／Vera Rubin GPU，以及專為 agentic AI 設計的 Vera CPU
- 機架級系統：NVLink 連接的 NVL 機櫃，而不是散裝加速卡
- 資料中心網路：Spectrum 乙太網路、InfiniBand、BlueField DPU
- 軟體層：CUDA、CUDA-X、Dynamo、Nemotron、Omniverse、DRIVE、Isaac

晶圓代工交給 TSMC（及部分 Samsung），先進封裝綁 TSMC CoWoS，HBM 來自 SK hynix／三星／美光。這種分工讓 NVIDIA 吃到軟體與系統溢價，CapEx 則由上游承擔——FY2026 與不動產／無形資產相關的資本支出僅 60.4 億美元，佔營收 2.8%。

這解釋了為什麼「AI GPU 晶片 TAM」會低估公司可服務市場：客戶採購的是 AI 工廠，報價單位是機架與叢集，不是單顆 GPU。

來源：
- [NVIDIA FY2026 財報](https://nvidianews.nvidia.com/news/nvidia-announces-financial-results-for-fourth-quarter-and-fiscal-2026)
- [NVIDIA 2026 Annual Review](https://s201.q4cdn.com/141608511/files/doc_financials/2026/ar/2026-Annual-Report-Web.pdf)

### 收入來源

| 口徑 | 期間 | 金額 | 佔比 | YoY |
| --- | --- | ---: | ---: | ---: |
| 總營收 | FY2026 | 2,159.38 億美元 | 100% | +65% |
| 資料中心 | FY2026 | 1,937 億美元 | 89.7% | +68% |
| Gaming | FY2026 | 160 億美元 | 7.4% | +41% |
| 專業視覺化 | FY2026 | 32 億美元 | 1.5% | +70% |
| 車用／機器人 | FY2026 | 23 億美元 | 1.1% | +39% |
| 其他 | FY2026 | 約 7 億美元 | 0.3% | — |
| 資料中心 | Q2 FY2027 | 890 億美元 | 92.5% | +117% |
| 邊緣運算 | Q2 FY2027 | 72 億美元 | 7.5% | +27% |

FY2027 起公司改成兩大平台：**Data Center** 與 **Edge Computing**。Data Center 再拆 Hyperscale（公有雲＋大型消費網路）與 ACIE（AI 雲、工業、企業）。Q1 FY2027：

- Hyperscale 378.69 億美元（約 50%，QoQ +12%，YoY +115%）
- ACIE 373.77 億美元（約 50%，QoQ +31%，YoY +74%）
- 舊口徑：計算 604 億美元（+77%）、網路 148 億美元（+199%）

網路不再是附屬品。ACIE 追上 Hyperscale，代表成長驅動已從「三家雲的訓練叢集」擴到 AI 雲、主權雲與企業 AI 工廠。

來源：
- [FY2026 財報（資料中心 1,937 億美元等）](https://nvidianews.nvidia.com/news/nvidia-announces-financial-results-for-fourth-quarter-and-fiscal-2026)
- [Q1 FY2027 財報（新分部與網路 148 億美元）](https://nvidianews.nvidia.com/news/nvidia-announces-financial-results-for-first-quarter-fiscal-2027)
- [Q2 FY2027 財報（Newsroom）](https://nvidianews.nvidia.com/news/nvidia-announces-financial-results-for-second-quarter-fiscal-2027)
- [Q2 FY2027 財報全文轉載](https://sa.marketscreener.com/news/nvidia-announces-financial-results-for-second-quarter-fiscal-2027-ce7858d9d188f021)
- [Q1 Hyperscale／ACIE 拆分](https://wccftech.com/nvidia-confirms-vera-rubin-launch-in-q3-volume-ramp-q4-blackwell-continues-to-see-massive-demand/)

### 客戶群體

以 **B2B** 為主，不是消費品牌生意。直接客戶包含 CSP、ODM／OEM、系統整合商與模型實驗室；最終需求來自超大規模雲、AI 雲（CoreWeave、Nebius 等）、主權與企業 AI 工廠，以及 PC／遊戲、工作站、車用與機器人。

集中度是這門生意最硬的基本面事實，不是附註：

- FY2026：單一直接客戶 22%、另一家 14%，合計 **36%**，幾乎全數在 Compute & Networking。FY2025 是三家各約 11–12%、合計 34%——佔比差不多，但形狀從「三家分散」變成「一家獨大」。
- 地理（依客戶總部）：美國 1,496.17 億美元（69.3%）、台灣 423.45 億美元（19.6%）、中國含香港 196.77 億美元（9.1%，YoY -21.5%）、其他 42.99 億美元。美國總部客戶佔比從 FY2025 的 59% 升到 69%，主因是中國出口管制與美國雲資本支出。

來源：
- [FY2026 10-K 地區與客戶集中摘錄](https://app.edgar.tools/companies/NVDA/disclosures/segments)
- [客戶集中度整理](https://axis-intelligence.com/nvidia-statistics/)

---

## 步驟二：Growth - 增長分析

### 總收入與 YoY

| 期間 | 營收 | YoY | 是否達標 |
| --- | ---: | ---: | --- |
| FY2025 | 1,304.97 億美元 | +114.2% | 遠超 20% |
| FY2026 | 2,159.38 億美元 | **+65%** | 遠超 20% |
| Q2 FY2027 | 962.21 億美元 | **+106%** | 遠超 20% |
| H1 FY2027 | 1,778.37 億美元 | +96% | 已達 FY2026 全年的 82% |

Q3 FY2027 指引 **1,080 億美元 ±2%**，毛利率 74.0% ±50bps，且 **不假設任何中國資料中心計算營收**。相對 FactSet 原共識約 1,038 億美元，指引仍高 4%。

來源：
- [FY2026 財報](https://nvidianews.nvidia.com/news/nvidia-announces-financial-results-for-fourth-quarter-and-fiscal-2026)
- [Q2 FY2027 財報（Newsroom）](https://nvidianews.nvidia.com/news/nvidia-announces-financial-results-for-second-quarter-fiscal-2027)
- [Q2 FY2027 財報（IR）](https://investor.nvidia.com/news/press-release-details/2026/NVIDIA-Announces-Financial-Results-for-Second-Quarter-Fiscal-2027/)
- [Q2 vs 指引／共識](https://www.rexshares.com/nvidia-earnings/)

### 未來增長指引（3 年 CAGR）

公司不給正式三年指引。市場共識（Yahoo Finance、MarketScreener、StockAnalysis；多數數字為 Q2 公布前）：

| 財年 | 營收共識 | YoY | EPS 共識 |
| --- | ---: | ---: | ---: |
| FY2026A | 2,159 億美元 | +65% | GAAP $4.90／non-GAAP $4.77 |
| FY2027E | 3,930–3,970 億美元 | +83% | 約 $9.05 |
| FY2028E | 5,620–5,740 億美元 | +43–45% | 約 $13.13 |
| FY2029E | 約 6,900 億美元 | +23% | 約 $15.32 |

- FY2026→FY2029 營收 CAGR：$(6901.49 / 2159.38)^{1/3} - 1 \approx$ **47.3%**
- 同期 EPS CAGR（$4.90 → $15.32）≈ **46.2%**

Q2 營收 962 億美元 vs 指引中值 910 億美元（+5.7%），且 Q3 指引高於原 Street。上表 CAGR 在上修後只會更高，不應再往下砍近端增速。真正要盯的是 **斜率**：共識已把 FY2029 放到 +23%，「超高增長」會在兩年內變成「高增長」。

來源：
- [Yahoo Finance Analysis](https://finance.yahoo.com/quote/NVDA/analysis/)
- [MarketScreener 財務預估](https://www.marketscreener.com/quote/stock/NVIDIA-CORPORATION-57355629/finances/)
- [StockAnalysis Forecast](https://stockanalysis.com/stocks/nvda/forecast/)
- [MarketWatch 分析師 EPS](https://www.marketwatch.com/investing/stock/nvda/analystestimates)

### 市場空間：大 M / 小 M / SAM

**大 M（TAM）—— AI 加速器／AI GPU**

- Bloomberg Intelligence（2026-01）：2024 年 1,160 億美元 → 2033 年 6,040 億美元，CAGR **16%**；其中 GPU 仍佔 81%，2033 年約 4,860 億美元。
- Mordor Intelligence：AI GPU 2025 1,675 億美元、2026 2,884 億美元、2031 6,217 億美元，2026–2031 CAGR **16.6%**。

這是「晶片」口徑。NVIDIA 自己的資料中心營收 FY2026 已 1,937 億美元，Q2 年化約 3,560 億美元，所以用晶片 TAM 去卡 NVIDIA 會得到錯誤的「已經超過 TAM」結論。

**小 M——商用資料中心 AI GPU（可外購部分）**

排除雲業者自研 ASIC 的內部產能後，商用市場仍高度集中：

- Mordor：NVIDIA 2026 年佔資料中心 AI 加速器營收約 **80–85%**；AMD 約 5–7%。
- BI：預期 NVIDIA 至 2030 仍持有 **70–75%**。

市佔下降 5–10 個百分點仍可能伴隨絕對營收大增——因為 TAM 本身在擴。這是「份額稀釋但蛋糕變大」的結構，不是立刻崩盤。

**SAM——NVIDIA 可服務的系統市場**

可服務範圍 = GPU + CPU + 網路 + 系統 + 軟體授權／支援。管理層在 2026 Annual Review 寫的錨是：

> 自 2025 年初至 2027 年，Blackwell 與 Rubin 累計營收能見度超過 **1 兆美元**。

這不是 IFRS 的剩餘履約義務（RPO），不能當成不可取消訂單；但它是把產能、定價與需求層疊起來的公司內部能見度。Q2 另宣布與 Apollo、BlackRock、Blackstone、Brookfield、高盛、KKR 合作，目標動員逾 **5,000 億美元** 第三方資金建 AI 基礎設施（仍待最終協議）。

來源：
- [Bloomberg Intelligence TAM](https://www.bloomberg.com/company/press/ai-accelerator-market-looks-set-to-exceed-600-billion-by-2033-driven-by-hyperscale-spending-and-asic-adoption-according-to-bloomberg-intelligence/)
- [Mordor AI GPU 市場](https://www.mordorintelligence.com/industry-reports/ai-gpu-chip-market)
- [2026 Annual Review（1 兆美元能見度）](https://s201.q4cdn.com/141608511/files/doc_financials/2026/ar/2026-Annual-Report-Web.pdf)
- [1 兆美元能見度與 ACIE 近半討論](https://404kresearch.substack.com/p/nvidia-roadshow-deep-dive-gb300-tokens)

### 業務部門增長與驅動力

主引擎仍是資料中心（FY2026 +68%、Q2 FY27 +117%）。結構上有三個比「總額很大」更重要的訊號：

1. **網路成為第二引擎**：Q1 網路 148 億美元、YoY +199%。機架內 NVLink 與機架間 Spectrum／CPO 讓 NVIDIA 在「連接」上收第二次款。
2. **ACIE 增速快於 Hyperscale**：Q1 ACIE QoQ +31% vs Hyperscale +12%。AI 雲、工業與企業正在分擔雲巨頭 CapEx 的周期性。
3. **邊緣不是歸零**：Gaming FY2026 +41% 至 160 億美元；Q2 邊緣運算 72 億美元、+27%。這條線對估值乘數幫助有限，但證明公司並非只有一個終端市場。

Vera Rubin 已在 CoreWeave、Google Cloud、Azure、OCI、Nebius 進入量產，產品周期從「Blackwell 供不應求」切到「Rubin 接棒」。黃仁勳在 Q2 的定調是 agentic AI 已產生可用 token、**compute is revenue**——也就是把需求從「訓練大模型的一次性建設」轉成「推理與代理的持續消耗」。

### 增長持續性

支持延續的證據：

- 連續 **14 季**高於自家指引；Q2 相對 910 億美元中值超標 5.7%。
- Q3 指引 1,080 億美元，且已明示不含中國資料中心計算。
- Blackwell＋Rubin 2025–2027 累計能見度 >1 兆美元（不含獨立 Vera CPU；黃仁勳把 Vera CPU 與 LPX 列為增量上檔）。
- 第三方融資平台目標 5,000 億美元，試圖把「雲業者自己有沒有錢」部分轉成專案融資。

限制延續的證據：

- 共識已把 FY2029 增速放到約 23%。
- 產能仍受 CoWoS 與 HBM 約束，不是需求函數。
- 中國計算營收被假設為零，這是基線不是壓力測試。

來源：
- [Q2 財報與 5,000 億美元融資合作](https://sa.marketscreener.com/news/nvidia-announces-financial-results-for-second-quarter-fiscal-2027-ce7858d9d188f021)
- [Futurum：Vera CPU 未計入 1 兆美元](https://futurumgroup.com/insights/nvidia-q1-fy2027-data-center-diversification-blackwell-scale-cpu-upside/)

---

## 步驟三：Valuation - 估值評估

股價與市值以 2026-08-26 收盤 $209.66、約 5.08–5.09 兆美元為準。Q2 超預期後分析師數字尚未全面改寫，遠期 PE 偏保守（實際可能更便宜）。

### 當前估值對比

| 指標 | NVDA | 產業比較 | 判讀 |
| --- | ---: | --- | --- |
| PE (TTM GAAP) | **26.51x**（$209.66 / $7.91） | Simply Wall St 美股半導體簡單平均 **45.2x**、市值加權 Absolute PE **23.6x**（2026-08-26）；GuruFocus 產業中位數約 **38.4x** | 低於簡單平均／中位數；略高於市值加權（因為 NVDA 本身就是權重） |
| PS (TTM) | **16.76–16.81x**（市值 / 3,029.7 億美元） | Simply Wall St **8.4x**；ScanX 大型同業約 **13.3x** | 高於產業。高 PS 來自 75% 毛利率，不能單獨當高估 |
| P/FCF (TTM) | **39.98–40.03x**（市值 / FCF 1,268.9 億美元） | MacroTrends 同日約 43.0x；美光約 40.8x、Microchip 約 46.5x | 略優於大型同業 |

TTM 定義為 Q3 FY2026 + Q4 FY2026 + Q1 FY2027 + Q2 FY2027。FY2026 全年 FCF 為 965.75 億美元（FCF 利潤率 44.7%）。

來源：
- [StockAnalysis Statistics（PE 26.51、PS 16.76、P/FCF 39.98）](https://stockanalysis.com/stocks/nvda/statistics/)
- [Simply Wall St 產業 PE／PS](https://simplywall.st/markets/us/tech/semiconductors)
- [GuruFocus PE 中位數](https://www.gurufocus.com/term/pettm/NVDA)
- [ScanX 同業倍數](https://scanx.trade/stock-market-news/companies/broadcom-trades-premium-valuation-multiples-vs-semiconductor-peers/49285551)
- [MacroTrends P/FCF](https://www.macrotrends.net/stocks/charts/NVDA/nvidia/price-fcf)

### 預期 PE

以 $209.66 與 Yahoo／MarketWatch 共識：

| 年度 | EPS | 預期 PE |
| --- | ---: | ---: |
| FY2027E | $9.05 | **23.17x** |
| FY2028E | $13.13 | **15.97x** |
| FY2029E | $15.32 | **13.69x** |
| **三年平均** | — | **17.61x** |

StockAnalysis 的 Forward PE 約 19.08x，與 FY2027 23x、再往後壓縮的路徑一致。PEG（NTM PE 23.17 ÷ 三年 CAGR 47）≈ **0.49**。

### 合理估值依據

2025 年高增長階段，市場曾用 35–40x 給「40% 增長 + 70% 毛利率 + 高護城河」。2026 年 8 月要改三件事：

1. 增長仍然極高（共識 47% CAGR），但分子已是 5 兆美元市值、2,160 億美元營收。
2. 共識自己就把 FY2029 增速放到 23%，倍數必須從「超高增長」切到「優質成長」。
3. 客戶集中與自研 ASIC 是永久性折價因子，不是暫時雜音。

因此合理 PE 區間定為 **28–35x**，中值 **31.5x**。這仍明顯高於目前 17.6x 的三年平均預期 PE，但不再使用歷史 50x+ 的 AI 泡沫錨。

### 潛在價值空間

公式（與報告架構一致）：

\[
(31.5 \div 17.61 - 1) \times 100\% \approx \mathbf{78.9\%}
\]

敏感度：

| 合理 PE | 價值空間 |
| ---: | ---: |
| 25x（保守，接近大型優質成長股） | 42.0% |
| 31.5x（基準） | 78.9% |
| 35x（若 30%+ CAGR 維持更久） | 98.8% |

61 位分析師平均目標價 **$305.79**，相對 $209.66 隱含 **+45.9%**，落在保守 25x 情景附近。結論：**價值空間充足**——不是因為市場沒發現 NVIDIA，而是盈利增長把倍數壓下來了。主要風險是共識 EPS 若大幅下修，17.6x 這個分母會立刻變大。

來源：
- [Yahoo 預估](https://finance.yahoo.com/quote/NVDA/analysis/)
- [MarketScreener 目標價 $305.79](https://sa.marketscreener.com/news/nvidia-announces-financial-results-for-second-quarter-fiscal-2027-ce7858d9d188f021)

---

## 步驟四：Profitability - 盈利能力

### 利潤率

| 指標 | FY2026 | Q2 FY2027 | TTM | 產業 | 判讀 |
| --- | ---: | ---: | ---: | --- | --- |
| 毛利率 | **71.1%** | **75.0%** | 74.7% | GuruFocus 中位數 29.51%；大型同業約 50–55% | 遠超 30% 標準 |
| 營運利潤率 | **60.4%** | **66.2%** | 65.2% | 中位數 4.02% | 遠高於產業 |
| 淨利率 | **55.6%** | 62.0% | 63.7% | 中位數 3.49% | 遠高於產業；TTM 含大量投資利益 |

FY2026 毛利率被 Q1 約 45 億美元 H20 相關費用壓低 3.9 個百分點（對 FY2025 的 75.0%）。費用出清後，Q4 FY2026 與整個 FY2027 上半年都穩在 75% 左右，Q3 指引 74.0%——這是產品組合與中國零貢獻假設下的「新常態」，不是 80% 的幻想。

淨利率 TTM 被權益證券評價利益放大（H1 FY2027 約 237 億美元）。衡量本業應看營運利潤：FY2026 營業利益 1,303.87 億美元，Q2 單季 637.34 億美元。

來源：
- [FY2026／Q2 損益](https://nvidianews.nvidia.com/news/nvidia-announces-financial-results-for-fourth-quarter-and-fiscal-2026)
- [GuruFocus 毛利率中位數 29.51%](https://www.gurufocus.com/term/gross-margin/NVDA)
- [GuruFocus 營運／淨利率中位數](https://www.gurufocus.com/term/operating-margin/NVDA)

### 股東回報

**回購（股本變化，評估稀釋或收縮）**

稀釋後加權股本（MacroTrends，已還原分割）：

| 財年 | 股數（百萬） | YoY |
| --- | ---: | ---: |
| 2022 | 25,350 | +1.00% |
| 2023 | 25,070 | -1.10% |
| 2024 | 24,940 | -0.52% |
| 2025 | 24,804 | -0.55% |
| 2026 | 24,514 | -1.17% |

五年平均每年 **-0.47%**（淨回購，未稀釋）。金額：FY2026 回購 400.86 億美元＋股息 9.74 億美元；H1 FY2027 回購 390.44 億美元。2026 年 5 月再授權 800 億美元，Q2 末剩餘授權約 990 億美元。Q2 單季返還股東約 260 億美元。

**股息率**

季息由 $0.01 提高至 **$0.25**（2026-05）。年化 $1.00 / $209.66 ≈ **0.48%**。仍不是收益股，但已脫離「幾乎零股息」。

來源：
- [MacroTrends 股本](https://www.macrotrends.net/stocks/charts/NVDA/nvidia/shares-outstanding)
- [FY2026 現金流量表](https://www.sec.gov/Archives/edgar/data/1045810/000104581026000019/q4fy26pr.htm)
- [Q1 股息上調與 800 億美元授權](https://nvidianews.nvidia.com/news/nvidia-announces-financial-results-for-first-quarter-fiscal-2027)

### 資本效率與安全

- **ROIC：** Macrotrends ROI 於 2026-04-30 為 **107.71%**；FY2026 約 106%。以 NOPAT／投入資本、剔除超額現金後約 70–94%。對照約 9% 的 WACC，經濟利潤差極大——這是輕資產 fabless + 軟體鎖定 + 系統溢價的結果，不是一次性和潤。
- **利息覆蓋：** FY2026 1,303.87 億美元 / 2.59 億美元 = **503 倍**。Q2 發行約 249 億美元債，長期負債從 74.7 億美元升至 323.7 億美元，覆蓋率會下降，但相對 TTM FCF 1,269 億美元與約 994 億美元現金及有價證券，債務仍不是約束。安全線是覆蓋率 >2，NVIDIA 高兩個數量級。

來源：
- [Macrotrends ROI](https://www.macrotrends.net/stocks/charts/NVDA/nvidia/roi)
- [FY2026 利息與營業利益](https://www.sec.gov/Archives/edgar/data/1045810/000104581026000019/q4fy26pr.htm)
- [Q2 資產負債表與發債](https://sa.marketscreener.com/news/nvidia-announces-financial-results-for-second-quarter-fiscal-2027-ce7858d9d188f021)

---

## 步驟五：Moat - 護城河評估

滿分 5.0，五維各 0–1.0。

### 成本優勢 0.9 / 1.0

75% 毛利率、2.8% 的 CapEx／營收、44.7% 的 FCF 利潤率，是規模經濟加輕資產，不是自己擁有最便宜的產能。定價權來自技術領先與產能綁定，讓公司能把 CoWoS／HBM 的稀缺轉成系統溢價。扣 0.1：成本結構仍暴露在上游瓶頸與中國折價 SKU（H20）——FY2026 毛利率因此掉到 71.1%。

### 網絡效應 0.9 / 1.0

年報口徑：約 **750 萬** CUDA 開發者、超過 **6,000** 個加速應用、TOP500 中逾 **78%** 使用 NVIDIA GPU 或網路。轉換成本是重寫 CUDA 依賴、重訓工程師、重做叢集排程與網路，而不是換供應商代碼。NVLink／Spectrum 把鎖定從晶片抬到機架。扣 0.1：這是極高轉換成本，不完全是雙邊網絡效應；CUDA 相容層與雲業者自己的軟體堆疊存在。

來源：[CUDA 750 萬開發者等，轉述 10-K／年報](https://axis-intelligence.com/nvidia-statistics/)

### 品牌優勢 0.9 / 1.0

- Interbrand 2025：品牌價值 **432 億美元**、全球第 15、年增 **116%**（該榜史上最大單年增幅）。
- Brand Finance 2026：品牌價值 **1,843 億美元**、全球第 5、年增 110%。

在 AI 基礎設施標案裡，NVIDIA 是預設規格。扣 0.1：品牌溢價跟 AI CapEx 叙事綁在一起，比 CUDA 技術債更脆弱。

來源：
- [Interbrand NVIDIA](https://interbrand.com/best-global-brands/global/nvidia/)
- [Interbrand 2025 新聞稿](https://finance.yahoo.com/news/brands-adapting-market-challenges-increases-040100854.html)
- [Brand Finance 2026](https://businesschief.com/news/how-nvidia-became-one-of-the-worlds-most-valuable-brands)

### 技術門檻 0.9 / 1.0

競爭已從單晶片 FLOPS 變成 CPU＋GPU＋DPU＋交換＋光通訊＋軟體的共設計，並以一年一代（Blackwell → Rubin → Feynman）壓縮追趕窗口。Q2：Vera Rubin 量產、Groq 3 LPX 量產、MLPerf Training 6.0 與 AgentPerf 全類別領先。FY2026 R&D **185.0 億美元**。扣 0.1：Google TPU、Amazon Trainium、Microsoft Maia 證明單點加速器可被做出來；護城河在系統與生態，不在「別人做不出矽」。

### 業務韌性 0.6 / 1.0

財務韌性極強（淨現金、503x 利息覆蓋、年 FCF ~1,000 億美元級）。商業韌性偏弱：資料中心 92.5%、兩客戶 36%、美國總部客戶 69%、製造集中亞洲、中國計算指引為零。ACIE 佔資料中心近半是真正的改善，但還不足以把集中度風險從「結構性」降成「可忽略」。

### 護城河總評：**4.2 / 5.0（高護城河）**

弱項幾乎全在集中度，不在產品可替代性。

---

## 主要風險

1. **客戶集中且買家即競爭者。** 22% + 14% 的直接客戶結構，疊加 10-K 把 Alphabet、Amazon、Microsoft 等列為自研矽競爭者。這不是普通大客戶風險。
2. **出口管制。** 中國含香港營收 FY2026 197 億美元、-21.5%；Q1 FY2026 約 45 億美元 H20 費用。指引連續假設中國資料中心計算營收為零。
3. **TSMC CoWoS／HBM 單點。** 需求函數上方有一條產能天花板。美國亞利桑那晶圓與德州組裝是對沖，2026–2027 年還不能替代台灣先進產能。
4. **AI CapEx 與 ROI。** 若推理 token 的單位經濟差於資金成本，Hyperscale 會延後提貨或砍下一世代，財報會落後一至兩季才反映。
5. **自研 ASIC 與第二來源政策。** 80%+ 市佔本身就會催生多元化採購。份額掉到 70% 仍可能賺更多錢，但倍數會先被殺。
6. **增長斜率下降。** 共識 FY2027 +83% → FY2029 +23%。即便 EPS 仍增，估值切換會造成股價波動，與基本面「變差」不是同一件事。

---

## 綜合分析與觀點

**評估結果：** 增長優異 · 價值空間充足 · 高護城河 · 盈利能力卓越

NVIDIA 用 FY2026 2,159 億美元營收（+65%）和 Q2 FY2027 單季 962 億美元（+106%）證明需求還沒到「庫存循環」階段；75% 毛利率、60%+ 營運利潤、ROIC >100% 證明它不只是景氣週期的受益者，而是把 CUDA 與機架級系統做成了高轉換成本的平台。遠期三年平均 PE 17.6x 對 47% CAGR 過低，基準價值空間約 79%；即使用 25x 保守倍數或 Street 目標價，上檔仍約 42–46%。最大隱憂不是 AMD 在單卡上追趕，而是 **最大客戶同時在做替代矽、最大市場（中國）被假設為零、最大產能在別人廠裡**。這是典型的 **趨勢成長股（平台型）**：基本面支持中長期持有，但倉位必須對「雲端 CapEx 放緩 + 客戶 ASIC」做情景管理，不能把 2023–2025 的三位數增速外推到 2029。

---

## 附錄：計算底稿

- TTM 營收：57.006 + 68.127 + 81.615 + 96.221 = **3,029.69 億美元**
- TTM GAAP EPS：1.30 + 1.76 + 2.39 + 2.46 = **$7.91**
- PE：209.66 / 7.91 = **26.51**
- TTM FCF：220.89 + 349.02 + 485.54 + 213.41 = **1,268.86 億美元**
- 三年平均預期 PE：(23.17 + 15.97 + 13.69) / 3 = **17.61**
- 價值空間：(31.5 / 17.61) - 1 = **78.9%**
- 利息覆蓋：130,387 / 259 = **503.4x**
- FY2026 資料中心佔比：1,937 / 2,159.38 = **89.7%**
- Q2 資料中心佔比：890 / 962.21 = **92.5%**
- 股息率：1.00 / 209.66 = **0.48%**

# Wiki 維護日誌 (Log)

本檔案為追加式紀錄（Append-only），依照時間倒序或順序記錄 Wiki 的生命週期事件（包含資料匯入 Ingest、深度問答沉澱 Query/Synthesis、健康檢查 Lint、簡報生成 Slide Build）。

---

## [2026-11-23] init | 專案初始化與結構建置
- 建立專案核心規範手冊：[[AGENTS.md]]
- 建立目錄架構：`raw/`、`wiki/chapters/`、`wiki/ratios/`、`wiki/syntheses/`、`wiki/slides/`
- 初始化知識總目錄：[[index.md]]
- 設定範疇為企管系初級會計（二），涵蓋 Chapter 8 到 Chapter 14（Weygandt IFRS 5th Edition）
- 確立「知識庫驅動教學型 HTML 互動簡報」之雙層流水線流程


## [2026-11-23] ingest | Ch08(e).docx & ch08(ex).xlsx
- 來源檔案：`raw/Ch08(e).docx` (章節講義)、`raw/ch08(ex).xlsx` (課堂習題 E1/E2/E3)
- 建置章節核心導航頁：[[wiki/chapters/Ch08-Receivables.md]]
- 建置專題筆記：[[wiki/chapters/Ch08-Valuation-Bad-Debts.md]]（備抵法三階段、帳齡分析、沖銷前後淨變現價值恆等式推導、Class Exercise 1 Sycamore AG 完整解答）
- 建置專題筆記：[[wiki/chapters/Ch08-Notes-Receivable.md]]（本票要素、計息與到期日、跨期調整與拒付處理、Class Exercise 2 Anping Enterprises 完整解答）
- 建立財務比率庫頁面：[[wiki/ratios/AR-Turnover-and-DSO.md]]（應收帳款週轉率、DSO、CCC 現金轉換循環、Class Exercise 3 Nike vs. Adidas 案例分析）
- 建立跨章節綜合分析：[[wiki/syntheses/Receivables-and-Cash-Flow-Linkage.md]]（應收帳款與現金流量表間接法勾稽、黑字倒閉與沖銷無現金流效應）
- 更新 [[index.md]]


## [2026-11-23] ingest | Ch09(e).docx & ch09(ex).xlsx
- 來源檔案：`raw/Ch09(e).docx` (章節講義)、`raw/ch09(ex).xlsx` (三大折舊排程表、課堂習題 E1/E2)
- 建置章節核心導航頁：[[wiki/chapters/Ch09-Plant-Assets.md]] (PPE 成本認定原則、資本支出 vs 收益支出)
- 建置專題筆記：[[wiki/chapters/Ch09-Depreciation-and-Disposal.md]] (直線法/生產數量法/倍數餘額遞減法深入演繹、組成份子會計、IFRS 重估價模式、折舊估計變動、Class Exercise 1 Jimenez Enterprises 完整題解與 T 字帳)
- 建置專題筆記：[[wiki/chapters/Ch09-Natural-Resources-and-Intangibles.md]] (天然資源折耗計入存貨、有限壽命攤銷 vs 無限壽命減損、R&D 技術可行性分水嶺、Class Exercise 2 Glover Restaurants 完整題解)
- 建立財務比率庫頁面：[[wiki/ratios/Asset-Turnover.md]] (資產週轉率公式、杜邦分析 ROE 拆解、重資產 vs 輕資產策略比較)
- 建立跨章節綜合分析：[[wiki/syntheses/CapEx-Depreciation-and-Cash-Flow.md]] (資本支出 CapEx、折舊與現金流量表間接法勾稽、處分利益調節、自由現金流 FCF 體質診斷)
- 更新 [[index.md]]


## [2026-11-23] ingest | Ch10(e).docx & ch10(ex).xlsx
- 來源檔案：`raw/Ch10(e).docx` (章節講義)、`raw/ch10(ex).xlsx` (課堂習題 E1/E2)
- 建置章節核心導航頁：[[wiki/chapters/Ch10-Current-Liabilities.md]] (流動負債定義、應付票據跨期計息、營業稅受託代收性、預收收入商模、薪資負債代扣與雇主稅、一年內到期長期負債重分類)
- 建置專題筆記：[[wiki/chapters/Ch10-Provisions-and-Contingencies.md]] (IAS 37 負債準備三大法定要件、產品保固核算模型、或有負債與或有資產處理矩陣、Class Exercise 1 Ting Manufacturing 完整題解與推導)
- 建立財務比率庫頁面：[[wiki/ratios/Liquidity-and-Working-Capital.md]] (營運資金、流動比率、速動比率、Class Exercise 2 Chen Group 題解、破解期末以現金清償應付帳款之 Window Dressing 手法)
- 建立跨章節綜合分析：[[wiki/syntheses/Working-Capital-and-Cash-Flow.md]] (營運資金變動在現金流量表間接法中的完整加減項直觀邏輯、三大營業週期與負 CCC 營運模式)
- 更新 [[index.md]]


## [2026-11-23] ingest | Ch12(e).docx & Ch12(ex).xlsx
- 來源檔案：`raw/Ch12(e).docx` (章節講義)、`raw/Ch12(ex).xlsx` (課堂習題 E1/E2)
- 建置章節核心導航頁：[[wiki/chapters/Ch12-Corporations-and-Equity.md]] (公司特徵、股東四大權利、股份發行對價客觀判定、特別股股利優先與清算優先、庫藏股成本法三階段分錄、權益架構)
- 建置專題筆記：[[wiki/chapters/Ch12-Dividends-and-Retained-Earnings.md]] (現金股利三關鍵日期、累積特別股積欠股利分配、股票股利大小額入帳區分、股票分割、Class Exercise 1 Lucerne Company AG 四方案影響矩陣、權益變動表編製、Class Exercise 2 Chamblin AG 完整詳解與股數勾稽)
- 建立財務比率庫頁面：[[wiki/ratios/ROE-and-Shareholder-Metrics.md]] (普通股東權益報酬率 ROE、杜邦分析三因子模型拆解、每股淨值 BVPS、股利發放率 Payout Ratio、高槓桿假性高 ROE 警訊)
- 建立跨章節綜合分析：[[wiki/syntheses/Equity-Financing-and-Cash-Flow.md]] (權益交易與籌資活動現金流勾稽、股票股利/分割之零現金流、非現金股份交易附註揭露、應付股利跨期跨表調節)
- 更新 [[index.md]]


## [2026-11-23] ingest | Ch13(e).docx & ch13(ex).xlsx
- 來源檔案：`raw/Ch13(e).docx` (章節講義)、`raw/ch13(ex).xlsx` (課堂習題 E1)
- 建置章節核心導航頁：[[wiki/chapters/Ch13-Investments.md]] (企業投資三大動機、IFRS 9 金融資產 SPPI 測試與經營模式分類地圖、債務 vs 權益全覽對照)
- 建置專題筆記：[[wiki/chapters/Ch13-Debt-and-Equity-Valuation.md]] (債券 AC/FVOCI/FVPL 會計循環、股票 <20% 交易目的 FVPL vs 策略性非交易 FVOCI、核心準則差異：債券 FVOCI 處分允許重分類至損益 vs 股票 FVOCI 處分嚴禁重分類而結轉保留盈餘)
- 建置專題筆記：[[wiki/chapters/Ch13-Equity-Method-and-Consolidations.md]] (持股 20%~50% 權益法運作原理：獲利認列收益、股利視為資產收回、期末無視公開股價波動；持股 >50% 合併報表單一實體；Class Exercise 1 Control Alt Design Ltd. vs. Walter Co. 公允價值法 vs 權益法雙軌全景對照詳解)
- 建立財務比率庫頁面：[[wiki/ratios/Investment-Returns-and-Yields.md]] (現金殖利率 Dividend Yield、投資報酬率 ROI、企業司庫 Treasury 資金配置平衡模型與 WACC 檢驗)
- 建立跨章節綜合分析：[[wiki/syntheses/Investment-Classification-and-Earnings-Quality.md]] (金融資產分類對損益表盈餘波動度之策略性衝擊、權益法投資收益在現金流量表間接法中之扣除調節)
- 更新 [[index.md]]


## [2026-11-23] slide_build | accounting2-core-concepts-slides.html
- 產出檔案：`wiki/slides/accounting2-core-concepts-slides.html`
- 規格大綱：`wiki/slides/outline-chapters-8-13.md`
- 涵蓋範圍：Chapter 8 (應收款項)、Chapter 9 (固定與無形資產)、Chapter 10 (流動負債)、Chapter 12 (公司權益)、Chapter 13 (金融資產投資) 及跨表現金流量勾稽前瞻
- 特性：單一獨立 HTML 檔案、Tailwind CSS CDN 現代商務配色、KaTeX 數學公式動態渲染、整合 `assets/` 雙圖資、完整鍵盤方向鍵與全螢幕導航支援
- 更新 [[index.md]]


## [2026-11-23] slide_build | ch12-corporations-morandi-slides.html
- 產出檔案：`wiki/slides/ch12-corporations-morandi-slides.html`
- 規格大綱：`wiki/slides/ch12-morandi-slides-spec.md` (14 頁完整設計規格與題型引導)
- 章節焦點：**Chapter 12: Corporations: Organization, Share Transactions, and Equity** (公司組織、股票交易與股東權益)
- 設計特點：
  1. **莫蘭迪色彩體系 (Morandi Palette)**：溫潤燕麥底色 (`#F5F2EB`)、霧藍 (`#5C768D`)、鼠尾草綠 (`#6B8068`)、乾燥玫瑰 (`#B87D75`)、大地暖灰 (`#8D7B68`) 與暖芥黃 (`#C29B38`)，兼具專業沉穩與舒適明亮，徹底擺脫沉悶。
  2. **大字體與多頁投影設計**：規劃 14 頁獨立投影單元，每頁單一主題深入淺出，文字適當放大，嚴格標註 [Chapter 12] 與 [LO 1] 至 [LO 5]。
  3. **易混淆點專題辨析**：
     - 開辦費為何必須即期費用化（無未來經濟效益明確保障，穩健原則）。
     - 股數三大層次（核定 vs. 發行 vs. 流通在外）與庫藏股夾心公式。
     - 庫藏股為何「絕不能列為資產」（公司不能自己持有自己，權益減項，買賣無損益）。
     - 庫藏股折價出售擊穿資本公積時之保留盈餘沖抵順序。
     - 積欠股利 (Dividends in Arrears) 絕非負債（未宣告即無法定義務，僅附註揭露）。
     - 現金股利三部曲（宣告日產生負債、基準日無分錄、發放日清償負債，發放日權益不變）。
     - 股票股利（小額市價轉出 vs. 大額面額轉出）與股票分割（零分錄）深度對決。
  4. **舉一反三與深度題型互動**：
     - **Slide 6**：庫藏股折價再出售分錄點擊展開與沖抵順序解析。
     - **Slide 9**：Tab 切換股票股利對比矩陣與小額 vs 大額入帳。
     - **Slide 10**：Lucerne AG 四方案 (現金股利、股票股利、股票分割、基準) 即時切換比較矩陣。
     - **Slide 11**：Chamblin AG 權益變動表多欄橫向與縱向嚴格勾稽。
     - **Slide 12**：ROE 杜邦三因子拆解與「借債買回庫藏股假性美化 ROE」財務危機警訊。
     - **Slide 13**：企管會計思維三大考驗互動卡片（點擊即時翻轉/查看解答）。
  5. **資產整合與快捷導航**：
     - 裁切並精緻呈現 `assets/` 圖資（Slide 1 封面頭像與 Slide 14 總結分析圖）。
     - 完整鍵盤導航 (`←` / `→` / `Space` / `F`)、即時進度條、LO 動態徽章、下拉跳頁選單。
- 更新 [[index.md]]

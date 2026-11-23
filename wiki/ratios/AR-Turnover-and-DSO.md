# [財務比率] 應收帳款週轉率與平均收現期間 (AR Turnover & DSO)

> 本頁定義應收帳款週轉率 (Accounts Receivable Turnover) 與平均收現天數 (Average Collection Period / Days Sales Outstanding, DSO)，並包含 Class Exercise 3 中 Nike 與 Adidas 的真實財報比較分析。

---

## 1. 核心公式與計算定義 (Formulas & Definitions)

### (1) 應收帳款週轉率 (Accounts Receivable Turnover Ratio)
衡量企業在一年內將應收帳款收回並轉化為現金的頻率（次數）。週轉率愈高，表示帳款回收速度愈快、資產流動性愈高。

$$\text{Accounts Receivable Turnover} = \frac{\text{Net Credit Sales (賒銷淨額)}}{\text{Average Net Accounts Receivable (平均應收帳款淨額)}}$$

#### 相關項計算細節：
* **賒銷淨額 (Net Credit Sales)**：
  $$\text{Net Credit Sales} = \text{Gross Credit Sales} - \text{Sales Returns \& Allowances} - \text{Sales Discounts}$$
* **平均應收帳款淨額 (Average Net Accounts Receivable)**：
  $$\text{Average Net Accounts Receivable} = \frac{\text{期初應收帳款淨額} + \text{期末應收帳款淨額}}{2}$$
  *(註：此處之應收帳款淨額必須扣除備抵損失)*

---

### (2) 平均收現期間 (Average Collection Period / Days Sales Outstanding, DSO)
衡量企業自賒銷成立日起，平均需要多少天才能真正收回現金。天數愈短，資金被客戶佔用的時間愈少。

$$\text{Average Collection Period (天數)} = \frac{365 \text{ (或 360 天)}}{\text{Accounts Receivable Turnover (應收帳款週轉率)}}$$

> [!TIP] 企管判讀基準 (Benchmark Rule)
> 企業的平均收現天數 **不應大幅超過** 公司所訂定的信用期間 (Credit Terms)。
> * 例如：若公司的交易條件為 `n/30`（30天內付款），而平均收現天數高達 65 天，即為嚴重的內部控制或信用催收警訊！

---

## 2. 實戰個案分析：Nike vs. Adidas 跨國運動品牌 PK (Class Exercise 3)

### 原始數據摘要 (2025 年報，百萬美元/歐元)

| 財務項目 | Nike (USA) | Adidas (DEU) |
| :--- | :---: | :---: |
| 賒銷淨額 (Net Credit Sales) | $14,000 | €11,720 |
| 期初應收帳款總額 (Gross AR, Beginning) | $2,880 | €1,700 |
| 期初備抵損失 (Allowance, Beginning) | $80 | €120 |
| **期初應收帳款淨額 (Net AR, Beginning)** | **$2,800** | **€1,580** |
| 期末應收帳款總額 (Gross AR, Ending) | $2,900 | €1,500 |
| 期末備抵損失 (Allowance, Ending) | $100 | €150 |
| **期末應收帳款淨額 (Net AR, Ending)** | **$2,800** | **€1,350** |
| **平均應收帳款淨額 (Average Net AR)** | **$2,800** | **€1,465** |

---

### 計算推導過程

#### 1. 應收帳款週轉率 (AR Turnover Ratio)
* **Nike**：
  $$\text{AR Turnover}_{\text{Nike}} = \frac{14,000}{2,800} = \mathbf{5.0 \text{ 次 (times)}}$$
* **Adidas**：
  $$\text{AR Turnover}_{\text{Adidas}} = \frac{11,720}{1,465} = \mathbf{8.0 \text{ 次 (times)}}$$

#### 2. 平均收現期間 (Average Collection Period / DSO) — 以 365 天計
* **Nike**：
  $$\text{Collection Period}_{\text{Nike}} = \frac{365}{5.0} = \mathbf{73 \text{ 天 (days)}}$$
* **Adidas**：
  $$\text{Collection Period}_{\text{Adidas}} = \frac{365}{8.0} = \mathbf{45.6 \text{ 天 (約 46 天)}}$$

---

### 企管決策與管理能力評析 (Comparative Management Insights)

1. **營運資金效能與變現能力 (Liquidity & Efficiency)**：
   * **Adidas 明顯勝出**。Adidas 每年能將應收帳款週轉 8 次，平均僅需 46 天就能將貨款變現；而 Nike 每年僅週轉 5 次，需要 73 天才能收回貨款。
   * Adidas 的營運資金循環更快，面臨的違約與壞帳風險相對更低，流動性（Liquidity）更佳。
2. **商業策略與通路模式之潛在意涵**：
   * **通路議價能力 (Bargaining Power)**：Nike 擁有較長的收現天數（73天），可能反映其在北美市場對大型經銷商（如 Foot Locker、Dick's Sporting Goods）給予了較長寬限期以搶佔市場佔有率。
   * **信用控管紀律**：若兩家公司的標準信用期皆為 30 ~ 45 天，則 Nike 存在嚴重的逾期催收拖延或通路庫存積壓（經銷商賣不掉故延遲付款）之風險。

---

## 3. 現金轉換循環 (Cash Conversion Cycle, CCC) 連結

在企業財務管理中，應收帳款天數 (DSO) 是三大核心週期之一：
$$\text{CCC (現金轉換循環)} = \text{DIO (存貨週轉天數)} + \mathbf{DSO (應收帳款收現天數)} - \text{DPO (應付帳款延付天數)}$$
* DSO 縮短 1 天，代表企業能少借 1 天的短期週轉金，直接降低利息支出並提高自由現金流 (Free Cash Flow)。

---

## 4. 關聯主題 (Related Concepts)

* [[Ch08-Receivables]] — Chapter 8 應收帳款全貌
* [[Ch08-Valuation-Bad-Debts]] — 備抵法與帳齡分析
* [[Ch14-Statement-of-Cash-Flows]] — 應收帳款變動與營業活動現金流的直接/間接法轉換

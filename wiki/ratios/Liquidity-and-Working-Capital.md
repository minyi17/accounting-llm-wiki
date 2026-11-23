# [財務比率] 營運資金、流動比率與速動比率 (Liquidity & Working Capital)

> 本頁定義衡量企業短期償債能力的核心三指標：營運資金 (Working Capital)、流動比率 (Current Ratio) 與速動比率 (Acid-Test Ratio)，並包含 Class Exercise 2 (Chen Group) 的完整解析與「期末美化報表 (Window Dressing)」伎倆破解。

---

## 1. 核心公式與計算定義 (Formulas & Definitions)

### (1) 營運資金 (Working Capital)
衡量企業在清償所有即將到期之流動負債後，剩餘可自由支配於日常營運的流動資產緩衝金額。
$$\text{Working Capital (金額)} = \text{Current Assets (流動資產)} - \text{Current Liabilities (流動負債)}$$
* **判讀基準**：營運資金應維持為**正數**。若為負數，代表短期資金缺口嚴重，隨時有跳票或流動性斷鏈危機。

---

### (2) 流動比率 (Current Ratio)
衡量每一元流動負債，有多少元的流動資產作為償債後盾。
$$\text{Current Ratio (倍數)} = \frac{\text{Current Assets (流動資產)}}{\text{Current Liabilities (流動負債)}}$$
* **判讀基準**：傳統經驗法則通常以 **1.5 ~ 2.0 倍** 為安全區間（視行業特性而定，例如連鎖零售業可較低，製造業需較高）。

---

### (3) 速動比率／酸性測驗比率 (Acid-Test / Quick Ratio)
流動比率可能被「變現緩慢的存貨」或「無法退現的預付費用」虛增。速動比率僅挑選**「能在極短時間內變現的高流動性資產（速動資產）」**：

$$\text{Quick Ratio (倍數)} = \frac{\text{Cash (現金)} + \text{Short-Term Investments (短期投資)} + \text{Net Receivables (應收帳款淨額)}}{\text{Current Liabilities (流動負債)}}$$
* **排除項目**：排除**存貨 (Inventory)**（可能滯銷）與**預付費用 (Prepaid Expenses)**（無法直接換回現金）。
* **判讀基準**：通常以 **1.0 倍** 為健全標準。

---

## 2. 課堂實戰詳解：Class Exercise 2 (Chen Group, P10.6)

### 題目資產負債表數據 (2025 年 12 月 31 日，千元)

| 資產 (Assets) | 金額 (¥) | 負債與權益 (Liabilities & Equity) | 金額 (¥) |
| :--- | :---: | :--- | :---: |
| 不動產、廠房及設備淨額 (Plant Assets, Net) | ¥220,000 | 普通股股本 (Share Capital - Ordinary) | ¥220,000 |
| 存貨 (Inventory) | ¥95,000 | 抵押借款 (Mortgage Payable, **2028 年到期**) | ¥140,000 |
| 應收款項 (Receivables) | ¥75,000 | 應付帳款 (Accounts Payable) | ¥70,000 |
| 現金 (Cash) | ¥40,000 | | |
| **資產總額** | **¥430,000** | **負債與權益總額** | **¥430,000** |

---

### 指標計算推導過程

#### (a) 劃分流動與非流動項目
* **流動資產合計 (Current Assets)**：
  $$\text{Current Assets} = \text{Cash } (¥40,000) + \text{Receivables } (¥75,000) + \text{Inventory } (¥95,000) = \mathbf{¥210,000}$$
* **流動負債合計 (Current Liabilities)**：
  * 應付帳款 (Accounts Payable) $= ¥70,000$
  * *(注意：Mortgage Payable 抵押借款於 2028 年到期，距今超過 2 年，**屬於非流動負債**，不得計入！)*
  $$\text{Current Liabilities} = \mathbf{¥70,000}$$

#### (b) 計算財務比率
1. **流動比率 (Current Ratio)**：
   $$\text{Current Ratio} = \frac{¥210,000}{¥70,000} = \mathbf{3.0 \text{ 倍}}$$
2. **營運資金 (Working Capital)**：
   $$\text{Working Capital} = ¥210,000 - ¥70,000 = \mathbf{¥140,000 \text{ (千元)}}$$

---

## 3. 企管管理者視角與財務盲點 (Management Insights)

### 1. 流動性 vs. 獲利性的兩難抉擇 (Liquidity vs. Profitability Trade-Off)
* 流動比率高達 3.0，雖然債權人感到極為安全，但對股東而言**並非全然好事**。
* 現金與流動資產的報酬率極低，帳上保留過多未運用的閒置流動資產，會拉低總資產報酬率 (ROA) 與股東權益報酬率 (ROE)。

### 2. 期末美化報表手法破解 (Window Dressing Defense)
經理人在年底向銀行申請貸款時，常利用會計數學特性粉飾流動比率：

> [!WARNING] 「以現金清償應付款」的美化伎倆
> 若企業當前的流動比率大於 1.0（例如：$\text{CA} = 200, \text{CL} = 100 \implies \text{CR} = 2.0$）：
> * 經理人在 12 月 31 日前，特意**提早動用現金 $50 清償應付帳款 $50**。
> * **交易後**：$\text{CA} = 150, \text{CL} = 50$。
> * **新流動比率** $= 150 / 50 = \mathbf{3.0 \text{ 倍}}$！
> * 實質營運資金完全沒變（$200 - 100 = 100$ vs $150 - 50 = 100$），但報表上的流動比率卻從 2.0 巨幅灌水至 3.0！

---

## 4. 關聯主題 (Related Concepts)

* [[Ch10-Current-Liabilities]] — Chapter 10 核心導航
* [[AR-Turnover-and-DSO]] — 應收帳款變現天數分析
* [[Working-Capital-and-Cash-Flow]] — 營運資金變動與現金流量表勾稽

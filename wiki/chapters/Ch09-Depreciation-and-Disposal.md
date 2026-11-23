# [Ch 09 專題] 折舊方法、組成份子會計、重估價與資產處分 (Depreciation & Disposal)

> 本頁深入剖析固定資產折舊之三大計算法、期中購置破月計算、IFRS 組成份子折舊與重估價模式、折舊估計變動，以及 Class Exercise 1 (Jimenez Enterprises) 的綜合全流程演練。

---

## 1. 折舊之本質與三大要素 (Nature & Factors of Depreciation)

* **會計本質**：折舊是**「成本分攤程序 (Cost Allocation)」**，而非「資產評價程序」。其目的係依合理且有系統的方法，將資產成本在估計耐用年限內分攤為費用，符合**繼續經營假設 (Going Concern)** 與**配合原則 (Matching Principle)**。
* **三大計量要素**：
  1. **成本 (Cost)**：依歷史成本原則入帳。
  2. **耐用年限 (Useful / Service Life)**：預期為企業帶來經濟效益的期間（年數或工作量）。
  3. **殘值 (Residual / Salvage Value)**：資產使用年限屆滿時，預期出售或處分可收回之淨額。
  4. **應折舊總額 (Depreciable Cost)**：$$\text{Depreciable Cost} = \text{Cost} - \text{Residual Value}$$

---

## 2. 三大折舊方法深入演繹 (Depreciation Methods)

以課本 Barb's Florists 運送設備為例：成本 €13,000，殘值 €1,000，應折舊總額 €12,000，估計耐用年限 5 年，總行駛里程 100,000 英里。

### (1) 直線法 (Straight-Line Method)
每年認列相同金額之折舊費用，假設資產效益隨時間平均遞耗。
$$\text{Annual Depreciation Expense} = \frac{\text{Cost} - \text{Residual Value}}{\text{Useful Life}} = \frac{€13,000 - €1,000}{5} = \mathbf{€2,400 \text{ /年}}$$
* **期中購置破月處理**：若於 4 月 1 日購置，第一年（4/1~12/31 共 9 個月）提列：
  $$\text{2025 年折舊} = €2,400 \times \frac{9}{12} = \mathbf{€1,800}$$

### (2) 生產數量法／活動量法 (Units-of-Activity Method)
依實際使用量或產出量提列折舊，適合耗損主要取決於使用程度而非時間的設備。
$$\text{Depreciation Cost per Unit} = \frac{\text{Cost} - \text{Residual Value}}{\text{Total Estimated Units}} = \frac{€13,000 - €1,000}{100,000 \text{ 英里}} = \mathbf{€0.12 \text{ /英里}}$$
* 2025 年行駛 15,000 英里：折舊費用 $= 15,000 \times €0.12 = \mathbf{€1,800}$
* 2026 年行駛 30,000 英里：折舊費用 $= 30,000 \times €0.12 = \mathbf{€3,600}$

### (3) 倍數餘額遞減法 (Double-Declining-Balance Method)
屬於**加速折舊法 (Accelerated Depreciation)**，前期提列較多折舊，後期提列較少。
* **折舊率**：直線法折舊率的兩倍（5 年期 $\implies 1/5 \times 2 = \mathbf{40\%}$）。
* **計算特色**：**初期完全忽略殘值**，直接以「期初帳面價值 (Beginning Book Value)」乘上折舊率。
  $$\text{Annual Depreciation} = \text{Beginning Book Value} \times \text{Declining-Balance Rate}$$
* **最後一年倒擠調整**：當帳面價值降至預估殘值時即停止提列折舊；最後一年折舊額為倒擠數：
  $$\text{最後一年折舊} = \text{期初帳面價值} - \text{預定殘值}$$

#### 全期折舊比較表 (Illustrations 9.8 ~ 9.14)
| 折舊方法 | 第 1 年折舊 | 第 2 年折舊 | 前兩年累計折舊 | 總折舊額 (5年) |
| :--- | :---: | :---: | :---: | :---: |
| **直線法** | €2,400 | €2,400 | €4,800 | €12,000 |
| **生產數量法** | €1,800 | €3,600 | €5,400 | €12,000 |
| **倍數餘額遞減法** | **€5,200** | **€3,120** | **€8,320** | €12,000 |

> [!TIP] 企管洞察：為什麼加速折舊能保護企業現金流？
> 資產剛買來時產能最高、維修費最低，此時提列高折舊，能配合資產的高收益；且高折舊產生**高所得稅盾 (Tax Shield)**，將繳稅現金流延後到後期，大幅提升初期營運資金的安全邊際。

---

## 3. IFRS 特色規範：組成份子折舊與重估價模式

### 1. 組成份子折舊 (Component Depreciation)
* **準則要求**：IFRS 強制規定，不動產若包含重大組成部分且耐用年限不同，**必須分開個別提列折舊**。
* **範例 (建築物總價 HK$4,000,000)**：
  * 主結構 (Building Structure)：成本 HK$3,080,000，年限 40 年 $\implies$ 年折舊 HK$77,000
  * 空調暖通系統 (HVAC)：成本 HK$320,000，年限 5 年 $\implies$ 年折舊 HK$64,000
  * 地面工程 (Flooring)：成本 HK$600,000，年限 10 年 $\implies$ 年折舊 HK$60,000
  * **第一年折舊合計** = $77,000 + 64,000 + 60,000 = \mathbf{HK\$201,000}$。

### 2. 固定資產重估價 (Revaluation of Plant Assets)
* IFRS 允許企業於資產負債表日以**公允價值 (Fair Value)** 重估（US GAAP 嚴格禁止）。
* **重估增值（公允價值 > 帳面價值）**：
  * 差額認列於其他綜合損益 (OCI) 中的**「重估增值 (Revaluation Surplus)」**，累積於權益項下，不影響本期淨利。
* **重估減損（公允價值 < 帳面價值）**：
  * 差額認列於損益表的**「減損損失 (Impairment Loss)」**，直接扣減本期淨利。

---

## 4. 折舊估計變動 (Revising Periodic Depreciation)

* 若資產在使用期間發現耐用年限或殘值估計有誤，會計上視為**「會計估計變動 (Change in Estimate)」**。
* **處理原則**：**推延法（Prospective Treatment）**，僅影響本期與未來期間，**絕不溯及既往更正過去已提列之折舊**。
* **新折舊額計算公式**：
  $$\text{New Annual Depreciation} = \frac{\text{變動當期期初帳面價值 (Book Value)} - \text{新估計殘值 (New Residual)}}{\text{剩餘耐用年限 (Remaining Useful Life)}}$$

---

## 5. 固定資產之處分 (Disposal of Plant Assets)

處分三步驟鐵律：
1. **補提折舊**：將折舊費用補提至處分日當天。
2. **結算帳面價值**：$\text{Book Value} = \text{Cost} - \text{累計折舊}$。
3. **計算處分損益**：比較處分收現數（Proceeds）與帳面價值：
   $$\text{處分利益／損失} = \text{處分收現金額} - \text{處分日帳面價值}$$

---

## 6. 綜合實戰題解：Class Exercise 1 (Jimenez Enterprises 完整詳解)

### 2024 年底期初狀態
* **Land**：€3,000,000
* **Buildings**：€26,500,000，累計折舊 €12,100,000（年限 50 年，無殘值，直線法）
* **Equipment**：€40,000,000，累計折舊 €5,000,000（年限 10 年，無殘值，直線法）

### 2025 年度交易分錄演繹

#### 4 月 1 日：購入土地 €2,200,000
```text
借：土地 (Land)                                     €2,200,000
    貸：現金 (Cash)                                             €2,200,000
```

#### 5 月 1 日：出售 2021/1/1 購入之設備（成本 €750,000，售價 €466,000）
* **(1) 補提 1/1 ~ 5/1 折舊 (4個月)**：
  年折舊 $= 750,000 / 10 = 75,000$；4 個月折舊 $= 75,000 \times 4/12 = \mathbf{€25,000}$。
  ```text
  借：折舊費用 (Depreciation Expense)                     €25,000
      貸：累計折舊－設備 (Accum. Deprec. - Equipment)                €25,000
  ```
* **(2) 記錄出售**：
  累計折舊 $= 75,000 \times 4 \text{ 年} + 25,000 = \mathbf{€325,000}$；帳面價值 $= 750,000 - 325,000 = \mathbf{€425,000}$。
  處分利益 $= 466,000 - 425,000 = \mathbf{€41,000}$。
  ```text
  借：現金 (Cash)                                      €466,000
  借：累計折舊－設備 (Accum. Deprec. - Equipment)        €325,000
      貸：設備 (Equipment)                                      €750,000
      貸：處分設備利益 (Gain on Sale of Equipment)                €41,000
  ```

#### 6 月 1 日：出售土地（成本 €300,000，售價 €1,800,000）
```text
借：現金 (Cash)                                     €1,800,000
    貸：土地 (Land)                                               €300,000
    貸：處分土地利益 (Gain on Sale of Land)                     €1,500,000
```

#### 7 月 1 日：購入新設備 €2,450,000
```text
借：設備 (Equipment)                                €2,450,000
    貸：現金 (Cash)                                             €2,450,000
```

#### 12 月 31 日：報廢 2015/12/31 購入之設備（成本 €500,000，無殘值）
* **(1) 補提 2025 全年折舊 (滿第 10 年)**：$500,000 / 10 = \mathbf{€50,000}$。
  ```text
  借：折舊費用 (Depreciation Expense)                     €50,000
      貸：累計折舊－設備 (Accum. Deprec. - Equipment)                €50,000
  ```
* **(2) 記錄設備報廢 (完全折舊完畢，帳面價值為 0)**：
  ```text
  借：累計折舊－設備 (Accum. Deprec. - Equipment)       €500,000
      貸：設備 (Equipment)                                       €500,000
  ```

---

### 2025 年底期末折舊調整分錄 (12/31)

1. **建築物折舊**：$26,500,000 / 50 = \mathbf{€530,000}$。
   ```text
   借：折舊費用 (Depreciation Expense)                    €530,000
       貸：累計折舊－建築物 (Accum. Deprec. - Buildings)           €530,000
   ```
2. **期末其餘設備折舊**：
   * 原有舊設備剩餘成本 $= 40,000,000 - 750,000 - 500,000 = €38,750,000$。
     全年折舊 $= 38,750,000 / 10 = €3,875,000$。
   * 7/1 購入新設備 $= 2,450,000 / 10 \times 6/12 = €122,500$。
   * **期末設備折舊調整總額** $= 3,875,000 + 122,500 = \mathbf{€3,997,500}$。
   ```text
   借：折舊費用 (Depreciation Expense)                  €3,997,500
       貸：累計折舊－設備 (Accum. Deprec. - Equipment)             €3,997,500
   ```

---

### 2025 年 12 月 31 日資產負債表表達 (Statement of Financial Position)

```text
不動產、廠房及設備 (Property, Plant, and Equipment)：
  土地 (Land)                                                    €4,900,000
  建築物 (Buildings)                              €26,500,000
  減：累計折舊－建築物 (Accumulated Depreciation)   (12,630,000)    13,870,000
  設備 (Equipment)                                 €41,200,000
  減：累計折舊－設備 (Accumulated Depreciation)     (8,247,500)    32,952,500
不動產、廠房及設備淨額合計                                       €51,722,500
```
* **各帳戶金額勾稽驗算**：
  * **Land** $= 3,000,000 + 2,200,000 - 300,000 = \mathbf{€4,900,000}$
  * **Buildings 累計折舊** $= 12,100,000 + 530,000 = \mathbf{€12,630,000}$
  * **Equipment 成本** $= 40,000,000 - 750,000 + 2,450,000 - 500,000 = \mathbf{€41,200,000}$
  * **Equipment 累計折舊** $= 5,000,000 + 25,000 - 325,000 + 50,000 - 500,000 + 3,997,500 = \mathbf{€8,247,500}$

---

## 7. 關聯主題 (Related Concepts)

* [[Ch09-Plant-Assets]] — Chapter 9 核心總覽
* [[Ch09-Natural-Resources-and-Intangibles]] — 天然資源與無形資產
* [[Asset-Turnover]] — 固定資產利用率與週轉率分析
* [[CapEx-Depreciation-and-Cash-Flow]] — 資本支出、折舊與現金流量表勾稽

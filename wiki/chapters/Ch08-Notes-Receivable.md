# [Ch 08 專題] 應收票據之認列、計息與處分 (Notes Receivable)

> 本頁深入剖析本票與應收票據之特性、到期日與利息計算、跨期兌現與拒付會計處理，以及 Class Exercise 2 (Anping Enterprises) 的完整演練。

---

## 1. 核心定義與要素 (Promissory Notes & Elements)

**本票／應收票據 (Promissory Note / Note Receivable)** 係出票人（發票人, Maker）向受款人（Payee）開立之正式書面付款承諾，保證於見票時或約定到期日無條件支付確定金額之款項。

### 適用商業情境
1. 企業或個人間之直接借貸融資 (Lending/Borrowing transactions)。
2. 交易金額龐大且信用期間超過一般賒銷正常期限 (Exceeding normal credit limits)。
3. 客戶應收帳款已逾期，經雙方協商延長還款期限並轉為正式計息票據以強化法律擔保 (Settlement of open accounts receivable)。

### 票據三核心計量要素
* **面額 (Face Value, Principal)**：票據票面載明之本金金額。
* **票面利率 (Stated Annual Interest Rate)**：票載之年利率。
* **發票日與到期日 (Issue Date & Maturity Date)**。

---

## 2. 到期日與利息計算公式 (Maturity Date & Interest Calculation)

### (1) 到期日判定規則
* **以「月」為單位**：例如 5 月 1 日發行之 2 個月期票據，到期日為 7 月 1 日。
* **以「天」為單位**：**「算尾不算頭」**（發票日當天不計入，但到期日當天需計入）。
  * 範例：7 月 17 日開立之 60 天期票據：
    * 7 月份剩餘天數：$31 - 17 = 14$ 天
    * 8 月份天數：$31$ 天（累計 $14 + 31 = 45$ 天）
    * 9 月份所需天數：$60 - 45 = 15$ 天 $\implies$ **到期日為 9 月 15 日**。

### (2) 利息計算公式 (Interest Formula)
$$\text{Interest (利息)} = \text{Face Value (面額)} \times \text{Annual Interest Rate (年利率)} \times \frac{\text{Term of Note (期間)}}{\text{360 天 (或 12 個月)}}$$
*(註：Weygandt 初會教科書及實務常採用一年 360 天之商業慣例簡化利息計算)*

---

## 3. 票據處理生命週期 (Accounting Lifecycle & Entries)

### 階段一：收受票據 (Receipt of Note)
* **清償逾期應收帳款**：
```text
借：應收票據 (Notes Receivable)                         $1,000
    貸：應收帳款 (Accounts Receivable)                           $1,000
```
* **直接借款給他公司**：
```text
借：應收票據 (Notes Receivable)                        $10,000
    貸：現金 (Cash)                                             $10,000
```

### 階段二：到期兌現 (Honor of Notes Receivable)

#### 情境 A：發行與到期落在「同一會計年度」
* 範例：6 月 1 日收受 5 個月期、9% 票據 €10,000，11 月 1 日全數兌現（5 個月利息 = $€10,000 \times 9\% \times 5/12 = €375$）：
```text
11/01
借：現金 (Cash)                                       €10,375
    貸：應收票據 (Notes Receivable)                             €10,000
    貸：利息收入 (Interest Revenue)                                €375
```

#### 情境 B：跨會計年度（需於資產負債表日作應計調整）
* 承上例，若公司會計年度結算日為 9 月 30 日（9/30 結算，11/1 到期）：
```text
09/30 (結算日應計 4 個月利息：€10,000 × 9% × 4/12 = €300)
借：應收利息 (Interest Receivable)                       €300
    貸：利息收入 (Interest Revenue)                                €300

11/01 (到期兌現收款，收取本金及全期 5 個月利息 €375)
借：現金 (Cash)                                       €10,375
    貸：應收票據 (Notes Receivable)                             €10,000
    貸：應收利息 (Interest Receivable - 沖轉前期應計數)            €300
    貸：利息收入 (Interest Revenue - 本期 10 月份 1 個月)           €75
```

---

### 階段三：票據拒付 (Dishonor of Notes Receivable)
當發票人到期無法全額清償時，票據即為「拒付」，不再具備流通性：

#### 情況 1：仍預期客戶後續具備還款能力 (Expect Eventual Collection)
* 將本金連同**全部應計利息**一併轉為對該客戶的「應收帳款」以利追索：
```text
借：應收帳款 (Accounts Receivable)                    €10,375
    貸：應收票據 (Notes Receivable)                             €10,000
    貸：利息收入 (Interest Revenue)                                €375
```

#### 情況 2：確認客戶破產、無法收回 (Expect Collection Will NOT Occur)
* 不認列任何利息收入，直接動用「備抵損失」將票據本金沖銷：
```text
借：備抵損失 (Allowance for Doubtful Accounts)         €10,000
    貸：應收票據 (Notes Receivable)                             €10,000
```

---

## 4. 經典課堂題解：Class Exercise 2 (Anping Enterprises 完整題解)

### 題目背景
安平企業 (Anping Enterprises) 於每年 7 月 31 日結帳，僅於年底進行利息應計調整。6 月 30 日應收票據餘額為 NT$23,800（千元），包含：
1. **Coote Inc.**：面額 NT$6,000，90 天期，利率 8%，到期日 7 月 20 日。
2. **Brady Co.**：面額 NT$7,800，60 天期，利率 10%，到期日 7 月 24 日。
3. **BMG Corp.**：面額 NT$10,000，6 個月期，利率 6%，發票日 6 月 30 日（到期日次年 12 月底）。

7 月份交易事項：
* **7/05**：以安平自有信用卡賒銷 NT$4,500。
* **7/14**：以 Visa 信用卡銷貨 NT$600，Visa 手續費率 3%。
* **7/20**：全額收妥 Coote Inc. 到期本息。
* **7/24**：全額收妥 Brady Co. 到期本息。
* **7/31**：提列 BMG Corp. 應收利息調整分錄。

---

### 問題解答與分錄演繹

#### (a) 7 月份交易分錄與 7/31 利息調整分錄
```text
Jul. 05  借：應收帳款 (Accounts Receivable)           NT$4,500
             貸：銷貨收入 (Sales Revenue)                         NT$4,500
         (自有信用卡賒銷)

Jul. 14  借：現金 (Cash)                                NT$582
         借：手續費費用 (Service Charge Expense, 600×3%)   NT$18
             貸：銷貨收入 (Sales Revenue)                           NT$600
         (Visa 信用卡銷貨，3% 手續費)

Jul. 20  借：現金 (Cash)                              NT$6,120
             貸：應收票據 (Notes Receivable)                       NT$6,000
             貸：利息收入 (Interest Revenue)                         NT$120
         (Coote 利息 = 6,000 × 8% × 90/360 = 120)

Jul. 24  借：現金 (Cash)                              NT$7,930
             貸：應收票據 (Notes Receivable)                       NT$7,800
             貸：利息收入 (Interest Revenue)                         NT$130
         (Brady 利息 = 7,800 × 10% × 60/360 = 130)

Jul. 31  借：應收利息 (Interest Receivable)             NT$50
             貸：利息收入 (Interest Revenue)                          NT$50
         (BMG 利息調整 = 10,000 × 6% × 1/12 = 50)
```

#### (b) 應收款項 T 字帳過帳 (T-Accounts)

```text
       應收票據 (Notes Receivable)
------------------------------------------
期初 (7/1)    23,800 | 7/20 Coote 收現   6,000
                     | 7/24 Brady 收現   7,800
------------------------------------------
期末餘額 (7/31) 10,000 (為 BMG 票據)

       應收帳款 (Accounts Receivable)
------------------------------------------
期初 (7/1)         0 | 
7/5 自有卡賒銷  4,500 | 
------------------------------------------
期末餘額 (7/31)  4,500 |

       應收利息 (Interest Receivable)
------------------------------------------
7/31 應計調整     50 | 
------------------------------------------
期末餘額 (7/31)    50 |
```

#### (c) 7 月 31 日資產負債表表達 (Statement of Financial Position)
```text
流動資產 (Current Assets)：
  應收票據 (Notes Receivable)                 NT$10,000
  應收帳款 (Accounts Receivable)               NT$4,500
  應收利息 (Interest Receivable)                  NT$50
流動資產總計 (Total Current Assets)           NT$14,550  (千元)
```

---

## 5. 企管管理者視角 (Management Implications)

1. **應收票據作為債權保障的法律防線**：
   * 商業信用（應收帳款）多為口頭或發票約定，若客戶賴帳，訴訟舉證程序冗長。
   * 要求客戶簽發本票（Notes Receivable）具備法律本票裁定之執行力，是經理人處理**高風險或延期還款客戶時的最佳風險管理手段**。
2. **票據貼現與資金調度 (Discounting Notes)**：
   * 當企業面臨流動性缺口時，持未到期票據向銀行貼現可換取現金。經理人需注意「附追索權 (With Recourse)」之貼現會產生**或有負債 (Contingent Liability)**，若發票人違約，銀行仍會向本公司追償。

---

## 6. 關聯主題 (Related Concepts)

* [[Ch08-Receivables]] — Chapter 8 全章核心導航
* [[Ch08-Valuation-Bad-Debts]] — 應收帳款備抵法評價與帳齡分析
* [[Ch10-Current-Liabilities]] — 票據對立面：應付票據 (Notes Payable) 之會計處理

<style> * {font-family: "roboto", sans-serif; line-height: 1.5em;} h1,h2,h3 {font-family: "open-sans", sans-serif; } h2 { color: #777; } h3 { color: #4285f4; font-size: 1.5em; margin-bottom: 0;} hr {opacity: .5} .date {font-size: larger; color: #777;} th{background: #e0e6ee;} code {color: #659999;} img {filter: grayscale(100%) brightness(0%);}</style>

# MBM | PMG :  Dealer Bonus Reference

<span class="date">_As of Q1 2019_</span>

---

I am writing this program as a brief reference point for the person(s)responsible for calculating manufacturer bonus amounts earned each month or for anyone who wants to learn more about how the MB programs generally work and payout at the time of this writing. It may also be helpful for balancing the Sales Doc, especially for the last day of the month.

For the person reporting amounts to accounting, I've provided ways which I've accessed/compiled the information, but feel free to use another, as long as accounting receives the necessary information by the time they need it. Typically they require a spreadsheet that details a bonus amount earned, the program it is earned for, and some unique identifier for the vehicle that earned it (VIN/stock/etc.).

Programs sent to accounting usually include detail for:
* <a href="#amg">AMG Sales Bonus</a>
* <a href="#leadership">Leadership Accrual</a>.
* <a href="#dealer-cash">Dealer Bonus, Region Cash Earnings</a>
* <a href="#c3">C3 Program Earnings</a>


Programs change and vary per MB, so these descriptions may be inaccurate in the near future. Mercedes is also constantly improving their reporting software. The best way to learn about any of these programs is by reading the official manuals in Netstar or the specific program rules details. Continue reading for a brief overview on each of these programs, which are, as MB would say," *_subject to change_".

---
## NEW

### **Dealer Performance Bonus**
---

Earned _Dealer Performance Bonus_, colloquially "below the line money", is calculated on a percentage of MSRP basis per achieving specified performance qualifiers for the previous quarter.

For vehicles wholesaled after Jan 3<sup>rd</sup>, 2019, the qualifiers and respective percentages are as followed:

Qualifier | Percentage (`%`)
------- | ---------
Sales Experience Scores | `0.75%`
Service Opportunity Index | `0.75%`
Training Bonus | `0.50%`
Sales Effectiveness | `0.75%`
Off-Lease Qualifiers | `0.75%`
Brand Standards Bonus | `2.00%`

We will also earn automatically, without any qualifiers:
Description | Percentage (`%`)
--- | ---
Flooring Interest | `1.00%`
Operational Expense Assistance | `0.50%`

For vehicles wholesaled before 1/3/2019, operational expense assistance is only `0.25%`. Vehicles wholesaled before 1/4/2018 do not earn any (`$0`) operational expense assistance. 

Percentages are multiplied with an _adjusted_ MSRP. The general formula is:

```
(MSRP
less(-) Destination/Delivery charge
less(-) Gas Guzzler Tax
) * %
```

After adjustment, the above categories can be summed into one % to multiply by, based on the wholesale date, represented by the year code shown in Netstar retail:
Year | Total `%`
--- | ---
191 | `6.0%`
182 | `5.5%`
181 | `5.0%`


As of this writing, we account for all of these categories _excluding_ Flooring Interest in the Sales Doc, and accounting typically puts all of the categories with qualifiers under 'New Additions', and operational expense to courtesy vehicles. The operational expense difference normally accounts for $20 - $40K of discrepancy between the doc amount sent on the last day of the month and the finalized variable gross. 

These amounts typically do NOT need to be sent to accounting, but may be useful for verifying under/over on the sales doc and for verification with Mercedes final amounts. Amount earned per vehicle can be searched individually via the "new" dealer performance bonus scorecard, or seen as a statement in Netstar Reports, typically released 3-5 days after close. 

### <span id="amg">**AMG Performance Bonus**</span>
---
The AMG Performance Bonus works similarly to the Dealer Performance Bonus. However, the qualifiers and percent differ.

As of this writing, the qualifier is purely achieving AMG Sales goals. While the payout is also based on the previous quarter, and typically paid once per quarter, this program is typically less strict based on inventory variability, and also allows for a "catch-up" qualifier, by receiving payout if you achieve the annual AMG Sales goal, but miss a quarterly goal. 

AMG Sales counts and bonus earnings only apply to "One Man - One Engine" vehicles. (e.g GT's, *65, *63, *55, *45, etc.). As of this writing, *43's, *53s, do not qualify. 

AMG Performance Bonus % for our current tier is `1%`, multiplied with the adjusted MSRP formula in 'DPB'.

Usually, qualifying vehicles with accordingly calculated amounts are sent to accounting to be included for posting. These amounts are available in Netstar in the same area as the DPB, though usually 3-7 days after close. 

### <span id="leadership">**Leadership Acrrual**</span>
---
The MB Leadership Bonus program divies unearned Dealer Performance Bonus amounts from all dealers to qualifying dealerships. For 2019, qualifying dealerships will have:
* Green CEx Sales scores
* Achieve Training Bonus
* Achieve Brand Standards
* Meet StockPro Criteria

If qualified, we will receive payout in April for Q2 of the previous year through Q1 of the current year. for all New Vehicle retails and CVP sales. Since this program is paid out of a "pool", the amount earned per unit varies each year. We have seen it range from $80/unit to $170/unit. Nothing is received if qualifiers aren't met. 

The amount posted each month is chosen somewhat arbitrarily. In 2018 and so far in 2019, we have accrued $100 per new vehicle retail, not accruing anything for CVP.

Accounting requires a list of all new vehicle retails with the chosen amount per unit to accrue for.

Note this will leave SCH55 with a an aging snowball that should hopefully clear every April.

### <span id="dealer-cash">**Bonus, Regional "Dealer" Cash**</span>
---
**Preface**: This is general guide for multiple programs that fall under this umbrella. This area is one of the more complicated ones that requires double checking. Often MB will even make mistakes upon payment. 

Bonus, Regional Cash, referred to as dealer cash herein, is generally any earned cash that is not seen in deal postings. While the earnings will be tied to a specific vehicle similar to leadership, this money is not currently included in salesperson commission calculations.

Dealer cash programs are typically **not** in Netstar. They are usually sent via email by the MB Market Rep/Manager. To determine qualifying vehicles simply requires matching sold vehicles with the program rules (which do vary). These program rules should be given first priority. Following are a few guidelines that are *generally* true for the program:

* New vehicle DDR's matching the specified model for the program typically qualify.
    * This almost always exludes EDD's & "Ex-EDD's", as well as pinnacle sales.
* Programs will typically only include "CVP" sales (put into loaner) OR "Ex-CVP" vehicles (4R* stock numbers). 
* Should "Ex-CVP's" be included in the program, only vehicles that are "retailed as new" will qualify.
    * The simple rule is if we use the "Customer Incentive Bonus" or "Fleet Bonus" for the deal, this was retailed as new. 
    * Usually, it does **not** matter (with respect to this program) if the vehicle was Certified. 
    * If special CPO rates or programs (e.g free maintenance) are used, this program will be given priority and will not be eligible for dealer cash bonuses. 
* Again, special demos or Ex-EDD sales almost always are ineligible.

**Gotchas**: _errors where DDR date & contract date fall in different MB cycles usually result in no payment whatsoever, but occasionally are paid out for the program in effect when the vehicle is DDR'd._ 

In the case where a Mercedes month cycle does not align with the PMG cycle (e.g a close on the 1st & 2nd), we typically keep the bonus earnings tied to the PMG month. 

Although accounting really only needs a VIN, an earning amount and maybe a description, it helps to keep the programs as separate as possible for tracking discrepancies later. For example, describing each program with a month title, differentiating separate programs for the same month, and even separating earnings for "New retails" and "Ex-CVP retails" should they both qualify. 

Usually all of this money should be included in the doc. Postings for new vehicles typically are against cost of goods, and for ex-cvp, used vehicle cost of goods. (e.g will see in gross, not additions). 

The only exception when this money is not included in the doc is when the program has "Override" money. As long as I've been doing this program, amounts and VINs are sent to accounting as a separate programming, letting them know Mike W. will decide what to do with that money. 

Lastly, I'll reiterate that it helps to keep documents of what we accrue for with very specific program names for the often case that Mercedes misses a payment, creating a discrepancy in SCH55. If unsure whether a vehicle qualifies or not, it's better to err on the "it doesn't" qualify side. 

---

## USED

### <span id="c3">**C3 - Overview**</span>
---
C3 money refers to off-lease disposition acquisitions and retailed. It is often referred to as one program, but should be looked at as three when determining payout amounts:
* C3 CPO Retails
* **Non-C3** CPO Retails
* C3 Grounding/Acquisition Bonus

As of this writing, the retail bonus payout amounts are determined by the preceding month's CPO sales relative to the MB CPO objective. Amounts also vary, but can be found in the Sales Program Guide each month. Perhaps the way to ensure you are using the right percentage amount is to look at https://www.mercedesprograminfo.com. This is not, however, the most accurate way to determine payout amounts.

The best way I've found to determine amounts is by looking at the VIN level report for the given month accessed via the C3 widget on Netstar. More on this in each category below.  

### **C3 CPO Retail**
---

Upon accessing the VIN level report, you'll see a list of the C3 CPO sales and acquisitions. For this category, you can assume each of the rows with "C3 Retail" will earn the determined amount. Do make sure to minus any retails with any shown calculations though. 

Another way, though sometimes delayed or wrong, will be looking at the CPO retails in Netstar. Vehicles that qualify as a C3 CPO retail will show 'Y' under 'MBCPO' and 'C3' under 'PGM'. 

**Gotchas**: _C3 retails that are NOT certified will still show under the VIN level report. Make sure to double check that it was indeed certified._ 

### **CPO (Non-C3) Retail**
---

To determine Non-C3 CPO retail qualifying vehicles, I recommend using the Pre-Owned Retails download in NetStar, filtering to only Certified sales (Y under MBCPO), removing any that you determined were C3 retails, and then removing any vehicles that were retailed as new (despite whether they show MBCPO or not). Vehicles retailed as new but showing as Certified are typically Ex-CVP vehicles. There are cases when these vehicle do qualify (refer to specifications under Bonus, Regional cash), but for the most part, we use the new car incentive, disqualifying the vehicle for this program. 

### **C3 Grounding Bonus**
---

This earning amount does not vary month to month. For the past 2 years, it has been $300 per qualifying unit. After some trial-and-error, the best way to determine which of these vehicles qualify is by looking at the VIN level C3 report. 

Filter the report down to only those with type "C3 Acquisition". From there, any vehicles with the the below types are eligible. Any outside of this type are not.
* **DPP Grounded** (not DPP+ Closed) 
* **Payoff**
* **ICP**

For a quick rule of thumb, generally any vehicle stocked in for the given month with a stock number of 4L* or 4CP* will be qualifiers. 

**Gotchas**: Even if the vehicle does not end up being certified, if the acquistion type matches, it will qualify. And, if a C3 acquisition did not qualify for this earning (aka was not one of the above programs), it can still qualify for the C3 retail payout.

### **Other Occurrences**
---
Besides Ex-CVP sales qualifying for the "new car" dealer cash programs, C3 typically is the majority of used car additions. There are occasionally other cases that would be considered a "Used car bonus" though:

* Cases of reimbursement for certification costs that ended up being sold as new. 
* Pre-paid maintenance honorarium money for months where the CPO specials include pre-paid maintenance to buyers.

I don't recommend worrying about or including these amounts since it's difficult to keep track of and usually not a significant amount. (e.g $25/unit for the PPM honorarium.)

---

### **Final Notes**
---

* For each of these programs, ensure the amount isn't already included in the deal. If it is, determine whether to remove it from the deal, or not include it to accrue for. If it is on both, double will be posted and expected. 
* Again, try to keep a detailed description separated by month and specific program. When a payment amount is missed or is different, having this handy will save you time in determining if it was our error or MB's error. Payment program report summaries and per VIN can be found in the market support system link via Netstar. 
* More often than not, programs are paid out on different statements. If you are missing money after seeing some of the program paid, give it one more statement, then inquire about any monies still not received.
* For me, the easiest way to prepare for sending is to download both the NetStar retail report for New & Pre-owned to a spreadsheet, download a list of sales for the PMG month from CDK Drive to another spreadsheet, and proceed to match up the programs with each of the Vins according to how they are retailed for both PMG & MB. 

<br><br>
Hope this helps and happy accounting! 

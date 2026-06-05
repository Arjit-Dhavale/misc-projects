# Rent It Out or Sell & Invest — Complete User Guide

> **Reminder:** This tool is a financial model, not professional advice. Numbers are only as accurate as the inputs you provide. Confirm tax figures with a CPA and consult a financial advisor before making major decisions.

---

## What This Tool Does

You're moving. You own a home. You have two choices: sell it now and invest the proceeds, or keep it and rent it out to tenants.

This tool races those two futures **year by year** using your actual numbers — every landlord cost, every selling cost, your mortgage, your taxes, and your employer's relocation package. It shows you which path produces more total wealth at your chosen horizon, when (if ever) one path overtakes the other, and exactly what home-appreciation rate the property would need to grow at for renting to beat selling.

---

## How to Use It (Quick Start)

1. **Start at the top — Relocation & moving benefits.** If your employer is paying for your move, enter the package details here. If not, set both package dropdowns to "None."

2. **Fill in Property & tax profile.** Use your actual purchase price, today's market value, and your real tax rates. The mortgage sub-box matters a lot — enter your loan balance and rate accurately.

3. **Fill in the Rent costs panel.** Enter what you'd realistically charge in rent and every cost you'd bear as a landlord. Don't underestimate — use the hover tooltips for guidance on each line.

4. **Fill in the Sell costs panel.** Enter the commission rate, expected concessions, and any prep work costs.

5. **Set Comparison assumptions.** Choose your horizon (how many years to compare), your expected home appreciation, and the investment return you'd earn on the proceeds if you sold.

6. **Read the verdict banner at the top.** It tells you which path wins, by how much, at your chosen horizon — and the break-even appreciation rate that would flip the verdict.

7. **Scroll through the output cards** for the sell waterfall, rent cash-flow breakdown, tax picture, and wealth comparison bars.

8. **Adjust inputs and watch the results update live.** Try different horizons, appreciation rates, and investment returns to stress-test the decision.

---

## The Two Paths — What the Tool Is Comparing

**Sell path:** You sell the home today. After paying selling costs, clearing the mortgage, and paying any capital-gains tax, you invest the net proceeds at your assumed investment return. That lump sum compounds over your horizon.

**Rent path:** You keep the home and rent it to tenants. Each year's after-tax rental cash flow is reinvested. At the end of your horizon, you sell the home, pay selling costs, clear the remaining mortgage balance, and pay the (usually larger) tax bill — then add everything up.

Both paths are alternatives, not things you do simultaneously. The tool finds which one leaves you richer at your chosen horizon.

---

## Input Fields — What Each One Means

### Relocation & Moving Benefits

This panel is for employer relocation packages. **If you have no relocation package, set both package dropdowns to "None" and skip this panel.**

---

**Your status** (Homeowner / Non-homeowner)
Sets the default dollar amounts for the MEA and lump sum. Homeowners receive larger benefits because selling a home is more complex. Homeowner defaults: $3,500 MEA, $30,000 lump. Non-homeowner: $2,000 MEA, $20,000 lump.

---

**Package if you SELL** and **Package if you RENT**

These are two separate fields because the optimal package choice depends on what you do with the house — and the tool compares each path at its own best-case package.

- **Full-service:** Your employer directly covers your home-selling costs (agent commission, closing costs, transfer tax, etc.) and gives a small cash MEA. This coverage is only valuable if you actually sell — on the sell path it's a direct credit. On the rent path, that selling coverage goes unused, so only the MEA carries over.
- **Lump sum:** You receive a single net cash payment ($30K homeowner / $20K non-homeowner). Your employer pays the tax on it. This is cash either way — it boosts your sell proceeds or gets invested on the rent path.
- **None:** No relocation benefit on this path.

*Why two dropdowns?* Because in the sell scenario, full-service (which covers ~$25–30K of selling costs on a typical home) is usually more valuable than the $30K lump. In the rent scenario, the home-selling coverage is worthless, so the lump sum wins. Setting each path to its natural best-case makes the comparison fair. In reality you commit to one package — if you want to model that, set both dropdowns to the same option.

---

**Months at new role**
How long you expect to stay with the employer after relocating. This drives the clawback calculation:
- Full-service package: 24-month clawback window, prorated.
- Lump-sum package: 12-month clawback window, prorated.

If you leave inside the window, you repay the unserved fraction. Example: leave at 12 months on a full-service package → you repay 12/24 = 50% of the benefit. The tool subtracts this automatically from each path's benefit when triggered. The clawback is about your **employment**, not about how long you hold the house.

---

**Lump-sum amount (net)**
The lump-sum payout from your employer — net, meaning they pay the income tax on your behalf. Default: $30,000 (homeowner) or $20,000 (non-homeowner). Adjust if your actual offer differs.

---

**Misc. expense allowance (MEA)**
Discretionary cash paid directly to you to cover incidentals during the move — pet deposits, utility hookups, minor travel, etc. Default: $3,500 (homeowner) or $2,000 (non-homeowner). Unlike the lump sum, the MEA is **taxable income** that your employer does not gross up, so what you actually keep is less.

---

**MEA is taxable (not grossed up)**
Leave this checked if the MEA is taxable and not grossed up (the standard). The tool reduces the MEA by your ordinary federal tax rate to show what you keep after tax.

---

**Full-service covers these selling costs** (checkboxes)
Check each cost your employer's program actually covers. The tool credits these amounts back to you on the sell path, since you would have otherwise paid them out of pocket.
- *Agent commission* — total agent fees (listing + buyer).
- *Closing costs (seller side)* — title, attorney, settlement, recording.
- *Transfer tax* — state/local tax on the sale.
- *Seller concessions* — credits to the buyer.
- *Pre-sale prep* — repairs, staging, cleaning before listing.

---

**Coverage cap (0 = none)**
If your employer caps total coverage (e.g., "we'll pay selling costs up to $25,000"), enter that limit. Enter 0 if coverage is uncapped.

---

### Property & Tax Profile

---

**Current market value**
What your home is worth today — your realistic sale price. This is also the base from which appreciation compounds. Use a recent appraisal or comparable sales, not the Zillow estimate alone.

---

**Original purchase price**
What you originally paid. This is the starting point for your cost basis.

---

**Capital improvements since purchase**
Money spent on permanent, value-adding improvements — a new roof, addition, kitchen remodel, HVAC replacement. These increase your cost basis and reduce your taxable gain at sale. Routine maintenance and repairs do not count.

---

**Land portion of value**
Land cannot be depreciated. Only the building can. You must split your cost basis into land and building for the depreciation calculation. A practical, IRS-accepted method: look at your property-tax assessment and use the land-to-total ratio. If the assessment shows Land $15,000 / Building $44,400 / Total $59,400, then land portion = 15,000 ÷ 59,400 = **25%**. Enter that percentage here. Apply the ratio to your actual market value, not the assessed dollar amounts.

---

**Filing status**
Single or Married (filing jointly). This sets your **§121 exclusion** — the amount of home-sale gain you can exclude from tax:
- Single: up to **$250,000** excluded
- Married (joint): up to **$500,000** excluded

This is one of the biggest tax differences between the two filing statuses and can meaningfully change which path wins.

---

**Ordinary income tax rate (federal)**
Your top federal marginal rate. This applies to taxable rental profit and to depreciation recapture at sale (capped at 25% for the federal recapture portion).

**2026 single filer brackets (approximate):**
- 32% bracket: ~$202K–$256K of taxable income
- 35% bracket: ~$256K–$641K
- 37% bracket: above $641K

Note: 37% is a common misconception for high earners. You're only in 37% if your **taxable income** (after all deductions) exceeds ~$641K.

*Do not include NIIT (3.8%) or state tax here — the tool adds those separately.*

---

**Long-term cap-gains rate**
Federal rate on the appreciation portion of a taxable home sale — 0%, 15%, or 20% depending on your taxable income. Most homeowners use 15%.

---

**State tax rate (gain & recapture)**
State income tax applied at sale. This reduces the gain (and now also the recapture) in the tool. NJ's top rate for this income range is approximately 6.37%. Enter 0 if your state has no income tax on gains.

---

**Apply 3.8% NIIT (Net Investment Income Tax)**
Check this if your modified AGI exceeds $200,000 (single) or $250,000 (married). The NIIT applies to the sale gain, the depreciation recapture, and any year in which your rental income is net-positive. Leave unchecked if your income is below the threshold.

---

**Qualifies for §121 primary-residence exclusion**
Check this if you've lived in the home as your primary residence for at least 2 of the last 5 years — the standard IRS test. When checked, the tool excludes up to $250K/$500K of appreciation from capital-gains tax at sale.

---

**§121 valid if sold within (years)**
Once you move out, the 2-of-5 year clock starts ticking. This field says how many years you have left before §121 expires. Typically **~3 years** if you've been in the home at least 2 years. After this window closes, renting and selling later exposes the full gain to capital-gains tax. This is one of the most powerful arguments for selling promptly rather than renting indefinitely.

---

**Mortgage — Loan balance**
Your current outstanding mortgage balance. This is subtracted from sale proceeds in the sell scenario, and the mortgage continues amortizing in the rent scenario. **This is the most important input for changing the sell-vs-rent verdict.** If your balance is large (say $280K on a $410K home), selling only frees up ~$100K to invest. The rent path keeps the full home equity working with leverage, which dramatically improves the rent case in early years.

---

**Mortgage — Interest rate**
Your current annual mortgage rate. Only the interest portion of each payment is tax-deductible against rental income — the principal portion builds equity but is not deductible.

---

**Mortgage — Term remaining**
Years left to pay off the loan. Used to compute the amortization schedule.

---

**Monthly P&I override**
If you know your exact monthly payment (from your mortgage statement), enter it here to skip the auto-calculation. Leave at 0 to have the tool compute it from the balance, rate, and term.

---

### If You RENT — The Costs

Every number in this section represents a cost you bear as a landlord. Together they determine your rental cash flow and your taxable rental income.

---

**Monthly rent**
What you'd charge a tenant. A widely used rule of thumb: monthly rent should be at least **1% of home value** for rental economics to be favorable. Example: $410,000 home → $4,100/month threshold. If you can only charge $2,800/month, your gross rent yield is 0.68%/month — below the threshold. This doesn't make renting automatically wrong, but it means appreciation and appreciation alone must carry most of the case for renting.

---

**Annual rent growth**
How much rent rises each year. Typically **2–4%** in most markets, tracking roughly with inflation.

---

**HOA dues**
Your monthly homeowners-association dues, if any. These continue as a landlord cost.

---

**HOA rental / processing fees**
Some HOAs charge additional fees when you rent out your unit — tenant screening fees, move-in/move-out fees, or a subletting surcharge. Check your HOA rules.

---

**Municipal rental registration**
Many municipalities (especially in New Jersey) require annual registration as a landlord and periodic inspections, typically $75–$300/year.

---

**Property tax**
Your annual property-tax bill. As a rental property, this moves from Schedule A (personal, SALT-capped at $40,400 for most filers in 2026) to **Schedule E** (rental, uncapped). This means the property-tax deduction is often more valuable on a rental than as an owner-occupant.

---

**Landlord insurance**
Landlord (dwelling/rental) insurance covers the structure, liability, and lost-rent coverage. It is more expensive than standard homeowner's insurance — budget 10–25% more.

---

**Repairs & maintenance**
Routine upkeep: fixing leaks, painting, appliance repairs. These are deductible in the year spent. A common estimate is **1% of home value per year**, or about **10% of gross rent**.

---

**Capital reserve (CapEx)**
Money set aside for large replacements — roof, HVAC, water heater, flooring. These are not deducted when reserved — they are depreciated when actually spent. Budget **0.5–1.5% of home value per year** depending on the home's age and condition. Skipping this line makes cash flow look artificially good.

---

**Vacancy allowance**
The percentage of gross rent lost to vacancy between tenants. Realistic range: **5–8%** for a single-family rental with typical tenant turnover. A 5% vacancy = roughly 2.5 weeks per year empty.

---

**Property management**
If you're relocating out of state, a property manager is essentially mandatory. Typical fee: **8–10% of collected rent** (not gross rent). The tool applies this percentage after vacancy.

---

**Leasing fee (per new tenant)**
The fee to find, screen, and place a new tenant — typically **1 month's rent** per new lease, paid to the property manager. The tool amortizes this over the average tenancy.

---

**Avg tenant stays (years)**
How long a typical tenant remains. This spreads the leasing fee over time. A 2-year average tenant means the leasing fee effectively costs 1 month ÷ 24 months ≈ 4.2% per month of rent.

---

**Landlord-paid utilities**
Utilities you, not the tenant, pay — water, trash, common-area electricity. Often $0 for a condo where the HOA covers these.

---

**Legal & accounting**
Lease preparation, eviction risk reserve, and Schedule E tax preparation. Budget $300–$600/year.

---

**Cost inflation**
How fast your landlord costs (taxes, insurance, repairs, HOA, etc.) grow each year. Typically matches general inflation: **2.5–3.5%**.

---

**High earner — suspend rental losses until sale**
Check this if your modified adjusted gross income (MAGI) is above **~$150,000**. Above this threshold, the IRS passive-activity loss rules prevent you from deducting a net rental loss against your W-2 or other ordinary income in the year it occurs. The loss is "suspended" and accumulates until you sell — at which point it offsets the gain. **Leaving this unchecked when it should be checked overstates your annual after-tax cash flow.** For most high-income professionals, this box should be checked.

---

### If You SELL — The Costs

---

**Agent commission (total)**
Total agent fees — both listing agent and buyer's agent. Traditionally 5–6%. Post-NAR settlement this may be lower; negotiate accordingly and enter your expected rate.

---

**Seller concessions**
Credits you give the buyer at closing — often used to cover their closing costs or repair credits. Common range: 0–2% depending on market conditions and negotiation.

---

**Closing costs (seller side)**
Title, attorney, escrow/settlement, deed preparation, and recording fees. Typically **0.5–1%** of the sale price.

---

**Transfer tax**
State and local tax imposed on the sale. New Jersey's realty transfer fee is approximately **1–1.25%** for the seller on a typical home sale (the rate is tiered by sale price). Confirm your jurisdiction's current rate.

---

**Pre-sale repairs / staging / landscaping / cleaning**
Out-of-pocket costs to prepare the home for listing. These reduce your **cash** from the sale but do **not** reduce your taxable gain — that's the IRS distinction between "selling expenses" (which do reduce gain) and "fix-up costs" (which don't). Commission, closing costs, transfer tax, and concessions do reduce gain.

---

### Comparison Assumptions

---

**Analysis horizon (years)**
How many years into the future you're comparing the two paths. The verdict banner and wealth comparison are read at this year.

**This is the single most important assumption to experiment with.** At a 2-year horizon, selling almost always wins — rental cash flow has barely accumulated and there's no time to overcome the selling-cost drag. At 10–15 years, renting has had time to build cash flow and equity. Try several horizons to understand how the verdict changes.

---

**Table years**
How many rows to show in the year-by-year detail table. Can be set lower than the horizon to keep the table manageable.

---

**Home appreciation %**
Annual rate at which the home's value grows. Historical context:
- US national long-run average: **~3–4%/year** (roughly tracking inflation)
- High-growth coastal metros (NYC suburbs, Bay Area): have averaged **5–7%/year** over the past decade, though this is not guaranteed to continue
- Inflation-adjusted "real" appreciation: **~1–2%/year** nationally over the very long run

The break-even appreciation line in the verdict tells you exactly what appreciation rate the home needs to achieve for renting to win. Compare that threshold against your local market expectations.

---

**Investment return %**
What you'd earn annually by investing the sale proceeds (typically in a diversified equity portfolio). Key points:
- The S&P 500 has averaged **~10% nominal** / **~7% real** (after inflation) per year since 1926.
- These two figures are not contradictory — "7% real" and "10% nominal" describe the same historical return measured in different ways.
- For a consistent model: if your appreciation rate is nominal (3–4%), your investment return should also be nominal (~7–10%). Mixing real and nominal assumptions will distort the comparison.
- Use **7%** as a conservative nominal estimate; **10%** as the historical average. The right choice depends on your own investment approach and risk tolerance.

---

## Understanding the Outputs

### Verdict Banner (top of page)

Shows which path wins at your chosen horizon, by how much, and the current appreciation rate assumed. The second line shows the **break-even appreciation rate** — the annual home-price growth rate at which both paths tie. If your expected appreciation is below that threshold, selling wins; above it, renting wins.

---

### Sell Waterfall Card ("If you sell now")

A step-by-step reconciliation from sale price to net cash in hand:

| Line | What it means |
|---|---|
| Sale price | Today's market value |
| − Agent commission | Total agent fees |
| − Closing costs | Title, settlement, etc. |
| − Transfer tax | State/local transfer fee |
| − Concessions | Credits to buyer |
| − Pre-sale prep | Repairs, staging, etc. |
| − Total selling costs | Sum of the above |
| − Mortgage payoff | Remaining loan balance |
| Taxable gain | Proceeds minus basis (after deducting selling expenses) |
| − Capital-gains tax | Tax on gain, after §121 exclusion if applicable |
| + Relocation credit | Costs covered by employer (full-service) |
| + Relocation MEA | After-tax MEA |
| + Relocation lump sum | Cash lump sum if chosen |
| − Relocation clawback | Amount repaid if leaving inside clawback window |
| **NET IN YOUR HAND** | **What you walk away with to invest** |

---

### Rent Year-1 Cash Flow Card ("Year-1 landlord P&L")

Shows what happens in the first year as a landlord:

| Line | What it means |
|---|---|
| Gross rent | Rent × 12 months |
| − Vacancy | Lost rent between tenants |
| Effective rent | Rent actually collected |
| − HOA, fees, taxes, insurance, repairs, CapEx, management, leasing, mortgage | All landlord costs |
| **Pre-tax cash flow** | Cash in your pocket before income tax |
| Tax on rental income | Tax on taxable income (not cash flow — see below) |
| **After-tax cash flow** | Actual annual cash benefit of renting |
| Cash-on-cash yield | After-tax cash ÷ home value |

**Important:** Pre-tax cash flow and taxable income are two different things. You are taxed on taxable income, which deducts mortgage interest and depreciation — not on your cash flow. In most years with a mortgage and normal depreciation, your taxable income is actually a loss, meaning you pay **$0 in rental income tax** even while receiving positive cash flow. The depreciation deduction is the reason real estate has favorable tax treatment.

---

### Tax & Payback Card

| Metric | What it means |
|---|---|
| Annual depreciation | Building basis ÷ 27.5 years. This is a non-cash deduction that shelters rental income. |
| Year-1 rental tax | What you actually owe in income tax on the rental in year 1 (often $0 due to depreciation). |
| Accumulated depreciation (at horizon) | Total depreciation deducted over the holding period — this amount will be **recaptured** at sale. |
| Suspended losses (at horizon) | Losses banked because your income was too high to deduct them — released at sale. |
| Recapture exposure (at horizon) | The cumulative depreciation subject to recapture tax when you eventually sell. |
| §121 status | Whether the exclusion still applies at the selected horizon year. |
| Cash payback | Years until accumulated after-tax rental cash flow recovers the initial equity cost of renting vs selling. |

---

### Wealth Comparison Card ("Which path wins at year N")

Shows total wealth at your chosen horizon for each path, with a proportional bar chart. Also breaks down how the rent path's total wealth is composed:

- **Net proceeds (rent path sale):** What you'd receive from selling the home at the horizon year.
- **Reinvested cash flows:** Accumulated after-tax rental cash flow, compounded at your investment return.
- **Relocation benefit (invested):** The rent-path relocation lump sum (or MEA) compounded over the horizon.
- **Break-even appreciation:** The appreciation rate at which rent and sell wealth are equal.

---

### Year-by-Year Chart and Table

The chart plots both wealth paths from year 1 to your horizon. A gold dot marks the **crossover year** — the year (if any) when the rent path overtakes the sell path. If no crossover appears, one path dominates for the entire period.

The table below the chart shows the same data in rows: home value, mortgage balance, equity, after-tax cash flow, invested cash flows, net sale proceeds (rent path), and both paths' total wealth at each year.

---

## Key Tax Concepts

### The §121 Primary-Residence Exclusion

The IRS allows you to exclude up to $250,000 (single) or $500,000 (married) of home-sale gain from capital-gains tax, provided you lived in the home as your primary residence for at least 2 of the last 5 years before the sale.

**Why this matters for renting:** Once you move out, the clock runs. If you rent the home and sell it more than ~3 years after moving out, you may lose the exclusion — and the entire appreciation (not just the amount above $250K/$500K) becomes taxable at roughly 15–25% depending on your bracket, plus state. This is one of the most compelling reasons to sell promptly rather than renting indefinitely, especially if your gain is large.

---

### Depreciation

When you own a rental property, the IRS lets you deduct a portion of the building's value each year as if the building is wearing out. The formula is: **(purchase price + improvements − land value) ÷ 27.5 years.** For a $380,000 basis home with 25% land, that's $285,000 ÷ 27.5 = roughly **$10,400/year** in non-cash deduction.

This deduction often makes the difference between taxable rental income and a paper loss, even when cash flow is positive.

---

### Depreciation Recapture

The IRS gives you the depreciation deduction during the rental years, but takes it back at sale. When you sell the rental property, all accumulated depreciation is "recaptured" and taxed at up to **25% federal** (the §1250 cap), plus NIIT (3.8%) and state tax. On a 10-year rental, this can be $100K+ of accumulated depreciation, resulting in a recapture tax bill of $35,000+. The tool tracks this accumulating exposure in the tax card and includes it in the rent-path's eventual sale calculation.

---

### Suspended Passive Losses

The IRS passive-activity loss rules say that rental losses cannot offset ordinary income (W-2, salary) for high earners — specifically, above $150,000 MAGI, the $25,000 special allowance phases out completely. Instead, the losses are "suspended" (banked) until you sell the property, at which point they're released and used to offset the gain.

This means high earners see no annual tax benefit from rental losses — but they do get a lump-sum benefit at sale. Check the "suspend losses" box if this applies to you.

---

### NIIT — Net Investment Income Tax

A 3.8% surtax on net investment income for high earners: single filers with MAGI over $200,000, married above $250,000. It applies to:
- Capital gains on the home sale
- Depreciation recapture at sale
- Positive net rental income in years when the rental is profitable

It does not reduce or increase a rental loss. The threshold is not adjusted for inflation, so it reaches more people each year.

---

## FAQ

**Why does selling always win in my scenario, no matter what horizon I try?**

Three things usually drive this result together:

1. **No mortgage, or a small mortgage.** When you sell a paid-off (or nearly paid-off) home, you free up the full equity to invest. If the home is worth $400K and you owe $30K, selling releases ~$365K to invest at 7%. That compounding is very powerful. Renting only makes financial sense early on when the equity released by selling is small — meaning the mortgage is large.

2. **Investment return exceeds appreciation by a wide margin.** If you assume 7% investment return and 4% home appreciation, the sell path has a 3-point structural advantage. Your rental cash flow must bridge that gap — and often can't. Look at the break-even appreciation rate: if it says "rent needs 6.8%/yr appreciation to win" and you only expect 4%, that's the root cause.

3. **Rent yield is below threshold.** A quick check: divide your annual rent by your home value. A $2,800/month rent on a $410,000 home is 8.2% gross yield. Subtract vacancy, management, insurance, property tax, HOA, and repairs, and the net operating income yield is typically 3–4%. Competing against 7% equities with a 3–4% net yield requires very strong appreciation. Many metro-area homeowners are in this situation.

*Try entering a realistic mortgage balance. This is often the single input that most changes the verdict.*

---

**What return should I assume for investing the proceeds?**

The S&P 500 has averaged approximately **10% per year nominal** (before inflation) and **7% per year real** (after inflation) since 1926. These two figures are not contradictory — they describe the same historical return measured differently. The ~3% gap between them is long-run average inflation.

Use **7%** if you want a conservative, real-terms-ish planning figure. Use **10%** if you believe in the long-run historical nominal return. Make sure it's consistent with your appreciation assumption — both should be nominal, or both adjusted for inflation.

Future returns may be higher or lower. Plugging in 5% shows you the rent-vs-sell verdict under a more pessimistic market outlook.

---

**What is the "break-even appreciation" shown in the verdict?**

The appreciation rate at which both paths produce identical total wealth at your chosen horizon. Below it, selling wins. Above it, renting wins. It's solved numerically by the tool.

Use this number as a test against your local market: "Does my neighborhood realistically sustain X% annual price growth?" If the break-even is 7% and your market typically grows at 4%, selling is the more defensible choice on the numbers.

---

**Investors always say long-term renting wins. Why doesn't my model agree?**

Investors saying "long-term renting always wins" are usually assuming one or more of the following:

1. **Significant leverage (mortgage).** The classic example: you put 20% down on a $500K home. A 5% appreciation = $25K gain on your $100K invested = 25% cash-on-cash return. That's the power of leverage. The comparison is not full equity vs full equity — it's small invested equity in a leveraged property vs the same small sum in stocks. If you're comparing unleveraged equity in both paths, the math is different.

2. **Higher appreciation.** 5–7%/year in high-growth metros has historically beaten stock returns. At 4%/year nationally, it hasn't.

3. **Comparison against cash, not stocks.** If the alternative to keeping the property is a savings account at 3–4%, renting wins much more easily. At 7%+ in equities, the hurdle is higher.

4. **Favorable rent-to-value ratio.** Markets where rent is closer to 1% per month of value support much better rental economics than markets where home prices have run ahead of rents.

Enter your actual mortgage balance and real rent/cost figures, and let the model tell you what's true for your specific property.

---

**Why do I see "sheltered" next to the rental income tax?**

Because your taxable rental income is a loss — even though you received positive cash flow. The depreciation deduction and mortgage interest deduction together often push taxable income below zero. When the tool shows "$0 (sheltered)," it means your paper loss is fully absorbing the tax.

If you are a high earner, that loss is then "suspended" (it can't offset your salary), so it accumulates for release at sale. The tool tracks this separately in the tax card.

---

**What is the difference between "pre-tax cash flow" and "after-tax cash flow" on the rent card?**

- **Pre-tax cash flow:** Rent collected minus all out-of-pocket costs (operating expenses + full mortgage payment including principal). This is money in your pocket before income tax.
- **After-tax cash flow:** Pre-tax cash flow minus the income tax on rental income. Since taxable income (which includes depreciation and deducts only interest, not principal) often shows a loss, the tax is typically $0, so after-tax cash flow equals pre-tax cash flow in many years.

---

**What is the §121 exclusion and how does it affect my decision timing?**

The §121 exclusion lets you exclude up to $250,000 (single) / $500,000 (married) of home-sale gain from capital-gains tax if the home was your primary residence for at least 2 of the last 5 years. Once you move out, you have roughly 3 more years to sell and still qualify.

After that window closes, renting and eventually selling means the full gain is taxed at ~15–25% depending on your bracket, NIIT, and state. This is a significant factor that pushes the math toward selling sooner — especially if you're a single filer ($250K exclusion, not $500K).

---

**The clawback warning appeared — does that mean I shouldn't take the relocation package?**

No — it means you should think carefully about job stability before committing to a package with a long clawback window. The clawback is only repaid if you leave the employer inside the window. If you're confident you'll stay, the clawback is irrelevant. If there's real uncertainty (you're weighing other opportunities), it's a contingent liability: the benefit is real, but so is the repayment risk.

To model the worst case: set "Months at new role" to the number of months you might realistically stay. The tool subtracts the prorated repayment and shows you the net. To model the best case: set months high (36+), and no clawback is subtracted.

---

**Should I use the land percentage from my property assessment?**

Yes — the IRS explicitly accepts the assessor's land-to-total ratio as a basis for allocating your cost basis between land and building. Find the assessment breakdown (Land / Building / Total) and compute: land % = assessed land ÷ assessed total. Do not plug in the dollar amounts from the assessment — only the ratio matters, applied to your actual purchase price and improvements.

---

**What does the "cash payback" figure in the tax card mean?**

The number of years it takes for your accumulated after-tax rental cash flows to recover the opportunity cost of renting instead of selling. It answers: "If I had sold today, I'd have had that money invested from day one. How long does it take for renting's cash flows to make up the difference?" A very long payback (10+ years) means the rental generates slow cash and you'd be better off with the proceeds invested early.

---

## A Note on Defaults

The tool ships with defaults calibrated for a typical NJ-area homeowner relocating to a new employer:
- Single filer, 35% federal ordinary rate, NJ 6.37% state rate, NIIT on, losses suspended.
- Typical NJ landlord costs (HOA, property tax, registration, management at 9%).
- 4% appreciation, 7% investment return.

These are starting points. Your actual numbers may differ significantly, and the verdict can swing on a single input (especially mortgage balance and investment return). Fill in your real figures before drawing conclusions.

---

*Tool built for a relocation decision. Not a substitute for professional financial, tax, or legal advice.*

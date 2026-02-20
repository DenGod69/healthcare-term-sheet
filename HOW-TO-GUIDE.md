# Healthcare Travel Staffing Term Sheet — How-To Guide

**Live URL:** https://dengod69.github.io/healthcare-term-sheet/

---

## Quick Start

Open the term sheet in any browser (desktop or mobile). All calculations happen in real time — just start entering data and watch the sidebars update instantly. Your session auto-saves to your browser, so you can close the tab and pick up where you left off.

---

## Step-by-Step Walkthrough

### Step 1: Session Management

When you first open the page (or return to it), you may see a banner at the top:

- **Restore Session** — Reloads your previously saved data (shows how long ago it was saved)
- **Start Fresh** — Clears everything and starts with a blank form

> Your data auto-saves to your browser's local storage every time you make a change. The "Auto-save active" indicator appears in the top-right corner.

---

### Step 2: Assignment & Candidate Details

Fill in the top section with basic deal information:

| Field | What to Enter |
|-------|--------------|
| **Assignment ID** | Your internal tracking ID |
| **Status** | Select: Prospecting, Negotiating, Pending Approval, Active, or Completed |
| **Date Created** | Auto-fills with today's date |
| **Position Title** | e.g., "RN - ICU", "LPN - Med/Surg" |
| **Facility Name** | Name of the healthcare facility |
| **City, State** | e.g., "Austin, TX" |
| **Facility Zip** | 5-digit zip code — auto-detects the state for OT rules |
| **Candidate Name** | Traveler's full name |
| **Email / Phone** | Contact information |
| **License Number / Expiry** | Professional license details |

---

### Step 3: Assignment Duration & Hours

This is where the financial engine starts. These fields drive every calculation on the page.

1. **Start Date** — When the assignment begins
2. **Contract Weeks** — Length of the contract (e.g., 13 weeks). The End Date calculates automatically.
3. **Hours Per Week** — Scheduled hours (e.g., 36). This is the most critical input — it unlocks all per-hour, per-week, and per-contract calculations.

#### OT Rules (State)

- The **OT Rules dropdown** lets you select the state's overtime rules (Federal, California, Alaska, Nevada, Colorado, Oregon, or Florida)
- If you enter a **Facility Zip** or look up a **GSA Zip Code** (in the Travel tab), the state auto-detects
- An **OT Rule Banner** appears showing the specific rules (e.g., "OT (1.5x) after 40 hrs/week")
- **Shift Hours/Day (OT)** — This field only appears when the selected state has daily OT rules (e.g., California: OT after 8 hrs/day). Enter the scheduled hours per shift so the system can calculate daily vs. weekly overtime correctly.

---

### Step 4: Rate Details — Choose Your Rate Type

Click one of the three tabs to match the assignment type:

| Tab | When to Use |
|-----|------------|
| **Local** | Local/staff assignments — no stipends or per diem |
| **Per Diem** | Per diem assignments — includes GSA stipend panel |
| **Travel** | Travel assignments — includes GSA stipend panel with zip code lookup |

#### Candidate Pay Rates (Left Table)

Enter the **pay rate per hour** for each applicable pay type:

- **Regular** — Base hourly pay rate (e.g., $20/hr)
- **OT (1.5x)** — Overtime rate. The hours auto-calculate based on the OT state rules.
- **DT (2x)** — Double time rate (only visible for states like California that have DT rules)
- **Differential / On-Call / Callback / Charge / Holiday** — Enter rates if applicable

The system auto-calculates:
- **$/Wk** = rate × hours for that type
- **Total Amount** = $/Wk × contract weeks
- **Bill %** = what percentage of total bill this pay type represents

#### GSA Stipend Rates (Right Table — Per Diem & Travel only)

**Using GSA Rate Lookup (Travel tab):**

1. Enter the **facility zip code** in the GSA Rate Lookup box
2. Click **Lookup**
3. The system fetches the GSA per diem rates and displays:
   - **Max Lodging $/Day** (e.g., $107.00/day)
   - **Max M&I $/Day** (e.g., $68.00/day)
4. You can then enter the **$/Hr** or **$/Wk** stipend amounts for Lodging and M&I
   - The "max" row below each stipend shows the GSA maximum — don't exceed it
   - Editing $/Hr auto-calculates $/Wk and vice versa
5. The **GSA Total** row shows combined stipend per day, hour, week, and contract total

> **Important:** GSA stipends are non-taxable. The system separates them from taxable wages when calculating burdens (WC + ER).

---

### Step 5: Bill Rate Details

Enter what you're billing the client for each rate type:

1. **Bill Rate (Regular)** — e.g., $75/hr
2. **OT Bill Rate** — e.g., $112.50/hr
3. **DT Bill Rate** — (if applicable)
4. **Differential / On-Call / Callback / Charge / Holiday bill rates** — as needed

#### VMS Fee

If the assignment goes through a Vendor Management System:

1. Enter the **VMS Fee %** (e.g., 4%)
2. **Net Bill Rate** rows automatically appear below each bill rate, showing the rate after the VMS cut
3. All margin calculations use the net (post-VMS) bill rate

#### Custom Pay Types

Click **"+ Add Custom Type"** to add non-standard pay categories (e.g., certification pay, preceptor pay). Enter a name, hourly rate, and hours.

---

### Step 6: Cost & Expenses

Enter one-time flat-dollar expenses for the assignment:

| Expense | Example |
|---------|---------|
| **Drug Screening** | $85 |
| **Background Check** | $120 |
| **Occupational Screening** | $350 |

The system calculates:
- **$/Hr Burden** = Flat cost ÷ total contract hours (e.g., $570 ÷ 468 hrs = $1.22/hr)
- This burden is factored into Net Markup, Net Margin, and Net Profit

#### Adding Custom Expense Categories

1. Click **"+ Add Category"**
2. Enter the category name (e.g., "Housing", "Skills Testing")
3. Enter the flat dollar amount
4. Click the **green checkmark (✓)** to confirm the category

> **Tip:** Enter contract weeks AND hours per week before entering expenses — this gives you the most accurate per-hour amortization. Without weeks, the system estimates using a single week.

---

### Step 7: Burdens, Taxes & Fees

Enter the employer burden percentages:

| Field | What It Is | Example |
|-------|-----------|---------|
| **WC - Workers Comp (%)** | Workers' compensation insurance rate | 5.5% |
| **ER Cost - Employer Cost (%)** | Employer payroll taxes (FICA, FUTA, SUTA, etc.) | 18.5% |

The burden is applied only to **taxable wages** (excludes GSA stipends). The $/hr burden displays below each input field.

---

### Step 8: Notes

Use the **Special Requirements** text box for any deal-specific notes, special conditions, or internal comments.

---

### Step 9: Save / Print / Clear

| Button | Action |
|--------|--------|
| **Save Term Sheet** | Manually saves to browser storage |
| **Print/PDF** | Opens the browser print dialog — sidebars are hidden for a clean printout |
| **Clear Form** | Resets all fields to blank |

> Remember: auto-save is always running, so you rarely need to click Save manually.

---

## Reading the Sidebars

### Left Sidebar: Candidate Compensation

Shows a complete breakdown of what the traveler earns:

- **Pay Totals** — Hourly rate (blended), daily pay, weekly pay, monthly pay
- **Hourly Breakdown** — Each pay type's $/hr contribution
- **Weekly Breakdown** — Each pay type's $/wk contribution (including GSA stipend)

### Right Sidebar: Margin & Markup

The financial health of the deal at a glance:

**Hero Section (top):**
- **Weekly Bill Amount** — Net bill per week (after VMS)
- **Weekly Gross** — Total gross pay per week
- **Weekly Margin** — Net margin per week (bill - all costs)

**Metrics Grid:**

| Metric | What It Means |
|--------|--------------|
| **Net Markup** | Net Bill ÷ Total Cost as a multiplier (e.g., 1.20x means 20% markup) |
| **Burden % of GM** | What percentage of gross margin goes to burdens (expenses + WC/ER) |
| **Gross Margin $$** | Bill - Pay (before burdens and expenses) |
| **GM %** | Gross margin as a percentage of total bill |
| **Net Margin $$** | Net Bill - Total Cost (after VMS, burdens, and expenses) |
| **Net Margin %** | Net margin as a percentage of net bill |

**Detail Sections:**
- **Gross Margin Details** — Total Bill vs. Gross Wages
- **Burden Details** — Expense $/Hr, WC+ER $/Hr, Total Burden $/Hr and $/Wk
- **Net Margin Details** — Net Margin/Hr, Net Bill, Total Cost

### Profit Breakdowns (scrolls below Margin & Markup on desktop; 3rd column on mobile)

**GM Profit Breakdown** — Gross margin per Hour, Day, Week, and Month with bill/pay sub-details

**Net Profit Breakdown** — Net profit (after all burdens + expenses) per Hour, Day, Week, and Month

**Weeks to Cover Expenses** — Shows how many weeks of net profit it takes to recover flat expenses:
- **Green** (≤2 weeks) — Expenses recovered quickly
- **Orange** (2-4 weeks) — Moderate recovery time
- **Red** (>4 weeks) — Slow recovery, consider the impact
- Includes a **progress bar** showing what % of the contract is spent just covering expenses

**OT/DT Margin Breakdown** — Profit analysis by rate type:
- Regular margin/hr and weekly profit
- OT margin/hr and weekly profit
- DT margin/hr and weekly profit (if applicable)
- Burden per rate type
- Total weekly profit and OT/DT % of total profit

---

## Example Deal Walkthrough

Here's a quick example to see the tool in action:

1. **Contract:** 13 weeks, 36 hrs/week, Federal OT rules
2. **Pay Rate:** $20/hr regular
3. **Bill Rate:** $75/hr regular
4. **VMS Fee:** 4%
5. **GSA (Travel tab):** Zip 14601 → Lodging $749/wk, M&I $476/wk
6. **Expenses:** Drug Screen $85, Background Check $135, Occupational $350 (total: $570)
7. **Burdens:** WC 5.5%, ER Cost 18.5%

**What you should see:**
- Expense burden: $570 ÷ 468 hrs = **$1.22/hr**
- Total burden: ~$6.02/hr (expense + WC/ER)
- Net Markup: ~1.20x
- GM%: ~28%
- Net Margin%: ~17%
- Weeks to Cover Expenses: the tool calculates how many weeks of net profit cover the $570

---

## Mobile View

On phones and tablets, the layout automatically adapts:
- The **main form** displays full-width at the top
- Below it, **three columns** appear side-by-side:
  1. **Candidate Compensation** (left)
  2. **Margin & Markup** (center)
  3. **Profit Breakdowns** (right)

All columns are scrollable and fill the full screen width.

---

## Tips & Best Practices

1. **Enter hours and weeks first** — Most calculations depend on these. Enter them before pay/bill rates for the most accurate results.
2. **Use the GSA Lookup** — Don't guess at stipend rates. The zip code lookup pulls official GSA per diem rates.
3. **Watch the Weeks to Cover metric** — If it's red (>4 weeks), your expenses are eating too much margin. Consider negotiating a higher bill rate.
4. **Check Net Markup** — A healthy markup is typically 1.15x–1.35x. Below 1.0x means you're losing money.
5. **VMS deals need higher bill rates** — The VMS fee reduces your effective bill rate. Factor this in when pricing.
6. **Compare GM% vs NM%** — The gap between these shows how much burden and expenses cost you. A large gap means high overhead.
7. **Use the OT/DT Breakdown** — For states like California with daily OT rules, this shows exactly how overtime hours impact your profit.
8. **Auto-save has your back** — Your data persists in the browser. But for a permanent record, use Print/PDF.

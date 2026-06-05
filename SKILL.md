---
name: serenity
description: "Serenity investment research method, also called 紫苏叶 theory or Chokepoint Theory. Use when the user asks to analyze an industry chain, find overlooked upstream bottleneck suppliers, identify hidden champions, validate a stock thesis, compare chokepoint players, or run supply-chain card-point analysis for AI semiconductors, optical communications, robotics, new energy, rare earth materials, precision manufacturing, or other long industrial chains. Trigger phrases include 紫苏叶, serenity打法, 瓶颈分析, 供应链卡点, 拆产业链, 隐形冠军, 上游垄断, 不可替代性, chokepoint, reverse engineering, 卡脖子, and physical bottleneck."
version: "3.2.0"
agent_created: true
---

# Serenity: Chokepoint research method

Serenity is a research workflow for finding the overlooked physical bottleneck in a long industrial chain. The target is usually not the visible first-layer winner, but a smaller upstream supplier that is hard to replace, capacity constrained, and mispriced relative to the value of the link it controls.

Use this skill for research, not for direct investment advice. Any price target, stop loss, catalyst scenario, or ranking is a hypothesis and must include assumptions, evidence quality, and risk conditions.

## When to use

Use this skill when the user asks for:

- "紫苏叶" or Serenity-style analysis.
- Chokepoint, bottleneck, card-point, or hidden champion analysis.
- Reverse engineering a supply chain from a final product or theme.
- Validating whether a stock is truly irreplaceable upstream.
- Comparing global suppliers in a technical manufacturing chain.
- Finding under-covered A-share, Hong Kong, US, or global suppliers in AI, semiconductors, CPO, robotics, batteries, rare earths, industrial software tied to hardware, precision equipment, sensors, or materials.

Do not use this skill as the main framework for consumer brands, pure financial services, content platforms, generic internet platforms, or themes without a long physical supply chain.

## Data rules

1. Browse or use current financial-data skills for market, financial, customer, and industry facts. For installed local skills, prefer `neodata-financial-search` for broad market and financial queries, and `westock-data` for stock, ETF, K-line, financial statement, sector, news, announcement, research report, and fund-flow detail.
2. Do not answer time-sensitive financial facts from memory. Verify current market data, filings, prices, estimates, and news.
3. Cite the source for every material data point. If a fact cannot be verified, mark it as `待补充` or `low confidence`.
4. Do not mix data sources silently. If different sources disagree, show the conflict and prefer filings, exchange disclosures, company reports, regulator data, or primary technical sources over summaries.
5. Separate fact, inference, and speculation. Label each major conclusion with confidence: high, medium, or low.

Useful source types:

| Need | Preferred sources |
| --- | --- |
| Financials | annual/interim reports, prospectuses, exchange filings, audited statements |
| Customers | annual reports, prospectuses, supplier lists, procurement disclosures, verified conference material |
| Capacity | company IR, environmental impact reports, permitting documents, plant announcements, customs data |
| Technology | patents, standards documents, academic papers, product datasheets, certification records |
| Market position | filings, industry reports, customer qualification lists, import/export data |
| Current price and events | exchange data, company announcements, trusted financial data tools |

## Core question

Ask throughout the analysis:

> In this system, what is the quiet physical switch that everyone needs and few can replace?

Avoid over-focusing on the first-layer giant. The method is designed to find the upstream dependency that is less visible but structurally powerful.

## Workflow

Run the phases in order. For a quick answer, compress the evidence, but do not skip the source, risk, and confidence checks.

### Phase 1: Map the chain

Build a 5-7 layer chain from the end demand backward:

```text
Layer 1: end product/service -> representative leaders
Layer 2: core system/module -> direct suppliers
Layer 3: critical subcomponent/material -> candidate bottlenecks
Layer 4: special material/equipment/process -> narrower candidates
Layer 5: base input, unique equipment, process know-how, or certified supplier
Layer 6-7: only if the real dependency sits deeper
```

At each layer ask: What must this layer have, and what is difficult to replace?

### Phase 2: Count real players

Count global commercially relevant suppliers, not just companies that claim they can make the product.

| Supplier count | Interpretation | Action |
| --- | --- | --- |
| 4+ credible suppliers | likely competitive | usually pass unless qualification barriers are extreme |
| 3 suppliers | possible oligopoly | continue only if qualification, capacity, or patent barriers are strong |
| 2 suppliers | strong chokepoint candidate | verify deeply |
| 1 supplier or de facto monopoly | absolute chokepoint candidate | make it the focus |

Clarify what qualifies as a "real player": production scale, customer qualification, product performance, yield, certification, delivery reliability, and ability to serve the target market.

### Phase 3: Verify five dimensions

For each candidate, produce a yes/no/unclear conclusion:

1. Irreplaceability: Can downstream customers switch? How long is qualification? Are there safety, automotive, aerospace, military, or reliability certifications?
2. Capacity ceiling: Current capacity, utilization, expansion cycle, capex bottlenecks, upstream raw-material limits.
3. Customer structure: Top five customer concentration, contract duration, single-customer risk, customer quality.
4. Technical moat: Key patents, process know-how, yield, certification, data, standards, and route-change risk.
5. Valuation mismatch: market cap and enterprise value versus the value and scarcity of the controlled link.

Use financial indicators as verification, not as the whole thesis. Do not say "do not look at PE/ROE"; instead, do not stop at PE/ROE.

### Phase 4: Run devil's advocate

Attack the thesis before presenting it:

```text
Assume you are a harsh short seller. Attack every link in this chokepoint thesis. Look for substitute technologies, customer bargaining power, a second supplier entering, capacity overbuild, demand disappointment, patent weakness, source errors, valuation traps, liquidity risk, and timing risk.
```

Include the 3-5 strongest attacks and whether they weaken, break, or merely qualify the thesis.

### Phase 5: Compare global competitors

Cover at least three international competitors when available.

| Dimension | Target | Competitor 1 | Competitor 2 | Competitor 3 |
| --- | --- | --- | --- | --- |
| Country / production base | | | | |
| Core product metric | | | | |
| Technology generation | | | | |
| Major customers | | | | |
| Capacity / expansion | | | | |
| Gross margin / revenue scale | | | | |
| Patents / certifications | | | | |

Answer:

- How many years behind or ahead is the target versus the global leader?
- Is the moat absolute, regulatory, qualification-based, capacity-based, or merely temporary?
- How likely is foreign or domestic competition to erode the moat?

### Phase 6: Position the capital-cycle stage

Classify the theme or target:

| Stage | Meaning |
| --- | --- |
| Stage 1: ignored | few reports, little institutional ownership, facts not yet connected |
| Stage 2: early discovery | specialized investors notice, liquidity improves, still under-modeled |
| Stage 3: confirmation | sell-side and institutions validate, valuation begins to price growth |
| Stage 4: crowded | common narrative, high expectations, asymmetric upside fades |

State the evidence for the stage, such as report count, holdings, liquidity, earnings revisions, conference mentions, or announcement frequency.

### Phase 7: Use alternative data

Look beyond standard financial summaries:

| Data | What it verifies |
| --- | --- |
| Patent citation network | technical moat and route choice |
| Supplier/customer lists | position in the chain |
| customs data | shipment trend and market access |
| hiring and capex | expansion pressure |
| environmental filings | plant capacity and timeline |
| standards and certification | qualification barriers |
| conference decks and datasheets | ecosystem role and product metrics |
| GitHub / developer signals | demand signal only when the product has a software or developer ecosystem |

### Phase 8: Classify the mispricing

Choose one primary type:

| Type | Meaning |
| --- | --- |
| Traditional chokepoint | scarce physical supplier controls a necessary link |
| Relative-value mismatch | market classifies the company incorrectly |
| Code or data confusion | ticker/data ambiguity creates wrong screening or valuation |
| Mechanical dislocation | non-fundamental selling creates a temporary discount |
| Timing option | technology is not confirmed yet, but the supplier has asymmetric optionality |

### Phase 9: Mark physical and geopolitical coordinates

For each target, list:

- production location and key plant dependency
- upstream raw material or equipment dependency
- export controls, sanctions, tariff, or geopolitical risk
- customer geography and market-access limits
- next financial, product, regulatory, or capacity milestone

### Phase 10: Run A-share / Hong Kong six tests when applicable

Define the metrics explicitly:

| Test | Metric | A-share guide | Hong Kong guide |
| --- | --- | --- | --- |
| T1 earnings quality | recurring net profit / reported net profit | >80% | >90% |
| T2 cash conversion | operating cash flow / net profit | >0.8x | >1.0x |
| T3 real growth | latest revenue growth or 2-year CAGR | >25% | >20% |
| T4 valuation digestibility | PEG or EV/EBITDA versus growth | <1.0 PEG guide | <0.8 PEG guide |
| T5 competitive position | domestic and global rank | domestic top 3 or global top 5 | global top 3 preferred |
| T6 absolute scale | recurring net profit or segment operating profit | >RMB 100m | >RMB 200m |

If T6 uses revenue, backlog, or market cap instead of recurring profit, say so explicitly and explain why.

### Phase 11: Produce scenario frameworks

If the user asks for investment framing, provide three research scenarios. Avoid presenting them as instructions to buy or sell.

```text
Momentum scenario: target range X, key assumption Y, invalidation Z
Value scenario: fair value X, required margin of safety Y%, why the market may not offer it
Catalyst scenario: if event X occurs, expected reaction Y, risk/reward Z:1
```

Every target price must include: valuation method, key assumptions, data date, and confidence level.

### Phase 12: Risk matrix and exit conditions

Always include a risk matrix:

| Risk | Monitoring indicator | Warning threshold | Exit / thesis-break condition |
| --- | --- | --- | --- |
| technology route changes | standards, customer design wins, patents | | |
| second supplier enters | customer qualification, capacity announcement | | |
| demand misses | orders, backlog, utilization, customer capex | | |
| capacity overbuild | industry capex, new permits | | |
| liquidity / crowding | turnover, ownership, financing pressure | | |
| valuation overshoot | implied expectations vs feasible growth | | |

## Output formats

### Quick analysis

Use for a single stock or a narrow theme:

```markdown
## [Target/theme] Serenity quick view

### Verdict
- Chokepoint status:
- Confidence:
- Main reason:
- Main thesis-break risk:

### Chain map
[5-7 layers]

### Bottleneck evidence
| Dimension | Evidence | Source | Confidence |
| --- | --- | --- | --- |

### Competitor count
[real supplier count and why]

### Devil's advocate
[3-5 attacks and response]

### Scenario framework
[momentum / value / catalyst, if requested]

### Risk matrix
[monitoring indicators and exit conditions]
```

### Full report

Use for an industry or multi-target request:

```markdown
## [Industry/theme] Serenity full report

### Executive view
### 5-7 layer chain map
### Candidate chokepoint list
### Global competitor comparison
### Phase 3 five-dimension verification
### Capital-cycle stage
### Alternative-data evidence
### A-share / Hong Kong six tests, if applicable
### Ranking and confidence
### Devil's advocate
### Scenario framework, if requested
### Risk matrix and thesis-break conditions
### Source notes and unresolved items
```

## Self-check before final answer

- Did I identify the physical dependency, not just the visible leader?
- Did I map at least five layers unless the chain is genuinely shorter?
- Did I count real global suppliers and define "real supplier"?
- Did I cite sources for material claims?
- Did I separate fact, inference, and speculation?
- Did I include the strongest opposing arguments?
- Did I include risk and exit conditions?
- For A-share/Hong Kong targets, did I define and run T1-T6 or explain why data is unavailable?
- Did I avoid presenting research scenarios as personalized investment advice?

## Boundaries

- This skill does not replace valuation modeling, accounting due diligence, or portfolio risk management.
- This skill is not suitable for direct trading signals without independent verification.
- If the task requires current market data, browse or use financial data tools before concluding.
- If data quality is weak, say so plainly and reduce confidence instead of forcing a conclusion.

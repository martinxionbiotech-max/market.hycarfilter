# Supply Chain Structure: OEM and Aftermarket (AM)

!!! note "Source attribution"
    This article is an editor's original compilation. **[Industry Knowledge]** = common industry practices; **[Data Citation]** = citing values identical to [data.hycarfilter](https://data.hycarfilter.com); **[Analytical Judgment]** = the researcher's original judgment (Xiaozhu ✍️). The OEM/AM shares are **estimated reference / for reference only**.

## 1. The difference between OEM and AM (industry knowledge)

The automotive filter supply chain has two legs: **OEM (original equipment)** and **AM (Aftermarket)**. The customers, product logic, and profit structures of the two legs are completely different:

| Dimension | OEM (original equipment) | AM (aftermarket) |
|---|---|---|
| Customer | Automakers / Tier 1 suppliers | Distributors / auto-parts chains / repair shops / end vehicle owners / e-commerce |
| Entry method | Automaker supplier approval (long cycle, high threshold) | Channel cooperation / brand / white-label OEM/ODM |
| Product logic | Developed per vehicle model, bound to OE numbers | SKUs spread by parc, matched via OE cross-reference numbers |
| Profit structure | Stable but thin, relies on scale | Larger channel markup, but fierce price competition |
| Certification threshold | Automaker quality system (IATF 16949 etc.) | Market entry certifications (EAC/GCC/INMETRO etc.) + optional system certification |
| Volatility | Fluctuates with new-vehicle production | Fluctuates with parc and replacement cycles, relatively stable |

**[Industry Knowledge]** Regarding the volume share of OEM vs AM, the industry's common understanding is "**the aftermarket takes the majority**" (about 70%–80%, estimated reference). The reason is: a vehicle changes filter elements multiple times over its life, while a new vehicle only gets original parts fitted once — **replacement demand is naturally far larger than assembly demand**.

## 2. The OEM side: a "slow business" bound to automakers

**[Industry Knowledge]** OEM supply requires passing the automaker's supplier audit — quality system, capacity, traceability, and annual cost reduction. Its characteristics are:

- **Long cycle**: from sourcing decision to mass production often takes 1–3 years;
- **Sticky relationship**: once selected, switching costs are high and orders are stable;
- **Thin margins**: automakers exert annual cost-reduction pressure, so supply prices are continuously compressed;
- **High requirements**: traceability, 0 PPM, and VDA/APQP/PPAP system requirements.

**[Analytical Judgment]** For small and medium factories in the Qinghe industrial belt, **OEM automaker supply is usually not the optimal path** — high investment, slow payment collection, and weak bargaining power. A more realistic positioning is "**a quality Tier 2/Tier 3 or aftermarket contract manufacturer**": doing contract manufacturing for Tier 1 suppliers or brand owners, or directly doing AM export.

## 3. The AM side: the main battleground for export buyers

**[Industry Knowledge]** The typical AM supply chain link is:

```
Factory (Qinghe etc.) → exporter/brand owner → importer/distributor → auto-parts chain/repair shop/e-commerce → end vehicle owner
```

**[Data Citation]** hycarfilter's canonical dataset `target_markets` field covers regions such as **Middle East / Russia / South America / Europe / North America / Southeast Asia / Africa** — this is exactly the typical target-market distribution of AM export, identical in value to [data.hycarfilter](https://data.hycarfilter.com).

**[Analytical Judgment]** The ranking of core competitiveness for AM-side buyers is completely different from OEM:

1. **SKU breadth**: how many parc vehicle models can be covered (OE cross-reference numbers determine the fitment range);
2. **Quality consistency**: not "the best", but "stable across batches";
3. **Price and MOQ**: the entry ticket for price-sensitive markets;
4. **Lead time and logistics**: aftermarket restocking is frequent, and lead time is cash flow.

## 4. Which side buyers should stand on

**[Analytical Judgment]** Export buyers almost all stand on the **AM side** — even if you supply brand owners, what you do is "AM contract manufacturing". This brings three direct conclusions:

1. **Don't scare yourself with OEM certification thresholds**: what AM purchasing really needs is target-market entry certifications (EAC/GCC/INMETRO etc.) + optional quality systems (ISO 9001/IATF 16949 framework), not an automaker sourcing audit;
2. **OE cross-reference numbers are the key to fitment**: AM purchasing matches vehicle models backward via OE numbers, and the [data site's OE cross-reference](https://data.hycarfilter.com/crossref/oe-cross-reference/) does exactly this (reference nature);
3. **Channels matter more than brands**: on the AM side, whoever controls the distribution channels and stays close to the end replacement scenario has the bargaining power — what suppliers need to do is help buyers "sell well", not just "be cheap".

---

*Next: [Regional Market Reports](../regional-reports/index.md)*

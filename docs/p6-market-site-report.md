# Hycarfilter Phase 6 — market.hycarfilter Industry Report Layer Delivery Report

> Production date: 2026-10-25 | Author: B2B industry researcher + export market analysis editor (Xiaozhu ✍️)
> Repository: `market.hycarfilter` (MkDocs · industry report/export intelligence) | Basis: `docs/hycarfilter-p1-inventory-architecture.md` §2.4 + data site deliverables `data.hycarfilter/data/products.json` + tech site deliverables

---

## 1. Delivery overview

The MkDocs Material industry report sub-site is online, positioned as "the searched and cited industry report layer" — **zero overlap with the main site's marketing, and no overlap with the data site's product values or the tech site's process standards** (market = industry layer, data = product values, tech = process standards). The entire site was originally authored in Chinese, focused on five sections: "industry overview / regional market reports / industry trends / purchasing guide / industry data reference".

## 2. Site scale (20 content pages + 404)

| Section | Pages | Content |
|---|---|---|
| Home | 1 | Positioning / four-layer interlinking / source attribution labeling standard / data-consistency statement |
| Industry Overview | 4 | Overview · Global Market Size and Landscape · China's Filter Industry Cluster (Qinghe) · Supply Chain Structure (OEM/AM) |
| Regional Market Reports | 6 | Regional overview · Europe · Middle East · Southeast Asia · Latin America · Africa (each with five parts: demand characteristics/import channels/competitive landscape/buyer decision factors/market entry recommendations) |
| Industry Trends | 5 | Trends overview · Aftermarket vs OEM · Electrification impact · E-commerce channels · Anti-dumping and trade compliance |
| Purchasing Guide | 3 | Overview · Full export procurement flow (six steps) · Common purchasing pitfalls (eight pitfalls) |
| Industry Data Reference | 1 | Market size ranges/HS codes/efficiency grades/export fields/certification framework summary |
| **Total** | **20** | (+ 404 = 21 HTML) |

**Regional report scale**: 5 in-depth reports, each with a uniform five-part structure (market demand characteristics · import channel structure · competitive landscape · buyer decision factors · market entry recommendations [original subjective opinion section]), averaging about 4–5 subsections each, containing data citations and editor opinion attribution.

**Purchasing guide article count**: 2 body articles — "Full Export Procurement Flow" in 6 steps (inquiry/sample order/factory audit/inspection/logistics/customs clearance) + "Common Purchasing Pitfalls" in 8 pitfalls; plus 1 overview page.

## 3. Source attribution layering execution

The whole site uses a uniform four-state labeling, with a note declaration at the top of each page + inline tags in the body:

- **[Industry Knowledge]** — common industry practices / public consensus;
- **[Framework Reference]** — certification/market entry/compliance frameworks (EAC/GCC/INMETRO/CE/REACH/RoHS), **not constituting certification or legal conclusions**;
- **[Data Citation]** — citing values identical to the data site's canonical dataset (HS codes/efficiency grades/certification fields/target markets);
- **[Analytical Judgment]** — the researcher's original subjective judgment, attributed to "Xiaozhu ✍️".

**Estimated data is explicitly marked**: market size/growth rate ranges are uniformly marked "**estimated reference / for reference only**", not authoritative statistics, only for order-of-magnitude reference. The anti-dumping/trade compliance article separately sets a "no legal advice provided" statement.

## 4. Data consistency check (0 conflicts)

Checked item by item against the data site's `products.json` (v0.1.0) for consistency:

- **HS codes**: air filter/cabin filter 8421310000 · oil filter/fuel filter 8421230000 · wiper blade 8512400000 · transmission filter screen 8708409990 · LED lights 8512209000;
- **Efficiency grades**: air filter 99.0%–99.6% · oil filter 90–95%@20um · fuel filter 95–97%@10um · cabin filter 95%–99.97%H13 · transmission filter screen 90%@40um;
- **Export fields**: MOQ 200/300/500/1000 · lead time 15/18/20/22/25 days · certification ISO 9001/IATF 16949/CE/RoHS · target markets Europe/Middle East/Russia/Southeast Asia/South America/North America/Africa;
- **Category division**: 7 categories (air filter/cabin filter/oil filter/fuel filter/wiper blade/transmission filter screen/LED lights) identical in value to the data site;
- **Brand/origin**: hycarfilter (Qinghe County Hongying Auto Parts Co., Ltd. / 清河县宏盈汽车零部件有限公司, since 2013, Qinghe County) consistent with the data site homepage.

**No claimed certification**: certification items uniformly use "standard framework/market entry framework" wording, with no claim of holding any certification; **no fabricated source names** — source attribution layering (industry knowledge/framework reference/data citation/analytical judgment) with no fictitious citations.

## 5. build / commit / push

- **build**: `mkdocs build` ✅ 20 content pages + 404, 0.66s, Material theme (language=zh, deep orange color scheme), 0 content WARNING / 0 ERROR.
- **commit**: see below (`p6-market-*` marker).
- **push**: origin/main.
- **sync**: 0 conflicts with data/tech site values (checked item by item, consistent).

## 6. Chinese compact report

**Site scale**: 20 content pages = Home 1 · Industry Overview 4 · Regional Market Reports 6 · Industry Trends 5 · Purchasing Guide 3 · Data Reference 1.

**Regional report scale**: 5 in-depth reports (Europe/Middle East/Southeast Asia/Latin America/Africa), each with a five-part structure (demand characteristics/import channels/competitive landscape/buyer decision factors/market entry recommendations [original opinion section]).

**Purchasing guide article count**: 2 body articles (full flow 6 steps + common pitfalls 8 items) + 1 overview.

**Source attribution layering execution**: four-state labeling (industry knowledge/framework reference/data citation/analytical judgment) uniform across the whole site, note declaration per page + inline tags; estimated data explicitly "for reference only"; no claimed certification, no fabricated source names.

**build**: mkdocs build 20 pages all green, 0 content warnings. **commit**: `p6-market-*`. **push**: origin/main. **sync**: 0/0.

**Report path**: `docs/p6-market-site-report.md` (this document).

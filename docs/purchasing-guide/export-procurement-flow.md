# Full Export Procurement Flow

!!! note "Source attribution"
    This article is an editor's original compilation. **[Industry Knowledge]** = common industry practices; **[Framework Reference]** = introductions to customs clearance/logistics frameworks, **not constituting legal or compliance conclusions**; **[Data Citation]** = citing values identical to [data.hycarfilter](https://data.hycarfilter.com); **[Analytical Judgment]** = the researcher's original judgment (Xiaozhu ✍️). Backlinks: [data export packing](https://data.hycarfilter.com/crossref/export-packing/) · [tech export inspection](https://tech.hycarfilter.com/qc/export-inspection/).

For filter export procurement, the standard flow has six steps: **inquiry → sample order → factory audit → inspection → logistics → customs clearance**. The "completion standard" of each step is as follows.

## 1. Inquiry (RFQ / Inquiry)

**[Industry Knowledge]** When a buyer sends an inquiry to a supplier, they need to provide key parameters, otherwise the quote is meaningless:

- **Selection information**: category, OE cross-reference numbers, fitment models, specs (dimensions/efficiency/material);
- **Quantity and MOQ**: minimum order quantity, quantity tiers;
- **Certification requirements**: target-market entry (EAC/GCC/INMETRO etc.) + optional systems (ISO 9001/IATF 16949);
- **Packaging and lead time**: inner box/outer carton, lead time, trade terms (FOB/CIF etc.).

**[Data Citation]** The spec parameters needed for inquiry are subject to the canonical dataset of [data.hycarfilter](https://data.hycarfilter.com) (model/dimensions/efficiency/material/OE cross-reference/packaging/MOQ/lead time/certification/HS Code).

**[Analytical Judgment]** **The quality of a quote directly reflects the supplier's professionalism** — a quote that clearly states "efficiency scope, OE cross-reference, packaging, MOQ, lead time, certification" is far more credible than a sentence like "price is negotiable". Buyers should **prioritize filtering suppliers with complete, standardized quotes**.

## 2. Sample Order

**[Industry Knowledge]** Before bulk ordering, place a sample order first to verify "**whether the physical item matches the description**":

- Confirm dimensions, material, efficiency, and OE cross-reference fitment on the sample;
- Confirm packaging, labels, and brand printing (OEM/ODM);
- Sample orders are usually small-batch, priced at sample or expedited rates.

**[Analytical Judgment]** **The sample order is the "most cost-effective" step in the procurement flow** — spend a little money to catch major "description vs physical item" mismatches early. **Skipping the sample order and going straight to a large order is one of the most expensive mistakes a novice buyer can make.**

## 3. Factory Audit

**[Industry Knowledge]** A factory audit verifies "**whether the supplier is a real factory and has stable capacity and quality control**":

- Look at the production line (folding machine, glue injection, curing, spin-on assembly);
- Look at filter paper/raw material inventory (to judge self-produced vs outsourced);
- Look at QC equipment and inspection records (air-tightness, burst, bypass valve calibration);
- Look at whether capacity and lead-time promises match.

**[Analytical Judgment]** **"Trading companies posing as factories" are very common in the filter industry.** A factory audit needs to look at only three things to identify them: **whether the production line is running, whether the filter paper inventory is sufficient, and whether the QC equipment is in use**. If these three are absent, be wary no matter how low the quote.

## 4. Inspection

**[Industry Knowledge]** Before shipping/pre-shipment inspection, sample per AQL, with key checks on:

- Dimensions and OE cross-reference fitment;
- Efficiency/material (against spec);
- Packaging integrity, labels, and carton quantities;
- Seal ring rebound, check valve/bypass valve (oil filters).

**[Data Citation]** Inspection items and judgment standards can refer to the [tech site's "Shipping and Export Inspection (OQC)"](https://tech.hycarfilter.com/qc/export-inspection/); packaging/carton quantities are subject to the [data site's "Export Packing Data"](https://data.hycarfilter.com/crossref/export-packing/).

**[Analytical Judgment]** **Inspection must be "third-party + pre-shipment"**: once the goods are on the ship, the remediation cost of finding problems is far higher. For key categories (oil filters), **add seal and bypass valve checks** — these two are high-frequency return points in the Middle East/Russia region.

## 5. Logistics

**[Industry Knowledge]** Filters are "**bulky goods, light weight**", and logistics is mainly ocean freight:

- For light cargo, container loading **is constrained by volume** (not weight);
- Pallet specs and container-load quantities affect per-unit freight;
- Moisture protection (desiccant/VCI/moisture-barrier pallets) is key for transoceanic transport.

**[Data Citation]** Pallet/40HQ loading quantity estimates are subject to the estimates in the [data site's "Export Packing Data"](https://data.hycarfilter.com/crossref/export-packing/) (**estimated reference / for reference only**), with the authoritative values being inner box/outer carton/loading quantity/net weight.

**[Analytical Judgment]** **Logistics cost is the invisible killer of filter export profits** — light cargo is billed by volume, and a 10% difference in loading density can mean a 10%–20% difference in per-unit freight. **Asking the supplier for a loading plan before ordering is a required lesson in saving money.**

## 6. Customs Clearance

**[Industry Knowledge]** Customs clearance requires: commercial invoice, packing list, bill of lading, certificate of origin, and certification documents (depending on the target country).

- **Correct HS classification** is the foundation of customs clearance (see filter HS codes below);
- Certification documents (EAC/GCC/INMETRO etc.) depend on the target country's requirements;
- The certificate of origin affects tariff treatment.

**[Data Citation]** The main HS codes for filters: air filter/cabin filter **8421310000**, oil filter/fuel filter **8421230000**, wiper blade **8512400000**, transmission filter screen **8708409990**, LED lights **8512209000** — identical in value to [data.hycarfilter](https://data.hycarfilter.com).

**[Framework Reference]** The legal and compliance requirements involved in customs clearance are subject to the target country's current regulations; **this article is a common-knowledge framework, not a legal or compliance conclusion**; for specific customs clearance, consult a professional customs broker.

## 7. Summary of the six-step flow

**[Analytical Judgment]** The essence of the six-step flow is to **use "small money + time" to verify away risks before "paying big money"**:

| Step | What it verifies | Cost of skipping |
|---|---|---|
| Inquiry | Supplier professionalism | Choosing the wrong supplier |
| Sample order | Physical item vs description | Bulk goods not matching the description |
| Factory audit | Real factory, capacity and quality control | Supply disruption/quality collapse |
| Inspection | Pre-shipment quality | Unrecoverable after the ship has sailed |
| Logistics | Loading and cost | Freight eating up profits |
| Customs clearance | Compliance and classification | Customs blockage/back taxes/returns |

**Every step is "insurance", not "cost".**

---

*Next: [Common Purchasing Pitfalls](common-pitfalls.md)*

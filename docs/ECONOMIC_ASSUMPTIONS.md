# Farm Economic Assumptions

**Purpose:** one common economic model for every space folder.  
**Currency:** Bangladesh Taka (BDT).  
**Status:** planning model, not an investment guarantee.

## 1. Current official market reference

The Bangladesh Department of Agricultural Marketing (DAM) online portal was checked on **2026-09-30**. It displayed current retail reference ranges including:
- Aman coarse rice: about BDT 48–50/kg
- Boro coarse rice: about BDT 47–49/kg
- farm-raised chicken: about BDT 162–167/kg
- mung: about BDT 122–128/kg
- local onion: about BDT 60–64/kg
- green chili: about BDT 218–237/kg

Source: https://market.dam.gov.bd/retail_price_commodity_report?L=E

**Important:** retail price is not the same as farm-gate price. Each space economics file must use the farm's actual realized price before any investment decision.

## 2. Editable example price scenarios

These are **model inputs only**, not claims about current farm-gate prices.

| Product/value | Conservative | Base | Upside | Unit |
|---|---:|---:|---:|---|
| Rice | 45 | 50 | 55 | BDT/kg |
| Maize | 30 | 35 | 40 | BDT/kg |
| Pulses | 100 | 115 | 130 | BDT/kg |
| Mustard/sesame | 60 | 70 | 80 | BDT/kg |
| Mixed vegetables | 35 | 50 | 80 | BDT/kg |
| Mixed fruit | 50 | 70 | 100 | BDT/kg |
| Fresh fodder replacement | 4 | 6 | 8 | BDT/kg fresh |
| Milk | 60 | 70 | 80 | BDT/L |
| Layer egg | 10 | 11.5 | 13 | BDT/egg |
| Broiler live price | 140 | 155 | 170 | BDT/kg live |
| Duck egg | 12 | 14 | 16 | BDT/egg |
| Fish | 180 | 220 | 280 | BDT/kg |
| Goat kid | 7,000 | 9,000 | 12,000 | BDT/head |
| Lamb | 6,000 | 8,000 | 10,000 | BDT/head |

## 3. Output scenarios used by the model

- Rice: 3.0 / 3.45 / 3.9 t/year
- Maize: 1.0 / 1.2 / 1.4 t/year
- Pulses: 0.12 / 0.15 / 0.18 t/year
- Oilseed: 0.10 / 0.125 / 0.15 t/year
- Vegetables: 8 / 11.5 / 15 t/year
- Mature orchard fruit: 6 / 8 / 10 t/year
- Fresh fodder: 80 / 95 / 110 t/year
- Milk: 6,720 / 10,920 / 15,120 L/year
- Layer eggs: 32,400 / 39,450 / 46,500/year
- Broiler sales: 300 / 435 / 570 birds/year, example average live weight 1.7 / 1.85 / 2.0 kg
- Duck eggs: 10,800 / 15,000 / 19,200/year
- Goat kids: 12 / 16 / 20/year
- Lambs: 4 / 6 / 8/year
- Canal fish: 1.2 / 1.6 / 2.0 t/year

## 4. Value categories

### Cash revenue
Money received from external sale.

### Internal replacement value
Value of an item the farm uses itself instead of buying externally, such as fodder, electricity, fertilizer, seed, irrigation water or milling.

### Avoided-loss value
Value protected by drainage, flood control, security, cold storage, quarantine, biosecurity, roads and backup power.

Do not add an avoided-loss value as if it were cash received. Keep cash and economic value separate.

## 5. Cost policy

The OPEX ranges in space folders are placeholders for planning sensitivity only. Replace with:
- local labor rates
- seed/feed/fertilizer/mineral prices
- veterinary and testing costs
- electricity/fuel prices
- packaging/transport
- repair/spare prices
- security/administration
- waste treatment
- insurance/finance if used

CAPEX is intentionally category-based until BOQ + vendor quotations are available.

## 6. Profit policy

No space file should call "gross value - selected OPEX" final profit. Full net profit also requires depreciation, finance, taxes/fees, owner/family labor policy, central overhead, replacement reserves and abnormal-loss allowance.

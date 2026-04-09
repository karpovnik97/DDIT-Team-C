# Three Horizons Portfolio Template

## Purpose

Structure transformation investments across short, medium, and long term. This portfolio becomes the sequencing logic for your midterm transformation roadmap.

## Instructions

Complete during the Sunday Three Horizons workshop. Use your AI Opportunity Map from Saturday as the primary input. Initiatives in the Deploy Now quadrant map to Horizon 1. Initiatives in the Invest to Enable quadrant map to Horizon 2.

---

## Horizon 1: Defend and Extend (Now to 12 months)

AI augmentation of existing processes. High readiness, high near-term ROI.

| # | Initiative name | Description | Investment estimate | Funding source | Link to AI Opportunity Map |
|---|---|---|---|---|---|
| H1-1 | AI Route Optimization Engine  | Deploy machine-learning routing software across Georgian Post's top 5 highest-volume delivery corridors (Tbilisi, Kutaisi, Batumi, Rustavi, Gori). Algorithm ingests live traffic, parcel density, and driver availability to generate daily optimized route plans, replacing manual dispatcher scheduling. Target: 12–15% reduction in cost-per-delivery within 9 months. | GEL 480,000 (software licensing + integration + dispatcher retraining) | Operational budget reallocation from fuel and overtime savings | Deploy Now — Route Optimization (High Value / High Readiness) |
| H1-2 | AI Customer Service Chatbot | Launch a Georgian-language conversational AI chatbot on the Georgian Post website and mobile app. Handles tier-1 queries: parcel tracking, delivery status, rescheduling, complaint logging, and COD confirmation. Deflects 60–65% of inbound call centre volume, freeing agents for complex cases | GEL 160,000 (chatbot platform license + Georgian NLP training + integration with tracking system) | Operational budget; partially offset by call centre headcount redeployment | Deploy Now — Customer Service Automation (High Value / High Readiness) |
| H1-3 | Seller API and Digital Onboarding Portal | Build and launch a public Seller Integration API enabling e-commerce sellers to generate labels, book pick-ups, receive tracking webhooks, and access delivery analytics programmatically. Zero-fee onboarding in Year 1 to accelerate supply-side critical mass. Target: 200 active sellers within 6 months of launch | GEL 320,000 (API development + seller dashboard UI + documentation + onboarding support) | Capital budget — platform foundation investment; revenue-generating from Month 7 via volume uplift | Deploy Now — Digital Seller Integration (High Value / High Readiness) |


---

## Horizon 2: Nurture and Build (12 to 36 months)

Platform pilots, data infrastructure, emerging business opportunities. Requires capital commitment before ROI is visible.

| # | Initiative name | Description | Investment estimate | Funding source | Prerequisite from H1 |
|---|---|---|---|---|---|
| H2-1 | National Logistics Data Platform | Consolidate all parcel, route, seller, and consumer data into a unified cloud data warehouse. Deploy demand forecasting models (predicting daily parcel volume by region 14 days ahead) and dynamic pricing engine (adjusting delivery rates by route density, time window, and parcel type). This becomes the intelligence layer powering all H3 initiatives. | GEL 740,000 (cloud infrastructure + data engineering team hire + model development) | H1 ROI savings + government digital transformation grant (if applicable) | H1-1 route data pipeline must be live and generating clean structured data; H1-3 seller API must be feeding volume data |  |
| H2-2 | Parcel Locker Network Rollout (AI-Sited) | Deploy 80–100 smart parcel lockers across Tbilisi and three secondary cities, with locker locations chosen by AI demand-density modelling (using H1-1 route data). Lockers enable 24/7 consumer collection, reduce failed-delivery rate (currently estimated 18–22%), and cut last-mile cost on dense urban routes by up to 30%. Partner with petrol stations, supermarkets, and pharmacies for host locations | GEL 1,800,000 (locker hardware + installation + IoT connectivity + consumer app integration) | Development bank financing + host-partner revenue-share to offset capex | H1-1 route density data required to site lockers accurately; H1-2 chatbot handles locker booking and consumer notifications  |
| H2-3 | Cross-Border E-Commerce Customs Integration | Build a digital customs pre-clearance API connecting Georgian Post's shipping system directly to the Revenue Service of Georgia. Sellers declare goods digitally at label generation; Georgian Post acts as a licensed customs broker. Reduces average clearance time from 3–5 days to same-day for compliant shipments. Positions Georgian Post as the preferred gateway for international e-commerce imports | GEL 560,000 (API development + legal/regulatory setup + Revenue Service integration + staff certification) | H1 ROI savings + per-shipment customs facilitation fee (new revenue stream from Month 18) | H1-3 Seller API must be live — customs data flows through the same seller onboarding pipeline |

---

## Horizon 3: Create and Options (36 months+)

AI-first operating model experiments, new market creation. Low probability, high upside. Only viable after H2 infrastructure is in place.

| # | Initiative name | Description | Investment estimate | Funding source | Prerequisite from H2 |
|---|---|---|---|---|---|
| H3-1 | Georgian E-Commerce Logistics Platform (Marketplace OS) | Launch a fully open logistics marketplace platform: Georgian Post becomes the operating system of domestic e-commerce, offering third-party couriers, warehousing partners, and fulfilment providers the ability to plug into the Georgian Post seller and consumer network via API. Georgian Post earns platform fees, data licensing revenue, and premium seller subscription tiers. Analogous to Fulfillment by Amazon but built on national postal infrastructure | GEL 2,200,000 (platform engineering + marketplace governance + partner integration + legal framework) | H2 platform data revenues + strategic investor / IFC / EBRD development finance | H2-1 data platform must be mature — marketplace pricing and matching is AI-driven; H2-3 customs integration creates the cross-border seller moat |
| H3-2 | Autonomous Last-Mile Pilot (Drone + Micro-EV) | Run a controlled pilot of autonomous last-mile delivery in two high-density Tbilisi districts using electric cargo bikes with AI routing and, in Phase 2, regulatory-approved delivery drones for rural low-density routes where human delivery is uneconomical. Designed to reduce last-mile cost by 40% on pilot routes and generate national policy precedent for drone logistics regulation | GEL 950,000 (pilot vehicles + regulatory engagement + safety certification + route AI adaptation) | Innovation grant (EU Horizon / USAID Georgia) + Georgian Post R&D budget | H2-1 demand forecasting required for autonomous routing; H2-2 locker network provides autonomous drop-off anchor points |

---

## Funding logic

How does H1 fund H2? How does H2 enable H3?

- H1 generates:
- GEL 580,000 in Year 1 operational savings from route optimization (fuel, overtime, dispatcher hours)
- GEL 95,000 in call centre cost reduction from chatbot deflection (agent headcount redeployment)
- GEL 320,000 in incremental parcel revenue from seller API volume uplift (200 new active sellers × average GEL 1,600 annual parcel spend)
- **Total H1 net value Year 1: ~GEL 995,000 against GEL 960,000 investment — payback within 12 months**

- H1 ROI funds:
- H2-1 Data Platform: financed by H1 savings reinvested in Year 2
- H2-3 Customs Integration: financed by H1 revenue uplift + new customs facilitation fee stream
- H2-2 Parcel Locker Network: requires development bank financing — H1 demonstrated operational improvements serve as the investment thesis for lenders

- H2 enables:
- H2-1 (Data Platform) is the non-negotiable prerequisite for H3-1 (Marketplace OS) — without clean, structured, real-time logistics data, the marketplace matching and dynamic pricing engine cannot function
- H2-2 (Locker Network) provides the physical anchor points for H3-2 autonomous delivery — lockers become autonomous drop zones, removing the need for human handoff
- H2-3 (Customs Integration) creates the cross-border seller moat that makes H3-1 platform defensible — international sellers stay on the platform because customs clearance is embedded and irreplaceable
- H2 revenue streams (customs fees, locker subscriptions, data licensing) provide the recurring income base that funds H3 R&D without requiring external equity dilution

---

## Quality check

Before finalizing:
- Is there at least one initiative per horizon?
- Is the sequencing logical: does H2 depend on H1 outputs?
- Is the funding logic explicit?
- Do H1 initiatives match your AI Opportunity Map Deploy Now quadrant?

## Deliverable

Save in your team folder as:
`three_horizons_portfolio_v1.md`

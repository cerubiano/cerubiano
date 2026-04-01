# Carlos Rubiano — Data Analyst & Data Engineer | Travel Tech · Montreal, QC

I build data pipelines and analytical systems applied to real-world API integrations, search engine observability, and multi-source data quality.

Based in Montreal. Open to Data Analyst and Data Engineer roles
in Canadian travel tech.

---

## Portfolio Projects

### Flight API Data Quality Platform
A batch data pipeline that ingests, normalizes, and scores the
quality of flight offers from Amadeus (GDS) and Duffel (NDC).

- Medallion Architecture: Bronze → Silver → Gold layers
- Hexagonal Architecture (Ports & Adapters) for provider isolation
- Quality scoring across four dimensions: Completeness, Validity,
  Consistency, and Conformity
- Results published on Tableau Public

**Stack:** Python 3.12 · Pydantic v2 · PostgreSQL · Parquet · Tableau Public  
**Repo:** [flight-api-data-quality](https://github.com/cerubiano/flight-api-data-quality)  
**Dashboard:** [Tableau Public](https://public.tableau.com/app/profile/carlos.rubiano3854/viz/FlightAPIDataQualityPlatform/FlightAPIDataQuality?publish=yes)

---

### Search Engine Performance Monitor
Monitors flight search engine behavior across 12 routes —
domestic Canadian, short-haul, and long-haul international.
Tracks coverage, price stability, and anomalies over time.

- Six days-in-advance windows per route (7 to 180 days)
- Three anomaly detection rules: coverage drop, price spike,
  and zero-results
- Hexagonal Architecture with provider and repository ports
- Full documentation: PRD, System Architecture, and layer specs

**Stack:** Python 3.12 · Pydantic v2 · PostgreSQL · Parquet · Tableau Public  
**Repo:** [search-engine-monitor](https://github.com/cerubiano/search-engine-monitor)

---

## Domain Knowledge

Production integrations across the full travel stack:

- **GDS:** Amadeus, Sabre
- **NDC:** Direct airline connections, Duffel aggregator
- **Rail:** RailEurope
- **Hotels:** Hotelbeds
- **Payments:** Multi-country gateways across LATAM (Argentina,
  Colombia, Ecuador)

I understand how flight data moves from airline inventory to OTA
search results — and where quality breaks down.

---

## Technical Skills

**Languages:** Python · SQL  
**Data:** Pandas · PyArrow · Pydantic v2 · PostgreSQL  
**Architecture:** Medallion Architecture · Hexagonal Architecture ·
TDD · SOLID  
**Visualization:** Tableau Public · Power BI · Looker  
**DevOps:** Git · GitHub Actions · Docker  
**Cloud:** AWS (EC2, S3, RDS) · Terraform

---

## Articles & Technical Content

Architectural breakdowns and hands-on use cases:  
[Medium — Data Engineering & Travel Tech](https://medium.com/@cerubiano)

---

## Contact

[LinkedIn](https://www.linkedin.com/in/cerubiano/) ·
[GitHub](https://github.com/cerubiano) ·
cerubiano@gmail.com

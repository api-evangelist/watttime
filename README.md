# WattTime (watttime)

WattTime is a nonprofit organization that provides real-time, forecast, and historical data for electric grids around the world, enabling carbon-aware computing and clean energy procurement decisions. The WattTime API delivers marginal emissions data (CO2 MOER), health damage signals, average emissions rates, and renewable energy forecasts for 342 grid regions across 210 countries and territories.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/watttime/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Emissions, Climate, Carbon, Energy, Electricity Grid, Sustainability, Clean Energy

## Timestamps

- **Created:** 2025-05-02
- **Modified:** 2026-05-03

## APIs

### WattTime API

The WattTime Data API v3 provides access to real-time, forecast, and historical marginal emissions data for electric grids worldwide. Key signals include CO2 MOER, health damage estimates, and CO2 AOER. The API covers 342 grid regions in 210 countries and territories, with real-time data updated every five minutes.

**Human URL:** [https://docs.watttime.org/](https://docs.watttime.org/)

#### Tags:

 - Emissions, Carbon, Electricity Grid, Marginal Emissions, Forecasting, Climate

#### Properties

- [Documentation](https://docs.watttime.org/)
- [Legacy API v2 Documentation](https://legacy-docs.watttime.org/)
- [OpenAPI](openapi/watttime-openapi.yml)
- [Data Point Schema](json-schema/watttime-data-point-schema.json)
- [Data Response Schema](json-schema/watttime-data-response-schema.json)
- [Forecast Response Schema](json-schema/watttime-forecast-response-schema.json)
- [Region Response Schema](json-schema/watttime-region-response-schema.json)
- [Data Point Structure](json-structure/watttime-data-point-structure.json)
- [Data Response Structure](json-structure/watttime-data-response-structure.json)

### WattTime Python Client

Official Python SDK for the WattTime API providing simplified access to real-time, forecast, and historical emissions data.

**Human URL:** [https://github.com/WattTime/watttime-python-client](https://github.com/WattTime/watttime-python-client)

#### Tags:

 - Python, SDK, Client Library

#### Properties

- [Python SDK (PyPI)](https://pypi.org/project/watttime/)
- [Python Client Examples](https://github.com/WattTime/watttime-python-client)

## Common Properties

- [WattTime Website](https://watttime.org/)
- [API Documentation](https://docs.watttime.org/)
- [API Release Notes](https://watttime.org/data-science/release-notes/)
- [API Status Page](http://status.watttime.org/)
- [WattTime GitHub Organization](https://github.com/WattTime)
- [Support Email](mailto:support@watttime.org)
- [WattTime Spectral Rules](rules/watttime-spectral-rules.yml)
- [Carbon-Aware Computing Capability](capabilities/carbon-aware-computing.yaml)
- [WattTime Vocabulary](vocabulary/watttime-vocabulary.yml)
- [WattTime JSON-LD Context](json-ld/watttime-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Real-Time Marginal Emissions | CO2 MOER signal providing real-time marginal carbon intensity for local grid regions, updated every 5 minutes. |
| Emissions Forecasting | 24-72 hour ahead emissions forecasts enabling applications to schedule energy-intensive workloads during low-carbon windows. |
| Historical Data Access | Historical MOER data available for up to 32 days, and multi-year historical datasets downloadable as CSV files. |
| Health Damage Signal | Estimates the damage to human life and health caused by emissions from electricity generation based on time and location. |
| Global Grid Coverage | Coverage across 342 grid regions in 210 countries and territories. |
| Grid Region Discovery | Identify the relevant balancing authority for any geographic coordinates. |
| Model Versioning | Date-based model versioning (e.g., 2026-03-01) for reproducibility and comparison. |

## Use Cases

| Name | Description |
|------|-------------|
| Carbon-Aware Computing | Schedule compute workloads, data transfers, and batch jobs to run during periods of low marginal carbon intensity. |
| Clean Energy Procurement | Measure actual emissions reductions from renewable energy procurement and power purchase agreements. |
| Sustainability Reporting | Report Scope 2 emissions more accurately using marginal emissions rates rather than average grid factors. |
| Smart Building Optimization | Shift heating, cooling, and EV charging to low-emission grid windows to reduce carbon footprint. |
| Grid Research and Analysis | Analyze historical and forecast emissions data to study grid decarbonization trends. |

## Integrations

| Name | Description |
|------|-------------|
| Green Software Foundation | Provides carbon intensity data underlying the Green Software Foundation's SCI specification. |
| Climate TRACE | Contributes emissions data and modeling to the Climate TRACE global emissions inventory. |
| Impact Framework | Official GSF Impact Framework plugin for integrating WattTime data into software sustainability measurements. |

## Artifacts

### OpenAPI

- [WattTime API](openapi/watttime-openapi.yml)

### JSON Schema

- [watttime-data-meta-schema.json](json-schema/watttime-data-meta-schema.json)
- [watttime-data-point-schema.json](json-schema/watttime-data-point-schema.json)
- [watttime-data-response-schema.json](json-schema/watttime-data-response-schema.json)
- [watttime-forecast-meta-schema.json](json-schema/watttime-forecast-meta-schema.json)
- [watttime-forecast-response-schema.json](json-schema/watttime-forecast-response-schema.json)
- [watttime-grid-maps-response-schema.json](json-schema/watttime-grid-maps-response-schema.json)
- [watttime-historical-download-response-schema.json](json-schema/watttime-historical-download-response-schema.json)
- [watttime-login-response-schema.json](json-schema/watttime-login-response-schema.json)
- [watttime-my-access-response-schema.json](json-schema/watttime-my-access-response-schema.json)
- [watttime-region-access-schema.json](json-schema/watttime-region-access-schema.json)
- [watttime-region-response-schema.json](json-schema/watttime-region-response-schema.json)
- [watttime-register-request-schema.json](json-schema/watttime-register-request-schema.json)
- [watttime-register-response-schema.json](json-schema/watttime-register-response-schema.json)

### JSON Structure

- [watttime-data-meta-structure.json](json-structure/watttime-data-meta-structure.json)
- [watttime-data-point-structure.json](json-structure/watttime-data-point-structure.json)
- [watttime-data-response-structure.json](json-structure/watttime-data-response-structure.json)
- [watttime-forecast-meta-structure.json](json-structure/watttime-forecast-meta-structure.json)
- [watttime-forecast-response-structure.json](json-structure/watttime-forecast-response-structure.json)
- [watttime-grid-maps-response-structure.json](json-structure/watttime-grid-maps-response-structure.json)
- [watttime-historical-download-response-structure.json](json-structure/watttime-historical-download-response-structure.json)
- [watttime-login-response-structure.json](json-structure/watttime-login-response-structure.json)
- [watttime-my-access-response-structure.json](json-structure/watttime-my-access-response-structure.json)
- [watttime-region-access-structure.json](json-structure/watttime-region-access-structure.json)
- [watttime-region-response-structure.json](json-structure/watttime-region-response-structure.json)
- [watttime-register-request-structure.json](json-structure/watttime-register-request-structure.json)
- [watttime-register-response-structure.json](json-structure/watttime-register-response-structure.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [WattTime API](capabilities/shared/watttime-api.yaml) — 8 operations for marginal emissions data, forecasting, and grid region discovery

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Carbon-Aware Computing](capabilities/carbon-aware-computing.yaml) | WattTime API | 8 | Software Engineer, Platform Engineer, Sustainability Analyst |

## Vocabulary

- [WattTime Vocabulary](vocabulary/watttime-vocabulary.yml) — Unified taxonomy mapping 5 resources, 8 actions, 3 workflows, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [WattTime Spectral Rules](rules/watttime-spectral-rules.yml) — 22 rules across 9 categories enforcing WattTime API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

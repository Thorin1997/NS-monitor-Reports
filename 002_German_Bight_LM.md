<div align="center">

![NS-Monitor Logo](./Logo_report.png)

# NS-Monitor

### Research Report — 002

**Maritime Geo-Risk Intelligence · North Sea Basin**

| | |
|---|---|
| **Report number** | Research Report 002 |
| **Publication date** | 07 August 2026 |
| **Focus** | German EEZ -- Longitudinal Monitoring |
| **Object** | Assess maritime activity around subsea infrastructure |
| **Coverage area** | German Bight |
| **Monitoring period** | 03-04 August 2026 |
| **Daily observation window** | 2030/2130Z |

---

</div>

## Executive Summary

During this longitudinal monitoring of the German Bight, **NS-Monitor** processed over **16,000 unique MMSIs** across the North Sea basin, integrating real-time AIS data with EMODnet datasets on critical subsea infrastructure. Approximately **60 minutes** of cumulative monitoring generated multiple analyst review events; **14 events** were selected for manual analysis based on infrastructure proximity and vessel behaviour.

Although no anomalous behaviour was identified during this monitoring period, the study demonstrates the usefulness of systematic automated screening for supporting maritime infrastructure monitoring.

---

## 1. Introduction

Over the past few months, I have been developing my own maritime geo-risk monitoring platform. I developed this platform to support the prioritisation of maritime activity around critical infrastructure, enabling analysts to focus manual review on the most relevant events.

---

## 2. Methodology

### 2.1 Data sources

| Source | Description |
|--------|-------------|
| **AIS (Automatic Identification System)** | Real-time vessel position and identity data |
| **EMODnet Human Activities** | Critical subsea infrastructure: pipelines, power cables, telecommunication cables |

### 2.2 Processing scope

- **Unique vessels (MMSI):** > 16,000
- **Geographic scope:** German Bight
- **Monitoring duration:** ~60 minutes (cumulative)
- **Event selection:** Manual analysis subset chosen by infrastructure proximity and vessel behaviour

### 2.3 Analyst Review Queue

An event entering the **Analyst Review Queue** does **not** indicate suspicious or malicious activity. It represents a **prioritised case** for manual assessment based on predefined monitoring criteria (proximity to infrastructure, movement patterns, etc.).

---

## 3. Results

### 3.1 Event breakdown by infrastructure type

| Infrastructure type | Events | Share |
|---------------------|--------|-------|
| Telecommunications cables | 12 | 85.7% |
| Power cables | 2 | 14.3% |
| **Total (analysed subset)** | **14** | **100%** |

### 3.2 Flag-state analysis (preliminary)

Vessels involved in the analysed events are **almost exclusively** registered to countries bordering the North Sea:

| Flag state | Notes |
|------------|-------|
| Germany | Primary |
| Nethrelands | Primary |
| Denmark | Primary |
| United Kingdom | Primary |
| France | Exception |
| Niue | Exception |
| Panama | Exception |
| Bahamas | Exception |
| Faroe Islands | Exception |
| Madeira | Exception |
| Malta | Exception |

---

## 4. Limitations

AIS coverage depends on the availability of transmissions and reception quality.
An event entering the Analyst Review Queue does not indicate suspicious or malicious activity. It simply represents a prioritised case for manual assessment based on predefined monitoring criteria.
This monitoring represents a limited temporal observation and should not be interpreted as a comprehensive assessment of all maritime activity within the area.
AIS message totals and unique MMSI counts are subject to variance due to observation window constraints.


---

## 5. Conclusion

Although no anomalous behaviour was identified during this monitoring period, the study demonstrates the usefulness of systematic automated screening for supporting maritime infrastructure monitoring.
This report forms part of the ongoing NS-Monitor research programme, documenting software development, operational monitoring activities, and maritime traffic analysis across the North Sea.

---

<div align="center">

*This report is part of an ongoing operational series documenting the development of NS-Monitor and long-term maritime activity trends in the North Sea.*

**NS-Monitor** · Maritime Geo-Risk Intelligence

</div>

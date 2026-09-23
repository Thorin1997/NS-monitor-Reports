<div align="center">

![NS-Monitor Logo](./images/Logo_report.png)

# NS-Monitor

### Research Report — 008

**Maritime Geo-Risk Intelligence · North Sea Basin**

Bericht über das Monitoring in der Deutschen Bucht
Risikobewertung

| | |
|---|---|
| **Report number** | Research Report 008 |
| **Publication date** | 23 September 2026 |
| **Focus** | German EEZ -- Longitudinal Monitoring |
| **Object** | Assess maritime activity around subsea infrastructure |
| **Coverage area** | German Bight |
| **Monitoring period** | 21-22 September 2026 |
| **Daily observation window** | 1900/2000Z |

---

</div>

## Executive Summary

During this longitudinal monitoring of the German Bight, **NS-Monitor** processed over **14,000 unique MMSIs** across the North Sea basin, integrating real-time AIS data with EMODnet datasets on critical subsea infrastructure. Approximately **120 minutes** of cumulative monitoring generated multiple analyst review events; **3 events** were selected for manual analysis based on infrastructure proximity and vessel behaviour.

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

- **Unique vessels (MMSI):** > 14,000
- **Geographic scope:** German Bight
- **Monitoring duration:** ~120 minutes (cumulative)
- **Event selection:** Manual analysis subset chosen by infrastructure proximity and vessel behaviour

### 2.3 Analyst Review Queue

An event entering the **Analyst Review Queue** does **not** indicate suspicious or malicious activity. It represents a **prioritised case** for manual assessment based on predefined monitoring criteria (proximity to infrastructure, movement patterns, etc.).

---

## 3. Results

### 3.1 Event breakdown by infrastructure type

| Infrastructure type | Events | Share |
|---------------------|--------|-------|
| Telecommunications cables | 2 | 66,5% |
| Power Cable | 1 | 33,5% |
| Pipelines | 0 | 0% |
| **Total (analysed subset)** | **3** | **100%** |

### 3.2 Flag-state analysis (preliminary)

Vessels involved in the analysed events are **almost exclusively** registered to countries bordering the North Sea:

| Flag state | Notes |
|------------|-------|
| Germany | Primary |
| Nethrelands | Primary |
| Denmark | Primary |
| United Kingdom | Primary |
| Bahamas | Exception |
| France | Exception |
| Gibraltar | Exception |

### 3.3 Risk/Attention level

1)      MMSI Bahamas, infrastructure ID: bshcontiscables.20, attention level: LOW
2)      MMSI France, infrastructure ID: pcablesrijks.36, attention level: LOW
3)      MMSI Gibraltar, infrastructure ID: bshcontiscables.20, attention level: MODERATE

---

## 4. Limitations

AIS coverage depends on the availability of transmissions and reception quality.
An event entering the Analyst Review Queue does not indicate suspicious or malicious activity. It simply represents a prioritised case for manual assessment based on predefined monitoring criteria.
This monitoring represents a limited temporal observation and should not be interpreted as a comprehensive assessment of all maritime activity within the area.
AIS message totals and unique MMSI counts are subject to variance due to observation window constraints.


---

## 5. Conclusion

The Gibraltar-flagged vessel (MMSI 3) is identified by MarineTraffic as a Multi-Purpose Offshore Vessel. During the observation period, it was travelling below 1 knot, and its destination was listed as Unknown.
These observations resulted in a MODERATE attention classification under the NS-Monitor assessment criteria. The classification indicates that the event warranted manual review; it does not indicate suspicious or malicious activity.

---

<div align="center">

*This report is part of an ongoing operational series documenting the development of NS-Monitor and long-term maritime activity trends in the North Sea.*

**NS-Monitor** · Maritime Geo-Risk Intelligence

</div>

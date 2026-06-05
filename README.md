# U.S. Airline Network Resilience and Connectivity Analysis (2019–2022)

## Social Network Analysis Project

---

## Overview

This project applies Social Network Analysis (SNA) to study the structure, resilience, and evolution of the U.S. domestic airline network from 2019 to 2022.

The airline system is modeled as a weighted network where passenger flows between states define connections. The study examines how the network changed during the COVID-19 pandemic, identifies key hubs and bottlenecks, and evaluates the recovery of connectivity after disruption.

---

## Research Questions

* Which states act as the main passenger hubs in the U.S. airline network?
* Which states serve as major origins and destinations of air traffic?
* Which states function as network bottlenecks?
* Which states are most influential in maintaining network connectivity?
* How does COVID-19 affect network structure and connectivity?
* How resilient is the airline network to large-scale disruption?

---

## Dataset

The analysis uses the **US Airline Flight Routes and Fares Dataset (1993–2024)**.

Four yearly networks were constructed:

* 2019 (Pre-COVID period)
* 2020 (COVID peak)
* 2021 (Recovery phase)
* 2022 (Post-COVID recovery)

---

## Network Construction

* **Nodes:** U.S. states / metropolitan areas
* **Edges:** Passenger flows between states
* **Edge Weights:** Number of passengers transported

The airline system is modeled as a **weighted directed network**.

---

## Methodology

### Social Network Analysis (SNA)

The following network metrics were computed:

#### Degree Centrality

Measures overall connectivity and identifies major airline hubs.

#### Weighted In-Degree

Measures passenger arrivals (destination importance).

#### Weighted Out-Degree

Measures passenger departures (origin importance).

#### Betweenness Centrality

Identifies bottleneck states controlling passenger flow.

#### Eigenvector Centrality

Measures influence based on connections to other important nodes.

#### Closeness Centrality

Captures how quickly disruptions can spread across the network.

#### Clustering Coefficient

Measures local connectivity and regional structure.

#### Degree Assortativity

Evaluates whether hubs connect to other hubs or to smaller states.

---

## Key Findings

### Core Airline Hubs

The U.S. airline network is consistently dominated by:

* California
* Texas
* Florida
* New York
* Illinois

These states act as:

* Major hubs
* Network bottlenecks
* Influence centers
* Delay propagation points

---

### Network Structure

* The system follows a **hub-and-spoke structure**
* Strong negative assortativity (~ -0.63) confirms that hubs primarily connect to smaller states
* The network remains highly centralized across all years

---

### COVID-19 Impact

#### 2020 (Pandemic Peak)

* Sharp decline in passenger flows
* Increased reliance on major hubs
* Reduced network diversity

#### 2021 (Recovery)

* Gradual restoration of connectivity
* Partial recovery of key hubs (NY, CA)

#### 2022 (Post-Recovery)

* Return to pre-pandemic structure
* Re-establishment of dominant hubs

---

### Network Resilience

* Despite major disruption, the overall structure remained stable
* Hub dominance persisted across all years
* Regional connectivity helped maintain system stability

---

### Bottlenecks and Risk

* Texas consistently emerged as the most important bottleneck
* Highly connected states are also the most likely to propagate delays and disruptions
* Some states show strong dependence on limited routes, increasing vulnerability

---

## Conclusion

This study shows that the U.S. airline network is both **highly resilient and highly centralized**.

While COVID-19 caused major short-term disruptions in passenger flows, the underlying hub-and-spoke structure remained stable. Recovery patterns confirm that a small group of core hubs continues to dominate national connectivity.

These findings highlight the importance of improving regional connectivity and reducing over-dependence on major hubs to enhance system robustness against future disruptions.

---

## Tools & Technologies

* Python
* NetworkX
* Pandas
* NumPy
* Gephi
* Data Visualization

---

## Skills Demonstrated

* Social Network Analysis (SNA)
* Network Centrality Analysis
* Graph Theory Applications
* Data Visualization
* Transportation Network Modeling
* Resilience & Disruption Analysis
* Python Data Science
* Gephi Network Mapping

---

## Keywords

Social Network Analysis, Airline Network, NetworkX, Gephi, COVID-19 Impact, Transportation Networks, Graph Theory, Centrality Measures, Network Resilience, Data Science, Python

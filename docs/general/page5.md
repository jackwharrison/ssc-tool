# Default Decision Tree

This page outlines the default decision-tree approach used to aggregate the three pillar scores for each household, ultimately determining the Overall Shelter Severity Score. This method is sequential, meaning each step in the aggregation process depends on the previous one. Specifically, you first assess Pillar 1 (The Shelter), then Pillar 2 (Inside the Shelter), and finally Pillar 3 (Outside the Shelter). The path taken through these steps determines the final severity score.

The underlying logic prioritizes the condition of the shelter itself. If a household’s shelter is in poor condition—or worse, if they have no shelter at all—this places them in a high level of need, regardless of their domestic functionality or access to services. As a result, the shelter score has the greatest influence on the final severity score. However, if a household has low severity in terms of shelter, their overall severity may still increase slightly if they face significant challenges in domestic functions or access to services.

## Pillar 1 - Phase 5 (Catastrophic)


| Pillar 1: The Shelter | Pillar 2: Inside The Shelter | Pillar 3: Outside The Shelter | Overall Shelter Severity Score |
|-----------------------|----------------------------|-----------------------------|--------------------------------|
| 5                     | 4                          | 4                           | 5                              |
| 5                     | 4                          | 3                           | 5                              |
| 5                     | 4                          | 2                           | 5                              |
| 5                     | 4                          | 1                           | 5                              |
| 5                     | 3                          | 4                           | 5                              |
| 5                     | 3                          | 3                           | 5                              |
| 5                     | 3                          | 2                           | 5                              |
| 5                     | 3                          | 1                           | 5                              |
| 5                     | 2                          | 4                           | 5                              |
| 5                     | 2                          | 3                           | 5                              |
| 5                     | 2                          | 2                           | 5                              |
| 5                     | 2                          | 1                           | 5                              |
| 5                     | 1                          | 4                           | 5                              |
| 5                     | 1                          | 3                           | 5                              |
| 5                     | 1                          | 2                           | 5                              |
| 5                     | 1                          | 1                           | 5                              |


## Pillar 1  - Phase 4 (Critical)


| Pillar 1: The Shelter | Pillar 2: Inside The Shelter | Pillar 3: Outside The Shelter | Overall Shelter Severity Score |
|-----------------------|----------------------------|-----------------------------|--------------------------------|
| 4                     | 4                          | 4                           | 4                              |
| 4                     | 4                          | 3                           | 4                              |
| 4                     | 4                          | 2                           | 4                              |
| 4                     | 4                          | 1                           | 4                              |
| 4                     | 3                          | 4                           | 4                              |
| 4                     | 3                          | 3                           | 4                              |
| 4                     | 3                          | 2                           | 4                              |
| 4                     | 3                          | 1                           | 4                              |
| 4                     | 2                          | 4                           | 3                              |
| 4                     | 2                          | 3                           | 3                              |
| 4                     | 2                          | 2                           | 3                              |
| 4                     | 2                          | 1                           | 3                              |
| 4                     | 1                          | 4                           | 3                              |
| 4                     | 1                          | 3                           | 3                              |
| 4                     | 1                          | 2                           | 3                              |
| 4                     | 1                          | 1                           | 3                              |


## Pillar 1 - Phase 3 (Crisis)

| Pillar 1: The Shelter | Pillar 2: Inside The Shelter | Pillar 3: Outside The Shelter | Overall Shelter Severity Score |
|-----------------------|----------------------------|-----------------------------|--------------------------------|
| 3                     | 4                          | 4                           | 4                              |
| 3                     | 4                          | 3                           | 3                              |
| 3                     | 4                          | 2                           | 3                              |
| 3                     | 4                          | 1                           | 3                              |
| 3                     | 3                          | 4                           | 3                              |
| 3                     | 3                          | 3                           | 3                              |
| 3                     | 3                          | 2                           | 3                              |
| 3                     | 3                          | 1                           | 3                              |
| 3                     | 2                          | 4                           | 3                              |
| 3                     | 2                          | 3                           | 3                              |
| 3                     | 2                          | 2                           | 3                              |
| 3                     | 2                          | 1                           | 3                              |
| 3                     | 1                          | 4                           | 3                              |
| 3                     | 1                          | 3                           | 3                              |
| 3                     | 1                          | 2                           | 3                              |
| 3                     | 1                          | 1                           | 3                              |


## Pillar 1 - Phase 2 (Stressed)

| Pillar 1: The Shelter | Pillar 2: Inside The Shelter | Pillar 3: Outside The Shelter | Overall Shelter Severity Score |
|-----------------------|----------------------------|-----------------------------|--------------------------------|
| 2                     | 4                          | 4                           | 3                              |
| 2                     | 4                          | 3                           | 3                              |
| 2                     | 4                          | 2                           | 2                              |
| 2                     | 4                          | 1                           | 2                              |
| 2                     | 3                          | 4                           | 3                              |
| 2                     | 3                          | 3                           | 2                              |
| 2                     | 3                          | 2                           | 2                              |
| 2                     | 3                          | 1                           | 2                              |
| 2                     | 2                          | 4                           | 2                              |
| 2                     | 2                          | 3                           | 2                              |
| 2                     | 2                          | 2                           | 2                              |
| 2                     | 2                          | 1                           | 2                              |
| 2                     | 1                          | 4                           | 2                              |
| 2                     | 1                          | 3                           | 2                              |
| 2                     | 1                          | 2                           | 2                              |
| 2                     | 1                          | 1                           | 2                              |


## Pillar 1 - Phase 1 (None / Minimal)

| Pillar 1: The Shelter | Pillar 2: Inside The Shelter | Pillar 3: Outside The Shelter | Overall Shelter Severity Score |
|-----------------------|----------------------------|-----------------------------|--------------------------------|
| 1                     | 4                          | 4                           | 3                              |
| 1                     | 4                          | 3                           | 2                              |
| 1                     | 4                          | 2                           | 2                              |
| 1                     | 4                          | 1                           | 2                              |
| 1                     | 3                          | 4                           | 3                              |
| 1                     | 3                          | 3                           | 2                              |
| 1                     | 3                          | 2                           | 2                              |
| 1                     | 3                          | 1                           | 2                              |
| 1                     | 2                          | 4                           | 2                              |
| 1                     | 2                          | 3                           | 2                              |
| 1                     | 2                          | 2                           | 1                              |
| 1                     | 2                          | 1                           | 1                              |
| 1                     | 1                          | 4                           | 1                              |
| 1                     | 1                          | 3                           | 2                              |
| 1                     | 1                          | 2                           | 1                              |
| 1                     | 1                          | 1                           | 1                              |



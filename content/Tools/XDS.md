---
aliases:
  - XDS
  - X-ray Detector Software
tags: [tool]
---
> [!info] Info
> XDS is the most widely used software for processing X-ray diffraction data from single-crystal experiments. Developed by [[Wolfgang Kabsch]] at the Max Planck Institute for Medical Research, Heidelberg, Germany. Free for academic use but closed-source (binary-only distribution). Handles indexing, integration, scaling, and merging.

> [!warning] Closed source
> Unlike [[DIALS]] (fully open-source) and [[CCP4]] tools, XDS is distributed as binaries only. This is a significant governance/access point. Wolfgang Kabsch is the sole developer and maintainer, creating a bus factor of 1.

## People
| Name | Role | Affiliation |
|------|------|-------------|
| [[Wolfgang Kabsch]] | Sole developer | Max Planck Institute for Medical Research, Heidelberg |

## Key Relationships
- Dominant competitor to [[DIALS]] and [[Global Phasing Ltd]] autoPROC for data processing
- Output feeds into [[CCP4]], [[PHENIX]], [[Coot]] pipelines
- XSCALE (part of XDS) used for scaling/merging
- XDS2 successor effort has been discussed but not publicly released

## Key Reference
Kabsch, Acta Cryst D66, 125-132 (2010)
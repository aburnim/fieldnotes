---
aliases:
  - PHENIX Consortium
  - Phenix Consortium
  - Phenix Team
tags: [institution]
---

#mx #cryo-em #computational #software-dev #phenix-community

> [!info] Info
> PHENIX (Python-based Hierarchical ENvironment for Integrated Xtallography) is a multi-institutional software consortium developing the dominant automated macromolecular structure determination suite for X-ray crystallography, neutron diffraction, and cryo-EM. The consortium has been led by [[Paul Adams]] at [[Lawrence Berkeley National Laboratory|LBNL]] since 1999, with partner sites at the [[University of Cambridge]] (Phaser), [[Duke University]] (MolProbity / Richardson Lab), [[Los Alamos National Laboratory]] / [[New Mexico Consortium]], and UTHealth Houston. A 2021 Berkeley Lab Tech Transfer Award recognized the LBNL core team.

> [!faq] Why PHENIX matters for this landscape
> PHENIX is built on the Computational Crystallography Toolbox (cctbx), which is the shared numerical foundation with [[DIALS]] (data processing). The consortium is the single largest concentration of current-generation structural biology software development in the US, and its training lineage runs back through CNS/XPLOR to [[Axel T. Brunger]] at [[Stanford University]].

## Current team (2026)

### Lawrence Berkeley National Laboratory
| Member | Role |
|--------|------|
| [[Paul Adams]] | Principal Investigator and Phenix Program Director |
| [[Pavel Afonine]] | Scientist - phenix.refine lead |
| [[Dorothee Liebschner]] | Scientist - real-space refinement, cryo-EM, validation |
| [[Nigel Moriarty]] | Scientist - eLBOW, ligand restraints |
| [[Billy Poon]] | Scientist - cctbx, build infrastructure |
| [[Oleg Sobolev]] | Scientist - refinement, riding hydrogen model |
| [[Peter H. Zwart]] | Scientist - cctbx, SAXS (also [[ALS]] beamline scientist) |
| [[Christopher Schlicksup]] | Postdoctoral Associate |

### University of Cambridge (CIMR)
| Member | Role |
|--------|------|
| [[Randy Read]] | Principal Investigator, Professor of Protein Crystallography; [[IUCr]] President |
| [[Airlie McCoy]] | Principal Research Associate; [[Phaser]] lead developer (2000-) |
| [[Alisia Fadini]] | Research Associate |

### Duke University (Richardson Lab)
| Member | Role |
|--------|------|
| [[Jane S. Richardson]] | Principal Investigator; [[MolProbity]] co-founder |
| [[Vincent Chen]] | Senior Research Associate; MolProbity / KiNG / Probe |
| [[Christopher Williams]] | Postdoctoral Associate; Reduce / CaBLAM |
| [[W. Bryan Arendall, III]] | Richardson Lab staff; [[wwPDB task force-X-Ray Validation|XVTF]] |

### Los Alamos National Laboratory / New Mexico Consortium
| Member | Role |
|--------|------|
| [[Thomas Terwilliger]] | Laboratory Fellow and Senior Scientist; SOLVE/RESOLVE; PHENIX co-founder |
| [[Li-Wei Hung]] | Staff Member; LANL PHENIX contingent |

### UTHealth Houston
| Member | Role |
|--------|------|
| [[Matt Baker]] | Assistant Professor; cryo-EM tools integration |

## Generational structure

PHENIX is a good illustration of the founder-to-current-generation handoff in macromolecular software:

| Role | Founders (1999-2010) | Current generation (2020s) |
|------|----------------------|----------------------------|
| LBNL lead | [[Paul Adams]] | [[Paul Adams]] (continuing), with [[Pavel Afonine]], [[Dorothee Liebschner]], [[Billy Poon]] as senior scientists |
| Molecular replacement | [[Randy Read]] | [[Airlie McCoy]] (lead developer); [[Alisia Fadini]] |
| Validation (Duke) | [[Jane S. Richardson]] / David Richardson | [[Vincent Chen]], [[Christopher Williams]] |
| Experimental phasing (LANL) | [[Thomas Terwilliger]] | [[Li-Wei Hung]] |
| Cryo-EM integration | (none originally) | [[Matt Baker]] (UTHealth), [[Dorothee Liebschner]] (LBNL) |

## Software lineage context

The PHENIX codebase descends from **CNS** (Crystallography and NMR System) which [[Paul Adams]] helped develop as a postdoc in [[Axel T. Brunger]]'s lab at Yale. CNS in turn descended from **XPLOR** (also Brunger). Parallel descendants from the same root include [[XPLOR-NIH]] ([[Charles Schwieters]], [[Marius Clore]]). This means [[PHENIX]] and [[XPLOR-NIH]] are computational siblings with shared DNA in the Brunger lineage.

## Key Relationships
- [[CCP4]] -- European parallel consortium for MX software; Phaser is co-distributed via both
- [[DIALS]] -- data processing partner built on the same cctbx foundation
- [[MolProbity]] -- validation pipeline, shared Duke origin
- [[wwPDB]] -- PHENIX is embedded in OneDep deposition/validation
- [[ALS]] -- LBNL home facility; Berkeley Center for Structural Biology
- [[NIAC]] ([[Aaron Brewster]], Chair) -- data format governance partner at LBNL

## Funding
- NIH P01 GM063210 (to [[Paul Adams]], [[Randy Read]], [[Jane S. Richardson]]) -- core multi-institutional program project grant
- NIH R01/R24 supplements
- 2017 NIH $9.3M award for further PHENIX development
- DOE support via LBNL

## Primary sources
- PHENIX team page: https://phenix-online.org/people
- 2021 Berkeley Lab Tech Transfer Award (Phenix Team): https://recognition.lbl.gov/2021-laureates/
- Liebschner et al., "Macromolecular structure determination using X-rays, neutrons and electrons: recent developments in Phenix" (Acta Cryst D 2019): https://pubmed.ncbi.nlm.nih.gov/31588918/

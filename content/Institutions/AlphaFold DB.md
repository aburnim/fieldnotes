---
aliases:
  - AlphaFold Protein Structure Database
  - AlphaFold DB
  - AFDB
tags: [institution]
---
> [!info] Info
> The AlphaFold Protein Structure Database (AFDB) provides open access to >200 million AI-predicted protein structure predictions. Developed as a partnership between [[EMBL-EBI]] and [[Google DeepMind]]. Launched July 2021 with ~300k structures; expanded to 214M+ by 2024. Uses AlphaFold v2.0 (2024 Nobel Prize in Chemistry to [[Demis Hassabis]] and [[John Jumper]]). Most recent update aligns with UniProt 2025_03 release. New collaboration with NVIDIA and Seoul National University added millions of protein complex predictions (March 2026).

> [!warning] The elephant in the room
> AlphaFold DB has fundamentally changed the structural biology landscape. The governance of predicted vs. experimental structures is THE emerging issue in the field. Any landscape document for Stephanie must address how AlphaFold DB interacts with the [[wwPDB]] ecosystem.


## People

| Name | Role | Affiliation |
|------|------|-------------|
| [[Sameer Velankar]] | PI (EMBL-EBI side) | [[PDBe (UK, EMBL-EBI)\|PDBe]] / [[EMBL-EBI]] |
| [[Mihaly Varadi]] | Project lead / data management | PDBe / EMBL-EBI |
| [[Sreenath Nair]] | Lead developer (API, infrastructure) | PDBe / EMBL-EBI |
| [[Jennifer Fleming]] | Lead (current papers) | PDBe / EMBL-EBI |
| [[Demis Hassabis]] | Co-lead (DeepMind side); 2024 Nobel Laureate | [[Google DeepMind]] |
| [[John Jumper]] | Lead scientist; 2024 Nobel Laureate | Google DeepMind |
| [[Ewan Birney]] | EMBL-EBI Director (institutional oversight) | EMBL-EBI |
| [[Gerard Kleywegt]] | Former PDBe lead (early AFDB papers) | EMBL-EBI (historical) |


## Funding
- Google DeepMind funds the AlphaFold Protein Structure Database
- Wellcome Trust (310300/Z/24/Z to [[Sameer Velankar]])
- BBSRC (BB/W008556/1)

## Key Relationships
- Hosted at [[EMBL-EBI]], same campus as [[PDBe (UK, EMBL-EBI)|PDBe]], [[EMDB]], [[EMPIAR]], [[ELIXIR]] Hub
- [[Sameer Velankar]] leads both AlphaFold DB and [[PDBe (UK, EMBL-EBI)|PDBe]] -- single person bridging predicted and experimental structures
- Data provider in [[3D-Beacons]] network
- Uses [[Mol*]] as its 3D viewer
- AlphaMissense pathogenicity predictions integrated (from DeepMind)
- Foldseek structural search integrated (from [[Martin Steinegger]], Seoul National University)
- Does NOT deposit into [[wwPDB]] PDB archive -- predicted structures remain separate from experimental structures. This governance boundary is a major ongoing discussion.

## Key Reference
Bertoni et al., NAR 54(D1), D358-D362 (2026). doi:10.1093/nar/gkaf1226
Varadi et al., NAR 50(D1), D439-D444 (2022)
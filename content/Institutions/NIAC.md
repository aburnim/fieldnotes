---
aliases:
  - NeXus International Advisory Committee
  - NIAC
  - NeXus data format
  - NeXus
tags: [institution]
---
> [!info] Info
> The NeXus International Advisory Committee (NIAC) supervises the development and maintenance of the NeXus common data format for neutron, X-ray, and muon science. NeXus is built on top of HDF5 and defines domain-specific rules for organizing experimental data within HDF5 files, plus a dictionary of standardized field names. NeXus is an international standard developed by scientists representing major facilities in Europe, Asia, Australia, and North America. The format serves both as a container for all beamline data and as application definitions for data exchange between programs.

> [!faq] Why NIAC matters for DiffUSE
> NeXus is the dominant data format at many synchrotron and neutron facilities where diffuse scattering data is collected. DiffUSE's data collection/processing pipeline (Mdx2) and any data standards work will need to reckon with NeXus format conventions. The NIAC governance model (facility-delegate voting, ratification of application definitions) is also a relevant precedent for DiffUSE's own data governance approach.


## Governance Structure
- **Constitution**: at most one voting representative per major neutron, synchrotron X-ray, or muon facility
- **Terms**: 3-year renewable, nominated by facility directors, approved by committee
- **Meetings**: biennial as satellite to NOBUGS conference; working meetings in intervening years
- **Voting**: simple majority at meetings; 2/3 response required for email votes
- **Open process**: all debates public; non-members encouraged to participate
- **Special Interest Groups**: appointed editors for instrument definitions and specialized uses

### Executive Officers (2-year terms)
- **Chair**: oversees deliberations
- **Executive Secretary**: coordinates meetings/debates (need not be member)
- **Technical Manager**: oversees NeXus API (need not be member)
- **Definition Release Manager**: oversees definitions/docs release (need not be member)


## Current Members

| Name | Facility | Country | Role |
|------|----------|---------|------|
| [[Aaron Brewster]] | [[Lawrence Berkeley Laboratory]] | USA | **Chair** |
| [[Sandor Brockhauser]] | Center for Materials Science Data (HU Berlin) | Germany | **Executive Secretary** |
| [[Peter Chang]] | [[Diamond Light Source]] | UK | **Documentation Release Manager** |
| [[Benjamin Watts]] | Swiss Light Source | Switzerland | |
| [[Herbert Bernstein]] | CIF | (non-facility) | |
| [[Thomas Caswell]] | Brookhaven National Laboratory / NSLS-II | USA | |
| [[Bjorn Clausen]] | Los Alamos National Laboratory | USA | |
| [[Heike Gorzig]] | Helmholtz Zentrum Berlin | Germany | |
| [[Pete Jemian]] | Advanced Photon Source | USA | |
| [[Raymond Osborn]] | Argonne National Laboratory | USA | (non-facility) |
| [[Wout de Nolf]] | European Synchrotron Radiation Facility | France | |
| [[Takahiro Matsumoto]] | SPring-8 | Japan | |
| [[Balazs Bago]] | Extreme Light Infrastructure | Czech Republic/Hungary/Romania | |
| [[Russ Berg]] | Canadian Light Source | Canada | |
| [[Majid Ounsy]] | Synchrotron Soleil | France | |
| [[Chen Zhang]] | Oak Ridge National Laboratory (SNS/HFIR) | USA | |
| [[Fabio Dall'Antonia]] | European XFEL | Germany | |
| [[Paul Millar]] | DESY | Germany | |
| [[Zdenek Matej]] | MAX IV | Sweden | |
| [[Fernan Saiz]] | ALBA | Spain | |
| [[Fredrik Bolmsten]] | ESS | Sweden | |


## Historical Origins
- June 1994: [[Mark Konnecke]] (PSI, Switzerland) proposed netCDF-based format at ISIS
- August 1994: [[Jon Tischler]] and [[Mitch Nelson]] (ORNL)
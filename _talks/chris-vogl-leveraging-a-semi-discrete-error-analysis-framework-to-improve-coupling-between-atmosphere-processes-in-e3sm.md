---
speakers:
  - Chris Vogl
name: "Leveraging a Semi-Discrete Error Analysis Framework to Improve Coupling Between Atmosphere Processes in E3SM"
categories:
  - Short Talks
hide: no
---
The Energy Exascale Earth System Model (E3SM), like other global climate models, seeks to solve a truly multiphysics problem that includes processes such as fluid flow, heat exchange, chemical reactions, and phase changes. Those processes are partitioned into individual models that, along with the associated numerical discretization, are each developed more-or-less independently of the others, which has resulted in process coupling that remains essentially a sequential splitting approach. Thus, this work leverages a semi-discrete error analysis framework to investigate the potential both of alternative coupling approaches in the literature and of new coupling approaches developed specifically to the software architecture of the E3SM atmosphere model (EAM). The analysis framework isolates the coupling error from that of the temporal and spatial discretization, avoiding the need to rederive error terms for each combination of coupling approach and temporal and/or spatial discretization present in EAM. By leveraging such analysis, an alternative coupling approach for aerosol processes has been developed that substantially improves dust lifetime simulation, which is crucial to reliable climate prediction. Both the improvement in aerosol process coupling and the progress on improving coupling between other atmosphere processes will be presented.

Prepared by LLNL under Contract DE-AC52-07NA27344. LLNL-ABS-840173.


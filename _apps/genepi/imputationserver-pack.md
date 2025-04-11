---
layout: application_pack
permalink: genepi/imputationserver-pack
title: Imputationserver - Starter Pack
website: https://imputationserver.sph.umich.edu
github: https://github.com/genepi/imputationserver2
description_short: This pack includes Imputationserver2 and the HapMap2 reference panel.
releases:
  - version: 2.0.7
    content:
      - version: 2.0.7
        url: genepi/imputationserver2@v2.0.7
        config:
          nextflow.profile: test,docker
      - version: 1.0.0
        url: https://imputationserver.sph.umich.edu/resources/ref-panels/imputationserver2-hapmap2.zip

authors:
  - name: Sebastian Schoenherr
    mail: sebastian.schoenherr@i-med.ac.at
    twitter: seppinho
    avatar: https://avatars2.githubusercontent.com/u/1942824?s=30
  - name: Lukas Forer
    mail: lukas.forer@i-med.ac.at
    twitter: lukfor
    avatar: https://avatars2.githubusercontent.com/u/210220?s=30

---

This server provides a free genotype imputation service. You can upload GWAS genotypes (VCF or 23andMe format) and receive phased and imputed genomes in return. Our server offers imputation from HapMap, 1000 Genomes (Phase 1 and 3), CAAPA and the updated Haplotype Reference Consortium (HRC version r1.1) panel.
[https://imputationserver.sph.umich.edu](https://imputationserver.sph.umich.edu)

In cooperation with the University of Michigan, Gonçalo Abecasis & Christian Fuchsberger.

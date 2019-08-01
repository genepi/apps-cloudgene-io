---
layout: app
title: Haplocheck
app_id: haplocheck
version: 1.0.4
last_update: 2019-08-01
website: https://mitoverse.i-med.ac.at
package_url: https://github.com/genepi/haplocheck/releases/download/v1.0.4/haplocheck.zip
description_short: mtDNA contamnation detection for whole genome and targed mtDNA sequencing studies.
source_url: https://github.com/genepi/haplocheck
category: app
authors:
  - name: Sebastian Schoenherr
    mail: sebastian.schoenherr@i-med.ac.at
    twitter: seppinho
    avatar: https://avatars2.githubusercontent.com/u/1942824?s=30
  - name: Hansi Weissensteiner
    mail: hansi.weissensteiner@i-med.ac.at
    avatar: http://www.gravatar.com/avatar/8280e95f36c6cac4cf5ca36afa0952e6?s=30
  - name: Lukas Forer
    mail: lukas.forer@i-med.ac.at
    twitter: lukfor
    avatar: https://avatars2.githubusercontent.com/u/210220?s=30    
---

Haplocheck is a contamination tool using the mtDNA phylogeny and has been integrated into the mitoverse mtDNA platform based on Cloudgene.


## Run Haplocheck locally

Using Cloudgene, the complete workflow can also be executed locally. The final report is located `outfolder/report`.

        curl -s install.cloudgene.io | bash -s 2.0.0-rc9
        ./cloudgene install https://github.com/genepi/haplocheck/releases/download/v1.0.2/haplocheck.zip
        ./cloudgene run haplocheck@1.0.2 --files <input-files> --output <folder>  

## Input File Formats
Haplocheck accepts BAM/CRAM files, vcf.gz as an input.

## Output File Formats
Haplocheck genereates a text file including summary statistics for each sample and a contamination status. It also provides a graphical report which can shared with collaborators.    

## Documentation
Please click [here](https://mitoverse.readthedocs.io/en/latest/) to get the latest documentation.

## Blog
Check out our [blog](http://haplogrep.uibk.ac.at/blog/) regarding mtDNA topics.

## Contact
[Hansi Weissensteiner](mailto:hansi.weissensteiner@i-med.ac.at) ([@haansi](https://twitter.com/whansi)) and [Sebastian Schoenherr](mailto:sebastian.schoenherr@i-med.ac.at) ([@seppinho](https://twitter.com/seppinho)); Division of Genetic Epidemiology, Medical University of Innsbruck;

# Bioinformatics Open-Source Conference (BOSC) 2021 - POSTER

## Putting standards into practice - ontologizing the Canadian COVID Genomics Network specification

### Rhiannon Cameron, Damion Dooley, Emma Griffiths, Sarah Savić Kallesøe, William Hsiao

**Affiliation:** Hsiao Public Health Bioinformatics Laboratory, Simon Fraser University, Burnaby, BC, Canada

_Now known as: Centre for Infectios Disease Genomics and One Health_

---

**Event Website:** https://www.open-bio.org/events/bosc-2021/

**Poster Abstract:** https://www.iscb.org/cms_addon/conferences/ismbeccb2021/posters.php?track=BOSC&session=E#search

---
**CanCOGeN Specification**
- Website: https://github.com/Public-Health-Bioinformatics/DataHarmonizer/wiki/CanCOGeN-Contextual-Data-Specification

- Specification TSV: https://github.com/Public-Health-Bioinformatics/DataHarmonizer/blob/master/template/canada_covid19/data.tsv

- License: MIT License

**GenEpiO** 
- Website: https://genepio.org/

- Source Code: https://github.com/GenEpiO/genepio

- License: CC BY 3.0

Sequencing viral genomes and collecting associated contextual data is key to the
SARS-CoV-2 pandemic public health response. However, variation in contextual data across
health regions often results in data sets that are small and/or difficult to compare due to
variations in data structure, format, and values. To resolve this issue and improve virus
surveillance in Canada, the Canadian COVID Genomics Network (CanCOGeN) [VirusSeq](https://www.genomecanada.ca/en/cancogen/cancogen-virusseq) has
developed a data specification, fine tuned for SARS-CoV-2 and public health, that
incorporates existing standards. Working openly and collaboratively with Open Biological
and Biomedical Ontologies Foundry ([OBOF](http://www.obofoundry.org/)) domain ontologies, specification fields and
picklist values are being integrated into the open-source OBOF Genomic Epidemiology
Ontology (GenEpiO) to provide an interoperable and controlled vocabulary that is
responsive to the dynamic needs of different stakeholders. The specification contains 133
fields, structured according to Linked data Modeling Language ([LinkML](https://github.com/linkml/linkml)) classes and
relations ([CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)), and 1043 terms which we obtain from or collaborate on with
OBOF domain ontologies. We seek to integrate terminology that both reflects the needs of
COVID-19 surveillance and interoperable data sharing, while simultaneously creating a
semantic model with nuanced query capabilities for downstream tool development.

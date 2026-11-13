# Swedish MS Registry (SMSReg)

[Back to overview](../README.md) · Registry website: [Svenska neuroregister (neuroreg.se)](https://neuroreg.se/)

Nationwide Swedish quality registry of people with MS, part of the Swedish Neuro Registries, with the disease course
(RRMS, SPMS, PPMS) recorded by the treating clinician at each hospital visit [[1]](#r1) [[2]](#r2).

## Extracts

| Extract | Extraction date | People with MS | Hospital visits | Source |
|---|---|---:|---:|---|
| SMSReg-2022 | 19 December 2022 | 22,748 | 197,227 | [[3]](#r3) [[4]](#r4) |
| SMSReg-2025 | 21 February 2025 | 24,441 | 228,192 | [[4]](#r4) |

## Curated datasets from previous work

| Dataset | Individuals | Hospital visits | Use | Source |
|---|---:|---:|---|---|
| SMSReg-2022 after quality control, PPMS excluded | 14,382 | 113,784 | Development of the published conformal prediction model | [[4]](#r4) |
| SMSReg-2025 after quality control, PPMS excluded | 19,004 | 158,722 |  | [[4]](#r4) |
| SMSReg-2025, visits not used in SMSReg-2022 model development | 15,719 | 45,077 | Prospective validation | [[4]](#r4) |
| SMSReg after HARMONISE curation | 15,579 | 127,720 | Cross-registry harmonisation with MSBase | [[5]](#r5) |

Quality control removed duplicates and records missing EDSS, date of birth, disease course at the visit or onset date [[4]](#r4).

## Role in this project

| Item | Details |
|---|---|
| Aims | Main supervised development for Aims 1 and 2; internal testing and chronology sensitivity analyses |
| Patients used for RRMS/SPMS and CDW models | RRMS and SPMS only |
| PPMS | Self-supervised pretraining only |
| Exclusions | Participants linked to [RIFUND-MS / RIDOSE-MS](RIFUND-RIDOSE.md) are excluded from Aim 1 and 2 development |

## Harmonised clinical variables used in previous work [[5]](#r5)

| Variable | Description |
|---|---|
| Diagnosis age | Age at diagnosis |
| EDSS score | EDSS recorded at the hospital visit |
| Age at visit | Age when EDSS was assessed |
| Sex | Patient's sex |
| Diagnosis year | Year of MS diagnosis |
| No treatment | No treatment at this visit |
| First-line DMT | First-line disease-modifying therapy at this visit |
| Second-line DMT | Second-line disease-modifying therapy at this visit |
| Stem cell treatment | Previous haematopoietic stem cell transplantation |

## Ethics

Swedish Ethical Review Authority, Dnr 2021-00702, 2024-07442-02 and 2025-00541-02. Data are provided without
direct identifiers and the researchers have no access to the re-identification key.

## References

<a id="r1"></a>1. Andersen O. From the Gothenburg cohort to the Swedish multiple sclerosis registry. *Acta Neurol Scand.* 2012;126(Suppl 195):13–19. [doi:10.1111/ane.12023](https://doi.org/10.1111/ane.12023)

<a id="r2"></a>2. Hillert J, Stawiarz L. The Swedish MS registry: clinical support tool and scientific resource. *Acta Neurol Scand.* 2015;132(Suppl 199):11–19. [doi:10.1111/ane.12425](https://doi.org/10.1111/ane.12425) · [PubMed 26046553](https://pubmed.ncbi.nlm.nih.gov/26046553/)

<a id="r3"></a>3. Sreenivasan AP, et al. Conformal prediction enables disease course prediction and allows individualized diagnostic uncertainty in multiple sclerosis. *NPJ Digit Med.* 2025;8:224. [doi:10.1038/s41746-025-01616-z](https://doi.org/10.1038/s41746-025-01616-z) · [PubMed 40275055](https://pubmed.ncbi.nlm.nih.gov/40275055/) · Tool: [MSP-Tracker](https://msp-tracker.serve.scilifelab.se/)

<a id="r4"></a>4. Sreenivasan AP, Noui Y, Erngren I, Spjuth O, Burman J, Kultima K. Prospective validation of an uncertainty-aware machine learning model for secondary progressive multiple sclerosis classification. medRxiv preprint, 2026 (under revision). [doi:10.64898/2026.10.07.26364939](https://doi.org/10.64898/2026.10.07.26364939)

<a id="r5"></a>5. Sreenivasan AP, et al. HARMONISE: an uncertainty-aware framework for harmonising disease-course predictions across international clinical registries. Manuscript.

# PanPATH

**Patient-state-aware clinical reasoning for streamlining pancreatic diagnostic pathways**

PanPATH is a research framework for large language model (LLM)-assisted sequential diagnosis in patients with suspected pancreatic tumors. It adapts diagnostic reasoning and examination selection to evolving patient information while considering the potential burden of further testing.

## Overview

- **Patient-state-aware reasoning:** Updates diagnostic context as clinical evidence becomes available.
- **Knowledge-supported decisions:** Integrates relevant clinical resources and prior diagnostic experience.
- **Burden-conscious examination selection:** Considers diagnostic value alongside temporal, safety, and financial factors.
- **Retrospective evaluation:** Supports replay and assessment of diagnostic pathways using structured clinical records.

## Getting started

The main entry point is `main_v9_TTD.py`.

```bash
python main_v9_TTD.py --help
```

Running the pipeline requires the accompanying project modules, an appropriate configuration file (`configs/setting.yaml`), configured LLM access, and authorized structured clinical data. Runtime options are defined in the main script.

## Outputs

Depending on the configuration, PanPATH generates diagnostic replay records, patient-level evaluation summaries, and computational usage statistics.

## Data and responsible use

Clinical data are subject to institutional access and privacy requirements. Use only appropriately authorized, de-identified data. PanPATH is intended for research purposes and is **not validated for autonomous clinical use**.

## Citation

Manuscript in preparation. Citation details will be provided following publication.

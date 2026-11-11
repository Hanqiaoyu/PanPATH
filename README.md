# PanPATH

**Patient-state-aware clinical reasoning for streamlining pancreatic diagnostic pathways**

PanPATH is a framework designed to streamline sequential diagnostic workflows for patients with suspected pancreatic tumors. It adapts diagnostic reasoning and examination selection to evolving patient information while considering the potential burden of further testing.

## Overview

- **Patient-state-aware reasoning** 
- **Evidence-supported decisions**
- **Burden-conscious examination selection** 
- **Retrospective evaluation** 

## Getting started

The main entry point is `main.py`.

```bash
python main.py --help
```

Running the pipeline requires the accompanying project modules, an appropriate configuration file (`configs/setting.yaml`), configured LLM access, and authorized structured clinical data. Runtime options are defined in the main script.

## Outputs

Depending on the configuration, PanPATH generates diagnostic replay records, patient-level evaluation summaries, and computational usage statistics.

## Data and responsible use

Clinical data are subject to institutional access and privacy requirements. Use only appropriately authorized, de-identified data. PanPATH is intended for research purposes and is **not validated for autonomous clinical use**.

## Citation

Manuscript in preparation. Citation details will be provided following publication.

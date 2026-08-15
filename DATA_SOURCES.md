# Data sources and reconstruction notes

The original R Markdown references files that are not distributed in this portfolio repository. The rendered PDF is retained as the historical result.

| Expected file | Role in the analysis | Source described by the project |
| --- | --- | --- |
| `NG2_N.XLS` | Henry Hub natural-gas futures prices. | EIA natural-gas data cited in the report. |
| `USC00218450.csv` | Monthly average temperature for the University of Minnesota St. Paul station. | GSOM/NCEI station data cited in the report. |
| `NG_MOVE_IMPC_S1_M.xlsx` | United States natural-gas imports. | EIA natural-gas data cited in the report. |
| `NG_STOR_SUM_A_EPG0_SAT_MMCF_M.xlsx` | United States natural-gas storage. | EIA natural-gas data cited in the report. |
| `bib.bib` | Bibliographic records used to render citations. | References listed in the submitted PDF. |

## Reconstruction guidance

1. Obtain authorized versions of each series directly from the relevant provider.
2. Preserve the filenames above or update the R Markdown paths in a separate working copy.
3. Verify units, observation frequency, date coverage, missing-value conventions, and revision vintage.
4. Use the submitted PDF as the reference for the intended sample and model narrative.

Data-provider interfaces and series definitions may have changed since the project was submitted. Reconstructed results may therefore differ from the saved report.

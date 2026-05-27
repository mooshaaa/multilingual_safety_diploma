# multilingual_safety_diploma

This is a repository of the bachelor thesis titled "Investigating Safety and Multilinguality in Large Language Models through the Analysis of Internal Representations."

The repository is organized as follows:

```
multilingual_safety_diploma/
├── README.md                          # This file
├── data/
│   ├── README.md                      # Data documentation
│   └── sorry_bench_russian_prompts.json
├── code/
│   ├── logit_lens_analysis.py         # Stage 1: Layer-by-layer analysis
│   ├── safety_steering.py             # Stage 2: Steering experiments
│   ├── evaluation.py                  # Safety evaluation utilities
│   └── utils.py                       # Helper functions
├── results/
│   ├── stage1_logit_lens/
│   │   ├── safety_scores_by_layer.csv # Main results
│   │   ├── language_ratio_by_layer.csv
│   │   └── visualizations/            # Plots and figures
│   ├── stage2_steering/
│   │   ├── steering_results.csv       # Main results
│   │   ├── direction_analysis.csv
│   │   └── visualizations/
│   └── tables/                        # Publication-ready tables
├── requirements.txt                   # Dependencies
└── thesis/                            # Full thesis document (optional)
```
! Because this is a safety-related study, the dataset contains potentially harmful content.  Be careful.

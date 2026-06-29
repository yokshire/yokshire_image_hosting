# Current Paper Assets

This file records the figure assets that are allowed for the active Notion paper page.
The broader historical record remains in `manifest.json`; this page is the short
operator checklist for avoiding stale or misleading figures.

Notion page:

- page id: `3524c48e-4da3-81b5-8d22-c7d73ae6e455`
- page url: `https://app.notion.com/p/3524c48e4da381b58d22c7d73ae6e455`

## Current Figures

| Figure | Asset id | Hosted path | Local source or renderer |
| --- | --- | --- | --- |
| Figure 4-a | `fig_3_2b_stateprep_matched_reps_q5_seed10_ryrz_cx_hinit_v1` | `figures/fig_3_2b_stateprep_matched_reps_q5_seed10_ryrz_cx_hinit_v1.png` | `experiments/matched_stateprep_reps/render_mainstream_ansatz_figures.py` |
| Figure 4-b | `fig_3_2c_matched_stateprep_ansatz_unit_ryrz_cx_hinit_v1` | `figures/fig_3_2c_matched_stateprep_ansatz_unit_ryrz_cx_hinit_v1.png` | `experiments/matched_stateprep_reps/render_mainstream_ansatz_figures.py` |
| Figure 5 | `fig_3_5_matched_reps8_learning_histograms_seed10_ryrz_cx_hinit_trace3000_v2` | `figures/fig_3_5_matched_reps8_learning_histograms_seed10_ryrz_cx_hinit_trace3000_v2.png` | `experiments/matched_stateprep_reps/render_mainstream_ansatz_figures.py` |
| Figure 6 | `fig_3_6_theta_matched_reps8_learning_histograms_seed10_ryrz_cx_hinit_trace3000_v2` | `figures/fig_3_6_theta_matched_reps8_learning_histograms_seed10_ryrz_cx_hinit_trace3000_v2.png` | `experiments/matched_stateprep_reps/render_mainstream_ansatz_figures.py` |

Figure 4-a through Figure 6 use the manuscript-current state-preparation ansatz:

- initialization: Hadamard
- ansatz: `TwoLocal(ry, rz)`
- entanglement: circular `cx`
- seeds: `0..9`
- Figure 5 and Figure 6 learning traces are rendered only through iteration 3000.

## Do Not Use

| Asset id | Status | Reason |
| --- | --- | --- |
| `fig_3_5_matched_reps8_learning_histograms_seed10_v2` | removed | Generated from the pre-mainstream `rx/rz/ry` full-entanglement run. It does not match the real-backend ansatz family. |
| `fig_3_6_theta_matched_reps8_learning_histograms_seed10_v2` | removed | Generated from the pre-mainstream `rx/rz/ry` full-entanglement run. It does not match the real-backend ansatz family. |
| `fig_3_5_matched_reps8_learning_histograms_seed10_ryrz_cx_hinit_v1` | superseded | Same ansatz family, but the trace is not clipped to the current 3000-iteration presentation. |
| `fig_3_6_theta_matched_reps8_learning_histograms_seed10_ryrz_cx_hinit_v1` | superseded | Same ansatz family, but the trace is not clipped to the current 3000-iteration presentation. |

## Update Rules

1. Regenerate current Figure 4-a through Figure 6 with:

   ```powershell
   python experiments\matched_stateprep_reps\render_mainstream_ansatz_figures.py
   ```

2. Do not call the deprecated renderers below; they intentionally exit with an error:

   ```powershell
   python experiments\matched_stateprep_reps\render_figure_5_matched_reps8.py
   python experiments\matched_stateprep_reps\render_figure_6_theta_matched_reps8.py
   ```

3. Before inserting a figure into Notion, confirm the asset is marked current here
   and active in `manifest.json`.
4. When replacing a figure, update `manifest.json`, this file, and the local
   `paper_current/current_assets_manifest.json` together.
5. Keep GitHub Pages under `https://yokshire.github.io/yokshire_image_hosting/figures/`
   as the canonical delivery source for Notion figures.

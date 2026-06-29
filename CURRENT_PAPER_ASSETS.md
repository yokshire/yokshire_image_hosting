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
| Figure X-1 | `cross_check_fig_intro_xcom_h2o_interaction_coefficients_6mev` | `figures/cross_check_fig_intro_xcom_h2o_interaction_coefficients_6mev_v1.png` | `final_figure/method_support/xcom_h2o_6mev/generate_xcom_h2o_interaction_coefficients.py` |
| Figure 1 | `fig_3_1_scattering_path_Dl_notation` | `figures/fig_3_1_scattering_path_Dl_notation.jpg` | manual geometry notation render |
| Figure 3 | `fig_3_3_second_collision_joint_probability_maps_title_only` | `figures/fig_3_3_second_collision_joint_probability_maps_title_only.png` | `experiments/render_figure_3_joint_probability_maps.py` |
| Figure 4-a | `fig_3_2b_stateprep_matched_reps_q5_seed10_ryrz_cx_hinit_whisker_v2` | `figures/fig_3_2b_stateprep_matched_reps_q5_seed10_ryrz_cx_hinit_whisker_v2.png` | `experiments/matched_stateprep_reps/render_mainstream_ansatz_figures.py` |
| Figure 4-b | `fig_3_2c_matched_stateprep_ansatz_unit_ryrz_cx_hinit_v1` | `figures/fig_3_2c_matched_stateprep_ansatz_unit_ryrz_cx_hinit_v1.png` | `experiments/matched_stateprep_reps/render_mainstream_ansatz_figures.py` |
| Figure 5 | `fig_3_5_matched_reps8_learning_histograms_seed10_ryrz_cx_hinit_trace3000_v2` | `figures/fig_3_5_matched_reps8_learning_histograms_seed10_ryrz_cx_hinit_trace3000_v2.png` | `experiments/matched_stateprep_reps/render_mainstream_ansatz_figures.py` |
| Figure 6 | `fig_3_6_theta_matched_reps8_learning_histograms_seed10_ryrz_cx_hinit_trace3000_v2` | `figures/fig_3_6_theta_matched_reps8_learning_histograms_seed10_ryrz_cx_hinit_trace3000_v2.png` | `experiments/matched_stateprep_reps/render_mainstream_ansatz_figures.py` |
| Figure 21 | `fig_4_6_method_selection_summary_v1` | `figures/fig_4_6_method_selection_summary_v1.png` | `experiments/section4_method_selection/render_method_selection_summary.py` |
| Figure 22 | `fig_4_6b_yonsei_hn_chebyshev_real_backend_v1` | `figures/fig_4_6b_yonsei_hn_chebyshev_real_backend_v1.png` | `experiments/real_backend_yonsei/render_yonsei_backend_summary.py` |
| Figure 23 | `fig_4_6d_yonsei_noise_correction_recovery_v1` | `figures/fig_4_6d_yonsei_noise_correction_recovery_v1.png` | `experiments/real_backend_yonsei/render_yonsei_noise_correction_recovery.py` |
| Figure 24 | `fig_4_6e_yonsei_aer_mitigation_probe_v1` | `figures/fig_4_6e_yonsei_aer_mitigation_probe_v1.png` | `experiments/real_backend_yonsei/render_yonsei_mitigation_probe.py` |
| Figure 25 | `fig_4_6f_yonsei_real_backend_mitigation_result_v1` | `figures/fig_4_6f_yonsei_real_backend_mitigation_result_v1.png` | `experiments/real_backend_yonsei/render_yonsei_real_mitigation_result.py` |

Figure 4-a through Figure 6 use the manuscript-current state-preparation ansatz:

- initialization: Hadamard
- ansatz: `TwoLocal(ry, rz)`
- entanglement: circular `cx`
- seeds: `0..9`
- Figure 5 and Figure 6 learning traces are rendered only through iteration 3000.

Figure 22 through Figure 25 must remain consistent with the same H + TwoLocal(ry, rz; circular CX), reps=8 HN-MLP Chebyshev state-preparation circuit. Raw Yonsei validation uses 4096 shots and jobs `d900llg6c68s73ahft4g`, `d900o3propqc738d5cj0`, `d900vq8pknjs73a1ppv0`; the real mitigated run uses job `d90csl6mvj5c73ej20hg`.

## Do Not Use

| Asset id | Status | Reason |
| --- | --- | --- |
| `fig_3_5_matched_reps8_learning_histograms_seed10_v2` | removed | Generated from the pre-mainstream `rx/rz/ry` full-entanglement run. It does not match the real-backend ansatz family. |
| `fig_3_6_theta_matched_reps8_learning_histograms_seed10_v2` | removed | Generated from the pre-mainstream `rx/rz/ry` full-entanglement run. It does not match the real-backend ansatz family. |
| `fig_3_2b_stateprep_matched_reps_q5_seed10_ryrz_cx_hinit_v1` | superseded | Same image lineage as Figure 4-a, but Notion uses the explicit `whisker_v2` filename. |
| `fig_3_5_matched_reps8_learning_histograms_seed10_ryrz_cx_hinit_v1` | superseded | Same ansatz family, but the trace is not clipped to the current 3000-iteration presentation. |
| `fig_3_6_theta_matched_reps8_learning_histograms_seed10_ryrz_cx_hinit_v1` | superseded | Same ansatz family, but the trace is not clipped to the current 3000-iteration presentation. |

## Reconciliation Notes

- Figure 2 is currently fetched from Notion as `fig_3_2_depth_dose_benchmark_exact_q5_highres.png`, while `manifest.json` marks `fig_3_2_depth_dose_benchmark_exact_q5_highres_v2.png` as the active replacement. Resolve this deliberately before treating Figure 2 as provenance-clean.

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

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
| Figure 1 | `cross_check_fig_intro_xcom_h2o_interaction_coefficients_6mev` | `figures/cross_check_fig_intro_xcom_h2o_interaction_coefficients_6mev_v1.png` | `final_figure/method_support/xcom_h2o_6mev/generate_xcom_h2o_interaction_coefficients.py` |
| Figure 2 | `fig_x2_qmci_workflow_intro_v1` | `figures/fig_x2_qmci_workflow_intro_v1.png` | workflow schematic SVG/PNG render |
| Figure 3 | `fig_3_1_scattering_path_Dl_notation` | `figures/fig_3_1_scattering_path_Dl_notation.jpg` | manual geometry notation render |
| Figure 4 | `fig_3_2_depth_dose_benchmark_exact_q5_highres_v3` | `figures/fig_3_2_depth_dose_benchmark_exact_q5_highres_v3.png` | `experiments/matched_stateprep_reps/render_figure_2ab_labels.py` |
| Figure 5 | `fig_3_3_second_collision_joint_probability_maps_title_only` | `figures/fig_3_3_second_collision_joint_probability_maps_title_only.png` | `experiments/render_figure_3_joint_probability_maps.py` |
| Figure 6 | `fig_3_2c_matched_stateprep_ansatz_unit_ryrz_cx_hinit_v2` | `figures/fig_3_2c_matched_stateprep_ansatz_unit_ryrz_cx_hinit_v2.png` | `experiments/matched_stateprep_reps/render_mainstream_ansatz_figures.py` |
| Figure 7 | `fig_3_10_qae_qmci_mode_estimator_block_v5` | `figures/fig_3_10_qae_qmci_mode_estimator_block_v5.png` | Qiskit `mpl` circuit rendering |
| Figure 8-a | `fig_3_12_fft_reconstruction_Gu` | `figures/fig_3_12_fft_reconstruction_Gu.png` | `final_figure/refer_pre_paper/qae_fft_1d_context/fft_reconstruction_Gu.png` |
| Figure 8-b | `fig_3_12_chebyshev_reconstruction_Gq` | `figures/fig_3_12_chebyshev_reconstruction_Gq.png` | `notion_github_hosted_figures/fig_3_12_chebyshev_reconstruction_Gq.png` |
| Figure 9 | `fig_4_1_first_compton_local_deposition_geant4_6mev_water_500k_depth170_v3` | `figures/fig_4_1_first_compton_local_deposition_geant4_6mev_water_500k_depth170_v3.png` | `experiments/geant4_depthdose_fig14/run_geant4_first_compton_depthdose.py` |
| Figure 10 | `fig_4_1b_second_compton_fixed_lambda_geant4_6mev_water_500k_depth170_v2` | `figures/fig_4_1b_second_compton_fixed_lambda_geant4_6mev_water_500k_depth170_v2.png` | `experiments/geant4_depthdose_fig14/run_geant4_second_compton_fixed_lambda_depthdose.py` |
| Figure 11 | `fig_3_14_q50_stateprep_fft_chebyshev_dose_seed10_v2` | `figures/fig_3_14_q50_stateprep_fft_chebyshev_dose_seed10_v2.png` | `experiments/stateprep_qmci_seed10/render_figures_12_13_stateprep_qmci.py` |
| Figure 12 | `fig_3_13_q55_stateprep_fft_chebyshev_dose_profile_seed10_v2` | `figures/fig_3_13_q55_stateprep_fft_chebyshev_dose_profile_seed10_v2.png` | `experiments/stateprep_qmci_seed10/render_figure_13_q55_dose_profile.py` |
| Figure 13 | `fig_3_2b_stateprep_matched_reps_q5_seed10_ryrz_cx_hinit_whisker_v3` | `figures/fig_3_2b_stateprep_matched_reps_q5_seed10_ryrz_cx_hinit_whisker_v3.png` | `experiments/matched_stateprep_reps/render_mainstream_ansatz_figures.py` |
| Figure 14 | `fig_3_5_matched_reps8_learning_histograms_seed10_ryrz_cx_hinit_trace3000_v4` | `figures/fig_3_5_matched_reps8_learning_histograms_seed10_ryrz_cx_hinit_trace3000_v4.png` | `experiments/matched_stateprep_reps/render_mainstream_ansatz_figures.py` |
| Figure 15 | `fig_3_6_theta_matched_reps8_learning_histograms_seed10_ryrz_cx_hinit_trace3000_v4` | `figures/fig_3_6_theta_matched_reps8_learning_histograms_seed10_ryrz_cx_hinit_trace3000_v4.png` | `experiments/matched_stateprep_reps/render_mainstream_ansatz_figures.py` |
| Figure 16 | `fig_3_9_stateprep_main_channel_integral_convergence_reps8_iter10000_v3` | `figures/fig_3_9_stateprep_main_channel_integral_convergence_reps8_iter10000_v3.png` | `experiments/stateprep_qubit_scaling_figure9/render_main_channel_integral_convergence.py` |
| Figure 17 | `fig_4_6g_yonsei_compact_backend_feasibility_v2` | `figures/fig_4_6g_yonsei_compact_backend_feasibility_v2.png` | `experiments/real_backend_yonsei/render_yonsei_compact_backend_feasibility.py` |
| Figure 18 | `fig_4_7_hn_chebyshev_qae_rmse_three_methods_v5` | `figures/fig_4_7_hn_chebyshev_qae_rmse_three_methods_v5.png` | `experiments/qae_rmse_three_methods_20260629/run_hn_chebyshev_qae_rmse_three_methods_v5.py` |

Figure 6, Figure 13, Figure 14, and Figure 15 use the manuscript-current state-preparation ansatz:

- initialization: Hadamard
- ansatz: `TwoLocal(ry, rz)`
- entanglement: circular `cx`
- seeds: `0..9`

Figure 17 must remain consistent with the same H + TwoLocal(ry, rz; circular CX), reps=8 HN-MLP Chebyshev state-preparation circuit. Raw Yonsei validation uses 4096 shots and jobs `d900llg6c68s73ahft4g`, `d900o3propqc738d5cj0`, `d900vq8pknjs73a1ppv0`; the real mitigated run uses job `d90csl6mvj5c73ej20hg`.

## Do Not Use

| Asset id | Status | Reason |
| --- | --- | --- |
| `fig_3_5_matched_reps8_learning_histograms_seed10_v2` | removed | Generated from the pre-mainstream `rx/rz/ry` full-entanglement run. It does not match the real-backend ansatz family. |
| `fig_3_6_theta_matched_reps8_learning_histograms_seed10_v2` | removed | Generated from the pre-mainstream `rx/rz/ry` full-entanglement run. It does not match the real-backend ansatz family. |
| `fig_3_2b_stateprep_matched_reps_q5_seed10_ryrz_cx_hinit_v1` | superseded | Same image lineage as Figure 4-a, but Notion uses the explicit `whisker_v2` filename. |
| `fig_3_5_matched_reps8_learning_histograms_seed10_ryrz_cx_hinit_v1` | superseded | Same ansatz family, but the trace is not clipped to the current 3000-iteration presentation. |
| `fig_3_6_theta_matched_reps8_learning_histograms_seed10_ryrz_cx_hinit_v1` | superseded | Same ansatz family, but the trace is not clipped to the current 3000-iteration presentation. |

## Reconciliation Notes

- Figure captions in the active Notion page were renumbered on 2026-06-30 so the manuscript-visible sequence runs Figure 1 through Figure 18 without duplicate Figure 13/17 references.
- `q50` and `q55` remain internal filename/source-path tags only. Manuscript-visible text uses 5-qubit and 5+5 qubits.

## Update Rules

1. Regenerate current Figure 6, Figure 13, Figure 14, and Figure 15 with:

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

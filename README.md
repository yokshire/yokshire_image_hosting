# Research Figure Hosting Assets

This repository hosts figure assets for research documentation and manuscript
drafting. The `figures/` directory contains the original PNG/JPG assets used by
Notion and manuscript pages.

Preferred delivery URLs:

- GitHub Pages: `https://yokshire.github.io/yokshire_image_hosting/figures/...`
- GitHub raw fallback: `https://github.com/yokshire/yokshire_image_hosting/raw/main/figures/...`

The `notion_github_hosted_figures/` directory contains SVG wrappers generated
from the same local raster figures. These wrappers were kept as a fallback for
text-based upload workflows.

| slug | source | status | upload path |
| --- | --- | --- | --- |
| `fig_3_1_scattering_path_Dl_notation` | `final_figure/refer_pre_paper/notation_context/scattering_path_Dl_notation.jpg` | OK | `notion_github_hosted_figures/fig_3_1_scattering_path_Dl_notation.svg` |
| `fig_3_2_depth_dose_analytic_vs_mc` | `final_figure/refer_pre_paper/notation_context/depth_dose_Dz_analytic_vs_MC.jpg` | OK | `notion_github_hosted_figures/fig_3_2_depth_dose_analytic_vs_mc.svg` |
| `fig_3_2_depth_dose_stateprep_comparison` | combined draft from Figure 2-a/2-b sources | superseded | `figures/fig_3_2_depth_dose_stateprep_comparison.png` |
| `fig_3_2a_depth_dose_benchmark` | analytic/sample-only draft | superseded | `figures/fig_3_2a_depth_dose_benchmark.png` |
| `fig_3_2a_depth_dose_benchmark_exact_q5` | `*/final_data_analysis/observables/raw/1d/q50/theta/dose_curve.csv` | superseded | `figures/fig_3_2a_depth_dose_benchmark_exact_q5.png` |
| `fig_3_2_depth_dose_benchmark_exact_q5_highres` | `*/final_data_analysis/observables/raw/1d/q50/theta/dose_curve.csv` | OK | `figures/fig_3_2_depth_dose_benchmark_exact_q5_highres.png` |
| `fig_3_2b_stateprep_kl_comparison` | mixed q5/q60 comparison draft | superseded | `figures/fig_3_2b_stateprep_kl_comparison.png` |
| `fig_3_2b_stateprep_kl_comparison_q5` | earlier mixed qGAN/HN/initialize 5-qubit comparison | superseded | `figures/fig_3_2b_stateprep_kl_comparison_q5.png` |
| `fig_3_2b_stateprep_matched_reps_q5` | Figure 4-a matched q50 reps diagnostic from `experiments/matched_stateprep_reps/final_qgan_ansatz_runs/*/matched_reps_summary.csv`; `최종데이터/final_data_analysis/raw/1d/q50/cos_q/target_probs.npy` | superseded | `figures/fig_3_2b_stateprep_matched_reps_q5.png` |
| `fig_3_2b_stateprep_matched_reps_q5_label_v2` | Figure 4-a cache-busting asset with the target/ansatz label box below the plot area | superseded | `figures/fig_3_2b_stateprep_matched_reps_q5_label_v2.png` |
| `fig_3_2b_stateprep_matched_reps_q5_seed10` | Figure 4-a seed10 matched q50 reps diagnostic with lower method label and reduced full-width info label | superseded | `figures/fig_3_2b_stateprep_matched_reps_q5_seed10.png` |
| `fig_3_2b_stateprep_matched_reps_q5_seed10_v2` | Figure 4-a seed10 matched q50 reps diagnostic with a two-line full-width info label | OK | `figures/fig_3_2b_stateprep_matched_reps_q5_seed10_v2.png` |
| `fig_3_2c_matched_stateprep_ansatz_unit` | Figure 4-b Qiskit `mpl` rendering of the matched H + TwoLocal(rx, rz, ry; full CZ) reps-unit ansatz used for qGAN and HN-MLP | superseded | `figures/fig_3_2c_matched_stateprep_ansatz_unit.png` |
| `fig_3_2c_matched_stateprep_ansatz_unit_upright_v3` | Figure 4-b cache-busting Qiskit `mpl` rendering with q0-to-q4 order preserved and no old in-image title/subtitle | OK | `figures/fig_3_2c_matched_stateprep_ansatz_unit_upright_v3.png` |
| `fig_3_2d_qgan_hn_mlp_qubit_integral_convergence` | Matched q50 reps=8 qGAN/HN-MLP distributions coarse-grained by data-qubit resolution | superseded | `figures/fig_3_2d_qgan_hn_mlp_qubit_integral_convergence.png` |
| `fig_3_2d_qgan_hn_mlp_qubit_integral_convergence_v2` | Figure 9 two-panel qGAN/HN-MLP data-qubit convergence with target-midpoint baseline and ten-seed min-max error ranges | superseded | `figures/fig_3_2d_qgan_hn_mlp_qubit_integral_convergence_v2.png` |
| `fig_3_2d_qgan_hn_mlp_qubit_integral_convergence_v3` | Figure 9 draft qGAN/HN-MLP data-qubit convergence using the superseded target-midpoint baseline | superseded | `figures/fig_3_2d_qgan_hn_mlp_qubit_integral_convergence_v3.png` |
| `fig_3_2d_qgan_hn_mlp_qubit_integral_convergence_v4` | Current Figure 9 original two-panel qGAN/HN-MLP data-qubit convergence with the checked continuous integral reference `I_ref=0.289768` and recomputed error panel | OK | `figures/fig_3_2d_qgan_hn_mlp_qubit_integral_convergence_v4.png` |
| `fig_3_9_qae_fft_data_qubit_convergence_v1` | Temporary QAE-cell-derived diagnostic; not used as the current Notion Figure 9 | superseded | `figures/fig_3_9_qae_fft_data_qubit_convergence_v1.png` |
| `fig_3_5_matched_reps8_learning_histograms` | Figure 5 matched reps=8 qGAN/HN-MLP KL learning trace and target-distribution histogram diagnostic | superseded | `figures/fig_3_5_matched_reps8_learning_histograms.png` |
| `fig_3_5_matched_reps8_learning_histograms_seed10` | Figure 5 seed10 matched reps=8 qGAN/HN-MLP learning and histogram diagnostic with selected seed bars plus 10-seed range | OK | `figures/fig_3_5_matched_reps8_learning_histograms_seed10.png` |
| `fig_3_6_theta_matched_reps8_learning_histograms` | Figure 6 matched reps=8 qGAN/HN-MLP KL learning trace and theta-target histogram diagnostic for Chebyshev loading | superseded | `figures/fig_3_6_theta_matched_reps8_learning_histograms.png` |
| `fig_3_6_theta_matched_reps8_learning_histograms_legend_v2` | Figure 6 cache-busting asset with lower-panel labels moved out of the histogram plots | superseded | `figures/fig_3_6_theta_matched_reps8_learning_histograms_legend_v2.png` |
| `fig_3_6_theta_matched_reps8_learning_histograms_seed10` | Figure 6 seed10 theta-space matched reps=8 diagnostic with selected seed bars plus 10-seed range | OK | `figures/fig_3_6_theta_matched_reps8_learning_histograms_seed10.png` |
| `fig_3_3_chebyshev_joint_probability_3d` | `final_figure/method_support/chebyshev_joint_probability_3d.png` | superseded | `notion_github_hosted_figures/fig_3_3_chebyshev_joint_probability_3d.svg` |
| `fig_3_3_second_collision_joint_probability_maps` | `final_figure/method_support/fig_3_3_second_collision_joint_probability_maps.png` | superseded | `figures/fig_3_3_second_collision_joint_probability_maps.png` |
| `fig_3_3_second_collision_joint_probability_maps_title_only` | `final_figure/method_support/fig_3_3_second_collision_joint_probability_maps_title_only.png` | OK | `figures/fig_3_3_second_collision_joint_probability_maps_title_only.png` |
| `fig_3_4_qgan_twolocal_ansatz` | `final_figure/qgan_baseline/qgan_twolocal_ansatz.png` | legacy | `notion_github_hosted_figures/fig_3_4_qgan_twolocal_ansatz.svg` |
| `fig_3_5_qgan_training_history_q5` | `final_figure/qgan_baseline/training_history/q5_R1.png` | superseded | `notion_github_hosted_figures/fig_3_5_qgan_training_history_q5.svg` |
| `fig_3_5_qgan_learned_distribution_q5` | `final_figure/qgan_baseline/learned_distributions/q5_KL_0p1601.png` | superseded | `notion_github_hosted_figures/fig_3_5_qgan_learned_distribution_q5.svg` |
| `fig_3_6_hea_ryrz_circular_reps2_ansatz` | `final_figure/method_circuits/hea_ryrz_circular_reps2_ansatz.png` | legacy | `notion_github_hosted_figures/fig_3_6_hea_ryrz_circular_reps2_ansatz.svg` |
| `fig_3_9_cos_q_joint_probability_heatmaps` | `final_figure/stateprep_distribution_curated/2d_q66/cos_q_joint_probability_heatmaps.png` | legacy | `figures/fig_3_9_cos_q_joint_probability_heatmaps.png` |
| `fig_3_9_cos_q_joint_probability_error_heatmaps` | `final_figure/stateprep_distribution_curated/2d_q66/cos_q_joint_probability_error_heatmaps.png` | legacy | `figures/fig_3_9_cos_q_joint_probability_error_heatmaps.png` |
| `fig_3_9_cos_q_joint_probability_marginals` | `final_figure/stateprep_distribution_curated/2d_q66/cos_q_joint_probability_marginals.png` | legacy | `figures/fig_3_9_cos_q_joint_probability_marginals.png` |
| `fig_3_9_theta_joint_probability_heatmaps` | `final_figure/stateprep_distribution_curated/2d_q66/theta_joint_probability_heatmaps.png` | legacy | `figures/fig_3_9_theta_joint_probability_heatmaps.png` |
| `fig_3_9_theta_joint_probability_error_heatmaps` | `final_figure/stateprep_distribution_curated/2d_q66/theta_joint_probability_error_heatmaps.png` | legacy | `figures/fig_3_9_theta_joint_probability_error_heatmaps.png` |
| `fig_3_9_theta_joint_probability_marginals` | `final_figure/stateprep_distribution_curated/2d_q66/theta_joint_probability_marginals.png` | legacy | `figures/fig_3_9_theta_joint_probability_marginals.png` |
| `fig_3_10_qae_qmci_mode_estimator_block` | `final_figure/method_circuits/qae_qmci_mode_estimator_block.png` | superseded | `notion_github_hosted_figures/fig_3_10_qae_qmci_mode_estimator_block.svg` |
| `fig_3_10_qae_qmci_mode_estimator_block_v2` | Manual three-panel QMCI/QAE schematic draft; superseded because Figure 8 must use Qiskit `mpl` circuit rendering | superseded | `figures/fig_3_10_qae_qmci_mode_estimator_block_v2.png` |
| `fig_3_10_qae_qmci_mode_estimator_block_v3` | Qiskit `mpl` Figure 8 draft before removing the basis block and restoring iQFT as a compact block | superseded | `figures/fig_3_10_qae_qmci_mode_estimator_block_v3.png` |
| `fig_3_10_qae_qmci_mode_estimator_block_v4` | Qiskit `mpl` Figure 8 draft with compact plain-text internal labels | superseded | `figures/fig_3_10_qae_qmci_mode_estimator_block_v4.png` |
| `fig_3_10_qae_qmci_mode_estimator_block_v5` | Current Figure 8 Qiskit `mpl` rendering with mathtext labels for $R_y(g_k)$, $S_\chi$, $A^\dagger$, $S_0$, controlled $Q^k$, $\chi=1$, and iQFT | OK | `figures/fig_3_10_qae_qmci_mode_estimator_block_v5.png` |
| `fig_3_11_qae_qmci_mode_estimator_decomposed` | Current Figure 10 QAE/QMCI mode-estimator gate-level decomposition | OK | `notion_github_hosted_figures/fig_3_11_qae_qmci_mode_estimator_decomposed.svg` |
| `fig_3_12_fft_reconstruction_Gu` | Current Figure 11-a FFT reconstruction context for the first-order QMCI workflow | OK | `notion_github_hosted_figures/fig_3_12_fft_reconstruction_Gu.svg` |
| `fig_3_12_qae_vs_nonqae_std_loglog` | Current Figure 11-b QAE versus non-QAE estimator scaling context | OK | `notion_github_hosted_figures/fig_3_12_qae_vs_nonqae_std_loglog.svg` |
| `fig_3_13_chebyshev_dose_heatmap_z0p5_x10` | Current Figure 12-a Chebyshev second-collision dose-map reconstruction panel | OK | `notion_github_hosted_figures/fig_3_13_chebyshev_dose_heatmap_z0p5_x10.svg` |
| `fig_3_13_fft_dose_heatmap_z0p5_x10` | Current Figure 12-b FFT second-collision dose-map reconstruction panel | OK | `notion_github_hosted_figures/fig_3_13_fft_dose_heatmap_z0p5_x10.svg` |
| `fig_3_13_chebyshev_profile_z0p5` | Current Figure 12-c Chebyshev profile reconstruction panel | OK | `notion_github_hosted_figures/fig_3_13_chebyshev_profile_z0p5.svg` |
| `fig_3_13_fft_profile_z0p5` | Current Figure 12-d FFT profile reconstruction panel | OK | `notion_github_hosted_figures/fig_3_13_fft_profile_z0p5.svg` |
| `fig_3_14_chebyshev_q60_dose` | Current Figure 13-a Chebyshev 1D dose reconstruction representative | OK | `notion_github_hosted_figures/fig_3_14_chebyshev_q60_dose.svg` |
| `fig_3_14_fft_q60_dose` | Current Figure 13-b FFT 1D dose reconstruction representative | OK | `notion_github_hosted_figures/fig_3_14_fft_q60_dose.svg` |
| `fig_4_1_depth_dose_analytic_vs_mc` | `final_figure/refer_pre_paper/notation_context/depth_dose_Dz_analytic_vs_MC.jpg` | superseded | `notion_github_hosted_figures/fig_4_1_depth_dose_analytic_vs_mc.svg` |
| `fig_4_1_depth_dose_geant4_6mev_water_500k_depth170` | `experiments/geant4_depthdose_fig14/final_500k_depth170_outputs/fig_4_1_depth_dose_geant4_6mev_water.png` | superseded | `figures/fig_4_1_depth_dose_geant4_6mev_water_500k_depth170.png` |
| `fig_4_1_first_compton_local_deposition_geant4_6mev_water_500k_depth170` | `experiments/geant4_depthdose_fig14/first_compton_500k_depth170_outputs/fig_4_1_first_compton_depth_dose_geant4_6mev_water.png` | superseded | `figures/fig_4_1_first_compton_local_deposition_geant4_6mev_water_500k_depth170.png` |
| `fig_4_1_first_compton_local_deposition_geant4_6mev_water_500k_depth170_v2` | `experiments/geant4_depthdose_fig14/first_compton_500k_depth170_outputs/fig_4_1_first_compton_depth_dose_geant4_6mev_water.png` | OK | `figures/fig_4_1_first_compton_local_deposition_geant4_6mev_water_500k_depth170_v2.png` |
| `fig_4_2_single_compton_D1_qmci` | `final_figure/refer_pre_paper/qae_fft_1d_context/single_compton_D1_qmci.png` | OK | `notion_github_hosted_figures/fig_4_2_single_compton_D1_qmci.svg` |
| `fig_4_3_qae_vs_nonqae_std_loglog` | `final_figure/refer_pre_paper/qae_fft_1d_context/qae_vs_nonqae_std_loglog.png` | OK | `notion_github_hosted_figures/fig_4_3_qae_vs_nonqae_std_loglog.svg` |
| `fig_4_4_2d_dose_mae_vs_reps` | `final_figure/qmci_qae_curated/trends/2d_dose_mae_vs_reps.png` | OK | `notion_github_hosted_figures/fig_4_4_2d_dose_mae_vs_reps.svg` |
| `fig_4_5_2d_profile_mae_vs_reps` | `final_figure/qmci_qae_curated/trends/2d_profile_mae_vs_reps.png` | OK | `notion_github_hosted_figures/fig_4_5_2d_profile_mae_vs_reps.svg` |
| `fig_4_6_2d_stateprep_kl_vs_reps` | `final_figure/qmci_qae_curated/trends/2d_stateprep_kl_vs_reps.png` | OK | `notion_github_hosted_figures/fig_4_6_2d_stateprep_kl_vs_reps.svg` |
| `fig_4_7_q44_chebyshev_best_dose` | `final_figure/qmci_qae_curated/2d_best_representatives/q44_chebyshev_best_dose_reps20.png` | OK | `notion_github_hosted_figures/fig_4_7_q44_chebyshev_best_dose.svg` |
| `fig_4_7_q44_fft_best_dose` | `final_figure/qmci_qae_curated/2d_best_representatives/q44_fft_best_dose_reps20.png` | OK | `notion_github_hosted_figures/fig_4_7_q44_fft_best_dose.svg` |
| `fig_4_7_q55_chebyshev_best_profile` | `final_figure/qmci_qae_curated/2d_best_representatives/q55_chebyshev_best_profile_z0p5_reps20.png` | OK | `notion_github_hosted_figures/fig_4_7_q55_chebyshev_best_profile.svg` |
| `fig_4_7_q55_fft_best_profile` | `final_figure/qmci_qae_curated/2d_best_representatives/q55_fft_best_profile_z0p5_reps20.png` | OK | `notion_github_hosted_figures/fig_4_7_q55_fft_best_profile.svg` |
| `fig_4_7_q66_chebyshev_best_profile` | `final_figure/qmci_qae_curated/2d_best_representatives/q66_chebyshev_best_profile_z0p5_reps24.png` | OK | `notion_github_hosted_figures/fig_4_7_q66_chebyshev_best_profile.svg` |
| `fig_4_7_q66_fft_best_profile` | `final_figure/qmci_qae_curated/2d_best_representatives/q66_fft_best_profile_z0p5_reps24.png` | OK | `notion_github_hosted_figures/fig_4_7_q66_fft_best_profile.svg` |
| `fig_4_8_kl_threshold_rmse_norm_convergence` | `final_figure/kl_ladder_q60/figures/kl_threshold_rmse_norm_convergence.png` | OK | `notion_github_hosted_figures/fig_4_8_kl_threshold_rmse_norm_convergence.svg` |
| `fig_4_9_kl_threshold_mse_norm_vs_invshots` | `final_figure/kl_ladder_q60/figures/kl_threshold_mse_norm_vs_invshots.png` | OK | `notion_github_hosted_figures/fig_4_9_kl_threshold_mse_norm_vs_invshots.svg` |

## Auxiliary Hosted Assets

These hosted assets are available for support or future editing, but are not
part of the currently rendered Notion paper figure set.

| slug | source | status | upload path | note |
| --- | --- | --- | --- | --- |
| `fig_3_5_qgan_training_diagram` | `final_figure/qgan_baseline/qgan_training_diagram.pdf` | auxiliary | `notion_github_hosted_figures/fig_3_5_qgan_training_diagram.svg` | Available qGAN training-loop support asset; superseded in the paper by the matched reps=8 Figure 5 diagnostic. |
| `fig_3_7_hn_zero_shot_kl_bar` | `final_figure/stateprep_hn/zero_shot_kl_bar.png` | legacy | `notion_github_hosted_figures/fig_3_7_hn_zero_shot_kl_bar.svg` | Legacy HN/state-preparation support asset; not part of the currently rendered Notion paper figure set. |
| `fig_3_7_hn_finetune_curves_kl` | `final_figure/stateprep_hn/finetune_curves_kl.png` | legacy | `notion_github_hosted_figures/fig_3_7_hn_finetune_curves_kl.svg` | Legacy HN/state-preparation support asset; not part of the currently rendered Notion paper figure set. |
| `fig_3_7_hn_median_kl_vs_reps` | `final_figure/stateprep_hn/median_kl_vs_reps_hea_hn.png` | legacy | `notion_github_hosted_figures/fig_3_7_hn_median_kl_vs_reps.svg` | Legacy HN/state-preparation support asset; not part of the currently rendered Notion paper figure set. |
| `fig_3_8_hn_target_pos` | `final_figure/stateprep_hn/target_pos.png` | legacy | `notion_github_hosted_figures/fig_3_8_hn_target_pos.svg` | Legacy HN/state-preparation support asset; not part of the currently rendered Notion paper figure set. |
| `fig_3_8_hn_zero_shot_pos` | `final_figure/stateprep_hn/hn_zero_shot_pos.png` | legacy | `notion_github_hosted_figures/fig_3_8_hn_zero_shot_pos.svg` | Legacy HN/state-preparation support asset; not part of the currently rendered Notion paper figure set. |
| `fig_3_8_hn_zero_shot_diff_pos` | `final_figure/stateprep_hn/hn_zero_shot_diff_pos.png` | legacy | `notion_github_hosted_figures/fig_3_8_hn_zero_shot_diff_pos.svg` | Legacy HN/state-preparation support asset; not part of the currently rendered Notion paper figure set. |

## Cross Check Figures (2026-06-19)

These figures are candidate additions proposed through `cross_check` Notion
comments. They are hosted for review and should not be treated as accepted
paper figures until a human editor applies the corresponding page edit.

| slug | source data | status | canonical URL |
| --- | --- | --- | --- |
| `cross_check_fig_4_10_q60_floor_vs_observed_kl` | `최종데이터/final_data_analysis/q60_1d_qae_kl_thresholds_reps8/summaries/fit_summary.csv` | candidate | `https://yokshire.github.io/yokshire_image_hosting/figures/cross_check_fig_4_10_q60_floor_vs_observed_kl.png` |
| `cross_check_fig_3_2_stateprep_status_kl` | `최종데이터/final_data_analysis/summaries/stateprep_comparison_summary.csv` | candidate | `https://yokshire.github.io/yokshire_image_hosting/figures/cross_check_fig_3_2_stateprep_status_kl.png` |
| `cross_check_fig_3_5_qgan_qubit_kl_scope` | `final_figure/qgan_baseline/README.md`; `final_figure/qgan_baseline/learned_distributions/*` | candidate | `https://yokshire.github.io/yokshire_image_hosting/figures/cross_check_fig_3_5_qgan_qubit_kl_scope.png` |
| `cross_check_fig_3_9_initialize_vs_hea_depth_complexity` | `최종데이터/final_data_analysis/transpiled_stateprep_complexity/summaries/complexity_summary_best_opt1.csv` | candidate | `https://yokshire.github.io/yokshire_image_hosting/figures/cross_check_fig_3_9_initialize_vs_hea_depth_complexity.png` |
| `cross_check_fig_4_4_1d_point_fft_scope` | `최종데이터/final_data_analysis/qmci_actual_all_reps/summaries/one_d_summary.csv` | candidate | `https://yokshire.github.io/yokshire_image_hosting/figures/cross_check_fig_4_4_1d_point_fft_scope.png` |
| `cross_check_fig_4_11_2d_matched_pair_scatter` | `final_figure/role_up/role_up_2d_matched_pair_summary.csv` | candidate | `https://yokshire.github.io/yokshire_image_hosting/figures/cross_check_fig_4_11_2d_matched_pair_scatter.png` |
| `cross_check_fig_4_12_figure19_missing_representatives` | `final_figure/qmci_qae_curated/2d_best_representatives/*` selected missing panels | candidate | `https://yokshire.github.io/yokshire_image_hosting/figures/cross_check_fig_4_12_figure19_missing_representatives.png` |

## Role Up Figures (2026-06-01)

These figures were regenerated from the project CSV/raw evidence for the
Notion `Research / Quantum_Algorithm / Quantum Monte Carlo / Role Up` page.

| slug | source data | status | canonical URL |
| --- | --- | --- | --- |
| `role_up_fig_1_2d_family_average_mae` | `최종데이터/final_data_analysis/qmci_actual_all_reps/summaries/two_d_summary.csv` | OK | `https://yokshire.github.io/yokshire_image_hosting/figures/role_up_fig_1_2d_family_average_mae.png` |
| `role_up_fig_2_2d_dose_mae_by_reps` | `최종데이터/final_data_analysis/qmci_actual_all_reps/summaries/two_d_summary.csv` | OK | `https://yokshire.github.io/yokshire_image_hosting/figures/role_up_fig_2_2d_dose_mae_by_reps.png` |
| `role_up_fig_3_stateprep_exact_kl` | `최종데이터/final_data_analysis/summaries/stateprep_comparison_summary.csv` | OK | `https://yokshire.github.io/yokshire_image_hosting/figures/role_up_fig_3_stateprep_exact_kl.png` |
| `role_up_fig_4_1d_qmci_mae_distribution` | `최종데이터/final_data_analysis/qmci_actual_all_reps/summaries/one_d_summary.csv` | OK | `https://yokshire.github.io/yokshire_image_hosting/figures/role_up_fig_4_1d_qmci_mae_distribution.png` |
| `role_up_fig_5_representative_dose_curves` | `최종데이터/final_data_analysis/qmci_actual_all_reps/raw/2d/chebyshev/q66/theta/reps_24/dose_curve.csv`; `최종데이터/final_data_analysis/qmci_actual_all_reps/raw/2d/fft/q66/cos_q/reps_24/dose_curve.csv` | OK | `https://yokshire.github.io/yokshire_image_hosting/figures/role_up_fig_5_representative_dose_curves.png` |
| `role_up_fig_6_representative_profile_z0p5` | `최종데이터/final_data_analysis/qmci_actual_all_reps/raw/2d/chebyshev/q66/theta/reps_24/profile_comparison_all_z.csv`; `최종데이터/final_data_analysis/qmci_actual_all_reps/raw/2d/fft/q66/cos_q/reps_24/profile_comparison_all_z.csv` | OK | `https://yokshire.github.io/yokshire_image_hosting/figures/role_up_fig_6_representative_profile_z0p5.png` |
| `role_up_fig_7_2d_matched_pair_delta` | `최종데이터/final_data_analysis/qmci_actual_all_reps/summaries/two_d_summary.csv` matched by q-resolution and reps | OK | `https://yokshire.github.io/yokshire_image_hosting/figures/role_up_fig_7_2d_matched_pair_delta.png` |

## Copyright and reuse

This repository intentionally has no open-source or open-content license. Public
visibility is used only for figure rendering in research documents and academic
review workflows.

Unless explicit written permission is granted by the repository owner, the
images and derived assets may not be copied, redistributed, modified, published,
or reused outside the associated research/manuscript context.

See [NOTICE.md](NOTICE.md) for the full reuse notice.

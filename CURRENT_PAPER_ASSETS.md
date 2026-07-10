# Current Paper Assets: QMCI Manuscript v04

This file is the operator checklist for the active Notion paper page and the
LaTeX package in `exports/QMCI_manuscript_v04`. The broader historical asset
record remains in `manifest.json`.

- Notion page id: `3524c48e-4da3-81b5-8d22-c7d73ae6e455`
- Notion page: `https://app.notion.com/p/3524c48e4da381b58d22c7d73ae6e455`
- LaTeX source manifest: `exports/QMCI_manuscript_v04/figure_manifest.tsv`
- Hosting manifest: `paper_v04_manifest.json`
- Canonical delivery base: `https://yokshire.github.io/yokshire_image_hosting/figures/`
- Reconciled: 2026-07-10

## Current Figures

| Figure | Label | Hosted asset | Protocol role |
| --- | --- | --- | --- |
| Figure 1 | `fig:xcom` | `figures/cross_check_fig_intro_xcom_h2o_interaction_coefficients_6mev_v1.png` | XCOM motivation |
| Figure 2 | `fig:workflow` | `figures/fig_x2_qmci_workflow_intro_v1.png` | QMCI workflow |
| Figure 3 | `fig:geometry` | `figures/fig_3_1_scattering_path_Dl_notation.jpg` | Multiple-scattering geometry |
| Figure 4 | `fig:d1exact` | `figures/fig_3_2_depth_dose_benchmark_exact_q5_highres_v3.png` | First-collision exact-loading benchmark |
| Figure 5 | `fig:jointtarget` | `figures/fig_3_3_second_collision_joint_probability_maps_title_only.png` | Second-collision joint target |
| Figure 6 | `fig:ansatz` | `figures/fig_3_2c_matched_stateprep_ansatz_unit_ryrz_cx_hinit_v2.png` | One-dimensional matched ansatz unit |
| Figure 7 | `fig:qae` | `figures/fig_3_10_qae_qmci_mode_estimator_block_v5.png` | QAE-style mode estimator |
| Figure 8-a | `fig:basis` | `figures/fig_3_12_fft_reconstruction_Gu.png` | FFT/Fourier basis illustration |
| Figure 8-b | `fig:basis` | `figures/fig_3_12_chebyshev_reconstruction_Gq.png` | Chebyshev basis illustration |
| Figure 9-a | `fig:g4bench` | `figures/fig_4_1_first_compton_local_deposition_geant4_6mev_water_500k_depth170_v3.png` | First-Compton Geant4 reference |
| Figure 9-b | `fig:g4bench` | `figures/fig_4_1b_second_compton_fixed_lambda_geant4_6mev_water_500k_depth170_v2.png` | Fixed-lambda second-Compton reference |
| Figure 10 | `fig:d1recon` | `figures/fig_3_14_q50_stateprep_fft_chebyshev_dose_seed10_v2.png` | Ten-seed first-collision reconstruction |
| Figure 11 | `fig:d2profile` | `figures/fig_3_13_q55_stateprep_fft_chebyshev_dose_profile_seed0_iter5000_v4.png` | Selected 5+5-qubit seed-0 checkpoint at 5000 updates |
| Figure 12 | `fig:repsdiag` | `figures/fig_3_2b_stateprep_matched_reps_q5_seed10_ryrz_cx_hinit_whisker_v3.png` | Reps 1--8, seeds 0--9 loading diagnostic |
| Figure 13 | `fig:qspacehist` | `figures/fig_3_5_matched_reps8_learning_histograms_seed10_ryrz_cx_hinit_trace3000_v4.png` | Reps-8 q-space diagnostic |
| Figure 14 | `fig:thetaspacehist` | `figures/fig_3_6_theta_matched_reps8_learning_histograms_seed10_ryrz_cx_hinit_trace3000_v4.png` | Reps-8 theta-space diagnostic |
| Figure 15 | `fig:mainchannel` | `figures/fig_3_9_stateprep_main_channel_integral_convergence_reps8_iter10000_v3.png` | Main-channel qubit convergence |
| Figure 16 | `fig:backendstateprep` | `figures/fig_backend_stateprep_metrics_n2_8_v1_paper.png` | Distribution-level backend diagnostic |
| Figure 17 | `fig:iqaeconvergence` | `figures/fig_backend_iqae_k1_convergence_n5_v1_paper.png` | Full-circuit IQAE convergence |
| Figure 18 | `fig:ecrscaling` | `figures/fig_backend_ecr_scaling_collision_v1_paper.png` | Controlled ECR error attribution |

The LaTeX package uses RGB-normalized copies for several pre-existing figures.
`paper_v04_manifest.json` records both hashes and verifies that each hosted
asset is pixel-equivalent to the corresponding TeX image.

## Protocol Boundaries

- One-dimensional diagnostics: 5 qubits, H initialization, `Ry/Rz`, circular
  CX, repetitions 1--8, seeds 0--9. Learning traces display the first 3000
  updates.
- Selected two-dimensional reconstruction: 5+5 qubits, H initialization,
  `Rx/Rz/Ry`, full entanglement, repetitions 8, 270 parameters, seed 0,
  selected from 5000-update runs. It is not a seed-range result.
- Backend state-preparation study: independently trained repetitions-8 HN-MLP
  Chebyshev loaders. Mitigated points are an availability-limited envelope,
  not a uniform mitigation protocol.
- Full-circuit estimator study: first Chebyshev mode, 5 data qubits,
  `epsilon=0.005`, 512--8192 shots.
- ECR attribution: controlled depolarizing ECR scaling with calibrated SX/X
  depolarizing errors fixed; readout, relaxation, and coherent errors are not
  included in this attribution model.

## Superseded In v04

| Asset | Reason |
| --- | --- |
| `figures/fig_3_13_q55_stateprep_fft_chebyshev_dose_profile_seed10_v2.png` | Replaced by the selected seed-0, 5000-update Figure 11. |
| `figures/fig_4_6g_yonsei_compact_backend_feasibility_v2.png` | Replaced by the distribution-level backend, full-circuit IQAE, and ECR-attribution sequence. |
| `figures/fig_4_7_hn_chebyshev_qae_rmse_three_methods_v5.png` | Older ideal estimator-scaling branch; not in the v04 paper sequence. |
| `figures/fig_3_5_matched_reps8_learning_histograms_seed10_v2.png` | Pre-mainstream two-dimensional ansatz family. |
| `figures/fig_3_6_theta_matched_reps8_learning_histograms_seed10_v2.png` | Pre-mainstream two-dimensional ansatz family. |

Historical files remain available for provenance and must not be deleted solely
because they are superseded.

## Update Rules

1. Update `exports/QMCI_manuscript_v04/figure_manifest.tsv`,
   `paper_v04_manifest.json`, and this file together.
2. Upload and verify GitHub Pages URLs before changing a Notion image block.
3. Use GitHub Pages as the canonical source and GitHub raw only as fallback.
4. Preserve historical assets and mark their status instead of silently
   overwriting their meaning.
5. Keep filename-only `q50` and `q55` compatibility tags out of visible captions;
   use `5-qubit` and `5+5-qubit` in manuscript text.

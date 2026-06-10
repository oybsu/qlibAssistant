# params 
 {'predict_dates': [{'start': '2026-06-10', 'end': '2026-06-10'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260610_18 226436234867046459 (Recorders: 3/5)

	Recorder: e0eb0f8f169e48a0bd0398bf0365eed8

		Model: {'id': 'e0eb0f8f169e48a0bd0398bf0365eed8', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.051, 'Rank IC': 0.04, 'Rank ICIR': 0.251}, 'data_train_vec': ['2022-06-10', '2025-06-09'], 'train_time_vec': ['2026-06-10', '2026-06-10'], 'rank_icir': '0.251', 'weight': '0.056'}

	Recorder: 0d468a3239354e10af689d7c4b0d3d1e

		Model: {'id': '0d468a3239354e10af689d7c4b0d3d1e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.165, 'Rank IC': 0.043, 'Rank ICIR': 0.302}, 'data_train_vec': ['2023-06-10', '2025-09-09'], 'train_time_vec': ['2026-06-10', '2026-06-10'], 'rank_icir': '0.302', 'weight': '0.068'}

	Recorder: 7c56eb7d34614a44af509d5ea35b2f79

		Model: {'id': '7c56eb7d34614a44af509d5ea35b2f79', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.26, 'Rank IC': 0.031, 'Rank ICIR': 0.278}, 'data_train_vec': ['2024-06-10', '2025-12-09'], 'train_time_vec': ['2026-06-10', '2026-06-10'], 'rank_icir': '0.278', 'weight': '0.062'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260610_18 329776480920661477 (Recorders: 3/5)

	Recorder: 72a210e273014e629295e09f06810e9f

		Model: {'id': '72a210e273014e629295e09f06810e9f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.061, 'Rank IC': 0.031, 'Rank ICIR': 0.186}, 'data_train_vec': ['2021-06-10', '2025-03-09'], 'train_time_vec': ['2026-06-10', '2026-06-10'], 'rank_icir': '0.186', 'weight': '0.042'}

	Recorder: 1c782bcb51aa438a8e10759893a93052

		Model: {'id': '1c782bcb51aa438a8e10759893a93052', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.22, 'Rank IC': 0.039, 'Rank ICIR': 0.311}, 'data_train_vec': ['2023-06-10', '2025-09-09'], 'train_time_vec': ['2026-06-10', '2026-06-10'], 'rank_icir': '0.311', 'weight': '0.070'}

	Recorder: fe4e8e281c4646aa8b08be4e7909bb23

		Model: {'id': 'fe4e8e281c4646aa8b08be4e7909bb23', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.195, 'Rank IC': 0.026, 'Rank ICIR': 0.254}, 'data_train_vec': ['2024-06-10', '2025-12-09'], 'train_time_vec': ['2026-06-10', '2026-06-10'], 'rank_icir': '0.254', 'weight': '0.057'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260610_16 661525298491905331 (Recorders: 4/5)

	Recorder: 4c0a84a020904c949ab9c85ca0bf0a3d

		Model: {'id': '4c0a84a020904c949ab9c85ca0bf0a3d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.135, 'Rank IC': 0.047, 'Rank ICIR': 0.324}, 'data_train_vec': ['2021-06-10', '2025-03-09'], 'train_time_vec': ['2026-06-10', '2026-06-10'], 'rank_icir': '0.324', 'weight': '0.072'}

	Recorder: 8e1eb33548c340c38ac3db9fd9769394

		Model: {'id': '8e1eb33548c340c38ac3db9fd9769394', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.128, 'Rank IC': 0.053, 'Rank ICIR': 0.296}, 'data_train_vec': ['2022-06-10', '2025-06-09'], 'train_time_vec': ['2026-06-10', '2026-06-10'], 'rank_icir': '0.296', 'weight': '0.066'}

	Recorder: 096ca8b029e94b53a32854da35093d33

		Model: {'id': '096ca8b029e94b53a32854da35093d33', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.27, 'Rank IC': 0.053, 'Rank ICIR': 0.358}, 'data_train_vec': ['2023-06-10', '2025-09-09'], 'train_time_vec': ['2026-06-10', '2026-06-10'], 'rank_icir': '0.358', 'weight': '0.080'}

	Recorder: 9545d23ed0ab49e9a3b32d72656379cd

		Model: {'id': '9545d23ed0ab49e9a3b32d72656379cd', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.105, 'Rank IC': 0.012, 'Rank ICIR': 0.107}, 'data_train_vec': ['2024-06-10', '2025-12-09'], 'train_time_vec': ['2026-06-10', '2026-06-10'], 'rank_icir': '0.107', 'weight': '0.024'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260610_16 549983423013324715 (Recorders: 4/5)

	Recorder: 0979298e8e3a402fbc6b6d7b8126e4aa

		Model: {'id': '0979298e8e3a402fbc6b6d7b8126e4aa', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.128, 'Rank IC': 0.043, 'Rank ICIR': 0.368}, 'data_train_vec': ['2021-06-10', '2025-03-09'], 'train_time_vec': ['2026-06-10', '2026-06-10'], 'rank_icir': '0.368', 'weight': '0.082'}

	Recorder: 3b6279cb99224bf4b270ca538c8d0e52

		Model: {'id': '3b6279cb99224bf4b270ca538c8d0e52', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.01, 'Rank IC': 0.04, 'Rank ICIR': 0.287}, 'data_train_vec': ['2022-06-10', '2025-06-09'], 'train_time_vec': ['2026-06-10', '2026-06-10'], 'rank_icir': '0.287', 'weight': '0.064'}

	Recorder: e56895b505f4400b9b13cffc68cf8393

		Model: {'id': 'e56895b505f4400b9b13cffc68cf8393', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.126, 'Rank IC': 0.039, 'Rank ICIR': 0.341}, 'data_train_vec': ['2023-06-10', '2025-09-09'], 'train_time_vec': ['2026-06-10', '2026-06-10'], 'rank_icir': '0.341', 'weight': '0.076'}

	Recorder: 13c45c701f02433faabfe9b3f82f1d0d

		Model: {'id': '13c45c701f02433faabfe9b3f82f1d0d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.029, 'Rank IC': 0.012, 'Rank ICIR': 0.079}, 'data_train_vec': ['2024-06-10', '2025-12-09'], 'train_time_vec': ['2026-06-10', '2026-06-10'], 'rank_icir': '0.079', 'weight': '0.018'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260610_16 394169160912904006 (Recorders: 3/5)

	Recorder: f432c57de40d48589092a8b16a80f446

		Model: {'id': 'f432c57de40d48589092a8b16a80f446', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.147, 'Rank IC': 0.046, 'Rank ICIR': 0.276}, 'data_train_vec': ['2021-06-10', '2025-03-09'], 'train_time_vec': ['2026-06-10', '2026-06-10'], 'rank_icir': '0.276', 'weight': '0.062'}

	Recorder: 14f6a102f56f4df5b0a7132d0ebb404c

		Model: {'id': '14f6a102f56f4df5b0a7132d0ebb404c', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.033, 'Rank IC': 0.041, 'Rank ICIR': 0.224}, 'data_train_vec': ['2022-06-10', '2025-06-09'], 'train_time_vec': ['2026-06-10', '2026-06-10'], 'rank_icir': '0.224', 'weight': '0.050'}

	Recorder: d6988291870e419491bc700dd4792b81

		Model: {'id': 'd6988291870e419491bc700dd4792b81', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.074, 'Rank IC': 0.039, 'Rank ICIR': 0.232}, 'data_train_vec': ['2023-06-10', '2025-09-09'], 'train_time_vec': ['2026-06-10', '2026-06-10'], 'rank_icir': '0.232', 'weight': '0.052'}

# params 
 {'predict_dates': [{'start': '2026-09-24', 'end': '2026-09-24'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260924_19 969409506169885066 (Recorders: 3/5)

	Recorder: cee35d35ff1c47c2a6a810e3f09aeda5

		Model: {'id': 'cee35d35ff1c47c2a6a810e3f09aeda5', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.049, 'Rank IC': 0.026, 'Rank ICIR': 0.15}, 'data_train_vec': ['2021-09-24', '2025-06-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.150', 'weight': '0.064'}

	Recorder: 5c6f4e73fe3047bbb7f831d98b3e6cbb

		Model: {'id': '5c6f4e73fe3047bbb7f831d98b3e6cbb', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.091, 'Rank IC': 0.036, 'Rank ICIR': 0.199}, 'data_train_vec': ['2022-09-24', '2025-09-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.199', 'weight': '0.085'}

	Recorder: 02173e77239f4b84942c3398f0f6e478

		Model: {'id': '02173e77239f4b84942c3398f0f6e478', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.093, 'Rank IC': 0.02, 'Rank ICIR': 0.121}, 'data_train_vec': ['2023-09-24', '2025-12-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.121', 'weight': '0.052'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260924_19 953034941783254415 (Recorders: 3/5)

	Recorder: e7763d782eec4f06b7568cd3f5a514b7

		Model: {'id': 'e7763d782eec4f06b7568cd3f5a514b7', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.153, 'Rank IC': 0.031, 'Rank ICIR': 0.228}, 'data_train_vec': ['2021-09-24', '2025-06-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.228', 'weight': '0.097'}

	Recorder: af70fb0cd59a4337986f0419cfbd259a

		Model: {'id': 'af70fb0cd59a4337986f0419cfbd259a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.121, 'Rank IC': 0.034, 'Rank ICIR': 0.193}, 'data_train_vec': ['2022-09-24', '2025-09-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.193', 'weight': '0.082'}

	Recorder: 20962c3fdc7b4ac5a33d22c5d4958952

		Model: {'id': '20962c3fdc7b4ac5a33d22c5d4958952', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.027, 'Rank IC': 0.009, 'Rank ICIR': 0.05}, 'data_train_vec': ['2023-09-24', '2025-12-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.050', 'weight': '0.021'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260924_17 993124968085756001 (Recorders: 4/5)

	Recorder: 7058d9405b73448a9d32a6f69eddc208

		Model: {'id': '7058d9405b73448a9d32a6f69eddc208', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.162, 'Rank IC': 0.043, 'Rank ICIR': 0.245}, 'data_train_vec': ['2021-09-24', '2025-06-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.245', 'weight': '0.104'}

	Recorder: a18fdebec3f7423bba9f50f8cd04b321

		Model: {'id': 'a18fdebec3f7423bba9f50f8cd04b321', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.11, 'Rank IC': 0.034, 'Rank ICIR': 0.186}, 'data_train_vec': ['2022-09-24', '2025-09-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.186', 'weight': '0.079'}

	Recorder: 45c173da90e44e3287ff05a6796e5eac

		Model: {'id': '45c173da90e44e3287ff05a6796e5eac', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.023, 'Rank IC': 0.008, 'Rank ICIR': 0.038}, 'data_train_vec': ['2023-09-24', '2025-12-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.038', 'weight': '0.016'}

	Recorder: f1bdfb570c094ab49d6b296010241eb2

		Model: {'id': 'f1bdfb570c094ab49d6b296010241eb2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.116, 'Rank IC': 0.012, 'Rank ICIR': 0.062}, 'data_train_vec': ['2024-09-24', '2026-03-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.062', 'weight': '0.026'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260924_17 247949398999698436 (Recorders: 3/5)

	Recorder: 17067f5ff44d47fe8a51800fa05e3112

		Model: {'id': '17067f5ff44d47fe8a51800fa05e3112', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.158, 'Rank IC': 0.037, 'Rank ICIR': 0.211}, 'data_train_vec': ['2021-09-24', '2025-06-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.211', 'weight': '0.090'}

	Recorder: 5df0740eb9644913afbc75fa21d7c97d

		Model: {'id': '5df0740eb9644913afbc75fa21d7c97d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.13, 'Rank IC': 0.018, 'Rank ICIR': 0.102}, 'data_train_vec': ['2022-09-24', '2025-09-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.102', 'weight': '0.043'}

	Recorder: 18b3cfdb55a8493e976c94f985bba032

		Model: {'id': '18b3cfdb55a8493e976c94f985bba032', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.047, 'ICIR': 0.19, 'Rank IC': 0.02, 'Rank ICIR': 0.096}, 'data_train_vec': ['2024-09-24', '2026-03-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.096', 'weight': '0.041'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260924_17 393412606708563083 (Recorders: 3/5)

	Recorder: cf61fcc811024eb8913f67b33f138ab0

		Model: {'id': 'cf61fcc811024eb8913f67b33f138ab0', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.043, 'Rank IC': 0.035, 'Rank ICIR': 0.204}, 'data_train_vec': ['2021-09-24', '2025-06-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.204', 'weight': '0.087'}

	Recorder: dd2ba6223cff43b7a3b41ff39079b5c2

		Model: {'id': 'dd2ba6223cff43b7a3b41ff39079b5c2', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.028, 'Rank IC': 0.025, 'Rank ICIR': 0.148}, 'data_train_vec': ['2022-09-24', '2025-09-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.148', 'weight': '0.063'}

	Recorder: a7e51ed893454ba3b59861ea372e8131

		Model: {'id': 'a7e51ed893454ba3b59861ea372e8131', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.125, 'Rank IC': 0.018, 'Rank ICIR': 0.114}, 'data_train_vec': ['2024-09-24', '2026-03-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.114', 'weight': '0.049'}

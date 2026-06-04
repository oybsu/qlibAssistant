# params 
 {'predict_dates': [{'start': '2026-06-03', 'end': '2026-06-03'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260604_03 766606804158237788 (Recorders: 2/5)

	Recorder: 0dc4c9cdd06b448fb1e53e837f2d1d84

		Model: {'id': '0dc4c9cdd06b448fb1e53e837f2d1d84', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.123, 'Rank IC': 0.03, 'Rank ICIR': 0.212}, 'data_train_vec': ['2021-06-04', '2025-03-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.212', 'weight': '0.071'}

	Recorder: 6f54ccf6dbdf4a228105fc2e27bb1f77

		Model: {'id': '6f54ccf6dbdf4a228105fc2e27bb1f77', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.198, 'Rank IC': 0.033, 'Rank ICIR': 0.221}, 'data_train_vec': ['2023-06-04', '2025-09-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.221', 'weight': '0.074'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260604_03 249659820891405537 (Recorders: 3/5)

	Recorder: 0c835ef434974f039a3abb0d183ecd48

		Model: {'id': '0c835ef434974f039a3abb0d183ecd48', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.03, 'Rank IC': 0.022, 'Rank ICIR': 0.149}, 'data_train_vec': ['2021-06-04', '2025-03-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.149', 'weight': '0.050'}

	Recorder: b26f34f0ab90440ca85e8bcbcd0ada57

		Model: {'id': 'b26f34f0ab90440ca85e8bcbcd0ada57', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.146, 'Rank IC': 0.029, 'Rank ICIR': 0.222}, 'data_train_vec': ['2023-06-04', '2025-09-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.222', 'weight': '0.074'}

	Recorder: 1e01781bc63f45f5996a9607b90058da

		Model: {'id': '1e01781bc63f45f5996a9607b90058da', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.064, 'ICIR': 0.267, 'Rank IC': 0.029, 'Rank ICIR': 0.124}, 'data_train_vec': ['2025-06-04', '2026-03-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.124', 'weight': '0.041'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260604_01 460196147569867976 (Recorders: 3/5)

	Recorder: d60dc95c273e4158aaece0264bdcbc0b

		Model: {'id': 'd60dc95c273e4158aaece0264bdcbc0b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.13, 'Rank IC': 0.044, 'Rank ICIR': 0.304}, 'data_train_vec': ['2021-06-04', '2025-03-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.304', 'weight': '0.102'}

	Recorder: 25be1d32d3bb48c9a5a42d6ac8c08af8

		Model: {'id': '25be1d32d3bb48c9a5a42d6ac8c08af8', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.064, 'Rank IC': 0.043, 'Rank ICIR': 0.243}, 'data_train_vec': ['2022-06-04', '2025-06-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.243', 'weight': '0.081'}

	Recorder: 2f26b4a09c524ad488e36bd16449d50c

		Model: {'id': '2f26b4a09c524ad488e36bd16449d50c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.217, 'Rank IC': 0.044, 'Rank ICIR': 0.3}, 'data_train_vec': ['2023-06-04', '2025-09-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.300', 'weight': '0.100'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260604_01 410880407096026276 (Recorders: 4/5)

	Recorder: f6765e1ab36b43688a410107a19e0213

		Model: {'id': 'f6765e1ab36b43688a410107a19e0213', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.086, 'Rank IC': 0.038, 'Rank ICIR': 0.334}, 'data_train_vec': ['2021-06-04', '2025-03-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.334', 'weight': '0.112'}

	Recorder: 01a4fedc7bc5409382319339e07eeb84

		Model: {'id': '01a4fedc7bc5409382319339e07eeb84', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.046, 'Rank IC': 0.029, 'Rank ICIR': 0.26}, 'data_train_vec': ['2023-06-04', '2025-09-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.260', 'weight': '0.087'}

	Recorder: 9a81e8e54df2418d858ee9f975b25840

		Model: {'id': '9a81e8e54df2418d858ee9f975b25840', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.036, 'Rank IC': 0.014, 'Rank ICIR': 0.098}, 'data_train_vec': ['2024-06-04', '2025-12-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.098', 'weight': '0.033'}

	Recorder: 3f95192b08cd492fb6973d6bc4ff3264

		Model: {'id': '3f95192b08cd492fb6973d6bc4ff3264', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.039, 'ICIR': 0.178, 'Rank IC': 0.023, 'Rank ICIR': 0.096}, 'data_train_vec': ['2025-06-04', '2026-03-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.096', 'weight': '0.032'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260604_01 930338190112569689 (Recorders: 2/5)

	Recorder: 3c0e8f090e1d4a1e82d15cf1886f3281

		Model: {'id': '3c0e8f090e1d4a1e82d15cf1886f3281', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.066, 'Rank IC': 0.039, 'Rank ICIR': 0.234}, 'data_train_vec': ['2021-06-04', '2025-03-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.234', 'weight': '0.078'}

	Recorder: 69b47c376e9b4508bca398ae27fd979b

		Model: {'id': '69b47c376e9b4508bca398ae27fd979b', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.117, 'Rank IC': 0.031, 'Rank ICIR': 0.194}, 'data_train_vec': ['2023-06-04', '2025-09-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.194', 'weight': '0.065'}

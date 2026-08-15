# params 
 {'predict_dates': [{'start': '2026-08-14', 'end': '2026-08-14'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260815_15 783559178667589703 (Recorders: 1/5)

	Recorder: a9c44f3afdb54e4bab296954efd3cef0

		Model: {'id': 'a9c44f3afdb54e4bab296954efd3cef0', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.013, 'Rank IC': 0.025, 'Rank ICIR': 0.163}, 'data_train_vec': ['2023-08-15', '2025-11-14'], 'train_time_vec': ['2026-08-15', '2026-08-15'], 'rank_icir': '0.163', 'weight': '0.109'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260815_15 988947317237003921 (Recorders: 3/5)

	Recorder: ef14e73098354922a4ff6c33e8edca59

		Model: {'id': 'ef14e73098354922a4ff6c33e8edca59', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.06, 'Rank IC': 0.023, 'Rank ICIR': 0.163}, 'data_train_vec': ['2021-08-15', '2025-05-14'], 'train_time_vec': ['2026-08-15', '2026-08-15'], 'rank_icir': '0.163', 'weight': '0.109'}

	Recorder: 3b4385be51534510961b371b362dd129

		Model: {'id': '3b4385be51534510961b371b362dd129', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.013, 'Rank IC': 0.016, 'Rank ICIR': 0.1}, 'data_train_vec': ['2022-08-15', '2025-08-14'], 'train_time_vec': ['2026-08-15', '2026-08-15'], 'rank_icir': '0.100', 'weight': '0.067'}

	Recorder: c3a24359590245bda09ac8eaa8e0d03c

		Model: {'id': 'c3a24359590245bda09ac8eaa8e0d03c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.083, 'Rank IC': 0.015, 'Rank ICIR': 0.125}, 'data_train_vec': ['2023-08-15', '2025-11-14'], 'train_time_vec': ['2026-08-15', '2026-08-15'], 'rank_icir': '0.125', 'weight': '0.084'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260815_13 123086728165434519 (Recorders: 2/5)

	Recorder: 39e2e75ef32c403b812bbc7901b54b5e

		Model: {'id': '39e2e75ef32c403b812bbc7901b54b5e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.068, 'Rank IC': 0.026, 'Rank ICIR': 0.155}, 'data_train_vec': ['2021-08-15', '2025-05-14'], 'train_time_vec': ['2026-08-15', '2026-08-15'], 'rank_icir': '0.155', 'weight': '0.104'}

	Recorder: 59b1680071ef4c51a155b95a84d5e3db

		Model: {'id': '59b1680071ef4c51a155b95a84d5e3db', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.115, 'Rank IC': 0.035, 'Rank ICIR': 0.2}, 'data_train_vec': ['2022-08-15', '2025-08-14'], 'train_time_vec': ['2026-08-15', '2026-08-15'], 'rank_icir': '0.200', 'weight': '0.134'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260815_13 884228622716998878 (Recorders: 3/5)

	Recorder: 699430e21fd4450b88016d6885102b16

		Model: {'id': '699430e21fd4450b88016d6885102b16', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.025, 'Rank IC': 0.022, 'Rank ICIR': 0.139}, 'data_train_vec': ['2021-08-15', '2025-05-14'], 'train_time_vec': ['2026-08-15', '2026-08-15'], 'rank_icir': '0.139', 'weight': '0.093'}

	Recorder: 6a6d59f371ec47ed87f64a6fdfa2b120

		Model: {'id': '6a6d59f371ec47ed87f64a6fdfa2b120', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.123, 'Rank IC': 0.032, 'Rank ICIR': 0.207}, 'data_train_vec': ['2022-08-15', '2025-08-14'], 'train_time_vec': ['2026-08-15', '2026-08-15'], 'rank_icir': '0.207', 'weight': '0.139'}

	Recorder: ce48186a75d44d2a898374b188c0ead7

		Model: {'id': 'ce48186a75d44d2a898374b188c0ead7', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.041, 'ICIR': 0.124, 'Rank IC': 0.015, 'Rank ICIR': 0.061}, 'data_train_vec': ['2025-08-15', '2026-05-14'], 'train_time_vec': ['2026-08-15', '2026-08-15'], 'rank_icir': '0.061', 'weight': '0.041'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260815_12 948007376476636779 (Recorders: 1/5)

	Recorder: f5dcc1b1d9004749aa8036970fb84bca

		Model: {'id': 'f5dcc1b1d9004749aa8036970fb84bca', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.029, 'Rank IC': 0.03, 'Rank ICIR': 0.176}, 'data_train_vec': ['2021-08-15', '2025-05-14'], 'train_time_vec': ['2026-08-15', '2026-08-15'], 'rank_icir': '0.176', 'weight': '0.118'}

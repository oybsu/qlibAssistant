# params 
 {'predict_dates': [{'start': '2026-09-30', 'end': '2026-09-30'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260930_20 376474075349347544 (Recorders: 5/5)

	Recorder: 98af9288faa842e8b2015968a5161cee

		Model: {'id': '98af9288faa842e8b2015968a5161cee', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.105, 'Rank IC': 0.03, 'Rank ICIR': 0.196}, 'data_train_vec': ['2021-09-30', '2025-06-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.196', 'weight': '0.069'}

	Recorder: 2a54939a5a0c462a9ceb3891d3b16981

		Model: {'id': '2a54939a5a0c462a9ceb3891d3b16981', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.095, 'Rank IC': 0.034, 'Rank ICIR': 0.163}, 'data_train_vec': ['2022-09-30', '2025-09-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.163', 'weight': '0.058'}

	Recorder: f71e5df345fd4b49b37f18738106f6c5

		Model: {'id': 'f71e5df345fd4b49b37f18738106f6c5', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.035, 'Rank IC': 0.014, 'Rank ICIR': 0.07}, 'data_train_vec': ['2023-09-30', '2025-12-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.070', 'weight': '0.025'}

	Recorder: ecb81d38fbed42a78433b21dd3f0b873

		Model: {'id': 'ecb81d38fbed42a78433b21dd3f0b873', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.254, 'Rank IC': 0.014, 'Rank ICIR': 0.114}, 'data_train_vec': ['2024-09-30', '2026-03-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.114', 'weight': '0.040'}

	Recorder: 9bbb0d9eabbd4e81b59134144d128b18

		Model: {'id': '9bbb0d9eabbd4e81b59134144d128b18', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.194, 'Rank IC': 0.012, 'Rank ICIR': 0.117}, 'data_train_vec': ['2025-09-30', '2026-06-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.117', 'weight': '0.041'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260930_20 671869298377341958 (Recorders: 5/5)

	Recorder: 52778c65b8a14b50a3e240ee97cce916

		Model: {'id': '52778c65b8a14b50a3e240ee97cce916', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.225, 'Rank IC': 0.042, 'Rank ICIR': 0.245}, 'data_train_vec': ['2021-09-30', '2025-06-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.245', 'weight': '0.087'}

	Recorder: fcfdde1a33764e32a8db96cc446a73ab

		Model: {'id': 'fcfdde1a33764e32a8db96cc446a73ab', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.165, 'Rank IC': 0.035, 'Rank ICIR': 0.2}, 'data_train_vec': ['2022-09-30', '2025-09-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.200', 'weight': '0.071'}

	Recorder: 52cb01637dfc47cf8a5b729d284b6492

		Model: {'id': '52cb01637dfc47cf8a5b729d284b6492', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.057, 'Rank IC': 0.017, 'Rank ICIR': 0.084}, 'data_train_vec': ['2023-09-30', '2025-12-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.084', 'weight': '0.030'}

	Recorder: ed9f320806d743668590c5b331a0779e

		Model: {'id': 'ed9f320806d743668590c5b331a0779e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.04, 'Rank IC': 0.008, 'Rank ICIR': 0.054}, 'data_train_vec': ['2024-09-30', '2026-03-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.054', 'weight': '0.019'}

	Recorder: 8dd122470cde4c2e9e1c44a5810a5743

		Model: {'id': '8dd122470cde4c2e9e1c44a5810a5743', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.043, 'Rank IC': 0.005, 'Rank ICIR': 0.049}, 'data_train_vec': ['2025-09-30', '2026-06-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.049', 'weight': '0.017'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260930_18 657937093233241552 (Recorders: 3/5)

	Recorder: 87b30e07ac294606972953d60470e243

		Model: {'id': '87b30e07ac294606972953d60470e243', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.039, 'ICIR': 0.194, 'Rank IC': 0.049, 'Rank ICIR': 0.281}, 'data_train_vec': ['2021-09-30', '2025-06-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.281', 'weight': '0.099'}

	Recorder: 5a5b11b41bac4e62b9fe34096a7bc1d4

		Model: {'id': '5a5b11b41bac4e62b9fe34096a7bc1d4', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.122, 'Rank IC': 0.03, 'Rank ICIR': 0.155}, 'data_train_vec': ['2022-09-30', '2025-09-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.155', 'weight': '0.055'}

	Recorder: dfa8a6c36df24ed0adcaf3168396dcb0

		Model: {'id': 'dfa8a6c36df24ed0adcaf3168396dcb0', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.041, 'Rank IC': 0.012, 'Rank ICIR': 0.056}, 'data_train_vec': ['2023-09-30', '2025-12-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.056', 'weight': '0.020'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260930_18 831585353935181665 (Recorders: 5/5)

	Recorder: ea55688c68b14aea81e297a2fc09fa77

		Model: {'id': 'ea55688c68b14aea81e297a2fc09fa77', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.037, 'ICIR': 0.182, 'Rank IC': 0.04, 'Rank ICIR': 0.227}, 'data_train_vec': ['2021-09-30', '2025-06-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.227', 'weight': '0.080'}

	Recorder: 22102e83e7ef4a9b9fb1fa27e79fc343

		Model: {'id': '22102e83e7ef4a9b9fb1fa27e79fc343', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.144, 'Rank IC': 0.02, 'Rank ICIR': 0.108}, 'data_train_vec': ['2022-09-30', '2025-09-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.108', 'weight': '0.038'}

	Recorder: b02234a5660b4db88731e4cc43a7293f

		Model: {'id': 'b02234a5660b4db88731e4cc43a7293f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.031, 'Rank IC': 0.003, 'Rank ICIR': 0.014}, 'data_train_vec': ['2023-09-30', '2025-12-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.014', 'weight': '0.005'}

	Recorder: 63e7c435727740e79b76983b1c1d1792

		Model: {'id': '63e7c435727740e79b76983b1c1d1792', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.054, 'ICIR': 0.244, 'Rank IC': 0.029, 'Rank ICIR': 0.159}, 'data_train_vec': ['2024-09-30', '2026-03-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.159', 'weight': '0.056'}

	Recorder: 34660a0154f84959a7d7a47a5f26019f

		Model: {'id': '34660a0154f84959a7d7a47a5f26019f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.121, 'Rank IC': 0.014, 'Rank ICIR': 0.103}, 'data_train_vec': ['2025-09-30', '2026-06-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.103', 'weight': '0.036'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260930_17 613654750717178988 (Recorders: 2/5)

	Recorder: e1b9ece021114ade893f916e0d52e871

		Model: {'id': 'e1b9ece021114ade893f916e0d52e871', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.023, 'Rank IC': 0.043, 'Rank ICIR': 0.26}, 'data_train_vec': ['2021-09-30', '2025-06-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.260', 'weight': '0.092'}

	Recorder: dcb05bef8f53420d813ac9b9fc78e661

		Model: {'id': 'dcb05bef8f53420d813ac9b9fc78e661', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.046, 'ICIR': 0.225, 'Rank IC': 0.025, 'Rank ICIR': 0.175}, 'data_train_vec': ['2024-09-30', '2026-03-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.175', 'weight': '0.062'}

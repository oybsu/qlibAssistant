# params 
 {'predict_dates': [{'start': '2026-06-11', 'end': '2026-06-11'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260611_18 686175160063290982 (Recorders: 4/5)

	Recorder: 17e1e931a04943f2986b5ef5e64e0657

		Model: {'id': '17e1e931a04943f2986b5ef5e64e0657', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.046, 'Rank IC': 0.026, 'Rank ICIR': 0.156}, 'data_train_vec': ['2021-06-11', '2025-03-10'], 'train_time_vec': ['2026-06-11', '2026-06-11'], 'rank_icir': '0.156', 'weight': '0.032'}

	Recorder: f8730859f1174355ab871b6d0ecd57c9

		Model: {'id': 'f8730859f1174355ab871b6d0ecd57c9', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.124, 'Rank IC': 0.04, 'Rank ICIR': 0.258}, 'data_train_vec': ['2022-06-11', '2025-06-10'], 'train_time_vec': ['2026-06-11', '2026-06-11'], 'rank_icir': '0.258', 'weight': '0.053'}

	Recorder: db4d18d4a01e48138d68aee1f759e1c2

		Model: {'id': 'db4d18d4a01e48138d68aee1f759e1c2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.288, 'Rank IC': 0.047, 'Rank ICIR': 0.348}, 'data_train_vec': ['2023-06-11', '2025-09-10'], 'train_time_vec': ['2026-06-11', '2026-06-11'], 'rank_icir': '0.348', 'weight': '0.071'}

	Recorder: 4ecc0ba9d38c430f9e6a51b161e9ff75

		Model: {'id': '4ecc0ba9d38c430f9e6a51b161e9ff75', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.111, 'Rank IC': 0.022, 'Rank ICIR': 0.21}, 'data_train_vec': ['2024-06-11', '2025-12-10'], 'train_time_vec': ['2026-06-11', '2026-06-11'], 'rank_icir': '0.210', 'weight': '0.043'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260611_18 863219065026068275 (Recorders: 4/5)

	Recorder: 8f1dd9419d154b0989adaed25ec6a209

		Model: {'id': '8f1dd9419d154b0989adaed25ec6a209', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.044, 'Rank IC': 0.025, 'Rank ICIR': 0.152}, 'data_train_vec': ['2021-06-11', '2025-03-10'], 'train_time_vec': ['2026-06-11', '2026-06-11'], 'rank_icir': '0.152', 'weight': '0.031'}

	Recorder: 9c028181dfd942ae8b2eafceeb4de577

		Model: {'id': '9c028181dfd942ae8b2eafceeb4de577', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.084, 'Rank IC': 0.041, 'Rank ICIR': 0.302}, 'data_train_vec': ['2022-06-11', '2025-06-10'], 'train_time_vec': ['2026-06-11', '2026-06-11'], 'rank_icir': '0.302', 'weight': '0.062'}

	Recorder: 7c7104b754e648178dd07ab9fba0212c

		Model: {'id': '7c7104b754e648178dd07ab9fba0212c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.217, 'Rank IC': 0.039, 'Rank ICIR': 0.286}, 'data_train_vec': ['2023-06-11', '2025-09-10'], 'train_time_vec': ['2026-06-11', '2026-06-11'], 'rank_icir': '0.286', 'weight': '0.059'}

	Recorder: 87fbf8e30e31429bafd52a07b02cba12

		Model: {'id': '87fbf8e30e31429bafd52a07b02cba12', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.192, 'Rank IC': 0.029, 'Rank ICIR': 0.283}, 'data_train_vec': ['2024-06-11', '2025-12-10'], 'train_time_vec': ['2026-06-11', '2026-06-11'], 'rank_icir': '0.283', 'weight': '0.058'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260611_16 347677793294337972 (Recorders: 3/5)

	Recorder: 7a782457c239454586869b3c77b829e7

		Model: {'id': '7a782457c239454586869b3c77b829e7', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.146, 'Rank IC': 0.048, 'Rank ICIR': 0.325}, 'data_train_vec': ['2021-06-11', '2025-03-10'], 'train_time_vec': ['2026-06-11', '2026-06-11'], 'rank_icir': '0.325', 'weight': '0.067'}

	Recorder: 4a99f4aaf0c245228f963198c790aafa

		Model: {'id': '4a99f4aaf0c245228f963198c790aafa', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.16, 'Rank IC': 0.059, 'Rank ICIR': 0.348}, 'data_train_vec': ['2022-06-11', '2025-06-10'], 'train_time_vec': ['2026-06-11', '2026-06-11'], 'rank_icir': '0.348', 'weight': '0.071'}

	Recorder: 48958aa6f8fa480bac47ce6f1355a170

		Model: {'id': '48958aa6f8fa480bac47ce6f1355a170', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.198, 'Rank IC': 0.047, 'Rank ICIR': 0.318}, 'data_train_vec': ['2023-06-11', '2025-09-10'], 'train_time_vec': ['2026-06-11', '2026-06-11'], 'rank_icir': '0.318', 'weight': '0.065'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260611_16 121710659130819498 (Recorders: 4/5)

	Recorder: 1090f4e6f9aa453a92ea625cbe1e6b3e

		Model: {'id': '1090f4e6f9aa453a92ea625cbe1e6b3e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.119, 'Rank IC': 0.043, 'Rank ICIR': 0.368}, 'data_train_vec': ['2021-06-11', '2025-03-10'], 'train_time_vec': ['2026-06-11', '2026-06-11'], 'rank_icir': '0.368', 'weight': '0.076'}

	Recorder: a3b9a6b7958b4d47bec826e25121dfd1

		Model: {'id': 'a3b9a6b7958b4d47bec826e25121dfd1', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.036, 'Rank IC': 0.043, 'Rank ICIR': 0.316}, 'data_train_vec': ['2022-06-11', '2025-06-10'], 'train_time_vec': ['2026-06-11', '2026-06-11'], 'rank_icir': '0.316', 'weight': '0.065'}

	Recorder: 03b112f90ec449a3a8161c6cfc19b70a

		Model: {'id': '03b112f90ec449a3a8161c6cfc19b70a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.128, 'Rank IC': 0.038, 'Rank ICIR': 0.333}, 'data_train_vec': ['2023-06-11', '2025-09-10'], 'train_time_vec': ['2026-06-11', '2026-06-11'], 'rank_icir': '0.333', 'weight': '0.068'}

	Recorder: 9c9d5be53adc4a2fa03fe6ab5706f116

		Model: {'id': '9c9d5be53adc4a2fa03fe6ab5706f116', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.04, 'Rank IC': 0.013, 'Rank ICIR': 0.082}, 'data_train_vec': ['2024-06-11', '2025-12-10'], 'train_time_vec': ['2026-06-11', '2026-06-11'], 'rank_icir': '0.082', 'weight': '0.017'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260611_16 547946540959892610 (Recorders: 3/5)

	Recorder: 13fac196457742b18584fc0abe5c85e0

		Model: {'id': '13fac196457742b18584fc0abe5c85e0', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.073, 'Rank IC': 0.042, 'Rank ICIR': 0.267}, 'data_train_vec': ['2021-06-11', '2025-03-10'], 'train_time_vec': ['2026-06-11', '2026-06-11'], 'rank_icir': '0.267', 'weight': '0.055'}

	Recorder: e50d2583478b440fba7ea87bbee62d8f

		Model: {'id': 'e50d2583478b440fba7ea87bbee62d8f', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.059, 'Rank IC': 0.054, 'Rank ICIR': 0.301}, 'data_train_vec': ['2022-06-11', '2025-06-10'], 'train_time_vec': ['2026-06-11', '2026-06-11'], 'rank_icir': '0.301', 'weight': '0.062'}

	Recorder: 7c78d742c17f41e88d7b4ded3f5371dd

		Model: {'id': '7c78d742c17f41e88d7b4ded3f5371dd', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.064, 'Rank IC': 0.035, 'Rank ICIR': 0.221}, 'data_train_vec': ['2023-06-11', '2025-09-10'], 'train_time_vec': ['2026-06-11', '2026-06-11'], 'rank_icir': '0.221', 'weight': '0.045'}

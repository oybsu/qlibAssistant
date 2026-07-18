# params 
 {'predict_dates': [{'start': '2026-07-17', 'end': '2026-07-17'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260718_16 918514910373818301 (Recorders: 2/5)

	Recorder: 74434eb1031444f3969566ca8b532e2b

		Model: {'id': '74434eb1031444f3969566ca8b532e2b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.079, 'Rank IC': 0.033, 'Rank ICIR': 0.189}, 'data_train_vec': ['2021-07-18', '2025-04-17'], 'train_time_vec': ['2026-07-18', '2026-07-18'], 'rank_icir': '0.189', 'weight': '0.156'}

	Recorder: fb59254180474a0d94e287e9bcc7d22b

		Model: {'id': 'fb59254180474a0d94e287e9bcc7d22b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.113, 'Rank IC': 0.024, 'Rank ICIR': 0.203}, 'data_train_vec': ['2023-07-18', '2025-10-17'], 'train_time_vec': ['2026-07-18', '2026-07-18'], 'rank_icir': '0.203', 'weight': '0.167'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260718_16 280685750221245122 (Recorders: 2/5)

	Recorder: f309fea2913e441687e6011136637a5f

		Model: {'id': 'f309fea2913e441687e6011136637a5f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.037, 'Rank IC': 0.031, 'Rank ICIR': 0.202}, 'data_train_vec': ['2021-07-18', '2025-04-17'], 'train_time_vec': ['2026-07-18', '2026-07-18'], 'rank_icir': '0.202', 'weight': '0.166'}

	Recorder: c7f4b7fe47db4ff4a1be03d31ee2286f

		Model: {'id': 'c7f4b7fe47db4ff4a1be03d31ee2286f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.162, 'Rank IC': 0.024, 'Rank ICIR': 0.203}, 'data_train_vec': ['2023-07-18', '2025-10-17'], 'train_time_vec': ['2026-07-18', '2026-07-18'], 'rank_icir': '0.203', 'weight': '0.167'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260718_13 860337589715708575 (Recorders: 2/5)

	Recorder: 5d194920849d4545b8bbe71105c21c5f

		Model: {'id': '5d194920849d4545b8bbe71105c21c5f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.073, 'Rank IC': 0.039, 'Rank ICIR': 0.247}, 'data_train_vec': ['2021-07-18', '2025-04-17'], 'train_time_vec': ['2026-07-18', '2026-07-18'], 'rank_icir': '0.247', 'weight': '0.203'}

	Recorder: 9b7526c72116461b8dc176b820a024c0

		Model: {'id': '9b7526c72116461b8dc176b820a024c0', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.041, 'Rank IC': 0.026, 'Rank ICIR': 0.171}, 'data_train_vec': ['2022-07-18', '2025-07-17'], 'train_time_vec': ['2026-07-18', '2026-07-18'], 'rank_icir': '0.171', 'weight': '0.141'}

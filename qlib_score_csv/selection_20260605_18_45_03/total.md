# params 
 {'predict_dates': [{'start': '2026-06-05', 'end': '2026-06-05'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260605_18 429280940109099059 (Recorders: 2/5)

	Recorder: d5b209eb534843899db93f98aaf12211

		Model: {'id': 'd5b209eb534843899db93f98aaf12211', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.187, 'Rank IC': 0.048, 'Rank ICIR': 0.282}, 'data_train_vec': ['2023-06-05', '2025-09-04'], 'train_time_vec': ['2026-06-05', '2026-06-05'], 'rank_icir': '0.282', 'weight': '0.091'}

	Recorder: a533591266b841c1b9b98521120a6a2a

		Model: {'id': 'a533591266b841c1b9b98521120a6a2a', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.016, 'Rank IC': 0.015, 'Rank ICIR': 0.126}, 'data_train_vec': ['2024-06-05', '2025-12-04'], 'train_time_vec': ['2026-06-05', '2026-06-05'], 'rank_icir': '0.126', 'weight': '0.041'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260605_18 511819254515074755 (Recorders: 4/5)

	Recorder: ba1c9b265be842f2985c50a2f866fd68

		Model: {'id': 'ba1c9b265be842f2985c50a2f866fd68', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.008, 'Rank IC': 0.028, 'Rank ICIR': 0.185}, 'data_train_vec': ['2021-06-05', '2025-03-04'], 'train_time_vec': ['2026-06-05', '2026-06-05'], 'rank_icir': '0.185', 'weight': '0.060'}

	Recorder: c66b7455be4c4c05b050eb8b68229578

		Model: {'id': 'c66b7455be4c4c05b050eb8b68229578', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.227, 'Rank IC': 0.036, 'Rank ICIR': 0.293}, 'data_train_vec': ['2023-06-05', '2025-09-04'], 'train_time_vec': ['2026-06-05', '2026-06-05'], 'rank_icir': '0.293', 'weight': '0.095'}

	Recorder: 2b8329d079c04b08905b0437a87828cc

		Model: {'id': '2b8329d079c04b08905b0437a87828cc', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.022, 'Rank IC': 0.008, 'Rank ICIR': 0.088}, 'data_train_vec': ['2024-06-05', '2025-12-04'], 'train_time_vec': ['2026-06-05', '2026-06-05'], 'rank_icir': '0.088', 'weight': '0.029'}

	Recorder: 0de1b267b283450e99cd3a42cd1ea463

		Model: {'id': '0de1b267b283450e99cd3a42cd1ea463', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.044, 'ICIR': 0.189, 'Rank IC': 0.007, 'Rank ICIR': 0.032}, 'data_train_vec': ['2025-06-05', '2026-03-04'], 'train_time_vec': ['2026-06-05', '2026-06-05'], 'rank_icir': '0.032', 'weight': '0.010'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260605_15 986635113056496030 (Recorders: 3/5)

	Recorder: f2e9424781784765b862090d3133ab2f

		Model: {'id': 'f2e9424781784765b862090d3133ab2f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.14, 'Rank IC': 0.047, 'Rank ICIR': 0.323}, 'data_train_vec': ['2021-06-05', '2025-03-04'], 'train_time_vec': ['2026-06-05', '2026-06-05'], 'rank_icir': '0.323', 'weight': '0.105'}

	Recorder: e82ca348cbbe49e1ac37325c760ed6ef

		Model: {'id': 'e82ca348cbbe49e1ac37325c760ed6ef', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.069, 'Rank IC': 0.043, 'Rank ICIR': 0.242}, 'data_train_vec': ['2022-06-05', '2025-06-04'], 'train_time_vec': ['2026-06-05', '2026-06-05'], 'rank_icir': '0.242', 'weight': '0.078'}

	Recorder: ba8b2d54895549f7a5c4a8d8311b81ec

		Model: {'id': 'ba8b2d54895549f7a5c4a8d8311b81ec', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.223, 'Rank IC': 0.048, 'Rank ICIR': 0.326}, 'data_train_vec': ['2023-06-05', '2025-09-04'], 'train_time_vec': ['2026-06-05', '2026-06-05'], 'rank_icir': '0.326', 'weight': '0.106'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260605_15 499081917332900134 (Recorders: 4/5)

	Recorder: f6d67edc16174126af75157143f744f1

		Model: {'id': 'f6d67edc16174126af75157143f744f1', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.121, 'Rank IC': 0.042, 'Rank ICIR': 0.362}, 'data_train_vec': ['2021-06-05', '2025-03-04'], 'train_time_vec': ['2026-06-05', '2026-06-05'], 'rank_icir': '0.362', 'weight': '0.117'}

	Recorder: 58ec7e96dc1548eaaf80297b11f99fb4

		Model: {'id': '58ec7e96dc1548eaaf80297b11f99fb4', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.044, 'Rank IC': 0.032, 'Rank ICIR': 0.29}, 'data_train_vec': ['2023-06-05', '2025-09-04'], 'train_time_vec': ['2026-06-05', '2026-06-05'], 'rank_icir': '0.290', 'weight': '0.094'}

	Recorder: 990e4bcc747f493c9a72b0e025be14d1

		Model: {'id': '990e4bcc747f493c9a72b0e025be14d1', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.039, 'Rank IC': 0.013, 'Rank ICIR': 0.088}, 'data_train_vec': ['2024-06-05', '2025-12-04'], 'train_time_vec': ['2026-06-05', '2026-06-05'], 'rank_icir': '0.088', 'weight': '0.029'}

	Recorder: 1eba107a57ed4966966cf3c9a558d4ef

		Model: {'id': '1eba107a57ed4966966cf3c9a558d4ef', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.098, 'Rank IC': 0.007, 'Rank ICIR': 0.028}, 'data_train_vec': ['2025-06-05', '2026-03-04'], 'train_time_vec': ['2026-06-05', '2026-06-05'], 'rank_icir': '0.028', 'weight': '0.009'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260605_15 407209615726325641 (Recorders: 2/5)

	Recorder: 0d582faf9cfc4a6794d00d02c80e2db4

		Model: {'id': '0d582faf9cfc4a6794d00d02c80e2db4', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.087, 'Rank IC': 0.033, 'Rank ICIR': 0.205}, 'data_train_vec': ['2021-06-05', '2025-03-04'], 'train_time_vec': ['2026-06-05', '2026-06-05'], 'rank_icir': '0.205', 'weight': '0.066'}

	Recorder: 0e94f3a694314055a0031cb9ba061fd7

		Model: {'id': '0e94f3a694314055a0031cb9ba061fd7', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.049, 'Rank IC': 0.034, 'Rank ICIR': 0.213}, 'data_train_vec': ['2023-06-05', '2025-09-04'], 'train_time_vec': ['2026-06-05', '2026-06-05'], 'rank_icir': '0.213', 'weight': '0.069'}

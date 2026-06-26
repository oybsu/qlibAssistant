# params 
 {'predict_dates': [{'start': '2026-06-26', 'end': '2026-06-26'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260626_17 913287031053700189 (Recorders: 2/5)

	Recorder: b5c09ff8f6d0410ba4ddbc43fcd3d2e2

		Model: {'id': 'b5c09ff8f6d0410ba4ddbc43fcd3d2e2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.267, 'Rank IC': 0.028, 'Rank ICIR': 0.232}, 'data_train_vec': ['2023-06-26', '2025-09-25'], 'train_time_vec': ['2026-06-26', '2026-06-26'], 'rank_icir': '0.232', 'weight': '0.104'}

	Recorder: b8e72d7174594b92b9576faf76d8d91d

		Model: {'id': 'b8e72d7174594b92b9576faf76d8d91d', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.268, 'Rank IC': 0.03, 'Rank ICIR': 0.311}, 'data_train_vec': ['2024-06-26', '2025-12-25'], 'train_time_vec': ['2026-06-26', '2026-06-26'], 'rank_icir': '0.311', 'weight': '0.140'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260626_17 996511300919867163 (Recorders: 3/5)

	Recorder: d760fdc0a2d043c19c0cc01329c90c55

		Model: {'id': 'd760fdc0a2d043c19c0cc01329c90c55', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.249, 'Rank IC': 0.03, 'Rank ICIR': 0.249}, 'data_train_vec': ['2023-06-26', '2025-09-25'], 'train_time_vec': ['2026-06-26', '2026-06-26'], 'rank_icir': '0.249', 'weight': '0.112'}

	Recorder: e98da71addcf454aa19ef98516a2d65a

		Model: {'id': 'e98da71addcf454aa19ef98516a2d65a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.264, 'Rank IC': 0.024, 'Rank ICIR': 0.234}, 'data_train_vec': ['2024-06-26', '2025-12-25'], 'train_time_vec': ['2026-06-26', '2026-06-26'], 'rank_icir': '0.234', 'weight': '0.105'}

	Recorder: 83466affffee4b1d8bf11a942fad2555

		Model: {'id': '83466affffee4b1d8bf11a942fad2555', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.041, 'ICIR': 0.165, 'Rank IC': 0.005, 'Rank ICIR': 0.024}, 'data_train_vec': ['2025-06-26', '2026-03-25'], 'train_time_vec': ['2026-06-26', '2026-06-26'], 'rank_icir': '0.024', 'weight': '0.011'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260626_14 386525632602962056 (Recorders: 3/5)

	Recorder: 689e2e352057405ca86e25f965411166

		Model: {'id': '689e2e352057405ca86e25f965411166', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.048, 'Rank IC': 0.041, 'Rank ICIR': 0.246}, 'data_train_vec': ['2021-06-26', '2025-03-25'], 'train_time_vec': ['2026-06-26', '2026-06-26'], 'rank_icir': '0.246', 'weight': '0.110'}

	Recorder: d711e2108a5e4713b2c2116c071734bf

		Model: {'id': 'd711e2108a5e4713b2c2116c071734bf', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.064, 'Rank IC': 0.043, 'Rank ICIR': 0.257}, 'data_train_vec': ['2022-06-26', '2025-06-25'], 'train_time_vec': ['2026-06-26', '2026-06-26'], 'rank_icir': '0.257', 'weight': '0.115'}

	Recorder: 7574949d3fc94fc69cada5431b996f48

		Model: {'id': '7574949d3fc94fc69cada5431b996f48', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.179, 'Rank IC': 0.035, 'Rank ICIR': 0.268}, 'data_train_vec': ['2023-06-26', '2025-09-25'], 'train_time_vec': ['2026-06-26', '2026-06-26'], 'rank_icir': '0.268', 'weight': '0.120'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260626_14 840074331337089984 (Recorders: 2/5)

	Recorder: df2f66c0809d4d5f923c6defaee4e734

		Model: {'id': 'df2f66c0809d4d5f923c6defaee4e734', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.008, 'Rank IC': 0.037, 'Rank ICIR': 0.221}, 'data_train_vec': ['2021-06-26', '2025-03-25'], 'train_time_vec': ['2026-06-26', '2026-06-26'], 'rank_icir': '0.221', 'weight': '0.099'}

	Recorder: e888fc2c45ed4c18bf526a1e466bbdd9

		Model: {'id': 'e888fc2c45ed4c18bf526a1e466bbdd9', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.078, 'Rank IC': 0.026, 'Rank ICIR': 0.186}, 'data_train_vec': ['2023-06-26', '2025-09-25'], 'train_time_vec': ['2026-06-26', '2026-06-26'], 'rank_icir': '0.186', 'weight': '0.083'}

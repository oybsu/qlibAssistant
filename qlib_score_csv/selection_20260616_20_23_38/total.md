# params 
 {'predict_dates': [{'start': '2026-06-16', 'end': '2026-06-16'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260616_19 232890208549256881 (Recorders: 2/5)

	Recorder: fcac6ef84eb14038acf7dfcf6b998e25

		Model: {'id': 'fcac6ef84eb14038acf7dfcf6b998e25', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.139, 'Rank IC': 0.032, 'Rank ICIR': 0.22}, 'data_train_vec': ['2023-06-16', '2025-09-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.220', 'weight': '0.049'}

	Recorder: ff7d4eb480594bbe9c681897368c8851

		Model: {'id': 'ff7d4eb480594bbe9c681897368c8851', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.107, 'Rank IC': 0.042, 'Rank ICIR': 0.335}, 'data_train_vec': ['2024-06-16', '2025-12-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.335', 'weight': '0.074'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260616_19 191162272147601546 (Recorders: 4/5)

	Recorder: 92046d0879c244129ef3b341ddd4088b

		Model: {'id': '92046d0879c244129ef3b341ddd4088b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.04, 'Rank IC': 0.023, 'Rank ICIR': 0.161}, 'data_train_vec': ['2021-06-16', '2025-03-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.161', 'weight': '0.036'}

	Recorder: 5b46dbc6d8b34c98a19ace2f7ad92134

		Model: {'id': '5b46dbc6d8b34c98a19ace2f7ad92134', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.032, 'Rank IC': 0.037, 'Rank ICIR': 0.28}, 'data_train_vec': ['2022-06-16', '2025-06-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.280', 'weight': '0.062'}

	Recorder: 8b2971f7005f45fb9d459a792291b5db

		Model: {'id': '8b2971f7005f45fb9d459a792291b5db', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.226, 'Rank IC': 0.036, 'Rank ICIR': 0.279}, 'data_train_vec': ['2023-06-16', '2025-09-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.279', 'weight': '0.062'}

	Recorder: 13f897b0f2f44d9ab9c926e5c2cfc6fc

		Model: {'id': '13f897b0f2f44d9ab9c926e5c2cfc6fc', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.373, 'Rank IC': 0.034, 'Rank ICIR': 0.364}, 'data_train_vec': ['2024-06-16', '2025-12-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.364', 'weight': '0.081'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260616_17 903380119648400338 (Recorders: 4/5)

	Recorder: 055c1295c64f466291515b71b56f86fd

		Model: {'id': '055c1295c64f466291515b71b56f86fd', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.143, 'Rank IC': 0.046, 'Rank ICIR': 0.31}, 'data_train_vec': ['2021-06-16', '2025-03-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.310', 'weight': '0.069'}

	Recorder: 6137a43849184e6caeb59b1ef989b373

		Model: {'id': '6137a43849184e6caeb59b1ef989b373', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.163, 'Rank IC': 0.056, 'Rank ICIR': 0.327}, 'data_train_vec': ['2022-06-16', '2025-06-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.327', 'weight': '0.072'}

	Recorder: b27843050b70429d85a040b74985e392

		Model: {'id': 'b27843050b70429d85a040b74985e392', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.172, 'Rank IC': 0.039, 'Rank ICIR': 0.268}, 'data_train_vec': ['2023-06-16', '2025-09-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.268', 'weight': '0.059'}

	Recorder: 13ded419372f4d95b540c77982399201

		Model: {'id': '13ded419372f4d95b540c77982399201', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.241, 'Rank IC': 0.034, 'Rank ICIR': 0.298}, 'data_train_vec': ['2024-06-16', '2025-12-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.298', 'weight': '0.066'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260616_17 881682186467240309 (Recorders: 4/5)

	Recorder: 3b8d0780f53348359175a5e70585c79c

		Model: {'id': '3b8d0780f53348359175a5e70585c79c', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.085, 'Rank IC': 0.04, 'Rank ICIR': 0.344}, 'data_train_vec': ['2021-06-16', '2025-03-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.344', 'weight': '0.076'}

	Recorder: 89d4a2a151674942bb46a1ecb45695de

		Model: {'id': '89d4a2a151674942bb46a1ecb45695de', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.024, 'Rank IC': 0.041, 'Rank ICIR': 0.305}, 'data_train_vec': ['2022-06-16', '2025-06-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.305', 'weight': '0.068'}

	Recorder: a3df25f3f73c4f0ba67b432a93d8d202

		Model: {'id': 'a3df25f3f73c4f0ba67b432a93d8d202', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.075, 'Rank IC': 0.033, 'Rank ICIR': 0.286}, 'data_train_vec': ['2023-06-16', '2025-09-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.286', 'weight': '0.063'}

	Recorder: 3a636593f7384842bef3e8c67dcd4cf7

		Model: {'id': '3a636593f7384842bef3e8c67dcd4cf7', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.185, 'Rank IC': 0.029, 'Rank ICIR': 0.2}, 'data_train_vec': ['2024-06-16', '2025-12-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.200', 'weight': '0.044'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260616_17 653705831875143242 (Recorders: 2/5)

	Recorder: 4a6018ba6ea44977b2a645d52c0c6a31

		Model: {'id': '4a6018ba6ea44977b2a645d52c0c6a31', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.035, 'Rank IC': 0.039, 'Rank ICIR': 0.239}, 'data_train_vec': ['2021-06-16', '2025-03-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.239', 'weight': '0.053'}

	Recorder: 14cb03ae573344a68c38c99df1dfdf14

		Model: {'id': '14cb03ae573344a68c38c99df1dfdf14', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.11, 'Rank IC': 0.024, 'Rank ICIR': 0.297}, 'data_train_vec': ['2024-06-16', '2025-12-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.297', 'weight': '0.066'}

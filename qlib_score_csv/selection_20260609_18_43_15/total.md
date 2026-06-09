# params 
 {'predict_dates': [{'start': '2026-06-09', 'end': '2026-06-09'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260609_18 863128411795230576 (Recorders: 3/5)

	Recorder: 032489497c604c9998eea08310bb1385

		Model: {'id': '032489497c604c9998eea08310bb1385', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.018, 'Rank IC': 0.029, 'Rank ICIR': 0.174}, 'data_train_vec': ['2021-06-09', '2025-03-08'], 'train_time_vec': ['2026-06-09', '2026-06-09'], 'rank_icir': '0.174', 'weight': '0.042'}

	Recorder: 26d26651f3304d219f8a06263847a6ee

		Model: {'id': '26d26651f3304d219f8a06263847a6ee', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.212, 'Rank IC': 0.039, 'Rank ICIR': 0.238}, 'data_train_vec': ['2023-06-09', '2025-09-08'], 'train_time_vec': ['2026-06-09', '2026-06-09'], 'rank_icir': '0.238', 'weight': '0.057'}

	Recorder: feda379786ef4bb695e53b6b67fa08b2

		Model: {'id': 'feda379786ef4bb695e53b6b67fa08b2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.189, 'Rank IC': 0.031, 'Rank ICIR': 0.272}, 'data_train_vec': ['2024-06-09', '2025-12-08'], 'train_time_vec': ['2026-06-09', '2026-06-09'], 'rank_icir': '0.272', 'weight': '0.066'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260609_18 793322809907107998 (Recorders: 3/5)

	Recorder: 574c1923b5744cf3862b5d53ed3ab0e6

		Model: {'id': '574c1923b5744cf3862b5d53ed3ab0e6', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.054, 'Rank IC': 0.03, 'Rank ICIR': 0.184}, 'data_train_vec': ['2021-06-09', '2025-03-08'], 'train_time_vec': ['2026-06-09', '2026-06-09'], 'rank_icir': '0.184', 'weight': '0.044'}

	Recorder: 03dfbc046a9e4215a026da188459e300

		Model: {'id': '03dfbc046a9e4215a026da188459e300', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.254, 'Rank IC': 0.04, 'Rank ICIR': 0.321}, 'data_train_vec': ['2023-06-09', '2025-09-08'], 'train_time_vec': ['2026-06-09', '2026-06-09'], 'rank_icir': '0.321', 'weight': '0.077'}

	Recorder: b9a733221ec84945b497f83131da5288

		Model: {'id': 'b9a733221ec84945b497f83131da5288', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.2, 'Rank IC': 0.025, 'Rank ICIR': 0.255}, 'data_train_vec': ['2024-06-09', '2025-12-08'], 'train_time_vec': ['2026-06-09', '2026-06-09'], 'rank_icir': '0.255', 'weight': '0.061'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260609_15 450544446857400858 (Recorders: 4/5)

	Recorder: 5587dd0919f34e87b298e473f12bfe4c

		Model: {'id': '5587dd0919f34e87b298e473f12bfe4c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.137, 'Rank IC': 0.048, 'Rank ICIR': 0.316}, 'data_train_vec': ['2021-06-09', '2025-03-08'], 'train_time_vec': ['2026-06-09', '2026-06-09'], 'rank_icir': '0.316', 'weight': '0.076'}

	Recorder: e284618452a14588a2f30603ef7c4a51

		Model: {'id': 'e284618452a14588a2f30603ef7c4a51', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.116, 'Rank IC': 0.052, 'Rank ICIR': 0.3}, 'data_train_vec': ['2022-06-09', '2025-06-08'], 'train_time_vec': ['2026-06-09', '2026-06-09'], 'rank_icir': '0.300', 'weight': '0.072'}

	Recorder: 26743c3eae604b839e86f2a1474141ea

		Model: {'id': '26743c3eae604b839e86f2a1474141ea', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.278, 'Rank IC': 0.057, 'Rank ICIR': 0.386}, 'data_train_vec': ['2023-06-09', '2025-09-08'], 'train_time_vec': ['2026-06-09', '2026-06-09'], 'rank_icir': '0.386', 'weight': '0.093'}

	Recorder: 29ab8861a3794909850c426ab63fb760

		Model: {'id': '29ab8861a3794909850c426ab63fb760', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.074, 'Rank IC': 0.014, 'Rank ICIR': 0.121}, 'data_train_vec': ['2024-06-09', '2025-12-08'], 'train_time_vec': ['2026-06-09', '2026-06-09'], 'rank_icir': '0.121', 'weight': '0.029'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260609_15 476102863023311573 (Recorders: 3/5)

	Recorder: 45acece5771f49d28d60f3b1befd36be

		Model: {'id': '45acece5771f49d28d60f3b1befd36be', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.113, 'Rank IC': 0.042, 'Rank ICIR': 0.361}, 'data_train_vec': ['2021-06-09', '2025-03-08'], 'train_time_vec': ['2026-06-09', '2026-06-09'], 'rank_icir': '0.361', 'weight': '0.087'}

	Recorder: 482832d293d64819bf01c5c955702ac6

		Model: {'id': '482832d293d64819bf01c5c955702ac6', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.112, 'Rank IC': 0.039, 'Rank ICIR': 0.344}, 'data_train_vec': ['2023-06-09', '2025-09-08'], 'train_time_vec': ['2026-06-09', '2026-06-09'], 'rank_icir': '0.344', 'weight': '0.083'}

	Recorder: 1a09fc31231a46debb6ab7e7b7e51562

		Model: {'id': '1a09fc31231a46debb6ab7e7b7e51562', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.075, 'Rank IC': 0.019, 'Rank ICIR': 0.131}, 'data_train_vec': ['2024-06-09', '2025-12-08'], 'train_time_vec': ['2026-06-09', '2026-06-09'], 'rank_icir': '0.131', 'weight': '0.032'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260609_15 531322702387761043 (Recorders: 3/5)

	Recorder: f0d9a7ee60d54dbe862b0dc28571706b

		Model: {'id': 'f0d9a7ee60d54dbe862b0dc28571706b', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.072, 'Rank IC': 0.036, 'Rank ICIR': 0.217}, 'data_train_vec': ['2021-06-09', '2025-03-08'], 'train_time_vec': ['2026-06-09', '2026-06-09'], 'rank_icir': '0.217', 'weight': '0.052'}

	Recorder: f4f60d8f43ae495db85c444e579170ea

		Model: {'id': 'f4f60d8f43ae495db85c444e579170ea', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.045, 'Rank IC': 0.048, 'Rank ICIR': 0.263}, 'data_train_vec': ['2022-06-09', '2025-06-08'], 'train_time_vec': ['2026-06-09', '2026-06-09'], 'rank_icir': '0.263', 'weight': '0.063'}

	Recorder: 5ba4432b64894d7abb75a0d6f1340fe5

		Model: {'id': '5ba4432b64894d7abb75a0d6f1340fe5', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.118, 'Rank IC': 0.046, 'Rank ICIR': 0.268}, 'data_train_vec': ['2023-06-09', '2025-09-08'], 'train_time_vec': ['2026-06-09', '2026-06-09'], 'rank_icir': '0.268', 'weight': '0.065'}

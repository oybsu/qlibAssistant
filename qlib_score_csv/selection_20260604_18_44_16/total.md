# params 
 {'predict_dates': [{'start': '2026-06-04', 'end': '2026-06-04'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260604_18 409800380067690027 (Recorders: 2/5)

	Recorder: 2d5c48e9c69147e98adea0dac7fcb43f

		Model: {'id': '2d5c48e9c69147e98adea0dac7fcb43f', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.113, 'Rank IC': 0.029, 'Rank ICIR': 0.205}, 'data_train_vec': ['2021-06-04', '2025-03-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.205', 'weight': '0.062'}

	Recorder: b2037faea2234bb8815851d755097c01

		Model: {'id': 'b2037faea2234bb8815851d755097c01', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.221, 'Rank IC': 0.035, 'Rank ICIR': 0.235}, 'data_train_vec': ['2023-06-04', '2025-09-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.235', 'weight': '0.071'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260604_18 433255881449469446 (Recorders: 4/5)

	Recorder: 7026617a09a242aca7424f8e0958f179

		Model: {'id': '7026617a09a242aca7424f8e0958f179', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.036, 'Rank IC': 0.023, 'Rank ICIR': 0.157}, 'data_train_vec': ['2021-06-04', '2025-03-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.157', 'weight': '0.047'}

	Recorder: 768acc5843594052a9bda9f6a7c68af8

		Model: {'id': '768acc5843594052a9bda9f6a7c68af8', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.166, 'Rank IC': 0.032, 'Rank ICIR': 0.241}, 'data_train_vec': ['2023-06-04', '2025-09-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.241', 'weight': '0.073'}

	Recorder: e1c3a834a08e4e279911e8440d110a62

		Model: {'id': 'e1c3a834a08e4e279911e8440d110a62', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.044, 'Rank IC': 0.009, 'Rank ICIR': 0.096}, 'data_train_vec': ['2024-06-04', '2025-12-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.096', 'weight': '0.029'}

	Recorder: 8533b329522e4298bb1561c5c67a2a7d

		Model: {'id': '8533b329522e4298bb1561c5c67a2a7d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.072, 'ICIR': 0.309, 'Rank IC': 0.034, 'Rank ICIR': 0.152}, 'data_train_vec': ['2025-06-04', '2026-03-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.152', 'weight': '0.046'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260604_15 859306522046242489 (Recorders: 4/5)

	Recorder: c43bb0fc55f540f98b0a106f6007912d

		Model: {'id': 'c43bb0fc55f540f98b0a106f6007912d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.109, 'Rank IC': 0.042, 'Rank ICIR': 0.291}, 'data_train_vec': ['2021-06-04', '2025-03-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.291', 'weight': '0.088'}

	Recorder: 87a87e3ffe314b70947a0ae8c027fad9

		Model: {'id': '87a87e3ffe314b70947a0ae8c027fad9', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.054, 'Rank IC': 0.043, 'Rank ICIR': 0.244}, 'data_train_vec': ['2022-06-04', '2025-06-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.244', 'weight': '0.074'}

	Recorder: d353d0416c11463694a771f9a21aa954

		Model: {'id': 'd353d0416c11463694a771f9a21aa954', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.241, 'Rank IC': 0.047, 'Rank ICIR': 0.328}, 'data_train_vec': ['2023-06-04', '2025-09-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.328', 'weight': '0.099'}

	Recorder: 1eb1894a8b2441518bdb43e2582dba8f

		Model: {'id': '1eb1894a8b2441518bdb43e2582dba8f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.01, 'Rank IC': 0.003, 'Rank ICIR': 0.027}, 'data_train_vec': ['2024-06-04', '2025-12-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.027', 'weight': '0.008'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260604_15 676878852911576500 (Recorders: 4/5)

	Recorder: bf259614a30b42f88d62a8d55f358921

		Model: {'id': 'bf259614a30b42f88d62a8d55f358921', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.083, 'Rank IC': 0.039, 'Rank ICIR': 0.338}, 'data_train_vec': ['2021-06-04', '2025-03-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.338', 'weight': '0.102'}

	Recorder: 094735617c874c0689c28f507f310070

		Model: {'id': '094735617c874c0689c28f507f310070', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.067, 'Rank IC': 0.032, 'Rank ICIR': 0.28}, 'data_train_vec': ['2023-06-04', '2025-09-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.280', 'weight': '0.084'}

	Recorder: 5aef35f5d69c4bb399f9dc8fce250c60

		Model: {'id': '5aef35f5d69c4bb399f9dc8fce250c60', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.076, 'Rank IC': 0.018, 'Rank ICIR': 0.127}, 'data_train_vec': ['2024-06-04', '2025-12-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.127', 'weight': '0.038'}

	Recorder: a93fe8947500429ebe64a83da54d0053

		Model: {'id': 'a93fe8947500429ebe64a83da54d0053', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.049, 'ICIR': 0.223, 'Rank IC': 0.033, 'Rank ICIR': 0.14}, 'data_train_vec': ['2025-06-04', '2026-03-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.140', 'weight': '0.042'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260604_15 373424574253600280 (Recorders: 2/5)

	Recorder: 1a5904c9d88a456aa794ef45530ad51b

		Model: {'id': '1a5904c9d88a456aa794ef45530ad51b', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.069, 'Rank IC': 0.041, 'Rank ICIR': 0.244}, 'data_train_vec': ['2021-06-04', '2025-03-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.244', 'weight': '0.074'}

	Recorder: 31ae622749a34bd79335df10328ea98e

		Model: {'id': '31ae622749a34bd79335df10328ea98e', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.139, 'Rank IC': 0.033, 'Rank ICIR': 0.212}, 'data_train_vec': ['2023-06-04', '2025-09-03'], 'train_time_vec': ['2026-06-04', '2026-06-04'], 'rank_icir': '0.212', 'weight': '0.064'}

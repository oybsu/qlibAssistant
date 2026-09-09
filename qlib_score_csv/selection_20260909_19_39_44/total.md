# params 
 {'predict_dates': [{'start': '2026-09-09', 'end': '2026-09-09'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260909_19 698376508710311636 (Recorders: 2/5)

	Recorder: 2be6e40739b444d2b2670912562f99e8

		Model: {'id': '2be6e40739b444d2b2670912562f99e8', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.093, 'Rank IC': 0.038, 'Rank ICIR': 0.239}, 'data_train_vec': ['2022-09-09', '2025-09-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.239', 'weight': '0.104'}

	Recorder: 88bbaf3ab76349b8af4781a634f8b011

		Model: {'id': '88bbaf3ab76349b8af4781a634f8b011', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.056, 'Rank IC': 0.014, 'Rank ICIR': 0.08}, 'data_train_vec': ['2023-09-09', '2025-12-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.080', 'weight': '0.035'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260909_19 252345148214357424 (Recorders: 3/5)

	Recorder: 73e27338401e4cd2997f0bdea29e865c

		Model: {'id': '73e27338401e4cd2997f0bdea29e865c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.099, 'Rank IC': 0.027, 'Rank ICIR': 0.175}, 'data_train_vec': ['2021-09-09', '2025-06-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.175', 'weight': '0.076'}

	Recorder: 6f42c799d62142c0aab2d94aa0b563a5

		Model: {'id': '6f42c799d62142c0aab2d94aa0b563a5', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.156, 'Rank IC': 0.033, 'Rank ICIR': 0.259}, 'data_train_vec': ['2022-09-09', '2025-09-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.259', 'weight': '0.113'}

	Recorder: 0efad3da2ebe4e23981a13d822b4b0fe

		Model: {'id': '0efad3da2ebe4e23981a13d822b4b0fe', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.039, 'Rank IC': 0.007, 'Rank ICIR': 0.044}, 'data_train_vec': ['2023-09-09', '2025-12-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.044', 'weight': '0.019'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260909_16 657161246979427169 (Recorders: 3/5)

	Recorder: f065883b84124941aadef0590f7eef65

		Model: {'id': 'f065883b84124941aadef0590f7eef65', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.108, 'Rank IC': 0.035, 'Rank ICIR': 0.21}, 'data_train_vec': ['2021-09-09', '2025-06-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.210', 'weight': '0.091'}

	Recorder: 996af9311e244433bc969c9d87d87094

		Model: {'id': '996af9311e244433bc969c9d87d87094', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.141, 'Rank IC': 0.04, 'Rank ICIR': 0.244}, 'data_train_vec': ['2022-09-09', '2025-09-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.244', 'weight': '0.106'}

	Recorder: 79aa34667b8f4b14aa8cbaf1d52431a6

		Model: {'id': '79aa34667b8f4b14aa8cbaf1d52431a6', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.01, 'Rank IC': 0.006, 'Rank ICIR': 0.031}, 'data_train_vec': ['2023-09-09', '2025-12-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.031', 'weight': '0.013'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260909_16 177975322393799013 (Recorders: 4/5)

	Recorder: 3b511416c0e9495185b1303d145dce57

		Model: {'id': '3b511416c0e9495185b1303d145dce57', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.106, 'Rank IC': 0.028, 'Rank ICIR': 0.173}, 'data_train_vec': ['2021-09-09', '2025-06-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.173', 'weight': '0.075'}

	Recorder: 928740e5702644d3804e2ae1cf6949b1

		Model: {'id': '928740e5702644d3804e2ae1cf6949b1', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.039, 'ICIR': 0.205, 'Rank IC': 0.034, 'Rank ICIR': 0.216}, 'data_train_vec': ['2022-09-09', '2025-09-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.216', 'weight': '0.094'}

	Recorder: 6aee75d69e1448b2a0bfb26050c6cdc8

		Model: {'id': '6aee75d69e1448b2a0bfb26050c6cdc8', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.041, 'Rank IC': 0.002, 'Rank ICIR': 0.008}, 'data_train_vec': ['2024-09-09', '2026-03-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.008', 'weight': '0.003'}

	Recorder: aa944457cff94fd6af0f5fb50f5fd21a

		Model: {'id': 'aa944457cff94fd6af0f5fb50f5fd21a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.044, 'ICIR': 0.21, 'Rank IC': 0.03, 'Rank ICIR': 0.15}, 'data_train_vec': ['2025-09-09', '2026-06-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.150', 'weight': '0.065'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260909_16 139461886571372346 (Recorders: 2/5)

	Recorder: 6b5be07cbb87456cb053719231d9069a

		Model: {'id': '6b5be07cbb87456cb053719231d9069a', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.019, 'Rank IC': 0.031, 'Rank ICIR': 0.185}, 'data_train_vec': ['2021-09-09', '2025-06-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.185', 'weight': '0.080'}

	Recorder: 8e0bcf35971a4a9bb74333db97acff8e

		Model: {'id': '8e0bcf35971a4a9bb74333db97acff8e', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.059, 'Rank IC': 0.044, 'Rank ICIR': 0.286}, 'data_train_vec': ['2022-09-09', '2025-09-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.286', 'weight': '0.124'}

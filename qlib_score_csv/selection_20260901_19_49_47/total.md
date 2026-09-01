# params 
 {'predict_dates': [{'start': '2026-09-01', 'end': '2026-09-01'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260901_19 615781777391875952 (Recorders: 2/5)

	Recorder: ddbaecfc0956481699235e7f486b3908

		Model: {'id': 'ddbaecfc0956481699235e7f486b3908', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.115, 'Rank IC': 0.04, 'Rank ICIR': 0.278}, 'data_train_vec': ['2022-09-01', '2025-08-31'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.278', 'weight': '0.139'}

	Recorder: d1377498ea97496ab18bdc2ce6214ecf

		Model: {'id': 'd1377498ea97496ab18bdc2ce6214ecf', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.073, 'Rank IC': 0.019, 'Rank ICIR': 0.116}, 'data_train_vec': ['2023-09-01', '2025-11-30'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.116', 'weight': '0.058'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260901_19 688571837611522990 (Recorders: 2/5)

	Recorder: cfb6bed0c90b46109d37c9383ef76931

		Model: {'id': 'cfb6bed0c90b46109d37c9383ef76931', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.134, 'Rank IC': 0.023, 'Rank ICIR': 0.204}, 'data_train_vec': ['2022-09-01', '2025-08-31'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.204', 'weight': '0.102'}

	Recorder: 19c59546938a4993a697ad16b784cba2

		Model: {'id': '19c59546938a4993a697ad16b784cba2', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.051, 'Rank IC': 0.008, 'Rank ICIR': 0.054}, 'data_train_vec': ['2023-09-01', '2025-11-30'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.054', 'weight': '0.027'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260901_16 482369145167308759 (Recorders: 4/5)

	Recorder: 17123e590d9a4fe088ea8a928b6da8ac

		Model: {'id': '17123e590d9a4fe088ea8a928b6da8ac', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.056, 'Rank IC': 0.023, 'Rank ICIR': 0.137}, 'data_train_vec': ['2021-09-01', '2025-05-31'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.137', 'weight': '0.068'}

	Recorder: 8cb31f58c14b468f980cac053641ec54

		Model: {'id': '8cb31f58c14b468f980cac053641ec54', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.104, 'Rank IC': 0.035, 'Rank ICIR': 0.2}, 'data_train_vec': ['2022-09-01', '2025-08-31'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.200', 'weight': '0.100'}

	Recorder: 626496137464455b961982ad8cbec89d

		Model: {'id': '626496137464455b961982ad8cbec89d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.011, 'Rank IC': 0.008, 'Rank ICIR': 0.044}, 'data_train_vec': ['2023-09-01', '2025-11-30'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.044', 'weight': '0.022'}

	Recorder: d9b0432dfe5f44b99a50456a1531fa83

		Model: {'id': 'd9b0432dfe5f44b99a50456a1531fa83', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.054, 'Rank IC': 0.005, 'Rank ICIR': 0.022}, 'data_train_vec': ['2025-09-01', '2026-05-31'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.022', 'weight': '0.011'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260901_16 174290209135948858 (Recorders: 5/5)

	Recorder: 3f57ac5406ed476da279fbdd959dedfa

		Model: {'id': '3f57ac5406ed476da279fbdd959dedfa', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.079, 'Rank IC': 0.026, 'Rank ICIR': 0.16}, 'data_train_vec': ['2021-09-01', '2025-05-31'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.160', 'weight': '0.080'}

	Recorder: 9fde0f6f2d5641259da803b67847800a

		Model: {'id': '9fde0f6f2d5641259da803b67847800a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.182, 'Rank IC': 0.035, 'Rank ICIR': 0.213}, 'data_train_vec': ['2022-09-01', '2025-08-31'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.213', 'weight': '0.106'}

	Recorder: f9e5768e97d24b8c98501f5bdec5ec20

		Model: {'id': 'f9e5768e97d24b8c98501f5bdec5ec20', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.032, 'Rank IC': 0.003, 'Rank ICIR': 0.014}, 'data_train_vec': ['2023-09-01', '2025-11-30'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.014', 'weight': '0.007'}

	Recorder: bdfefdaff2ef4501a5d4eec8bd204386

		Model: {'id': 'bdfefdaff2ef4501a5d4eec8bd204386', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.039, 'Rank IC': 0.008, 'Rank ICIR': 0.029}, 'data_train_vec': ['2024-09-01', '2026-02-28'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.029', 'weight': '0.014'}

	Recorder: ca40078501c44a898c263136ca6f94fb

		Model: {'id': 'ca40078501c44a898c263136ca6f94fb', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.077, 'ICIR': 0.365, 'Rank IC': 0.05, 'Rank ICIR': 0.271}, 'data_train_vec': ['2025-09-01', '2026-05-31'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.271', 'weight': '0.135'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260901_16 166615911695123369 (Recorders: 3/5)

	Recorder: b7d1a37a5a5d407489403f1b6ba196a7

		Model: {'id': 'b7d1a37a5a5d407489403f1b6ba196a7', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.008, 'Rank IC': 0.023, 'Rank ICIR': 0.139}, 'data_train_vec': ['2022-09-01', '2025-08-31'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.139', 'weight': '0.069'}

	Recorder: 5a0a6a281a354f0fb752bd4ed01401ce

		Model: {'id': '5a0a6a281a354f0fb752bd4ed01401ce', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.016, 'Rank IC': 0.015, 'Rank ICIR': 0.09}, 'data_train_vec': ['2023-09-01', '2025-11-30'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.090', 'weight': '0.045'}

	Recorder: c6bc7e4e016f4e699b7c25a67b86d1c1

		Model: {'id': 'c6bc7e4e016f4e699b7c25a67b86d1c1', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.103, 'Rank IC': 0.007, 'Rank ICIR': 0.032}, 'data_train_vec': ['2025-09-01', '2026-05-31'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.032', 'weight': '0.016'}

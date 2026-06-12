# params 
 {'predict_dates': [{'start': '2026-06-12', 'end': '2026-06-12'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260612_18 924290006873501714 (Recorders: 4/5)

	Recorder: 1af8bb3b7ecd4b839cf79619f88a99f7

		Model: {'id': '1af8bb3b7ecd4b839cf79619f88a99f7', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.053, 'Rank IC': 0.035, 'Rank ICIR': 0.194}, 'data_train_vec': ['2021-06-12', '2025-03-11'], 'train_time_vec': ['2026-06-12', '2026-06-12'], 'rank_icir': '0.194', 'weight': '0.041'}

	Recorder: 1253c9197ca040b6a7e49b3453013bcc

		Model: {'id': '1253c9197ca040b6a7e49b3453013bcc', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.011, 'Rank IC': 0.032, 'Rank ICIR': 0.22}, 'data_train_vec': ['2022-06-12', '2025-06-11'], 'train_time_vec': ['2026-06-12', '2026-06-12'], 'rank_icir': '0.220', 'weight': '0.047'}

	Recorder: d4a92fdae2bd42e9b7a9775e8b0790f3

		Model: {'id': 'd4a92fdae2bd42e9b7a9775e8b0790f3', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.239, 'Rank IC': 0.034, 'Rank ICIR': 0.23}, 'data_train_vec': ['2023-06-12', '2025-09-11'], 'train_time_vec': ['2026-06-12', '2026-06-12'], 'rank_icir': '0.230', 'weight': '0.049'}

	Recorder: d6a22fb917484ef5b3a19bde04fc3e0e

		Model: {'id': 'd6a22fb917484ef5b3a19bde04fc3e0e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.128, 'Rank IC': 0.032, 'Rank ICIR': 0.286}, 'data_train_vec': ['2024-06-12', '2025-12-11'], 'train_time_vec': ['2026-06-12', '2026-06-12'], 'rank_icir': '0.286', 'weight': '0.061'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260612_18 668440198312980773 (Recorders: 4/5)

	Recorder: 367ea77804cf4319bd33d5871fb9b9c6

		Model: {'id': '367ea77804cf4319bd33d5871fb9b9c6', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.069, 'Rank IC': 0.027, 'Rank ICIR': 0.175}, 'data_train_vec': ['2021-06-12', '2025-03-11'], 'train_time_vec': ['2026-06-12', '2026-06-12'], 'rank_icir': '0.175', 'weight': '0.037'}

	Recorder: df059bad4d6942fa8023e91e847083b4

		Model: {'id': 'df059bad4d6942fa8023e91e847083b4', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.015, 'Rank IC': 0.027, 'Rank ICIR': 0.166}, 'data_train_vec': ['2022-06-12', '2025-06-11'], 'train_time_vec': ['2026-06-12', '2026-06-12'], 'rank_icir': '0.166', 'weight': '0.035'}

	Recorder: 83baa1012c0946b587b73c96c79faa0e

		Model: {'id': '83baa1012c0946b587b73c96c79faa0e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.227, 'Rank IC': 0.038, 'Rank ICIR': 0.275}, 'data_train_vec': ['2023-06-12', '2025-09-11'], 'train_time_vec': ['2026-06-12', '2026-06-12'], 'rank_icir': '0.275', 'weight': '0.059'}

	Recorder: 2cb7994905fd47e2a0c9cfe2d28843b9

		Model: {'id': '2cb7994905fd47e2a0c9cfe2d28843b9', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.156, 'Rank IC': 0.021, 'Rank ICIR': 0.233}, 'data_train_vec': ['2024-06-12', '2025-12-11'], 'train_time_vec': ['2026-06-12', '2026-06-12'], 'rank_icir': '0.233', 'weight': '0.050'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260612_15 640326236386986127 (Recorders: 4/5)

	Recorder: 3d49a53a96fc4883b6ff94944cfe4d90

		Model: {'id': '3d49a53a96fc4883b6ff94944cfe4d90', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.145, 'Rank IC': 0.049, 'Rank ICIR': 0.324}, 'data_train_vec': ['2021-06-12', '2025-03-11'], 'train_time_vec': ['2026-06-12', '2026-06-12'], 'rank_icir': '0.324', 'weight': '0.069'}

	Recorder: f66155cd5e0d4278878dafa6a5b9bfed

		Model: {'id': 'f66155cd5e0d4278878dafa6a5b9bfed', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.137, 'Rank IC': 0.051, 'Rank ICIR': 0.297}, 'data_train_vec': ['2022-06-12', '2025-06-11'], 'train_time_vec': ['2026-06-12', '2026-06-12'], 'rank_icir': '0.297', 'weight': '0.063'}

	Recorder: 731a9303df434282bf1ca3e5672643d8

		Model: {'id': '731a9303df434282bf1ca3e5672643d8', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.192, 'Rank IC': 0.044, 'Rank ICIR': 0.294}, 'data_train_vec': ['2023-06-12', '2025-09-11'], 'train_time_vec': ['2026-06-12', '2026-06-12'], 'rank_icir': '0.294', 'weight': '0.063'}

	Recorder: 8c7b0b304550459ba57c01588ebc0535

		Model: {'id': '8c7b0b304550459ba57c01588ebc0535', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.057, 'Rank IC': 0.01, 'Rank ICIR': 0.091}, 'data_train_vec': ['2024-06-12', '2025-12-11'], 'train_time_vec': ['2026-06-12', '2026-06-12'], 'rank_icir': '0.091', 'weight': '0.019'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260612_15 948669216137921296 (Recorders: 4/5)

	Recorder: c71548594d934b65a598af10cd31f3ef

		Model: {'id': 'c71548594d934b65a598af10cd31f3ef', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.136, 'Rank IC': 0.043, 'Rank ICIR': 0.37}, 'data_train_vec': ['2021-06-12', '2025-03-11'], 'train_time_vec': ['2026-06-12', '2026-06-12'], 'rank_icir': '0.370', 'weight': '0.079'}

	Recorder: 8bb6aad378b7466296d74e4bed8ac885

		Model: {'id': '8bb6aad378b7466296d74e4bed8ac885', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.042, 'Rank IC': 0.041, 'Rank ICIR': 0.304}, 'data_train_vec': ['2022-06-12', '2025-06-11'], 'train_time_vec': ['2026-06-12', '2026-06-12'], 'rank_icir': '0.304', 'weight': '0.065'}

	Recorder: 0599772396bc48df9f2c650a25fdf979

		Model: {'id': '0599772396bc48df9f2c650a25fdf979', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.101, 'Rank IC': 0.035, 'Rank ICIR': 0.304}, 'data_train_vec': ['2023-06-12', '2025-09-11'], 'train_time_vec': ['2026-06-12', '2026-06-12'], 'rank_icir': '0.304', 'weight': '0.065'}

	Recorder: 649ae8cb54644293a976a15dc363f498

		Model: {'id': '649ae8cb54644293a976a15dc363f498', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.03, 'Rank IC': 0.012, 'Rank ICIR': 0.08}, 'data_train_vec': ['2024-06-12', '2025-12-11'], 'train_time_vec': ['2026-06-12', '2026-06-12'], 'rank_icir': '0.080', 'weight': '0.017'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260612_15 235601749315461874 (Recorders: 4/5)

	Recorder: 38636e27dc3c4ec69b0edab843a8c861

		Model: {'id': '38636e27dc3c4ec69b0edab843a8c861', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.045, 'Rank IC': 0.041, 'Rank ICIR': 0.255}, 'data_train_vec': ['2021-06-12', '2025-03-11'], 'train_time_vec': ['2026-06-12', '2026-06-12'], 'rank_icir': '0.255', 'weight': '0.054'}

	Recorder: a9dad377f18e4412acb7e870813c9766

		Model: {'id': 'a9dad377f18e4412acb7e870813c9766', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.032, 'Rank IC': 0.047, 'Rank ICIR': 0.263}, 'data_train_vec': ['2022-06-12', '2025-06-11'], 'train_time_vec': ['2026-06-12', '2026-06-12'], 'rank_icir': '0.263', 'weight': '0.056'}

	Recorder: fccacf568cd04ecdad40173585a764d3

		Model: {'id': 'fccacf568cd04ecdad40173585a764d3', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.032, 'Rank IC': 0.028, 'Rank ICIR': 0.168}, 'data_train_vec': ['2023-06-12', '2025-09-11'], 'train_time_vec': ['2026-06-12', '2026-06-12'], 'rank_icir': '0.168', 'weight': '0.036'}

	Recorder: c93d2aec98184402b07ddb765e00f461

		Model: {'id': 'c93d2aec98184402b07ddb765e00f461', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.023, 'Rank IC': 0.016, 'Rank ICIR': 0.164}, 'data_train_vec': ['2024-06-12', '2025-12-11'], 'train_time_vec': ['2026-06-12', '2026-06-12'], 'rank_icir': '0.164', 'weight': '0.035'}

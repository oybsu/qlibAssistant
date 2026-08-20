# params 
 {'predict_dates': [{'start': '2026-08-20', 'end': '2026-08-20'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260820_15 394641650694040058 (Recorders: 3/5)

	Recorder: 28149936cdf94c04b768654e532f836c

		Model: {'id': '28149936cdf94c04b768654e532f836c', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.006, 'Rank IC': 0.011, 'Rank ICIR': 0.055}, 'data_train_vec': ['2021-08-20', '2025-05-19'], 'train_time_vec': ['2026-08-20', '2026-08-20'], 'rank_icir': '0.055', 'weight': '0.038'}

	Recorder: 39ce1a75482e4fe987fd3e4ed7dbf88a

		Model: {'id': '39ce1a75482e4fe987fd3e4ed7dbf88a', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.021, 'Rank IC': 0.024, 'Rank ICIR': 0.148}, 'data_train_vec': ['2022-08-20', '2025-08-19'], 'train_time_vec': ['2026-08-20', '2026-08-20'], 'rank_icir': '0.148', 'weight': '0.102'}

	Recorder: f3817f40d2464d6387f7be017d0b30ea

		Model: {'id': 'f3817f40d2464d6387f7be017d0b30ea', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.043, 'Rank IC': 0.016, 'Rank ICIR': 0.108}, 'data_train_vec': ['2023-08-20', '2025-11-19'], 'train_time_vec': ['2026-08-20', '2026-08-20'], 'rank_icir': '0.108', 'weight': '0.074'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260820_15 450079399569155850 (Recorders: 2/5)

	Recorder: aaa54d938f1f448ba06108810cb730ce

		Model: {'id': 'aaa54d938f1f448ba06108810cb730ce', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.041, 'Rank IC': 0.013, 'Rank ICIR': 0.091}, 'data_train_vec': ['2021-08-20', '2025-05-19'], 'train_time_vec': ['2026-08-20', '2026-08-20'], 'rank_icir': '0.091', 'weight': '0.063'}

	Recorder: 563b3e9673ff4ad58fda912b6bd80083

		Model: {'id': '563b3e9673ff4ad58fda912b6bd80083', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.112, 'Rank IC': 0.015, 'Rank ICIR': 0.147}, 'data_train_vec': ['2023-08-20', '2025-11-19'], 'train_time_vec': ['2026-08-20', '2026-08-20'], 'rank_icir': '0.147', 'weight': '0.101'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260820_13 192008195806151234 (Recorders: 3/5)

	Recorder: bd1e3ebffdcf4bd681dad83236dbf7c4

		Model: {'id': 'bd1e3ebffdcf4bd681dad83236dbf7c4', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.069, 'Rank IC': 0.026, 'Rank ICIR': 0.152}, 'data_train_vec': ['2021-08-20', '2025-05-19'], 'train_time_vec': ['2026-08-20', '2026-08-20'], 'rank_icir': '0.152', 'weight': '0.105'}

	Recorder: 549b1c8e89c5484eb1c25ff59c7c5491

		Model: {'id': '549b1c8e89c5484eb1c25ff59c7c5491', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.11, 'Rank IC': 0.033, 'Rank ICIR': 0.193}, 'data_train_vec': ['2022-08-20', '2025-08-19'], 'train_time_vec': ['2026-08-20', '2026-08-20'], 'rank_icir': '0.193', 'weight': '0.133'}

	Recorder: 747d6ebd768e49238d109201ded1cb68

		Model: {'id': '747d6ebd768e49238d109201ded1cb68', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.01, 'Rank IC': 0.013, 'Rank ICIR': 0.077}, 'data_train_vec': ['2023-08-20', '2025-11-19'], 'train_time_vec': ['2026-08-20', '2026-08-20'], 'rank_icir': '0.077', 'weight': '0.053'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260820_13 987164548089293430 (Recorders: 3/5)

	Recorder: 97609b8ca0884953a946bd0ad01d066e

		Model: {'id': '97609b8ca0884953a946bd0ad01d066e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.069, 'Rank IC': 0.027, 'Rank ICIR': 0.167}, 'data_train_vec': ['2021-08-20', '2025-05-19'], 'train_time_vec': ['2026-08-20', '2026-08-20'], 'rank_icir': '0.167', 'weight': '0.115'}

	Recorder: 8f67534bf9c44a93a83fe43566c48b99

		Model: {'id': '8f67534bf9c44a93a83fe43566c48b99', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.162, 'Rank IC': 0.036, 'Rank ICIR': 0.228}, 'data_train_vec': ['2022-08-20', '2025-08-19'], 'train_time_vec': ['2026-08-20', '2026-08-20'], 'rank_icir': '0.228', 'weight': '0.157'}

	Recorder: ae8e01bba7ef4638b2835fdf8aee949b

		Model: {'id': 'ae8e01bba7ef4638b2835fdf8aee949b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.043, 'ICIR': 0.165, 'Rank IC': 0.016, 'Rank ICIR': 0.087}, 'data_train_vec': ['2025-08-20', '2026-05-19'], 'train_time_vec': ['2026-08-20', '2026-08-20'], 'rank_icir': '0.087', 'weight': '0.060'}

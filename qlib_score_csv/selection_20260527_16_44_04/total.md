# params 
 {'predict_dates': [{'start': '2026-05-27', 'end': '2026-05-27'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260527_15 316294472871859901 (Recorders: 3/5)

	Recorder: 6dcb6c2ff06f4b928dfb43a0c4712844

		Model: {'id': '6dcb6c2ff06f4b928dfb43a0c4712844', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.017, 'Rank IC': 0.021, 'Rank ICIR': 0.14}, 'data_train_vec': ['2022-05-27', '2025-05-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.140', 'weight': '0.043'}

	Recorder: bd3c7dd7165c48aa944991537e03e5c2

		Model: {'id': 'bd3c7dd7165c48aa944991537e03e5c2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.018, 'Rank IC': 0.028, 'Rank ICIR': 0.16}, 'data_train_vec': ['2023-05-27', '2025-08-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.160', 'weight': '0.049'}

	Recorder: baecf924a2dc435ca05c7a3e1cce0102

		Model: {'id': 'baecf924a2dc435ca05c7a3e1cce0102', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.061, 'ICIR': 0.259, 'Rank IC': 0.032, 'Rank ICIR': 0.154}, 'data_train_vec': ['2025-05-27', '2026-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.154', 'weight': '0.047'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260527_15 465220822704744835 (Recorders: 3/5)

	Recorder: e1853b398e2c4e74b9a8b4e95a19ffb9

		Model: {'id': 'e1853b398e2c4e74b9a8b4e95a19ffb9', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.184, 'Rank IC': 0.031, 'Rank ICIR': 0.236}, 'data_train_vec': ['2023-05-27', '2025-08-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.236', 'weight': '0.073'}

	Recorder: d5a8e44d15c74d64abe8710b7ce6487a

		Model: {'id': 'd5a8e44d15c74d64abe8710b7ce6487a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.11, 'Rank IC': 0.011, 'Rank ICIR': 0.107}, 'data_train_vec': ['2024-05-27', '2025-11-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.107', 'weight': '0.033'}

	Recorder: 2c474fbbb0f44c3eaa7aa688451ebd89

		Model: {'id': '2c474fbbb0f44c3eaa7aa688451ebd89', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.09, 'ICIR': 0.482, 'Rank IC': 0.047, 'Rank ICIR': 0.243}, 'data_train_vec': ['2025-05-27', '2026-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.243', 'weight': '0.075'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260527_13 769623751784310471 (Recorders: 4/5)

	Recorder: 0c7a618073f44c0191523d6ecee4cf12

		Model: {'id': '0c7a618073f44c0191523d6ecee4cf12', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.05, 'Rank IC': 0.032, 'Rank ICIR': 0.211}, 'data_train_vec': ['2021-05-27', '2025-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.211', 'weight': '0.065'}

	Recorder: 3b47df24928445f58dcbf3a1f1b55fcd

		Model: {'id': '3b47df24928445f58dcbf3a1f1b55fcd', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.087, 'Rank IC': 0.041, 'Rank ICIR': 0.229}, 'data_train_vec': ['2022-05-27', '2025-05-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.229', 'weight': '0.071'}

	Recorder: 0ac726f0f84c429da0ee959633f2db6c

		Model: {'id': '0ac726f0f84c429da0ee959633f2db6c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.169, 'Rank IC': 0.042, 'Rank ICIR': 0.266}, 'data_train_vec': ['2023-05-27', '2025-08-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.266', 'weight': '0.082'}

	Recorder: 7b388691b2364533b141c8b277ed27cc

		Model: {'id': '7b388691b2364533b141c8b277ed27cc', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.059, 'ICIR': 0.318, 'Rank IC': 0.025, 'Rank ICIR': 0.131}, 'data_train_vec': ['2025-05-27', '2026-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.131', 'weight': '0.040'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260527_13 704558390912200741 (Recorders: 3/5)

	Recorder: 8b75b6c8d3e0445994c071ee59d6cccf

		Model: {'id': '8b75b6c8d3e0445994c071ee59d6cccf', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.06, 'Rank IC': 0.034, 'Rank ICIR': 0.292}, 'data_train_vec': ['2021-05-27', '2025-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.292', 'weight': '0.090'}

	Recorder: 9fbf4996b99844febbf8ab3a0ad95b03

		Model: {'id': '9fbf4996b99844febbf8ab3a0ad95b03', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.118, 'Rank IC': 0.036, 'Rank ICIR': 0.326}, 'data_train_vec': ['2023-05-27', '2025-08-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.326', 'weight': '0.100'}

	Recorder: 5e2826c835a64ab0a6b8ebec9edab0c0

		Model: {'id': '5e2826c835a64ab0a6b8ebec9edab0c0', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.092, 'ICIR': 0.507, 'Rank IC': 0.067, 'Rank ICIR': 0.319}, 'data_train_vec': ['2025-05-27', '2026-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.319', 'weight': '0.098'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260527_12 147954719974534842 (Recorders: 2/5)

	Recorder: 63e844c8b3ea46ba9aad238dc8f42d64

		Model: {'id': '63e844c8b3ea46ba9aad238dc8f42d64', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.09, 'Rank IC': 0.028, 'Rank ICIR': 0.174}, 'data_train_vec': ['2023-05-27', '2025-08-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.174', 'weight': '0.054'}

	Recorder: c7fd40cfe950405e9205b911f19d47fe

		Model: {'id': 'c7fd40cfe950405e9205b911f19d47fe', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.052, 'ICIR': 0.314, 'Rank IC': 0.042, 'Rank ICIR': 0.256}, 'data_train_vec': ['2025-05-27', '2026-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.256', 'weight': '0.079'}

# params 
 {'predict_dates': [{'start': '2026-09-29', 'end': '2026-09-29'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260929_20 602665215062637668 (Recorders: 4/5)

	Recorder: d438aba39c14446a9aea2aee30c82da2

		Model: {'id': 'd438aba39c14446a9aea2aee30c82da2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.099, 'Rank IC': 0.027, 'Rank ICIR': 0.154}, 'data_train_vec': ['2021-09-29', '2025-06-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.154', 'weight': '0.057'}

	Recorder: 7980900eb6bd409481425bcbb206bb73

		Model: {'id': '7980900eb6bd409481425bcbb206bb73', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.103, 'Rank IC': 0.03, 'Rank ICIR': 0.149}, 'data_train_vec': ['2022-09-29', '2025-09-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.149', 'weight': '0.055'}

	Recorder: 6cdbffc95b12497d82b16d5a74e814d0

		Model: {'id': '6cdbffc95b12497d82b16d5a74e814d0', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.021, 'Rank IC': 0.012, 'Rank ICIR': 0.06}, 'data_train_vec': ['2023-09-29', '2025-12-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.060', 'weight': '0.022'}

	Recorder: 4ec7637967fb4e9e8106026769cb25e9

		Model: {'id': '4ec7637967fb4e9e8106026769cb25e9', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.046, 'ICIR': 0.292, 'Rank IC': 0.016, 'Rank ICIR': 0.127}, 'data_train_vec': ['2024-09-29', '2026-03-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.127', 'weight': '0.047'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260929_20 112410999705549650 (Recorders: 4/5)

	Recorder: 44bff94d96a449569717b157b8ec3d69

		Model: {'id': '44bff94d96a449569717b157b8ec3d69', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.172, 'Rank IC': 0.03, 'Rank ICIR': 0.221}, 'data_train_vec': ['2021-09-29', '2025-06-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.221', 'weight': '0.081'}

	Recorder: 2d98a97285fb422ebe4ca4938ebbf58f

		Model: {'id': '2d98a97285fb422ebe4ca4938ebbf58f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.178, 'Rank IC': 0.033, 'Rank ICIR': 0.201}, 'data_train_vec': ['2022-09-29', '2025-09-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.201', 'weight': '0.074'}

	Recorder: 7c53a0e370b2424c9c3b73bfe9a8d6ef

		Model: {'id': '7c53a0e370b2424c9c3b73bfe9a8d6ef', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.018, 'Rank IC': 0.009, 'Rank ICIR': 0.045}, 'data_train_vec': ['2023-09-29', '2025-12-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.045', 'weight': '0.017'}

	Recorder: 28c57a45a81d4e38951537b5a4f76624

		Model: {'id': '28c57a45a81d4e38951537b5a4f76624', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.055, 'Rank IC': 0.008, 'Rank ICIR': 0.054}, 'data_train_vec': ['2024-09-29', '2026-03-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.054', 'weight': '0.020'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260929_18 873672084811354405 (Recorders: 4/5)

	Recorder: 61c223874625456897ea9cff4b68a41b

		Model: {'id': '61c223874625456897ea9cff4b68a41b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.186, 'Rank IC': 0.046, 'Rank ICIR': 0.27}, 'data_train_vec': ['2021-09-29', '2025-06-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.270', 'weight': '0.099'}

	Recorder: 229e188ed9c24ad7b1b8cd50dfba2e7e

		Model: {'id': '229e188ed9c24ad7b1b8cd50dfba2e7e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.109, 'Rank IC': 0.026, 'Rank ICIR': 0.139}, 'data_train_vec': ['2022-09-29', '2025-09-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.139', 'weight': '0.051'}

	Recorder: 867da5828ee9449ca8de5d23a95d6246

		Model: {'id': '867da5828ee9449ca8de5d23a95d6246', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.014, 'Rank IC': 0.008, 'Rank ICIR': 0.038}, 'data_train_vec': ['2023-09-29', '2025-12-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.038', 'weight': '0.014'}

	Recorder: 7c76cf6e44484d6c9c4929a61482e358

		Model: {'id': '7c76cf6e44484d6c9c4929a61482e358', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.037, 'ICIR': 0.179, 'Rank IC': 0.008, 'Rank ICIR': 0.045}, 'data_train_vec': ['2024-09-29', '2026-03-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.045', 'weight': '0.017'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260929_18 203824978531283413 (Recorders: 5/5)

	Recorder: 151fadc2e2d04664916ec4609bed1120

		Model: {'id': '151fadc2e2d04664916ec4609bed1120', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.17, 'Rank IC': 0.038, 'Rank ICIR': 0.22}, 'data_train_vec': ['2021-09-29', '2025-06-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.220', 'weight': '0.081'}

	Recorder: 9bb9ea54167441e68d7076c05f9d64af

		Model: {'id': '9bb9ea54167441e68d7076c05f9d64af', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.127, 'Rank IC': 0.019, 'Rank ICIR': 0.1}, 'data_train_vec': ['2022-09-29', '2025-09-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.100', 'weight': '0.037'}

	Recorder: 2fbba425f8e24eb68131a2bbf6c09b60

		Model: {'id': '2fbba425f8e24eb68131a2bbf6c09b60', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.027, 'Rank IC': 0.001, 'Rank ICIR': 0.006}, 'data_train_vec': ['2023-09-29', '2025-12-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.006', 'weight': '0.002'}

	Recorder: d11a106f3bf7402ca6e89a0ac382fd85

		Model: {'id': 'd11a106f3bf7402ca6e89a0ac382fd85', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.073, 'ICIR': 0.34, 'Rank IC': 0.045, 'Rank ICIR': 0.254}, 'data_train_vec': ['2024-09-29', '2026-03-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.254', 'weight': '0.093'}

	Recorder: 0ef15de377d74254b548f8961c63a55d

		Model: {'id': '0ef15de377d74254b548f8961c63a55d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.07, 'Rank IC': 0.005, 'Rank ICIR': 0.032}, 'data_train_vec': ['2025-09-29', '2026-06-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.032', 'weight': '0.012'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260929_18 419202811426960372 (Recorders: 3/5)

	Recorder: 3577c9ce627247dc8aef8c0606b2a6b7

		Model: {'id': '3577c9ce627247dc8aef8c0606b2a6b7', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.021, 'Rank IC': 0.041, 'Rank ICIR': 0.236}, 'data_train_vec': ['2021-09-29', '2025-06-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.236', 'weight': '0.087'}

	Recorder: 0e0ed61d6ce64108802cf012180590bb

		Model: {'id': '0e0ed61d6ce64108802cf012180590bb', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.04, 'Rank IC': 0.024, 'Rank ICIR': 0.14}, 'data_train_vec': ['2022-09-29', '2025-09-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.140', 'weight': '0.051'}

	Recorder: 7f212ef9c3b04935ab3cd82c68bc8e3c

		Model: {'id': '7f212ef9c3b04935ab3cd82c68bc8e3c', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.06, 'ICIR': 0.291, 'Rank IC': 0.033, 'Rank ICIR': 0.233}, 'data_train_vec': ['2024-09-29', '2026-03-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.233', 'weight': '0.086'}

# params 
 {'predict_dates': [{'start': '2026-06-25', 'end': '2026-06-25'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260625_17 296629366058393866 (Recorders: 2/5)

	Recorder: e31099fa4dbb4464bf0149f836e2fe81

		Model: {'id': 'e31099fa4dbb4464bf0149f836e2fe81', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.191, 'Rank IC': 0.026, 'Rank ICIR': 0.206}, 'data_train_vec': ['2023-06-25', '2025-09-24'], 'train_time_vec': ['2026-06-25', '2026-06-25'], 'rank_icir': '0.206', 'weight': '0.123'}

	Recorder: 1476c626cef141048b2cb57fb9f7f860

		Model: {'id': '1476c626cef141048b2cb57fb9f7f860', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.25, 'Rank IC': 0.025, 'Rank ICIR': 0.25}, 'data_train_vec': ['2024-06-25', '2025-12-24'], 'train_time_vec': ['2026-06-25', '2026-06-25'], 'rank_icir': '0.250', 'weight': '0.149'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260625_17 941135683513843060 (Recorders: 3/5)

	Recorder: b9c05438e6df4397afa523483396e723

		Model: {'id': 'b9c05438e6df4397afa523483396e723', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.21, 'Rank IC': 0.03, 'Rank ICIR': 0.248}, 'data_train_vec': ['2023-06-25', '2025-09-24'], 'train_time_vec': ['2026-06-25', '2026-06-25'], 'rank_icir': '0.248', 'weight': '0.148'}

	Recorder: 6d88252a75df478c867bd3d0c3e0a56a

		Model: {'id': '6d88252a75df478c867bd3d0c3e0a56a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.188, 'Rank IC': 0.023, 'Rank ICIR': 0.205}, 'data_train_vec': ['2024-06-25', '2025-12-24'], 'train_time_vec': ['2026-06-25', '2026-06-25'], 'rank_icir': '0.205', 'weight': '0.122'}

	Recorder: 1c23426d17c44bd7a50e0509b84dcc7e

		Model: {'id': '1c23426d17c44bd7a50e0509b84dcc7e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.046, 'ICIR': 0.175, 'Rank IC': 0.005, 'Rank ICIR': 0.021}, 'data_train_vec': ['2025-06-25', '2026-03-24'], 'train_time_vec': ['2026-06-25', '2026-06-25'], 'rank_icir': '0.021', 'weight': '0.013'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260625_15 894864443438555381 (Recorders: 3/5)

	Recorder: 3c3fd90ed437492d89b1722b794dd11a

		Model: {'id': '3c3fd90ed437492d89b1722b794dd11a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.062, 'Rank IC': 0.045, 'Rank ICIR': 0.269}, 'data_train_vec': ['2021-06-25', '2025-03-24'], 'train_time_vec': ['2026-06-25', '2026-06-25'], 'rank_icir': '0.269', 'weight': '0.160'}

	Recorder: cd3be6ce1df24515ab3b99b47702c2d6

		Model: {'id': 'cd3be6ce1df24515ab3b99b47702c2d6', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.113, 'Rank IC': 0.049, 'Rank ICIR': 0.283}, 'data_train_vec': ['2022-06-25', '2025-06-24'], 'train_time_vec': ['2026-06-25', '2026-06-25'], 'rank_icir': '0.283', 'weight': '0.169'}

	Recorder: 49a6b0c7d3394eb5bb48a888a56d83fc

		Model: {'id': '49a6b0c7d3394eb5bb48a888a56d83fc', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.103, 'Rank IC': 0.027, 'Rank ICIR': 0.188}, 'data_train_vec': ['2023-06-25', '2025-09-24'], 'train_time_vec': ['2026-06-25', '2026-06-25'], 'rank_icir': '0.188', 'weight': '0.112'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260625_14 586602001025727708 (Recorders: 1/5)

	Recorder: d834c7c238d24cffbbb5364e937fc810

		Model: {'id': 'd834c7c238d24cffbbb5364e937fc810', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.02, 'Rank IC': 0.001, 'Rank ICIR': 0.008}, 'data_train_vec': ['2024-06-25', '2025-12-24'], 'train_time_vec': ['2026-06-25', '2026-06-25'], 'rank_icir': '0.008', 'weight': '0.005'}

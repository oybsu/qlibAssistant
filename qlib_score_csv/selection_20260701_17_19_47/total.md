# params 
 {'predict_dates': [{'start': '2026-07-01', 'end': '2026-07-01'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260701_16 422590192492731773 (Recorders: 4/5)

	Recorder: c2c4dad2cc534984b3c51962f8100688

		Model: {'id': 'c2c4dad2cc534984b3c51962f8100688', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.066, 'Rank IC': 0.015, 'Rank ICIR': 0.11}, 'data_train_vec': ['2022-07-01', '2025-06-30'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.110', 'weight': '0.047'}

	Recorder: 3312a2c152574874af5cb2347da16107

		Model: {'id': '3312a2c152574874af5cb2347da16107', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.25, 'Rank IC': 0.028, 'Rank ICIR': 0.221}, 'data_train_vec': ['2023-07-01', '2025-09-30'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.221', 'weight': '0.094'}

	Recorder: d9955758888b49dfbb38627331061d6f

		Model: {'id': 'd9955758888b49dfbb38627331061d6f', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.181, 'Rank IC': 0.025, 'Rank ICIR': 0.221}, 'data_train_vec': ['2024-07-01', '2025-12-31'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.221', 'weight': '0.094'}

	Recorder: 619825bae4f642b9b8ab9494d60cd8b4

		Model: {'id': '619825bae4f642b9b8ab9494d60cd8b4', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.116, 'Rank IC': 0.008, 'Rank ICIR': 0.055}, 'data_train_vec': ['2025-07-01', '2026-03-31'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.055', 'weight': '0.023'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260701_16 841739923607597681 (Recorders: 3/5)

	Recorder: cb535dc57e494d64b6d1633e645e400e

		Model: {'id': 'cb535dc57e494d64b6d1633e645e400e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.195, 'Rank IC': 0.025, 'Rank ICIR': 0.191}, 'data_train_vec': ['2023-07-01', '2025-09-30'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.191', 'weight': '0.081'}

	Recorder: d7521acff54d4574893198236030936f

		Model: {'id': 'd7521acff54d4574893198236030936f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.222, 'Rank IC': 0.027, 'Rank ICIR': 0.209}, 'data_train_vec': ['2024-07-01', '2025-12-31'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.209', 'weight': '0.089'}

	Recorder: eb4f4d3b674c4ed7a8665d04b28ffd91

		Model: {'id': 'eb4f4d3b674c4ed7a8665d04b28ffd91', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.059, 'ICIR': 0.245, 'Rank IC': 0.044, 'Rank ICIR': 0.208}, 'data_train_vec': ['2025-07-01', '2026-03-31'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.208', 'weight': '0.089'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260701_15 391844192528993255 (Recorders: 3/5)

	Recorder: 01b3611f18d543ddaa3716c0f78b1a27

		Model: {'id': '01b3611f18d543ddaa3716c0f78b1a27', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.051, 'Rank IC': 0.042, 'Rank ICIR': 0.251}, 'data_train_vec': ['2021-07-01', '2025-03-31'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.251', 'weight': '0.107'}

	Recorder: 3087fba8f3f94531b5290c513aa4b444

		Model: {'id': '3087fba8f3f94531b5290c513aa4b444', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.077, 'Rank IC': 0.038, 'Rank ICIR': 0.236}, 'data_train_vec': ['2022-07-01', '2025-06-30'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.236', 'weight': '0.101'}

	Recorder: 331546d06a5b484ea4127e4e5b22c192

		Model: {'id': '331546d06a5b484ea4127e4e5b22c192', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.108, 'Rank IC': 0.025, 'Rank ICIR': 0.195}, 'data_train_vec': ['2023-07-01', '2025-09-30'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.195', 'weight': '0.083'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260701_15 647922943263265598 (Recorders: 2/5)

	Recorder: 63982b66d3c34b4d9ca3ae703d81d100

		Model: {'id': '63982b66d3c34b4d9ca3ae703d81d100', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.039, 'Rank IC': 0.023, 'Rank ICIR': 0.172}, 'data_train_vec': ['2023-07-01', '2025-09-30'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.172', 'weight': '0.073'}

	Recorder: b3b12d62b7a542d69b6028d5b0bdba5f

		Model: {'id': 'b3b12d62b7a542d69b6028d5b0bdba5f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.085, 'Rank IC': 0.003, 'Rank ICIR': 0.014}, 'data_train_vec': ['2025-07-01', '2026-03-31'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.014', 'weight': '0.006'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260701_14 620719635058740624 (Recorders: 2/5)

	Recorder: 0241ff72603f4b4f9952da43b223bc90

		Model: {'id': '0241ff72603f4b4f9952da43b223bc90', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.056, 'Rank IC': 0.012, 'Rank ICIR': 0.09}, 'data_train_vec': ['2023-07-01', '2025-09-30'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.090', 'weight': '0.038'}

	Recorder: 1d22403759ef4a41bb2868aea4610bc3

		Model: {'id': '1d22403759ef4a41bb2868aea4610bc3', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.081, 'Rank IC': 0.018, 'Rank ICIR': 0.174}, 'data_train_vec': ['2024-07-01', '2025-12-31'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.174', 'weight': '0.074'}

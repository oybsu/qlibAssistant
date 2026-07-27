# params 
 {'predict_dates': [{'start': '2026-07-27', 'end': '2026-07-27'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260727_17 975138610255650724 (Recorders: 1/5)

	Recorder: 6a262d1cba2e43a7a7d9eea4fab50d64

		Model: {'id': '6a262d1cba2e43a7a7d9eea4fab50d64', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.045, 'Rank IC': 0.034, 'Rank ICIR': 0.185}, 'data_train_vec': ['2021-07-27', '2025-04-26'], 'train_time_vec': ['2026-07-27', '2026-07-27'], 'rank_icir': '0.185', 'weight': '0.172'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260727_17 860382726712186379 (Recorders: 3/5)

	Recorder: 6bb1bbed5fdf4861b5f5ff43e037eedd

		Model: {'id': '6bb1bbed5fdf4861b5f5ff43e037eedd', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.089, 'Rank IC': 0.032, 'Rank ICIR': 0.233}, 'data_train_vec': ['2021-07-27', '2025-04-26'], 'train_time_vec': ['2026-07-27', '2026-07-27'], 'rank_icir': '0.233', 'weight': '0.217'}

	Recorder: e5ea860a70bf45a8a52849e195103950

		Model: {'id': 'e5ea860a70bf45a8a52849e195103950', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.015, 'Rank IC': 0.019, 'Rank ICIR': 0.128}, 'data_train_vec': ['2022-07-27', '2025-07-26'], 'train_time_vec': ['2026-07-27', '2026-07-27'], 'rank_icir': '0.128', 'weight': '0.119'}

	Recorder: 3353ac3a691f40c0943f61e1371413da

		Model: {'id': '3353ac3a691f40c0943f61e1371413da', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.125, 'Rank IC': 0.022, 'Rank ICIR': 0.164}, 'data_train_vec': ['2023-07-27', '2025-10-26'], 'train_time_vec': ['2026-07-27', '2026-07-27'], 'rank_icir': '0.164', 'weight': '0.153'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260727_15 449801137694024003 (Recorders: 2/5)

	Recorder: 39554f4b2c0f448584331d1689291816

		Model: {'id': '39554f4b2c0f448584331d1689291816', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.091, 'Rank IC': 0.039, 'Rank ICIR': 0.222}, 'data_train_vec': ['2021-07-27', '2025-04-26'], 'train_time_vec': ['2026-07-27', '2026-07-27'], 'rank_icir': '0.222', 'weight': '0.207'}

	Recorder: a53038afc7984e3c8dc550a10d995f49

		Model: {'id': 'a53038afc7984e3c8dc550a10d995f49', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.046, 'Rank IC': 0.023, 'Rank ICIR': 0.142}, 'data_train_vec': ['2022-07-27', '2025-07-26'], 'train_time_vec': ['2026-07-27', '2026-07-27'], 'rank_icir': '0.142', 'weight': '0.132'}

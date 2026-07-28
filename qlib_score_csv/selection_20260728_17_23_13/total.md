# params 
 {'predict_dates': [{'start': '2026-07-28', 'end': '2026-07-28'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260728_17 639522758383673425 (Recorders: 1/5)

	Recorder: d5cdf437a419404294c6c8ec0d6b8c29

		Model: {'id': 'd5cdf437a419404294c6c8ec0d6b8c29', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.107, 'Rank IC': 0.019, 'Rank ICIR': 0.163}, 'data_train_vec': ['2023-07-28', '2025-10-27'], 'train_time_vec': ['2026-07-28', '2026-07-28'], 'rank_icir': '0.163', 'weight': '0.206'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260728_17 956501976574715290 (Recorders: 2/5)

	Recorder: 58c6d749989341e5b8fee1ef8f6b206e

		Model: {'id': '58c6d749989341e5b8fee1ef8f6b206e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.075, 'Rank IC': 0.031, 'Rank ICIR': 0.2}, 'data_train_vec': ['2021-07-28', '2025-04-27'], 'train_time_vec': ['2026-07-28', '2026-07-28'], 'rank_icir': '0.200', 'weight': '0.253'}

	Recorder: 20b96398896f425fb2a2e23aac732cb3

		Model: {'id': '20b96398896f425fb2a2e23aac732cb3', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.164, 'Rank IC': 0.027, 'Rank ICIR': 0.236}, 'data_train_vec': ['2023-07-28', '2025-10-27'], 'train_time_vec': ['2026-07-28', '2026-07-28'], 'rank_icir': '0.236', 'weight': '0.299'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260728_14 784110001091600097 (Recorders: 1/5)

	Recorder: 1a2bc2ecce344370aab5ab62c094c318

		Model: {'id': '1a2bc2ecce344370aab5ab62c094c318', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.069, 'Rank IC': 0.032, 'Rank ICIR': 0.191}, 'data_train_vec': ['2021-07-28', '2025-04-27'], 'train_time_vec': ['2026-07-28', '2026-07-28'], 'rank_icir': '0.191', 'weight': '0.242'}

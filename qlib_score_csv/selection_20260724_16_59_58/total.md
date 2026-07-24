# params 
 {'predict_dates': [{'start': '2026-07-23', 'end': '2026-07-23'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260724_16 490856131018311249 (Recorders: 2/5)

	Recorder: fff29ca16a5a44e99986b783223540ae

		Model: {'id': 'fff29ca16a5a44e99986b783223540ae', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.025, 'Rank IC': 0.029, 'Rank ICIR': 0.156}, 'data_train_vec': ['2021-07-24', '2025-04-23'], 'train_time_vec': ['2026-07-24', '2026-07-24'], 'rank_icir': '0.156', 'weight': '0.162'}

	Recorder: 71d28fed2ab14c4b8f202c3fc2e95437

		Model: {'id': '71d28fed2ab14c4b8f202c3fc2e95437', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.063, 'Rank IC': 0.022, 'Rank ICIR': 0.176}, 'data_train_vec': ['2023-07-24', '2025-10-23'], 'train_time_vec': ['2026-07-24', '2026-07-24'], 'rank_icir': '0.176', 'weight': '0.183'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260724_16 413304568181904199 (Recorders: 2/5)

	Recorder: bc3ba530789842f98526a5937cf89e9f

		Model: {'id': 'bc3ba530789842f98526a5937cf89e9f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.1, 'Rank IC': 0.037, 'Rank ICIR': 0.22}, 'data_train_vec': ['2021-07-24', '2025-04-23'], 'train_time_vec': ['2026-07-24', '2026-07-24'], 'rank_icir': '0.220', 'weight': '0.228'}

	Recorder: 68d521f421ba42b5bf4336a3345f11fb

		Model: {'id': '68d521f421ba42b5bf4336a3345f11fb', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.129, 'Rank IC': 0.026, 'Rank ICIR': 0.206}, 'data_train_vec': ['2023-07-24', '2025-10-23'], 'train_time_vec': ['2026-07-24', '2026-07-24'], 'rank_icir': '0.206', 'weight': '0.214'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260724_14 736105180826471628 (Recorders: 1/5)

	Recorder: 3a97383b14334b5d8f405757e1367a27

		Model: {'id': '3a97383b14334b5d8f405757e1367a27', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.053, 'Rank IC': 0.036, 'Rank ICIR': 0.205}, 'data_train_vec': ['2021-07-24', '2025-04-23'], 'train_time_vec': ['2026-07-24', '2026-07-24'], 'rank_icir': '0.205', 'weight': '0.213'}

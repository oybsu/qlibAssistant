# params 
 {'predict_dates': [{'start': '2026-07-31', 'end': '2026-07-31'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260801_16 360141512761672201 (Recorders: 2/5)

	Recorder: 9335dff1c0c74a4694878d46c144b6b1

		Model: {'id': '9335dff1c0c74a4694878d46c144b6b1', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.032, 'Rank IC': 0.028, 'Rank ICIR': 0.139}, 'data_train_vec': ['2021-08-01', '2025-04-30'], 'train_time_vec': ['2026-08-01', '2026-08-01'], 'rank_icir': '0.139', 'weight': '0.213'}

	Recorder: 55cb13a76d1849ae84b1768ac94ea5af

		Model: {'id': '55cb13a76d1849ae84b1768ac94ea5af', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.02, 'Rank IC': 0.005, 'Rank ICIR': 0.03}, 'data_train_vec': ['2023-08-01', '2025-10-31'], 'train_time_vec': ['2026-08-01', '2026-08-01'], 'rank_icir': '0.030', 'weight': '0.046'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260801_16 816173780223510023 (Recorders: 2/5)

	Recorder: 8313986f7e3947dd9ad3db1439bbdf5a

		Model: {'id': '8313986f7e3947dd9ad3db1439bbdf5a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.062, 'Rank IC': 0.029, 'Rank ICIR': 0.176}, 'data_train_vec': ['2021-08-01', '2025-04-30'], 'train_time_vec': ['2026-08-01', '2026-08-01'], 'rank_icir': '0.176', 'weight': '0.270'}

	Recorder: 729dfe35589f4b5b9db982925d692480

		Model: {'id': '729dfe35589f4b5b9db982925d692480', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.081, 'Rank IC': 0.018, 'Rank ICIR': 0.132}, 'data_train_vec': ['2023-08-01', '2025-10-31'], 'train_time_vec': ['2026-08-01', '2026-08-01'], 'rank_icir': '0.132', 'weight': '0.202'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260801_14 353153198024625365 (Recorders: 1/5)

	Recorder: cefd8489d7304bb9813e558fb996bf53

		Model: {'id': 'cefd8489d7304bb9813e558fb996bf53', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.061, 'Rank IC': 0.029, 'Rank ICIR': 0.176}, 'data_train_vec': ['2021-08-01', '2025-04-30'], 'train_time_vec': ['2026-08-01', '2026-08-01'], 'rank_icir': '0.176', 'weight': '0.270'}

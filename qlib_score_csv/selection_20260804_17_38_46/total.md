# params 
 {'predict_dates': [{'start': '2026-08-04', 'end': '2026-08-04'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260804_17 591487938103557734 (Recorders: 2/5)

	Recorder: 0b42993a42b14654a9a0656218e14842

		Model: {'id': '0b42993a42b14654a9a0656218e14842', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.045, 'Rank IC': 0.028, 'Rank ICIR': 0.177}, 'data_train_vec': ['2021-08-04', '2025-05-03'], 'train_time_vec': ['2026-08-04', '2026-08-04'], 'rank_icir': '0.177', 'weight': '0.323'}

	Recorder: 1eb3862d3d594f4485f1751d68614764

		Model: {'id': '1eb3862d3d594f4485f1751d68614764', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.111, 'Rank IC': 0.024, 'Rank ICIR': 0.173}, 'data_train_vec': ['2023-08-04', '2025-11-03'], 'train_time_vec': ['2026-08-04', '2026-08-04'], 'rank_icir': '0.173', 'weight': '0.316'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260804_14 636023307404771358 (Recorders: 1/5)

	Recorder: b516e25f2dbf4232a88c99630e4debf8

		Model: {'id': 'b516e25f2dbf4232a88c99630e4debf8', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.069, 'Rank IC': 0.034, 'Rank ICIR': 0.198}, 'data_train_vec': ['2021-08-04', '2025-05-03'], 'train_time_vec': ['2026-08-04', '2026-08-04'], 'rank_icir': '0.198', 'weight': '0.361'}

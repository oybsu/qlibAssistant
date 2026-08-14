# params 
 {'predict_dates': [{'start': '2026-08-14', 'end': '2026-08-14'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260814_16 281517172188294896 (Recorders: 3/5)

	Recorder: d887f4543af44033b0dc5ea3d17f5ca2

		Model: {'id': 'd887f4543af44033b0dc5ea3d17f5ca2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.049, 'Rank IC': 0.014, 'Rank ICIR': 0.073}, 'data_train_vec': ['2021-08-14', '2025-05-13'], 'train_time_vec': ['2026-08-14', '2026-08-14'], 'rank_icir': '0.073', 'weight': '0.062'}

	Recorder: d1484881c2b948f38d876c7b890a6444

		Model: {'id': 'd1484881c2b948f38d876c7b890a6444', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.029, 'Rank IC': 0.016, 'Rank ICIR': 0.092}, 'data_train_vec': ['2022-08-14', '2025-08-13'], 'train_time_vec': ['2026-08-14', '2026-08-14'], 'rank_icir': '0.092', 'weight': '0.079'}

	Recorder: bf3d7efc554f44998bcc2d4016708f38

		Model: {'id': 'bf3d7efc554f44998bcc2d4016708f38', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.047, 'Rank IC': 0.015, 'Rank ICIR': 0.111}, 'data_train_vec': ['2023-08-14', '2025-11-13'], 'train_time_vec': ['2026-08-14', '2026-08-14'], 'rank_icir': '0.111', 'weight': '0.095'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260814_16 441401755113566687 (Recorders: 2/5)

	Recorder: ca3b64a469fb4bb09c7cb5ac2fddd0fa

		Model: {'id': 'ca3b64a469fb4bb09c7cb5ac2fddd0fa', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.036, 'Rank IC': 0.013, 'Rank ICIR': 0.096}, 'data_train_vec': ['2022-08-14', '2025-08-13'], 'train_time_vec': ['2026-08-14', '2026-08-14'], 'rank_icir': '0.096', 'weight': '0.082'}

	Recorder: 9fcdc1b25a3146dd90f80a5a6674d6ca

		Model: {'id': '9fcdc1b25a3146dd90f80a5a6674d6ca', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.097, 'Rank IC': 0.024, 'Rank ICIR': 0.177}, 'data_train_vec': ['2023-08-14', '2025-11-13'], 'train_time_vec': ['2026-08-14', '2026-08-14'], 'rank_icir': '0.177', 'weight': '0.151'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260814_13 723991620061450418 (Recorders: 3/5)

	Recorder: e674eab1d1e74d0290d59bf062e58806

		Model: {'id': 'e674eab1d1e74d0290d59bf062e58806', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.046, 'Rank IC': 0.023, 'Rank ICIR': 0.132}, 'data_train_vec': ['2021-08-14', '2025-05-13'], 'train_time_vec': ['2026-08-14', '2026-08-14'], 'rank_icir': '0.132', 'weight': '0.113'}

	Recorder: d58657d7ba29493cb6d4410094ccf1a7

		Model: {'id': 'd58657d7ba29493cb6d4410094ccf1a7', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.052, 'Rank IC': 0.024, 'Rank ICIR': 0.137}, 'data_train_vec': ['2022-08-14', '2025-08-13'], 'train_time_vec': ['2026-08-14', '2026-08-14'], 'rank_icir': '0.137', 'weight': '0.117'}

	Recorder: 9b4c5ff90add4fa9a24e30b263a0916f

		Model: {'id': '9b4c5ff90add4fa9a24e30b263a0916f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.011, 'Rank IC': 0.008, 'Rank ICIR': 0.046}, 'data_train_vec': ['2023-08-14', '2025-11-13'], 'train_time_vec': ['2026-08-14', '2026-08-14'], 'rank_icir': '0.046', 'weight': '0.039'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260814_13 304814751356067135 (Recorders: 2/5)

	Recorder: 0ca10a718cd347c18e4e044fdd99cbac

		Model: {'id': '0ca10a718cd347c18e4e044fdd99cbac', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.022, 'Rank IC': 0.022, 'Rank ICIR': 0.138}, 'data_train_vec': ['2021-08-14', '2025-05-13'], 'train_time_vec': ['2026-08-14', '2026-08-14'], 'rank_icir': '0.138', 'weight': '0.118'}

	Recorder: c04778e1ca0e488c81a7148e723c677c

		Model: {'id': 'c04778e1ca0e488c81a7148e723c677c', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.083, 'Rank IC': 0.027, 'Rank ICIR': 0.167}, 'data_train_vec': ['2022-08-14', '2025-08-13'], 'train_time_vec': ['2026-08-14', '2026-08-14'], 'rank_icir': '0.167', 'weight': '0.143'}

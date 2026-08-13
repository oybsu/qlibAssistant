# params 
 {'predict_dates': [{'start': '2026-08-13', 'end': '2026-08-13'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260813_16 123172795653757751 (Recorders: 3/5)

	Recorder: 40f9eaf2b54d411b9e64745149368fdd

		Model: {'id': '40f9eaf2b54d411b9e64745149368fdd', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.032, 'Rank IC': 0.014, 'Rank ICIR': 0.095}, 'data_train_vec': ['2021-08-13', '2025-05-12'], 'train_time_vec': ['2026-08-13', '2026-08-13'], 'rank_icir': '0.095', 'weight': '0.084'}

	Recorder: 15c0cf1961ff44549ffe0fdb6f872646

		Model: {'id': '15c0cf1961ff44549ffe0fdb6f872646', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.038, 'Rank IC': 0.012, 'Rank ICIR': 0.094}, 'data_train_vec': ['2022-08-13', '2025-08-12'], 'train_time_vec': ['2026-08-13', '2026-08-13'], 'rank_icir': '0.094', 'weight': '0.083'}

	Recorder: 4811203023c748a18bbbe20c4a5b7f6e

		Model: {'id': '4811203023c748a18bbbe20c4a5b7f6e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.094, 'Rank IC': 0.02, 'Rank ICIR': 0.156}, 'data_train_vec': ['2023-08-13', '2025-11-12'], 'train_time_vec': ['2026-08-13', '2026-08-13'], 'rank_icir': '0.156', 'weight': '0.138'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260813_13 849337110308859907 (Recorders: 2/5)

	Recorder: a7f07725a1ec43d8b90a2246e7cefba2

		Model: {'id': 'a7f07725a1ec43d8b90a2246e7cefba2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.067, 'Rank IC': 0.029, 'Rank ICIR': 0.163}, 'data_train_vec': ['2021-08-13', '2025-05-12'], 'train_time_vec': ['2026-08-13', '2026-08-13'], 'rank_icir': '0.163', 'weight': '0.144'}

	Recorder: 08be04efc0c14f39992d002cef180ab6

		Model: {'id': '08be04efc0c14f39992d002cef180ab6', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.056, 'Rank IC': 0.026, 'Rank ICIR': 0.147}, 'data_train_vec': ['2022-08-13', '2025-08-12'], 'train_time_vec': ['2026-08-13', '2026-08-13'], 'rank_icir': '0.147', 'weight': '0.130'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260813_13 396170692288371648 (Recorders: 2/5)

	Recorder: 7d13e99b13774f1bb8ee2ac83bb0f10e

		Model: {'id': '7d13e99b13774f1bb8ee2ac83bb0f10e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.031, 'Rank IC': 0.021, 'Rank ICIR': 0.131}, 'data_train_vec': ['2021-08-13', '2025-05-12'], 'train_time_vec': ['2026-08-13', '2026-08-13'], 'rank_icir': '0.131', 'weight': '0.116'}

	Recorder: 45da80d691344b2a9a57a9ec503fbf3a

		Model: {'id': '45da80d691344b2a9a57a9ec503fbf3a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.09, 'Rank IC': 0.026, 'Rank ICIR': 0.162}, 'data_train_vec': ['2022-08-13', '2025-08-12'], 'train_time_vec': ['2026-08-13', '2026-08-13'], 'rank_icir': '0.162', 'weight': '0.143'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260813_13 692065830037352632 (Recorders: 1/5)

	Recorder: bd595c5625684f868648b3c1049eaf2a

		Model: {'id': 'bd595c5625684f868648b3c1049eaf2a', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.064, 'Rank IC': 0.033, 'Rank ICIR': 0.183}, 'data_train_vec': ['2021-08-13', '2025-05-12'], 'train_time_vec': ['2026-08-13', '2026-08-13'], 'rank_icir': '0.183', 'weight': '0.162'}

# params 
 {'predict_dates': [{'start': '2026-08-11', 'end': '2026-08-11'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260811_16 159685765744619226 (Recorders: 3/5)

	Recorder: f3eb6f10d4c54c7290d7514be723aa5a

		Model: {'id': 'f3eb6f10d4c54c7290d7514be723aa5a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.008, 'Rank IC': 0.018, 'Rank ICIR': 0.135}, 'data_train_vec': ['2021-08-11', '2025-05-10'], 'train_time_vec': ['2026-08-11', '2026-08-11'], 'rank_icir': '0.135', 'weight': '0.128'}

	Recorder: e4c2fbb4cefb4fcf84e1e9711e9082af

		Model: {'id': 'e4c2fbb4cefb4fcf84e1e9711e9082af', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.124, 'Rank IC': 0.018, 'Rank ICIR': 0.147}, 'data_train_vec': ['2022-08-11', '2025-08-10'], 'train_time_vec': ['2026-08-11', '2026-08-11'], 'rank_icir': '0.147', 'weight': '0.139'}

	Recorder: 3cbcebdde07244cf9c12ab2801e429d1

		Model: {'id': '3cbcebdde07244cf9c12ab2801e429d1', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.081, 'Rank IC': 0.019, 'Rank ICIR': 0.152}, 'data_train_vec': ['2023-08-11', '2025-11-10'], 'train_time_vec': ['2026-08-11', '2026-08-11'], 'rank_icir': '0.152', 'weight': '0.144'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260811_13 934152231025480719 (Recorders: 2/5)

	Recorder: ecb6364bad4e423ea9324146179eae27

		Model: {'id': 'ecb6364bad4e423ea9324146179eae27', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.08, 'Rank IC': 0.033, 'Rank ICIR': 0.185}, 'data_train_vec': ['2021-08-11', '2025-05-10'], 'train_time_vec': ['2026-08-11', '2026-08-11'], 'rank_icir': '0.185', 'weight': '0.175'}

	Recorder: b5b15d0f3526466b8e5a355cf19662c3

		Model: {'id': 'b5b15d0f3526466b8e5a355cf19662c3', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.079, 'Rank IC': 0.024, 'Rank ICIR': 0.133}, 'data_train_vec': ['2022-08-11', '2025-08-10'], 'train_time_vec': ['2026-08-11', '2026-08-11'], 'rank_icir': '0.133', 'weight': '0.126'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260811_13 999301272006450318 (Recorders: 2/5)

	Recorder: 425b63d841e444e9820068c41a525c7a

		Model: {'id': '425b63d841e444e9820068c41a525c7a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.044, 'Rank IC': 0.024, 'Rank ICIR': 0.148}, 'data_train_vec': ['2021-08-11', '2025-05-10'], 'train_time_vec': ['2026-08-11', '2026-08-11'], 'rank_icir': '0.148', 'weight': '0.140'}

	Recorder: d8dbe07dd6da4111b000d27b791516ac

		Model: {'id': 'd8dbe07dd6da4111b000d27b791516ac', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.087, 'Rank IC': 0.026, 'Rank ICIR': 0.156}, 'data_train_vec': ['2022-08-11', '2025-08-10'], 'train_time_vec': ['2026-08-11', '2026-08-11'], 'rank_icir': '0.156', 'weight': '0.148'}

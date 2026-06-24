# params 
 {'predict_dates': [{'start': '2026-06-24', 'end': '2026-06-24'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260624_17 896733793124782543 (Recorders: 2/5)

	Recorder: b0ccbf18dd0c48689f806f2b09431d1e

		Model: {'id': 'b0ccbf18dd0c48689f806f2b09431d1e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.224, 'Rank IC': 0.029, 'Rank ICIR': 0.222}, 'data_train_vec': ['2023-06-24', '2025-09-23'], 'train_time_vec': ['2026-06-24', '2026-06-24'], 'rank_icir': '0.222', 'weight': '0.117'}

	Recorder: 5d66ccce51094ecd94b31a3b0ab9cdee

		Model: {'id': '5d66ccce51094ecd94b31a3b0ab9cdee', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.183, 'Rank IC': 0.018, 'Rank ICIR': 0.185}, 'data_train_vec': ['2024-06-24', '2025-12-23'], 'train_time_vec': ['2026-06-24', '2026-06-24'], 'rank_icir': '0.185', 'weight': '0.097'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260624_17 175975330552715022 (Recorders: 2/5)

	Recorder: 3e78251589254c6ba644a0df6bc488ae

		Model: {'id': '3e78251589254c6ba644a0df6bc488ae', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.256, 'Rank IC': 0.036, 'Rank ICIR': 0.282}, 'data_train_vec': ['2023-06-24', '2025-09-23'], 'train_time_vec': ['2026-06-24', '2026-06-24'], 'rank_icir': '0.282', 'weight': '0.148'}

	Recorder: 8a77387c976c4e74b2c498aced1b7f63

		Model: {'id': '8a77387c976c4e74b2c498aced1b7f63', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.219, 'Rank IC': 0.028, 'Rank ICIR': 0.208}, 'data_train_vec': ['2024-06-24', '2025-12-23'], 'train_time_vec': ['2026-06-24', '2026-06-24'], 'rank_icir': '0.208', 'weight': '0.109'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260624_15 253871031566578857 (Recorders: 3/5)

	Recorder: 152bd7b3f9c14b998b6e3002e634fba1

		Model: {'id': '152bd7b3f9c14b998b6e3002e634fba1', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.079, 'Rank IC': 0.047, 'Rank ICIR': 0.279}, 'data_train_vec': ['2021-06-24', '2025-03-23'], 'train_time_vec': ['2026-06-24', '2026-06-24'], 'rank_icir': '0.279', 'weight': '0.147'}

	Recorder: 461f9e4cf6344a9a93dcd2c0b3d72ecd

		Model: {'id': '461f9e4cf6344a9a93dcd2c0b3d72ecd', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.105, 'Rank IC': 0.052, 'Rank ICIR': 0.299}, 'data_train_vec': ['2022-06-24', '2025-06-23'], 'train_time_vec': ['2026-06-24', '2026-06-24'], 'rank_icir': '0.299', 'weight': '0.157'}

	Recorder: 770a7ffe2de9477cbdb560f12da3820e

		Model: {'id': '770a7ffe2de9477cbdb560f12da3820e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.181, 'Rank IC': 0.032, 'Rank ICIR': 0.233}, 'data_train_vec': ['2023-06-24', '2025-09-23'], 'train_time_vec': ['2026-06-24', '2026-06-24'], 'rank_icir': '0.233', 'weight': '0.122'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260624_14 871875166875870059 (Recorders: 2/5)

	Recorder: 21ed779a3f8f41a2b89216820db01e80

		Model: {'id': '21ed779a3f8f41a2b89216820db01e80', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.033, 'Rank IC': 0.021, 'Rank ICIR': 0.164}, 'data_train_vec': ['2023-06-24', '2025-09-23'], 'train_time_vec': ['2026-06-24', '2026-06-24'], 'rank_icir': '0.164', 'weight': '0.086'}

	Recorder: 2311e59c22f94f04982f1a52d6556ad2

		Model: {'id': '2311e59c22f94f04982f1a52d6556ad2', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.042, 'Rank IC': 0.005, 'Rank ICIR': 0.031}, 'data_train_vec': ['2024-06-24', '2025-12-23'], 'train_time_vec': ['2026-06-24', '2026-06-24'], 'rank_icir': '0.031', 'weight': '0.016'}

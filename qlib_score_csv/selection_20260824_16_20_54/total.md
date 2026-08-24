# params 
 {'predict_dates': [{'start': '2026-08-24', 'end': '2026-08-24'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260824_15 925949012883838174 (Recorders: 1/5)

	Recorder: 3140aa493aa643f8835d181908d57757

		Model: {'id': '3140aa493aa643f8835d181908d57757', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.01, 'Rank IC': 0.023, 'Rank ICIR': 0.164}, 'data_train_vec': ['2022-08-24', '2025-08-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.164', 'weight': '0.109'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260824_15 315348814174887564 (Recorders: 1/5)

	Recorder: 595d974ecf7742ffba398072ec962b42

		Model: {'id': '595d974ecf7742ffba398072ec962b42', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.059, 'Rank IC': 0.01, 'Rank ICIR': 0.083}, 'data_train_vec': ['2023-08-24', '2025-11-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.083', 'weight': '0.055'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260824_13 565290414849311744 (Recorders: 3/5)

	Recorder: e410f3278e504492bfc2fb8a31b0dc2b

		Model: {'id': 'e410f3278e504492bfc2fb8a31b0dc2b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.075, 'Rank IC': 0.026, 'Rank ICIR': 0.157}, 'data_train_vec': ['2021-08-24', '2025-05-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.157', 'weight': '0.105'}

	Recorder: c6e0d458c5f0493b8ad355f9bfcfda1a

		Model: {'id': 'c6e0d458c5f0493b8ad355f9bfcfda1a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.102, 'Rank IC': 0.032, 'Rank ICIR': 0.183}, 'data_train_vec': ['2022-08-24', '2025-08-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.183', 'weight': '0.122'}

	Recorder: bc95ff4dd57944bc9912b2107ee63fd3

		Model: {'id': 'bc95ff4dd57944bc9912b2107ee63fd3', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.015, 'Rank IC': 0.014, 'Rank ICIR': 0.077}, 'data_train_vec': ['2023-08-24', '2025-11-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.077', 'weight': '0.051'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260824_13 954892340705496515 (Recorders: 4/5)

	Recorder: 28a5f70a91e14f33b11263295bea24c8

		Model: {'id': '28a5f70a91e14f33b11263295bea24c8', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.056, 'Rank IC': 0.024, 'Rank ICIR': 0.148}, 'data_train_vec': ['2021-08-24', '2025-05-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.148', 'weight': '0.099'}

	Recorder: 6df9923f81f341b1ad60ef81d90beb46

		Model: {'id': '6df9923f81f341b1ad60ef81d90beb46', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.159, 'Rank IC': 0.035, 'Rank ICIR': 0.218}, 'data_train_vec': ['2022-08-24', '2025-08-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.218', 'weight': '0.146'}

	Recorder: 66e151263b8540ff9433e5cd5549920b

		Model: {'id': '66e151263b8540ff9433e5cd5549920b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.089, 'Rank IC': 0.016, 'Rank ICIR': 0.061}, 'data_train_vec': ['2024-08-24', '2026-02-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.061', 'weight': '0.041'}

	Recorder: 39d025c26c1c4c4abf23a7e44e005d8d

		Model: {'id': '39d025c26c1c4c4abf23a7e44e005d8d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.145, 'Rank IC': 0.02, 'Rank ICIR': 0.107}, 'data_train_vec': ['2025-08-24', '2026-05-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.107', 'weight': '0.071'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260824_13 727496483182211306 (Recorders: 3/5)

	Recorder: 3ee1f8505baa4ff0898dc99379c14f3a

		Model: {'id': '3ee1f8505baa4ff0898dc99379c14f3a', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.012, 'Rank IC': 0.023, 'Rank ICIR': 0.132}, 'data_train_vec': ['2021-08-24', '2025-05-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.132', 'weight': '0.088'}

	Recorder: 165ee80b7a47425a80769efe8eb42c20

		Model: {'id': '165ee80b7a47425a80769efe8eb42c20', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.014, 'Rank IC': 0.019, 'Rank ICIR': 0.113}, 'data_train_vec': ['2023-08-24', '2025-11-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.113', 'weight': '0.075'}

	Recorder: 129d3f3f2b054bc1b466a2aa725ff939

		Model: {'id': '129d3f3f2b054bc1b466a2aa725ff939', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.082, 'Rank IC': 0.013, 'Rank ICIR': 0.055}, 'data_train_vec': ['2025-08-24', '2026-05-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.055', 'weight': '0.037'}

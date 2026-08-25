# params 
 {'predict_dates': [{'start': '2026-08-25', 'end': '2026-08-25'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260825_15 989204074421515564 (Recorders: 1/5)

	Recorder: f51509b4deb64aca9860afc33224c954

		Model: {'id': 'f51509b4deb64aca9860afc33224c954', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.012, 'Rank IC': 0.02, 'Rank ICIR': 0.142}, 'data_train_vec': ['2023-08-25', '2025-11-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.142', 'weight': '0.097'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260825_15 957531844241582876 (Recorders: 2/5)

	Recorder: fda95cd6516a4cc985c6ee1a293359fd

		Model: {'id': 'fda95cd6516a4cc985c6ee1a293359fd', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.056, 'Rank IC': 0.02, 'Rank ICIR': 0.136}, 'data_train_vec': ['2021-08-25', '2025-05-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.136', 'weight': '0.093'}

	Recorder: a68443ccbc4a42998cfb0a5a39eba0dd

		Model: {'id': 'a68443ccbc4a42998cfb0a5a39eba0dd', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.066, 'Rank IC': 0.011, 'Rank ICIR': 0.091}, 'data_train_vec': ['2023-08-25', '2025-11-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.091', 'weight': '0.062'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260825_13 260816556385639856 (Recorders: 3/5)

	Recorder: 87ebb3c059384d6798bc0ea90c87e8fa

		Model: {'id': '87ebb3c059384d6798bc0ea90c87e8fa', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.071, 'Rank IC': 0.027, 'Rank ICIR': 0.157}, 'data_train_vec': ['2021-08-25', '2025-05-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.157', 'weight': '0.108'}

	Recorder: 8b40317d75d44d78aae6d4207fdf16bf

		Model: {'id': '8b40317d75d44d78aae6d4207fdf16bf', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.106, 'Rank IC': 0.032, 'Rank ICIR': 0.187}, 'data_train_vec': ['2022-08-25', '2025-08-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.187', 'weight': '0.128'}

	Recorder: 0ca07341ef9c4042a26d1ac41e22d177

		Model: {'id': '0ca07341ef9c4042a26d1ac41e22d177', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.006, 'Rank IC': 0.009, 'Rank ICIR': 0.051}, 'data_train_vec': ['2023-08-25', '2025-11-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.051', 'weight': '0.035'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260825_13 702287245842809105 (Recorders: 4/5)

	Recorder: f92e05fd932f4c27b315f8ace04b2c65

		Model: {'id': 'f92e05fd932f4c27b315f8ace04b2c65', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.05, 'Rank IC': 0.022, 'Rank ICIR': 0.139}, 'data_train_vec': ['2021-08-25', '2025-05-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.139', 'weight': '0.095'}

	Recorder: 1c94a535342f49bfb12c8b3c4abd037a

		Model: {'id': '1c94a535342f49bfb12c8b3c4abd037a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.15, 'Rank IC': 0.03, 'Rank ICIR': 0.193}, 'data_train_vec': ['2022-08-25', '2025-08-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.193', 'weight': '0.132'}

	Recorder: f12d774be67f40c696b3b36fd385ee78

		Model: {'id': 'f12d774be67f40c696b3b36fd385ee78', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.095, 'Rank IC': 0.018, 'Rank ICIR': 0.066}, 'data_train_vec': ['2024-08-25', '2026-02-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.066', 'weight': '0.045'}

	Recorder: 481b5c0d593542ab92a0c68343c39cbc

		Model: {'id': '481b5c0d593542ab92a0c68343c39cbc', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.062, 'ICIR': 0.285, 'Rank IC': 0.033, 'Rank ICIR': 0.205}, 'data_train_vec': ['2025-08-25', '2026-05-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.205', 'weight': '0.141'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260825_13 134425153779758572 (Recorders: 1/5)

	Recorder: 83f3a00f78a143489103ea83d1dd9b29

		Model: {'id': '83f3a00f78a143489103ea83d1dd9b29', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.053, 'ICIR': 0.156, 'Rank IC': 0.021, 'Rank ICIR': 0.092}, 'data_train_vec': ['2025-08-25', '2026-05-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.092', 'weight': '0.063'}

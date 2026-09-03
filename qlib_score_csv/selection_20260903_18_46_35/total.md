# params 
 {'predict_dates': [{'start': '2026-09-03', 'end': '2026-09-03'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260903_18 937416862781322629 (Recorders: 3/5)

	Recorder: cd7f242584694845b53ace44f3055161

		Model: {'id': 'cd7f242584694845b53ace44f3055161', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.06, 'Rank IC': 0.025, 'Rank ICIR': 0.137}, 'data_train_vec': ['2021-09-03', '2025-06-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.137', 'weight': '0.059'}

	Recorder: cd56c47afe9a4ddf9d2a32b9f078dee5

		Model: {'id': 'cd56c47afe9a4ddf9d2a32b9f078dee5', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.084, 'Rank IC': 0.025, 'Rank ICIR': 0.176}, 'data_train_vec': ['2022-09-03', '2025-09-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.176', 'weight': '0.076'}

	Recorder: a308af9d7213450f80d954eab88a79e4

		Model: {'id': 'a308af9d7213450f80d954eab88a79e4', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.09, 'Rank IC': 0.018, 'Rank ICIR': 0.107}, 'data_train_vec': ['2023-09-03', '2025-12-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.107', 'weight': '0.046'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260903_18 525314036986384205 (Recorders: 3/5)

	Recorder: 20d15201d7fa40e89cff5a412d5d5d91

		Model: {'id': '20d15201d7fa40e89cff5a412d5d5d91', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.064, 'Rank IC': 0.018, 'Rank ICIR': 0.121}, 'data_train_vec': ['2021-09-03', '2025-06-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.121', 'weight': '0.052'}

	Recorder: de5db63a32b74bad8af914c2f078e740

		Model: {'id': 'de5db63a32b74bad8af914c2f078e740', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.138, 'Rank IC': 0.025, 'Rank ICIR': 0.229}, 'data_train_vec': ['2022-09-03', '2025-09-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.229', 'weight': '0.099'}

	Recorder: 8a101e9106dd4da6b5193c94ef0cf618

		Model: {'id': '8a101e9106dd4da6b5193c94ef0cf618', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.052, 'Rank IC': 0.014, 'Rank ICIR': 0.083}, 'data_train_vec': ['2023-09-03', '2025-12-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.083', 'weight': '0.036'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260903_16 216647706696323911 (Recorders: 3/5)

	Recorder: 790fdb945b9d454a9eda72bb9ba756f3

		Model: {'id': '790fdb945b9d454a9eda72bb9ba756f3', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.098, 'Rank IC': 0.031, 'Rank ICIR': 0.187}, 'data_train_vec': ['2021-09-03', '2025-06-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.187', 'weight': '0.081'}

	Recorder: e83c945e89eb4aa7b7d510e3d901380a

		Model: {'id': 'e83c945e89eb4aa7b7d510e3d901380a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.149, 'Rank IC': 0.043, 'Rank ICIR': 0.266}, 'data_train_vec': ['2022-09-03', '2025-09-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.266', 'weight': '0.115'}

	Recorder: cd16a4b89fc14af5a5e18da43a928e4c

		Model: {'id': 'cd16a4b89fc14af5a5e18da43a928e4c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.009, 'Rank IC': 0.01, 'Rank ICIR': 0.056}, 'data_train_vec': ['2023-09-03', '2025-12-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.056', 'weight': '0.024'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260903_16 558700749526560069 (Recorders: 4/5)

	Recorder: d078417212654c8f94ed15d40b0848d9

		Model: {'id': 'd078417212654c8f94ed15d40b0848d9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.101, 'Rank IC': 0.03, 'Rank ICIR': 0.179}, 'data_train_vec': ['2021-09-03', '2025-06-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.179', 'weight': '0.077'}

	Recorder: 559841c240f442d6b74a250a56ac5e08

		Model: {'id': '559841c240f442d6b74a250a56ac5e08', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.21, 'Rank IC': 0.039, 'Rank ICIR': 0.242}, 'data_train_vec': ['2022-09-03', '2025-09-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.242', 'weight': '0.104'}

	Recorder: 7b4eeecbf3e3410f8a0e270427ff886c

		Model: {'id': '7b4eeecbf3e3410f8a0e270427ff886c', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.027, 'Rank IC': 0.003, 'Rank ICIR': 0.01}, 'data_train_vec': ['2024-09-03', '2026-03-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.010', 'weight': '0.004'}

	Recorder: e0a11fd899254e0195eb272e25a83844

		Model: {'id': 'e0a11fd899254e0195eb272e25a83844', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.077, 'ICIR': 0.383, 'Rank IC': 0.052, 'Rank ICIR': 0.283}, 'data_train_vec': ['2025-09-03', '2026-06-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.283', 'weight': '0.122'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260903_16 869385404489105276 (Recorders: 1/5)

	Recorder: 595bd86dfdec40478a0d734826d7fd90

		Model: {'id': '595bd86dfdec40478a0d734826d7fd90', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.026, 'Rank IC': 0.037, 'Rank ICIR': 0.245}, 'data_train_vec': ['2022-09-03', '2025-09-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.245', 'weight': '0.106'}

# params 
 {'predict_dates': [{'start': '2026-09-22', 'end': '2026-09-22'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260922_19 271865762989365046 (Recorders: 3/5)

	Recorder: c17627661d6a435ea98fa5db08db8392

		Model: {'id': 'c17627661d6a435ea98fa5db08db8392', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.055, 'Rank IC': 0.018, 'Rank ICIR': 0.097}, 'data_train_vec': ['2021-09-22', '2025-06-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.097', 'weight': '0.054'}

	Recorder: d3f5f63683594490bf9514848d920a60

		Model: {'id': 'd3f5f63683594490bf9514848d920a60', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.07, 'Rank IC': 0.024, 'Rank ICIR': 0.146}, 'data_train_vec': ['2022-09-22', '2025-09-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.146', 'weight': '0.081'}

	Recorder: bd83cc51247749e7b197027415b9eec0

		Model: {'id': 'bd83cc51247749e7b197027415b9eec0', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.011, 'Rank IC': 0.007, 'Rank ICIR': 0.041}, 'data_train_vec': ['2023-09-22', '2025-12-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.041', 'weight': '0.023'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260922_19 601333658787222937 (Recorders: 2/5)

	Recorder: e11b22a343fa4c3caa32d4a2453cb0f2

		Model: {'id': 'e11b22a343fa4c3caa32d4a2453cb0f2', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.147, 'Rank IC': 0.027, 'Rank ICIR': 0.187}, 'data_train_vec': ['2021-09-22', '2025-06-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.187', 'weight': '0.104'}

	Recorder: f262fe00f5e643188deff5c65cf301d5

		Model: {'id': 'f262fe00f5e643188deff5c65cf301d5', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.098, 'Rank IC': 0.018, 'Rank ICIR': 0.141}, 'data_train_vec': ['2022-09-22', '2025-09-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.141', 'weight': '0.078'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260922_17 285853012412548742 (Recorders: 2/5)

	Recorder: 53a6e7db09754ca98308f9315020ff39

		Model: {'id': '53a6e7db09754ca98308f9315020ff39', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.144, 'Rank IC': 0.037, 'Rank ICIR': 0.218}, 'data_train_vec': ['2021-09-22', '2025-06-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.218', 'weight': '0.121'}

	Recorder: 562e7d433c4f45d3beb633c8fd066a94

		Model: {'id': '562e7d433c4f45d3beb633c8fd066a94', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.095, 'Rank IC': 0.03, 'Rank ICIR': 0.171}, 'data_train_vec': ['2022-09-22', '2025-09-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.171', 'weight': '0.095'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260922_16 505544835069943393 (Recorders: 3/5)

	Recorder: 75a6aee9557c4050aa375ba47b8cf939

		Model: {'id': '75a6aee9557c4050aa375ba47b8cf939', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.14, 'Rank IC': 0.032, 'Rank ICIR': 0.191}, 'data_train_vec': ['2021-09-22', '2025-06-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.191', 'weight': '0.106'}

	Recorder: f55584ed9f4248d0a845e2758af9e24d

		Model: {'id': 'f55584ed9f4248d0a845e2758af9e24d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.13, 'Rank IC': 0.016, 'Rank ICIR': 0.095}, 'data_train_vec': ['2022-09-22', '2025-09-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.095', 'weight': '0.053'}

	Recorder: 2387674db8734a1f87d72037caa53495

		Model: {'id': '2387674db8734a1f87d72037caa53495', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.06, 'ICIR': 0.258, 'Rank IC': 0.031, 'Rank ICIR': 0.155}, 'data_train_vec': ['2024-09-22', '2026-03-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.155', 'weight': '0.086'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260922_16 673184964478212386 (Recorders: 2/5)

	Recorder: e148057eb0794df4a49fd0093d8fd21f

		Model: {'id': 'e148057eb0794df4a49fd0093d8fd21f', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.022, 'Rank IC': 0.028, 'Rank ICIR': 0.175}, 'data_train_vec': ['2021-09-22', '2025-06-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.175', 'weight': '0.097'}

	Recorder: 3a3ea68e5feb47f78568241b39f56552

		Model: {'id': '3a3ea68e5feb47f78568241b39f56552', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.077, 'Rank IC': 0.031, 'Rank ICIR': 0.189}, 'data_train_vec': ['2022-09-22', '2025-09-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.189', 'weight': '0.105'}

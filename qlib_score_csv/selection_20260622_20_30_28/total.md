# params 
 {'predict_dates': [{'start': '2026-06-22', 'end': '2026-06-22'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260622_19 253534397892523347 (Recorders: 3/5)

	Recorder: bb2a5adeb6844ca3bf581ef98f45f87a

		Model: {'id': 'bb2a5adeb6844ca3bf581ef98f45f87a', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.051, 'Rank IC': 0.02, 'Rank ICIR': 0.138}, 'data_train_vec': ['2022-06-22', '2025-06-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.138', 'weight': '0.036'}

	Recorder: 8b56187af29f4868ae895af22311937a

		Model: {'id': '8b56187af29f4868ae895af22311937a', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.014, 'Rank IC': 0.029, 'Rank ICIR': 0.192}, 'data_train_vec': ['2023-06-22', '2025-09-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.192', 'weight': '0.050'}

	Recorder: b900275c63ab466ebf960fa59fb5e800

		Model: {'id': 'b900275c63ab466ebf960fa59fb5e800', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.044, 'ICIR': 0.409, 'Rank IC': 0.035, 'Rank ICIR': 0.404}, 'data_train_vec': ['2024-06-22', '2025-12-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.404', 'weight': '0.106'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260622_19 655392455524612909 (Recorders: 4/5)

	Recorder: 99cfd2c614d4447db7b24bd3920dfea7

		Model: {'id': '99cfd2c614d4447db7b24bd3920dfea7', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.029, 'Rank IC': 0.033, 'Rank ICIR': 0.221}, 'data_train_vec': ['2022-06-22', '2025-06-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.221', 'weight': '0.058'}

	Recorder: 7b9fd98173474d6e9208985a1a3020e7

		Model: {'id': '7b9fd98173474d6e9208985a1a3020e7', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.312, 'Rank IC': 0.04, 'Rank ICIR': 0.316}, 'data_train_vec': ['2023-06-22', '2025-09-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.316', 'weight': '0.083'}

	Recorder: de2227027e054e8c86395cef17878154

		Model: {'id': 'de2227027e054e8c86395cef17878154', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.244, 'Rank IC': 0.03, 'Rank ICIR': 0.231}, 'data_train_vec': ['2024-06-22', '2025-12-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.231', 'weight': '0.061'}

	Recorder: 5f7f2e3e8953455789cd3ad66f72f3cd

		Model: {'id': '5f7f2e3e8953455789cd3ad66f72f3cd', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.043, 'ICIR': 0.162, 'Rank IC': 0.007, 'Rank ICIR': 0.028}, 'data_train_vec': ['2025-06-22', '2026-03-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.028', 'weight': '0.007'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260622_17 575831865307264141 (Recorders: 4/5)

	Recorder: 0bf13a82dcce45fd9587fce893c9d6c5

		Model: {'id': '0bf13a82dcce45fd9587fce893c9d6c5', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.1, 'Rank IC': 0.05, 'Rank ICIR': 0.292}, 'data_train_vec': ['2021-06-22', '2025-03-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.292', 'weight': '0.077'}

	Recorder: d2c9b33503d94390ab6cf41e8e7a29e7

		Model: {'id': 'd2c9b33503d94390ab6cf41e8e7a29e7', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.109, 'Rank IC': 0.047, 'Rank ICIR': 0.283}, 'data_train_vec': ['2022-06-22', '2025-06-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.283', 'weight': '0.074'}

	Recorder: 73dda1ff7eea4744a4deaa870e42562b

		Model: {'id': '73dda1ff7eea4744a4deaa870e42562b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.154, 'Rank IC': 0.032, 'Rank ICIR': 0.226}, 'data_train_vec': ['2023-06-22', '2025-09-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.226', 'weight': '0.059'}

	Recorder: b03a79f055aa484b8c98137fccc0bee4

		Model: {'id': 'b03a79f055aa484b8c98137fccc0bee4', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.153, 'Rank IC': 0.02, 'Rank ICIR': 0.158}, 'data_train_vec': ['2024-06-22', '2025-12-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.158', 'weight': '0.041'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260622_17 725709436438857370 (Recorders: 3/5)

	Recorder: 15c0f3a53d544fc586e916289831efe9

		Model: {'id': '15c0f3a53d544fc586e916289831efe9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.008, 'Rank IC': 0.035, 'Rank ICIR': 0.267}, 'data_train_vec': ['2021-06-22', '2025-03-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.267', 'weight': '0.070'}

	Recorder: 30a1ad87c57444cdb21787656177e719

		Model: {'id': '30a1ad87c57444cdb21787656177e719', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.034, 'Rank IC': 0.022, 'Rank ICIR': 0.176}, 'data_train_vec': ['2023-06-22', '2025-09-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.176', 'weight': '0.046'}

	Recorder: 460943524f6b4faa859bfd8f7f947654

		Model: {'id': '460943524f6b4faa859bfd8f7f947654', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.137, 'Rank IC': 0.019, 'Rank ICIR': 0.114}, 'data_train_vec': ['2024-06-22', '2025-12-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.114', 'weight': '0.030'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260622_17 883231373882543207 (Recorders: 3/5)

	Recorder: 11a775ea28084ae5878d252650aa7211

		Model: {'id': '11a775ea28084ae5878d252650aa7211', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.053, 'Rank IC': 0.048, 'Rank ICIR': 0.279}, 'data_train_vec': ['2022-06-22', '2025-06-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.279', 'weight': '0.073'}

	Recorder: 929b03c3cccd4cc09c60819e8a9a555a

		Model: {'id': '929b03c3cccd4cc09c60819e8a9a555a', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.066, 'Rank IC': 0.025, 'Rank ICIR': 0.168}, 'data_train_vec': ['2023-06-22', '2025-09-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.168', 'weight': '0.044'}

	Recorder: d86c833a2de34ee080ecf4ee06159077

		Model: {'id': 'd86c833a2de34ee080ecf4ee06159077', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.103, 'Rank IC': 0.028, 'Rank ICIR': 0.32}, 'data_train_vec': ['2024-06-22', '2025-12-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.320', 'weight': '0.084'}

# params 
 {'predict_dates': [{'start': '2026-09-23', 'end': '2026-09-23'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260923_19 945955054154148665 (Recorders: 3/5)

	Recorder: a30746ccdcfa4a11a841d81f9baa42a1

		Model: {'id': 'a30746ccdcfa4a11a841d81f9baa42a1', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.195, 'Rank IC': 0.033, 'Rank ICIR': 0.22}, 'data_train_vec': ['2021-09-23', '2025-06-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.220', 'weight': '0.116'}

	Recorder: 86e7045f6c9a42cc8b3a4419d41e024a

		Model: {'id': '86e7045f6c9a42cc8b3a4419d41e024a', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.097, 'Rank IC': 0.03, 'Rank ICIR': 0.173}, 'data_train_vec': ['2022-09-23', '2025-09-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.173', 'weight': '0.091'}

	Recorder: bdde666ce3dc46398c3d0ebabb8cf709

		Model: {'id': 'bdde666ce3dc46398c3d0ebabb8cf709', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.04, 'Rank IC': 0.012, 'Rank ICIR': 0.061}, 'data_train_vec': ['2023-09-23', '2025-12-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.061', 'weight': '0.032'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260923_19 440196956204844118 (Recorders: 2/5)

	Recorder: 0dd93600db0d439aa02a0b98663d3a21

		Model: {'id': '0dd93600db0d439aa02a0b98663d3a21', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.051, 'Rank IC': 0.018, 'Rank ICIR': 0.105}, 'data_train_vec': ['2021-09-23', '2025-06-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.105', 'weight': '0.055'}

	Recorder: c669be45d16b493ab95027d420e076e9

		Model: {'id': 'c669be45d16b493ab95027d420e076e9', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.149, 'Rank IC': 0.033, 'Rank ICIR': 0.211}, 'data_train_vec': ['2022-09-23', '2025-09-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.211', 'weight': '0.111'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260923_17 258344529034178063 (Recorders: 3/5)

	Recorder: 4ed0a848a22b4b95b3bf57f1501e5472

		Model: {'id': '4ed0a848a22b4b95b3bf57f1501e5472', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.138, 'Rank IC': 0.038, 'Rank ICIR': 0.229}, 'data_train_vec': ['2021-09-23', '2025-06-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.229', 'weight': '0.121'}

	Recorder: 1b9b14a938664c7a9591cc911d388d0a

		Model: {'id': '1b9b14a938664c7a9591cc911d388d0a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.112, 'Rank IC': 0.031, 'Rank ICIR': 0.177}, 'data_train_vec': ['2022-09-23', '2025-09-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.177', 'weight': '0.094'}

	Recorder: b304578994d34ba296f592f0fccd3a4b

		Model: {'id': 'b304578994d34ba296f592f0fccd3a4b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.127, 'Rank IC': 0.006, 'Rank ICIR': 0.031}, 'data_train_vec': ['2024-09-23', '2026-03-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.031', 'weight': '0.016'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260923_16 824717392370451743 (Recorders: 3/5)

	Recorder: 1cd864fe2bbc43a09122ab7b8eb7d34a

		Model: {'id': '1cd864fe2bbc43a09122ab7b8eb7d34a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.137, 'Rank IC': 0.033, 'Rank ICIR': 0.193}, 'data_train_vec': ['2021-09-23', '2025-06-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.193', 'weight': '0.102'}

	Recorder: ad0b3e57937549dc92aafb56250dcfc6

		Model: {'id': 'ad0b3e57937549dc92aafb56250dcfc6', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.124, 'Rank IC': 0.016, 'Rank ICIR': 0.092}, 'data_train_vec': ['2022-09-23', '2025-09-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.092', 'weight': '0.049'}

	Recorder: 3535e8f51f5f455eade7d5f7d2d45f5e

		Model: {'id': '3535e8f51f5f455eade7d5f7d2d45f5e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.061, 'ICIR': 0.259, 'Rank IC': 0.032, 'Rank ICIR': 0.162}, 'data_train_vec': ['2024-09-23', '2026-03-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.162', 'weight': '0.086'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260923_16 233589323343250900 (Recorders: 2/5)

	Recorder: 31ca7b3c3a4344ac95bb0fa5d7bd2d6d

		Model: {'id': '31ca7b3c3a4344ac95bb0fa5d7bd2d6d', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.056, 'Rank IC': 0.035, 'Rank ICIR': 0.211}, 'data_train_vec': ['2021-09-23', '2025-06-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.211', 'weight': '0.111'}

	Recorder: df37b6410d44476e961097734730767e

		Model: {'id': 'df37b6410d44476e961097734730767e', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.164, 'Rank IC': 0.004, 'Rank ICIR': 0.028}, 'data_train_vec': ['2024-09-23', '2026-03-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.028', 'weight': '0.015'}

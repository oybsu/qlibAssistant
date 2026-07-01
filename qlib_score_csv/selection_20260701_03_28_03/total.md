# params 
 {'predict_dates': [{'start': '2026-06-30', 'end': '2026-06-30'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260701_03 658488400602576653 (Recorders: 4/5)

	Recorder: b5632a9cabfc4e36ac783d21314b18bd

		Model: {'id': 'b5632a9cabfc4e36ac783d21314b18bd', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.059, 'Rank IC': 0.016, 'Rank ICIR': 0.118}, 'data_train_vec': ['2022-07-01', '2025-06-30'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.118', 'weight': '0.049'}

	Recorder: 7b93041a4a9e4820a02c16e95e72452b

		Model: {'id': '7b93041a4a9e4820a02c16e95e72452b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.272, 'Rank IC': 0.031, 'Rank ICIR': 0.248}, 'data_train_vec': ['2023-07-01', '2025-09-30'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.248', 'weight': '0.102'}

	Recorder: ab68231d638c4774966a8e79f0022d66

		Model: {'id': 'ab68231d638c4774966a8e79f0022d66', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.2, 'Rank IC': 0.025, 'Rank ICIR': 0.223}, 'data_train_vec': ['2024-07-01', '2025-12-31'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.223', 'weight': '0.092'}

	Recorder: f3a8d21a572b4e4f840b2daaba2c3991

		Model: {'id': 'f3a8d21a572b4e4f840b2daaba2c3991', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.134, 'Rank IC': 0.002, 'Rank ICIR': 0.016}, 'data_train_vec': ['2025-07-01', '2026-03-31'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.016', 'weight': '0.007'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260701_02 477233728753090981 (Recorders: 3/5)

	Recorder: 9db4d8cb41a449c28d02ebbcbfa6ac6d

		Model: {'id': '9db4d8cb41a449c28d02ebbcbfa6ac6d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.212, 'Rank IC': 0.028, 'Rank ICIR': 0.216}, 'data_train_vec': ['2023-07-01', '2025-09-30'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.216', 'weight': '0.089'}

	Recorder: 3513cca9684f4c1db898d7dd92c39b19

		Model: {'id': '3513cca9684f4c1db898d7dd92c39b19', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.25, 'Rank IC': 0.031, 'Rank ICIR': 0.24}, 'data_train_vec': ['2024-07-01', '2025-12-31'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.240', 'weight': '0.099'}

	Recorder: 371422d281234f6897958497de668b5c

		Model: {'id': '371422d281234f6897958497de668b5c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.069, 'ICIR': 0.284, 'Rank IC': 0.044, 'Rank ICIR': 0.203}, 'data_train_vec': ['2025-07-01', '2026-03-31'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.203', 'weight': '0.084'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260701_00 578215085073653113 (Recorders: 3/5)

	Recorder: 141c71c5940940499392e2b3dbeba129

		Model: {'id': '141c71c5940940499392e2b3dbeba129', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.041, 'Rank IC': 0.04, 'Rank ICIR': 0.237}, 'data_train_vec': ['2021-07-01', '2025-03-31'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.237', 'weight': '0.098'}

	Recorder: dec3b8e4a0e4475c8d4b9b6e5df0d38c

		Model: {'id': 'dec3b8e4a0e4475c8d4b9b6e5df0d38c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.091, 'Rank IC': 0.041, 'Rank ICIR': 0.247}, 'data_train_vec': ['2022-07-01', '2025-06-30'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.247', 'weight': '0.102'}

	Recorder: b3ee462d19084de7bdc8e44517ff3e55

		Model: {'id': 'b3ee462d19084de7bdc8e44517ff3e55', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.159, 'Rank IC': 0.027, 'Rank ICIR': 0.215}, 'data_train_vec': ['2023-07-01', '2025-09-30'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.215', 'weight': '0.089'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260701_00 477341227969317912 (Recorders: 1/5)

	Recorder: 730ad63d9fba435692c4e87a8238a81b

		Model: {'id': '730ad63d9fba435692c4e87a8238a81b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.036, 'Rank IC': 0.023, 'Rank ICIR': 0.172}, 'data_train_vec': ['2023-07-01', '2025-09-30'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.172', 'weight': '0.071'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260701_00 841074424043802180 (Recorders: 2/5)

	Recorder: 5b2c3daceed9448c838572b80137af00

		Model: {'id': '5b2c3daceed9448c838572b80137af00', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.072, 'Rank IC': 0.013, 'Rank ICIR': 0.095}, 'data_train_vec': ['2023-07-01', '2025-09-30'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.095', 'weight': '0.039'}

	Recorder: 829b4e0739bd486f82d79766c611d701

		Model: {'id': '829b4e0739bd486f82d79766c611d701', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.088, 'Rank IC': 0.02, 'Rank ICIR': 0.193}, 'data_train_vec': ['2024-07-01', '2025-12-31'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.193', 'weight': '0.080'}

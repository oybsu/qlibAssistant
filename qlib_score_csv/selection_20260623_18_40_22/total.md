# params 
 {'predict_dates': [{'start': '2026-06-23', 'end': '2026-06-23'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260623_18 451158039164573954 (Recorders: 4/5)

	Recorder: 9da1449c33a34cbf88a0d5841d81b5c6

		Model: {'id': '9da1449c33a34cbf88a0d5841d81b5c6', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.039, 'Rank IC': 0.027, 'Rank ICIR': 0.183}, 'data_train_vec': ['2021-06-23', '2025-03-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.183', 'weight': '0.047'}

	Recorder: e340ab2baa33499eafbd83281136ca24

		Model: {'id': 'e340ab2baa33499eafbd83281136ca24', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.058, 'Rank IC': 0.042, 'Rank ICIR': 0.239}, 'data_train_vec': ['2022-06-23', '2025-06-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.239', 'weight': '0.062'}

	Recorder: 7079766e05d646c7b055c6e4f43dc3c2

		Model: {'id': '7079766e05d646c7b055c6e4f43dc3c2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.353, 'Rank IC': 0.042, 'Rank ICIR': 0.376}, 'data_train_vec': ['2023-06-23', '2025-09-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.376', 'weight': '0.097'}

	Recorder: 960edddf567345c3a45c1740cf0b5b0e

		Model: {'id': '960edddf567345c3a45c1740cf0b5b0e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.039, 'ICIR': 0.371, 'Rank IC': 0.036, 'Rank ICIR': 0.415}, 'data_train_vec': ['2024-06-23', '2025-12-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.415', 'weight': '0.107'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260623_18 888265542405533921 (Recorders: 3/5)

	Recorder: ec4f075badd446b689e0545041624a48

		Model: {'id': 'ec4f075badd446b689e0545041624a48', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.044, 'Rank IC': 0.025, 'Rank ICIR': 0.138}, 'data_train_vec': ['2021-06-23', '2025-03-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.138', 'weight': '0.036'}

	Recorder: 6c019b8295ad4448b3a9ec71c1a7edcc

		Model: {'id': '6c019b8295ad4448b3a9ec71c1a7edcc', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.211, 'Rank IC': 0.035, 'Rank ICIR': 0.275}, 'data_train_vec': ['2023-06-23', '2025-09-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.275', 'weight': '0.071'}

	Recorder: a55c20c6e05c48a0800719ca11061f8b

		Model: {'id': 'a55c20c6e05c48a0800719ca11061f8b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.125, 'Rank IC': 0.012, 'Rank ICIR': 0.103}, 'data_train_vec': ['2024-06-23', '2025-12-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.103', 'weight': '0.027'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260623_15 986241774108426362 (Recorders: 4/5)

	Recorder: a685cb867cb347a298ff06823d3b11b1

		Model: {'id': 'a685cb867cb347a298ff06823d3b11b1', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.097, 'Rank IC': 0.05, 'Rank ICIR': 0.298}, 'data_train_vec': ['2021-06-23', '2025-03-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.298', 'weight': '0.077'}

	Recorder: e5b9a4de660244e2965bd73f7b7bef29

		Model: {'id': 'e5b9a4de660244e2965bd73f7b7bef29', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.132, 'Rank IC': 0.052, 'Rank ICIR': 0.305}, 'data_train_vec': ['2022-06-23', '2025-06-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.305', 'weight': '0.079'}

	Recorder: 109ca6d12b2f471198077cffc011714e

		Model: {'id': '109ca6d12b2f471198077cffc011714e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.163, 'Rank IC': 0.033, 'Rank ICIR': 0.239}, 'data_train_vec': ['2023-06-23', '2025-09-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.239', 'weight': '0.062'}

	Recorder: 10ae3e553a104a01b0837c63db821049

		Model: {'id': '10ae3e553a104a01b0837c63db821049', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.129, 'Rank IC': 0.019, 'Rank ICIR': 0.143}, 'data_train_vec': ['2024-06-23', '2025-12-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.143', 'weight': '0.037'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260623_15 643646654140006999 (Recorders: 3/5)

	Recorder: 1666d922f7ab4012928de2823d97df3d

		Model: {'id': '1666d922f7ab4012928de2823d97df3d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.018, 'Rank IC': 0.036, 'Rank ICIR': 0.274}, 'data_train_vec': ['2021-06-23', '2025-03-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.274', 'weight': '0.071'}

	Recorder: c4588d26198c499cb3d16b7cca0e37d2

		Model: {'id': 'c4588d26198c499cb3d16b7cca0e37d2', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.021, 'Rank IC': 0.021, 'Rank ICIR': 0.163}, 'data_train_vec': ['2023-06-23', '2025-09-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.163', 'weight': '0.042'}

	Recorder: 92590cea500449a986bc58486bd94763

		Model: {'id': '92590cea500449a986bc58486bd94763', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.077, 'Rank IC': 0.011, 'Rank ICIR': 0.063}, 'data_train_vec': ['2024-06-23', '2025-12-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.063', 'weight': '0.016'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260623_15 423193795492533407 (Recorders: 3/5)

	Recorder: d4c320e1ce954c75914dd1c61c402afe

		Model: {'id': 'd4c320e1ce954c75914dd1c61c402afe', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.009, 'Rank IC': 0.049, 'Rank ICIR': 0.287}, 'data_train_vec': ['2022-06-23', '2025-06-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.287', 'weight': '0.074'}

	Recorder: 6f41a1c332b443bda5fc2b6502d543ff

		Model: {'id': '6f41a1c332b443bda5fc2b6502d543ff', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.012, 'Rank IC': 0.016, 'Rank ICIR': 0.109}, 'data_train_vec': ['2023-06-23', '2025-09-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.109', 'weight': '0.028'}

	Recorder: ce38ead5ff7143a98c6c1a41f2753d15

		Model: {'id': 'ce38ead5ff7143a98c6c1a41f2753d15', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.17, 'Rank IC': 0.026, 'Rank ICIR': 0.252}, 'data_train_vec': ['2024-06-23', '2025-12-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.252', 'weight': '0.065'}

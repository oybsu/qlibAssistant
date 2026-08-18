# params 
 {'predict_dates': [{'start': '2026-08-18', 'end': '2026-08-18'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260818_15 412321482422597330 (Recorders: 2/5)

	Recorder: b4845cc82a0541e39f73d3991d4cfc8d

		Model: {'id': 'b4845cc82a0541e39f73d3991d4cfc8d', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.21, 'Rank IC': 0.031, 'Rank ICIR': 0.219}, 'data_train_vec': ['2022-08-18', '2025-08-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.219', 'weight': '0.122'}

	Recorder: 7ece5bd36ce145ecb8c6c1ae8e2eb6eb

		Model: {'id': '7ece5bd36ce145ecb8c6c1ae8e2eb6eb', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.069, 'Rank IC': 0.014, 'Rank ICIR': 0.088}, 'data_train_vec': ['2023-08-18', '2025-11-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.088', 'weight': '0.049'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260818_15 668803031562970853 (Recorders: 2/5)

	Recorder: 61173d5099aa4bba945def7d5edd3f51

		Model: {'id': '61173d5099aa4bba945def7d5edd3f51', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.018, 'Rank IC': 0.012, 'Rank ICIR': 0.087}, 'data_train_vec': ['2021-08-18', '2025-05-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.087', 'weight': '0.049'}

	Recorder: a5ce302c50e44467a874eb8f8cb3eac0

		Model: {'id': 'a5ce302c50e44467a874eb8f8cb3eac0', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.065, 'Rank IC': 0.019, 'Rank ICIR': 0.124}, 'data_train_vec': ['2023-08-18', '2025-11-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.124', 'weight': '0.069'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260818_13 121481955375642387 (Recorders: 4/5)

	Recorder: b4147a5ae1a5430e91f30338cc1cb665

		Model: {'id': 'b4147a5ae1a5430e91f30338cc1cb665', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.077, 'Rank IC': 0.027, 'Rank ICIR': 0.163}, 'data_train_vec': ['2021-08-18', '2025-05-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.163', 'weight': '0.091'}

	Recorder: 9a8ae74af9934b08987b98dba6b4a0fc

		Model: {'id': '9a8ae74af9934b08987b98dba6b4a0fc', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.11, 'Rank IC': 0.029, 'Rank ICIR': 0.171}, 'data_train_vec': ['2022-08-18', '2025-08-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.171', 'weight': '0.095'}

	Recorder: 0960471ac6104bf1bd70157f255d6277

		Model: {'id': '0960471ac6104bf1bd70157f255d6277', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.017, 'Rank IC': 0.01, 'Rank ICIR': 0.055}, 'data_train_vec': ['2023-08-18', '2025-11-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.055', 'weight': '0.031'}

	Recorder: 9eae5bf9ff424bf5a3a8d3cd59f0e18d

		Model: {'id': '9eae5bf9ff424bf5a3a8d3cd59f0e18d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.084, 'Rank IC': 0.02, 'Rank ICIR': 0.095}, 'data_train_vec': ['2025-08-18', '2026-05-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.095', 'weight': '0.053'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260818_13 338075042268426538 (Recorders: 3/5)

	Recorder: ed856019bcb04a39b0dffe19b43d5756

		Model: {'id': 'ed856019bcb04a39b0dffe19b43d5756', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.043, 'Rank IC': 0.024, 'Rank ICIR': 0.15}, 'data_train_vec': ['2021-08-18', '2025-05-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.150', 'weight': '0.084'}

	Recorder: 2584e7badc694ed7a743f25f4e5d6532

		Model: {'id': '2584e7badc694ed7a743f25f4e5d6532', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.143, 'Rank IC': 0.032, 'Rank ICIR': 0.202}, 'data_train_vec': ['2022-08-18', '2025-08-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.202', 'weight': '0.113'}

	Recorder: 1cc0e1ca226a43d3ba1a836461020315

		Model: {'id': '1cc0e1ca226a43d3ba1a836461020315', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.123, 'Rank IC': 0.003, 'Rank ICIR': 0.018}, 'data_train_vec': ['2025-08-18', '2026-05-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.018', 'weight': '0.010'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260818_13 500411929551252249 (Recorders: 4/5)

	Recorder: 7c8cebceb44140038be8a4c56cfdddfa

		Model: {'id': '7c8cebceb44140038be8a4c56cfdddfa', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.014, 'Rank IC': 0.027, 'Rank ICIR': 0.15}, 'data_train_vec': ['2021-08-18', '2025-05-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.150', 'weight': '0.084'}

	Recorder: 897f8bf48d4a459ba08900394395a57f

		Model: {'id': '897f8bf48d4a459ba08900394395a57f', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.048, 'Rank IC': 0.028, 'Rank ICIR': 0.169}, 'data_train_vec': ['2022-08-18', '2025-08-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.169', 'weight': '0.094'}

	Recorder: 744a3f15c46a498687219e981662f921

		Model: {'id': '744a3f15c46a498687219e981662f921', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.014, 'Rank IC': 0.003, 'Rank ICIR': 0.021}, 'data_train_vec': ['2023-08-18', '2025-11-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.021', 'weight': '0.012'}

	Recorder: 27623c38f4cf48efb2fdb694a969abd0

		Model: {'id': '27623c38f4cf48efb2fdb694a969abd0', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.039, 'ICIR': 0.118, 'Rank IC': 0.016, 'Rank ICIR': 0.079}, 'data_train_vec': ['2025-08-18', '2026-05-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.079', 'weight': '0.044'}

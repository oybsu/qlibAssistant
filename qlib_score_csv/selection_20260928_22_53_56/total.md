# params 
 {'predict_dates': [{'start': '2026-09-28', 'end': '2026-09-28'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260928_22 403433770571375033 (Recorders: 4/5)

	Recorder: 5903c8559125449ab451be51c6442f49

		Model: {'id': '5903c8559125449ab451be51c6442f49', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.126, 'Rank IC': 0.038, 'Rank ICIR': 0.282}, 'data_train_vec': ['2021-09-28', '2025-06-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.282', 'weight': '0.109'}

	Recorder: 9931fd5175f241a79793f960df72d457

		Model: {'id': '9931fd5175f241a79793f960df72d457', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.089, 'Rank IC': 0.027, 'Rank ICIR': 0.149}, 'data_train_vec': ['2022-09-28', '2025-09-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.149', 'weight': '0.058'}

	Recorder: 8e6caa46ba874c1792d6553a9943701b

		Model: {'id': '8e6caa46ba874c1792d6553a9943701b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.016, 'Rank IC': 0.014, 'Rank ICIR': 0.071}, 'data_train_vec': ['2023-09-28', '2025-12-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.071', 'weight': '0.028'}

	Recorder: 9aaa63ffb2374298853a8679bd28c15b

		Model: {'id': '9aaa63ffb2374298853a8679bd28c15b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.24, 'Rank IC': 0.015, 'Rank ICIR': 0.125}, 'data_train_vec': ['2024-09-28', '2026-03-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.125', 'weight': '0.048'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260928_22 809378834479473033 (Recorders: 3/5)

	Recorder: 64910464939b4257a3e4833865b667de

		Model: {'id': '64910464939b4257a3e4833865b667de', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.168, 'Rank IC': 0.041, 'Rank ICIR': 0.244}, 'data_train_vec': ['2021-09-28', '2025-06-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.244', 'weight': '0.095'}

	Recorder: 3e41f6d33efd4ed0b6d0a25b4099581c

		Model: {'id': '3e41f6d33efd4ed0b6d0a25b4099581c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.134, 'Rank IC': 0.033, 'Rank ICIR': 0.188}, 'data_train_vec': ['2022-09-28', '2025-09-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.188', 'weight': '0.073'}

	Recorder: 46cd2c41508b4f82af62744e95a8117e

		Model: {'id': '46cd2c41508b4f82af62744e95a8117e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.043, 'Rank IC': 0.015, 'Rank ICIR': 0.076}, 'data_train_vec': ['2023-09-28', '2025-12-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.076', 'weight': '0.029'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260928_19 375776945439172475 (Recorders: 3/5)

	Recorder: 279730c107c448398d7a4048bb6e80f4

		Model: {'id': '279730c107c448398d7a4048bb6e80f4', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.188, 'Rank IC': 0.047, 'Rank ICIR': 0.267}, 'data_train_vec': ['2021-09-28', '2025-06-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.267', 'weight': '0.104'}

	Recorder: f85ffbe3d54045aba775dd41a1859914

		Model: {'id': 'f85ffbe3d54045aba775dd41a1859914', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.147, 'Rank IC': 0.036, 'Rank ICIR': 0.197}, 'data_train_vec': ['2022-09-28', '2025-09-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.197', 'weight': '0.076'}

	Recorder: 00793d7ae4af4be2b25fc8e5d295572c

		Model: {'id': '00793d7ae4af4be2b25fc8e5d295572c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.042, 'Rank IC': 0.014, 'Rank ICIR': 0.064}, 'data_train_vec': ['2023-09-28', '2025-12-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.064', 'weight': '0.025'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260928_19 252375012940355921 (Recorders: 4/5)

	Recorder: 1e8302caac984c099374cc15d71eb0e3

		Model: {'id': '1e8302caac984c099374cc15d71eb0e3', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.166, 'Rank IC': 0.037, 'Rank ICIR': 0.212}, 'data_train_vec': ['2021-09-28', '2025-06-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.212', 'weight': '0.082'}

	Recorder: 263c543bedd849758d74981d415c362d

		Model: {'id': '263c543bedd849758d74981d415c362d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.136, 'Rank IC': 0.02, 'Rank ICIR': 0.108}, 'data_train_vec': ['2022-09-28', '2025-09-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.108', 'weight': '0.042'}

	Recorder: 50f70d8e6e86443a8d2ca49fdf9db60b

		Model: {'id': '50f70d8e6e86443a8d2ca49fdf9db60b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.037, 'Rank IC': 0.002, 'Rank ICIR': 0.01}, 'data_train_vec': ['2023-09-28', '2025-12-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.010', 'weight': '0.004'}

	Recorder: 45131fdbb9794aadaed6279a51442aba

		Model: {'id': '45131fdbb9794aadaed6279a51442aba', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.059, 'ICIR': 0.25, 'Rank IC': 0.033, 'Rank ICIR': 0.174}, 'data_train_vec': ['2024-09-28', '2026-03-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.174', 'weight': '0.067'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260928_19 961359636717773734 (Recorders: 2/5)

	Recorder: f712d770e879437293f90a4124c0f753

		Model: {'id': 'f712d770e879437293f90a4124c0f753', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.033, 'Rank IC': 0.035, 'Rank ICIR': 0.208}, 'data_train_vec': ['2021-09-28', '2025-06-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.208', 'weight': '0.081'}

	Recorder: c954ebe7a8b54f64a222d9317ebc61f7

		Model: {'id': 'c954ebe7a8b54f64a222d9317ebc61f7', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.048, 'ICIR': 0.213, 'Rank IC': 0.03, 'Rank ICIR': 0.204}, 'data_train_vec': ['2024-09-28', '2026-03-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.204', 'weight': '0.079'}

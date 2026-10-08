# params 
 {'predict_dates': [{'start': '2026-10-08', 'end': '2026-10-08'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20261008_21 355796008412834236 (Recorders: 4/5)

	Recorder: 61f8f6690aba46b2854da5e2d7493634

		Model: {'id': '61f8f6690aba46b2854da5e2d7493634', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.171, 'Rank IC': 0.04, 'Rank ICIR': 0.206}, 'data_train_vec': ['2021-10-08', '2025-07-07'], 'train_time_vec': ['2026-10-08', '2026-10-08'], 'rank_icir': '0.206', 'weight': '0.070'}

	Recorder: 52f682a9806d42d3bb89bedbfc58293b

		Model: {'id': '52f682a9806d42d3bb89bedbfc58293b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.073, 'Rank IC': 0.03, 'Rank ICIR': 0.168}, 'data_train_vec': ['2022-10-08', '2025-10-07'], 'train_time_vec': ['2026-10-08', '2026-10-08'], 'rank_icir': '0.168', 'weight': '0.057'}

	Recorder: 2d735ee03557405dbd95e1c5f8703d08

		Model: {'id': '2d735ee03557405dbd95e1c5f8703d08', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.014, 'Rank IC': 0.016, 'Rank ICIR': 0.077}, 'data_train_vec': ['2023-10-08', '2026-01-07'], 'train_time_vec': ['2026-10-08', '2026-10-08'], 'rank_icir': '0.077', 'weight': '0.026'}

	Recorder: 2ca9192aed2945df87e0646c89193bed

		Model: {'id': '2ca9192aed2945df87e0646c89193bed', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.199, 'Rank IC': 0.026, 'Rank ICIR': 0.201}, 'data_train_vec': ['2024-10-08', '2026-04-07'], 'train_time_vec': ['2026-10-08', '2026-10-08'], 'rank_icir': '0.201', 'weight': '0.068'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20261008_21 617920258320046508 (Recorders: 4/5)

	Recorder: 553d32350e574b8da739283907a026ca

		Model: {'id': '553d32350e574b8da739283907a026ca', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.204, 'Rank IC': 0.039, 'Rank ICIR': 0.269}, 'data_train_vec': ['2021-10-08', '2025-07-07'], 'train_time_vec': ['2026-10-08', '2026-10-08'], 'rank_icir': '0.269', 'weight': '0.091'}

	Recorder: 6448cf2e1191425b8d231d270a4423c4

		Model: {'id': '6448cf2e1191425b8d231d270a4423c4', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.156, 'Rank IC': 0.034, 'Rank ICIR': 0.171}, 'data_train_vec': ['2022-10-08', '2025-10-07'], 'train_time_vec': ['2026-10-08', '2026-10-08'], 'rank_icir': '0.171', 'weight': '0.058'}

	Recorder: 1c4d0ed8351242f695c76069248232bd

		Model: {'id': '1c4d0ed8351242f695c76069248232bd', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.076, 'Rank IC': 0.021, 'Rank ICIR': 0.098}, 'data_train_vec': ['2023-10-08', '2026-01-07'], 'train_time_vec': ['2026-10-08', '2026-10-08'], 'rank_icir': '0.098', 'weight': '0.033'}

	Recorder: a2396eaa96e044d1a6bfd5abc0ac8bfc

		Model: {'id': 'a2396eaa96e044d1a6bfd5abc0ac8bfc', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.18, 'Rank IC': 0.026, 'Rank ICIR': 0.232}, 'data_train_vec': ['2025-10-08', '2026-07-07'], 'train_time_vec': ['2026-10-08', '2026-10-08'], 'rank_icir': '0.232', 'weight': '0.078'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20261008_19 556657939879187180 (Recorders: 3/5)

	Recorder: 4551f7bb859745be87158991a31f9b3d

		Model: {'id': '4551f7bb859745be87158991a31f9b3d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.043, 'ICIR': 0.213, 'Rank IC': 0.053, 'Rank ICIR': 0.306}, 'data_train_vec': ['2021-10-08', '2025-07-07'], 'train_time_vec': ['2026-10-08', '2026-10-08'], 'rank_icir': '0.306', 'weight': '0.103'}

	Recorder: 5469e3c3be7044c7849494a515e44264

		Model: {'id': '5469e3c3be7044c7849494a515e44264', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.107, 'Rank IC': 0.028, 'Rank ICIR': 0.139}, 'data_train_vec': ['2022-10-08', '2025-10-07'], 'train_time_vec': ['2026-10-08', '2026-10-08'], 'rank_icir': '0.139', 'weight': '0.047'}

	Recorder: ec150abc583c49e8829b9e15d871c662

		Model: {'id': 'ec150abc583c49e8829b9e15d871c662', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.037, 'Rank IC': 0.011, 'Rank ICIR': 0.048}, 'data_train_vec': ['2023-10-08', '2026-01-07'], 'train_time_vec': ['2026-10-08', '2026-10-08'], 'rank_icir': '0.048', 'weight': '0.016'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20261008_18 751807432861734473 (Recorders: 3/5)

	Recorder: b827beea62894454a21aa9130b454588

		Model: {'id': 'b827beea62894454a21aa9130b454588', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.202, 'Rank IC': 0.043, 'Rank ICIR': 0.247}, 'data_train_vec': ['2021-10-08', '2025-07-07'], 'train_time_vec': ['2026-10-08', '2026-10-08'], 'rank_icir': '0.247', 'weight': '0.083'}

	Recorder: abd47a2a53f3420f8550ca02d23049b0

		Model: {'id': 'abd47a2a53f3420f8550ca02d23049b0', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.149, 'Rank IC': 0.021, 'Rank ICIR': 0.111}, 'data_train_vec': ['2022-10-08', '2025-10-07'], 'train_time_vec': ['2026-10-08', '2026-10-08'], 'rank_icir': '0.111', 'weight': '0.037'}

	Recorder: a1024490e7da428dbb9085bbe0076151

		Model: {'id': 'a1024490e7da428dbb9085bbe0076151', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.232, 'Rank IC': 0.03, 'Rank ICIR': 0.271}, 'data_train_vec': ['2025-10-08', '2026-07-07'], 'train_time_vec': ['2026-10-08', '2026-10-08'], 'rank_icir': '0.271', 'weight': '0.091'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20261008_18 303977681727787819 (Recorders: 2/5)

	Recorder: 91242725ecc04a0db0b59af0747e7e1a

		Model: {'id': '91242725ecc04a0db0b59af0747e7e1a', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.079, 'Rank IC': 0.048, 'Rank ICIR': 0.284}, 'data_train_vec': ['2021-10-08', '2025-07-07'], 'train_time_vec': ['2026-10-08', '2026-10-08'], 'rank_icir': '0.284', 'weight': '0.096'}

	Recorder: 8d4ec665ef354abcbf2114b19edf1818

		Model: {'id': '8d4ec665ef354abcbf2114b19edf1818', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.051, 'Rank IC': 0.025, 'Rank ICIR': 0.135}, 'data_train_vec': ['2022-10-08', '2025-10-07'], 'train_time_vec': ['2026-10-08', '2026-10-08'], 'rank_icir': '0.135', 'weight': '0.046'}

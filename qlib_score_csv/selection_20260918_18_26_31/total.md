# params 
 {'predict_dates': [{'start': '2026-09-18', 'end': '2026-09-18'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260918_18 493363430569595966 (Recorders: 3/5)

	Recorder: d096bdf971f44ac68c5da5db9b5616b5

		Model: {'id': 'd096bdf971f44ac68c5da5db9b5616b5', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.06, 'Rank IC': 0.034, 'Rank ICIR': 0.208}, 'data_train_vec': ['2021-09-18', '2025-06-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.208', 'weight': '0.097'}

	Recorder: e08f49b06991450c9e6195220c4e8a3d

		Model: {'id': 'e08f49b06991450c9e6195220c4e8a3d', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.077, 'Rank IC': 0.031, 'Rank ICIR': 0.195}, 'data_train_vec': ['2022-09-18', '2025-09-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.195', 'weight': '0.091'}

	Recorder: 323f335b982b4cbabaedbf508a015456

		Model: {'id': '323f335b982b4cbabaedbf508a015456', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.037, 'Rank IC': 0.009, 'Rank ICIR': 0.053}, 'data_train_vec': ['2023-09-18', '2025-12-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.053', 'weight': '0.025'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260918_17 522377594206446095 (Recorders: 3/5)

	Recorder: 70d467f391ef41a4b5c3f04f97b761ea

		Model: {'id': '70d467f391ef41a4b5c3f04f97b761ea', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.094, 'Rank IC': 0.025, 'Rank ICIR': 0.163}, 'data_train_vec': ['2021-09-18', '2025-06-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.163', 'weight': '0.076'}

	Recorder: 3d27d70d01d944489bc60d681b04889e

		Model: {'id': '3d27d70d01d944489bc60d681b04889e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.12, 'Rank IC': 0.034, 'Rank ICIR': 0.214}, 'data_train_vec': ['2022-09-18', '2025-09-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.214', 'weight': '0.100'}

	Recorder: c257eb7be69342908f2bd57962792029

		Model: {'id': 'c257eb7be69342908f2bd57962792029', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.096, 'Rank IC': 0.007, 'Rank ICIR': 0.042}, 'data_train_vec': ['2024-09-18', '2026-03-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.042', 'weight': '0.020'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260918_16 403638310267875256 (Recorders: 4/5)

	Recorder: 017a7eaf7cff4746aaa285f8411d99b2

		Model: {'id': '017a7eaf7cff4746aaa285f8411d99b2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.138, 'Rank IC': 0.035, 'Rank ICIR': 0.206}, 'data_train_vec': ['2021-09-18', '2025-06-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.206', 'weight': '0.096'}

	Recorder: 667210a8ab194c00911c0117b81d36a6

		Model: {'id': '667210a8ab194c00911c0117b81d36a6', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.11, 'Rank IC': 0.033, 'Rank ICIR': 0.189}, 'data_train_vec': ['2022-09-18', '2025-09-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.189', 'weight': '0.088'}

	Recorder: 5d2ef49005f442618a4b3cf6d237f54c

		Model: {'id': '5d2ef49005f442618a4b3cf6d237f54c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.014, 'Rank IC': 0.004, 'Rank ICIR': 0.021}, 'data_train_vec': ['2023-09-18', '2025-12-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.021', 'weight': '0.010'}

	Recorder: 18fa9f9d13b643439f186ee1674d9343

		Model: {'id': '18fa9f9d13b643439f186ee1674d9343', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.093, 'Rank IC': 0.004, 'Rank ICIR': 0.022}, 'data_train_vec': ['2024-09-18', '2026-03-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.022', 'weight': '0.010'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260918_16 508015736248083203 (Recorders: 3/5)

	Recorder: b4369316375147afb9c6185cab7d5697

		Model: {'id': 'b4369316375147afb9c6185cab7d5697', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.142, 'Rank IC': 0.034, 'Rank ICIR': 0.2}, 'data_train_vec': ['2021-09-18', '2025-06-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.200', 'weight': '0.093'}

	Recorder: 025af59051ad412c8a3ecc38b8453e05

		Model: {'id': '025af59051ad412c8a3ecc38b8453e05', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.118, 'Rank IC': 0.017, 'Rank ICIR': 0.101}, 'data_train_vec': ['2022-09-18', '2025-09-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.101', 'weight': '0.047'}

	Recorder: f86f403dba6949a98a666359db566e65

		Model: {'id': 'f86f403dba6949a98a666359db566e65', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.061, 'ICIR': 0.255, 'Rank IC': 0.037, 'Rank ICIR': 0.181}, 'data_train_vec': ['2024-09-18', '2026-03-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.181', 'weight': '0.084'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260918_16 646570303517204243 (Recorders: 3/5)

	Recorder: 363bd0e84b3946e8903a223b8d1aa9e5

		Model: {'id': '363bd0e84b3946e8903a223b8d1aa9e5', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.007, 'Rank IC': 0.029, 'Rank ICIR': 0.168}, 'data_train_vec': ['2021-09-18', '2025-06-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.168', 'weight': '0.078'}

	Recorder: 5e7b4b44daef490083f91105a4e218b9

		Model: {'id': '5e7b4b44daef490083f91105a4e218b9', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.008, 'Rank IC': 0.012, 'Rank ICIR': 0.071}, 'data_train_vec': ['2023-09-18', '2025-12-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.071', 'weight': '0.033'}

	Recorder: a9c27160bfc042e8891a1f10c4c581a2

		Model: {'id': 'a9c27160bfc042e8891a1f10c4c581a2', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.121, 'Rank IC': 0.02, 'Rank ICIR': 0.113}, 'data_train_vec': ['2024-09-18', '2026-03-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.113', 'weight': '0.053'}

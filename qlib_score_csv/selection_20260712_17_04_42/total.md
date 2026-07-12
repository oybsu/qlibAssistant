# params 
 {'predict_dates': [{'start': '2026-07-10', 'end': '2026-07-10'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260712_16 626935104950076367 (Recorders: 2/5)

	Recorder: f2c5bf4469bf4dbea6087c2a0d311b62

		Model: {'id': 'f2c5bf4469bf4dbea6087c2a0d311b62', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.145, 'Rank IC': 0.023, 'Rank ICIR': 0.202}, 'data_train_vec': ['2023-07-12', '2025-10-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.202', 'weight': '0.084'}

	Recorder: 6512c3a91a424734818cebe762e568cb

		Model: {'id': '6512c3a91a424734818cebe762e568cb', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.058, 'Rank IC': 0.007, 'Rank ICIR': 0.057}, 'data_train_vec': ['2024-07-12', '2026-01-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.057', 'weight': '0.024'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260712_16 470850720804372177 (Recorders: 4/5)

	Recorder: 6fe701e0c74e458eb3b5bff306f10a8b

		Model: {'id': '6fe701e0c74e458eb3b5bff306f10a8b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.027, 'Rank IC': 0.026, 'Rank ICIR': 0.17}, 'data_train_vec': ['2021-07-12', '2025-04-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.170', 'weight': '0.071'}

	Recorder: c9ee3512fb454b4cbe554426e0f434d7

		Model: {'id': 'c9ee3512fb454b4cbe554426e0f434d7', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.266, 'Rank IC': 0.03, 'Rank ICIR': 0.273}, 'data_train_vec': ['2023-07-12', '2025-10-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.273', 'weight': '0.114'}

	Recorder: 3ef69e2a02aa4650b9f618058c491c31

		Model: {'id': '3ef69e2a02aa4650b9f618058c491c31', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.087, 'Rank IC': 0.014, 'Rank ICIR': 0.107}, 'data_train_vec': ['2024-07-12', '2026-01-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.107', 'weight': '0.045'}

	Recorder: cede1ddebb3e4538bd4c4fc68a140cab

		Model: {'id': 'cede1ddebb3e4538bd4c4fc68a140cab', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.094, 'Rank IC': 0.004, 'Rank ICIR': 0.016}, 'data_train_vec': ['2025-07-12', '2026-04-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.016', 'weight': '0.007'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260712_14 890171890404453233 (Recorders: 3/5)

	Recorder: 15e4ef58f8d5415a8243ed901434b264

		Model: {'id': '15e4ef58f8d5415a8243ed901434b264', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.075, 'Rank IC': 0.041, 'Rank ICIR': 0.254}, 'data_train_vec': ['2021-07-12', '2025-04-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.254', 'weight': '0.106'}

	Recorder: 6009d9bdc03547cbb35e4823b3ce8e6b

		Model: {'id': '6009d9bdc03547cbb35e4823b3ce8e6b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.168, 'Rank IC': 0.042, 'Rank ICIR': 0.277}, 'data_train_vec': ['2022-07-12', '2025-07-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.277', 'weight': '0.115'}

	Recorder: bcff573c2595449a8815d33bdb4607db

		Model: {'id': 'bcff573c2595449a8815d33bdb4607db', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.189, 'Rank IC': 0.036, 'Rank ICIR': 0.282}, 'data_train_vec': ['2023-07-12', '2025-10-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.282', 'weight': '0.117'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260712_13 983380452506827905 (Recorders: 1/5)

	Recorder: a21594d6175f47d4979498936a87b588

		Model: {'id': 'a21594d6175f47d4979498936a87b588', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.058, 'Rank IC': 0.021, 'Rank ICIR': 0.144}, 'data_train_vec': ['2023-07-12', '2025-10-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.144', 'weight': '0.060'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260712_13 765015011292829588 (Recorders: 3/5)

	Recorder: bbbbc141496f4cb6aa42bceea20b0f0e

		Model: {'id': 'bbbbc141496f4cb6aa42bceea20b0f0e', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.008, 'Rank IC': 0.034, 'Rank ICIR': 0.206}, 'data_train_vec': ['2021-07-12', '2025-04-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.206', 'weight': '0.086'}

	Recorder: 7088dc57a071474d99028270b91007c5

		Model: {'id': '7088dc57a071474d99028270b91007c5', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.038, 'Rank IC': 0.035, 'Rank ICIR': 0.217}, 'data_train_vec': ['2022-07-12', '2025-07-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.217', 'weight': '0.090'}

	Recorder: 58b1ccd0ef5046ae98ff076403b7eaa0

		Model: {'id': '58b1ccd0ef5046ae98ff076403b7eaa0', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.011, 'Rank IC': 0.025, 'Rank ICIR': 0.197}, 'data_train_vec': ['2023-07-12', '2025-10-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.197', 'weight': '0.082'}

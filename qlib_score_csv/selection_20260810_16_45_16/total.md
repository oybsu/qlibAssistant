# params 
 {'predict_dates': [{'start': '2026-08-10', 'end': '2026-08-10'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260810_16 945626570017057179 (Recorders: 1/5)

	Recorder: 6c320e442d6a42468784bfd833d370fe

		Model: {'id': '6c320e442d6a42468784bfd833d370fe', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.032, 'Rank IC': 0.017, 'Rank ICIR': 0.086}, 'data_train_vec': ['2023-08-10', '2025-11-09'], 'train_time_vec': ['2026-08-10', '2026-08-10'], 'rank_icir': '0.086', 'weight': '0.070'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260810_16 130856277250518289 (Recorders: 3/5)

	Recorder: bc497890eb1b418eb768d54665781e27

		Model: {'id': 'bc497890eb1b418eb768d54665781e27', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.027, 'Rank IC': 0.015, 'Rank ICIR': 0.093}, 'data_train_vec': ['2021-08-10', '2025-05-09'], 'train_time_vec': ['2026-08-10', '2026-08-10'], 'rank_icir': '0.093', 'weight': '0.075'}

	Recorder: c355e6c8b7a9486ca17787d0e3714746

		Model: {'id': 'c355e6c8b7a9486ca17787d0e3714746', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.029, 'Rank IC': 0.014, 'Rank ICIR': 0.092}, 'data_train_vec': ['2022-08-10', '2025-08-09'], 'train_time_vec': ['2026-08-10', '2026-08-10'], 'rank_icir': '0.092', 'weight': '0.074'}

	Recorder: 41d6a2f446774b0d8c2df0f04d17ebf5

		Model: {'id': '41d6a2f446774b0d8c2df0f04d17ebf5', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.115, 'Rank IC': 0.023, 'Rank ICIR': 0.166}, 'data_train_vec': ['2023-08-10', '2025-11-09'], 'train_time_vec': ['2026-08-10', '2026-08-10'], 'rank_icir': '0.166', 'weight': '0.134'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260810_13 328172665124813934 (Recorders: 2/5)

	Recorder: 28c8bd4b9ed44dbba75063a8bfdbbf6b

		Model: {'id': '28c8bd4b9ed44dbba75063a8bfdbbf6b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.074, 'Rank IC': 0.032, 'Rank ICIR': 0.182}, 'data_train_vec': ['2021-08-10', '2025-05-09'], 'train_time_vec': ['2026-08-10', '2026-08-10'], 'rank_icir': '0.182', 'weight': '0.147'}

	Recorder: 94b89c97f4974de5b126cc66bdbd87ab

		Model: {'id': '94b89c97f4974de5b126cc66bdbd87ab', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.07, 'Rank IC': 0.025, 'Rank ICIR': 0.142}, 'data_train_vec': ['2022-08-10', '2025-08-09'], 'train_time_vec': ['2026-08-10', '2026-08-10'], 'rank_icir': '0.142', 'weight': '0.115'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260810_13 983874338515308224 (Recorders: 2/5)

	Recorder: ad0fc86d30b44dcb9c8aa4d48a0ecb59

		Model: {'id': 'ad0fc86d30b44dcb9c8aa4d48a0ecb59', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.036, 'Rank IC': 0.023, 'Rank ICIR': 0.143}, 'data_train_vec': ['2021-08-10', '2025-05-09'], 'train_time_vec': ['2026-08-10', '2026-08-10'], 'rank_icir': '0.143', 'weight': '0.116'}

	Recorder: d089746b0f4a45308222c380db4f3f86

		Model: {'id': 'd089746b0f4a45308222c380db4f3f86', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.064, 'Rank IC': 0.02, 'Rank ICIR': 0.126}, 'data_train_vec': ['2022-08-10', '2025-08-09'], 'train_time_vec': ['2026-08-10', '2026-08-10'], 'rank_icir': '0.126', 'weight': '0.102'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260810_13 524794454109231722 (Recorders: 2/5)

	Recorder: 4616b7304d774f31a52e08b5b28ee9bc

		Model: {'id': '4616b7304d774f31a52e08b5b28ee9bc', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.011, 'Rank IC': 0.028, 'Rank ICIR': 0.157}, 'data_train_vec': ['2021-08-10', '2025-05-09'], 'train_time_vec': ['2026-08-10', '2026-08-10'], 'rank_icir': '0.157', 'weight': '0.127'}

	Recorder: da54413e66344434a05e3ec4fd9ea52e

		Model: {'id': 'da54413e66344434a05e3ec4fd9ea52e', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.073, 'Rank IC': 0.011, 'Rank ICIR': 0.048}, 'data_train_vec': ['2025-08-10', '2026-05-09'], 'train_time_vec': ['2026-08-10', '2026-08-10'], 'rank_icir': '0.048', 'weight': '0.039'}

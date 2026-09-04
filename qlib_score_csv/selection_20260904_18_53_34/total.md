# params 
 {'predict_dates': [{'start': '2026-09-04', 'end': '2026-09-04'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260904_18 779970319401163189 (Recorders: 3/5)

	Recorder: e115062eae8b407785dd6eba05fd6f3e

		Model: {'id': 'e115062eae8b407785dd6eba05fd6f3e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.116, 'Rank IC': 0.033, 'Rank ICIR': 0.238}, 'data_train_vec': ['2021-09-04', '2025-06-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.238', 'weight': '0.101'}

	Recorder: ef0f2da4b6b14a8da324526424e9a2e7

		Model: {'id': 'ef0f2da4b6b14a8da324526424e9a2e7', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.041, 'Rank IC': 0.027, 'Rank ICIR': 0.196}, 'data_train_vec': ['2022-09-04', '2025-09-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.196', 'weight': '0.083'}

	Recorder: 72ee2595c8e64b81988f169cf9128413

		Model: {'id': '72ee2595c8e64b81988f169cf9128413', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.083, 'Rank IC': 0.015, 'Rank ICIR': 0.093}, 'data_train_vec': ['2023-09-04', '2025-12-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.093', 'weight': '0.040'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260904_18 743700577914744127 (Recorders: 3/5)

	Recorder: 310fa6dfa34a4b78b46ca057b0b753e0

		Model: {'id': '310fa6dfa34a4b78b46ca057b0b753e0', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.082, 'Rank IC': 0.016, 'Rank ICIR': 0.109}, 'data_train_vec': ['2021-09-04', '2025-06-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.109', 'weight': '0.046'}

	Recorder: 321a83fc9a3c470eb5f9743ec5411ffd

		Model: {'id': '321a83fc9a3c470eb5f9743ec5411ffd', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.238, 'Rank IC': 0.03, 'Rank ICIR': 0.303}, 'data_train_vec': ['2022-09-04', '2025-09-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.303', 'weight': '0.129'}

	Recorder: 778d2590f0434c4aa36a99db0ff941f5

		Model: {'id': '778d2590f0434c4aa36a99db0ff941f5', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.097, 'Rank IC': 0.017, 'Rank ICIR': 0.107}, 'data_train_vec': ['2023-09-04', '2025-12-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.107', 'weight': '0.045'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260904_16 989897810370809734 (Recorders: 3/5)

	Recorder: b3c58bed1c7845d78196b0e4c66792ee

		Model: {'id': 'b3c58bed1c7845d78196b0e4c66792ee', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.085, 'Rank IC': 0.03, 'Rank ICIR': 0.179}, 'data_train_vec': ['2021-09-04', '2025-06-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.179', 'weight': '0.076'}

	Recorder: 81212939d9e04809ae150f6abfd25a4f

		Model: {'id': '81212939d9e04809ae150f6abfd25a4f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.152, 'Rank IC': 0.044, 'Rank ICIR': 0.266}, 'data_train_vec': ['2022-09-04', '2025-09-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.266', 'weight': '0.113'}

	Recorder: 67fb7567b62840689ff9e1d6d572f3ba

		Model: {'id': '67fb7567b62840689ff9e1d6d572f3ba', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.035, 'Rank IC': 0.012, 'Rank ICIR': 0.065}, 'data_train_vec': ['2023-09-04', '2025-12-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.065', 'weight': '0.028'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260904_16 572803566891272470 (Recorders: 3/5)

	Recorder: 491bc7051c2549f8a7e0018e16c18eb1

		Model: {'id': '491bc7051c2549f8a7e0018e16c18eb1', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.082, 'Rank IC': 0.026, 'Rank ICIR': 0.156}, 'data_train_vec': ['2021-09-04', '2025-06-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.156', 'weight': '0.066'}

	Recorder: 0e4a514cfa404257b6077cc3c0c385ce

		Model: {'id': '0e4a514cfa404257b6077cc3c0c385ce', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.213, 'Rank IC': 0.038, 'Rank ICIR': 0.242}, 'data_train_vec': ['2022-09-04', '2025-09-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.242', 'weight': '0.103'}

	Recorder: 80f575b9807847918fd99bf7cdc681a1

		Model: {'id': '80f575b9807847918fd99bf7cdc681a1', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.047, 'ICIR': 0.212, 'Rank IC': 0.033, 'Rank ICIR': 0.162}, 'data_train_vec': ['2025-09-04', '2026-06-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.162', 'weight': '0.069'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260904_16 675266189109276839 (Recorders: 1/5)

	Recorder: ab275f7a6fcd416e81984d5c315e49a5

		Model: {'id': 'ab275f7a6fcd416e81984d5c315e49a5', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.055, 'Rank IC': 0.036, 'Rank ICIR': 0.237}, 'data_train_vec': ['2022-09-04', '2025-09-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.237', 'weight': '0.101'}

# params 
 {'predict_dates': [{'start': '2026-08-26', 'end': '2026-08-26'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260828_00 916059780718025544 (Recorders: 3/5)

	Recorder: 0ab02d5414d34c618592826d0802c00a

		Model: {'id': '0ab02d5414d34c618592826d0802c00a', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.031, 'Rank IC': 0.001, 'Rank ICIR': 0.008}, 'data_train_vec': ['2021-08-28', '2025-05-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.008', 'weight': '0.006'}

	Recorder: 5ba2031389b64b48af15812b9c284a66

		Model: {'id': '5ba2031389b64b48af15812b9c284a66', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.06, 'Rank IC': 0.031, 'Rank ICIR': 0.22}, 'data_train_vec': ['2022-08-28', '2025-08-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.220', 'weight': '0.163'}

	Recorder: 00178fa7b04c4606a1ada91d193cebb2

		Model: {'id': '00178fa7b04c4606a1ada91d193cebb2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.022, 'Rank IC': 0.007, 'Rank ICIR': 0.041}, 'data_train_vec': ['2023-08-28', '2025-11-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.041', 'weight': '0.030'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260828_00 418371356660258782 (Recorders: 2/5)

	Recorder: 8e3d64842c884abe95784701e4213802

		Model: {'id': '8e3d64842c884abe95784701e4213802', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.09, 'Rank IC': 0.025, 'Rank ICIR': 0.185}, 'data_train_vec': ['2021-08-28', '2025-05-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.185', 'weight': '0.137'}

	Recorder: 4846214da1df48ca9997eb7c0ea6f34a

		Model: {'id': '4846214da1df48ca9997eb7c0ea6f34a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.027, 'Rank IC': 0.01, 'Rank ICIR': 0.067}, 'data_train_vec': ['2023-08-28', '2025-11-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.067', 'weight': '0.050'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260827_22 412320782597822128 (Recorders: 3/5)

	Recorder: a961e14b0c914cb88ece93825d0509f9

		Model: {'id': 'a961e14b0c914cb88ece93825d0509f9', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.079, 'Rank IC': 0.027, 'Rank ICIR': 0.161}, 'data_train_vec': ['2021-08-27', '2025-05-26'], 'train_time_vec': ['2026-08-27', '2026-08-28'], 'rank_icir': '0.161', 'weight': '0.119'}

	Recorder: 5a0414326d0845bc9e55cff1b9e57939

		Model: {'id': '5a0414326d0845bc9e55cff1b9e57939', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.108, 'Rank IC': 0.03, 'Rank ICIR': 0.174}, 'data_train_vec': ['2022-08-27', '2025-08-26'], 'train_time_vec': ['2026-08-27', '2026-08-27'], 'rank_icir': '0.174', 'weight': '0.129'}

	Recorder: 118108ea3b8348ec8c4de3290660621c

		Model: {'id': '118108ea3b8348ec8c4de3290660621c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.006, 'Rank IC': 0.01, 'Rank ICIR': 0.051}, 'data_train_vec': ['2023-08-27', '2025-11-26'], 'train_time_vec': ['2026-08-27', '2026-08-27'], 'rank_icir': '0.051', 'weight': '0.038'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260827_22 722937667042809432 (Recorders: 4/5)

	Recorder: b3d299a5ac6a4b7d9ee90ec1dddb0b46

		Model: {'id': 'b3d299a5ac6a4b7d9ee90ec1dddb0b46', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.06, 'Rank IC': 0.024, 'Rank ICIR': 0.145}, 'data_train_vec': ['2021-08-27', '2025-05-26'], 'train_time_vec': ['2026-08-27', '2026-08-27'], 'rank_icir': '0.145', 'weight': '0.108'}

	Recorder: 47a4d638060145bcbc669307b31b7c9e

		Model: {'id': '47a4d638060145bcbc669307b31b7c9e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.154, 'Rank IC': 0.029, 'Rank ICIR': 0.186}, 'data_train_vec': ['2022-08-27', '2025-08-26'], 'train_time_vec': ['2026-08-27', '2026-08-27'], 'rank_icir': '0.186', 'weight': '0.138'}

	Recorder: 6430ac8288fe4d24ae68c9bdd06067e0

		Model: {'id': '6430ac8288fe4d24ae68c9bdd06067e0', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.098, 'Rank IC': 0.015, 'Rank ICIR': 0.056}, 'data_train_vec': ['2024-08-27', '2026-02-26'], 'train_time_vec': ['2026-08-27', '2026-08-27'], 'rank_icir': '0.056', 'weight': '0.042'}

	Recorder: e4174ccc397940a7b2ef2d5662cfeef8

		Model: {'id': 'e4174ccc397940a7b2ef2d5662cfeef8', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.185, 'Rank IC': 0.009, 'Rank ICIR': 0.054}, 'data_train_vec': ['2025-08-27', '2026-05-26'], 'train_time_vec': ['2026-08-27', '2026-08-27'], 'rank_icir': '0.054', 'weight': '0.040'}

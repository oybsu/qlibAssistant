# params 
 {'predict_dates': [{'start': '2026-09-11', 'end': '2026-09-11'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260911_19 922038403425435315 (Recorders: 2/5)

	Recorder: f67fee38316f454da27095ea15763341

		Model: {'id': 'f67fee38316f454da27095ea15763341', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.054, 'Rank IC': 0.029, 'Rank ICIR': 0.188}, 'data_train_vec': ['2022-09-11', '2025-09-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.188', 'weight': '0.076'}

	Recorder: d636588c4e974b04af3c84057f94df20

		Model: {'id': 'd636588c4e974b04af3c84057f94df20', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.047, 'Rank IC': 0.017, 'Rank ICIR': 0.108}, 'data_train_vec': ['2023-09-11', '2025-12-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.108', 'weight': '0.043'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260911_19 568382560531187794 (Recorders: 3/5)

	Recorder: cf8f1900d2e2421e922cafeda5a691a7

		Model: {'id': 'cf8f1900d2e2421e922cafeda5a691a7', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.107, 'Rank IC': 0.026, 'Rank ICIR': 0.204}, 'data_train_vec': ['2021-09-11', '2025-06-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.204', 'weight': '0.082'}

	Recorder: 0ac93ca12eae4c0ba9d4286f0cb97af7

		Model: {'id': '0ac93ca12eae4c0ba9d4286f0cb97af7', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.178, 'Rank IC': 0.046, 'Rank ICIR': 0.32}, 'data_train_vec': ['2022-09-11', '2025-09-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.320', 'weight': '0.129'}

	Recorder: ab8d18db70cf4250a9a68e153ff4c493

		Model: {'id': 'ab8d18db70cf4250a9a68e153ff4c493', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.105, 'Rank IC': 0.017, 'Rank ICIR': 0.108}, 'data_train_vec': ['2023-09-11', '2025-12-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.108', 'weight': '0.043'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260911_16 332683096225104528 (Recorders: 3/5)

	Recorder: 6c9cafb99e3645ccb7f124e1db9b22d7

		Model: {'id': '6c9cafb99e3645ccb7f124e1db9b22d7', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.139, 'Rank IC': 0.039, 'Rank ICIR': 0.233}, 'data_train_vec': ['2021-09-11', '2025-06-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.233', 'weight': '0.094'}

	Recorder: 77d33397b6994173926dc730901018c3

		Model: {'id': '77d33397b6994173926dc730901018c3', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.134, 'Rank IC': 0.043, 'Rank ICIR': 0.252}, 'data_train_vec': ['2022-09-11', '2025-09-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.252', 'weight': '0.101'}

	Recorder: ddbd9d9d28da40678dc72052e40c0d00

		Model: {'id': 'ddbd9d9d28da40678dc72052e40c0d00', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.05, 'Rank IC': 0.016, 'Rank ICIR': 0.081}, 'data_train_vec': ['2023-09-11', '2025-12-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.081', 'weight': '0.033'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260911_16 279981980721272304 (Recorders: 5/5)

	Recorder: 2ef653517254420e82d12e3c293d0d0f

		Model: {'id': '2ef653517254420e82d12e3c293d0d0f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.133, 'Rank IC': 0.035, 'Rank ICIR': 0.212}, 'data_train_vec': ['2021-09-11', '2025-06-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.212', 'weight': '0.085'}

	Recorder: c155ab4eb0f542b6b439d1b82a186d83

		Model: {'id': 'c155ab4eb0f542b6b439d1b82a186d83', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.194, 'Rank IC': 0.035, 'Rank ICIR': 0.215}, 'data_train_vec': ['2022-09-11', '2025-09-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.215', 'weight': '0.087'}

	Recorder: f63f502ac8a54fc5b92a00210a924da0

		Model: {'id': 'f63f502ac8a54fc5b92a00210a924da0', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.044, 'Rank IC': 0.006, 'Rank ICIR': 0.029}, 'data_train_vec': ['2023-09-11', '2025-12-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.029', 'weight': '0.012'}

	Recorder: 0653c690490f4dd1993de036c3536ece

		Model: {'id': '0653c690490f4dd1993de036c3536ece', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.07, 'Rank IC': 0.011, 'Rank ICIR': 0.04}, 'data_train_vec': ['2024-09-11', '2026-03-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.040', 'weight': '0.016'}

	Recorder: 73ae71cb0ed14ea3ae74206b81f6a52e

		Model: {'id': '73ae71cb0ed14ea3ae74206b81f6a52e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.047, 'ICIR': 0.214, 'Rank IC': 0.037, 'Rank ICIR': 0.179}, 'data_train_vec': ['2025-09-11', '2026-06-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.179', 'weight': '0.072'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260911_16 919759021978452065 (Recorders: 2/5)

	Recorder: ffbba2b2109f49339f7a22883b0801ef

		Model: {'id': 'ffbba2b2109f49339f7a22883b0801ef', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.054, 'Rank IC': 0.038, 'Rank ICIR': 0.235}, 'data_train_vec': ['2022-09-11', '2025-09-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.235', 'weight': '0.095'}

	Recorder: 798d0a1909cb4658bfea592e4137ef05

		Model: {'id': '798d0a1909cb4658bfea592e4137ef05', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.01, 'Rank IC': 0.014, 'Rank ICIR': 0.08}, 'data_train_vec': ['2023-09-11', '2025-12-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.080', 'weight': '0.032'}

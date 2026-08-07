# params 
 {'predict_dates': [{'start': '2026-08-07', 'end': '2026-08-07'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260807_16 670770122575871784 (Recorders: 1/5)

	Recorder: c57f3d80eb9245679b6a4403c48a6c85

		Model: {'id': 'c57f3d80eb9245679b6a4403c48a6c85', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.022, 'Rank IC': 0.03, 'Rank ICIR': 0.2}, 'data_train_vec': ['2023-08-07', '2025-11-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.200', 'weight': '0.122'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260807_16 183444388597315504 (Recorders: 3/5)

	Recorder: a7831aefa1b24897b36c64d263df26c8

		Model: {'id': 'a7831aefa1b24897b36c64d263df26c8', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.048, 'Rank IC': 0.021, 'Rank ICIR': 0.137}, 'data_train_vec': ['2021-08-07', '2025-05-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.137', 'weight': '0.083'}

	Recorder: 9c5bcdf4aec04a71ab21913383550843

		Model: {'id': '9c5bcdf4aec04a71ab21913383550843', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.051, 'Rank IC': 0.009, 'Rank ICIR': 0.066}, 'data_train_vec': ['2022-08-07', '2025-08-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.066', 'weight': '0.040'}

	Recorder: 4e70fd1268354f0fa30c8ae7cd6bd4bd

		Model: {'id': '4e70fd1268354f0fa30c8ae7cd6bd4bd', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.16, 'Rank IC': 0.033, 'Rank ICIR': 0.244}, 'data_train_vec': ['2023-08-07', '2025-11-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.244', 'weight': '0.149'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260807_13 103070458558328968 (Recorders: 3/5)

	Recorder: 6a9110a808eb4a6eb0c7df6953740e59

		Model: {'id': '6a9110a808eb4a6eb0c7df6953740e59', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.109, 'Rank IC': 0.038, 'Rank ICIR': 0.219}, 'data_train_vec': ['2021-08-07', '2025-05-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.219', 'weight': '0.133'}

	Recorder: 60f2d98061524dda8862012dacffda18

		Model: {'id': '60f2d98061524dda8862012dacffda18', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.027, 'Rank IC': 0.019, 'Rank ICIR': 0.111}, 'data_train_vec': ['2022-08-07', '2025-08-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.111', 'weight': '0.068'}

	Recorder: 7d937721f61d4a179e670888d0641c2e

		Model: {'id': '7d937721f61d4a179e670888d0641c2e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.026, 'Rank IC': 0.016, 'Rank ICIR': 0.087}, 'data_train_vec': ['2023-08-07', '2025-11-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.087', 'weight': '0.053'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260807_13 475169464984198196 (Recorders: 2/5)

	Recorder: aa0e3e5a9b8a473a88773a8ea52e3f85

		Model: {'id': 'aa0e3e5a9b8a473a88773a8ea52e3f85', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.044, 'Rank IC': 0.025, 'Rank ICIR': 0.158}, 'data_train_vec': ['2021-08-07', '2025-05-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.158', 'weight': '0.096'}

	Recorder: b30c126473f74b2891555c4844ca7284

		Model: {'id': 'b30c126473f74b2891555c4844ca7284', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.044, 'Rank IC': 0.019, 'Rank ICIR': 0.12}, 'data_train_vec': ['2022-08-07', '2025-08-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.120', 'weight': '0.073'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260807_13 898932739371328645 (Recorders: 2/5)

	Recorder: 7c4916240aa44e45803266c536700f7e

		Model: {'id': '7c4916240aa44e45803266c536700f7e', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.07, 'Rank IC': 0.039, 'Rank ICIR': 0.214}, 'data_train_vec': ['2021-08-07', '2025-05-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.214', 'weight': '0.130'}

	Recorder: a208273b295d49d28edfebe804c6005f

		Model: {'id': 'a208273b295d49d28edfebe804c6005f', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.011, 'Rank IC': 0.014, 'Rank ICIR': 0.086}, 'data_train_vec': ['2023-08-07', '2025-11-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.086', 'weight': '0.052'}

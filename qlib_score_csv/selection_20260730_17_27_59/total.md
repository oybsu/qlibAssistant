# params 
 {'predict_dates': [{'start': '2026-07-30', 'end': '2026-07-30'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260730_17 960017175577314257 (Recorders: 2/5)

	Recorder: ad53e18c57784ba887915d2e1d37b41b

		Model: {'id': 'ad53e18c57784ba887915d2e1d37b41b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.056, 'Rank IC': 0.027, 'Rank ICIR': 0.177}, 'data_train_vec': ['2021-07-28', '2025-04-27'], 'train_time_vec': ['2026-07-30', '2026-07-30'], 'rank_icir': '0.177', 'weight': '0.378'}

	Recorder: d258f76303ab4bd1bb5576aa9681c4c0

		Model: {'id': 'd258f76303ab4bd1bb5576aa9681c4c0', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.053, 'Rank IC': 0.018, 'Rank ICIR': 0.133}, 'data_train_vec': ['2023-07-30', '2025-10-29'], 'train_time_vec': ['2026-07-30', '2026-07-30'], 'rank_icir': '0.133', 'weight': '0.284'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260730_14 864037029305583774 (Recorders: 1/5)

	Recorder: 08de5088893d40e3b16f862d97e33ef2

		Model: {'id': '08de5088893d40e3b16f862d97e33ef2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.042, 'Rank IC': 0.027, 'Rank ICIR': 0.158}, 'data_train_vec': ['2021-07-28', '2025-04-27'], 'train_time_vec': ['2026-07-30', '2026-07-30'], 'rank_icir': '0.158', 'weight': '0.338'}

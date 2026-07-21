# params 
 {'predict_dates': [{'start': '2026-07-20', 'end': '2026-07-20'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260721_16 806595557830650990 (Recorders: 2/5)

	Recorder: 5f09031c898d45d196ace910efdbaf71

		Model: {'id': '5f09031c898d45d196ace910efdbaf71', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.036, 'Rank IC': 0.023, 'Rank ICIR': 0.148}, 'data_train_vec': ['2021-07-21', '2025-04-20'], 'train_time_vec': ['2026-07-21', '2026-07-21'], 'rank_icir': '0.148', 'weight': '0.207'}

	Recorder: 7c966e0173e147189936860fe4233377

		Model: {'id': '7c966e0173e147189936860fe4233377', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.103, 'Rank IC': 0.027, 'Rank ICIR': 0.233}, 'data_train_vec': ['2023-07-21', '2025-10-20'], 'train_time_vec': ['2026-07-21', '2026-07-21'], 'rank_icir': '0.233', 'weight': '0.325'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260721_14 364490046914745762 (Recorders: 2/5)

	Recorder: d9ef6deeb2a04b4c886bb68be22f5966

		Model: {'id': 'd9ef6deeb2a04b4c886bb68be22f5966', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.034, 'Rank IC': 0.034, 'Rank ICIR': 0.208}, 'data_train_vec': ['2021-07-21', '2025-04-20'], 'train_time_vec': ['2026-07-21', '2026-07-21'], 'rank_icir': '0.208', 'weight': '0.291'}

	Recorder: 13e5812fbd0f44b299d713996c2f25b5

		Model: {'id': '13e5812fbd0f44b299d713996c2f25b5', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.026, 'Rank IC': 0.019, 'Rank ICIR': 0.127}, 'data_train_vec': ['2022-07-21', '2025-07-20'], 'train_time_vec': ['2026-07-21', '2026-07-21'], 'rank_icir': '0.127', 'weight': '0.177'}

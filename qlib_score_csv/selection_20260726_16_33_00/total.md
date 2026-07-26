# params 
 {'predict_dates': [{'start': '2026-07-24', 'end': '2026-07-24'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260726_16 756163781912564884 (Recorders: 1/5)

	Recorder: 4aad08111f4e4943bd6dbdecade932ff

		Model: {'id': '4aad08111f4e4943bd6dbdecade932ff', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.054, 'Rank IC': 0.035, 'Rank ICIR': 0.178}, 'data_train_vec': ['2021-07-26', '2025-04-25'], 'train_time_vec': ['2026-07-26', '2026-07-26'], 'rank_icir': '0.178', 'weight': '0.262'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260726_16 972547020275259066 (Recorders: 1/5)

	Recorder: c783802614204f0e8a89de9feb9764c7

		Model: {'id': 'c783802614204f0e8a89de9feb9764c7', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.075, 'Rank IC': 0.016, 'Rank ICIR': 0.128}, 'data_train_vec': ['2023-07-26', '2025-10-25'], 'train_time_vec': ['2026-07-26', '2026-07-26'], 'rank_icir': '0.128', 'weight': '0.189'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260726_14 262270273303343630 (Recorders: 2/5)

	Recorder: d4b0f13a5636495ea5569bd42aa5e79c

		Model: {'id': 'd4b0f13a5636495ea5569bd42aa5e79c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.067, 'Rank IC': 0.037, 'Rank ICIR': 0.213}, 'data_train_vec': ['2021-07-26', '2025-04-25'], 'train_time_vec': ['2026-07-26', '2026-07-26'], 'rank_icir': '0.213', 'weight': '0.314'}

	Recorder: 18cd7fbe60474ef88228ce54561e0446

		Model: {'id': '18cd7fbe60474ef88228ce54561e0446', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.051, 'Rank IC': 0.025, 'Rank ICIR': 0.16}, 'data_train_vec': ['2022-07-26', '2025-07-25'], 'train_time_vec': ['2026-07-26', '2026-07-26'], 'rank_icir': '0.160', 'weight': '0.236'}

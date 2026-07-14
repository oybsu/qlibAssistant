# params 
 {'predict_dates': [{'start': '2026-07-14', 'end': '2026-07-14'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260714_16 813501488391072918 (Recorders: 2/5)

	Recorder: 08a2d11ccf4f4ccda17c781967839c09

		Model: {'id': '08a2d11ccf4f4ccda17c781967839c09', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.068, 'Rank IC': 0.029, 'Rank ICIR': 0.225}, 'data_train_vec': ['2021-07-14', '2025-04-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.225', 'weight': '0.089'}

	Recorder: 32f491665a2042f487ecb0b228db9809

		Model: {'id': '32f491665a2042f487ecb0b228db9809', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.13, 'Rank IC': 0.021, 'Rank ICIR': 0.215}, 'data_train_vec': ['2023-07-14', '2025-10-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.215', 'weight': '0.085'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260714_16 783355705499707591 (Recorders: 3/5)

	Recorder: 9560edbc4bd74686a96dd62ce8faa62f

		Model: {'id': '9560edbc4bd74686a96dd62ce8faa62f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.083, 'Rank IC': 0.041, 'Rank ICIR': 0.275}, 'data_train_vec': ['2021-07-14', '2025-04-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.275', 'weight': '0.109'}

	Recorder: f6fc29b10a87469b9a248643b3e6da9e

		Model: {'id': 'f6fc29b10a87469b9a248643b3e6da9e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.304, 'Rank IC': 0.036, 'Rank ICIR': 0.321}, 'data_train_vec': ['2023-07-14', '2025-10-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.321', 'weight': '0.127'}

	Recorder: dc40dd69ca22479fadc71d745c10ff66

		Model: {'id': 'dc40dd69ca22479fadc71d745c10ff66', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.065, 'Rank IC': 0.01, 'Rank ICIR': 0.073}, 'data_train_vec': ['2024-07-14', '2026-01-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.073', 'weight': '0.029'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260714_14 840909780936544901 (Recorders: 3/5)

	Recorder: 6a11d1080961403fbe471a3298aa57af

		Model: {'id': '6a11d1080961403fbe471a3298aa57af', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.133, 'Rank IC': 0.051, 'Rank ICIR': 0.305}, 'data_train_vec': ['2021-07-14', '2025-04-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.305', 'weight': '0.121'}

	Recorder: 2cb763dda27941929b56103e725171b3

		Model: {'id': '2cb763dda27941929b56103e725171b3', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.11, 'Rank IC': 0.036, 'Rank ICIR': 0.241}, 'data_train_vec': ['2022-07-14', '2025-07-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.241', 'weight': '0.096'}

	Recorder: 748e6c4c7e164ef8b5f2df3a4410f9cb

		Model: {'id': '748e6c4c7e164ef8b5f2df3a4410f9cb', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.097, 'Rank IC': 0.027, 'Rank ICIR': 0.214}, 'data_train_vec': ['2023-07-14', '2025-10-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.214', 'weight': '0.085'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260714_14 458052411463107495 (Recorders: 1/5)

	Recorder: c6fa75c771774b01b4e4cc201a34a6ba

		Model: {'id': 'c6fa75c771774b01b4e4cc201a34a6ba', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.028, 'Rank IC': 0.02, 'Rank ICIR': 0.135}, 'data_train_vec': ['2023-07-14', '2025-10-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.135', 'weight': '0.054'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260714_14 824908705066111263 (Recorders: 2/5)

	Recorder: dfc6446ff58b43e3a1a7ce048493d3c1

		Model: {'id': 'dfc6446ff58b43e3a1a7ce048493d3c1', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.025, 'Rank IC': 0.036, 'Rank ICIR': 0.224}, 'data_train_vec': ['2021-07-14', '2025-04-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.224', 'weight': '0.089'}

	Recorder: 2b4dd65c85784e16bd8b0cd3cd56c341

		Model: {'id': '2b4dd65c85784e16bd8b0cd3cd56c341', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.061, 'Rank IC': 0.035, 'Rank ICIR': 0.292}, 'data_train_vec': ['2023-07-14', '2025-10-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.292', 'weight': '0.116'}

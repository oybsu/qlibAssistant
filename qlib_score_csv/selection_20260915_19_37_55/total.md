# params 
 {'predict_dates': [{'start': '2026-09-15', 'end': '2026-09-15'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260915_19 120326673848477014 (Recorders: 2/5)

	Recorder: 03cef41ccae64a6a80bb82d784c3f7e0

		Model: {'id': '03cef41ccae64a6a80bb82d784c3f7e0', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.137, 'Rank IC': 0.045, 'Rank ICIR': 0.278}, 'data_train_vec': ['2022-09-15', '2025-09-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.278', 'weight': '0.104'}

	Recorder: bdb99fa7b9fa4a8ba83469c1810eaa8a

		Model: {'id': 'bdb99fa7b9fa4a8ba83469c1810eaa8a', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.04, 'Rank IC': 0.021, 'Rank ICIR': 0.121}, 'data_train_vec': ['2023-09-15', '2025-12-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.121', 'weight': '0.045'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260915_19 782282815876698617 (Recorders: 4/5)

	Recorder: 94efbd5c24b34ce8b1583066973fbecb

		Model: {'id': '94efbd5c24b34ce8b1583066973fbecb', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.118, 'Rank IC': 0.029, 'Rank ICIR': 0.195}, 'data_train_vec': ['2021-09-15', '2025-06-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.195', 'weight': '0.073'}

	Recorder: 7f0c39e4756e4051a19a1445f2347220

		Model: {'id': '7f0c39e4756e4051a19a1445f2347220', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.16, 'Rank IC': 0.04, 'Rank ICIR': 0.273}, 'data_train_vec': ['2022-09-15', '2025-09-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.273', 'weight': '0.102'}

	Recorder: 8a16a548563242689560f78ee0b538b7

		Model: {'id': '8a16a548563242689560f78ee0b538b7', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.029, 'Rank IC': 0.004, 'Rank ICIR': 0.028}, 'data_train_vec': ['2023-09-15', '2025-12-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.028', 'weight': '0.010'}

	Recorder: 9239afb9a17d41939fca0ee39037976e

		Model: {'id': '9239afb9a17d41939fca0ee39037976e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.08, 'Rank IC': 0.006, 'Rank ICIR': 0.03}, 'data_train_vec': ['2024-09-15', '2026-03-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.030', 'weight': '0.011'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260915_17 436560556116506355 (Recorders: 4/5)

	Recorder: 3dd00af5044a4f3f9fedb9b03e8ad03d

		Model: {'id': '3dd00af5044a4f3f9fedb9b03e8ad03d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.166, 'Rank IC': 0.046, 'Rank ICIR': 0.273}, 'data_train_vec': ['2021-09-15', '2025-06-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.273', 'weight': '0.102'}

	Recorder: 32d7e0885abf4d84a4efbbea07cde94a

		Model: {'id': '32d7e0885abf4d84a4efbbea07cde94a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.158, 'Rank IC': 0.043, 'Rank ICIR': 0.256}, 'data_train_vec': ['2022-09-15', '2025-09-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.256', 'weight': '0.096'}

	Recorder: b47673eff40b4d358ac604610640eafe

		Model: {'id': 'b47673eff40b4d358ac604610640eafe', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.053, 'Rank IC': 0.017, 'Rank ICIR': 0.085}, 'data_train_vec': ['2023-09-15', '2025-12-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.085', 'weight': '0.032'}

	Recorder: 74bbd99e6e504236b37c9e303fdb7942

		Model: {'id': '74bbd99e6e504236b37c9e303fdb7942', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.073, 'Rank IC': 0.007, 'Rank ICIR': 0.032}, 'data_train_vec': ['2024-09-15', '2026-03-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.032', 'weight': '0.012'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260915_16 674343709576369036 (Recorders: 5/5)

	Recorder: 90e9fda586d240f0a6ded447433ff2b1

		Model: {'id': '90e9fda586d240f0a6ded447433ff2b1', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.149, 'Rank IC': 0.039, 'Rank ICIR': 0.236}, 'data_train_vec': ['2021-09-15', '2025-06-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.236', 'weight': '0.088'}

	Recorder: bec04e9af76940489d7059f326da1616

		Model: {'id': 'bec04e9af76940489d7059f326da1616', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.168, 'Rank IC': 0.029, 'Rank ICIR': 0.171}, 'data_train_vec': ['2022-09-15', '2025-09-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.171', 'weight': '0.064'}

	Recorder: 0bdfc61990354d50a2dc7866c9dc971e

		Model: {'id': '0bdfc61990354d50a2dc7866c9dc971e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.019, 'Rank IC': 0.002, 'Rank ICIR': 0.011}, 'data_train_vec': ['2023-09-15', '2025-12-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.011', 'weight': '0.004'}

	Recorder: 03ae34be15fd49acb2aa92ff41dafed9

		Model: {'id': '03ae34be15fd49acb2aa92ff41dafed9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.046, 'ICIR': 0.159, 'Rank IC': 0.03, 'Rank ICIR': 0.121}, 'data_train_vec': ['2024-09-15', '2026-03-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.121', 'weight': '0.045'}

	Recorder: 141befd1f0d64bb3be47ff9c0283d982

		Model: {'id': '141befd1f0d64bb3be47ff9c0283d982', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.135, 'Rank IC': 0.014, 'Rank ICIR': 0.072}, 'data_train_vec': ['2025-09-15', '2026-06-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.072', 'weight': '0.027'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260915_16 302000507865097564 (Recorders: 2/5)

	Recorder: 899015856eae4797889b6d20603eb889

		Model: {'id': '899015856eae4797889b6d20603eb889', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.096, 'Rank IC': 0.047, 'Rank ICIR': 0.285}, 'data_train_vec': ['2021-09-15', '2025-06-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.285', 'weight': '0.107'}

	Recorder: 2c880cfa53d3420e9f0eab1823e58747

		Model: {'id': '2c880cfa53d3420e9f0eab1823e58747', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.01, 'Rank IC': 0.033, 'Rank ICIR': 0.204}, 'data_train_vec': ['2022-09-15', '2025-09-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.204', 'weight': '0.076'}

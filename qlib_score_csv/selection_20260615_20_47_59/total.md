# params 
 {'predict_dates': [{'start': '2026-06-15', 'end': '2026-06-15'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260615_20 919183354903759402 (Recorders: 3/5)

	Recorder: 466d3cfd00a74d728e9e3c0fea79e3ac

		Model: {'id': '466d3cfd00a74d728e9e3c0fea79e3ac', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.037, 'Rank IC': 0.028, 'Rank ICIR': 0.179}, 'data_train_vec': ['2021-06-15', '2025-03-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.179', 'weight': '0.041'}

	Recorder: 3cbf0473efb047c682dfd99b0a5a9539

		Model: {'id': '3cbf0473efb047c682dfd99b0a5a9539', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.139, 'Rank IC': 0.035, 'Rank ICIR': 0.218}, 'data_train_vec': ['2023-06-15', '2025-09-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.218', 'weight': '0.050'}

	Recorder: 20ed4cbf447542f9b699be11f8eb98a9

		Model: {'id': '20ed4cbf447542f9b699be11f8eb98a9', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.127, 'Rank IC': 0.035, 'Rank ICIR': 0.333}, 'data_train_vec': ['2024-06-15', '2025-12-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.333', 'weight': '0.076'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260615_20 588896989487756681 (Recorders: 4/5)

	Recorder: d028b41093e546c0bb603e6156813936

		Model: {'id': 'd028b41093e546c0bb603e6156813936', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.019, 'Rank IC': 0.022, 'Rank ICIR': 0.151}, 'data_train_vec': ['2021-06-15', '2025-03-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.151', 'weight': '0.034'}

	Recorder: f06cea043b654c599485b8e9c1d00e24

		Model: {'id': 'f06cea043b654c599485b8e9c1d00e24', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.033, 'Rank IC': 0.036, 'Rank ICIR': 0.278}, 'data_train_vec': ['2022-06-15', '2025-06-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.278', 'weight': '0.063'}

	Recorder: 9d41f2be2da549d895a66859626e4c62

		Model: {'id': '9d41f2be2da549d895a66859626e4c62', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.155, 'Rank IC': 0.032, 'Rank ICIR': 0.253}, 'data_train_vec': ['2023-06-15', '2025-09-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.253', 'weight': '0.057'}

	Recorder: 1d820463e02144f49c77ce5d75ff8a35

		Model: {'id': '1d820463e02144f49c77ce5d75ff8a35', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.159, 'Rank IC': 0.025, 'Rank ICIR': 0.257}, 'data_train_vec': ['2024-06-15', '2025-12-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.257', 'weight': '0.058'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260615_17 252766412697073513 (Recorders: 4/5)

	Recorder: 94ae28aa5d25435e9ca9f8a2b251e8d7

		Model: {'id': '94ae28aa5d25435e9ca9f8a2b251e8d7', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.134, 'Rank IC': 0.047, 'Rank ICIR': 0.304}, 'data_train_vec': ['2021-06-15', '2025-03-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.304', 'weight': '0.069'}

	Recorder: 097642fc3cef4f73ba398f9a22f7f172

		Model: {'id': '097642fc3cef4f73ba398f9a22f7f172', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.176, 'Rank IC': 0.055, 'Rank ICIR': 0.333}, 'data_train_vec': ['2022-06-15', '2025-06-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.333', 'weight': '0.076'}

	Recorder: 61a12e06a0194eacb7c35a6066286f71

		Model: {'id': '61a12e06a0194eacb7c35a6066286f71', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.163, 'Rank IC': 0.038, 'Rank ICIR': 0.26}, 'data_train_vec': ['2023-06-15', '2025-09-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.260', 'weight': '0.059'}

	Recorder: 0ffa4b0de922459d8cc1d1dd3c95ff67

		Model: {'id': '0ffa4b0de922459d8cc1d1dd3c95ff67', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.093, 'Rank IC': 0.02, 'Rank ICIR': 0.184}, 'data_train_vec': ['2024-06-15', '2025-12-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.184', 'weight': '0.042'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260615_17 268491968817651162 (Recorders: 4/5)

	Recorder: 7c2811a30df54554bda1ecaedee36107

		Model: {'id': '7c2811a30df54554bda1ecaedee36107', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.115, 'Rank IC': 0.043, 'Rank ICIR': 0.363}, 'data_train_vec': ['2021-06-15', '2025-03-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.363', 'weight': '0.082'}

	Recorder: e83e37b6bafd49bdb035c2123751f8e1

		Model: {'id': 'e83e37b6bafd49bdb035c2123751f8e1', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.044, 'Rank IC': 0.043, 'Rank ICIR': 0.317}, 'data_train_vec': ['2022-06-15', '2025-06-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.317', 'weight': '0.072'}

	Recorder: 3993a3fac2a1407f9b8a30141158237d

		Model: {'id': '3993a3fac2a1407f9b8a30141158237d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.081, 'Rank IC': 0.034, 'Rank ICIR': 0.291}, 'data_train_vec': ['2023-06-15', '2025-09-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.291', 'weight': '0.066'}

	Recorder: f07374671f334dc8832af9841871bde8

		Model: {'id': 'f07374671f334dc8832af9841871bde8', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.102, 'Rank IC': 0.022, 'Rank ICIR': 0.158}, 'data_train_vec': ['2024-06-15', '2025-12-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.158', 'weight': '0.036'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260615_17 495544038630135275 (Recorders: 2/5)

	Recorder: 17b9687e05f3483b86145fa82f1cb5bc

		Model: {'id': '17b9687e05f3483b86145fa82f1cb5bc', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.034, 'Rank IC': 0.039, 'Rank ICIR': 0.239}, 'data_train_vec': ['2021-06-15', '2025-03-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.239', 'weight': '0.054'}

	Recorder: 9312461949214a2b9033c4aa13d93dac

		Model: {'id': '9312461949214a2b9033c4aa13d93dac', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.143, 'Rank IC': 0.048, 'Rank ICIR': 0.284}, 'data_train_vec': ['2022-06-15', '2025-06-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.284', 'weight': '0.065'}

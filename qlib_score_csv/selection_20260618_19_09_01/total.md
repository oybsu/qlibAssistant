# params 
 {'predict_dates': [{'start': '2026-06-18', 'end': '2026-06-18'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260618_18 514188509422711256 (Recorders: 3/5)

	Recorder: 3cfdb5ca2a15451e93903e0581f06fd7

		Model: {'id': '3cfdb5ca2a15451e93903e0581f06fd7', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.016, 'Rank IC': 0.025, 'Rank ICIR': 0.154}, 'data_train_vec': ['2021-06-18', '2025-03-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.154', 'weight': '0.042'}

	Recorder: 3207b6dab89e42ea9935127337c8899c

		Model: {'id': '3207b6dab89e42ea9935127337c8899c', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.183, 'Rank IC': 0.036, 'Rank ICIR': 0.258}, 'data_train_vec': ['2023-06-18', '2025-09-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.258', 'weight': '0.070'}

	Recorder: 717544b42b5543909eeebfd500d53d3e

		Model: {'id': '717544b42b5543909eeebfd500d53d3e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.31, 'Rank IC': 0.038, 'Rank ICIR': 0.363}, 'data_train_vec': ['2024-06-18', '2025-12-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.363', 'weight': '0.098'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260618_18 836503072482948179 (Recorders: 4/5)

	Recorder: dff35f68924b4a0fbf3bf73dcfd2a16d

		Model: {'id': 'dff35f68924b4a0fbf3bf73dcfd2a16d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.043, 'Rank IC': 0.035, 'Rank ICIR': 0.255}, 'data_train_vec': ['2022-06-18', '2025-06-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.255', 'weight': '0.069'}

	Recorder: 6ec78aabeded4ecda51739f8c45a65d8

		Model: {'id': '6ec78aabeded4ecda51739f8c45a65d8', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.266, 'Rank IC': 0.036, 'Rank ICIR': 0.301}, 'data_train_vec': ['2023-06-18', '2025-09-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.301', 'weight': '0.081'}

	Recorder: 9407bd05f90d401c887f8d149b7fb363

		Model: {'id': '9407bd05f90d401c887f8d149b7fb363', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.211, 'Rank IC': 0.033, 'Rank ICIR': 0.302}, 'data_train_vec': ['2024-06-18', '2025-12-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.302', 'weight': '0.082'}

	Recorder: bee98e1f5c5f4475900838a708f99b61

		Model: {'id': 'bee98e1f5c5f4475900838a708f99b61', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.165, 'Rank IC': 0.009, 'Rank ICIR': 0.04}, 'data_train_vec': ['2025-06-18', '2026-03-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.040', 'weight': '0.011'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260618_16 146383737818707906 (Recorders: 4/5)

	Recorder: 3c49a33e49cf4710addf9aa5bf99fdb2

		Model: {'id': '3c49a33e49cf4710addf9aa5bf99fdb2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.069, 'Rank IC': 0.042, 'Rank ICIR': 0.269}, 'data_train_vec': ['2021-06-18', '2025-03-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.269', 'weight': '0.073'}

	Recorder: 9527d3f937fe4fabb0dbdc5413862f75

		Model: {'id': '9527d3f937fe4fabb0dbdc5413862f75', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.115, 'Rank IC': 0.048, 'Rank ICIR': 0.285}, 'data_train_vec': ['2022-06-18', '2025-06-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.285', 'weight': '0.077'}

	Recorder: 1f2c235e657f4ff6b3558b13599d7d6e

		Model: {'id': '1f2c235e657f4ff6b3558b13599d7d6e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.108, 'Rank IC': 0.034, 'Rank ICIR': 0.233}, 'data_train_vec': ['2023-06-18', '2025-09-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.233', 'weight': '0.063'}

	Recorder: 40cadd4ff66c4320946a09e8307da22b

		Model: {'id': '40cadd4ff66c4320946a09e8307da22b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.119, 'Rank IC': 0.019, 'Rank ICIR': 0.161}, 'data_train_vec': ['2024-06-18', '2025-12-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.161', 'weight': '0.044'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260618_15 164740125484537206 (Recorders: 3/5)

	Recorder: 977aa94552874ddfade3451c1841bc9a

		Model: {'id': '977aa94552874ddfade3451c1841bc9a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.017, 'Rank IC': 0.035, 'Rank ICIR': 0.288}, 'data_train_vec': ['2021-06-18', '2025-03-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.288', 'weight': '0.078'}

	Recorder: 6c78fe560d94479f82d5409dadbc1697

		Model: {'id': '6c78fe560d94479f82d5409dadbc1697', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.017, 'Rank IC': 0.026, 'Rank ICIR': 0.207}, 'data_train_vec': ['2023-06-18', '2025-09-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.207', 'weight': '0.056'}

	Recorder: 448384e235084ad5a9b95f2ae99cb943

		Model: {'id': '448384e235084ad5a9b95f2ae99cb943', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.129, 'Rank IC': 0.019, 'Rank ICIR': 0.131}, 'data_train_vec': ['2024-06-18', '2025-12-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.131', 'weight': '0.035'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260618_15 142971405164063380 (Recorders: 2/5)

	Recorder: ada836d6b77240f2ae7b5f38af7b3e02

		Model: {'id': 'ada836d6b77240f2ae7b5f38af7b3e02', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.025, 'Rank IC': 0.037, 'Rank ICIR': 0.22}, 'data_train_vec': ['2021-06-18', '2025-03-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.220', 'weight': '0.060'}

	Recorder: 4b0677f7e3284836b062c62d100979ae

		Model: {'id': '4b0677f7e3284836b062c62d100979ae', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.049, 'Rank IC': 0.022, 'Rank ICIR': 0.23}, 'data_train_vec': ['2024-06-18', '2025-12-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.230', 'weight': '0.062'}

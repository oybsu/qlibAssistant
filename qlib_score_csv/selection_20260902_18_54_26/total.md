# params 
 {'predict_dates': [{'start': '2026-09-02', 'end': '2026-09-02'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260902_18 992497625444908859 (Recorders: 2/5)

	Recorder: 7b46e4d79c6748fab48322857d79f9b4

		Model: {'id': '7b46e4d79c6748fab48322857d79f9b4', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.082, 'Rank IC': 0.029, 'Rank ICIR': 0.19}, 'data_train_vec': ['2022-09-02', '2025-09-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.190', 'weight': '0.081'}

	Recorder: d0300932993d405896b09b96d4d7d94c

		Model: {'id': 'd0300932993d405896b09b96d4d7d94c', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.063, 'Rank IC': 0.018, 'Rank ICIR': 0.114}, 'data_train_vec': ['2023-09-02', '2025-12-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.114', 'weight': '0.049'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260902_18 517330783152468713 (Recorders: 3/5)

	Recorder: 9eb73de79e454e6ebe96d6f48eb387ea

		Model: {'id': '9eb73de79e454e6ebe96d6f48eb387ea', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.034, 'Rank IC': 0.016, 'Rank ICIR': 0.117}, 'data_train_vec': ['2021-09-02', '2025-06-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.117', 'weight': '0.050'}

	Recorder: 87717b781cb6462eb937a8f01d94adbf

		Model: {'id': '87717b781cb6462eb937a8f01d94adbf', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.114, 'Rank IC': 0.032, 'Rank ICIR': 0.215}, 'data_train_vec': ['2022-09-02', '2025-09-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.215', 'weight': '0.092'}

	Recorder: ec1321ba87394fe49a0c7a3375eea807

		Model: {'id': 'ec1321ba87394fe49a0c7a3375eea807', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.057, 'Rank IC': 0.011, 'Rank ICIR': 0.072}, 'data_train_vec': ['2023-09-02', '2025-12-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.072', 'weight': '0.031'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260902_16 872878449795207137 (Recorders: 3/5)

	Recorder: 11a5fdedc628420eaa2234f679f2efef

		Model: {'id': '11a5fdedc628420eaa2234f679f2efef', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.069, 'Rank IC': 0.024, 'Rank ICIR': 0.144}, 'data_train_vec': ['2021-09-02', '2025-06-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.144', 'weight': '0.062'}

	Recorder: 7b4e8ecb764b4117af90a1202a071d48

		Model: {'id': '7b4e8ecb764b4117af90a1202a071d48', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.145, 'Rank IC': 0.045, 'Rank ICIR': 0.261}, 'data_train_vec': ['2022-09-02', '2025-09-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.261', 'weight': '0.112'}

	Recorder: d75fff11ab6c4317b2dd8cb33f8a6099

		Model: {'id': 'd75fff11ab6c4317b2dd8cb33f8a6099', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.027, 'Rank IC': 0.016, 'Rank ICIR': 0.084}, 'data_train_vec': ['2023-09-02', '2025-12-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.084', 'weight': '0.036'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260902_16 408235844284706779 (Recorders: 5/5)

	Recorder: 4ff387af466744528024ede0ac6debc3

		Model: {'id': '4ff387af466744528024ede0ac6debc3', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.102, 'Rank IC': 0.03, 'Rank ICIR': 0.178}, 'data_train_vec': ['2021-09-02', '2025-06-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.178', 'weight': '0.076'}

	Recorder: 616b5127d51f44b181a20b51806b590b

		Model: {'id': '616b5127d51f44b181a20b51806b590b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.039, 'ICIR': 0.202, 'Rank IC': 0.037, 'Rank ICIR': 0.233}, 'data_train_vec': ['2022-09-02', '2025-09-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.233', 'weight': '0.100'}

	Recorder: c2d499381e2f464a86e6bfe788be58b9

		Model: {'id': 'c2d499381e2f464a86e6bfe788be58b9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.024, 'Rank IC': 0.002, 'Rank ICIR': 0.009}, 'data_train_vec': ['2023-09-02', '2025-12-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.009', 'weight': '0.004'}

	Recorder: 9b6a324510044265a3794d923d3a3e52

		Model: {'id': '9b6a324510044265a3794d923d3a3e52', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.025, 'Rank IC': 0.005, 'Rank ICIR': 0.018}, 'data_train_vec': ['2024-09-02', '2026-03-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.018', 'weight': '0.008'}

	Recorder: b71b6611e0e8436596fbec32976f1012

		Model: {'id': 'b71b6611e0e8436596fbec32976f1012', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.078, 'ICIR': 0.391, 'Rank IC': 0.055, 'Rank ICIR': 0.309}, 'data_train_vec': ['2025-09-02', '2026-06-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.309', 'weight': '0.132'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260902_16 788503992985018760 (Recorders: 2/5)

	Recorder: e3c5e3daa6964e038538a82f55c3c161

		Model: {'id': 'e3c5e3daa6964e038538a82f55c3c161', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.033, 'Rank IC': 0.025, 'Rank ICIR': 0.148}, 'data_train_vec': ['2021-09-02', '2025-06-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.148', 'weight': '0.063'}

	Recorder: 482f3165bfdb40e1971802fa6f22f564

		Model: {'id': '482f3165bfdb40e1971802fa6f22f564', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.057, 'Rank IC': 0.04, 'Rank ICIR': 0.247}, 'data_train_vec': ['2022-09-02', '2025-09-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.247', 'weight': '0.106'}

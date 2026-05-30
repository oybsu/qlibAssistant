# params 
 {'predict_dates': [{'start': '2026-05-29', 'end': '2026-05-29'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260530_16 321217330985636255 (Recorders: 4/5)

	Recorder: 6fcccc9c412246189b6e9dd7433ffa01

		Model: {'id': '6fcccc9c412246189b6e9dd7433ffa01', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.012, 'Rank IC': 0.022, 'Rank ICIR': 0.15}, 'data_train_vec': ['2021-05-28', '2025-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.150', 'weight': '0.054'}

	Recorder: dee5b38ee2ec411fb7ef76ae82d43b2b

		Model: {'id': 'dee5b38ee2ec411fb7ef76ae82d43b2b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.008, 'Rank IC': 0.019, 'Rank ICIR': 0.137}, 'data_train_vec': ['2022-05-30', '2025-05-29'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.137', 'weight': '0.049'}

	Recorder: 9d4faf8fc6374ebcb27ac099a0217179

		Model: {'id': '9d4faf8fc6374ebcb27ac099a0217179', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.31, 'Rank IC': 0.029, 'Rank ICIR': 0.196}, 'data_train_vec': ['2023-05-28', '2025-08-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.196', 'weight': '0.071'}

	Recorder: 78f56ae65a93492dbe58e3483c4f91b8

		Model: {'id': '78f56ae65a93492dbe58e3483c4f91b8', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.048, 'ICIR': 0.245, 'Rank IC': 0.012, 'Rank ICIR': 0.058}, 'data_train_vec': ['2025-05-28', '2026-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.058', 'weight': '0.021'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260530_16 695028177308281676 (Recorders: 3/5)

	Recorder: 888d2ec3b212463cbcb911263aed4fe2

		Model: {'id': '888d2ec3b212463cbcb911263aed4fe2', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.16, 'Rank IC': 0.027, 'Rank ICIR': 0.189}, 'data_train_vec': ['2023-05-28', '2025-08-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.189', 'weight': '0.068'}

	Recorder: 52b828ab4f5e4245825a68b0ed1149a3

		Model: {'id': '52b828ab4f5e4245825a68b0ed1149a3', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.081, 'Rank IC': 0.009, 'Rank ICIR': 0.083}, 'data_train_vec': ['2024-05-30', '2025-11-29'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.083', 'weight': '0.030'}

	Recorder: e8238675bc924e6da1c3e2d8aac10c1c

		Model: {'id': 'e8238675bc924e6da1c3e2d8aac10c1c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.076, 'ICIR': 0.34, 'Rank IC': 0.03, 'Rank ICIR': 0.135}, 'data_train_vec': ['2025-05-28', '2026-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.135', 'weight': '0.049'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260530_14 534402606224043767 (Recorders: 3/5)

	Recorder: bcd7726687e14555906b9fe6e484bb55

		Model: {'id': 'bcd7726687e14555906b9fe6e484bb55', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.063, 'Rank IC': 0.035, 'Rank ICIR': 0.233}, 'data_train_vec': ['2021-05-28', '2025-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.233', 'weight': '0.084'}

	Recorder: 329f0602ab25445eaadca2eb16a91c15

		Model: {'id': '329f0602ab25445eaadca2eb16a91c15', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.037, 'Rank IC': 0.039, 'Rank ICIR': 0.212}, 'data_train_vec': ['2022-05-30', '2025-05-29'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.212', 'weight': '0.077'}

	Recorder: 2b208be02e724d5fa937da7526ec24ab

		Model: {'id': '2b208be02e724d5fa937da7526ec24ab', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.227, 'Rank IC': 0.039, 'Rank ICIR': 0.259}, 'data_train_vec': ['2023-05-28', '2025-08-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.259', 'weight': '0.093'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260530_14 818746067877930118 (Recorders: 4/5)

	Recorder: 073d1a2eb7534361b91f1457563b875c

		Model: {'id': '073d1a2eb7534361b91f1457563b875c', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.064, 'Rank IC': 0.035, 'Rank ICIR': 0.304}, 'data_train_vec': ['2021-05-28', '2025-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.304', 'weight': '0.110'}

	Recorder: 8fecac4dbad944f48ed36519723d2f4f

		Model: {'id': '8fecac4dbad944f48ed36519723d2f4f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.097, 'Rank IC': 0.031, 'Rank ICIR': 0.281}, 'data_train_vec': ['2023-05-28', '2025-08-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.281', 'weight': '0.101'}

	Recorder: 4afbc367aea64a1082e4a43350d6231c

		Model: {'id': '4afbc367aea64a1082e4a43350d6231c', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.029, 'Rank IC': 0.011, 'Rank ICIR': 0.083}, 'data_train_vec': ['2024-05-30', '2025-11-29'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.083', 'weight': '0.030'}

	Recorder: d9b69287dbf1499eb57198187ae95aef

		Model: {'id': 'd9b69287dbf1499eb57198187ae95aef', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.051, 'ICIR': 0.242, 'Rank IC': 0.029, 'Rank ICIR': 0.124}, 'data_train_vec': ['2025-05-28', '2026-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.124', 'weight': '0.045'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260530_14 141128461464970684 (Recorders: 3/5)

	Recorder: 712a84df463c4accbdfa49e16e1204c7

		Model: {'id': '712a84df463c4accbdfa49e16e1204c7', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.025, 'Rank IC': 0.02, 'Rank ICIR': 0.122}, 'data_train_vec': ['2021-05-28', '2025-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.122', 'weight': '0.044'}

	Recorder: 4fae3f40da444839bbf7ee4fd4d5a8a6

		Model: {'id': '4fae3f40da444839bbf7ee4fd4d5a8a6', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.036, 'Rank IC': 0.026, 'Rank ICIR': 0.168}, 'data_train_vec': ['2023-05-28', '2025-08-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.168', 'weight': '0.061'}

	Recorder: 623e4271aef74ea883e90a65f0bc1128

		Model: {'id': '623e4271aef74ea883e90a65f0bc1128', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.086, 'Rank IC': 0.006, 'Rank ICIR': 0.037}, 'data_train_vec': ['2025-05-28', '2026-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.037', 'weight': '0.013'}

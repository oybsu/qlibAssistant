# params 
 {'predict_dates': [{'start': '2026-06-08', 'end': '2026-06-08'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260608_18 407085286869189131 (Recorders: 4/5)

	Recorder: 298905d04df943df87a1cfeb95a7f3cb

		Model: {'id': '298905d04df943df87a1cfeb95a7f3cb', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.016, 'Rank IC': 0.027, 'Rank ICIR': 0.177}, 'data_train_vec': ['2021-06-08', '2025-03-07'], 'train_time_vec': ['2026-06-08', '2026-06-08'], 'rank_icir': '0.177', 'weight': '0.044'}

	Recorder: c11be021d7ba467186e9b39b18cb089b

		Model: {'id': 'c11be021d7ba467186e9b39b18cb089b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.014, 'Rank IC': 0.027, 'Rank ICIR': 0.177}, 'data_train_vec': ['2022-06-08', '2025-06-07'], 'train_time_vec': ['2026-06-08', '2026-06-08'], 'rank_icir': '0.177', 'weight': '0.044'}

	Recorder: dd19691f494c4d3eb103cd27eab1a889

		Model: {'id': 'dd19691f494c4d3eb103cd27eab1a889', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.274, 'Rank IC': 0.049, 'Rank ICIR': 0.323}, 'data_train_vec': ['2023-06-08', '2025-09-07'], 'train_time_vec': ['2026-06-08', '2026-06-08'], 'rank_icir': '0.323', 'weight': '0.080'}

	Recorder: 2f31435beb4f4fe49a23a93de4c9d666

		Model: {'id': '2f31435beb4f4fe49a23a93de4c9d666', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.039, 'Rank IC': 0.025, 'Rank ICIR': 0.242}, 'data_train_vec': ['2024-06-08', '2025-12-07'], 'train_time_vec': ['2026-06-08', '2026-06-08'], 'rank_icir': '0.242', 'weight': '0.060'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260608_18 849586480677163707 (Recorders: 3/5)

	Recorder: 4e4b0bd38fa64dca833c5aa68b544803

		Model: {'id': '4e4b0bd38fa64dca833c5aa68b544803', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.068, 'Rank IC': 0.025, 'Rank ICIR': 0.174}, 'data_train_vec': ['2021-06-08', '2025-03-07'], 'train_time_vec': ['2026-06-08', '2026-06-08'], 'rank_icir': '0.174', 'weight': '0.043'}

	Recorder: 4c17388bdb8d4a5ca62fa3e0333418f9

		Model: {'id': '4c17388bdb8d4a5ca62fa3e0333418f9', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.148, 'Rank IC': 0.035, 'Rank ICIR': 0.252}, 'data_train_vec': ['2023-06-08', '2025-09-07'], 'train_time_vec': ['2026-06-08', '2026-06-08'], 'rank_icir': '0.252', 'weight': '0.062'}

	Recorder: adfa16b6c64e4bf49017096bb0a99616

		Model: {'id': 'adfa16b6c64e4bf49017096bb0a99616', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.097, 'Rank IC': 0.017, 'Rank ICIR': 0.188}, 'data_train_vec': ['2024-06-08', '2025-12-07'], 'train_time_vec': ['2026-06-08', '2026-06-08'], 'rank_icir': '0.188', 'weight': '0.046'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260608_16 440188412680768242 (Recorders: 3/5)

	Recorder: 4fd2ecd5769d48418c86c980980ebfd6

		Model: {'id': '4fd2ecd5769d48418c86c980980ebfd6', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.162, 'Rank IC': 0.049, 'Rank ICIR': 0.324}, 'data_train_vec': ['2021-06-08', '2025-03-07'], 'train_time_vec': ['2026-06-08', '2026-06-08'], 'rank_icir': '0.324', 'weight': '0.080'}

	Recorder: 939bfc4553af47ad8fa1e379c4927d63

		Model: {'id': '939bfc4553af47ad8fa1e379c4927d63', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.136, 'Rank IC': 0.053, 'Rank ICIR': 0.293}, 'data_train_vec': ['2022-06-08', '2025-06-07'], 'train_time_vec': ['2026-06-08', '2026-06-08'], 'rank_icir': '0.293', 'weight': '0.072'}

	Recorder: 049fc37e62844507b06084c12c2353d8

		Model: {'id': '049fc37e62844507b06084c12c2353d8', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.226, 'Rank IC': 0.054, 'Rank ICIR': 0.352}, 'data_train_vec': ['2023-06-08', '2025-09-07'], 'train_time_vec': ['2026-06-08', '2026-06-08'], 'rank_icir': '0.352', 'weight': '0.087'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260608_16 943145419551606784 (Recorders: 4/5)

	Recorder: ba70206160c34abfa4b09b38ee105be6

		Model: {'id': 'ba70206160c34abfa4b09b38ee105be6', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.122, 'Rank IC': 0.043, 'Rank ICIR': 0.371}, 'data_train_vec': ['2021-06-08', '2025-03-07'], 'train_time_vec': ['2026-06-08', '2026-06-08'], 'rank_icir': '0.371', 'weight': '0.092'}

	Recorder: e87da12a26fb45da963907b43ff70f51

		Model: {'id': 'e87da12a26fb45da963907b43ff70f51', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.015, 'Rank IC': 0.04, 'Rank ICIR': 0.303}, 'data_train_vec': ['2022-06-08', '2025-06-07'], 'train_time_vec': ['2026-06-08', '2026-06-08'], 'rank_icir': '0.303', 'weight': '0.075'}

	Recorder: 024f2873632142a788bed4cdf90d3291

		Model: {'id': '024f2873632142a788bed4cdf90d3291', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.088, 'Rank IC': 0.04, 'Rank ICIR': 0.353}, 'data_train_vec': ['2023-06-08', '2025-09-07'], 'train_time_vec': ['2026-06-08', '2026-06-08'], 'rank_icir': '0.353', 'weight': '0.087'}

	Recorder: 91c068bf759145b089bb584c93cd7f3d

		Model: {'id': '91c068bf759145b089bb584c93cd7f3d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.029, 'Rank IC': 0.012, 'Rank ICIR': 0.082}, 'data_train_vec': ['2024-06-08', '2025-12-07'], 'train_time_vec': ['2026-06-08', '2026-06-08'], 'rank_icir': '0.082', 'weight': '0.020'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260608_16 618641565647375930 (Recorders: 2/5)

	Recorder: 309b4e2c98b34556a12754c20cc253c6

		Model: {'id': '309b4e2c98b34556a12754c20cc253c6', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.074, 'Rank IC': 0.036, 'Rank ICIR': 0.208}, 'data_train_vec': ['2021-06-08', '2025-03-07'], 'train_time_vec': ['2026-06-08', '2026-06-08'], 'rank_icir': '0.208', 'weight': '0.051'}

	Recorder: 605ada0495b34a8cae5ccc08b6b9a958

		Model: {'id': '605ada0495b34a8cae5ccc08b6b9a958', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.044, 'Rank IC': 0.037, 'Rank ICIR': 0.231}, 'data_train_vec': ['2023-06-08', '2025-09-07'], 'train_time_vec': ['2026-06-08', '2026-06-08'], 'rank_icir': '0.231', 'weight': '0.057'}

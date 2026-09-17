# params 
 {'predict_dates': [{'start': '2026-09-17', 'end': '2026-09-17'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260917_19 715042071026795200 (Recorders: 3/5)

	Recorder: ba92be3b0efd4168989970c0edfa8cf0

		Model: {'id': 'ba92be3b0efd4168989970c0edfa8cf0', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.048, 'Rank IC': 0.027, 'Rank ICIR': 0.18}, 'data_train_vec': ['2021-09-17', '2025-06-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.180', 'weight': '0.078'}

	Recorder: 8639bad07b404233b82c2c455f097ae3

		Model: {'id': '8639bad07b404233b82c2c455f097ae3', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.074, 'Rank IC': 0.033, 'Rank ICIR': 0.198}, 'data_train_vec': ['2022-09-17', '2025-09-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.198', 'weight': '0.086'}

	Recorder: cda54e6fdbe2408cbee718a3d14c0bb8

		Model: {'id': 'cda54e6fdbe2408cbee718a3d14c0bb8', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.009, 'Rank IC': 0.005, 'Rank ICIR': 0.024}, 'data_train_vec': ['2023-09-17', '2025-12-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.024', 'weight': '0.010'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260917_19 832732884876258587 (Recorders: 3/5)

	Recorder: 36b42ea505774ecf9e17672e2a078ea9

		Model: {'id': '36b42ea505774ecf9e17672e2a078ea9', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.148, 'Rank IC': 0.036, 'Rank ICIR': 0.241}, 'data_train_vec': ['2021-09-17', '2025-06-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.241', 'weight': '0.104'}

	Recorder: b9d9cf1c242b479fbad1e764e0269f1c

		Model: {'id': 'b9d9cf1c242b479fbad1e764e0269f1c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.144, 'Rank IC': 0.038, 'Rank ICIR': 0.247}, 'data_train_vec': ['2022-09-17', '2025-09-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.247', 'weight': '0.107'}

	Recorder: 1f86ab0b634a476584d31b2ce53911c4

		Model: {'id': '1f86ab0b634a476584d31b2ce53911c4', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.167, 'Rank IC': 0.021, 'Rank ICIR': 0.121}, 'data_train_vec': ['2024-09-17', '2026-03-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.121', 'weight': '0.052'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260917_17 723411276715355343 (Recorders: 4/5)

	Recorder: 922e447837dc497bae81d6288fd1c561

		Model: {'id': '922e447837dc497bae81d6288fd1c561', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.163, 'Rank IC': 0.043, 'Rank ICIR': 0.258}, 'data_train_vec': ['2021-09-17', '2025-06-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.258', 'weight': '0.112'}

	Recorder: 17897ecbc5084eb0b53ed30712666a33

		Model: {'id': '17897ecbc5084eb0b53ed30712666a33', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.14, 'Rank IC': 0.037, 'Rank ICIR': 0.219}, 'data_train_vec': ['2022-09-17', '2025-09-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.219', 'weight': '0.095'}

	Recorder: 41f6080e18884a5fa1d746b3338e31af

		Model: {'id': '41f6080e18884a5fa1d746b3338e31af', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.021, 'Rank IC': 0.008, 'Rank ICIR': 0.04}, 'data_train_vec': ['2023-09-17', '2025-12-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.040', 'weight': '0.017'}

	Recorder: ba9c84e0e2e04893afdb63e4c6a79ecc

		Model: {'id': 'ba9c84e0e2e04893afdb63e4c6a79ecc', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.041, 'ICIR': 0.147, 'Rank IC': 0.022, 'Rank ICIR': 0.099}, 'data_train_vec': ['2024-09-17', '2026-03-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.099', 'weight': '0.043'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260917_17 483028921189336913 (Recorders: 4/5)

	Recorder: 1ca649c7dc10451bb811ffa995024954

		Model: {'id': '1ca649c7dc10451bb811ffa995024954', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.156, 'Rank IC': 0.038, 'Rank ICIR': 0.229}, 'data_train_vec': ['2021-09-17', '2025-06-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.229', 'weight': '0.099'}

	Recorder: d97182698e6c41ba891e93917b80724d

		Model: {'id': 'd97182698e6c41ba891e93917b80724d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.138, 'Rank IC': 0.022, 'Rank ICIR': 0.132}, 'data_train_vec': ['2022-09-17', '2025-09-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.132', 'weight': '0.057'}

	Recorder: aef28263335c4c66a1605147c8b5840f

		Model: {'id': 'aef28263335c4c66a1605147c8b5840f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.029, 'Rank IC': 0.003, 'Rank ICIR': 0.017}, 'data_train_vec': ['2023-09-17', '2025-12-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.017', 'weight': '0.007'}

	Recorder: 32feab1c7cfb496d97178945364296ef

		Model: {'id': '32feab1c7cfb496d97178945364296ef', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.076, 'ICIR': 0.281, 'Rank IC': 0.05, 'Rank ICIR': 0.217}, 'data_train_vec': ['2024-09-17', '2026-03-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.217', 'weight': '0.094'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260917_16 355883893341359692 (Recorders: 1/5)

	Recorder: 7e16c3db09dc4fa6b068e040bb1812e9

		Model: {'id': '7e16c3db09dc4fa6b068e040bb1812e9', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.133, 'Rank IC': 0.017, 'Rank ICIR': 0.087}, 'data_train_vec': ['2024-09-17', '2026-03-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.087', 'weight': '0.038'}

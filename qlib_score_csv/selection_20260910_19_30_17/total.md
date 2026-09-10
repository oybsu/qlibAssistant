# params 
 {'predict_dates': [{'start': '2026-09-10', 'end': '2026-09-10'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260910_19 678038590652491610 (Recorders: 2/5)

	Recorder: 4d0ea75736f14e7faaceebc9e076a6d5

		Model: {'id': '4d0ea75736f14e7faaceebc9e076a6d5', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.17, 'Rank IC': 0.044, 'Rank ICIR': 0.282}, 'data_train_vec': ['2022-09-10', '2025-09-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.282', 'weight': '0.128'}

	Recorder: b79648f5bccc455685bb0d44c29d78c9

		Model: {'id': 'b79648f5bccc455685bb0d44c29d78c9', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.04, 'Rank IC': 0.015, 'Rank ICIR': 0.083}, 'data_train_vec': ['2023-09-10', '2025-12-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.083', 'weight': '0.038'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260910_18 708884536226664586 (Recorders: 3/5)

	Recorder: bee5ed901cfb4633b243743c2a7e46bb

		Model: {'id': 'bee5ed901cfb4633b243743c2a7e46bb', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.134, 'Rank IC': 0.027, 'Rank ICIR': 0.185}, 'data_train_vec': ['2021-09-10', '2025-06-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.185', 'weight': '0.084'}

	Recorder: 767515513d7845d7907e13f40d373a2b

		Model: {'id': '767515513d7845d7907e13f40d373a2b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.144, 'Rank IC': 0.032, 'Rank ICIR': 0.245}, 'data_train_vec': ['2022-09-10', '2025-09-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.245', 'weight': '0.112'}

	Recorder: 56131f2e942943fda4c31725e4e95745

		Model: {'id': '56131f2e942943fda4c31725e4e95745', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.048, 'Rank IC': 0.008, 'Rank ICIR': 0.051}, 'data_train_vec': ['2023-09-10', '2025-12-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.051', 'weight': '0.023'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260910_16 624165949728164111 (Recorders: 3/5)

	Recorder: 0f0ef7f99c794285b0fce47c2b896f9c

		Model: {'id': '0f0ef7f99c794285b0fce47c2b896f9c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.126, 'Rank IC': 0.038, 'Rank ICIR': 0.218}, 'data_train_vec': ['2021-09-10', '2025-06-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.218', 'weight': '0.099'}

	Recorder: 7efd4623fa80408784a294fa1ce2df46

		Model: {'id': '7efd4623fa80408784a294fa1ce2df46', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.149, 'Rank IC': 0.041, 'Rank ICIR': 0.246}, 'data_train_vec': ['2022-09-10', '2025-09-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.246', 'weight': '0.112'}

	Recorder: 395f51a861844a52b2e50599f201a142

		Model: {'id': '395f51a861844a52b2e50599f201a142', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.042, 'Rank IC': 0.014, 'Rank ICIR': 0.073}, 'data_train_vec': ['2023-09-10', '2025-12-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.073', 'weight': '0.033'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260910_16 262927147542474096 (Recorders: 5/5)

	Recorder: de526dca88474e81a2b467d55497a208

		Model: {'id': 'de526dca88474e81a2b467d55497a208', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.12, 'Rank IC': 0.033, 'Rank ICIR': 0.196}, 'data_train_vec': ['2021-09-10', '2025-06-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.196', 'weight': '0.089'}

	Recorder: 0feff6b72cfe4827a9936445fcbfe949

		Model: {'id': '0feff6b72cfe4827a9936445fcbfe949', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.037, 'ICIR': 0.192, 'Rank IC': 0.033, 'Rank ICIR': 0.206}, 'data_train_vec': ['2022-09-10', '2025-09-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.206', 'weight': '0.094'}

	Recorder: 4292755cd7234bcb80e03e6e1dde63e9

		Model: {'id': '4292755cd7234bcb80e03e6e1dde63e9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.043, 'Rank IC': 0.004, 'Rank ICIR': 0.018}, 'data_train_vec': ['2023-09-10', '2025-12-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.018', 'weight': '0.008'}

	Recorder: 0e34ad7727e446e0aa9be267ae6c788a

		Model: {'id': '0e34ad7727e446e0aa9be267ae6c788a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.078, 'Rank IC': 0.014, 'Rank ICIR': 0.051}, 'data_train_vec': ['2024-09-10', '2026-03-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.051', 'weight': '0.023'}

	Recorder: ca8fc12c8ed945d789e7de1a92fc7a72

		Model: {'id': 'ca8fc12c8ed945d789e7de1a92fc7a72', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.042, 'ICIR': 0.195, 'Rank IC': 0.027, 'Rank ICIR': 0.132}, 'data_train_vec': ['2025-09-10', '2026-06-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.132', 'weight': '0.060'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260910_16 737549398697178492 (Recorders: 1/5)

	Recorder: b9d5fb1fa02d4ae1880802e658d6cb98

		Model: {'id': 'b9d5fb1fa02d4ae1880802e658d6cb98', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.073, 'Rank IC': 0.033, 'Rank ICIR': 0.21}, 'data_train_vec': ['2022-09-10', '2025-09-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.210', 'weight': '0.096'}

# params 
 {'predict_dates': [{'start': '2026-08-28', 'end': '2026-08-28'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260829_00 488022521050564698 (Recorders: 2/5)

	Recorder: 5c5ce7d6c8074095a52a27334d6cf660

		Model: {'id': '5c5ce7d6c8074095a52a27334d6cf660', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.129, 'Rank IC': 0.035, 'Rank ICIR': 0.227}, 'data_train_vec': ['2022-08-29', '2025-08-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.227', 'weight': '0.117'}

	Recorder: a12f8d92355e4369bd910bab5c6e2e9e

		Model: {'id': 'a12f8d92355e4369bd910bab5c6e2e9e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.072, 'Rank IC': 0.009, 'Rank ICIR': 0.061}, 'data_train_vec': ['2023-08-29', '2025-11-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.061', 'weight': '0.031'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260829_00 540608269324800966 (Recorders: 3/5)

	Recorder: a1b9a16341dc4e98982c615c11a223aa

		Model: {'id': 'a1b9a16341dc4e98982c615c11a223aa', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.073, 'Rank IC': 0.02, 'Rank ICIR': 0.154}, 'data_train_vec': ['2021-08-29', '2025-05-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.154', 'weight': '0.079'}

	Recorder: 0341909b4d464f6bb034cb4abfd01ecc

		Model: {'id': '0341909b4d464f6bb034cb4abfd01ecc', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.088, 'Rank IC': 0.007, 'Rank ICIR': 0.065}, 'data_train_vec': ['2023-08-29', '2025-11-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.065', 'weight': '0.033'}

	Recorder: 17bf04bf6eb14e31ac56c281d9864ab1

		Model: {'id': '17bf04bf6eb14e31ac56c281d9864ab1', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.01, 'Rank IC': 0.027, 'Rank ICIR': 0.159}, 'data_train_vec': ['2025-08-29', '2026-05-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.159', 'weight': '0.082'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260828_22 207631740665652183 (Recorders: 4/5)

	Recorder: eae7c2ca9af4448f8efb7bbbcfe1d00a

		Model: {'id': 'eae7c2ca9af4448f8efb7bbbcfe1d00a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.054, 'Rank IC': 0.021, 'Rank ICIR': 0.127}, 'data_train_vec': ['2021-08-28', '2025-05-27'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.127', 'weight': '0.065'}

	Recorder: 7fad87587d894c659a6e88a178e64bb0

		Model: {'id': '7fad87587d894c659a6e88a178e64bb0', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.114, 'Rank IC': 0.03, 'Rank ICIR': 0.179}, 'data_train_vec': ['2022-08-28', '2025-08-27'], 'train_time_vec': ['2026-08-28', '2026-08-29'], 'rank_icir': '0.179', 'weight': '0.092'}

	Recorder: e63f2462d8814cbc81e2a52f726999a4

		Model: {'id': 'e63f2462d8814cbc81e2a52f726999a4', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.009, 'Rank IC': 0.008, 'Rank ICIR': 0.043}, 'data_train_vec': ['2023-08-28', '2025-11-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.043', 'weight': '0.022'}

	Recorder: 60813c09700c4622a49350e6d57bd4fa

		Model: {'id': '60813c09700c4622a49350e6d57bd4fa', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.025, 'Rank IC': 0.005, 'Rank ICIR': 0.019}, 'data_train_vec': ['2025-08-28', '2026-05-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.019', 'weight': '0.010'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260828_22 843272995831738804 (Recorders: 4/5)

	Recorder: e6b8c58cf10b49b3943d40ad1da69b2e

		Model: {'id': 'e6b8c58cf10b49b3943d40ad1da69b2e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.055, 'Rank IC': 0.021, 'Rank ICIR': 0.129}, 'data_train_vec': ['2021-08-28', '2025-05-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.129', 'weight': '0.066'}

	Recorder: 9eebce5776084f1fa1b8c91b73fb09c5

		Model: {'id': '9eebce5776084f1fa1b8c91b73fb09c5', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.153, 'Rank IC': 0.028, 'Rank ICIR': 0.182}, 'data_train_vec': ['2022-08-28', '2025-08-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.182', 'weight': '0.093'}

	Recorder: b2f5c4bfe3dc4c468d3756be4466611a

		Model: {'id': 'b2f5c4bfe3dc4c468d3756be4466611a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.1, 'Rank IC': 0.018, 'Rank ICIR': 0.069}, 'data_train_vec': ['2024-08-28', '2026-02-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.069', 'weight': '0.035'}

	Recorder: 8892e057c0a3444098fc042feadd0c08

		Model: {'id': '8892e057c0a3444098fc042feadd0c08', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.067, 'ICIR': 0.297, 'Rank IC': 0.036, 'Rank ICIR': 0.198}, 'data_train_vec': ['2025-08-28', '2026-05-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.198', 'weight': '0.102'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260828_22 593096006323165988 (Recorders: 3/5)

	Recorder: 9fb9e60161c2486fb072b50318fa5b56

		Model: {'id': '9fb9e60161c2486fb072b50318fa5b56', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.008, 'Rank IC': 0.016, 'Rank ICIR': 0.095}, 'data_train_vec': ['2021-08-28', '2025-05-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.095', 'weight': '0.049'}

	Recorder: c4270532af4347598cc1c2b81c0c00d4

		Model: {'id': 'c4270532af4347598cc1c2b81c0c00d4', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.02, 'Rank IC': 0.026, 'Rank ICIR': 0.168}, 'data_train_vec': ['2022-08-28', '2025-08-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.168', 'weight': '0.086'}

	Recorder: 1f161a69c50f48898e918ddff9e3d750

		Model: {'id': '1f161a69c50f48898e918ddff9e3d750', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.128, 'Rank IC': 0.016, 'Rank ICIR': 0.073}, 'data_train_vec': ['2025-08-28', '2026-05-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.073', 'weight': '0.037'}

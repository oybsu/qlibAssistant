# params 
 {'predict_dates': [{'start': '2026-07-02', 'end': '2026-07-02'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260702_17 558262724931053873 (Recorders: 3/5)

	Recorder: b1b63c01d230486cba58d01b34e9f7c4

		Model: {'id': 'b1b63c01d230486cba58d01b34e9f7c4', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.138, 'Rank IC': 0.019, 'Rank ICIR': 0.126}, 'data_train_vec': ['2022-07-02', '2025-07-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.126', 'weight': '0.059'}

	Recorder: f2635c90886a49e9a183541316fed2c4

		Model: {'id': 'f2635c90886a49e9a183541316fed2c4', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.233, 'Rank IC': 0.025, 'Rank ICIR': 0.196}, 'data_train_vec': ['2023-07-02', '2025-10-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.196', 'weight': '0.092'}

	Recorder: 00a229a03dbe423bab97a7dd7c4b41ba

		Model: {'id': '00a229a03dbe423bab97a7dd7c4b41ba', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.204, 'Rank IC': 0.014, 'Rank ICIR': 0.17}, 'data_train_vec': ['2024-07-02', '2026-01-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.170', 'weight': '0.080'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260702_17 692928739207699408 (Recorders: 3/5)

	Recorder: df6fe617df9f4bb0861febc7d44c2293

		Model: {'id': 'df6fe617df9f4bb0861febc7d44c2293', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.198, 'Rank IC': 0.025, 'Rank ICIR': 0.195}, 'data_train_vec': ['2023-07-02', '2025-10-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.195', 'weight': '0.092'}

	Recorder: 44fc5c5b122a4743898dd4fc76ca728d

		Model: {'id': '44fc5c5b122a4743898dd4fc76ca728d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.178, 'Rank IC': 0.022, 'Rank ICIR': 0.175}, 'data_train_vec': ['2024-07-02', '2026-01-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.175', 'weight': '0.082'}

	Recorder: 48b52011bc3148479a6270ba1fe44757

		Model: {'id': '48b52011bc3148479a6270ba1fe44757', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.041, 'ICIR': 0.152, 'Rank IC': 0.022, 'Rank ICIR': 0.092}, 'data_train_vec': ['2025-07-02', '2026-04-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.092', 'weight': '0.043'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260702_14 849583463997975127 (Recorders: 3/5)

	Recorder: 5aabe3893b9f4414a5823cc210528995

		Model: {'id': '5aabe3893b9f4414a5823cc210528995', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.052, 'Rank IC': 0.041, 'Rank ICIR': 0.247}, 'data_train_vec': ['2021-07-02', '2025-04-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.247', 'weight': '0.116'}

	Recorder: 77d0ae566d034d91aa9a622520859e53

		Model: {'id': '77d0ae566d034d91aa9a622520859e53', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.097, 'Rank IC': 0.041, 'Rank ICIR': 0.255}, 'data_train_vec': ['2022-07-02', '2025-07-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.255', 'weight': '0.120'}

	Recorder: dbbd389a82034ef89e3b0b589eda7bc8

		Model: {'id': 'dbbd389a82034ef89e3b0b589eda7bc8', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.107, 'Rank IC': 0.025, 'Rank ICIR': 0.194}, 'data_train_vec': ['2023-07-02', '2025-10-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.194', 'weight': '0.091'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260702_14 505951613308684915 (Recorders: 1/5)

	Recorder: 7925fc45dcba4bb6bf822bd9fd547ed4

		Model: {'id': '7925fc45dcba4bb6bf822bd9fd547ed4', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.053, 'Rank IC': 0.022, 'Rank ICIR': 0.162}, 'data_train_vec': ['2023-07-02', '2025-10-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.162', 'weight': '0.076'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260702_14 736284798949687681 (Recorders: 2/5)

	Recorder: 3414cfe110df40039d71b0bfed8fd6b1

		Model: {'id': '3414cfe110df40039d71b0bfed8fd6b1', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.032, 'Rank IC': 0.035, 'Rank ICIR': 0.216}, 'data_train_vec': ['2022-07-02', '2025-07-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.216', 'weight': '0.101'}

	Recorder: db994397eccc4a458679ff4c41ee5afb

		Model: {'id': 'db994397eccc4a458679ff4c41ee5afb', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.068, 'Rank IC': 0.014, 'Rank ICIR': 0.101}, 'data_train_vec': ['2023-07-02', '2025-10-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.101', 'weight': '0.047'}

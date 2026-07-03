# params 
 {'predict_dates': [{'start': '2026-07-03', 'end': '2026-07-03'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260703_17 876895233170248657 (Recorders: 3/5)

	Recorder: e9f0b9287ddf4acd8e9231c0369fb67d

		Model: {'id': 'e9f0b9287ddf4acd8e9231c0369fb67d', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.146, 'Rank IC': 0.024, 'Rank ICIR': 0.152}, 'data_train_vec': ['2022-07-03', '2025-07-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.152', 'weight': '0.058'}

	Recorder: a98e1cfa6bad4e38b294a33fdf2000ad

		Model: {'id': 'a98e1cfa6bad4e38b294a33fdf2000ad', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.237, 'Rank IC': 0.025, 'Rank ICIR': 0.2}, 'data_train_vec': ['2023-07-03', '2025-10-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.200', 'weight': '0.076'}

	Recorder: b3e9905d38614b24ba6c6c966555a995

		Model: {'id': 'b3e9905d38614b24ba6c6c966555a995', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.294, 'Rank IC': 0.037, 'Rank ICIR': 0.368}, 'data_train_vec': ['2024-07-03', '2026-01-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.368', 'weight': '0.140'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260703_16 828898430494762029 (Recorders: 3/5)

	Recorder: 9348fe8924dc477189f1bd80a02c4b0b

		Model: {'id': '9348fe8924dc477189f1bd80a02c4b0b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.207, 'Rank IC': 0.027, 'Rank ICIR': 0.214}, 'data_train_vec': ['2023-07-03', '2025-10-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.214', 'weight': '0.082'}

	Recorder: ddc5233a8672412f8a213cad12364670

		Model: {'id': 'ddc5233a8672412f8a213cad12364670', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.168, 'Rank IC': 0.02, 'Rank ICIR': 0.154}, 'data_train_vec': ['2024-07-03', '2026-01-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.154', 'weight': '0.059'}

	Recorder: 6fc22195ec89419e80997e110d3e4c53

		Model: {'id': '6fc22195ec89419e80997e110d3e4c53', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.067, 'Rank IC': 0.015, 'Rank ICIR': 0.066}, 'data_train_vec': ['2025-07-03', '2026-04-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.066', 'weight': '0.025'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260703_14 412577630332371081 (Recorders: 3/5)

	Recorder: fc7c4e2c36394eaa93501f3f26bb1e85

		Model: {'id': 'fc7c4e2c36394eaa93501f3f26bb1e85', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.076, 'Rank IC': 0.045, 'Rank ICIR': 0.262}, 'data_train_vec': ['2021-07-03', '2025-04-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.262', 'weight': '0.100'}

	Recorder: e004b17e54314e05be931405cf0754bd

		Model: {'id': 'e004b17e54314e05be931405cf0754bd', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.119, 'Rank IC': 0.044, 'Rank ICIR': 0.272}, 'data_train_vec': ['2022-07-03', '2025-07-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.272', 'weight': '0.104'}

	Recorder: 95ee120fff1c4d81b7fb702f71e51886

		Model: {'id': '95ee120fff1c4d81b7fb702f71e51886', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.158, 'Rank IC': 0.032, 'Rank ICIR': 0.247}, 'data_train_vec': ['2023-07-03', '2025-10-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.247', 'weight': '0.094'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260703_14 533071144650314584 (Recorders: 1/5)

	Recorder: 103675bb42d04b998cad333333846a6b

		Model: {'id': '103675bb42d04b998cad333333846a6b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.063, 'Rank IC': 0.021, 'Rank ICIR': 0.154}, 'data_train_vec': ['2023-07-03', '2025-10-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.154', 'weight': '0.059'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260703_14 237388665315603948 (Recorders: 3/5)

	Recorder: f6b7dfdf7dee4c21bb6a7fd79dc68351

		Model: {'id': 'f6b7dfdf7dee4c21bb6a7fd79dc68351', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.029, 'Rank IC': 0.038, 'Rank ICIR': 0.212}, 'data_train_vec': ['2021-07-03', '2025-04-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.212', 'weight': '0.081'}

	Recorder: ec6c4f9729f14bf9b03d0a49a4c8cfe3

		Model: {'id': 'ec6c4f9729f14bf9b03d0a49a4c8cfe3', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.034, 'Rank IC': 0.033, 'Rank ICIR': 0.206}, 'data_train_vec': ['2022-07-03', '2025-07-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.206', 'weight': '0.079'}

	Recorder: 5a8f914310b544649fbd915b6aa7e021

		Model: {'id': '5a8f914310b544649fbd915b6aa7e021', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.08, 'Rank IC': 0.016, 'Rank ICIR': 0.113}, 'data_train_vec': ['2023-07-03', '2025-10-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.113', 'weight': '0.043'}

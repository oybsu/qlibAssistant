# params 
 {'predict_dates': [{'start': '2026-09-14', 'end': '2026-09-14'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260914_20 275977399945680476 (Recorders: 3/5)

	Recorder: 80f974577f5744dea0d5ee9082d559a0

		Model: {'id': '80f974577f5744dea0d5ee9082d559a0', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.018, 'Rank IC': 0.018, 'Rank ICIR': 0.11}, 'data_train_vec': ['2021-09-14', '2025-06-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.110', 'weight': '0.041'}

	Recorder: 757e25c8b9e145039449c4bf554225f8

		Model: {'id': '757e25c8b9e145039449c4bf554225f8', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.075, 'Rank IC': 0.034, 'Rank ICIR': 0.236}, 'data_train_vec': ['2022-09-14', '2025-09-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.236', 'weight': '0.088'}

	Recorder: a55143aa2a01446a981a831098c047bb

		Model: {'id': 'a55143aa2a01446a981a831098c047bb', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.035, 'Rank IC': 0.008, 'Rank ICIR': 0.045}, 'data_train_vec': ['2023-09-14', '2025-12-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.045', 'weight': '0.017'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260914_20 875348767459289026 (Recorders: 3/5)

	Recorder: c182249c8f4c4b60a3a26289a14329a6

		Model: {'id': 'c182249c8f4c4b60a3a26289a14329a6', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.161, 'Rank IC': 0.031, 'Rank ICIR': 0.245}, 'data_train_vec': ['2021-09-14', '2025-06-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.245', 'weight': '0.091'}

	Recorder: 52b73149fafa41439e91e3ff3bd243c7

		Model: {'id': '52b73149fafa41439e91e3ff3bd243c7', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.188, 'Rank IC': 0.049, 'Rank ICIR': 0.329}, 'data_train_vec': ['2022-09-14', '2025-09-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.329', 'weight': '0.122'}

	Recorder: decc4c9fd36c405aa199a3be69d0f637

		Model: {'id': 'decc4c9fd36c405aa199a3be69d0f637', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.07, 'Rank IC': 0.011, 'Rank ICIR': 0.072}, 'data_train_vec': ['2023-09-14', '2025-12-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.072', 'weight': '0.027'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260914_18 143905277433621571 (Recorders: 3/5)

	Recorder: 70e76f88c60144f28b859d9a9ec807d4

		Model: {'id': '70e76f88c60144f28b859d9a9ec807d4', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.142, 'Rank IC': 0.043, 'Rank ICIR': 0.251}, 'data_train_vec': ['2021-09-14', '2025-06-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.251', 'weight': '0.093'}

	Recorder: fa423e1e54b144d99641f628a9334917

		Model: {'id': 'fa423e1e54b144d99641f628a9334917', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.152, 'Rank IC': 0.042, 'Rank ICIR': 0.245}, 'data_train_vec': ['2022-09-14', '2025-09-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.245', 'weight': '0.091'}

	Recorder: 99fad8d1d8a1455299ca3ead4a83b73a

		Model: {'id': '99fad8d1d8a1455299ca3ead4a83b73a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.032, 'Rank IC': 0.014, 'Rank ICIR': 0.072}, 'data_train_vec': ['2023-09-14', '2025-12-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.072', 'weight': '0.027'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260914_18 157214999745756855 (Recorders: 5/5)

	Recorder: 2558725d7ff846beb99e3f47fac24bc4

		Model: {'id': '2558725d7ff846beb99e3f47fac24bc4', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.137, 'Rank IC': 0.037, 'Rank ICIR': 0.219}, 'data_train_vec': ['2021-09-14', '2025-06-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.219', 'weight': '0.081'}

	Recorder: 9670b08be3cb495194bcf27a63c3227a

		Model: {'id': '9670b08be3cb495194bcf27a63c3227a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.188, 'Rank IC': 0.032, 'Rank ICIR': 0.192}, 'data_train_vec': ['2022-09-14', '2025-09-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.192', 'weight': '0.071'}

	Recorder: c90691bb4f1a47788ea2d9f189f7c62c

		Model: {'id': 'c90691bb4f1a47788ea2d9f189f7c62c', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.037, 'Rank IC': 0.005, 'Rank ICIR': 0.025}, 'data_train_vec': ['2023-09-14', '2025-12-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.025', 'weight': '0.009'}

	Recorder: b4a66f5f13ce411180b73dd8d1c69536

		Model: {'id': 'b4a66f5f13ce411180b73dd8d1c69536', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.102, 'Rank IC': 0.018, 'Rank ICIR': 0.072}, 'data_train_vec': ['2024-09-14', '2026-03-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.072', 'weight': '0.027'}

	Recorder: 8939c28814114488978bb48854f0a865

		Model: {'id': '8939c28814114488978bb48854f0a865', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.095, 'Rank IC': 0.014, 'Rank ICIR': 0.072}, 'data_train_vec': ['2025-09-14', '2026-06-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.072', 'weight': '0.027'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260914_18 807792458758212251 (Recorders: 2/5)

	Recorder: a566d5143cd0404eb29f62f5b49677d2

		Model: {'id': 'a566d5143cd0404eb29f62f5b49677d2', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.022, 'Rank IC': 0.032, 'Rank ICIR': 0.19}, 'data_train_vec': ['2021-09-14', '2025-06-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.190', 'weight': '0.071'}

	Recorder: 60ef8e6a8bc141ddba86e139f4888f26

		Model: {'id': '60ef8e6a8bc141ddba86e139f4888f26', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.075, 'Rank IC': 0.05, 'Rank ICIR': 0.319}, 'data_train_vec': ['2022-09-14', '2025-09-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.319', 'weight': '0.118'}

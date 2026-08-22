# params 
 {'predict_dates': [{'start': '2026-08-21', 'end': '2026-08-21'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260822_15 339372283135562018 (Recorders: 1/5)

	Recorder: 354365d4c2e442fca0e2e817034513d7

		Model: {'id': '354365d4c2e442fca0e2e817034513d7', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.083, 'Rank IC': 0.023, 'Rank ICIR': 0.15}, 'data_train_vec': ['2023-08-22', '2025-11-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.150', 'weight': '0.083'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260822_15 637335629340302641 (Recorders: 3/5)

	Recorder: 146e396ff7cf42f6bedbe726299c01e0

		Model: {'id': '146e396ff7cf42f6bedbe726299c01e0', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.015, 'Rank IC': 0.014, 'Rank ICIR': 0.109}, 'data_train_vec': ['2021-08-22', '2025-05-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.109', 'weight': '0.060'}

	Recorder: 7c7b23d0cd304368b8cbbb4b1937a1e9

		Model: {'id': '7c7b23d0cd304368b8cbbb4b1937a1e9', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.019, 'Rank IC': 0.011, 'Rank ICIR': 0.081}, 'data_train_vec': ['2022-08-22', '2025-08-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.081', 'weight': '0.045'}

	Recorder: ecafc8d1af33420da4dc3432fd962293

		Model: {'id': 'ecafc8d1af33420da4dc3432fd962293', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.049, 'Rank IC': 0.016, 'Rank ICIR': 0.119}, 'data_train_vec': ['2023-08-22', '2025-11-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.119', 'weight': '0.066'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260822_13 968139969417344326 (Recorders: 4/5)

	Recorder: cda4bcf9a3ae4cae90eefb29f6173b16

		Model: {'id': 'cda4bcf9a3ae4cae90eefb29f6173b16', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.072, 'Rank IC': 0.027, 'Rank ICIR': 0.158}, 'data_train_vec': ['2021-08-22', '2025-05-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.158', 'weight': '0.087'}

	Recorder: 28c56ac4f00344a7b3e64784fbe867ea

		Model: {'id': '28c56ac4f00344a7b3e64784fbe867ea', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.112, 'Rank IC': 0.034, 'Rank ICIR': 0.2}, 'data_train_vec': ['2022-08-22', '2025-08-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.200', 'weight': '0.110'}

	Recorder: 89b62ab8b3824b8089dec68085d60951

		Model: {'id': '89b62ab8b3824b8089dec68085d60951', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.03, 'Rank IC': 0.012, 'Rank ICIR': 0.065}, 'data_train_vec': ['2023-08-22', '2025-11-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.065', 'weight': '0.036'}

	Recorder: 35336cbc828542f987846c8494a9ea7d

		Model: {'id': '35336cbc828542f987846c8494a9ea7d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.017, 'Rank IC': 0.006, 'Rank ICIR': 0.025}, 'data_train_vec': ['2025-08-22', '2026-05-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.025', 'weight': '0.014'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260822_13 302306708892611757 (Recorders: 4/5)

	Recorder: df869bc6207343e8bf0776bad24fc346

		Model: {'id': 'df869bc6207343e8bf0776bad24fc346', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.06, 'Rank IC': 0.025, 'Rank ICIR': 0.154}, 'data_train_vec': ['2021-08-22', '2025-05-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.154', 'weight': '0.085'}

	Recorder: e6c202613ad0430090b9aad28897ada9

		Model: {'id': 'e6c202613ad0430090b9aad28897ada9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.16, 'Rank IC': 0.035, 'Rank ICIR': 0.221}, 'data_train_vec': ['2022-08-22', '2025-08-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.221', 'weight': '0.122'}

	Recorder: 24cc8131664b42c59cfc15c0ce54383d

		Model: {'id': '24cc8131664b42c59cfc15c0ce54383d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.063, 'Rank IC': 0.012, 'Rank ICIR': 0.043}, 'data_train_vec': ['2024-08-22', '2026-02-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.043', 'weight': '0.024'}

	Recorder: b21654451c434d9cb34b9ba99c6ba436

		Model: {'id': 'b21654451c434d9cb34b9ba99c6ba436', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.043, 'ICIR': 0.169, 'Rank IC': 0.017, 'Rank ICIR': 0.092}, 'data_train_vec': ['2025-08-22', '2026-05-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.092', 'weight': '0.051'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260822_12 830900668354899755 (Recorders: 3/5)

	Recorder: 32d7df6d1f254792aa79349ce0a3903a

		Model: {'id': '32d7df6d1f254792aa79349ce0a3903a', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.02, 'Rank IC': 0.019, 'Rank ICIR': 0.11}, 'data_train_vec': ['2021-08-22', '2025-05-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.110', 'weight': '0.061'}

	Recorder: 6201fac47f7f4f7cb48537771455c656

		Model: {'id': '6201fac47f7f4f7cb48537771455c656', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.03, 'Rank IC': 0.027, 'Rank ICIR': 0.163}, 'data_train_vec': ['2022-08-22', '2025-08-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.163', 'weight': '0.090'}

	Recorder: 196850ac245443998cce146ea54bf4bb

		Model: {'id': '196850ac245443998cce146ea54bf4bb', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.108, 'Rank IC': 0.03, 'Rank ICIR': 0.124}, 'data_train_vec': ['2025-08-22', '2026-05-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.124', 'weight': '0.068'}

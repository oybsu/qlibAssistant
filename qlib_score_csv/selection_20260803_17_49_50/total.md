# params 
 {'predict_dates': [{'start': '2026-08-03', 'end': '2026-08-03'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260803_17 455432873051867082 (Recorders: 1/5)

	Recorder: facf590cdc1c49f19bc735b2898efca7

		Model: {'id': 'facf590cdc1c49f19bc735b2898efca7', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.076, 'Rank IC': 0.02, 'Rank ICIR': 0.154}, 'data_train_vec': ['2023-08-03', '2025-11-02'], 'train_time_vec': ['2026-08-03', '2026-08-03'], 'rank_icir': '0.154', 'weight': '0.507'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260803_15 645699022167807126 (Recorders: 1/5)

	Recorder: 5000e8cc2a094f14adeb6094093ef883

		Model: {'id': '5000e8cc2a094f14adeb6094093ef883', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.024, 'Rank IC': 0.026, 'Rank ICIR': 0.15}, 'data_train_vec': ['2021-08-03', '2025-05-02'], 'train_time_vec': ['2026-08-03', '2026-08-03'], 'rank_icir': '0.150', 'weight': '0.493'}

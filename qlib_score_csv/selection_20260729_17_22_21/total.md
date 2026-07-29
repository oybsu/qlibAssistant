# params 
 {'predict_dates': [{'start': '2026-07-29', 'end': '2026-07-29'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260729_17 378148554830755231 (Recorders: 1/5)

	Recorder: b47767c2709847e89ebd137095ebd983

		Model: {'id': 'b47767c2709847e89ebd137095ebd983', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.049, 'Rank IC': 0.013, 'Rank ICIR': 0.088}, 'data_train_vec': ['2023-07-29', '2025-10-28'], 'train_time_vec': ['2026-07-29', '2026-07-29'], 'rank_icir': '0.088', 'weight': '0.146'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260729_17 697876573844493682 (Recorders: 2/5)

	Recorder: 23d099b21c764f36beeed66c5866f4a2

		Model: {'id': '23d099b21c764f36beeed66c5866f4a2', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.075, 'Rank IC': 0.03, 'Rank ICIR': 0.193}, 'data_train_vec': ['2021-07-28', '2025-04-27'], 'train_time_vec': ['2026-07-29', '2026-07-29'], 'rank_icir': '0.193', 'weight': '0.321'}

	Recorder: 554e902521a2421cb94f3654313a19c3

		Model: {'id': '554e902521a2421cb94f3654313a19c3', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.101, 'Rank IC': 0.022, 'Rank ICIR': 0.149}, 'data_train_vec': ['2023-07-29', '2025-10-28'], 'train_time_vec': ['2026-07-29', '2026-07-29'], 'rank_icir': '0.149', 'weight': '0.248'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260729_14 648550358852421390 (Recorders: 1/5)

	Recorder: 019940fc8b264b1ab72230c192dfd9d4

		Model: {'id': '019940fc8b264b1ab72230c192dfd9d4', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.054, 'Rank IC': 0.029, 'Rank ICIR': 0.171}, 'data_train_vec': ['2021-07-28', '2025-04-27'], 'train_time_vec': ['2026-07-29', '2026-07-29'], 'rank_icir': '0.171', 'weight': '0.285'}

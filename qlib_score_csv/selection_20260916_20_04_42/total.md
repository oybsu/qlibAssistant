# params 
 {'predict_dates': [{'start': '2026-09-16', 'end': '2026-09-16'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260916_19 819546746020452762 (Recorders: 3/5)

	Recorder: eb7fdeca14d24eebbd34c156470f837a

		Model: {'id': 'eb7fdeca14d24eebbd34c156470f837a', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.076, 'Rank IC': 0.018, 'Rank ICIR': 0.111}, 'data_train_vec': ['2021-09-16', '2025-06-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.111', 'weight': '0.045'}

	Recorder: 784a84f2d09c42fcbbf90156f747a860

		Model: {'id': '784a84f2d09c42fcbbf90156f747a860', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.112, 'Rank IC': 0.026, 'Rank ICIR': 0.154}, 'data_train_vec': ['2022-09-16', '2025-09-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.154', 'weight': '0.062'}

	Recorder: 1369c6578cd14a2f9ba8d4da911e1b7f

		Model: {'id': '1369c6578cd14a2f9ba8d4da911e1b7f', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.013, 'Rank IC': 0.007, 'Rank ICIR': 0.045}, 'data_train_vec': ['2023-09-16', '2025-12-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.045', 'weight': '0.018'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260916_19 450159507266705910 (Recorders: 4/5)

	Recorder: 2298bade4fd14d6e8fe8cb6599fb18b9

		Model: {'id': '2298bade4fd14d6e8fe8cb6599fb18b9', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.114, 'Rank IC': 0.027, 'Rank ICIR': 0.181}, 'data_train_vec': ['2021-09-16', '2025-06-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.181', 'weight': '0.073'}

	Recorder: f0b1863b79af4d6f8c9df712404103a3

		Model: {'id': 'f0b1863b79af4d6f8c9df712404103a3', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.155, 'Rank IC': 0.037, 'Rank ICIR': 0.247}, 'data_train_vec': ['2022-09-16', '2025-09-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.247', 'weight': '0.100'}

	Recorder: 5309279823de4e52bb3c5597e7f39d06

		Model: {'id': '5309279823de4e52bb3c5597e7f39d06', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.02, 'Rank IC': 0.002, 'Rank ICIR': 0.014}, 'data_train_vec': ['2023-09-16', '2025-12-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.014', 'weight': '0.006'}

	Recorder: e74ddb015588446998f9a5fe70c8df58

		Model: {'id': 'e74ddb015588446998f9a5fe70c8df58', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.116, 'Rank IC': 0.014, 'Rank ICIR': 0.067}, 'data_train_vec': ['2024-09-16', '2026-03-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.067', 'weight': '0.027'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260916_17 326889011924953908 (Recorders: 4/5)

	Recorder: a5b06726b1e44398a4f7a0d14f215445

		Model: {'id': 'a5b06726b1e44398a4f7a0d14f215445', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.166, 'Rank IC': 0.042, 'Rank ICIR': 0.258}, 'data_train_vec': ['2021-09-16', '2025-06-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.258', 'weight': '0.104'}

	Recorder: 67e0087af9f040fe962cdfe8a9dc5f66

		Model: {'id': '67e0087af9f040fe962cdfe8a9dc5f66', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.13, 'Rank IC': 0.038, 'Rank ICIR': 0.22}, 'data_train_vec': ['2022-09-16', '2025-09-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.220', 'weight': '0.089'}

	Recorder: 63b6d15df57f441798162a57f00ae57a

		Model: {'id': '63b6d15df57f441798162a57f00ae57a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.04, 'Rank IC': 0.012, 'Rank ICIR': 0.06}, 'data_train_vec': ['2023-09-16', '2025-12-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.060', 'weight': '0.024'}

	Recorder: d40b4e0780294b779b7ff4befe59c17d

		Model: {'id': 'd40b4e0780294b779b7ff4befe59c17d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.121, 'Rank IC': 0.015, 'Rank ICIR': 0.071}, 'data_train_vec': ['2024-09-16', '2026-03-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.071', 'weight': '0.029'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260916_16 485089260798613152 (Recorders: 4/5)

	Recorder: c3f6959c7d45442dad2aa2d599984a7e

		Model: {'id': 'c3f6959c7d45442dad2aa2d599984a7e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.159, 'Rank IC': 0.038, 'Rank ICIR': 0.229}, 'data_train_vec': ['2021-09-16', '2025-06-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.229', 'weight': '0.092'}

	Recorder: 16cdbd92a3c64cd0ad87a42a26ddbdd2

		Model: {'id': '16cdbd92a3c64cd0ad87a42a26ddbdd2', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.145, 'Rank IC': 0.023, 'Rank ICIR': 0.138}, 'data_train_vec': ['2022-09-16', '2025-09-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.138', 'weight': '0.056'}

	Recorder: 76f72a54c43947ccb305baf6b5221854

		Model: {'id': '76f72a54c43947ccb305baf6b5221854', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.024, 'Rank IC': 0.002, 'Rank ICIR': 0.008}, 'data_train_vec': ['2023-09-16', '2025-12-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.008', 'weight': '0.003'}

	Recorder: 263816db93bd4b858612f2b0775f1a88

		Model: {'id': '263816db93bd4b858612f2b0775f1a88', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.064, 'ICIR': 0.226, 'Rank IC': 0.046, 'Rank ICIR': 0.195}, 'data_train_vec': ['2024-09-16', '2026-03-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.195', 'weight': '0.079'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260916_16 426244676225195809 (Recorders: 3/5)

	Recorder: 4872766d288f44ba968760a2e5bd8752

		Model: {'id': '4872766d288f44ba968760a2e5bd8752', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.012, 'Rank IC': 0.035, 'Rank ICIR': 0.2}, 'data_train_vec': ['2021-09-16', '2025-06-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.200', 'weight': '0.081'}

	Recorder: a3ae325ac854433eac730b308adfb79a

		Model: {'id': 'a3ae325ac854433eac730b308adfb79a', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.019, 'Rank IC': 0.038, 'Rank ICIR': 0.254}, 'data_train_vec': ['2022-09-16', '2025-09-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.254', 'weight': '0.102'}

	Recorder: 887693b03f97445dbf18323a133fecae

		Model: {'id': '887693b03f97445dbf18323a133fecae', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.087, 'Rank IC': 0.005, 'Rank ICIR': 0.029}, 'data_train_vec': ['2024-09-16', '2026-03-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.029', 'weight': '0.012'}

# params 
 {'predict_dates': [{'start': '2026-06-17', 'end': '2026-06-17'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260617_18 629196449864598138 (Recorders: 3/5)

	Recorder: 113b7541df4448108266e93799a2dabc

		Model: {'id': '113b7541df4448108266e93799a2dabc', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.056, 'Rank IC': 0.036, 'Rank ICIR': 0.223}, 'data_train_vec': ['2022-06-17', '2025-06-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.223', 'weight': '0.045'}

	Recorder: 0a3fc837ccb94c838edd54edece8ce81

		Model: {'id': '0a3fc837ccb94c838edd54edece8ce81', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.1, 'Rank IC': 0.032, 'Rank ICIR': 0.214}, 'data_train_vec': ['2023-06-17', '2025-09-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.214', 'weight': '0.043'}

	Recorder: bbc580cdd5fb4e5a9fae63e55de8fb79

		Model: {'id': 'bbc580cdd5fb4e5a9fae63e55de8fb79', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.041, 'ICIR': 0.352, 'Rank IC': 0.042, 'Rank ICIR': 0.423}, 'data_train_vec': ['2024-06-17', '2025-12-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.423', 'weight': '0.085'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260617_18 460206496712122736 (Recorders: 4/5)

	Recorder: 97020682b2ad47d6af79dc3b1a427eb2

		Model: {'id': '97020682b2ad47d6af79dc3b1a427eb2', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.013, 'Rank IC': 0.019, 'Rank ICIR': 0.134}, 'data_train_vec': ['2021-06-17', '2025-03-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.134', 'weight': '0.027'}

	Recorder: 726f734ef9a448a79d1c4a616285204d

		Model: {'id': '726f734ef9a448a79d1c4a616285204d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.031, 'Rank IC': 0.038, 'Rank ICIR': 0.254}, 'data_train_vec': ['2022-06-17', '2025-06-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.254', 'weight': '0.051'}

	Recorder: fd338e3278694378bea1c6b95a16f84c

		Model: {'id': 'fd338e3278694378bea1c6b95a16f84c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.309, 'Rank IC': 0.042, 'Rank ICIR': 0.348}, 'data_train_vec': ['2023-06-17', '2025-09-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.348', 'weight': '0.070'}

	Recorder: 90f7c6cfbf9e4e86a9639a09335186f2

		Model: {'id': '90f7c6cfbf9e4e86a9639a09335186f2', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.351, 'Rank IC': 0.037, 'Rank ICIR': 0.383}, 'data_train_vec': ['2024-06-17', '2025-12-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.383', 'weight': '0.077'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260617_16 840912984319383566 (Recorders: 4/5)

	Recorder: 0ec7247ebab3420d986a393fecf76875

		Model: {'id': '0ec7247ebab3420d986a393fecf76875', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.098, 'Rank IC': 0.043, 'Rank ICIR': 0.295}, 'data_train_vec': ['2021-06-17', '2025-03-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.295', 'weight': '0.059'}

	Recorder: 90653e27659946958be412ab301547a1

		Model: {'id': '90653e27659946958be412ab301547a1', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.145, 'Rank IC': 0.051, 'Rank ICIR': 0.306}, 'data_train_vec': ['2022-06-17', '2025-06-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.306', 'weight': '0.062'}

	Recorder: 6837b71561664f3ea57a8bd01d8b2590

		Model: {'id': '6837b71561664f3ea57a8bd01d8b2590', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.133, 'Rank IC': 0.04, 'Rank ICIR': 0.263}, 'data_train_vec': ['2023-06-17', '2025-09-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.263', 'weight': '0.053'}

	Recorder: a68c1abd3b444827ac4c1667733a3695

		Model: {'id': 'a68c1abd3b444827ac4c1667733a3695', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.165, 'Rank IC': 0.028, 'Rank ICIR': 0.247}, 'data_train_vec': ['2024-06-17', '2025-12-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.247', 'weight': '0.050'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260617_16 556568351506740806 (Recorders: 4/5)

	Recorder: b0b4d30c4a28414cac3484dcbcf5f58f

		Model: {'id': 'b0b4d30c4a28414cac3484dcbcf5f58f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.035, 'Rank IC': 0.036, 'Rank ICIR': 0.299}, 'data_train_vec': ['2021-06-17', '2025-03-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.299', 'weight': '0.060'}

	Recorder: 16683fbb61f64093b7f720d63d2e073d

		Model: {'id': '16683fbb61f64093b7f720d63d2e073d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.007, 'Rank IC': 0.038, 'Rank ICIR': 0.281}, 'data_train_vec': ['2022-06-17', '2025-06-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.281', 'weight': '0.057'}

	Recorder: 3e032f81ea244bfb8d7228950a02411f

		Model: {'id': '3e032f81ea244bfb8d7228950a02411f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.035, 'Rank IC': 0.029, 'Rank ICIR': 0.234}, 'data_train_vec': ['2023-06-17', '2025-09-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.234', 'weight': '0.047'}

	Recorder: 1c28ddd682fa4076beec00f2b390fab7

		Model: {'id': '1c28ddd682fa4076beec00f2b390fab7', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.119, 'Rank IC': 0.021, 'Rank ICIR': 0.147}, 'data_train_vec': ['2024-06-17', '2025-12-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.147', 'weight': '0.030'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260617_16 754116491715682035 (Recorders: 4/5)

	Recorder: 5da6b295c49a444497849a0b35d76a29

		Model: {'id': '5da6b295c49a444497849a0b35d76a29', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.051, 'Rank IC': 0.043, 'Rank ICIR': 0.258}, 'data_train_vec': ['2021-06-17', '2025-03-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.258', 'weight': '0.052'}

	Recorder: c3876e14f70a478da4b09dc4739d895b

		Model: {'id': 'c3876e14f70a478da4b09dc4739d895b', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.053, 'Rank IC': 0.041, 'Rank ICIR': 0.233}, 'data_train_vec': ['2022-06-17', '2025-06-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.233', 'weight': '0.047'}

	Recorder: 4c1a5b512570455f94f2b23a71b09df5

		Model: {'id': '4c1a5b512570455f94f2b23a71b09df5', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.027, 'Rank IC': 0.029, 'Rank ICIR': 0.183}, 'data_train_vec': ['2023-06-17', '2025-09-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.183', 'weight': '0.037'}

	Recorder: 61c62d61147a4f969e0ed3a9e4582273

		Model: {'id': '61c62d61147a4f969e0ed3a9e4582273', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.043, 'Rank IC': 0.026, 'Rank ICIR': 0.242}, 'data_train_vec': ['2024-06-17', '2025-12-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.242', 'weight': '0.049'}

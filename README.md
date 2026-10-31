# ai-archive

learning archive for OSN AI / IOAI prep. not competition entries, just training and experience. bronze OSN AI, 8th place, 4000+ entrants.

all notebooks run on kaggle or locally. datasets not included (too big / competition data).

## OSN EKKA finals

| notebook | what its for |
|---|---|
| `muhammad-faiq-misyal-1-1-final-ekka.ipynb` | OSN 1-1: Membership Inference Attack. predict Member / Non-Member from overfit target model on sensitive text docs. |
| `muhammad-faiq-misyal-1-2-ekka-final.ipynb` | OSN 1-2: Leave You on the Back of the Earth. tonal alien language (Chi / Kyuuno / Ura / Nya), audio classification with librosa. |
| `muhammad-faiq-misyal-ekka-1-3-2-final.ipynb` | OSN 1-3: Scan Beras. 3D rice-grain MRI/CT slices (72 x 128 x 128), defect segmentation in RLE + volume regression. metric: 0.5 Dice + 0.5 volume accuracy. |
| `2-1-muhammad-faiq-misyal-final-ekka-2026.ipynb` | OSN 2-1: Alien Color Classification. MI / RE / DO sensor intensities -> color, 81 aliens, tabular classification. |
| `2-2-muhammad-faiq-misyal-final-ekka-2026.ipynb` | OSN 2-2: Dua Puluh Stasiun Cuaca. reconstruct 400 weather stations from 20 readings per row. matrix decomposition / PCA, NRMSE metric. |
| `2-3-muhammad-faiq-misyal-final-ekka-2026.ipynb` | OSN 2-3: Kunjungan Negara. Indonesian-Dutch sentence matching, N=20 permutation per testcase, retrieval / embedding similarity. |

## practice / training

| notebook | what its for |
|---|---|
| `Preprocessing_practice.ipynb` | hAIplay Locked Box starter. preprocessing drills only: fix the preprocess function, LogisticRegression baseline. |
| `torch_practice.ipynb` | pytorch basics drill: tensors, ops, autograd, small nn. generated drills + answers. |
| `paperreview.ipynb` | tabular practice: paper preliminary_decision / evaluation -> score prediction. RF / HGB / sklearn baselines. |
| `riceforecast.ipynb` | time-series practice: daily rice prices DKI / Jateng / Jatim 2021-2023. lags, Ridge / HGB, naive vs SES vs Holt baselines. |
| `socialmediaaddiction.ipynb` | tabular classification practice: social media addiction level from survey features. |
| `anxiety.ipynb` | tabular regression practice: anxiety_level from sleep / activity / caffeine / stress / vitals. |
| `alrena1.ipynb` | tabular classification practice: airena english dataset, RF / HGB / XGBoost + CV. |
| `haippychallenge4.ipynb` | image classification practice: haiplay challenge 4, CNN baseline on image-folder dataset. |

## stack

python, pandas, numpy, scikit-learn, pytorch. no venv, no install step, notebooks only.

# DACON Competitions

Competition notebooks from [DACON](https://dacon.io), Korea's largest data-science
competition platform. Six podium or award finishes across tabular, time-series,
audio and vision problems.

**Profile:** [dacon.io/myprofile/412049](https://dacon.io/myprofile/412049/home)

![DACON profile](https://github.com/paulms77/Dacon/assets/69188065/33fe797f-6a03-49ae-8178-0a2a9ae96f0d)

---

## Awards

| Competition | Result | Field |
| --- | --- | --- |
| 음향 데이터 COVID-19 검출 AI 경진대회 | 🥇 **1st** / 686 | Audio classification |
| 물류 유통량 예측 경진대회 | 🥈 **2nd** / 848 | Tabular regression |
| 인공지능 비트 트레이더 경진대회 시즌3 | 🥉 **3rd** / 1,411 | Time-series / trading |
| 건설기계 오일 상태 분류 AI 경진대회 | 🏅 우수상 (Excellence) / 1,309 | Tabular classification |
| 잡케어 추천 알고리즘 경진대회 | 🏅 장려상 (Encouragement) / 1,439 | Recommendation |
| 운동 동작 분류 AI 경진대회 | 🏅 **7th** / 1,280 | Sensor time-series |

> Prize money from the COVID-19 audio detection competition was donated to Save
> the Children Korea, for psychological therapy for children in low-income
> households (foster care and community child centres).

## Top placements

| Competition | Result |
| --- | --- |
| 자율주행 센서의 안테나 성능 예측 AI 경진대회 | Top 3% |
| 대구 교통사고 피해 예측 AI 경진대회 | Top 6% |
| 국민대학교 AI빅데이터 분석 경진대회 | Top 6% |
| AI 신약 개발 경진대회 | Top 6% |
| KRX 주식 투자 알고리즘 경진대회 | Finalist (본선 진출) |

## Notebooks

All competition notebooks live under [`competitions/`](competitions/).
Filenames were normalised to ASCII slugs; the Korean competition titles are kept
here.

### Time series and forecasting

| Notebook | Competition | Result |
| --- | --- | --- |
| [`ai-bit-trader-s3-arima.ipynb`](competitions/ai-bit-trader-s3-arima.ipynb) | 인공지능 비트 트레이더 시즌3 — ARIMA | Public 3rd / Private 29th |
| [`kogas-gas-demand-forecasting.ipynb`](competitions/kogas-gas-demand-forecasting.ipynb) | 한국가스공사 가스공급량 수요예측 | — |
| [`jeju-produce-price-forecasting.ipynb`](competitions/jeju-produce-price-forecasting.ipynb) | 제주 특산물 가격 예측 | — |
| [`hd-hyundai-vessel-waiting-time.ipynb`](competitions/hd-hyundai-vessel-waiting-time.ipynb) | HD현대 — 선박 대기시간 예측 | — |
| [`krx-trading-algorithm.ipynb`](competitions/krx-trading-algorithm.ipynb) | KRX 주식 투자 알고리즘 — see [KRX](https://github.com/paulms77/KRX) | Finalist |

### Tabular

| Notebook | Competition | Result |
| --- | --- | --- |
| [`stacking-ensemble-private-3rd.ipynb`](competitions/stacking-ensemble-private-3rd.ipynb) | Stacking ensemble | Private 3rd (8.69965) |
| [`catboost-3model-blend-private-8th.ipynb`](competitions/catboost-3model-blend-private-8th.ipynb) | 3-model CatBoost blend | Private 8th (Public 0.49139) |
| [`daegu-traffic-accident-risk.ipynb`](competitions/daegu-traffic-accident-risk.ipynb) | 대구 교통사고 피해 예측 | Top 6% |
| [`kookmin-job-recommender.ipynb`](competitions/kookmin-job-recommender.ipynb) | 국민대학교 AI빅데이터 분석 — see [Recommender-System](https://github.com/paulms77/Recommender-System) | Top 6% |
| [`lh-korea-land-housing.ipynb`](competitions/lh-korea-land-housing.ipynb) | LH 한국토지주택공사 | — |
| [`demographic-prediction.ipynb`](competitions/demographic-prediction.ipynb) | 인구 통계 예측 | — |
| [`psychological-disposition-prediction.ipynb`](competitions/psychological-disposition-prediction.ipynb) | 심리 성향 예측 AI | — |
| [`dacon-social-ai.ipynb`](competitions/dacon-social-ai.ipynb) | Social AI | — |

### Audio

| Notebook | Competition | Result |
| --- | --- | --- |
| [`covid19-cough-audio-detection-1st.ipynb`](competitions/covid19-cough-audio-detection-1st.ipynb) | 음향 데이터 COVID-19 검출 AI | 🥇 **1st / 686** |

### Vision

| Notebook | Competition |
| --- | --- |
| [`hansol-deco-s1-wallpaper-defect-classification.ipynb`](competitions/hansol-deco-s1-wallpaper-defect-classification.ipynb) | 한솔데코 시즌1 — 도배 하자 유형 분류 |
| [`swinv2-image-classification.ipynb`](competitions/swinv2-image-classification.ipynb) | Swin Transformer V2 image classification |

### Chemistry and materials

| Notebook | Competition | Result |
| --- | --- | --- |
| [`irak4-ic50-drug-discovery.ipynb`](competitions/irak4-ic50-drug-discovery.ipynb) | AI 신약개발 — see [AI-to-Drug-Discovery](https://github.com/paulms77/AI-to-Drug-Discovery) | Top 6% |
| [`samsung-ai-materials-discovery.ipynb`](competitions/samsung-ai-materials-discovery.ipynb) | 삼성 AI 신소재 발굴 | — |

### LG Aimers

Two cohorts of the LG Aimers programme, each ending in a competition — see
[Study](https://github.com/paulms77/Study) for the programme itself.

| Notebook | Task |
| --- | --- |
| [`lg-aimers/lg_antenna.ipynb`](competitions/lg-aimers/lg_antenna.ipynb) | 자율주행 센서 안테나 성능 예측 (cohort 1) — Top 3% |
| [`lg-aimers/lg_smartfactory.ipynb`](competitions/lg-aimers/lg_smartfactory.ipynb) | 스마트 공장 제품 품질 상태 분류 (cohort 2) |

Completion certificates for both cohorts are in
[`competitions/lg-aimers/`](competitions/lg-aimers/).

## Running these

Each notebook is self-contained and was written for Colab or Kaggle. Competition
data is **not** redistributed here — download it from the relevant DACON
competition page and adjust the data path at the top of the notebook.

```bash
git clone https://github.com/paulms77/Dacon.git
cd Dacon
jupyter notebook
```

## Related repositories

Competitions that grew large enough to deserve their own repository:

- [Hansol-Deco](https://github.com/paulms77/Hansol-Deco) — season 3, construction accident response generation (RAG)
- [Wallpaper-defects-knowledge-chat-service](https://github.com/paulms77/Wallpaper-defects-knowledge-chat-service) — season 2, QA service
- [Recommender-System](https://github.com/paulms77/Recommender-System) — Kookmin University AI big-data
- [AI-to-Drug-Discovery](https://github.com/paulms77/AI-to-Drug-Discovery) — IRAK4 IC50 prediction
- [Life-Research-Resources](https://github.com/paulms77/Life-Research-Resources) — cancer subtype classification
- [KRX](https://github.com/paulms77/KRX) — stock trading algorithm

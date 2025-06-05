# multi-AI-agent-investment-system
A multi-AI-agent investment simulation system using news and market data

Модель системи взаємодії AI-агентів для прийняття інвестиційних рішень на основі:
- Прогноз цін (LSTM)
- Аналіз новин (FinBERT + XGBoost)
- Портфельне перебалансування (Reinforcement Learning)
- Справедливий розподіл винагороди агентам (Nash Bargaining Solution)
- Google-таблиця для організації взаємодії агентів

## Структура
- `agents/` — скрипти кожного агента
- `notebooks/` — Colab-ноутбуки для тренування моделей
- `models/` — збережені моделі
  https://colab.research.google.com/drive/1OXvtthsAsr7qzB5Yyyo7WExkUWuxr1xW#scrollTo=-eoXloT6Layq
- `runAgents.py` — автоматичний запуск і координація

## Агенти
1. Client_01
https://colab.research.google.com/drive/1iiJeIpvTtqCpq3BQVodmv8kT6R0noZRE#scrollTo=4xGkpI0xK_OS
3. AnalyticalAgent
4. ExecutionAgent
https://colab.research.google.com/drive/1-pZkK5DBnJqZPClghU_NxNV1g2nLJ-Dn#scrollTo=tjIiJXAGNjPO
5. NewsAgent
https://colab.research.google.com/drive/1mhTKK8zy6HCiutNqQ2Z7epB_7cPRj8KF#scrollTo=0SdDp2y-XiM7

7. PortfolioAgent

8. SupervisorAgent

9. RewardAgent
https://colab.research.google.com/drive/1v2vqpZRVXIH2mnpD_QURfutuL567jLfB#scrollTo=sCZ1An8saDbd

## Google Sheets
- Уся взаємодія між агентами через таблицю:
  `[https://docs.google.com/spreadsheets/d/1gZW.../edit](https://docs.google.com/spreadsheets/d/1IfS73cTHuqCApp5XNrtuqFxwlzIINSPuOW5uxvrbgR8/edit)`

## Залежності

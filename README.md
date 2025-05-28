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
- `runAgents.py` — автоматичний запуск і координація

## Агенти
1. Client_01
[![Open in Colab](https://colab.research.google.com/drive/1iiJeIpvTtqCpq3BQVodmv8kT6R0noZRE#scrollTo=4xGkpI0xK_OS)
2. AnalyticalAgent
3. ExecutionAgent
4. NewsAgent
5. PortfolioAgent
6. SupervisorAgent
7. RewardAgent


## Google Sheets
- Уся взаємодія між агентами через таблицю:
  `[https://docs.google.com/spreadsheets/d/1gZW.../edit](https://docs.google.com/spreadsheets/d/1IfS73cTHuqCApp5XNrtuqFxwlzIINSPuOW5uxvrbgR8/edit)`

## Залежності

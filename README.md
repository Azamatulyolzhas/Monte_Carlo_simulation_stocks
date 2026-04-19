# Stock Price Analysis & Monte Carlo Simulation

Анализ акций **AAPL • MSFT • TSLA** с помощью **NumPy**, **Matplotlib** и **SciPy**.  
Проект полностью без pandas — только чистый Python и математика.

## Что сделал в проекте

- Симуляция цен акций с помощью **Geometric Brownian Motion (GBM)**
- Расчёт доходности, волатильности, Sharpe Ratio, VaR и CVaR
- **Monte Carlo Simulation** — 10 000 сценариев развития цен
- Построение **Efficient Frontier** из 50 000 случайных портфелей
- Проверка нормальности распределения доходностей (Jarque-Bera + Q-Q plots)
- Красивый Summary Dashboard

## Технологии

- **Python**
- **NumPy** — вся математика и симуляции
- **Matplotlib** + **gridspec** — профессиональная визуализация
- **SciPy** — статистические тесты

## Основные визуализации

- Динамика цен и кумулятивная доходность
- Efficient Frontier с выделением лучшего портфеля
- Rolling volatility
- Q-Q plots и тест на нормальность
- Итоговый Dashboard

## Как запустить

```bash
git clone https://github.com/твой_ник/stock-analysis-montecarlo.git
cd stock-analysis-montecarlo

# Если нужно, создай окружение
pip install numpy matplotlib scipy
jupyter notebook stock_analysis.ipynb

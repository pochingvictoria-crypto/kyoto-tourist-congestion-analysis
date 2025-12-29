# kyoto-tourist-congestion-analysis
An analysis of tourist congestion in Kyoto using monthly visitor data, focusing on structural factors, regional interaction, and inbound visitor behavior.

## Overview
This project provides a data-driven examination of tourist congestion in Kyoto
based on monthly visitor statistics.
The objective is to understand the structural and temporal factors behind congestion
and to explore possible directions for effective tourist dispersion strategies.

## Data
- Monthly tourist arrivals (観光入込客数・月次)
- Period: 2014–2019, 2023–2024
- Source: Public tourism statistics published by Kyoto City

## Analysis Structure

### 1. Factors Behind Tourist Congestion in Kyoto City
This section examines how tourist congestion has emerged by analyzing long-term trends
and seasonal patterns in monthly visitor data. The analysis highlights structural
characteristics rather than short-term fluctuations.

京都市における観光客の混雑が、長期的なトレンドや季節性といった
構造的要因によって形成されていることを分析する。

### 2. Interaction Between Kyoto City and Surrounding Regions
This section examines the relationship between tourism activity in Kyoto City and
surrounding regions using correlation analysis. The focus is on identifying whether
visitor movements show synchronous patterns rather than evaluating causal or policy
effects.

This analysis is descriptive and does not attempt to infer causal relationships
or policy impacts.

本節では、京都市と周辺地域における観光動態の関係性について、
相関分析を用いた記述的な検討を行っている。
観光客数の変動が同時的に連動しているかを確認することを主眼とし、
因果関係や施策効果の検証を目的とした分析ではない。

### 3. Direction of Tourist Dispersion Based on Inbound Visitor Behavior
This section incorporates insights from inbound tourist behavior and preferences
to discuss potential directions for tourist dispersion beyond purely quantitative indicators.

訪日外国人の行動意識を踏まえ、観光統計などの定量データを背景情報として用いながら、
数値指標だけでは捉えきれない分流促進の方向性について考察する。

## Tools
- Python (pandas, matplotlib)
- Jupyter Notebook
- Ordinary Least Squares (OLS) regression
- Correlation analysis

## Limitations
- Monthly data limits the analysis of intra-day congestion patterns
- Policy impact identification remains exploratory due to data constraints

## Future Work
- Incorporate higher-frequency or spatial data
- Apply forecasting models to evaluate future congestion scenarios

今後は、日次・時間帯別データや地域別データなど、
より高頻度・空間的に詳細なデータを用いることで、
混雑の発生タイミングや場所をより精緻に把握することが可能になる。
また、過去の傾向を基にした時系列予測モデルを適用することで、
将来的な混雑状況に関するシナリオ分析も検討できる。

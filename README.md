# LSTM Models Directory

Place your trained LSTM model files here with the following naming convention:

## Required Model Files:
- btc_hourly_lstm.keras
- btc_daily_lstm.keras
- eth_hourly_lstm.keras
- eth_daily_lstm.keras
- sol_hourly_lstm.keras
- sol_daily_lstm.keras
- xrp_hourly_lstm.keras
- xrp_daily_lstm.keras
- ltc_hourly_lstm.keras
- ltc_daily_lstm.keras
- doge_hourly_lstm.keras
- doge_daily_lstm.keras
- bch_hourly_lstm.keras
- bch_daily_lstm.keras

## Notes:
- Models should be saved in Keras format (.keras extension)
- Each cryptocurrency needs both hourly and daily models
- Models should accept the same input format as your existing predict_function.py
- Make sure your predict_function.py is in the root directory
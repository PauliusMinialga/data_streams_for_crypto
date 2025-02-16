# data_streams_for_crypto
This project is designed to collect and process various data streams related to cryptocurrency trading on Binance. The project consists of multiple scripts that connect to Binance's WebSocket API to fetch real-time data on trades, liquidations, and funding rates.
--------
### Features
- Collects and processes real-time trade data for multiple cryptocurrency symbols
- Tracks and alerts on large trades and liquidations
- Monitors and displays funding rates for various symbols
- Stores collected data in CSV files for further analysis
---
### Scripts
- **huge_trades.py**: Connects to Binance's WebSocket API to fetch real-time trade data for multiple symbols. It aggregates trades by symbol and time, and prints out large trades.
- **liquidations.py**: Connects to Binance's WebSocket API to fetch real-time liquidation data. It prints out liquidations that exceed a certain threshold.
- **funding.py**: Connects to Binance's WebSocket API to fetch real-time funding rate data for multiple symbols. It displays the funding rates in real-time.
---
### Requirements
- Python 3.x
- *websockets* library
- *termcolor* library
- *pytz* library
- *json* library
---
### Usage
1. Install the required libraries
2. Run each script individually using *python script_name.py*
3. Configure the symbols list in each script to track the desired cryptocurrency symbols
---
### Notes
- This project is for educational purposes only and should not be used for production trading.
- The project uses Binance's WebSocket API, which may have usage limits and requirements.
- The project stores collected data in CSV files, which can grow large over time.


--------------
**P.S.** - the code was written by following MoonDevs' 'Algo Trading Bootcamp'
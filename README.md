# TradingView
Using a provided widgit and Firebase as a source of configuration data.

A widgit for charting shares is provided  by Trading View https://uk.tradingview.com/

The widgit is configured with configuration data which is set with the code generation tool which makes the information fixed.

Providing storage on a server for this configuration data allows this to be changed with a common login.

Firebase is used as a simple storage for configuration data. Using the REST API interface with no authentication required for data read.

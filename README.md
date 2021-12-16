# Autoencoder-Powered-Trading-Bot-for-Pfizer-Stock

I use an autoencoder and reinforcement learning to create a trading bot for the Pfizer stock. I calculate important financial indicators for the stock, such as RSI and moving averages. I then use an autoencoder to eliminate noise and extract important trends from the indicators, using the compressed (bottleneck) representation as environment signals that are fed to the trading bot. I also build a baseline model, against which I compare the performance of the AE-powered trading bot.

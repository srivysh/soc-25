# AI-based Financial Portfolio Manager using DRL

This is my midterm submission for the project where I am building a financial portfolio manager using Deep Reinforcement Learning (DRL). Over the last 4 weeks, I explored the basics of RL, financial data processing, technical indicators, and started working on integrating DRL agents for training.

# Week 1: Introduction to DRL & Financial Markets

In this week, I learnt the fundamentals of Reinforcement Learning like agent, environment, rewards, and policies. I also understood how RL applies to finance — where an agent makes asset allocation decisions based on reward signals. I studied risk-return metrics like Sharpe Ratio and Drawdown to evaluate trading performance.

# Week 2: Data Collection & Processing

I learnt how to collect historical data for stocks and crypto using APIs like yFinance. I worked on cleaning and aligning time series data for multiple assets using pandas. This helped me understand how to prepare real-world financial data that can be used for training RL models.

## Week 3: Technical Indicators and Custom Gym Environment

This week, I implemented technical indicators like RSI, MACD, and Bollinger Bands using TA-Lib. I also created a basic custom OpenAI Gym environment for trading simulation. I defined the state, action, and reward setup so that it can later be used to train a reinforcement learning agent.

# Week 4: PPO/DDPG Agent Integration (In Progress)

In this week, I started working with DRL algorithms like PPO (Proximal Policy Optimization) and DDPG (Deep Deterministic Policy Gradient). I explored how to define action and observation spaces for portfolio allocation. I used the stable-baselines3 library to begin training agents on historical data using the custom environment. This part is still in progress and will be developed further after midterm.

# What I Have Learnt So Far

- Core RL concepts and their mapping to finance
- Collecting and cleaning financial time series data
- Computing technical indicators for market analysis
- Building a Gym environment for trading
- Initial integration of DRL agents using stable-baselines3

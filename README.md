🚀 Crypto Vista-Cryptocurrency-Trading-Platform

A beginner to intermediate full-stack cryptocurrency trading platform built with React,   , Spring Boot, MySQL, and third-party APIs like Coin Gecko and Gemini. The app supports real-time crypto data, wallet management, order placement, payments, and even AI chatbot interaction.

🔍 Overview

Crypto Vista offers users a secure and responsive environment to:

1.	🔐 Sign up / log in securely using JWT + Spring Security

2.	📈 View live market data for hundreds of cryptocurrencies

3.	👛 Manage wallets and track individual assets

4.	📊 Buy/sell coins using simulated orders

5.	💳 Pay via Razorpay/Stripe

6.	🤖 Ask questions to an AI-powered chatbot (Gemini-based)

7.	🔄 Perform wallet-to-wallet transactions (on-chain concept)


🚀 Features

1.	🔐 Secure Login & JWT Authentication

2.	📈 Real-Time Market Data from CoinGecko & Gemini APIs

3.	🪙 Buy/Sell Orders with OrderType (BUY/SELL)

4.	💼 Portfolio View by Logged-In User

5.	👛 Wallet & Transaction Management

6.	🤖 AI Chatbot for User Support (Gemini integrated)

7.	📲 Responsive UI using React + Tailwind CSS + ShadCN

8.	💳 Razorpay & Stripe Integration for Payments

9.	🧾 Order History & Wallet History by User

10.	📊 Crypto Chart Visualizations

11.	🌍 Exportable Coin & Portfolio Data (CSV/Excel coming soon)


🧩 Folder Structure & Modules

Backend (Spring Boot)

a.	model/ - Java classes like CoinDTO, Asset, WalletTransaction

b.	repository/ - Repositories like AssetsRepository, OrderRepository

c.	controller/ - REST APIs for coins, orders, wallets, auth

d.	request/ - Request DTOs like CreateOrderRequest

e.	service/ - Service layer for business logic

f.	security/ - JWT-based Spring Security configuration


Frontend (React)

a.	pages/ - Pages like Dashboard, Orders, Portfolio

b.	components/ - UI Components for Header, CoinCard, etc.

c.	redux/ - State Management for user, coins, wallets

d.	api/ - Axios-based service for API calls

e.	assets/ - Icons, images, logo


🔄 State Management

a.	Frontend uses Redux Toolkit to manage state:

i.	User Auth & Tokens

ii.	Coin List / Prices

iii.	Wallet & Order Data

b.	Backend uses Spring layers for logic separation

c.	Repositories act as DAO (Data Access Object) between DB and services


🙌 Credits

🪙 CoinGecko & Gemini for crypto APIs

🤖 Gemini AI for Chatbot

💳 Stripe & Razorpay for payments







  

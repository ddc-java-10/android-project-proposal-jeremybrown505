---
title: Investmentz
description: "Tools for Traders"
layout: default
---

## Summary

Investmentz is an android based platform that will allow its users to setup an account, chose to use fake money or real money and start trading using live market data. Investmentz will have several tools such as the ability to buy and sell with fake money before risking their real life assets, setting up buy and sell orders from the app, keep a history of those orders, and some basic profit analysis to help a trader monitor and analyze the effectiveness of their strategies. 

## Intended users
		
*New traders who want to use play money and develop some strategies using real market conditions, and analyze their decisions before rising their real life assets. 
	
"As a new trader I really want a platform that uses live, real market data to allow me to set up fake trades and test my strategy. I would like some tools that allow me to see a history of market, and a some data that helps me analyze whether my strategies are working."
	
*Day traders who want to create and tweak new strategies, and be able to use real world funds to execute trades and have access to some tools to help them analyze the results. 
	
"As a day trader I wonder how effective the trades I have initiated have been. I would like to see a history of the trades I have made, the price I purchased the comodity for, how much it sold for, the date and time this transaction occured, and the profit margins of that particular trade, shown both in dollars, as well as a percentage of the total investment. With these tools I wish to create, test, and evaluate new strategies, in a real or simulated environment." 
	
	
## Functionality

*The ability to set up a unique username and password, as well as tying that into a cell phone number, and possibly setting up two factor authentication. 
	
*Access live market data.
	
*Storing a history of data. What was purchased, when, for what price, and what it sold for, as well as the profit/loss in raw dollar amounts and percentage of initial investment. 
	
*The program will create a simulated environment using fake money and live market data allow the user to practice their trading skills while recording and analyzing the results. 

## Persistent data 
	
*The name of the user.
	
*Last known market price of comodity(s) that the user has invested in. 
	
*Last known balance of users "virtual wallet"
	
*An array containing a history of data, including the price a comodity was purchased for, what it was sold for, as well as the dollar amount gained or lost, and a percentage gain/loss on total investment. 

    
## Device/external service

*Need access to the security sensors (fingerprint/ faceid/ iris scanner) for login purposes.
	
*Access to an api from Coinbase pro, pulling in data pertaining to the current price, as well as putting in buy and sell orders (limit and stop orders included) from within the app. [Click for Coinbase pro API.](https://developers.coinbase.com/api/v2#introduction) 
	

## Stretch goals/possible enhancements 
	
*A way users can log in to see not only a history of transactions but a list of currently open orders
	
*An indicator showing how much profit they earned yesterday, last week, last month, and last year.
	
*An indicator that runs a calculaton showing the estimated profit/loss from an open trade if it was closed right now, as well as profit margins if a stop or limit order was used. 
	
*Software that will help you report your income and properly fill out tax paperwork. 


For these last couple I do not plan to work on them in school, but I plan on implementing them sometime in the future as I continue to develop this platform. 
	
*Paramaters that traders can adjust, to set up a system that executes buy/sell orders based on pre-determined conditions, and will execute those trades even when the user is offline. 
	
*A bot that has the paramaters already programed in with a set of rules that has been tested to be consistently profitable. Including software with break even paramaters and the ability to calculate your current profit/loss margin while taking into account transactional fees and taxes. Lastly the bot should report its earnings to the user on a trade by trade basis via the app, and calculate how much profit has been earned daily, weekly, monthly, and yearly. 
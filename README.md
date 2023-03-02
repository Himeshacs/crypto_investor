# CryptoInvestor CLI

## Overview

This is a command line program for a crypto investor who has made transactions over a period of time which is logged in a CSV file. The program provides functionality to retrieve the portfolio value per token in USD at a specific date or the latest portfolio value for a specific token.

## Problem Statement

Write a command line program that does the following:

✅Given no parameters, return the latest portfolio value per token in USD
✅Given a token, return the latest portfolio value for that token in USD
✅Given a date, return the portfolio value per token in USD on that date
✅Given a date and a token, return the portfolio value of that token in USD on that date

The CSV file has the following columns:

✅timestamp: Integer number of seconds since the Epoch
✅transaction_type: Either a DEPOSIT or a WITHDRAWAL
✅token: The token symbol
✅amount: The amount transacted

## Dependencies

✅request package
✅yargs package
✅date-and-time package

## Installation

> Clone the repository
> Run npm install to install the required node modules
> Run npm install request to install the request package
> Run npm install yargs to install the yargs package
> Run npm install date-and-time to install the date-and-time package

## Retrieve Latest Portfolio Value

To retrieve the latest portfolio value per token in USD, run the following command in the terminal:

> > node main.js

## Retrieve Latest Portfolio Value for a Specific Token

To retrieve the latest portfolio value for a specific token in USD, run the following command in the terminal, replacing TOKEN_SYMBOL with the token symbol of your choice (e.g. BTC, ETH, XRP):

> > node main.js --token=TOKEN_SYMBOL

## Retrieve Portfolio Value per Token on a Specific Date

To retrieve the portfolio value per token in USD on a specific date, run the following command in the terminal, replacing DATE with the desired date in the format MM/DD/YYYY (e.g. 04/03/2019):

> > node main.js --date=DATE

## Retrieve portfolio Value of a Specific Token on a Specific Date

To retrieve the portfolio value of a specific token in USD on a specific date, run the following command in the terminal, replacing TOKEN_SYMBOL with the token symbol of your choice (e.g. BTC, ETH, XRP), and DATE with the desired date in the format MM/DD/YYYY (e.g. 04/03/2019):

> > node main.js --token=TOKEN_SYMBOL --date=DATE

Owner : Himesha Sooriarachchi

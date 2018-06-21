# TradingView JS API Examples

> In order to run these examples you need to download the private [TradingView Charting Library](https://github.com/tradingview/charting_library) from github, which you must [apply](https://www.tradingview.com/HTML5-stock-forex-bitcoin-charting-library/) for acces to from TradingView. These won't work without the Library!
> If you do have access to the repo, then follow the instructions at the bottom of this Readme

Code for a series about using the TradingView Charting Library's JS API. 

Find the guide on Medium [here](https://medium.com/@jonchurch/tradingview-js-api-integration-tutorial-introduction-5e4809d9ef36)

## Setup

First, do you have access to the [TradingView Charting Library](https://github.com/tradingview/charting_library)? 

If that link shows you a 404, then you do not, and you must [apply for access](https://www.tradingview.com/HTML5-stock-forex-bitcoin-charting-library/) with TradingView before proceeding.

If you do have access, then clone the repository to your local machine and copy the charting_library folder inside the charting library project into the public folder of an example before running it.


```
git clone https://github.com/tradingview/charting_library
cp -r charting_library/charting_library ./part1/public/
```
Once you have added the charting library, run `npm install` from inside the step you want to run.

Then run `npm start` to start the development server, and visit `localhost:3000` in your browser.

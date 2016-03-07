# JSE Reference Data
Reference data for JSE (Johannesburg Stock Exchnage) listed and delisted companies

There is a lack of publicly available reference data on JSE listed and delisted stocks that can be easily consumed by programming languages and applications.
This data set is provided in the the public domain to use and keep up to date for this purpose.

## Data Format:

|Column | Description|
|---|---|
|ticker | Unique value that gets reused.  To keep the uniqueness .DEL is appended to a ticker to indicate that it was assigned to a stock that is not listed anymore and there exists another stock with the same ticker
|isin | The international security identifier
|shortname | A shortname as useed by the JSE
|fullname | The fullname of the registered company
|industry | The industry according to the JSE industry classification
|supersector |  
|sector |
|subsector |
|listing_status|
|trading_status|
|equity_type|
|equity_class|
|marketdata_currency| The iso currency code of the currency in which the stock is traded - for the JSE it would be ZAR
|financial_currency| The iso currency code of the currency in which the finacial statements of the company is reported
|last_update| **This column can be removed**
|alsi_member| Is this stock a member of the FTSE/JSE ALSI index
|top40_member| Is this stock a member of the FTSE/JSE Top40 index
|irregular_flag| **This column can be removed**

## Usage

The data is provided freely to use as you like.  Either download the file or clone the repo.

## Contribute

If you would like to contribute to the improvment and maintenance of this data, clone the repo, make changes and send a pull request.

See the open issues for specific fix and enhancement requests.

Also if you would like to contribute other reference data for other instruments (Unit trusts, Futures, Warrants, options etc), it would be appreciated.  The data can be for any other country given that the data is not available in a convenient format anywhere else and you have the permission to publish it under the creative commons license.

##License:

All the data in this repository is licensed under the creative commons [CCO 1.0] licence.

See the licence file.
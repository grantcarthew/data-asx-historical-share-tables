# ASX Historical Share Tables

These historical share tables cover trading in all main board
Australian Stock Exchange stocks.

This project contains an archive of these tables in CSV format.

## Installation

`git clone https://github.com/grantcarthew/data-historical-share-tables.git`

## Usage

All files are of the CSV file format which can be opened with data analysis
applications such as Microsoft's Excel. Alternatively you can import the
data into a Database for further manipulation.

The files are stored in a directory structure under the csv directory.
Under csv you will find a Daily or Weekly directory with the table name
directory under that.

The filenames are complete so each file can stand alone out of its
directory structure. The file name standard is the following;
`[Daily or Weekly] - [Table Name] - [ISO Date Format yyyy-MM-dd].csv`

Example:
`Daily - 50 Leading Mining and Oil Stocks - 2009-10-20.csv`

### Daily Summary Files

*   100 Leading Industrial Stocks
*   50 Leading Mining and Oil Stocks
*   Industrial Market
*   Mining & Oil Market
*   Interest Rate Securities Market
*   S&P/ASX200
*   S&P/ASX300
*   Rolling Year Records
*   ASX Market Action - stocks that moved by 5% or more
*   Warrant Market
*   Derivatives - Call Options
*   Derivatives - Put Options
*   Course of Sales
*   ASX Daily Gross Short Sales Summary

### Weekly Summary Files

*   Weekly Roundup - Sector by Sector
*   Industrial Market
*   Interest Rate Securities Market
*   Mining and Oil Market
*   Weekly Roundup - Australian Indices
*   Weekly Roundup - ASX National Turnovers
*   Weekly Roundup - Sydney Futures Exchange
*   Weekly Roundup - Overseas Indices
*   Warrant Market
*   Derivatives - Call Options
*   Derivatives - Put Options
*   ASX Top 300 Stocks
*   ASX Dividends Declared
*   Overseas Stocks
*   Managed Funds

## Contributing

1.  Fork it!
2.  Create your feature branch: `git checkout -b my-new-feature`
3.  Commit your changes: `git commit -am 'Add some feature'`
4.  Push to the branch: `git push origin my-new-feature`
5.  Submit a pull request :D

## History

2016-01-02: Initial Commit

## Credits

[Australian Financial Review](http://www.afr.com/)
[Australian Financial Review - Share Tables](http://www.afr.com/share_tables/#daily_tables)

## License

This is public data and as far as I can tell from the Australian
Financial Review website there are no restrictions on its use.

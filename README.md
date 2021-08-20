
<h1>Balance Sheet API - Finnworlds</h1>

<p><a href="https://finnworlds.com/finance-data/balance-sheet-api/">The Balance Sheet API</a> is available through JSON REST API and our databases are also downloadable as an excel or csv file.  We have historical balance sheets in our database from the IPO of all publicly traded companies. Through our API you can request individual components of the balance sheet over the history of a company, or you can request the entire balance sheet based on ticker symbol or ISIN number of a company. The API is very intuitive and easy to use</p>



<p><a href="https://finnworlds.com/">Finnworlds</a> Our clients are big enterprises as well as individual developers who use the financial data to develop their platforms without having to worry about maintaining an actual database. We take this worry away so that you can focus on your core business.</p>




<p><a href="https://finnworlds.com/pricing">Sign up for an API key</a> to get started with the data right away. We don't have free packages on the website but for students we can do something. Just email us and lets talk about it.</p>



<h2>API Features</h2>



<ul><li><strong>Historical Balance Sheets</strong></li><li><strong>Current Balance Sheets</strong></li><li><strong>Filter by individual components</strong></li><li><strong>Extract Balance Sheets from multiple companies at once</strong></li><li><strong>Request more features from us</strong></li></ul>


<h2>How to access the data</h2>



<ul><li><strong>JSON rest API</strong></li><li><strong>Excel CSV download</strong></li><li><strong>PDF reports</strong></li><li><strong>Email link</strong></li></ul>



<h2>Documentation</h2>



Our <a href="https://finnworlds.com/documentation">documentation</a> includes input parameters, output objects with explanation of their meaning, we also provide clear examples on the documentation page of various endpoints and their output. On top of this we have SDKs for Javascript, JQuery, VueJS, Angular, JAVA, PHP, NodeJS, Python, Go, Ruby, C#, R, Strest, Rust, Swift and Scala</p>


<h2>Examples</h2>




<p>https://finnworlds.com/api/v1/balancesheets?key=YOUR-KEY&stock_ticker_symbol=aapl</p>



    "status": {
        "message": "Success"
    },
    "results": [
        {
        "basics": {
            "name": "Apple Inc",
            "stock_ticker_symbol": "AAPL"
            "isin_identifier": "US0378331005"
            "exchange": "nasdaq"
            "industry": "technology"
            "sector": "consumer electronics"
        },
        "output": {
            "total_assets": "323,888,000",
            "total_liabilities_net_minority_interest": "258,549,000"
            "total_equity_gross_minority_interest": "65,339,000"
            "total_capitalization": "164,006,000"
            "common_stock_equity": "65,339,000"
            "net_tangible_assets": "65,339,000"
            "working_capital": "38,321,000"
            "invested_capital": "177,775,000"
            "tangible_book_value": "65,339,000"
            "total_debt": "112,436,000"
            "net_debt": "74,420,000"
            "share_issued": "16,976,763",
            "ordinary_shares_number": "16,976,763"
        }
    [





<p>https://finnworlds.com/api/v1/balancesheets?key=YOUR-KEY&sector=technology&industry=consumer_electronics&income_statement=total_assets&year=2021</p>





    "status": {
        "message": "Success"
    },
    "results": [
        {
        "basics": {
            "name": "Apple Inc",
            "stock_ticker_symbol": "AAPL"
            "isin_identifier": "US0378331005"
            "exchange": "nasdaq"
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "total_assets": "323,888,000",
            },
        "basics": {
            "name": "Microsoft Corporation",
            "stock_ticker_symbol": "MSFT"
            "isin_identifier": "US5949181045"
            "exchange": "nasdaq"
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "total_assets": "333,779,000",
            },
        "basics": {
            "name": "Dell Technologies Inc",
            "stock_ticker_symbol": "DELL"
            "isin_identifier": "US24703L2025"
            "exchange": "NYSE"
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "total_assets": "123,415,000",
            },
        "basics": {
            "name": "...",
            "stock_ticker_symbol": "..."
            "isin_identifier": "..."
            "exchange": "..."
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "total_assets": "...",
            }
        "basics": {
            "name": "...",
            "stock_ticker_symbol": "..."
            "isin_identifier": "..."
            "exchange": "..."
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "total_assets": "...",
            },
        }
    [




<h2>Customer Support</h2>

<p>Need help, have questions? <a href="mailto:support@finnworlds.com">Get in touch with Support</a>.</p>

<h2>Legal</h2>

<p>Use of the Finnworlds website, services like API and database are subject to the&nbsp;<a href="https://finnworlds.com/legal/terms-and-conditions-on-finnworlds-data/">Finnworlds terms &amp; Conditions</a></p>

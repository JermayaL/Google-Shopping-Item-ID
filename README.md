# Google-Shopping-Item-ID
This Google Ads script gathers various performance metrics for items in shopping or PMax campaigns. The script collects the following data for each item.

<ol>
<li>ROAS.</li>
<li>Spend.</li>
<li>Conversion Rate.</li>
<li>Revenue.</li>
<li>Conversions.</li>
<li>Average Order Value (AOV).</li>
<li>Price.</li>
<li>Price - AOV (difference between the item's price and the average order value).</li>
</ol>
&nbsp;
<p></p>These metrics are collected for different time periods: 24 months, 12 months, 60 days, 14 days, and 7 days. The script handles an API limit of 250 items by processing the data in portions. This means that it retrieves the metrics for a subset of items at a time, considering the API limit restrictions.</p>
&nbsp;

<h2><strong></strong>Commands</h2>
<ol>
<li>The script contains one spreadsheet. And is a MCC-level script.</li>
<li>Make a copy from the spreadsheet: Item-ID trend report.</li>
<li>Go to your MCC-account. Go to scripts. Insert the script and give it a descriptive name (Item ID analytics)</li>
<li>In row 2, insert your spreadsheet copy URL from the Item-ID trend report.</li>
<li>Open the spreadsheet and include both your Google Ads Client ID and Merchant Centre ID (Settings tab).</li>
<li>Go back to Google Ads and enable ‘Shopping content’.</li>
<li>You are now able to run the script.</li></ol>

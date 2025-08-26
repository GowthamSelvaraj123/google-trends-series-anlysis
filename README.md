  <h1>Google Trends Time Series Analysis</h1>
    <p>
        This project explores the relationship between Google search trends and time series data such as:
    </p>
    <ul>
        <li>Tesla stock price vs Tesla web search popularity</li>
        <li>Bitcoin daily price vs Bitcoin news search trends</li>
        <li>Unemployment rate vs "Unemployment Benefits" search trends in the U.S.</li>
    </ul>
    <h2>Key Features</h2>
    <ul>
        <li>Convert daily to monthly data using <code>resample()</code></li>
        <li>Use Matplotlib's <code>Locators</code> and <code>DateFormatters</code> for time axes</li>
        <li>Dual-axis line charts for comparing trends with actual values</li>
        <li>Rolling average calculations to smooth search data</li>
        <li>Gridlines and enhanced styling for better visualization</li>
    </ul>
    <h2>Libraries Required</h2>
    <ul>
        <li><code>pandas</code></li>
        <li><code>matplotlib</code></li>
    </ul>
    <h2>Installation</h2>
    <pre>
    pip install pandas matplotlib
    </pre>
    <h2>Usage</h2>
    <p>
        1. Place the CSV files (tesla.csv, bitcoin_price.csv, bitcoin_search.csv, unemployment.csv, UE Benefits Search vs UE Rate 2004-20.csv) in the project folder.<br>
        2. Run <code>app.py</code> to generate all the visualizations for Tesla, Bitcoin, and US unemployment trends.
    </p>
    <h2>Insights</h2>
    <ul>
        <li>Search trends often act as leading indicators for stock and economic movements.</li>
        <li>Tesla stock price spikes correlate with increased web search popularity.</li>
        <li>Bitcoin search trends show spikes during major price changes.</li>
        <li>US unemployment search trends anticipate changes in the official unemployment rate.</li>
    </ul>

    <h2>License</h2>
    <p>MIT License</p>

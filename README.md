<h1>Web Traffic Analysis Project Overview</h1>
   <p> A comprehensive web traffic analysis dashboard was created using Splunk to identify trends, patterns, and anomalies in web traffic data. The primary objective was to investigate potential security threats, detect trends and anomalies, and inform business decisions.</p>

<hr>

<h2>Project Methodology</h2>
<p>The following steps were taken to complete the project:</p>
<ul>
<li><strong>Step 1: Data Index and Source Type</strong>

<img src="https://i.imgur.com/SkPYhtn.jpeg" alt="Data Index and Source Type">
</li>
<li><strong>Step 2: Data Visualization of Total Traffic</strong>

<img src="https://i.imgur.com/CWjPceM.jpeg" alt="Data Visualization of Total Traffic1">
<img src="https://i.imgur.com/Pd3OEzz.jpeg" alt="Data Visualization of Total Traffic2">
<img src="https://i.imgur.com/cLX9xvl.jpeg" alt="Data Visualization of Total Traffic3">
</li>
<li><strong>Step 3: Geographical Visualization of Web Traffic</strong>

<img src="https://i.imgur.com/6EhTcs0.jpeg" alt="Geographical Visualization of Web Traffic1">
<img src="https://i.imgur.com/QWVJyw4.jpeg" alt="Geographical Visualization of Web Traffic2">
<img src="https://i.imgur.com/NwRaqj6.jpeg" alt="Geographical Visualization of Web Traffic3">
</li>
<li><strong>Step 4: Step 4: Dashboard Visualisation by Action.This Dashboard shows the Traffic volume of each value of the action field.These values are Addtocart,Change quality,Purchase,Remove,View.</strong>

<img src="https://i.imgur.com/yJ0MjF4.jpeg" alt="Web Traffic Analysis Dashboard Visualization1">
<img src="https://i.imgur.com/ueYvFi0.jpeg" alt="Web Traffic Analysis Dashboard Visualization2">
<img src="https://i.imgur.com/hYPGCR9.jpeg" alt="Web Traffic Analysis Dashboard Visualization3">
<img src="https://i.imgur.com/rr3aYV9.jpeg" alt="Web Traffic Analysis Dashboard Visualization4">
</li>
</ul>

<hr>

<h2>Key Findings</h2>
<ul>
<li><strong>Total Web Actions:</strong> 19,718</li>
<li><strong>Action Distribution:</strong>
<ul>
<li>View: 5,391 (27.34%)</li>
<li>Add to Cart: 5,743 (29.12%)</li>
<li>Change Quantity: 1,402 (7.11%)</li>
<li>Purchase: 5,737 (29.09%)</li>
<li>Remove: 1,445 (7.34%)</li>
</ul>
</li>
<li><strong>Highest Activity by IP:</strong>
<ul>
<li>United Kingdom: 153 "Add to Cart" actions (87.194.216.51)</li>
<li>United Kingdom: 151 "Purchase" actions (87.194.216.51)</li>
<li>United Kingdom: 145 "View" actions (87.194.216.51)</li>
<li>China: 109 "Add to Cart" actions (211.166.11.101)</li>
</ul>
</li>
<li><strong>Geo-Location Analysis:</strong>
<ul>
<li>United States: 5,084 (25.78%)</li>
<li>United Kingdom: 1,349 (6.85%)</li>
<li>China: 3,453 (17.51%)</li>
</ul>
</li>
</ul>

<hr>

<h2>Technical Tool(s) Utilized</h2>
<ul>
<li>Splunk</li>
</ul>

<hr>

<h2>Achievements</h2>
<ul>
<li>Successfully created a comprehensive web traffic analysis dashboard.</li>
<li>Identified key trends, patterns, and anomalies.</li>
<li>Demonstrated expertise in Splunk, web traffic analysis, and data visualization.</li>
</ul>

<hr>

<h2>Project Highlights</h2>
<ul>
<li>Designed and developed a comprehensive web traffic analysis dashboard.</li>
<li>Analyzed and visualized web traffic data.</li>
<li>Utilized Splunk for data visualization.</li>
<li>Demonstrated expertise in data visualization and dashboard creation.</li>
</ul>

<hr>

<h2>Analysis of Action Distribution</h2>
<p>The action distribution analysis provides valuable insights into user behavior and demographics. The high traffic from China (3,453) and the United Kingdom (1,349) indicates a strong interest in purchasing products from these regions. The "Purchase" actions from the United Kingdom (151) and China (109) also suggest a high conversion rate from cart additions to purchases.
</p>

<hr>

 <h2>Challenges Encountered</h2>
    <ul>
        <li>Data quality issues: Some of the web traffic data was incomplete or inconsistent, which made it difficult to analyze.</li>
        <li>Time constraints: The project timeline was tight, which made it challenging to complete the analysis and visualization tasks on time.</li>
        <li>Complexity of data interpretation: Interpreting the results of the analysis, particularly distinguishing between legitimate and potentially malicious purchases, was a challenging task.</li>
        <li>Absence of timestamps and date stamps resulted in regulatory violations such as HIPAA.It also leaves conclusions from this project vague and lacking depth</li>
    </ul>

<hr>

<h2>Timestamps included</h2>
<img src="https://i.imgur.com/FFOMKkA.png" alt="Web Traffic Analysis Dashboard Visualization with timestamps">
<p>
  By adding the the timestamps,datestamps and useragent field,we get clearer insights,make recommendations and correlate our findings here with prior findings
  for data enrichment.Lets take one entry from the above as an example.

  01/Apr/2021	06:29:23	88.12.32.208	Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/536.5 (KHTML, like Gecko) Chrome/19.0.1084.46 Safari/536.5	purchase	4

1. Date and Time: 01/Apr/2021 06:29:23 (April 1, 2021, 6:29:23 AM)
2. IP Address: 88.12.32.208
3. User Agent: Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/536.5 (KHTML, like Gecko) Chrome/19.0.1084.46 Safari/536.5
    1. Device: Desktop
    2. Operating System: Windows 7 (64-bit)
    3. Browser: Google Chrome 19.0.1084.46
    4. Browser Engine: WebKit (like Safari)
4. Action: purchase
5. Quantity: 4

 A user from IP address 88.12.32.208 made a purchase on April 1, 2021, at 6:29:23 AM.The user used Google Chrome 19.0.1084.46 on a Windows 7 (64-bit) desktop.
 The purchase quantity was 4 items.After verifying purchase details (order ID, revenue),we found out it was genuine.


<p>Some benefits of the useragent field are highlighted below</p>
  <ul>
    <li>Compatibility testing: Ensure website compatibility with various devices/browsers.</li>
    <li>Error detection: Identify device/browser-specific errors.</li>
    <li> Performance optimization: Optimize website performance for different devices/browsers.</li>
    <li> Bot detection: Identify and filter non-human traffic.</li>
    <li>Spider and crawler detection: Exclude search engine bots.</li>
    <li>Malicious traffic detection: Identify potential security threats.</li>
</li>
  </ul>
  
</p>
<hr>
  <h2>Recommendations</h2>
<ul>
<li>Consider implementing geo-targeted marketing campaigns to cater to the high demand from regions like China and the United Kingdom.</li>
<li>Continuously monitor web traffic data to detect and respond to potential security threats and anomalies.</li>
<li>Implement Geo-IP Blocking: Block traffic from specific countries or regions that are known to be sources of malicious traffic.</li>
<li>Monitor for Denial of Service (DoS) and Distributed Denial of Service (DDoS) Attacks: Regularly monitor web traffic for signs of DoS and DDoS attacks.</li>
<li> Develop an Incident Response Plan: Establish an incident response plan to quickly respond to and contain security incidents.</li>
</ul>
<hr>
<h2>Conclusion</h2>

<p>
      This project has been able to demonstrate and visualise web traffic patterns by users,IP addresses,useragent,etc through a comprehensive dashboard.By uncovering potential anomalies, suspicious logins, and unusual geographic activity, we've highlighted critical areas for investigation and presented our recommendations.
</p>

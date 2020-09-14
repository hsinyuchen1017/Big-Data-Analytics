<div id="readme" class="Box-body readme blob js-code-block-container p-5 p-xl-6 gist-border-0">
    <article class="markdown-body entry-content container-lg" itemprop="text"><h1><a id="user-content-google-analytics-customer-revenue-analysis" class="anchor" aria-hidden="true" href="#google-analytics-customer-revenue-analysis"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Google Analytics Customer Revenue Analysis</h1>
<h2><a id="user-content-table-of-content" class="anchor" aria-hidden="true" href="#table-of-content"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Table of Content</h2>
<ul>
<li><a href="#group-member">Group Member</a></li>
<li><a href="#executive-summary">Executive Summary</a></li>
<li><a href="#introduction">Introduction</a></li>
<li><a href="#exploratory-analysis">Exploratory Analysis</a></li>
<li><a href="#method">Methods</a></li>
<li><a href="#results-and-conclusions">Results and Conclusions</a></li>
<li><a href="#challenges">Challenges</a></li>
<li><a href="#futurework">Future Work</a></li>
<li><a href="#division-of-labor">Division of Labor</a></li>
<li><a href="#takeaways-from-the-course">Takeaways From the Course</a></li>
</ul>
<h2><a id="user-content-group-member" class="anchor" aria-hidden="true" href="#group-member"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Group Member</h2>
<ul>
<li>Zili Bu</li>
<li>Hsin-Yu Chen</li>
<li>Huang-Chin Yen</li>
<li>Kexin Zhang</li>
</ul>
<h2><a id="user-content-executive-summary" class="anchor" aria-hidden="true" href="#executive-summary"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Executive Summary</h2>
<h3><a id="user-content-overview" class="anchor" aria-hidden="true" href="#overview"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Overview</h3>
<p>This is the data we obtained from Kaggle analysis. In this competition, the original challenge was to analyze a Google Merchandise Store (also known as GStore, where Google swag is sold) customer dataset to predict revenue per customer. However, we are planning for some new challenges form this Working with Large Dataset Class.</p>
<h3><a id="user-content-the-problems" class="anchor" aria-hidden="true" href="#the-problems"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>The problems</h3>
<ul>
<li>Can we deal with this large dataset with similar methods as we used in small datasets?</li>
<li>What can we do to our json column?</li>
<li>What model will be appropriate to this certain project?</li>
<li>Should we include all the variables in this dataset to do prediction about total revenues?</li>
</ul>
<h3><a id="user-content-the-solutions" class="anchor" aria-hidden="true" href="#the-solutions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>The solutions</h3>
<ul>
<li>We will use both what we learned in class and also our experience from dealing with small datasets in this project.</li>
<li>We would try to convert the json column into regular data frame. If it does not work, we would delete the column since there are a lot of NAs in it.</li>
<li>We will first try to use linear regression model to fit our data because the dependent variable is numerical. We would also try some model such as XGBoost, Random Forest, and Gradient Boost.</li>
<li>We will make the decision later after we look through the coefficient matrix and the important features.</li>
</ul>
<h2><a id="user-content-introduction" class="anchor" aria-hidden="true" href="#introduction"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Introduction</h2>
<p>We found Google Analytics Customer Revenue Prediction dataset from Kaggle. <a href="https://www.kaggle.com/c/ga-customer-revenue-prediction/overview" rel="nofollow">Dataset Link</a></p>
<p>Our dataset is sources from Google Analytics platform. It contains 12 columns with 4 json format columns with 1708337 rows of data. After the conversion, it has 60 columns instead:</p>
<ul>
<li>bool(1)</li>
<li>int64(4)</li>
<li>object(55))</li>
</ul>
<p>The Column Information</p>
<ul>
<li>fullVisitorId- A unique identifier for each user of the Google Merchandise Store.</li>
<li>channelGrouping - The channel via which the user came to the Store.</li>
<li>date - The date on which the user visited the Store.</li>
<li>device - The specifications for the device used to access the Store.</li>
<li>geoNetwork - This section contains information about the geography of the user.</li>
<li>socialEngagementType - Engagement type, either "Socially Engaged" or "Not Socially Engaged".</li>
<li>totals - This section contains aggregate values across the session.</li>
<li>trafficSource - This section contains information about the Traffic Source from which the session originated.</li>
<li>visitId - An identifier for this session. This is part of the value usually stored as the _utmb cookie. This is only unique to the user. For a completely unique ID, you should use a combination of fullVisitorId and visitId.</li>
<li>visitNumber - The session number for this user. If this is the first session, then this is set to 1.</li>
<li>visitStartTime - The timestamp (expressed as POSIX time).</li>
<li>hits - This row and nested fields are populated for any and all types of hits. Provides a record of all page visits.</li>
<li>customDimensions - This section contains any user-level or session-level custom dimensions that are set for a session. This is a repeated field and has an entry for each dimension that is set.</li>
<li>totals - This set of columns mostly includes high-level aggregate data.</li>
</ul>
<p>As the website introduced, the 80/20 rule is a prevalent rule for many businesses in the real world. It is important to understand our target customers and attract their willingness to purchase the product at Google Store by coordinating proper marketing promotions.</p>
<p>Here are some important business questions:</p>
<ul>
<li>Which region/continent has the highest customers, or highest revenues?</li>
<li>Which type of devices/OS has the highest access?</li>
<li>Which channel group has the highest access or revenues?</li>
<li>Which weekdays, months have the highest access or revenue?</li>
<li>Can we build some models to predict the revenues from our customers?</li>
</ul>
<p>After the initial exploration about our data, we would like to focus our analysis on columns like:</p>
<ul>
<li><code>totals.transactionRevenue</code>: The revenue made from this visit.</li>
<li><code>device.browser</code>: which browser is this visit used.</li>
<li><code>device.deviceCategory</code> : what kind of device is this visit (tablet, mobile or desktop).</li>
<li><code>channelGrouping</code>: The channel via which the user came to the Store. (organic search, display ads, direct, etc.)</li>
<li><code>device.operatingSystem</code>: which operating system is this visit.</li>
</ul>
<h2><a id="user-content-results-and-conclusions" class="anchor" aria-hidden="true" href="#results-and-conclusions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Results and Conclusions</h2>
<ul>
<li>
<p>From our analysis, we found out that total hits and visit hour as well as visit numbers are important features when predicting whether the visitor's total transaction revenue is high or low.</p>
</li>
<li>
<p>In conclusion, in this dataset, majority of the visitors have total hits smaller than 100 and spent more than 10 hours. It is reasonable since most of the people would think twice and browsing around the website before buying items online. Moreover, most of the visitors who spend higher are not in the first session. It might because visitors who spend more have already been through the website before or have already browsing around the website many time before making transaction.</p>
</li>
<li>
<p>We randomly split the data into train and test sets. We utilize test accuracy or test error to evaluate our model performance.</p>
</li>
</ul>
<h2><a id="user-content-challenges" class="anchor" aria-hidden="true" href="#challenges"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Challenges</h2>
<ol>
<li>
<p>The very first challenge is how to handle with these json type columns in our csv file. Fortunately, we find a code provided by another analyst in Kaggle to help us transform our data. <a href="https://www.kaggle.com/julian3833/1-quick-start-read-csv-and-flatten-json-fields" rel="nofollow">reference</a> However, the kernel failed everytime we convert the json column, therefore, we finish the conversion on local machine and save the converted file into S3 for further analysis.</p>
</li>
<li>
<p>The introduction of this dataset on Kaggle.com is not very clear. Therefore, we need to spend some time on the internet to look into the dataset to understand the meaning of each column, especially those new columns converted from json.</p>
</li>
<li>
<p>We have a very large dataset, and it takes a long time to process (the kernel even died several times) . Therefore, we use a smaller sample of our original dataset to ensure the correctness of our code. After that, we apply all the code on the larger dataset to save our time.</p>
</li>
<li>
<p>The json columns after conversion have a period in the column name, which hinder our <code>spark.sql</code> command later on. Then we realize that we need to use a back quote symbol to quote those column names to perform sql command.</p>
</li>
<li>
<p>Column <code>totals.transactionRevenue</code> has a lot of null value after converted from json, we have to fill all the null value with zero since it means they do not conduct any transactions through these visits.</p>
</li>
<li>
<p>Our dataset contains many null values and most of the features are categorical, and even many numerical features are constant value, which is challenging for model building. After cleaning up the null value and label the categorical feature, our model accuracy enhanced from <strong>28%</strong> to <strong>54%</strong>.</p>
</li>
<li>
<p>Most of the value in our original target prediction "total.transactionrevenue" are 0, which is somehow meaningless for prediction. Therefore, instead of building regression models, we split the revenue into three classes and build <code>classifier models</code> for predictions.</p>
</li>
</ol>
<h2><a id="user-content-future-work" class="anchor" aria-hidden="true" href="#future-work"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Future Work</h2>
<ol>
<li>
<p>We do not have much information about the <code>groupchannels</code> (what are their differences, their return on investment, etc). If we could have more data about these channels, we can evaluate which social platform or referral methods generates more vitis to Gstore. As a result, we can reallocate the resources to different social and referral channels to optimize the results. For example, to improve the poor performing ones or to expand the size of the good perfoming ones.</p>
</li>
<li>
<p>Our model of the classifying level of revenue of customers has a best accuracy <strong>54%</strong>, which remains a lot of space for improvement. Instead of directly deleting the null value and constant data, we can try to gather more information and take more references to better deal with those missing values, which might enhanced model prediction by considering those deleted features. Also, instead of labelizing categorical variables, we may try one-hot-encoding method to check whether it is better.</p>
</li>
</ol>
<h2><a id="user-content-division-of-labor" class="anchor" aria-hidden="true" href="#division-of-labor"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Division of Labor</h2>
<ul>
<li>Zili Bu and Huang-Chin Yen focus on the Introductions, Data Source, Data Preparation and clean, and Exploratory Analysis</li>
<li>Hsin-Yu Chen and Kexin Zhang focus on building Models, Executive Summary.</li>
<li>Then we are contributed into the Challenges, Takeaways, Results together.</li>
</ul>
<h2><a id="user-content-takeaways-from-the-course" class="anchor" aria-hidden="true" href="#takeaways-from-the-course"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Takeaways From the Course</h2>
<ul>
<li>We are able to get familiar with <strong>github</strong>, for example, how to connect github, create and clone repositories, and how to update our work to a repo in github. Meanwhile, we also benefit from the github's ability to record the history(changes) of each commits we made.</li>
<li>The practise of <strong>regular express</strong> help us to extract desired string from certain text files.</li>
<li>The experience to work with AWS platform is great. We learned how to properly connect to a virtual machine, and navigate through our virtual machine and extract informations about our files on<code>HDFS</code> or <code>S3</code> file system via shell command.</li>
<li>We get a brief introduction on <code>map</code> and <code>reduce</code> function when we dealing with large size of data in the real world. Meanwhile, we also experience the power of the parallized computations in clusters on how to increase the speed of processing tasks.</li>
<li>Establish a spark environment to run <code>spark.sql</code> command directly in python (juypter notebook)</li>
<li>When using spark dataframe, we realize the <code>.cache()</code> method could save the dataframe into memory so that we are able to save a lot of time to run sql command towards that spark dataframe, especially with such a large size of data.</li>
<li>Build machine learning models through pipeline.</li>
</ul>
</article>
  </div>

    </div>

  


  <details class="details-reset details-overlay details-overlay-dark" id="jumpto-line-details-dialog">
    <summary data-hotkey="l" aria-label="Jump to line"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast linejump" aria-label="Jump to line">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-jump-to-line-form Box-body d-flex" action="" accept-charset="UTF-8" method="get">
        <input class="form-control flex-auto mr-3 linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
        <button type="submit" class="btn" data-close-dialog>Go</button>
</form>    </details-dialog>
  </details>




  </div>
</div>

    </main>
  </div>

  </div>

        
<div class="footer container-xl width-full p-responsive" role="contentinfo">
  <div class="position-relative d-flex flex-row-reverse flex-lg-row flex-wrap flex-lg-nowrap flex-justify-center flex-lg-justify-between pt-6 pb-2 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
      <li class="mr-3 mr-lg-0">&copy; 2020 GitHub, Inc.</li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to terms, text:terms" href="https://github.com/site/terms">Terms</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to privacy, text:privacy" href="https://github.com/site/privacy">Privacy</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to security, text:security" href="https://github.com/security">Security</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://githubstatus.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a data-ga-click="Footer, go to help, text:help" href="https://docs.github.com">Help</a></li>

    </ul>

    <a aria-label="Homepage" title="GitHub" class="footer-octicon d-none d-lg-block mx-lg-4" href="https://github.com">
      <svg height="24" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="24" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path></svg>
</a>
   <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to contact, text:contact" href="https://github.com/contact">Contact GitHub</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.com/pricing" data-ga-click="Footer, go to Pricing, text:Pricing">Pricing</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://docs.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://services.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About</a></li>
    </ul>
  </div>
  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 text-gray-light"></span>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.22 1.754a.25.25 0 00-.44 0L1.698 13.132a.25.25 0 00.22.368h12.164a.25.25 0 00.22-.368L8.22 1.754zm-1.763-.707c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0114.082 15H1.918a1.75 1.75 0 01-1.543-2.575L6.457 1.047zM9 11a1 1 0 11-2 0 1 1 0 012 0zm-.25-5.25a.75.75 0 00-1.5 0v2.5a.75.75 0 001.5 0v-2.5z"></path></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg class="octicon octicon-x" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M3.72 3.72a.75.75 0 011.06 0L8 6.94l3.22-3.22a.75.75 0 111.06 1.06L9.06 8l3.22 3.22a.75.75 0 11-1.06 1.06L8 9.06l-3.22 3.22a.75.75 0 01-1.06-1.06L6.94 8 3.72 4.78a.75.75 0 010-1.06z"></path></svg>
    </button>
    You can’t perform that action at this time.
  </div>


    <script crossorigin="anonymous" async="async" integrity="sha512-bn/3rKJzBl2H64K38R8KaVcT26vKK7BJQC59lwYc+9fjlHzmy0fwh+hzBtsgTdhIi13dxjzNKWhdSN8WTM9qUw==" type="application/javascript" id="js-conditional-compat" data-src="https://github.githubassets.com/assets/compat-bootstrap-6e7ff7ac.js"></script>
    <script crossorigin="anonymous" integrity="sha512-CxjaMepCmi+z0LTeztU2S8qGD25LyHD6j9t0RSPevy63trFWJVwUM6ipAVLgtpMBBgZ53wq8JPkSeQ6ruaZL2w==" type="application/javascript" src="https://github.githubassets.com/assets/environment-bootstrap-0b18da31.js"></script>
    <script crossorigin="anonymous" async="async" integrity="sha512-qNG6dHHR6Fjppk1MAW2Wi83aW43n9UnpdlyCTMs4Th8tZCnzXmrNdicussOgdWWz+fBEGFggfQT4LnbTDugm8g==" type="application/javascript" src="https://github.githubassets.com/assets/vendor-a8d1ba74.js"></script>
    <script crossorigin="anonymous" async="async" integrity="sha512-MwOFiWexKpAMFmQ1R8v6hGSRpL7x83omQEqm1bArRTfitE/iwmdz68FuRq+tICbWGAlPx1pii5sNwhKne1M7bw==" type="application/javascript" src="https://github.githubassets.com/assets/frameworks-33038589.js"></script>
    
    <script crossorigin="anonymous" async="async" integrity="sha512-1dM4oK6pDsTBrlDwOjYXiv6LcMB4imnsvYLE/+k/AdFLIoUA33MkhUGC8s6abCBwySqj6RcVVSV63lAvlkGIWQ==" type="application/javascript" src="https://github.githubassets.com/assets/behaviors-bootstrap-d5d338a0.js"></script>
    
      <script crossorigin="anonymous" async="async" integrity="sha512-44qssMj+fXq3KdFy9Xwq1xbyF9+0lUDA4T8YID97FKD+j18CEaDsPGutuPP3frQFBwcikEViAK+3cFq5MzmQCg==" type="application/javascript" data-module-id="./contributions-spider-graph.js" data-src="https://github.githubassets.com/assets/contributions-spider-graph-e38aacb0.js"></script>
      <script crossorigin="anonymous" async="async" integrity="sha512-EOcKJC66ZRh9HbNcX4OaUtWMBVt6SEC3qOFS0QOam5vJQ1OD1sdHNk/Pns/CboOmqzrtBDObn7Cj06879tEsog==" type="application/javascript" data-module-id="./drag-drop.js" data-src="https://github.githubassets.com/assets/drag-drop-10e70a24.js"></script>
      <script crossorigin="anonymous" async="async" integrity="sha512-Ih1K+uJKIIjmm3N1q1OppWuDEGnElhMbAhGxf9n48DoxomSE7OPAGXNMQ5LB8WalcKjOQZJVUFOX7QrHy2URkA==" type="application/javascript" data-module-id="./jump-to.js" data-src="https://github.githubassets.com/assets/jump-to-221d4afa.js"></script>
      <script crossorigin="anonymous" async="async" integrity="sha512-HzWUeLy0p20M4Lc3+EerTwy/VaH3vMuKLvhFJr0PsJfKXnsD9oy5SfashhxStUirglhYZUB4fLYQRM1uzrFyNg==" type="application/javascript" data-module-id="./profile-pins-element.js" data-src="https://github.githubassets.com/assets/profile-pins-element-1f359478.js"></script>
      <script crossorigin="anonymous" async="async" integrity="sha512-qECv/jhsvLFN77eGNu0cjMR2+zvAlLyhQVTnmayJc5OLZoxMLjQZxZW1hK/dhcYro6Wec/aiF21HYf2N5OilYQ==" type="application/javascript" data-module-id="./randomColor.js" data-src="https://github.githubassets.com/assets/randomColor-a840affe.js"></script>
      <script crossorigin="anonymous" async="async" integrity="sha512-vK7rRnsAi4qcmC2HqCfPyEBZgIMWb6Azyb1PJxgL1FtEFMydK//dsnuLdVx+RaPGg71Z58ossFXqkLWgMevvdw==" type="application/javascript" data-module-id="./sortable-behavior.js" data-src="https://github.githubassets.com/assets/sortable-behavior-bcaeeb46.js"></script>
      <script crossorigin="anonymous" async="async" integrity="sha512-mHqsE5aQq7fAmmLd0epHBJK8rn8DOVnjW2YQOT8wvsN1oLrypw0cDFmwXPDwbMghHyo4kKiOtVJ/kEsEzwwibw==" type="application/javascript" data-module-id="./tweetsodium.js" data-src="https://github.githubassets.com/assets/tweetsodium-987aac13.js"></script>
      <script crossorigin="anonymous" async="async" integrity="sha512-+QfOLG8ES1hxkJ+lK3yX/qtYw+eNEa/t8M/3m/q/A9gu+9SJzObmbDEQLv2hiDBYx3OFx9G1a7DrxQtD5cdhEQ==" type="application/javascript" data-module-id="./user-status-submit.js" data-src="https://github.githubassets.com/assets/user-status-submit-f907ce2c.js"></script>
    
    <script crossorigin="anonymous" async="async" integrity="sha512-xHEP9r2UXQWzkpa1OgHb5mbRzyiMdyQ0YVkxYjr5Xy/lAveQ1elRngSfvFGupKyIQxoMLnvG15ZC4jeus7TAAQ==" type="application/javascript" src="https://github.githubassets.com/assets/repositories-bootstrap-c4710ff6.js"></script>
<script crossorigin="anonymous" async="async" integrity="sha512-fLmwfnkET+1RjTY2z0N13tAGGa2GjZACBr/GBIERRJuQIEKkKDIU5cniUOFbznA814vRvr91uB9UsLk3ujnZjw==" type="application/javascript" src="https://github.githubassets.com/assets/github-bootstrap-7cb9b07e.js"></script>
  <div class="js-stale-session-flash flash flash-warn flash-banner" hidden
    >
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.22 1.754a.25.25 0 00-.44 0L1.698 13.132a.25.25 0 00.22.368h12.164a.25.25 0 00.22-.368L8.22 1.754zm-1.763-.707c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0114.082 15H1.918a1.75 1.75 0 01-1.543-2.575L6.457 1.047zM9 11a1 1 0 11-2 0 1 1 0 012 0zm-.25-5.25a.75.75 0 00-1.5 0v2.5a.75.75 0 001.5 0v-2.5z"></path></svg>
    <span class="js-stale-session-flash-signed-in" hidden>You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="js-stale-session-flash-signed-out" hidden>You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <template id="site-details-dialog">
  <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark hx_rsm" open>
    <summary role="button" aria-label="Close dialog"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast hx_rsm-dialog hx_rsm-modal">
      <button class="Box-btn-octicon m-0 btn-octicon position-absolute right-0 top-0" type="button" aria-label="Close dialog" data-close-dialog>
        <svg class="octicon octicon-x" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M3.72 3.72a.75.75 0 011.06 0L8 6.94l3.22-3.22a.75.75 0 111.06 1.06L9.06 8l3.22 3.22a.75.75 0 11-1.06 1.06L8 9.06l-3.22 3.22a.75.75 0 01-1.06-1.06L6.94 8 3.72 4.78a.75.75 0 010-1.06z"></path></svg>
      </button>
      <div class="octocat-spinner my-6 js-details-dialog-spinner"></div>
    </details-dialog>
  </details>
</template>

  <div class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;" tabindex="0">
  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box box-shadow-large" style="width:360px;">
  </div>
</div>


  </body>
</html>


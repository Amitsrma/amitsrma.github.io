---
layout: analytics_page
title: About
permalink: /about/
---
<ul>
      <b>
        <li>Education</li>
      </b>
      <ul>
        <li>Systems Science, Masters, 2019, University of Ottawa</li>
        <li>Bachelors of Engineering, 2015, Institute of Engineering, Tribhuwan University, Nepal</li>
      </ul>
    </ul>

I am a Data Analyst and Data Engineer with Masters in Systems Science, with focus on Data Science and Statistics. I like solving problems and I love playing with data. I am an evidence driven insightful person who is passionate about working in cross-functional team. I have strong foundation in Data Mining, Data Analysis, analysis tools like Tableau, R and hands-on skills with Python and its Data Analysis libraries.<br><br>
I like the idea that we can measure correlation of the major events of system with other seemingly in-significant ones and make predictions about event of interest through those seemingly in-significant event. I am fascinated by the application of data to solve problems/challenges. For example, pairing the data from sensors to check tire pressure with the google map's location information can give information on location of pot holes. The correlation being, pot holes cause spike in tire pressure, as vehicle moves through them.

<h3>CURRENT PROJECTS</h3>


<ul>
    <li> <b>News Summarizer</b> Feb 2020 – Present 
    <br>
    <a href="https://github.com/Amitsrma/Scrapy-Django-NewsScraper" target="_blank">
    <code>GitHub Link</code>
    </a>
    </li>
    While using Bloomberg terminal and checking news on seekingalpha, I would see new news automatically updated.
    My curiosity about how one might go about designing a system that reconciles news from multiple sources made me start
    and complete the project. The challenge for me at the point was to bring multiple framework to write information to same database without conflict.<br>
    After accomplishing the above, I realized that some news are long and it takes a long time to understand what the whole body of text is
    saying. So I started thinking about how fast you could understand the news, just by reading couple lines. Can we properly summarize the text?
    <br>
    <ol>
    <li>
    Designed a Scrapy framework to collect news from hackernews. Scrapy will start by going in 14 page deep and keep scanning first page for new news being added.
    </li>
    <li>
    Designed a django server connected with a database. Connected this database with Scrapy. Scrapy spiders scrape the webpages and pass it to
    django database via django models through scrapy pipeline.
    </li>
    <li>
    Made REST api to access all news scraped until the point in time.
    </li>
    <li>
    Designed a page that will take in a query and return a set of news that are relevant to those query. Relevant news items are
    selected through keyword matching. This page also shows bar chart of most occuring words in the news of result set.
    </li>
    </ol>
    Coronavirus pandemic was just starting and I was filtering the news with respect to coronavirus keyword. I could see the evolution of news items discussing about spread of infection to
    increasing deaths to economic meltdown to discussion on possible drugs for covid. Right now I am looking forward to use pretrained BERT for showing summary of the news items collected.
</ul>



<h3><b>EXPERIENCE</b></h3>

<ul>
<li><b>Preventive Maintenance Engineer at Government of Nepal, <a href="http://dohslmd.gov.np/web/en/" target="_blank" >Department of Health Services, Logistics Management Division</a><span class="w3-opacity"> from July 2016 - June 2018</span></b></li>
<ol>
<li>Prepared cost estimates of vehicle repair using current market valuation of the parts for The Secretary of
Ministry of Health and Directors and Auditors at Department of Health Services.
</li>
<li>Prepared specification and cost estimates of vehicle to be purchased through competitive bidding.
</li>
<li>Completed size requirement analysis and specification design from scratch for competitive bidding of
Refrigeration Truck to transport vaccine.</li>
</ol>
<li><b>CAD and Systems Engineer at <a href="https://e-et-t.com/" target="_blank" >E&T Pvt Ltd</a><span class="w3-opacity"> from Nov 2015 - Apr 2016</span></b></li>
<ol>
<li>Development of solid model in CATIA.</li>
<li>Preliminary study for the flow of air in the intake manifold of engine.</li>
</ol>
</ul>

<h3>PROJECTS</h3>

<ul>
<li> <b>
Automatic Identification of Inventive Concepts of Patent Documents (Bell Advanced Research Lab)
</b> Jun 2019 – Dec 2019 </li>
    This is a project I did under supervision of Professor Tet Yeap.
    <ol>
    <li>Completed unsupervised classification of text documents using LDA, NNMF and LSA algorithms.</li>
    <li>Used nltk, gensim and spacy for feature engineering and validating the model to decide which
    algorithm to adopt.</li>
    <li>Automated data extraction from website, using python’s bs4 and requests libraries. Extracted text
    is used for training and testing.</li>
    <li>Automated data extraction from xml files of size over 600MB. Data extracted through webscraping was noisy
    and classification criteria could not be set in concrete by text extraction through web scrapping.
    Used xml library with assumption that quadratic blowup would not occur since USPTO's bulkdata was used.</li>
    </ol>
<li><b>User privacy Problems in Data Mining</b></li>
<ol>
    <li>
    Working on understanding underying mechanisms in the notion of privacy in a data set, some of them are scrubbing 
    data for Anonymity, Randomization on result of Query to Database and Secure Multi-party Computation.
    </li>
    <li>
    Working on understanding and creating a framework for Differential Privacy.
    </li>
</ol>
<li><b>
    <a target="_blank" href="https://github.com/Amitsrma/sentiment_analysis-User_server_interaction-using-django-python">
    Sentiment classification using Bag-of-Words model
    </a></b>
</li>
    <ol>
    <li> Made a sentiment classification system using tensorflow and Django. Model would be generated based on a set of
        training data categorizing a specific sentiment class.</li>
    <li>Learned about feature engineering, tensorflow, system integration.</li>
    <li>Working on the raw data just by converting text to uniform lower case and removing unnecessary punctuation
        gave accuracy of around 60%. Through feature engineering .i.e. by cleaning data by correct understanding of
        what has an effect on the system and what information could be ignored, accuracy was improved to 83%. </li>
    </ol>
<li>
    <a target="_blank" href="https://github.com/Amitsrma/Convolution-Neural-Network-DogsVsCats_Classification">
    <b>Using Convolutional Neural Network for image classification</b>
    </a>
    <ol>
    <li>This was a part of <a target="_blank" href="https://www.kaggle.com/c/dogs-vs-cats/overview">kaggle competition</a> that aimed at
        being able to differentiate between images of dogs and cats.</li>
    <li>Understood convolutional neural network, learned to set it up in tensorflow. </li>
    </ol>
</li>




<h3>ONLINE COURSES</h3>

<ul>
<li>
    <a target="_blank" href="https://www.edx.org/course/machine-learning-with-python-from-linear-models-to-deep-learning-3">
        6.86x</a>: Machine Learning with Python-From Linear Models to Deep Learning
    <a target="_blank" href="https://courses.edx.org/certificates/439d520a49bd46b2b06e5bdb02800a10">
        <code>Certificate Link</code>
    </a>
</li>
<li>
    Spark for Machine Learning & AI.
    <a target="_blank" href="/Image/CertificateOfCompletion_Spark For Machine Learning Ai.pdf">
        <code>Certificate Link</code>
    </a>
</li>
<li>
    <a target="_blank" href="https://www.bloomberg.com/professional/product/bloomberg-market-concepts/">
        BMC</a>: Bloomberg Market Concepts
    <a target="_blank" href="/Image/BMC_certificate_of_completion.pdf">
        <code>Certificate Link</code>
    </a>
</li>
<li>
    Introduction to TensorFlow for Artificial Intelligence, Machine Learning, and Deep Learning.
    <a target="_blank" href="https://www.coursera.org/account/accomplishments/certificate/8HRDY4ACTGTQ">
        <code>Certificate Link</code>
    </a>
</li>
    <li> <a target="_blank" href="https://www.edx.org/course/6-00-1x-introduction-to-computer-science-and-programming-using-python-3">
    6.00.1x</a>: Introduction to Computer Science and Programming Using Python
    <a target="_blank" href="https://courses.edx.org/certificates/626c4350be494c1f9905f15cf5d3646a">
        <code>Certificate Link</code>
    </a>
    </li>
    <li>
    <a target="_blank" href="https://www.edx.org/course/introduction-to-computational-thinking-and-data-science-2">
    6.00.2x</a>: Introduction to Computational Thinking and Data Science</a>
    <code>Certificate Link</code>
    </li>
    <li> <a target="_blank" href="https://www.coursera.org/learn/game-theory-2">
    Game Theory II</a>: Advanced Applications
    <a target="_blank" href="/Image/Coursera_Certificate_v1-97600816044654.pdf">
        <code>Certificate Link</code>
    </a>
    </li>
    <li>Microeconomics: The Power of Markets.
    <a target="_blank" href="https://www.coursera.org/account/accomplishments/certificate/4GU3H58KNLCC"> <code>Certificate Link</code></a></li>
</ul>

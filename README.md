# Classifying Twitter

## Motivation 
Twitter is a rich ecosystem. Even with the constraint of 14 characters allotted per tweet, people have no problem expressing emotions, opinions, and facts. So it comes as no surprise that there is an endless amount of opportunities to learn from it. Apposphere has done exactly that!

## Apposphere
Apposphere is a start-up based here in Austin that focuses on extracting business leads from Twitter and delivering them to their clients. Once these leads are delivered, businesses have the option to strike up conversations in however way they please.

The success rate is astounding at over 70%. This makes Aingine, their AI system, much more desirable than PCP ads, which can be elusive and expensive.

## Motivation 

My capstone projects aims to classify tweets into leads. Each tweet will be scored from cold to hot on a scale of 0-4.

## Data

The tweets came from a Twitter API, which was stored in Apposphere's MySQL database. At the start of the project, it had over 2.8 million tweets. For my project, I used a random sample of 150,000.

<p align="center">
    <a href="https://plot.ly/~EarlynR/44/?share_key=VQ8HBNmkVLBBYrxYE6fxdd" target="_blank" title="plot from API (15)" style="display: block; text-align: center;"><img src="https://plot.ly/~EarlynR/44.png?share_key=VQ8HBNmkVLBBYrxYE6fxdd" alt="plot from API (15)" style="max-width: 100%; width: 600px;" width="600" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="EarlynR:44" sharekey-plotly="VQ8HBNmkVLBBYrxYE6fxdd" src="https://plot.ly/embed.js" async></script>
</p>


## Feature Engineering

There are numerous ways to include text into your model, and I took full advantage of that. I used simple bag of words (CBOW) matrices, term frequency-inverse document frequency (Tf-IDF) matrices, and doc2vecs.

<p align="center">
 <img src="images/feature_engineering/feature_engineering.001.jpeg">
</p>


## Models

I tested five models, starting from the most basic Logistic Regression model to the most complicated Fasttext model. For each model, I used the different features to make sure that I chose the best one.

## Results

Please come to my capstone presentation and see for yourself!

## Future Plans 
Though I have done a lot for this project, I feel like I am nowhere near done. The possibilities are endless in trying to make this better. However, in the immediate future, my model will be deployed and used in production.

## Appendix 

### Dependencies
<p align="center">
 <img src="images/dependencies.jpg">
</p>


<h1>Project_One:  Berlin Airbnb Data </h1>
<h2>Project Overview</h2>
<p>This project is part of Udacity's Data Science Nanodegree. This project aims to create a blog post and Github repository to
begin building a data science portfolio of my own. For that, I choose Kaggle's Berlin Airbnb Data and
followed the CRISP-DM process to conduct my analyze.</p>
<h2>Installation and libraries</h2>
  The csv file, listings_summary, used on this project can be found on this link: https://www.kaggle.com/brittabettendorf/berlin-airbnb-data. The existence of this file on the directory of this project is fundamental to its execution. The python version used is 3.6.
  <p> Python Packages used in the project: </p>
<ul>
<li>NumPy</li>
<li>Pandas</li>
<li>Scikit-learn</li>
<li>matplotlib</li>
</ul>
<h2>Project Motivation</h2>
<p>The motivation for this project was to answer the questions below:
<ul>
  <li> 1. Do the neighborhoods with more listings have a lower average price? </li> 
  <li> 2. What the correlation between neighborhoods, reviews and price?</li>
  <li> 3. The distance of listing from the Berlin's downtown is directly related to the price? What about number of reviews?</li>
  <li> 4. Can you predict the price of Berlin's listings?</li>
</ul>
<h2>Repository Contents</h2>
  <p>This repo contains:</p>
    <ul>
      <li>/notebook:  ipynb file used to EDA + modeling  </li>
      <li>/src:  py file used to create functions  </li>
    </ul>
<h2>Results</h2>
  <p>Questions 1, 2, and 3 were not possible to get clear results, because most of the analysis was inconclusive. But it was possible to ensure that the closest the listings are, the higher number of reviews. And there is a direct relation between neighborhoods with a high number of listings and neighborhoods with a high number of reviews. The 5 neighborhoods with more reviews: Prenzlauer Berg, Mitte, Kreuzberg, Neukölln, Friedrichshain are the top 5 with more listings, which means, they have a more accurate average prices, as we told before. But we can't say that more reviews per neighborhood have a higher or lower price compared to the average price.</p>
  <p>In the end, was made a price prediction using Linear Regression and calculated the most influential coefficients on the model by providing the coefficient estimates along with the name of the variable attached to the coefficient.</p>


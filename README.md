<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <h2>Lights, Camera, Prediction – Blockbusters and Oscar Baits</h2>
</head>
<body>
    <h3>Introduction:</h3>
    <p>Lights, Camera, Prediction – Blockbusters and Oscar Baits. Rolling out the red carpet for data science, this project’s mission is to direct a star-studded predictive model that outshines the competition in forecasting both box office revenues and movie scores for 2023's feature presentations.</p>
    <p>In the quest to become the Quentin Tarantino of data-driven insights, I’ll scrape the IMDB website from studio bigwigs to indie auteurs– and extract any possible features in my way to build the most detailed dataset the industry has seen. By fine tuning the model like an obsessive method actor; we’ll learn what makes a good movie tick, and a bad movie stink!</p>
    <h2>Mission statement:</h2>
<p>The aim of this project is to meticulously extract data from the IMDb website for all films released between 2018 and 2022, and pair it with the biographies of the actors, writers, and directors involved, ultimately consolidating it into a comprehensive dataset.</p>
<p>Utilizing the dataset, the following Hypotheses will be investigated:</p>

<h3>Hypothesis A:</h3>
<p>By fine-tune various prediction model, the extracted features will be able and accurately forecast the following outcomes for any future film release:</p>
<ul>
    <li>Opening Week Revenue (In US)</li>
    <li>Total Gross Revenue (In US)</li>
    <li>Critic Meta Score</li>
    <li>User Rating</li>
</ul>

<h3>Hypothesis B:</h3>
<p>Critic vs. Audience rating. In the last few years there has been a divide between the audience and the professional movie critics when it comes to movie scores.</p>
<p>By examining feature importance, this project intends to test the claim that audience and critics score relies on entirely different features, and discuss the differences between the two dependents.</p>

<h3>Hypothesis C:</h3>
<p>The “Wokeness” effect. There has been a growing resentment among movie-goers fandom towards production studios that put emphasis on representation and diversity before a good storytelling.</p>
<p>The claim is that movies that are too heavily based on women empowerment and LGBTQ+ representation are alienating their audience and are damaging the user rating, and much as the movie’s revenue. This project hopes to examine this claim and see if there is indeed a correlation between number of women and LGBTQ+ members in a movie production to its bottom line.</p>

<h2>Data Scraping:</h2>
<p>Perhaps the most challenging part of the project. With the outdated html structure IMDB was built in, there was a need for a powerful library that could tackle this task. The Python ‘BeautifulSoup’ library was selected and combined with an API call containing an IMDB search query URL.</p>
<p>The query set the desired population as Feature Films created in 2022 in United States. Please note that due to major missing data discovered in the scrapping stages, additional search filters needed to be set, such as: A minimum of 1,000 movie reviews and an existing user rating. This helped reduced low-effort films with non-reliant /

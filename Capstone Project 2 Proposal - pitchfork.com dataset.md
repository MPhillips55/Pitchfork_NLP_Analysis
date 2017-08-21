# Capstone Project 2 - Pitchfork Dataset
## Michael Phillips

### 1. What is the problem you want to solve?

Pitchfork is one of the most influential music news and review sites currently in operation. Launched in 1995, the site has 
slowly grew over the years into the industry powerhouse it is today. Musical acts can achieve overnight success with a 
positive Pitchfork review. This very phenemona has happened time after time. Bands like Arcade Fire, The National, and 
Deafheaven have all benefitted from the Pitchfork 'bump'. 

Making money on the internet is tough, especially with the prevalence of ad-blockers, so I aim to leverage one of
Pitchfork's biggest assets: their massive review archive. I envision licensing this archive to a streaming 
music platform such as Spotify. What the Spotify user would do is type a question into the app such as, "What are some
other bands that sound like Bruce Springsteen?" NLP techniques could be used to 'learn' the Pitchfork archive and 
provide answers to this and many other questions.

### 2. Who is your client and why do they care about this problem?

I envision my client being the Pitchfork leadership team. Providing a significant source of additional income would be
the main benefit I would be aiming to provide. I'm sure Pitchfork is doing fine financially, but running the site is 
probably not cheap and providing a way to make money off reviews that do not generate much traffic anymore would either
provide additional financial freedom, or the ability for the site to expand to other areas they may have wanted to explore.

Based on my analysis and proposal the Pitchfork team would have to decide whether or not to follow-up with streaming
music platforms and explore licensing the review archive.

### 3. What data are you going to use?

The Pitchfork review archive was acquired from a public Kaggle repo that was compiled by a Kaggle user. It is
complete up until early 2017 when the repo was posted.

### 4. Outline your approach to solving this problem?

I plan to use some of the Python NLP packages such as spaCy, LDA, word2vec, and likely visualization libraries like 
pyLDAvis. I will need to do further research on capabilities of these libraries which is one of my personal goals for
this project - to become more aware of and fluent with modern NLP techniques.

### 5. What are your deliverables?

I plan on delivering an EDA notebook with a basic look at the breadth and scope of the dataset completed using Pandas, 
a more general NLP exploration notebook where I train a model and see what kinds of questions I can answer with it, 
and a final 'presentation' notebook that could be used to present to the stakeholders and to make my case for moving
forward with the proposed licensing of the database. A Tableau slidedeck will accompony the final notebook and provide
further explanation for what I make.

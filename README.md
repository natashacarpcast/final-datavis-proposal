# Data Visualization - Final Project Proposal

This repository contains an updated visual portfolio proposal for exploring the topic of the moralization of self improvement. 

## Research Questions

1) To what degree is moral language present when talking about self improvement?
2) Are there some specific topics within self improvement discussions that tend to be discussed with a higher moral tone?
3) How does the usage of moral language associate with different emotions in the context of self-improvement?

## Data 

Submissions and comments from the subreddit r/selfimprovement were analyzed to obtain topics on the corpus and scores of moralization language. The data and a more detailed explanation are available in the [data folder](data).

put moralbert
and all data

## Proposal

I intend to build on the work from previous assignments and add some new plots. The final deliverable I envision is a website where the user can navigate through the three research questions and have a separate page for each of them. 

### Page 1 - To what degree is moral language present when talking about self improvement?

[SCREENSHOT]

For exploring this question I want to reuse the plots from the Tableau assignment, which showcase the difference in morality scores across 3 subreddits. Additionally, I want to add a new similar plot which corresponds to a new measure of morality (MoralBERT), so I can show the similarities and differences across the three ways of measurement. I'm still unsure on what's the best way to organize them/display on the page but the idea is for it to be something like above. The goal is to show that the self improvement subreddit shows higher values of morality consistently with different types of measures. 

### Page 2 - Are there some specific topics within self improvement discussions that tend to be discussed with a higher moral tone?


[EMBEDDED OF TOPICS]

<div class='tableauPlaceholder' id='viz1740186577357' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;to&#47;topics_exploration&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='topics_exploration&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;to&#47;topics_exploration&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1740186577357');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='727px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>



[Alternative link if embedded visualization does not work](https://public.tableau.com/app/profile/natasha.carpio.castellanos/viz/topics_exploration/Dashboard1?publish=yes)

Although on my initial proposal suggested using bar plots for showing the distribution of topics, I believe I already have too many bar plots and this is one place where I can sacrifice them and use something more visually engagement. I'm thinking on bubble charts just to show a very vague idea of the proportions and allow the user to hover to get the total percentage of the corpus (and maybe some example documents?). In the end, the proportions are not the most important thing but they serve as an introduction to the topics for the subsequent graphs.

In the same page, I want to display an interactive graph that allows the user to move from one moral dimension to another and visualize how different topics score in each dimension. Above you could see an example of the sanctity dimension but the idea will be to move from dimension to dimension. 


### Page 3 - How does the usage of moral language associate with different emotions in the context of self-improvement?


[SCREENSHOT 3] 

For this question, I want to reuse the plot from Assignment 3 where the reader can visualize that moral language is not related to negative emotion, but rather the topics are the ones that relate to the emotional tone of the content. Aditionally, I want to expand by adding a new plot (per topic) where the user can visualize the connotation of a word on a given topic, using the positive emotion and negative emotion scores as x and y axis. The idea is to show which words are mostly used on a positive context vs which ones on a negative context. This allows for a nuanced overview of the specific words used in moral language and how they differ by topic. The idea is that the user can move from topic to topic and see the top 10-20 moral words used in the given topic and their connotations. 







## SERP and Landing Page Conversion Rate

**Description:** This illustration examines the organic search performances across landing pages.  By combining SERP data on Search Console and data from Google Analytics and using landing page as the joining key, we can evaluate the performance of different aspects in SEO and their corresponding product-side performances.  The following examples illustrates some of the practical uses of the data including:
Evaluate how certain features may impact on SEO performance
Map out movement of Search Rank between dates
Locate high conversion potentials landing pages

### 1. Basic ETL

Tools we are using here include BigQuery and Tableau.  Search Console does not have its own built in data transfer to BigQuery, however a python script and Cloud Scheduler could easily fulfill the job without costing you more than a penny.  This also allows us to look into SERP data by day hence we can monitor changes of metric within a given period of time.  


### 2. The impact of pop-up ad on SEO

<img src="images/seo_rank_difference?raw=true"/>

The evaluation here is to look at how pop-up ad have impacted on the SEO performance.  Position here uses Search Console default explanation therefore a rises in position is a decreases in rank in SERP.  The use of differences in positions compare to previous week here illustrate the impact on changes better but it also hinders the ability to show trends.  
The implementation of the pop-up ad is at around late W36 and the removal in late W38.  There are certainly some other factors affecting the SERP position including natural rises and drops depends on how competitors perform.  Fluctuations immediately between weeks however should normally be small, so we'd expect the majority hugging around the 0.  
Here we observe rises of SERP positions in nearly all of the page cateogries in W37, espcially the big movers, and the subsequent slight imporvement when the ad withdrew.  

<img src="images/rank_difference_table_blur.png?raw=true"/>
Breaking down in numbers, we see 8 page categories that have more than 1 increase in rank in W36 with an average of 1.81.  Most categories have yet to recover from the shock within the observation period.




### 3. Support the selection of appropriate statistical tools and techniques

<img src="images/dummy_thumbnail.jpg?raw=true"/>

### 4. Provide a basis for further data collection through surveys or experiments

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

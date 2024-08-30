# URL: https://jjiaxinnnn.github.io/html/

## Domain
The selected domain is Global YouTube Statistics, where data visualisation is used to represent the statistics of the most subscribed YouTube channels.

Dataset
URL: https://www.kaggle.com/datasets/nelgiriyewithana/global-youtube-statistics-2023 Author: Nidula Elgiriyewithana
This dataset from Kaggle contains statistics of the most subscribed YouTube channels in the world in 2023, including their subscriber counts, video views, upload frequency, country of origin, earnings, etc. (Elgiriyewithana, 2023).
I performed some data cleaning on the dataset such as removing rows with nan in the country, created_year, or channel_type column. Next, I removed the row with Andorra country as it does not have longitude and latitude values. Then, I deleted the rank column. Lastly, I grouped some channel types into a newly created group called ‘Others’.

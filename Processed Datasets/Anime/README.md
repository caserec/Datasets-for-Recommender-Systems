SUMMARY & USAGE LICENSE
=============================================

This dataset is provided by Keagle through the link: https://www.kaggle.com/CooperUnion/anime-recommendations-database

* Context
The original dataset contains information on user preference data from 73,516 users on 12,294 anime. Each user is able to add anime to their completed list and give it a rating and this data set is a compilation of those ratings. This dataset has been organized and reduced by Arthur Fortes [1], which generated new IDs for users and items, separated in files the information of history and ratings and randomly selected a subsample of 5,000 users. 

The reduced was made with Python [2] with random.seed(123).

* Acknowledgements
Thanks to myanimelist.net API for providing anime data and user ratings.


Detailed descriptions of the data file can be found at the end of this file.
 
This dataset consists of:
  * 520,610 interactions (play / purchase) from 5,000 users on 7,718 animes.
    - History: 5,000 users and 7,390 games (520,610 interactions)
    - Ratings: 4,714 users and 7,157 animes (419,944 interactions) 

If you have any further questions or comments, please contact me
<fortes.arthur@gmail.com>. 


DETAILED DESCRIPTIONS OF DATA FILES
==============================================

Here are brief descriptions of the data.

anime_ratings.dat    

                  The full ratings set: 419,944 interactions by 4,714 users on 7,157 animes.
                  Users and items are numbered consecutively from 1. The data is ordered by users ids. 
                  This is a tab separated list of 
                  User_ID | Anime_ID | Feedback 

                  Range of ratings: 1 - 10

anime_history.dat    

                  The full history set: 520,610 interactions by 5,000 users on 7,390 animes.
                  Users and items are numbered consecutively from 1. The data is ordered by users ids. 
                  This is a tab separated list of 
                  User_ID | Anime_ID | Feedback 

anime_info.dat 

                  Information about the items (animes); this is a tab separated list of
                  anime_ids | name | genre | type | episodes | rating | members

                  The item ids are the ones used in the game_purchase.dat 
                  and game_play.dat files.

                  anime_ids - myanimelist.net's unique id identifying an anime.
                  name - full name of anime.
                  genre - comma separated list of genres for this anime.
                  type - movie, TV, OVA, etc.
                  episodes - how many episodes in this show. (1 if movie).
                  rating - average rating out of 10 for this anime.
                  members - number of community members that are in this anime's "group".


REFERENCES
==============================================

[1] Da Costa, Arthur Fortes. PhD candidate at the Institute of Mathematical and Computational Sciences, 
University of São Paulo. URL: https://arthurfortes.github.io/

[2] https://www.python.org/
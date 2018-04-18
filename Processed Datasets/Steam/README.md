SUMMARY & USAGE LICENSE
=============================================

This dataset is provided by Keagle through the link: https://www.kaggle.com/tamber/steam-video-games/data.

* Context
Steam is the world's most popular PC Gaming hub, with over 6,000 games and a community of millions of gamers. With a massive collection that includes everything from AAA blockbusters to small indie titles, great discovery tools are a highly valuable asset for Steam. How can we make them better?

* Content
This dataset is a list of user behaviors, with columns: user-id, game-title, behavior-name, value. The behaviors included are 'purchase' and 'play'. The value indicates the degree to which the behavior was performed - in the case of 'purchase' the value is always 1, and in the case of 'play' the value represents the number of hours the user has played the game.

* Acknowledgements
This dataset is generated entirely from public Steam data, so we want to thank Steam for building such an awesome platform and community!


This data has been organized by Arthur Fortes [1], which generated new IDs for users and items and separated in files 
the information of purchase and play hours. 

Detailed descriptions of the data file can be found at the end of this file.
 
This dataset consists of:
  * 200,000 interactions (play / purchase) from 12,393 users on 5,155 games.
    - Play Hours: 11,350 users and 3,600 games (70,490 interactions)
    - Purchase: 12,393 users and 5,155 games (129,512 interactions) 

If you have any further questions or comments, please contact me
<fortes.arthur@gmail.com>. 


DETAILED DESCRIPTIONS OF DATA FILES
==============================================

Here are brief descriptions of the data.

items_info.dat    

                  Information about the items (games); this is a tab separated list of
                  Game_ID | Game Name |
                  The item ids are the ones used in the game_purchase.dat 
                  and game_play.dat files.


users_info.dat    

                  IDs information about the users; this is a tab separated list of
                  New_ID | Real_ID |

                  The user ids are the ones used in the game_purchase.dat 
                  and game_play.dat files.


game_purchase.dat 

                  The full purchase set: 129,512 interactions by 12,393 users on 5,155 games.
                  Users and items are numbered consecutively from 1. The data is ordered by users ids. 
                  This is a tab separated list of 
                  User_ID | Game_ID | Purchase 
                  

game_play.dat     

                  The full play hours set: 70,490 interactions by 11,350 users on 3,600 games.
                  Users and items are numbered consecutively from 1. The data is ordered by users ids. 
                  This is a tab separated list of 
                  User_ID | Game_ID | Hours 


REFERENCES
==============================================

[1] Da Costa, Arthur Fortes. PhD candidate at the Institute of Mathematical and Computational Sciences, 
University of São Paulo. URL: https://arthurfortes.github.io/
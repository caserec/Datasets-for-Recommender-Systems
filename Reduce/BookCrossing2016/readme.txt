
=======================
Book-Crossing2016
=======================

-------------------
Version and Author
-------------------

Version 1.0 (Set 2016)
Arthur Fortes da Costa 
University of São Paulo

-----------
Description
-----------

  Collected by Cai-Nicolas Ziegler in a 4-week crawl (August / September 2004) from the Book-Crossing community with kind permission from Ron Hornbaker, CTO of Humankind Systems. Contains 278,858 users (anonymized but with demographic information) providing 1,149,780 ratings (explicit / implicit) about 271,379 books.


    [ ! ] Freely available for research use when acknowledged with the following reference (further details on the dataset are given in this publication):

    Improving Recommendation Lists Through Topic Diversification,
    Cai-Nicolas Ziegler, Sean M. McNee, Joseph A. Konstan, Georg Lausen; Proceedings of the 14th International World Wide Web Conference (WWW '05), May 10-14, 2005, Chiba, Japan. To appear.


  If you have any further questions or comments, please contact Cai-Nicolas Ziegler
  <cziegler@informatik.uni-freiburg.de>. 


  The data set may be used for any research purposes under the following conditions:

    * The user must acknowledge the use of the data set in publications resulting from the use of the data set, and must
    send us an electronic or paper copy of those publications.

    * The user may not redistribute the data without separate permission.

  Changes
  ========
    - We removed all interactions without context information about the book

-----------------
ACKNOWLEDGEMENTS
-----------------

Thanks to Cai-Nicolas Ziegler by providing the database.

------------------------------------------
PUBLISHED WORK THAT HAS USED THIS DATASET
------------------------------------------

Please cite one or both of the following if you use the data in any way:

  Improving Recommendation Lists Through Topic Diversification,
  Cai-Nicolas Ziegler, Sean M. McNee, Joseph A. Konstan, Georg Lausen; Proceedings of the 14th International World Wide Web Conference (WWW '05), May 10-14, 2005, Chiba, Japan.

---------------
Data statistics
---------------

    92.107 users
    270.170 books

    Feedbacks

      - 383.852 ratings
      - 1.031.175 history

-----
Files
-----
    * user_history_book.dat
      These file contain the users' history based on their navigation on the system.

    * user_rated_books.dat
      These file contain the ratings of the books provided by each particular user.

    * books.dat
      This file contains information about the books of the database.
    
      The original book information avalible is:
         - ISBN
         - Title
         - Author
         - Year
         - Publisher
         - Image Url

    * movie_locations.dat

      This file contains locations and age of the users.

-----------
Data format
-----------

  The data is formatted one entry per line as follows (tab separated, "\t"):

  userID \t movieID \t rating

  Example:
        75  3 1

-------
Credits
-------

   This dataset was built by Arthur Fortes da Costa Phd student at University of São Paulo

-------   
Contact
-------

  Arthur Fortes da Costa, fortes [dot] arthur [at] gmail [dot] com
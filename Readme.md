
## Building a database for crime reports¶

In this project I build a database for storing data related with crimes that ocurred in Boston. This dataset is available in the file `boston.csv`.

The goal of this project is to build a database named crimes_db with a table boston_crimes with appropiate datatypes for storing the data from the boston.csv file. I created
the table inside a schema named crimes. Besides, I also created the readonly and readwrite groups with the appropiate privileges. Finally, I created one user for each group.

**Frameworks used**

Python 3 with psycopg library

Sadly, I could not complete the privileges assignment because I was using the online PostgreSQL platform ElephantSQL which does not give the proper permission to do these types of
operations.

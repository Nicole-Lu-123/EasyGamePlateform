# EasyGamePlateform
* This database is written by Java and SQL.

* This project aims to create a game launcher, which contains
  - A platform, which may run in MacOs or PC with its uniqueID, we use a ISA relationship to represent it. 
  - Users and games. They have the aggregation relation.
  - Game records, there is a weak entity to it. 
  - Games are classified to be a singleplayer game and multi-player game with unique game ID.
  - Hub.There are many hubs owned by game. In the hubs,
  - Game market. There is a game market in hubs that user can create transactions on it. 
 
The database records the information of each account and builds logical relationships
between entries. It means the data is sorted and stored in a proper way. For application, firstly,
it can use the database structure to build UI, like what information should be collected, what is
its type and if there should have a quick access button to imply the relationship between two
entries. Then, it benefits the data operations, the database provide proper positions for the
data to store in, informs works more like some individual parts not as a whole, so users can
show the inform they want others see like achievement and hide what they don't want to show
like personal information. Also, it can protect the data security, only the data of the specific account
and platform will be store in that device, information of other account won't be appeared,
and if some parts of database were hacked unfortunately, good news is other information
is ok, we just need to find and fix the hacked parts, if there is no such database, all data
stored together, then the loss will be credible large.

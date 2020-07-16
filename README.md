# Gymnast Web App
This app will allow the users to:
* Add a Gymnast
* Check the details of all Gymnasts
* Update a Gymnasts entry
* Delete a Gymnast from the database

## Technologies
Here is a list of technologies used :

| Required  | Used    |
|-----------|---------|
| Kanban Board |  Trello |
| Database |MYSQL|
| Programming |Python  |
| Front End | Flask/HTML |
| Version Control | Git |
| CI Server | Jenkins |
| Cloud Server | Google Cloud Platform (GCP) |

## CI Pipeline
Below is my CI Pipeline Diagram with the technologies explained above:

![CI Pipeline](https://github.com/paullagah/DevOps/blob/master/CI_Pipeline.jpg)


## Data
The design of the data will be as follows in the Entity Relationship Diagram:

![ERD](https://github.com/paullagah/DevOps/blob/master/Entity%20Relationship%20Diagram.jpg)

This ERD is the final draft that was completed after consideration about how to 
design the database in the first instance.

The initial design was as seen below:

![OLD ERD](https://github.com/paullagah/DevOps/blob/master/ERD.jpg)

Changes were made to the design as the project went on, 
for security purposes only Coaches/Gymnastic Staff should be able to make changes to the gymnast entries.

This required a stand-alone table to be set for the Coaches as the implemented "Users" table that you can see above.

